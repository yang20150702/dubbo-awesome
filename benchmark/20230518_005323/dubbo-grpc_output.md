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
# Warmup Iteration   1: 3.488 ops/ms
# Warmup Iteration   2: 7.823 ops/ms
# Warmup Iteration   3: 8.561 ops/ms
Iteration   1: 9.036 ops/ms
Iteration   2: 9.004 ops/ms
Iteration   3: 8.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.997 ±(99.9%) 0.781 ops/ms [Average]
  (min, avg, max) = (8.951, 8.997, 9.036), stdev = 0.043
  CI (99.9%): [8.216, 9.778] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.254 ops/ms
# Warmup Iteration   2: 9.227 ops/ms
# Warmup Iteration   3: 9.553 ops/ms
Iteration   1: 9.507 ops/ms
Iteration   2: 9.534 ops/ms
Iteration   3: 9.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.524 ±(99.9%) 0.266 ops/ms [Average]
  (min, avg, max) = (9.507, 9.524, 9.534), stdev = 0.015
  CI (99.9%): [9.257, 9.790] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.701 ops/ms
# Warmup Iteration   2: 8.721 ops/ms
# Warmup Iteration   3: 9.149 ops/ms
Iteration   1: 9.241 ops/ms
Iteration   2: 9.261 ops/ms
Iteration   3: 9.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.229 ±(99.9%) 0.707 ops/ms [Average]
  (min, avg, max) = (9.186, 9.229, 9.261), stdev = 0.039
  CI (99.9%): [8.522, 9.936] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.183 ops/ms
# Warmup Iteration   2: 6.854 ops/ms
# Warmup Iteration   3: 6.948 ops/ms
Iteration   1: 7.079 ops/ms
Iteration   2: 6.999 ops/ms
Iteration   3: 7.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.093 ±(99.9%) 1.840 ops/ms [Average]
  (min, avg, max) = (6.999, 7.093, 7.200), stdev = 0.101
  CI (99.9%): [5.253, 8.932] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.935 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.006 ms/op
Iteration   1: 3.490 ±(99.9%) 0.004 ms/op
Iteration   2: 3.494 ±(99.9%) 0.004 ms/op
Iteration   3: 3.579 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.521 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (3.490, 3.521, 3.579), stdev = 0.050
  CI (99.9%): [2.602, 4.439] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.920 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.003 ms/op
Iteration   1: 3.416 ±(99.9%) 0.003 ms/op
Iteration   2: 3.333 ±(99.9%) 0.002 ms/op
Iteration   3: 3.363 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.371 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (3.333, 3.371, 3.416), stdev = 0.042
  CI (99.9%): [2.601, 4.140] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.202 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.005 ms/op
Iteration   1: 3.602 ±(99.9%) 0.004 ms/op
Iteration   2: 3.458 ±(99.9%) 0.005 ms/op
Iteration   3: 3.509 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.523 ±(99.9%) 1.333 ms/op [Average]
  (min, avg, max) = (3.458, 3.523, 3.602), stdev = 0.073
  CI (99.9%): [2.190, 4.856] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.904 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.632 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.590 ±(99.9%) 0.024 ms/op
Iteration   1: 4.541 ±(99.9%) 0.008 ms/op
Iteration   2: 4.611 ±(99.9%) 0.014 ms/op
Iteration   3: 4.565 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.573 ±(99.9%) 0.652 ms/op [Average]
  (min, avg, max) = (4.541, 4.573, 4.611), stdev = 0.036
  CI (99.9%): [3.921, 5.224] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.153 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.008 ms/op
Iteration   1: 3.580 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  14.762 ms/op
                 createUser·p0.9999: 21.498 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   2: 3.582 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  9.319 ms/op
                 createUser·p0.9999: 21.103 ms/op
                 createUser·p1.00:   21.430 ms/op

Iteration   3: 3.483 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  10.781 ms/op
                 createUser·p0.9999: 22.893 ms/op
                 createUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 270386
  mean =      3.548 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8776 
    [ 2.500,  5.000) = 255476 
    [ 5.000,  7.500) = 5387 
    [ 7.500, 10.000) = 471 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     10.070 ms/op
     p(99.9900) =     21.724 ms/op
     p(99.9990) =     23.412 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 4.595 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.008 ms/op
Iteration   1: 3.447 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  9.702 ms/op
                 existUser·p0.9999: 23.583 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   2: 3.385 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  12.114 ms/op
                 existUser·p0.9999: 16.679 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   3: 3.401 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  11.074 ms/op
                 existUser·p0.9999: 17.302 ms/op
                 existUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 281351
  mean =      3.411 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10600 
    [ 2.500,  5.000) = 265448 
    [ 5.000,  7.500) = 4373 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     10.644 ms/op
     p(99.9900) =     22.442 ms/op
     p(99.9990) =     23.933 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.007 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.741 ±(99.9%) 0.010 ms/op
Iteration   1: 3.640 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  14.506 ms/op
                 getUser·p0.9999: 18.055 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   2: 3.574 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  12.547 ms/op
                 getUser·p0.9999: 17.009 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   3: 3.441 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.071 ms/op
                 getUser·p0.999:  10.110 ms/op
                 getUser·p0.9999: 16.941 ms/op
                 getUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 270448
  mean =      3.549 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 7393 
    [ 2.500,  3.750) = 189044 
    [ 3.750,  5.000) = 67916 
    [ 5.000,  6.250) = 4592 
    [ 6.250,  7.500) = 636 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 144 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 51 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     11.183 ms/op
     p(99.9900) =     17.266 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 6.628 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.005 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.651 ±(99.9%) 0.012 ms/op
Iteration   1: 4.740 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.988 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  14.885 ms/op
                 listUser·p0.9999: 16.933 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   2: 4.614 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.726 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  17.417 ms/op
                 listUser·p0.9999: 24.971 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   3: 4.553 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.751 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   8.352 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 21.331 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207141
  mean =      4.634 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 633 
    [ 2.500,  5.000) = 162630 
    [ 5.000,  7.500) = 38623 
    [ 7.500, 10.000) = 4376 
    [10.000, 12.500) = 429 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.767 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     17.002 ms/op
     p(99.9900) =     22.455 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.997 ± 0.781  ops/ms
ClientGrpc.existUser                       thrpt       3   9.524 ± 0.266  ops/ms
ClientGrpc.getUser                         thrpt       3   9.229 ± 0.707  ops/ms
ClientGrpc.listUser                        thrpt       3   7.093 ± 1.840  ops/ms
ClientGrpc.createUser                       avgt       3   3.521 ± 0.919   ms/op
ClientGrpc.existUser                        avgt       3   3.371 ± 0.770   ms/op
ClientGrpc.getUser                          avgt       3   3.523 ± 1.333   ms/op
ClientGrpc.listUser                         avgt       3   4.573 ± 0.652   ms/op
ClientGrpc.createUser                     sample  270386   3.548 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.857           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.182           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.070           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.724           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.855           ms/op
ClientGrpc.existUser                      sample  281351   3.411 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.757           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.603           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.644           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.442           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.986           ms/op
ClientGrpc.getUser                        sample  270448   3.549 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.720           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.137           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.595           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.183           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.266           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.809           ms/op
ClientGrpc.listUser                       sample  207141   4.634 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.223           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.440           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.585           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.002           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.455           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.854           ms/op
