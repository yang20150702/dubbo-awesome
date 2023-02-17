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
# Warmup Iteration   1: 2.477 ops/ms
# Warmup Iteration   2: 6.163 ops/ms
# Warmup Iteration   3: 7.668 ops/ms
Iteration   1: 7.637 ops/ms
Iteration   2: 7.842 ops/ms
Iteration   3: 7.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.742 ±(99.9%) 1.875 ops/ms [Average]
  (min, avg, max) = (7.637, 7.742, 7.842), stdev = 0.103
  CI (99.9%): [5.867, 9.617] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.332 ops/ms
# Warmup Iteration   2: 7.946 ops/ms
# Warmup Iteration   3: 8.217 ops/ms
Iteration   1: 8.188 ops/ms
Iteration   2: 8.142 ops/ms
Iteration   3: 8.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.202 ±(99.9%) 1.234 ops/ms [Average]
  (min, avg, max) = (8.142, 8.202, 8.275), stdev = 0.068
  CI (99.9%): [6.968, 9.436] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.007 ops/ms
# Warmup Iteration   2: 7.097 ops/ms
# Warmup Iteration   3: 7.388 ops/ms
Iteration   1: 7.687 ops/ms
Iteration   2: 7.519 ops/ms
Iteration   3: 7.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.504 ±(99.9%) 3.476 ops/ms [Average]
  (min, avg, max) = (7.306, 7.504, 7.687), stdev = 0.191
  CI (99.9%): [4.028, 10.980] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.720 ops/ms
# Warmup Iteration   2: 5.625 ops/ms
# Warmup Iteration   3: 5.949 ops/ms
Iteration   1: 6.254 ops/ms
Iteration   2: 6.138 ops/ms
Iteration   3: 6.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.172 ±(99.9%) 1.304 ops/ms [Average]
  (min, avg, max) = (6.124, 6.172, 6.254), stdev = 0.071
  CI (99.9%): [4.868, 7.476] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.833 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.008 ms/op
Iteration   1: 4.011 ±(99.9%) 0.004 ms/op
Iteration   2: 3.957 ±(99.9%) 0.003 ms/op
Iteration   3: 3.981 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.983 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (3.957, 3.983, 4.011), stdev = 0.027
  CI (99.9%): [3.489, 4.478] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.784 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.004 ms/op
Iteration   1: 3.886 ±(99.9%) 0.003 ms/op
Iteration   2: 3.772 ±(99.9%) 0.003 ms/op
Iteration   3: 3.748 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.802 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (3.748, 3.802, 3.886), stdev = 0.074
  CI (99.9%): [2.459, 5.144] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.112 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.370 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.012 ms/op
Iteration   1: 4.123 ±(99.9%) 0.004 ms/op
Iteration   2: 4.142 ±(99.9%) 0.002 ms/op
Iteration   3: 4.153 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.140 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (4.123, 4.140, 4.153), stdev = 0.015
  CI (99.9%): [3.862, 4.417] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.625 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.856 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.370 ±(99.9%) 0.010 ms/op
Iteration   1: 5.248 ±(99.9%) 0.008 ms/op
Iteration   2: 5.172 ±(99.9%) 0.034 ms/op
Iteration   3: 5.222 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.214 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (5.172, 5.214, 5.248), stdev = 0.038
  CI (99.9%): [4.515, 5.913] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.104 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.491 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.192 ±(99.9%) 0.012 ms/op
Iteration   1: 4.115 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   4.006 ms/op
                 createUser·p0.90:   5.202 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  11.008 ms/op
                 createUser·p0.9999: 15.677 ms/op
                 createUser·p1.00:   16.269 ms/op

Iteration   2: 4.110 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   4.039 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  13.300 ms/op
                 createUser·p0.9999: 28.286 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   3: 4.139 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   4.047 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  12.699 ms/op
                 createUser·p0.9999: 19.801 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 232962
  mean =      4.121 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5943 
    [ 2.500,  5.000) = 191634 
    [ 5.000,  7.500) = 33504 
    [ 7.500, 10.000) = 1419 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     12.732 ms/op
     p(99.9900) =     27.112 ms/op
     p(99.9990) =     28.639 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.203 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.012 ms/op
