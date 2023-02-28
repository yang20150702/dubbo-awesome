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
# Warmup Iteration   1: 4.517 ops/ms
# Warmup Iteration   2: 9.279 ops/ms
# Warmup Iteration   3: 10.249 ops/ms
Iteration   1: 10.333 ops/ms
Iteration   2: 10.397 ops/ms
Iteration   3: 10.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.362 ±(99.9%) 0.601 ops/ms [Average]
  (min, avg, max) = (10.333, 10.362, 10.397), stdev = 0.033
  CI (99.9%): [9.761, 10.962] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.113 ops/ms
# Warmup Iteration   2: 10.596 ops/ms
# Warmup Iteration   3: 10.849 ops/ms
Iteration   1: 10.739 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.700 ±(99.9%) 0.729 ops/ms [Average]
  (min, avg, max) = (10.660, 10.700, 10.739), stdev = 0.040
  CI (99.9%): [9.972, 11.429] (assumes normal distribution)


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
# Warmup Iteration   1: 7.772 ops/ms
# Warmup Iteration   2: 10.363 ops/ms
# Warmup Iteration   3: 10.535 ops/ms
Iteration   1: 10.304 ops/ms
Iteration   2: 10.335 ops/ms
Iteration   3: 10.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.236 ±(99.9%) 2.647 ops/ms [Average]
  (min, avg, max) = (10.070, 10.236, 10.335), stdev = 0.145
  CI (99.9%): [7.589, 12.884] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.612 ops/ms
# Warmup Iteration   2: 7.761 ops/ms
# Warmup Iteration   3: 7.879 ops/ms
Iteration   1: 7.990 ops/ms
Iteration   2: 8.171 ops/ms
Iteration   3: 8.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.064 ±(99.9%) 1.726 ops/ms [Average]
  (min, avg, max) = (7.990, 8.064, 8.171), stdev = 0.095
  CI (99.9%): [6.338, 9.790] (assumes normal distribution)


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
# Warmup Iteration   1: 4.130 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.002 ms/op
Iteration   1: 3.041 ±(99.9%) 0.002 ms/op
Iteration   2: 3.159 ±(99.9%) 0.001 ms/op
Iteration   3: 3.151 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.117 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (3.041, 3.117, 3.159), stdev = 0.066
  CI (99.9%): [1.913, 4.320] (assumes normal distribution)


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.902 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.003 ms/op
Iteration   1: 2.912 ±(99.9%) 0.002 ms/op
Iteration   2: 2.982 ±(99.9%) 0.002 ms/op
Iteration   3: 2.946 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.946 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (2.912, 2.946, 2.982), stdev = 0.035
  CI (99.9%): [2.305, 3.588] (assumes normal distribution)


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.005 ms/op
Iteration   1: 3.050 ±(99.9%) 0.002 ms/op
Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
Iteration   3: 2.976 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.023 ±(99.9%) 0.742 ms/op [Average]
  (min, avg, max) = (2.976, 3.023, 3.050), stdev = 0.041
  CI (99.9%): [2.280, 3.765] (assumes normal distribution)


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
# Warmup Iteration   1: 4.826 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.012 ms/op
Iteration   1: 3.915 ±(99.9%) 0.040 ms/op
Iteration   2: 3.936 ±(99.9%) 0.030 ms/op
Iteration   3: 3.924 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.925 ±(99.9%) 0.190 ms/op [Average]
  (min, avg, max) = (3.915, 3.925, 3.936), stdev = 0.010
  CI (99.9%): [3.735, 4.115] (assumes normal distribution)


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
Iteration   1: 2.972 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  6.029 ms/op
                 createUser·p0.9999: 20.469 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.531 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  8.298 ms/op
                 createUser·p0.9999: 19.313 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   3: 3.118 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  13.730 ms/op
                 createUser·p0.9999: 26.427 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313416
  mean =      3.064 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33135 
    [ 2.500,  5.000) = 279306 
    [ 5.000,  7.500) = 550 
    [ 7.500, 10.000) = 159 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      9.047 ms/op
     p(99.9900) =     25.581 ms/op
     p(99.9990) =     27.750 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.953 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.006 ms/op
Iteration   1: 2.973 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  7.196 ms/op
                 existUser·p0.9999: 15.929 ms/op
                 existUser·p1.00:   16.122 ms/op

Iteration   2: 2.870 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.272 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  9.200 ms/op
                 existUser·p0.9999: 15.904 ms/op
                 existUser·p1.00:   16.286 ms/op

Iteration   3: 2.856 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  5.907 ms/op
                 existUser·p0.9999: 26.595 ms/op
                 existUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331020
  mean =      2.899 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56964 
    [ 2.500,  5.000) = 273266 
    [ 5.000,  7.500) = 521 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.272 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     16.276 ms/op
     p(99.9990) =     26.983 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.372 ms/op
                 getUser·p0.9999: 11.794 ms/op
                 getUser·p1.00:   12.108 ms/op

Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.766 ms/op
                 getUser·p0.9999: 13.306 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.275 ms/op
                 getUser·p0.999:  7.364 ms/op
                 getUser·p0.9999: 15.775 ms/op
                 getUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312058
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 936 
    [ 1.250,  2.500) = 28432 
    [ 2.500,  3.750) = 253755 
    [ 3.750,  5.000) = 27948 
    [ 5.000,  6.250) = 390 
    [ 6.250,  7.500) = 290 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =     14.382 ms/op
     p(99.9990) =     16.132 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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
# Warmup Iteration   1: 5.238 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.012 ms/op
Iteration   1: 3.745 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  11.734 ms/op
                 listUser·p0.9999: 19.462 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   2: 3.971 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.712 ms/op
                 listUser·p0.9999: 20.083 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   3: 4.042 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  16.911 ms/op
                 listUser·p0.9999: 26.747 ms/op
                 listUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245069
  mean =      3.915 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5696 
    [ 2.500,  5.000) = 211077 
    [ 5.000,  7.500) = 27332 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     27.102 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.362 ± 0.601  ops/ms
ClientGrpc.existUser                       thrpt       3  10.700 ± 0.729  ops/ms
ClientGrpc.getUser                         thrpt       3  10.236 ± 2.647  ops/ms
ClientGrpc.listUser                        thrpt       3   8.064 ± 1.726  ops/ms
ClientGrpc.createUser                       avgt       3   3.117 ± 1.204   ms/op
ClientGrpc.existUser                        avgt       3   2.946 ± 0.641   ms/op
ClientGrpc.getUser                          avgt       3   3.023 ± 0.742   ms/op
ClientGrpc.listUser                         avgt       3   3.925 ± 0.190   ms/op
ClientGrpc.createUser                     sample  313416   3.064 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.531           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.047           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.581           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.787           ms/op
ClientGrpc.existUser                      sample  331020   2.899 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.272           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.102           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.276           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.132           ms/op
ClientGrpc.getUser                        sample  312058   3.074 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.743           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.487           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.382           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.253           ms/op
ClientGrpc.listUser                       sample  245069   3.915 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.969           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.894           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.969           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.230           ms/op
