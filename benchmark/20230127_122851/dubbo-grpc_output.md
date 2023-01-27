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
# Warmup Iteration   1: 5.167 ops/ms
# Warmup Iteration   2: 9.299 ops/ms
# Warmup Iteration   3: 10.389 ops/ms
Iteration   1: 10.500 ops/ms
Iteration   2: 10.180 ops/ms
Iteration   3: 10.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.237 ±(99.9%) 4.380 ops/ms [Average]
  (min, avg, max) = (10.031, 10.237, 10.500), stdev = 0.240
  CI (99.9%): [5.856, 14.617] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 7.963 ops/ms
# Warmup Iteration   2: 10.667 ops/ms
# Warmup Iteration   3: 11.299 ops/ms
Iteration   1: 10.742 ops/ms
Iteration   2: 10.810 ops/ms
Iteration   3: 10.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.815 ±(99.9%) 1.366 ops/ms [Average]
  (min, avg, max) = (10.742, 10.815, 10.892), stdev = 0.075
  CI (99.9%): [9.449, 12.180] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.465 ops/ms
# Warmup Iteration   2: 9.957 ops/ms
# Warmup Iteration   3: 10.465 ops/ms
Iteration   1: 10.382 ops/ms
Iteration   2: 10.382 ops/ms
Iteration   3: 10.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.474 ±(99.9%) 2.908 ops/ms [Average]
  (min, avg, max) = (10.382, 10.474, 10.658), stdev = 0.159
  CI (99.9%): [7.566, 13.382] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.069 ops/ms
# Warmup Iteration   2: 7.530 ops/ms
# Warmup Iteration   3: 7.854 ops/ms
Iteration   1: 7.951 ops/ms
Iteration   2: 8.048 ops/ms
Iteration   3: 8.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.058 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (7.951, 8.058, 8.175), stdev = 0.112
  CI (99.9%): [6.009, 10.107] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.003 ms/op
Iteration   1: 3.077 ±(99.9%) 0.003 ms/op
Iteration   2: 3.057 ±(99.9%) 0.002 ms/op
Iteration   3: 3.112 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.082 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.057, 3.082, 3.112), stdev = 0.028
  CI (99.9%): [2.572, 3.592] (assumes normal distribution)


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
# Warmup Iteration   1: 3.593 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.837 ±(99.9%) 0.003 ms/op
Iteration   1: 2.931 ±(99.9%) 0.003 ms/op
Iteration   2: 2.955 ±(99.9%) 0.002 ms/op
Iteration   3: 2.991 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.959 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (2.931, 2.959, 2.991), stdev = 0.031
  CI (99.9%): [2.402, 3.516] (assumes normal distribution)


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.002 ms/op
Iteration   1: 3.051 ±(99.9%) 0.002 ms/op
Iteration   2: 3.056 ±(99.9%) 0.003 ms/op
Iteration   3: 3.020 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (3.020, 3.043, 3.056), stdev = 0.020
  CI (99.9%): [2.687, 3.398] (assumes normal distribution)


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
# Warmup Iteration   1: 4.913 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.052 ms/op
Iteration   1: 4.076 ±(99.9%) 0.026 ms/op
Iteration   2: 3.984 ±(99.9%) 0.006 ms/op
Iteration   3: 3.984 ±(99.9%) 0.054 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.015 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (3.984, 4.015, 4.076), stdev = 0.053
  CI (99.9%): [3.040, 4.989] (assumes normal distribution)


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
Iteration   1: 3.108 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  6.423 ms/op
                 createUser·p0.9999: 11.726 ms/op
                 createUser·p1.00:   11.993 ms/op

Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.283 ms/op
                 createUser·p0.9999: 22.905 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   3: 3.127 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.368 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 14.128 ms/op
                 createUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307059
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24953 
    [ 2.500,  5.000) = 281397 
    [ 5.000,  7.500) = 489 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.511 ms/op
     p(99.9900) =     22.488 ms/op
     p(99.9990) =     24.291 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 3.751 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  8.220 ms/op
                 existUser·p0.9999: 11.918 ms/op
                 existUser·p1.00:   12.239 ms/op

Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  5.947 ms/op
                 existUser·p0.9999: 18.095 ms/op
                 existUser·p1.00:   19.038 ms/op

Iteration   3: 2.923 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.303 ms/op
                 existUser·p0.9999: 25.461 ms/op
                 existUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322601
  mean =      2.974 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47592 
    [ 2.500,  5.000) = 274130 
    [ 5.000,  7.500) = 584 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.947 ms/op
     p(99.9900) =     22.384 ms/op
     p(99.9990) =     25.772 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.547 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.870 ms/op
                 getUser·p0.9999: 12.500 ms/op
                 getUser·p1.00:   12.730 ms/op

Iteration   2: 3.126 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.132 ms/op
                 getUser·p0.9999: 12.403 ms/op
                 getUser·p1.00:   12.681 ms/op

Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.237 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.417 ms/op
                 getUser·p0.999:  6.545 ms/op
                 getUser·p0.9999: 26.281 ms/op
                 getUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312635
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25289 
    [ 2.500,  5.000) = 286419 
    [ 5.000,  7.500) = 693 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.237 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.838 ms/op
     p(99.9900) =     25.540 ms/op
     p(99.9990) =     26.468 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.637 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.063 ±(99.9%) 0.011 ms/op
Iteration   1: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.908 ms/op
                 listUser·p0.9999: 21.856 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   2: 3.873 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.746 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  15.702 ms/op
                 listUser·p0.9999: 25.190 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   3: 3.971 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.829 ms/op
                 listUser·p0.999:  15.105 ms/op
                 listUser·p0.9999: 25.719 ms/op
                 listUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243276
  mean =      3.945 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3410 
    [ 2.500,  5.000) = 218323 
    [ 5.000,  7.500) = 20391 
    [ 7.500, 10.000) = 672 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.856 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.237 ± 4.380  ops/ms
ClientGrpc.existUser                       thrpt       3  10.815 ± 1.366  ops/ms
ClientGrpc.getUser                         thrpt       3  10.474 ± 2.908  ops/ms
ClientGrpc.listUser                        thrpt       3   8.058 ± 2.049  ops/ms
ClientGrpc.createUser                       avgt       3   3.082 ± 0.510   ms/op
ClientGrpc.existUser                        avgt       3   2.959 ± 0.557   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.356   ms/op
ClientGrpc.listUser                         avgt       3   4.015 ± 0.975   ms/op
ClientGrpc.createUser                     sample  307059   3.125 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.368           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.511           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.488           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.625           ms/op
ClientGrpc.existUser                      sample  322601   2.974 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.537           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.826           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.947           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.384           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.018           ms/op
ClientGrpc.getUser                        sample  312635   3.071 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.237           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.903           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.838           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.540           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.542           ms/op
ClientGrpc.listUser                       sample  243276   3.945 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.746           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.856           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.362           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.051           ms/op
