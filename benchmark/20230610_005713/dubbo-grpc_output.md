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
# Warmup Iteration   1: 4.658 ops/ms
# Warmup Iteration   2: 9.432 ops/ms
# Warmup Iteration   3: 10.185 ops/ms
Iteration   1: 10.666 ops/ms
Iteration   2: 10.664 ops/ms
Iteration   3: 11.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.778 ±(99.9%) 3.579 ops/ms [Average]
  (min, avg, max) = (10.664, 10.778, 11.005), stdev = 0.196
  CI (99.9%): [7.199, 14.357] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.042 ops/ms
# Warmup Iteration   2: 10.791 ops/ms
# Warmup Iteration   3: 11.144 ops/ms
Iteration   1: 11.387 ops/ms
Iteration   2: 11.171 ops/ms
Iteration   3: 11.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.218 ±(99.9%) 2.762 ops/ms [Average]
  (min, avg, max) = (11.096, 11.218, 11.387), stdev = 0.151
  CI (99.9%): [8.456, 13.979] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.145 ops/ms
# Warmup Iteration   2: 10.336 ops/ms
# Warmup Iteration   3: 10.715 ops/ms
Iteration   1: 10.711 ops/ms
Iteration   2: 10.572 ops/ms
Iteration   3: 10.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.697 ±(99.9%) 2.169 ops/ms [Average]
  (min, avg, max) = (10.572, 10.697, 10.808), stdev = 0.119
  CI (99.9%): [8.529, 12.866] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.078 ops/ms
# Warmup Iteration   2: 7.529 ops/ms
# Warmup Iteration   3: 7.916 ops/ms
Iteration   1: 8.133 ops/ms
Iteration   2: 8.157 ops/ms
Iteration   3: 8.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.118 ±(99.9%) 0.864 ops/ms [Average]
  (min, avg, max) = (8.065, 8.118, 8.157), stdev = 0.047
  CI (99.9%): [7.254, 8.982] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.141 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.003 ms/op
Iteration   1: 2.964 ±(99.9%) 0.002 ms/op
Iteration   2: 2.992 ±(99.9%) 0.004 ms/op
Iteration   3: 2.967 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.974 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (2.964, 2.974, 2.992), stdev = 0.016
  CI (99.9%): [2.690, 3.259] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.883 ±(99.9%) 0.003 ms/op
Iteration   1: 2.872 ±(99.9%) 0.003 ms/op
Iteration   2: 2.929 ±(99.9%) 0.004 ms/op
Iteration   3: 2.875 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (2.872, 2.892, 2.929), stdev = 0.032
  CI (99.9%): [2.311, 3.472] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.826 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.002 ms/op
Iteration   1: 3.002 ±(99.9%) 0.006 ms/op
Iteration   2: 2.964 ±(99.9%) 0.002 ms/op
Iteration   3: 2.960 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.975 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (2.960, 2.975, 3.002), stdev = 0.024
  CI (99.9%): [2.545, 3.406] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.017 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.009 ms/op
Iteration   1: 3.806 ±(99.9%) 0.012 ms/op
Iteration   2: 3.928 ±(99.9%) 0.010 ms/op
Iteration   3: 3.879 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.871 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (3.806, 3.871, 3.928), stdev = 0.061
  CI (99.9%): [2.753, 4.988] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.027 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.310 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.176 ms/op
                 createUser·p0.9999: 15.786 ms/op
                 createUser·p1.00:   15.991 ms/op

Iteration   2: 2.978 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  6.771 ms/op
                 createUser·p0.9999: 20.480 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  12.160 ms/op
                 createUser·p0.9999: 20.572 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320659
  mean =      2.993 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30460 
    [ 2.500,  5.000) = 288779 
    [ 5.000,  7.500) = 1048 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.842 ms/op
     p(99.9900) =     20.412 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.948 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.005 ms/op
Iteration   1: 2.825 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  7.137 ms/op
                 existUser·p0.9999: 11.775 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   2: 2.894 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.469 ms/op
                 existUser·p0.9999: 19.694 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   3: 2.817 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.391 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  5.624 ms/op
                 existUser·p0.9999: 25.253 ms/op
                 existUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337177
  mean =      2.845 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53995 
    [ 2.500,  5.000) = 282120 
    [ 5.000,  7.500) = 797 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      6.762 ms/op
     p(99.9900) =     20.301 ms/op
     p(99.9990) =     25.481 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 3.949 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.666 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  6.885 ms/op
                 getUser·p0.9999: 20.046 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.284 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.545 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  8.183 ms/op
                 getUser·p0.9999: 13.180 ms/op
                 getUser·p1.00:   13.484 ms/op

Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.601 ms/op
                 getUser·p0.9999: 15.575 ms/op
                 getUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318125
  mean =      3.019 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20372 
    [ 2.500,  5.000) = 296525 
    [ 5.000,  7.500) = 917 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.284 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.421 ms/op
     p(99.9900) =     19.247 ms/op
     p(99.9990) =     20.337 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 4.573 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.010 ms/op
Iteration   1: 3.917 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  12.816 ms/op
                 listUser·p0.9999: 16.397 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 3.875 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.466 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.115 ms/op
                 listUser·p0.9999: 20.095 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 3.843 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  13.378 ms/op
                 listUser·p0.9999: 20.186 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247532
  mean =      3.878 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5012 
    [ 2.500,  5.000) = 223074 
    [ 5.000,  7.500) = 18250 
    [ 7.500, 10.000) = 754 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     20.695 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.778 ± 3.579  ops/ms
ClientGrpc.existUser                       thrpt       3  11.218 ± 2.762  ops/ms
ClientGrpc.getUser                         thrpt       3  10.697 ± 2.169  ops/ms
ClientGrpc.listUser                        thrpt       3   8.118 ± 0.864  ops/ms
ClientGrpc.createUser                       avgt       3   2.974 ± 0.284   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 0.581   ms/op
ClientGrpc.getUser                          avgt       3   2.975 ± 0.431   ms/op
ClientGrpc.listUser                         avgt       3   3.871 ± 1.117   ms/op
ClientGrpc.createUser                     sample  320659   2.993 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.310           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.842           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.412           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.791           ms/op
ClientGrpc.existUser                      sample  337177   2.845 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.616           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.762           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.301           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.592           ms/op
ClientGrpc.getUser                        sample  318125   3.019 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.284           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.421           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.247           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.414           ms/op
ClientGrpc.listUser                       sample  247532   3.878 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.466           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.042           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.923           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.594           ms/op
