# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.744 ops/ms
# Warmup Iteration   2: 9.362 ops/ms
# Warmup Iteration   3: 10.114 ops/ms
Iteration   1: 10.413 ops/ms
Iteration   2: 10.711 ops/ms
Iteration   3: 10.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.557 ±(99.9%) 2.728 ops/ms [Average]
  (min, avg, max) = (10.413, 10.557, 10.711), stdev = 0.150
  CI (99.9%): [7.828, 13.285] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.492 ops/ms
# Warmup Iteration   2: 10.882 ops/ms
# Warmup Iteration   3: 11.255 ops/ms
Iteration   1: 11.302 ops/ms
Iteration   2: 11.025 ops/ms
Iteration   3: 11.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.309 ±(99.9%) 5.246 ops/ms [Average]
  (min, avg, max) = (11.025, 11.309, 11.600), stdev = 0.288
  CI (99.9%): [6.063, 16.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.436 ops/ms
# Warmup Iteration   2: 10.304 ops/ms
# Warmup Iteration   3: 10.616 ops/ms
Iteration   1: 10.725 ops/ms
Iteration   2: 10.810 ops/ms
Iteration   3: 10.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.756 ±(99.9%) 0.856 ops/ms [Average]
  (min, avg, max) = (10.725, 10.756, 10.810), stdev = 0.047
  CI (99.9%): [9.899, 11.612] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.217 ops/ms
# Warmup Iteration   2: 8.124 ops/ms
# Warmup Iteration   3: 8.560 ops/ms
Iteration   1: 8.433 ops/ms
Iteration   2: 8.461 ops/ms
Iteration   3: 8.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.414 ±(99.9%) 1.090 ops/ms [Average]
  (min, avg, max) = (8.347, 8.414, 8.461), stdev = 0.060
  CI (99.9%): [7.323, 9.504] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.003 ms/op
Iteration   1: 2.996 ±(99.9%) 0.003 ms/op
Iteration   2: 3.026 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.010 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (2.996, 3.010, 3.026), stdev = 0.015
  CI (99.9%): [2.730, 3.289] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.848 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.923 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.003 ms/op
Iteration   1: 2.832 ±(99.9%) 0.004 ms/op
Iteration   2: 2.841 ±(99.9%) 0.004 ms/op
Iteration   3: 2.851 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.841 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (2.832, 2.841, 2.851), stdev = 0.009
  CI (99.9%): [2.674, 3.008] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.933 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.002 ms/op
Iteration   1: 2.941 ±(99.9%) 0.002 ms/op
Iteration   2: 2.946 ±(99.9%) 0.003 ms/op
Iteration   3: 2.945 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.944 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.941, 2.944, 2.946), stdev = 0.003
  CI (99.9%): [2.888, 3.000] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.981 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.011 ms/op
Iteration   1: 3.883 ±(99.9%) 0.014 ms/op
Iteration   2: 3.722 ±(99.9%) 0.018 ms/op
Iteration   3: 3.834 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.813 ±(99.9%) 1.504 ms/op [Average]
  (min, avg, max) = (3.722, 3.813, 3.883), stdev = 0.082
  CI (99.9%): [2.309, 5.317] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  8.485 ms/op
                 createUser·p0.9999: 14.603 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  8.253 ms/op
                 createUser·p0.9999: 16.380 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.247 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  10.592 ms/op
                 createUser·p0.9999: 20.262 ms/op
                 createUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321058
  mean =      2.988 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28230 
    [ 2.500,  5.000) = 291689 
    [ 5.000,  7.500) = 727 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.247 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.895 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     20.316 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.700 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.978 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.869 ±(99.9%) 0.005 ms/op
Iteration   1: 2.853 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.535 ms/op
                 existUser·p0.9999: 12.907 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   2: 2.847 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  5.931 ms/op
                 existUser·p0.9999: 13.210 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   3: 2.850 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 15.131 ms/op
                 existUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337061
  mean =      2.850 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2165 
    [ 1.250,  2.500) = 44941 
    [ 2.500,  3.750) = 281363 
    [ 3.750,  5.000) = 7678 
    [ 5.000,  6.250) = 535 
    [ 6.250,  7.500) = 149 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.498 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.406 ms/op
     p(99.9900) =     14.505 ms/op
     p(99.9990) =     16.351 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.992 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
Iteration   1: 2.982 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  6.396 ms/op
                 getUser·p0.9999: 12.321 ms/op
                 getUser·p1.00:   12.681 ms/op

Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.663 ms/op
                 getUser·p0.9999: 19.280 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.609 ms/op
                 getUser·p0.9999: 24.084 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320637
  mean =      2.995 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21965 
    [ 2.500,  5.000) = 297630 
    [ 5.000,  7.500) = 824 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     23.299 ms/op
     p(99.9990) =     24.307 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.376 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.010 ms/op
Iteration   1: 3.880 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.713 ms/op
                 listUser·p0.9999: 18.244 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   2: 3.739 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.443 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  16.768 ms/op
                 listUser·p0.9999: 25.257 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.635 ms/op
                 listUser·p0.99:   6.588 ms/op
                 listUser·p0.999:  14.501 ms/op
                 listUser·p0.9999: 19.807 ms/op
                 listUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250648
  mean =      3.830 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5603 
    [ 2.500,  5.000) = 225732 
    [ 5.000,  7.500) = 18380 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.582 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     24.377 ms/op
     p(99.9990) =     25.722 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.557 ± 2.728  ops/ms
ClientGrpc.existUser                       thrpt       3  11.309 ± 5.246  ops/ms
ClientGrpc.getUser                         thrpt       3  10.756 ± 0.856  ops/ms
ClientGrpc.listUser                        thrpt       3   8.414 ± 1.090  ops/ms
ClientGrpc.createUser                       avgt       3   3.010 ± 0.280   ms/op
ClientGrpc.existUser                        avgt       3   2.841 ± 0.167   ms/op
ClientGrpc.getUser                          avgt       3   2.944 ± 0.056   ms/op
ClientGrpc.listUser                         avgt       3   3.813 ± 1.504   ms/op
ClientGrpc.createUser                     sample  321058   2.988 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.247           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.895           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.826           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.316           ms/op
ClientGrpc.existUser                      sample  337061   2.850 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.484           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.273           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.406           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.505           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.843           ms/op
ClientGrpc.getUser                        sample  320637   2.995 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.719           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.881           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.299           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.805           ms/op
ClientGrpc.listUser                       sample  250648   3.830 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.877           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.582           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.615           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.377           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.821           ms/op
