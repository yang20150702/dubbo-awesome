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
# Warmup Iteration   1: 3.790 ops/ms
# Warmup Iteration   2: 8.228 ops/ms
# Warmup Iteration   3: 9.654 ops/ms
Iteration   1: 9.741 ops/ms
Iteration   2: 9.833 ops/ms
Iteration   3: 9.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.757 ±(99.9%) 1.275 ops/ms [Average]
  (min, avg, max) = (9.696, 9.757, 9.833), stdev = 0.070
  CI (99.9%): [8.482, 11.031] (assumes normal distribution)


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
# Warmup Iteration   1: 7.070 ops/ms
# Warmup Iteration   2: 10.098 ops/ms
# Warmup Iteration   3: 10.396 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.449 ops/ms
Iteration   3: 10.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.443 ±(99.9%) 2.726 ops/ms [Average]
  (min, avg, max) = (10.291, 10.443, 10.590), stdev = 0.149
  CI (99.9%): [7.718, 13.169] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.686 ops/ms
# Warmup Iteration   2: 9.934 ops/ms
# Warmup Iteration   3: 9.914 ops/ms
Iteration   1: 9.845 ops/ms
Iteration   2: 10.014 ops/ms
Iteration   3: 10.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.967 ±(99.9%) 1.932 ops/ms [Average]
  (min, avg, max) = (9.845, 9.967, 10.041), stdev = 0.106
  CI (99.9%): [8.034, 11.899] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.191 ops/ms
# Warmup Iteration   2: 7.375 ops/ms
# Warmup Iteration   3: 7.660 ops/ms
Iteration   1: 7.820 ops/ms
Iteration   2: 7.862 ops/ms
Iteration   3: 7.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.854 ±(99.9%) 0.562 ops/ms [Average]
  (min, avg, max) = (7.820, 7.854, 7.880), stdev = 0.031
  CI (99.9%): [7.292, 8.416] (assumes normal distribution)


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.003 ms/op
Iteration   1: 3.237 ±(99.9%) 0.011 ms/op
Iteration   2: 3.244 ±(99.9%) 0.002 ms/op
Iteration   3: 3.270 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.250 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.237, 3.250, 3.270), stdev = 0.017
  CI (99.9%): [2.936, 3.565] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.003 ms/op
Iteration   1: 3.167 ±(99.9%) 0.003 ms/op
Iteration   2: 3.120 ±(99.9%) 0.002 ms/op
Iteration   3: 3.104 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.130 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (3.104, 3.130, 3.167), stdev = 0.032
  CI (99.9%): [2.539, 3.721] (assumes normal distribution)


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
# Warmup Iteration   1: 4.410 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.233 ±(99.9%) 0.003 ms/op
Iteration   1: 3.215 ±(99.9%) 0.002 ms/op
Iteration   2: 3.232 ±(99.9%) 0.001 ms/op
Iteration   3: 3.243 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.230 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (3.215, 3.230, 3.243), stdev = 0.014
  CI (99.9%): [2.973, 3.487] (assumes normal distribution)


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
# Warmup Iteration   1: 5.545 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.011 ms/op
Iteration   1: 4.070 ±(99.9%) 0.019 ms/op
Iteration   2: 4.085 ±(99.9%) 0.015 ms/op
Iteration   3: 4.040 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.065 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (4.040, 4.065, 4.085), stdev = 0.023
  CI (99.9%): [3.646, 4.484] (assumes normal distribution)


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.344 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.007 ms/op
Iteration   1: 3.283 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  9.497 ms/op
                 createUser·p0.9999: 16.458 ms/op
                 createUser·p1.00:   16.695 ms/op

Iteration   2: 3.177 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.759 ms/op
                 createUser·p0.9999: 16.220 ms/op
                 createUser·p1.00:   16.728 ms/op

Iteration   3: 3.309 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   4.607 ms/op
                 createUser·p0.999:  10.645 ms/op
                 createUser·p0.9999: 23.975 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294979
  mean =      3.256 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10712 
    [ 2.500,  5.000) = 282871 
    [ 5.000,  7.500) = 965 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      9.225 ms/op
     p(99.9900) =     23.052 ms/op
     p(99.9990) =     24.217 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 4.115 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
Iteration   1: 3.143 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.447 ms/op
                 existUser·p0.9999: 15.737 ms/op
                 existUser·p1.00:   16.220 ms/op

Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  7.264 ms/op
                 existUser·p0.9999: 18.285 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   3: 3.146 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.381 ms/op
                 existUser·p0.9999: 19.742 ms/op
                 existUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 305270
  mean =      3.144 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26635 
    [ 2.500,  5.000) = 277524 
    [ 5.000,  7.500) = 850 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.371 ms/op
     p(99.9900) =     18.267 ms/op
     p(99.9990) =     20.120 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 4.320 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.007 ms/op
Iteration   1: 3.203 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.465 ms/op
                 getUser·p0.9999: 17.269 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  8.289 ms/op
                 getUser·p0.9999: 26.188 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   3: 3.261 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  8.273 ms/op
                 getUser·p0.9999: 22.826 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 296968
  mean =      3.230 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20109 
    [ 2.500,  5.000) = 275630 
    [ 5.000,  7.500) = 813 
    [ 7.500, 10.000) = 256 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.971 ms/op
     p(99.9900) =     25.798 ms/op
     p(99.9990) =     26.510 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.442 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.126 ±(99.9%) 0.011 ms/op
Iteration   1: 4.102 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.099 ms/op
                 listUser·p0.999:  14.714 ms/op
                 listUser·p0.9999: 28.160 ms/op
                 listUser·p1.00:   30.114 ms/op

Iteration   2: 4.136 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  16.090 ms/op
                 listUser·p0.9999: 29.092 ms/op
                 listUser·p1.00:   29.950 ms/op

Iteration   3: 4.073 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  15.775 ms/op
                 listUser·p0.9999: 21.763 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233800
  mean =      4.103 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1420 
    [ 2.500,  5.000) = 206946 
    [ 5.000,  7.500) = 23687 
    [ 7.500, 10.000) = 1119 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     27.775 ms/op
     p(99.9990) =     30.069 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.757 ± 1.275  ops/ms
ClientGrpc.existUser                       thrpt       3  10.443 ± 2.726  ops/ms
ClientGrpc.getUser                         thrpt       3   9.967 ± 1.932  ops/ms
ClientGrpc.listUser                        thrpt       3   7.854 ± 0.562  ops/ms
ClientGrpc.createUser                       avgt       3   3.250 ± 0.315   ms/op
ClientGrpc.existUser                        avgt       3   3.130 ± 0.591   ms/op
ClientGrpc.getUser                          avgt       3   3.230 ± 0.257   ms/op
ClientGrpc.listUser                         avgt       3   4.065 ± 0.419   ms/op
ClientGrpc.createUser                     sample  294979   3.256 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.647           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.215           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.137           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.225           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.052           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.347           ms/op
ClientGrpc.existUser                      sample  305270   3.144 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.607           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.117           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.850           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.043           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.371           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.267           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.152           ms/op
ClientGrpc.getUser                        sample  296968   3.230 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.746           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.199           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.162           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.971           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.798           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.542           ms/op
ClientGrpc.listUser                       sample  233800   4.103 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.196           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.928           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.516           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.775           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.114           ms/op
