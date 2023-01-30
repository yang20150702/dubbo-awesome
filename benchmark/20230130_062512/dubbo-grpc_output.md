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
# Warmup Iteration   1: 4.318 ops/ms
# Warmup Iteration   2: 8.986 ops/ms
# Warmup Iteration   3: 9.870 ops/ms
Iteration   1: 10.393 ops/ms
Iteration   2: 10.007 ops/ms
Iteration   3: 10.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.265 ±(99.9%) 4.072 ops/ms [Average]
  (min, avg, max) = (10.007, 10.265, 10.395), stdev = 0.223
  CI (99.9%): [6.193, 14.337] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.281 ops/ms
# Warmup Iteration   2: 10.347 ops/ms
# Warmup Iteration   3: 10.445 ops/ms
Iteration   1: 10.665 ops/ms
Iteration   2: 10.504 ops/ms
Iteration   3: 10.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.582 ±(99.9%) 1.468 ops/ms [Average]
  (min, avg, max) = (10.504, 10.582, 10.665), stdev = 0.080
  CI (99.9%): [9.114, 12.050] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.687 ops/ms
# Warmup Iteration   2: 9.728 ops/ms
# Warmup Iteration   3: 9.904 ops/ms
Iteration   1: 10.185 ops/ms
Iteration   2: 10.110 ops/ms
Iteration   3: 10.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.174 ±(99.9%) 1.070 ops/ms [Average]
  (min, avg, max) = (10.110, 10.174, 10.226), stdev = 0.059
  CI (99.9%): [9.104, 11.244] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.133 ops/ms
# Warmup Iteration   2: 7.469 ops/ms
# Warmup Iteration   3: 7.403 ops/ms
Iteration   1: 7.608 ops/ms
Iteration   2: 7.630 ops/ms
Iteration   3: 7.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.684 ±(99.9%) 2.063 ops/ms [Average]
  (min, avg, max) = (7.608, 7.684, 7.814), stdev = 0.113
  CI (99.9%): [5.620, 9.747] (assumes normal distribution)


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
# Warmup Iteration   1: 4.493 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.003 ms/op
Iteration   1: 3.170 ±(99.9%) 0.002 ms/op
Iteration   2: 3.249 ±(99.9%) 0.002 ms/op
Iteration   3: 3.252 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.223 ±(99.9%) 0.849 ms/op [Average]
  (min, avg, max) = (3.170, 3.223, 3.252), stdev = 0.047
  CI (99.9%): [2.375, 4.072] (assumes normal distribution)


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.001 ms/op
Iteration   1: 3.059 ±(99.9%) 0.002 ms/op
Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.052 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (3.025, 3.052, 3.072), stdev = 0.025
  CI (99.9%): [2.605, 3.499] (assumes normal distribution)


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
# Warmup Iteration   1: 4.315 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.005 ms/op
Iteration   1: 3.241 ±(99.9%) 0.003 ms/op
Iteration   2: 3.260 ±(99.9%) 0.001 ms/op
Iteration   3: 3.306 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.269 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (3.241, 3.269, 3.306), stdev = 0.034
  CI (99.9%): [2.657, 3.881] (assumes normal distribution)


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
# Warmup Iteration   1: 5.460 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.475 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.019 ms/op
Iteration   1: 4.092 ±(99.9%) 0.006 ms/op
Iteration   2: 4.146 ±(99.9%) 0.009 ms/op
Iteration   3: 4.116 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.118 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (4.092, 4.118, 4.146), stdev = 0.027
  CI (99.9%): [3.624, 4.613] (assumes normal distribution)


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.006 ms/op
Iteration   1: 3.235 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.776 ms/op
                 createUser·p0.9999: 12.474 ms/op
                 createUser·p1.00:   12.796 ms/op

Iteration   2: 3.236 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.250 ms/op
                 createUser·p0.9999: 14.522 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   3: 3.304 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  15.517 ms/op
                 createUser·p0.9999: 17.007 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294603
  mean =      3.258 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 269 
    [ 1.250,  2.500) = 15018 
    [ 2.500,  3.750) = 227469 
    [ 3.750,  5.000) = 50503 
    [ 5.000,  6.250) = 572 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 244 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 79 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.318 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 4.182 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.064 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.459 ms/op
                 existUser·p0.9999: 12.856 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.040 ms/op
                 existUser·p0.9999: 23.648 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  8.145 ms/op
                 existUser·p0.9999: 24.037 ms/op
                 existUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312076
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38945 
    [ 2.500,  5.000) = 272296 
    [ 5.000,  7.500) = 618 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.758 ms/op
     p(99.9900) =     23.488 ms/op
     p(99.9990) =     24.564 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 4.378 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.006 ms/op
Iteration   1: 3.195 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  6.577 ms/op
                 getUser·p0.9999: 13.090 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.607 ms/op
                 getUser·p0.999:  7.881 ms/op
                 getUser·p0.9999: 14.220 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   3: 3.199 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.087 ms/op
                 getUser·p0.9999: 17.531 ms/op
                 getUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301033
  mean =      3.188 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 508 
    [ 1.250,  2.500) = 19421 
    [ 2.500,  3.750) = 237384 
    [ 3.750,  5.000) = 42649 
    [ 5.000,  6.250) = 658 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      6.947 ms/op
     p(99.9900) =     15.560 ms/op
     p(99.9990) =     18.054 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 5.451 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.376 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.012 ms/op
Iteration   1: 4.074 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  13.907 ms/op
                 listUser·p0.9999: 16.698 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   2: 4.104 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  15.124 ms/op
                 listUser·p0.9999: 20.749 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   3: 4.099 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  16.564 ms/op
                 listUser·p0.9999: 26.188 ms/op
                 listUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234578
  mean =      4.092 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1587 
    [ 2.500,  5.000) = 206360 
    [ 5.000,  7.500) = 24935 
    [ 7.500, 10.000) = 1195 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     15.129 ms/op
     p(99.9900) =     25.216 ms/op
     p(99.9990) =     26.400 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.265 ± 4.072  ops/ms
ClientGrpc.existUser                       thrpt       3  10.582 ± 1.468  ops/ms
ClientGrpc.getUser                         thrpt       3  10.174 ± 1.070  ops/ms
ClientGrpc.listUser                        thrpt       3   7.684 ± 2.063  ops/ms
ClientGrpc.createUser                       avgt       3   3.223 ± 0.849   ms/op
ClientGrpc.existUser                        avgt       3   3.052 ± 0.447   ms/op
ClientGrpc.getUser                          avgt       3   3.269 ± 0.612   ms/op
ClientGrpc.listUser                         avgt       3   4.118 ± 0.494   ms/op
ClientGrpc.createUser                     sample  294603   3.258 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.776           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.219           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.137           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.318           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.843           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.236           ms/op
ClientGrpc.existUser                      sample  312076   3.077 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.769           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.056           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.949           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.758           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.488           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.805           ms/op
ClientGrpc.getUser                        sample  301033   3.188 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.691           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.047           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.947           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.560           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.186           ms/op
ClientGrpc.listUser                       sample  234578   4.092 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.881           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.920           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.129           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.216           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.509           ms/op
