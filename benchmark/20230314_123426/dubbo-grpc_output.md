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
# Warmup Iteration   1: 4.290 ops/ms
# Warmup Iteration   2: 9.022 ops/ms
# Warmup Iteration   3: 9.916 ops/ms
Iteration   1: 10.563 ops/ms
Iteration   2: 10.627 ops/ms
Iteration   3: 10.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.609 ±(99.9%) 0.728 ops/ms [Average]
  (min, avg, max) = (10.563, 10.609, 10.637), stdev = 0.040
  CI (99.9%): [9.881, 11.337] (assumes normal distribution)


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
# Warmup Iteration   1: 7.253 ops/ms
# Warmup Iteration   2: 10.228 ops/ms
# Warmup Iteration   3: 10.877 ops/ms
Iteration   1: 10.887 ops/ms
Iteration   2: 11.013 ops/ms
Iteration   3: 11.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.041 ±(99.9%) 3.102 ops/ms [Average]
  (min, avg, max) = (10.887, 11.041, 11.224), stdev = 0.170
  CI (99.9%): [7.939, 14.144] (assumes normal distribution)


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
# Warmup Iteration   1: 7.111 ops/ms
# Warmup Iteration   2: 10.195 ops/ms
# Warmup Iteration   3: 10.430 ops/ms
Iteration   1: 10.270 ops/ms
Iteration   2: 10.289 ops/ms
Iteration   3: 10.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.350 ±(99.9%) 2.220 ops/ms [Average]
  (min, avg, max) = (10.270, 10.350, 10.490), stdev = 0.122
  CI (99.9%): [8.130, 12.569] (assumes normal distribution)


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
# Warmup Iteration   1: 5.522 ops/ms
# Warmup Iteration   2: 7.540 ops/ms
# Warmup Iteration   3: 7.863 ops/ms
Iteration   1: 8.013 ops/ms
Iteration   2: 8.105 ops/ms
Iteration   3: 7.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.036 ±(99.9%) 1.123 ops/ms [Average]
  (min, avg, max) = (7.989, 8.036, 8.105), stdev = 0.062
  CI (99.9%): [6.913, 9.158] (assumes normal distribution)


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.004 ms/op
Iteration   1: 3.089 ±(99.9%) 0.003 ms/op
Iteration   2: 3.033 ±(99.9%) 0.002 ms/op
Iteration   3: 3.035 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.053 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.033, 3.053, 3.089), stdev = 0.032
  CI (99.9%): [2.474, 3.631] (assumes normal distribution)


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.002 ms/op
Iteration   1: 2.973 ±(99.9%) 0.002 ms/op
Iteration   2: 2.942 ±(99.9%) 0.001 ms/op
Iteration   3: 2.868 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.928 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (2.868, 2.928, 2.973), stdev = 0.054
  CI (99.9%): [1.940, 3.916] (assumes normal distribution)


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
# Warmup Iteration   1: 4.514 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.003 ms/op
Iteration   1: 3.077 ±(99.9%) 0.002 ms/op
Iteration   2: 3.079 ±(99.9%) 0.002 ms/op
Iteration   3: 3.092 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.083 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (3.077, 3.083, 3.092), stdev = 0.008
  CI (99.9%): [2.930, 3.236] (assumes normal distribution)


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
# Warmup Iteration   1: 5.698 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.027 ms/op
Iteration   1: 4.027 ±(99.9%) 0.009 ms/op
Iteration   2: 3.926 ±(99.9%) 0.015 ms/op
Iteration   3: 4.012 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.988 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (3.926, 3.988, 4.027), stdev = 0.054
  CI (99.9%): [2.995, 4.982] (assumes normal distribution)


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
Iteration   1: 3.119 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  10.524 ms/op
                 createUser·p0.9999: 18.553 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  6.726 ms/op
                 createUser·p0.9999: 19.022 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  9.126 ms/op
                 createUser·p0.9999: 26.529 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312293
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12582 
    [ 2.500,  5.000) = 298185 
    [ 5.000,  7.500) = 1065 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.926 ms/op
     p(99.9900) =     19.336 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
Iteration   1: 2.923 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  6.382 ms/op
                 existUser·p0.9999: 12.833 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   2: 2.950 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.733 ms/op
                 existUser·p0.9999: 14.257 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  6.708 ms/op
                 existUser·p0.9999: 22.128 ms/op
                 existUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324887
  mean =      2.953 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23240 
    [ 2.500,  5.000) = 300462 
    [ 5.000,  7.500) = 959 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.587 ms/op
     p(99.9900) =     18.734 ms/op
     p(99.9990) =     22.618 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 4.373 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
Iteration   1: 3.100 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.605 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  10.384 ms/op
                 getUser·p0.9999: 19.215 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  7.868 ms/op
                 getUser·p0.9999: 14.127 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 3.037 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  8.438 ms/op
                 getUser·p0.9999: 17.808 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310998
  mean =      3.085 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 310 
    [ 1.250,  2.500) = 11066 
    [ 2.500,  3.750) = 281199 
    [ 3.750,  5.000) = 16681 
    [ 5.000,  6.250) = 886 
    [ 6.250,  7.500) = 417 
    [ 7.500,  8.750) = 150 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     18.049 ms/op
     p(99.9990) =     19.428 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 6.116 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.012 ms/op
Iteration   1: 4.033 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 21.072 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   2: 3.943 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.938 ms/op
                 listUser·p0.999:  14.875 ms/op
                 listUser·p0.9999: 16.120 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   3: 4.017 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  17.819 ms/op
                 listUser·p0.9999: 25.461 ms/op
                 listUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239997
  mean =      3.997 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2076 
    [ 2.500,  5.000) = 216889 
    [ 5.000,  7.500) = 19548 
    [ 7.500, 10.000) = 951 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     26.758 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.609 ± 0.728  ops/ms
ClientGrpc.existUser                       thrpt       3  11.041 ± 3.102  ops/ms
ClientGrpc.getUser                         thrpt       3  10.350 ± 2.220  ops/ms
ClientGrpc.listUser                        thrpt       3   8.036 ± 1.123  ops/ms
ClientGrpc.createUser                       avgt       3   3.053 ± 0.579   ms/op
ClientGrpc.existUser                        avgt       3   2.928 ± 0.988   ms/op
ClientGrpc.getUser                          avgt       3   3.083 ± 0.153   ms/op
ClientGrpc.listUser                         avgt       3   3.988 ± 0.994   ms/op
ClientGrpc.createUser                     sample  312293   3.076 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.686           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.926           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.336           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.771           ms/op
ClientGrpc.existUser                      sample  324887   2.953 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.652           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.587           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.734           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.774           ms/op
ClientGrpc.getUser                        sample  310998   3.085 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.654           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.438           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.049           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.497           ms/op
ClientGrpc.listUser                       sample  239997   3.997 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.065           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.270           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.002           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
