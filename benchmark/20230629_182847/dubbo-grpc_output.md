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
# Warmup Iteration   1: 2.573 ops/ms
# Warmup Iteration   2: 6.134 ops/ms
# Warmup Iteration   3: 7.174 ops/ms
Iteration   1: 7.542 ops/ms
Iteration   2: 7.900 ops/ms
Iteration   3: 7.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.691 ±(99.9%) 3.404 ops/ms [Average]
  (min, avg, max) = (7.542, 7.691, 7.900), stdev = 0.187
  CI (99.9%): [4.287, 11.094] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.217 ops/ms
# Warmup Iteration   2: 7.587 ops/ms
# Warmup Iteration   3: 7.920 ops/ms
Iteration   1: 8.203 ops/ms
Iteration   2: 8.532 ops/ms
Iteration   3: 7.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.238 ±(99.9%) 5.074 ops/ms [Average]
  (min, avg, max) = (7.979, 8.238, 8.532), stdev = 0.278
  CI (99.9%): [3.164, 13.312] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.460 ops/ms
# Warmup Iteration   2: 7.448 ops/ms
# Warmup Iteration   3: 7.754 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 7.997 ops/ms
Iteration   3: 8.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.038 ±(99.9%) 0.846 ops/ms [Average]
  (min, avg, max) = (7.997, 8.038, 8.088), stdev = 0.046
  CI (99.9%): [7.192, 8.884] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ops/ms
# Warmup Iteration   2: 5.422 ops/ms
# Warmup Iteration   3: 5.817 ops/ms
Iteration   1: 5.949 ops/ms
Iteration   2: 5.912 ops/ms
Iteration   3: 5.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.926 ±(99.9%) 0.367 ops/ms [Average]
  (min, avg, max) = (5.912, 5.926, 5.949), stdev = 0.020
  CI (99.9%): [5.559, 6.294] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.099 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.003 ms/op
Iteration   1: 4.031 ±(99.9%) 0.002 ms/op
Iteration   2: 3.978 ±(99.9%) 0.002 ms/op
Iteration   3: 4.018 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.009 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (3.978, 4.009, 4.031), stdev = 0.027
  CI (99.9%): [3.509, 4.510] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.546 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.004 ms/op
Iteration   1: 3.857 ±(99.9%) 0.003 ms/op
Iteration   2: 3.948 ±(99.9%) 0.002 ms/op
Iteration   3: 3.838 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.881 ±(99.9%) 1.073 ms/op [Average]
  (min, avg, max) = (3.838, 3.881, 3.948), stdev = 0.059
  CI (99.9%): [2.808, 4.954] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.155 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.236 ±(99.9%) 0.004 ms/op
Iteration   1: 4.082 ±(99.9%) 0.002 ms/op
Iteration   2: 4.109 ±(99.9%) 0.003 ms/op
Iteration   3: 3.995 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.062 ±(99.9%) 1.086 ms/op [Average]
  (min, avg, max) = (3.995, 4.062, 4.109), stdev = 0.060
  CI (99.9%): [2.976, 5.148] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.972 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 6.034 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.394 ±(99.9%) 0.023 ms/op
Iteration   1: 5.289 ±(99.9%) 0.012 ms/op
Iteration   2: 5.365 ±(99.9%) 0.031 ms/op
Iteration   3: 5.271 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.308 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (5.271, 5.308, 5.365), stdev = 0.050
  CI (99.9%): [4.393, 6.223] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.295 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.011 ms/op
Iteration   1: 3.798 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   7.487 ms/op
                 createUser·p0.999:  13.149 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   2: 3.334 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  7.815 ms/op
                 createUser·p0.9999: 20.054 ms/op
                 createUser·p1.00:   20.120 ms/op

Iteration   3: 3.386 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.498 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  11.336 ms/op
                 createUser·p0.9999: 34.901 ms/op
                 createUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 274759
  mean =      3.494 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11051 
    [ 2.500,  5.000) = 253990 
    [ 5.000,  7.500) = 8523 
    [ 7.500, 10.000) = 777 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.309 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.008 ms/op
Iteration   1: 3.148 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   4.784 ms/op
                 existUser·p0.999:  6.663 ms/op
                 existUser·p0.9999: 11.831 ms/op
                 existUser·p1.00:   12.452 ms/op

Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.355 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  8.241 ms/op
                 existUser·p0.9999: 21.713 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   3: 3.139 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  7.857 ms/op
                 existUser·p0.9999: 16.493 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 307161
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26249 
    [ 2.500,  5.000) = 278149 
    [ 5.000,  7.500) = 2397 
    [ 7.500, 10.000) = 203 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.355 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      7.716 ms/op
     p(99.9900) =     20.925 ms/op
     p(99.9990) =     22.081 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.108 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.009 ms/op
Iteration   1: 3.371 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  8.964 ms/op
                 getUser·p0.9999: 14.074 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   2: 3.426 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 22.402 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   3: 3.446 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   5.291 ms/op
                 getUser·p0.999:  8.195 ms/op
                 getUser·p0.9999: 15.966 ms/op
                 getUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 281114
  mean =      3.414 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9572 
    [ 2.500,  5.000) = 266328 
    [ 5.000,  7.500) = 4690 
    [ 7.500, 10.000) = 312 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     21.620 ms/op
     p(99.9990) =     23.448 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 6.610 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.667 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.552 ±(99.9%) 0.013 ms/op
Iteration   1: 4.578 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   6.619 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  16.531 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 4.580 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   8.495 ms/op
                 listUser·p0.999:  16.139 ms/op
                 listUser·p0.9999: 24.478 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   3: 4.489 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   4.276 ms/op
                 listUser·p0.90:   5.849 ms/op
                 listUser·p0.95:   6.586 ms/op
                 listUser·p0.99:   8.233 ms/op
                 listUser·p0.999:  17.498 ms/op
                 listUser·p0.9999: 21.066 ms/op
                 listUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 211129
  mean =      4.549 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 890 
    [ 2.500,  5.000) = 161999 
    [ 5.000,  7.500) = 43507 
    [ 7.500, 10.000) = 3925 
    [10.000, 12.500) = 388 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     16.609 ms/op
     p(99.9900) =     23.651 ms/op
     p(99.9990) =     27.685 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.691 ± 3.404  ops/ms
ClientGrpc.existUser                       thrpt       3   8.238 ± 5.074  ops/ms
ClientGrpc.getUser                         thrpt       3   8.038 ± 0.846  ops/ms
ClientGrpc.listUser                        thrpt       3   5.926 ± 0.367  ops/ms
ClientGrpc.createUser                       avgt       3   4.009 ± 0.500   ms/op
ClientGrpc.existUser                        avgt       3   3.881 ± 1.073   ms/op
ClientGrpc.getUser                          avgt       3   4.062 ± 1.086   ms/op
ClientGrpc.listUser                         avgt       3   5.308 ± 0.915   ms/op
ClientGrpc.createUser                     sample  274759   3.494 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.498           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.379           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.275           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.059           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.882           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.979           ms/op
ClientGrpc.existUser                      sample  307161   3.125 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.355           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.084           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.940           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.716           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.925           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.217           ms/op
ClientGrpc.getUser                        sample  281114   3.414 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.775           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.346           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.162           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.464           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.962           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.620           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.560           ms/op
ClientGrpc.listUser                       sample  211129   4.549 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.130           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.325           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.438           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.609           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.651           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.082           ms/op
