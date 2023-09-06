# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.231 ops/ms
# Warmup Iteration   2: 9.091 ops/ms
# Warmup Iteration   3: 9.936 ops/ms
Iteration   1: 10.465 ops/ms
Iteration   2: 10.463 ops/ms
Iteration   3: 10.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.487 ±(99.9%) 0.739 ops/ms [Average]
  (min, avg, max) = (10.463, 10.487, 10.534), stdev = 0.040
  CI (99.9%): [9.749, 11.226] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.804 ops/ms
# Warmup Iteration   2: 10.466 ops/ms
# Warmup Iteration   3: 10.860 ops/ms
Iteration   1: 10.916 ops/ms
Iteration   2: 11.107 ops/ms
Iteration   3: 10.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.994 ±(99.9%) 1.832 ops/ms [Average]
  (min, avg, max) = (10.916, 10.994, 11.107), stdev = 0.100
  CI (99.9%): [9.162, 12.826] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.530 ops/ms
# Warmup Iteration   2: 10.475 ops/ms
# Warmup Iteration   3: 10.666 ops/ms
Iteration   1: 10.724 ops/ms
Iteration   2: 10.680 ops/ms
Iteration   3: 10.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.656 ±(99.9%) 1.506 ops/ms [Average]
  (min, avg, max) = (10.564, 10.656, 10.724), stdev = 0.083
  CI (99.9%): [9.150, 12.162] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.631 ops/ms
# Warmup Iteration   2: 8.017 ops/ms
# Warmup Iteration   3: 8.020 ops/ms
Iteration   1: 8.051 ops/ms
Iteration   2: 8.175 ops/ms
Iteration   3: 8.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.157 ±(99.9%) 1.798 ops/ms [Average]
  (min, avg, max) = (8.051, 8.157, 8.245), stdev = 0.099
  CI (99.9%): [6.359, 9.955] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.003 ms/op
Iteration   2: 3.021 ±(99.9%) 0.002 ms/op
Iteration   3: 3.005 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.032 ±(99.9%) 0.615 ms/op [Average]
  (min, avg, max) = (3.005, 3.032, 3.070), stdev = 0.034
  CI (99.9%): [2.417, 3.647] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.792 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.877 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.003 ms/op
Iteration   1: 2.899 ±(99.9%) 0.004 ms/op
Iteration   2: 2.935 ±(99.9%) 0.003 ms/op
Iteration   3: 2.926 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.920 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (2.899, 2.920, 2.935), stdev = 0.019
  CI (99.9%): [2.580, 3.261] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.073 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.002 ms/op
Iteration   1: 3.021 ±(99.9%) 0.003 ms/op
Iteration   2: 3.014 ±(99.9%) 0.002 ms/op
Iteration   3: 3.040 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.025 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (3.014, 3.025, 3.040), stdev = 0.014
  CI (99.9%): [2.774, 3.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.797 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.011 ms/op
Iteration   1: 3.756 ±(99.9%) 0.009 ms/op
Iteration   2: 3.880 ±(99.9%) 0.010 ms/op
Iteration   3: 3.911 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.849 ±(99.9%) 1.489 ms/op [Average]
  (min, avg, max) = (3.756, 3.849, 3.911), stdev = 0.082
  CI (99.9%): [2.360, 5.338] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.037 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.008 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.953 ms/op
                 createUser·p0.9999: 17.876 ms/op
                 createUser·p1.00:   18.317 ms/op

Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.629 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.820 ms/op
                 createUser·p0.9999: 13.810 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   3: 2.995 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.391 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  7.145 ms/op
                 createUser·p0.9999: 26.061 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317090
  mean =      3.027 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26245 
    [ 2.500,  5.000) = 288942 
    [ 5.000,  7.500) = 1527 
    [ 7.500, 10.000) = 155 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.093 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     26.302 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.007 ms/op
Iteration   1: 2.945 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  7.954 ms/op
                 existUser·p0.9999: 14.029 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.955 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  9.099 ms/op
                 existUser·p0.9999: 13.444 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  7.627 ms/op
                 existUser·p0.9999: 18.062 ms/op
                 existUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324844
  mean =      2.955 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1518 
    [ 1.250,  2.500) = 32255 
    [ 2.500,  3.750) = 277103 
    [ 3.750,  5.000) = 12265 
    [ 5.000,  6.250) = 773 
    [ 6.250,  7.500) = 472 
    [ 7.500,  8.750) = 186 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.038 ms/op
     p(99.9900) =     16.071 ms/op
     p(99.9990) =     18.211 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.129 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.007 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  9.111 ms/op
                 getUser·p0.9999: 12.252 ms/op
                 getUser·p1.00:   12.501 ms/op

Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  12.122 ms/op
                 getUser·p0.9999: 28.367 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 2.990 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.308 ms/op
                 getUser·p0.9999: 26.356 ms/op
                 getUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319420
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24913 
    [ 2.500,  5.000) = 292659 
    [ 5.000,  7.500) = 1415 
    [ 7.500, 10.000) = 174 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.761 ms/op
     p(99.9900) =     26.118 ms/op
     p(99.9990) =     28.666 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.820 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.010 ms/op
Iteration   1: 3.954 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.082 ms/op
                 listUser·p0.9999: 18.183 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   2: 3.918 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.152 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.796 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.221 ms/op
                 listUser·p0.9999: 20.630 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243934
  mean =      3.935 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2565 
    [ 2.500,  5.000) = 220609 
    [ 5.000,  7.500) = 19176 
    [ 7.500, 10.000) = 1028 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     13.731 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     21.387 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.487 ± 0.739  ops/ms
ClientGrpc.existUser                       thrpt       3  10.994 ± 1.832  ops/ms
ClientGrpc.getUser                         thrpt       3  10.656 ± 1.506  ops/ms
ClientGrpc.listUser                        thrpt       3   8.157 ± 1.798  ops/ms
ClientGrpc.createUser                       avgt       3   3.032 ± 0.615   ms/op
ClientGrpc.existUser                        avgt       3   2.920 ± 0.340   ms/op
ClientGrpc.getUser                          avgt       3   3.025 ± 0.251   ms/op
ClientGrpc.listUser                         avgt       3   3.849 ± 1.489   ms/op
ClientGrpc.createUser                     sample  317090   3.027 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.391           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.093           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.657           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.411           ms/op
ClientGrpc.existUser                      sample  324844   2.955 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.517           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.038           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.071           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.448           ms/op
ClientGrpc.getUser                        sample  319420   3.006 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.618           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.761           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.118           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.803           ms/op
ClientGrpc.listUser                       sample  243934   3.935 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.796           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.731           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.054           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.529           ms/op
