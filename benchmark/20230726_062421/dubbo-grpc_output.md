# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.697 ops/ms
# Warmup Iteration   2: 8.702 ops/ms
# Warmup Iteration   3: 10.169 ops/ms
Iteration   1: 10.538 ops/ms
Iteration   2: 10.533 ops/ms
Iteration   3: 10.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.535 ±(99.9%) 0.051 ops/ms [Average]
  (min, avg, max) = (10.533, 10.535, 10.538), stdev = 0.003
  CI (99.9%): [10.483, 10.586] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.229 ops/ms
# Warmup Iteration   2: 9.970 ops/ms
# Warmup Iteration   3: 10.816 ops/ms
Iteration   1: 10.862 ops/ms
Iteration   2: 10.953 ops/ms
Iteration   3: 10.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.893 ±(99.9%) 0.955 ops/ms [Average]
  (min, avg, max) = (10.862, 10.893, 10.953), stdev = 0.052
  CI (99.9%): [9.937, 11.848] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.071 ops/ms
# Warmup Iteration   2: 10.069 ops/ms
# Warmup Iteration   3: 10.183 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.545 ±(99.9%) 1.085 ops/ms [Average]
  (min, avg, max) = (10.478, 10.545, 10.590), stdev = 0.059
  CI (99.9%): [9.461, 11.630] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.956 ops/ms
# Warmup Iteration   2: 7.693 ops/ms
# Warmup Iteration   3: 7.743 ops/ms
Iteration   1: 7.769 ops/ms
Iteration   2: 7.914 ops/ms
Iteration   3: 7.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.881 ±(99.9%) 1.817 ops/ms [Average]
  (min, avg, max) = (7.769, 7.881, 7.960), stdev = 0.100
  CI (99.9%): [6.064, 9.699] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.003 ms/op
Iteration   1: 3.172 ±(99.9%) 0.002 ms/op
Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
Iteration   3: 3.060 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.105 ±(99.9%) 1.084 ms/op [Average]
  (min, avg, max) = (3.060, 3.105, 3.172), stdev = 0.059
  CI (99.9%): [2.021, 4.189] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.670 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.002 ms/op
Iteration   1: 2.943 ±(99.9%) 0.002 ms/op
Iteration   2: 2.853 ±(99.9%) 0.003 ms/op
Iteration   3: 2.904 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.900 ±(99.9%) 0.827 ms/op [Average]
  (min, avg, max) = (2.853, 2.900, 2.943), stdev = 0.045
  CI (99.9%): [2.073, 3.727] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.428 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.004 ms/op
Iteration   1: 2.987 ±(99.9%) 0.003 ms/op
Iteration   2: 3.036 ±(99.9%) 0.004 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.010 ±(99.9%) 0.444 ms/op [Average]
  (min, avg, max) = (2.987, 3.010, 3.036), stdev = 0.024
  CI (99.9%): [2.565, 3.454] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.921 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.026 ms/op
Iteration   1: 4.018 ±(99.9%) 0.007 ms/op
Iteration   2: 4.002 ±(99.9%) 0.011 ms/op
Iteration   3: 4.059 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.026 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (4.002, 4.026, 4.059), stdev = 0.029
  CI (99.9%): [3.489, 4.563] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.327 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  6.513 ms/op
                 createUser·p0.9999: 21.409 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   2: 3.058 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.245 ms/op
                 createUser·p0.9999: 23.888 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 24.002 ms/op
                 createUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313726
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23067 
    [ 2.500,  5.000) = 289372 
    [ 5.000,  7.500) = 991 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.285 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     24.370 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.090 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
Iteration   1: 2.892 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   3.887 ms/op
                 existUser·p0.999:  6.608 ms/op
                 existUser·p0.9999: 13.303 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.921 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  6.352 ms/op
                 existUser·p0.9999: 18.448 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   3: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  10.987 ms/op
                 existUser·p0.9999: 18.451 ms/op
                 existUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329397
  mean =      2.915 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 916 
    [ 1.250,  2.500) = 35558 
    [ 2.500,  3.750) = 284334 
    [ 3.750,  5.000) = 7661 
    [ 5.000,  6.250) = 431 
    [ 6.250,  7.500) = 197 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 58 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      7.050 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     18.986 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.382 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.808 ms/op
                 getUser·p0.9999: 14.139 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.356 ms/op
                 getUser·p0.9999: 16.417 ms/op
                 getUser·p1.00:   16.630 ms/op

Iteration   3: 3.079 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  9.767 ms/op
                 getUser·p0.9999: 20.336 ms/op
                 getUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311807
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17840 
    [ 2.500,  5.000) = 292258 
    [ 5.000,  7.500) = 1353 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.697 ms/op
     p(99.9900) =     19.616 ms/op
     p(99.9990) =     20.632 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.684 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.332 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.013 ms/op
Iteration   1: 4.127 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  14.309 ms/op
                 listUser·p0.9999: 21.567 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   2: 4.122 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.370 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  16.704 ms/op
                 listUser·p0.9999: 23.404 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   3: 4.058 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.022 ms/op
                 listUser·p0.999:  22.158 ms/op
                 listUser·p0.9999: 25.465 ms/op
                 listUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234138
  mean =      4.102 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1738 
    [ 2.500,  5.000) = 205619 
    [ 5.000,  7.500) = 24928 
    [ 7.500, 10.000) = 1330 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     16.499 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     26.246 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.535 ± 0.051  ops/ms
ClientGrpc.existUser                       thrpt       3  10.893 ± 0.955  ops/ms
ClientGrpc.getUser                         thrpt       3  10.545 ± 1.085  ops/ms
ClientGrpc.listUser                        thrpt       3   7.881 ± 1.817  ops/ms
ClientGrpc.createUser                       avgt       3   3.105 ± 1.084   ms/op
ClientGrpc.existUser                        avgt       3   2.900 ± 0.827   ms/op
ClientGrpc.getUser                          avgt       3   3.010 ± 0.444   ms/op
ClientGrpc.listUser                         avgt       3   4.026 ± 0.537   ms/op
ClientGrpc.createUser                     sample  313726   3.060 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.736           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.285           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.658           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.642           ms/op
ClientGrpc.existUser                      sample  329397   2.915 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.742           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.050           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.219           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.137           ms/op
ClientGrpc.getUser                        sample  311807   3.078 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.812           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.697           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.616           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.103           ms/op
ClientGrpc.listUser                       sample  234138   4.102 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.370           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.242           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.499           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.068           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.411           ms/op
