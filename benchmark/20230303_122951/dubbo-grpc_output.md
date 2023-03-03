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
# Warmup Iteration   1: 3.993 ops/ms
# Warmup Iteration   2: 8.729 ops/ms
# Warmup Iteration   3: 9.664 ops/ms
Iteration   1: 10.158 ops/ms
Iteration   2: 9.764 ops/ms
Iteration   3: 9.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.946 ±(99.9%) 3.627 ops/ms [Average]
  (min, avg, max) = (9.764, 9.946, 10.158), stdev = 0.199
  CI (99.9%): [6.319, 13.573] (assumes normal distribution)


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
# Warmup Iteration   1: 7.560 ops/ms
# Warmup Iteration   2: 10.093 ops/ms
# Warmup Iteration   3: 10.343 ops/ms
Iteration   1: 10.762 ops/ms
Iteration   2: 10.760 ops/ms
Iteration   3: 10.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.724 ±(99.9%) 1.176 ops/ms [Average]
  (min, avg, max) = (10.649, 10.724, 10.762), stdev = 0.064
  CI (99.9%): [9.548, 11.900] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.679 ops/ms
# Warmup Iteration   2: 9.958 ops/ms
# Warmup Iteration   3: 9.982 ops/ms
Iteration   1: 10.306 ops/ms
Iteration   2: 10.164 ops/ms
Iteration   3: 10.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.267 ±(99.9%) 1.631 ops/ms [Average]
  (min, avg, max) = (10.164, 10.267, 10.329), stdev = 0.089
  CI (99.9%): [8.635, 11.898] (assumes normal distribution)


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
# Warmup Iteration   1: 5.397 ops/ms
# Warmup Iteration   2: 7.590 ops/ms
# Warmup Iteration   3: 7.787 ops/ms
Iteration   1: 7.956 ops/ms
Iteration   2: 7.858 ops/ms
Iteration   3: 7.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.923 ±(99.9%) 1.027 ops/ms [Average]
  (min, avg, max) = (7.858, 7.923, 7.956), stdev = 0.056
  CI (99.9%): [6.896, 8.950] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.313 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.001 ms/op
Iteration   1: 3.233 ±(99.9%) 0.003 ms/op
Iteration   2: 3.235 ±(99.9%) 0.002 ms/op
Iteration   3: 3.169 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.212 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (3.169, 3.212, 3.235), stdev = 0.038
  CI (99.9%): [2.525, 3.899] (assumes normal distribution)


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
# Warmup Iteration   1: 4.417 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.002 ms/op
Iteration   1: 3.051 ±(99.9%) 0.002 ms/op
Iteration   2: 3.039 ±(99.9%) 0.002 ms/op
Iteration   3: 3.147 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.079 ±(99.9%) 1.076 ms/op [Average]
  (min, avg, max) = (3.039, 3.079, 3.147), stdev = 0.059
  CI (99.9%): [2.003, 4.154] (assumes normal distribution)


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.003 ms/op
Iteration   1: 3.208 ±(99.9%) 0.003 ms/op
Iteration   2: 3.201 ±(99.9%) 0.002 ms/op
Iteration   3: 3.230 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.213 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.201, 3.213, 3.230), stdev = 0.015
  CI (99.9%): [2.944, 3.482] (assumes normal distribution)


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
# Warmup Iteration   1: 6.173 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.033 ms/op
Iteration   1: 4.003 ±(99.9%) 0.010 ms/op
Iteration   2: 4.061 ±(99.9%) 0.013 ms/op
Iteration   3: 4.018 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.028 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (4.003, 4.028, 4.061), stdev = 0.030
  CI (99.9%): [3.482, 4.573] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.823 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.007 ms/op
Iteration   1: 3.174 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.582 ms/op
                 createUser·p0.9999: 17.629 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.145 ms/op
                 createUser·p0.9999: 14.986 ms/op
                 createUser·p1.00:   15.270 ms/op

Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.878 ms/op
                 createUser·p0.9999: 19.133 ms/op
                 createUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305409
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 269 
    [ 1.250,  2.500) = 21290 
    [ 2.500,  3.750) = 251764 
    [ 3.750,  5.000) = 31272 
    [ 5.000,  6.250) = 246 
    [ 6.250,  7.500) = 203 
    [ 7.500,  8.750) = 96 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.497 ms/op
     p(99.9900) =     18.246 ms/op
     p(99.9990) =     19.395 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 4.119 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.006 ms/op
Iteration   1: 3.077 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.012 ms/op
                 existUser·p0.9999: 11.204 ms/op
                 existUser·p1.00:   11.551 ms/op

Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 15.082 ms/op
                 existUser·p1.00:   15.942 ms/op

Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.692 ms/op
                 existUser·p0.9999: 16.465 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311318
  mean =      3.082 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1264 
    [ 1.250,  2.500) = 37176 
    [ 2.500,  3.750) = 236226 
    [ 3.750,  5.000) = 35801 
    [ 5.000,  6.250) = 371 
    [ 6.250,  7.500) = 217 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.133 ms/op
     p(99.9900) =     15.251 ms/op
     p(99.9990) =     17.855 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.641 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  8.442 ms/op
                 getUser·p0.9999: 12.903 ms/op
                 getUser·p1.00:   13.206 ms/op

Iteration   2: 3.219 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  9.159 ms/op
                 getUser·p0.9999: 16.878 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 3.266 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  8.487 ms/op
                 getUser·p0.9999: 21.215 ms/op
                 getUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299639
  mean =      3.203 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17532 
    [ 2.500,  5.000) = 280759 
    [ 5.000,  7.500) = 834 
    [ 7.500, 10.000) = 322 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.722 ms/op
     p(99.9900) =     20.220 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 5.443 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.471 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.012 ms/op
Iteration   1: 4.170 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.673 ms/op
                 listUser·p0.9999: 19.551 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   2: 4.219 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.356 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  18.520 ms/op
                 listUser·p0.9999: 26.189 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   3: 4.146 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  15.546 ms/op
                 listUser·p0.9999: 28.461 ms/op
                 listUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229758
  mean =      4.178 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1742 
    [ 2.500,  5.000) = 195826 
    [ 5.000,  7.500) = 30225 
    [ 7.500, 10.000) = 1513 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.356 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     16.691 ms/op
     p(99.9900) =     27.657 ms/op
     p(99.9990) =     28.672 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.946 ± 3.627  ops/ms
ClientGrpc.existUser                       thrpt       3  10.724 ± 1.176  ops/ms
ClientGrpc.getUser                         thrpt       3  10.267 ± 1.631  ops/ms
ClientGrpc.listUser                        thrpt       3   7.923 ± 1.027  ops/ms
ClientGrpc.createUser                       avgt       3   3.212 ± 0.687   ms/op
ClientGrpc.existUser                        avgt       3   3.079 ± 1.076   ms/op
ClientGrpc.getUser                          avgt       3   3.213 ± 0.269   ms/op
ClientGrpc.listUser                         avgt       3   4.028 ± 0.546   ms/op
ClientGrpc.createUser                     sample  305409   3.143 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.802           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.497           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.246           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.530           ms/op
ClientGrpc.existUser                      sample  311318   3.082 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.591           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.080           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.973           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.133           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.251           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.957           ms/op
ClientGrpc.getUser                        sample  299639   3.203 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.787           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.170           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.076           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.722           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.220           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.660           ms/op
ClientGrpc.listUser                       sample  229758   4.178 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.356           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.981           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.382           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.348           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.691           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.657           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.705           ms/op
