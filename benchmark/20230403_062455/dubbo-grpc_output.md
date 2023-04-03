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
# Warmup Iteration   1: 3.320 ops/ms
# Warmup Iteration   2: 6.699 ops/ms
# Warmup Iteration   3: 8.458 ops/ms
Iteration   1: 8.756 ops/ms
Iteration   2: 8.722 ops/ms
Iteration   3: 8.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.779 ±(99.9%) 1.311 ops/ms [Average]
  (min, avg, max) = (8.722, 8.779, 8.860), stdev = 0.072
  CI (99.9%): [7.468, 10.090] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.812 ops/ms
# Warmup Iteration   2: 8.627 ops/ms
# Warmup Iteration   3: 9.499 ops/ms
Iteration   1: 9.287 ops/ms
Iteration   2: 9.261 ops/ms
Iteration   3: 9.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.268 ±(99.9%) 0.319 ops/ms [Average]
  (min, avg, max) = (9.254, 9.268, 9.287), stdev = 0.017
  CI (99.9%): [8.949, 9.586] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.466 ops/ms
# Warmup Iteration   2: 8.376 ops/ms
# Warmup Iteration   3: 8.761 ops/ms
Iteration   1: 8.769 ops/ms
Iteration   2: 8.809 ops/ms
Iteration   3: 8.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.783 ±(99.9%) 0.405 ops/ms [Average]
  (min, avg, max) = (8.769, 8.783, 8.809), stdev = 0.022
  CI (99.9%): [8.378, 9.188] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.983 ops/ms
# Warmup Iteration   2: 6.163 ops/ms
# Warmup Iteration   3: 6.816 ops/ms
Iteration   1: 6.710 ops/ms
Iteration   2: 6.725 ops/ms
Iteration   3: 6.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.756 ±(99.9%) 1.225 ops/ms [Average]
  (min, avg, max) = (6.710, 6.756, 6.833), stdev = 0.067
  CI (99.9%): [5.531, 7.980] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.557 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.015 ms/op
Iteration   1: 3.611 ±(99.9%) 0.003 ms/op
Iteration   2: 3.616 ±(99.9%) 0.003 ms/op
Iteration   3: 3.577 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.601 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (3.577, 3.601, 3.616), stdev = 0.021
  CI (99.9%): [3.213, 3.990] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.946 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.003 ms/op
Iteration   1: 3.495 ±(99.9%) 0.003 ms/op
Iteration   2: 3.404 ±(99.9%) 0.003 ms/op
Iteration   3: 3.505 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.468 ±(99.9%) 1.017 ms/op [Average]
  (min, avg, max) = (3.404, 3.468, 3.505), stdev = 0.056
  CI (99.9%): [2.451, 4.486] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.428 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.003 ms/op
Iteration   1: 3.675 ±(99.9%) 0.004 ms/op
Iteration   2: 3.619 ±(99.9%) 0.005 ms/op
Iteration   3: 3.709 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.667 ±(99.9%) 0.827 ms/op [Average]
  (min, avg, max) = (3.619, 3.667, 3.709), stdev = 0.045
  CI (99.9%): [2.840, 4.495] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.830 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.031 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.840 ±(99.9%) 0.016 ms/op
Iteration   1: 4.770 ±(99.9%) 0.009 ms/op
Iteration   2: 4.722 ±(99.9%) 0.010 ms/op
Iteration   3: 4.701 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.731 ±(99.9%) 0.642 ms/op [Average]
  (min, avg, max) = (4.701, 4.731, 4.770), stdev = 0.035
  CI (99.9%): [4.089, 5.373] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.469 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.008 ms/op
Iteration   1: 3.665 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  9.183 ms/op
                 createUser·p0.9999: 20.194 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   2: 3.595 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  8.300 ms/op
                 createUser·p0.9999: 24.478 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   3: 3.617 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  18.802 ms/op
                 createUser·p0.9999: 22.488 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264812
  mean =      3.625 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7515 
    [ 2.500,  5.000) = 252005 
    [ 5.000,  7.500) = 4732 
    [ 7.500, 10.000) = 319 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.620 ms/op
     p(99.9900) =     23.496 ms/op
     p(99.9990) =     24.917 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.152 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.009 ms/op
Iteration   1: 3.518 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  7.991 ms/op
                 existUser·p0.9999: 14.744 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   2: 3.433 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  7.410 ms/op
                 existUser·p0.9999: 14.539 ms/op
                 existUser·p1.00:   16.351 ms/op

Iteration   3: 3.481 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  12.157 ms/op
                 existUser·p0.9999: 18.180 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275962
  mean =      3.477 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 261 
    [ 1.250,  2.500) = 6898 
    [ 2.500,  3.750) = 210854 
    [ 3.750,  5.000) = 54732 
    [ 5.000,  6.250) = 2431 
    [ 6.250,  7.500) = 400 
    [ 7.500,  8.750) = 180 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.148 ms/op
     p(99.9000) =      8.126 ms/op
     p(99.9900) =     17.269 ms/op
     p(99.9990) =     18.497 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.197 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.010 ms/op
Iteration   1: 3.619 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  7.607 ms/op
                 getUser·p0.9999: 16.200 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 3.642 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.556 ms/op
                 getUser·p0.999:  8.765 ms/op
                 getUser·p0.9999: 25.926 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   3: 3.644 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  9.634 ms/op
                 getUser·p0.9999: 17.702 ms/op
                 getUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263994
  mean =      3.635 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5179 
    [ 2.500,  5.000) = 253567 
    [ 5.000,  7.500) = 4769 
    [ 7.500, 10.000) = 292 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     24.989 ms/op
     p(99.9990) =     26.161 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 6.014 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.399 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.790 ±(99.9%) 0.014 ms/op
Iteration   1: 4.696 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.556 ms/op
                 listUser·p0.99:   8.102 ms/op
                 listUser·p0.999:  16.166 ms/op
                 listUser·p0.9999: 22.629 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   2: 4.722 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.013 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  19.624 ms/op
                 listUser·p0.9999: 23.739 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   3: 4.696 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 26.143 ms/op
                 listUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203990
  mean =      4.705 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 263 
    [ 2.500,  5.000) = 163246 
    [ 5.000,  7.500) = 36412 
    [ 7.500, 10.000) = 3534 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.504 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     18.154 ms/op
     p(99.9900) =     24.497 ms/op
     p(99.9990) =     26.833 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.779 ± 1.311  ops/ms
ClientGrpc.existUser                       thrpt       3   9.268 ± 0.319  ops/ms
ClientGrpc.getUser                         thrpt       3   8.783 ± 0.405  ops/ms
ClientGrpc.listUser                        thrpt       3   6.756 ± 1.225  ops/ms
ClientGrpc.createUser                       avgt       3   3.601 ± 0.389   ms/op
ClientGrpc.existUser                        avgt       3   3.468 ± 1.017   ms/op
ClientGrpc.getUser                          avgt       3   3.667 ± 0.827   ms/op
ClientGrpc.listUser                         avgt       3   4.731 ± 0.642   ms/op
ClientGrpc.createUser                     sample  264812   3.625 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.884           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.554           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.620           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.496           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.068           ms/op
ClientGrpc.existUser                      sample  275962   3.477 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.667           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.965           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.148           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.126           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.269           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.842           ms/op
ClientGrpc.getUser                        sample  263994   3.635 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.872           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.620           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.634           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.989           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.214           ms/op
ClientGrpc.listUser                       sample  203990   4.705 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.865           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.538           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.504           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.154           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.497           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.903           ms/op
