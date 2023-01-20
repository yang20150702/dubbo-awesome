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
# Warmup Iteration   1: 1.827 ops/ms
# Warmup Iteration   2: 4.758 ops/ms
# Warmup Iteration   3: 6.339 ops/ms
Iteration   1: 6.387 ops/ms
Iteration   2: 6.529 ops/ms
Iteration   3: 6.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.483 ±(99.9%) 1.506 ops/ms [Average]
  (min, avg, max) = (6.387, 6.483, 6.531), stdev = 0.083
  CI (99.9%): [4.977, 7.988] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.178 ops/ms
# Warmup Iteration   2: 6.611 ops/ms
# Warmup Iteration   3: 6.703 ops/ms
Iteration   1: 6.809 ops/ms
Iteration   2: 6.876 ops/ms
Iteration   3: 6.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.764 ±(99.9%) 2.552 ops/ms [Average]
  (min, avg, max) = (6.607, 6.764, 6.876), stdev = 0.140
  CI (99.9%): [4.212, 9.316] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.680 ops/ms
# Warmup Iteration   2: 5.749 ops/ms
# Warmup Iteration   3: 6.253 ops/ms
Iteration   1: 6.295 ops/ms
Iteration   2: 6.354 ops/ms
Iteration   3: 6.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.364 ±(99.9%) 1.348 ops/ms [Average]
  (min, avg, max) = (6.295, 6.364, 6.442), stdev = 0.074
  CI (99.9%): [5.016, 7.711] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.460 ops/ms
# Warmup Iteration   2: 4.426 ops/ms
# Warmup Iteration   3: 5.098 ops/ms
Iteration   1: 5.055 ops/ms
Iteration   2: 5.121 ops/ms
Iteration   3: 5.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.089 ±(99.9%) 0.602 ops/ms [Average]
  (min, avg, max) = (5.055, 5.089, 5.121), stdev = 0.033
  CI (99.9%): [4.487, 5.690] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.123 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.354 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.153 ±(99.9%) 0.005 ms/op
Iteration   1: 5.074 ±(99.9%) 0.004 ms/op
Iteration   2: 5.041 ±(99.9%) 0.003 ms/op
Iteration   3: 5.003 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.039 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (5.003, 5.039, 5.074), stdev = 0.036
  CI (99.9%): [4.386, 5.692] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.670 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.082 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.741 ±(99.9%) 0.007 ms/op
Iteration   1: 4.597 ±(99.9%) 0.004 ms/op
Iteration   2: 4.632 ±(99.9%) 0.007 ms/op
Iteration   3: 4.644 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.624 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (4.597, 4.624, 4.644), stdev = 0.025
  CI (99.9%): [4.174, 5.074] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.354 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.169 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.040 ±(99.9%) 0.013 ms/op
Iteration   1: 5.070 ±(99.9%) 0.006 ms/op
Iteration   2: 5.128 ±(99.9%) 0.004 ms/op
Iteration   3: 4.943 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.047 ±(99.9%) 1.721 ms/op [Average]
  (min, avg, max) = (4.943, 5.047, 5.128), stdev = 0.094
  CI (99.9%): [3.326, 6.768] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.618 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 6.935 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 6.423 ±(99.9%) 0.014 ms/op
Iteration   1: 6.332 ±(99.9%) 0.012 ms/op
Iteration   2: 6.320 ±(99.9%) 0.012 ms/op
Iteration   3: 6.364 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.339 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (6.320, 6.339, 6.364), stdev = 0.023
  CI (99.9%): [5.920, 6.757] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.474 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.299 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.087 ±(99.9%) 0.016 ms/op
Iteration   1: 4.993 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.316 ms/op
                 createUser·p0.95:   6.734 ms/op
                 createUser·p0.99:   8.067 ms/op
                 createUser·p0.999:  11.827 ms/op
                 createUser·p0.9999: 20.341 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   2: 5.030 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.373 ms/op
                 createUser·p0.95:   6.840 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  12.195 ms/op
                 createUser·p0.9999: 31.956 ms/op
                 createUser·p1.00:   32.309 ms/op

Iteration   3: 4.921 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   4.801 ms/op
                 createUser·p0.90:   6.111 ms/op
                 createUser·p0.95:   6.554 ms/op
                 createUser·p0.99:   8.135 ms/op
                 createUser·p0.999:  22.994 ms/op
                 createUser·p0.9999: 33.342 ms/op
                 createUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 192673
  mean =      4.981 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2054 
    [ 2.500,  5.000) = 104001 
    [ 5.000,  7.500) = 83057 
    [ 7.500, 10.000) = 2802 
    [10.000, 12.500) = 460 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.275 ms/op
     p(95.0000) =      6.717 ms/op
     p(99.0000) =      8.323 ms/op
     p(99.9000) =     15.409 ms/op
     p(99.9900) =     32.670 ms/op
     p(99.9990) =     35.399 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 6.155 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.029 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.766 ±(99.9%) 0.014 ms/op
