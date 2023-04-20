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
# Warmup Iteration   1: 2.647 ops/ms
# Warmup Iteration   2: 6.253 ops/ms
# Warmup Iteration   3: 7.592 ops/ms
Iteration   1: 7.584 ops/ms
Iteration   2: 7.507 ops/ms
Iteration   3: 7.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.665 ±(99.9%) 3.833 ops/ms [Average]
  (min, avg, max) = (7.507, 7.665, 7.903), stdev = 0.210
  CI (99.9%): [3.832, 11.498] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.892 ops/ms
# Warmup Iteration   2: 7.783 ops/ms
# Warmup Iteration   3: 8.210 ops/ms
Iteration   1: 8.174 ops/ms
Iteration   2: 8.338 ops/ms
Iteration   3: 8.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.328 ±(99.9%) 2.733 ops/ms [Average]
  (min, avg, max) = (8.174, 8.328, 8.473), stdev = 0.150
  CI (99.9%): [5.596, 11.061] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.544 ops/ms
# Warmup Iteration   2: 7.134 ops/ms
# Warmup Iteration   3: 7.855 ops/ms
Iteration   1: 7.822 ops/ms
Iteration   2: 7.907 ops/ms
Iteration   3: 7.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.878 ±(99.9%) 0.882 ops/ms [Average]
  (min, avg, max) = (7.822, 7.878, 7.907), stdev = 0.048
  CI (99.9%): [6.996, 8.760] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.863 ops/ms
# Warmup Iteration   2: 5.535 ops/ms
# Warmup Iteration   3: 5.976 ops/ms
Iteration   1: 6.152 ops/ms
Iteration   2: 6.104 ops/ms
Iteration   3: 6.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.102 ±(99.9%) 0.923 ops/ms [Average]
  (min, avg, max) = (6.050, 6.102, 6.152), stdev = 0.051
  CI (99.9%): [5.179, 7.025] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.140 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.003 ms/op
Iteration   1: 4.209 ±(99.9%) 0.004 ms/op
Iteration   2: 3.951 ±(99.9%) 0.005 ms/op
Iteration   3: 4.052 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.071 ±(99.9%) 2.368 ms/op [Average]
  (min, avg, max) = (3.951, 4.071, 4.209), stdev = 0.130
  CI (99.9%): [1.702, 6.439] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.524 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.005 ms/op
Iteration   1: 3.823 ±(99.9%) 0.003 ms/op
Iteration   2: 3.664 ±(99.9%) 0.003 ms/op
Iteration   3: 4.002 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.830 ±(99.9%) 3.088 ms/op [Average]
  (min, avg, max) = (3.664, 3.830, 4.002), stdev = 0.169
  CI (99.9%): [0.741, 6.918] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.226 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.462 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.314 ±(99.9%) 0.008 ms/op
Iteration   1: 4.039 ±(99.9%) 0.020 ms/op
Iteration   2: 4.091 ±(99.9%) 0.004 ms/op
Iteration   3: 4.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.076 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (4.039, 4.076, 4.098), stdev = 0.033
  CI (99.9%): [3.483, 4.670] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.272 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.392 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.172 ±(99.9%) 0.016 ms/op
Iteration   1: 5.206 ±(99.9%) 0.018 ms/op
Iteration   2: 5.067 ±(99.9%) 0.018 ms/op
Iteration   3: 5.044 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.105 ±(99.9%) 1.601 ms/op [Average]
  (min, avg, max) = (5.044, 5.105, 5.206), stdev = 0.088
  CI (99.9%): [3.505, 6.706] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.342 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.319 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.011 ms/op
Iteration   1: 4.106 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   4.026 ms/op
                 createUser·p0.90:   5.136 ms/op
                 createUser·p0.95:   5.480 ms/op
                 createUser·p0.99:   6.857 ms/op
                 createUser·p0.999:  12.419 ms/op
                 createUser·p0.9999: 15.830 ms/op
                 createUser·p1.00:   21.365 ms/op

