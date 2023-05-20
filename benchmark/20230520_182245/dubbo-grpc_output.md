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
# Warmup Iteration   1: 4.624 ops/ms
# Warmup Iteration   2: 9.526 ops/ms
# Warmup Iteration   3: 10.152 ops/ms
Iteration   1: 10.233 ops/ms
Iteration   2: 10.730 ops/ms
Iteration   3: 10.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.546 ±(99.9%) 4.975 ops/ms [Average]
  (min, avg, max) = (10.233, 10.546, 10.730), stdev = 0.273
  CI (99.9%): [5.570, 15.521] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.039 ops/ms
# Warmup Iteration   2: 10.824 ops/ms
# Warmup Iteration   3: 11.281 ops/ms
Iteration   1: 11.138 ops/ms
Iteration   2: 11.249 ops/ms
Iteration   3: 11.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.258 ±(99.9%) 2.267 ops/ms [Average]
  (min, avg, max) = (11.138, 11.258, 11.386), stdev = 0.124
  CI (99.9%): [8.990, 13.525] (assumes normal distribution)


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
# Warmup Iteration   1: 8.396 ops/ms
# Warmup Iteration   2: 10.303 ops/ms
# Warmup Iteration   3: 10.698 ops/ms
Iteration   1: 10.814 ops/ms
Iteration   2: 10.644 ops/ms
Iteration   3: 10.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.762 ±(99.9%) 1.861 ops/ms [Average]
  (min, avg, max) = (10.644, 10.762, 10.827), stdev = 0.102
  CI (99.9%): [8.900, 12.623] (assumes normal distribution)


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
# Warmup Iteration   1: 6.002 ops/ms
# Warmup Iteration   2: 7.984 ops/ms
# Warmup Iteration   3: 8.088 ops/ms
Iteration   1: 8.030 ops/ms
Iteration   2: 8.259 ops/ms
Iteration   3: 8.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.170 ±(99.9%) 2.235 ops/ms [Average]
  (min, avg, max) = (8.030, 8.170, 8.259), stdev = 0.123
  CI (99.9%): [5.935, 10.406] (assumes normal distribution)


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.002 ms/op
Iteration   1: 2.983 ±(99.9%) 0.003 ms/op
Iteration   2: 3.013 ±(99.9%) 0.003 ms/op
Iteration   3: 2.939 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.978 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (2.939, 2.978, 3.013), stdev = 0.037
  CI (99.9%): [2.300, 3.657] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.880 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.930 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.855 ±(99.9%) 0.003 ms/op
Iteration   1: 2.845 ±(99.9%) 0.003 ms/op
Iteration   2: 2.871 ±(99.9%) 0.003 ms/op
Iteration   3: 2.794 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.837 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (2.794, 2.837, 2.871), stdev = 0.039
  CI (99.9%): [2.128, 3.545] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.974 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.002 ms/op
Iteration   1: 2.996 ±(99.9%) 0.003 ms/op
Iteration   2: 2.933 ±(99.9%) 0.003 ms/op
Iteration   3: 2.999 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.976 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (2.933, 2.976, 2.999), stdev = 0.037
  CI (99.9%): [2.303, 3.649] (assumes normal distribution)


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
# Warmup Iteration   1: 4.914 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.036 ms/op
Iteration   1: 3.963 ±(99.9%) 0.028 ms/op
Iteration   2: 3.893 ±(99.9%) 0.019 ms/op
Iteration   3: 3.754 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.870 ±(99.9%) 1.941 ms/op [Average]
  (min, avg, max) = (3.754, 3.870, 3.963), stdev = 0.106
  CI (99.9%): [1.929, 5.811] (assumes normal distribution)


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.937 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.400 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  6.603 ms/op
                 createUser·p0.9999: 17.760 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.642 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  9.042 ms/op
                 createUser·p0.9999: 20.722 ms/op
                 createUser·p1.00:   20.939 ms/op

Iteration   3: 2.974 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.242 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.125 ms/op
                 createUser·p0.9999: 23.175 ms/op
                 createUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322933
  mean =      2.973 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19022 
    [ 2.500,  5.000) = 302925 
    [ 5.000,  7.500) = 644 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.242 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     22.096 ms/op
     p(99.9990) =     23.356 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 3.656 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.855 ±(99.9%) 0.007 ms/op
Iteration   1: 2.840 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.311 ms/op
                 existUser·p0.9999: 17.653 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   2: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.209 ms/op
                 existUser·p0.9999: 17.625 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   3: 2.855 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  5.859 ms/op
                 existUser·p0.9999: 13.431 ms/op
                 existUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336056
  mean =      2.856 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2630 
    [ 1.250,  2.500) = 50104 
    [ 2.500,  3.750) = 271661 
    [ 3.750,  5.000) = 10854 
    [ 5.000,  6.250) = 449 
    [ 6.250,  7.500) = 153 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      6.413 ms/op
     p(99.9900) =     17.478 ms/op
     p(99.9990) =     17.978 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 3.972 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.007 ms/op
Iteration   1: 2.944 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  5.941 ms/op
                 getUser·p0.9999: 12.227 ms/op
                 getUser·p1.00:   12.567 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.504 ms/op
                 getUser·p0.9999: 13.992 ms/op
                 getUser·p1.00:   16.073 ms/op

Iteration   3: 2.968 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.547 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.152 ms/op
                 getUser·p0.9999: 26.818 ms/op
                 getUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323469
  mean =      2.967 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29257 
    [ 2.500,  5.000) = 293002 
    [ 5.000,  7.500) = 975 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.222 ms/op
     p(99.9900) =     22.937 ms/op
     p(99.9990) =     26.960 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.833 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.012 ms/op
Iteration   1: 3.904 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  13.008 ms/op
                 listUser·p0.9999: 14.483 ms/op
                 listUser·p1.00:   15.106 ms/op

Iteration   2: 3.876 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 23.904 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   3: 3.866 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  15.094 ms/op
                 listUser·p0.9999: 22.330 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247278
  mean =      3.882 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4175 
    [ 2.500,  5.000) = 224175 
    [ 5.000,  7.500) = 17786 
    [ 7.500, 10.000) = 669 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.695 ms/op
     p(99.9000) =     14.093 ms/op
     p(99.9900) =     23.078 ms/op
     p(99.9990) =     24.561 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.546 ± 4.975  ops/ms
ClientGrpc.existUser                       thrpt       3  11.258 ± 2.267  ops/ms
ClientGrpc.getUser                         thrpt       3  10.762 ± 1.861  ops/ms
ClientGrpc.listUser                        thrpt       3   8.170 ± 2.235  ops/ms
ClientGrpc.createUser                       avgt       3   2.978 ± 0.678   ms/op
ClientGrpc.existUser                        avgt       3   2.837 ± 0.708   ms/op
ClientGrpc.getUser                          avgt       3   2.976 ± 0.673   ms/op
ClientGrpc.listUser                         avgt       3   3.870 ± 1.941   ms/op
ClientGrpc.createUser                     sample  322933   2.973 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.242           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.379           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.157           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.405           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.096           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.462           ms/op
ClientGrpc.existUser                      sample  336056   2.856 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.604           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.334           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.413           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.478           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.022           ms/op
ClientGrpc.getUser                        sample  323469   2.967 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.547           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.222           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.937           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.034           ms/op
ClientGrpc.listUser                       sample  247278   3.882 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.978           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.710           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.695           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.093           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.078           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.609           ms/op
