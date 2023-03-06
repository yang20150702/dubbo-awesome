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
# Warmup Iteration   1: 4.912 ops/ms
# Warmup Iteration   2: 9.826 ops/ms
# Warmup Iteration   3: 10.261 ops/ms
Iteration   1: 10.573 ops/ms
Iteration   2: 10.111 ops/ms
Iteration   3: 10.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.286 ±(99.9%) 4.580 ops/ms [Average]
  (min, avg, max) = (10.111, 10.286, 10.573), stdev = 0.251
  CI (99.9%): [5.705, 14.866] (assumes normal distribution)


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
# Warmup Iteration   1: 8.109 ops/ms
# Warmup Iteration   2: 10.798 ops/ms
# Warmup Iteration   3: 11.003 ops/ms
Iteration   1: 10.894 ops/ms
Iteration   2: 11.113 ops/ms
Iteration   3: 10.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.988 ±(99.9%) 2.050 ops/ms [Average]
  (min, avg, max) = (10.894, 10.988, 11.113), stdev = 0.112
  CI (99.9%): [8.938, 13.038] (assumes normal distribution)


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
# Warmup Iteration   1: 7.655 ops/ms
# Warmup Iteration   2: 10.367 ops/ms
# Warmup Iteration   3: 10.285 ops/ms
Iteration   1: 10.154 ops/ms
Iteration   2: 10.380 ops/ms
Iteration   3: 10.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.302 ±(99.9%) 2.339 ops/ms [Average]
  (min, avg, max) = (10.154, 10.302, 10.380), stdev = 0.128
  CI (99.9%): [7.962, 12.641] (assumes normal distribution)


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
# Warmup Iteration   1: 5.968 ops/ms
# Warmup Iteration   2: 7.680 ops/ms
# Warmup Iteration   3: 7.754 ops/ms
Iteration   1: 8.269 ops/ms
Iteration   2: 8.112 ops/ms
Iteration   3: 8.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.151 ±(99.9%) 1.890 ops/ms [Average]
  (min, avg, max) = (8.073, 8.151, 8.269), stdev = 0.104
  CI (99.9%): [6.262, 10.041] (assumes normal distribution)


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
# Warmup Iteration   1: 4.156 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.002 ms/op
Iteration   1: 3.062 ±(99.9%) 0.003 ms/op
Iteration   2: 2.951 ±(99.9%) 0.002 ms/op
Iteration   3: 3.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.025 ±(99.9%) 1.171 ms/op [Average]
  (min, avg, max) = (2.951, 3.025, 3.063), stdev = 0.064
  CI (99.9%): [1.855, 4.196] (assumes normal distribution)


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
# Warmup Iteration   1: 3.679 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.002 ms/op
Iteration   1: 3.023 ±(99.9%) 0.002 ms/op
Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
Iteration   3: 2.933 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.989 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (2.933, 2.989, 3.023), stdev = 0.049
  CI (99.9%): [2.089, 3.890] (assumes normal distribution)


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.002 ms/op
Iteration   2: 3.116 ±(99.9%) 0.002 ms/op
Iteration   3: 3.053 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.082 ±(99.9%) 0.575 ms/op [Average]
  (min, avg, max) = (3.053, 3.082, 3.116), stdev = 0.032
  CI (99.9%): [2.506, 3.657] (assumes normal distribution)


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
# Warmup Iteration   1: 5.209 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.020 ms/op
Iteration   1: 3.948 ±(99.9%) 0.007 ms/op
Iteration   2: 4.004 ±(99.9%) 0.014 ms/op
Iteration   3: 3.831 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.928 ±(99.9%) 1.612 ms/op [Average]
  (min, avg, max) = (3.831, 3.928, 4.004), stdev = 0.088
  CI (99.9%): [2.316, 5.540] (assumes normal distribution)


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
# Warmup Iteration   1: 4.135 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  6.371 ms/op
                 createUser·p0.9999: 16.612 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.979 ms/op
                 createUser·p0.9999: 16.754 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   3: 2.974 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.430 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  10.835 ms/op
                 createUser·p0.9999: 19.071 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319824
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27441 
    [ 2.500,  5.000) = 291191 
    [ 5.000,  7.500) = 858 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.430 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.630 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     19.353 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.622 ms/op
                 existUser·p0.9999: 12.040 ms/op
                 existUser·p1.00:   12.534 ms/op

Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.460 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  10.178 ms/op
                 existUser·p0.9999: 13.436 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   3: 2.979 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  8.155 ms/op
                 existUser·p0.9999: 20.489 ms/op
                 existUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317606
  mean =      3.021 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42351 
    [ 2.500,  5.000) = 274403 
    [ 5.000,  7.500) = 507 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.805 ms/op
     p(99.9900) =     18.555 ms/op
     p(99.9990) =     20.894 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
Iteration   1: 3.145 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.534 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.171 ms/op
                 getUser·p0.9999: 12.105 ms/op
                 getUser·p1.00:   12.452 ms/op

Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.569 ms/op
                 getUser·p0.9999: 13.797 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.037 ms/op
                 getUser·p0.9999: 13.692 ms/op
                 getUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309242
  mean =      3.104 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1435 
    [ 1.250,  2.500) = 23933 
    [ 2.500,  3.750) = 253955 
    [ 3.750,  5.000) = 28799 
    [ 5.000,  6.250) = 515 
    [ 6.250,  7.500) = 323 
    [ 7.500,  8.750) = 112 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.428 ms/op
     p(99.9900) =     13.518 ms/op
     p(99.9990) =     14.151 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


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
# Warmup Iteration   1: 5.210 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.010 ms/op
Iteration   1: 4.004 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.925 ms/op
                 listUser·p0.999:  11.370 ms/op
                 listUser·p0.9999: 15.319 ms/op
                 listUser·p1.00:   15.958 ms/op

Iteration   2: 4.100 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.599 ms/op
                 listUser·p0.9999: 16.286 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 4.017 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 21.398 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237567
  mean =      4.040 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4333 
    [ 2.500,  5.000) = 201589 
    [ 5.000,  7.500) = 30234 
    [ 7.500, 10.000) = 892 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     13.622 ms/op
     p(99.9900) =     20.627 ms/op
     p(99.9990) =     21.578 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.286 ± 4.580  ops/ms
ClientGrpc.existUser                       thrpt       3  10.988 ± 2.050  ops/ms
ClientGrpc.getUser                         thrpt       3  10.302 ± 2.339  ops/ms
ClientGrpc.listUser                        thrpt       3   8.151 ± 1.890  ops/ms
ClientGrpc.createUser                       avgt       3   3.025 ± 1.171   ms/op
ClientGrpc.existUser                        avgt       3   2.989 ± 0.901   ms/op
ClientGrpc.getUser                          avgt       3   3.082 ± 0.575   ms/op
ClientGrpc.listUser                         avgt       3   3.928 ± 1.612   ms/op
ClientGrpc.createUser                     sample  319824   3.001 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.430           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.630           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.514           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.725           ms/op
ClientGrpc.existUser                      sample  317606   3.021 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.460           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.805           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.555           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.004           ms/op
ClientGrpc.getUser                        sample  309242   3.104 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.534           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.428           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.518           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.090           ms/op
ClientGrpc.listUser                       sample  237567   4.040 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.921           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.622           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.627           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.020           ms/op
