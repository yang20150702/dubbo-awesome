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
# Warmup Iteration   1: 5.072 ops/ms
# Warmup Iteration   2: 9.555 ops/ms
# Warmup Iteration   3: 10.087 ops/ms
Iteration   1: 10.652 ops/ms
Iteration   2: 10.461 ops/ms
Iteration   3: 10.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.562 ±(99.9%) 1.749 ops/ms [Average]
  (min, avg, max) = (10.461, 10.562, 10.652), stdev = 0.096
  CI (99.9%): [8.813, 12.311] (assumes normal distribution)


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
# Warmup Iteration   1: 7.914 ops/ms
# Warmup Iteration   2: 10.901 ops/ms
# Warmup Iteration   3: 11.298 ops/ms
Iteration   1: 11.350 ops/ms
Iteration   2: 11.250 ops/ms
Iteration   3: 11.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.351 ±(99.9%) 1.852 ops/ms [Average]
  (min, avg, max) = (11.250, 11.351, 11.453), stdev = 0.102
  CI (99.9%): [9.499, 13.203] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.442 ops/ms
# Warmup Iteration   2: 10.326 ops/ms
# Warmup Iteration   3: 10.641 ops/ms
Iteration   1: 10.840 ops/ms
Iteration   2: 10.651 ops/ms
Iteration   3: 10.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.781 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (10.651, 10.781, 10.853), stdev = 0.113
  CI (99.9%): [8.724, 12.838] (assumes normal distribution)


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
# Warmup Iteration   1: 7.000 ops/ms
# Warmup Iteration   2: 7.969 ops/ms
# Warmup Iteration   3: 8.251 ops/ms
Iteration   1: 8.277 ops/ms
Iteration   2: 8.313 ops/ms
Iteration   3: 8.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.297 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (8.277, 8.297, 8.313), stdev = 0.019
  CI (99.9%): [7.957, 8.637] (assumes normal distribution)


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.004 ms/op
Iteration   1: 3.023 ±(99.9%) 0.003 ms/op
Iteration   2: 2.972 ±(99.9%) 0.003 ms/op
Iteration   3: 2.989 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.995 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (2.972, 2.995, 3.023), stdev = 0.026
  CI (99.9%): [2.526, 3.464] (assumes normal distribution)


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.002 ms/op
Iteration   1: 2.939 ±(99.9%) 0.002 ms/op
Iteration   2: 2.899 ±(99.9%) 0.004 ms/op
Iteration   3: 2.778 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.872 ±(99.9%) 1.530 ms/op [Average]
  (min, avg, max) = (2.778, 2.872, 2.939), stdev = 0.084
  CI (99.9%): [1.342, 4.403] (assumes normal distribution)


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.003 ms/op
Iteration   1: 2.968 ±(99.9%) 0.003 ms/op
Iteration   2: 3.024 ±(99.9%) 0.003 ms/op
Iteration   3: 2.972 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.988 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (2.968, 2.988, 3.024), stdev = 0.031
  CI (99.9%): [2.416, 3.560] (assumes normal distribution)


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
# Warmup Iteration   1: 4.487 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.007 ms/op
Iteration   1: 3.909 ±(99.9%) 0.035 ms/op
Iteration   2: 3.897 ±(99.9%) 0.044 ms/op
Iteration   3: 3.865 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.890 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (3.865, 3.890, 3.909), stdev = 0.023
  CI (99.9%): [3.474, 4.307] (assumes normal distribution)


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.968 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.564 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  6.171 ms/op
                 createUser·p0.9999: 21.168 ms/op
                 createUser·p1.00:   21.398 ms/op

Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.521 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  6.660 ms/op
                 createUser·p0.9999: 13.697 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.802 ms/op
                 createUser·p0.9999: 14.526 ms/op
                 createUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320428
  mean =      2.995 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27994 
    [ 2.500,  5.000) = 291540 
    [ 5.000,  7.500) = 565 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.575 ms/op
     p(99.9900) =     20.240 ms/op
     p(99.9990) =     21.325 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 3.659 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.863 ±(99.9%) 0.006 ms/op
Iteration   1: 2.869 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  5.612 ms/op
                 existUser·p0.9999: 13.746 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.841 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  5.769 ms/op
                 existUser·p0.9999: 12.218 ms/op
                 existUser·p1.00:   12.435 ms/op

Iteration   3: 2.870 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.462 ms/op
                 existUser·p0.9999: 14.856 ms/op
                 existUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335632
  mean =      2.860 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2828 
    [ 1.250,  2.500) = 52428 
    [ 2.500,  3.750) = 269292 
    [ 3.750,  5.000) = 10394 
    [ 5.000,  6.250) = 408 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      5.975 ms/op
     p(99.9900) =     14.439 ms/op
     p(99.9990) =     15.154 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.005 ms/op
Iteration   1: 2.961 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.978 ms/op
                 getUser·p0.9999: 13.392 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.574 ms/op
                 getUser·p0.9999: 15.802 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.083 ms/op
                 getUser·p0.9999: 14.951 ms/op
                 getUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322962
  mean =      2.971 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1699 
    [ 1.250,  2.500) = 29707 
    [ 2.500,  3.750) = 276279 
    [ 3.750,  5.000) = 13908 
    [ 5.000,  6.250) = 795 
    [ 6.250,  7.500) = 253 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.479 ms/op
     p(99.9900) =     15.101 ms/op
     p(99.9990) =     17.228 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 4.859 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.011 ms/op
Iteration   1: 3.873 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.512 ms/op
                 listUser·p0.9999: 14.151 ms/op
                 listUser·p1.00:   14.287 ms/op

Iteration   2: 3.893 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  12.789 ms/op
                 listUser·p0.9999: 16.419 ms/op
                 listUser·p1.00:   16.663 ms/op

Iteration   3: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.828 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  12.434 ms/op
                 listUser·p0.9999: 15.715 ms/op
                 listUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247871
  mean =      3.871 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 3961 
    [ 2.500,  3.750) = 117054 
    [ 3.750,  5.000) = 109834 
    [ 5.000,  6.250) = 12832 
    [ 6.250,  7.500) = 3295 
    [ 7.500,  8.750) = 360 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     12.501 ms/op
     p(99.9900) =     16.011 ms/op
     p(99.9990) =     16.961 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.562 ± 1.749  ops/ms
ClientGrpc.existUser                       thrpt       3  11.351 ± 1.852  ops/ms
ClientGrpc.getUser                         thrpt       3  10.781 ± 2.057  ops/ms
ClientGrpc.listUser                        thrpt       3   8.297 ± 0.340  ops/ms
ClientGrpc.createUser                       avgt       3   2.995 ± 0.469   ms/op
ClientGrpc.existUser                        avgt       3   2.872 ± 1.530   ms/op
ClientGrpc.getUser                          avgt       3   2.988 ± 0.572   ms/op
ClientGrpc.listUser                         avgt       3   3.890 ± 0.417   ms/op
ClientGrpc.createUser                     sample  320428   2.995 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.521           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.575           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.240           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.398           ms/op
ClientGrpc.existUser                      sample  335632   2.860 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.547           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.975           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.439           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.270           ms/op
ClientGrpc.getUser                        sample  322962   2.971 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.734           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.479           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.101           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.433           ms/op
ClientGrpc.listUser                       sample  247871   3.871 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.828           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.530           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.545           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.501           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.011           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          17.367           ms/op
