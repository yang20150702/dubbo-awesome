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
# Warmup Iteration   1: 3.929 ops/ms
# Warmup Iteration   2: 8.583 ops/ms
# Warmup Iteration   3: 9.768 ops/ms
Iteration   1: 9.691 ops/ms
Iteration   2: 9.873 ops/ms
Iteration   3: 9.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.761 ±(99.9%) 1.785 ops/ms [Average]
  (min, avg, max) = (9.691, 9.761, 9.873), stdev = 0.098
  CI (99.9%): [7.976, 11.546] (assumes normal distribution)


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
# Warmup Iteration   1: 6.984 ops/ms
# Warmup Iteration   2: 10.413 ops/ms
# Warmup Iteration   3: 10.487 ops/ms
Iteration   1: 10.549 ops/ms
Iteration   2: 10.316 ops/ms
Iteration   3: 10.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.472 ±(99.9%) 2.461 ops/ms [Average]
  (min, avg, max) = (10.316, 10.472, 10.551), stdev = 0.135
  CI (99.9%): [8.011, 12.933] (assumes normal distribution)


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
# Warmup Iteration   1: 6.564 ops/ms
# Warmup Iteration   2: 9.718 ops/ms
# Warmup Iteration   3: 9.762 ops/ms
Iteration   1: 10.021 ops/ms
Iteration   2: 10.036 ops/ms
Iteration   3: 9.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.959 ±(99.9%) 2.205 ops/ms [Average]
  (min, avg, max) = (9.820, 9.959, 10.036), stdev = 0.121
  CI (99.9%): [7.754, 12.164] (assumes normal distribution)


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
# Warmup Iteration   1: 6.056 ops/ms
# Warmup Iteration   2: 7.501 ops/ms
# Warmup Iteration   3: 7.552 ops/ms
Iteration   1: 7.704 ops/ms
Iteration   2: 7.912 ops/ms
Iteration   3: 7.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.867 ±(99.9%) 2.648 ops/ms [Average]
  (min, avg, max) = (7.704, 7.867, 7.983), stdev = 0.145
  CI (99.9%): [5.219, 10.515] (assumes normal distribution)


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
# Warmup Iteration   1: 4.593 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.390 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.011 ms/op
Iteration   1: 3.350 ±(99.9%) 0.002 ms/op
Iteration   2: 3.325 ±(99.9%) 0.001 ms/op
Iteration   3: 3.247 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.307 ±(99.9%) 0.978 ms/op [Average]
  (min, avg, max) = (3.247, 3.307, 3.350), stdev = 0.054
  CI (99.9%): [2.330, 4.285] (assumes normal distribution)


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
# Warmup Iteration   1: 4.207 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.002 ms/op
Iteration   1: 3.138 ±(99.9%) 0.002 ms/op
Iteration   2: 3.151 ±(99.9%) 0.002 ms/op
Iteration   3: 3.096 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.128 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.096, 3.128, 3.151), stdev = 0.029
  CI (99.9%): [2.607, 3.650] (assumes normal distribution)


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.003 ms/op
Iteration   1: 3.259 ±(99.9%) 0.003 ms/op
Iteration   2: 3.198 ±(99.9%) 0.003 ms/op
Iteration   3: 3.252 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.236 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (3.198, 3.236, 3.259), stdev = 0.033
  CI (99.9%): [2.627, 3.846] (assumes normal distribution)


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
# Warmup Iteration   1: 5.951 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.013 ms/op
Iteration   1: 4.200 ±(99.9%) 0.015 ms/op
Iteration   2: 3.943 ±(99.9%) 0.008 ms/op
Iteration   3: 4.123 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.089 ±(99.9%) 2.398 ms/op [Average]
  (min, avg, max) = (3.943, 4.089, 4.200), stdev = 0.131
  CI (99.9%): [1.691, 6.487] (assumes normal distribution)


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
# Warmup Iteration   1: 4.582 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.007 ms/op
Iteration   1: 3.227 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  7.028 ms/op
                 createUser·p0.9999: 13.815 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   2: 3.272 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.208 ms/op
                 createUser·p0.9999: 16.260 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   3: 3.142 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  10.637 ms/op
                 createUser·p0.9999: 26.372 ms/op
                 createUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298591
  mean =      3.213 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16852 
    [ 2.500,  5.000) = 280340 
    [ 5.000,  7.500) = 1071 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.848 ms/op
     p(99.9900) =     19.239 ms/op
     p(99.9990) =     26.608 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.126 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.496 ms/op
                 existUser·p0.9999: 18.014 ms/op
                 existUser·p1.00:   18.612 ms/op

Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.034 ms/op
                 existUser·p0.9999: 15.303 ms/op
                 existUser·p1.00:   15.663 ms/op

Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  9.864 ms/op
                 existUser·p0.9999: 15.981 ms/op
                 existUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 308804
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1062 
    [ 1.250,  2.500) = 32993 
    [ 2.500,  3.750) = 233924 
    [ 3.750,  5.000) = 39829 
    [ 5.000,  6.250) = 458 
    [ 6.250,  7.500) = 204 
    [ 7.500,  8.750) = 96 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 61 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.655 ms/op
     p(99.9900) =     17.404 ms/op
     p(99.9990) =     18.544 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 4.429 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.007 ms/op
Iteration   1: 3.195 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  10.762 ms/op
                 getUser·p0.9999: 13.369 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 3.298 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.455 ms/op
                 getUser·p0.9999: 15.088 ms/op
                 getUser·p1.00:   15.483 ms/op

Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  9.618 ms/op
                 getUser·p0.9999: 29.227 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 293865
  mean =      3.264 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16624 
    [ 2.500,  5.000) = 275781 
    [ 5.000,  7.500) = 1088 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      8.882 ms/op
     p(99.9900) =     28.417 ms/op
     p(99.9990) =     29.642 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 5.122 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.134 ±(99.9%) 0.011 ms/op
Iteration   1: 4.105 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  14.064 ms/op
                 listUser·p0.9999: 26.464 ms/op
                 listUser·p1.00:   27.329 ms/op

Iteration   2: 4.173 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.132 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 25.275 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   3: 4.152 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.076 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 18.992 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231554
  mean =      4.143 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1675 
    [ 2.500,  5.000) = 199513 
    [ 5.000,  7.500) = 28836 
    [ 7.500, 10.000) = 1097 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     15.785 ms/op
     p(99.9900) =     25.544 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.761 ± 1.785  ops/ms
ClientGrpc.existUser                       thrpt       3  10.472 ± 2.461  ops/ms
ClientGrpc.getUser                         thrpt       3   9.959 ± 2.205  ops/ms
ClientGrpc.listUser                        thrpt       3   7.867 ± 2.648  ops/ms
ClientGrpc.createUser                       avgt       3   3.307 ± 0.978   ms/op
ClientGrpc.existUser                        avgt       3   3.128 ± 0.521   ms/op
ClientGrpc.getUser                          avgt       3   3.236 ± 0.610   ms/op
ClientGrpc.listUser                         avgt       3   4.089 ± 2.398   ms/op
ClientGrpc.createUser                     sample  298591   3.213 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.686           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.178           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.071           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.848           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.239           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.706           ms/op
ClientGrpc.existUser                      sample  308804   3.111 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.739           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.092           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.018           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.655           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.404           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.612           ms/op
ClientGrpc.getUser                        sample  293865   3.264 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.871           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.236           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.981           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.182           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.882           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.417           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.048           ms/op
ClientGrpc.listUser                       sample  231554   4.143 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.087           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.961           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.972           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.785           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.544           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.394           ms/op
