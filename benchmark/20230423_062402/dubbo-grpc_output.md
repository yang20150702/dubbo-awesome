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
# Warmup Iteration   1: 4.154 ops/ms
# Warmup Iteration   2: 9.132 ops/ms
# Warmup Iteration   3: 10.217 ops/ms
Iteration   1: 10.543 ops/ms
Iteration   2: 10.560 ops/ms
Iteration   3: 10.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.542 ±(99.9%) 0.343 ops/ms [Average]
  (min, avg, max) = (10.522, 10.542, 10.560), stdev = 0.019
  CI (99.9%): [10.198, 10.885] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.431 ops/ms
# Warmup Iteration   2: 10.459 ops/ms
# Warmup Iteration   3: 11.190 ops/ms
Iteration   1: 11.044 ops/ms
Iteration   2: 11.108 ops/ms
Iteration   3: 11.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.068 ±(99.9%) 0.646 ops/ms [Average]
  (min, avg, max) = (11.044, 11.068, 11.108), stdev = 0.035
  CI (99.9%): [10.421, 11.714] (assumes normal distribution)


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
# Warmup Iteration   1: 6.749 ops/ms
# Warmup Iteration   2: 10.228 ops/ms
# Warmup Iteration   3: 10.290 ops/ms
Iteration   1: 10.490 ops/ms
Iteration   2: 10.507 ops/ms
Iteration   3: 10.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.512 ±(99.9%) 0.473 ops/ms [Average]
  (min, avg, max) = (10.490, 10.512, 10.541), stdev = 0.026
  CI (99.9%): [10.040, 10.985] (assumes normal distribution)


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
# Warmup Iteration   1: 5.842 ops/ms
# Warmup Iteration   2: 7.752 ops/ms
# Warmup Iteration   3: 8.013 ops/ms
Iteration   1: 8.153 ops/ms
Iteration   2: 8.243 ops/ms
Iteration   3: 8.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.203 ±(99.9%) 0.829 ops/ms [Average]
  (min, avg, max) = (8.153, 8.203, 8.243), stdev = 0.045
  CI (99.9%): [7.374, 9.032] (assumes normal distribution)


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
# Warmup Iteration   1: 4.452 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.004 ms/op
Iteration   1: 2.935 ±(99.9%) 0.004 ms/op
Iteration   2: 3.042 ±(99.9%) 0.004 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.003 ±(99.9%) 1.071 ms/op [Average]
  (min, avg, max) = (2.935, 3.003, 3.042), stdev = 0.059
  CI (99.9%): [1.932, 4.074] (assumes normal distribution)


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
# Warmup Iteration   1: 3.906 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.003 ms/op
Iteration   1: 2.938 ±(99.9%) 0.003 ms/op
Iteration   2: 2.921 ±(99.9%) 0.002 ms/op
Iteration   3: 2.905 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.921 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (2.905, 2.921, 2.938), stdev = 0.017
  CI (99.9%): [2.619, 3.224] (assumes normal distribution)


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.003 ms/op
Iteration   1: 3.015 ±(99.9%) 0.003 ms/op
Iteration   2: 3.069 ±(99.9%) 0.002 ms/op
Iteration   3: 3.016 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.033 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (3.015, 3.033, 3.069), stdev = 0.031
  CI (99.9%): [2.467, 3.599] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.001 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.021 ms/op
Iteration   1: 3.911 ±(99.9%) 0.011 ms/op
Iteration   2: 3.950 ±(99.9%) 0.030 ms/op
Iteration   3: 3.933 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.932 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (3.911, 3.932, 3.950), stdev = 0.020
  CI (99.9%): [3.573, 4.290] (assumes normal distribution)


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.865 ms/op
                 createUser·p0.9999: 12.599 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.626 ms/op
                 createUser·p0.9999: 21.676 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  12.042 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316266
  mean =      3.034 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24961 
    [ 2.500,  5.000) = 289950 
    [ 5.000,  7.500) = 982 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     21.062 ms/op
     p(99.9990) =     22.048 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.005 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.582 ms/op
                 existUser·p0.9999: 15.032 ms/op
                 existUser·p1.00:   16.286 ms/op

Iteration   2: 2.923 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  6.842 ms/op
                 existUser·p0.9999: 25.921 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 2.940 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.396 ms/op
                 existUser·p0.9999: 23.794 ms/op
                 existUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325602
  mean =      2.946 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28537 
    [ 2.500,  5.000) = 296011 
    [ 5.000,  7.500) = 781 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.947 ms/op
     p(99.9900) =     25.073 ms/op
     p(99.9990) =     26.140 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 4.352 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.005 ms/op
Iteration   1: 3.037 ±(99.9%) 0.004 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.559 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.581 ms/op
                 getUser·p0.9999: 12.214 ms/op
                 getUser·p1.00:   12.354 ms/op

Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.389 ms/op
                 getUser·p0.9999: 12.523 ms/op
                 getUser·p1.00:   12.648 ms/op

Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.169 ms/op
                 getUser·p0.9999: 22.850 ms/op
                 getUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315080
  mean =      3.045 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13003 
    [ 2.500,  5.000) = 300903 
    [ 5.000,  7.500) = 930 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     23.092 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 5.612 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.010 ms/op
Iteration   1: 3.898 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  12.938 ms/op
                 listUser·p0.9999: 16.978 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   2: 3.864 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  14.888 ms/op
                 listUser·p0.9999: 22.549 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  15.250 ms/op
                 listUser·p0.9999: 18.329 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246367
  mean =      3.898 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4093 
    [ 2.500,  5.000) = 221805 
    [ 5.000,  7.500) = 19095 
    [ 7.500, 10.000) = 882 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     13.953 ms/op
     p(99.9900) =     21.835 ms/op
     p(99.9990) =     23.285 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.542 ± 0.343  ops/ms
ClientGrpc.existUser                       thrpt       3  11.068 ± 0.646  ops/ms
ClientGrpc.getUser                         thrpt       3  10.512 ± 0.473  ops/ms
ClientGrpc.listUser                        thrpt       3   8.203 ± 0.829  ops/ms
ClientGrpc.createUser                       avgt       3   3.003 ± 1.071   ms/op
ClientGrpc.existUser                        avgt       3   2.921 ± 0.302   ms/op
ClientGrpc.getUser                          avgt       3   3.033 ± 0.566   ms/op
ClientGrpc.listUser                         avgt       3   3.932 ± 0.358   ms/op
ClientGrpc.createUser                     sample  316266   3.034 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.742           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.667           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.062           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  325602   2.946 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.651           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.947           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.073           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.182           ms/op
ClientGrpc.getUser                        sample  315080   3.045 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.681           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.963           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.118           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.233           ms/op
ClientGrpc.listUser                       sample  246367   3.898 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.011           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.953           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.835           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.364           ms/op
