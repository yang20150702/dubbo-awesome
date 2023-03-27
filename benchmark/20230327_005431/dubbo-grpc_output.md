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
# Warmup Iteration   1: 1.994 ops/ms
# Warmup Iteration   2: 5.420 ops/ms
# Warmup Iteration   3: 6.933 ops/ms
Iteration   1: 7.098 ops/ms
Iteration   2: 6.999 ops/ms
Iteration   3: 7.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.133 ±(99.9%) 2.819 ops/ms [Average]
  (min, avg, max) = (6.999, 7.133, 7.302), stdev = 0.155
  CI (99.9%): [4.314, 9.952] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.610 ops/ms
# Warmup Iteration   2: 5.825 ops/ms
# Warmup Iteration   3: 7.029 ops/ms
Iteration   1: 7.453 ops/ms
Iteration   2: 7.607 ops/ms
Iteration   3: 7.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.465 ±(99.9%) 2.494 ops/ms [Average]
  (min, avg, max) = (7.334, 7.465, 7.607), stdev = 0.137
  CI (99.9%): [4.970, 9.959] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.149 ops/ms
# Warmup Iteration   2: 6.676 ops/ms
# Warmup Iteration   3: 6.855 ops/ms
Iteration   1: 6.915 ops/ms
Iteration   2: 7.011 ops/ms
Iteration   3: 7.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.038 ±(99.9%) 2.532 ops/ms [Average]
  (min, avg, max) = (6.915, 7.038, 7.189), stdev = 0.139
  CI (99.9%): [4.506, 9.570] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.406 ops/ms
# Warmup Iteration   2: 4.895 ops/ms
# Warmup Iteration   3: 5.090 ops/ms
Iteration   1: 5.485 ops/ms
Iteration   2: 5.323 ops/ms
Iteration   3: 5.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.384 ±(99.9%) 1.607 ops/ms [Average]
  (min, avg, max) = (5.323, 5.384, 5.485), stdev = 0.088
  CI (99.9%): [3.777, 6.990] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.859 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.342 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.013 ±(99.9%) 0.006 ms/op
Iteration   1: 4.571 ±(99.9%) 0.003 ms/op
Iteration   2: 4.660 ±(99.9%) 0.003 ms/op
Iteration   3: 5.486 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.906 ±(99.9%) 9.205 ms/op [Average]
  (min, avg, max) = (4.571, 4.906, 5.486), stdev = 0.505
  CI (99.9%): [≈ 0, 14.110] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.795 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.451 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.303 ±(99.9%) 0.003 ms/op
Iteration   1: 4.262 ±(99.9%) 0.004 ms/op
Iteration   2: 4.298 ±(99.9%) 0.004 ms/op
Iteration   3: 4.222 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.261 ±(99.9%) 0.693 ms/op [Average]
  (min, avg, max) = (4.222, 4.261, 4.298), stdev = 0.038
  CI (99.9%): [3.568, 4.953] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.356 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.031 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.622 ±(99.9%) 0.005 ms/op
Iteration   1: 4.956 ±(99.9%) 0.006 ms/op
Iteration   2: 5.736 ±(99.9%) 0.009 ms/op
Iteration   3: 5.035 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.242 ±(99.9%) 7.831 ms/op [Average]
  (min, avg, max) = (4.956, 5.242, 5.736), stdev = 0.429
  CI (99.9%): [≈ 0, 13.073] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.093 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 7.374 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.574 ±(99.9%) 0.017 ms/op
Iteration   1: 6.492 ±(99.9%) 0.015 ms/op
Iteration   2: 6.535 ±(99.9%) 0.013 ms/op
Iteration   3: 6.423 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.483 ±(99.9%) 1.029 ms/op [Average]
  (min, avg, max) = (6.423, 6.483, 6.535), stdev = 0.056
  CI (99.9%): [5.454, 7.512] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.830 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.879 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.037 ±(99.9%) 0.019 ms/op
Iteration   1: 5.468 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   8.004 ms/op
                 createUser·p0.99:   10.638 ms/op
                 createUser·p0.999:  14.951 ms/op
                 createUser·p0.9999: 16.356 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   2: 5.493 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   7.389 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   11.534 ms/op
                 createUser·p0.999:  16.625 ms/op
                 createUser·p0.9999: 22.856 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 4.540 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   4.383 ms/op
                 createUser·p0.90:   5.612 ms/op
                 createUser·p0.95:   6.177 ms/op
                 createUser·p0.99:   8.454 ms/op
                 createUser·p0.999:  14.861 ms/op
                 createUser·p0.9999: 24.079 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 187156
  mean =      5.126 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1753 
    [ 2.500,  5.000) = 103350 
    [ 5.000,  7.500) = 71045 
    [ 7.500, 10.000) = 8652 
    [10.000, 12.500) = 1599 
    [12.500, 15.000) = 534 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      7.717 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     15.251 ms/op
     p(99.9900) =     22.563 ms/op
     p(99.9990) =     24.909 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.455 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.705 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.354 ±(99.9%) 0.012 ms/op
