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
# Warmup Iteration   1: 2.148 ops/ms
# Warmup Iteration   2: 5.044 ops/ms
# Warmup Iteration   3: 7.010 ops/ms
Iteration   1: 7.140 ops/ms
Iteration   2: 6.923 ops/ms
Iteration   3: 7.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.159 ±(99.9%) 4.472 ops/ms [Average]
  (min, avg, max) = (6.923, 7.159, 7.412), stdev = 0.245
  CI (99.9%): [2.687, 11.630] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.741 ops/ms
# Warmup Iteration   2: 6.917 ops/ms
# Warmup Iteration   3: 7.669 ops/ms
Iteration   1: 7.870 ops/ms
Iteration   2: 7.650 ops/ms
Iteration   3: 7.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.737 ±(99.9%) 2.139 ops/ms [Average]
  (min, avg, max) = (7.650, 7.737, 7.870), stdev = 0.117
  CI (99.9%): [5.598, 9.876] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.096 ops/ms
# Warmup Iteration   2: 6.787 ops/ms
# Warmup Iteration   3: 7.263 ops/ms
Iteration   1: 6.937 ops/ms
Iteration   2: 7.311 ops/ms
Iteration   3: 7.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.235 ±(99.9%) 4.885 ops/ms [Average]
  (min, avg, max) = (6.937, 7.235, 7.456), stdev = 0.268
  CI (99.9%): [2.350, 12.120] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.499 ops/ms
# Warmup Iteration   2: 5.293 ops/ms
# Warmup Iteration   3: 5.636 ops/ms
Iteration   1: 5.700 ops/ms
Iteration   2: 5.731 ops/ms
Iteration   3: 5.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.708 ±(99.9%) 0.377 ops/ms [Average]
  (min, avg, max) = (5.692, 5.708, 5.731), stdev = 0.021
  CI (99.9%): [5.331, 6.085] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.660 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.819 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.584 ±(99.9%) 0.036 ms/op
Iteration   1: 4.413 ±(99.9%) 0.005 ms/op
Iteration   2: 4.495 ±(99.9%) 0.003 ms/op
Iteration   3: 4.583 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.497 ±(99.9%) 1.552 ms/op [Average]
  (min, avg, max) = (4.413, 4.497, 4.583), stdev = 0.085
  CI (99.9%): [2.945, 6.049] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.899 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.004 ms/op
Iteration   1: 3.974 ±(99.9%) 0.004 ms/op
Iteration   2: 4.116 ±(99.9%) 0.003 ms/op
Iteration   3: 4.121 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.070 ±(99.9%) 1.520 ms/op [Average]
  (min, avg, max) = (3.974, 4.070, 4.121), stdev = 0.083
  CI (99.9%): [2.550, 5.590] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.701 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.887 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.392 ±(99.9%) 0.004 ms/op
Iteration   1: 4.491 ±(99.9%) 0.003 ms/op
Iteration   2: 4.474 ±(99.9%) 0.002 ms/op
Iteration   3: 4.380 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.448 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (4.380, 4.448, 4.491), stdev = 0.060
  CI (99.9%): [3.360, 5.537] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.210 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 6.337 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.626 ±(99.9%) 0.034 ms/op
Iteration   1: 5.561 ±(99.9%) 0.022 ms/op
Iteration   2: 5.544 ±(99.9%) 0.015 ms/op
Iteration   3: 5.482 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.529 ±(99.9%) 0.763 ms/op [Average]
  (min, avg, max) = (5.482, 5.529, 5.561), stdev = 0.042
  CI (99.9%): [4.766, 6.292] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.844 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.855 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.461 ±(99.9%) 0.012 ms/op
Iteration   1: 4.376 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.349 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.234 ms/op
                 createUser·p0.999:  9.500 ms/op
                 createUser·p0.9999: 16.953 ms/op
                 createUser·p1.00:   17.727 ms/op

Iteration   2: 4.373 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.456 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  24.707 ms/op
                 createUser·p0.9999: 31.338 ms/op
                 createUser·p1.00:   32.014 ms/op

Iteration   3: 4.355 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   5.759 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  14.740 ms/op
                 createUser·p0.9999: 21.124 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219879
  mean =      4.368 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3481 
    [ 2.500,  5.000) = 178105 
    [ 5.000,  7.500) = 35990 
    [ 7.500, 10.000) = 1581 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     31.936 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.498 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.536 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.311 ±(99.9%) 0.010 ms/op
