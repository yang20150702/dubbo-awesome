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
# Warmup Iteration   1: 4.455 ops/ms
# Warmup Iteration   2: 8.560 ops/ms
# Warmup Iteration   3: 9.838 ops/ms
Iteration   1: 10.308 ops/ms
Iteration   2: 10.302 ops/ms
Iteration   3: 10.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.303 ±(99.9%) 0.096 ops/ms [Average]
  (min, avg, max) = (10.298, 10.303, 10.308), stdev = 0.005
  CI (99.9%): [10.207, 10.398] (assumes normal distribution)


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
# Warmup Iteration   1: 7.209 ops/ms
# Warmup Iteration   2: 10.659 ops/ms
# Warmup Iteration   3: 10.816 ops/ms
Iteration   1: 10.781 ops/ms
Iteration   2: 10.847 ops/ms
Iteration   3: 11.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.881 ±(99.9%) 2.201 ops/ms [Average]
  (min, avg, max) = (10.781, 10.881, 11.015), stdev = 0.121
  CI (99.9%): [8.679, 13.082] (assumes normal distribution)


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
# Warmup Iteration   1: 6.870 ops/ms
# Warmup Iteration   2: 10.040 ops/ms
# Warmup Iteration   3: 10.195 ops/ms
Iteration   1: 10.214 ops/ms
Iteration   2: 10.437 ops/ms
Iteration   3: 10.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.432 ±(99.9%) 3.920 ops/ms [Average]
  (min, avg, max) = (10.214, 10.432, 10.644), stdev = 0.215
  CI (99.9%): [6.512, 14.351] (assumes normal distribution)


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
# Warmup Iteration   1: 6.820 ops/ms
# Warmup Iteration   2: 8.124 ops/ms
# Warmup Iteration   3: 8.473 ops/ms
Iteration   1: 8.260 ops/ms
Iteration   2: 8.311 ops/ms
Iteration   3: 8.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.315 ±(99.9%) 1.037 ops/ms [Average]
  (min, avg, max) = (8.260, 8.315, 8.373), stdev = 0.057
  CI (99.9%): [7.278, 9.352] (assumes normal distribution)


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.003 ms/op
Iteration   1: 3.044 ±(99.9%) 0.003 ms/op
Iteration   2: 3.018 ±(99.9%) 0.004 ms/op
Iteration   3: 3.084 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.049 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.018, 3.049, 3.084), stdev = 0.033
  CI (99.9%): [2.447, 3.650] (assumes normal distribution)


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.004 ms/op
Iteration   1: 2.969 ±(99.9%) 0.003 ms/op
Iteration   2: 2.961 ±(99.9%) 0.003 ms/op
Iteration   3: 2.906 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.946 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (2.906, 2.946, 2.969), stdev = 0.034
  CI (99.9%): [2.319, 3.572] (assumes normal distribution)


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
# Warmup Iteration   1: 3.852 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.003 ms/op
Iteration   1: 2.984 ±(99.9%) 0.002 ms/op
Iteration   2: 2.965 ±(99.9%) 0.002 ms/op
Iteration   3: 3.018 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.989 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (2.965, 2.989, 3.018), stdev = 0.027
  CI (99.9%): [2.499, 3.479] (assumes normal distribution)


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.009 ms/op
Iteration   1: 3.798 ±(99.9%) 0.017 ms/op
Iteration   2: 3.938 ±(99.9%) 0.014 ms/op
Iteration   3: 4.088 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.941 ±(99.9%) 2.651 ms/op [Average]
  (min, avg, max) = (3.798, 3.941, 4.088), stdev = 0.145
  CI (99.9%): [1.291, 6.592] (assumes normal distribution)


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.007 ms/op
Iteration   1: 3.117 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  9.582 ms/op
                 createUser·p0.9999: 18.168 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   2: 3.133 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.156 ms/op
                 createUser·p0.9999: 14.145 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.429 ms/op
                 createUser·p0.999:  7.323 ms/op
                 createUser·p0.9999: 26.567 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307508
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14598 
    [ 2.500,  5.000) = 291393 
    [ 5.000,  7.500) = 1181 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.901 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     27.457 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.938 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  6.128 ms/op
                 existUser·p0.9999: 16.304 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 2.966 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.410 ms/op
                 existUser·p0.9999: 12.941 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  7.261 ms/op
                 existUser·p0.9999: 17.367 ms/op
                 existUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323060
  mean =      2.971 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1010 
    [ 1.250,  2.500) = 22603 
    [ 2.500,  3.750) = 288618 
    [ 3.750,  5.000) = 9876 
    [ 5.000,  6.250) = 568 
    [ 6.250,  7.500) = 149 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.536 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.259 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.007 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.812 ms/op
                 getUser·p0.9999: 18.032 ms/op
                 getUser·p1.00:   19.005 ms/op

Iteration   2: 2.986 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.819 ms/op
                 getUser·p0.9999: 19.726 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   3: 3.011 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.573 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  9.254 ms/op
                 getUser·p0.9999: 22.078 ms/op
                 getUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320623
  mean =      2.993 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27146 
    [ 2.500,  5.000) = 292097 
    [ 5.000,  7.500) = 948 
    [ 7.500, 10.000) = 218 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.879 ms/op
     p(99.9900) =     20.120 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 5.337 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.010 ms/op
Iteration   1: 3.937 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  12.529 ms/op
                 listUser·p0.9999: 13.648 ms/op
                 listUser·p1.00:   14.107 ms/op

Iteration   2: 3.922 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.286 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.276 ms/op
                 listUser·p0.9999: 26.590 ms/op
                 listUser·p1.00:   27.689 ms/op

Iteration   3: 3.836 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  12.701 ms/op
                 listUser·p0.9999: 15.390 ms/op
                 listUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246205
  mean =      3.898 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5244 
    [ 2.500,  5.000) = 220399 
    [ 5.000,  7.500) = 19291 
    [ 7.500, 10.000) = 823 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.286 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     12.973 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     27.641 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.303 ± 0.096  ops/ms
ClientGrpc.existUser                       thrpt       3  10.881 ± 2.201  ops/ms
ClientGrpc.getUser                         thrpt       3  10.432 ± 3.920  ops/ms
ClientGrpc.listUser                        thrpt       3   8.315 ± 1.037  ops/ms
ClientGrpc.createUser                       avgt       3   3.049 ± 0.601   ms/op
ClientGrpc.existUser                        avgt       3   2.946 ± 0.626   ms/op
ClientGrpc.getUser                          avgt       3   2.989 ± 0.490   ms/op
ClientGrpc.listUser                         avgt       3   3.941 ± 2.651   ms/op
ClientGrpc.createUser                     sample  307508   3.123 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.721           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.901           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.494           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.689           ms/op
ClientGrpc.existUser                      sample  323060   2.971 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.647           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.536           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.105           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.153           ms/op
ClientGrpc.getUser                        sample  320623   2.993 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.535           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.879           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.120           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.348           ms/op
ClientGrpc.listUser                       sample  246205   3.898 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.286           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.973           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.938           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.689           ms/op
