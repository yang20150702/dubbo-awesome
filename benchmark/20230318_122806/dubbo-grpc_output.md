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
# Warmup Iteration   1: 4.595 ops/ms
# Warmup Iteration   2: 9.326 ops/ms
# Warmup Iteration   3: 10.440 ops/ms
Iteration   1: 10.617 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.683 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (10.617, 10.683, 10.746), stdev = 0.064
  CI (99.9%): [9.508, 11.858] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.929 ops/ms
# Warmup Iteration   2: 10.843 ops/ms
# Warmup Iteration   3: 11.141 ops/ms
Iteration   1: 11.285 ops/ms
Iteration   2: 11.283 ops/ms
Iteration   3: 11.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.373 ±(99.9%) 2.805 ops/ms [Average]
  (min, avg, max) = (11.283, 11.373, 11.550), stdev = 0.154
  CI (99.9%): [8.567, 14.178] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.671 ops/ms
# Warmup Iteration   2: 10.364 ops/ms
# Warmup Iteration   3: 10.451 ops/ms
Iteration   1: 10.867 ops/ms
Iteration   2: 10.844 ops/ms
Iteration   3: 10.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.843 ±(99.9%) 0.435 ops/ms [Average]
  (min, avg, max) = (10.819, 10.843, 10.867), stdev = 0.024
  CI (99.9%): [10.409, 11.278] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.685 ops/ms
# Warmup Iteration   2: 8.055 ops/ms
# Warmup Iteration   3: 8.533 ops/ms
Iteration   1: 8.280 ops/ms
Iteration   2: 8.354 ops/ms
Iteration   3: 8.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.406 ±(99.9%) 2.885 ops/ms [Average]
  (min, avg, max) = (8.280, 8.406, 8.583), stdev = 0.158
  CI (99.9%): [5.520, 11.291] (assumes normal distribution)


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.003 ms/op
Iteration   1: 2.978 ±(99.9%) 0.003 ms/op
Iteration   2: 2.929 ±(99.9%) 0.002 ms/op
Iteration   3: 2.976 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.961 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (2.929, 2.961, 2.978), stdev = 0.027
  CI (99.9%): [2.460, 3.462] (assumes normal distribution)


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
# Warmup Iteration   1: 3.888 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.859 ±(99.9%) 0.003 ms/op
Iteration   1: 2.755 ±(99.9%) 0.003 ms/op
Iteration   2: 2.814 ±(99.9%) 0.003 ms/op
Iteration   3: 2.887 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.819 ±(99.9%) 1.200 ms/op [Average]
  (min, avg, max) = (2.755, 2.819, 2.887), stdev = 0.066
  CI (99.9%): [1.618, 4.019] (assumes normal distribution)


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.003 ms/op
Iteration   1: 2.959 ±(99.9%) 0.002 ms/op
Iteration   2: 2.986 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.986 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (2.959, 2.986, 3.012), stdev = 0.026
  CI (99.9%): [2.503, 3.469] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.044 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.019 ms/op
Iteration   1: 3.853 ±(99.9%) 0.064 ms/op
Iteration   2: 3.847 ±(99.9%) 0.010 ms/op
Iteration   3: 3.919 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.873 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (3.847, 3.873, 3.919), stdev = 0.040
  CI (99.9%): [3.146, 4.600] (assumes normal distribution)


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.006 ms/op
Iteration   1: 2.960 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.666 ms/op
                 createUser·p0.9999: 13.110 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.351 ms/op
                 createUser·p0.9999: 14.752 ms/op
                 createUser·p1.00:   15.188 ms/op

Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.361 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.981 ms/op
                 createUser·p0.9999: 15.568 ms/op
                 createUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324303
  mean =      2.962 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1650 
    [ 1.250,  2.500) = 28237 
    [ 2.500,  3.750) = 280372 
    [ 3.750,  5.000) = 12758 
    [ 5.000,  6.250) = 713 
    [ 6.250,  7.500) = 233 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.361 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.624 ms/op
     p(99.9900) =     15.148 ms/op
     p(99.9990) =     15.679 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.868 ±(99.9%) 0.005 ms/op
Iteration   1: 2.901 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  8.418 ms/op
                 existUser·p0.9999: 11.829 ms/op
                 existUser·p1.00:   12.091 ms/op

Iteration   2: 2.875 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   3.873 ms/op
                 existUser·p0.999:  5.898 ms/op
                 existUser·p0.9999: 20.509 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   3: 2.870 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.819 ms/op
                 existUser·p0.9999: 15.888 ms/op
                 existUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332966
  mean =      2.882 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45371 
    [ 2.500,  5.000) = 286639 
    [ 5.000,  7.500) = 683 
    [ 7.500, 10.000) = 81 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.808 ms/op
     p(99.9900) =     16.250 ms/op
     p(99.9990) =     20.819 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.007 ms/op
Iteration   1: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.610 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.599 ms/op
                 getUser·p0.9999: 13.140 ms/op
                 getUser·p1.00:   13.320 ms/op

Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.058 ms/op
                 getUser·p0.9999: 13.095 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 3.008 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.594 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  8.051 ms/op
                 getUser·p0.9999: 27.656 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320496
  mean =      2.993 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30179 
    [ 2.500,  5.000) = 288909 
    [ 5.000,  7.500) = 1061 
    [ 7.500, 10.000) = 179 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.795 ms/op
     p(99.9900) =     25.682 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 4.906 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.010 ms/op
Iteration   1: 3.872 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.401 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  12.517 ms/op
                 listUser·p0.9999: 14.434 ms/op
                 listUser·p1.00:   14.696 ms/op

Iteration   2: 3.839 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  12.583 ms/op
                 listUser·p0.9999: 15.155 ms/op
                 listUser·p1.00:   16.220 ms/op

Iteration   3: 3.910 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  17.141 ms/op
                 listUser·p0.9999: 24.609 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247967
  mean =      3.874 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4320 
    [ 2.500,  5.000) = 223682 
    [ 5.000,  7.500) = 18965 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.401 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.026 ms/op
     p(99.9900) =     24.458 ms/op
     p(99.9990) =     24.708 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.683 ± 1.175  ops/ms
ClientGrpc.existUser                       thrpt       3  11.373 ± 2.805  ops/ms
ClientGrpc.getUser                         thrpt       3  10.843 ± 0.435  ops/ms
ClientGrpc.listUser                        thrpt       3   8.406 ± 2.885  ops/ms
ClientGrpc.createUser                       avgt       3   2.961 ± 0.501   ms/op
ClientGrpc.existUser                        avgt       3   2.819 ± 1.200   ms/op
ClientGrpc.getUser                          avgt       3   2.986 ± 0.483   ms/op
ClientGrpc.listUser                         avgt       3   3.873 ± 0.727   ms/op
ClientGrpc.createUser                     sample  324303   2.962 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.361           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.445           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.624           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.148           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.040           ms/op
ClientGrpc.existUser                      sample  332966   2.882 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.612           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.808           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.250           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.939           ms/op
ClientGrpc.getUser                        sample  320496   2.993 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.594           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.795           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.682           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.344           ms/op
ClientGrpc.listUser                       sample  247967   3.874 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.401           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.026           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.458           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.740           ms/op
