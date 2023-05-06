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
# Warmup Iteration   1: 4.298 ops/ms
# Warmup Iteration   2: 9.252 ops/ms
# Warmup Iteration   3: 10.468 ops/ms
Iteration   1: 10.668 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.601 ±(99.9%) 1.121 ops/ms [Average]
  (min, avg, max) = (10.546, 10.601, 10.668), stdev = 0.061
  CI (99.9%): [9.480, 11.723] (assumes normal distribution)


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
# Warmup Iteration   1: 7.756 ops/ms
# Warmup Iteration   2: 10.810 ops/ms
# Warmup Iteration   3: 11.165 ops/ms
Iteration   1: 11.413 ops/ms
Iteration   2: 11.334 ops/ms
Iteration   3: 11.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.304 ±(99.9%) 2.295 ops/ms [Average]
  (min, avg, max) = (11.166, 11.304, 11.413), stdev = 0.126
  CI (99.9%): [9.010, 13.599] (assumes normal distribution)


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
# Warmup Iteration   1: 7.526 ops/ms
# Warmup Iteration   2: 10.468 ops/ms
# Warmup Iteration   3: 10.686 ops/ms
Iteration   1: 10.969 ops/ms
Iteration   2: 10.729 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.799 ±(99.9%) 2.704 ops/ms [Average]
  (min, avg, max) = (10.698, 10.799, 10.969), stdev = 0.148
  CI (99.9%): [8.094, 13.503] (assumes normal distribution)


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
# Warmup Iteration   1: 5.846 ops/ms
# Warmup Iteration   2: 8.027 ops/ms
# Warmup Iteration   3: 8.265 ops/ms
Iteration   1: 8.180 ops/ms
Iteration   2: 8.366 ops/ms
Iteration   3: 8.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.213 ±(99.9%) 2.538 ops/ms [Average]
  (min, avg, max) = (8.093, 8.213, 8.366), stdev = 0.139
  CI (99.9%): [5.675, 10.751] (assumes normal distribution)


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.003 ms/op
Iteration   1: 3.032 ±(99.9%) 0.009 ms/op
Iteration   2: 3.001 ±(99.9%) 0.002 ms/op
Iteration   3: 3.026 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.019 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (3.001, 3.019, 3.032), stdev = 0.017
  CI (99.9%): [2.717, 3.322] (assumes normal distribution)


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.955 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.004 ms/op
Iteration   1: 2.858 ±(99.9%) 0.005 ms/op
Iteration   2: 2.868 ±(99.9%) 0.004 ms/op
Iteration   3: 2.837 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.854 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (2.837, 2.854, 2.868), stdev = 0.016
  CI (99.9%): [2.560, 3.149] (assumes normal distribution)


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 3.020 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.026 ±(99.9%) 0.874 ms/op [Average]
  (min, avg, max) = (2.981, 3.026, 3.076), stdev = 0.048
  CI (99.9%): [2.151, 3.900] (assumes normal distribution)


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
# Warmup Iteration   1: 5.003 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.020 ms/op
Iteration   1: 3.877 ±(99.9%) 0.016 ms/op
Iteration   2: 3.802 ±(99.9%) 0.041 ms/op
Iteration   3: 3.902 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.860 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (3.802, 3.860, 3.902), stdev = 0.052
  CI (99.9%): [2.906, 4.814] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  6.773 ms/op
                 createUser·p0.9999: 15.401 ms/op
                 createUser·p1.00:   16.024 ms/op

Iteration   2: 2.980 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.283 ms/op
                 createUser·p0.999:  6.562 ms/op
                 createUser·p0.9999: 17.426 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 18.848 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320940
  mean =      2.991 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25990 
    [ 2.500,  5.000) = 293751 
    [ 5.000,  7.500) = 884 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.439 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     19.883 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.943 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.007 ms/op
Iteration   1: 2.912 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.503 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  6.637 ms/op
                 existUser·p0.9999: 11.551 ms/op
                 existUser·p1.00:   12.157 ms/op

Iteration   2: 2.870 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.609 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  5.428 ms/op
                 existUser·p0.9999: 20.017 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   3: 2.867 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.649 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.299 ms/op
                 existUser·p0.9999: 25.718 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332879
  mean =      2.883 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45350 
    [ 2.500,  5.000) = 286339 
    [ 5.000,  7.500) = 969 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      6.792 ms/op
     p(99.9900) =     21.781 ms/op
     p(99.9990) =     25.843 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
Iteration   1: 3.003 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.394 ms/op
                 getUser·p0.9999: 11.829 ms/op
                 getUser·p1.00:   12.042 ms/op

Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.527 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.655 ms/op
                 getUser·p0.9999: 14.061 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.620 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.456 ms/op
                 getUser·p0.9999: 17.875 ms/op
                 getUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319091
  mean =      3.007 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1219 
    [ 1.250,  2.500) = 19755 
    [ 2.500,  3.750) = 285367 
    [ 3.750,  5.000) = 11308 
    [ 5.000,  6.250) = 819 
    [ 6.250,  7.500) = 299 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.520 ms/op
     p(99.9900) =     16.983 ms/op
     p(99.9990) =     18.049 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 5.260 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.010 ms/op
Iteration   1: 3.860 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  13.025 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   2: 3.903 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  19.761 ms/op
                 listUser·p0.9999: 24.852 ms/op
                 listUser·p1.00:   27.689 ms/op

Iteration   3: 3.781 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.529 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  15.520 ms/op
                 listUser·p0.9999: 22.348 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249516
  mean =      3.847 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6892 
    [ 2.500,  5.000) = 220721 
    [ 5.000,  7.500) = 20696 
    [ 7.500, 10.000) = 708 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     15.130 ms/op
     p(99.9900) =     22.660 ms/op
     p(99.9990) =     27.640 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.601 ± 1.121  ops/ms
ClientGrpc.existUser                       thrpt       3  11.304 ± 2.295  ops/ms
ClientGrpc.getUser                         thrpt       3  10.799 ± 2.704  ops/ms
ClientGrpc.listUser                        thrpt       3   8.213 ± 2.538  ops/ms
ClientGrpc.createUser                       avgt       3   3.019 ± 0.302   ms/op
ClientGrpc.existUser                        avgt       3   2.854 ± 0.294   ms/op
ClientGrpc.getUser                          avgt       3   3.026 ± 0.874   ms/op
ClientGrpc.listUser                         avgt       3   3.860 ± 0.954   ms/op
ClientGrpc.createUser                     sample  320940   2.991 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.643           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.439           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.924           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.251           ms/op
ClientGrpc.existUser                      sample  332879   2.883 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.503           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.792           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.781           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.919           ms/op
ClientGrpc.getUser                        sample  319091   3.007 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.527           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.520           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.983           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.481           ms/op
ClientGrpc.listUser                       sample  249516   3.847 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.529           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.130           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.660           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.689           ms/op
