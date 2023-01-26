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
# Warmup Iteration   1: 5.037 ops/ms
# Warmup Iteration   2: 9.400 ops/ms
# Warmup Iteration   3: 10.325 ops/ms
Iteration   1: 10.411 ops/ms
Iteration   2: 10.407 ops/ms
Iteration   3: 10.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.345 ±(99.9%) 2.020 ops/ms [Average]
  (min, avg, max) = (10.217, 10.345, 10.411), stdev = 0.111
  CI (99.9%): [8.325, 12.365] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.973 ops/ms
# Warmup Iteration   2: 10.647 ops/ms
# Warmup Iteration   3: 11.013 ops/ms
Iteration   1: 10.939 ops/ms
Iteration   2: 11.355 ops/ms
Iteration   3: 11.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.230 ±(99.9%) 4.604 ops/ms [Average]
  (min, avg, max) = (10.939, 11.230, 11.395), stdev = 0.252
  CI (99.9%): [6.626, 15.834] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.552 ops/ms
# Warmup Iteration   2: 10.442 ops/ms
# Warmup Iteration   3: 10.222 ops/ms
Iteration   1: 10.444 ops/ms
Iteration   2: 10.835 ops/ms
Iteration   3: 10.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.472 ±(99.9%) 6.389 ops/ms [Average]
  (min, avg, max) = (10.136, 10.472, 10.835), stdev = 0.350
  CI (99.9%): [4.083, 16.861] (assumes normal distribution)


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
# Warmup Iteration   1: 7.033 ops/ms
# Warmup Iteration   2: 7.668 ops/ms
# Warmup Iteration   3: 8.235 ops/ms
Iteration   1: 8.197 ops/ms
Iteration   2: 8.115 ops/ms
Iteration   3: 8.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.180 ±(99.9%) 1.073 ops/ms [Average]
  (min, avg, max) = (8.115, 8.180, 8.229), stdev = 0.059
  CI (99.9%): [7.107, 9.254] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.002 ms/op
Iteration   1: 3.102 ±(99.9%) 0.002 ms/op
Iteration   2: 3.090 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.098 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (3.090, 3.098, 3.102), stdev = 0.007
  CI (99.9%): [2.970, 3.225] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.003 ms/op
Iteration   1: 3.009 ±(99.9%) 0.002 ms/op
Iteration   2: 2.928 ±(99.9%) 0.003 ms/op
Iteration   3: 3.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.984 ±(99.9%) 0.883 ms/op [Average]
  (min, avg, max) = (2.928, 2.984, 3.014), stdev = 0.048
  CI (99.9%): [2.101, 3.867] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.108 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 3.150 ±(99.9%) 0.001 ms/op
Iteration   2: 3.116 ±(99.9%) 0.003 ms/op
Iteration   3: 3.116 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.127 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (3.116, 3.127, 3.150), stdev = 0.019
  CI (99.9%): [2.773, 3.481] (assumes normal distribution)


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
# Warmup Iteration   1: 4.568 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.018 ms/op
Iteration   1: 3.982 ±(99.9%) 0.020 ms/op
Iteration   2: 3.902 ±(99.9%) 0.010 ms/op
Iteration   3: 3.876 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.920 ±(99.9%) 1.007 ms/op [Average]
  (min, avg, max) = (3.876, 3.920, 3.982), stdev = 0.055
  CI (99.9%): [2.913, 4.926] (assumes normal distribution)


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
Iteration   1: 3.165 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.421 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  6.446 ms/op
                 createUser·p0.9999: 16.214 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   2: 3.243 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.473 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.201 ms/op
                 createUser·p0.9999: 18.125 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   3: 3.088 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.354 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  6.853 ms/op
                 createUser·p0.9999: 33.817 ms/op
                 createUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303647
  mean =      3.164 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17809 
    [ 2.500,  5.000) = 285203 
    [ 5.000,  7.500) = 419 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.551 ms/op
     p(99.9900) =     32.985 ms/op
     p(99.9990) =     34.013 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 3.729 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  5.669 ms/op
                 existUser·p0.9999: 12.947 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   2: 2.960 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.261 ms/op
                 existUser·p0.9999: 14.461 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   3: 2.960 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.913 ms/op
                 existUser·p0.9999: 29.229 ms/op
                 existUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324081
  mean =      2.962 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46600 
    [ 2.500,  5.000) = 276538 
    [ 5.000,  7.500) = 679 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.824 ms/op
     p(99.9900) =     22.902 ms/op
     p(99.9990) =     29.582 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.125 ms/op
                 getUser·p0.9999: 11.889 ms/op
                 getUser·p1.00:   12.091 ms/op

Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.463 ms/op
                 getUser·p0.9999: 14.342 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.610 ms/op
                 getUser·p0.9999: 16.295 ms/op
                 getUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313419
  mean =      3.063 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1660 
    [ 1.250,  2.500) = 22678 
    [ 2.500,  3.750) = 268570 
    [ 3.750,  5.000) = 19375 
    [ 5.000,  6.250) = 627 
    [ 6.250,  7.500) = 242 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.029 ms/op
     p(99.9900) =     15.313 ms/op
     p(99.9990) =     16.806 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.174 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.010 ms/op
Iteration   1: 4.082 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.261 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  12.960 ms/op
                 listUser·p0.9999: 20.813 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 3.952 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  14.436 ms/op
                 listUser·p0.9999: 22.443 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   3: 3.973 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.708 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  17.429 ms/op
                 listUser·p0.9999: 22.379 ms/op
                 listUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239797
  mean =      4.002 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4699 
    [ 2.500,  5.000) = 204519 
    [ 5.000,  7.500) = 29266 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.261 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     15.175 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     27.676 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.345 ± 2.020  ops/ms
ClientGrpc.existUser                       thrpt       3  11.230 ± 4.604  ops/ms
ClientGrpc.getUser                         thrpt       3  10.472 ± 6.389  ops/ms
ClientGrpc.listUser                        thrpt       3   8.180 ± 1.073  ops/ms
ClientGrpc.createUser                       avgt       3   3.098 ± 0.128   ms/op
ClientGrpc.existUser                        avgt       3   2.984 ± 0.883   ms/op
ClientGrpc.getUser                          avgt       3   3.127 ± 0.354   ms/op
ClientGrpc.listUser                         avgt       3   3.920 ± 1.007   ms/op
ClientGrpc.createUser                     sample  303647   3.164 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.354           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.551           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.985           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.013           ms/op
ClientGrpc.existUser                      sample  324081   2.962 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.622           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.824           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.902           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.802           ms/op
ClientGrpc.getUser                        sample  313419   3.063 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.598           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.029           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.313           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.941           ms/op
ClientGrpc.listUser                       sample  239797   4.002 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.261           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.175           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.249           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.754           ms/op
