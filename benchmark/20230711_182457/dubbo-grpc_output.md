# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ops/ms
# Warmup Iteration   2: 8.909 ops/ms
# Warmup Iteration   3: 9.822 ops/ms
Iteration   1: 10.459 ops/ms
Iteration   2: 10.344 ops/ms
Iteration   3: 10.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.421 ±(99.9%) 1.216 ops/ms [Average]
  (min, avg, max) = (10.344, 10.421, 10.460), stdev = 0.067
  CI (99.9%): [9.206, 11.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.370 ops/ms
# Warmup Iteration   2: 10.356 ops/ms
# Warmup Iteration   3: 10.728 ops/ms
Iteration   1: 10.820 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.735 ±(99.9%) 1.389 ops/ms [Average]
  (min, avg, max) = (10.672, 10.735, 10.820), stdev = 0.076
  CI (99.9%): [9.347, 12.124] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.478 ops/ms
# Warmup Iteration   2: 9.856 ops/ms
# Warmup Iteration   3: 10.496 ops/ms
Iteration   1: 10.380 ops/ms
Iteration   2: 10.389 ops/ms
Iteration   3: 10.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.389 ±(99.9%) 0.164 ops/ms [Average]
  (min, avg, max) = (10.380, 10.389, 10.398), stdev = 0.009
  CI (99.9%): [10.225, 10.553] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.068 ops/ms
# Warmup Iteration   2: 7.779 ops/ms
# Warmup Iteration   3: 7.931 ops/ms
Iteration   1: 8.012 ops/ms
Iteration   2: 7.973 ops/ms
Iteration   3: 7.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.987 ±(99.9%) 0.393 ops/ms [Average]
  (min, avg, max) = (7.973, 7.987, 8.012), stdev = 0.022
  CI (99.9%): [7.594, 8.379] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.241 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.002 ms/op
Iteration   2: 2.978 ±(99.9%) 0.003 ms/op
Iteration   3: 3.005 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.003 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (2.978, 3.003, 3.026), stdev = 0.024
  CI (99.9%): [2.558, 3.448] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.165 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.002 ms/op
Iteration   1: 2.963 ±(99.9%) 0.003 ms/op
Iteration   2: 2.942 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.956 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.942, 2.956, 2.963), stdev = 0.012
  CI (99.9%): [2.741, 3.171] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.377 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.008 ms/op
Iteration   1: 3.106 ±(99.9%) 0.003 ms/op
Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
Iteration   3: 3.023 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.063 ±(99.9%) 0.758 ms/op [Average]
  (min, avg, max) = (3.023, 3.063, 3.106), stdev = 0.042
  CI (99.9%): [2.305, 3.821] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.352 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.020 ms/op
Iteration   1: 4.012 ±(99.9%) 0.009 ms/op
Iteration   2: 3.970 ±(99.9%) 0.019 ms/op
Iteration   3: 4.024 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.002 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (3.970, 4.002, 4.024), stdev = 0.028
  CI (99.9%): [3.484, 4.520] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.283 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.046 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  10.699 ms/op
                 createUser·p0.9999: 18.645 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.129 ms/op
                 createUser·p0.999:  13.225 ms/op
                 createUser·p0.9999: 22.886 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  10.008 ms/op
                 createUser·p0.9999: 22.917 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316954
  mean =      3.027 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23217 
    [ 2.500,  5.000) = 292257 
    [ 5.000,  7.500) = 999 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =     10.781 ms/op
     p(99.9900) =     22.620 ms/op
     p(99.9990) =     23.484 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.943 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 2.860 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.473 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  6.369 ms/op
                 existUser·p0.9999: 10.974 ms/op
                 existUser·p1.00:   11.895 ms/op

Iteration   2: 2.883 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.326 ms/op
                 existUser·p0.99:   3.961 ms/op
                 existUser·p0.999:  6.103 ms/op
                 existUser·p0.9999: 22.217 ms/op
                 existUser·p1.00:   22.413 ms/op

Iteration   3: 2.934 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  6.430 ms/op
                 existUser·p0.9999: 15.794 ms/op
                 existUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331758
  mean =      2.892 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34965 
    [ 2.500,  5.000) = 296093 
    [ 5.000,  7.500) = 506 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.478 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      6.283 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     22.370 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.345 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  9.257 ms/op
                 getUser·p0.9999: 13.840 ms/op
                 getUser·p1.00:   15.663 ms/op

Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.815 ms/op
                 getUser·p0.999:  7.232 ms/op
                 getUser·p0.9999: 21.653 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.043 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.416 ms/op
                 getUser·p0.999:  6.740 ms/op
                 getUser·p0.9999: 16.245 ms/op
                 getUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315774
  mean =      3.040 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18789 
    [ 2.500,  5.000) = 295107 
    [ 5.000,  7.500) = 1569 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      7.438 ms/op
     p(99.9900) =     20.503 ms/op
     p(99.9990) =     22.113 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.064 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.010 ms/op
Iteration   1: 4.024 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.206 ms/op
                 listUser·p0.9999: 20.875 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.973 ms/op
                 listUser·p0.999:  15.960 ms/op
                 listUser·p0.9999: 24.333 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   3: 4.014 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.901 ms/op
                 listUser·p0.999:  15.570 ms/op
                 listUser·p0.9999: 29.859 ms/op
                 listUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237706
  mean =      4.036 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2040 
    [ 2.500,  5.000) = 215112 
    [ 5.000,  7.500) = 19287 
    [ 7.500, 10.000) = 855 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     15.624 ms/op
     p(99.9900) =     29.040 ms/op
     p(99.9990) =     31.117 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.421 ± 1.216  ops/ms
ClientGrpc.existUser                       thrpt       3  10.735 ± 1.389  ops/ms
ClientGrpc.getUser                         thrpt       3  10.389 ± 0.164  ops/ms
ClientGrpc.listUser                        thrpt       3   7.987 ± 0.393  ops/ms
ClientGrpc.createUser                       avgt       3   3.003 ± 0.445   ms/op
ClientGrpc.existUser                        avgt       3   2.956 ± 0.215   ms/op
ClientGrpc.getUser                          avgt       3   3.063 ± 0.758   ms/op
ClientGrpc.listUser                         avgt       3   4.002 ± 0.518   ms/op
ClientGrpc.createUser                     sample  316954   3.027 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.606           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.781           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.620           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.084           ms/op
ClientGrpc.existUser                      sample  331758   2.892 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.473           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.063           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.283           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.808           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.413           ms/op
ClientGrpc.getUser                        sample  315774   3.040 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.605           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.661           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.438           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.503           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.512           ms/op
ClientGrpc.listUser                       sample  237706   4.036 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.292           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.624           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.040           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.228           ms/op
