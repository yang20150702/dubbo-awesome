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
# Warmup Iteration   1: 4.239 ops/ms
# Warmup Iteration   2: 8.741 ops/ms
# Warmup Iteration   3: 9.766 ops/ms
Iteration   1: 10.029 ops/ms
Iteration   2: 10.155 ops/ms
Iteration   3: 10.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.076 ±(99.9%) 1.262 ops/ms [Average]
  (min, avg, max) = (10.029, 10.076, 10.155), stdev = 0.069
  CI (99.9%): [8.814, 11.337] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.256 ops/ms
# Warmup Iteration   2: 10.068 ops/ms
# Warmup Iteration   3: 10.636 ops/ms
Iteration   1: 10.931 ops/ms
Iteration   2: 10.948 ops/ms
Iteration   3: 11.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.996 ±(99.9%) 1.811 ops/ms [Average]
  (min, avg, max) = (10.931, 10.996, 11.111), stdev = 0.099
  CI (99.9%): [9.185, 12.808] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.762 ops/ms
# Warmup Iteration   2: 10.127 ops/ms
# Warmup Iteration   3: 10.291 ops/ms
Iteration   1: 10.413 ops/ms
Iteration   2: 10.486 ops/ms
Iteration   3: 10.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.452 ±(99.9%) 0.663 ops/ms [Average]
  (min, avg, max) = (10.413, 10.452, 10.486), stdev = 0.036
  CI (99.9%): [9.789, 11.115] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.706 ops/ms
# Warmup Iteration   2: 7.550 ops/ms
# Warmup Iteration   3: 7.953 ops/ms
Iteration   1: 7.780 ops/ms
Iteration   2: 7.938 ops/ms
Iteration   3: 7.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.880 ±(99.9%) 1.597 ops/ms [Average]
  (min, avg, max) = (7.780, 7.880, 7.938), stdev = 0.088
  CI (99.9%): [6.283, 9.478] (assumes normal distribution)


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.003 ms/op
Iteration   1: 3.058 ±(99.9%) 0.003 ms/op
Iteration   2: 3.028 ±(99.9%) 0.004 ms/op
Iteration   3: 3.077 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.054 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (3.028, 3.054, 3.077), stdev = 0.025
  CI (99.9%): [2.598, 3.511] (assumes normal distribution)


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.004 ms/op
Iteration   1: 2.892 ±(99.9%) 0.004 ms/op
Iteration   2: 2.947 ±(99.9%) 0.003 ms/op
Iteration   3: 2.991 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.943 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (2.892, 2.943, 2.991), stdev = 0.049
  CI (99.9%): [2.045, 3.842] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.085 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.004 ms/op
Iteration   1: 3.049 ±(99.9%) 0.002 ms/op
Iteration   2: 3.056 ±(99.9%) 0.003 ms/op
Iteration   3: 3.009 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.038 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (3.009, 3.038, 3.056), stdev = 0.025
  CI (99.9%): [2.574, 3.501] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.472 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.037 ms/op
Iteration   1: 4.062 ±(99.9%) 0.015 ms/op
Iteration   2: 4.000 ±(99.9%) 0.013 ms/op
Iteration   3: 4.067 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.043 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (4.000, 4.043, 4.067), stdev = 0.037
  CI (99.9%): [3.365, 4.721] (assumes normal distribution)


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.092 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  9.441 ms/op
                 createUser·p0.9999: 14.500 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.717 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  8.172 ms/op
                 createUser·p0.9999: 16.554 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   3: 3.059 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  14.012 ms/op
                 createUser·p0.9999: 20.697 ms/op
                 createUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314391
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20053 
    [ 2.500,  5.000) = 292003 
    [ 5.000,  7.500) = 1716 
    [ 7.500, 10.000) = 327 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =      9.447 ms/op
     p(99.9900) =     19.880 ms/op
     p(99.9990) =     22.469 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.441 ms/op
                 existUser·p0.999:  7.556 ms/op
                 existUser·p0.9999: 14.124 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.912 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  10.243 ms/op
                 existUser·p0.9999: 17.172 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  8.521 ms/op
                 existUser·p0.9999: 17.998 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326275
  mean =      2.941 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1712 
    [ 1.250,  2.500) = 37118 
    [ 2.500,  3.750) = 272414 
    [ 3.750,  5.000) = 13272 
    [ 5.000,  6.250) = 828 
    [ 6.250,  7.500) = 409 
    [ 7.500,  8.750) = 243 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      8.348 ms/op
     p(99.9900) =     17.498 ms/op
     p(99.9990) =     18.619 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.264 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.647 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  8.498 ms/op
                 getUser·p0.9999: 16.073 ms/op
                 getUser·p1.00:   16.499 ms/op

Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  8.492 ms/op
                 getUser·p0.9999: 16.695 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  7.564 ms/op
                 getUser·p0.9999: 19.478 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317365
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26975 
    [ 2.500,  5.000) = 288372 
    [ 5.000,  7.500) = 1573 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      8.263 ms/op
     p(99.9900) =     18.981 ms/op
     p(99.9990) =     21.330 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 4.886 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.247 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.013 ms/op
Iteration   1: 4.126 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  14.502 ms/op
                 listUser·p0.9999: 20.160 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 4.143 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.492 ms/op
                 listUser·p0.999:  19.066 ms/op
                 listUser·p0.9999: 22.881 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   3: 4.028 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  19.562 ms/op
                 listUser·p0.9999: 25.959 ms/op
                 listUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234107
  mean =      4.099 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2224 
    [ 2.500,  5.000) = 204119 
    [ 5.000,  7.500) = 25320 
    [ 7.500, 10.000) = 1763 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     24.628 ms/op
     p(99.9990) =     26.421 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.076 ± 1.262  ops/ms
ClientGrpc.existUser                       thrpt       3  10.996 ± 1.811  ops/ms
ClientGrpc.getUser                         thrpt       3  10.452 ± 0.663  ops/ms
ClientGrpc.listUser                        thrpt       3   7.880 ± 1.597  ops/ms
ClientGrpc.createUser                       avgt       3   3.054 ± 0.456   ms/op
ClientGrpc.existUser                        avgt       3   2.943 ± 0.898   ms/op
ClientGrpc.getUser                          avgt       3   3.038 ± 0.464   ms/op
ClientGrpc.listUser                         avgt       3   4.043 ± 0.678   ms/op
ClientGrpc.createUser                     sample  314391   3.052 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.684           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.447           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.880           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.544           ms/op
ClientGrpc.existUser                      sample  326275   2.941 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.587           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.348           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.498           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.678           ms/op
ClientGrpc.getUser                        sample  317365   3.024 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.647           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.263           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.981           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.889           ms/op
ClientGrpc.listUser                       sample  234107   4.099 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.075           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.553           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.088           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.628           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.542           ms/op
