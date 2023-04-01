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
# Warmup Iteration   1: 4.198 ops/ms
# Warmup Iteration   2: 9.151 ops/ms
# Warmup Iteration   3: 10.124 ops/ms
Iteration   1: 10.525 ops/ms
Iteration   2: 10.505 ops/ms
Iteration   3: 10.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.521 ±(99.9%) 0.272 ops/ms [Average]
  (min, avg, max) = (10.505, 10.521, 10.534), stdev = 0.015
  CI (99.9%): [10.249, 10.793] (assumes normal distribution)


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
# Warmup Iteration   1: 7.651 ops/ms
# Warmup Iteration   2: 10.798 ops/ms
# Warmup Iteration   3: 11.104 ops/ms
Iteration   1: 11.504 ops/ms
Iteration   2: 11.140 ops/ms
Iteration   3: 11.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.284 ±(99.9%) 3.530 ops/ms [Average]
  (min, avg, max) = (11.140, 11.284, 11.504), stdev = 0.193
  CI (99.9%): [7.754, 14.814] (assumes normal distribution)


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
# Warmup Iteration   1: 6.799 ops/ms
# Warmup Iteration   2: 10.173 ops/ms
# Warmup Iteration   3: 10.582 ops/ms
Iteration   1: 10.550 ops/ms
Iteration   2: 10.596 ops/ms
Iteration   3: 10.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.592 ±(99.9%) 0.727 ops/ms [Average]
  (min, avg, max) = (10.550, 10.592, 10.630), stdev = 0.040
  CI (99.9%): [9.864, 11.319] (assumes normal distribution)


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
# Warmup Iteration   1: 5.049 ops/ms
# Warmup Iteration   2: 7.714 ops/ms
# Warmup Iteration   3: 8.211 ops/ms
Iteration   1: 8.049 ops/ms
Iteration   2: 8.153 ops/ms
Iteration   3: 8.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.228 ±(99.9%) 4.124 ops/ms [Average]
  (min, avg, max) = (8.049, 8.228, 8.482), stdev = 0.226
  CI (99.9%): [4.104, 12.352] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.298 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.002 ms/op
Iteration   1: 2.992 ±(99.9%) 0.005 ms/op
Iteration   2: 3.085 ±(99.9%) 0.002 ms/op
Iteration   3: 3.056 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.044 ±(99.9%) 0.867 ms/op [Average]
  (min, avg, max) = (2.992, 3.044, 3.085), stdev = 0.048
  CI (99.9%): [2.177, 3.912] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.003 ms/op
Iteration   1: 3.223 ±(99.9%) 0.005 ms/op
Iteration   2: 2.905 ±(99.9%) 0.002 ms/op
Iteration   3: 2.899 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.009 ±(99.9%) 3.380 ms/op [Average]
  (min, avg, max) = (2.899, 3.009, 3.223), stdev = 0.185
  CI (99.9%): [≈ 0, 6.388] (assumes normal distribution)


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
# Warmup Iteration   1: 4.324 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.003 ms/op
Iteration   1: 3.005 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.001 ms/op
Iteration   3: 3.048 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.026 ±(99.9%) 0.392 ms/op [Average]
  (min, avg, max) = (3.005, 3.026, 3.048), stdev = 0.021
  CI (99.9%): [2.634, 3.418] (assumes normal distribution)


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
# Warmup Iteration   1: 5.800 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
Iteration   1: 3.945 ±(99.9%) 0.037 ms/op
Iteration   2: 3.920 ±(99.9%) 0.017 ms/op
Iteration   3: 3.943 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.936 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (3.920, 3.936, 3.945), stdev = 0.014
  CI (99.9%): [3.686, 4.186] (assumes normal distribution)


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
Iteration   1: 3.007 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.214 ms/op
                 createUser·p0.9999: 12.583 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  7.596 ms/op
                 createUser·p0.9999: 15.245 ms/op
                 createUser·p1.00:   15.876 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  8.941 ms/op
                 createUser·p0.9999: 27.937 ms/op
                 createUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315758
  mean =      3.038 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22584 
    [ 2.500,  5.000) = 291068 
    [ 5.000,  7.500) = 1747 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      7.870 ms/op
     p(99.9900) =     26.879 ms/op
     p(99.9990) =     28.274 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.005 ms/op
Iteration   1: 2.954 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.034 ms/op
                 existUser·p0.9999: 19.011 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   2: 2.957 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.996 ms/op
                 existUser·p0.9999: 15.129 ms/op
                 existUser·p1.00:   15.401 ms/op

Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  7.391 ms/op
                 existUser·p0.9999: 27.132 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324357
  mean =      2.958 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27426 
    [ 2.500,  5.000) = 295724 
    [ 5.000,  7.500) = 951 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      7.127 ms/op
     p(99.9900) =     22.999 ms/op
     p(99.9990) =     27.353 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 4.542 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.143 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   2: 3.063 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.151 ms/op
                 getUser·p0.9999: 14.460 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.574 ms/op
                 getUser·p0.9999: 16.499 ms/op
                 getUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315117
  mean =      3.047 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 892 
    [ 1.250,  2.500) = 20211 
    [ 2.500,  3.750) = 277076 
    [ 3.750,  5.000) = 15207 
    [ 5.000,  6.250) = 1124 
    [ 6.250,  7.500) = 318 
    [ 7.500,  8.750) = 90 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     18.602 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 5.708 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.011 ms/op
Iteration   1: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  13.718 ms/op
                 listUser·p0.9999: 16.516 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   2: 4.010 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.651 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 3.980 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 33.456 ms/op
                 listUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239839
  mean =      4.000 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3001 
    [ 2.500,  5.000) = 210693 
    [ 5.000,  7.500) = 24593 
    [ 7.500, 10.000) = 1091 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     32.834 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.521 ± 0.272  ops/ms
ClientGrpc.existUser                       thrpt       3  11.284 ± 3.530  ops/ms
ClientGrpc.getUser                         thrpt       3  10.592 ± 0.727  ops/ms
ClientGrpc.listUser                        thrpt       3   8.228 ± 4.124  ops/ms
ClientGrpc.createUser                       avgt       3   3.044 ± 0.867   ms/op
ClientGrpc.existUser                        avgt       3   3.009 ± 3.380   ms/op
ClientGrpc.getUser                          avgt       3   3.026 ± 0.392   ms/op
ClientGrpc.listUser                         avgt       3   3.936 ± 0.250   ms/op
ClientGrpc.createUser                     sample  315758   3.038 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.719           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.870           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.879           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.410           ms/op
ClientGrpc.existUser                      sample  324357   2.958 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.599           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.127           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.999           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.460           ms/op
ClientGrpc.getUser                        sample  315117   3.047 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.702           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.307           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.596           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.743           ms/op
ClientGrpc.listUser                       sample  239839   4.000 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.182           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.834           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.686           ms/op
