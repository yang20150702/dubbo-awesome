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
# Warmup Iteration   1: 3.437 ops/ms
# Warmup Iteration   2: 7.048 ops/ms
# Warmup Iteration   3: 8.851 ops/ms
Iteration   1: 8.888 ops/ms
Iteration   2: 8.990 ops/ms
Iteration   3: 9.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.989 ±(99.9%) 1.823 ops/ms [Average]
  (min, avg, max) = (8.888, 8.989, 9.088), stdev = 0.100
  CI (99.9%): [7.166, 10.812] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.044 ops/ms
# Warmup Iteration   2: 9.040 ops/ms
# Warmup Iteration   3: 9.353 ops/ms
Iteration   1: 9.447 ops/ms
Iteration   2: 9.574 ops/ms
Iteration   3: 9.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.538 ±(99.9%) 1.442 ops/ms [Average]
  (min, avg, max) = (9.447, 9.538, 9.592), stdev = 0.079
  CI (99.9%): [8.095, 10.980] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.508 ops/ms
# Warmup Iteration   2: 8.472 ops/ms
# Warmup Iteration   3: 9.062 ops/ms
Iteration   1: 9.029 ops/ms
Iteration   2: 9.237 ops/ms
Iteration   3: 9.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.125 ±(99.9%) 1.918 ops/ms [Average]
  (min, avg, max) = (9.029, 9.125, 9.237), stdev = 0.105
  CI (99.9%): [7.207, 11.043] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.253 ops/ms
# Warmup Iteration   2: 6.410 ops/ms
# Warmup Iteration   3: 6.868 ops/ms
Iteration   1: 6.950 ops/ms
Iteration   2: 6.994 ops/ms
Iteration   3: 7.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.987 ±(99.9%) 0.617 ops/ms [Average]
  (min, avg, max) = (6.950, 6.987, 7.016), stdev = 0.034
  CI (99.9%): [6.370, 7.603] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.178 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.007 ms/op
Iteration   1: 3.541 ±(99.9%) 0.003 ms/op
Iteration   2: 3.513 ±(99.9%) 0.003 ms/op
Iteration   3: 3.505 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.520 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (3.505, 3.520, 3.541), stdev = 0.019
  CI (99.9%): [3.179, 3.860] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.028 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.003 ms/op
Iteration   1: 3.348 ±(99.9%) 0.002 ms/op
Iteration   2: 3.347 ±(99.9%) 0.003 ms/op
Iteration   3: 3.352 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.349 ±(99.9%) 0.049 ms/op [Average]
  (min, avg, max) = (3.347, 3.349, 3.352), stdev = 0.003
  CI (99.9%): [3.300, 3.399] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.140 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.003 ms/op
Iteration   1: 3.510 ±(99.9%) 0.002 ms/op
Iteration   2: 3.468 ±(99.9%) 0.004 ms/op
Iteration   3: 3.505 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.494 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (3.468, 3.494, 3.510), stdev = 0.023
  CI (99.9%): [3.071, 3.918] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.707 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.746 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.594 ±(99.9%) 0.015 ms/op
Iteration   1: 4.615 ±(99.9%) 0.025 ms/op
Iteration   2: 4.475 ±(99.9%) 0.016 ms/op
Iteration   3: 4.368 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.486 ±(99.9%) 2.258 ms/op [Average]
  (min, avg, max) = (4.368, 4.486, 4.615), stdev = 0.124
  CI (99.9%): [2.228, 6.744] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.383 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.008 ms/op
Iteration   1: 3.515 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.054 ms/op
                 createUser·p0.999:  10.977 ms/op
                 createUser·p0.9999: 16.971 ms/op
                 createUser·p1.00:   17.236 ms/op

Iteration   2: 3.472 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  8.744 ms/op
                 createUser·p0.9999: 17.386 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   3: 3.549 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  8.667 ms/op
                 createUser·p0.9999: 22.052 ms/op
                 createUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 273339
  mean =      3.512 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2839 
    [ 2.500,  5.000) = 267484 
    [ 5.000,  7.500) = 2377 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.071 ms/op
     p(99.9000) =      8.994 ms/op
     p(99.9900) =     19.683 ms/op
     p(99.9990) =     22.374 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.638 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.008 ms/op
Iteration   1: 3.402 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 19.523 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   2: 3.412 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  7.373 ms/op
                 existUser·p0.9999: 14.264 ms/op
                 existUser·p1.00:   16.695 ms/op

Iteration   3: 3.392 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   4.719 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 20.138 ms/op
                 existUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 282118
  mean =      3.402 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5582 
    [ 2.500,  5.000) = 274083 
    [ 5.000,  7.500) = 2021 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     19.457 ms/op
     p(99.9990) =     21.764 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.766 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.008 ms/op
Iteration   1: 3.512 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  9.608 ms/op
                 getUser·p0.9999: 14.631 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   2: 3.521 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  7.351 ms/op
                 getUser·p0.9999: 17.200 ms/op
                 getUser·p1.00:   17.400 ms/op

Iteration   3: 3.509 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  8.135 ms/op
                 getUser·p0.9999: 17.433 ms/op
                 getUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 273293
  mean =      3.514 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 6990 
    [ 2.500,  3.750) = 194118 
    [ 3.750,  5.000) = 68106 
    [ 5.000,  6.250) = 3184 
    [ 6.250,  7.500) = 405 
    [ 7.500,  8.750) = 182 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 72 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      8.302 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     18.036 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.210 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.901 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.599 ±(99.9%) 0.013 ms/op
Iteration   1: 4.545 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.324 ms/op
                 listUser·p0.99:   8.073 ms/op
                 listUser·p0.999:  15.335 ms/op
                 listUser·p0.9999: 23.458 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   2: 4.602 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  16.736 ms/op
                 listUser·p0.9999: 22.259 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   3: 4.739 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.988 ms/op
                 listUser·p0.95:   6.799 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  19.391 ms/op
                 listUser·p0.9999: 33.275 ms/op
                 listUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207484
  mean =      4.627 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 561 
    [ 2.500,  5.000) = 169237 
    [ 5.000,  7.500) = 33669 
    [ 7.500, 10.000) = 3473 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     32.645 ms/op
     p(99.9990) =     33.615 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.989 ± 1.823  ops/ms
ClientGrpc.existUser                       thrpt       3   9.538 ± 1.442  ops/ms
ClientGrpc.getUser                         thrpt       3   9.125 ± 1.918  ops/ms
ClientGrpc.listUser                        thrpt       3   6.987 ± 0.617  ops/ms
ClientGrpc.createUser                       avgt       3   3.520 ± 0.340   ms/op
ClientGrpc.existUser                        avgt       3   3.349 ± 0.049   ms/op
ClientGrpc.getUser                          avgt       3   3.494 ± 0.424   ms/op
ClientGrpc.listUser                         avgt       3   4.486 ± 2.258   ms/op
ClientGrpc.createUser                     sample  273339   3.512 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.824           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.465           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.071           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.994           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.683           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.512           ms/op
ClientGrpc.existUser                      sample  282118   3.402 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.854           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.882           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.633           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.457           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.118           ms/op
ClientGrpc.getUser                        sample  273293   3.514 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.695           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.100           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.341           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.302           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.170           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.464           ms/op
ClientGrpc.listUser                       sample  207484   4.627 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.268           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.465           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.744           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.645           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.751           ms/op
