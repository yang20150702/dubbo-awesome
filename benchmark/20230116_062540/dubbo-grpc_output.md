# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.982 ops/ms
# Warmup Iteration   2: 8.990 ops/ms
# Warmup Iteration   3: 9.919 ops/ms
Iteration   1: 10.060 ops/ms
Iteration   2: 10.067 ops/ms
Iteration   3: 9.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.017 ±(99.9%) 1.478 ops/ms [Average]
  (min, avg, max) = (9.923, 10.017, 10.067), stdev = 0.081
  CI (99.9%): [8.538, 11.495] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.510 ops/ms
# Warmup Iteration   2: 10.398 ops/ms
# Warmup Iteration   3: 10.418 ops/ms
Iteration   1: 10.386 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 10.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.434 ±(99.9%) 1.160 ops/ms [Average]
  (min, avg, max) = (10.386, 10.434, 10.506), stdev = 0.064
  CI (99.9%): [9.275, 11.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.593 ops/ms
# Warmup Iteration   2: 10.014 ops/ms
# Warmup Iteration   3: 9.878 ops/ms
Iteration   1: 10.161 ops/ms
Iteration   2: 9.949 ops/ms
Iteration   3: 10.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.080 ±(99.9%) 2.096 ops/ms [Average]
  (min, avg, max) = (9.949, 10.080, 10.161), stdev = 0.115
  CI (99.9%): [7.984, 12.177] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.447 ops/ms
# Warmup Iteration   2: 7.297 ops/ms
# Warmup Iteration   3: 7.676 ops/ms
Iteration   1: 7.716 ops/ms
Iteration   2: 7.624 ops/ms
Iteration   3: 7.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.678 ±(99.9%) 0.871 ops/ms [Average]
  (min, avg, max) = (7.624, 7.678, 7.716), stdev = 0.048
  CI (99.9%): [6.807, 8.549] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.862 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.003 ms/op
Iteration   1: 3.270 ±(99.9%) 0.002 ms/op
Iteration   2: 3.160 ±(99.9%) 0.003 ms/op
Iteration   3: 3.236 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.222 ±(99.9%) 1.024 ms/op [Average]
  (min, avg, max) = (3.160, 3.222, 3.270), stdev = 0.056
  CI (99.9%): [2.198, 4.246] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.053 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.002 ms/op
Iteration   1: 3.124 ±(99.9%) 0.002 ms/op
Iteration   2: 3.138 ±(99.9%) 0.001 ms/op
Iteration   3: 3.137 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.133 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (3.124, 3.133, 3.138), stdev = 0.008
  CI (99.9%): [2.989, 3.277] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.406 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.003 ms/op
Iteration   1: 3.216 ±(99.9%) 0.002 ms/op
Iteration   2: 3.156 ±(99.9%) 0.002 ms/op
Iteration   3: 3.248 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.207 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (3.156, 3.207, 3.248), stdev = 0.047
  CI (99.9%): [2.350, 4.063] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.721 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.244 ±(99.9%) 0.010 ms/op
Iteration   1: 4.156 ±(99.9%) 0.010 ms/op
Iteration   2: 4.178 ±(99.9%) 0.014 ms/op
Iteration   3: 4.242 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.192 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (4.156, 4.192, 4.242), stdev = 0.044
  CI (99.9%): [3.385, 4.999] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.404 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
Iteration   1: 3.087 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.629 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  7.750 ms/op
                 createUser·p0.9999: 21.713 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.244 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.891 ms/op
                 createUser·p0.9999: 24.941 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 3.274 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  14.907 ms/op
                 createUser·p0.9999: 26.368 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299973
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17477 
    [ 2.500,  5.000) = 281015 
    [ 5.000,  7.500) = 1102 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 83 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.283 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.117 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.109 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.857 ms/op
                 existUser·p0.9999: 13.411 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  8.128 ms/op
                 existUser·p0.9999: 14.491 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.537 ms/op
                 existUser·p0.9999: 18.361 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 308702
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 642 
    [ 1.250,  2.500) = 29117 
    [ 2.500,  3.750) = 243886 
    [ 3.750,  5.000) = 34048 
    [ 5.000,  6.250) = 529 
    [ 6.250,  7.500) = 209 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.236 ms/op
     p(99.9900) =     16.095 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.494 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.007 ms/op
Iteration   1: 3.217 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.028 ms/op
                 getUser·p0.9999: 20.319 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   2: 3.231 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  6.954 ms/op
                 getUser·p0.9999: 15.254 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   3: 3.164 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.675 ms/op
                 getUser·p0.9999: 19.591 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299847
  mean =      3.204 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15617 
    [ 2.500,  5.000) = 282866 
    [ 5.000,  7.500) = 1106 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.177 ms/op
     p(99.9900) =     19.760 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.101 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.690 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.013 ms/op
Iteration   1: 4.197 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 23.036 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   2: 4.141 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.695 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  17.065 ms/op
                 listUser·p0.9999: 24.257 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   3: 4.066 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.858 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   7.020 ms/op
                 listUser·p0.999:  17.052 ms/op
                 listUser·p0.9999: 22.558 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232015
  mean =      4.134 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1368 
    [ 2.500,  5.000) = 203346 
    [ 5.000,  7.500) = 25577 
    [ 7.500, 10.000) = 1206 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     16.515 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     25.735 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.017 ± 1.478  ops/ms
ClientGrpc.existUser                       thrpt       3  10.434 ± 1.160  ops/ms
ClientGrpc.getUser                         thrpt       3  10.080 ± 2.096  ops/ms
ClientGrpc.listUser                        thrpt       3   7.678 ± 0.871  ops/ms
ClientGrpc.createUser                       avgt       3   3.222 ± 1.024   ms/op
ClientGrpc.existUser                        avgt       3   3.133 ± 0.144   ms/op
ClientGrpc.getUser                          avgt       3   3.207 ± 0.857   ms/op
ClientGrpc.listUser                         avgt       3   4.192 ± 0.807   ms/op
ClientGrpc.createUser                     sample  299973   3.200 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.597           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.162           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.035           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.283           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.854           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.165           ms/op
ClientGrpc.existUser                      sample  308702   3.109 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.798           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.084           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.236           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.095           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.743           ms/op
ClientGrpc.getUser                        sample  299847   3.204 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.727           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.170           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.076           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.177           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.760           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.742           ms/op
ClientGrpc.listUser                       sample  232015   4.134 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.695           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.957           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.515           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.822           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.821           ms/op
