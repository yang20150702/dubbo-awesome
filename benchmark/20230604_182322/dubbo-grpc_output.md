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
# Warmup Iteration   1: 3.828 ops/ms
# Warmup Iteration   2: 8.301 ops/ms
# Warmup Iteration   3: 9.712 ops/ms
Iteration   1: 10.319 ops/ms
Iteration   2: 10.361 ops/ms
Iteration   3: 10.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.340 ±(99.9%) 0.377 ops/ms [Average]
  (min, avg, max) = (10.319, 10.340, 10.361), stdev = 0.021
  CI (99.9%): [9.963, 10.717] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.983 ops/ms
# Warmup Iteration   2: 10.195 ops/ms
# Warmup Iteration   3: 10.745 ops/ms
Iteration   1: 11.140 ops/ms
Iteration   2: 11.165 ops/ms
Iteration   3: 10.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.080 ±(99.9%) 2.304 ops/ms [Average]
  (min, avg, max) = (10.935, 11.080, 11.165), stdev = 0.126
  CI (99.9%): [8.776, 13.384] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.961 ops/ms
# Warmup Iteration   2: 9.899 ops/ms
# Warmup Iteration   3: 10.395 ops/ms
Iteration   1: 10.466 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.504 ±(99.9%) 0.974 ops/ms [Average]
  (min, avg, max) = (10.466, 10.504, 10.565), stdev = 0.053
  CI (99.9%): [9.530, 11.477] (assumes normal distribution)


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
# Warmup Iteration   1: 5.483 ops/ms
# Warmup Iteration   2: 7.634 ops/ms
# Warmup Iteration   3: 7.790 ops/ms
Iteration   1: 8.038 ops/ms
Iteration   2: 8.046 ops/ms
Iteration   3: 8.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.070 ±(99.9%) 0.899 ops/ms [Average]
  (min, avg, max) = (8.038, 8.070, 8.127), stdev = 0.049
  CI (99.9%): [7.171, 8.970] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.460 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.003 ms/op
Iteration   1: 3.042 ±(99.9%) 0.002 ms/op
Iteration   2: 2.962 ±(99.9%) 0.003 ms/op
Iteration   3: 3.028 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.010 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (2.962, 3.010, 3.042), stdev = 0.043
  CI (99.9%): [2.229, 3.792] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.003 ms/op
Iteration   1: 2.926 ±(99.9%) 0.002 ms/op
Iteration   2: 2.930 ±(99.9%) 0.002 ms/op
Iteration   3: 2.934 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.930 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (2.926, 2.930, 2.934), stdev = 0.004
  CI (99.9%): [2.858, 3.001] (assumes normal distribution)


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
# Warmup Iteration   1: 4.373 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.003 ms/op
Iteration   1: 3.029 ±(99.9%) 0.002 ms/op
Iteration   2: 3.060 ±(99.9%) 0.002 ms/op
Iteration   3: 3.057 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.049 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (3.029, 3.049, 3.060), stdev = 0.017
  CI (99.9%): [2.738, 3.360] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.367 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.235 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.015 ms/op
Iteration   1: 3.944 ±(99.9%) 0.011 ms/op
Iteration   2: 3.963 ±(99.9%) 0.033 ms/op
Iteration   3: 3.979 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.962 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.944, 3.962, 3.979), stdev = 0.017
  CI (99.9%): [3.645, 4.278] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.375 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.450 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.520 ms/op
                 createUser·p0.999:  7.585 ms/op
                 createUser·p0.9999: 18.443 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.930 ms/op
                 createUser·p0.9999: 22.902 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.298 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.495 ms/op
                 createUser·p0.9999: 16.547 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316586
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20140 
    [ 2.500,  5.000) = 294802 
    [ 5.000,  7.500) = 1279 
    [ 7.500, 10.000) = 172 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.786 ms/op
     p(99.9900) =     21.890 ms/op
     p(99.9990) =     23.254 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.082 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.005 ms/op
Iteration   1: 2.925 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.840 ms/op
                 existUser·p0.9999: 13.470 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  9.549 ms/op
                 existUser·p0.9999: 14.452 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 17.891 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327303
  mean =      2.932 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 873 
    [ 1.250,  2.500) = 39131 
    [ 2.500,  3.750) = 275969 
    [ 3.750,  5.000) = 9516 
    [ 5.000,  6.250) = 1060 
    [ 6.250,  7.500) = 329 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      8.728 ms/op
     p(99.9900) =     15.918 ms/op
     p(99.9990) =     17.924 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.400 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.491 ms/op
                 getUser·p0.999:  7.303 ms/op
                 getUser·p0.9999: 15.082 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  8.070 ms/op
                 getUser·p0.9999: 16.633 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   3: 3.068 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  9.500 ms/op
                 getUser·p0.9999: 30.335 ms/op
                 getUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312634
  mean =      3.070 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18303 
    [ 2.500,  5.000) = 292477 
    [ 5.000,  7.500) = 1458 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.985 ms/op
     p(99.9900) =     28.065 ms/op
     p(99.9990) =     30.441 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 5.943 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.011 ms/op
Iteration   1: 4.007 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  13.568 ms/op
                 listUser·p0.9999: 16.220 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   2: 4.006 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  15.752 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 3.955 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  16.106 ms/op
                 listUser·p0.9999: 31.818 ms/op
                 listUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240710
  mean =      3.989 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2027 
    [ 2.500,  5.000) = 212228 
    [ 5.000,  7.500) = 24939 
    [ 7.500, 10.000) = 1129 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     15.057 ms/op
     p(99.9900) =     30.886 ms/op
     p(99.9990) =     31.982 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.340 ± 0.377  ops/ms
ClientGrpc.existUser                       thrpt       3  11.080 ± 2.304  ops/ms
ClientGrpc.getUser                         thrpt       3  10.504 ± 0.974  ops/ms
ClientGrpc.listUser                        thrpt       3   8.070 ± 0.899  ops/ms
ClientGrpc.createUser                       avgt       3   3.010 ± 0.782   ms/op
ClientGrpc.existUser                        avgt       3   2.930 ± 0.072   ms/op
ClientGrpc.getUser                          avgt       3   3.049 ± 0.311   ms/op
ClientGrpc.listUser                         avgt       3   3.962 ± 0.316   ms/op
ClientGrpc.createUser                     sample  316586   3.032 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.298           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.786           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.890           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.364           ms/op
ClientGrpc.existUser                      sample  327303   2.932 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.645           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.728           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.918           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.924           ms/op
ClientGrpc.getUser                        sample  312634   3.070 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.750           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.985           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.065           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.507           ms/op
ClientGrpc.listUser                       sample  240710   3.989 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.305           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.057           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.886           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.211           ms/op
