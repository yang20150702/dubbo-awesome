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
# Warmup Iteration   1: 4.331 ops/ms
# Warmup Iteration   2: 8.973 ops/ms
# Warmup Iteration   3: 9.968 ops/ms
Iteration   1: 10.241 ops/ms
Iteration   2: 10.460 ops/ms
Iteration   3: 10.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.394 ±(99.9%) 2.436 ops/ms [Average]
  (min, avg, max) = (10.241, 10.394, 10.483), stdev = 0.134
  CI (99.9%): [7.959, 12.830] (assumes normal distribution)


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
# Warmup Iteration   1: 7.130 ops/ms
# Warmup Iteration   2: 10.279 ops/ms
# Warmup Iteration   3: 10.846 ops/ms
Iteration   1: 10.854 ops/ms
Iteration   2: 10.788 ops/ms
Iteration   3: 11.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.906 ±(99.9%) 2.751 ops/ms [Average]
  (min, avg, max) = (10.788, 10.906, 11.076), stdev = 0.151
  CI (99.9%): [8.154, 13.657] (assumes normal distribution)


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
# Warmup Iteration   1: 6.856 ops/ms
# Warmup Iteration   2: 9.905 ops/ms
# Warmup Iteration   3: 10.221 ops/ms
Iteration   1: 10.459 ops/ms
Iteration   2: 10.550 ops/ms
Iteration   3: 10.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.528 ±(99.9%) 1.121 ops/ms [Average]
  (min, avg, max) = (10.459, 10.528, 10.575), stdev = 0.061
  CI (99.9%): [9.407, 11.649] (assumes normal distribution)


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
# Warmup Iteration   1: 5.267 ops/ms
# Warmup Iteration   2: 7.426 ops/ms
# Warmup Iteration   3: 7.640 ops/ms
Iteration   1: 7.813 ops/ms
Iteration   2: 7.925 ops/ms
Iteration   3: 7.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.831 ±(99.9%) 1.580 ops/ms [Average]
  (min, avg, max) = (7.755, 7.831, 7.925), stdev = 0.087
  CI (99.9%): [6.251, 9.411] (assumes normal distribution)


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
# Warmup Iteration   1: 4.234 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.003 ms/op
Iteration   1: 3.059 ±(99.9%) 0.002 ms/op
Iteration   2: 3.057 ±(99.9%) 0.003 ms/op
Iteration   3: 3.051 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.056 ±(99.9%) 0.076 ms/op [Average]
  (min, avg, max) = (3.051, 3.056, 3.059), stdev = 0.004
  CI (99.9%): [2.980, 3.132] (assumes normal distribution)


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.003 ms/op
Iteration   1: 3.007 ±(99.9%) 0.003 ms/op
Iteration   2: 2.945 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.971 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (2.945, 2.971, 3.007), stdev = 0.032
  CI (99.9%): [2.389, 3.553] (assumes normal distribution)


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
# Warmup Iteration   1: 4.139 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.004 ms/op
Iteration   1: 3.103 ±(99.9%) 0.001 ms/op
Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
Iteration   3: 3.094 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.118 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.094, 3.118, 3.158), stdev = 0.035
  CI (99.9%): [2.489, 3.748] (assumes normal distribution)


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
# Warmup Iteration   1: 5.904 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.024 ms/op
Iteration   1: 4.072 ±(99.9%) 0.014 ms/op
Iteration   2: 4.062 ±(99.9%) 0.018 ms/op
Iteration   3: 4.088 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.074 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (4.062, 4.074, 4.088), stdev = 0.013
  CI (99.9%): [3.830, 4.318] (assumes normal distribution)


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
# Warmup Iteration   1: 4.229 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
Iteration   1: 3.102 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.715 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   2: 3.042 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  8.389 ms/op
                 createUser·p0.9999: 19.923 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   3: 3.093 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.679 ms/op
                 createUser·p0.999:  13.820 ms/op
                 createUser·p0.9999: 23.254 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311623
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17248 
    [ 2.500,  5.000) = 292008 
    [ 5.000,  7.500) = 1747 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      9.509 ms/op
     p(99.9900) =     22.829 ms/op
     p(99.9990) =     23.429 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.982 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
Iteration   1: 2.832 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  8.309 ms/op
                 existUser·p0.9999: 12.452 ms/op
                 existUser·p1.00:   12.599 ms/op

Iteration   2: 2.852 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  8.389 ms/op
                 existUser·p0.9999: 20.906 ms/op
                 existUser·p1.00:   21.365 ms/op

Iteration   3: 2.925 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  9.985 ms/op
                 existUser·p0.9999: 26.444 ms/op
                 existUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334554
  mean =      2.869 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43089 
    [ 2.500,  5.000) = 289761 
    [ 5.000,  7.500) = 1011 
    [ 7.500, 10.000) = 465 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.855 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.943 ms/op
                 getUser·p0.9999: 14.191 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  8.629 ms/op
                 getUser·p0.9999: 14.402 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.210 ms/op
                 getUser·p0.9999: 18.788 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312202
  mean =      3.072 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 499 
    [ 1.250,  2.500) = 17906 
    [ 2.500,  3.750) = 274126 
    [ 3.750,  5.000) = 17444 
    [ 5.000,  6.250) = 1252 
    [ 6.250,  7.500) = 590 
    [ 7.500,  8.750) = 164 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 100 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      7.795 ms/op
     p(99.9900) =     17.600 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 5.695 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.011 ms/op
Iteration   1: 4.131 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 16.765 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   2: 4.105 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  16.325 ms/op
                 listUser·p0.9999: 19.516 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 3.993 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.694 ms/op
                 listUser·p0.9999: 24.936 ms/op
                 listUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235583
  mean =      4.075 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2208 
    [ 2.500,  5.000) = 205502 
    [ 5.000,  7.500) = 25570 
    [ 7.500, 10.000) = 1744 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     15.080 ms/op
     p(99.9900) =     24.722 ms/op
     p(99.9990) =     25.741 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.394 ± 2.436  ops/ms
ClientGrpc.existUser                       thrpt       3  10.906 ± 2.751  ops/ms
ClientGrpc.getUser                         thrpt       3  10.528 ± 1.121  ops/ms
ClientGrpc.listUser                        thrpt       3   7.831 ± 1.580  ops/ms
ClientGrpc.createUser                       avgt       3   3.056 ± 0.076   ms/op
ClientGrpc.existUser                        avgt       3   2.971 ± 0.582   ms/op
ClientGrpc.getUser                          avgt       3   3.118 ± 0.630   ms/op
ClientGrpc.listUser                         avgt       3   4.074 ± 0.244   ms/op
ClientGrpc.createUser                     sample  311623   3.079 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.585           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.509           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.829           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.626           ms/op
ClientGrpc.existUser                      sample  334554   2.869 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.713           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.855           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.625           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.165           ms/op
ClientGrpc.getUser                        sample  312202   3.072 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.834           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.694           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.795           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.600           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.907           ms/op
ClientGrpc.listUser                       sample  235583   4.075 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.083           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.972           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.479           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.080           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.722           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.509           ms/op
