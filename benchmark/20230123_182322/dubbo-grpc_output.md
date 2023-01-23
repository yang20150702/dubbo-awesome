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
# Warmup Iteration   1: 4.044 ops/ms
# Warmup Iteration   2: 8.649 ops/ms
# Warmup Iteration   3: 9.498 ops/ms
Iteration   1: 9.673 ops/ms
Iteration   2: 9.667 ops/ms
Iteration   3: 9.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.642 ±(99.9%) 0.898 ops/ms [Average]
  (min, avg, max) = (9.585, 9.642, 9.673), stdev = 0.049
  CI (99.9%): [8.744, 10.539] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.999 ops/ms
# Warmup Iteration   2: 9.959 ops/ms
# Warmup Iteration   3: 10.074 ops/ms
Iteration   1: 10.126 ops/ms
Iteration   2: 10.368 ops/ms
Iteration   3: 10.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.225 ±(99.9%) 2.310 ops/ms [Average]
  (min, avg, max) = (10.126, 10.225, 10.368), stdev = 0.127
  CI (99.9%): [7.915, 12.535] (assumes normal distribution)


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
# Warmup Iteration   1: 6.393 ops/ms
# Warmup Iteration   2: 9.421 ops/ms
# Warmup Iteration   3: 9.909 ops/ms
Iteration   1: 9.806 ops/ms
Iteration   2: 9.857 ops/ms
Iteration   3: 9.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.805 ±(99.9%) 0.949 ops/ms [Average]
  (min, avg, max) = (9.753, 9.805, 9.857), stdev = 0.052
  CI (99.9%): [8.856, 10.754] (assumes normal distribution)


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
# Warmup Iteration   1: 5.346 ops/ms
# Warmup Iteration   2: 7.238 ops/ms
# Warmup Iteration   3: 7.715 ops/ms
Iteration   1: 7.684 ops/ms
Iteration   2: 7.806 ops/ms
Iteration   3: 7.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.668 ±(99.9%) 2.692 ops/ms [Average]
  (min, avg, max) = (7.512, 7.668, 7.806), stdev = 0.148
  CI (99.9%): [4.976, 10.360] (assumes normal distribution)


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
# Warmup Iteration   1: 4.393 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.002 ms/op
Iteration   1: 3.284 ±(99.9%) 0.010 ms/op
Iteration   2: 3.310 ±(99.9%) 0.001 ms/op
Iteration   3: 3.195 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.263 ±(99.9%) 1.101 ms/op [Average]
  (min, avg, max) = (3.195, 3.263, 3.310), stdev = 0.060
  CI (99.9%): [2.162, 4.365] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.128 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.003 ms/op
Iteration   1: 3.089 ±(99.9%) 0.003 ms/op
Iteration   2: 3.175 ±(99.9%) 0.003 ms/op
Iteration   3: 3.139 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.134 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (3.089, 3.134, 3.175), stdev = 0.043
  CI (99.9%): [2.352, 3.917] (assumes normal distribution)


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
# Warmup Iteration   1: 4.322 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.002 ms/op
Iteration   1: 3.229 ±(99.9%) 0.002 ms/op
Iteration   2: 3.380 ±(99.9%) 0.002 ms/op
Iteration   3: 3.296 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.301 ±(99.9%) 1.382 ms/op [Average]
  (min, avg, max) = (3.229, 3.301, 3.380), stdev = 0.076
  CI (99.9%): [1.919, 4.684] (assumes normal distribution)


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
# Warmup Iteration   1: 5.259 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.307 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.018 ms/op
Iteration   1: 4.157 ±(99.9%) 0.009 ms/op
Iteration   2: 4.118 ±(99.9%) 0.015 ms/op
Iteration   3: 4.093 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.123 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (4.093, 4.123, 4.157), stdev = 0.032
  CI (99.9%): [3.532, 4.714] (assumes normal distribution)


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
# Warmup Iteration   1: 4.567 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.007 ms/op
Iteration   1: 3.297 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   4.781 ms/op
                 createUser·p0.999:  8.172 ms/op
                 createUser·p0.9999: 20.031 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   2: 3.319 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   4.756 ms/op
                 createUser·p0.999:  7.919 ms/op
                 createUser·p0.9999: 19.464 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   3: 3.286 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.627 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  9.497 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 290935
  mean =      3.301 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16687 
    [ 2.500,  5.000) = 272141 
    [ 5.000,  7.500) = 1648 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     24.090 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.149 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.008 ms/op
Iteration   1: 3.121 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.678 ms/op
                 existUser·p0.9999: 17.695 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   2: 3.223 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.182 ms/op
                 existUser·p0.9999: 18.617 ms/op
                 existUser·p1.00:   18.874 ms/op

Iteration   3: 3.186 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  11.987 ms/op
                 existUser·p0.9999: 21.689 ms/op
                 existUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 302085
  mean =      3.176 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21927 
    [ 2.500,  5.000) = 278592 
    [ 5.000,  7.500) = 1093 
    [ 7.500, 10.000) = 200 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.134 ms/op
     p(99.9900) =     21.063 ms/op
     p(99.9990) =     22.116 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 4.750 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.007 ms/op
Iteration   1: 3.224 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  9.074 ms/op
                 getUser·p0.9999: 15.864 ms/op
                 getUser·p1.00:   16.335 ms/op

Iteration   2: 3.184 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  9.093 ms/op
                 getUser·p0.9999: 14.893 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   3: 3.270 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.892 ms/op
                 getUser·p0.9999: 18.922 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297397
  mean =      3.226 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 288 
    [ 1.250,  2.500) = 11014 
    [ 2.500,  3.750) = 246239 
    [ 3.750,  5.000) = 38325 
    [ 5.000,  6.250) = 690 
    [ 6.250,  7.500) = 388 
    [ 7.500,  8.750) = 142 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     16.819 ms/op
     p(99.9990) =     19.334 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 5.663 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.250 ±(99.9%) 0.012 ms/op
Iteration   1: 4.224 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.768 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  13.519 ms/op
                 listUser·p0.9999: 15.087 ms/op
                 listUser·p1.00:   15.532 ms/op

Iteration   2: 4.161 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  15.652 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   3: 4.162 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  14.847 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229554
  mean =      4.182 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1907 
    [ 2.500,  5.000) = 192401 
    [ 5.000,  7.500) = 33668 
    [ 7.500, 10.000) = 1158 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     19.466 ms/op
     p(99.9990) =     21.403 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.642 ± 0.898  ops/ms
ClientGrpc.existUser                       thrpt       3  10.225 ± 2.310  ops/ms
ClientGrpc.getUser                         thrpt       3   9.805 ± 0.949  ops/ms
ClientGrpc.listUser                        thrpt       3   7.668 ± 2.692  ops/ms
ClientGrpc.createUser                       avgt       3   3.263 ± 1.101   ms/op
ClientGrpc.existUser                        avgt       3   3.134 ± 0.783   ms/op
ClientGrpc.getUser                          avgt       3   3.301 ± 1.382   ms/op
ClientGrpc.listUser                         avgt       3   4.123 ± 0.591   ms/op
ClientGrpc.createUser                     sample  290935   3.301 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.627           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.273           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.768           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.831           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.529           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.248           ms/op
ClientGrpc.existUser                      sample  302085   3.176 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.622           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.146           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.134           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.063           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.643           ms/op
ClientGrpc.getUser                        sample  297397   3.226 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.881           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.187           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.962           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.819           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.431           ms/op
ClientGrpc.listUser                       sample  229554   4.182 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.762           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.990           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.160           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.270           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.466           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.955           ms/op
