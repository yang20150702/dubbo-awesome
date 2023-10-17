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
# Warmup Iteration   1: 4.285 ops/ms
# Warmup Iteration   2: 9.159 ops/ms
# Warmup Iteration   3: 9.916 ops/ms
Iteration   1: 10.307 ops/ms
Iteration   2: 10.090 ops/ms
Iteration   3: 10.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.277 ±(99.9%) 3.182 ops/ms [Average]
  (min, avg, max) = (10.090, 10.277, 10.435), stdev = 0.174
  CI (99.9%): [7.095, 13.459] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.850 ops/ms
# Warmup Iteration   2: 10.597 ops/ms
# Warmup Iteration   3: 11.009 ops/ms
Iteration   1: 10.871 ops/ms
Iteration   2: 10.636 ops/ms
Iteration   3: 10.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.768 ±(99.9%) 2.188 ops/ms [Average]
  (min, avg, max) = (10.636, 10.768, 10.871), stdev = 0.120
  CI (99.9%): [8.580, 12.957] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.606 ops/ms
# Warmup Iteration   2: 10.009 ops/ms
# Warmup Iteration   3: 10.362 ops/ms
Iteration   1: 10.393 ops/ms
Iteration   2: 10.234 ops/ms
Iteration   3: 9.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.204 ±(99.9%) 3.772 ops/ms [Average]
  (min, avg, max) = (9.983, 10.204, 10.393), stdev = 0.207
  CI (99.9%): [6.431, 13.976] (assumes normal distribution)


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
# Warmup Iteration   1: 5.854 ops/ms
# Warmup Iteration   2: 8.169 ops/ms
# Warmup Iteration   3: 8.331 ops/ms
Iteration   1: 8.386 ops/ms
Iteration   2: 8.409 ops/ms
Iteration   3: 8.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.409 ±(99.9%) 0.415 ops/ms [Average]
  (min, avg, max) = (8.386, 8.409, 8.432), stdev = 0.023
  CI (99.9%): [7.994, 8.824] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.000 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.002 ms/op
Iteration   1: 3.079 ±(99.9%) 0.002 ms/op
Iteration   2: 3.154 ±(99.9%) 0.003 ms/op
Iteration   3: 3.111 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.115 ±(99.9%) 0.683 ms/op [Average]
  (min, avg, max) = (3.079, 3.115, 3.154), stdev = 0.037
  CI (99.9%): [2.431, 3.798] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.002 ms/op
Iteration   1: 2.997 ±(99.9%) 0.003 ms/op
Iteration   2: 2.939 ±(99.9%) 0.003 ms/op
Iteration   3: 2.976 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.971 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (2.939, 2.971, 2.997), stdev = 0.030
  CI (99.9%): [2.430, 3.511] (assumes normal distribution)


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
# Warmup Iteration   1: 3.528 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.003 ms/op
Iteration   1: 3.139 ±(99.9%) 0.002 ms/op
Iteration   2: 3.087 ±(99.9%) 0.001 ms/op
Iteration   3: 3.094 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.107 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (3.087, 3.107, 3.139), stdev = 0.028
  CI (99.9%): [2.595, 3.618] (assumes normal distribution)


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
# Warmup Iteration   1: 5.260 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.044 ms/op
Iteration   1: 3.880 ±(99.9%) 0.012 ms/op
Iteration   2: 3.770 ±(99.9%) 0.031 ms/op
Iteration   3: 3.809 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.820 ±(99.9%) 1.024 ms/op [Average]
  (min, avg, max) = (3.770, 3.820, 3.880), stdev = 0.056
  CI (99.9%): [2.796, 4.843] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.096 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.538 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.410 ms/op
                 createUser·p0.9999: 11.216 ms/op
                 createUser·p1.00:   11.354 ms/op

Iteration   2: 3.112 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.874 ms/op
                 createUser·p0.9999: 13.715 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  10.948 ms/op
                 createUser·p0.9999: 25.264 ms/op
                 createUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309490
  mean =      3.102 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11958 
    [ 2.500,  5.000) = 295881 
    [ 5.000,  7.500) = 1219 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     24.938 ms/op
     p(99.9990) =     25.458 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.005 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.790 ms/op
                 existUser·p0.9999: 11.663 ms/op
                 existUser·p1.00:   12.042 ms/op

Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.322 ms/op
                 existUser·p0.999:  8.419 ms/op
                 existUser·p0.9999: 13.816 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   3.989 ms/op
                 existUser·p0.999:  6.562 ms/op
                 existUser·p0.9999: 16.600 ms/op
                 existUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320751
  mean =      2.995 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1606 
    [ 1.250,  2.500) = 21500 
    [ 2.500,  3.750) = 285830 
    [ 3.750,  5.000) = 10263 
    [ 5.000,  6.250) = 893 
    [ 6.250,  7.500) = 323 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.829 ms/op
     p(99.9900) =     16.152 ms/op
     p(99.9990) =     16.767 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.006 ms/op
Iteration   1: 3.054 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.251 ms/op
                 getUser·p0.9999: 14.893 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.673 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.475 ms/op
                 getUser·p0.9999: 16.220 ms/op
                 getUser·p1.00:   16.744 ms/op

Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  9.219 ms/op
                 getUser·p0.9999: 16.941 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311388
  mean =      3.083 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1009 
    [ 1.250,  2.500) = 12073 
    [ 2.500,  3.750) = 280654 
    [ 3.750,  5.000) = 16228 
    [ 5.000,  6.250) = 691 
    [ 6.250,  7.500) = 330 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     16.677 ms/op
     p(99.9990) =     17.130 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.561 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.921 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.009 ms/op
Iteration   1: 3.857 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  12.075 ms/op
                 listUser·p0.9999: 13.671 ms/op
                 listUser·p1.00:   14.172 ms/op

Iteration   2: 3.779 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.039 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  12.245 ms/op
                 listUser·p0.9999: 13.509 ms/op
                 listUser·p1.00:   14.746 ms/op

Iteration   3: 3.862 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  13.523 ms/op
                 listUser·p0.9999: 17.086 ms/op
                 listUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250386
  mean =      3.832 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 3451 
    [ 2.500,  3.750) = 120792 
    [ 3.750,  5.000) = 112587 
    [ 5.000,  6.250) = 9260 
    [ 6.250,  7.500) = 3374 
    [ 7.500,  8.750) = 319 
    [ 8.750, 10.000) = 162 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 165 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     16.377 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.277 ± 3.182  ops/ms
ClientGrpc.existUser                       thrpt       3  10.768 ± 2.188  ops/ms
ClientGrpc.getUser                         thrpt       3  10.204 ± 3.772  ops/ms
ClientGrpc.listUser                        thrpt       3   8.409 ± 0.415  ops/ms
ClientGrpc.createUser                       avgt       3   3.115 ± 0.683   ms/op
ClientGrpc.existUser                        avgt       3   2.971 ± 0.540   ms/op
ClientGrpc.getUser                          avgt       3   3.107 ± 0.511   ms/op
ClientGrpc.listUser                         avgt       3   3.820 ± 1.024   ms/op
ClientGrpc.createUser                     sample  309490   3.102 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.538           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.650           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.938           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.526           ms/op
ClientGrpc.existUser                      sample  320751   2.995 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.674           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.829           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.152           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.908           ms/op
ClientGrpc.getUser                        sample  311388   3.083 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.588           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.471           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.677           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.170           ms/op
ClientGrpc.listUser                       sample  250386   3.832 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.014           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.284           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.513           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.452           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.377           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          17.367           ms/op
