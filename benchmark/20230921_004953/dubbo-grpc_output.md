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
# Warmup Iteration   1: 4.141 ops/ms
# Warmup Iteration   2: 8.900 ops/ms
# Warmup Iteration   3: 9.778 ops/ms
Iteration   1: 10.218 ops/ms
Iteration   2: 10.023 ops/ms
Iteration   3: 10.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.223 ±(99.9%) 3.682 ops/ms [Average]
  (min, avg, max) = (10.023, 10.223, 10.426), stdev = 0.202
  CI (99.9%): [6.541, 13.904] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.902 ops/ms
# Warmup Iteration   2: 10.450 ops/ms
# Warmup Iteration   3: 10.441 ops/ms
Iteration   1: 10.480 ops/ms
Iteration   2: 10.655 ops/ms
Iteration   3: 10.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.604 ±(99.9%) 1.980 ops/ms [Average]
  (min, avg, max) = (10.480, 10.604, 10.678), stdev = 0.109
  CI (99.9%): [8.625, 12.584] (assumes normal distribution)


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
# Warmup Iteration   1: 6.819 ops/ms
# Warmup Iteration   2: 9.963 ops/ms
# Warmup Iteration   3: 10.217 ops/ms
Iteration   1: 10.202 ops/ms
Iteration   2: 10.196 ops/ms
Iteration   3: 10.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.238 ±(99.9%) 1.237 ops/ms [Average]
  (min, avg, max) = (10.196, 10.238, 10.317), stdev = 0.068
  CI (99.9%): [9.001, 11.475] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.302 ops/ms
# Warmup Iteration   2: 7.709 ops/ms
# Warmup Iteration   3: 8.036 ops/ms
Iteration   1: 8.088 ops/ms
Iteration   2: 8.063 ops/ms
Iteration   3: 8.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.074 ±(99.9%) 0.238 ops/ms [Average]
  (min, avg, max) = (8.063, 8.074, 8.088), stdev = 0.013
  CI (99.9%): [7.836, 8.312] (assumes normal distribution)


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.001 ms/op
Iteration   1: 3.161 ±(99.9%) 0.001 ms/op
Iteration   2: 3.178 ±(99.9%) 0.001 ms/op
Iteration   3: 3.096 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.145 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.096, 3.145, 3.178), stdev = 0.043
  CI (99.9%): [2.359, 3.931] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.118 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.004 ms/op
Iteration   1: 2.993 ±(99.9%) 0.002 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 2.937 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.976 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (2.937, 2.976, 2.999), stdev = 0.034
  CI (99.9%): [2.351, 3.601] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.284 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.002 ms/op
Iteration   2: 3.090 ±(99.9%) 0.003 ms/op
Iteration   3: 3.107 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.089 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (3.070, 3.089, 3.107), stdev = 0.018
  CI (99.9%): [2.753, 3.424] (assumes normal distribution)


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
# Warmup Iteration   1: 4.968 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.033 ms/op
Iteration   1: 4.027 ±(99.9%) 0.046 ms/op
Iteration   2: 3.895 ±(99.9%) 0.010 ms/op
Iteration   3: 3.932 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.951 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (3.895, 3.951, 4.027), stdev = 0.068
  CI (99.9%): [2.712, 5.190] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
Iteration   1: 3.156 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  10.840 ms/op
                 createUser·p0.9999: 18.116 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  8.012 ms/op
                 createUser·p0.9999: 18.973 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   3: 3.123 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.540 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  8.559 ms/op
                 createUser·p0.9999: 25.322 ms/op
                 createUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306799
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12031 
    [ 2.500,  5.000) = 292907 
    [ 5.000,  7.500) = 1287 
    [ 7.500, 10.000) = 278 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     24.706 ms/op
     p(99.9990) =     25.522 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.005 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  9.683 ms/op
                 existUser·p0.9999: 13.360 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   2: 2.927 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  6.525 ms/op
                 existUser·p0.9999: 15.909 ms/op
                 existUser·p1.00:   16.155 ms/op

Iteration   3: 2.918 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.274 ms/op
                 existUser·p0.9999: 16.729 ms/op
                 existUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324815
  mean =      2.955 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1103 
    [ 1.250,  2.500) = 29498 
    [ 2.500,  3.750) = 283739 
    [ 3.750,  5.000) = 9137 
    [ 5.000,  6.250) = 704 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      7.832 ms/op
     p(99.9900) =     16.000 ms/op
     p(99.9990) =     17.023 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
Iteration   1: 3.211 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.532 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  9.028 ms/op
                 getUser·p0.9999: 13.304 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 3.171 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  8.167 ms/op
                 getUser·p0.9999: 13.894 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  7.126 ms/op
                 getUser·p0.9999: 23.940 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302661
  mean =      3.172 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9562 
    [ 2.500,  5.000) = 291161 
    [ 5.000,  7.500) = 1511 
    [ 7.500, 10.000) = 216 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.151 ms/op
     p(99.9900) =     22.241 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 5.786 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.011 ms/op
Iteration   1: 4.065 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  17.389 ms/op
                 listUser·p0.9999: 19.217 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   2: 3.942 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  13.829 ms/op
                 listUser·p0.9999: 17.814 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   3: 3.924 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  15.012 ms/op
                 listUser·p0.9999: 19.645 ms/op
                 listUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241400
  mean =      3.976 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1780 
    [ 2.500,  5.000) = 224607 
    [ 5.000,  7.500) = 13735 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     20.260 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.223 ± 3.682  ops/ms
ClientGrpc.existUser                       thrpt       3  10.604 ± 1.980  ops/ms
ClientGrpc.getUser                         thrpt       3  10.238 ± 1.237  ops/ms
ClientGrpc.listUser                        thrpt       3   8.074 ± 0.238  ops/ms
ClientGrpc.createUser                       avgt       3   3.145 ± 0.786   ms/op
ClientGrpc.existUser                        avgt       3   2.976 ± 0.625   ms/op
ClientGrpc.getUser                          avgt       3   3.089 ± 0.335   ms/op
ClientGrpc.listUser                         avgt       3   3.951 ± 1.239   ms/op
ClientGrpc.createUser                     sample  306799   3.129 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.540           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.634           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.706           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.592           ms/op
ClientGrpc.existUser                      sample  324815   2.955 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.701           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.832           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.000           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.138           ms/op
ClientGrpc.getUser                        sample  302661   3.172 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.532           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.151           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.241           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.216           ms/op
ClientGrpc.listUser                       sample  241400   3.976 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.827           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.268           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.480           ms/op
