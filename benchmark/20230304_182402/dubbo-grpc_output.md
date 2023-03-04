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
# Warmup Iteration   1: 4.217 ops/ms
# Warmup Iteration   2: 9.399 ops/ms
# Warmup Iteration   3: 10.494 ops/ms
Iteration   1: 10.412 ops/ms
Iteration   2: 10.549 ops/ms
Iteration   3: 10.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.463 ±(99.9%) 1.374 ops/ms [Average]
  (min, avg, max) = (10.412, 10.463, 10.549), stdev = 0.075
  CI (99.9%): [9.088, 11.837] (assumes normal distribution)


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
# Warmup Iteration   1: 8.117 ops/ms
# Warmup Iteration   2: 10.857 ops/ms
# Warmup Iteration   3: 11.154 ops/ms
Iteration   1: 10.957 ops/ms
Iteration   2: 11.238 ops/ms
Iteration   3: 11.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.111 ±(99.9%) 2.597 ops/ms [Average]
  (min, avg, max) = (10.957, 11.111, 11.238), stdev = 0.142
  CI (99.9%): [8.514, 13.708] (assumes normal distribution)


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
# Warmup Iteration   1: 7.676 ops/ms
# Warmup Iteration   2: 10.102 ops/ms
# Warmup Iteration   3: 10.467 ops/ms
Iteration   1: 10.459 ops/ms
Iteration   2: 10.526 ops/ms
Iteration   3: 10.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.451 ±(99.9%) 1.441 ops/ms [Average]
  (min, avg, max) = (10.368, 10.451, 10.526), stdev = 0.079
  CI (99.9%): [9.010, 11.892] (assumes normal distribution)


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
# Warmup Iteration   1: 5.804 ops/ms
# Warmup Iteration   2: 7.891 ops/ms
# Warmup Iteration   3: 8.079 ops/ms
Iteration   1: 8.179 ops/ms
Iteration   2: 8.178 ops/ms
Iteration   3: 7.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.092 ±(99.9%) 2.737 ops/ms [Average]
  (min, avg, max) = (7.919, 8.092, 8.179), stdev = 0.150
  CI (99.9%): [5.355, 10.829] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.002 ms/op
Iteration   1: 3.027 ±(99.9%) 0.002 ms/op
Iteration   2: 2.969 ±(99.9%) 0.003 ms/op
Iteration   3: 3.038 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.011 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (2.969, 3.011, 3.038), stdev = 0.037
  CI (99.9%): [2.333, 3.690] (assumes normal distribution)


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
# Warmup Iteration   1: 3.676 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.003 ms/op
Iteration   1: 2.946 ±(99.9%) 0.003 ms/op
Iteration   2: 2.854 ±(99.9%) 0.002 ms/op
Iteration   3: 2.905 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.902 ±(99.9%) 0.840 ms/op [Average]
  (min, avg, max) = (2.854, 2.902, 2.946), stdev = 0.046
  CI (99.9%): [2.061, 3.742] (assumes normal distribution)


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.002 ms/op
Iteration   1: 3.112 ±(99.9%) 0.002 ms/op
Iteration   2: 2.962 ±(99.9%) 0.002 ms/op
Iteration   3: 3.019 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.031 ±(99.9%) 1.377 ms/op [Average]
  (min, avg, max) = (2.962, 3.031, 3.112), stdev = 0.075
  CI (99.9%): [1.654, 4.408] (assumes normal distribution)


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
# Warmup Iteration   1: 4.741 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
Iteration   1: 3.802 ±(99.9%) 0.015 ms/op
Iteration   2: 3.925 ±(99.9%) 0.009 ms/op
Iteration   3: 3.860 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.863 ±(99.9%) 1.116 ms/op [Average]
  (min, avg, max) = (3.802, 3.863, 3.925), stdev = 0.061
  CI (99.9%): [2.746, 4.979] (assumes normal distribution)


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.490 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  6.136 ms/op
                 createUser·p0.9999: 13.051 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.497 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.038 ms/op
                 createUser·p0.9999: 13.173 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   3: 3.073 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  9.748 ms/op
                 createUser·p0.9999: 25.625 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311848
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32808 
    [ 2.500,  5.000) = 277964 
    [ 5.000,  7.500) = 740 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     23.718 ms/op
     p(99.9990) =     26.224 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.006 ms/op
Iteration   1: 2.889 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  5.155 ms/op
                 existUser·p0.9999: 13.155 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   2: 2.961 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  6.570 ms/op
                 existUser·p0.9999: 24.052 ms/op
                 existUser·p1.00:   25.166 ms/op

Iteration   3: 2.820 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  5.993 ms/op
                 existUser·p0.9999: 17.127 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332121
  mean =      2.889 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59510 
    [ 2.500,  5.000) = 272004 
    [ 5.000,  7.500) = 443 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      5.972 ms/op
     p(99.9900) =     17.386 ms/op
     p(99.9990) =     24.379 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.046 ms/op
                 getUser·p0.9999: 14.392 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.051 ms/op
                 getUser·p0.9999: 22.542 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  6.134 ms/op
                 getUser·p0.9999: 16.400 ms/op
                 getUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318321
  mean =      3.016 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31173 
    [ 2.500,  5.000) = 286371 
    [ 5.000,  7.500) = 547 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.447 ms/op
     p(99.9900) =     21.671 ms/op
     p(99.9990) =     22.893 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 4.319 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.011 ms/op
Iteration   1: 3.913 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.406 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   2: 3.850 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  15.625 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 4.082 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.928 ms/op
                 listUser·p0.999:  19.726 ms/op
                 listUser·p0.9999: 25.930 ms/op
                 listUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243315
  mean =      3.946 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3876 
    [ 2.500,  5.000) = 212757 
    [ 5.000,  7.500) = 25648 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     15.614 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     26.336 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.463 ± 1.374  ops/ms
ClientGrpc.existUser                       thrpt       3  11.111 ± 2.597  ops/ms
ClientGrpc.getUser                         thrpt       3  10.451 ± 1.441  ops/ms
ClientGrpc.listUser                        thrpt       3   8.092 ± 2.737  ops/ms
ClientGrpc.createUser                       avgt       3   3.011 ± 0.678   ms/op
ClientGrpc.existUser                        avgt       3   2.902 ± 0.840   ms/op
ClientGrpc.getUser                          avgt       3   3.031 ± 1.377   ms/op
ClientGrpc.listUser                         avgt       3   3.863 ± 1.116   ms/op
ClientGrpc.createUser                     sample  311848   3.078 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.490           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.799           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.718           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.313           ms/op
ClientGrpc.existUser                      sample  332121   2.889 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.662           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.972           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.386           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.166           ms/op
ClientGrpc.getUser                        sample  318321   3.016 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.719           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.447           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.671           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.970           ms/op
ClientGrpc.listUser                       sample  243315   3.946 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.948           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.614           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.674           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.444           ms/op
