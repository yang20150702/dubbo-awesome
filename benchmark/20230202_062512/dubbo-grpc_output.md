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
# Warmup Iteration   1: 5.239 ops/ms
# Warmup Iteration   2: 9.617 ops/ms
# Warmup Iteration   3: 10.375 ops/ms
Iteration   1: 10.077 ops/ms
Iteration   2: 10.320 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.280 ±(99.9%) 3.390 ops/ms [Average]
  (min, avg, max) = (10.077, 10.280, 10.442), stdev = 0.186
  CI (99.9%): [6.889, 13.670] (assumes normal distribution)


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
# Warmup Iteration   1: 8.881 ops/ms
# Warmup Iteration   2: 10.631 ops/ms
# Warmup Iteration   3: 11.237 ops/ms
Iteration   1: 10.574 ops/ms
Iteration   2: 11.017 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.768 ±(99.9%) 4.132 ops/ms [Average]
  (min, avg, max) = (10.574, 10.768, 11.017), stdev = 0.226
  CI (99.9%): [6.636, 14.900] (assumes normal distribution)


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
# Warmup Iteration   1: 7.568 ops/ms
# Warmup Iteration   2: 10.486 ops/ms
# Warmup Iteration   3: 10.181 ops/ms
Iteration   1: 10.795 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.669 ±(99.9%) 2.048 ops/ms [Average]
  (min, avg, max) = (10.578, 10.669, 10.795), stdev = 0.112
  CI (99.9%): [8.621, 12.718] (assumes normal distribution)


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
# Warmup Iteration   1: 6.350 ops/ms
# Warmup Iteration   2: 7.767 ops/ms
# Warmup Iteration   3: 8.016 ops/ms
Iteration   1: 8.022 ops/ms
Iteration   2: 7.918 ops/ms
Iteration   3: 8.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.998 ±(99.9%) 1.300 ops/ms [Average]
  (min, avg, max) = (7.918, 7.998, 8.055), stdev = 0.071
  CI (99.9%): [6.699, 9.298] (assumes normal distribution)


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
# Warmup Iteration   1: 3.614 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.003 ms/op
Iteration   1: 2.951 ±(99.9%) 0.002 ms/op
Iteration   2: 3.018 ±(99.9%) 0.002 ms/op
Iteration   3: 3.130 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.033 ±(99.9%) 1.651 ms/op [Average]
  (min, avg, max) = (2.951, 3.033, 3.130), stdev = 0.090
  CI (99.9%): [1.383, 4.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.915 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.005 ms/op
Iteration   1: 2.906 ±(99.9%) 0.002 ms/op
Iteration   2: 2.938 ±(99.9%) 0.002 ms/op
Iteration   3: 2.936 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.926 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (2.906, 2.926, 2.938), stdev = 0.018
  CI (99.9%): [2.598, 3.255] (assumes normal distribution)


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.004 ms/op
Iteration   1: 2.969 ±(99.9%) 0.002 ms/op
Iteration   2: 3.010 ±(99.9%) 0.002 ms/op
Iteration   3: 3.080 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.020 ±(99.9%) 1.028 ms/op [Average]
  (min, avg, max) = (2.969, 3.020, 3.080), stdev = 0.056
  CI (99.9%): [1.992, 4.047] (assumes normal distribution)


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
# Warmup Iteration   1: 5.074 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.022 ms/op
Iteration   1: 3.812 ±(99.9%) 0.010 ms/op
Iteration   2: 3.837 ±(99.9%) 0.008 ms/op
Iteration   3: 4.011 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.887 ±(99.9%) 1.981 ms/op [Average]
  (min, avg, max) = (3.812, 3.887, 4.011), stdev = 0.109
  CI (99.9%): [1.906, 5.867] (assumes normal distribution)


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
# Warmup Iteration   1: 4.064 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.465 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  6.668 ms/op
                 createUser·p0.9999: 11.604 ms/op
                 createUser·p1.00:   11.911 ms/op

Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.166 ms/op
                 createUser·p0.999:  6.845 ms/op
                 createUser·p0.9999: 14.058 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.627 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  10.328 ms/op
                 createUser·p0.9999: 19.056 ms/op
                 createUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313258
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1360 
    [ 1.250,  2.500) = 27785 
    [ 2.500,  3.750) = 257493 
    [ 3.750,  5.000) = 25630 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 220 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.518 ms/op
     p(99.9900) =     18.635 ms/op
     p(99.9990) =     19.169 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 3.772 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.007 ms/op
Iteration   1: 2.904 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.045 ms/op
                 existUser·p0.9999: 14.614 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.645 ms/op
                 existUser·p0.9999: 16.538 ms/op
                 existUser·p1.00:   16.728 ms/op

Iteration   3: 2.968 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.201 ms/op
                 existUser·p0.9999: 19.970 ms/op
                 existUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323683
  mean =      2.965 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44600 
    [ 2.500,  5.000) = 278311 
    [ 5.000,  7.500) = 542 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =     19.464 ms/op
     p(99.9990) =     21.931 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
Iteration   1: 3.092 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.598 ms/op
                 getUser·p0.9999: 11.354 ms/op
                 getUser·p1.00:   13.369 ms/op

Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.446 ms/op
                 getUser·p0.9999: 25.751 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.467 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  7.684 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316404
  mean =      3.032 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31258 
    [ 2.500,  5.000) = 284072 
    [ 5.000,  7.500) = 750 
    [ 7.500, 10.000) = 146 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.821 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.586 ms/op
     p(99.9900) =     24.829 ms/op
     p(99.9990) =     26.078 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 4.389 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.012 ms/op
Iteration   1: 3.944 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.575 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  12.166 ms/op
                 listUser·p0.9999: 16.996 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   2: 3.927 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  15.041 ms/op
                 listUser·p0.9999: 23.265 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   3: 3.933 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.748 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.683 ms/op
                 listUser·p0.999:  14.817 ms/op
                 listUser·p0.9999: 18.182 ms/op
                 listUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243858
  mean =      3.934 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4920 
    [ 2.500,  5.000) = 213612 
    [ 5.000,  7.500) = 24237 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     27.355 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.280 ± 3.390  ops/ms
ClientGrpc.existUser                       thrpt       3  10.768 ± 4.132  ops/ms
ClientGrpc.getUser                         thrpt       3  10.669 ± 2.048  ops/ms
ClientGrpc.listUser                        thrpt       3   7.998 ± 1.300  ops/ms
ClientGrpc.createUser                       avgt       3   3.033 ± 1.651   ms/op
ClientGrpc.existUser                        avgt       3   2.926 ± 0.329   ms/op
ClientGrpc.getUser                          avgt       3   3.020 ± 1.028   ms/op
ClientGrpc.listUser                         avgt       3   3.887 ± 1.981   ms/op
ClientGrpc.createUser                     sample  313258   3.066 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.465           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.518           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.635           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.235           ms/op
ClientGrpc.existUser                      sample  323683   2.965 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.569           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.652           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.464           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.053           ms/op
ClientGrpc.getUser                        sample  316404   3.032 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.467           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.821           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.586           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.829           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.182           ms/op
ClientGrpc.listUser                       sample  243858   3.934 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.575           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.566           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.217           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.656           ms/op
