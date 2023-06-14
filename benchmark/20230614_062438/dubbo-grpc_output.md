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
# Warmup Iteration   1: 2.865 ops/ms
# Warmup Iteration   2: 6.117 ops/ms
# Warmup Iteration   3: 6.616 ops/ms
Iteration   1: 6.590 ops/ms
Iteration   2: 6.867 ops/ms
Iteration   3: 6.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.781 ±(99.9%) 3.024 ops/ms [Average]
  (min, avg, max) = (6.590, 6.781, 6.886), stdev = 0.166
  CI (99.9%): [3.757, 9.805] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.505 ops/ms
# Warmup Iteration   2: 6.989 ops/ms
# Warmup Iteration   3: 7.046 ops/ms
Iteration   1: 7.394 ops/ms
Iteration   2: 7.361 ops/ms
Iteration   3: 7.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.331 ±(99.9%) 1.487 ops/ms [Average]
  (min, avg, max) = (7.239, 7.331, 7.394), stdev = 0.082
  CI (99.9%): [5.844, 8.819] (assumes normal distribution)


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
# Warmup Iteration   1: 5.235 ops/ms
# Warmup Iteration   2: 6.746 ops/ms
# Warmup Iteration   3: 7.214 ops/ms
Iteration   1: 7.050 ops/ms
Iteration   2: 7.342 ops/ms
Iteration   3: 7.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.235 ±(99.9%) 2.930 ops/ms [Average]
  (min, avg, max) = (7.050, 7.235, 7.342), stdev = 0.161
  CI (99.9%): [4.305, 10.165] (assumes normal distribution)


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
# Warmup Iteration   1: 4.228 ops/ms
# Warmup Iteration   2: 5.328 ops/ms
# Warmup Iteration   3: 5.530 ops/ms
Iteration   1: 5.620 ops/ms
Iteration   2: 5.549 ops/ms
Iteration   3: 5.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.648 ±(99.9%) 2.096 ops/ms [Average]
  (min, avg, max) = (5.549, 5.648, 5.774), stdev = 0.115
  CI (99.9%): [3.552, 7.743] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.595 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.641 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.594 ±(99.9%) 0.025 ms/op
Iteration   1: 4.441 ±(99.9%) 0.006 ms/op
Iteration   2: 4.284 ±(99.9%) 0.005 ms/op
Iteration   3: 4.353 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.359 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (4.284, 4.359, 4.441), stdev = 0.079
  CI (99.9%): [2.918, 5.801] (assumes normal distribution)


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
# Warmup Iteration   1: 5.082 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.004 ms/op
Iteration   1: 4.328 ±(99.9%) 0.003 ms/op
Iteration   2: 4.269 ±(99.9%) 0.004 ms/op
Iteration   3: 4.295 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.297 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (4.269, 4.297, 4.328), stdev = 0.030
  CI (99.9%): [3.750, 4.845] (assumes normal distribution)


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
# Warmup Iteration   1: 5.371 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.459 ±(99.9%) 0.071 ms/op
# Warmup Iteration   3: 4.491 ±(99.9%) 0.007 ms/op
Iteration   1: 4.515 ±(99.9%) 0.004 ms/op
Iteration   2: 4.361 ±(99.9%) 0.006 ms/op
Iteration   3: 4.423 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.433 ±(99.9%) 1.411 ms/op [Average]
  (min, avg, max) = (4.361, 4.433, 4.515), stdev = 0.077
  CI (99.9%): [3.022, 5.844] (assumes normal distribution)


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
# Warmup Iteration   1: 7.567 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.933 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.777 ±(99.9%) 0.022 ms/op
Iteration   1: 5.564 ±(99.9%) 0.014 ms/op
Iteration   2: 5.802 ±(99.9%) 0.018 ms/op
Iteration   3: 5.860 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.742 ±(99.9%) 2.862 ms/op [Average]
  (min, avg, max) = (5.564, 5.742, 5.860), stdev = 0.157
  CI (99.9%): [2.880, 8.604] (assumes normal distribution)


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
# Warmup Iteration   1: 5.694 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.481 ±(99.9%) 0.019 ms/op
Iteration   1: 4.402 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   4.129 ms/op
                 createUser·p0.90:   5.898 ms/op
                 createUser·p0.95:   6.791 ms/op
                 createUser·p0.99:   9.060 ms/op
                 createUser·p0.999:  14.313 ms/op
                 createUser·p0.9999: 39.828 ms/op
                 createUser·p1.00:   40.305 ms/op

Iteration   2: 4.550 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   6.144 ms/op
                 createUser·p0.95:   7.118 ms/op
                 createUser·p0.99:   9.486 ms/op
                 createUser·p0.999:  22.064 ms/op
                 createUser·p0.9999: 33.382 ms/op
                 createUser·p1.00:   33.817 ms/op

