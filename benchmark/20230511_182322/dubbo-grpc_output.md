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
# Warmup Iteration   1: 4.571 ops/ms
# Warmup Iteration   2: 9.350 ops/ms
# Warmup Iteration   3: 10.070 ops/ms
Iteration   1: 10.545 ops/ms
Iteration   2: 10.575 ops/ms
Iteration   3: 10.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.595 ±(99.9%) 1.138 ops/ms [Average]
  (min, avg, max) = (10.545, 10.595, 10.665), stdev = 0.062
  CI (99.9%): [9.457, 11.733] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.841 ops/ms
# Warmup Iteration   2: 10.608 ops/ms
# Warmup Iteration   3: 11.117 ops/ms
Iteration   1: 10.898 ops/ms
Iteration   2: 11.110 ops/ms
Iteration   3: 11.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.119 ±(99.9%) 4.107 ops/ms [Average]
  (min, avg, max) = (10.898, 11.119, 11.348), stdev = 0.225
  CI (99.9%): [7.011, 15.226] (assumes normal distribution)


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
# Warmup Iteration   1: 7.214 ops/ms
# Warmup Iteration   2: 10.398 ops/ms
# Warmup Iteration   3: 10.805 ops/ms
Iteration   1: 10.847 ops/ms
Iteration   2: 10.724 ops/ms
Iteration   3: 10.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.749 ±(99.9%) 1.612 ops/ms [Average]
  (min, avg, max) = (10.675, 10.749, 10.847), stdev = 0.088
  CI (99.9%): [9.136, 12.361] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.885 ops/ms
# Warmup Iteration   2: 7.880 ops/ms
# Warmup Iteration   3: 8.132 ops/ms
Iteration   1: 8.490 ops/ms
Iteration   2: 8.264 ops/ms
Iteration   3: 8.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.310 ±(99.9%) 2.953 ops/ms [Average]
  (min, avg, max) = (8.177, 8.310, 8.490), stdev = 0.162
  CI (99.9%): [5.358, 11.263] (assumes normal distribution)


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
# Warmup Iteration   1: 4.115 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.003 ms/op
Iteration   1: 2.999 ±(99.9%) 0.002 ms/op
Iteration   2: 2.949 ±(99.9%) 0.002 ms/op
Iteration   3: 3.012 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.987 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (2.949, 2.987, 3.012), stdev = 0.033
  CI (99.9%): [2.383, 3.591] (assumes normal distribution)


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.003 ms/op
Iteration   1: 2.884 ±(99.9%) 0.003 ms/op
Iteration   2: 2.896 ±(99.9%) 0.002 ms/op
Iteration   3: 2.832 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.871 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (2.832, 2.871, 2.896), stdev = 0.034
  CI (99.9%): [2.248, 3.494] (assumes normal distribution)


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
# Warmup Iteration   1: 4.045 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.002 ms/op
Iteration   1: 2.958 ±(99.9%) 0.002 ms/op
Iteration   2: 2.973 ±(99.9%) 0.002 ms/op
Iteration   3: 2.932 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.954 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (2.932, 2.954, 2.973), stdev = 0.021
  CI (99.9%): [2.569, 3.340] (assumes normal distribution)


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
# Warmup Iteration   1: 5.166 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.031 ms/op
Iteration   1: 3.894 ±(99.9%) 0.028 ms/op
Iteration   2: 3.847 ±(99.9%) 0.039 ms/op
Iteration   3: 3.832 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.858 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (3.832, 3.858, 3.894), stdev = 0.033
  CI (99.9%): [3.261, 4.454] (assumes normal distribution)


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
# Warmup Iteration   1: 4.064 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 2.937 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.546 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.866 ms/op
                 createUser·p0.9999: 11.929 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.300 ms/op
                 createUser·p0.9999: 19.740 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.236 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  7.827 ms/op
                 createUser·p0.9999: 17.313 ms/op
                 createUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323573
  mean =      2.968 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30280 
    [ 2.500,  5.000) = 292096 
    [ 5.000,  7.500) = 909 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.236 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.086 ms/op
     p(99.9900) =     18.720 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.933 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.878 ±(99.9%) 0.006 ms/op
Iteration   1: 2.887 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  6.457 ms/op
                 existUser·p0.9999: 12.680 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   2: 2.856 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  7.127 ms/op
                 existUser·p0.9999: 18.278 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   3: 2.869 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  7.558 ms/op
                 existUser·p0.9999: 17.685 ms/op
                 existUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334223
  mean =      2.871 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2807 
    [ 1.250,  2.500) = 37830 
    [ 2.500,  3.750) = 283089 
    [ 3.750,  5.000) = 8982 
    [ 5.000,  6.250) = 980 
    [ 6.250,  7.500) = 278 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.068 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     19.355 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.946 ms/op
                 getUser·p0.9999: 22.195 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   2: 2.994 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.417 ms/op
                 getUser·p0.9999: 15.324 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.677 ms/op
                 getUser·p0.9999: 16.455 ms/op
                 getUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320340
  mean =      2.996 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29080 
    [ 2.500,  5.000) = 289883 
    [ 5.000,  7.500) = 1062 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.381 ms/op
     p(99.9900) =     21.525 ms/op
     p(99.9990) =     22.374 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 4.963 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.011 ms/op
Iteration   1: 3.903 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.239 ms/op
                 listUser·p0.9999: 18.999 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 3.782 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.304 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  14.521 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.624 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  14.025 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247963
  mean =      3.874 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3822 
    [ 2.500,  5.000) = 223729 
    [ 5.000,  7.500) = 18936 
    [ 7.500, 10.000) = 938 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.304 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     14.222 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     21.698 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.595 ± 1.138  ops/ms
ClientGrpc.existUser                       thrpt       3  11.119 ± 4.107  ops/ms
ClientGrpc.getUser                         thrpt       3  10.749 ± 1.612  ops/ms
ClientGrpc.listUser                        thrpt       3   8.310 ± 2.953  ops/ms
ClientGrpc.createUser                       avgt       3   2.987 ± 0.604   ms/op
ClientGrpc.existUser                        avgt       3   2.871 ± 0.623   ms/op
ClientGrpc.getUser                          avgt       3   2.954 ± 0.385   ms/op
ClientGrpc.listUser                         avgt       3   3.858 ± 0.596   ms/op
ClientGrpc.createUser                     sample  323573   2.968 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.236           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.086           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.720           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.021           ms/op
ClientGrpc.existUser                      sample  334223   2.871 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.565           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.068           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.826           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.366           ms/op
ClientGrpc.getUser                        sample  320340   2.996 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.690           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.381           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.525           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.413           ms/op
ClientGrpc.listUser                       sample  247963   3.874 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.304           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.222           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.825           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.922           ms/op
