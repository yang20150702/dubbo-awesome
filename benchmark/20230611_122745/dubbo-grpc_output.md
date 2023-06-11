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
# Warmup Iteration   1: 4.288 ops/ms
# Warmup Iteration   2: 9.398 ops/ms
# Warmup Iteration   3: 10.135 ops/ms
Iteration   1: 10.403 ops/ms
Iteration   2: 10.499 ops/ms
Iteration   3: 10.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.554 ±(99.9%) 3.379 ops/ms [Average]
  (min, avg, max) = (10.403, 10.554, 10.761), stdev = 0.185
  CI (99.9%): [7.175, 13.933] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.262 ops/ms
# Warmup Iteration   2: 10.551 ops/ms
# Warmup Iteration   3: 11.053 ops/ms
Iteration   1: 11.357 ops/ms
Iteration   2: 11.383 ops/ms
Iteration   3: 11.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.337 ±(99.9%) 1.058 ops/ms [Average]
  (min, avg, max) = (11.272, 11.337, 11.383), stdev = 0.058
  CI (99.9%): [10.279, 12.395] (assumes normal distribution)


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
# Warmup Iteration   1: 7.371 ops/ms
# Warmup Iteration   2: 10.326 ops/ms
# Warmup Iteration   3: 10.467 ops/ms
Iteration   1: 10.577 ops/ms
Iteration   2: 10.756 ops/ms
Iteration   3: 10.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.663 ±(99.9%) 1.641 ops/ms [Average]
  (min, avg, max) = (10.577, 10.663, 10.756), stdev = 0.090
  CI (99.9%): [9.022, 12.304] (assumes normal distribution)


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
# Warmup Iteration   1: 5.482 ops/ms
# Warmup Iteration   2: 7.861 ops/ms
# Warmup Iteration   3: 8.175 ops/ms
Iteration   1: 8.279 ops/ms
Iteration   2: 8.356 ops/ms
Iteration   3: 8.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.287 ±(99.9%) 1.201 ops/ms [Average]
  (min, avg, max) = (8.225, 8.287, 8.356), stdev = 0.066
  CI (99.9%): [7.086, 9.488] (assumes normal distribution)


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.003 ms/op
Iteration   1: 3.109 ±(99.9%) 0.003 ms/op
Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
Iteration   3: 3.081 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.087 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (3.070, 3.087, 3.109), stdev = 0.020
  CI (99.9%): [2.725, 3.449] (assumes normal distribution)


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.982 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.882 ±(99.9%) 0.002 ms/op
Iteration   1: 2.846 ±(99.9%) 0.001 ms/op
Iteration   2: 2.903 ±(99.9%) 0.002 ms/op
Iteration   3: 2.900 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.883 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (2.846, 2.883, 2.903), stdev = 0.032
  CI (99.9%): [2.296, 3.469] (assumes normal distribution)


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.004 ms/op
Iteration   1: 3.023 ±(99.9%) 0.002 ms/op
Iteration   2: 2.990 ±(99.9%) 0.003 ms/op
Iteration   3: 3.000 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.005 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (2.990, 3.005, 3.023), stdev = 0.017
  CI (99.9%): [2.701, 3.308] (assumes normal distribution)


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
# Warmup Iteration   1: 5.246 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.017 ms/op
Iteration   1: 3.860 ±(99.9%) 0.017 ms/op
Iteration   2: 3.848 ±(99.9%) 0.033 ms/op
Iteration   3: 3.842 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.850 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (3.842, 3.850, 3.860), stdev = 0.009
  CI (99.9%): [3.686, 4.014] (assumes normal distribution)


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.695 ms/op
                 createUser·p0.9999: 13.828 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  7.903 ms/op
                 createUser·p0.9999: 15.020 ms/op
                 createUser·p1.00:   15.532 ms/op

Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  11.104 ms/op
                 createUser·p0.9999: 16.766 ms/op
                 createUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317858
  mean =      3.018 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 695 
    [ 1.250,  2.500) = 22448 
    [ 2.500,  3.750) = 279415 
    [ 3.750,  5.000) = 13673 
    [ 5.000,  6.250) = 876 
    [ 6.250,  7.500) = 282 
    [ 7.500,  8.750) = 110 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     15.679 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.808 ±(99.9%) 0.006 ms/op
Iteration   1: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.707 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  6.409 ms/op
                 existUser·p0.9999: 18.984 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   3.981 ms/op
                 existUser·p0.999:  7.431 ms/op
                 existUser·p0.9999: 20.781 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   3: 2.878 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  5.518 ms/op
                 existUser·p0.9999: 27.853 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331987
  mean =      2.891 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42473 
    [ 2.500,  5.000) = 288648 
    [ 5.000,  7.500) = 632 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.494 ms/op
     p(99.0000) =      4.084 ms/op
     p(99.9000) =      6.603 ms/op
     p(99.9900) =     21.679 ms/op
     p(99.9990) =     27.973 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.007 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  10.491 ms/op
                 getUser·p0.9999: 13.830 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.266 ms/op
                 getUser·p0.9999: 13.903 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.014 ms/op
                 getUser·p0.9999: 17.384 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313991
  mean =      3.057 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 411 
    [ 1.250,  2.500) = 18898 
    [ 2.500,  3.750) = 278040 
    [ 3.750,  5.000) = 15094 
    [ 5.000,  6.250) = 878 
    [ 6.250,  7.500) = 314 
    [ 7.500,  8.750) = 87 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.045 ms/op
     p(99.9900) =     15.909 ms/op
     p(99.9990) =     17.817 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 4.791 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.011 ms/op
Iteration   1: 3.867 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.667 ms/op
                 listUser·p0.9999: 16.494 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   2: 3.879 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.559 ms/op
                 listUser·p0.999:  15.254 ms/op
                 listUser·p0.9999: 26.469 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   3: 3.928 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  15.278 ms/op
                 listUser·p0.9999: 29.902 ms/op
                 listUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246742
  mean =      3.891 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2920 
    [ 2.500,  5.000) = 225344 
    [ 5.000,  7.500) = 17373 
    [ 7.500, 10.000) = 655 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     15.061 ms/op
     p(99.9900) =     28.355 ms/op
     p(99.9990) =     31.359 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.554 ± 3.379  ops/ms
ClientGrpc.existUser                       thrpt       3  11.337 ± 1.058  ops/ms
ClientGrpc.getUser                         thrpt       3  10.663 ± 1.641  ops/ms
ClientGrpc.listUser                        thrpt       3   8.287 ± 1.201  ops/ms
ClientGrpc.createUser                       avgt       3   3.087 ± 0.362   ms/op
ClientGrpc.existUser                        avgt       3   2.883 ± 0.586   ms/op
ClientGrpc.getUser                          avgt       3   3.005 ± 0.304   ms/op
ClientGrpc.listUser                         avgt       3   3.850 ± 0.164   ms/op
ClientGrpc.createUser                     sample  317858   3.018 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.723           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.126           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.679           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.465           ms/op
ClientGrpc.existUser                      sample  331987   2.891 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.707           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.084           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.603           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.679           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.344           ms/op
ClientGrpc.getUser                        sample  313991   3.057 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.788           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.045           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.909           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.924           ms/op
ClientGrpc.listUser                       sample  246742   3.891 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.015           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.686           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.061           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.355           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.392           ms/op
