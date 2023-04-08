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
# Warmup Iteration   1: 3.630 ops/ms
# Warmup Iteration   2: 7.990 ops/ms
# Warmup Iteration   3: 9.375 ops/ms
Iteration   1: 9.558 ops/ms
Iteration   2: 9.540 ops/ms
Iteration   3: 9.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.484 ±(99.9%) 2.054 ops/ms [Average]
  (min, avg, max) = (9.354, 9.484, 9.558), stdev = 0.113
  CI (99.9%): [7.430, 11.539] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.633 ops/ms
# Warmup Iteration   2: 9.140 ops/ms
# Warmup Iteration   3: 10.084 ops/ms
Iteration   1: 10.141 ops/ms
Iteration   2: 10.074 ops/ms
Iteration   3: 10.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.111 ±(99.9%) 0.625 ops/ms [Average]
  (min, avg, max) = (10.074, 10.111, 10.141), stdev = 0.034
  CI (99.9%): [9.485, 10.736] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.817 ops/ms
# Warmup Iteration   2: 9.098 ops/ms
# Warmup Iteration   3: 9.431 ops/ms
Iteration   1: 9.403 ops/ms
Iteration   2: 9.278 ops/ms
Iteration   3: 9.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.427 ±(99.9%) 2.961 ops/ms [Average]
  (min, avg, max) = (9.278, 9.427, 9.600), stdev = 0.162
  CI (99.9%): [6.466, 12.388] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.994 ops/ms
# Warmup Iteration   2: 6.942 ops/ms
# Warmup Iteration   3: 7.319 ops/ms
Iteration   1: 7.194 ops/ms
Iteration   2: 7.279 ops/ms
Iteration   3: 7.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.263 ±(99.9%) 1.135 ops/ms [Average]
  (min, avg, max) = (7.194, 7.263, 7.315), stdev = 0.062
  CI (99.9%): [6.128, 8.397] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.111 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.003 ms/op
Iteration   1: 3.437 ±(99.9%) 0.002 ms/op
Iteration   2: 3.282 ±(99.9%) 0.004 ms/op
Iteration   3: 3.330 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.350 ±(99.9%) 1.448 ms/op [Average]
  (min, avg, max) = (3.282, 3.350, 3.437), stdev = 0.079
  CI (99.9%): [1.902, 4.798] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.003 ms/op
Iteration   1: 3.277 ±(99.9%) 0.003 ms/op
Iteration   2: 3.267 ±(99.9%) 0.002 ms/op
Iteration   3: 3.172 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.238 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (3.172, 3.238, 3.277), stdev = 0.058
  CI (99.9%): [2.186, 4.291] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.721 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.003 ms/op
Iteration   1: 3.327 ±(99.9%) 0.002 ms/op
Iteration   2: 3.374 ±(99.9%) 0.005 ms/op
Iteration   3: 3.325 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.342 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (3.325, 3.342, 3.374), stdev = 0.028
  CI (99.9%): [2.838, 3.846] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.037 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.508 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.501 ±(99.9%) 0.010 ms/op
Iteration   1: 4.600 ±(99.9%) 0.025 ms/op
Iteration   2: 4.514 ±(99.9%) 0.010 ms/op
Iteration   3: 4.434 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.516 ±(99.9%) 1.514 ms/op [Average]
  (min, avg, max) = (4.434, 4.516, 4.600), stdev = 0.083
  CI (99.9%): [3.002, 6.030] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.885 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.007 ms/op
Iteration   1: 3.386 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  7.250 ms/op
                 createUser·p0.9999: 22.529 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   2: 3.418 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  9.141 ms/op
                 createUser·p0.9999: 21.910 ms/op
                 createUser·p1.00:   23.822 ms/op

Iteration   3: 3.366 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  11.141 ms/op
                 createUser·p0.9999: 17.596 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 283121
  mean =      3.390 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8511 
    [ 2.500,  5.000) = 271478 
    [ 5.000,  7.500) = 2795 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =      9.337 ms/op
     p(99.9900) =     22.000 ms/op
     p(99.9990) =     23.103 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.752 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.007 ms/op
Iteration   1: 3.206 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  8.507 ms/op
                 existUser·p0.9999: 16.123 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   2: 3.242 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  8.913 ms/op
                 existUser·p0.9999: 13.923 ms/op
                 existUser·p1.00:   15.516 ms/op

Iteration   3: 3.240 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   4.825 ms/op
                 existUser·p0.999:  9.054 ms/op
                 existUser·p0.9999: 16.843 ms/op
                 existUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 297218
  mean =      3.229 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 461 
    [ 1.250,  2.500) = 13717 
    [ 2.500,  3.750) = 257639 
    [ 3.750,  5.000) = 23357 
    [ 5.000,  6.250) = 1206 
    [ 6.250,  7.500) = 355 
    [ 7.500,  8.750) = 154 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 66 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      8.958 ms/op
     p(99.9900) =     16.433 ms/op
     p(99.9990) =     17.571 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.041 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.008 ms/op
Iteration   1: 3.465 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  7.885 ms/op
                 getUser·p0.9999: 15.147 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   2: 3.339 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.985 ms/op
                 getUser·p0.999:  8.111 ms/op
                 getUser·p0.9999: 15.457 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   3: 3.347 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  9.119 ms/op
                 getUser·p0.9999: 26.191 ms/op
                 getUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 284010
  mean =      3.382 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10004 
    [ 2.500,  5.000) = 270776 
    [ 5.000,  7.500) = 2795 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.104 ms/op
     p(99.9000) =      8.036 ms/op
     p(99.9900) =     25.172 ms/op
     p(99.9990) =     27.136 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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
# Warmup Iteration   1: 6.422 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.376 ±(99.9%) 0.012 ms/op
Iteration   1: 4.423 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  14.808 ms/op
                 listUser·p0.9999: 20.745 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 4.411 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.193 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  14.440 ms/op
                 listUser·p0.9999: 19.381 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 4.457 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   4.268 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   6.414 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 22.985 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 216726
  mean =      4.430 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1138 
    [ 2.500,  5.000) = 177906 
    [ 5.000,  7.500) = 35144 
    [ 7.500, 10.000) = 2086 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.242 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     16.201 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.287 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.484 ± 2.054  ops/ms
ClientGrpc.existUser                       thrpt       3  10.111 ± 0.625  ops/ms
ClientGrpc.getUser                         thrpt       3   9.427 ± 2.961  ops/ms
ClientGrpc.listUser                        thrpt       3   7.263 ± 1.135  ops/ms
ClientGrpc.createUser                       avgt       3   3.350 ± 1.448   ms/op
ClientGrpc.existUser                        avgt       3   3.238 ± 1.052   ms/op
ClientGrpc.getUser                          avgt       3   3.342 ± 0.504   ms/op
ClientGrpc.listUser                         avgt       3   4.516 ± 1.514   ms/op
ClientGrpc.createUser                     sample  283121   3.390 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.631           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.355           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.985           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.079           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.337           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.000           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.822           ms/op
ClientGrpc.existUser                      sample  297218   3.229 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.613           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.224           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.686           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.958           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.433           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.121           ms/op
ClientGrpc.getUser                        sample  284010   3.382 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.637           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.346           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.965           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.104           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.036           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.172           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.427           ms/op
ClientGrpc.listUser                       sample  216726   4.430 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.057           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.260           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.242           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.651           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.201           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.282           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.331           ms/op
