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
# Warmup Iteration   1: 3.837 ops/ms
# Warmup Iteration   2: 8.837 ops/ms
# Warmup Iteration   3: 9.864 ops/ms
Iteration   1: 10.481 ops/ms
Iteration   2: 10.458 ops/ms
Iteration   3: 10.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.510 ±(99.9%) 1.302 ops/ms [Average]
  (min, avg, max) = (10.458, 10.510, 10.592), stdev = 0.071
  CI (99.9%): [9.208, 11.813] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.634 ops/ms
# Warmup Iteration   2: 10.641 ops/ms
# Warmup Iteration   3: 10.954 ops/ms
Iteration   1: 11.072 ops/ms
Iteration   2: 11.193 ops/ms
Iteration   3: 10.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.039 ±(99.9%) 3.152 ops/ms [Average]
  (min, avg, max) = (10.852, 11.039, 11.193), stdev = 0.173
  CI (99.9%): [7.887, 14.191] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.543 ops/ms
# Warmup Iteration   2: 9.943 ops/ms
# Warmup Iteration   3: 10.183 ops/ms
Iteration   1: 10.365 ops/ms
Iteration   2: 10.595 ops/ms
Iteration   3: 10.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.523 ±(99.9%) 2.503 ops/ms [Average]
  (min, avg, max) = (10.365, 10.523, 10.609), stdev = 0.137
  CI (99.9%): [8.020, 13.025] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.416 ops/ms
# Warmup Iteration   2: 7.309 ops/ms
# Warmup Iteration   3: 7.920 ops/ms
Iteration   1: 7.906 ops/ms
Iteration   2: 7.830 ops/ms
Iteration   3: 7.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.908 ±(99.9%) 1.444 ops/ms [Average]
  (min, avg, max) = (7.830, 7.908, 7.988), stdev = 0.079
  CI (99.9%): [6.465, 9.352] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.356 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.002 ms/op
Iteration   1: 3.081 ±(99.9%) 0.002 ms/op
Iteration   2: 3.001 ±(99.9%) 0.003 ms/op
Iteration   3: 3.052 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.044 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (3.001, 3.044, 3.081), stdev = 0.040
  CI (99.9%): [2.310, 3.779] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.165 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.954 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.002 ms/op
Iteration   1: 2.820 ±(99.9%) 0.003 ms/op
Iteration   2: 2.868 ±(99.9%) 0.002 ms/op
Iteration   3: 2.893 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.860 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (2.820, 2.860, 2.893), stdev = 0.037
  CI (99.9%): [2.177, 3.544] (assumes normal distribution)


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.002 ms/op
Iteration   1: 3.017 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.002 ms/op
Iteration   3: 3.025 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.023 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (3.017, 3.023, 3.027), stdev = 0.005
  CI (99.9%): [2.925, 3.122] (assumes normal distribution)


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
# Warmup Iteration   1: 5.501 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.012 ms/op
Iteration   1: 3.915 ±(99.9%) 0.041 ms/op
Iteration   2: 3.958 ±(99.9%) 0.017 ms/op
Iteration   3: 3.943 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.939 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (3.915, 3.939, 3.958), stdev = 0.022
  CI (99.9%): [3.543, 4.334] (assumes normal distribution)


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.461 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.469 ms/op
                 createUser·p0.9999: 16.441 ms/op
                 createUser·p1.00:   16.679 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  8.354 ms/op
                 createUser·p0.9999: 13.590 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  10.756 ms/op
                 createUser·p0.9999: 29.753 ms/op
                 createUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316980
  mean =      3.028 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21506 
    [ 2.500,  5.000) = 293802 
    [ 5.000,  7.500) = 1247 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     28.014 ms/op
     p(99.9990) =     29.983 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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
# Warmup Iteration   1: 4.225 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
Iteration   1: 2.884 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.048 ms/op
                 existUser·p0.9999: 13.140 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.895 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  6.785 ms/op
                 existUser·p0.9999: 14.189 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   3: 2.923 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  6.801 ms/op
                 existUser·p0.9999: 17.795 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330688
  mean =      2.901 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1150 
    [ 1.250,  2.500) = 38759 
    [ 2.500,  3.750) = 282339 
    [ 3.750,  5.000) = 7272 
    [ 5.000,  6.250) = 677 
    [ 6.250,  7.500) = 289 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      6.840 ms/op
     p(99.9900) =     17.199 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.614 ms/op
                 getUser·p0.999:  7.312 ms/op
                 getUser·p0.9999: 14.649 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   2: 3.034 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  6.717 ms/op
                 getUser·p0.9999: 14.810 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.909 ms/op
                 getUser·p0.9999: 20.168 ms/op
                 getUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315144
  mean =      3.044 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21883 
    [ 2.500,  5.000) = 291658 
    [ 5.000,  7.500) = 1369 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      6.943 ms/op
     p(99.9900) =     18.019 ms/op
     p(99.9990) =     20.521 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 5.358 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.010 ms/op
Iteration   1: 3.893 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  13.482 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   2: 3.948 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.878 ms/op
                 listUser·p0.999:  15.301 ms/op
                 listUser·p0.9999: 23.553 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   3: 3.927 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.801 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.218 ms/op
                 listUser·p0.9999: 18.799 ms/op
                 listUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244628
  mean =      3.922 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2278 
    [ 2.500,  5.000) = 223929 
    [ 5.000,  7.500) = 17129 
    [ 7.500, 10.000) = 776 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.676 ms/op
     p(99.9900) =     22.791 ms/op
     p(99.9990) =     23.964 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.510 ± 1.302  ops/ms
ClientGrpc.existUser                       thrpt       3  11.039 ± 3.152  ops/ms
ClientGrpc.getUser                         thrpt       3  10.523 ± 2.503  ops/ms
ClientGrpc.listUser                        thrpt       3   7.908 ± 1.444  ops/ms
ClientGrpc.createUser                       avgt       3   3.044 ± 0.735   ms/op
ClientGrpc.existUser                        avgt       3   2.860 ± 0.684   ms/op
ClientGrpc.getUser                          avgt       3   3.023 ± 0.099   ms/op
ClientGrpc.listUser                         avgt       3   3.939 ± 0.395   ms/op
ClientGrpc.createUser                     sample  316980   3.028 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.461           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.618           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.014           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.114           ms/op
ClientGrpc.existUser                      sample  330688   2.901 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.737           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.840           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.199           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.285           ms/op
ClientGrpc.getUser                        sample  315144   3.044 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.665           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.943           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.019           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.906           ms/op
ClientGrpc.listUser                       sample  244628   3.922 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.801           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.676           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.791           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.150           ms/op
