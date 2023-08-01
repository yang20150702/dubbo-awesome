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
# Warmup Iteration   1: 4.020 ops/ms
# Warmup Iteration   2: 8.693 ops/ms
# Warmup Iteration   3: 9.842 ops/ms
Iteration   1: 10.330 ops/ms
Iteration   2: 10.332 ops/ms
Iteration   3: 10.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.273 ±(99.9%) 1.855 ops/ms [Average]
  (min, avg, max) = (10.155, 10.273, 10.332), stdev = 0.102
  CI (99.9%): [8.417, 12.128] (assumes normal distribution)


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
# Warmup Iteration   1: 7.326 ops/ms
# Warmup Iteration   2: 10.440 ops/ms
# Warmup Iteration   3: 10.932 ops/ms
Iteration   1: 11.065 ops/ms
Iteration   2: 11.054 ops/ms
Iteration   3: 10.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.991 ±(99.9%) 2.191 ops/ms [Average]
  (min, avg, max) = (10.852, 10.991, 11.065), stdev = 0.120
  CI (99.9%): [8.799, 13.182] (assumes normal distribution)


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
# Warmup Iteration   1: 7.230 ops/ms
# Warmup Iteration   2: 10.095 ops/ms
# Warmup Iteration   3: 10.533 ops/ms
Iteration   1: 10.516 ops/ms
Iteration   2: 10.601 ops/ms
Iteration   3: 10.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.542 ±(99.9%) 0.933 ops/ms [Average]
  (min, avg, max) = (10.510, 10.542, 10.601), stdev = 0.051
  CI (99.9%): [9.609, 11.476] (assumes normal distribution)


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
# Warmup Iteration   1: 6.267 ops/ms
# Warmup Iteration   2: 7.608 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 7.851 ops/ms
Iteration   2: 7.980 ops/ms
Iteration   3: 7.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.914 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (7.851, 7.914, 7.980), stdev = 0.065
  CI (99.9%): [6.736, 9.091] (assumes normal distribution)


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
# Warmup Iteration   1: 4.459 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.120 ±(99.9%) 0.002 ms/op
Iteration   2: 3.138 ±(99.9%) 0.003 ms/op
Iteration   3: 3.088 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.115 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (3.088, 3.115, 3.138), stdev = 0.025
  CI (99.9%): [2.651, 3.580] (assumes normal distribution)


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.002 ms/op
Iteration   1: 2.942 ±(99.9%) 0.002 ms/op
Iteration   2: 2.982 ±(99.9%) 0.003 ms/op
Iteration   3: 2.907 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.943 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (2.907, 2.943, 2.982), stdev = 0.037
  CI (99.9%): [2.261, 3.626] (assumes normal distribution)


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
# Warmup Iteration   1: 4.448 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.004 ms/op
Iteration   1: 3.073 ±(99.9%) 0.004 ms/op
Iteration   2: 3.069 ±(99.9%) 0.003 ms/op
Iteration   3: 3.051 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.064 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (3.051, 3.064, 3.073), stdev = 0.012
  CI (99.9%): [2.849, 3.280] (assumes normal distribution)


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
# Warmup Iteration   1: 5.405 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.023 ms/op
Iteration   1: 4.056 ±(99.9%) 0.033 ms/op
Iteration   2: 4.069 ±(99.9%) 0.015 ms/op
Iteration   3: 4.071 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.065 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (4.056, 4.065, 4.071), stdev = 0.008
  CI (99.9%): [3.913, 4.218] (assumes normal distribution)


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
Iteration   1: 3.055 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  10.561 ms/op
                 createUser·p0.9999: 13.935 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.885 ms/op
                 createUser·p0.9999: 15.655 ms/op
                 createUser·p1.00:   15.860 ms/op

Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  10.221 ms/op
                 createUser·p0.9999: 21.682 ms/op
                 createUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312443
  mean =      3.070 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18528 
    [ 2.500,  5.000) = 291764 
    [ 5.000,  7.500) = 1548 
    [ 7.500, 10.000) = 295 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      9.850 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     21.754 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 4.109 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
Iteration   1: 2.909 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.530 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.193 ms/op
                 existUser·p0.9999: 16.499 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   2: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.689 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 16.205 ms/op
                 existUser·p1.00:   16.384 ms/op

Iteration   3: 2.888 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.543 ms/op
                 existUser·p0.999:  9.347 ms/op
                 existUser·p0.9999: 27.619 ms/op
                 existUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329735
  mean =      2.909 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39558 
    [ 2.500,  5.000) = 288235 
    [ 5.000,  7.500) = 1383 
    [ 7.500, 10.000) = 334 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     18.221 ms/op
     p(99.9990) =     27.997 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 4.184 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
Iteration   1: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.304 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  7.576 ms/op
                 getUser·p0.9999: 18.448 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  8.112 ms/op
                 getUser·p0.9999: 18.502 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  10.207 ms/op
                 getUser·p0.9999: 27.394 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312357
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14164 
    [ 2.500,  5.000) = 295708 
    [ 5.000,  7.500) = 2020 
    [ 7.500, 10.000) = 222 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.304 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =      8.058 ms/op
     p(99.9900) =     26.690 ms/op
     p(99.9990) =     27.427 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 5.901 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.225 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.010 ms/op
Iteration   1: 4.143 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  15.674 ms/op
                 listUser·p0.9999: 20.728 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 4.008 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.621 ms/op
                 listUser·p0.9999: 16.702 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 4.102 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  20.218 ms/op
                 listUser·p0.9999: 26.811 ms/op
                 listUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234927
  mean =      4.084 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2155 
    [ 2.500,  5.000) = 204358 
    [ 5.000,  7.500) = 26407 
    [ 7.500, 10.000) = 1386 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     25.281 ms/op
     p(99.9990) =     27.152 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.273 ± 1.855  ops/ms
ClientGrpc.existUser                       thrpt       3  10.991 ± 2.191  ops/ms
ClientGrpc.getUser                         thrpt       3  10.542 ± 0.933  ops/ms
ClientGrpc.listUser                        thrpt       3   7.914 ± 1.177  ops/ms
ClientGrpc.createUser                       avgt       3   3.115 ± 0.464   ms/op
ClientGrpc.existUser                        avgt       3   2.943 ± 0.682   ms/op
ClientGrpc.getUser                          avgt       3   3.064 ± 0.215   ms/op
ClientGrpc.listUser                         avgt       3   4.065 ± 0.153   ms/op
ClientGrpc.createUser                     sample  312443   3.070 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.734           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.850           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.907           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.758           ms/op
ClientGrpc.existUser                      sample  329735   2.909 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.530           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.552           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.221           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.082           ms/op
ClientGrpc.getUser                        sample  312357   3.073 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.304           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.058           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.690           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.541           ms/op
ClientGrpc.listUser                       sample  234927   4.084 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.155           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.332           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.368           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.281           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.230           ms/op
