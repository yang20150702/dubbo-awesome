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
# Warmup Iteration   1: 4.959 ops/ms
# Warmup Iteration   2: 9.578 ops/ms
# Warmup Iteration   3: 10.354 ops/ms
Iteration   1: 10.583 ops/ms
Iteration   2: 10.720 ops/ms
Iteration   3: 10.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.593 ±(99.9%) 2.217 ops/ms [Average]
  (min, avg, max) = (10.477, 10.593, 10.720), stdev = 0.122
  CI (99.9%): [8.376, 12.811] (assumes normal distribution)


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
# Warmup Iteration   1: 8.860 ops/ms
# Warmup Iteration   2: 10.821 ops/ms
# Warmup Iteration   3: 11.263 ops/ms
Iteration   1: 11.379 ops/ms
Iteration   2: 11.293 ops/ms
Iteration   3: 11.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.280 ±(99.9%) 1.936 ops/ms [Average]
  (min, avg, max) = (11.168, 11.280, 11.379), stdev = 0.106
  CI (99.9%): [9.344, 13.216] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.156 ops/ms
# Warmup Iteration   2: 10.603 ops/ms
# Warmup Iteration   3: 10.861 ops/ms
Iteration   1: 10.830 ops/ms
Iteration   2: 10.843 ops/ms
Iteration   3: 10.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.820 ±(99.9%) 0.536 ops/ms [Average]
  (min, avg, max) = (10.787, 10.820, 10.843), stdev = 0.029
  CI (99.9%): [10.284, 11.356] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.629 ops/ms
# Warmup Iteration   2: 8.049 ops/ms
# Warmup Iteration   3: 8.369 ops/ms
Iteration   1: 8.368 ops/ms
Iteration   2: 8.540 ops/ms
Iteration   3: 8.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.459 ±(99.9%) 1.572 ops/ms [Average]
  (min, avg, max) = (8.368, 8.459, 8.540), stdev = 0.086
  CI (99.9%): [6.887, 10.031] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.002 ms/op
Iteration   1: 3.038 ±(99.9%) 0.003 ms/op
Iteration   2: 2.993 ±(99.9%) 0.002 ms/op
Iteration   3: 3.041 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.024 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (2.993, 3.024, 3.041), stdev = 0.027
  CI (99.9%): [2.534, 3.514] (assumes normal distribution)


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.809 ±(99.9%) 0.004 ms/op
Iteration   1: 2.853 ±(99.9%) 0.004 ms/op
Iteration   2: 2.856 ±(99.9%) 0.007 ms/op
Iteration   3: 2.852 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.854 ±(99.9%) 0.040 ms/op [Average]
  (min, avg, max) = (2.852, 2.854, 2.856), stdev = 0.002
  CI (99.9%): [2.814, 2.894] (assumes normal distribution)


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
# Warmup Iteration   1: 3.578 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.003 ms/op
Iteration   1: 2.928 ±(99.9%) 0.003 ms/op
Iteration   2: 2.995 ±(99.9%) 0.002 ms/op
Iteration   3: 2.924 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.949 ±(99.9%) 0.724 ms/op [Average]
  (min, avg, max) = (2.924, 2.949, 2.995), stdev = 0.040
  CI (99.9%): [2.225, 3.673] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.946 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.022 ms/op
Iteration   1: 3.845 ±(99.9%) 0.010 ms/op
Iteration   2: 3.816 ±(99.9%) 0.035 ms/op
Iteration   3: 3.810 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.824 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (3.810, 3.824, 3.845), stdev = 0.019
  CI (99.9%): [3.477, 4.170] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.915 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.007 ms/op
Iteration   1: 2.951 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.477 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.864 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  8.802 ms/op
                 createUser·p0.9999: 12.097 ms/op
                 createUser·p1.00:   12.337 ms/op

Iteration   2: 2.940 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.607 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  10.433 ms/op
                 createUser·p0.9999: 16.320 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  8.644 ms/op
                 createUser·p0.9999: 18.364 ms/op
                 createUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323608
  mean =      2.965 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3098 
    [ 1.250,  2.500) = 34008 
    [ 2.500,  3.750) = 269661 
    [ 3.750,  5.000) = 14348 
    [ 5.000,  6.250) = 1314 
    [ 6.250,  7.500) = 565 
    [ 7.500,  8.750) = 297 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =      8.706 ms/op
     p(99.9900) =     16.754 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.923 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.917 ±(99.9%) 0.007 ms/op
Iteration   1: 2.861 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  7.555 ms/op
                 existUser·p0.9999: 15.067 ms/op
                 existUser·p1.00:   15.761 ms/op

Iteration   2: 2.908 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.619 ms/op
                 existUser·p0.9999: 12.419 ms/op
                 existUser·p1.00:   12.665 ms/op

Iteration   3: 2.901 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.278 ms/op
                 existUser·p0.999:  7.856 ms/op
                 existUser·p0.9999: 14.221 ms/op
                 existUser·p1.00:   14.516 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332186
  mean =      2.890 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2838 
    [ 1.250,  2.500) = 44996 
    [ 2.500,  3.750) = 272797 
    [ 3.750,  5.000) = 9846 
    [ 5.000,  6.250) = 926 
    [ 6.250,  7.500) = 361 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.725 ms/op
     p(99.9900) =     14.320 ms/op
     p(99.9990) =     15.664 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.231 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  8.146 ms/op
                 getUser·p0.9999: 11.660 ms/op
                 getUser·p1.00:   11.846 ms/op

Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.416 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  8.368 ms/op
                 getUser·p0.9999: 19.706 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  8.711 ms/op
                 getUser·p0.9999: 15.920 ms/op
                 getUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319364
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28496 
    [ 2.500,  5.000) = 288873 
    [ 5.000,  7.500) = 1502 
    [ 7.500, 10.000) = 333 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.231 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.361 ms/op
     p(99.9900) =     18.915 ms/op
     p(99.9990) =     20.015 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 4.876 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.011 ms/op
Iteration   1: 3.842 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.829 ms/op
                 listUser·p0.999:  13.198 ms/op
                 listUser·p0.9999: 18.701 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   2: 3.832 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.709 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.450 ms/op
                 listUser·p0.9999: 22.905 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   3: 3.817 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.974 ms/op
                 listUser·p0.999:  15.257 ms/op
                 listUser·p0.9999: 18.424 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250618
  mean =      3.830 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6741 
    [ 2.500,  5.000) = 224016 
    [ 5.000,  7.500) = 18338 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.938 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     23.035 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.593 ± 2.217  ops/ms
ClientGrpc.existUser                       thrpt       3  11.280 ± 1.936  ops/ms
ClientGrpc.getUser                         thrpt       3  10.820 ± 0.536  ops/ms
ClientGrpc.listUser                        thrpt       3   8.459 ± 1.572  ops/ms
ClientGrpc.createUser                       avgt       3   3.024 ± 0.490   ms/op
ClientGrpc.existUser                        avgt       3   2.854 ± 0.040   ms/op
ClientGrpc.getUser                          avgt       3   2.949 ± 0.724   ms/op
ClientGrpc.listUser                         avgt       3   3.824 ± 0.346   ms/op
ClientGrpc.createUser                     sample  323608   2.965 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.477           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.498           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.706           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.754           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.464           ms/op
ClientGrpc.existUser                      sample  332186   2.890 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.604           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.725           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.320           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.761           ms/op
ClientGrpc.getUser                        sample  319364   3.007 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.231           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.361           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.915           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.120           ms/op
ClientGrpc.listUser                       sample  250618   3.830 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.709           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.938           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.103           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.101           ms/op
