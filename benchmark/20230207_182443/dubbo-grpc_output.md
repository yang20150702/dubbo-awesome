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
# Warmup Iteration   1: 4.604 ops/ms
# Warmup Iteration   2: 9.322 ops/ms
# Warmup Iteration   3: 10.143 ops/ms
Iteration   1: 10.232 ops/ms
Iteration   2: 10.167 ops/ms
Iteration   3: 10.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.244 ±(99.9%) 1.528 ops/ms [Average]
  (min, avg, max) = (10.167, 10.244, 10.333), stdev = 0.084
  CI (99.9%): [8.716, 11.772] (assumes normal distribution)


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
# Warmup Iteration   1: 7.827 ops/ms
# Warmup Iteration   2: 10.924 ops/ms
# Warmup Iteration   3: 10.660 ops/ms
Iteration   1: 10.753 ops/ms
Iteration   2: 10.746 ops/ms
Iteration   3: 11.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.841 ±(99.9%) 2.890 ops/ms [Average]
  (min, avg, max) = (10.746, 10.841, 11.024), stdev = 0.158
  CI (99.9%): [7.951, 13.731] (assumes normal distribution)


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
# Warmup Iteration   1: 7.244 ops/ms
# Warmup Iteration   2: 10.329 ops/ms
# Warmup Iteration   3: 10.646 ops/ms
Iteration   1: 10.406 ops/ms
Iteration   2: 10.200 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.387 ±(99.9%) 3.240 ops/ms [Average]
  (min, avg, max) = (10.200, 10.387, 10.554), stdev = 0.178
  CI (99.9%): [7.146, 13.627] (assumes normal distribution)


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
# Warmup Iteration   1: 6.048 ops/ms
# Warmup Iteration   2: 7.924 ops/ms
# Warmup Iteration   3: 8.121 ops/ms
Iteration   1: 7.776 ops/ms
Iteration   2: 8.124 ops/ms
Iteration   3: 7.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.964 ±(99.9%) 3.213 ops/ms [Average]
  (min, avg, max) = (7.776, 7.964, 8.124), stdev = 0.176
  CI (99.9%): [4.751, 11.178] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.008 ms/op
Iteration   1: 3.097 ±(99.9%) 0.002 ms/op
Iteration   2: 3.007 ±(99.9%) 0.003 ms/op
Iteration   3: 3.129 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.078 ±(99.9%) 1.153 ms/op [Average]
  (min, avg, max) = (3.007, 3.078, 3.129), stdev = 0.063
  CI (99.9%): [1.925, 4.231] (assumes normal distribution)


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.002 ms/op
Iteration   1: 2.955 ±(99.9%) 0.002 ms/op
Iteration   2: 3.017 ±(99.9%) 0.002 ms/op
Iteration   3: 2.878 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.950 ±(99.9%) 1.275 ms/op [Average]
  (min, avg, max) = (2.878, 2.950, 3.017), stdev = 0.070
  CI (99.9%): [1.675, 4.225] (assumes normal distribution)


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
# Warmup Iteration   1: 3.946 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.001 ms/op
Iteration   1: 3.121 ±(99.9%) 0.007 ms/op
Iteration   2: 3.171 ±(99.9%) 0.002 ms/op
Iteration   3: 3.156 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.149 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (3.121, 3.149, 3.171), stdev = 0.025
  CI (99.9%): [2.688, 3.610] (assumes normal distribution)


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
# Warmup Iteration   1: 4.650 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.011 ms/op
Iteration   1: 4.048 ±(99.9%) 0.023 ms/op
Iteration   2: 4.014 ±(99.9%) 0.009 ms/op
Iteration   3: 4.053 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.038 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (4.014, 4.038, 4.053), stdev = 0.021
  CI (99.9%): [3.654, 4.423] (assumes normal distribution)


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
# Warmup Iteration   1: 4.198 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 3.183 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.419 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  8.066 ms/op
                 createUser·p0.9999: 11.860 ms/op
                 createUser·p1.00:   12.255 ms/op

