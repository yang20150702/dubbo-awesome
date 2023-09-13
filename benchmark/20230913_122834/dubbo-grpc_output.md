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
# Warmup Iteration   1: 4.274 ops/ms
# Warmup Iteration   2: 8.815 ops/ms
# Warmup Iteration   3: 9.943 ops/ms
Iteration   1: 10.381 ops/ms
Iteration   2: 10.521 ops/ms
Iteration   3: 10.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.488 ±(99.9%) 1.731 ops/ms [Average]
  (min, avg, max) = (10.381, 10.488, 10.562), stdev = 0.095
  CI (99.9%): [8.756, 12.219] (assumes normal distribution)


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
# Warmup Iteration   1: 7.372 ops/ms
# Warmup Iteration   2: 10.679 ops/ms
# Warmup Iteration   3: 10.917 ops/ms
Iteration   1: 10.930 ops/ms
Iteration   2: 10.869 ops/ms
Iteration   3: 11.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.013 ±(99.9%) 3.634 ops/ms [Average]
  (min, avg, max) = (10.869, 11.013, 11.241), stdev = 0.199
  CI (99.9%): [7.379, 14.648] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.867 ops/ms
# Warmup Iteration   2: 10.310 ops/ms
# Warmup Iteration   3: 10.551 ops/ms
Iteration   1: 10.482 ops/ms
Iteration   2: 10.542 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.501 ±(99.9%) 0.635 ops/ms [Average]
  (min, avg, max) = (10.480, 10.501, 10.542), stdev = 0.035
  CI (99.9%): [9.866, 11.137] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.308 ops/ms
# Warmup Iteration   2: 7.767 ops/ms
# Warmup Iteration   3: 7.705 ops/ms
Iteration   1: 8.040 ops/ms
Iteration   2: 8.049 ops/ms
Iteration   3: 7.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.002 ±(99.9%) 1.356 ops/ms [Average]
  (min, avg, max) = (7.916, 8.002, 8.049), stdev = 0.074
  CI (99.9%): [6.646, 9.357] (assumes normal distribution)


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.004 ms/op
Iteration   1: 3.047 ±(99.9%) 0.003 ms/op
Iteration   2: 3.065 ±(99.9%) 0.002 ms/op
Iteration   3: 2.994 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.035 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (2.994, 3.035, 3.065), stdev = 0.037
  CI (99.9%): [2.361, 3.709] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.119 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.004 ms/op
Iteration   1: 2.894 ±(99.9%) 0.003 ms/op
Iteration   2: 2.899 ±(99.9%) 0.002 ms/op
Iteration   3: 2.874 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.889 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.874, 2.889, 2.899), stdev = 0.013
  CI (99.9%): [2.650, 3.128] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.127 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.002 ms/op
Iteration   1: 2.991 ±(99.9%) 0.003 ms/op
Iteration   2: 3.052 ±(99.9%) 0.004 ms/op
Iteration   3: 3.024 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.022 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (2.991, 3.022, 3.052), stdev = 0.031
  CI (99.9%): [2.462, 3.582] (assumes normal distribution)


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
# Warmup Iteration   1: 4.617 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.016 ms/op
Iteration   1: 3.982 ±(99.9%) 0.017 ms/op
Iteration   2: 3.930 ±(99.9%) 0.020 ms/op
Iteration   3: 3.983 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.965 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.930, 3.965, 3.983), stdev = 0.031
  CI (99.9%): [3.404, 4.526] (assumes normal distribution)


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.008 ms/op
Iteration   1: 3.083 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.554 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  11.682 ms/op
                 createUser·p0.9999: 16.496 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.170 ms/op
                 createUser·p0.999:  9.644 ms/op
                 createUser·p0.9999: 26.722 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.622 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.899 ms/op
                 createUser·p0.9999: 19.005 ms/op
                 createUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313768
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18117 
    [ 2.500,  5.000) = 294055 
    [ 5.000,  7.500) = 1102 
    [ 7.500, 10.000) = 174 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =     10.750 ms/op
     p(99.9900) =     25.837 ms/op
     p(99.9990) =     27.127 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
Iteration   1: 2.914 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.741 ms/op
                 existUser·p0.9999: 18.547 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   2: 2.937 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.298 ms/op
                 existUser·p0.9999: 14.126 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.930 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  11.130 ms/op
                 existUser·p0.9999: 14.716 ms/op
                 existUser·p1.00:   15.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328283
  mean =      2.927 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2570 
    [ 1.250,  2.500) = 35246 
    [ 2.500,  3.750) = 279778 
    [ 3.750,  5.000) = 8954 
    [ 5.000,  6.250) = 625 
    [ 6.250,  7.500) = 591 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.400 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     17.870 ms/op
     p(99.9990) =     18.856 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  8.618 ms/op
                 getUser·p0.9999: 12.215 ms/op
                 getUser·p1.00:   12.403 ms/op

Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.811 ms/op
                 getUser·p0.999:  8.107 ms/op
                 getUser·p0.9999: 18.565 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  7.875 ms/op
                 getUser·p0.9999: 16.078 ms/op
                 getUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313378
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1433 
    [ 1.250,  2.500) = 21052 
    [ 2.500,  3.750) = 269567 
    [ 3.750,  5.000) = 18971 
    [ 5.000,  6.250) = 1275 
    [ 6.250,  7.500) = 499 
    [ 7.500,  8.750) = 360 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =      8.372 ms/op
     p(99.9900) =     18.164 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 5.280 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.011 ms/op
Iteration   1: 4.005 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.036 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.155 ms/op
                 listUser·p0.999:  12.719 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 3.960 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  16.384 ms/op
                 listUser·p0.9999: 28.538 ms/op
                 listUser·p1.00:   29.000 ms/op

Iteration   3: 4.031 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 18.385 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240107
  mean =      3.998 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3438 
    [ 2.500,  5.000) = 211212 
    [ 5.000,  7.500) = 23929 
    [ 7.500, 10.000) = 1135 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     14.875 ms/op
     p(99.9900) =     27.656 ms/op
     p(99.9990) =     28.934 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.488 ± 1.731  ops/ms
ClientGrpc.existUser                       thrpt       3  11.013 ± 3.634  ops/ms
ClientGrpc.getUser                         thrpt       3  10.501 ± 0.635  ops/ms
ClientGrpc.listUser                        thrpt       3   8.002 ± 1.356  ops/ms
ClientGrpc.createUser                       avgt       3   3.035 ± 0.674   ms/op
ClientGrpc.existUser                        avgt       3   2.889 ± 0.239   ms/op
ClientGrpc.getUser                          avgt       3   3.022 ± 0.560   ms/op
ClientGrpc.listUser                         avgt       3   3.965 ± 0.561   ms/op
ClientGrpc.createUser                     sample  313768   3.060 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.554           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.750           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.837           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.197           ms/op
ClientGrpc.existUser                      sample  328283   2.927 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.539           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.400           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.454           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.870           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.940           ms/op
ClientGrpc.getUser                        sample  313378   3.066 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.510           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.372           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.164           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.907           ms/op
ClientGrpc.listUser                       sample  240107   3.998 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.824           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.875           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.656           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.000           ms/op
