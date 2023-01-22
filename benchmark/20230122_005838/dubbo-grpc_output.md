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
# Warmup Iteration   1: 4.057 ops/ms
# Warmup Iteration   2: 9.137 ops/ms
# Warmup Iteration   3: 10.022 ops/ms
Iteration   1: 10.380 ops/ms
Iteration   2: 10.131 ops/ms
Iteration   3: 9.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.168 ±(99.9%) 3.592 ops/ms [Average]
  (min, avg, max) = (9.992, 10.168, 10.380), stdev = 0.197
  CI (99.9%): [6.575, 13.760] (assumes normal distribution)


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
# Warmup Iteration   1: 7.610 ops/ms
# Warmup Iteration   2: 9.871 ops/ms
# Warmup Iteration   3: 10.585 ops/ms
Iteration   1: 10.380 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.462 ±(99.9%) 1.717 ops/ms [Average]
  (min, avg, max) = (10.380, 10.462, 10.565), stdev = 0.094
  CI (99.9%): [8.746, 12.179] (assumes normal distribution)


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
# Warmup Iteration   1: 6.679 ops/ms
# Warmup Iteration   2: 10.037 ops/ms
# Warmup Iteration   3: 10.271 ops/ms
Iteration   1: 10.039 ops/ms
Iteration   2: 9.963 ops/ms
Iteration   3: 9.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.972 ±(99.9%) 1.131 ops/ms [Average]
  (min, avg, max) = (9.916, 9.972, 10.039), stdev = 0.062
  CI (99.9%): [8.841, 11.104] (assumes normal distribution)


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
# Warmup Iteration   1: 5.441 ops/ms
# Warmup Iteration   2: 7.539 ops/ms
# Warmup Iteration   3: 7.841 ops/ms
Iteration   1: 7.732 ops/ms
Iteration   2: 7.979 ops/ms
Iteration   3: 7.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.854 ±(99.9%) 2.254 ops/ms [Average]
  (min, avg, max) = (7.732, 7.854, 7.979), stdev = 0.124
  CI (99.9%): [5.601, 10.108] (assumes normal distribution)


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
# Warmup Iteration   1: 4.351 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.003 ms/op
Iteration   1: 3.252 ±(99.9%) 0.002 ms/op
Iteration   2: 3.171 ±(99.9%) 0.003 ms/op
Iteration   3: 3.226 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.216 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (3.171, 3.216, 3.252), stdev = 0.041
  CI (99.9%): [2.462, 3.970] (assumes normal distribution)


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
# Warmup Iteration   1: 3.533 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.004 ms/op
Iteration   1: 2.977 ±(99.9%) 0.002 ms/op
Iteration   2: 2.964 ±(99.9%) 0.002 ms/op
Iteration   3: 3.078 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.006 ±(99.9%) 1.145 ms/op [Average]
  (min, avg, max) = (2.964, 3.006, 3.078), stdev = 0.063
  CI (99.9%): [1.861, 4.152] (assumes normal distribution)


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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.001 ms/op
Iteration   1: 3.167 ±(99.9%) 0.002 ms/op
Iteration   2: 3.201 ±(99.9%) 0.002 ms/op
Iteration   3: 3.204 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.191 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (3.167, 3.191, 3.204), stdev = 0.020
  CI (99.9%): [2.819, 3.562] (assumes normal distribution)


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
# Warmup Iteration   1: 5.455 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.020 ms/op
Iteration   1: 4.110 ±(99.9%) 0.016 ms/op
Iteration   2: 4.100 ±(99.9%) 0.010 ms/op
Iteration   3: 4.100 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.103 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (4.100, 4.103, 4.110), stdev = 0.006
  CI (99.9%): [3.998, 4.209] (assumes normal distribution)


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.006 ms/op
Iteration   1: 3.199 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  10.208 ms/op
                 createUser·p0.9999: 17.498 ms/op
                 createUser·p1.00:   19.562 ms/op

Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.919 ms/op
                 createUser·p0.9999: 14.052 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  8.249 ms/op
                 createUser·p0.9999: 21.299 ms/op
                 createUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303288
  mean =      3.162 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27179 
    [ 2.500,  5.000) = 274665 
    [ 5.000,  7.500) = 978 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.474 ms/op
     p(99.9000) =      9.460 ms/op
     p(99.9900) =     19.738 ms/op
     p(99.9990) =     21.855 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
Iteration   1: 3.056 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.394 ms/op
                 existUser·p0.9999: 21.695 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   2: 3.010 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.021 ms/op
                 existUser·p0.9999: 16.194 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  5.903 ms/op
                 existUser·p0.9999: 19.085 ms/op
                 existUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316754
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42638 
    [ 2.500,  5.000) = 273223 
    [ 5.000,  7.500) = 668 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.849 ms/op
     p(99.9900) =     20.786 ms/op
     p(99.9990) =     22.238 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.006 ms/op
Iteration   1: 3.190 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.817 ms/op
                 getUser·p0.9999: 12.680 ms/op
                 getUser·p1.00:   12.927 ms/op

Iteration   2: 3.188 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.437 ms/op
                 getUser·p0.999:  8.090 ms/op
                 getUser·p0.9999: 15.169 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   3: 3.144 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.869 ms/op
                 getUser·p0.9999: 17.165 ms/op
                 getUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302429
  mean =      3.174 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 741 
    [ 1.250,  2.500) = 19420 
    [ 2.500,  3.750) = 240948 
    [ 3.750,  5.000) = 40221 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 292 
    [ 7.500,  8.750) = 104 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.689 ms/op
     p(99.9900) =     16.478 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 5.586 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.208 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.011 ms/op
Iteration   1: 4.075 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  13.310 ms/op
                 listUser·p0.9999: 15.012 ms/op
                 listUser·p1.00:   16.040 ms/op

Iteration   2: 4.092 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.100 ms/op
                 listUser·p0.999:  15.841 ms/op
                 listUser·p0.9999: 17.752 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 4.064 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 28.132 ms/op
                 listUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235400
  mean =      4.077 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2585 
    [ 2.500,  5.000) = 205986 
    [ 5.000,  7.500) = 25527 
    [ 7.500, 10.000) = 878 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     14.071 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     28.722 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.168 ± 3.592  ops/ms
ClientGrpc.existUser                       thrpt       3  10.462 ± 1.717  ops/ms
ClientGrpc.getUser                         thrpt       3   9.972 ± 1.131  ops/ms
ClientGrpc.listUser                        thrpt       3   7.854 ± 2.254  ops/ms
ClientGrpc.createUser                       avgt       3   3.216 ± 0.754   ms/op
ClientGrpc.existUser                        avgt       3   3.006 ± 1.145   ms/op
ClientGrpc.getUser                          avgt       3   3.191 ± 0.371   ms/op
ClientGrpc.listUser                         avgt       3   4.103 ± 0.105   ms/op
ClientGrpc.createUser                     sample  303288   3.162 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.709           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.055           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.474           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.460           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.738           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.955           ms/op
ClientGrpc.existUser                      sample  316754   3.030 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.635           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.019           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.849           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.786           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.381           ms/op
ClientGrpc.getUser                        sample  302429   3.174 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.778           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.150           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.051           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.689           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.478           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.465           ms/op
ClientGrpc.listUser                       sample  235400   4.077 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.118           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.912           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.071           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.771           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.803           ms/op
