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
# Warmup Iteration   1: 4.085 ops/ms
# Warmup Iteration   2: 8.816 ops/ms
# Warmup Iteration   3: 10.115 ops/ms
Iteration   1: 10.434 ops/ms
Iteration   2: 10.782 ops/ms
Iteration   3: 10.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.492 ±(99.9%) 4.845 ops/ms [Average]
  (min, avg, max) = (10.261, 10.492, 10.782), stdev = 0.266
  CI (99.9%): [5.648, 15.337] (assumes normal distribution)


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
# Warmup Iteration   1: 7.715 ops/ms
# Warmup Iteration   2: 11.034 ops/ms
# Warmup Iteration   3: 11.098 ops/ms
Iteration   1: 10.957 ops/ms
Iteration   2: 11.048 ops/ms
Iteration   3: 11.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.029 ±(99.9%) 1.178 ops/ms [Average]
  (min, avg, max) = (10.957, 11.029, 11.081), stdev = 0.065
  CI (99.9%): [9.851, 12.206] (assumes normal distribution)


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
# Warmup Iteration   1: 7.469 ops/ms
# Warmup Iteration   2: 9.998 ops/ms
# Warmup Iteration   3: 10.328 ops/ms
Iteration   1: 10.505 ops/ms
Iteration   2: 10.542 ops/ms
Iteration   3: 10.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.521 ±(99.9%) 0.352 ops/ms [Average]
  (min, avg, max) = (10.505, 10.521, 10.542), stdev = 0.019
  CI (99.9%): [10.169, 10.873] (assumes normal distribution)


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
# Warmup Iteration   1: 5.353 ops/ms
# Warmup Iteration   2: 7.775 ops/ms
# Warmup Iteration   3: 7.894 ops/ms
Iteration   1: 8.079 ops/ms
Iteration   2: 8.020 ops/ms
Iteration   3: 8.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.108 ±(99.9%) 1.929 ops/ms [Average]
  (min, avg, max) = (8.020, 8.108, 8.225), stdev = 0.106
  CI (99.9%): [6.179, 10.037] (assumes normal distribution)


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
# Warmup Iteration   1: 4.286 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.002 ms/op
Iteration   1: 3.039 ±(99.9%) 0.003 ms/op
Iteration   2: 3.061 ±(99.9%) 0.001 ms/op
Iteration   3: 3.002 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.034 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (3.002, 3.034, 3.061), stdev = 0.030
  CI (99.9%): [2.492, 3.576] (assumes normal distribution)


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.978 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.003 ms/op
Iteration   1: 2.874 ±(99.9%) 0.003 ms/op
Iteration   2: 2.910 ±(99.9%) 0.002 ms/op
Iteration   3: 2.913 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.899 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (2.874, 2.899, 2.913), stdev = 0.022
  CI (99.9%): [2.504, 3.294] (assumes normal distribution)


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.004 ms/op
Iteration   1: 3.047 ±(99.9%) 0.003 ms/op
Iteration   2: 3.039 ±(99.9%) 0.002 ms/op
Iteration   3: 3.030 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.039 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (3.030, 3.039, 3.047), stdev = 0.009
  CI (99.9%): [2.876, 3.201] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.682 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.008 ms/op
Iteration   1: 3.985 ±(99.9%) 0.006 ms/op
Iteration   2: 3.982 ±(99.9%) 0.019 ms/op
Iteration   3: 4.001 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.989 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (3.982, 3.989, 4.001), stdev = 0.010
  CI (99.9%): [3.808, 4.171] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.250 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.008 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.630 ms/op
                 createUser·p0.999:  7.103 ms/op
                 createUser·p0.9999: 22.282 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   2: 3.040 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.108 ms/op
                 createUser·p0.9999: 24.068 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   3: 3.098 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  17.924 ms/op
                 createUser·p0.9999: 24.598 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314336
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24326 
    [ 2.500,  5.000) = 288189 
    [ 5.000,  7.500) = 1436 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     24.431 ms/op
     p(99.9990) =     26.467 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.005 ms/op
Iteration   1: 2.967 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  8.407 ms/op
                 existUser·p0.9999: 13.807 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  6.994 ms/op
                 existUser·p0.9999: 13.394 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   3: 2.932 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  5.644 ms/op
                 existUser·p0.9999: 17.341 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324981
  mean =      2.951 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 787 
    [ 1.250,  2.500) = 36467 
    [ 2.500,  3.750) = 277162 
    [ 3.750,  5.000) = 9565 
    [ 5.000,  6.250) = 451 
    [ 6.250,  7.500) = 263 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.095 ms/op
     p(99.9900) =     15.532 ms/op
     p(99.9990) =     17.687 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 4.377 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  9.465 ms/op
                 getUser·p0.9999: 12.754 ms/op
                 getUser·p1.00:   12.861 ms/op

Iteration   2: 3.061 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.524 ms/op
                 getUser·p0.9999: 17.582 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.533 ms/op
                 getUser·p0.9999: 15.876 ms/op
                 getUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314036
  mean =      3.056 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 453 
    [ 1.250,  2.500) = 21632 
    [ 2.500,  3.750) = 272145 
    [ 3.750,  5.000) = 18561 
    [ 5.000,  6.250) = 662 
    [ 6.250,  7.500) = 231 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.197 ms/op
     p(99.9900) =     16.420 ms/op
     p(99.9990) =     18.074 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.145 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.012 ms/op
Iteration   1: 3.941 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.599 ms/op
                 listUser·p0.9999: 15.602 ms/op
                 listUser·p1.00:   16.122 ms/op

Iteration   2: 4.077 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 21.533 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 3.937 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  16.492 ms/op
                 listUser·p0.9999: 25.293 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240970
  mean =      3.984 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2608 
    [ 2.500,  5.000) = 214290 
    [ 5.000,  7.500) = 22833 
    [ 7.500, 10.000) = 811 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.492 ± 4.845  ops/ms
ClientGrpc.existUser                       thrpt       3  11.029 ± 1.178  ops/ms
ClientGrpc.getUser                         thrpt       3  10.521 ± 0.352  ops/ms
ClientGrpc.listUser                        thrpt       3   8.108 ± 1.929  ops/ms
ClientGrpc.createUser                       avgt       3   3.034 ± 0.542   ms/op
ClientGrpc.existUser                        avgt       3   2.899 ± 0.395   ms/op
ClientGrpc.getUser                          avgt       3   3.039 ± 0.162   ms/op
ClientGrpc.listUser                         avgt       3   3.989 ± 0.182   ms/op
ClientGrpc.createUser                     sample  314336   3.052 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.640           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.748           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.431           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.608           ms/op
ClientGrpc.existUser                      sample  324981   2.951 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.555           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.095           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.532           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.793           ms/op
ClientGrpc.getUser                        sample  314036   3.056 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.764           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.197           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.420           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.285           ms/op
ClientGrpc.listUser                       sample  240970   3.984 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.830           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.729           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.805           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
