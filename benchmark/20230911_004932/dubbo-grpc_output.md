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
# Warmup Iteration   1: 3.702 ops/ms
# Warmup Iteration   2: 8.285 ops/ms
# Warmup Iteration   3: 9.575 ops/ms
Iteration   1: 10.023 ops/ms
Iteration   2: 10.087 ops/ms
Iteration   3: 10.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.068 ±(99.9%) 0.714 ops/ms [Average]
  (min, avg, max) = (10.023, 10.068, 10.094), stdev = 0.039
  CI (99.9%): [9.354, 10.782] (assumes normal distribution)


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
# Warmup Iteration   1: 7.349 ops/ms
# Warmup Iteration   2: 10.087 ops/ms
# Warmup Iteration   3: 10.604 ops/ms
Iteration   1: 10.469 ops/ms
Iteration   2: 10.452 ops/ms
Iteration   3: 10.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.573 ±(99.9%) 3.564 ops/ms [Average]
  (min, avg, max) = (10.452, 10.573, 10.799), stdev = 0.195
  CI (99.9%): [7.009, 14.138] (assumes normal distribution)


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
# Warmup Iteration   1: 6.337 ops/ms
# Warmup Iteration   2: 9.746 ops/ms
# Warmup Iteration   3: 10.142 ops/ms
Iteration   1: 10.182 ops/ms
Iteration   2: 10.258 ops/ms
Iteration   3: 10.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.203 ±(99.9%) 0.876 ops/ms [Average]
  (min, avg, max) = (10.169, 10.203, 10.258), stdev = 0.048
  CI (99.9%): [9.327, 11.079] (assumes normal distribution)


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
# Warmup Iteration   1: 5.671 ops/ms
# Warmup Iteration   2: 6.962 ops/ms
# Warmup Iteration   3: 7.332 ops/ms
Iteration   1: 7.550 ops/ms
Iteration   2: 7.437 ops/ms
Iteration   3: 7.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.508 ±(99.9%) 1.120 ops/ms [Average]
  (min, avg, max) = (7.437, 7.508, 7.550), stdev = 0.061
  CI (99.9%): [6.388, 8.627] (assumes normal distribution)


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
# Warmup Iteration   1: 4.671 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.394 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.002 ms/op
Iteration   1: 3.130 ±(99.9%) 0.003 ms/op
Iteration   2: 3.151 ±(99.9%) 0.002 ms/op
Iteration   3: 3.139 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.140 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (3.130, 3.140, 3.151), stdev = 0.010
  CI (99.9%): [2.951, 3.329] (assumes normal distribution)


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
# Warmup Iteration   1: 4.296 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.003 ms/op
Iteration   1: 2.989 ±(99.9%) 0.003 ms/op
Iteration   2: 2.996 ±(99.9%) 0.003 ms/op
Iteration   3: 3.054 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.013 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (2.989, 3.013, 3.054), stdev = 0.036
  CI (99.9%): [2.359, 3.667] (assumes normal distribution)


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
# Warmup Iteration   1: 4.597 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.002 ms/op
Iteration   1: 3.190 ±(99.9%) 0.003 ms/op
Iteration   2: 3.143 ±(99.9%) 0.002 ms/op
Iteration   3: 3.136 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.156 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (3.136, 3.156, 3.190), stdev = 0.030
  CI (99.9%): [2.615, 3.698] (assumes normal distribution)


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
# Warmup Iteration   1: 5.446 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.282 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.009 ms/op
Iteration   1: 4.222 ±(99.9%) 0.009 ms/op
Iteration   2: 4.264 ±(99.9%) 0.011 ms/op
Iteration   3: 4.199 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.228 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (4.199, 4.228, 4.264), stdev = 0.033
  CI (99.9%): [3.630, 4.827] (assumes normal distribution)


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.007 ms/op
Iteration   1: 3.174 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  9.144 ms/op
                 createUser·p0.9999: 12.875 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   2: 3.195 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.733 ms/op
                 createUser·p0.999:  9.566 ms/op
                 createUser·p0.9999: 14.172 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   3: 3.170 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  7.969 ms/op
                 createUser·p0.9999: 18.740 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302055
  mean =      3.180 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 351 
    [ 1.250,  2.500) = 11863 
    [ 2.500,  3.750) = 263561 
    [ 3.750,  5.000) = 24057 
    [ 5.000,  6.250) = 1067 
    [ 6.250,  7.500) = 674 
    [ 7.500,  8.750) = 123 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     18.873 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.088 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  9.692 ms/op
                 existUser·p0.9999: 20.010 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.275 ms/op
                 existUser·p0.999:  8.293 ms/op
                 existUser·p0.9999: 14.134 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  8.651 ms/op
                 existUser·p0.9999: 20.298 ms/op
                 existUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315986
  mean =      3.038 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17597 
    [ 2.500,  5.000) = 296572 
    [ 5.000,  7.500) = 1155 
    [ 7.500, 10.000) = 485 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     20.100 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.008 ms/op
Iteration   1: 3.169 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.366 ms/op
                 getUser·p0.9999: 27.713 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.474 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.576 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   3: 3.126 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.887 ms/op
                 getUser·p0.9999: 20.604 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303798
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12016 
    [ 2.500,  5.000) = 290022 
    [ 5.000,  7.500) = 1367 
    [ 7.500, 10.000) = 231 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.881 ms/op
     p(99.9900) =     26.837 ms/op
     p(99.9990) =     28.081 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 5.575 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.011 ms/op
Iteration   1: 4.317 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   4.116 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 15.394 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   2: 4.239 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  15.495 ms/op
                 listUser·p0.9999: 20.884 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 4.229 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  16.756 ms/op
                 listUser·p0.9999: 27.007 ms/op
                 listUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 225402
  mean =      4.262 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1114 
    [ 2.500,  5.000) = 194819 
    [ 5.000,  7.500) = 27151 
    [ 7.500, 10.000) = 1901 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      6.144 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     25.509 ms/op
     p(99.9990) =     27.598 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.068 ± 0.714  ops/ms
ClientGrpc.existUser                       thrpt       3  10.573 ± 3.564  ops/ms
ClientGrpc.getUser                         thrpt       3  10.203 ± 0.876  ops/ms
ClientGrpc.listUser                        thrpt       3   7.508 ± 1.120  ops/ms
ClientGrpc.createUser                       avgt       3   3.140 ± 0.189   ms/op
ClientGrpc.existUser                        avgt       3   3.013 ± 0.654   ms/op
ClientGrpc.getUser                          avgt       3   3.156 ± 0.541   ms/op
ClientGrpc.listUser                         avgt       3   4.228 ± 0.598   ms/op
ClientGrpc.createUser                     sample  302055   3.180 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.833           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.944           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.388           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.367           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.038           ms/op
ClientGrpc.existUser                      sample  315986   3.038 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.006           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.454           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.100           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.611           ms/op
ClientGrpc.getUser                        sample  303798   3.158 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.474           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.881           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.837           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.246           ms/op
ClientGrpc.listUser                       sample  225402   4.262 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.094           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.080           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.144           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.528           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.155           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.509           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.722           ms/op
