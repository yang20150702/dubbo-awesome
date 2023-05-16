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
# Warmup Iteration   1: 3.760 ops/ms
# Warmup Iteration   2: 8.551 ops/ms
# Warmup Iteration   3: 9.981 ops/ms
Iteration   1: 10.256 ops/ms
Iteration   2: 10.379 ops/ms
Iteration   3: 10.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.308 ±(99.9%) 1.168 ops/ms [Average]
  (min, avg, max) = (10.256, 10.308, 10.379), stdev = 0.064
  CI (99.9%): [9.140, 11.476] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.265 ops/ms
# Warmup Iteration   2: 10.244 ops/ms
# Warmup Iteration   3: 10.695 ops/ms
Iteration   1: 10.889 ops/ms
Iteration   2: 11.069 ops/ms
Iteration   3: 10.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.957 ±(99.9%) 1.784 ops/ms [Average]
  (min, avg, max) = (10.889, 10.957, 11.069), stdev = 0.098
  CI (99.9%): [9.173, 12.741] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.922 ops/ms
# Warmup Iteration   2: 10.064 ops/ms
# Warmup Iteration   3: 10.455 ops/ms
Iteration   1: 10.566 ops/ms
Iteration   2: 10.347 ops/ms
Iteration   3: 10.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.462 ±(99.9%) 2.009 ops/ms [Average]
  (min, avg, max) = (10.347, 10.462, 10.566), stdev = 0.110
  CI (99.9%): [8.453, 12.471] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.362 ops/ms
# Warmup Iteration   2: 7.526 ops/ms
# Warmup Iteration   3: 7.822 ops/ms
Iteration   1: 7.864 ops/ms
Iteration   2: 8.048 ops/ms
Iteration   3: 8.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.992 ±(99.9%) 2.028 ops/ms [Average]
  (min, avg, max) = (7.864, 7.992, 8.065), stdev = 0.111
  CI (99.9%): [5.964, 10.021] (assumes normal distribution)


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
# Warmup Iteration   1: 4.568 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.003 ms/op
Iteration   1: 3.051 ±(99.9%) 0.007 ms/op
Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
Iteration   3: 3.091 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.073 ±(99.9%) 0.373 ms/op [Average]
  (min, avg, max) = (3.051, 3.073, 3.091), stdev = 0.020
  CI (99.9%): [2.701, 3.446] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.113 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.003 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
Iteration   3: 2.987 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.975 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (2.931, 2.975, 3.006), stdev = 0.039
  CI (99.9%): [2.263, 3.687] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.227 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.003 ms/op
Iteration   1: 3.041 ±(99.9%) 0.002 ms/op
Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
Iteration   3: 3.110 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.059 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (3.027, 3.059, 3.110), stdev = 0.044
  CI (99.9%): [2.250, 3.869] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.722 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.174 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.019 ms/op
Iteration   1: 4.031 ±(99.9%) 0.028 ms/op
Iteration   2: 4.045 ±(99.9%) 0.023 ms/op
Iteration   3: 3.983 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.020 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (3.983, 4.020, 4.045), stdev = 0.033
  CI (99.9%): [3.422, 4.617] (assumes normal distribution)


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.008 ms/op
Iteration   1: 3.089 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.262 ms/op
                 createUser·p0.9999: 26.847 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.488 ms/op
                 createUser·p0.999:  7.045 ms/op
                 createUser·p0.9999: 18.726 ms/op
                 createUser·p1.00:   18.940 ms/op

Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.458 ms/op
                 createUser·p0.999:  8.741 ms/op
                 createUser·p0.9999: 26.323 ms/op
                 createUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312011
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13190 
    [ 2.500,  5.000) = 297535 
    [ 5.000,  7.500) = 986 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.422 ms/op
     p(99.9900) =     26.260 ms/op
     p(99.9990) =     27.157 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 4.156 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.005 ms/op
Iteration   1: 2.970 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.414 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   12.517 ms/op

Iteration   2: 2.953 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.247 ms/op
                 existUser·p0.9999: 13.902 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.946 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.711 ms/op
                 existUser·p0.9999: 26.186 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324556
  mean =      2.956 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27059 
    [ 2.500,  5.000) = 296351 
    [ 5.000,  7.500) = 913 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      6.860 ms/op
     p(99.9900) =     21.473 ms/op
     p(99.9990) =     26.378 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 4.665 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
Iteration   1: 3.151 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  9.045 ms/op
                 getUser·p0.9999: 13.037 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   2: 3.089 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.889 ms/op
                 getUser·p0.9999: 15.400 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.849 ms/op
                 getUser·p0.9999: 16.886 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308396
  mean =      3.110 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 341 
    [ 1.250,  2.500) = 12140 
    [ 2.500,  3.750) = 274899 
    [ 3.750,  5.000) = 19698 
    [ 5.000,  6.250) = 652 
    [ 6.250,  7.500) = 374 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.283 ms/op
     p(99.9900) =     16.228 ms/op
     p(99.9990) =     17.332 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 5.844 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.010 ms/op
Iteration   1: 4.064 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.631 ms/op
                 listUser·p0.9999: 19.861 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 4.009 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  14.790 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 4.024 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.142 ms/op
                 listUser·p0.999:  16.374 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238199
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2355 
    [ 2.500,  5.000) = 210794 
    [ 5.000,  7.500) = 23519 
    [ 7.500, 10.000) = 1072 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     15.152 ms/op
     p(99.9900) =     20.525 ms/op
     p(99.9990) =     25.334 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.308 ± 1.168  ops/ms
ClientGrpc.existUser                       thrpt       3  10.957 ± 1.784  ops/ms
ClientGrpc.getUser                         thrpt       3  10.462 ± 2.009  ops/ms
ClientGrpc.listUser                        thrpt       3   7.992 ± 2.028  ops/ms
ClientGrpc.createUser                       avgt       3   3.073 ± 0.373   ms/op
ClientGrpc.existUser                        avgt       3   2.975 ± 0.712   ms/op
ClientGrpc.getUser                          avgt       3   3.059 ± 0.809   ms/op
ClientGrpc.listUser                         avgt       3   4.020 ± 0.597   ms/op
ClientGrpc.createUser                     sample  312011   3.077 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.771           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.422           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.260           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.361           ms/op
ClientGrpc.existUser                      sample  324556   2.956 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.517           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.860           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.473           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.575           ms/op
ClientGrpc.getUser                        sample  308396   3.110 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.715           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.283           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.228           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.383           ms/op
ClientGrpc.listUser                       sample  238199   4.032 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.257           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.152           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.525           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.477           ms/op
