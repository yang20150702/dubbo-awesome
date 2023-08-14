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
# Warmup Iteration   1: 4.086 ops/ms
# Warmup Iteration   2: 8.864 ops/ms
# Warmup Iteration   3: 9.442 ops/ms
Iteration   1: 8.980 ops/ms
Iteration   2: 8.961 ops/ms
Iteration   3: 9.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.982 ±(99.9%) 0.401 ops/ms [Average]
  (min, avg, max) = (8.961, 8.982, 9.005), stdev = 0.022
  CI (99.9%): [8.580, 9.383] (assumes normal distribution)


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
# Warmup Iteration   1: 6.190 ops/ms
# Warmup Iteration   2: 8.643 ops/ms
# Warmup Iteration   3: 9.354 ops/ms
Iteration   1: 9.729 ops/ms
Iteration   2: 9.652 ops/ms
Iteration   3: 9.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.731 ±(99.9%) 1.472 ops/ms [Average]
  (min, avg, max) = (9.652, 9.731, 9.813), stdev = 0.081
  CI (99.9%): [8.259, 11.203] (assumes normal distribution)


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
# Warmup Iteration   1: 6.716 ops/ms
# Warmup Iteration   2: 10.249 ops/ms
# Warmup Iteration   3: 10.380 ops/ms
Iteration   1: 10.562 ops/ms
Iteration   2: 10.365 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.475 ±(99.9%) 1.834 ops/ms [Average]
  (min, avg, max) = (10.365, 10.475, 10.562), stdev = 0.101
  CI (99.9%): [8.641, 12.308] (assumes normal distribution)


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
# Warmup Iteration   1: 5.454 ops/ms
# Warmup Iteration   2: 7.476 ops/ms
# Warmup Iteration   3: 7.865 ops/ms
Iteration   1: 7.878 ops/ms
Iteration   2: 7.910 ops/ms
Iteration   3: 7.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.876 ±(99.9%) 0.649 ops/ms [Average]
  (min, avg, max) = (7.839, 7.876, 7.910), stdev = 0.036
  CI (99.9%): [7.227, 8.525] (assumes normal distribution)


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
# Warmup Iteration   1: 4.229 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.003 ms/op
Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
Iteration   3: 3.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.084 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (3.070, 3.084, 3.098), stdev = 0.014
  CI (99.9%): [2.828, 3.341] (assumes normal distribution)


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.003 ms/op
Iteration   1: 2.929 ±(99.9%) 0.003 ms/op
Iteration   2: 2.931 ±(99.9%) 0.004 ms/op
Iteration   3: 2.892 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.917 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (2.892, 2.917, 2.931), stdev = 0.022
  CI (99.9%): [2.519, 3.315] (assumes normal distribution)


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.004 ms/op
Iteration   1: 3.084 ±(99.9%) 0.004 ms/op
Iteration   2: 3.059 ±(99.9%) 0.003 ms/op
Iteration   3: 3.039 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.061 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (3.039, 3.061, 3.084), stdev = 0.022
  CI (99.9%): [2.655, 3.467] (assumes normal distribution)


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
# Warmup Iteration   1: 5.408 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.007 ms/op
Iteration   1: 4.072 ±(99.9%) 0.014 ms/op
Iteration   2: 4.014 ±(99.9%) 0.018 ms/op
Iteration   3: 4.077 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.054 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (4.014, 4.054, 4.077), stdev = 0.035
  CI (99.9%): [3.419, 4.689] (assumes normal distribution)


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
# Warmup Iteration   1: 4.252 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
Iteration   1: 3.057 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  11.071 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   2: 3.007 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  7.893 ms/op
                 createUser·p0.9999: 22.196 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.040 ms/op
                 createUser·p0.9999: 29.164 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315876
  mean =      3.038 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19352 
    [ 2.500,  5.000) = 294790 
    [ 5.000,  7.500) = 1249 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     26.359 ms/op
     p(99.9990) =     29.317 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
Iteration   1: 2.957 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  8.941 ms/op
                 existUser·p0.9999: 12.730 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   2: 3.001 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  8.397 ms/op
                 existUser·p0.9999: 14.260 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   3: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.303 ms/op
                 existUser·p0.999:  8.097 ms/op
                 existUser·p0.9999: 15.533 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324194
  mean =      2.958 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1242 
    [ 1.250,  2.500) = 27450 
    [ 2.500,  3.750) = 284693 
    [ 3.750,  5.000) = 9125 
    [ 5.000,  6.250) = 744 
    [ 6.250,  7.500) = 445 
    [ 7.500,  8.750) = 252 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.451 ms/op
     p(99.9900) =     14.950 ms/op
     p(99.9990) =     15.630 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


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
# Warmup Iteration   1: 4.311 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
Iteration   1: 3.082 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.638 ms/op
                 getUser·p0.9999: 19.878 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   2: 3.083 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   5.136 ms/op
                 getUser·p0.999:  11.949 ms/op
                 getUser·p0.9999: 26.124 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.577 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.400 ms/op
                 getUser·p0.999:  7.856 ms/op
                 getUser·p0.9999: 18.174 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311466
  mean =      3.082 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17318 
    [ 2.500,  5.000) = 291610 
    [ 5.000,  7.500) = 1909 
    [ 7.500, 10.000) = 341 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.825 ms/op
     p(99.9000) =      8.922 ms/op
     p(99.9900) =     25.418 ms/op
     p(99.9990) =     26.371 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 5.003 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.011 ms/op
Iteration   1: 3.987 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 16.481 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 4.009 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  17.697 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 4.055 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  16.452 ms/op
                 listUser·p0.9999: 27.463 ms/op
                 listUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239018
  mean =      4.017 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2824 
    [ 2.500,  5.000) = 211883 
    [ 5.000,  7.500) = 22471 
    [ 7.500, 10.000) = 1301 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     26.775 ms/op
     p(99.9990) =     31.707 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.982 ± 0.401  ops/ms
ClientGrpc.existUser                       thrpt       3   9.731 ± 1.472  ops/ms
ClientGrpc.getUser                         thrpt       3  10.475 ± 1.834  ops/ms
ClientGrpc.listUser                        thrpt       3   7.876 ± 0.649  ops/ms
ClientGrpc.createUser                       avgt       3   3.084 ± 0.257   ms/op
ClientGrpc.existUser                        avgt       3   2.917 ± 0.398   ms/op
ClientGrpc.getUser                          avgt       3   3.061 ± 0.406   ms/op
ClientGrpc.listUser                         avgt       3   4.054 ± 0.635   ms/op
ClientGrpc.createUser                     sample  315876   3.038 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.656           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.086           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.359           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.426           ms/op
ClientGrpc.existUser                      sample  324194   2.958 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.536           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.451           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.950           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.679           ms/op
ClientGrpc.getUser                        sample  311466   3.082 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.577           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.825           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.922           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.418           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.444           ms/op
ClientGrpc.listUser                       sample  239018   4.017 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.766           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.581           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.775           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.850           ms/op
