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
# Warmup Iteration   1: 4.085 ops/ms
# Warmup Iteration   2: 9.437 ops/ms
# Warmup Iteration   3: 10.140 ops/ms
Iteration   1: 10.089 ops/ms
Iteration   2: 10.063 ops/ms
Iteration   3: 10.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.122 ±(99.9%) 1.469 ops/ms [Average]
  (min, avg, max) = (10.063, 10.122, 10.213), stdev = 0.081
  CI (99.9%): [8.653, 11.591] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.273 ops/ms
# Warmup Iteration   2: 10.105 ops/ms
# Warmup Iteration   3: 10.341 ops/ms
Iteration   1: 10.260 ops/ms
Iteration   2: 10.460 ops/ms
Iteration   3: 10.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.413 ±(99.9%) 2.480 ops/ms [Average]
  (min, avg, max) = (10.260, 10.413, 10.519), stdev = 0.136
  CI (99.9%): [7.933, 12.892] (assumes normal distribution)


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
# Warmup Iteration   1: 7.068 ops/ms
# Warmup Iteration   2: 9.902 ops/ms
# Warmup Iteration   3: 10.031 ops/ms
Iteration   1: 9.965 ops/ms
Iteration   2: 9.792 ops/ms
Iteration   3: 9.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.911 ±(99.9%) 1.874 ops/ms [Average]
  (min, avg, max) = (9.792, 9.911, 9.975), stdev = 0.103
  CI (99.9%): [8.036, 11.785] (assumes normal distribution)


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
# Warmup Iteration   1: 4.847 ops/ms
# Warmup Iteration   2: 7.533 ops/ms
# Warmup Iteration   3: 7.855 ops/ms
Iteration   1: 7.746 ops/ms
Iteration   2: 7.808 ops/ms
Iteration   3: 7.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.772 ±(99.9%) 0.591 ops/ms [Average]
  (min, avg, max) = (7.746, 7.772, 7.808), stdev = 0.032
  CI (99.9%): [7.181, 8.363] (assumes normal distribution)


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.001 ms/op
Iteration   1: 3.201 ±(99.9%) 0.002 ms/op
Iteration   2: 3.132 ±(99.9%) 0.004 ms/op
Iteration   3: 3.227 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.187 ±(99.9%) 0.894 ms/op [Average]
  (min, avg, max) = (3.132, 3.187, 3.227), stdev = 0.049
  CI (99.9%): [2.293, 4.081] (assumes normal distribution)


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.001 ms/op
Iteration   1: 3.039 ±(99.9%) 0.004 ms/op
Iteration   2: 3.037 ±(99.9%) 0.002 ms/op
Iteration   3: 3.095 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.057 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.037, 3.057, 3.095), stdev = 0.033
  CI (99.9%): [2.456, 3.658] (assumes normal distribution)


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.003 ms/op
Iteration   1: 3.220 ±(99.9%) 0.004 ms/op
Iteration   2: 3.148 ±(99.9%) 0.002 ms/op
Iteration   3: 3.210 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.193 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (3.148, 3.193, 3.220), stdev = 0.039
  CI (99.9%): [2.479, 3.906] (assumes normal distribution)


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
# Warmup Iteration   1: 5.510 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.260 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.172 ±(99.9%) 0.023 ms/op
Iteration   1: 4.157 ±(99.9%) 0.042 ms/op
Iteration   2: 4.082 ±(99.9%) 0.007 ms/op
Iteration   3: 4.128 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.122 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (4.082, 4.122, 4.157), stdev = 0.037
  CI (99.9%): [3.440, 4.804] (assumes normal distribution)


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.007 ms/op
Iteration   1: 3.285 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  11.818 ms/op
                 createUser·p0.9999: 20.382 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   2: 3.255 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  11.977 ms/op
                 createUser·p0.9999: 22.255 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   3: 3.241 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  12.419 ms/op
                 createUser·p0.9999: 30.216 ms/op
                 createUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294276
  mean =      3.260 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17765 
    [ 2.500,  5.000) = 275271 
    [ 5.000,  7.500) = 690 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =     12.005 ms/op
     p(99.9900) =     29.744 ms/op
     p(99.9990) =     30.515 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
Iteration   1: 3.125 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  8.839 ms/op
                 existUser·p0.9999: 13.414 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.249 ms/op
                 existUser·p0.9999: 24.117 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.333 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  9.173 ms/op
                 existUser·p0.9999: 17.105 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313635
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34450 
    [ 2.500,  5.000) = 277687 
    [ 5.000,  7.500) = 1111 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     23.090 ms/op
     p(99.9990) =     26.168 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 4.498 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.006 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  9.028 ms/op
                 getUser·p0.9999: 13.410 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   2: 3.162 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  5.994 ms/op
                 getUser·p0.9999: 14.575 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.324 ms/op
                 getUser·p0.999:  6.176 ms/op
                 getUser·p0.9999: 29.688 ms/op
                 getUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304547
  mean =      3.152 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21906 
    [ 2.500,  5.000) = 281667 
    [ 5.000,  7.500) = 718 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.160 ms/op
     p(99.9900) =     28.889 ms/op
     p(99.9990) =     30.015 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 5.644 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.011 ms/op
Iteration   1: 4.197 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.411 ms/op
                 listUser·p0.999:  14.800 ms/op
                 listUser·p0.9999: 16.512 ms/op
                 listUser·p1.00:   16.712 ms/op

Iteration   2: 4.202 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 18.052 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   3: 4.096 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  17.977 ms/op
                 listUser·p0.9999: 19.935 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230624
  mean =      4.164 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2142 
    [ 2.500,  5.000) = 194516 
    [ 5.000,  7.500) = 32296 
    [ 7.500, 10.000) = 1152 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     14.975 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     20.142 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.122 ± 1.469  ops/ms
ClientGrpc.existUser                       thrpt       3  10.413 ± 2.480  ops/ms
ClientGrpc.getUser                         thrpt       3   9.911 ± 1.874  ops/ms
ClientGrpc.listUser                        thrpt       3   7.772 ± 0.591  ops/ms
ClientGrpc.createUser                       avgt       3   3.187 ± 0.894   ms/op
ClientGrpc.existUser                        avgt       3   3.057 ± 0.601   ms/op
ClientGrpc.getUser                          avgt       3   3.193 ± 0.713   ms/op
ClientGrpc.listUser                         avgt       3   4.122 ± 0.682   ms/op
ClientGrpc.createUser                     sample  294276   3.260 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.719           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.228           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.137           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.005           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.744           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.704           ms/op
ClientGrpc.existUser                      sample  313635   3.063 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.333           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.924           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.897           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.090           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.640           ms/op
ClientGrpc.getUser                        sample  304547   3.152 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.680           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.002           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.160           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.889           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.081           ms/op
ClientGrpc.listUser                       sample  230624   4.164 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.867           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.969           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.160           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.975           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.562           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.053           ms/op
