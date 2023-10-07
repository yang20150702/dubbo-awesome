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
# Warmup Iteration   1: 3.914 ops/ms
# Warmup Iteration   2: 8.497 ops/ms
# Warmup Iteration   3: 9.721 ops/ms
Iteration   1: 9.725 ops/ms
Iteration   2: 10.304 ops/ms
Iteration   3: 10.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.128 ±(99.9%) 6.380 ops/ms [Average]
  (min, avg, max) = (9.725, 10.128, 10.355), stdev = 0.350
  CI (99.9%): [3.748, 16.508] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.097 ops/ms
# Warmup Iteration   2: 10.154 ops/ms
# Warmup Iteration   3: 10.388 ops/ms
Iteration   1: 10.902 ops/ms
Iteration   2: 10.680 ops/ms
Iteration   3: 10.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.822 ±(99.9%) 2.242 ops/ms [Average]
  (min, avg, max) = (10.680, 10.822, 10.902), stdev = 0.123
  CI (99.9%): [8.580, 13.063] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.653 ops/ms
# Warmup Iteration   2: 10.026 ops/ms
# Warmup Iteration   3: 10.266 ops/ms
Iteration   1: 10.296 ops/ms
Iteration   2: 10.178 ops/ms
Iteration   3: 10.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.217 ±(99.9%) 1.244 ops/ms [Average]
  (min, avg, max) = (10.177, 10.217, 10.296), stdev = 0.068
  CI (99.9%): [8.974, 11.461] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.435 ops/ms
# Warmup Iteration   2: 7.137 ops/ms
# Warmup Iteration   3: 7.889 ops/ms
Iteration   1: 7.970 ops/ms
Iteration   2: 8.137 ops/ms
Iteration   3: 8.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.118 ±(99.9%) 2.542 ops/ms [Average]
  (min, avg, max) = (7.970, 8.118, 8.246), stdev = 0.139
  CI (99.9%): [5.576, 10.660] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.572 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.002 ms/op
Iteration   1: 3.111 ±(99.9%) 0.015 ms/op
Iteration   2: 3.108 ±(99.9%) 0.004 ms/op
Iteration   3: 3.132 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.117 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (3.108, 3.117, 3.132), stdev = 0.013
  CI (99.9%): [2.884, 3.350] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.004 ms/op
Iteration   1: 2.959 ±(99.9%) 0.007 ms/op
Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
Iteration   3: 2.990 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 0.283 ms/op [Average]
  (min, avg, max) = (2.959, 2.974, 2.990), stdev = 0.016
  CI (99.9%): [2.692, 3.257] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.283 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.004 ms/op
Iteration   1: 3.085 ±(99.9%) 0.004 ms/op
Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
Iteration   3: 3.091 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.098 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (3.085, 3.098, 3.119), stdev = 0.018
  CI (99.9%): [2.769, 3.427] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.039 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.009 ms/op
Iteration   1: 3.918 ±(99.9%) 0.012 ms/op
Iteration   2: 3.942 ±(99.9%) 0.013 ms/op
Iteration   3: 3.981 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.947 ±(99.9%) 0.583 ms/op [Average]
  (min, avg, max) = (3.918, 3.947, 3.981), stdev = 0.032
  CI (99.9%): [3.364, 4.530] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.482 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.300 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
Iteration   1: 3.100 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.334 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   2: 3.171 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  9.246 ms/op
                 createUser·p0.9999: 14.707 ms/op
                 createUser·p1.00:   16.613 ms/op

Iteration   3: 3.193 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  9.259 ms/op
                 createUser·p0.9999: 24.379 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304344
  mean =      3.154 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14224 
    [ 2.500,  5.000) = 288186 
    [ 5.000,  7.500) = 1347 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      9.006 ms/op
     p(99.9900) =     20.419 ms/op
     p(99.9990) =     24.636 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.242 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
Iteration   1: 2.996 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.684 ms/op
                 existUser·p0.9999: 20.196 ms/op
                 existUser·p1.00:   20.840 ms/op

Iteration   2: 2.986 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  9.853 ms/op
                 existUser·p0.9999: 21.744 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  8.409 ms/op
                 existUser·p0.9999: 20.546 ms/op
                 existUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319205
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26096 
    [ 2.500,  5.000) = 291268 
    [ 5.000,  7.500) = 1325 
    [ 7.500, 10.000) = 278 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     22.919 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.464 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.006 ms/op
Iteration   1: 3.152 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  10.804 ms/op
                 getUser·p0.9999: 20.120 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 3.123 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.706 ms/op
                 getUser·p0.999:  7.945 ms/op
                 getUser·p0.9999: 15.377 ms/op
                 getUser·p1.00:   15.778 ms/op

Iteration   3: 3.112 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.334 ms/op
                 getUser·p0.9999: 16.734 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306718
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12874 
    [ 2.500,  5.000) = 291280 
    [ 5.000,  7.500) = 2094 
    [ 7.500, 10.000) = 222 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     19.770 ms/op
     p(99.9990) =     20.281 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 4.854 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.011 ms/op
Iteration   1: 3.947 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.287 ms/op
                 listUser·p0.9999: 14.482 ms/op
                 listUser·p1.00:   14.664 ms/op

Iteration   2: 3.905 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  15.355 ms/op
                 listUser·p0.9999: 17.983 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   3: 3.920 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.142 ms/op
                 listUser·p0.9999: 28.067 ms/op
                 listUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244717
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2848 
    [ 2.500,  5.000) = 226662 
    [ 5.000,  7.500) = 13803 
    [ 7.500, 10.000) = 717 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 311 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.717 ms/op
     p(99.9900) =     26.609 ms/op
     p(99.9990) =     28.530 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.128 ± 6.380  ops/ms
ClientGrpc.existUser                       thrpt       3  10.822 ± 2.242  ops/ms
ClientGrpc.getUser                         thrpt       3  10.217 ± 1.244  ops/ms
ClientGrpc.listUser                        thrpt       3   8.118 ± 2.542  ops/ms
ClientGrpc.createUser                       avgt       3   3.117 ± 0.233   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 0.283   ms/op
ClientGrpc.getUser                          avgt       3   3.098 ± 0.329   ms/op
ClientGrpc.listUser                         avgt       3   3.947 ± 0.583   ms/op
ClientGrpc.createUser                     sample  304344   3.154 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.827           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.940           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.006           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.419           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.707           ms/op
ClientGrpc.existUser                      sample  319205   3.006 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.594           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.028           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.513           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.167           ms/op
ClientGrpc.getUser                        sample  306718   3.129 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.602           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.716           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.770           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.349           ms/op
ClientGrpc.listUser                       sample  244717   3.924 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.854           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.717           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.609           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.738           ms/op