Iteration   1: 3.965 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   5.046 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   7.172 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 23.722 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 4.036 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   3.977 ms/op
                 existUser·p0.90:   5.210 ms/op
                 existUser·p0.95:   5.530 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 21.103 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   3: 3.946 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.413 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  14.170 ms/op
                 existUser·p0.9999: 34.465 ms/op
                 existUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 240876
  mean =      3.982 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9365 
    [ 2.500,  5.000) = 202824 
    [ 5.000,  7.500) = 26811 
    [ 7.500, 10.000) = 1343 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     11.928 ms/op
     p(99.9900) =     33.188 ms/op
     p(99.9990) =     35.035 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.133 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.397 ±(99.9%) 0.014 ms/op
Iteration   1: 4.257 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   4.178 ms/op
                 getUser·p0.90:   5.374 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   6.947 ms/op
                 getUser·p0.999:  9.468 ms/op
                 getUser·p0.9999: 17.661 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   2: 4.163 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.710 ms/op
                 getUser·p0.99:   7.668 ms/op
                 getUser·p0.999:  12.173 ms/op
                 getUser·p0.9999: 20.599 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   3: 4.242 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   4.112 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   5.800 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  11.338 ms/op
                 getUser·p0.9999: 20.185 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227312
  mean =      4.220 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3743 
    [ 2.500,  5.000) = 184081 
    [ 5.000,  7.500) = 37419 
    [ 7.500, 10.000) = 1654 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     11.005 ms/op
     p(99.9900) =     20.096 ms/op
     p(99.9990) =     21.100 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 6.643 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.194 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.241 ±(99.9%) 0.019 ms/op
Iteration   1: 5.169 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   6.619 ms/op
                 listUser·p0.95:   7.427 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  16.127 ms/op
                 listUser·p0.9999: 21.053 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   2: 5.096 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   6.504 ms/op
                 listUser·p0.95:   7.315 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  17.505 ms/op
                 listUser·p0.9999: 21.024 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   3: 5.280 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   7.037 ms/op
                 listUser·p0.95:   7.905 ms/op
                 listUser·p0.99:   10.044 ms/op
                 listUser·p0.999:  18.606 ms/op
                 listUser·p0.9999: 23.165 ms/op
                 listUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 185286
  mean =      5.180 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 245 
    [ 2.500,  5.000) = 98463 
    [ 5.000,  7.500) = 76771 
    [ 7.500, 10.000) = 7974 
    [10.000, 12.500) = 1294 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.726 ms/op
     p(95.0000) =      7.567 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     17.685 ms/op
     p(99.9900) =     22.377 ms/op
     p(99.9990) =     23.598 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.742 ± 1.875  ops/ms
ClientGrpc.existUser                       thrpt       3   8.202 ± 1.234  ops/ms
ClientGrpc.getUser                         thrpt       3   7.504 ± 3.476  ops/ms
ClientGrpc.listUser                        thrpt       3   6.172 ± 1.304  ops/ms
ClientGrpc.createUser                       avgt       3   3.983 ± 0.495   ms/op
ClientGrpc.existUser                        avgt       3   3.802 ± 1.342   ms/op
ClientGrpc.getUser                          avgt       3   4.140 ± 0.277   ms/op
ClientGrpc.listUser                         avgt       3   5.214 ± 0.699   ms/op
ClientGrpc.createUser                     sample  232962   4.121 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.968           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.030           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.251           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.184           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.732           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.112           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.065           ms/op
ClientGrpc.existUser                      sample  240876   3.982 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.979           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.104           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.472           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.947           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.928           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.188           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.193           ms/op
ClientGrpc.getUser                        sample  227312   4.220 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.916           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.108           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.349           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.751           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.307           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.005           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.096           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.201           ms/op
ClientGrpc.listUser                       sample  185286   5.180 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.206           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.567           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.978           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.685           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.377           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.626           ms/op
