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
# Warmup Iteration   1: 4.709 ops/ms
# Warmup Iteration   2: 9.312 ops/ms
# Warmup Iteration   3: 10.839 ops/ms
Iteration   1: 10.694 ops/ms
Iteration   2: 10.705 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.699 ±(99.9%) 0.103 ops/ms [Average]
  (min, avg, max) = (10.694, 10.699, 10.705), stdev = 0.006
  CI (99.9%): [10.596, 10.801] (assumes normal distribution)


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
# Warmup Iteration   1: 7.527 ops/ms
# Warmup Iteration   2: 11.099 ops/ms
# Warmup Iteration   3: 11.208 ops/ms
Iteration   1: 11.268 ops/ms
Iteration   2: 11.331 ops/ms
Iteration   3: 11.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.327 ±(99.9%) 1.028 ops/ms [Average]
  (min, avg, max) = (11.268, 11.327, 11.381), stdev = 0.056
  CI (99.9%): [10.299, 12.354] (assumes normal distribution)


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
# Warmup Iteration   1: 7.702 ops/ms
# Warmup Iteration   2: 10.466 ops/ms
# Warmup Iteration   3: 10.654 ops/ms
Iteration   1: 10.631 ops/ms
Iteration   2: 10.533 ops/ms
Iteration   3: 10.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.615 ±(99.9%) 1.380 ops/ms [Average]
  (min, avg, max) = (10.533, 10.615, 10.682), stdev = 0.076
  CI (99.9%): [9.236, 11.995] (assumes normal distribution)


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
# Warmup Iteration   1: 6.130 ops/ms
# Warmup Iteration   2: 7.856 ops/ms
# Warmup Iteration   3: 8.175 ops/ms
Iteration   1: 8.470 ops/ms
Iteration   2: 8.477 ops/ms
Iteration   3: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.435 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (8.358, 8.435, 8.477), stdev = 0.066
  CI (99.9%): [7.223, 9.647] (assumes normal distribution)


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
# Warmup Iteration   1: 3.758 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 2.982 ±(99.9%) 0.002 ms/op
Iteration   3: 2.962 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.992 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (2.962, 2.992, 3.031), stdev = 0.036
  CI (99.9%): [2.343, 3.641] (assumes normal distribution)


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
# Warmup Iteration   1: 3.564 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 2.932 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.917 ±(99.9%) 0.003 ms/op
Iteration   1: 2.843 ±(99.9%) 0.003 ms/op
Iteration   2: 2.806 ±(99.9%) 0.004 ms/op
Iteration   3: 2.804 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.817 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (2.804, 2.817, 2.843), stdev = 0.022
  CI (99.9%): [2.416, 3.218] (assumes normal distribution)


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.003 ms/op
Iteration   1: 2.946 ±(99.9%) 0.003 ms/op
Iteration   2: 2.970 ±(99.9%) 0.002 ms/op
Iteration   3: 2.941 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.952 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (2.941, 2.952, 2.970), stdev = 0.015
  CI (99.9%): [2.674, 3.231] (assumes normal distribution)


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
# Warmup Iteration   1: 4.818 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.027 ms/op
Iteration   1: 3.761 ±(99.9%) 0.011 ms/op
Iteration   2: 3.792 ±(99.9%) 0.008 ms/op
Iteration   3: 3.767 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.773 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (3.761, 3.773, 3.792), stdev = 0.016
  CI (99.9%): [3.474, 4.073] (assumes normal distribution)


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
# Warmup Iteration   1: 3.683 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
Iteration   1: 2.933 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  7.560 ms/op
                 createUser·p0.9999: 17.796 ms/op
                 createUser·p1.00:   18.022 ms/op

Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  11.702 ms/op
                 createUser·p0.9999: 16.817 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.560 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  9.290 ms/op
                 createUser·p0.9999: 20.965 ms/op
                 createUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322878
  mean =      2.972 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32092 
    [ 2.500,  5.000) = 289486 
    [ 5.000,  7.500) = 862 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.994 ms/op
     p(99.9900) =     19.750 ms/op
     p(99.9990) =     21.259 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.850 ±(99.9%) 0.006 ms/op
Iteration   1: 2.850 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.822 ms/op
                 existUser·p0.9999: 17.163 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   2: 2.817 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.271 ms/op
                 existUser·p0.9999: 21.615 ms/op
                 existUser·p1.00:   22.020 ms/op

Iteration   3: 2.919 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  11.059 ms/op
                 existUser·p0.9999: 14.205 ms/op
                 existUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335294
  mean =      2.861 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50011 
    [ 2.500,  5.000) = 284277 
    [ 5.000,  7.500) = 699 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.217 ms/op
     p(99.9900) =     17.431 ms/op
     p(99.9990) =     21.943 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 2.973 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 11.387 ms/op
                 getUser·p1.00:   13.058 ms/op

Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.728 ms/op
                 getUser·p0.9999: 17.214 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   3: 3.035 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  7.321 ms/op
                 getUser·p0.9999: 17.039 ms/op
                 getUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319912
  mean =      3.001 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 695 
    [ 1.250,  2.500) = 22722 
    [ 2.500,  3.750) = 284577 
    [ 3.750,  5.000) = 10791 
    [ 5.000,  6.250) = 469 
    [ 6.250,  7.500) = 302 
    [ 7.500,  8.750) = 110 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 50 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     17.452 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 5.288 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.903 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.010 ms/op
Iteration   1: 3.800 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  11.878 ms/op
                 listUser·p0.9999: 15.024 ms/op
                 listUser·p1.00:   15.614 ms/op

Iteration   2: 3.902 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 21.404 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 3.775 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  20.447 ms/op
                 listUser·p0.9999: 23.317 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250907
  mean =      3.825 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6638 
    [ 2.500,  5.000) = 222995 
    [ 5.000,  7.500) = 20182 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     23.756 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.699 ± 0.103  ops/ms
ClientGrpc.existUser                       thrpt       3  11.327 ± 1.028  ops/ms
ClientGrpc.getUser                         thrpt       3  10.615 ± 1.380  ops/ms
ClientGrpc.listUser                        thrpt       3   8.435 ± 1.212  ops/ms
ClientGrpc.createUser                       avgt       3   2.992 ± 0.649   ms/op
ClientGrpc.existUser                        avgt       3   2.817 ± 0.401   ms/op
ClientGrpc.getUser                          avgt       3   2.952 ± 0.279   ms/op
ClientGrpc.listUser                         avgt       3   3.773 ± 0.300   ms/op
ClientGrpc.createUser                     sample  322878   2.972 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.560           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.994           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.750           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.299           ms/op
ClientGrpc.existUser                      sample  335294   2.861 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.616           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.843           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.217           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.431           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.020           ms/op
ClientGrpc.getUser                        sample  319912   3.001 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.849           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.799           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.974           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.596           ms/op
ClientGrpc.listUser                       sample  250907   3.825 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.853           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.674           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.118           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.888           ms/op
