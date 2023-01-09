# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.595 ops/ms
# Warmup Iteration   2: 6.379 ops/ms
# Warmup Iteration   3: 8.046 ops/ms
Iteration   1: 7.971 ops/ms
Iteration   2: 8.093 ops/ms
Iteration   3: 7.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.974 ±(99.9%) 2.160 ops/ms [Average]
  (min, avg, max) = (7.856, 7.974, 8.093), stdev = 0.118
  CI (99.9%): [5.813, 10.134] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.948 ops/ms
# Warmup Iteration   2: 8.044 ops/ms
# Warmup Iteration   3: 8.698 ops/ms
Iteration   1: 8.530 ops/ms
Iteration   2: 8.270 ops/ms
Iteration   3: 8.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.416 ±(99.9%) 2.423 ops/ms [Average]
  (min, avg, max) = (8.270, 8.416, 8.530), stdev = 0.133
  CI (99.9%): [5.993, 10.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.281 ops/ms
# Warmup Iteration   2: 7.720 ops/ms
# Warmup Iteration   3: 7.672 ops/ms
Iteration   1: 7.625 ops/ms
Iteration   2: 7.737 ops/ms
Iteration   3: 7.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.677 ±(99.9%) 1.037 ops/ms [Average]
  (min, avg, max) = (7.625, 7.677, 7.737), stdev = 0.057
  CI (99.9%): [6.640, 8.713] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.389 ops/ms
# Warmup Iteration   2: 5.549 ops/ms
# Warmup Iteration   3: 6.172 ops/ms
Iteration   1: 6.156 ops/ms
Iteration   2: 6.147 ops/ms
Iteration   3: 6.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.212 ±(99.9%) 1.922 ops/ms [Average]
  (min, avg, max) = (6.147, 6.212, 6.334), stdev = 0.105
  CI (99.9%): [4.290, 8.134] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.139 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.300 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.003 ms/op
Iteration   1: 4.297 ±(99.9%) 0.003 ms/op
Iteration   2: 4.252 ±(99.9%) 0.003 ms/op
Iteration   3: 4.007 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.186 ±(99.9%) 2.850 ms/op [Average]
  (min, avg, max) = (4.007, 4.186, 4.297), stdev = 0.156
  CI (99.9%): [1.336, 7.035] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.447 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.312 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.172 ±(99.9%) 0.003 ms/op
Iteration   1: 3.901 ±(99.9%) 0.004 ms/op
Iteration   2: 3.803 ±(99.9%) 0.003 ms/op
Iteration   3: 3.693 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.799 ±(99.9%) 1.899 ms/op [Average]
  (min, avg, max) = (3.693, 3.799, 3.901), stdev = 0.104
  CI (99.9%): [1.900, 5.698] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.967 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.003 ms/op
Iteration   1: 3.935 ±(99.9%) 0.003 ms/op
Iteration   2: 3.915 ±(99.9%) 0.002 ms/op
Iteration   3: 4.154 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.001 ±(99.9%) 2.415 ms/op [Average]
  (min, avg, max) = (3.915, 4.001, 4.154), stdev = 0.132
  CI (99.9%): [1.586, 6.416] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.140 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.186 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.766 ±(99.9%) 0.016 ms/op
Iteration   1: 5.044 ±(99.9%) 0.012 ms/op
Iteration   2: 4.859 ±(99.9%) 0.009 ms/op
Iteration   3: 5.106 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.003 ±(99.9%) 2.349 ms/op [Average]
  (min, avg, max) = (4.859, 5.003, 5.106), stdev = 0.129
  CI (99.9%): [2.654, 7.352] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.694 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.201 ±(99.9%) 0.012 ms/op
Iteration   1: 4.101 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   5.177 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  11.699 ms/op
                 createUser·p0.9999: 14.978 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   2: 4.181 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   4.096 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  14.163 ms/op
                 createUser·p0.9999: 25.036 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 4.208 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   4.178 ms/op
                 createUser·p0.90:   5.267 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  11.090 ms/op
                 createUser·p0.9999: 20.158 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 230577
  mean =      4.163 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4160 
    [ 2.500,  5.000) = 190671 
    [ 5.000,  7.500) = 34695 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     11.646 ms/op
     p(99.9900) =     24.113 ms/op
     p(99.9990) =     25.421 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.697 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.012 ms/op
Iteration   1: 3.959 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  9.903 ms/op
                 existUser·p0.9999: 17.525 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   2: 4.120 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   4.010 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.489 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  9.725 ms/op
                 existUser·p0.9999: 18.619 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   3: 4.009 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   3.949 ms/op
                 existUser·p0.90:   5.054 ms/op
                 existUser·p0.95:   5.341 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  10.788 ms/op
                 existUser·p0.9999: 20.415 ms/op
                 existUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238233
  mean =      4.028 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5652 
    [ 2.500,  5.000) = 204089 
    [ 5.000,  7.500) = 27480 
    [ 7.500, 10.000) = 752 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     10.207 ms/op
     p(99.9900) =     19.749 ms/op
     p(99.9990) =     20.664 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.561 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.525 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.010 ms/op
Iteration   1: 4.114 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   5.218 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  13.158 ms/op
                 getUser·p0.9999: 18.521 ms/op
                 getUser·p1.00:   19.202 ms/op

Iteration   2: 4.187 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   4.076 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  14.356 ms/op
                 getUser·p0.9999: 26.226 ms/op
                 getUser·p1.00:   26.411 ms/op

Iteration   3: 3.999 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   5.448 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  11.208 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 234184
  mean =      4.099 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7382 
    [ 2.500,  5.000) = 193710 
    [ 5.000,  7.500) = 31696 
    [ 7.500, 10.000) = 777 
    [10.000, 12.500) = 356 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     25.873 ms/op
     p(99.9990) =     26.367 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.427 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.691 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.294 ±(99.9%) 0.018 ms/op
Iteration   1: 4.796 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.193 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  14.012 ms/op
                 listUser·p0.9999: 15.471 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   2: 4.817 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.275 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 22.939 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   3: 4.920 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   7.004 ms/op
                 listUser·p0.99:   8.750 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198389
  mean =      4.844 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 524 
    [ 2.500,  5.000) = 132528 
    [ 5.000,  7.500) = 58824 
    [ 7.500, 10.000) = 5415 
    [10.000, 12.500) = 576 
    [12.500, 15.000) = 261 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.226 ms/op
     p(95.0000) =      7.012 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     16.338 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     23.563 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.974 ± 2.160  ops/ms
ClientGrpc.existUser                       thrpt       3   8.416 ± 2.423  ops/ms
ClientGrpc.getUser                         thrpt       3   7.677 ± 1.037  ops/ms
ClientGrpc.listUser                        thrpt       3   6.212 ± 1.922  ops/ms
ClientGrpc.createUser                       avgt       3   4.186 ± 2.850   ms/op
ClientGrpc.existUser                        avgt       3   3.799 ± 1.899   ms/op
ClientGrpc.getUser                          avgt       3   4.001 ± 2.415   ms/op
ClientGrpc.listUser                         avgt       3   5.003 ± 2.349   ms/op
ClientGrpc.createUser                     sample  230577   4.163 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.077           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.235           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.562           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.447           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.646           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.113           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.461           ms/op
ClientGrpc.existUser                      sample  238233   4.028 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.534           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.087           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.390           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.423           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.207           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.749           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.939           ms/op
ClientGrpc.getUser                        sample  234184   4.099 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.585           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.210           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.603           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.758           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.943           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.873           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.411           ms/op
ClientGrpc.listUser                       sample  198389   4.844 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.030           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.913           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.338           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.413           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.724           ms/op
