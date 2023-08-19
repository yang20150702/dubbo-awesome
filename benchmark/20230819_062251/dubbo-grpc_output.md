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
# Warmup Iteration   1: 4.804 ops/ms
# Warmup Iteration   2: 9.228 ops/ms
# Warmup Iteration   3: 10.353 ops/ms
Iteration   1: 10.592 ops/ms
Iteration   2: 10.649 ops/ms
Iteration   3: 10.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.630 ±(99.9%) 0.603 ops/ms [Average]
  (min, avg, max) = (10.592, 10.630, 10.649), stdev = 0.033
  CI (99.9%): [10.027, 11.233] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.119 ops/ms
# Warmup Iteration   2: 11.015 ops/ms
# Warmup Iteration   3: 11.198 ops/ms
Iteration   1: 11.271 ops/ms
Iteration   2: 11.211 ops/ms
Iteration   3: 11.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.278 ±(99.9%) 1.278 ops/ms [Average]
  (min, avg, max) = (11.211, 11.278, 11.351), stdev = 0.070
  CI (99.9%): [9.999, 12.556] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.598 ops/ms
# Warmup Iteration   2: 10.319 ops/ms
# Warmup Iteration   3: 10.501 ops/ms
Iteration   1: 10.906 ops/ms
Iteration   2: 10.692 ops/ms
Iteration   3: 10.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.818 ±(99.9%) 2.041 ops/ms [Average]
  (min, avg, max) = (10.692, 10.818, 10.906), stdev = 0.112
  CI (99.9%): [8.777, 12.859] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.955 ops/ms
# Warmup Iteration   2: 7.863 ops/ms
# Warmup Iteration   3: 7.950 ops/ms
Iteration   1: 8.041 ops/ms
Iteration   2: 8.376 ops/ms
Iteration   3: 8.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.192 ±(99.9%) 3.104 ops/ms [Average]
  (min, avg, max) = (8.041, 8.192, 8.376), stdev = 0.170
  CI (99.9%): [5.087, 11.296] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.937 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.003 ms/op
Iteration   1: 3.005 ±(99.9%) 0.009 ms/op
Iteration   2: 2.995 ±(99.9%) 0.003 ms/op
Iteration   3: 3.019 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.007 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (2.995, 3.007, 3.019), stdev = 0.012
  CI (99.9%): [2.788, 3.225] (assumes normal distribution)


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.004 ms/op
Iteration   1: 2.821 ±(99.9%) 0.004 ms/op
Iteration   2: 2.890 ±(99.9%) 0.003 ms/op
Iteration   3: 2.815 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.842 ±(99.9%) 0.760 ms/op [Average]
  (min, avg, max) = (2.815, 2.842, 2.890), stdev = 0.042
  CI (99.9%): [2.082, 3.602] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.003 ms/op
Iteration   1: 3.013 ±(99.9%) 0.003 ms/op
Iteration   2: 2.983 ±(99.9%) 0.003 ms/op
Iteration   3: 2.964 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.987 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (2.964, 2.987, 3.013), stdev = 0.025
  CI (99.9%): [2.538, 3.435] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.519 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.035 ms/op
Iteration   1: 3.892 ±(99.9%) 0.025 ms/op
Iteration   2: 3.913 ±(99.9%) 0.012 ms/op
Iteration   3: 3.871 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (3.871, 3.892, 3.913), stdev = 0.021
  CI (99.9%): [3.516, 4.268] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.718 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.008 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.825 ms/op
                 createUser·p0.9999: 22.719 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 3.009 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  9.721 ms/op
                 createUser·p0.9999: 26.882 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   3: 2.992 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.710 ms/op
                 createUser·p0.9999: 21.332 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319925
  mean =      3.000 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29524 
    [ 2.500,  5.000) = 288449 
    [ 5.000,  7.500) = 1510 
    [ 7.500, 10.000) = 217 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      8.249 ms/op
     p(99.9900) =     26.150 ms/op
     p(99.9990) =     27.158 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.329 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
Iteration   1: 2.861 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  7.356 ms/op
                 existUser·p0.9999: 11.201 ms/op
                 existUser·p1.00:   12.026 ms/op

Iteration   2: 2.939 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  8.183 ms/op
                 existUser·p0.9999: 22.352 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   3: 2.926 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.801 ms/op
                 existUser·p0.999:  8.237 ms/op
                 existUser·p0.9999: 16.584 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329820
  mean =      2.908 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47960 
    [ 2.500,  5.000) = 279685 
    [ 5.000,  7.500) = 1800 
    [ 7.500, 10.000) = 179 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     19.185 ms/op
     p(99.9990) =     23.157 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.005 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  8.178 ms/op
                 getUser·p0.9999: 12.427 ms/op
                 getUser·p1.00:   12.632 ms/op

Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.764 ms/op
                 getUser·p0.999:  8.621 ms/op
                 getUser·p0.9999: 12.659 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.890 ms/op
                 getUser·p0.9999: 18.699 ms/op
                 getUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318028
  mean =      3.016 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1446 
    [ 1.250,  2.500) = 25899 
    [ 2.500,  3.750) = 272137 
    [ 3.750,  5.000) = 16563 
    [ 5.000,  6.250) = 936 
    [ 6.250,  7.500) = 589 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      8.044 ms/op
     p(99.9900) =     16.351 ms/op
     p(99.9990) =     19.190 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 4.472 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.010 ms/op
Iteration   1: 3.889 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  12.173 ms/op
                 listUser·p0.9999: 15.161 ms/op
                 listUser·p1.00:   15.925 ms/op

Iteration   2: 3.917 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.812 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.126 ms/op
                 listUser·p0.9999: 21.287 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.568 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.482 ms/op
                 listUser·p0.9999: 25.620 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245678
  mean =      3.911 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5091 
    [ 2.500,  5.000) = 216967 
    [ 5.000,  7.500) = 21949 
    [ 7.500, 10.000) = 1163 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     14.079 ms/op
     p(99.9900) =     24.492 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.630 ± 0.603  ops/ms
ClientGrpc.existUser                       thrpt       3  11.278 ± 1.278  ops/ms
ClientGrpc.getUser                         thrpt       3  10.818 ± 2.041  ops/ms
ClientGrpc.listUser                        thrpt       3   8.192 ± 3.104  ops/ms
ClientGrpc.createUser                       avgt       3   3.007 ± 0.218   ms/op
ClientGrpc.existUser                        avgt       3   2.842 ± 0.760   ms/op
ClientGrpc.getUser                          avgt       3   2.987 ± 0.448   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 0.376   ms/op
ClientGrpc.createUser                     sample  319925   3.000 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.628           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.249           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.150           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.263           ms/op
ClientGrpc.existUser                      sample  329820   2.908 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.571           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.710           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.668           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.185           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.167           ms/op
ClientGrpc.getUser                        sample  318028   3.016 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.551           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.044           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.351           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.300           ms/op
ClientGrpc.listUser                       sample  245678   3.911 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.568           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.079           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.492           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.280           ms/op
