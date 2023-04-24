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
# Warmup Iteration   1: 3.986 ops/ms
# Warmup Iteration   2: 9.208 ops/ms
# Warmup Iteration   3: 10.245 ops/ms
Iteration   1: 10.338 ops/ms
Iteration   2: 10.457 ops/ms
Iteration   3: 10.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.431 ±(99.9%) 1.528 ops/ms [Average]
  (min, avg, max) = (10.338, 10.431, 10.499), stdev = 0.084
  CI (99.9%): [8.903, 11.959] (assumes normal distribution)


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
# Warmup Iteration   1: 7.444 ops/ms
# Warmup Iteration   2: 10.446 ops/ms
# Warmup Iteration   3: 11.139 ops/ms
Iteration   1: 11.068 ops/ms
Iteration   2: 11.068 ops/ms
Iteration   3: 11.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.222 ±(99.9%) 4.877 ops/ms [Average]
  (min, avg, max) = (11.068, 11.222, 11.531), stdev = 0.267
  CI (99.9%): [6.345, 16.099] (assumes normal distribution)


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
# Warmup Iteration   1: 6.879 ops/ms
# Warmup Iteration   2: 10.446 ops/ms
# Warmup Iteration   3: 10.557 ops/ms
Iteration   1: 10.626 ops/ms
Iteration   2: 10.541 ops/ms
Iteration   3: 10.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.554 ±(99.9%) 1.228 ops/ms [Average]
  (min, avg, max) = (10.494, 10.554, 10.626), stdev = 0.067
  CI (99.9%): [9.326, 11.782] (assumes normal distribution)


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
# Warmup Iteration   1: 5.894 ops/ms
# Warmup Iteration   2: 7.793 ops/ms
# Warmup Iteration   3: 7.943 ops/ms
Iteration   1: 7.997 ops/ms
Iteration   2: 8.117 ops/ms
Iteration   3: 7.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.023 ±(99.9%) 1.532 ops/ms [Average]
  (min, avg, max) = (7.955, 8.023, 8.117), stdev = 0.084
  CI (99.9%): [6.491, 9.555] (assumes normal distribution)


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.003 ms/op
Iteration   1: 2.990 ±(99.9%) 0.003 ms/op
Iteration   2: 2.962 ±(99.9%) 0.002 ms/op
Iteration   3: 3.056 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.003 ±(99.9%) 0.874 ms/op [Average]
  (min, avg, max) = (2.962, 3.003, 3.056), stdev = 0.048
  CI (99.9%): [2.128, 3.877] (assumes normal distribution)


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.877 ±(99.9%) 0.002 ms/op
Iteration   1: 2.919 ±(99.9%) 0.002 ms/op
Iteration   2: 2.840 ±(99.9%) 0.003 ms/op
Iteration   3: 2.894 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.884 ±(99.9%) 0.742 ms/op [Average]
  (min, avg, max) = (2.840, 2.884, 2.919), stdev = 0.041
  CI (99.9%): [2.142, 3.626] (assumes normal distribution)


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
# Warmup Iteration   1: 4.265 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.004 ms/op
Iteration   1: 2.998 ±(99.9%) 0.004 ms/op
Iteration   2: 2.993 ±(99.9%) 0.002 ms/op
Iteration   3: 3.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.002 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (2.993, 3.002, 3.014), stdev = 0.011
  CI (99.9%): [2.804, 3.199] (assumes normal distribution)


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
# Warmup Iteration   1: 5.336 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.008 ms/op
Iteration   1: 3.968 ±(99.9%) 0.023 ms/op
Iteration   2: 3.810 ±(99.9%) 0.021 ms/op
Iteration   3: 3.923 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.900 ±(99.9%) 1.485 ms/op [Average]
  (min, avg, max) = (3.810, 3.900, 3.968), stdev = 0.081
  CI (99.9%): [2.416, 5.385] (assumes normal distribution)


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
# Warmup Iteration   1: 4.318 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 2.990 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.428 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.728 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  8.388 ms/op
                 createUser·p0.9999: 12.537 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  6.790 ms/op
                 createUser·p0.9999: 14.074 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.570 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  9.601 ms/op
                 createUser·p0.9999: 26.477 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319302
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29155 
    [ 2.500,  5.000) = 288620 
    [ 5.000,  7.500) = 1196 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.818 ms/op
     p(99.9900) =     24.742 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.006 ms/op
Iteration   1: 2.888 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  8.851 ms/op
                 existUser·p0.9999: 13.401 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   2: 2.915 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  6.687 ms/op
                 existUser·p0.9999: 14.713 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   3: 2.957 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  5.616 ms/op
                 existUser·p0.9999: 16.810 ms/op
                 existUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328659
  mean =      2.919 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 568 
    [ 1.250,  2.500) = 32725 
    [ 2.500,  3.750) = 284720 
    [ 3.750,  5.000) = 9783 
    [ 5.000,  6.250) = 491 
    [ 6.250,  7.500) = 159 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      6.480 ms/op
     p(99.9900) =     15.152 ms/op
     p(99.9990) =     16.932 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 3.021 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.385 ms/op
                 getUser·p0.999:  6.808 ms/op
                 getUser·p0.9999: 26.405 ms/op
                 getUser·p1.00:   27.656 ms/op

Iteration   2: 3.024 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  8.595 ms/op
                 getUser·p0.9999: 22.224 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 2.966 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.560 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.808 ms/op
                 getUser·p0.9999: 24.248 ms/op
                 getUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319534
  mean =      3.004 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29143 
    [ 2.500,  5.000) = 288967 
    [ 5.000,  7.500) = 1157 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.033 ms/op
     p(99.9900) =     25.629 ms/op
     p(99.9990) =     26.732 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 5.689 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.010 ms/op
Iteration   1: 3.946 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  12.827 ms/op
                 listUser·p0.9999: 14.252 ms/op
                 listUser·p1.00:   14.975 ms/op

Iteration   2: 3.979 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 21.405 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 3.965 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  13.898 ms/op
                 listUser·p0.9999: 25.358 ms/op
                 listUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242172
  mean =      3.963 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1773 
    [ 2.500,  5.000) = 221988 
    [ 5.000,  7.500) = 17345 
    [ 7.500, 10.000) = 662 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     24.562 ms/op
     p(99.9990) =     25.794 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.431 ± 1.528  ops/ms
ClientGrpc.existUser                       thrpt       3  11.222 ± 4.877  ops/ms
ClientGrpc.getUser                         thrpt       3  10.554 ± 1.228  ops/ms
ClientGrpc.listUser                        thrpt       3   8.023 ± 1.532  ops/ms
ClientGrpc.createUser                       avgt       3   3.003 ± 0.874   ms/op
ClientGrpc.existUser                        avgt       3   2.884 ± 0.742   ms/op
ClientGrpc.getUser                          avgt       3   3.002 ± 0.198   ms/op
ClientGrpc.listUser                         avgt       3   3.900 ± 1.485   ms/op
ClientGrpc.createUser                     sample  319302   3.005 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.428           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.818           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.742           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.099           ms/op
ClientGrpc.existUser                      sample  328659   2.919 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.674           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.480           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.152           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.138           ms/op
ClientGrpc.getUser                        sample  319534   3.004 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.560           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.033           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.629           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.656           ms/op
ClientGrpc.listUser                       sample  242172   3.963 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.260           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.631           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.562           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.083           ms/op
