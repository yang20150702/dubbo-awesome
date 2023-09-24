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
# Warmup Iteration   1: 3.220 ops/ms
# Warmup Iteration   2: 7.215 ops/ms
# Warmup Iteration   3: 8.576 ops/ms
Iteration   1: 8.820 ops/ms
Iteration   2: 9.162 ops/ms
Iteration   3: 9.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.257 ±(99.9%) 8.972 ops/ms [Average]
  (min, avg, max) = (8.820, 9.257, 9.789), stdev = 0.492
  CI (99.9%): [0.284, 18.229] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.716 ops/ms
# Warmup Iteration   2: 9.238 ops/ms
# Warmup Iteration   3: 9.714 ops/ms
Iteration   1: 10.054 ops/ms
Iteration   2: 10.068 ops/ms
Iteration   3: 9.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.984 ±(99.9%) 2.425 ops/ms [Average]
  (min, avg, max) = (9.831, 9.984, 10.068), stdev = 0.133
  CI (99.9%): [7.559, 12.410] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.498 ops/ms
# Warmup Iteration   2: 9.188 ops/ms
# Warmup Iteration   3: 9.422 ops/ms
Iteration   1: 9.672 ops/ms
Iteration   2: 9.575 ops/ms
Iteration   3: 9.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.439 ±(99.9%) 5.895 ops/ms [Average]
  (min, avg, max) = (9.070, 9.439, 9.672), stdev = 0.323
  CI (99.9%): [3.543, 15.334] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.889 ops/ms
# Warmup Iteration   2: 6.526 ops/ms
# Warmup Iteration   3: 7.127 ops/ms
Iteration   1: 7.372 ops/ms
Iteration   2: 7.494 ops/ms
Iteration   3: 7.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.383 ±(99.9%) 1.934 ops/ms [Average]
  (min, avg, max) = (7.283, 7.383, 7.494), stdev = 0.106
  CI (99.9%): [5.450, 9.317] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.277 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.008 ms/op
Iteration   1: 3.512 ±(99.9%) 0.002 ms/op
Iteration   2: 3.524 ±(99.9%) 0.002 ms/op
Iteration   3: 3.399 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.478 ±(99.9%) 1.263 ms/op [Average]
  (min, avg, max) = (3.399, 3.478, 3.524), stdev = 0.069
  CI (99.9%): [2.215, 4.741] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.584 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.003 ms/op
Iteration   1: 3.254 ±(99.9%) 0.002 ms/op
Iteration   2: 3.225 ±(99.9%) 0.002 ms/op
Iteration   3: 3.247 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.242 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.225, 3.242, 3.254), stdev = 0.015
  CI (99.9%): [2.968, 3.516] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.778 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.003 ms/op
Iteration   1: 3.396 ±(99.9%) 0.004 ms/op
Iteration   2: 3.381 ±(99.9%) 0.002 ms/op
Iteration   3: 3.384 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.387 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (3.381, 3.387, 3.396), stdev = 0.008
  CI (99.9%): [3.240, 3.535] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.199 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.496 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.286 ±(99.9%) 0.008 ms/op
Iteration   1: 4.184 ±(99.9%) 0.024 ms/op
Iteration   2: 4.266 ±(99.9%) 0.016 ms/op
Iteration   3: 4.252 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.234 ±(99.9%) 0.797 ms/op [Average]
  (min, avg, max) = (4.184, 4.234, 4.266), stdev = 0.044
  CI (99.9%): [3.437, 5.031] (assumes normal distribution)


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.008 ms/op
Iteration   1: 3.440 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.104 ms/op
                 createUser·p0.999:  8.651 ms/op
                 createUser·p0.9999: 12.070 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   2: 3.411 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  7.686 ms/op
                 createUser·p0.9999: 16.105 ms/op
                 createUser·p1.00:   16.384 ms/op

Iteration   3: 3.419 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  10.614 ms/op
                 createUser·p0.9999: 17.573 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 280290
  mean =      3.423 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 5721 
    [ 2.500,  3.750) = 204479 
    [ 3.750,  5.000) = 67599 
    [ 5.000,  6.250) = 1379 
    [ 6.250,  7.500) = 535 
    [ 7.500,  8.750) = 219 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =      9.006 ms/op
     p(99.9900) =     16.842 ms/op
     p(99.9990) =     18.855 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.395 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.006 ms/op
Iteration   1: 3.436 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  7.509 ms/op
                 existUser·p0.9999: 13.971 ms/op
                 existUser·p1.00:   16.286 ms/op

Iteration   2: 3.228 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  9.027 ms/op
                 existUser·p0.9999: 14.270 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   3: 3.152 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.043 ms/op
                 existUser·p0.9999: 17.451 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 293573
  mean =      3.268 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 321 
    [ 1.250,  2.500) = 11644 
    [ 2.500,  3.750) = 239086 
    [ 3.750,  5.000) = 40560 
    [ 5.000,  6.250) = 1129 
    [ 6.250,  7.500) = 476 
    [ 7.500,  8.750) = 146 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      7.856 ms/op
     p(99.9900) =     16.534 ms/op
     p(99.9990) =     17.832 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.804 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.008 ms/op
Iteration   1: 3.369 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 17.187 ms/op
                 getUser·p1.00:   19.038 ms/op

Iteration   2: 3.361 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.666 ms/op
                 getUser·p0.9999: 14.647 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   3: 3.354 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  8.352 ms/op
                 getUser·p0.9999: 19.479 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 285552
  mean =      3.361 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8906 
    [ 2.500,  5.000) = 273923 
    [ 5.000,  7.500) = 2159 
    [ 7.500, 10.000) = 356 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     19.126 ms/op
     p(99.9990) =     19.544 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 5.363 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.705 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.010 ms/op
Iteration   1: 4.267 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   4.149 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 16.081 ms/op
                 listUser·p1.00:   25.494 ms/op

Iteration   2: 4.122 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   3: 4.179 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 20.731 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229269
  mean =      4.188 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 657 
    [ 2.500,  5.000) = 212037 
    [ 5.000,  7.500) = 14931 
    [ 7.500, 10.000) = 1160 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     14.413 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     25.343 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.257 ± 8.972  ops/ms
ClientGrpc.existUser                       thrpt       3   9.984 ± 2.425  ops/ms
ClientGrpc.getUser                         thrpt       3   9.439 ± 5.895  ops/ms
ClientGrpc.listUser                        thrpt       3   7.383 ± 1.934  ops/ms
ClientGrpc.createUser                       avgt       3   3.478 ± 1.263   ms/op
ClientGrpc.existUser                        avgt       3   3.242 ± 0.274   ms/op
ClientGrpc.getUser                          avgt       3   3.387 ± 0.148   ms/op
ClientGrpc.listUser                         avgt       3   4.234 ± 0.797   ms/op
ClientGrpc.createUser                     sample  280290   3.423 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.811           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.375           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.080           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.841           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.006           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.842           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.973           ms/op
ClientGrpc.existUser                      sample  293573   3.268 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.703           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.211           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.856           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.534           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.924           ms/op
ClientGrpc.getUser                        sample  285552   3.361 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.640           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.305           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.964           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.487           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.126           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  229269   4.188 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.901           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.100           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.413           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.890           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.494           ms/op
