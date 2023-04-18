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
# Warmup Iteration   1: 4.329 ops/ms
# Warmup Iteration   2: 9.460 ops/ms
# Warmup Iteration   3: 10.228 ops/ms
Iteration   1: 10.613 ops/ms
Iteration   2: 10.521 ops/ms
Iteration   3: 10.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.591 ±(99.9%) 1.147 ops/ms [Average]
  (min, avg, max) = (10.521, 10.591, 10.641), stdev = 0.063
  CI (99.9%): [9.444, 11.738] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.754 ops/ms
# Warmup Iteration   2: 10.675 ops/ms
# Warmup Iteration   3: 10.878 ops/ms
Iteration   1: 10.847 ops/ms
Iteration   2: 11.087 ops/ms
Iteration   3: 10.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.958 ±(99.9%) 2.205 ops/ms [Average]
  (min, avg, max) = (10.847, 10.958, 11.087), stdev = 0.121
  CI (99.9%): [8.754, 13.163] (assumes normal distribution)


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
# Warmup Iteration   1: 6.919 ops/ms
# Warmup Iteration   2: 10.293 ops/ms
# Warmup Iteration   3: 10.464 ops/ms
Iteration   1: 10.520 ops/ms
Iteration   2: 10.566 ops/ms
Iteration   3: 10.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.526 ±(99.9%) 0.675 ops/ms [Average]
  (min, avg, max) = (10.492, 10.526, 10.566), stdev = 0.037
  CI (99.9%): [9.851, 11.201] (assumes normal distribution)


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
# Warmup Iteration   1: 6.070 ops/ms
# Warmup Iteration   2: 7.819 ops/ms
# Warmup Iteration   3: 8.236 ops/ms
Iteration   1: 8.220 ops/ms
Iteration   2: 8.476 ops/ms
Iteration   3: 8.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.363 ±(99.9%) 2.381 ops/ms [Average]
  (min, avg, max) = (8.220, 8.363, 8.476), stdev = 0.131
  CI (99.9%): [5.982, 10.744] (assumes normal distribution)


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.003 ms/op
Iteration   1: 3.016 ±(99.9%) 0.002 ms/op
Iteration   2: 3.126 ±(99.9%) 0.001 ms/op
Iteration   3: 3.026 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.056 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.016, 3.056, 3.126), stdev = 0.061
  CI (99.9%): [1.944, 4.167] (assumes normal distribution)


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.005 ms/op
Iteration   1: 2.990 ±(99.9%) 0.002 ms/op
Iteration   2: 2.924 ±(99.9%) 0.006 ms/op
Iteration   3: 2.896 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.936 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (2.896, 2.936, 2.990), stdev = 0.048
  CI (99.9%): [2.058, 3.815] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.029 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.003 ms/op
Iteration   1: 3.034 ±(99.9%) 0.003 ms/op
Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
Iteration   3: 3.070 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.038 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (3.011, 3.038, 3.070), stdev = 0.030
  CI (99.9%): [2.498, 3.579] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.530 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.032 ms/op
Iteration   1: 3.949 ±(99.9%) 0.032 ms/op
Iteration   2: 4.478 ±(99.9%) 0.047 ms/op
Iteration   3: 4.472 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.300 ±(99.9%) 5.535 ms/op [Average]
  (min, avg, max) = (3.949, 4.300, 4.478), stdev = 0.303
  CI (99.9%): [≈ 0, 9.835] (assumes normal distribution)


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
# Warmup Iteration   1: 4.884 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.516 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  9.633 ms/op
                 createUser·p0.9999: 16.253 ms/op
                 createUser·p1.00:   16.548 ms/op

Iteration   2: 3.043 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  8.212 ms/op
                 createUser·p0.9999: 19.819 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  10.617 ms/op
                 createUser·p0.9999: 17.203 ms/op
                 createUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316560
  mean =      3.032 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24888 
    [ 2.500,  5.000) = 289985 
    [ 5.000,  7.500) = 1203 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      9.051 ms/op
     p(99.9900) =     18.831 ms/op
     p(99.9990) =     20.278 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 3.638 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.817 ±(99.9%) 0.007 ms/op
Iteration   1: 2.889 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.386 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   4.086 ms/op
                 existUser·p0.999:  6.685 ms/op
                 existUser·p0.9999: 12.074 ms/op
                 existUser·p1.00:   12.403 ms/op

Iteration   2: 2.890 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  7.471 ms/op
                 existUser·p0.9999: 13.843 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   3: 2.892 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.462 ms/op
                 existUser·p0.9999: 15.482 ms/op
                 existUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332071
  mean =      2.890 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2736 
    [ 1.250,  2.500) = 33454 
    [ 2.500,  3.750) = 286326 
    [ 3.750,  5.000) = 8306 
    [ 5.000,  6.250) = 788 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.386 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      6.921 ms/op
     p(99.9900) =     15.188 ms/op
     p(99.9990) =     15.778 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  8.133 ms/op
                 getUser·p0.9999: 11.598 ms/op
                 getUser·p1.00:   12.042 ms/op

Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.069 ms/op
                 getUser·p0.9999: 20.166 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.409 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.504 ms/op
                 getUser·p0.9999: 15.022 ms/op
                 getUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317385
  mean =      3.025 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22061 
    [ 2.500,  5.000) = 294181 
    [ 5.000,  7.500) = 848 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.409 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.250 ms/op
     p(99.9900) =     15.016 ms/op
     p(99.9990) =     20.442 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 4.901 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.010 ms/op
Iteration   1: 3.801 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  12.499 ms/op
                 listUser·p0.9999: 14.994 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 3.888 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  15.687 ms/op
                 listUser·p0.9999: 24.692 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   3: 3.809 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.292 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.873 ms/op
                 listUser·p0.9999: 22.124 ms/op
                 listUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250525
  mean =      3.832 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4073 
    [ 2.500,  5.000) = 226457 
    [ 5.000,  7.500) = 19060 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.292 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     14.402 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     24.920 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.591 ± 1.147  ops/ms
ClientGrpc.existUser                       thrpt       3  10.958 ± 2.205  ops/ms
ClientGrpc.getUser                         thrpt       3  10.526 ± 0.675  ops/ms
ClientGrpc.listUser                        thrpt       3   8.363 ± 2.381  ops/ms
ClientGrpc.createUser                       avgt       3   3.056 ± 1.112   ms/op
ClientGrpc.existUser                        avgt       3   2.936 ± 0.878   ms/op
ClientGrpc.getUser                          avgt       3   3.038 ± 0.541   ms/op
ClientGrpc.listUser                         avgt       3   4.300 ± 5.535   ms/op
ClientGrpc.createUser                     sample  316560   3.032 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.598           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.051           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.831           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.349           ms/op
ClientGrpc.existUser                      sample  332071   2.890 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.386           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.921           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.188           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.892           ms/op
ClientGrpc.getUser                        sample  317385   3.025 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.409           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.250           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.016           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.611           ms/op
ClientGrpc.listUser                       sample  250525   3.832 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.292           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.402           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.774           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.936           ms/op
