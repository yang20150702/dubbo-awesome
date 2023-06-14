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
# Warmup Iteration   1: 4.153 ops/ms
# Warmup Iteration   2: 8.629 ops/ms
# Warmup Iteration   3: 9.997 ops/ms
Iteration   1: 10.388 ops/ms
Iteration   2: 10.505 ops/ms
Iteration   3: 10.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.458 ±(99.9%) 1.136 ops/ms [Average]
  (min, avg, max) = (10.388, 10.458, 10.505), stdev = 0.062
  CI (99.9%): [9.322, 11.594] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.877 ops/ms
# Warmup Iteration   2: 10.510 ops/ms
# Warmup Iteration   3: 11.068 ops/ms
Iteration   1: 10.755 ops/ms
Iteration   2: 11.049 ops/ms
Iteration   3: 10.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.896 ±(99.9%) 2.689 ops/ms [Average]
  (min, avg, max) = (10.755, 10.896, 11.049), stdev = 0.147
  CI (99.9%): [8.208, 13.585] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.424 ops/ms
# Warmup Iteration   2: 10.268 ops/ms
# Warmup Iteration   3: 10.430 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.476 ops/ms
Iteration   3: 10.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.522 ±(99.9%) 1.776 ops/ms [Average]
  (min, avg, max) = (10.456, 10.522, 10.634), stdev = 0.097
  CI (99.9%): [8.746, 12.298] (assumes normal distribution)


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
# Warmup Iteration   1: 5.269 ops/ms
# Warmup Iteration   2: 7.917 ops/ms
# Warmup Iteration   3: 7.913 ops/ms
Iteration   1: 8.081 ops/ms
Iteration   2: 8.188 ops/ms
Iteration   3: 8.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.105 ±(99.9%) 1.361 ops/ms [Average]
  (min, avg, max) = (8.044, 8.105, 8.188), stdev = 0.075
  CI (99.9%): [6.744, 9.466] (assumes normal distribution)


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
# Warmup Iteration   1: 4.332 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.003 ms/op
Iteration   1: 3.072 ±(99.9%) 0.001 ms/op
Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
Iteration   3: 3.022 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.035 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (3.010, 3.035, 3.072), stdev = 0.033
  CI (99.9%): [2.426, 3.644] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.004 ms/op
Iteration   1: 2.886 ±(99.9%) 0.003 ms/op
Iteration   2: 2.937 ±(99.9%) 0.003 ms/op
Iteration   3: 2.850 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 0.796 ms/op [Average]
  (min, avg, max) = (2.850, 2.891, 2.937), stdev = 0.044
  CI (99.9%): [2.095, 3.688] (assumes normal distribution)


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.025 ms/op
Iteration   1: 3.057 ±(99.9%) 0.004 ms/op
Iteration   2: 3.022 ±(99.9%) 0.004 ms/op
Iteration   3: 3.082 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.054 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (3.022, 3.054, 3.082), stdev = 0.030
  CI (99.9%): [2.502, 3.605] (assumes normal distribution)


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
# Warmup Iteration   1: 5.334 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.007 ms/op
Iteration   1: 3.873 ±(99.9%) 0.020 ms/op
Iteration   2: 3.926 ±(99.9%) 0.015 ms/op
Iteration   3: 3.928 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.909 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (3.873, 3.909, 3.928), stdev = 0.031
  CI (99.9%): [3.338, 4.480] (assumes normal distribution)


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  7.307 ms/op
                 createUser·p0.9999: 12.742 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.535 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.395 ms/op
                 createUser·p0.9999: 14.933 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.157 ms/op
                 createUser·p0.999:  9.535 ms/op
                 createUser·p0.9999: 26.719 ms/op
                 createUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314893
  mean =      3.048 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20245 
    [ 2.500,  5.000) = 293122 
    [ 5.000,  7.500) = 1195 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.652 ms/op
     p(99.9900) =     26.100 ms/op
     p(99.9990) =     26.991 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
Iteration   1: 2.993 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.349 ms/op
                 existUser·p0.9999: 18.338 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   2: 2.918 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.688 ms/op
                 existUser·p0.9999: 14.305 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   3: 2.922 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.862 ms/op
                 existUser·p0.9999: 16.681 ms/op
                 existUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325852
  mean =      2.944 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 603 
    [ 1.250,  2.500) = 34997 
    [ 2.500,  3.750) = 279648 
    [ 3.750,  5.000) = 9445 
    [ 5.000,  6.250) = 628 
    [ 6.250,  7.500) = 292 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.915 ms/op
     p(99.9900) =     17.126 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 4.256 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.006 ms/op
Iteration   1: 3.048 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  10.470 ms/op
                 getUser·p0.9999: 14.770 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  7.430 ms/op
                 getUser·p0.9999: 14.100 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.736 ms/op
                 getUser·p0.999:  6.839 ms/op
                 getUser·p0.9999: 16.663 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314158
  mean =      3.053 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 425 
    [ 1.250,  2.500) = 19891 
    [ 2.500,  3.750) = 275196 
    [ 3.750,  5.000) = 16830 
    [ 5.000,  6.250) = 1242 
    [ 6.250,  7.500) = 263 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      7.471 ms/op
     p(99.9900) =     16.024 ms/op
     p(99.9990) =     17.788 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 5.670 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.011 ms/op
Iteration   1: 3.972 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 23.753 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 3.869 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  19.431 ms/op
                 listUser·p0.9999: 23.884 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   3: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.647 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.804 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 18.866 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244544
  mean =      3.927 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2860 
    [ 2.500,  5.000) = 220112 
    [ 5.000,  7.500) = 20357 
    [ 7.500, 10.000) = 744 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     26.410 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.458 ± 1.136  ops/ms
ClientGrpc.existUser                       thrpt       3  10.896 ± 2.689  ops/ms
ClientGrpc.getUser                         thrpt       3  10.522 ± 1.776  ops/ms
ClientGrpc.listUser                        thrpt       3   8.105 ± 1.361  ops/ms
ClientGrpc.createUser                       avgt       3   3.035 ± 0.609   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 0.796   ms/op
ClientGrpc.getUser                          avgt       3   3.054 ± 0.552   ms/op
ClientGrpc.listUser                         avgt       3   3.909 ± 0.571   ms/op
ClientGrpc.createUser                     sample  314893   3.048 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.535           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.652           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.100           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.066           ms/op
ClientGrpc.existUser                      sample  325852   2.944 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.642           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.915           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.126           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.071           ms/op
ClientGrpc.getUser                        sample  314158   3.053 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.790           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.471           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.024           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.923           ms/op
ClientGrpc.listUser                       sample  244544   3.927 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.647           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.565           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.560           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.706           ms/op
