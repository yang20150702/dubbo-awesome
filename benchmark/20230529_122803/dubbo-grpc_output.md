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
# Warmup Iteration   1: 2.132 ops/ms
# Warmup Iteration   2: 5.216 ops/ms
# Warmup Iteration   3: 6.938 ops/ms
Iteration   1: 7.101 ops/ms
Iteration   2: 7.125 ops/ms
Iteration   3: 7.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.129 ±(99.9%) 0.540 ops/ms [Average]
  (min, avg, max) = (7.101, 7.129, 7.160), stdev = 0.030
  CI (99.9%): [6.589, 7.669] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.771 ops/ms
# Warmup Iteration   2: 6.937 ops/ms
# Warmup Iteration   3: 7.551 ops/ms
Iteration   1: 7.683 ops/ms
Iteration   2: 7.649 ops/ms
Iteration   3: 7.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.674 ±(99.9%) 0.407 ops/ms [Average]
  (min, avg, max) = (7.649, 7.674, 7.691), stdev = 0.022
  CI (99.9%): [7.267, 8.081] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.241 ops/ms
# Warmup Iteration   2: 6.629 ops/ms
# Warmup Iteration   3: 7.047 ops/ms
Iteration   1: 7.339 ops/ms
Iteration   2: 7.470 ops/ms
Iteration   3: 7.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.333 ±(99.9%) 2.560 ops/ms [Average]
  (min, avg, max) = (7.189, 7.333, 7.470), stdev = 0.140
  CI (99.9%): [4.772, 9.893] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.424 ops/ms
# Warmup Iteration   2: 5.432 ops/ms
# Warmup Iteration   3: 5.547 ops/ms
Iteration   1: 5.819 ops/ms
Iteration   2: 5.882 ops/ms
Iteration   3: 5.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.842 ±(99.9%) 0.625 ops/ms [Average]
  (min, avg, max) = (5.819, 5.842, 5.882), stdev = 0.034
  CI (99.9%): [5.217, 6.467] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.211 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.668 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 4.510 ±(99.9%) 0.008 ms/op
Iteration   1: 4.265 ±(99.9%) 0.005 ms/op
Iteration   2: 4.416 ±(99.9%) 0.005 ms/op
Iteration   3: 4.304 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.328 ±(99.9%) 1.427 ms/op [Average]
  (min, avg, max) = (4.265, 4.328, 4.416), stdev = 0.078
  CI (99.9%): [2.901, 5.755] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.580 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.004 ms/op
Iteration   1: 4.105 ±(99.9%) 0.003 ms/op
Iteration   2: 4.053 ±(99.9%) 0.003 ms/op
Iteration   3: 4.128 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.095 ±(99.9%) 0.707 ms/op [Average]
  (min, avg, max) = (4.053, 4.095, 4.128), stdev = 0.039
  CI (99.9%): [3.388, 4.802] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.976 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.842 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.566 ±(99.9%) 0.003 ms/op
Iteration   1: 4.505 ±(99.9%) 0.007 ms/op
Iteration   2: 4.349 ±(99.9%) 0.003 ms/op
Iteration   3: 4.386 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.413 ±(99.9%) 1.488 ms/op [Average]
  (min, avg, max) = (4.349, 4.413, 4.505), stdev = 0.082
  CI (99.9%): [2.926, 5.901] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.016 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.971 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.642 ±(99.9%) 0.017 ms/op
Iteration   1: 5.468 ±(99.9%) 0.014 ms/op
Iteration   2: 5.497 ±(99.9%) 0.017 ms/op
Iteration   3: 5.476 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.480 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (5.468, 5.480, 5.497), stdev = 0.015
  CI (99.9%): [5.215, 5.746] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.914 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.915 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.612 ±(99.9%) 0.014 ms/op
Iteration   1: 4.478 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.734 ms/op
                 createUser·p0.95:   6.267 ms/op
                 createUser·p0.99:   8.684 ms/op
                 createUser·p0.999:  16.049 ms/op
                 createUser·p0.9999: 22.142 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   2: 4.441 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.505 ms/op
                 createUser·p0.95:   5.923 ms/op
                 createUser·p0.99:   7.479 ms/op
                 createUser·p0.999:  11.420 ms/op
                 createUser·p0.9999: 17.147 ms/op
                 createUser·p1.00:   18.219 ms/op

Iteration   3: 4.513 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.693 ms/op
                 createUser·p0.95:   6.152 ms/op
                 createUser·p0.99:   8.782 ms/op
                 createUser·p0.999:  14.672 ms/op
                 createUser·p0.9999: 21.296 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214423
  mean =      4.477 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4939 
    [ 2.500,  5.000) = 158230 
    [ 5.000,  7.500) = 48049 
    [ 7.500, 10.000) = 2324 
    [10.000, 12.500) = 482 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =      8.348 ms/op
     p(99.9000) =     14.790 ms/op
     p(99.9900) =     21.631 ms/op
     p(99.9990) =     25.554 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.469 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.634 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.246 ±(99.9%) 0.012 ms/op
