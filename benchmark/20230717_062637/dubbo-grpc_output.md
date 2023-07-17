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
# Warmup Iteration   1: 4.149 ops/ms
# Warmup Iteration   2: 8.679 ops/ms
# Warmup Iteration   3: 9.757 ops/ms
Iteration   1: 10.284 ops/ms
Iteration   2: 10.375 ops/ms
Iteration   3: 10.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.378 ±(99.9%) 1.749 ops/ms [Average]
  (min, avg, max) = (10.284, 10.378, 10.475), stdev = 0.096
  CI (99.9%): [8.629, 12.127] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.534 ops/ms
# Warmup Iteration   2: 10.842 ops/ms
# Warmup Iteration   3: 10.728 ops/ms
Iteration   1: 10.928 ops/ms
Iteration   2: 10.813 ops/ms
Iteration   3: 10.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.891 ±(99.9%) 1.236 ops/ms [Average]
  (min, avg, max) = (10.813, 10.891, 10.933), stdev = 0.068
  CI (99.9%): [9.655, 12.127] (assumes normal distribution)


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
# Warmup Iteration   1: 7.144 ops/ms
# Warmup Iteration   2: 9.939 ops/ms
# Warmup Iteration   3: 10.280 ops/ms
Iteration   1: 10.406 ops/ms
Iteration   2: 10.179 ops/ms
Iteration   3: 10.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.315 ±(99.9%) 2.195 ops/ms [Average]
  (min, avg, max) = (10.179, 10.315, 10.406), stdev = 0.120
  CI (99.9%): [8.120, 12.510] (assumes normal distribution)


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
# Warmup Iteration   1: 5.338 ops/ms
# Warmup Iteration   2: 7.543 ops/ms
# Warmup Iteration   3: 8.043 ops/ms
Iteration   1: 7.867 ops/ms
Iteration   2: 7.955 ops/ms
Iteration   3: 8.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.034 ±(99.9%) 3.977 ops/ms [Average]
  (min, avg, max) = (7.867, 8.034, 8.280), stdev = 0.218
  CI (99.9%): [4.057, 12.011] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.253 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 3.029 ±(99.9%) 0.003 ms/op
Iteration   2: 3.075 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.062 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (3.029, 3.062, 3.084), stdev = 0.030
  CI (99.9%): [2.520, 3.605] (assumes normal distribution)


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.920 ±(99.9%) 0.003 ms/op
Iteration   1: 2.927 ±(99.9%) 0.003 ms/op
Iteration   2: 2.926 ±(99.9%) 0.003 ms/op
Iteration   3: 2.821 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 1.111 ms/op [Average]
  (min, avg, max) = (2.821, 2.891, 2.927), stdev = 0.061
  CI (99.9%): [1.780, 4.002] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.325 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.004 ms/op
Iteration   1: 3.101 ±(99.9%) 0.003 ms/op
Iteration   2: 3.035 ±(99.9%) 0.003 ms/op
Iteration   3: 3.050 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.062 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.035, 3.062, 3.101), stdev = 0.035
  CI (99.9%): [2.432, 3.693] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.584 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.009 ms/op
Iteration   1: 4.008 ±(99.9%) 0.035 ms/op
Iteration   2: 4.107 ±(99.9%) 0.016 ms/op
Iteration   3: 3.953 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.022 ±(99.9%) 1.420 ms/op [Average]
  (min, avg, max) = (3.953, 4.022, 4.107), stdev = 0.078
  CI (99.9%): [2.602, 5.443] (assumes normal distribution)


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
# Warmup Iteration   1: 4.352 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
Iteration   1: 3.057 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.316 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.038 ms/op
                 createUser·p0.999:  9.886 ms/op
                 createUser·p0.9999: 13.706 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  8.071 ms/op
                 createUser·p0.9999: 14.814 ms/op
                 createUser·p1.00:   14.991 ms/op

Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.079 ms/op
                 createUser·p0.999:  12.561 ms/op
                 createUser·p0.9999: 17.471 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312926
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 788 
    [ 1.250,  2.500) = 26595 
    [ 2.500,  3.750) = 262097 
    [ 3.750,  5.000) = 20482 
    [ 5.000,  6.250) = 1877 
    [ 6.250,  7.500) = 481 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.316 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =     10.110 ms/op
     p(99.9900) =     15.560 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 3.974 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 2.925 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  8.261 ms/op
                 existUser·p0.9999: 21.955 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   2: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.189 ms/op
                 existUser·p0.999:  6.478 ms/op
                 existUser·p0.9999: 13.970 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.918 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.757 ms/op
                 existUser·p0.9999: 27.789 ms/op
                 existUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330523
  mean =      2.902 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31258 
    [ 2.500,  5.000) = 297735 
    [ 5.000,  7.500) = 1242 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      6.861 ms/op
     p(99.9900) =     23.132 ms/op
     p(99.9990) =     28.007 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.006 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.336 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.071 ms/op
                 getUser·p0.999:  8.782 ms/op
                 getUser·p0.9999: 15.335 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   2: 3.100 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.948 ms/op
                 getUser·p0.999:  7.106 ms/op
                 getUser·p0.9999: 13.981 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  8.630 ms/op
                 getUser·p0.9999: 17.461 ms/op
                 getUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308767
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 925 
    [ 1.250,  2.500) = 19653 
    [ 2.500,  3.750) = 262025 
    [ 3.750,  5.000) = 22672 
    [ 5.000,  6.250) = 2311 
    [ 6.250,  7.500) = 745 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 51 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.095 ms/op
     p(99.9000) =      8.157 ms/op
     p(99.9900) =     16.814 ms/op
     p(99.9990) =     17.725 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 5.740 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.011 ms/op
Iteration   1: 4.064 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  13.604 ms/op
                 listUser·p0.9999: 19.299 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 4.009 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  14.704 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 4.062 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  16.470 ms/op
                 listUser·p0.9999: 18.895 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237245
  mean =      4.045 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3226 
    [ 2.500,  5.000) = 206619 
    [ 5.000,  7.500) = 25526 
    [ 7.500, 10.000) = 1299 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     18.883 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.378 ± 1.749  ops/ms
ClientGrpc.existUser                       thrpt       3  10.891 ± 1.236  ops/ms
ClientGrpc.getUser                         thrpt       3  10.315 ± 2.195  ops/ms
ClientGrpc.listUser                        thrpt       3   8.034 ± 3.977  ops/ms
ClientGrpc.createUser                       avgt       3   3.062 ± 0.542   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 1.111   ms/op
ClientGrpc.getUser                          avgt       3   3.062 ± 0.630   ms/op
ClientGrpc.listUser                         avgt       3   4.022 ± 1.420   ms/op
ClientGrpc.createUser                     sample  312926   3.066 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.316           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.964           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.110           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.560           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.088           ms/op
ClientGrpc.existUser                      sample  330523   2.902 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.666           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.861           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.132           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.082           ms/op
ClientGrpc.getUser                        sample  308767   3.110 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.336           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.095           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.157           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.814           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.826           ms/op
ClientGrpc.listUser                       sample  237245   4.045 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.959           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.877           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.883           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.316           ms/op
