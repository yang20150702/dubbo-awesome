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
# Warmup Iteration   1: 5.180 ops/ms
# Warmup Iteration   2: 9.156 ops/ms
# Warmup Iteration   3: 10.252 ops/ms
Iteration   1: 10.274 ops/ms
Iteration   2: 10.283 ops/ms
Iteration   3: 10.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.400 ±(99.9%) 3.851 ops/ms [Average]
  (min, avg, max) = (10.274, 10.400, 10.644), stdev = 0.211
  CI (99.9%): [6.549, 14.252] (assumes normal distribution)


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
# Warmup Iteration   1: 8.300 ops/ms
# Warmup Iteration   2: 10.560 ops/ms
# Warmup Iteration   3: 10.790 ops/ms
Iteration   1: 10.929 ops/ms
Iteration   2: 10.850 ops/ms
Iteration   3: 10.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.844 ±(99.9%) 1.602 ops/ms [Average]
  (min, avg, max) = (10.754, 10.844, 10.929), stdev = 0.088
  CI (99.9%): [9.242, 12.447] (assumes normal distribution)


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
# Warmup Iteration   1: 6.924 ops/ms
# Warmup Iteration   2: 10.050 ops/ms
# Warmup Iteration   3: 10.195 ops/ms
Iteration   1: 10.324 ops/ms
Iteration   2: 10.683 ops/ms
Iteration   3: 10.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.482 ±(99.9%) 3.350 ops/ms [Average]
  (min, avg, max) = (10.324, 10.482, 10.683), stdev = 0.184
  CI (99.9%): [7.132, 13.831] (assumes normal distribution)


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
# Warmup Iteration   1: 5.829 ops/ms
# Warmup Iteration   2: 7.922 ops/ms
# Warmup Iteration   3: 8.110 ops/ms
Iteration   1: 8.097 ops/ms
Iteration   2: 8.368 ops/ms
Iteration   3: 8.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.196 ±(99.9%) 2.739 ops/ms [Average]
  (min, avg, max) = (8.097, 8.196, 8.368), stdev = 0.150
  CI (99.9%): [5.457, 10.934] (assumes normal distribution)


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
# Warmup Iteration   1: 3.969 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.003 ms/op
Iteration   1: 3.074 ±(99.9%) 0.002 ms/op
Iteration   2: 2.992 ±(99.9%) 0.002 ms/op
Iteration   3: 3.183 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.083 ±(99.9%) 1.750 ms/op [Average]
  (min, avg, max) = (2.992, 3.083, 3.183), stdev = 0.096
  CI (99.9%): [1.333, 4.833] (assumes normal distribution)


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
# Warmup Iteration   1: 3.821 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.002 ms/op
Iteration   1: 2.957 ±(99.9%) 0.002 ms/op
Iteration   2: 2.979 ±(99.9%) 0.002 ms/op
Iteration   3: 3.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.991 ±(99.9%) 0.761 ms/op [Average]
  (min, avg, max) = (2.957, 2.991, 3.038), stdev = 0.042
  CI (99.9%): [2.230, 3.753] (assumes normal distribution)


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.003 ms/op
Iteration   2: 3.058 ±(99.9%) 0.003 ms/op
Iteration   3: 3.065 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.051 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (3.028, 3.051, 3.065), stdev = 0.019
  CI (99.9%): [2.695, 3.406] (assumes normal distribution)


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
# Warmup Iteration   1: 5.012 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.036 ms/op
Iteration   1: 4.049 ±(99.9%) 0.023 ms/op
Iteration   2: 4.060 ±(99.9%) 0.008 ms/op
Iteration   3: 3.919 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.009 ±(99.9%) 1.430 ms/op [Average]
  (min, avg, max) = (3.919, 4.009, 4.060), stdev = 0.078
  CI (99.9%): [2.579, 5.439] (assumes normal distribution)


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.417 ms/op
                 createUser·p0.9999: 14.340 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   2: 3.114 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.017 ms/op
                 createUser·p0.9999: 16.009 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   3: 3.064 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.377 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.149 ms/op
                 createUser·p0.999:  12.632 ms/op
                 createUser·p0.9999: 29.756 ms/op
                 createUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310893
  mean =      3.088 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28298 
    [ 2.500,  5.000) = 281787 
    [ 5.000,  7.500) = 515 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.377 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.358 ms/op
     p(99.9900) =     28.863 ms/op
     p(99.9990) =     30.012 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.006 ms/op
Iteration   1: 2.915 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  9.566 ms/op
                 existUser·p0.9999: 19.696 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   2: 2.942 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.521 ms/op
                 existUser·p0.9999: 14.063 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  8.545 ms/op
                 existUser·p0.9999: 17.864 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327066
  mean =      2.935 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53640 
    [ 2.500,  5.000) = 272599 
    [ 5.000,  7.500) = 460 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      8.117 ms/op
     p(99.9900) =     18.441 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.865 ms/op
                 getUser·p0.9999: 12.349 ms/op
                 getUser·p1.00:   12.747 ms/op

Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.247 ms/op
                 getUser·p0.9999: 13.284 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.382 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.171 ms/op
                 getUser·p0.999:  6.065 ms/op
                 getUser·p0.9999: 25.024 ms/op
                 getUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313089
  mean =      3.065 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23987 
    [ 2.500,  5.000) = 288267 
    [ 5.000,  7.500) = 647 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.478 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     25.321 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 4.710 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.010 ms/op
Iteration   1: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.378 ms/op
                 listUser·p0.9999: 19.924 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 4.096 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  13.744 ms/op
                 listUser·p0.9999: 16.947 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 3.881 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 18.949 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240188
  mean =      3.995 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3235 
    [ 2.500,  5.000) = 207603 
    [ 5.000,  7.500) = 28292 
    [ 7.500, 10.000) = 613 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.657 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     19.529 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.400 ± 3.851  ops/ms
ClientGrpc.existUser                       thrpt       3  10.844 ± 1.602  ops/ms
ClientGrpc.getUser                         thrpt       3  10.482 ± 3.350  ops/ms
ClientGrpc.listUser                        thrpt       3   8.196 ± 2.739  ops/ms
ClientGrpc.createUser                       avgt       3   3.083 ± 1.750   ms/op
ClientGrpc.existUser                        avgt       3   2.991 ± 0.761   ms/op
ClientGrpc.getUser                          avgt       3   3.051 ± 0.355   ms/op
ClientGrpc.listUser                         avgt       3   4.009 ± 1.430   ms/op
ClientGrpc.createUser                     sample  310893   3.088 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.377           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.358           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.863           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.081           ms/op
ClientGrpc.existUser                      sample  327066   2.935 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.517           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.117           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.441           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.316           ms/op
ClientGrpc.getUser                        sample  313089   3.065 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.382           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.478           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.445           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.428           ms/op
ClientGrpc.listUser                       sample  240188   3.995 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.908           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.657           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.696           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.529           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.283           ms/op
