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
# Warmup Iteration   1: 4.207 ops/ms
# Warmup Iteration   2: 8.654 ops/ms
# Warmup Iteration   3: 10.219 ops/ms
Iteration   1: 10.363 ops/ms
Iteration   2: 10.236 ops/ms
Iteration   3: 10.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.203 ±(99.9%) 3.265 ops/ms [Average]
  (min, avg, max) = (10.010, 10.203, 10.363), stdev = 0.179
  CI (99.9%): [6.938, 13.468] (assumes normal distribution)


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
# Warmup Iteration   1: 7.332 ops/ms
# Warmup Iteration   2: 10.249 ops/ms
# Warmup Iteration   3: 10.439 ops/ms
Iteration   1: 10.642 ops/ms
Iteration   2: 10.630 ops/ms
Iteration   3: 10.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.598 ±(99.9%) 1.216 ops/ms [Average]
  (min, avg, max) = (10.521, 10.598, 10.642), stdev = 0.067
  CI (99.9%): [9.382, 11.813] (assumes normal distribution)


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
# Warmup Iteration   1: 7.104 ops/ms
# Warmup Iteration   2: 10.033 ops/ms
# Warmup Iteration   3: 10.064 ops/ms
Iteration   1: 10.174 ops/ms
Iteration   2: 9.945 ops/ms
Iteration   3: 10.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.084 ±(99.9%) 2.238 ops/ms [Average]
  (min, avg, max) = (9.945, 10.084, 10.174), stdev = 0.123
  CI (99.9%): [7.846, 12.323] (assumes normal distribution)


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
# Warmup Iteration   1: 5.459 ops/ms
# Warmup Iteration   2: 7.654 ops/ms
# Warmup Iteration   3: 7.838 ops/ms
Iteration   1: 7.887 ops/ms
Iteration   2: 7.938 ops/ms
Iteration   3: 8.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.010 ±(99.9%) 3.110 ops/ms [Average]
  (min, avg, max) = (7.887, 8.010, 8.204), stdev = 0.170
  CI (99.9%): [4.900, 11.119] (assumes normal distribution)


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.001 ms/op
Iteration   1: 3.198 ±(99.9%) 0.001 ms/op
Iteration   2: 3.186 ±(99.9%) 0.002 ms/op
Iteration   3: 3.181 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.189 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (3.181, 3.189, 3.198), stdev = 0.009
  CI (99.9%): [3.027, 3.350] (assumes normal distribution)


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.002 ms/op
Iteration   1: 3.023 ±(99.9%) 0.002 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 3.025 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.034 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (3.023, 3.034, 3.055), stdev = 0.018
  CI (99.9%): [2.705, 3.364] (assumes normal distribution)


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.003 ms/op
Iteration   1: 3.084 ±(99.9%) 0.004 ms/op
Iteration   2: 3.161 ±(99.9%) 0.002 ms/op
Iteration   3: 3.176 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.141 ±(99.9%) 0.900 ms/op [Average]
  (min, avg, max) = (3.084, 3.141, 3.176), stdev = 0.049
  CI (99.9%): [2.240, 4.041] (assumes normal distribution)


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
# Warmup Iteration   1: 5.470 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.009 ms/op
Iteration   1: 4.067 ±(99.9%) 0.030 ms/op
Iteration   2: 3.959 ±(99.9%) 0.008 ms/op
Iteration   3: 4.039 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.021 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.959, 4.021, 4.067), stdev = 0.056
  CI (99.9%): [2.997, 5.046] (assumes normal distribution)


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
# Warmup Iteration   1: 4.368 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.007 ms/op
Iteration   1: 3.264 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.390 ms/op
                 createUser·p0.9999: 12.848 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.681 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.633 ms/op
                 createUser·p0.9999: 12.780 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  14.049 ms/op
                 createUser·p0.9999: 23.205 ms/op
                 createUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299934
  mean =      3.199 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23860 
    [ 2.500,  5.000) = 274969 
    [ 5.000,  7.500) = 657 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =     10.407 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
Iteration   1: 2.941 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  5.548 ms/op
                 existUser·p0.9999: 20.775 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.756 ms/op
                 existUser·p0.9999: 16.125 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   3: 3.025 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.385 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319013
  mean =      3.008 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45563 
    [ 2.500,  5.000) = 272491 
    [ 5.000,  7.500) = 708 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.873 ms/op
     p(99.9900) =     22.734 ms/op
     p(99.9990) =     25.416 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.006 ms/op
Iteration   1: 3.219 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.979 ms/op
                 getUser·p0.9999: 16.188 ms/op
                 getUser·p1.00:   16.531 ms/op

Iteration   2: 3.231 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  8.151 ms/op
                 getUser·p0.9999: 16.358 ms/op
                 getUser·p1.00:   16.728 ms/op

Iteration   3: 3.175 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.038 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  5.760 ms/op
                 getUser·p0.9999: 15.646 ms/op
                 getUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299170
  mean =      3.208 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 415 
    [ 1.250,  2.500) = 16721 
    [ 2.500,  3.750) = 235310 
    [ 3.750,  5.000) = 45833 
    [ 5.000,  6.250) = 404 
    [ 6.250,  7.500) = 201 
    [ 7.500,  8.750) = 87 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     16.189 ms/op
     p(99.9990) =     17.597 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 5.813 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.010 ms/op
Iteration   1: 4.072 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  13.795 ms/op
                 listUser·p0.9999: 16.553 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 4.075 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.366 ms/op
                 listUser·p0.9999: 21.116 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 4.002 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.692 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 27.361 ms/op
                 listUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237135
  mean =      4.049 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2353 
    [ 2.500,  5.000) = 209842 
    [ 5.000,  7.500) = 23695 
    [ 7.500, 10.000) = 767 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      6.936 ms/op
     p(99.9000) =     14.989 ms/op
     p(99.9900) =     26.659 ms/op
     p(99.9990) =     28.078 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.203 ± 3.265  ops/ms
ClientGrpc.existUser                       thrpt       3  10.598 ± 1.216  ops/ms
ClientGrpc.getUser                         thrpt       3  10.084 ± 2.238  ops/ms
ClientGrpc.listUser                        thrpt       3   8.010 ± 3.110  ops/ms
ClientGrpc.createUser                       avgt       3   3.189 ± 0.162   ms/op
ClientGrpc.existUser                        avgt       3   3.034 ± 0.329   ms/op
ClientGrpc.getUser                          avgt       3   3.141 ± 0.900   ms/op
ClientGrpc.listUser                         avgt       3   4.021 ± 1.025   ms/op
ClientGrpc.createUser                     sample  299934   3.199 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.671           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.170           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.096           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.407           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.708           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.560           ms/op
ClientGrpc.existUser                      sample  319013   3.008 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.660           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.863           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.873           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.734           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.526           ms/op
ClientGrpc.getUser                        sample  299170   3.208 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.775           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.174           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.100           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.406           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.189           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.727           ms/op
ClientGrpc.listUser                       sample  237135   4.049 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.692           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.936           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.989           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.659           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.180           ms/op
