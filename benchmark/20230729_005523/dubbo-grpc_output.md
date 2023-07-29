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
# Warmup Iteration   1: 3.445 ops/ms
# Warmup Iteration   2: 7.113 ops/ms
# Warmup Iteration   3: 8.104 ops/ms
Iteration   1: 8.702 ops/ms
Iteration   2: 8.601 ops/ms
Iteration   3: 8.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.678 ±(99.9%) 1.241 ops/ms [Average]
  (min, avg, max) = (8.601, 8.678, 8.731), stdev = 0.068
  CI (99.9%): [7.438, 9.919] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.803 ops/ms
# Warmup Iteration   2: 8.645 ops/ms
# Warmup Iteration   3: 9.171 ops/ms
Iteration   1: 9.345 ops/ms
Iteration   2: 9.375 ops/ms
Iteration   3: 9.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.341 ±(99.9%) 0.660 ops/ms [Average]
  (min, avg, max) = (9.303, 9.341, 9.375), stdev = 0.036
  CI (99.9%): [8.681, 10.001] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.801 ops/ms
# Warmup Iteration   2: 8.152 ops/ms
# Warmup Iteration   3: 8.571 ops/ms
Iteration   1: 8.562 ops/ms
Iteration   2: 8.719 ops/ms
Iteration   3: 8.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.678 ±(99.9%) 1.863 ops/ms [Average]
  (min, avg, max) = (8.562, 8.678, 8.753), stdev = 0.102
  CI (99.9%): [6.815, 10.541] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.532 ops/ms
# Warmup Iteration   2: 6.089 ops/ms
# Warmup Iteration   3: 6.428 ops/ms
Iteration   1: 6.585 ops/ms
Iteration   2: 6.601 ops/ms
Iteration   3: 6.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.627 ±(99.9%) 1.074 ops/ms [Average]
  (min, avg, max) = (6.585, 6.627, 6.694), stdev = 0.059
  CI (99.9%): [5.553, 7.700] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.383 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.006 ms/op
Iteration   1: 3.685 ±(99.9%) 0.002 ms/op
Iteration   2: 3.700 ±(99.9%) 0.004 ms/op
Iteration   3: 3.679 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.688 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (3.679, 3.688, 3.700), stdev = 0.011
  CI (99.9%): [3.488, 3.887] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.760 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.004 ms/op
Iteration   1: 3.598 ±(99.9%) 0.003 ms/op
Iteration   2: 3.456 ±(99.9%) 0.004 ms/op
Iteration   3: 3.483 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.512 ±(99.9%) 1.380 ms/op [Average]
  (min, avg, max) = (3.456, 3.512, 3.598), stdev = 0.076
  CI (99.9%): [2.132, 4.893] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.218 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.002 ms/op
Iteration   1: 3.670 ±(99.9%) 0.003 ms/op
Iteration   2: 3.666 ±(99.9%) 0.003 ms/op
Iteration   3: 3.577 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.637 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (3.577, 3.637, 3.670), stdev = 0.052
  CI (99.9%): [2.686, 4.589] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.287 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.934 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 4.813 ±(99.9%) 0.020 ms/op
Iteration   1: 4.806 ±(99.9%) 0.019 ms/op
Iteration   2: 4.716 ±(99.9%) 0.017 ms/op
Iteration   3: 4.906 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.810 ±(99.9%) 1.730 ms/op [Average]
  (min, avg, max) = (4.716, 4.810, 4.906), stdev = 0.095
  CI (99.9%): [3.079, 6.540] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.651 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.009 ms/op
Iteration   1: 3.668 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   5.840 ms/op
                 createUser·p0.999:  12.861 ms/op
                 createUser·p0.9999: 15.192 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   2: 3.599 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  9.814 ms/op
                 createUser·p0.9999: 23.593 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   3: 3.621 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  13.946 ms/op
                 createUser·p0.9999: 19.716 ms/op
                 createUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264450
  mean =      3.629 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8452 
    [ 2.500,  5.000) = 249402 
    [ 5.000,  7.500) = 5817 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     12.322 ms/op
     p(99.9900) =     22.974 ms/op
     p(99.9990) =     23.759 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 4.908 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.008 ms/op
Iteration   1: 3.456 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.517 ms/op
                 existUser·p0.999:  7.569 ms/op
                 existUser·p0.9999: 22.756 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   2: 3.421 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.702 ms/op
                 existUser·p0.999:  7.098 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   3: 3.434 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  10.088 ms/op
                 existUser·p0.9999: 18.493 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279328
  mean =      3.437 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6901 
    [ 2.500,  5.000) = 268357 
    [ 5.000,  7.500) = 3719 
    [ 7.500, 10.000) = 157 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =      8.097 ms/op
     p(99.9900) =     22.350 ms/op
     p(99.9990) =     23.875 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 5.255 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.009 ms/op
Iteration   1: 3.721 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   7.184 ms/op
                 getUser·p0.999:  11.322 ms/op
                 getUser·p0.9999: 15.454 ms/op
                 getUser·p1.00:   15.843 ms/op

Iteration   2: 3.674 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  15.791 ms/op
                 getUser·p0.9999: 26.824 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   3: 3.670 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  8.452 ms/op
                 getUser·p0.9999: 17.756 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260107
  mean =      3.688 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5705 
    [ 2.500,  5.000) = 246161 
    [ 5.000,  7.500) = 7074 
    [ 7.500, 10.000) = 765 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     25.198 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 6.788 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.107 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.736 ±(99.9%) 0.013 ms/op
Iteration   1: 4.796 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.980 ms/op
                 listUser·p0.95:   6.857 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  14.641 ms/op
                 listUser·p0.9999: 22.446 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 4.835 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.078 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 21.861 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.817 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  19.333 ms/op
                 listUser·p0.9999: 21.235 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199304
  mean =      4.816 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 351 
    [ 2.500,  5.000) = 147846 
    [ 5.000,  7.500) = 45384 
    [ 7.500, 10.000) = 4947 
    [10.000, 12.500) = 379 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      6.046 ms/op
     p(95.0000) =      6.906 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     16.484 ms/op
     p(99.9900) =     21.990 ms/op
     p(99.9990) =     23.989 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.678 ± 1.241  ops/ms
ClientGrpc.existUser                       thrpt       3   9.341 ± 0.660  ops/ms
ClientGrpc.getUser                         thrpt       3   8.678 ± 1.863  ops/ms
ClientGrpc.listUser                        thrpt       3   6.627 ± 1.074  ops/ms
ClientGrpc.createUser                       avgt       3   3.688 ± 0.200   ms/op
ClientGrpc.existUser                        avgt       3   3.512 ± 1.380   ms/op
ClientGrpc.getUser                          avgt       3   3.637 ± 0.951   ms/op
ClientGrpc.listUser                         avgt       3   4.810 ± 1.730   ms/op
ClientGrpc.createUser                     sample  264450   3.629 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.911           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.726           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.322           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.974           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.888           ms/op
ClientGrpc.existUser                      sample  279328   3.437 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.767           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.349           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.097           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.350           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.740           ms/op
ClientGrpc.getUser                        sample  260107   3.688 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.855           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.111           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.076           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.198           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.296           ms/op
ClientGrpc.listUser                       sample  199304   4.816 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.204           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.585           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.484           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.990           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.347           ms/op
