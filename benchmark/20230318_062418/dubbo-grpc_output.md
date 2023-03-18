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
# Warmup Iteration   1: 4.299 ops/ms
# Warmup Iteration   2: 9.256 ops/ms
# Warmup Iteration   3: 10.336 ops/ms
Iteration   1: 10.892 ops/ms
Iteration   2: 10.830 ops/ms
Iteration   3: 10.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.764 ±(99.9%) 3.125 ops/ms [Average]
  (min, avg, max) = (10.569, 10.764, 10.892), stdev = 0.171
  CI (99.9%): [7.639, 13.889] (assumes normal distribution)


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
# Warmup Iteration   1: 8.941 ops/ms
# Warmup Iteration   2: 10.727 ops/ms
# Warmup Iteration   3: 11.146 ops/ms
Iteration   1: 11.190 ops/ms
Iteration   2: 11.374 ops/ms
Iteration   3: 11.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.251 ±(99.9%) 1.940 ops/ms [Average]
  (min, avg, max) = (11.189, 11.251, 11.374), stdev = 0.106
  CI (99.9%): [9.311, 13.191] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.489 ops/ms
# Warmup Iteration   2: 10.348 ops/ms
# Warmup Iteration   3: 10.698 ops/ms
Iteration   1: 10.706 ops/ms
Iteration   2: 10.642 ops/ms
Iteration   3: 10.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.707 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (10.642, 10.707, 10.771), stdev = 0.064
  CI (99.9%): [9.531, 11.882] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.570 ops/ms
# Warmup Iteration   2: 8.010 ops/ms
# Warmup Iteration   3: 8.205 ops/ms
Iteration   1: 8.332 ops/ms
Iteration   2: 8.067 ops/ms
Iteration   3: 8.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.143 ±(99.9%) 3.014 ops/ms [Average]
  (min, avg, max) = (8.029, 8.143, 8.332), stdev = 0.165
  CI (99.9%): [5.129, 11.157] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.003 ms/op
Iteration   1: 3.022 ±(99.9%) 0.003 ms/op
Iteration   2: 2.960 ±(99.9%) 0.004 ms/op
Iteration   3: 2.987 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.990 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (2.960, 2.990, 3.022), stdev = 0.031
  CI (99.9%): [2.421, 3.558] (assumes normal distribution)


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
# Warmup Iteration   1: 3.763 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.869 ±(99.9%) 0.003 ms/op
Iteration   1: 2.885 ±(99.9%) 0.004 ms/op
Iteration   2: 2.880 ±(99.9%) 0.004 ms/op
Iteration   3: 2.875 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.880 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.875, 2.880, 2.885), stdev = 0.005
  CI (99.9%): [2.788, 2.972] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.002 ms/op
Iteration   1: 2.970 ±(99.9%) 0.003 ms/op
Iteration   2: 2.973 ±(99.9%) 0.003 ms/op
Iteration   3: 2.967 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.970 ±(99.9%) 0.055 ms/op [Average]
  (min, avg, max) = (2.967, 2.970, 2.973), stdev = 0.003
  CI (99.9%): [2.915, 3.025] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.064 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.008 ms/op
Iteration   1: 3.945 ±(99.9%) 0.029 ms/op
Iteration   2: 3.873 ±(99.9%) 0.011 ms/op
Iteration   3: 3.881 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.900 ±(99.9%) 0.720 ms/op [Average]
  (min, avg, max) = (3.873, 3.900, 3.945), stdev = 0.039
  CI (99.9%): [3.179, 4.620] (assumes normal distribution)


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.006 ms/op
Iteration   1: 2.968 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.492 ms/op
                 createUser·p0.999:  8.355 ms/op
                 createUser·p0.9999: 15.867 ms/op
                 createUser·p1.00:   16.286 ms/op

Iteration   2: 2.981 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.758 ms/op
                 createUser·p0.9999: 13.521 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   3: 2.971 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.217 ms/op
                 createUser·p0.9999: 25.002 ms/op
                 createUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322963
  mean =      2.973 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32973 
    [ 2.500,  5.000) = 288618 
    [ 5.000,  7.500) = 961 
    [ 7.500, 10.000) = 182 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.020 ms/op
     p(99.9900) =     23.872 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 3.677 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.911 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.844 ±(99.9%) 0.006 ms/op
Iteration   1: 2.782 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.414 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  5.866 ms/op
                 existUser·p0.9999: 10.977 ms/op
                 existUser·p1.00:   11.305 ms/op

Iteration   2: 2.824 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  5.534 ms/op
                 existUser·p0.9999: 12.725 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   3: 2.750 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.798 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.508 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  9.967 ms/op
                 existUser·p0.9999: 17.051 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 344509
  mean =      2.785 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7399 
    [ 1.250,  2.500) = 54421 
    [ 2.500,  3.750) = 274135 
    [ 3.750,  5.000) = 7746 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 146 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.453 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.836 ms/op
     p(99.9900) =     14.107 ms/op
     p(99.9990) =     18.681 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.560 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.190 ms/op
                 getUser·p0.9999: 11.862 ms/op
                 getUser·p1.00:   11.993 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.255 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  9.426 ms/op
                 getUser·p0.9999: 12.587 ms/op
                 getUser·p1.00:   13.238 ms/op

Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.643 ms/op
                 getUser·p0.9999: 26.853 ms/op
                 getUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318870
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25813 
    [ 2.500,  5.000) = 291438 
    [ 5.000,  7.500) = 1308 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.255 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.464 ms/op
     p(99.9900) =     25.308 ms/op
     p(99.9990) =     27.126 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 4.597 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.010 ms/op
Iteration   1: 3.928 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.880 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  13.894 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 3.909 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.685 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  18.586 ms/op
                 listUser·p0.9999: 21.070 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 3.923 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 17.319 ms/op
                 listUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244842
  mean =      3.920 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6927 
    [ 2.500,  5.000) = 213728 
    [ 5.000,  7.500) = 22990 
    [ 7.500, 10.000) = 755 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     22.707 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.764 ± 3.125  ops/ms
ClientGrpc.existUser                       thrpt       3  11.251 ± 1.940  ops/ms
ClientGrpc.getUser                         thrpt       3  10.707 ± 1.175  ops/ms
ClientGrpc.listUser                        thrpt       3   8.143 ± 3.014  ops/ms
ClientGrpc.createUser                       avgt       3   2.990 ± 0.568   ms/op
ClientGrpc.existUser                        avgt       3   2.880 ± 0.092   ms/op
ClientGrpc.getUser                          avgt       3   2.970 ± 0.055   ms/op
ClientGrpc.listUser                         avgt       3   3.900 ± 0.720   ms/op
ClientGrpc.createUser                     sample  322963   2.973 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.697           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.020           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.872           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.297           ms/op
ClientGrpc.existUser                      sample  344509   2.785 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.603           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.830           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.265           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.836           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.107           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.842           ms/op
ClientGrpc.getUser                        sample  318870   3.010 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.255           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.464           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.308           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.230           ms/op
ClientGrpc.listUser                       sample  244842   3.920 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.685           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.368           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.808           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.872           ms/op
