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
# Warmup Iteration   1: 4.253 ops/ms
# Warmup Iteration   2: 8.727 ops/ms
# Warmup Iteration   3: 9.706 ops/ms
Iteration   1: 10.343 ops/ms
Iteration   2: 9.957 ops/ms
Iteration   3: 10.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.196 ±(99.9%) 3.810 ops/ms [Average]
  (min, avg, max) = (9.957, 10.196, 10.343), stdev = 0.209
  CI (99.9%): [6.386, 14.006] (assumes normal distribution)


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
# Warmup Iteration   1: 6.820 ops/ms
# Warmup Iteration   2: 10.049 ops/ms
# Warmup Iteration   3: 10.375 ops/ms
Iteration   1: 10.403 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.466 ±(99.9%) 1.976 ops/ms [Average]
  (min, avg, max) = (10.403, 10.466, 10.591), stdev = 0.108
  CI (99.9%): [8.490, 12.442] (assumes normal distribution)


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
# Warmup Iteration   1: 6.392 ops/ms
# Warmup Iteration   2: 9.734 ops/ms
# Warmup Iteration   3: 10.059 ops/ms
Iteration   1: 9.984 ops/ms
Iteration   2: 10.057 ops/ms
Iteration   3: 9.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.914 ±(99.9%) 3.429 ops/ms [Average]
  (min, avg, max) = (9.701, 9.914, 10.057), stdev = 0.188
  CI (99.9%): [6.486, 13.343] (assumes normal distribution)


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
# Warmup Iteration   1: 5.426 ops/ms
# Warmup Iteration   2: 7.383 ops/ms
# Warmup Iteration   3: 7.691 ops/ms
Iteration   1: 7.773 ops/ms
Iteration   2: 8.004 ops/ms
Iteration   3: 7.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.869 ±(99.9%) 2.190 ops/ms [Average]
  (min, avg, max) = (7.773, 7.869, 8.004), stdev = 0.120
  CI (99.9%): [5.679, 10.059] (assumes normal distribution)


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.005 ms/op
Iteration   1: 3.165 ±(99.9%) 0.003 ms/op
Iteration   2: 3.217 ±(99.9%) 0.002 ms/op
Iteration   3: 3.217 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.200 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (3.165, 3.200, 3.217), stdev = 0.030
  CI (99.9%): [2.654, 3.746] (assumes normal distribution)


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.002 ms/op
Iteration   1: 3.047 ±(99.9%) 0.002 ms/op
Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
Iteration   3: 3.084 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.058 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (3.042, 3.058, 3.084), stdev = 0.023
  CI (99.9%): [2.636, 3.479] (assumes normal distribution)


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.002 ms/op
Iteration   1: 3.299 ±(99.9%) 0.002 ms/op
Iteration   2: 3.228 ±(99.9%) 0.002 ms/op
Iteration   3: 3.251 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.260 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (3.228, 3.260, 3.299), stdev = 0.036
  CI (99.9%): [2.604, 3.915] (assumes normal distribution)


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
# Warmup Iteration   1: 5.805 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.011 ms/op
Iteration   1: 4.220 ±(99.9%) 0.010 ms/op
Iteration   2: 4.070 ±(99.9%) 0.013 ms/op
Iteration   3: 4.099 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.130 ±(99.9%) 1.453 ms/op [Average]
  (min, avg, max) = (4.070, 4.130, 4.220), stdev = 0.080
  CI (99.9%): [2.677, 5.583] (assumes normal distribution)


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
# Warmup Iteration   1: 4.312 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.007 ms/op
Iteration   1: 3.259 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  8.528 ms/op
                 createUser·p0.9999: 13.949 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   2: 3.191 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  9.213 ms/op
                 createUser·p0.9999: 14.876 ms/op
                 createUser·p1.00:   15.122 ms/op

Iteration   3: 3.165 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  12.017 ms/op
                 createUser·p0.9999: 33.354 ms/op
                 createUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299479
  mean =      3.205 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20505 
    [ 2.500,  5.000) = 277726 
    [ 5.000,  7.500) = 788 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =     10.371 ms/op
     p(99.9900) =     32.835 ms/op
     p(99.9990) =     33.423 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
Iteration   1: 2.974 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.510 ms/op
                 existUser·p0.9999: 28.745 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.010 ms/op
                 existUser·p0.9999: 25.910 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   3: 3.122 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   4.318 ms/op
                 existUser·p0.999:  10.565 ms/op
                 existUser·p0.9999: 24.297 ms/op
                 existUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314569
  mean =      3.054 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37007 
    [ 2.500,  5.000) = 276578 
    [ 5.000,  7.500) = 654 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.663 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 4.580 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.007 ms/op
Iteration   1: 3.260 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.347 ms/op
                 getUser·p0.9999: 13.969 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 3.281 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.457 ms/op
                 getUser·p0.9999: 14.654 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 292849
  mean =      3.275 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 292 
    [ 1.250,  2.500) = 17358 
    [ 2.500,  3.750) = 216368 
    [ 3.750,  5.000) = 57322 
    [ 5.000,  6.250) = 822 
    [ 6.250,  7.500) = 395 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      7.483 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     19.080 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 6.397 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.472 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.178 ±(99.9%) 0.012 ms/op
Iteration   1: 4.196 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  18.043 ms/op
                 listUser·p0.9999: 20.242 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   2: 4.158 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.602 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 23.111 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 4.087 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.823 ms/op
                 listUser·p0.9999: 24.161 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231665
  mean =      4.146 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1898 
    [ 2.500,  5.000) = 197951 
    [ 5.000,  7.500) = 30133 
    [ 7.500, 10.000) = 1195 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     17.640 ms/op
     p(99.9900) =     23.522 ms/op
     p(99.9990) =     24.467 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.196 ± 3.810  ops/ms
ClientGrpc.existUser                       thrpt       3  10.466 ± 1.976  ops/ms
ClientGrpc.getUser                         thrpt       3   9.914 ± 3.429  ops/ms
ClientGrpc.listUser                        thrpt       3   7.869 ± 2.190  ops/ms
ClientGrpc.createUser                       avgt       3   3.200 ± 0.546   ms/op
ClientGrpc.existUser                        avgt       3   3.058 ± 0.422   ms/op
ClientGrpc.getUser                          avgt       3   3.260 ± 0.655   ms/op
ClientGrpc.listUser                         avgt       3   4.130 ± 1.453   ms/op
ClientGrpc.createUser                     sample  299479   3.205 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.706           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.170           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.096           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.371           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.835           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.423           ms/op
ClientGrpc.existUser                      sample  314569   3.054 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.718           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.663           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.740           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.000           ms/op
ClientGrpc.getUser                        sample  292849   3.275 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.751           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.256           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.002           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.186           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.483           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.974           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.366           ms/op
ClientGrpc.listUser                       sample  231665   4.146 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.602           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.944           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.972           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.640           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.522           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.510           ms/op
