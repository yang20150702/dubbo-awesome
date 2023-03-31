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
# Warmup Iteration   1: 4.825 ops/ms
# Warmup Iteration   2: 9.940 ops/ms
# Warmup Iteration   3: 10.768 ops/ms
Iteration   1: 11.379 ops/ms
Iteration   2: 11.355 ops/ms
Iteration   3: 11.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  11.396 ±(99.9%) 0.952 ops/ms [Average]
  (min, avg, max) = (11.355, 11.396, 11.455), stdev = 0.052
  CI (99.9%): [10.444, 12.348] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.661 ops/ms
# Warmup Iteration   2: 10.916 ops/ms
# Warmup Iteration   3: 11.145 ops/ms
Iteration   1: 11.521 ops/ms
Iteration   2: 11.599 ops/ms
Iteration   3: 11.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.533 ±(99.9%) 1.104 ops/ms [Average]
  (min, avg, max) = (11.480, 11.533, 11.599), stdev = 0.061
  CI (99.9%): [10.430, 12.637] (assumes normal distribution)


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
# Warmup Iteration   1: 6.648 ops/ms
# Warmup Iteration   2: 10.630 ops/ms
# Warmup Iteration   3: 10.888 ops/ms
Iteration   1: 11.113 ops/ms
Iteration   2: 10.628 ops/ms
Iteration   3: 10.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.719 ±(99.9%) 6.508 ops/ms [Average]
  (min, avg, max) = (10.417, 10.719, 11.113), stdev = 0.357
  CI (99.9%): [4.211, 17.227] (assumes normal distribution)


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
# Warmup Iteration   1: 5.298 ops/ms
# Warmup Iteration   2: 7.799 ops/ms
# Warmup Iteration   3: 7.998 ops/ms
Iteration   1: 8.183 ops/ms
Iteration   2: 8.337 ops/ms
Iteration   3: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.223 ±(99.9%) 1.829 ops/ms [Average]
  (min, avg, max) = (8.149, 8.223, 8.337), stdev = 0.100
  CI (99.9%): [6.394, 10.052] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.413 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.002 ms/op
Iteration   1: 3.074 ±(99.9%) 0.004 ms/op
Iteration   2: 3.015 ±(99.9%) 0.002 ms/op
Iteration   3: 2.989 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.026 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (2.989, 3.026, 3.074), stdev = 0.043
  CI (99.9%): [2.237, 3.815] (assumes normal distribution)


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
# Warmup Iteration   1: 3.453 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.831 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.719 ±(99.9%) 0.001 ms/op
Iteration   1: 2.824 ±(99.9%) 0.001 ms/op
Iteration   2: 2.716 ±(99.9%) 0.002 ms/op
Iteration   3: 2.681 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.740 ±(99.9%) 1.365 ms/op [Average]
  (min, avg, max) = (2.681, 2.740, 2.824), stdev = 0.075
  CI (99.9%): [1.376, 4.105] (assumes normal distribution)


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.916 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.002 ms/op
Iteration   1: 2.841 ±(99.9%) 0.002 ms/op
Iteration   2: 2.926 ±(99.9%) 0.003 ms/op
Iteration   3: 2.802 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.856 ±(99.9%) 1.156 ms/op [Average]
  (min, avg, max) = (2.802, 2.856, 2.926), stdev = 0.063
  CI (99.9%): [1.700, 4.012] (assumes normal distribution)


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
# Warmup Iteration   1: 5.010 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.800 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.027 ms/op
Iteration   1: 3.768 ±(99.9%) 0.017 ms/op
Iteration   2: 3.688 ±(99.9%) 0.011 ms/op
Iteration   3: 3.693 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.717 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (3.688, 3.717, 3.768), stdev = 0.045
  CI (99.9%): [2.900, 4.533] (assumes normal distribution)


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
# Warmup Iteration   1: 4.118 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.936 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.830 ±(99.9%) 0.006 ms/op
Iteration   1: 2.893 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   2.859 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   3.949 ms/op
                 createUser·p0.999:  7.032 ms/op
                 createUser·p0.9999: 15.416 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   2: 2.882 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.554 ms/op
                 createUser·p0.50:   2.871 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.428 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  6.884 ms/op
                 createUser·p0.9999: 13.137 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   3: 2.839 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   2.814 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   3.424 ms/op
                 createUser·p0.99:   4.129 ms/op
                 createUser·p0.999:  7.107 ms/op
                 createUser·p0.9999: 29.819 ms/op
                 createUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 334193
  mean =      2.871 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53645 
    [ 2.500,  5.000) = 279580 
    [ 5.000,  7.500) = 682 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      3.985 ms/op
     p(99.9000) =      7.021 ms/op
     p(99.9900) =     22.727 ms/op
     p(99.9990) =     29.819 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 3.544 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.888 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.762 ±(99.9%) 0.005 ms/op
