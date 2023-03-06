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
# Warmup Iteration   1: 4.490 ops/ms
# Warmup Iteration   2: 9.221 ops/ms
# Warmup Iteration   3: 10.101 ops/ms
Iteration   1: 10.609 ops/ms
Iteration   2: 10.569 ops/ms
Iteration   3: 10.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.675 ±(99.9%) 2.746 ops/ms [Average]
  (min, avg, max) = (10.569, 10.675, 10.847), stdev = 0.151
  CI (99.9%): [7.928, 13.421] (assumes normal distribution)


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
# Warmup Iteration   1: 7.516 ops/ms
# Warmup Iteration   2: 10.566 ops/ms
# Warmup Iteration   3: 10.648 ops/ms
Iteration   1: 10.732 ops/ms
Iteration   2: 10.856 ops/ms
Iteration   3: 10.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.797 ±(99.9%) 1.138 ops/ms [Average]
  (min, avg, max) = (10.732, 10.797, 10.856), stdev = 0.062
  CI (99.9%): [9.659, 11.935] (assumes normal distribution)


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
# Warmup Iteration   1: 7.591 ops/ms
# Warmup Iteration   2: 10.229 ops/ms
# Warmup Iteration   3: 10.603 ops/ms
Iteration   1: 10.094 ops/ms
Iteration   2: 10.799 ops/ms
Iteration   3: 10.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.431 ±(99.9%) 6.445 ops/ms [Average]
  (min, avg, max) = (10.094, 10.431, 10.799), stdev = 0.353
  CI (99.9%): [3.986, 16.876] (assumes normal distribution)


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
# Warmup Iteration   1: 6.341 ops/ms
# Warmup Iteration   2: 7.857 ops/ms
# Warmup Iteration   3: 8.075 ops/ms
Iteration   1: 8.211 ops/ms
Iteration   2: 7.947 ops/ms
Iteration   3: 8.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.123 ±(99.9%) 2.782 ops/ms [Average]
  (min, avg, max) = (7.947, 8.123, 8.211), stdev = 0.153
  CI (99.9%): [5.340, 10.905] (assumes normal distribution)


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.003 ms/op
Iteration   1: 2.983 ±(99.9%) 0.003 ms/op
Iteration   2: 3.110 ±(99.9%) 0.002 ms/op
Iteration   3: 3.053 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.049 ±(99.9%) 1.166 ms/op [Average]
  (min, avg, max) = (2.983, 3.049, 3.110), stdev = 0.064
  CI (99.9%): [1.882, 4.215] (assumes normal distribution)


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
# Warmup Iteration   1: 3.324 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.003 ms/op
Iteration   1: 2.933 ±(99.9%) 0.002 ms/op
Iteration   2: 2.890 ±(99.9%) 0.002 ms/op
Iteration   3: 2.941 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.921 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (2.890, 2.921, 2.941), stdev = 0.028
  CI (99.9%): [2.415, 3.428] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.986 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.003 ms/op
Iteration   1: 3.060 ±(99.9%) 0.002 ms/op
Iteration   2: 2.987 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.012 ±(99.9%) 0.760 ms/op [Average]
  (min, avg, max) = (2.987, 3.012, 3.060), stdev = 0.042
  CI (99.9%): [2.252, 3.771] (assumes normal distribution)


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
# Warmup Iteration   1: 4.821 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.011 ms/op
Iteration   1: 3.897 ±(99.9%) 0.009 ms/op
Iteration   2: 3.955 ±(99.9%) 0.013 ms/op
Iteration   3: 4.051 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.968 ±(99.9%) 1.418 ms/op [Average]
  (min, avg, max) = (3.897, 3.968, 4.051), stdev = 0.078
  CI (99.9%): [2.550, 5.386] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.118 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.379 ms/op
                 createUser·p0.9999: 14.729 ms/op
                 createUser·p1.00:   15.450 ms/op

Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.963 ms/op
                 createUser·p0.9999: 16.140 ms/op
                 createUser·p1.00:   16.695 ms/op

Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.885 ms/op
                 createUser·p0.9999: 20.863 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310072
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33985 
    [ 2.500,  5.000) = 274890 
    [ 5.000,  7.500) = 779 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.298 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     22.603 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  7.129 ms/op
                 existUser·p0.9999: 17.629 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   2: 2.879 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.595 ms/op
                 existUser·p0.9999: 21.932 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   3: 2.932 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.103 ms/op
                 existUser·p0.9999: 21.859 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327022
  mean =      2.936 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55623 
    [ 2.500,  5.000) = 270623 
    [ 5.000,  7.500) = 514 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.930 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     22.241 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.947 ms/op
                 getUser·p0.9999: 14.303 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   2: 3.074 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.540 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.800 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.666 ms/op
                 getUser·p0.9999: 13.063 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  7.585 ms/op
                 getUser·p0.9999: 16.327 ms/op
                 getUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317575
  mean =      3.024 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1821 
    [ 1.250,  2.500) = 22941 
    [ 2.500,  3.750) = 278336 
    [ 3.750,  5.000) = 13578 
    [ 5.000,  6.250) = 430 
    [ 6.250,  7.500) = 139 
    [ 7.500,  8.750) = 131 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.606 ms/op
     p(99.9900) =     15.057 ms/op
     p(99.9990) =     16.591 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 5.190 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.012 ms/op
Iteration   1: 4.017 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  11.990 ms/op
                 listUser·p0.9999: 19.565 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   2: 4.040 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  13.728 ms/op
                 listUser·p0.9999: 16.484 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   3: 4.026 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.316 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  15.345 ms/op
                 listUser·p0.9999: 19.533 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238128
  mean =      4.028 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5619 
    [ 2.500,  5.000) = 197462 
    [ 5.000,  7.500) = 33782 
    [ 7.500, 10.000) = 843 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.316 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     19.247 ms/op
     p(99.9990) =     20.082 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.675 ± 2.746  ops/ms
ClientGrpc.existUser                       thrpt       3  10.797 ± 1.138  ops/ms
ClientGrpc.getUser                         thrpt       3  10.431 ± 6.445  ops/ms
ClientGrpc.listUser                        thrpt       3   8.123 ± 2.782  ops/ms
ClientGrpc.createUser                       avgt       3   3.049 ± 1.166   ms/op
ClientGrpc.existUser                        avgt       3   2.921 ± 0.506   ms/op
ClientGrpc.getUser                          avgt       3   3.012 ± 0.760   ms/op
ClientGrpc.listUser                         avgt       3   3.968 ± 1.418   ms/op
ClientGrpc.createUser                     sample  310072   3.096 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.695           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.298           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.316           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.708           ms/op
ClientGrpc.existUser                      sample  327022   2.936 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.638           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.930           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.529           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.134           ms/op
ClientGrpc.getUser                        sample  317575   3.024 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.540           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.606           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.057           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.941           ms/op
ClientGrpc.listUser                       sample  238128   4.028 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.316           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.057           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.247           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.218           ms/op
