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
# Warmup Iteration   1: 3.769 ops/ms
# Warmup Iteration   2: 8.546 ops/ms
# Warmup Iteration   3: 9.763 ops/ms
Iteration   1: 10.455 ops/ms
Iteration   2: 10.308 ops/ms
Iteration   3: 10.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.407 ±(99.9%) 1.568 ops/ms [Average]
  (min, avg, max) = (10.308, 10.407, 10.459), stdev = 0.086
  CI (99.9%): [8.839, 11.975] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.150 ops/ms
# Warmup Iteration   2: 10.195 ops/ms
# Warmup Iteration   3: 10.970 ops/ms
Iteration   1: 10.945 ops/ms
Iteration   2: 10.795 ops/ms
Iteration   3: 10.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.872 ±(99.9%) 1.365 ops/ms [Average]
  (min, avg, max) = (10.795, 10.872, 10.945), stdev = 0.075
  CI (99.9%): [9.506, 12.237] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.386 ops/ms
# Warmup Iteration   2: 9.515 ops/ms
# Warmup Iteration   3: 10.159 ops/ms
Iteration   1: 10.153 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 10.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.307 ±(99.9%) 2.599 ops/ms [Average]
  (min, avg, max) = (10.153, 10.307, 10.434), stdev = 0.142
  CI (99.9%): [7.708, 12.906] (assumes normal distribution)


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
# Warmup Iteration   1: 5.243 ops/ms
# Warmup Iteration   2: 7.528 ops/ms
# Warmup Iteration   3: 7.823 ops/ms
Iteration   1: 7.819 ops/ms
Iteration   2: 7.877 ops/ms
Iteration   3: 7.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.817 ±(99.9%) 1.125 ops/ms [Average]
  (min, avg, max) = (7.754, 7.817, 7.877), stdev = 0.062
  CI (99.9%): [6.691, 8.942] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.809 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.355 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.003 ms/op
Iteration   1: 3.163 ±(99.9%) 0.002 ms/op
Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
Iteration   3: 3.109 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.117 ±(99.9%) 0.795 ms/op [Average]
  (min, avg, max) = (3.077, 3.117, 3.163), stdev = 0.044
  CI (99.9%): [2.321, 3.912] (assumes normal distribution)


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
# Warmup Iteration   1: 4.118 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.868 ±(99.9%) 0.002 ms/op
Iteration   1: 2.972 ±(99.9%) 0.002 ms/op
Iteration   2: 2.991 ±(99.9%) 0.002 ms/op
Iteration   3: 2.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.960 ±(99.9%) 0.702 ms/op [Average]
  (min, avg, max) = (2.917, 2.960, 2.991), stdev = 0.038
  CI (99.9%): [2.258, 3.662] (assumes normal distribution)


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
# Warmup Iteration   1: 4.471 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.004 ms/op
Iteration   1: 3.078 ±(99.9%) 0.003 ms/op
Iteration   2: 3.106 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.094 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (3.078, 3.094, 3.106), stdev = 0.015
  CI (99.9%): [2.828, 3.361] (assumes normal distribution)


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
# Warmup Iteration   1: 5.109 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.017 ms/op
Iteration   1: 4.178 ±(99.9%) 0.013 ms/op
Iteration   2: 4.064 ±(99.9%) 0.032 ms/op
Iteration   3: 4.014 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.085 ±(99.9%) 1.534 ms/op [Average]
  (min, avg, max) = (4.014, 4.085, 4.178), stdev = 0.084
  CI (99.9%): [2.551, 5.620] (assumes normal distribution)


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
# Warmup Iteration   1: 4.480 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  7.674 ms/op
                 createUser·p0.9999: 18.402 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  9.339 ms/op
                 createUser·p0.9999: 19.615 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  7.389 ms/op
                 createUser·p0.9999: 20.532 ms/op
                 createUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311578
  mean =      3.079 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11661 
    [ 2.500,  5.000) = 298461 
    [ 5.000,  7.500) = 1115 
    [ 7.500, 10.000) = 130 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.720 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     21.124 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 4.325 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.005 ms/op
Iteration   1: 2.948 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.945 ms/op
                 existUser·p0.9999: 12.693 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   2: 2.933 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   3.969 ms/op
                 existUser·p0.999:  6.881 ms/op
                 existUser·p0.9999: 14.156 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.027 ms/op
                 existUser·p0.999:  6.800 ms/op
                 existUser·p0.9999: 16.613 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326476
  mean =      2.940 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1894 
    [ 1.250,  2.500) = 29321 
    [ 2.500,  3.750) = 284164 
    [ 3.750,  5.000) = 10075 
    [ 5.000,  6.250) = 459 
    [ 6.250,  7.500) = 334 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     16.078 ms/op
     p(99.9990) =     17.588 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 4.491 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  7.356 ms/op
                 getUser·p0.9999: 16.876 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.881 ms/op
                 getUser·p0.9999: 18.433 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.784 ms/op
                 getUser·p0.9999: 29.252 ms/op
                 getUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312216
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14421 
    [ 2.500,  5.000) = 296246 
    [ 5.000,  7.500) = 1238 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.478 ms/op
     p(99.9900) =     27.390 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


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
# Warmup Iteration   1: 5.469 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.282 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.138 ±(99.9%) 0.011 ms/op
Iteration   1: 4.089 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  13.807 ms/op
                 listUser·p0.9999: 21.043 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 4.106 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.627 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.125 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 21.286 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.062 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 23.212 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235048
  mean =      4.085 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2377 
    [ 2.500,  5.000) = 206823 
    [ 5.000,  7.500) = 24525 
    [ 7.500, 10.000) = 925 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     15.742 ms/op
     p(99.9900) =     22.724 ms/op
     p(99.9990) =     23.603 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.407 ± 1.568  ops/ms
ClientGrpc.existUser                       thrpt       3  10.872 ± 1.365  ops/ms
ClientGrpc.getUser                         thrpt       3  10.307 ± 2.599  ops/ms
ClientGrpc.listUser                        thrpt       3   7.817 ± 1.125  ops/ms
ClientGrpc.createUser                       avgt       3   3.117 ± 0.795   ms/op
ClientGrpc.existUser                        avgt       3   2.960 ± 0.702   ms/op
ClientGrpc.getUser                          avgt       3   3.094 ± 0.267   ms/op
ClientGrpc.listUser                         avgt       3   4.085 ± 1.534   ms/op
ClientGrpc.createUser                     sample  311578   3.079 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.721           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.720           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.792           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.201           ms/op
ClientGrpc.existUser                      sample  326476   2.940 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.713           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.881           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.078           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.022           ms/op
ClientGrpc.getUser                        sample  312216   3.074 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.614           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.478           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.390           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.688           ms/op
ClientGrpc.listUser                       sample  235048   4.085 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.627           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.928           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.742           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.724           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.724           ms/op
