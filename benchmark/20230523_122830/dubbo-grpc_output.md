# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.769 ops/ms
# Warmup Iteration   2: 9.414 ops/ms
# Warmup Iteration   3: 10.149 ops/ms
Iteration   1: 10.610 ops/ms
Iteration   2: 10.575 ops/ms
Iteration   3: 10.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.603 ±(99.9%) 0.462 ops/ms [Average]
  (min, avg, max) = (10.575, 10.603, 10.624), stdev = 0.025
  CI (99.9%): [10.141, 11.065] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.538 ops/ms
# Warmup Iteration   2: 10.736 ops/ms
# Warmup Iteration   3: 11.196 ops/ms
Iteration   1: 10.943 ops/ms
Iteration   2: 11.301 ops/ms
Iteration   3: 11.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.146 ±(99.9%) 3.348 ops/ms [Average]
  (min, avg, max) = (10.943, 11.146, 11.301), stdev = 0.184
  CI (99.9%): [7.798, 14.494] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.133 ops/ms
# Warmup Iteration   2: 10.243 ops/ms
# Warmup Iteration   3: 10.464 ops/ms
Iteration   1: 10.502 ops/ms
Iteration   2: 10.785 ops/ms
Iteration   3: 10.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.643 ±(99.9%) 2.583 ops/ms [Average]
  (min, avg, max) = (10.502, 10.643, 10.785), stdev = 0.142
  CI (99.9%): [8.060, 13.226] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.074 ops/ms
# Warmup Iteration   2: 8.167 ops/ms
# Warmup Iteration   3: 8.296 ops/ms
Iteration   1: 8.256 ops/ms
Iteration   2: 8.318 ops/ms
Iteration   3: 8.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.290 ±(99.9%) 0.568 ops/ms [Average]
  (min, avg, max) = (8.256, 8.290, 8.318), stdev = 0.031
  CI (99.9%): [7.722, 8.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.427 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.005 ms/op
Iteration   1: 3.051 ±(99.9%) 0.005 ms/op
Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
Iteration   3: 3.015 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.025 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (3.010, 3.025, 3.051), stdev = 0.023
  CI (99.9%): [2.613, 3.437] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.827 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.003 ms/op
Iteration   1: 2.876 ±(99.9%) 0.003 ms/op
Iteration   2: 2.907 ±(99.9%) 0.003 ms/op
Iteration   3: 2.841 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.875 ±(99.9%) 0.608 ms/op [Average]
  (min, avg, max) = (2.841, 2.875, 2.907), stdev = 0.033
  CI (99.9%): [2.266, 3.483] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.816 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.002 ms/op
Iteration   1: 3.046 ±(99.9%) 0.002 ms/op
Iteration   2: 2.996 ±(99.9%) 0.004 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.011 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (2.992, 3.011, 3.046), stdev = 0.030
  CI (99.9%): [2.465, 3.558] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.304 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.029 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.028 ms/op
Iteration   1: 3.856 ±(99.9%) 0.041 ms/op
Iteration   2: 3.881 ±(99.9%) 0.038 ms/op
Iteration   3: 3.885 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.874 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (3.856, 3.874, 3.885), stdev = 0.016
  CI (99.9%): [3.584, 4.164] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.410 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.007 ms/op
Iteration   1: 3.107 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.410 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  8.240 ms/op
                 createUser·p0.9999: 16.205 ms/op
                 createUser·p1.00:   16.679 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.223 ms/op
                 createUser·p0.9999: 24.819 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.126 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  8.667 ms/op
                 createUser·p0.9999: 18.008 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310676
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19730 
    [ 2.500,  5.000) = 289353 
    [ 5.000,  7.500) = 1147 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.249 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     25.293 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.923 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.007 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  6.242 ms/op
                 existUser·p0.9999: 11.544 ms/op
                 existUser·p1.00:   11.731 ms/op

Iteration   2: 2.885 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  6.170 ms/op
                 existUser·p0.9999: 14.153 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   3: 2.875 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 15.770 ms/op
                 existUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329118
  mean =      2.915 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3386 
    [ 1.250,  2.500) = 38155 
    [ 2.500,  3.750) = 269431 
    [ 3.750,  5.000) = 16631 
    [ 5.000,  6.250) = 1087 
    [ 6.250,  7.500) = 197 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      6.553 ms/op
     p(99.9900) =     14.288 ms/op
     p(99.9990) =     16.140 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.817 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.032 ms/op
                 getUser·p0.9999: 13.794 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.730 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.260 ms/op
                 getUser·p0.9999: 25.622 ms/op
                 getUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315659
  mean =      3.040 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16665 
    [ 2.500,  5.000) = 297768 
    [ 5.000,  7.500) = 931 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.392 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     25.914 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.229 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.011 ms/op
Iteration   1: 3.908 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  12.157 ms/op
                 listUser·p0.9999: 16.240 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   2: 3.922 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.235 ms/op
                 listUser·p0.9999: 26.499 ms/op
                 listUser·p1.00:   28.049 ms/op

Iteration   3: 3.952 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.636 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  16.153 ms/op
                 listUser·p0.9999: 24.176 ms/op
                 listUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244556
  mean =      3.927 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5137 
    [ 2.500,  5.000) = 216053 
    [ 5.000,  7.500) = 22222 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     25.875 ms/op
     p(99.9990) =     27.845 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.603 ± 0.462  ops/ms
ClientGrpc.existUser                       thrpt       3  11.146 ± 3.348  ops/ms
ClientGrpc.getUser                         thrpt       3  10.643 ± 2.583  ops/ms
ClientGrpc.listUser                        thrpt       3   8.290 ± 0.568  ops/ms
ClientGrpc.createUser                       avgt       3   3.025 ± 0.412   ms/op
ClientGrpc.existUser                        avgt       3   2.875 ± 0.608   ms/op
ClientGrpc.getUser                          avgt       3   3.011 ± 0.546   ms/op
ClientGrpc.listUser                         avgt       3   3.874 ± 0.290   ms/op
ClientGrpc.createUser                     sample  310676   3.089 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.410           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.249           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.315           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.395           ms/op
ClientGrpc.existUser                      sample  329118   2.915 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.518           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.553           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.288           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.269           ms/op
ClientGrpc.getUser                        sample  315659   3.040 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.738           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.392           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.773           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.018           ms/op
ClientGrpc.listUser                       sample  244556   3.927 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.636           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.991           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.875           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.049           ms/op
