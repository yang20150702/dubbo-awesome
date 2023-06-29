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
# Warmup Iteration   1: 3.954 ops/ms
# Warmup Iteration   2: 8.486 ops/ms
# Warmup Iteration   3: 9.966 ops/ms
Iteration   1: 10.231 ops/ms
Iteration   2: 10.421 ops/ms
Iteration   3: 10.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.397 ±(99.9%) 2.850 ops/ms [Average]
  (min, avg, max) = (10.231, 10.397, 10.540), stdev = 0.156
  CI (99.9%): [7.548, 13.247] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.325 ops/ms
# Warmup Iteration   2: 10.429 ops/ms
# Warmup Iteration   3: 10.988 ops/ms
Iteration   1: 10.798 ops/ms
Iteration   2: 10.930 ops/ms
Iteration   3: 10.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.871 ±(99.9%) 1.230 ops/ms [Average]
  (min, avg, max) = (10.798, 10.871, 10.930), stdev = 0.067
  CI (99.9%): [9.641, 12.101] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.679 ops/ms
# Warmup Iteration   2: 10.169 ops/ms
# Warmup Iteration   3: 10.339 ops/ms
Iteration   1: 10.401 ops/ms
Iteration   2: 10.416 ops/ms
Iteration   3: 10.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.461 ±(99.9%) 1.663 ops/ms [Average]
  (min, avg, max) = (10.401, 10.461, 10.566), stdev = 0.091
  CI (99.9%): [8.798, 12.125] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.301 ops/ms
# Warmup Iteration   2: 7.706 ops/ms
# Warmup Iteration   3: 7.854 ops/ms
Iteration   1: 8.004 ops/ms
Iteration   2: 8.128 ops/ms
Iteration   3: 7.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.031 ±(99.9%) 1.588 ops/ms [Average]
  (min, avg, max) = (7.961, 8.031, 8.128), stdev = 0.087
  CI (99.9%): [6.443, 9.619] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.336 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.002 ms/op
Iteration   1: 3.027 ±(99.9%) 0.002 ms/op
Iteration   2: 3.028 ±(99.9%) 0.002 ms/op
Iteration   3: 3.028 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.028 ±(99.9%) 0.019 ms/op [Average]
  (min, avg, max) = (3.027, 3.028, 3.028), stdev = 0.001
  CI (99.9%): [3.009, 3.047] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.035 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.003 ms/op
Iteration   1: 2.882 ±(99.9%) 0.003 ms/op
Iteration   2: 2.909 ±(99.9%) 0.002 ms/op
Iteration   3: 2.907 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.900 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (2.882, 2.900, 2.909), stdev = 0.015
  CI (99.9%): [2.626, 3.174] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.100 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.004 ms/op
Iteration   1: 3.056 ±(99.9%) 0.003 ms/op
Iteration   2: 3.060 ±(99.9%) 0.002 ms/op
Iteration   3: 3.034 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.050 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (3.034, 3.050, 3.060), stdev = 0.014
  CI (99.9%): [2.789, 3.310] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.368 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.011 ms/op
Iteration   1: 3.934 ±(99.9%) 0.012 ms/op
Iteration   2: 3.999 ±(99.9%) 0.016 ms/op
Iteration   3: 3.969 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.967 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (3.934, 3.967, 3.999), stdev = 0.032
  CI (99.9%): [3.377, 4.558] (assumes normal distribution)


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
# Warmup Iteration   1: 4.222 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  6.728 ms/op
                 createUser·p0.9999: 19.087 ms/op
                 createUser·p1.00:   19.595 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  8.488 ms/op
                 createUser·p0.9999: 14.410 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  14.828 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314323
  mean =      3.054 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20371 
    [ 2.500,  5.000) = 292627 
    [ 5.000,  7.500) = 886 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.315 ms/op
     p(99.9000) =     10.825 ms/op
     p(99.9900) =     18.448 ms/op
     p(99.9990) =     20.293 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.060 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.005 ms/op
Iteration   1: 2.911 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.963 ms/op
                 existUser·p0.9999: 16.728 ms/op
                 existUser·p1.00:   17.236 ms/op

Iteration   2: 2.954 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  9.414 ms/op
                 existUser·p0.9999: 16.649 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   3: 2.898 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  5.587 ms/op
                 existUser·p0.9999: 15.512 ms/op
                 existUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328911
  mean =      2.921 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1768 
    [ 1.250,  2.500) = 32189 
    [ 2.500,  3.750) = 285604 
    [ 3.750,  5.000) = 8489 
    [ 5.000,  6.250) = 432 
    [ 6.250,  7.500) = 167 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =     16.489 ms/op
     p(99.9990) =     17.194 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.436 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
Iteration   1: 2.974 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.198 ms/op
                 getUser·p0.9999: 16.187 ms/op
                 getUser·p1.00:   16.564 ms/op

Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.695 ms/op
                 getUser·p0.999:  10.303 ms/op
                 getUser·p0.9999: 14.216 ms/op
                 getUser·p1.00:   15.761 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.561 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.828 ms/op
                 getUser·p0.9999: 31.468 ms/op
                 getUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317182
  mean =      3.025 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27140 
    [ 2.500,  5.000) = 288705 
    [ 5.000,  7.500) = 1034 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.344 ms/op
     p(99.9900) =     30.296 ms/op
     p(99.9990) =     32.369 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 5.101 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.012 ms/op
Iteration   1: 4.003 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 3.954 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  16.046 ms/op
                 listUser·p0.9999: 24.598 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241742
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2307 
    [ 2.500,  5.000) = 219645 
    [ 5.000,  7.500) = 18527 
    [ 7.500, 10.000) = 795 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     15.377 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     26.954 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.397 ± 2.850  ops/ms
ClientGrpc.existUser                       thrpt       3  10.871 ± 1.230  ops/ms
ClientGrpc.getUser                         thrpt       3  10.461 ± 1.663  ops/ms
ClientGrpc.listUser                        thrpt       3   8.031 ± 1.588  ops/ms
ClientGrpc.createUser                       avgt       3   3.028 ± 0.019   ms/op
ClientGrpc.existUser                        avgt       3   2.900 ± 0.274   ms/op
ClientGrpc.getUser                          avgt       3   3.050 ± 0.261   ms/op
ClientGrpc.listUser                         avgt       3   3.967 ± 0.591   ms/op
ClientGrpc.createUser                     sample  314323   3.054 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.653           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.315           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.825           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.448           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.853           ms/op
ClientGrpc.existUser                      sample  328911   2.921 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.616           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.816           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.489           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.236           ms/op
ClientGrpc.getUser                        sample  317182   3.025 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.561           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.344           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.296           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.030           ms/op
ClientGrpc.listUser                       sample  241742   3.972 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.016           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.377           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.839           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.296           ms/op
