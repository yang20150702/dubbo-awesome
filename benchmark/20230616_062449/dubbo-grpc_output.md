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
# Warmup Iteration   1: 2.288 ops/ms
# Warmup Iteration   2: 5.141 ops/ms
# Warmup Iteration   3: 6.601 ops/ms
Iteration   1: 6.687 ops/ms
Iteration   2: 7.041 ops/ms
Iteration   3: 7.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.926 ±(99.9%) 3.788 ops/ms [Average]
  (min, avg, max) = (6.687, 6.926, 7.051), stdev = 0.208
  CI (99.9%): [3.139, 10.714] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.309 ops/ms
# Warmup Iteration   2: 6.770 ops/ms
# Warmup Iteration   3: 7.355 ops/ms
Iteration   1: 7.698 ops/ms
Iteration   2: 7.424 ops/ms
Iteration   3: 7.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.635 ±(99.9%) 3.426 ops/ms [Average]
  (min, avg, max) = (7.424, 7.635, 7.783), stdev = 0.188
  CI (99.9%): [4.209, 11.061] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.138 ops/ms
# Warmup Iteration   2: 6.302 ops/ms
# Warmup Iteration   3: 6.933 ops/ms
Iteration   1: 6.936 ops/ms
Iteration   2: 6.963 ops/ms
Iteration   3: 6.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.918 ±(99.9%) 1.029 ops/ms [Average]
  (min, avg, max) = (6.854, 6.918, 6.963), stdev = 0.056
  CI (99.9%): [5.889, 7.946] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.647 ops/ms
# Warmup Iteration   2: 4.726 ops/ms
# Warmup Iteration   3: 5.544 ops/ms
Iteration   1: 5.569 ops/ms
Iteration   2: 5.529 ops/ms
Iteration   3: 5.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.572 ±(99.9%) 0.805 ops/ms [Average]
  (min, avg, max) = (5.529, 5.572, 5.617), stdev = 0.044
  CI (99.9%): [4.768, 6.377] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.654 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.877 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.513 ±(99.9%) 0.010 ms/op
Iteration   1: 4.601 ±(99.9%) 0.003 ms/op
Iteration   2: 4.495 ±(99.9%) 0.003 ms/op
Iteration   3: 4.554 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.550 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (4.495, 4.550, 4.601), stdev = 0.053
  CI (99.9%): [3.582, 5.518] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.891 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.687 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.537 ±(99.9%) 0.004 ms/op
Iteration   1: 4.235 ±(99.9%) 0.003 ms/op
Iteration   2: 4.349 ±(99.9%) 0.004 ms/op
Iteration   3: 4.352 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.312 ±(99.9%) 1.215 ms/op [Average]
  (min, avg, max) = (4.235, 4.312, 4.352), stdev = 0.067
  CI (99.9%): [3.097, 5.527] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.650 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.809 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.493 ±(99.9%) 0.009 ms/op
Iteration   1: 4.435 ±(99.9%) 0.005 ms/op
Iteration   2: 4.498 ±(99.9%) 0.004 ms/op
Iteration   3: 4.457 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.463 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (4.435, 4.463, 4.498), stdev = 0.032
  CI (99.9%): [3.885, 5.041] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.895 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 6.491 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.734 ±(99.9%) 0.011 ms/op
Iteration   1: 5.732 ±(99.9%) 0.021 ms/op
Iteration   2: 5.752 ±(99.9%) 0.026 ms/op
Iteration   3: 5.457 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.647 ±(99.9%) 3.012 ms/op [Average]
  (min, avg, max) = (5.457, 5.647, 5.752), stdev = 0.165
  CI (99.9%): [2.635, 8.659] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.177 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.968 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.654 ±(99.9%) 0.015 ms/op
Iteration   1: 4.450 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   4.366 ms/op
                 createUser·p0.90:   5.546 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   7.430 ms/op
                 createUser·p0.999:  13.702 ms/op
                 createUser·p0.9999: 20.994 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   2: 4.379 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  14.346 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 4.542 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   4.440 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   5.915 ms/op
                 createUser·p0.99:   7.668 ms/op
                 createUser·p0.999:  15.467 ms/op
                 createUser·p0.9999: 26.116 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215411
  mean =      4.456 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3812 
    [ 2.500,  5.000) = 164888 
    [ 5.000,  7.500) = 44882 
    [ 7.500, 10.000) = 1335 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     13.962 ms/op
     p(99.9900) =     25.276 ms/op
     p(99.9990) =     26.494 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.207 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.573 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.371 ±(99.9%) 0.011 ms/op
