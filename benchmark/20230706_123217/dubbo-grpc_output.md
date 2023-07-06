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
# Warmup Iteration   1: 2.269 ops/ms
# Warmup Iteration   2: 5.685 ops/ms
# Warmup Iteration   3: 7.278 ops/ms
Iteration   1: 7.408 ops/ms
Iteration   2: 7.377 ops/ms
Iteration   3: 7.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.411 ±(99.9%) 0.642 ops/ms [Average]
  (min, avg, max) = (7.377, 7.411, 7.447), stdev = 0.035
  CI (99.9%): [6.769, 8.053] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.844 ops/ms
# Warmup Iteration   2: 7.224 ops/ms
# Warmup Iteration   3: 8.228 ops/ms
Iteration   1: 8.601 ops/ms
Iteration   2: 8.413 ops/ms
Iteration   3: 8.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.504 ±(99.9%) 1.712 ops/ms [Average]
  (min, avg, max) = (8.413, 8.504, 8.601), stdev = 0.094
  CI (99.9%): [6.792, 10.216] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.358 ops/ms
# Warmup Iteration   2: 7.004 ops/ms
# Warmup Iteration   3: 7.377 ops/ms
Iteration   1: 7.718 ops/ms
Iteration   2: 7.410 ops/ms
Iteration   3: 7.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.570 ±(99.9%) 2.814 ops/ms [Average]
  (min, avg, max) = (7.410, 7.570, 7.718), stdev = 0.154
  CI (99.9%): [4.756, 10.384] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.863 ops/ms
# Warmup Iteration   2: 5.230 ops/ms
# Warmup Iteration   3: 5.533 ops/ms
Iteration   1: 5.647 ops/ms
Iteration   2: 5.887 ops/ms
Iteration   3: 5.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.814 ±(99.9%) 2.641 ops/ms [Average]
  (min, avg, max) = (5.647, 5.814, 5.907), stdev = 0.145
  CI (99.9%): [3.172, 8.455] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.054 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.698 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.375 ±(99.9%) 0.006 ms/op
Iteration   1: 4.411 ±(99.9%) 0.003 ms/op
Iteration   2: 4.428 ±(99.9%) 0.003 ms/op
Iteration   3: 4.635 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.491 ±(99.9%) 2.279 ms/op [Average]
  (min, avg, max) = (4.411, 4.491, 4.635), stdev = 0.125
  CI (99.9%): [2.212, 6.770] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.272 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.003 ms/op
Iteration   1: 3.825 ±(99.9%) 0.005 ms/op
Iteration   2: 3.753 ±(99.9%) 0.003 ms/op
Iteration   3: 3.836 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.805 ±(99.9%) 0.818 ms/op [Average]
  (min, avg, max) = (3.753, 3.805, 3.836), stdev = 0.045
  CI (99.9%): [2.987, 4.622] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.328 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.664 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.536 ±(99.9%) 0.003 ms/op
Iteration   1: 4.336 ±(99.9%) 0.003 ms/op
Iteration   2: 4.273 ±(99.9%) 0.003 ms/op
Iteration   3: 4.211 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.273 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (4.211, 4.273, 4.336), stdev = 0.063
  CI (99.9%): [3.130, 5.416] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.722 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.796 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.470 ±(99.9%) 0.009 ms/op
Iteration   1: 5.281 ±(99.9%) 0.017 ms/op
Iteration   2: 5.293 ±(99.9%) 0.015 ms/op
Iteration   3: 5.256 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.277 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (5.256, 5.277, 5.293), stdev = 0.019
  CI (99.9%): [4.938, 5.616] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.255 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.716 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.015 ms/op
Iteration   1: 4.450 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  10.866 ms/op
                 createUser·p0.9999: 24.111 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   2: 4.394 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   7.741 ms/op
                 createUser·p0.999:  16.790 ms/op
                 createUser·p0.9999: 27.825 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   3: 4.243 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   4.157 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  13.697 ms/op
                 createUser·p0.9999: 28.128 ms/op
                 createUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 220203
  mean =      4.361 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4611 
    [ 2.500,  5.000) = 172137 
    [ 5.000,  7.500) = 41076 
    [ 7.500, 10.000) = 1781 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     15.283 ms/op
     p(99.9900) =     27.851 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 6.328 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.012 ms/op
