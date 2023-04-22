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
# Warmup Iteration   1: 4.440 ops/ms
# Warmup Iteration   2: 9.052 ops/ms
# Warmup Iteration   3: 9.750 ops/ms
Iteration   1: 10.380 ops/ms
Iteration   2: 10.397 ops/ms
Iteration   3: 10.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.414 ±(99.9%) 0.830 ops/ms [Average]
  (min, avg, max) = (10.380, 10.414, 10.466), stdev = 0.046
  CI (99.9%): [9.584, 11.244] (assumes normal distribution)


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
# Warmup Iteration   1: 7.087 ops/ms
# Warmup Iteration   2: 9.928 ops/ms
# Warmup Iteration   3: 10.696 ops/ms
Iteration   1: 10.875 ops/ms
Iteration   2: 10.583 ops/ms
Iteration   3: 10.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.581 ±(99.9%) 5.370 ops/ms [Average]
  (min, avg, max) = (10.286, 10.581, 10.875), stdev = 0.294
  CI (99.9%): [5.212, 15.951] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.649 ops/ms
# Warmup Iteration   2: 10.006 ops/ms
# Warmup Iteration   3: 10.333 ops/ms
Iteration   1: 10.414 ops/ms
Iteration   2: 10.558 ops/ms
Iteration   3: 10.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.536 ±(99.9%) 2.060 ops/ms [Average]
  (min, avg, max) = (10.414, 10.536, 10.637), stdev = 0.113
  CI (99.9%): [8.476, 12.597] (assumes normal distribution)


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
# Warmup Iteration   1: 5.572 ops/ms
# Warmup Iteration   2: 7.730 ops/ms
# Warmup Iteration   3: 8.088 ops/ms
Iteration   1: 8.187 ops/ms
Iteration   2: 8.072 ops/ms
Iteration   3: 8.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.119 ±(99.9%) 1.102 ops/ms [Average]
  (min, avg, max) = (8.072, 8.119, 8.187), stdev = 0.060
  CI (99.9%): [7.018, 9.221] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.311 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.003 ms/op
Iteration   1: 3.019 ±(99.9%) 0.003 ms/op
Iteration   2: 2.977 ±(99.9%) 0.003 ms/op
Iteration   3: 3.113 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.036 ±(99.9%) 1.271 ms/op [Average]
  (min, avg, max) = (2.977, 3.036, 3.113), stdev = 0.070
  CI (99.9%): [1.765, 4.307] (assumes normal distribution)


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
# Warmup Iteration   1: 4.262 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.002 ms/op
Iteration   1: 2.900 ±(99.9%) 0.002 ms/op
Iteration   2: 2.868 ±(99.9%) 0.003 ms/op
Iteration   3: 2.856 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.875 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (2.856, 2.875, 2.900), stdev = 0.023
  CI (99.9%): [2.459, 3.290] (assumes normal distribution)


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
# Warmup Iteration   1: 4.430 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.002 ms/op
Iteration   1: 2.968 ±(99.9%) 0.003 ms/op
Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
Iteration   3: 3.024 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.009 ±(99.9%) 0.664 ms/op [Average]
  (min, avg, max) = (2.968, 3.009, 3.036), stdev = 0.036
  CI (99.9%): [2.345, 3.673] (assumes normal distribution)


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
# Warmup Iteration   1: 5.407 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.019 ms/op
Iteration   1: 4.037 ±(99.9%) 0.021 ms/op
Iteration   2: 3.946 ±(99.9%) 0.010 ms/op
Iteration   3: 3.989 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.990 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (3.946, 3.990, 4.037), stdev = 0.045
  CI (99.9%): [3.162, 4.819] (assumes normal distribution)


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.433 ms/op
                 createUser·p0.9999: 13.706 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   2: 3.085 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  6.412 ms/op
                 createUser·p0.9999: 13.107 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.973 ms/op
                 createUser·p0.9999: 26.417 ms/op
                 createUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312457
  mean =      3.071 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21420 
    [ 2.500,  5.000) = 289635 
    [ 5.000,  7.500) = 1117 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.336 ms/op
     p(99.9900) =     23.143 ms/op
     p(99.9990) =     26.833 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
Iteration   1: 2.911 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.993 ms/op
                 existUser·p0.9999: 19.792 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   2: 2.868 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.293 ms/op
                 existUser·p0.99:   3.928 ms/op
                 existUser·p0.999:  7.510 ms/op
                 existUser·p0.9999: 14.137 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  7.236 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331042
  mean =      2.900 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35711 
    [ 2.500,  5.000) = 294403 
    [ 5.000,  7.500) = 622 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.139 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =     18.228 ms/op
     p(99.9990) =     20.875 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.322 ms/op
                 getUser·p0.95:   3.499 ms/op
                 getUser·p0.99:   4.241 ms/op
                 getUser·p0.999:  7.938 ms/op
                 getUser·p0.9999: 20.873 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  6.799 ms/op
                 getUser·p0.9999: 16.522 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.464 ms/op
                 getUser·p0.999:  6.660 ms/op
                 getUser·p0.9999: 16.516 ms/op
                 getUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319593
  mean =      3.004 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24138 
    [ 2.500,  5.000) = 294144 
    [ 5.000,  7.500) = 1051 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      6.942 ms/op
     p(99.9900) =     20.155 ms/op
     p(99.9990) =     21.149 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 5.676 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.011 ms/op
Iteration   1: 4.016 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  13.293 ms/op
                 listUser·p0.9999: 14.874 ms/op
                 listUser·p1.00:   16.433 ms/op

Iteration   2: 3.989 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.748 ms/op
                 listUser·p0.9999: 22.051 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  17.025 ms/op
                 listUser·p0.9999: 21.056 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241279
  mean =      3.979 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2578 
    [ 2.500,  5.000) = 214084 
    [ 5.000,  7.500) = 23219 
    [ 7.500, 10.000) = 914 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     14.266 ms/op
     p(99.9900) =     21.590 ms/op
     p(99.9990) =     22.353 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.414 ± 0.830  ops/ms
ClientGrpc.existUser                       thrpt       3  10.581 ± 5.370  ops/ms
ClientGrpc.getUser                         thrpt       3  10.536 ± 2.060  ops/ms
ClientGrpc.listUser                        thrpt       3   8.119 ± 1.102  ops/ms
ClientGrpc.createUser                       avgt       3   3.036 ± 1.271   ms/op
ClientGrpc.existUser                        avgt       3   2.875 ± 0.415   ms/op
ClientGrpc.getUser                          avgt       3   3.009 ± 0.664   ms/op
ClientGrpc.listUser                         avgt       3   3.990 ± 0.829   ms/op
ClientGrpc.createUser                     sample  312457   3.071 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.685           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.336           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.143           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.968           ms/op
ClientGrpc.existUser                      sample  331042   2.900 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.581           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.139           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.307           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.228           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.168           ms/op
ClientGrpc.getUser                        sample  319593   3.004 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.778           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.942           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.155           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.299           ms/op
ClientGrpc.listUser                       sample  241279   3.979 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.011           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.266           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.590           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.610           ms/op
