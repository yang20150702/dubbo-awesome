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
# Warmup Iteration   1: 4.209 ops/ms
# Warmup Iteration   2: 8.822 ops/ms
# Warmup Iteration   3: 9.895 ops/ms
Iteration   1: 10.132 ops/ms
Iteration   2: 10.382 ops/ms
Iteration   3: 9.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.166 ±(99.9%) 3.669 ops/ms [Average]
  (min, avg, max) = (9.984, 10.166, 10.382), stdev = 0.201
  CI (99.9%): [6.497, 13.835] (assumes normal distribution)


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
# Warmup Iteration   1: 7.478 ops/ms
# Warmup Iteration   2: 10.254 ops/ms
# Warmup Iteration   3: 10.172 ops/ms
Iteration   1: 10.509 ops/ms
Iteration   2: 10.669 ops/ms
Iteration   3: 10.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.650 ±(99.9%) 2.419 ops/ms [Average]
  (min, avg, max) = (10.509, 10.650, 10.772), stdev = 0.133
  CI (99.9%): [8.231, 13.069] (assumes normal distribution)


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
# Warmup Iteration   1: 6.655 ops/ms
# Warmup Iteration   2: 10.083 ops/ms
# Warmup Iteration   3: 10.125 ops/ms
Iteration   1: 10.028 ops/ms
Iteration   2: 10.132 ops/ms
Iteration   3: 10.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.119 ±(99.9%) 1.546 ops/ms [Average]
  (min, avg, max) = (10.028, 10.119, 10.196), stdev = 0.085
  CI (99.9%): [8.573, 11.665] (assumes normal distribution)


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
# Warmup Iteration   1: 5.428 ops/ms
# Warmup Iteration   2: 7.669 ops/ms
# Warmup Iteration   3: 7.662 ops/ms
Iteration   1: 7.732 ops/ms
Iteration   2: 7.926 ops/ms
Iteration   3: 8.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.892 ±(99.9%) 2.660 ops/ms [Average]
  (min, avg, max) = (7.732, 7.892, 8.018), stdev = 0.146
  CI (99.9%): [5.232, 10.552] (assumes normal distribution)


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
# Warmup Iteration   1: 4.357 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.003 ms/op
Iteration   1: 3.193 ±(99.9%) 0.002 ms/op
Iteration   2: 3.096 ±(99.9%) 0.003 ms/op
Iteration   3: 3.187 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.159 ±(99.9%) 0.995 ms/op [Average]
  (min, avg, max) = (3.096, 3.159, 3.193), stdev = 0.055
  CI (99.9%): [2.163, 4.154] (assumes normal distribution)


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
# Warmup Iteration   1: 4.171 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.003 ms/op
Iteration   1: 3.014 ±(99.9%) 0.002 ms/op
Iteration   2: 3.102 ±(99.9%) 0.001 ms/op
Iteration   3: 3.042 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.052 ±(99.9%) 0.822 ms/op [Average]
  (min, avg, max) = (3.014, 3.052, 3.102), stdev = 0.045
  CI (99.9%): [2.230, 3.874] (assumes normal distribution)


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.003 ms/op
Iteration   1: 3.239 ±(99.9%) 0.002 ms/op
Iteration   2: 3.178 ±(99.9%) 0.003 ms/op
Iteration   3: 3.135 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.184 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (3.135, 3.184, 3.239), stdev = 0.052
  CI (99.9%): [2.236, 4.132] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.677 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.280 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.030 ms/op
Iteration   1: 4.110 ±(99.9%) 0.032 ms/op
Iteration   2: 4.159 ±(99.9%) 0.012 ms/op
Iteration   3: 4.016 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.095 ±(99.9%) 1.333 ms/op [Average]
  (min, avg, max) = (4.016, 4.095, 4.159), stdev = 0.073
  CI (99.9%): [2.762, 5.428] (assumes normal distribution)


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
# Warmup Iteration   1: 4.436 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.007 ms/op
Iteration   1: 3.210 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   4.397 ms/op
                 createUser·p0.999:  7.867 ms/op
                 createUser·p0.9999: 13.666 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   2: 3.153 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.307 ms/op
                 createUser·p0.9999: 14.664 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   3: 3.129 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  13.279 ms/op
                 createUser·p0.9999: 19.588 ms/op
                 createUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303316
  mean =      3.164 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25028 
    [ 2.500,  5.000) = 277164 
    [ 5.000,  7.500) = 674 
    [ 7.500, 10.000) = 137 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =     10.230 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     20.019 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 4.118 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.962 ms/op
                 existUser·p0.9999: 12.383 ms/op
                 existUser·p1.00:   12.583 ms/op

Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.627 ms/op
                 existUser·p0.9999: 14.205 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   3: 2.993 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.636 ms/op
                 existUser·p0.9999: 23.351 ms/op
                 existUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319320
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46418 
    [ 2.500,  5.000) = 272052 
    [ 5.000,  7.500) = 636 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.838 ms/op
     p(99.9900) =     21.400 ms/op
     p(99.9990) =     23.619 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 4.431 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.007 ms/op
Iteration   1: 3.167 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  9.026 ms/op
                 getUser·p0.9999: 13.200 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   2: 3.126 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  8.036 ms/op
                 getUser·p0.9999: 15.348 ms/op
                 getUser·p1.00:   15.663 ms/op

Iteration   3: 3.194 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  5.994 ms/op
                 getUser·p0.9999: 17.989 ms/op
                 getUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303404
  mean =      3.162 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 396 
    [ 1.250,  2.500) = 23556 
    [ 2.500,  3.750) = 238366 
    [ 3.750,  5.000) = 39813 
    [ 5.000,  6.250) = 701 
    [ 6.250,  7.500) = 215 
    [ 7.500,  8.750) = 120 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.053 ms/op
     p(99.9900) =     16.329 ms/op
     p(99.9990) =     18.251 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 5.698 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.011 ms/op
Iteration   1: 4.124 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  14.555 ms/op
                 listUser·p0.9999: 20.175 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   6.943 ms/op
                 listUser·p0.999:  14.388 ms/op
                 listUser·p0.9999: 17.961 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 4.085 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  18.338 ms/op
                 listUser·p0.9999: 28.983 ms/op
                 listUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234878
  mean =      4.089 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2162 
    [ 2.500,  5.000) = 205464 
    [ 5.000,  7.500) = 25784 
    [ 7.500, 10.000) = 999 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.797 ms/op
     p(99.9900) =     25.102 ms/op
     p(99.9990) =     29.359 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.166 ± 3.669  ops/ms
ClientGrpc.existUser                       thrpt       3  10.650 ± 2.419  ops/ms
ClientGrpc.getUser                         thrpt       3  10.119 ± 1.546  ops/ms
ClientGrpc.listUser                        thrpt       3   7.892 ± 2.660  ops/ms
ClientGrpc.createUser                       avgt       3   3.159 ± 0.995   ms/op
ClientGrpc.existUser                        avgt       3   3.052 ± 0.822   ms/op
ClientGrpc.getUser                          avgt       3   3.184 ± 0.948   ms/op
ClientGrpc.listUser                         avgt       3   4.095 ± 1.333   ms/op
ClientGrpc.createUser                     sample  303316   3.164 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.708           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.230           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.400           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.447           ms/op
ClientGrpc.existUser                      sample  319320   3.006 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.674           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.838           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.400           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.757           ms/op
ClientGrpc.getUser                        sample  303404   3.162 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.742           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.051           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.053           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.329           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.350           ms/op
ClientGrpc.listUser                       sample  234878   4.089 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.840           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.920           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.797           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.102           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.426           ms/op