Iteration   1: 4.325 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   4.162 ms/op
                 existUser·p0.90:   5.366 ms/op
                 existUser·p0.95:   5.947 ms/op
                 existUser·p0.99:   8.654 ms/op
                 existUser·p0.999:  12.780 ms/op
                 existUser·p0.9999: 16.011 ms/op
                 existUser·p1.00:   16.597 ms/op

Iteration   2: 4.116 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   4.002 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   7.848 ms/op
                 existUser·p0.999:  15.053 ms/op
                 existUser·p0.9999: 22.887 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 4.131 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.472 ms/op
                 existUser·p0.99:   7.250 ms/op
                 existUser·p0.999:  14.633 ms/op
                 existUser·p0.9999: 34.227 ms/op
                 existUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229160
  mean =      4.188 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6182 
    [ 2.500,  5.000) = 192183 
    [ 5.000,  7.500) = 27820 
    [ 7.500, 10.000) = 2052 
    [10.000, 12.500) = 577 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      8.031 ms/op
     p(99.9000) =     13.711 ms/op
     p(99.9900) =     33.691 ms/op
     p(99.9990) =     34.518 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.783 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.614 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.495 ±(99.9%) 0.014 ms/op
Iteration   1: 4.483 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.210 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  12.993 ms/op
                 getUser·p0.9999: 18.571 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   2: 4.447 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   8.356 ms/op
                 getUser·p0.999:  12.195 ms/op
                 getUser·p0.9999: 18.809 ms/op
                 getUser·p1.00:   19.202 ms/op

Iteration   3: 4.354 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   7.627 ms/op
                 getUser·p0.999:  11.076 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216696
  mean =      4.428 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4016 
    [ 2.500,  5.000) = 167279 
    [ 5.000,  7.500) = 42034 
    [ 7.500, 10.000) = 2694 
    [10.000, 12.500) = 483 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     11.818 ms/op
     p(99.9900) =     18.787 ms/op
     p(99.9990) =     19.715 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.238 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 5.965 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.499 ±(99.9%) 0.020 ms/op
Iteration   1: 5.458 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   5.145 ms/op
                 listUser·p0.90:   7.234 ms/op
                 listUser·p0.95:   8.323 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  16.987 ms/op
                 listUser·p0.9999: 31.468 ms/op
                 listUser·p1.00:   35.652 ms/op

Iteration   2: 5.275 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   5.014 ms/op
                 listUser·p0.90:   6.880 ms/op
                 listUser·p0.95:   7.873 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 19.101 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   3: 5.491 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.037 ms/op
                 listUser·p0.95:   7.987 ms/op
                 listUser·p0.99:   10.477 ms/op
                 listUser·p0.999:  20.300 ms/op
                 listUser·p0.9999: 25.042 ms/op
                 listUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 177600
  mean =      5.406 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 154 
    [ 2.500,  5.000) = 78026 
    [ 5.000,  7.500) = 86329 
    [ 7.500, 10.000) = 10625 
    [10.000, 12.500) = 1806 
    [12.500, 15.000) = 309 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      5.128 ms/op
     p(90.0000) =      7.045 ms/op
     p(95.0000) =      8.061 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     30.867 ms/op
     p(99.9990) =     35.601 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.129 ± 0.540  ops/ms
ClientGrpc.existUser                       thrpt       3   7.674 ± 0.407  ops/ms
ClientGrpc.getUser                         thrpt       3   7.333 ± 2.560  ops/ms
ClientGrpc.listUser                        thrpt       3   5.842 ± 0.625  ops/ms
ClientGrpc.createUser                       avgt       3   4.328 ± 1.427   ms/op
ClientGrpc.existUser                        avgt       3   4.095 ± 0.707   ms/op
ClientGrpc.getUser                          avgt       3   4.413 ± 1.488   ms/op
ClientGrpc.listUser                         avgt       3   5.480 ± 0.265   ms/op
ClientGrpc.createUser                     sample  214423   4.477 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.143           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.111           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.348           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.790           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.631           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.935           ms/op
ClientGrpc.existUser                      sample  229160   4.188 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.822           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.047           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.218           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.759           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.031           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.711           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.691           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.603           ms/op
ClientGrpc.getUser                        sample  216696   4.428 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.979           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.521           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.029           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.225           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.818           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.787           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.692           ms/op
ClientGrpc.listUser                       sample  177600   5.406 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.079           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.061           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.551           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.990           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.867           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.652           ms/op
