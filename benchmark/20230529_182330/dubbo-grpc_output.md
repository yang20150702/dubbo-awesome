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
# Warmup Iteration   1: 4.182 ops/ms
# Warmup Iteration   2: 9.322 ops/ms
# Warmup Iteration   3: 10.170 ops/ms
Iteration   1: 10.565 ops/ms
Iteration   2: 10.595 ops/ms
Iteration   3: 10.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.636 ±(99.9%) 1.803 ops/ms [Average]
  (min, avg, max) = (10.565, 10.636, 10.749), stdev = 0.099
  CI (99.9%): [8.834, 12.439] (assumes normal distribution)


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
# Warmup Iteration   1: 7.923 ops/ms
# Warmup Iteration   2: 10.725 ops/ms
# Warmup Iteration   3: 10.943 ops/ms
Iteration   1: 11.212 ops/ms
Iteration   2: 11.247 ops/ms
Iteration   3: 11.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.163 ±(99.9%) 2.111 ops/ms [Average]
  (min, avg, max) = (11.031, 11.163, 11.247), stdev = 0.116
  CI (99.9%): [9.053, 13.274] (assumes normal distribution)


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
# Warmup Iteration   1: 7.100 ops/ms
# Warmup Iteration   2: 10.403 ops/ms
# Warmup Iteration   3: 10.551 ops/ms
Iteration   1: 10.567 ops/ms
Iteration   2: 10.810 ops/ms
Iteration   3: 10.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.729 ±(99.9%) 2.554 ops/ms [Average]
  (min, avg, max) = (10.567, 10.729, 10.810), stdev = 0.140
  CI (99.9%): [8.175, 13.283] (assumes normal distribution)


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
# Warmup Iteration   1: 6.432 ops/ms
# Warmup Iteration   2: 7.479 ops/ms
# Warmup Iteration   3: 7.746 ops/ms
Iteration   1: 7.971 ops/ms
Iteration   2: 7.964 ops/ms
Iteration   3: 8.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.050 ±(99.9%) 2.632 ops/ms [Average]
  (min, avg, max) = (7.964, 8.050, 8.217), stdev = 0.144
  CI (99.9%): [5.419, 10.682] (assumes normal distribution)


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
# Warmup Iteration   1: 4.220 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.004 ms/op
Iteration   2: 3.015 ±(99.9%) 0.004 ms/op
Iteration   3: 3.020 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.008 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (2.988, 3.008, 3.020), stdev = 0.017
  CI (99.9%): [2.695, 3.321] (assumes normal distribution)


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
# Warmup Iteration   1: 3.745 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.912 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.882 ±(99.9%) 0.004 ms/op
Iteration   1: 2.874 ±(99.9%) 0.003 ms/op
Iteration   2: 2.901 ±(99.9%) 0.003 ms/op
Iteration   3: 2.866 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.881 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (2.866, 2.881, 2.901), stdev = 0.018
  CI (99.9%): [2.545, 3.216] (assumes normal distribution)


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.060 ±(99.9%) 0.002 ms/op
Iteration   2: 3.039 ±(99.9%) 0.002 ms/op
Iteration   3: 3.056 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.052 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (3.039, 3.052, 3.060), stdev = 0.011
  CI (99.9%): [2.847, 3.256] (assumes normal distribution)


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.247 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.009 ms/op
Iteration   1: 3.959 ±(99.9%) 0.022 ms/op
Iteration   2: 3.993 ±(99.9%) 0.011 ms/op
Iteration   3: 3.999 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.983 ±(99.9%) 0.394 ms/op [Average]
  (min, avg, max) = (3.959, 3.983, 3.999), stdev = 0.022
  CI (99.9%): [3.589, 4.378] (assumes normal distribution)


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.007 ms/op
Iteration   1: 3.024 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.564 ms/op
                 createUser·p0.9999: 18.429 ms/op
                 createUser·p1.00:   18.842 ms/op

Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.510 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  8.225 ms/op
                 createUser·p0.9999: 15.566 ms/op
                 createUser·p1.00:   16.024 ms/op

Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.333 ms/op
                 createUser·p0.9999: 22.497 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317554
  mean =      3.023 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23255 
    [ 2.500,  5.000) = 292918 
    [ 5.000,  7.500) = 1020 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.126 ms/op
     p(99.9900) =     20.917 ms/op
     p(99.9990) =     22.735 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 3.725 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.883 ±(99.9%) 0.005 ms/op
Iteration   1: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.059 ms/op
                 existUser·p0.999:  6.076 ms/op
                 existUser·p0.9999: 19.136 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   2: 2.906 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   3.965 ms/op
                 existUser·p0.999:  6.356 ms/op
                 existUser·p0.9999: 13.876 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   3: 2.823 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  5.413 ms/op
                 existUser·p0.9999: 16.395 ms/op
                 existUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333613
  mean =      2.879 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2382 
    [ 1.250,  2.500) = 40418 
    [ 2.500,  3.750) = 283042 
    [ 3.750,  5.000) = 7081 
    [ 5.000,  6.250) = 431 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      6.005 ms/op
     p(99.9900) =     16.698 ms/op
     p(99.9990) =     19.475 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
Iteration   1: 3.065 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.636 ms/op
                 getUser·p0.9999: 12.297 ms/op
                 getUser·p1.00:   12.468 ms/op

Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.553 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.444 ms/op
                 getUser·p0.9999: 14.877 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.550 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.903 ms/op
                 getUser·p0.9999: 18.708 ms/op
                 getUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315117
  mean =      3.045 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 427 
    [ 1.250,  2.500) = 21471 
    [ 2.500,  3.750) = 274886 
    [ 3.750,  5.000) = 17174 
    [ 5.000,  6.250) = 725 
    [ 6.250,  7.500) = 219 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.668 ms/op
     p(99.9900) =     17.055 ms/op
     p(99.9990) =     19.558 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 4.753 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.393 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.011 ms/op
Iteration   1: 3.982 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  18.040 ms/op
                 listUser·p0.9999: 21.134 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   2: 3.982 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  15.832 ms/op
                 listUser·p0.9999: 25.160 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   3: 3.986 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  16.675 ms/op
                 listUser·p0.9999: 23.126 ms/op
                 listUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241027
  mean =      3.983 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3479 
    [ 2.500,  5.000) = 216093 
    [ 5.000,  7.500) = 20101 
    [ 7.500, 10.000) = 882 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     17.006 ms/op
     p(99.9900) =     24.540 ms/op
     p(99.9990) =     25.808 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.636 ± 1.803  ops/ms
ClientGrpc.existUser                       thrpt       3  11.163 ± 2.111  ops/ms
ClientGrpc.getUser                         thrpt       3  10.729 ± 2.554  ops/ms
ClientGrpc.listUser                        thrpt       3   8.050 ± 2.632  ops/ms
ClientGrpc.createUser                       avgt       3   3.008 ± 0.313   ms/op
ClientGrpc.existUser                        avgt       3   2.881 ± 0.335   ms/op
ClientGrpc.getUser                          avgt       3   3.052 ± 0.205   ms/op
ClientGrpc.listUser                         avgt       3   3.983 ± 0.394   ms/op
ClientGrpc.createUser                     sample  317554   3.023 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.685           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.126           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.917           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.101           ms/op
ClientGrpc.existUser                      sample  333613   2.879 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.547           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.059           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.005           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.698           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.530           ms/op
ClientGrpc.getUser                        sample  315117   3.045 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.553           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.668           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.055           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.726           ms/op
ClientGrpc.listUser                       sample  241027   3.983 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.886           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.006           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.540           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.919           ms/op