Iteration   1: 2.824 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 12.435 ms/op
                 existUser·p1.00:   12.730 ms/op

Iteration   2: 2.786 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   2.769 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   3.940 ms/op
                 existUser·p0.999:  9.654 ms/op
                 existUser·p0.9999: 14.001 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   3: 2.768 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.740 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.318 ms/op
                 existUser·p0.99:   3.813 ms/op
                 existUser·p0.999:  8.995 ms/op
                 existUser·p0.9999: 25.228 ms/op
                 existUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 343536
  mean =      2.792 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72371 
    [ 2.500,  5.000) = 270185 
    [ 5.000,  7.500) = 626 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.777 ms/op
     p(90.0000) =      3.228 ms/op
     p(95.0000) =      3.375 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      8.004 ms/op
     p(99.9900) =     24.794 ms/op
     p(99.9990) =     25.479 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.008 ms/op
Iteration   1: 2.910 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   2.879 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  8.684 ms/op
                 getUser·p0.9999: 15.106 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.300 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.352 ms/op
                 getUser·p0.9999: 14.647 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   3: 2.881 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   2.843 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.578 ms/op
                 getUser·p0.9999: 18.311 ms/op
                 getUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 328667
  mean =      2.919 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 534 
    [ 1.250,  2.500) = 54260 
    [ 2.500,  3.750) = 260222 
    [ 3.750,  5.000) = 12497 
    [ 5.000,  6.250) = 520 
    [ 6.250,  7.500) = 295 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.300 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.602 ms/op
     p(99.9900) =     16.440 ms/op
     p(99.9990) =     18.593 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 4.417 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.930 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.011 ms/op
Iteration   1: 3.639 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.989 ms/op
                 listUser·p0.50:   3.486 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 3.781 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.607 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  16.487 ms/op
                 listUser·p0.9999: 29.590 ms/op
                 listUser·p1.00:   29.950 ms/op

Iteration   3: 3.710 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   3.531 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  16.124 ms/op
                 listUser·p0.9999: 22.118 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 258957
  mean =      3.709 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3945 
    [ 2.500,  5.000) = 237949 
    [ 5.000,  7.500) = 16135 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     25.402 ms/op
     p(99.9990) =     29.840 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  11.396 ± 0.952  ops/ms
ClientGrpc.existUser                       thrpt       3  11.533 ± 1.104  ops/ms
ClientGrpc.getUser                         thrpt       3  10.719 ± 6.508  ops/ms
ClientGrpc.listUser                        thrpt       3   8.223 ± 1.829  ops/ms
ClientGrpc.createUser                       avgt       3   3.026 ± 0.789   ms/op
ClientGrpc.existUser                        avgt       3   2.740 ± 1.365   ms/op
ClientGrpc.getUser                          avgt       3   2.856 ± 1.156   ms/op
ClientGrpc.listUser                         avgt       3   3.717 ± 0.817   ms/op
ClientGrpc.createUser                     sample  334193   2.871 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.554           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.851           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.322           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           3.985           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.021           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.727           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.852           ms/op
ClientGrpc.existUser                      sample  343536   2.792 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.590           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.777           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.228           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.004           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.794           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.723           ms/op
ClientGrpc.getUser                        sample  328667   2.919 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.300           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.892           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.602           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.440           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.595           ms/op
ClientGrpc.listUser                       sample  258957   3.709 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.607           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.539           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.554           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.155           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.402           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.950           ms/op