Iteration   1: 4.366 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   4.268 ms/op
                 existUser·p0.90:   5.390 ms/op
                 existUser·p0.95:   5.743 ms/op
                 existUser·p0.99:   7.004 ms/op
                 existUser·p0.999:  12.726 ms/op
                 existUser·p0.9999: 16.996 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   2: 4.141 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   4.026 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.603 ms/op
                 existUser·p0.99:   6.881 ms/op
                 existUser·p0.999:  14.824 ms/op
                 existUser·p0.9999: 34.490 ms/op
                 existUser·p1.00:   36.635 ms/op

Iteration   3: 4.063 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   3.965 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.284 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  12.977 ms/op
                 existUser·p0.9999: 20.320 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229205
  mean =      4.186 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4645 
    [ 2.500,  5.000) = 194648 
    [ 5.000,  7.500) = 28263 
    [ 7.500, 10.000) = 1138 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     13.268 ms/op
     p(99.9900) =     33.333 ms/op
     p(99.9990) =     36.531 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.943 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.756 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.474 ±(99.9%) 0.014 ms/op
Iteration   1: 4.391 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   5.792 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  11.603 ms/op
                 getUser·p0.9999: 30.103 ms/op
                 getUser·p1.00:   30.376 ms/op

Iteration   2: 4.333 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   6.718 ms/op
                 getUser·p0.999:  10.119 ms/op
                 getUser·p0.9999: 30.525 ms/op
                 getUser·p1.00:   31.785 ms/op

Iteration   3: 4.514 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   5.849 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  12.665 ms/op
                 getUser·p0.9999: 29.352 ms/op
                 getUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217574
  mean =      4.412 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3105 
    [ 2.500,  5.000) = 173411 
    [ 5.000,  7.500) = 39412 
    [ 7.500, 10.000) = 1319 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     11.803 ms/op
     p(99.9900) =     29.524 ms/op
     p(99.9990) =     31.484 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.202 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 6.159 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.706 ±(99.9%) 0.020 ms/op
Iteration   1: 5.725 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.673 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   10.224 ms/op
                 listUser·p0.999:  16.202 ms/op
                 listUser·p0.9999: 24.736 ms/op
                 listUser·p1.00:   25.494 ms/op

Iteration   2: 5.640 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   7.127 ms/op
                 listUser·p0.95:   8.151 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  18.782 ms/op
                 listUser·p0.9999: 19.725 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   3: 5.780 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.722 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   7.340 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.417 ms/op
                 listUser·p0.999:  21.758 ms/op
                 listUser·p0.9999: 26.405 ms/op
                 listUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168073
  mean =      5.714 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 47357 
    [ 5.000,  7.500) = 105669 
    [ 7.500, 10.000) = 12720 
    [10.000, 12.500) = 1715 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.673 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.356 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     18.507 ms/op
     p(99.9900) =     25.218 ms/op
     p(99.9990) =     27.217 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.926 ± 3.788  ops/ms
ClientGrpc.existUser                       thrpt       3   7.635 ± 3.426  ops/ms
ClientGrpc.getUser                         thrpt       3   6.918 ± 1.029  ops/ms
ClientGrpc.listUser                        thrpt       3   5.572 ± 0.805  ops/ms
ClientGrpc.createUser                       avgt       3   4.550 ± 0.968   ms/op
ClientGrpc.existUser                        avgt       3   4.312 ± 1.215   ms/op
ClientGrpc.getUser                          avgt       3   4.463 ± 0.578   ms/op
ClientGrpc.listUser                         avgt       3   5.647 ± 3.012   ms/op
ClientGrpc.createUser                     sample  215411   4.456 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.976           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.464           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.857           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.234           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.962           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.276           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.608           ms/op
ClientGrpc.existUser                      sample  229205   4.186 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.910           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.177           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.587           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.914           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.268           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.333           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          36.635           ms/op
ClientGrpc.getUser                        sample  217574   4.412 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.057           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.374           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.743           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.070           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.803           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.524           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.785           ms/op
ClientGrpc.listUser                       sample  168073   5.714 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.673           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.324           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.356           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.387           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.507           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.218           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.329           ms/op
