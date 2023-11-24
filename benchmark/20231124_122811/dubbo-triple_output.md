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
# Warmup Iteration   1: 4.570 ops/ms
# Warmup Iteration   2: 11.818 ops/ms
# Warmup Iteration   3: 12.254 ops/ms
Iteration   1: 12.402 ops/ms
Iteration   2: 12.532 ops/ms
Iteration   3: 12.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.545 ±(99.9%) 2.733 ops/ms [Average]
  (min, avg, max) = (12.402, 12.545, 12.701), stdev = 0.150
  CI (99.9%): [9.812, 15.278] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.333 ops/ms
# Warmup Iteration   2: 13.049 ops/ms
# Warmup Iteration   3: 13.060 ops/ms
Iteration   1: 13.309 ops/ms
Iteration   2: 13.207 ops/ms
Iteration   3: 13.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.282 ±(99.9%) 1.205 ops/ms [Average]
  (min, avg, max) = (13.207, 13.282, 13.330), stdev = 0.066
  CI (99.9%): [12.077, 14.487] (assumes normal distribution)


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
# Warmup Iteration   1: 7.558 ops/ms
# Warmup Iteration   2: 12.539 ops/ms
# Warmup Iteration   3: 12.778 ops/ms
Iteration   1: 12.777 ops/ms
Iteration   2: 12.960 ops/ms
Iteration   3: 12.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.869 ±(99.9%) 1.671 ops/ms [Average]
  (min, avg, max) = (12.777, 12.869, 12.960), stdev = 0.092
  CI (99.9%): [11.198, 14.540] (assumes normal distribution)


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
# Warmup Iteration   1: 6.812 ops/ms
# Warmup Iteration   2: 10.396 ops/ms
# Warmup Iteration   3: 10.597 ops/ms
Iteration   1: 10.653 ops/ms
Iteration   2: 10.684 ops/ms
Iteration   3: 10.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.688 ±(99.9%) 0.683 ops/ms [Average]
  (min, avg, max) = (10.653, 10.688, 10.727), stdev = 0.037
  CI (99.9%): [10.005, 11.370] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.122 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (2.483, 2.512, 2.543), stdev = 0.030
  CI (99.9%): [1.963, 3.061] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.626 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.505 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (2.482, 2.505, 2.527), stdev = 0.022
  CI (99.9%): [2.097, 2.913] (assumes normal distribution)


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.539 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.515 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.498, 2.515, 2.539), stdev = 0.021
  CI (99.9%): [2.127, 2.904] (assumes normal distribution)


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.005 ms/op
Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
Iteration   3: 3.009 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.001 ±(99.9%) 0.122 ms/op [Average]
  (min, avg, max) = (2.996, 3.001, 3.009), stdev = 0.007
  CI (99.9%): [2.880, 3.123] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   4.039 ms/op
                 createUser·p0.999:  10.552 ms/op
                 createUser·p0.9999: 13.460 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  10.060 ms/op
                 createUser·p0.9999: 12.390 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  8.315 ms/op
                 createUser·p0.9999: 15.204 ms/op
                 createUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382358
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 183788 
    [ 2.500,  3.750) = 193891 
    [ 3.750,  5.000) = 3454 
    [ 5.000,  6.250) = 671 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     13.837 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


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
# Warmup Iteration   1: 3.656 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  9.443 ms/op
                 existUser·p0.9999: 13.531 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  5.734 ms/op
                 existUser·p0.9999: 13.270 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  8.201 ms/op
                 existUser·p0.9999: 11.731 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392715
  mean =      2.442 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 193282 
    [ 2.500,  3.750) = 196171 
    [ 3.750,  5.000) = 2394 
    [ 5.000,  6.250) = 354 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =      7.627 ms/op
     p(99.9900) =     13.267 ms/op
     p(99.9990) =     13.894 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  11.894 ms/op
                 getUser·p0.9999: 14.533 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.824 ms/op
                 getUser·p0.999:  10.146 ms/op
                 getUser·p0.9999: 13.376 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.949 ms/op
                 getUser·p0.9999: 10.535 ms/op
                 getUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376864
  mean =      2.545 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 183426 
    [ 2.500,  3.750) = 187301 
    [ 3.750,  5.000) = 4591 
    [ 5.000,  6.250) = 1034 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      8.185 ms/op
     p(99.9900) =     13.768 ms/op
     p(99.9990) =     14.684 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 4.761 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.009 ms/op
Iteration   1: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.073 ms/op
                 listUser·p0.9999: 12.177 ms/op
                 listUser·p1.00:   12.714 ms/op

Iteration   2: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.334 ms/op
                 listUser·p0.9999: 11.561 ms/op
                 listUser·p1.00:   13.320 ms/op

Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.637 ms/op
                 listUser·p0.9999: 11.354 ms/op
                 listUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317959
  mean =      3.017 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 92516 
    [ 2.500,  3.750) = 185553 
    [ 3.750,  5.000) = 32284 
    [ 5.000,  6.250) = 6050 
    [ 6.250,  7.500) = 765 
    [ 7.500,  8.750) = 221 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 151 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     11.370 ms/op
     p(99.9990) =     13.198 ms/op
     p(99.9999) =     13.320 ms/op
    p(100.0000) =     13.320 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.545 ± 2.733  ops/ms
ClientPb.existUser                       thrpt       3  13.282 ± 1.205  ops/ms
ClientPb.getUser                         thrpt       3  12.869 ± 1.671  ops/ms
ClientPb.listUser                        thrpt       3  10.688 ± 0.683  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.549   ms/op
ClientPb.existUser                        avgt       3   2.505 ± 0.408   ms/op
ClientPb.getUser                          avgt       3   2.515 ± 0.389   ms/op
ClientPb.listUser                         avgt       3   3.001 ± 0.122   ms/op
ClientPb.createUser                     sample  382358   2.509 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.866           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.273           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.837           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.122           ms/op
ClientPb.existUser                      sample  392715   2.442 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.933           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.627           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.267           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.976           ms/op
ClientPb.getUser                        sample  376864   2.545 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.705           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.185           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.768           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.811           ms/op
ClientPb.listUser                       sample  317959   3.017 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.814           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.370           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.320           ms/op
