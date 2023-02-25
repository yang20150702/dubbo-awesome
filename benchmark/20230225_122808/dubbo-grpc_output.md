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
# Warmup Iteration   1: 4.503 ops/ms
# Warmup Iteration   2: 9.523 ops/ms
# Warmup Iteration   3: 10.392 ops/ms
Iteration   1: 10.716 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.482 ±(99.9%) 5.204 ops/ms [Average]
  (min, avg, max) = (10.164, 10.482, 10.716), stdev = 0.285
  CI (99.9%): [5.278, 15.685] (assumes normal distribution)


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
# Warmup Iteration   1: 8.115 ops/ms
# Warmup Iteration   2: 10.759 ops/ms
# Warmup Iteration   3: 11.026 ops/ms
Iteration   1: 10.992 ops/ms
Iteration   2: 10.863 ops/ms
Iteration   3: 11.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.992 ±(99.9%) 2.363 ops/ms [Average]
  (min, avg, max) = (10.863, 10.992, 11.122), stdev = 0.130
  CI (99.9%): [8.629, 13.355] (assumes normal distribution)


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
# Warmup Iteration   1: 7.142 ops/ms
# Warmup Iteration   2: 9.995 ops/ms
# Warmup Iteration   3: 10.378 ops/ms
Iteration   1: 10.487 ops/ms
Iteration   2: 10.729 ops/ms
Iteration   3: 10.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.588 ±(99.9%) 2.298 ops/ms [Average]
  (min, avg, max) = (10.487, 10.588, 10.729), stdev = 0.126
  CI (99.9%): [8.290, 12.886] (assumes normal distribution)


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
# Warmup Iteration   1: 5.724 ops/ms
# Warmup Iteration   2: 7.786 ops/ms
# Warmup Iteration   3: 7.879 ops/ms
Iteration   1: 7.832 ops/ms
Iteration   2: 8.179 ops/ms
Iteration   3: 8.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.103 ±(99.9%) 4.414 ops/ms [Average]
  (min, avg, max) = (7.832, 8.103, 8.297), stdev = 0.242
  CI (99.9%): [3.688, 12.517] (assumes normal distribution)


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.002 ms/op
Iteration   1: 3.066 ±(99.9%) 0.002 ms/op
Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
Iteration   3: 3.165 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.087 ±(99.9%) 1.279 ms/op [Average]
  (min, avg, max) = (3.030, 3.087, 3.165), stdev = 0.070
  CI (99.9%): [1.808, 4.366] (assumes normal distribution)


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.002 ms/op
Iteration   1: 2.968 ±(99.9%) 0.002 ms/op
Iteration   2: 2.947 ±(99.9%) 0.002 ms/op
Iteration   3: 2.951 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.955 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (2.947, 2.955, 2.968), stdev = 0.011
  CI (99.9%): [2.750, 3.161] (assumes normal distribution)


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.003 ms/op
Iteration   2: 3.082 ±(99.9%) 0.001 ms/op
Iteration   3: 3.116 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.062 ±(99.9%) 1.203 ms/op [Average]
  (min, avg, max) = (2.988, 3.062, 3.116), stdev = 0.066
  CI (99.9%): [1.859, 4.265] (assumes normal distribution)


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.028 ms/op
Iteration   1: 3.936 ±(99.9%) 0.011 ms/op
Iteration   2: 3.880 ±(99.9%) 0.009 ms/op
Iteration   3: 4.046 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.954 ±(99.9%) 1.545 ms/op [Average]
  (min, avg, max) = (3.880, 3.954, 4.046), stdev = 0.085
  CI (99.9%): [2.409, 5.499] (assumes normal distribution)


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.007 ms/op
Iteration   1: 3.075 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.257 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  5.833 ms/op
                 createUser·p0.9999: 14.549 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.334 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.694 ms/op
                 createUser·p0.9999: 15.778 ms/op
                 createUser·p1.00:   16.318 ms/op

Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.154 ms/op
                 createUser·p0.9999: 25.247 ms/op
                 createUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316313
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27453 
    [ 2.500,  5.000) = 287874 
    [ 5.000,  7.500) = 702 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.257 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.198 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     25.810 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
Iteration   1: 2.913 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  7.923 ms/op
                 existUser·p0.9999: 12.650 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.201 ms/op
                 existUser·p0.9999: 19.080 ms/op
                 existUser·p1.00:   19.137 ms/op

Iteration   3: 2.855 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.567 ms/op
                 existUser·p0.9999: 15.709 ms/op
                 existUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329222
  mean =      2.914 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3862 
    [ 1.250,  2.500) = 48098 
    [ 2.500,  3.750) = 261468 
    [ 3.750,  5.000) = 15024 
    [ 5.000,  6.250) = 292 
    [ 6.250,  7.500) = 197 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      7.103 ms/op
     p(99.9900) =     16.058 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 3.517 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.007 ms/op
Iteration   1: 2.981 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.389 ms/op
                 getUser·p0.9999: 11.813 ms/op
                 getUser·p1.00:   12.501 ms/op

Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.599 ms/op
                 getUser·p0.9999: 18.605 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  6.185 ms/op
                 getUser·p0.9999: 15.344 ms/op
                 getUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314615
  mean =      3.054 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1967 
    [ 1.250,  2.500) = 28377 
    [ 2.500,  3.750) = 255548 
    [ 3.750,  5.000) = 27828 
    [ 5.000,  6.250) = 452 
    [ 6.250,  7.500) = 241 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.299 ms/op
     p(99.9000) =      6.767 ms/op
     p(99.9900) =     16.492 ms/op
     p(99.9990) =     19.029 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.011 ms/op
Iteration   1: 4.091 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.575 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  13.211 ms/op
                 listUser·p0.9999: 20.289 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 3.884 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  16.695 ms/op
                 listUser·p0.9999: 26.666 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   3: 3.879 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.352 ms/op
                 listUser·p0.9999: 20.701 ms/op
                 listUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243156
  mean =      3.949 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4468 
    [ 2.500,  5.000) = 212384 
    [ 5.000,  7.500) = 25202 
    [ 7.500, 10.000) = 573 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.500 ms/op
     p(99.9900) =     25.637 ms/op
     p(99.9990) =     27.810 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.482 ± 5.204  ops/ms
ClientGrpc.existUser                       thrpt       3  10.992 ± 2.363  ops/ms
ClientGrpc.getUser                         thrpt       3  10.588 ± 2.298  ops/ms
ClientGrpc.listUser                        thrpt       3   8.103 ± 4.414  ops/ms
ClientGrpc.createUser                       avgt       3   3.087 ± 1.279   ms/op
ClientGrpc.existUser                        avgt       3   2.955 ± 0.206   ms/op
ClientGrpc.getUser                          avgt       3   3.062 ± 1.203   ms/op
ClientGrpc.listUser                         avgt       3   3.954 ± 1.545   ms/op
ClientGrpc.createUser                     sample  316313   3.035 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.257           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.198           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.002           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.247           ms/op
ClientGrpc.existUser                      sample  329222   2.914 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.618           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.103           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.058           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.137           ms/op
ClientGrpc.getUser                        sample  314615   3.054 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.588           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.299           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.767           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.492           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.137           ms/op
ClientGrpc.listUser                       sample  243156   3.949 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.575           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.500           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.637           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.984           ms/op