Iteration   1: 4.712 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   4.637 ms/op
                 existUser·p0.90:   6.005 ms/op
                 existUser·p0.95:   6.414 ms/op
                 existUser·p0.99:   7.905 ms/op
                 existUser·p0.999:  15.057 ms/op
                 existUser·p0.9999: 18.678 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   2: 4.803 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   4.727 ms/op
                 existUser·p0.90:   6.128 ms/op
                 existUser·p0.95:   6.554 ms/op
                 existUser·p0.99:   7.979 ms/op
                 existUser·p0.999:  13.769 ms/op
                 existUser·p0.9999: 18.252 ms/op
                 existUser·p1.00:   18.842 ms/op

Iteration   3: 4.586 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.020 ms/op
                 existUser·p0.50:   4.481 ms/op
                 existUser·p0.90:   5.800 ms/op
                 existUser·p0.95:   6.275 ms/op
                 existUser·p0.99:   8.024 ms/op
                 existUser·p0.999:  13.877 ms/op
                 existUser·p0.9999: 22.710 ms/op
                 existUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 204240
  mean =      4.698 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5311 
    [ 2.500,  5.000) = 128036 
    [ 5.000,  7.500) = 68051 
    [ 7.500, 10.000) = 2158 
    [10.000, 12.500) = 354 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.431 ms/op
     p(99.0000) =      7.976 ms/op
     p(99.9000) =     13.877 ms/op
     p(99.9900) =     20.654 ms/op
     p(99.9990) =     23.228 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 7.731 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 5.331 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.135 ±(99.9%) 0.017 ms/op
Iteration   1: 5.089 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.529 ms/op
                 getUser·p0.95:   7.119 ms/op
                 getUser·p0.99:   9.388 ms/op
                 getUser·p0.999:  14.074 ms/op
                 getUser·p0.9999: 25.212 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   2: 4.972 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.193 ms/op
                 getUser·p0.95:   6.668 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  12.363 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   3: 4.994 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   4.915 ms/op
                 getUser·p0.90:   6.349 ms/op
                 getUser·p0.95:   6.783 ms/op
                 getUser·p0.99:   8.364 ms/op
                 getUser·p0.999:  12.795 ms/op
                 getUser·p0.9999: 21.057 ms/op
                 getUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 191362
  mean =      5.018 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2347 
    [ 2.500,  5.000) = 100206 
    [ 5.000,  7.500) = 84006 
    [ 7.500, 10.000) = 3795 
    [10.000, 12.500) = 719 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     24.521 ms/op
     p(99.9990) =     25.685 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 10.094 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 7.065 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 6.477 ±(99.9%) 0.028 ms/op
Iteration   1: 6.448 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   8.946 ms/op
                 listUser·p0.95:   10.043 ms/op
                 listUser·p0.99:   12.829 ms/op
                 listUser·p0.999:  17.484 ms/op
                 listUser·p0.9999: 23.732 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 6.218 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   8.372 ms/op
                 listUser·p0.95:   9.404 ms/op
                 listUser·p0.99:   12.222 ms/op
                 listUser·p0.999:  18.690 ms/op
                 listUser·p0.9999: 20.727 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 6.371 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.568 ms/op
                 listUser·p0.99:   12.568 ms/op
                 listUser·p0.999:  20.029 ms/op
                 listUser·p0.9999: 27.784 ms/op
                 listUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 151341
  mean =      6.344 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 27978 
    [ 5.000,  7.500) = 94019 
    [ 7.500, 10.000) = 23117 
    [10.000, 12.500) = 4633 
    [12.500, 15.000) = 1140 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      5.939 ms/op
     p(90.0000) =      8.618 ms/op
     p(95.0000) =      9.699 ms/op
     p(99.0000) =     12.550 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     24.263 ms/op
     p(99.9990) =     28.064 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.483 ± 1.506  ops/ms
ClientGrpc.existUser                       thrpt       3   6.764 ± 2.552  ops/ms
ClientGrpc.getUser                         thrpt       3   6.364 ± 1.348  ops/ms
ClientGrpc.listUser                        thrpt       3   5.089 ± 0.602  ops/ms
ClientGrpc.createUser                       avgt       3   5.039 ± 0.653   ms/op
ClientGrpc.existUser                        avgt       3   4.624 ± 0.450   ms/op
ClientGrpc.getUser                          avgt       3   5.047 ± 1.721   ms/op
ClientGrpc.listUser                         avgt       3   6.339 ± 0.419   ms/op
ClientGrpc.createUser                     sample  192673   4.981 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.010           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.874           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.275           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.717           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.323           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.409           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.670           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.521           ms/op
ClientGrpc.existUser                      sample  204240   4.698 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.020           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.604           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.988           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.431           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.976           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.877           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.654           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.331           ms/op
ClientGrpc.getUser                        sample  191362   5.018 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.276           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.907           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.357           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.857           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.897           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.255           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.521           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.673           ms/op
ClientGrpc.listUser                       sample  151341   6.344 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.413           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.699           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.550           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.137           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.263           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.148           ms/op
