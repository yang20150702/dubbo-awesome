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
# Warmup Iteration   1: 3.842 ops/ms
# Warmup Iteration   2: 8.963 ops/ms
# Warmup Iteration   3: 10.015 ops/ms
Iteration   1: 10.389 ops/ms
Iteration   2: 10.344 ops/ms
Iteration   3: 10.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.396 ±(99.9%) 1.017 ops/ms [Average]
  (min, avg, max) = (10.344, 10.396, 10.455), stdev = 0.056
  CI (99.9%): [9.378, 11.413] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.922 ops/ms
# Warmup Iteration   2: 10.641 ops/ms
# Warmup Iteration   3: 11.017 ops/ms
Iteration   1: 10.989 ops/ms
Iteration   2: 11.144 ops/ms
Iteration   3: 10.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.037 ±(99.9%) 1.696 ops/ms [Average]
  (min, avg, max) = (10.977, 11.037, 11.144), stdev = 0.093
  CI (99.9%): [9.341, 12.733] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.002 ops/ms
# Warmup Iteration   2: 9.599 ops/ms
# Warmup Iteration   3: 10.152 ops/ms
Iteration   1: 10.416 ops/ms
Iteration   2: 10.279 ops/ms
Iteration   3: 10.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.331 ±(99.9%) 1.353 ops/ms [Average]
  (min, avg, max) = (10.279, 10.331, 10.416), stdev = 0.074
  CI (99.9%): [8.978, 11.684] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.619 ops/ms
# Warmup Iteration   2: 7.241 ops/ms
# Warmup Iteration   3: 7.755 ops/ms
Iteration   1: 7.791 ops/ms
Iteration   2: 7.843 ops/ms
Iteration   3: 7.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.850 ±(99.9%) 1.152 ops/ms [Average]
  (min, avg, max) = (7.791, 7.850, 7.916), stdev = 0.063
  CI (99.9%): [6.698, 9.002] (assumes normal distribution)


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.002 ms/op
Iteration   1: 3.085 ±(99.9%) 0.004 ms/op
Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
Iteration   3: 3.090 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.084 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (3.077, 3.084, 3.090), stdev = 0.007
  CI (99.9%): [2.960, 3.208] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.050 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.002 ms/op
Iteration   1: 2.901 ±(99.9%) 0.002 ms/op
Iteration   2: 2.924 ±(99.9%) 0.001 ms/op
Iteration   3: 2.902 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.909 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (2.901, 2.909, 2.924), stdev = 0.013
  CI (99.9%): [2.671, 3.147] (assumes normal distribution)


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
# Warmup Iteration   1: 4.461 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.003 ms/op
Iteration   1: 3.084 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
Iteration   3: 3.068 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (3.047, 3.066, 3.084), stdev = 0.018
  CI (99.9%): [2.729, 3.403] (assumes normal distribution)


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
# Warmup Iteration   1: 5.777 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.028 ms/op
Iteration   1: 4.003 ±(99.9%) 0.011 ms/op
Iteration   2: 4.018 ±(99.9%) 0.007 ms/op
Iteration   3: 4.004 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.009 ±(99.9%) 0.154 ms/op [Average]
  (min, avg, max) = (4.003, 4.009, 4.018), stdev = 0.008
  CI (99.9%): [3.855, 4.163] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.531 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.564 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  8.733 ms/op
                 createUser·p0.9999: 13.009 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.453 ms/op
                 createUser·p0.999:  10.291 ms/op
                 createUser·p0.9999: 16.613 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.331 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  8.069 ms/op
                 createUser·p0.9999: 20.580 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314944
  mean =      3.045 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22120 
    [ 2.500,  5.000) = 290999 
    [ 5.000,  7.500) = 1345 
    [ 7.500, 10.000) = 195 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.331 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      9.738 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     20.934 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  8.454 ms/op
                 existUser·p0.9999: 13.105 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   2: 2.934 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  7.037 ms/op
                 existUser·p0.9999: 14.914 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   3: 2.934 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.488 ms/op
                 existUser·p0.9999: 16.635 ms/op
                 existUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325895
  mean =      2.946 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 573 
    [ 1.250,  2.500) = 29868 
    [ 2.500,  3.750) = 285465 
    [ 3.750,  5.000) = 8960 
    [ 5.000,  6.250) = 443 
    [ 6.250,  7.500) = 302 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.258 ms/op
     p(99.9900) =     14.851 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 4.468 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  8.061 ms/op
                 getUser·p0.9999: 12.963 ms/op
                 getUser·p1.00:   13.484 ms/op

Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.348 ms/op
                 getUser·p0.9999: 14.402 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.615 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.590 ms/op
                 getUser·p0.9999: 17.870 ms/op
                 getUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312417
  mean =      3.074 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 841 
    [ 1.250,  2.500) = 18073 
    [ 2.500,  3.750) = 272229 
    [ 3.750,  5.000) = 19833 
    [ 5.000,  6.250) = 866 
    [ 6.250,  7.500) = 266 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.496 ms/op
     p(99.9900) =     16.200 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 5.779 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.063 ±(99.9%) 0.011 ms/op
Iteration   1: 4.071 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  14.384 ms/op
                 listUser·p0.9999: 17.044 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   2: 4.009 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  15.077 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.083 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  16.025 ms/op
                 listUser·p0.9999: 18.819 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236910
  mean =      4.054 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1746 
    [ 2.500,  5.000) = 212729 
    [ 5.000,  7.500) = 20872 
    [ 7.500, 10.000) = 1068 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     14.862 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.396 ± 1.017  ops/ms
ClientGrpc.existUser                       thrpt       3  11.037 ± 1.696  ops/ms
ClientGrpc.getUser                         thrpt       3  10.331 ± 1.353  ops/ms
ClientGrpc.listUser                        thrpt       3   7.850 ± 1.152  ops/ms
ClientGrpc.createUser                       avgt       3   3.084 ± 0.124   ms/op
ClientGrpc.existUser                        avgt       3   2.909 ± 0.238   ms/op
ClientGrpc.getUser                          avgt       3   3.066 ± 0.337   ms/op
ClientGrpc.listUser                         avgt       3   4.009 ± 0.154   ms/op
ClientGrpc.createUser                     sample  314944   3.045 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.331           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.738           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.169           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.004           ms/op
ClientGrpc.existUser                      sample  325895   2.946 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.864           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.258           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.851           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.105           ms/op
ClientGrpc.getUser                        sample  312417   3.074 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.564           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.496           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.200           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.022           ms/op
ClientGrpc.listUser                       sample  236910   4.054 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.051           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.862           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.071           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.446           ms/op
