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
# Warmup Iteration   1: 3.603 ops/ms
# Warmup Iteration   2: 8.534 ops/ms
# Warmup Iteration   3: 9.784 ops/ms
Iteration   1: 10.637 ops/ms
Iteration   2: 10.330 ops/ms
Iteration   3: 10.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.482 ±(99.9%) 2.808 ops/ms [Average]
  (min, avg, max) = (10.330, 10.482, 10.637), stdev = 0.154
  CI (99.9%): [7.674, 13.290] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.464 ops/ms
# Warmup Iteration   2: 10.486 ops/ms
# Warmup Iteration   3: 10.951 ops/ms
Iteration   1: 10.917 ops/ms
Iteration   2: 11.311 ops/ms
Iteration   3: 11.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.201 ±(99.9%) 4.530 ops/ms [Average]
  (min, avg, max) = (10.917, 11.201, 11.375), stdev = 0.248
  CI (99.9%): [6.671, 15.731] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.309 ops/ms
# Warmup Iteration   2: 10.390 ops/ms
# Warmup Iteration   3: 10.712 ops/ms
Iteration   1: 10.731 ops/ms
Iteration   2: 10.773 ops/ms
Iteration   3: 10.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.803 ±(99.9%) 1.672 ops/ms [Average]
  (min, avg, max) = (10.731, 10.803, 10.906), stdev = 0.092
  CI (99.9%): [9.131, 12.475] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.051 ops/ms
# Warmup Iteration   2: 9.521 ops/ms
# Warmup Iteration   3: 8.148 ops/ms
Iteration   1: 8.351 ops/ms
Iteration   2: 8.240 ops/ms
Iteration   3: 8.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.331 ±(99.9%) 1.503 ops/ms [Average]
  (min, avg, max) = (8.240, 8.331, 8.401), stdev = 0.082
  CI (99.9%): [6.828, 9.833] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.025 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.002 ms/op
Iteration   1: 3.017 ±(99.9%) 0.002 ms/op
Iteration   2: 3.002 ±(99.9%) 0.002 ms/op
Iteration   3: 2.920 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.980 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (2.920, 2.980, 3.017), stdev = 0.052
  CI (99.9%): [2.030, 3.929] (assumes normal distribution)


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.957 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.828 ±(99.9%) 0.003 ms/op
Iteration   1: 2.855 ±(99.9%) 0.003 ms/op
Iteration   2: 2.830 ±(99.9%) 0.003 ms/op
Iteration   3: 2.826 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.837 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.826, 2.837, 2.855), stdev = 0.016
  CI (99.9%): [2.545, 3.128] (assumes normal distribution)


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.003 ms/op
Iteration   1: 2.968 ±(99.9%) 0.004 ms/op
Iteration   2: 2.995 ±(99.9%) 0.002 ms/op
Iteration   3: 3.032 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.998 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (2.968, 2.998, 3.032), stdev = 0.032
  CI (99.9%): [2.407, 3.590] (assumes normal distribution)


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
# Warmup Iteration   1: 4.953 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.020 ms/op
Iteration   1: 3.865 ±(99.9%) 0.024 ms/op
Iteration   2: 3.819 ±(99.9%) 0.010 ms/op
Iteration   3: 3.831 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.838 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (3.819, 3.838, 3.865), stdev = 0.024
  CI (99.9%): [3.402, 4.274] (assumes normal distribution)


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
# Warmup Iteration   1: 4.122 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 2.966 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.602 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.166 ms/op
                 createUser·p0.999:  7.135 ms/op
                 createUser·p0.9999: 15.742 ms/op
                 createUser·p1.00:   16.253 ms/op

Iteration   2: 2.964 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.383 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  6.963 ms/op
                 createUser·p0.9999: 15.001 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   3: 2.965 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.547 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  9.141 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323696
  mean =      2.965 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31414 
    [ 2.500,  5.000) = 291347 
    [ 5.000,  7.500) = 664 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.089 ms/op
     p(99.9900) =     24.105 ms/op
     p(99.9990) =     26.453 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 3.893 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.006 ms/op
Iteration   1: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.157 ms/op
                 existUser·p0.9999: 11.616 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   2: 2.848 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  6.581 ms/op
                 existUser·p0.9999: 25.559 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 2.894 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  5.910 ms/op
                 existUser·p0.9999: 15.990 ms/op
                 existUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332875
  mean =      2.882 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44378 
    [ 2.500,  5.000) = 287422 
    [ 5.000,  7.500) = 874 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.399 ms/op
     p(99.9900) =     16.370 ms/op
     p(99.9990) =     26.400 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.755 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.307 ms/op
                 getUser·p0.9999: 13.143 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   2: 2.969 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.715 ms/op
                 getUser·p0.9999: 17.637 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.527 ms/op
                 getUser·p0.9999: 17.770 ms/op
                 getUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322580
  mean =      2.975 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1681 
    [ 1.250,  2.500) = 28919 
    [ 2.500,  3.750) = 277047 
    [ 3.750,  5.000) = 13943 
    [ 5.000,  6.250) = 426 
    [ 6.250,  7.500) = 283 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.250 ms/op
     p(99.9900) =     17.350 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 4.809 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.010 ms/op
Iteration   1: 3.945 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.714 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  12.893 ms/op
                 listUser·p0.9999: 14.329 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 3.901 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  14.992 ms/op
                 listUser·p0.9999: 16.197 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   3: 3.914 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.338 ms/op
                 listUser·p0.9999: 19.125 ms/op
                 listUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244869
  mean =      3.920 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4173 
    [ 2.500,  5.000) = 219183 
    [ 5.000,  7.500) = 20012 
    [ 7.500, 10.000) = 879 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.322 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     21.051 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.482 ± 2.808  ops/ms
ClientGrpc.existUser                       thrpt       3  11.201 ± 4.530  ops/ms
ClientGrpc.getUser                         thrpt       3  10.803 ± 1.672  ops/ms
ClientGrpc.listUser                        thrpt       3   8.331 ± 1.503  ops/ms
ClientGrpc.createUser                       avgt       3   2.980 ± 0.949   ms/op
ClientGrpc.existUser                        avgt       3   2.837 ± 0.291   ms/op
ClientGrpc.getUser                          avgt       3   2.998 ± 0.591   ms/op
ClientGrpc.listUser                         avgt       3   3.838 ± 0.436   ms/op
ClientGrpc.createUser                     sample  323696   2.965 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.383           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.449           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.089           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.105           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.542           ms/op
ClientGrpc.existUser                      sample  332875   2.882 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.532           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.399           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.370           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.542           ms/op
ClientGrpc.getUser                        sample  322580   2.975 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.659           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.250           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.350           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.842           ms/op
ClientGrpc.listUser                       sample  244869   3.920 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.714           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.322           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.776           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.299           ms/op