Iteration   3: 4.681 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   6.562 ms/op
                 createUser·p0.95:   7.610 ms/op
                 createUser·p0.99:   10.076 ms/op
                 createUser·p0.999:  15.233 ms/op
                 createUser·p0.9999: 34.811 ms/op
                 createUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 211308
  mean =      4.542 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 154445 
    [ 5.000, 10.000) = 55209 
    [10.000, 15.000) = 1429 
    [15.000, 20.000) = 74 
    [20.000, 25.000) = 23 
    [25.000, 30.000) = 12 
    [30.000, 35.000) = 83 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      6.210 ms/op
     p(95.0000) =      7.197 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     15.424 ms/op
     p(99.9900) =     38.994 ms/op
     p(99.9990) =     40.224 ms/op
     p(99.9999) =     40.305 ms/op
    p(100.0000) =     40.305 ms/op


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
# Warmup Iteration   1: 5.227 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.536 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.640 ±(99.9%) 0.019 ms/op
Iteration   1: 4.305 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   4.063 ms/op
                 existUser·p0.90:   5.702 ms/op
                 existUser·p0.95:   6.562 ms/op
                 existUser·p0.99:   8.880 ms/op
                 existUser·p0.999:  12.567 ms/op
                 existUser·p0.9999: 21.598 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   2: 4.379 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   4.096 ms/op
                 existUser·p0.90:   6.005 ms/op
                 existUser·p0.95:   6.930 ms/op
                 existUser·p0.99:   9.028 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 19.595 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   3: 4.357 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   4.108 ms/op
                 existUser·p0.90:   5.825 ms/op
                 existUser·p0.95:   6.685 ms/op
                 existUser·p0.99:   9.277 ms/op
                 existUser·p0.999:  13.287 ms/op
                 existUser·p0.9999: 25.111 ms/op
                 existUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 220817
  mean =      4.346 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7039 
    [ 2.500,  5.000) = 166265 
    [ 5.000,  7.500) = 40880 
    [ 7.500, 10.000) = 5550 
    [10.000, 12.500) = 832 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      4.088 ms/op
     p(90.0000) =      5.841 ms/op
     p(95.0000) =      6.726 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     23.358 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 5.682 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.710 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.617 ±(99.9%) 0.020 ms/op
Iteration   1: 4.447 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.906 ms/op
                 getUser·p0.95:   6.619 ms/op
                 getUser·p0.99:   8.700 ms/op
                 getUser·p0.999:  13.058 ms/op
                 getUser·p0.9999: 26.051 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   2: 4.434 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.865 ms/op
                 getUser·p0.95:   6.693 ms/op
                 getUser·p0.99:   8.880 ms/op
                 getUser·p0.999:  12.796 ms/op
                 getUser·p0.9999: 26.542 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   3: 4.518 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.931 ms/op
                 getUser·p0.95:   6.676 ms/op
                 getUser·p0.99:   8.864 ms/op
                 getUser·p0.999:  14.290 ms/op
                 getUser·p0.9999: 37.607 ms/op
                 getUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214926
  mean =      4.466 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4767 
    [ 2.500,  5.000) = 156920 
    [ 5.000,  7.500) = 47622 
    [ 7.500, 10.000) = 4792 
    [10.000, 12.500) = 517 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.906 ms/op
     p(95.0000) =      6.660 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     38.067 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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
# Warmup Iteration   1: 7.050 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.865 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.336 ±(99.9%) 0.022 ms/op
Iteration   1: 5.489 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   4.973 ms/op
                 listUser·p0.90:   7.700 ms/op
                 listUser·p0.95:   8.929 ms/op
                 listUser·p0.99:   12.009 ms/op
                 listUser·p0.999:  19.923 ms/op
                 listUser·p0.9999: 24.556 ms/op
                 listUser·p1.00:   28.049 ms/op

Iteration   2: 5.443 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.370 ms/op
                 listUser·p0.999:  22.992 ms/op
                 listUser·p0.9999: 26.710 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   3: 5.786 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.421 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   9.798 ms/op
                 listUser·p0.99:   13.359 ms/op
                 listUser·p0.999:  26.370 ms/op
                 listUser·p0.9999: 35.945 ms/op
                 listUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172342
  mean =      5.569 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 252 
    [ 2.500,  5.000) = 84402 
    [ 5.000,  7.500) = 65905 
    [ 7.500, 10.000) = 16393 
    [10.000, 12.500) = 3800 
    [12.500, 15.000) = 980 
    [15.000, 17.500) = 269 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      7.905 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.304 ms/op
     p(99.9000) =     22.828 ms/op
     p(99.9900) =     34.048 ms/op
     p(99.9990) =     36.278 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.781 ± 3.024  ops/ms
ClientGrpc.existUser                       thrpt       3   7.331 ± 1.487  ops/ms
ClientGrpc.getUser                         thrpt       3   7.235 ± 2.930  ops/ms
ClientGrpc.listUser                        thrpt       3   5.648 ± 2.096  ops/ms
ClientGrpc.createUser                       avgt       3   4.359 ± 1.442   ms/op
ClientGrpc.existUser                        avgt       3   4.297 ± 0.548   ms/op
ClientGrpc.getUser                          avgt       3   4.433 ± 1.411   ms/op
ClientGrpc.listUser                         avgt       3   5.742 ± 2.862   ms/op
ClientGrpc.createUser                     sample  211308   4.542 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.008           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.210           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.197           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.617           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.424           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          38.994           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          40.305           ms/op
ClientGrpc.existUser                      sample  220817   4.346 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.767           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.088           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.841           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.726           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.044           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.665           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.358           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.083           ms/op
ClientGrpc.getUser                        sample  214926   4.466 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.016           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.906           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.660           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.798           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.304           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.375           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          38.142           ms/op
ClientGrpc.listUser                       sample  172342   5.569 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.421           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.905           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.126           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.304           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.828           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.048           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.372           ms/op
