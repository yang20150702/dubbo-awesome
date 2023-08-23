# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ops/ms
# Warmup Iteration   2: 8.146 ops/ms
# Warmup Iteration   3: 9.585 ops/ms
Iteration   1: 9.718 ops/ms
Iteration   2: 10.353 ops/ms
Iteration   3: 9.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.976 ±(99.9%) 6.090 ops/ms [Average]
  (min, avg, max) = (9.718, 9.976, 10.353), stdev = 0.334
  CI (99.9%): [3.887, 16.066] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.563 ops/ms
# Warmup Iteration   2: 9.858 ops/ms
# Warmup Iteration   3: 10.503 ops/ms
Iteration   1: 10.716 ops/ms
Iteration   2: 10.530 ops/ms
Iteration   3: 10.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.615 ±(99.9%) 1.711 ops/ms [Average]
  (min, avg, max) = (10.530, 10.615, 10.716), stdev = 0.094
  CI (99.9%): [8.905, 12.326] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 5.543 ops/ms
# Warmup Iteration   2: 9.167 ops/ms
# Warmup Iteration   3: 9.783 ops/ms
Iteration   1: 9.876 ops/ms
Iteration   2: 9.721 ops/ms
Iteration   3: 9.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.851 ±(99.9%) 2.180 ops/ms [Average]
  (min, avg, max) = (9.721, 9.851, 9.956), stdev = 0.120
  CI (99.9%): [7.671, 12.031] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.111 ops/ms
# Warmup Iteration   2: 7.005 ops/ms
# Warmup Iteration   3: 7.485 ops/ms
Iteration   1: 7.580 ops/ms
Iteration   2: 7.580 ops/ms
Iteration   3: 7.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.603 ±(99.9%) 0.726 ops/ms [Average]
  (min, avg, max) = (7.580, 7.603, 7.649), stdev = 0.040
  CI (99.9%): [6.877, 8.329] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.886 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.005 ms/op
Iteration   1: 3.117 ±(99.9%) 0.002 ms/op
Iteration   2: 3.149 ±(99.9%) 0.002 ms/op
Iteration   3: 3.141 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.136 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (3.117, 3.136, 3.149), stdev = 0.016
  CI (99.9%): [2.839, 3.433] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.458 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.002 ms/op
Iteration   1: 3.002 ±(99.9%) 0.003 ms/op
Iteration   2: 2.990 ±(99.9%) 0.003 ms/op
Iteration   3: 3.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.018 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (2.990, 3.018, 3.063), stdev = 0.039
  CI (99.9%): [2.304, 3.733] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.728 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.003 ms/op
Iteration   1: 3.142 ±(99.9%) 0.004 ms/op
Iteration   2: 3.122 ±(99.9%) 0.003 ms/op
Iteration   3: 3.164 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.143 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (3.122, 3.143, 3.164), stdev = 0.021
  CI (99.9%): [2.752, 3.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.337 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.018 ms/op
Iteration   1: 4.154 ±(99.9%) 0.014 ms/op
Iteration   2: 4.121 ±(99.9%) 0.013 ms/op
Iteration   3: 4.045 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.106 ±(99.9%) 1.019 ms/op [Average]
  (min, avg, max) = (4.045, 4.106, 4.154), stdev = 0.056
  CI (99.9%): [3.087, 5.125] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.749 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.364 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.006 ms/op
Iteration   1: 3.120 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  9.814 ms/op
                 createUser·p0.9999: 12.657 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  10.950 ms/op
                 createUser·p0.9999: 16.400 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  12.943 ms/op
                 createUser·p0.9999: 16.638 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305332
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 794 
    [ 1.250,  2.500) = 14398 
    [ 2.500,  3.750) = 267851 
    [ 3.750,  5.000) = 20175 
    [ 5.000,  6.250) = 1081 
    [ 6.250,  7.500) = 278 
    [ 7.500,  8.750) = 238 
    [ 8.750, 10.000) = 136 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 52 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =     11.665 ms/op
     p(99.9900) =     16.368 ms/op
     p(99.9990) =     17.038 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.558 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
Iteration   1: 3.085 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  9.180 ms/op
                 existUser·p0.9999: 13.658 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  9.204 ms/op
                 existUser·p0.9999: 13.807 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  8.429 ms/op
                 existUser·p0.9999: 15.925 ms/op
                 existUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 310536
  mean =      3.091 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 870 
    [ 1.250,  2.500) = 11286 
    [ 2.500,  3.750) = 280047 
    [ 3.750,  5.000) = 16535 
    [ 5.000,  6.250) = 850 
    [ 6.250,  7.500) = 378 
    [ 7.500,  8.750) = 226 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     15.653 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.905 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.007 ms/op
Iteration   1: 3.245 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.749 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  9.732 ms/op
                 getUser·p0.9999: 14.050 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 3.289 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   5.017 ms/op
                 getUser·p0.999:  13.410 ms/op
                 getUser·p0.9999: 15.209 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   3: 3.276 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  10.355 ms/op
                 getUser·p0.9999: 18.030 ms/op
                 getUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 293553
  mean =      3.270 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 279 
    [ 1.250,  2.500) = 7913 
    [ 2.500,  3.750) = 246403 
    [ 3.750,  5.000) = 36316 
    [ 5.000,  6.250) = 1292 
    [ 6.250,  7.500) = 449 
    [ 7.500,  8.750) = 292 
    [ 8.750, 10.000) = 206 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 90 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =     10.682 ms/op
     p(99.9900) =     17.433 ms/op
     p(99.9990) =     18.221 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.643 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.671 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.286 ±(99.9%) 0.013 ms/op
Iteration   1: 4.288 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   8.110 ms/op
                 listUser·p0.999:  14.448 ms/op
                 listUser·p0.9999: 17.389 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   2: 4.288 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  16.787 ms/op
                 listUser·p0.9999: 28.165 ms/op
                 listUser·p1.00:   30.245 ms/op

Iteration   3: 4.301 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.350 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  16.184 ms/op
                 listUser·p0.9999: 27.253 ms/op
                 listUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 223619
  mean =      4.292 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1026 
    [ 2.500,  5.000) = 187725 
    [ 5.000,  7.500) = 31965 
    [ 7.500, 10.000) = 2202 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.308 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     27.391 ms/op
     p(99.9990) =     30.181 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.976 ± 6.090  ops/ms
ClientGrpc.existUser                       thrpt       3  10.615 ± 1.711  ops/ms
ClientGrpc.getUser                         thrpt       3   9.851 ± 2.180  ops/ms
ClientGrpc.listUser                        thrpt       3   7.603 ± 0.726  ops/ms
ClientGrpc.createUser                       avgt       3   3.136 ± 0.297   ms/op
ClientGrpc.existUser                        avgt       3   3.018 ± 0.714   ms/op
ClientGrpc.getUser                          avgt       3   3.143 ± 0.390   ms/op
ClientGrpc.listUser                         avgt       3   4.106 ± 1.019   ms/op
ClientGrpc.createUser                     sample  305332   3.142 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.868           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.665           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.368           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.924           ms/op
ClientGrpc.existUser                      sample  310536   3.091 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.771           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.060           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.077           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.653           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.991           ms/op
ClientGrpc.getUser                        sample  293553   3.270 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.749           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.211           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.104           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.682           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.433           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.562           ms/op
ClientGrpc.listUser                       sample  223619   4.292 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.969           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.080           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.308           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.811           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.391           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.245           ms/op
