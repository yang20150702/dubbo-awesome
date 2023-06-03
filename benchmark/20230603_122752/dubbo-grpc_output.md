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
# Warmup Iteration   1: 4.264 ops/ms
# Warmup Iteration   2: 8.945 ops/ms
# Warmup Iteration   3: 9.939 ops/ms
Iteration   1: 10.424 ops/ms
Iteration   2: 10.537 ops/ms
Iteration   3: 10.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.532 ±(99.9%) 1.941 ops/ms [Average]
  (min, avg, max) = (10.424, 10.532, 10.636), stdev = 0.106
  CI (99.9%): [8.591, 12.473] (assumes normal distribution)


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
# Warmup Iteration   1: 7.496 ops/ms
# Warmup Iteration   2: 10.194 ops/ms
# Warmup Iteration   3: 10.712 ops/ms
Iteration   1: 11.100 ops/ms
Iteration   2: 10.931 ops/ms
Iteration   3: 10.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.953 ±(99.9%) 2.495 ops/ms [Average]
  (min, avg, max) = (10.829, 10.953, 11.100), stdev = 0.137
  CI (99.9%): [8.458, 13.448] (assumes normal distribution)


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
# Warmup Iteration   1: 6.668 ops/ms
# Warmup Iteration   2: 10.041 ops/ms
# Warmup Iteration   3: 10.207 ops/ms
Iteration   1: 10.299 ops/ms
Iteration   2: 10.463 ops/ms
Iteration   3: 10.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.424 ±(99.9%) 2.031 ops/ms [Average]
  (min, avg, max) = (10.299, 10.424, 10.511), stdev = 0.111
  CI (99.9%): [8.394, 12.455] (assumes normal distribution)


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
# Warmup Iteration   1: 5.064 ops/ms
# Warmup Iteration   2: 7.285 ops/ms
# Warmup Iteration   3: 7.685 ops/ms
Iteration   1: 7.834 ops/ms
Iteration   2: 7.634 ops/ms
Iteration   3: 7.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.701 ±(99.9%) 2.100 ops/ms [Average]
  (min, avg, max) = (7.634, 7.701, 7.834), stdev = 0.115
  CI (99.9%): [5.601, 9.801] (assumes normal distribution)


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
# Warmup Iteration   1: 4.669 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.002 ms/op
Iteration   1: 3.118 ±(99.9%) 0.001 ms/op
Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
Iteration   3: 3.104 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.120 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (3.104, 3.120, 3.138), stdev = 0.017
  CI (99.9%): [2.809, 3.431] (assumes normal distribution)


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.002 ms/op
Iteration   1: 2.943 ±(99.9%) 0.002 ms/op
Iteration   2: 2.945 ±(99.9%) 0.003 ms/op
Iteration   3: 2.904 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.931 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (2.904, 2.931, 2.945), stdev = 0.023
  CI (99.9%): [2.515, 3.346] (assumes normal distribution)


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
# Warmup Iteration   1: 4.433 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.002 ms/op
Iteration   1: 3.116 ±(99.9%) 0.003 ms/op
Iteration   2: 3.160 ±(99.9%) 0.003 ms/op
Iteration   3: 3.151 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.143 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.116, 3.143, 3.160), stdev = 0.023
  CI (99.9%): [2.719, 3.566] (assumes normal distribution)


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
# Warmup Iteration   1: 6.061 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.009 ms/op
Iteration   1: 4.167 ±(99.9%) 0.019 ms/op
Iteration   2: 4.153 ±(99.9%) 0.012 ms/op
Iteration   3: 4.124 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.148 ±(99.9%) 0.397 ms/op [Average]
  (min, avg, max) = (4.124, 4.148, 4.167), stdev = 0.022
  CI (99.9%): [3.751, 4.544] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.304 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  6.963 ms/op
                 createUser·p0.9999: 20.223 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.134 ms/op
                 createUser·p0.9999: 26.659 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.559 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  12.988 ms/op
                 createUser·p0.9999: 23.642 ms/op
                 createUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313710
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15441 
    [ 2.500,  5.000) = 296869 
    [ 5.000,  7.500) = 1020 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.808 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     26.964 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.156 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.005 ms/op
Iteration   1: 2.910 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  6.786 ms/op
                 existUser·p0.9999: 13.845 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 2.940 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.597 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  9.099 ms/op
                 existUser·p0.9999: 15.239 ms/op
                 existUser·p1.00:   15.811 ms/op

Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  11.786 ms/op
                 existUser·p0.9999: 17.630 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328356
  mean =      2.923 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1560 
    [ 1.250,  2.500) = 36876 
    [ 2.500,  3.750) = 279692 
    [ 3.750,  5.000) = 8713 
    [ 5.000,  6.250) = 696 
    [ 6.250,  7.500) = 339 
    [ 7.500,  8.750) = 133 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.476 ms/op
     p(99.9000) =      9.480 ms/op
     p(99.9900) =     17.176 ms/op
     p(99.9990) =     17.840 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.112 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.724 ms/op
                 getUser·p0.999:  7.826 ms/op
                 getUser·p0.9999: 13.475 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  6.875 ms/op
                 getUser·p0.9999: 15.024 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   3: 3.087 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.757 ms/op
                 getUser·p0.9999: 18.141 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309903
  mean =      3.098 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15631 
    [ 2.500,  5.000) = 292262 
    [ 5.000,  7.500) = 1720 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      7.350 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     21.374 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 5.429 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.242 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.011 ms/op
Iteration   1: 4.094 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  13.728 ms/op
                 listUser·p0.9999: 15.811 ms/op
                 listUser·p1.00:   16.155 ms/op

Iteration   2: 4.108 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.090 ms/op
                 listUser·p0.999:  14.453 ms/op
                 listUser·p0.9999: 20.986 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.122 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  16.080 ms/op
                 listUser·p0.9999: 26.321 ms/op
                 listUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233553
  mean =      4.108 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1713 
    [ 2.500,  5.000) = 208237 
    [ 5.000,  7.500) = 22013 
    [ 7.500, 10.000) = 1047 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     14.369 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     26.629 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.532 ± 1.941  ops/ms
ClientGrpc.existUser                       thrpt       3  10.953 ± 2.495  ops/ms
ClientGrpc.getUser                         thrpt       3  10.424 ± 2.031  ops/ms
ClientGrpc.listUser                        thrpt       3   7.701 ± 2.100  ops/ms
ClientGrpc.createUser                       avgt       3   3.120 ± 0.311   ms/op
ClientGrpc.existUser                        avgt       3   2.931 ± 0.416   ms/op
ClientGrpc.getUser                          avgt       3   3.143 ± 0.423   ms/op
ClientGrpc.listUser                         avgt       3   4.148 ± 0.397   ms/op
ClientGrpc.createUser                     sample  313710   3.060 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.559           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.808           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.231           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.066           ms/op
ClientGrpc.existUser                      sample  328356   2.923 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.606           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.476           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.480           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.176           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  309903   3.098 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.742           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.350           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.170           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.478           ms/op
ClientGrpc.listUser                       sample  233553   4.108 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.873           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.957           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.369           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.133           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.673           ms/op
