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
# Warmup Iteration   1: 4.207 ops/ms
# Warmup Iteration   2: 8.964 ops/ms
# Warmup Iteration   3: 10.136 ops/ms
Iteration   1: 10.371 ops/ms
Iteration   2: 10.046 ops/ms
Iteration   3: 10.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.189 ±(99.9%) 3.026 ops/ms [Average]
  (min, avg, max) = (10.046, 10.189, 10.371), stdev = 0.166
  CI (99.9%): [7.164, 13.215] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.306 ops/ms
# Warmup Iteration   2: 10.082 ops/ms
# Warmup Iteration   3: 10.503 ops/ms
Iteration   1: 10.494 ops/ms
Iteration   2: 10.571 ops/ms
Iteration   3: 10.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.554 ±(99.9%) 0.963 ops/ms [Average]
  (min, avg, max) = (10.494, 10.554, 10.596), stdev = 0.053
  CI (99.9%): [9.591, 11.517] (assumes normal distribution)


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
# Warmup Iteration   1: 6.505 ops/ms
# Warmup Iteration   2: 9.875 ops/ms
# Warmup Iteration   3: 10.044 ops/ms
Iteration   1: 10.072 ops/ms
Iteration   2: 10.029 ops/ms
Iteration   3: 9.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.006 ±(99.9%) 1.458 ops/ms [Average]
  (min, avg, max) = (9.917, 10.006, 10.072), stdev = 0.080
  CI (99.9%): [8.548, 11.465] (assumes normal distribution)


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
# Warmup Iteration   1: 5.951 ops/ms
# Warmup Iteration   2: 7.333 ops/ms
# Warmup Iteration   3: 7.820 ops/ms
Iteration   1: 7.913 ops/ms
Iteration   2: 7.894 ops/ms
Iteration   3: 7.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.892 ±(99.9%) 0.408 ops/ms [Average]
  (min, avg, max) = (7.869, 7.892, 7.913), stdev = 0.022
  CI (99.9%): [7.484, 8.300] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.443 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.003 ms/op
Iteration   1: 3.309 ±(99.9%) 0.001 ms/op
Iteration   2: 3.256 ±(99.9%) 0.003 ms/op
Iteration   3: 3.254 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.273 ±(99.9%) 0.570 ms/op [Average]
  (min, avg, max) = (3.254, 3.273, 3.309), stdev = 0.031
  CI (99.9%): [2.703, 3.844] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.346 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.001 ms/op
Iteration   1: 3.193 ±(99.9%) 0.002 ms/op
Iteration   2: 3.206 ±(99.9%) 0.002 ms/op
Iteration   3: 3.235 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.211 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (3.193, 3.211, 3.235), stdev = 0.022
  CI (99.9%): [2.818, 3.605] (assumes normal distribution)


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.002 ms/op
Iteration   1: 3.196 ±(99.9%) 0.002 ms/op
Iteration   2: 3.289 ±(99.9%) 0.003 ms/op
Iteration   3: 3.156 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.214 ±(99.9%) 1.242 ms/op [Average]
  (min, avg, max) = (3.156, 3.214, 3.289), stdev = 0.068
  CI (99.9%): [1.972, 4.456] (assumes normal distribution)


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
# Warmup Iteration   1: 6.125 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.011 ms/op
Iteration   1: 4.005 ±(99.9%) 0.013 ms/op
Iteration   2: 3.979 ±(99.9%) 0.038 ms/op
Iteration   3: 4.045 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.010 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (3.979, 4.010, 4.045), stdev = 0.033
  CI (99.9%): [3.400, 4.619] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.426 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
Iteration   1: 3.173 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.627 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  10.103 ms/op
                 createUser·p0.9999: 17.856 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   2: 3.263 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  9.750 ms/op
                 createUser·p0.9999: 19.012 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  12.304 ms/op
                 createUser·p0.9999: 24.512 ms/op
                 createUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298329
  mean =      3.216 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19892 
    [ 2.500,  5.000) = 276912 
    [ 5.000,  7.500) = 909 
    [ 7.500, 10.000) = 275 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     11.119 ms/op
     p(99.9900) =     24.090 ms/op
     p(99.9990) =     25.004 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
Iteration   1: 3.094 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  5.534 ms/op
                 existUser·p0.9999: 12.817 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  5.972 ms/op
                 existUser·p0.9999: 14.195 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  7.987 ms/op
                 existUser·p0.9999: 20.694 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313888
  mean =      3.058 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31663 
    [ 2.500,  5.000) = 281520 
    [ 5.000,  7.500) = 463 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      7.053 ms/op
     p(99.9900) =     19.422 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 4.719 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.006 ms/op
Iteration   1: 3.087 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.881 ms/op
                 getUser·p0.9999: 13.128 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  8.468 ms/op
                 getUser·p0.9999: 14.746 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   3: 3.178 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.542 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.601 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307362
  mean =      3.123 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1316 
    [ 1.250,  2.500) = 16919 
    [ 2.500,  3.750) = 262450 
    [ 3.750,  5.000) = 25695 
    [ 5.000,  6.250) = 436 
    [ 6.250,  7.500) = 260 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.285 ms/op
     p(99.9900) =     16.819 ms/op
     p(99.9990) =     17.594 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 5.312 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.011 ms/op
Iteration   1: 4.031 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.526 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.015 ms/op
                 listUser·p0.999:  15.657 ms/op
                 listUser·p0.9999: 22.581 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   2: 3.959 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.321 ms/op
                 listUser·p0.9999: 18.440 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   3: 4.049 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.714 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.032 ms/op
                 listUser·p0.999:  15.926 ms/op
                 listUser·p0.9999: 26.290 ms/op
                 listUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239256
  mean =      4.012 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2562 
    [ 2.500,  5.000) = 211026 
    [ 5.000,  7.500) = 24333 
    [ 7.500, 10.000) = 886 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     16.015 ms/op
     p(99.9900) =     25.307 ms/op
     p(99.9990) =     26.484 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.189 ± 3.026  ops/ms
ClientGrpc.existUser                       thrpt       3  10.554 ± 0.963  ops/ms
ClientGrpc.getUser                         thrpt       3  10.006 ± 1.458  ops/ms
ClientGrpc.listUser                        thrpt       3   7.892 ± 0.408  ops/ms
ClientGrpc.createUser                       avgt       3   3.273 ± 0.570   ms/op
ClientGrpc.existUser                        avgt       3   3.211 ± 0.393   ms/op
ClientGrpc.getUser                          avgt       3   3.214 ± 1.242   ms/op
ClientGrpc.listUser                         avgt       3   4.010 ± 0.609   ms/op
ClientGrpc.createUser                     sample  298329   3.216 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.627           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.183           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.071           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.119           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.090           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.100           ms/op
ClientGrpc.existUser                      sample  313888   3.058 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.592           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.053           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.422           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.168           ms/op
ClientGrpc.getUser                        sample  307362   3.123 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.542           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.285           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.819           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.662           ms/op
ClientGrpc.listUser                       sample  239256   4.012 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.526           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.015           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.307           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.870           ms/op
