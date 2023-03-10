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
# Warmup Iteration   1: 4.713 ops/ms
# Warmup Iteration   2: 9.337 ops/ms
# Warmup Iteration   3: 10.251 ops/ms
Iteration   1: 10.766 ops/ms
Iteration   2: 10.897 ops/ms
Iteration   3: 10.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.884 ±(99.9%) 2.031 ops/ms [Average]
  (min, avg, max) = (10.766, 10.884, 10.988), stdev = 0.111
  CI (99.9%): [8.852, 12.915] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.520 ops/ms
# Warmup Iteration   2: 11.018 ops/ms
# Warmup Iteration   3: 11.310 ops/ms
Iteration   1: 11.357 ops/ms
Iteration   2: 11.369 ops/ms
Iteration   3: 11.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.356 ±(99.9%) 0.253 ops/ms [Average]
  (min, avg, max) = (11.341, 11.356, 11.369), stdev = 0.014
  CI (99.9%): [11.103, 11.609] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.075 ops/ms
# Warmup Iteration   2: 10.311 ops/ms
# Warmup Iteration   3: 10.798 ops/ms
Iteration   1: 11.009 ops/ms
Iteration   2: 10.742 ops/ms
Iteration   3: 10.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.815 ±(99.9%) 3.092 ops/ms [Average]
  (min, avg, max) = (10.694, 10.815, 11.009), stdev = 0.169
  CI (99.9%): [7.723, 13.907] (assumes normal distribution)


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
# Warmup Iteration   1: 5.705 ops/ms
# Warmup Iteration   2: 8.104 ops/ms
# Warmup Iteration   3: 8.123 ops/ms
Iteration   1: 8.227 ops/ms
Iteration   2: 8.252 ops/ms
Iteration   3: 8.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.240 ±(99.9%) 0.224 ops/ms [Average]
  (min, avg, max) = (8.227, 8.240, 8.252), stdev = 0.012
  CI (99.9%): [8.016, 8.465] (assumes normal distribution)


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
# Warmup Iteration   1: 4.532 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.004 ms/op
Iteration   1: 2.994 ±(99.9%) 0.003 ms/op
Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
Iteration   3: 3.021 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.997 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.975, 2.997, 3.021), stdev = 0.023
  CI (99.9%): [2.570, 3.423] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.475 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.899 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.833 ±(99.9%) 0.003 ms/op
Iteration   1: 2.793 ±(99.9%) 0.005 ms/op
Iteration   2: 2.770 ±(99.9%) 0.004 ms/op
Iteration   3: 2.788 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.783 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (2.770, 2.783, 2.793), stdev = 0.012
  CI (99.9%): [2.565, 3.001] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.707 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.002 ms/op
Iteration   1: 3.014 ±(99.9%) 0.001 ms/op
Iteration   2: 3.038 ±(99.9%) 0.004 ms/op
Iteration   3: 2.971 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.008 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (2.971, 3.008, 3.038), stdev = 0.034
  CI (99.9%): [2.383, 3.632] (assumes normal distribution)


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
# Warmup Iteration   1: 5.316 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.025 ms/op
Iteration   1: 3.914 ±(99.9%) 0.010 ms/op
Iteration   2: 3.830 ±(99.9%) 0.028 ms/op
Iteration   3: 3.809 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.851 ±(99.9%) 1.013 ms/op [Average]
  (min, avg, max) = (3.809, 3.851, 3.914), stdev = 0.056
  CI (99.9%): [2.838, 4.864] (assumes normal distribution)


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 3.008 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.620 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  6.928 ms/op
                 createUser·p0.9999: 11.841 ms/op
                 createUser·p1.00:   11.960 ms/op

Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.925 ms/op
                 createUser·p0.9999: 20.694 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  11.010 ms/op
                 createUser·p0.9999: 22.358 ms/op
                 createUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317745
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25486 
    [ 2.500,  5.000) = 291125 
    [ 5.000,  7.500) = 803 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =     21.929 ms/op
     p(99.9990) =     23.105 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.006 ms/op
Iteration   1: 2.892 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  5.530 ms/op
                 existUser·p0.9999: 21.692 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   2: 2.869 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  7.513 ms/op
                 existUser·p0.9999: 12.775 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   3: 2.892 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.046 ms/op
                 existUser·p0.9999: 14.499 ms/op
                 existUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332785
  mean =      2.884 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40294 
    [ 2.500,  5.000) = 291439 
    [ 5.000,  7.500) = 816 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.655 ms/op
     p(99.9900) =     14.638 ms/op
     p(99.9990) =     22.031 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
Iteration   1: 3.014 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.151 ms/op
                 getUser·p0.9999: 13.366 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  10.624 ms/op
                 getUser·p0.9999: 14.848 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  9.306 ms/op
                 getUser·p0.9999: 16.097 ms/op
                 getUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317967
  mean =      3.019 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1491 
    [ 1.250,  2.500) = 20729 
    [ 2.500,  3.750) = 282550 
    [ 3.750,  5.000) = 11770 
    [ 5.000,  6.250) = 722 
    [ 6.250,  7.500) = 305 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      9.898 ms/op
     p(99.9900) =     15.644 ms/op
     p(99.9990) =     16.381 ms/op
     p(99.9999) =     16.499 ms/op
    p(100.0000) =     16.499 ms/op


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
# Warmup Iteration   1: 5.209 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.010 ms/op
Iteration   1: 3.906 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  12.306 ms/op
                 listUser·p0.9999: 19.261 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.834 ms/op
                 listUser·p0.999:  13.009 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 3.897 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.644 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  15.432 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245132
  mean =      3.912 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 4176 
    [ 2.500,  3.750) = 114127 
    [ 3.750,  5.000) = 105850 
    [ 5.000,  6.250) = 16143 
    [ 6.250,  7.500) = 3869 
    [ 7.500,  8.750) = 413 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 128 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     19.649 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.884 ± 2.031  ops/ms
ClientGrpc.existUser                       thrpt       3  11.356 ± 0.253  ops/ms
ClientGrpc.getUser                         thrpt       3  10.815 ± 3.092  ops/ms
ClientGrpc.listUser                        thrpt       3   8.240 ± 0.224  ops/ms
ClientGrpc.createUser                       avgt       3   2.997 ± 0.426   ms/op
ClientGrpc.existUser                        avgt       3   2.783 ± 0.218   ms/op
ClientGrpc.getUser                          avgt       3   3.008 ± 0.624   ms/op
ClientGrpc.listUser                         avgt       3   3.851 ± 1.013   ms/op
ClientGrpc.createUser                     sample  317745   3.020 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.601           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.929           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.298           ms/op
ClientGrpc.existUser                      sample  332785   2.884 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.539           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.655           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.638           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.086           ms/op
ClientGrpc.getUser                        sample  317967   3.019 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.590           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.898           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.644           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.499           ms/op
ClientGrpc.listUser                       sample  245132   3.912 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.644           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.709           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.091           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.005           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.759           ms/op
