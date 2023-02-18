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
# Warmup Iteration   1: 4.873 ops/ms
# Warmup Iteration   2: 9.608 ops/ms
# Warmup Iteration   3: 10.863 ops/ms
Iteration   1: 10.328 ops/ms
Iteration   2: 10.289 ops/ms
Iteration   3: 10.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.295 ±(99.9%) 0.560 ops/ms [Average]
  (min, avg, max) = (10.267, 10.295, 10.328), stdev = 0.031
  CI (99.9%): [9.735, 10.855] (assumes normal distribution)


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
# Warmup Iteration   1: 7.954 ops/ms
# Warmup Iteration   2: 10.684 ops/ms
# Warmup Iteration   3: 10.928 ops/ms
Iteration   1: 11.146 ops/ms
Iteration   2: 11.368 ops/ms
Iteration   3: 11.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.224 ±(99.9%) 2.276 ops/ms [Average]
  (min, avg, max) = (11.146, 11.224, 11.368), stdev = 0.125
  CI (99.9%): [8.948, 13.500] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.162 ops/ms
# Warmup Iteration   2: 10.042 ops/ms
# Warmup Iteration   3: 10.290 ops/ms
Iteration   1: 10.548 ops/ms
Iteration   2: 10.482 ops/ms
Iteration   3: 10.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.470 ±(99.9%) 1.545 ops/ms [Average]
  (min, avg, max) = (10.380, 10.470, 10.548), stdev = 0.085
  CI (99.9%): [8.925, 12.015] (assumes normal distribution)


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
# Warmup Iteration   1: 7.200 ops/ms
# Warmup Iteration   2: 7.930 ops/ms
# Warmup Iteration   3: 8.306 ops/ms
Iteration   1: 8.164 ops/ms
Iteration   2: 8.368 ops/ms
Iteration   3: 8.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.306 ±(99.9%) 2.241 ops/ms [Average]
  (min, avg, max) = (8.164, 8.306, 8.386), stdev = 0.123
  CI (99.9%): [6.064, 10.547] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.004 ms/op
Iteration   1: 2.971 ±(99.9%) 0.002 ms/op
Iteration   2: 3.141 ±(99.9%) 0.001 ms/op
Iteration   3: 3.126 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.080 ±(99.9%) 1.718 ms/op [Average]
  (min, avg, max) = (2.971, 3.080, 3.141), stdev = 0.094
  CI (99.9%): [1.362, 4.798] (assumes normal distribution)


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.877 ±(99.9%) 0.005 ms/op
Iteration   1: 2.934 ±(99.9%) 0.003 ms/op
Iteration   2: 2.942 ±(99.9%) 0.002 ms/op
Iteration   3: 2.917 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.931 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (2.917, 2.931, 2.942), stdev = 0.013
  CI (99.9%): [2.699, 3.162] (assumes normal distribution)


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
# Warmup Iteration   1: 3.671 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.003 ms/op
Iteration   1: 2.969 ±(99.9%) 0.002 ms/op
Iteration   2: 3.099 ±(99.9%) 0.003 ms/op
Iteration   3: 3.037 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.035 ±(99.9%) 1.182 ms/op [Average]
  (min, avg, max) = (2.969, 3.035, 3.099), stdev = 0.065
  CI (99.9%): [1.853, 4.217] (assumes normal distribution)


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
# Warmup Iteration   1: 5.007 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.010 ms/op
Iteration   1: 3.798 ±(99.9%) 0.026 ms/op
Iteration   2: 4.049 ±(99.9%) 0.019 ms/op
Iteration   3: 3.895 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.914 ±(99.9%) 2.309 ms/op [Average]
  (min, avg, max) = (3.798, 3.914, 4.049), stdev = 0.127
  CI (99.9%): [1.605, 6.223] (assumes normal distribution)


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
Iteration   1: 3.024 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  6.309 ms/op
                 createUser·p0.9999: 15.851 ms/op
                 createUser·p1.00:   16.466 ms/op

Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  9.822 ms/op
                 createUser·p0.9999: 16.868 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   3: 3.002 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.620 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.166 ms/op
                 createUser·p0.999:  9.917 ms/op
                 createUser·p0.9999: 21.551 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314740
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31452 
    [ 2.500,  5.000) = 282227 
    [ 5.000,  7.500) = 669 
    [ 7.500, 10.000) = 130 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      9.200 ms/op
     p(99.9900) =     20.892 ms/op
     p(99.9990) =     22.043 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.913 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.007 ms/op
Iteration   1: 2.927 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.388 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  5.590 ms/op
                 existUser·p0.9999: 14.517 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 2.867 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.551 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  11.411 ms/op
                 existUser·p0.9999: 15.642 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  5.874 ms/op
                 existUser·p0.9999: 17.501 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330427
  mean =      2.905 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2625 
    [ 1.250,  2.500) = 53436 
    [ 2.500,  3.750) = 259387 
    [ 3.750,  5.000) = 14262 
    [ 5.000,  6.250) = 352 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 63 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      6.550 ms/op
     p(99.9900) =     17.071 ms/op
     p(99.9990) =     17.806 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  10.633 ms/op
                 getUser·p0.9999: 13.364 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.247 ms/op
                 getUser·p0.9999: 12.772 ms/op
                 getUser·p1.00:   13.107 ms/op

Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.654 ms/op
                 getUser·p0.9999: 29.289 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315291
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32678 
    [ 2.500,  5.000) = 281633 
    [ 5.000,  7.500) = 678 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.315 ms/op
     p(99.9900) =     27.390 ms/op
     p(99.9990) =     29.579 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 5.265 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.010 ms/op
Iteration   1: 3.884 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.328 ms/op
                 listUser·p0.9999: 20.398 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   2: 3.935 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.784 ms/op
                 listUser·p0.999:  20.417 ms/op
                 listUser·p0.9999: 24.113 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   3: 3.928 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 27.713 ms/op
                 listUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245172
  mean =      3.915 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6495 
    [ 2.500,  5.000) = 210779 
    [ 5.000,  7.500) = 26932 
    [ 7.500, 10.000) = 527 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     14.985 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     28.169 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.295 ± 0.560  ops/ms
ClientGrpc.existUser                       thrpt       3  11.224 ± 2.276  ops/ms
ClientGrpc.getUser                         thrpt       3  10.470 ± 1.545  ops/ms
ClientGrpc.listUser                        thrpt       3   8.306 ± 2.241  ops/ms
ClientGrpc.createUser                       avgt       3   3.080 ± 1.718   ms/op
ClientGrpc.existUser                        avgt       3   2.931 ± 0.231   ms/op
ClientGrpc.getUser                          avgt       3   3.035 ± 1.182   ms/op
ClientGrpc.listUser                         avgt       3   3.914 ± 2.309   ms/op
ClientGrpc.createUser                     sample  314740   3.051 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.620           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.200           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.892           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  330427   2.905 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.388           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.550           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.071           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.924           ms/op
ClientGrpc.getUser                        sample  315291   3.046 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.764           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.315           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.390           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.655           ms/op
ClientGrpc.listUser                       sample  245172   3.915 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.830           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.985           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.280           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.279           ms/op