Iteration   1: 4.331 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   4.202 ms/op
                 existUser·p0.90:   5.415 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   7.332 ms/op
                 existUser·p0.999:  10.440 ms/op
                 existUser·p0.9999: 26.812 ms/op
                 existUser·p1.00:   31.228 ms/op

Iteration   2: 4.389 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   5.808 ms/op
                 existUser·p0.99:   7.869 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 21.687 ms/op
                 existUser·p1.00:   22.249 ms/op

Iteration   3: 4.697 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   4.497 ms/op
                 existUser·p0.90:   6.021 ms/op
                 existUser·p0.95:   6.783 ms/op
                 existUser·p0.99:   9.634 ms/op
                 existUser·p0.999:  16.477 ms/op
                 existUser·p0.9999: 20.880 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 214834
  mean =      4.467 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4164 
    [ 2.500,  5.000) = 164071 
    [ 5.000,  7.500) = 43093 
    [ 7.500, 10.000) = 2551 
    [10.000, 12.500) = 585 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      8.323 ms/op
     p(99.9000) =     13.555 ms/op
     p(99.9900) =     22.823 ms/op
     p(99.9990) =     30.614 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.984 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 6.365 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.370 ±(99.9%) 0.022 ms/op
Iteration   1: 4.952 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   4.768 ms/op
                 getUser·p0.90:   6.463 ms/op
                 getUser·p0.95:   7.152 ms/op
                 getUser·p0.99:   9.421 ms/op
                 getUser·p0.999:  17.153 ms/op
                 getUser·p0.9999: 20.122 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   2: 4.977 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   4.809 ms/op
                 getUser·p0.90:   6.332 ms/op
                 getUser·p0.95:   7.045 ms/op
                 getUser·p0.99:   9.306 ms/op
                 getUser·p0.999:  16.696 ms/op
                 getUser·p0.9999: 20.316 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   3: 5.111 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   4.956 ms/op
                 getUser·p0.90:   6.603 ms/op
                 getUser·p0.95:   7.315 ms/op
                 getUser·p0.99:   9.142 ms/op
                 getUser·p0.999:  12.286 ms/op
                 getUser·p0.9999: 22.609 ms/op
                 getUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 191452
  mean =      5.012 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3852 
    [ 2.500,  5.000) = 105262 
    [ 5.000,  7.500) = 75189 
    [ 7.500, 10.000) = 5879 
    [10.000, 12.500) = 876 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.472 ms/op
     p(95.0000) =      7.176 ms/op
     p(99.0000) =      9.273 ms/op
     p(99.9000) =     15.337 ms/op
     p(99.9900) =     22.006 ms/op
     p(99.9990) =     23.077 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.850 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 6.855 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 6.377 ±(99.9%) 0.027 ms/op
Iteration   1: 5.914 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   5.587 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.286 ms/op
                 listUser·p0.999:  17.134 ms/op
                 listUser·p0.9999: 20.262 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 5.743 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.684 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  19.256 ms/op
                 listUser·p0.9999: 23.201 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   3: 5.904 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   5.628 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   10.633 ms/op
                 listUser·p0.999:  20.727 ms/op
                 listUser·p0.9999: 41.037 ms/op
                 listUser·p1.00:   41.484 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 163955
  mean =      5.853 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 42136 
    [ 5.000, 10.000) = 118536 
    [10.000, 15.000) = 2959 
    [15.000, 20.000) = 213 
    [20.000, 25.000) = 79 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.676 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     11.026 ms/op
     p(99.9000) =     18.188 ms/op
     p(99.9900) =     40.042 ms/op
     p(99.9990) =     41.442 ms/op
     p(99.9999) =     41.484 ms/op
    p(100.0000) =     41.484 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.133 ± 2.819  ops/ms
ClientGrpc.existUser                       thrpt       3   7.465 ± 2.494  ops/ms
ClientGrpc.getUser                         thrpt       3   7.038 ± 2.532  ops/ms
ClientGrpc.listUser                        thrpt       3   5.384 ± 1.607  ops/ms
ClientGrpc.createUser                       avgt       3   4.906 ± 9.205   ms/op
ClientGrpc.existUser                        avgt       3   4.261 ± 0.693   ms/op
ClientGrpc.getUser                          avgt       3   5.242 ± 7.831   ms/op
ClientGrpc.listUser                         avgt       3   6.483 ± 1.029   ms/op
ClientGrpc.createUser                     sample  187156   5.126 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.053           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.832           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.717           ms/op
ClientGrpc.createUser:createUser·p0.99    sample          10.486           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.251           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.563           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.166           ms/op
ClientGrpc.existUser                      sample  214834   4.467 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.006           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.603           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.177           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.323           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.555           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.823           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.228           ms/op
ClientGrpc.getUser                        sample  191452   5.012 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.128           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.472           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.176           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.273           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.337           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.006           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.167           ms/op
ClientGrpc.listUser                       sample  163955   5.853 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.466           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.676           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.667           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.026           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.188           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          40.042           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          41.484           ms/op