Iteration   1: 3.926 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.023 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.784 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  12.526 ms/op
                 existUser·p0.9999: 24.108 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   2: 4.014 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   3.924 ms/op
                 existUser·p0.90:   4.891 ms/op
                 existUser·p0.95:   5.267 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  13.315 ms/op
                 existUser·p0.9999: 20.612 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   3: 3.906 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.292 ms/op
                 existUser·p0.99:   6.705 ms/op
                 existUser·p0.999:  11.984 ms/op
                 existUser·p0.9999: 19.753 ms/op
                 existUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 243116
  mean =      3.948 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8157 
    [ 2.500,  5.000) = 216534 
    [ 5.000,  7.500) = 16952 
    [ 7.500, 10.000) = 944 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     12.534 ms/op
     p(99.9900) =     23.452 ms/op
     p(99.9990) =     24.356 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.329 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.804 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.464 ±(99.9%) 0.015 ms/op
Iteration   1: 4.322 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.202 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   7.423 ms/op
                 getUser·p0.999:  13.845 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   2: 4.441 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   7.553 ms/op
                 getUser·p0.999:  13.394 ms/op
                 getUser·p0.9999: 22.910 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   3: 4.232 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   4.141 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   7.366 ms/op
                 getUser·p0.999:  14.851 ms/op
                 getUser·p0.9999: 26.309 ms/op
                 getUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221667
  mean =      4.330 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4091 
    [ 2.500,  5.000) = 180188 
    [ 5.000,  7.500) = 35224 
    [ 7.500, 10.000) = 1421 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     25.084 ms/op
     p(99.9990) =     26.717 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.314 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.928 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.586 ±(99.9%) 0.020 ms/op
Iteration   1: 5.384 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   6.529 ms/op
                 listUser·p0.95:   7.676 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  20.845 ms/op
                 listUser·p0.9999: 25.632 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   2: 5.467 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.346 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   7.111 ms/op
                 listUser·p0.95:   7.987 ms/op
                 listUser·p0.99:   10.322 ms/op
                 listUser·p0.999:  19.235 ms/op
                 listUser·p0.9999: 21.643 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   3: 5.525 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   7.234 ms/op
                 listUser·p0.95:   8.159 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  20.688 ms/op
                 listUser·p0.9999: 23.379 ms/op
                 listUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175895
  mean =      5.458 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 231 
    [ 2.500,  5.000) = 69901 
    [ 5.000,  7.500) = 93487 
    [ 7.500, 10.000) = 10276 
    [10.000, 12.500) = 1422 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.996 ms/op
     p(95.0000) =      7.971 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     26.018 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.411 ± 0.642  ops/ms
ClientGrpc.existUser                       thrpt       3   8.504 ± 1.712  ops/ms
ClientGrpc.getUser                         thrpt       3   7.570 ± 2.814  ops/ms
ClientGrpc.listUser                        thrpt       3   5.814 ± 2.641  ops/ms
ClientGrpc.createUser                       avgt       3   4.491 ± 2.279   ms/op
ClientGrpc.existUser                        avgt       3   3.805 ± 0.818   ms/op
ClientGrpc.getUser                          avgt       3   4.273 ± 1.143   ms/op
ClientGrpc.listUser                         avgt       3   5.277 ± 0.339   ms/op
ClientGrpc.createUser                     sample  220203   4.361 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.691           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.464           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.931           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.602           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.283           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.851           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.967           ms/op
ClientGrpc.existUser                      sample  243116   3.948 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.848           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.850           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.243           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.709           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.534           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.452           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.478           ms/op
ClientGrpc.getUser                        sample  221667   4.330 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.957           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.317           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.751           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.455           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.779           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.084           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.837           ms/op
ClientGrpc.listUser                       sample  175895   5.458 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.346           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.971           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.174           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.497           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.199           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.018           ms/op
