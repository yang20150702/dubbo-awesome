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
# Warmup Iteration   1: 4.162 ops/ms
# Warmup Iteration   2: 9.075 ops/ms
# Warmup Iteration   3: 10.097 ops/ms
Iteration   1: 10.512 ops/ms
Iteration   2: 10.286 ops/ms
Iteration   3: 10.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.339 ±(99.9%) 2.815 ops/ms [Average]
  (min, avg, max) = (10.217, 10.339, 10.512), stdev = 0.154
  CI (99.9%): [7.523, 13.154] (assumes normal distribution)


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
# Warmup Iteration   1: 7.244 ops/ms
# Warmup Iteration   2: 10.241 ops/ms
# Warmup Iteration   3: 10.964 ops/ms
Iteration   1: 10.941 ops/ms
Iteration   2: 10.805 ops/ms
Iteration   3: 11.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.001 ±(99.9%) 4.222 ops/ms [Average]
  (min, avg, max) = (10.805, 11.001, 11.256), stdev = 0.231
  CI (99.9%): [6.779, 15.222] (assumes normal distribution)


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
# Warmup Iteration   1: 6.460 ops/ms
# Warmup Iteration   2: 10.140 ops/ms
# Warmup Iteration   3: 10.231 ops/ms
Iteration   1: 10.340 ops/ms
Iteration   2: 10.246 ops/ms
Iteration   3: 10.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.293 ±(99.9%) 0.854 ops/ms [Average]
  (min, avg, max) = (10.246, 10.293, 10.340), stdev = 0.047
  CI (99.9%): [9.438, 11.147] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.450 ops/ms
# Warmup Iteration   2: 7.674 ops/ms
# Warmup Iteration   3: 7.728 ops/ms
Iteration   1: 7.815 ops/ms
Iteration   2: 7.879 ops/ms
Iteration   3: 7.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.874 ±(99.9%) 1.028 ops/ms [Average]
  (min, avg, max) = (7.815, 7.874, 7.928), stdev = 0.056
  CI (99.9%): [6.846, 8.902] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.496 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.002 ms/op
Iteration   1: 3.099 ±(99.9%) 0.002 ms/op
Iteration   2: 3.133 ±(99.9%) 0.004 ms/op
Iteration   3: 3.108 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.113 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (3.099, 3.113, 3.133), stdev = 0.017
  CI (99.9%): [2.796, 3.431] (assumes normal distribution)


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.003 ms/op
Iteration   1: 2.976 ±(99.9%) 0.004 ms/op
Iteration   2: 2.967 ±(99.9%) 0.003 ms/op
Iteration   3: 2.971 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.971 ±(99.9%) 0.080 ms/op [Average]
  (min, avg, max) = (2.967, 2.971, 2.976), stdev = 0.004
  CI (99.9%): [2.891, 3.051] (assumes normal distribution)


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
# Warmup Iteration   1: 4.414 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.004 ms/op
Iteration   1: 3.166 ±(99.9%) 0.003 ms/op
Iteration   2: 3.136 ±(99.9%) 0.004 ms/op
Iteration   3: 3.135 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.146 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.135, 3.146, 3.166), stdev = 0.017
  CI (99.9%): [2.829, 3.462] (assumes normal distribution)


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
# Warmup Iteration   1: 5.990 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.034 ms/op
Iteration   1: 4.136 ±(99.9%) 0.023 ms/op
Iteration   2: 4.059 ±(99.9%) 0.023 ms/op
Iteration   3: 4.053 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.083 ±(99.9%) 0.846 ms/op [Average]
  (min, avg, max) = (4.053, 4.083, 4.136), stdev = 0.046
  CI (99.9%): [3.237, 4.928] (assumes normal distribution)


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
# Warmup Iteration   1: 4.388 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.006 ms/op
Iteration   1: 3.121 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.465 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.678 ms/op
                 createUser·p0.9999: 15.741 ms/op
                 createUser·p1.00:   16.237 ms/op

Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.307 ms/op
                 createUser·p0.9999: 15.440 ms/op
                 createUser·p1.00:   16.105 ms/op

Iteration   3: 3.137 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.601 ms/op
                 createUser·p0.9999: 19.038 ms/op
                 createUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308757
  mean =      3.110 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 283 
    [ 1.250,  2.500) = 12410 
    [ 2.500,  3.750) = 278099 
    [ 3.750,  5.000) = 16769 
    [ 5.000,  6.250) = 624 
    [ 6.250,  7.500) = 259 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 97 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.520 ms/op
     p(99.9900) =     18.059 ms/op
     p(99.9990) =     19.360 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
Iteration   1: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  7.522 ms/op
                 existUser·p0.9999: 19.272 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.586 ms/op
                 existUser·p0.9999: 14.605 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.539 ms/op
                 existUser·p0.9999: 17.178 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321613
  mean =      2.986 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 801 
    [ 1.250,  2.500) = 31819 
    [ 2.500,  3.750) = 274639 
    [ 3.750,  5.000) = 13079 
    [ 5.000,  6.250) = 697 
    [ 6.250,  7.500) = 328 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.037 ms/op
     p(99.9900) =     18.426 ms/op
     p(99.9990) =     19.574 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 4.258 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
Iteration   1: 3.148 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  8.090 ms/op
                 getUser·p0.9999: 13.629 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   2: 3.162 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.398 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  8.310 ms/op
                 getUser·p0.9999: 14.348 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.989 ms/op
                 getUser·p0.9999: 19.492 ms/op
                 getUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304362
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14116 
    [ 2.500,  5.000) = 288373 
    [ 5.000,  7.500) = 1446 
    [ 7.500, 10.000) = 235 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      8.184 ms/op
     p(99.9900) =     19.122 ms/op
     p(99.9990) =     20.228 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 5.701 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.013 ms/op
Iteration   1: 4.130 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  21.154 ms/op
                 listUser·p0.9999: 23.331 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 4.067 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  16.360 ms/op
                 listUser·p0.9999: 27.865 ms/op
                 listUser·p1.00:   30.081 ms/op

Iteration   3: 4.104 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.087 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 20.794 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234253
  mean =      4.100 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2093 
    [ 2.500,  5.000) = 205065 
    [ 5.000,  7.500) = 25331 
    [ 7.500, 10.000) = 1220 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     18.669 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     29.458 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.339 ± 2.815  ops/ms
ClientGrpc.existUser                       thrpt       3  11.001 ± 4.222  ops/ms
ClientGrpc.getUser                         thrpt       3  10.293 ± 0.854  ops/ms
ClientGrpc.listUser                        thrpt       3   7.874 ± 1.028  ops/ms
ClientGrpc.createUser                       avgt       3   3.113 ± 0.317   ms/op
ClientGrpc.existUser                        avgt       3   2.971 ± 0.080   ms/op
ClientGrpc.getUser                          avgt       3   3.146 ± 0.316   ms/op
ClientGrpc.listUser                         avgt       3   4.083 ± 0.846   ms/op
ClientGrpc.createUser                     sample  308757   3.110 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.465           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.520           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.059           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.464           ms/op
ClientGrpc.existUser                      sample  321613   2.986 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.848           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.037           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.426           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.628           ms/op
ClientGrpc.getUser                        sample  304362   3.155 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.398           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.969           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.184           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.122           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.972           ms/op
ClientGrpc.listUser                       sample  234253   4.100 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.008           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.669           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.099           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.081           ms/op
