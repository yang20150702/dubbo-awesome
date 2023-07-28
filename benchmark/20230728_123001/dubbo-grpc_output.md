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
# Warmup Iteration   1: 3.765 ops/ms
# Warmup Iteration   2: 8.325 ops/ms
# Warmup Iteration   3: 9.638 ops/ms
Iteration   1: 10.253 ops/ms
Iteration   2: 10.118 ops/ms
Iteration   3: 9.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.111 ±(99.9%) 2.641 ops/ms [Average]
  (min, avg, max) = (9.963, 10.111, 10.253), stdev = 0.145
  CI (99.9%): [7.471, 12.752] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.937 ops/ms
# Warmup Iteration   2: 9.398 ops/ms
# Warmup Iteration   3: 9.572 ops/ms
Iteration   1: 9.843 ops/ms
Iteration   2: 9.987 ops/ms
Iteration   3: 9.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.773 ±(99.9%) 4.674 ops/ms [Average]
  (min, avg, max) = (9.490, 9.773, 9.987), stdev = 0.256
  CI (99.9%): [5.100, 14.447] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.321 ops/ms
# Warmup Iteration   2: 8.343 ops/ms
# Warmup Iteration   3: 9.479 ops/ms
Iteration   1: 9.615 ops/ms
Iteration   2: 9.644 ops/ms
Iteration   3: 9.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.637 ±(99.9%) 0.364 ops/ms [Average]
  (min, avg, max) = (9.615, 9.637, 9.653), stdev = 0.020
  CI (99.9%): [9.273, 10.001] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.953 ops/ms
# Warmup Iteration   2: 6.575 ops/ms
# Warmup Iteration   3: 7.047 ops/ms
Iteration   1: 7.255 ops/ms
Iteration   2: 7.313 ops/ms
Iteration   3: 7.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.334 ±(99.9%) 1.657 ops/ms [Average]
  (min, avg, max) = (7.255, 7.334, 7.433), stdev = 0.091
  CI (99.9%): [5.677, 8.991] (assumes normal distribution)


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
# Warmup Iteration   1: 5.230 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.005 ms/op
Iteration   1: 3.317 ±(99.9%) 0.003 ms/op
Iteration   2: 3.178 ±(99.9%) 0.003 ms/op
Iteration   3: 3.305 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.267 ±(99.9%) 1.407 ms/op [Average]
  (min, avg, max) = (3.178, 3.267, 3.317), stdev = 0.077
  CI (99.9%): [1.860, 4.674] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 5.368 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.002 ms/op
Iteration   1: 3.409 ±(99.9%) 0.002 ms/op
Iteration   2: 3.398 ±(99.9%) 0.002 ms/op
Iteration   3: 3.615 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.474 ±(99.9%) 2.228 ms/op [Average]
  (min, avg, max) = (3.398, 3.474, 3.615), stdev = 0.122
  CI (99.9%): [1.246, 5.702] (assumes normal distribution)


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
# Warmup Iteration   1: 5.464 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.003 ms/op
Iteration   1: 3.618 ±(99.9%) 0.002 ms/op
Iteration   2: 3.292 ±(99.9%) 0.004 ms/op
Iteration   3: 3.231 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.380 ±(99.9%) 3.794 ms/op [Average]
  (min, avg, max) = (3.231, 3.380, 3.618), stdev = 0.208
  CI (99.9%): [≈ 0, 7.174] (assumes normal distribution)


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
# Warmup Iteration   1: 6.224 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.432 ±(99.9%) 0.009 ms/op
Iteration   1: 4.431 ±(99.9%) 0.009 ms/op
Iteration   2: 4.317 ±(99.9%) 0.020 ms/op
Iteration   3: 4.390 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.379 ±(99.9%) 1.053 ms/op [Average]
  (min, avg, max) = (4.317, 4.379, 4.431), stdev = 0.058
  CI (99.9%): [3.327, 5.432] (assumes normal distribution)


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
# Warmup Iteration   1: 5.248 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.008 ms/op
Iteration   1: 3.291 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  9.322 ms/op
                 createUser·p0.9999: 23.953 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   2: 3.326 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  8.643 ms/op
                 createUser·p0.9999: 29.393 ms/op
                 createUser·p1.00:   32.113 ms/op

Iteration   3: 3.253 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  8.156 ms/op
                 createUser·p0.9999: 28.317 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 291778
  mean =      3.290 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9003 
    [ 2.500,  5.000) = 279382 
    [ 5.000,  7.500) = 2842 
    [ 7.500, 10.000) = 295 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =      8.966 ms/op
     p(99.9900) =     28.836 ms/op
     p(99.9990) =     31.987 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.108 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  8.135 ms/op
                 existUser·p0.9999: 31.743 ms/op
                 existUser·p1.00:   33.948 ms/op

Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.324 ms/op
                 existUser·p0.9999: 19.704 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.824 ms/op
                 existUser·p0.9999: 22.692 ms/op
                 existUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311373
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14294 
    [ 2.500,  5.000) = 294926 
    [ 5.000,  7.500) = 1797 
    [ 7.500, 10.000) = 159 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     30.731 ms/op
     p(99.9990) =     31.945 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 4.389 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.007 ms/op
Iteration   1: 3.092 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.168 ms/op
                 getUser·p0.9999: 13.823 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.577 ms/op
                 getUser·p0.9999: 25.156 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.129 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.660 ms/op
                 getUser·p0.999:  7.145 ms/op
                 getUser·p0.9999: 17.760 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308657
  mean =      3.109 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10034 
    [ 2.500,  5.000) = 296603 
    [ 5.000,  7.500) = 1766 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      7.217 ms/op
     p(99.9900) =     24.360 ms/op
     p(99.9990) =     25.485 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 5.566 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.469 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.013 ms/op
Iteration   1: 4.129 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.806 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 25.346 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 4.084 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  17.957 ms/op
                 listUser·p0.9999: 32.905 ms/op
                 listUser·p1.00:   33.423 ms/op

Iteration   3: 4.073 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234396
  mean =      4.095 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1537 
    [ 2.500,  5.000) = 206863 
    [ 5.000,  7.500) = 24244 
    [ 7.500, 10.000) = 1285 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     32.131 ms/op
     p(99.9990) =     33.301 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.111 ± 2.641  ops/ms
ClientGrpc.existUser                       thrpt       3   9.773 ± 4.674  ops/ms
ClientGrpc.getUser                         thrpt       3   9.637 ± 0.364  ops/ms
ClientGrpc.listUser                        thrpt       3   7.334 ± 1.657  ops/ms
ClientGrpc.createUser                       avgt       3   3.267 ± 1.407   ms/op
ClientGrpc.existUser                        avgt       3   3.474 ± 2.228   ms/op
ClientGrpc.getUser                          avgt       3   3.380 ± 3.794   ms/op
ClientGrpc.listUser                         avgt       3   4.379 ± 1.053   ms/op
ClientGrpc.createUser                     sample  291778   3.290 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.551           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.228           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.178           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.120           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.966           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.836           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.113           ms/op
ClientGrpc.existUser                      sample  311373   3.084 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.598           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.060           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.668           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.731           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.948           ms/op
ClientGrpc.getUser                        sample  308657   3.109 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.741           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.217           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.360           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.592           ms/op
ClientGrpc.listUser                       sample  234396   4.095 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.824           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.928           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.465           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.131           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.423           ms/op
