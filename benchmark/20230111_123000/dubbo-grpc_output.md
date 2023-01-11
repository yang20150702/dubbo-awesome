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
# Warmup Iteration   1: 3.969 ops/ms
# Warmup Iteration   2: 8.578 ops/ms
# Warmup Iteration   3: 10.320 ops/ms
Iteration   1: 10.327 ops/ms
Iteration   2: 10.145 ops/ms
Iteration   3: 9.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.100 ±(99.9%) 4.591 ops/ms [Average]
  (min, avg, max) = (9.829, 10.100, 10.327), stdev = 0.252
  CI (99.9%): [5.509, 14.692] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.059 ops/ms
# Warmup Iteration   2: 9.998 ops/ms
# Warmup Iteration   3: 10.604 ops/ms
Iteration   1: 10.370 ops/ms
Iteration   2: 10.385 ops/ms
Iteration   3: 10.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.357 ±(99.9%) 0.660 ops/ms [Average]
  (min, avg, max) = (10.316, 10.357, 10.385), stdev = 0.036
  CI (99.9%): [9.698, 11.017] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.629 ops/ms
# Warmup Iteration   2: 9.960 ops/ms
# Warmup Iteration   3: 10.099 ops/ms
Iteration   1: 10.107 ops/ms
Iteration   2: 9.695 ops/ms
Iteration   3: 10.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.969 ±(99.9%) 4.337 ops/ms [Average]
  (min, avg, max) = (9.695, 9.969, 10.107), stdev = 0.238
  CI (99.9%): [5.632, 14.306] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.452 ops/ms
# Warmup Iteration   2: 7.368 ops/ms
# Warmup Iteration   3: 7.573 ops/ms
Iteration   1: 7.666 ops/ms
Iteration   2: 7.605 ops/ms
Iteration   3: 7.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.602 ±(99.9%) 1.199 ops/ms [Average]
  (min, avg, max) = (7.535, 7.602, 7.666), stdev = 0.066
  CI (99.9%): [6.403, 8.802] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.554 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.002 ms/op
Iteration   1: 3.180 ±(99.9%) 0.002 ms/op
Iteration   2: 3.180 ±(99.9%) 0.002 ms/op
Iteration   3: 3.200 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.187 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (3.180, 3.187, 3.200), stdev = 0.011
  CI (99.9%): [2.979, 3.395] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.119 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.003 ms/op
Iteration   1: 3.056 ±(99.9%) 0.002 ms/op
Iteration   2: 3.008 ±(99.9%) 0.002 ms/op
Iteration   3: 3.040 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.035 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (3.008, 3.035, 3.056), stdev = 0.025
  CI (99.9%): [2.583, 3.486] (assumes normal distribution)


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.004 ms/op
Iteration   1: 3.199 ±(99.9%) 0.002 ms/op
Iteration   2: 3.188 ±(99.9%) 0.004 ms/op
Iteration   3: 3.177 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.188 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (3.177, 3.188, 3.199), stdev = 0.011
  CI (99.9%): [2.988, 3.388] (assumes normal distribution)


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
# Warmup Iteration   1: 5.797 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.279 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.037 ms/op
Iteration   1: 4.099 ±(99.9%) 0.021 ms/op
Iteration   2: 4.129 ±(99.9%) 0.024 ms/op
Iteration   3: 4.054 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.094 ±(99.9%) 0.690 ms/op [Average]
  (min, avg, max) = (4.054, 4.094, 4.129), stdev = 0.038
  CI (99.9%): [3.404, 4.784] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.506 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.007 ms/op
Iteration   1: 3.184 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.399 ms/op
                 createUser·p0.9999: 14.647 ms/op
                 createUser·p1.00:   15.008 ms/op

Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  9.428 ms/op
                 createUser·p0.9999: 14.723 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  10.568 ms/op
                 createUser·p0.9999: 18.373 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305297
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 641 
    [ 1.250,  2.500) = 24118 
    [ 2.500,  3.750) = 247399 
    [ 3.750,  5.000) = 31575 
    [ 5.000,  6.250) = 752 
    [ 6.250,  7.500) = 265 
    [ 7.500,  8.750) = 146 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 93 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =     10.022 ms/op
     p(99.9900) =     16.354 ms/op
     p(99.9990) =     18.543 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.085 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.049 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.381 ms/op
                 existUser·p0.9999: 17.826 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 3.100 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.023 ms/op
                 existUser·p0.9999: 15.046 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  5.388 ms/op
                 existUser·p0.9999: 18.510 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313924
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 881 
    [ 1.250,  2.500) = 37467 
    [ 2.500,  3.750) = 246253 
    [ 3.750,  5.000) = 28697 
    [ 5.000,  6.250) = 306 
    [ 6.250,  7.500) = 139 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.291 ms/op
     p(99.9900) =     17.682 ms/op
     p(99.9990) =     19.109 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 4.442 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.007 ms/op
Iteration   1: 3.145 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.575 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  9.019 ms/op
                 getUser·p0.9999: 17.433 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   2: 3.176 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.378 ms/op
                 getUser·p0.9999: 25.030 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.133 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.423 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.559 ms/op
                 getUser·p0.9999: 21.554 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304490
  mean =      3.151 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26692 
    [ 2.500,  5.000) = 276660 
    [ 5.000,  7.500) = 838 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.471 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     25.392 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 4.916 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.231 ±(99.9%) 0.013 ms/op
Iteration   1: 4.067 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.266 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   2: 4.147 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  18.678 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   3: 4.068 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  20.788 ms/op
                 listUser·p0.9999: 30.685 ms/op
                 listUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234315
  mean =      4.094 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2109 
    [ 2.500,  5.000) = 204081 
    [ 5.000,  7.500) = 26401 
    [ 7.500, 10.000) = 1166 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     29.791 ms/op
     p(99.9990) =     31.042 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.100 ± 4.591  ops/ms
ClientGrpc.existUser                       thrpt       3  10.357 ± 0.660  ops/ms
ClientGrpc.getUser                         thrpt       3   9.969 ± 4.337  ops/ms
ClientGrpc.listUser                        thrpt       3   7.602 ± 1.199  ops/ms
ClientGrpc.createUser                       avgt       3   3.187 ± 0.208   ms/op
ClientGrpc.existUser                        avgt       3   3.035 ± 0.451   ms/op
ClientGrpc.getUser                          avgt       3   3.188 ± 0.200   ms/op
ClientGrpc.listUser                         avgt       3   4.094 ± 0.690   ms/op
ClientGrpc.createUser                     sample  305297   3.143 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.605           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.022           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.354           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.743           ms/op
ClientGrpc.existUser                      sample  313924   3.059 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.778           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.912           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.291           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.682           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.235           ms/op
ClientGrpc.getUser                        sample  304490   3.151 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.423           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.051           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.471           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.740           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.592           ms/op
ClientGrpc.listUser                       sample  234315   4.094 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.810           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.791           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.195           ms/op
