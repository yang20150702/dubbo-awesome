# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.329 ops/ms
# Warmup Iteration   2: 8.994 ops/ms
# Warmup Iteration   3: 9.897 ops/ms
Iteration   1: 10.511 ops/ms
Iteration   2: 9.846 ops/ms
Iteration   3: 10.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.153 ±(99.9%) 6.117 ops/ms [Average]
  (min, avg, max) = (9.846, 10.153, 10.511), stdev = 0.335
  CI (99.9%): [4.036, 16.270] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.647 ops/ms
# Warmup Iteration   2: 10.540 ops/ms
# Warmup Iteration   3: 10.635 ops/ms
Iteration   1: 10.954 ops/ms
Iteration   2: 10.394 ops/ms
Iteration   3: 10.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.470 ±(99.9%) 8.227 ops/ms [Average]
  (min, avg, max) = (10.062, 10.470, 10.954), stdev = 0.451
  CI (99.9%): [2.242, 18.697] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.327 ops/ms
# Warmup Iteration   2: 9.918 ops/ms
# Warmup Iteration   3: 10.295 ops/ms
Iteration   1: 10.490 ops/ms
Iteration   2: 10.155 ops/ms
Iteration   3: 9.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.171 ±(99.9%) 5.667 ops/ms [Average]
  (min, avg, max) = (9.869, 10.171, 10.490), stdev = 0.311
  CI (99.9%): [4.504, 15.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.593 ops/ms
# Warmup Iteration   2: 7.763 ops/ms
# Warmup Iteration   3: 7.938 ops/ms
Iteration   1: 7.861 ops/ms
Iteration   2: 7.809 ops/ms
Iteration   3: 7.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.780 ±(99.9%) 1.805 ops/ms [Average]
  (min, avg, max) = (7.670, 7.780, 7.861), stdev = 0.099
  CI (99.9%): [5.975, 9.585] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.106 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.003 ms/op
Iteration   1: 3.189 ±(99.9%) 0.002 ms/op
Iteration   2: 3.287 ±(99.9%) 0.002 ms/op
Iteration   3: 3.285 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.254 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.189, 3.254, 3.287), stdev = 0.056
  CI (99.9%): [2.229, 4.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.739 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
Iteration   1: 3.130 ±(99.9%) 0.002 ms/op
Iteration   2: 3.141 ±(99.9%) 0.002 ms/op
Iteration   3: 2.998 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.090 ±(99.9%) 1.449 ms/op [Average]
  (min, avg, max) = (2.998, 3.090, 3.141), stdev = 0.079
  CI (99.9%): [1.640, 4.539] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.003 ms/op
Iteration   1: 3.164 ±(99.9%) 0.003 ms/op
Iteration   2: 3.108 ±(99.9%) 0.003 ms/op
Iteration   3: 2.975 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.082 ±(99.9%) 1.766 ms/op [Average]
  (min, avg, max) = (2.975, 3.082, 3.164), stdev = 0.097
  CI (99.9%): [1.316, 4.848] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.177 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.253 ±(99.9%) 0.016 ms/op
Iteration   1: 4.201 ±(99.9%) 0.009 ms/op
Iteration   2: 4.263 ±(99.9%) 0.011 ms/op
Iteration   3: 4.110 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.192 ±(99.9%) 1.402 ms/op [Average]
  (min, avg, max) = (4.110, 4.192, 4.263), stdev = 0.077
  CI (99.9%): [2.790, 5.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.618 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.008 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  7.642 ms/op
                 createUser·p0.9999: 14.080 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.550 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  9.193 ms/op
                 createUser·p0.9999: 14.402 ms/op
                 createUser·p1.00:   16.744 ms/op

Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  11.038 ms/op
                 createUser·p0.9999: 17.434 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305035
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1733 
    [ 1.250,  2.500) = 20402 
    [ 2.500,  3.750) = 248957 
    [ 3.750,  5.000) = 30642 
    [ 5.000,  6.250) = 1952 
    [ 6.250,  7.500) = 728 
    [ 7.500,  8.750) = 318 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.104 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     16.793 ms/op
     p(99.9990) =     17.724 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.870 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
Iteration   1: 3.075 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.979 ms/op
                 existUser·p0.9999: 13.055 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   2: 2.967 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.743 ms/op
                 existUser·p0.999:  7.522 ms/op
                 existUser·p0.9999: 16.732 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   3: 2.913 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.308 ms/op
                 existUser·p0.9999: 16.106 ms/op
                 existUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321555
  mean =      2.984 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3234 
    [ 1.250,  2.500) = 40323 
    [ 2.500,  3.750) = 255926 
    [ 3.750,  5.000) = 20384 
    [ 5.000,  6.250) = 1121 
    [ 6.250,  7.500) = 297 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.147 ms/op
     p(99.9900) =     16.281 ms/op
     p(99.9990) =     17.811 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.097 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.134 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  8.328 ms/op
                 getUser·p0.9999: 21.809 ms/op
                 getUser·p1.00:   22.217 ms/op

Iteration   2: 3.148 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.177 ms/op
                 getUser·p0.999:  7.356 ms/op
                 getUser·p0.9999: 22.010 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   3: 3.121 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  7.788 ms/op
                 getUser·p0.9999: 27.427 ms/op
                 getUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306273
  mean =      3.134 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27396 
    [ 2.500,  5.000) = 275383 
    [ 5.000,  7.500) = 3088 
    [ 7.500, 10.000) = 268 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =      7.938 ms/op
     p(99.9900) =     25.423 ms/op
     p(99.9990) =     27.687 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.727 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.012 ms/op
Iteration   1: 4.071 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.561 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  14.729 ms/op
                 listUser·p0.9999: 19.315 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 4.055 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  15.190 ms/op
                 listUser·p0.9999: 26.808 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   3: 4.249 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  15.240 ms/op
                 listUser·p0.9999: 22.446 ms/op
                 listUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232686
  mean =      4.123 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3763 
    [ 2.500,  5.000) = 188865 
    [ 5.000,  7.500) = 37986 
    [ 7.500, 10.000) = 1535 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     15.034 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     27.023 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.153 ± 6.117  ops/ms
ClientGrpc.existUser                       thrpt       3  10.470 ± 8.227  ops/ms
ClientGrpc.getUser                         thrpt       3  10.171 ± 5.667  ops/ms
ClientGrpc.listUser                        thrpt       3   7.780 ± 1.805  ops/ms
ClientGrpc.createUser                       avgt       3   3.254 ± 1.025   ms/op
ClientGrpc.existUser                        avgt       3   3.090 ± 1.449   ms/op
ClientGrpc.getUser                          avgt       3   3.082 ± 1.766   ms/op
ClientGrpc.listUser                         avgt       3   4.192 ± 1.402   ms/op
ClientGrpc.createUser                     sample  305035   3.149 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.550           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.039           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.104           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.733           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.793           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.924           ms/op
ClientGrpc.existUser                      sample  321555   2.984 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.615           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.147           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.281           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.088           ms/op
ClientGrpc.getUser                        sample  306273   3.134 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.580           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.067           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.136           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.938           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.423           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.787           ms/op
ClientGrpc.listUser                       sample  232686   4.123 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.561           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.034           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.872           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.901           ms/op
