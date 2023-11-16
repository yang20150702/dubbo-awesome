# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.395 ops/ms
# Warmup Iteration   2: 12.068 ops/ms
# Warmup Iteration   3: 12.375 ops/ms
Iteration   1: 12.660 ops/ms
Iteration   2: 12.651 ops/ms
Iteration   3: 12.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.662 ±(99.9%) 0.203 ops/ms [Average]
  (min, avg, max) = (12.651, 12.662, 12.674), stdev = 0.011
  CI (99.9%): [12.459, 12.865] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.659 ops/ms
# Warmup Iteration   2: 12.857 ops/ms
# Warmup Iteration   3: 12.912 ops/ms
Iteration   1: 13.060 ops/ms
Iteration   2: 13.044 ops/ms
Iteration   3: 13.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.052 ±(99.9%) 0.140 ops/ms [Average]
  (min, avg, max) = (13.044, 13.052, 13.060), stdev = 0.008
  CI (99.9%): [12.913, 13.192] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.070 ops/ms
# Warmup Iteration   2: 12.609 ops/ms
# Warmup Iteration   3: 12.765 ops/ms
Iteration   1: 12.879 ops/ms
Iteration   2: 12.863 ops/ms
Iteration   3: 12.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.785 ±(99.9%) 2.713 ops/ms [Average]
  (min, avg, max) = (12.614, 12.785, 12.879), stdev = 0.149
  CI (99.9%): [10.072, 15.498] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.579 ops/ms
# Warmup Iteration   2: 10.519 ops/ms
# Warmup Iteration   3: 10.432 ops/ms
Iteration   1: 10.592 ops/ms
Iteration   2: 10.462 ops/ms
Iteration   3: 10.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.547 ±(99.9%) 1.351 ops/ms [Average]
  (min, avg, max) = (10.462, 10.547, 10.592), stdev = 0.074
  CI (99.9%): [9.196, 11.898] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.185 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.580 ±(99.9%) 0.004 ms/op
Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (2.522, 2.549, 2.580), stdev = 0.029
  CI (99.9%): [2.022, 3.076] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.152 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.449 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.456 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.447, 2.456, 2.464), stdev = 0.009
  CI (99.9%): [2.296, 2.615] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.168 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.544 ±(99.9%) 0.004 ms/op
Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (2.507, 2.521, 2.544), stdev = 0.021
  CI (99.9%): [2.146, 2.896] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.943 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.005 ms/op
Iteration   1: 3.038 ±(99.9%) 0.005 ms/op
Iteration   2: 3.038 ±(99.9%) 0.005 ms/op
Iteration   3: 3.057 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (3.038, 3.044, 3.057), stdev = 0.011
  CI (99.9%): [2.839, 3.249] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.411 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.973 ms/op
                 createUser·p0.999:  11.813 ms/op
                 createUser·p0.9999: 13.959 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  9.268 ms/op
                 createUser·p0.9999: 12.976 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  9.716 ms/op
                 createUser·p0.9999: 14.617 ms/op
                 createUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377492
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 179017 
    [ 2.500,  3.750) = 194015 
    [ 3.750,  5.000) = 3438 
    [ 5.000,  6.250) = 424 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      9.757 ms/op
     p(99.9900) =     13.947 ms/op
     p(99.9990) =     15.470 ms/op
     p(99.9999) =     16.105 ms/op
    p(100.0000) =     16.105 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.026 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.476 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  6.561 ms/op
                 existUser·p0.9999: 17.194 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  6.704 ms/op
                 existUser·p0.9999: 16.122 ms/op
                 existUser·p1.00:   16.286 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  8.817 ms/op
                 existUser·p0.9999: 12.206 ms/op
                 existUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387919
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 190857 
    [ 2.500,  3.750) = 192474 
    [ 3.750,  5.000) = 3295 
    [ 5.000,  6.250) = 773 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     16.122 ms/op
     p(99.9990) =     18.636 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  6.915 ms/op
                 getUser·p0.9999: 14.090 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  9.845 ms/op
                 getUser·p0.9999: 16.112 ms/op
                 getUser·p1.00:   16.531 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  8.791 ms/op
                 getUser·p0.9999: 11.367 ms/op
                 getUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382693
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 187427 
    [ 2.500,  3.750) = 189447 
    [ 3.750,  5.000) = 4514 
    [ 5.000,  6.250) = 763 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =      8.813 ms/op
     p(99.9900) =     14.090 ms/op
     p(99.9990) =     16.450 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.069 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.009 ms/op
Iteration   1: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.772 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.626 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   2: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.925 ms/op
                 listUser·p0.9999: 11.524 ms/op
                 listUser·p1.00:   12.583 ms/op

Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 11.141 ms/op
                 listUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316810
  mean =      3.027 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 90418 
    [ 2.500,  3.750) = 186431 
    [ 3.750,  5.000) = 32225 
    [ 5.000,  6.250) = 6203 
    [ 6.250,  7.500) = 733 
    [ 7.500,  8.750) = 254 
    [ 8.750, 10.000) = 251 
    [10.000, 11.250) = 170 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     11.217 ms/op
     p(99.9990) =     12.184 ms/op
     p(99.9999) =     12.583 ms/op
    p(100.0000) =     12.583 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.662 ± 0.203  ops/ms
ClientPb.existUser                       thrpt       3  13.052 ± 0.140  ops/ms
ClientPb.getUser                         thrpt       3  12.785 ± 2.713  ops/ms
ClientPb.listUser                        thrpt       3  10.547 ± 1.351  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.527   ms/op
ClientPb.existUser                        avgt       3   2.456 ± 0.160   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.375   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.205   ms/op
ClientPb.createUser                     sample  377492   2.541 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.680           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.757           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.947           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.105           ms/op
ClientPb.existUser                      sample  387919   2.472 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.804           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.152           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.122           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.268           ms/op
ClientPb.getUser                        sample  382693   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.801           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.813           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.090           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.531           ms/op
ClientPb.listUser                       sample  316810   3.027 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.772           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.217           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.583           ms/op
