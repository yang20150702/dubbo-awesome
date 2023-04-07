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
# Warmup Iteration   1: 4.195 ops/ms
# Warmup Iteration   2: 9.270 ops/ms
# Warmup Iteration   3: 10.220 ops/ms
Iteration   1: 10.606 ops/ms
Iteration   2: 10.573 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.570 ±(99.9%) 0.689 ops/ms [Average]
  (min, avg, max) = (10.530, 10.570, 10.606), stdev = 0.038
  CI (99.9%): [9.881, 11.258] (assumes normal distribution)


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
# Warmup Iteration   1: 7.413 ops/ms
# Warmup Iteration   2: 10.482 ops/ms
# Warmup Iteration   3: 10.862 ops/ms
Iteration   1: 11.054 ops/ms
Iteration   2: 11.059 ops/ms
Iteration   3: 11.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.102 ±(99.9%) 1.434 ops/ms [Average]
  (min, avg, max) = (11.054, 11.102, 11.193), stdev = 0.079
  CI (99.9%): [9.668, 12.536] (assumes normal distribution)


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
# Warmup Iteration   1: 7.089 ops/ms
# Warmup Iteration   2: 10.000 ops/ms
# Warmup Iteration   3: 10.465 ops/ms
Iteration   1: 10.387 ops/ms
Iteration   2: 10.530 ops/ms
Iteration   3: 10.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.483 ±(99.9%) 1.509 ops/ms [Average]
  (min, avg, max) = (10.387, 10.483, 10.531), stdev = 0.083
  CI (99.9%): [8.974, 11.992] (assumes normal distribution)


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
# Warmup Iteration   1: 5.525 ops/ms
# Warmup Iteration   2: 7.572 ops/ms
# Warmup Iteration   3: 8.046 ops/ms
Iteration   1: 7.998 ops/ms
Iteration   2: 8.012 ops/ms
Iteration   3: 7.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.974 ±(99.9%) 1.006 ops/ms [Average]
  (min, avg, max) = (7.910, 7.974, 8.012), stdev = 0.055
  CI (99.9%): [6.967, 8.980] (assumes normal distribution)


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.002 ms/op
Iteration   1: 3.040 ±(99.9%) 0.004 ms/op
Iteration   2: 3.057 ±(99.9%) 0.004 ms/op
Iteration   3: 3.076 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.058 ±(99.9%) 0.326 ms/op [Average]
  (min, avg, max) = (3.040, 3.058, 3.076), stdev = 0.018
  CI (99.9%): [2.732, 3.384] (assumes normal distribution)


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.003 ms/op
Iteration   1: 2.892 ±(99.9%) 0.002 ms/op
Iteration   2: 2.973 ±(99.9%) 0.002 ms/op
Iteration   3: 2.906 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.924 ±(99.9%) 0.790 ms/op [Average]
  (min, avg, max) = (2.892, 2.924, 2.973), stdev = 0.043
  CI (99.9%): [2.134, 3.713] (assumes normal distribution)


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.004 ms/op
Iteration   1: 3.023 ±(99.9%) 0.003 ms/op
Iteration   2: 3.002 ±(99.9%) 0.003 ms/op
Iteration   3: 3.009 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.011 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (3.002, 3.011, 3.023), stdev = 0.011
  CI (99.9%): [2.810, 3.212] (assumes normal distribution)


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
# Warmup Iteration   1: 5.627 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.010 ms/op
Iteration   1: 3.851 ±(99.9%) 0.016 ms/op
Iteration   2: 3.953 ±(99.9%) 0.016 ms/op
Iteration   3: 3.950 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.918 ±(99.9%) 1.066 ms/op [Average]
  (min, avg, max) = (3.851, 3.918, 3.953), stdev = 0.058
  CI (99.9%): [2.852, 4.984] (assumes normal distribution)


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
# Warmup Iteration   1: 4.474 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 3.099 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.146 ms/op
                 createUser·p0.9999: 14.107 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.536 ms/op
                 createUser·p0.999:  6.082 ms/op
                 createUser·p0.9999: 22.694 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  9.864 ms/op
                 createUser·p0.9999: 22.820 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316399
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23591 
    [ 2.500,  5.000) = 291505 
    [ 5.000,  7.500) = 1033 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.176 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     23.325 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 3.920 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.006 ms/op
Iteration   1: 2.945 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.092 ms/op
                 existUser·p0.9999: 11.822 ms/op
                 existUser·p1.00:   12.190 ms/op

Iteration   2: 2.883 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.362 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  7.283 ms/op
                 existUser·p0.9999: 13.186 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   3: 2.936 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  10.469 ms/op
                 existUser·p0.9999: 16.810 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328619
  mean =      2.921 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1717 
    [ 1.250,  2.500) = 36240 
    [ 2.500,  3.750) = 279143 
    [ 3.750,  5.000) = 10612 
    [ 5.000,  6.250) = 380 
    [ 6.250,  7.500) = 202 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      7.458 ms/op
     p(99.9900) =     16.531 ms/op
     p(99.9990) =     16.988 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.006 ms/op
Iteration   1: 3.091 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.954 ms/op
                 getUser·p0.9999: 12.685 ms/op
                 getUser·p1.00:   13.206 ms/op

Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.389 ms/op
                 getUser·p0.9999: 19.320 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  6.595 ms/op
                 getUser·p0.9999: 16.412 ms/op
                 getUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313840
  mean =      3.061 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 353 
    [ 1.250,  2.500) = 14716 
    [ 2.500,  3.750) = 283665 
    [ 3.750,  5.000) = 13540 
    [ 5.000,  6.250) = 964 
    [ 6.250,  7.500) = 308 
    [ 7.500,  8.750) = 87 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.325 ms/op
     p(99.9900) =     18.517 ms/op
     p(99.9990) =     19.521 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 5.149 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
Iteration   1: 3.891 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.053 ms/op
                 listUser·p0.9999: 14.476 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   2: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.767 ms/op
                 listUser·p0.9999: 16.768 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   3: 3.952 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 18.986 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243985
  mean =      3.936 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3666 
    [ 2.500,  5.000) = 217734 
    [ 5.000,  7.500) = 21431 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     19.548 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.570 ± 0.689  ops/ms
ClientGrpc.existUser                       thrpt       3  11.102 ± 1.434  ops/ms
ClientGrpc.getUser                         thrpt       3  10.483 ± 1.509  ops/ms
ClientGrpc.listUser                        thrpt       3   7.974 ± 1.006  ops/ms
ClientGrpc.createUser                       avgt       3   3.058 ± 0.326   ms/op
ClientGrpc.existUser                        avgt       3   2.924 ± 0.790   ms/op
ClientGrpc.getUser                          avgt       3   3.011 ± 0.201   ms/op
ClientGrpc.listUser                         avgt       3   3.918 ± 1.066   ms/op
ClientGrpc.createUser                     sample  316399   3.035 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.751           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.176           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.610           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.757           ms/op
ClientGrpc.existUser                      sample  328619   2.921 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.362           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.458           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.531           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  313840   3.061 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.672           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.325           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.517           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.562           ms/op
ClientGrpc.listUser                       sample  243985   3.936 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.081           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.861           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.941           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.054           ms/op