Iteration   2: 3.965 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  10.813 ms/op
                 createUser·p0.9999: 16.972 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   3: 4.072 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   5.382 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  12.747 ms/op
                 createUser·p0.9999: 19.380 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 237216
  mean =      4.047 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6487 
    [ 2.500,  5.000) = 204950 
    [ 5.000,  7.500) = 24678 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     11.596 ms/op
     p(99.9900) =     18.696 ms/op
     p(99.9990) =     20.816 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.704 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.009 ms/op
Iteration   1: 3.923 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.719 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 16.332 ms/op
                 existUser·p1.00:   16.433 ms/op

Iteration   2: 3.777 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  13.047 ms/op
                 existUser·p0.9999: 25.070 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   3: 3.801 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  9.517 ms/op
                 existUser·p0.9999: 24.661 ms/op
                 existUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 250316
  mean =      3.833 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8573 
    [ 2.500,  5.000) = 229339 
    [ 5.000,  7.500) = 11241 
    [ 7.500, 10.000) = 781 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     11.677 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     25.493 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.354 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.356 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.012 ms/op
Iteration   1: 4.157 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.562 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  11.091 ms/op
                 getUser·p0.9999: 25.002 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   2: 4.168 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.046 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  14.387 ms/op
                 getUser·p0.9999: 26.563 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   3: 3.896 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  10.158 ms/op
                 getUser·p0.9999: 26.804 ms/op
                 getUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235844
  mean =      4.070 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4646 
    [ 2.500,  5.000) = 208589 
    [ 5.000,  7.500) = 21252 
    [ 7.500, 10.000) = 1010 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 81 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     12.656 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     27.616 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 6.949 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.662 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.259 ±(99.9%) 0.017 ms/op
Iteration   1: 5.217 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   4.997 ms/op
                 listUser·p0.90:   6.685 ms/op
                 listUser·p0.95:   7.578 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  17.943 ms/op
                 listUser·p0.9999: 20.836 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   2: 5.227 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   5.022 ms/op
                 listUser·p0.90:   6.627 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  17.043 ms/op
                 listUser·p0.9999: 22.700 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   3: 5.190 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   5.014 ms/op
                 listUser·p0.90:   6.283 ms/op
                 listUser·p0.95:   7.238 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 30.164 ms/op
                 listUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184333
  mean =      5.211 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 224 
    [ 2.500,  5.000) = 91136 
    [ 5.000,  7.500) = 83596 
    [ 7.500, 10.000) = 8069 
    [10.000, 12.500) = 880 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.528 ms/op
     p(99.0000) =      9.514 ms/op
     p(99.9000) =     18.077 ms/op
     p(99.9900) =     28.932 ms/op
     p(99.9990) =     30.802 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.665 ± 3.833  ops/ms
ClientGrpc.existUser                       thrpt       3   8.328 ± 2.733  ops/ms
ClientGrpc.getUser                         thrpt       3   7.878 ± 0.882  ops/ms
ClientGrpc.listUser                        thrpt       3   6.102 ± 0.923  ops/ms
ClientGrpc.createUser                       avgt       3   4.071 ± 2.368   ms/op
ClientGrpc.existUser                        avgt       3   3.830 ± 3.088   ms/op
ClientGrpc.getUser                          avgt       3   4.076 ± 0.594   ms/op
ClientGrpc.listUser                         avgt       3   5.105 ± 1.601   ms/op
ClientGrpc.createUser                     sample  237216   4.047 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.833           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.463           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.596           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.696           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.430           ms/op
ClientGrpc.existUser                      sample  250316   3.833 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.750           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.997           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.349           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.677           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.609           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.657           ms/op
ClientGrpc.getUser                        sample  235844   4.070 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.840           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.317           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.636           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.656           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.542           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.754           ms/op
ClientGrpc.listUser                       sample  184333   5.211 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.198           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.528           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.514           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.077           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.932           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.802           ms/op
