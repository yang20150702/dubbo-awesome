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
# Warmup Iteration   1: 4.156 ops/ms
# Warmup Iteration   2: 8.859 ops/ms
# Warmup Iteration   3: 10.298 ops/ms
Iteration   1: 10.459 ops/ms
Iteration   2: 10.592 ops/ms
Iteration   3: 10.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.585 ±(99.9%) 2.231 ops/ms [Average]
  (min, avg, max) = (10.459, 10.585, 10.704), stdev = 0.122
  CI (99.9%): [8.354, 12.816] (assumes normal distribution)


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
# Warmup Iteration   1: 7.524 ops/ms
# Warmup Iteration   2: 10.642 ops/ms
# Warmup Iteration   3: 11.106 ops/ms
Iteration   1: 11.248 ops/ms
Iteration   2: 11.245 ops/ms
Iteration   3: 11.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.273 ±(99.9%) 0.844 ops/ms [Average]
  (min, avg, max) = (11.245, 11.273, 11.327), stdev = 0.046
  CI (99.9%): [10.430, 12.117] (assumes normal distribution)


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
# Warmup Iteration   1: 6.707 ops/ms
# Warmup Iteration   2: 10.041 ops/ms
# Warmup Iteration   3: 10.541 ops/ms
Iteration   1: 10.564 ops/ms
Iteration   2: 10.597 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.592 ±(99.9%) 0.478 ops/ms [Average]
  (min, avg, max) = (10.564, 10.592, 10.615), stdev = 0.026
  CI (99.9%): [10.114, 11.070] (assumes normal distribution)


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
# Warmup Iteration   1: 5.586 ops/ms
# Warmup Iteration   2: 7.580 ops/ms
# Warmup Iteration   3: 7.901 ops/ms
Iteration   1: 8.016 ops/ms
Iteration   2: 7.967 ops/ms
Iteration   3: 8.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.005 ±(99.9%) 0.626 ops/ms [Average]
  (min, avg, max) = (7.967, 8.005, 8.033), stdev = 0.034
  CI (99.9%): [7.379, 8.631] (assumes normal distribution)


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
# Warmup Iteration   1: 4.140 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.003 ms/op
Iteration   1: 3.023 ±(99.9%) 0.003 ms/op
Iteration   2: 3.020 ±(99.9%) 0.003 ms/op
Iteration   3: 3.079 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.041 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (3.020, 3.041, 3.079), stdev = 0.033
  CI (99.9%): [2.438, 3.644] (assumes normal distribution)


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.002 ms/op
Iteration   1: 2.824 ±(99.9%) 0.003 ms/op
Iteration   2: 2.844 ±(99.9%) 0.003 ms/op
Iteration   3: 2.951 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.873 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (2.824, 2.873, 2.951), stdev = 0.068
  CI (99.9%): [1.634, 4.113] (assumes normal distribution)


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
# Warmup Iteration   1: 4.248 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.003 ms/op
Iteration   1: 2.986 ±(99.9%) 0.004 ms/op
Iteration   2: 3.019 ±(99.9%) 0.003 ms/op
Iteration   3: 2.967 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (2.967, 2.991, 3.019), stdev = 0.026
  CI (99.9%): [2.510, 3.471] (assumes normal distribution)


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
# Warmup Iteration   1: 5.137 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.022 ms/op
Iteration   1: 3.912 ±(99.9%) 0.034 ms/op
Iteration   2: 4.022 ±(99.9%) 0.033 ms/op
Iteration   3: 3.948 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.961 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.912, 3.961, 4.022), stdev = 0.056
  CI (99.9%): [2.936, 4.986] (assumes normal distribution)


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.006 ms/op
Iteration   1: 3.046 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  7.873 ms/op
                 createUser·p0.9999: 15.057 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.432 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  8.880 ms/op
                 createUser·p0.9999: 22.577 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  15.471 ms/op
                 createUser·p0.9999: 19.842 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318100
  mean =      3.017 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24518 
    [ 2.500,  5.000) = 292086 
    [ 5.000,  7.500) = 1076 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      9.644 ms/op
     p(99.9900) =     22.256 ms/op
     p(99.9990) =     22.735 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.857 ±(99.9%) 0.006 ms/op
Iteration   1: 2.883 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.701 ms/op
                 existUser·p0.9999: 20.939 ms/op
                 existUser·p1.00:   21.365 ms/op

Iteration   2: 2.895 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  6.874 ms/op
                 existUser·p0.9999: 14.974 ms/op
                 existUser·p1.00:   16.089 ms/op

Iteration   3: 2.908 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.387 ms/op
                 existUser·p0.999:  7.895 ms/op
                 existUser·p0.9999: 19.660 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331543
  mean =      2.895 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43735 
    [ 2.500,  5.000) = 286502 
    [ 5.000,  7.500) = 1003 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.417 ms/op
     p(99.9900) =     19.852 ms/op
     p(99.9990) =     21.256 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.258 ms/op
                 getUser·p0.9999: 12.918 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.318 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 15.886 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.112 ms/op
                 getUser·p0.9999: 17.774 ms/op
                 getUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315821
  mean =      3.039 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 389 
    [ 1.250,  2.500) = 19117 
    [ 2.500,  3.750) = 279512 
    [ 3.750,  5.000) = 14973 
    [ 5.000,  6.250) = 1106 
    [ 6.250,  7.500) = 450 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.318 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.235 ms/op
     p(99.9900) =     16.463 ms/op
     p(99.9990) =     18.138 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 5.430 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.011 ms/op
Iteration   1: 4.039 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  13.451 ms/op
                 listUser·p0.9999: 21.176 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   2: 4.002 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  23.036 ms/op
                 listUser·p0.9999: 27.394 ms/op
                 listUser·p1.00:   28.279 ms/op

Iteration   3: 4.007 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  17.579 ms/op
                 listUser·p0.9999: 28.017 ms/op
                 listUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239064
  mean =      4.016 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2651 
    [ 2.500,  5.000) = 212012 
    [ 5.000,  7.500) = 22728 
    [ 7.500, 10.000) = 1136 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     17.690 ms/op
     p(99.9900) =     27.561 ms/op
     p(99.9990) =     28.490 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.585 ± 2.231  ops/ms
ClientGrpc.existUser                       thrpt       3  11.273 ± 0.844  ops/ms
ClientGrpc.getUser                         thrpt       3  10.592 ± 0.478  ops/ms
ClientGrpc.listUser                        thrpt       3   8.005 ± 0.626  ops/ms
ClientGrpc.createUser                       avgt       3   3.041 ± 0.603   ms/op
ClientGrpc.existUser                        avgt       3   2.873 ± 1.239   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 0.480   ms/op
ClientGrpc.listUser                         avgt       3   3.961 ± 1.025   ms/op
ClientGrpc.createUser                     sample  318100   3.017 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.697           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.644           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.256           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.807           ms/op
ClientGrpc.existUser                      sample  331543   2.895 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.636           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.417           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.852           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.365           ms/op
ClientGrpc.getUser                        sample  315821   3.039 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.318           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.235           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.463           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.252           ms/op
ClientGrpc.listUser                       sample  239064   4.016 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.887           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.690           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.561           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.574           ms/op
