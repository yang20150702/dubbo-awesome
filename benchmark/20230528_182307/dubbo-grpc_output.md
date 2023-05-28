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
# Warmup Iteration   1: 4.243 ops/ms
# Warmup Iteration   2: 9.434 ops/ms
# Warmup Iteration   3: 10.172 ops/ms
Iteration   1: 10.705 ops/ms
Iteration   2: 10.884 ops/ms
Iteration   3: 10.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.746 ±(99.9%) 2.230 ops/ms [Average]
  (min, avg, max) = (10.650, 10.746, 10.884), stdev = 0.122
  CI (99.9%): [8.516, 12.976] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.734 ops/ms
# Warmup Iteration   2: 10.599 ops/ms
# Warmup Iteration   3: 11.173 ops/ms
Iteration   1: 11.088 ops/ms
Iteration   2: 11.245 ops/ms
Iteration   3: 11.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.295 ±(99.9%) 4.311 ops/ms [Average]
  (min, avg, max) = (11.088, 11.295, 11.553), stdev = 0.236
  CI (99.9%): [6.984, 15.607] (assumes normal distribution)


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
# Warmup Iteration   1: 7.140 ops/ms
# Warmup Iteration   2: 10.339 ops/ms
# Warmup Iteration   3: 10.680 ops/ms
Iteration   1: 10.730 ops/ms
Iteration   2: 10.658 ops/ms
Iteration   3: 10.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.754 ±(99.9%) 1.998 ops/ms [Average]
  (min, avg, max) = (10.658, 10.754, 10.873), stdev = 0.110
  CI (99.9%): [8.756, 12.751] (assumes normal distribution)


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
# Warmup Iteration   1: 6.455 ops/ms
# Warmup Iteration   2: 8.036 ops/ms
# Warmup Iteration   3: 8.205 ops/ms
Iteration   1: 8.176 ops/ms
Iteration   2: 8.572 ops/ms
Iteration   3: 8.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.378 ±(99.9%) 3.610 ops/ms [Average]
  (min, avg, max) = (8.176, 8.378, 8.572), stdev = 0.198
  CI (99.9%): [4.767, 11.988] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.002 ms/op
Iteration   1: 2.997 ±(99.9%) 0.002 ms/op
Iteration   2: 2.967 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.975 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (2.963, 2.975, 2.997), stdev = 0.018
  CI (99.9%): [2.639, 3.312] (assumes normal distribution)


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.004 ms/op
Iteration   1: 2.894 ±(99.9%) 0.003 ms/op
Iteration   2: 2.877 ±(99.9%) 0.003 ms/op
Iteration   3: 2.881 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.884 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.877, 2.884, 2.894), stdev = 0.009
  CI (99.9%): [2.721, 3.048] (assumes normal distribution)


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.004 ms/op
Iteration   1: 3.000 ±(99.9%) 0.004 ms/op
Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
Iteration   3: 3.011 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.008 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (3.000, 3.008, 3.012), stdev = 0.007
  CI (99.9%): [2.884, 3.132] (assumes normal distribution)


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.008 ms/op
Iteration   1: 3.816 ±(99.9%) 0.034 ms/op
Iteration   2: 3.779 ±(99.9%) 0.025 ms/op
Iteration   3: 3.771 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.789 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (3.771, 3.789, 3.816), stdev = 0.025
  CI (99.9%): [3.341, 4.236] (assumes normal distribution)


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
# Warmup Iteration   1: 4.045 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.005 ms/op
Iteration   1: 3.024 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  6.906 ms/op
                 createUser·p0.9999: 17.957 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  11.059 ms/op
                 createUser·p0.9999: 19.825 ms/op
                 createUser·p1.00:   20.054 ms/op

Iteration   3: 3.004 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.004 ms/op
                 createUser·p0.9999: 25.833 ms/op
                 createUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318360
  mean =      3.014 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26318 
    [ 2.500,  5.000) = 290550 
    [ 5.000,  7.500) = 1075 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      9.415 ms/op
     p(99.9900) =     24.931 ms/op
     p(99.9990) =     25.946 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.921 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.005 ms/op
Iteration   1: 2.972 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.534 ms/op
                 existUser·p0.9999: 11.649 ms/op
                 existUser·p1.00:   12.026 ms/op

Iteration   2: 2.912 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  6.488 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   3: 2.876 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  9.634 ms/op
                 existUser·p0.9999: 26.800 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328812
  mean =      2.920 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47688 
    [ 2.500,  5.000) = 279859 
    [ 5.000,  7.500) = 940 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.464 ms/op
     p(99.9900) =     14.982 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.920 ms/op
                 getUser·p0.9999: 12.432 ms/op
                 getUser·p1.00:   12.665 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  9.199 ms/op
                 getUser·p0.9999: 14.002 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.596 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  8.094 ms/op
                 getUser·p0.9999: 15.725 ms/op
                 getUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321206
  mean =      2.987 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2177 
    [ 1.250,  2.500) = 25242 
    [ 2.500,  3.750) = 277612 
    [ 3.750,  5.000) = 14846 
    [ 5.000,  6.250) = 628 
    [ 6.250,  7.500) = 286 
    [ 7.500,  8.750) = 134 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.141 ms/op
     p(99.9900) =     14.793 ms/op
     p(99.9990) =     16.230 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


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
# Warmup Iteration   1: 4.921 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.009 ms/op
Iteration   1: 3.890 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  12.970 ms/op
                 listUser·p0.9999: 17.540 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   2: 3.910 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.743 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.529 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  13.911 ms/op
                 listUser·p0.9999: 17.158 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.815 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   6.357 ms/op
                 listUser·p0.999:  20.748 ms/op
                 listUser·p0.9999: 23.449 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248126
  mean =      3.871 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3535 
    [ 2.500,  5.000) = 225966 
    [ 5.000,  7.500) = 17701 
    [ 7.500, 10.000) = 500 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     14.039 ms/op
     p(99.9900) =     22.852 ms/op
     p(99.9990) =     23.627 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.746 ± 2.230  ops/ms
ClientGrpc.existUser                       thrpt       3  11.295 ± 4.311  ops/ms
ClientGrpc.getUser                         thrpt       3  10.754 ± 1.998  ops/ms
ClientGrpc.listUser                        thrpt       3   8.378 ± 3.610  ops/ms
ClientGrpc.createUser                       avgt       3   2.975 ± 0.336   ms/op
ClientGrpc.existUser                        avgt       3   2.884 ± 0.163   ms/op
ClientGrpc.getUser                          avgt       3   3.008 ± 0.124   ms/op
ClientGrpc.listUser                         avgt       3   3.789 ± 0.447   ms/op
ClientGrpc.createUser                     sample  318360   3.014 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.593           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.415           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.931           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.051           ms/op
ClientGrpc.existUser                      sample  328812   2.920 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.568           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.464           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.982           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.968           ms/op
ClientGrpc.getUser                        sample  321206   2.987 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.596           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.141           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.793           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.351           ms/op
ClientGrpc.listUser                       sample  248126   3.871 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.743           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.399           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.595           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.039           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.852           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.724           ms/op
