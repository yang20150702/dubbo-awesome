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
# Warmup Iteration   1: 3.594 ops/ms
# Warmup Iteration   2: 8.825 ops/ms
# Warmup Iteration   3: 9.984 ops/ms
Iteration   1: 10.177 ops/ms
Iteration   2: 10.359 ops/ms
Iteration   3: 10.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.329 ±(99.9%) 2.552 ops/ms [Average]
  (min, avg, max) = (10.177, 10.329, 10.451), stdev = 0.140
  CI (99.9%): [7.777, 12.881] (assumes normal distribution)


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
# Warmup Iteration   1: 7.552 ops/ms
# Warmup Iteration   2: 10.662 ops/ms
# Warmup Iteration   3: 10.963 ops/ms
Iteration   1: 10.916 ops/ms
Iteration   2: 10.877 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.846 ±(99.9%) 1.636 ops/ms [Average]
  (min, avg, max) = (10.745, 10.846, 10.916), stdev = 0.090
  CI (99.9%): [9.210, 12.482] (assumes normal distribution)


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
# Warmup Iteration   1: 7.502 ops/ms
# Warmup Iteration   2: 9.956 ops/ms
# Warmup Iteration   3: 10.367 ops/ms
Iteration   1: 10.473 ops/ms
Iteration   2: 10.512 ops/ms
Iteration   3: 10.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.471 ±(99.9%) 0.767 ops/ms [Average]
  (min, avg, max) = (10.428, 10.471, 10.512), stdev = 0.042
  CI (99.9%): [9.704, 11.238] (assumes normal distribution)


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
# Warmup Iteration   1: 5.452 ops/ms
# Warmup Iteration   2: 7.777 ops/ms
# Warmup Iteration   3: 7.927 ops/ms
Iteration   1: 8.041 ops/ms
Iteration   2: 8.079 ops/ms
Iteration   3: 8.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.060 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (8.041, 8.060, 8.079), stdev = 0.019
  CI (99.9%): [7.720, 8.400] (assumes normal distribution)


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
# Warmup Iteration   1: 4.109 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 3.066 ±(99.9%) 0.003 ms/op
Iteration   3: 3.027 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.062 ±(99.9%) 0.607 ms/op [Average]
  (min, avg, max) = (3.027, 3.062, 3.093), stdev = 0.033
  CI (99.9%): [2.454, 3.669] (assumes normal distribution)


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.005 ms/op
Iteration   1: 2.980 ±(99.9%) 0.002 ms/op
Iteration   2: 2.983 ±(99.9%) 0.002 ms/op
Iteration   3: 2.911 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.958 ±(99.9%) 0.749 ms/op [Average]
  (min, avg, max) = (2.911, 2.958, 2.983), stdev = 0.041
  CI (99.9%): [2.209, 3.707] (assumes normal distribution)


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
# Warmup Iteration   1: 4.445 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.003 ms/op
Iteration   1: 3.036 ±(99.9%) 0.002 ms/op
Iteration   2: 3.083 ±(99.9%) 0.001 ms/op
Iteration   3: 3.067 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.062 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (3.036, 3.062, 3.083), stdev = 0.023
  CI (99.9%): [2.634, 3.490] (assumes normal distribution)


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
# Warmup Iteration   1: 5.533 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.031 ms/op
Iteration   1: 3.997 ±(99.9%) 0.012 ms/op
Iteration   2: 4.035 ±(99.9%) 0.016 ms/op
Iteration   3: 4.023 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.018 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (3.997, 4.018, 4.035), stdev = 0.019
  CI (99.9%): [3.664, 4.372] (assumes normal distribution)


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
# Warmup Iteration   1: 4.690 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.005 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  9.544 ms/op
                 createUser·p0.9999: 13.873 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  7.279 ms/op
                 createUser·p0.9999: 15.458 ms/op
                 createUser·p1.00:   15.909 ms/op

Iteration   3: 3.094 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  11.904 ms/op
                 createUser·p0.9999: 22.533 ms/op
                 createUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313140
  mean =      3.064 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21588 
    [ 2.500,  5.000) = 289641 
    [ 5.000,  7.500) = 1381 
    [ 7.500, 10.000) = 200 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =     10.273 ms/op
     p(99.9900) =     22.098 ms/op
     p(99.9990) =     22.643 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  6.629 ms/op
                 existUser·p0.9999: 13.635 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  9.044 ms/op
                 existUser·p0.9999: 14.538 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   3: 2.930 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  6.178 ms/op
                 existUser·p0.9999: 15.731 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323362
  mean =      2.968 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1111 
    [ 1.250,  2.500) = 25310 
    [ 2.500,  3.750) = 286560 
    [ 3.750,  5.000) = 9037 
    [ 5.000,  6.250) = 776 
    [ 6.250,  7.500) = 280 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.247 ms/op
     p(99.9900) =     14.756 ms/op
     p(99.9990) =     17.753 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.008 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  7.524 ms/op
                 getUser·p0.9999: 14.287 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.335 ms/op
                 getUser·p0.999:  6.799 ms/op
                 getUser·p0.9999: 23.364 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.627 ms/op
                 getUser·p0.9999: 18.597 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311605
  mean =      3.081 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14695 
    [ 2.500,  5.000) = 295487 
    [ 5.000,  7.500) = 1132 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.392 ms/op
     p(99.9900) =     22.796 ms/op
     p(99.9990) =     23.524 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 5.976 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.011 ms/op
Iteration   1: 3.973 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.458 ms/op
                 listUser·p0.999:  13.517 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 4.025 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.778 ms/op
                 listUser·p0.9999: 19.043 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   3: 4.047 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.696 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  18.305 ms/op
                 listUser·p0.9999: 28.720 ms/op
                 listUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239265
  mean =      4.015 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3078 
    [ 2.500,  5.000) = 212201 
    [ 5.000,  7.500) = 22295 
    [ 7.500, 10.000) = 1216 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     15.724 ms/op
     p(99.9900) =     25.332 ms/op
     p(99.9990) =     29.879 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.329 ± 2.552  ops/ms
ClientGrpc.existUser                       thrpt       3  10.846 ± 1.636  ops/ms
ClientGrpc.getUser                         thrpt       3  10.471 ± 0.767  ops/ms
ClientGrpc.listUser                        thrpt       3   8.060 ± 0.340  ops/ms
ClientGrpc.createUser                       avgt       3   3.062 ± 0.607   ms/op
ClientGrpc.existUser                        avgt       3   2.958 ± 0.749   ms/op
ClientGrpc.getUser                          avgt       3   3.062 ± 0.428   ms/op
ClientGrpc.listUser                         avgt       3   4.018 ± 0.354   ms/op
ClientGrpc.createUser                     sample  313140   3.064 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.785           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.273           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.098           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.807           ms/op
ClientGrpc.existUser                      sample  323362   2.968 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.683           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.247           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.756           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.859           ms/op
ClientGrpc.getUser                        sample  311605   3.081 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.728           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.392           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.796           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.593           ms/op
ClientGrpc.listUser                       sample  239265   4.015 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.696           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.168           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.724           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.332           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.950           ms/op
