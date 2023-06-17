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
# Warmup Iteration   1: 3.050 ops/ms
# Warmup Iteration   2: 7.208 ops/ms
# Warmup Iteration   3: 8.345 ops/ms
Iteration   1: 8.531 ops/ms
Iteration   2: 8.743 ops/ms
Iteration   3: 8.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.667 ±(99.9%) 2.149 ops/ms [Average]
  (min, avg, max) = (8.531, 8.667, 8.743), stdev = 0.118
  CI (99.9%): [6.518, 10.816] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.215 ops/ms
# Warmup Iteration   2: 8.534 ops/ms
# Warmup Iteration   3: 8.833 ops/ms
Iteration   1: 9.263 ops/ms
Iteration   2: 9.118 ops/ms
Iteration   3: 9.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.290 ±(99.9%) 3.406 ops/ms [Average]
  (min, avg, max) = (9.118, 9.290, 9.489), stdev = 0.187
  CI (99.9%): [5.883, 12.696] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.722 ops/ms
# Warmup Iteration   2: 8.150 ops/ms
# Warmup Iteration   3: 8.643 ops/ms
Iteration   1: 8.635 ops/ms
Iteration   2: 8.508 ops/ms
Iteration   3: 8.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.580 ±(99.9%) 1.190 ops/ms [Average]
  (min, avg, max) = (8.508, 8.580, 8.635), stdev = 0.065
  CI (99.9%): [7.390, 9.770] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.806 ops/ms
# Warmup Iteration   2: 6.688 ops/ms
# Warmup Iteration   3: 7.027 ops/ms
Iteration   1: 7.009 ops/ms
Iteration   2: 7.110 ops/ms
Iteration   3: 7.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.149 ±(99.9%) 2.988 ops/ms [Average]
  (min, avg, max) = (7.009, 7.149, 7.329), stdev = 0.164
  CI (99.9%): [4.162, 10.137] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.133 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.004 ms/op
Iteration   1: 3.498 ±(99.9%) 0.004 ms/op
Iteration   2: 3.419 ±(99.9%) 0.004 ms/op
Iteration   3: 3.408 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.442 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (3.408, 3.442, 3.498), stdev = 0.049
  CI (99.9%): [2.544, 4.340] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.548 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.407 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.005 ms/op
Iteration   1: 3.301 ±(99.9%) 0.004 ms/op
Iteration   2: 3.314 ±(99.9%) 0.004 ms/op
Iteration   3: 3.339 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.318 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (3.301, 3.318, 3.339), stdev = 0.019
  CI (99.9%): [2.967, 3.669] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.832 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.003 ms/op
Iteration   1: 3.460 ±(99.9%) 0.004 ms/op
Iteration   2: 3.505 ±(99.9%) 0.003 ms/op
Iteration   3: 3.387 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.451 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (3.387, 3.451, 3.505), stdev = 0.060
  CI (99.9%): [2.362, 4.539] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.793 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.791 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.023 ms/op
Iteration   1: 4.460 ±(99.9%) 0.016 ms/op
Iteration   2: 4.442 ±(99.9%) 0.015 ms/op
Iteration   3: 4.506 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.469 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (4.442, 4.469, 4.506), stdev = 0.033
  CI (99.9%): [3.872, 5.067] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.092 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.008 ms/op
Iteration   1: 3.426 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  8.362 ms/op
                 createUser·p0.9999: 15.903 ms/op
                 createUser·p1.00:   16.400 ms/op

Iteration   2: 3.397 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.681 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.025 ms/op
                 createUser·p0.999:  7.208 ms/op
                 createUser·p0.9999: 20.742 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   3: 3.463 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  8.348 ms/op
                 createUser·p0.9999: 31.736 ms/op
                 createUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 280086
  mean =      3.428 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7037 
    [ 2.500,  5.000) = 270197 
    [ 5.000,  7.500) = 2468 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.014 ms/op
     p(99.9000) =      8.298 ms/op
     p(99.9900) =     31.293 ms/op
     p(99.9990) =     32.591 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.522 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.008 ms/op
Iteration   1: 3.328 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  7.766 ms/op
                 existUser·p0.9999: 14.119 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 3.269 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  9.409 ms/op
                 existUser·p0.9999: 25.494 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   3: 3.290 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.981 ms/op
                 existUser·p0.999:  8.932 ms/op
                 existUser·p0.9999: 22.947 ms/op
                 existUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 291210
  mean =      3.296 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13416 
    [ 2.500,  5.000) = 274472 
    [ 5.000,  7.500) = 2859 
    [ 7.500, 10.000) = 271 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.112 ms/op
     p(99.9000) =      8.447 ms/op
     p(99.9900) =     24.957 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 4.865 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.008 ms/op
Iteration   1: 3.469 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  8.170 ms/op
                 getUser·p0.9999: 13.805 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 3.467 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  8.335 ms/op
                 getUser·p0.9999: 16.009 ms/op
                 getUser·p1.00:   16.564 ms/op

Iteration   3: 3.424 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  7.529 ms/op
                 getUser·p0.9999: 17.159 ms/op
                 getUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 277915
  mean =      3.453 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 8435 
    [ 2.500,  3.750) = 205588 
    [ 3.750,  5.000) = 58920 
    [ 5.000,  6.250) = 3845 
    [ 6.250,  7.500) = 568 
    [ 7.500,  8.750) = 259 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      7.939 ms/op
     p(99.9900) =     16.669 ms/op
     p(99.9990) =     18.627 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 6.236 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.711 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.562 ±(99.9%) 0.013 ms/op
Iteration   1: 4.539 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  13.999 ms/op
                 listUser·p0.9999: 15.646 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   2: 4.542 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.903 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  15.536 ms/op
                 listUser·p0.9999: 23.133 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 4.548 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.349 ms/op
                 listUser·p0.99:   7.975 ms/op
                 listUser·p0.999:  19.104 ms/op
                 listUser·p0.9999: 29.065 ms/op
                 listUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 211318
  mean =      4.543 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 704 
    [ 2.500,  5.000) = 176918 
    [ 5.000,  7.500) = 30359 
    [ 7.500, 10.000) = 2827 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      6.332 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     26.603 ms/op
     p(99.9990) =     29.295 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.667 ± 2.149  ops/ms
ClientGrpc.existUser                       thrpt       3   9.290 ± 3.406  ops/ms
ClientGrpc.getUser                         thrpt       3   8.580 ± 1.190  ops/ms
ClientGrpc.listUser                        thrpt       3   7.149 ± 2.988  ops/ms
ClientGrpc.createUser                       avgt       3   3.442 ± 0.898   ms/op
ClientGrpc.existUser                        avgt       3   3.318 ± 0.351   ms/op
ClientGrpc.getUser                          avgt       3   3.451 ± 1.088   ms/op
ClientGrpc.listUser                         avgt       3   4.469 ± 0.597   ms/op
ClientGrpc.createUser                     sample  280086   3.428 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.681           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.391           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.014           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.298           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.293           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.932           ms/op
ClientGrpc.existUser                      sample  291210   3.296 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.573           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.273           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.121           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.112           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.447           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.957           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.657           ms/op
ClientGrpc.getUser                        sample  277915   3.453 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.846           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.412           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.059           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.431           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.939           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.669           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.711           ms/op
ClientGrpc.listUser                       sample  211318   4.543 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.315           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.399           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.332           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.946           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.516           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.603           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.917           ms/op
