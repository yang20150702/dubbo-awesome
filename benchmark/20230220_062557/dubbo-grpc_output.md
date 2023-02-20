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
# Warmup Iteration   1: 4.726 ops/ms
# Warmup Iteration   2: 9.510 ops/ms
# Warmup Iteration   3: 10.785 ops/ms
Iteration   1: 11.051 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.709 ±(99.9%) 6.078 ops/ms [Average]
  (min, avg, max) = (10.385, 10.709, 11.051), stdev = 0.333
  CI (99.9%): [4.631, 16.788] (assumes normal distribution)


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
# Warmup Iteration   1: 7.814 ops/ms
# Warmup Iteration   2: 10.727 ops/ms
# Warmup Iteration   3: 11.063 ops/ms
Iteration   1: 11.044 ops/ms
Iteration   2: 11.088 ops/ms
Iteration   3: 11.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.084 ±(99.9%) 0.689 ops/ms [Average]
  (min, avg, max) = (11.044, 11.084, 11.119), stdev = 0.038
  CI (99.9%): [10.395, 11.773] (assumes normal distribution)


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
# Warmup Iteration   1: 7.446 ops/ms
# Warmup Iteration   2: 10.624 ops/ms
# Warmup Iteration   3: 10.882 ops/ms
Iteration   1: 10.510 ops/ms
Iteration   2: 10.698 ops/ms
Iteration   3: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.635 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (10.510, 10.635, 10.698), stdev = 0.108
  CI (99.9%): [8.662, 12.609] (assumes normal distribution)


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
# Warmup Iteration   1: 5.810 ops/ms
# Warmup Iteration   2: 7.770 ops/ms
# Warmup Iteration   3: 7.957 ops/ms
Iteration   1: 7.930 ops/ms
Iteration   2: 8.019 ops/ms
Iteration   3: 8.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.984 ±(99.9%) 0.870 ops/ms [Average]
  (min, avg, max) = (7.930, 7.984, 8.019), stdev = 0.048
  CI (99.9%): [7.114, 8.854] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.003 ms/op
Iteration   1: 3.133 ±(99.9%) 0.002 ms/op
Iteration   2: 3.132 ±(99.9%) 0.003 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.112 ±(99.9%) 0.636 ms/op [Average]
  (min, avg, max) = (3.072, 3.112, 3.133), stdev = 0.035
  CI (99.9%): [2.476, 3.749] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.004 ms/op
Iteration   1: 2.932 ±(99.9%) 0.003 ms/op
Iteration   2: 2.926 ±(99.9%) 0.002 ms/op
Iteration   3: 2.894 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.917 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (2.894, 2.917, 2.932), stdev = 0.021
  CI (99.9%): [2.540, 3.295] (assumes normal distribution)


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.002 ms/op
Iteration   1: 3.033 ±(99.9%) 0.003 ms/op
Iteration   2: 3.019 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.013 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.988, 3.013, 3.033), stdev = 0.023
  CI (99.9%): [2.587, 3.439] (assumes normal distribution)


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
# Warmup Iteration   1: 5.306 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.008 ms/op
Iteration   1: 4.026 ±(99.9%) 0.008 ms/op
Iteration   2: 3.919 ±(99.9%) 0.036 ms/op
Iteration   3: 4.038 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.994 ±(99.9%) 1.192 ms/op [Average]
  (min, avg, max) = (3.919, 3.994, 4.038), stdev = 0.065
  CI (99.9%): [2.803, 5.186] (assumes normal distribution)


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.008 ms/op
Iteration   1: 3.159 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  11.919 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  9.517 ms/op
                 createUser·p0.9999: 18.916 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.234 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.322 ms/op
                 createUser·p0.9999: 18.650 ms/op
                 createUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309079
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1288 
    [ 1.250,  2.500) = 22338 
    [ 2.500,  3.750) = 255280 
    [ 3.750,  5.000) = 28887 
    [ 5.000,  6.250) = 566 
    [ 6.250,  7.500) = 253 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 87 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.234 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =     10.038 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     19.134 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.931 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.006 ms/op
Iteration   1: 2.924 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  5.825 ms/op
                 existUser·p0.9999: 15.779 ms/op
                 existUser·p1.00:   16.138 ms/op

Iteration   2: 2.908 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.404 ms/op
                 existUser·p0.9999: 15.319 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   3: 2.893 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  5.414 ms/op
                 existUser·p0.9999: 19.329 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330225
  mean =      2.908 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3284 
    [ 1.250,  2.500) = 49950 
    [ 2.500,  3.750) = 262413 
    [ 3.750,  5.000) = 14114 
    [ 5.000,  6.250) = 251 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      5.489 ms/op
     p(99.9900) =     16.940 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.411 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  6.324 ms/op
                 getUser·p0.9999: 12.129 ms/op
                 getUser·p1.00:   12.419 ms/op

Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  5.997 ms/op
                 getUser·p0.9999: 13.823 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   3: 3.004 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.339 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.177 ms/op
                 getUser·p0.9999: 17.990 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316474
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3643 
    [ 1.250,  2.500) = 27506 
    [ 2.500,  3.750) = 258022 
    [ 3.750,  5.000) = 26550 
    [ 5.000,  6.250) = 459 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.339 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.169 ms/op
     p(99.9900) =     15.992 ms/op
     p(99.9990) =     18.214 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 4.657 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.012 ms/op
Iteration   1: 3.986 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.262 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  17.573 ms/op
                 listUser·p0.9999: 23.067 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   2: 3.947 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.650 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 22.803 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   3: 3.995 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.014 ms/op
                 listUser·p0.999:  12.354 ms/op
                 listUser·p0.9999: 24.281 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241344
  mean =      3.976 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6064 
    [ 2.500,  5.000) = 207201 
    [ 5.000,  7.500) = 26972 
    [ 7.500, 10.000) = 668 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.262 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.787 ms/op
     p(99.9000) =     14.996 ms/op
     p(99.9900) =     23.228 ms/op
     p(99.9990) =     24.595 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.709 ± 6.078  ops/ms
ClientGrpc.existUser                       thrpt       3  11.084 ± 0.689  ops/ms
ClientGrpc.getUser                         thrpt       3  10.635 ± 1.973  ops/ms
ClientGrpc.listUser                        thrpt       3   7.984 ± 0.870  ops/ms
ClientGrpc.createUser                       avgt       3   3.112 ± 0.636   ms/op
ClientGrpc.existUser                        avgt       3   2.917 ± 0.377   ms/op
ClientGrpc.getUser                          avgt       3   3.013 ± 0.426   ms/op
ClientGrpc.listUser                         avgt       3   3.994 ± 1.192   ms/op
ClientGrpc.createUser                     sample  309079   3.105 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.234           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.038           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.302           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.235           ms/op
ClientGrpc.existUser                      sample  330225   2.908 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.625           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.489           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.940           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  316474   3.035 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.339           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.169           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.992           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.317           ms/op
ClientGrpc.listUser                       sample  241344   3.976 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.262           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.787           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.996           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.228           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.740           ms/op
