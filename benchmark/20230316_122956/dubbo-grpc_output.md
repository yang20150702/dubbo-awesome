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
# Warmup Iteration   1: 4.398 ops/ms
# Warmup Iteration   2: 9.379 ops/ms
# Warmup Iteration   3: 10.240 ops/ms
Iteration   1: 10.413 ops/ms
Iteration   2: 10.503 ops/ms
Iteration   3: 10.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.551 ±(99.9%) 3.049 ops/ms [Average]
  (min, avg, max) = (10.413, 10.551, 10.737), stdev = 0.167
  CI (99.9%): [7.502, 13.599] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.881 ops/ms
# Warmup Iteration   2: 10.606 ops/ms
# Warmup Iteration   3: 11.331 ops/ms
Iteration   1: 11.177 ops/ms
Iteration   2: 11.079 ops/ms
Iteration   3: 11.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.258 ±(99.9%) 4.207 ops/ms [Average]
  (min, avg, max) = (11.079, 11.258, 11.518), stdev = 0.231
  CI (99.9%): [7.051, 15.466] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.904 ops/ms
# Warmup Iteration   2: 10.402 ops/ms
# Warmup Iteration   3: 10.384 ops/ms
Iteration   1: 10.306 ops/ms
Iteration   2: 10.576 ops/ms
Iteration   3: 10.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.475 ±(99.9%) 2.695 ops/ms [Average]
  (min, avg, max) = (10.306, 10.475, 10.576), stdev = 0.148
  CI (99.9%): [7.780, 13.170] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.256 ops/ms
# Warmup Iteration   2: 7.747 ops/ms
# Warmup Iteration   3: 8.224 ops/ms
Iteration   1: 8.325 ops/ms
Iteration   2: 8.240 ops/ms
Iteration   3: 8.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.247 ±(99.9%) 1.357 ops/ms [Average]
  (min, avg, max) = (8.177, 8.247, 8.325), stdev = 0.074
  CI (99.9%): [6.890, 9.605] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.378 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.002 ms/op
Iteration   1: 3.041 ±(99.9%) 0.003 ms/op
Iteration   2: 3.017 ±(99.9%) 0.003 ms/op
Iteration   3: 2.972 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.010 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (2.972, 3.010, 3.041), stdev = 0.035
  CI (99.9%): [2.364, 3.656] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.889 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 2.926 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.002 ms/op
Iteration   1: 2.884 ±(99.9%) 0.003 ms/op
Iteration   2: 2.960 ±(99.9%) 0.002 ms/op
Iteration   3: 2.810 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.885 ±(99.9%) 1.373 ms/op [Average]
  (min, avg, max) = (2.810, 2.885, 2.960), stdev = 0.075
  CI (99.9%): [1.511, 4.258] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.196 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.004 ms/op
Iteration   2: 2.977 ±(99.9%) 0.003 ms/op
Iteration   3: 2.979 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.994 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (2.977, 2.994, 3.026), stdev = 0.028
  CI (99.9%): [2.486, 3.502] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.183 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.018 ms/op
Iteration   1: 3.891 ±(99.9%) 0.020 ms/op
Iteration   2: 3.967 ±(99.9%) 0.019 ms/op
Iteration   3: 3.958 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.939 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (3.891, 3.939, 3.967), stdev = 0.042
  CI (99.9%): [3.177, 4.701] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.253 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  7.373 ms/op
                 createUser·p0.9999: 15.603 ms/op
                 createUser·p1.00:   15.761 ms/op

Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  6.929 ms/op
                 createUser·p0.9999: 23.134 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   3: 3.099 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  12.362 ms/op
                 createUser·p0.9999: 21.791 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315644
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24039 
    [ 2.500,  5.000) = 288309 
    [ 5.000,  7.500) = 2793 
    [ 7.500, 10.000) = 209 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =      9.232 ms/op
     p(99.9900) =     22.671 ms/op
     p(99.9990) =     23.391 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.871 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.953 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.005 ms/op
Iteration   1: 2.815 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.995 ms/op
                 existUser·p0.9999: 14.363 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   2: 2.839 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.294 ms/op
                 existUser·p0.9999: 14.057 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.888 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 17.673 ms/op
                 existUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337121
  mean =      2.847 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1497 
    [ 1.250,  2.500) = 51875 
    [ 2.500,  3.750) = 275663 
    [ 3.750,  5.000) = 6972 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     16.581 ms/op
     p(99.9990) =     18.674 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  9.158 ms/op
                 getUser·p0.9999: 13.779 ms/op
                 getUser·p1.00:   14.041 ms/op

Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.276 ms/op
                 getUser·p0.9999: 14.251 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   3: 3.075 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.168 ms/op
                 getUser·p0.9999: 29.563 ms/op
                 getUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314256
  mean =      3.053 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19872 
    [ 2.500,  5.000) = 292868 
    [ 5.000,  7.500) = 1185 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.567 ms/op
     p(99.9900) =     28.565 ms/op
     p(99.9990) =     29.875 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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
# Warmup Iteration   1: 5.509 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.011 ms/op
Iteration   1: 3.892 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   2: 3.932 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.812 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.899 ms/op
                 listUser·p0.9999: 15.204 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 3.949 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.929 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 28.049 ms/op
                 listUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244686
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3511 
    [ 2.500,  5.000) = 220757 
    [ 5.000,  7.500) = 19252 
    [ 7.500, 10.000) = 685 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     27.123 ms/op
     p(99.9990) =     28.246 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.551 ± 3.049  ops/ms
ClientGrpc.existUser                       thrpt       3  11.258 ± 4.207  ops/ms
ClientGrpc.getUser                         thrpt       3  10.475 ± 2.695  ops/ms
ClientGrpc.listUser                        thrpt       3   8.247 ± 1.357  ops/ms
ClientGrpc.createUser                       avgt       3   3.010 ± 0.646   ms/op
ClientGrpc.existUser                        avgt       3   2.885 ± 1.373   ms/op
ClientGrpc.getUser                          avgt       3   2.994 ± 0.508   ms/op
ClientGrpc.listUser                         avgt       3   3.939 ± 0.762   ms/op
ClientGrpc.createUser                     sample  315644   3.042 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.751           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.038           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.232           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.671           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.462           ms/op
ClientGrpc.existUser                      sample  337121   2.847 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.618           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.843           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.277           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.044           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.581           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.005           ms/op
ClientGrpc.getUser                        sample  314256   3.053 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.822           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.567           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.565           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.114           ms/op
ClientGrpc.listUser                       sample  244686   3.924 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.812           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.385           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.123           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.344           ms/op
