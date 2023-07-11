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
# Warmup Iteration   1: 3.640 ops/ms
# Warmup Iteration   2: 7.999 ops/ms
# Warmup Iteration   3: 9.925 ops/ms
Iteration   1: 9.839 ops/ms
Iteration   2: 10.262 ops/ms
Iteration   3: 10.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.171 ±(99.9%) 5.424 ops/ms [Average]
  (min, avg, max) = (9.839, 10.171, 10.413), stdev = 0.297
  CI (99.9%): [4.748, 15.595] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.646 ops/ms
# Warmup Iteration   2: 10.319 ops/ms
# Warmup Iteration   3: 10.811 ops/ms
Iteration   1: 10.695 ops/ms
Iteration   2: 10.753 ops/ms
Iteration   3: 10.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.716 ±(99.9%) 0.589 ops/ms [Average]
  (min, avg, max) = (10.695, 10.716, 10.753), stdev = 0.032
  CI (99.9%): [10.127, 11.305] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.112 ops/ms
# Warmup Iteration   2: 9.835 ops/ms
# Warmup Iteration   3: 10.251 ops/ms
Iteration   1: 10.173 ops/ms
Iteration   2: 10.541 ops/ms
Iteration   3: 10.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.345 ±(99.9%) 3.372 ops/ms [Average]
  (min, avg, max) = (10.173, 10.345, 10.541), stdev = 0.185
  CI (99.9%): [6.973, 13.716] (assumes normal distribution)


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
# Warmup Iteration   1: 4.948 ops/ms
# Warmup Iteration   2: 7.730 ops/ms
# Warmup Iteration   3: 7.718 ops/ms
Iteration   1: 7.665 ops/ms
Iteration   2: 7.677 ops/ms
Iteration   3: 8.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.872 ±(99.9%) 6.346 ops/ms [Average]
  (min, avg, max) = (7.665, 7.872, 8.274), stdev = 0.348
  CI (99.9%): [1.525, 14.218] (assumes normal distribution)


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
# Warmup Iteration   1: 4.695 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.013 ms/op
Iteration   1: 3.096 ±(99.9%) 0.002 ms/op
Iteration   2: 3.157 ±(99.9%) 0.002 ms/op
Iteration   3: 3.073 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.109 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (3.073, 3.109, 3.157), stdev = 0.043
  CI (99.9%): [2.320, 3.897] (assumes normal distribution)


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.001 ms/op
Iteration   1: 2.952 ±(99.9%) 0.003 ms/op
Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
Iteration   3: 3.086 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.021 ±(99.9%) 1.222 ms/op [Average]
  (min, avg, max) = (2.952, 3.021, 3.086), stdev = 0.067
  CI (99.9%): [1.799, 4.244] (assumes normal distribution)


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
# Warmup Iteration   1: 4.837 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.003 ms/op
Iteration   1: 3.223 ±(99.9%) 0.003 ms/op
Iteration   2: 3.150 ±(99.9%) 0.003 ms/op
Iteration   3: 3.152 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.175 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (3.150, 3.175, 3.223), stdev = 0.042
  CI (99.9%): [2.416, 3.933] (assumes normal distribution)


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
# Warmup Iteration   1: 5.804 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.357 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.011 ms/op
Iteration   1: 4.160 ±(99.9%) 0.014 ms/op
Iteration   2: 4.170 ±(99.9%) 0.018 ms/op
Iteration   3: 4.013 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.114 ±(99.9%) 1.605 ms/op [Average]
  (min, avg, max) = (4.013, 4.114, 4.170), stdev = 0.088
  CI (99.9%): [2.509, 5.719] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.721 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.006 ms/op
Iteration   1: 3.143 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  7.473 ms/op
                 createUser·p0.9999: 15.254 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   2: 3.232 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.065 ms/op
                 createUser·p0.9999: 15.567 ms/op
                 createUser·p1.00:   16.318 ms/op

Iteration   3: 3.259 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  11.665 ms/op
                 createUser·p0.9999: 19.240 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298979
  mean =      3.210 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11426 
    [ 2.500,  5.000) = 286018 
    [ 5.000,  7.500) = 1110 
    [ 7.500, 10.000) = 168 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     18.295 ms/op
     p(99.9990) =     19.596 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
Iteration   1: 3.113 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.005 ms/op
                 existUser·p0.999:  8.357 ms/op
                 existUser·p0.9999: 11.624 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  9.175 ms/op
                 existUser·p0.9999: 14.846 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   3: 3.135 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.947 ms/op
                 existUser·p0.9999: 16.653 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 306887
  mean =      3.126 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 781 
    [ 1.250,  2.500) = 10427 
    [ 2.500,  3.750) = 275905 
    [ 3.750,  5.000) = 17617 
    [ 5.000,  6.250) = 1082 
    [ 6.250,  7.500) = 699 
    [ 7.500,  8.750) = 127 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      8.138 ms/op
     p(99.9900) =     16.170 ms/op
     p(99.9990) =     17.004 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 5.010 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.006 ms/op
Iteration   1: 3.261 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  9.477 ms/op
                 getUser·p0.9999: 17.269 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   2: 3.317 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  8.785 ms/op
                 getUser·p0.9999: 18.711 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   3: 3.500 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.114 ms/op
                 getUser·p0.999:  9.026 ms/op
                 getUser·p0.9999: 20.854 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 285919
  mean =      3.357 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7350 
    [ 2.500,  5.000) = 273809 
    [ 5.000,  7.500) = 3955 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     19.229 ms/op
     p(99.9990) =     22.516 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 6.047 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.519 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.274 ±(99.9%) 0.012 ms/op
Iteration   1: 4.313 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.406 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  15.512 ms/op
                 listUser·p0.9999: 23.107 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   2: 4.291 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  16.158 ms/op
                 listUser·p0.9999: 19.124 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 3.942 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.303 ms/op
                 listUser·p0.999:  16.310 ms/op
                 listUser·p0.9999: 19.362 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230061
  mean =      4.175 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1626 
    [ 2.500,  5.000) = 194658 
    [ 5.000,  7.500) = 31002 
    [ 7.500, 10.000) = 2224 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.152 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     23.635 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.171 ± 5.424  ops/ms
ClientGrpc.existUser                       thrpt       3  10.716 ± 0.589  ops/ms
ClientGrpc.getUser                         thrpt       3  10.345 ± 3.372  ops/ms
ClientGrpc.listUser                        thrpt       3   7.872 ± 6.346  ops/ms
ClientGrpc.createUser                       avgt       3   3.109 ± 0.789   ms/op
ClientGrpc.existUser                        avgt       3   3.021 ± 1.222   ms/op
ClientGrpc.getUser                          avgt       3   3.175 ± 0.759   ms/op
ClientGrpc.listUser                         avgt       3   4.114 ± 1.605   ms/op
ClientGrpc.createUser                     sample  298979   3.210 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.669           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.195           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.536           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.295           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.644           ms/op
ClientGrpc.existUser                      sample  306887   3.126 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.710           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.097           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.694           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.138           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.170           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  285919   3.357 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.665           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.273           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.010           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.044           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.229           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.610           ms/op
ClientGrpc.listUser                       sample  230061   4.175 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.155           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.969           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.152           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.684           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.073           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.675           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.921           ms/op
