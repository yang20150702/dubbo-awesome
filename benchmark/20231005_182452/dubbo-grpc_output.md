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
# Warmup Iteration   1: 4.288 ops/ms
# Warmup Iteration   2: 8.899 ops/ms
# Warmup Iteration   3: 9.726 ops/ms
Iteration   1: 10.122 ops/ms
Iteration   2: 10.144 ops/ms
Iteration   3: 10.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.186 ±(99.9%) 1.678 ops/ms [Average]
  (min, avg, max) = (10.122, 10.186, 10.291), stdev = 0.092
  CI (99.9%): [8.508, 11.864] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.425 ops/ms
# Warmup Iteration   2: 10.537 ops/ms
# Warmup Iteration   3: 10.714 ops/ms
Iteration   1: 10.781 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.799 ±(99.9%) 1.943 ops/ms [Average]
  (min, avg, max) = (10.702, 10.799, 10.913), stdev = 0.106
  CI (99.9%): [8.856, 12.742] (assumes normal distribution)


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
# Warmup Iteration   1: 7.146 ops/ms
# Warmup Iteration   2: 10.205 ops/ms
# Warmup Iteration   3: 10.421 ops/ms
Iteration   1: 10.320 ops/ms
Iteration   2: 10.379 ops/ms
Iteration   3: 10.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.421 ±(99.9%) 2.312 ops/ms [Average]
  (min, avg, max) = (10.320, 10.421, 10.563), stdev = 0.127
  CI (99.9%): [8.109, 12.733] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.232 ops/ms
# Warmup Iteration   2: 8.543 ops/ms
# Warmup Iteration   3: 8.472 ops/ms
Iteration   1: 8.468 ops/ms
Iteration   2: 9.087 ops/ms
Iteration   3: 8.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.731 ±(99.9%) 5.830 ops/ms [Average]
  (min, avg, max) = (8.468, 8.731, 9.087), stdev = 0.320
  CI (99.9%): [2.901, 14.561] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.157 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.002 ms/op
Iteration   1: 3.092 ±(99.9%) 0.002 ms/op
Iteration   2: 3.043 ±(99.9%) 0.001 ms/op
Iteration   3: 3.080 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.072 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (3.043, 3.072, 3.092), stdev = 0.025
  CI (99.9%): [2.610, 3.533] (assumes normal distribution)


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.001 ms/op
Iteration   2: 2.974 ±(99.9%) 0.002 ms/op
Iteration   3: 2.904 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.970 ±(99.9%) 1.163 ms/op [Average]
  (min, avg, max) = (2.904, 2.970, 3.031), stdev = 0.064
  CI (99.9%): [1.807, 4.133] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.035 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.002 ms/op
Iteration   1: 3.055 ±(99.9%) 0.002 ms/op
Iteration   2: 3.057 ±(99.9%) 0.001 ms/op
Iteration   3: 3.039 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.050 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (3.039, 3.050, 3.057), stdev = 0.010
  CI (99.9%): [2.876, 3.225] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.228 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.025 ms/op
Iteration   1: 3.761 ±(99.9%) 0.018 ms/op
Iteration   2: 3.775 ±(99.9%) 0.030 ms/op
Iteration   3: 3.737 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.758 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (3.737, 3.758, 3.775), stdev = 0.019
  CI (99.9%): [3.410, 4.105] (assumes normal distribution)


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.217 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  8.487 ms/op
                 createUser·p0.9999: 15.192 ms/op
                 createUser·p1.00:   15.434 ms/op

Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  12.837 ms/op
                 createUser·p0.9999: 16.253 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   3: 3.060 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  6.874 ms/op
                 createUser·p0.9999: 36.307 ms/op
                 createUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316316
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18450 
    [ 2.500,  5.000) = 296438 
    [ 5.000,  7.500) = 1031 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.217 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =     10.306 ms/op
     p(99.9900) =     35.717 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.294 ms/op
                 existUser·p0.9999: 11.087 ms/op
                 existUser·p1.00:   11.698 ms/op

Iteration   2: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.479 ms/op
                 existUser·p0.9999: 12.500 ms/op
                 existUser·p1.00:   12.665 ms/op

Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.607 ms/op
                 existUser·p0.999:  9.470 ms/op
                 existUser·p0.9999: 14.799 ms/op
                 existUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324060
  mean =      2.961 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1364 
    [ 1.250,  2.500) = 25861 
    [ 2.500,  3.750) = 286381 
    [ 3.750,  5.000) = 8711 
    [ 5.000,  6.250) = 959 
    [ 6.250,  7.500) = 415 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.847 ms/op
     p(99.9900) =     13.805 ms/op
     p(99.9990) =     15.160 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.961 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.006 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  9.307 ms/op
                 getUser·p0.9999: 11.252 ms/op
                 getUser·p1.00:   11.567 ms/op

Iteration   2: 3.155 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.510 ms/op
                 getUser·p0.9999: 12.328 ms/op
                 getUser·p1.00:   12.730 ms/op

Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.600 ms/op
                 getUser·p0.9999: 14.342 ms/op
                 getUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306612
  mean =      3.131 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 569 
    [ 1.250,  2.500) = 9924 
    [ 2.500,  3.750) = 267260 
    [ 3.750,  5.000) = 27373 
    [ 5.000,  6.250) = 761 
    [ 6.250,  7.500) = 350 
    [ 7.500,  8.750) = 137 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.999 ms/op
     p(99.9900) =     14.041 ms/op
     p(99.9990) =     14.450 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.009 ms/op
Iteration   1: 3.799 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.349 ms/op
                 listUser·p0.999:  12.452 ms/op
                 listUser·p0.9999: 16.049 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   2: 3.708 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.308 ms/op
                 listUser·p0.999:  12.419 ms/op
                 listUser·p0.9999: 15.808 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   3: 3.695 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  13.363 ms/op
                 listUser·p0.9999: 20.316 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 257006
  mean =      3.733 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5094 
    [ 2.500,  5.000) = 238489 
    [ 5.000,  7.500) = 12511 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.150 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     12.780 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.186 ± 1.678  ops/ms
ClientGrpc.existUser                       thrpt       3  10.799 ± 1.943  ops/ms
ClientGrpc.getUser                         thrpt       3  10.421 ± 2.312  ops/ms
ClientGrpc.listUser                        thrpt       3   8.731 ± 5.830  ops/ms
ClientGrpc.createUser                       avgt       3   3.072 ± 0.461   ms/op
ClientGrpc.existUser                        avgt       3   2.970 ± 1.163   ms/op
ClientGrpc.getUser                          avgt       3   3.050 ± 0.174   ms/op
ClientGrpc.listUser                         avgt       3   3.758 ± 0.347   ms/op
ClientGrpc.createUser                     sample  316316   3.035 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.217           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.306           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.717           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.504           ms/op
ClientGrpc.existUser                      sample  324060   2.961 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.701           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.847           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.805           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.368           ms/op
ClientGrpc.getUser                        sample  306612   3.131 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.614           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.999           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.041           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.696           ms/op
ClientGrpc.listUser                       sample  257006   3.733 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.834           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.650           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.150           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.349           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.780           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.973           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.414           ms/op