Iteration   2: 3.048 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.137 ms/op
                 createUser·p0.999:  7.947 ms/op
                 createUser·p0.9999: 12.902 ms/op
                 createUser·p1.00:   13.222 ms/op

Iteration   3: 3.198 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.526 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  11.469 ms/op
                 createUser·p0.9999: 15.237 ms/op
                 createUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305586
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 810 
    [ 1.250,  2.500) = 20186 
    [ 2.500,  3.750) = 247290 
    [ 3.750,  5.000) = 36383 
    [ 5.000,  6.250) = 310 
    [ 6.250,  7.500) = 219 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.419 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =     10.834 ms/op
     p(99.9900) =     14.449 ms/op
     p(99.9990) =     16.495 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 3.854 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.007 ms/op
Iteration   1: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  8.152 ms/op
                 existUser·p0.9999: 11.485 ms/op
                 existUser·p1.00:   11.829 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  5.673 ms/op
                 existUser·p0.9999: 14.074 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.981 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  8.106 ms/op
                 existUser·p0.9999: 21.743 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322734
  mean =      2.973 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42335 
    [ 2.500,  5.000) = 279482 
    [ 5.000,  7.500) = 561 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.740 ms/op
     p(99.9900) =     19.295 ms/op
     p(99.9990) =     22.005 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
Iteration   1: 3.101 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.523 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  9.926 ms/op
                 getUser·p0.9999: 11.436 ms/op
                 getUser·p1.00:   11.698 ms/op

Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  11.354 ms/op
                 getUser·p0.9999: 13.722 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  5.630 ms/op
                 getUser·p0.9999: 14.663 ms/op
                 getUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310192
  mean =      3.094 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 875 
    [ 1.250,  2.500) = 22385 
    [ 2.500,  3.750) = 261150 
    [ 3.750,  5.000) = 24932 
    [ 5.000,  6.250) = 341 
    [ 6.250,  7.500) = 206 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.345 ms/op
     p(99.9900) =     13.778 ms/op
     p(99.9990) =     14.939 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.173 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.011 ms/op
Iteration   1: 3.916 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  15.744 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   2: 3.979 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.723 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.915 ms/op
                 listUser·p0.9999: 21.786 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   3: 3.923 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.626 ms/op
                 listUser·p0.999:  14.016 ms/op
                 listUser·p0.9999: 19.154 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243566
  mean =      3.939 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3816 
    [ 2.500,  5.000) = 216308 
    [ 5.000,  7.500) = 22445 
    [ 7.500, 10.000) = 563 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.663 ms/op
     p(99.9000) =     14.294 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     22.207 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.244 ± 1.528  ops/ms
ClientGrpc.existUser                       thrpt       3  10.841 ± 2.890  ops/ms
ClientGrpc.getUser                         thrpt       3  10.387 ± 3.240  ops/ms
ClientGrpc.listUser                        thrpt       3   7.964 ± 3.213  ops/ms
ClientGrpc.createUser                       avgt       3   3.078 ± 1.153   ms/op
ClientGrpc.existUser                        avgt       3   2.950 ± 1.275   ms/op
ClientGrpc.getUser                          avgt       3   3.149 ± 0.461   ms/op
ClientGrpc.listUser                         avgt       3   4.038 ± 0.384   ms/op
ClientGrpc.createUser                     sample  305586   3.141 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.419           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.998           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.834           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.449           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.646           ms/op
ClientGrpc.existUser                      sample  322734   2.973 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.556           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.740           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.295           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.086           ms/op
ClientGrpc.getUser                        sample  310192   3.094 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.523           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.345           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.778           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.106           ms/op
ClientGrpc.listUser                       sample  243566   3.939 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.723           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.663           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.294           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.316           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.412           ms/op
