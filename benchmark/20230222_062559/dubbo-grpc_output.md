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
# Warmup Iteration   1: 4.896 ops/ms
# Warmup Iteration   2: 9.903 ops/ms
# Warmup Iteration   3: 10.701 ops/ms
Iteration   1: 10.136 ops/ms
Iteration   2: 10.134 ops/ms
Iteration   3: 10.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.358 ±(99.9%) 7.051 ops/ms [Average]
  (min, avg, max) = (10.134, 10.358, 10.804), stdev = 0.387
  CI (99.9%): [3.307, 17.409] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.271 ops/ms
# Warmup Iteration   2: 10.936 ops/ms
# Warmup Iteration   3: 10.677 ops/ms
Iteration   1: 11.530 ops/ms
Iteration   2: 11.475 ops/ms
Iteration   3: 11.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.361 ±(99.9%) 4.476 ops/ms [Average]
  (min, avg, max) = (11.080, 11.361, 11.530), stdev = 0.245
  CI (99.9%): [6.885, 15.838] (assumes normal distribution)


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
# Warmup Iteration   1: 7.755 ops/ms
# Warmup Iteration   2: 10.438 ops/ms
# Warmup Iteration   3: 10.411 ops/ms
Iteration   1: 10.843 ops/ms
Iteration   2: 10.382 ops/ms
Iteration   3: 10.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.596 ±(99.9%) 4.240 ops/ms [Average]
  (min, avg, max) = (10.382, 10.596, 10.843), stdev = 0.232
  CI (99.9%): [6.356, 14.835] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.821 ops/ms
# Warmup Iteration   2: 7.925 ops/ms
# Warmup Iteration   3: 7.805 ops/ms
Iteration   1: 7.940 ops/ms
Iteration   2: 8.110 ops/ms
Iteration   3: 8.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.094 ±(99.9%) 2.667 ops/ms [Average]
  (min, avg, max) = (7.940, 8.094, 8.231), stdev = 0.146
  CI (99.9%): [5.426, 10.761] (assumes normal distribution)


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.009 ms/op
Iteration   1: 3.143 ±(99.9%) 0.001 ms/op
Iteration   2: 2.989 ±(99.9%) 0.003 ms/op
Iteration   3: 3.120 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.084 ±(99.9%) 1.515 ms/op [Average]
  (min, avg, max) = (2.989, 3.084, 3.143), stdev = 0.083
  CI (99.9%): [1.569, 4.600] (assumes normal distribution)


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
# Warmup Iteration   1: 3.647 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.908 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.002 ms/op
Iteration   1: 2.856 ±(99.9%) 0.003 ms/op
Iteration   2: 2.919 ±(99.9%) 0.003 ms/op
Iteration   3: 2.968 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.914 ±(99.9%) 1.019 ms/op [Average]
  (min, avg, max) = (2.856, 2.914, 2.968), stdev = 0.056
  CI (99.9%): [1.896, 3.933] (assumes normal distribution)


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
# Warmup Iteration   1: 3.526 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.005 ms/op
Iteration   1: 3.082 ±(99.9%) 0.002 ms/op
Iteration   2: 3.124 ±(99.9%) 0.002 ms/op
Iteration   3: 3.074 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.093 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.074, 3.093, 3.124), stdev = 0.027
  CI (99.9%): [2.597, 3.590] (assumes normal distribution)


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
# Warmup Iteration   1: 4.717 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.035 ms/op
Iteration   1: 4.031 ±(99.9%) 0.013 ms/op
Iteration   2: 3.932 ±(99.9%) 0.009 ms/op
Iteration   3: 3.879 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.947 ±(99.9%) 1.408 ms/op [Average]
  (min, avg, max) = (3.879, 3.947, 4.031), stdev = 0.077
  CI (99.9%): [2.539, 5.356] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.845 ms/op
                 createUser·p0.9999: 14.808 ms/op
                 createUser·p1.00:   15.647 ms/op

Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  6.000 ms/op
                 createUser·p0.9999: 12.157 ms/op
                 createUser·p1.00:   12.780 ms/op

Iteration   3: 2.939 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.519 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  9.014 ms/op
                 createUser·p0.9999: 26.578 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320343
  mean =      2.999 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35548 
    [ 2.500,  5.000) = 283707 
    [ 5.000,  7.500) = 761 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.649 ms/op
     p(99.9900) =     25.904 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 3.751 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.006 ms/op
Iteration   1: 2.889 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  5.744 ms/op
                 existUser·p0.9999: 11.334 ms/op
                 existUser·p1.00:   11.616 ms/op

Iteration   2: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.349 ms/op
                 existUser·p0.9999: 15.368 ms/op
                 existUser·p1.00:   16.384 ms/op

Iteration   3: 2.919 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  7.348 ms/op
                 existUser·p0.9999: 15.074 ms/op
                 existUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329774
  mean =      2.912 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2974 
    [ 1.250,  2.500) = 51750 
    [ 2.500,  3.750) = 260602 
    [ 3.750,  5.000) = 13605 
    [ 5.000,  6.250) = 455 
    [ 6.250,  7.500) = 130 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =      6.711 ms/op
     p(99.9900) =     15.041 ms/op
     p(99.9990) =     16.097 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.250 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.668 ms/op
                 getUser·p0.9999: 17.007 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.688 ms/op
                 getUser·p0.9999: 17.026 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.885 ms/op
                 getUser·p0.9999: 15.517 ms/op
                 getUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317946
  mean =      3.017 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2133 
    [ 1.250,  2.500) = 27609 
    [ 2.500,  3.750) = 270328 
    [ 3.750,  5.000) = 16753 
    [ 5.000,  6.250) = 570 
    [ 6.250,  7.500) = 213 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 60 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.250 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.750 ms/op
     p(99.9900) =     16.849 ms/op
     p(99.9990) =     17.296 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.637 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.011 ms/op
Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.786 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   2: 4.049 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  15.107 ms/op
                 listUser·p0.9999: 17.993 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 3.926 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.672 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  18.255 ms/op
                 listUser·p0.9999: 31.457 ms/op
                 listUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241352
  mean =      3.977 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6505 
    [ 2.500,  5.000) = 205416 
    [ 5.000,  7.500) = 28004 
    [ 7.500, 10.000) = 886 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     14.783 ms/op
     p(99.9900) =     29.593 ms/op
     p(99.9990) =     31.665 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.358 ± 7.051  ops/ms
ClientGrpc.existUser                       thrpt       3  11.361 ± 4.476  ops/ms
ClientGrpc.getUser                         thrpt       3  10.596 ± 4.240  ops/ms
ClientGrpc.listUser                        thrpt       3   8.094 ± 2.667  ops/ms
ClientGrpc.createUser                       avgt       3   3.084 ± 1.515   ms/op
ClientGrpc.existUser                        avgt       3   2.914 ± 1.019   ms/op
ClientGrpc.getUser                          avgt       3   3.093 ± 0.496   ms/op
ClientGrpc.listUser                         avgt       3   3.947 ± 1.408   ms/op
ClientGrpc.createUser                     sample  320343   2.999 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.519           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.649           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.904           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.213           ms/op
ClientGrpc.existUser                      sample  329774   2.912 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.616           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.711           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.041           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.384           ms/op
ClientGrpc.getUser                        sample  317946   3.017 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.250           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.750           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.849           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.334           ms/op
ClientGrpc.listUser                       sample  241352   3.977 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.672           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.783           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.593           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.752           ms/op