Iteration   1: 4.193 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   5.808 ms/op
                 existUser·p0.99:   7.528 ms/op
                 existUser·p0.999:  10.060 ms/op
                 existUser·p0.9999: 25.715 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   2: 4.192 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   4.112 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  11.104 ms/op
                 existUser·p0.9999: 26.444 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 4.159 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.071 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   6.988 ms/op
                 existUser·p0.999:  13.713 ms/op
                 existUser·p0.9999: 20.775 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229434
  mean =      4.181 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7075 
    [ 2.500,  5.000) = 194969 
    [ 5.000,  7.500) = 25415 
    [ 7.500, 10.000) = 1533 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     11.518 ms/op
     p(99.9900) =     25.757 ms/op
     p(99.9990) =     26.644 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.795 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.957 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.619 ±(99.9%) 0.014 ms/op
Iteration   1: 4.655 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   4.506 ms/op
                 getUser·p0.90:   5.857 ms/op
                 getUser·p0.95:   6.496 ms/op
                 getUser·p0.99:   8.995 ms/op
                 getUser·p0.999:  15.206 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   26.411 ms/op

Iteration   2: 4.574 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.759 ms/op
                 getUser·p0.95:   6.414 ms/op
                 getUser·p0.99:   9.339 ms/op
                 getUser·p0.999:  13.124 ms/op
                 getUser·p0.9999: 23.463 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 4.418 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   6.038 ms/op
                 getUser·p0.99:   8.831 ms/op
                 getUser·p0.999:  13.167 ms/op
                 getUser·p0.9999: 24.175 ms/op
                 getUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 210983
  mean =      4.547 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8243 
    [ 2.500,  5.000) = 146573 
    [ 5.000,  7.500) = 51688 
    [ 7.500, 10.000) = 3371 
    [10.000, 12.500) = 742 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.734 ms/op
     p(95.0000) =      6.316 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     25.720 ms/op
     p(99.9990) =     26.357 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.688 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 6.424 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.923 ±(99.9%) 0.025 ms/op
Iteration   1: 5.923 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   5.505 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   11.502 ms/op
                 listUser·p0.999:  16.205 ms/op
                 listUser·p0.9999: 20.815 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 6.129 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   8.487 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   11.861 ms/op
                 listUser·p0.999:  22.118 ms/op
                 listUser·p0.9999: 30.092 ms/op
                 listUser·p1.00:   30.441 ms/op

Iteration   3: 5.919 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   5.521 ms/op
                 listUser·p0.90:   8.225 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   11.543 ms/op
                 listUser·p0.999:  20.316 ms/op
                 listUser·p0.9999: 24.261 ms/op
                 listUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 160237
  mean =      5.989 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 253 
    [ 2.500,  5.000) = 45541 
    [ 5.000,  7.500) = 88173 
    [ 7.500, 10.000) = 21166 
    [10.000, 12.500) = 4107 
    [12.500, 15.000) = 611 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      5.579 ms/op
     p(90.0000) =      8.364 ms/op
     p(95.0000) =      9.372 ms/op
     p(99.0000) =     11.649 ms/op
     p(99.9000) =     20.308 ms/op
     p(99.9900) =     27.915 ms/op
     p(99.9990) =     30.382 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.159 ± 4.472  ops/ms
ClientGrpc.existUser                       thrpt       3   7.737 ± 2.139  ops/ms
ClientGrpc.getUser                         thrpt       3   7.235 ± 4.885  ops/ms
ClientGrpc.listUser                        thrpt       3   5.708 ± 0.377  ops/ms
ClientGrpc.createUser                       avgt       3   4.497 ± 1.552   ms/op
ClientGrpc.existUser                        avgt       3   4.070 ± 1.520   ms/op
ClientGrpc.getUser                          avgt       3   4.448 ± 1.089   ms/op
ClientGrpc.listUser                         avgt       3   5.529 ± 0.763   ms/op
ClientGrpc.createUser                     sample  219879   4.368 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.982           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.374           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.825           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.578           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          19.268           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.771           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.014           ms/op
ClientGrpc.existUser                      sample  229434   4.181 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.855           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.120           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.595           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.250           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.518           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.757           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.804           ms/op
ClientGrpc.getUser                        sample  210983   4.547 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.951           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.734           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.316           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.060           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.270           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.720           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.411           ms/op
ClientGrpc.listUser                       sample  160237   5.989 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.550           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.364           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.372           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.649           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.308           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.915           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.441           ms/op
