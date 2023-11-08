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
# Warmup Iteration   1: 4.657 ops/ms
# Warmup Iteration   2: 11.819 ops/ms
# Warmup Iteration   3: 12.250 ops/ms
Iteration   1: 12.392 ops/ms
Iteration   2: 12.541 ops/ms
Iteration   3: 12.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.533 ±(99.9%) 2.508 ops/ms [Average]
  (min, avg, max) = (12.392, 12.533, 12.667), stdev = 0.137
  CI (99.9%): [10.025, 15.041] (assumes normal distribution)


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
# Warmup Iteration   1: 8.394 ops/ms
# Warmup Iteration   2: 12.999 ops/ms
# Warmup Iteration   3: 13.216 ops/ms
Iteration   1: 13.221 ops/ms
Iteration   2: 13.137 ops/ms
Iteration   3: 13.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.163 ±(99.9%) 0.914 ops/ms [Average]
  (min, avg, max) = (13.132, 13.163, 13.221), stdev = 0.050
  CI (99.9%): [12.250, 14.077] (assumes normal distribution)


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
# Warmup Iteration   1: 7.577 ops/ms
# Warmup Iteration   2: 12.411 ops/ms
# Warmup Iteration   3: 12.544 ops/ms
Iteration   1: 12.814 ops/ms
Iteration   2: 12.748 ops/ms
Iteration   3: 12.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.737 ±(99.9%) 1.523 ops/ms [Average]
  (min, avg, max) = (12.648, 12.737, 12.814), stdev = 0.083
  CI (99.9%): [11.214, 14.260] (assumes normal distribution)


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
# Warmup Iteration   1: 6.841 ops/ms
# Warmup Iteration   2: 10.253 ops/ms
# Warmup Iteration   3: 10.604 ops/ms
Iteration   1: 10.687 ops/ms
Iteration   2: 10.652 ops/ms
Iteration   3: 10.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.693 ±(99.9%) 0.818 ops/ms [Average]
  (min, avg, max) = (10.652, 10.693, 10.741), stdev = 0.045
  CI (99.9%): [9.875, 11.512] (assumes normal distribution)


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.003 ms/op
Iteration   1: 2.513 ±(99.9%) 0.004 ms/op
Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.538 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (2.513, 2.538, 2.571), stdev = 0.030
  CI (99.9%): [1.996, 3.080] (assumes normal distribution)


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
# Warmup Iteration   1: 3.692 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.104 ms/op [Average]
  (min, avg, max) = (2.468, 2.472, 2.479), stdev = 0.006
  CI (99.9%): [2.369, 2.576] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.507 ±(99.9%) 0.003 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.476, 2.487, 2.507), stdev = 0.018
  CI (99.9%): [2.168, 2.806] (assumes normal distribution)


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
# Warmup Iteration   1: 4.585 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.005 ms/op
Iteration   1: 2.973 ±(99.9%) 0.004 ms/op
Iteration   2: 2.984 ±(99.9%) 0.005 ms/op
Iteration   3: 2.988 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.982 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (2.973, 2.982, 2.988), stdev = 0.007
  CI (99.9%): [2.846, 3.117] (assumes normal distribution)


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
# Warmup Iteration   1: 4.346 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.977 ms/op
                 createUser·p0.999:  11.100 ms/op
                 createUser·p0.9999: 13.713 ms/op
                 createUser·p1.00:   14.483 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.514 ms/op
                 createUser·p0.999:  9.984 ms/op
                 createUser·p0.9999: 12.578 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  8.253 ms/op
                 createUser·p0.9999: 10.475 ms/op
                 createUser·p1.00:   10.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378713
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 179550 
    [ 2.500,  3.750) = 194218 
    [ 3.750,  5.000) = 3913 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      8.298 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     13.982 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  6.471 ms/op
                 existUser·p0.9999: 13.664 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  7.108 ms/op
                 existUser·p0.9999: 12.553 ms/op
                 existUser·p1.00:   12.796 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  8.402 ms/op
                 existUser·p0.9999: 12.779 ms/op
                 existUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390798
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 195301 
    [ 2.500,  3.750) = 191673 
    [ 3.750,  5.000) = 2866 
    [ 5.000,  6.250) = 424 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      7.768 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     13.780 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  12.168 ms/op
                 getUser·p0.9999: 14.652 ms/op
                 getUser·p1.00:   16.286 ms/op

Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.051 ms/op
                 getUser·p0.999:  10.093 ms/op
                 getUser·p0.9999: 14.045 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  8.823 ms/op
                 getUser·p0.9999: 13.233 ms/op
                 getUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380077
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 186668 
    [ 2.500,  3.750) = 187890 
    [ 3.750,  5.000) = 4123 
    [ 5.000,  6.250) = 891 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 84 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      4.039 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     14.254 ms/op
     p(99.9990) =     16.155 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.009 ms/op
Iteration   1: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.305 ms/op
                 listUser·p0.9999: 11.092 ms/op
                 listUser·p1.00:   12.222 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.534 ms/op
                 listUser·p0.9999: 12.841 ms/op
                 listUser·p1.00:   13.468 ms/op

Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.315 ms/op
                 listUser·p0.9999: 11.141 ms/op
                 listUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318892
  mean =      3.008 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 92929 
    [ 2.500,  3.750) = 186753 
    [ 3.750,  5.000) = 31634 
    [ 5.000,  6.250) = 6170 
    [ 6.250,  7.500) = 676 
    [ 7.500,  8.750) = 173 
    [ 8.750, 10.000) = 246 
    [10.000, 11.250) = 162 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.357 ms/op
     p(99.9900) =     11.818 ms/op
     p(99.9990) =     13.174 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.533 ± 2.508  ops/ms
ClientPb.existUser                       thrpt       3  13.163 ± 0.914  ops/ms
ClientPb.getUser                         thrpt       3  12.737 ± 1.523  ops/ms
ClientPb.listUser                        thrpt       3  10.693 ± 0.818  ops/ms
ClientPb.createUser                       avgt       3   2.538 ± 0.542   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.104   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.319   ms/op
ClientPb.listUser                         avgt       3   2.982 ± 0.136   ms/op
ClientPb.createUser                     sample  378713   2.533 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.555           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.298           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.468           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.483           ms/op
ClientPb.existUser                      sample  390798   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.913           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.768           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.255           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.992           ms/op
ClientPb.getUser                        sample  380077   2.524 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.913           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.864           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.254           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.286           ms/op
ClientPb.listUser                       sample  318892   3.008 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.889           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.357           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.818           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.468           ms/op
