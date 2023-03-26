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
# Warmup Iteration   1: 4.204 ops/ms
# Warmup Iteration   2: 8.851 ops/ms
# Warmup Iteration   3: 10.146 ops/ms
Iteration   1: 10.726 ops/ms
Iteration   2: 10.387 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.548 ±(99.9%) 3.108 ops/ms [Average]
  (min, avg, max) = (10.387, 10.548, 10.726), stdev = 0.170
  CI (99.9%): [7.440, 13.656] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.760 ops/ms
# Warmup Iteration   2: 10.661 ops/ms
# Warmup Iteration   3: 11.082 ops/ms
Iteration   1: 11.085 ops/ms
Iteration   2: 11.267 ops/ms
Iteration   3: 11.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.164 ±(99.9%) 1.707 ops/ms [Average]
  (min, avg, max) = (11.085, 11.164, 11.267), stdev = 0.094
  CI (99.9%): [9.457, 12.872] (assumes normal distribution)


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
# Warmup Iteration   1: 6.912 ops/ms
# Warmup Iteration   2: 10.094 ops/ms
# Warmup Iteration   3: 10.637 ops/ms
Iteration   1: 10.587 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.660 ±(99.9%) 1.170 ops/ms [Average]
  (min, avg, max) = (10.587, 10.660, 10.707), stdev = 0.064
  CI (99.9%): [9.491, 11.830] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.704 ops/ms
# Warmup Iteration   2: 7.833 ops/ms
# Warmup Iteration   3: 8.090 ops/ms
Iteration   1: 8.101 ops/ms
Iteration   2: 8.137 ops/ms
Iteration   3: 8.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.109 ±(99.9%) 0.458 ops/ms [Average]
  (min, avg, max) = (8.089, 8.109, 8.137), stdev = 0.025
  CI (99.9%): [7.651, 8.567] (assumes normal distribution)


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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.002 ms/op
Iteration   1: 2.980 ±(99.9%) 0.003 ms/op
Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
Iteration   3: 2.993 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.018 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (2.980, 3.018, 3.082), stdev = 0.055
  CI (99.9%): [2.008, 4.029] (assumes normal distribution)


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.003 ms/op
Iteration   1: 2.882 ±(99.9%) 0.002 ms/op
Iteration   2: 2.871 ±(99.9%) 0.004 ms/op
Iteration   3: 2.860 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.871 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (2.860, 2.871, 2.882), stdev = 0.011
  CI (99.9%): [2.670, 3.072] (assumes normal distribution)


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.003 ms/op
Iteration   1: 2.980 ±(99.9%) 0.005 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 2.987 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.989 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (2.980, 2.989, 2.999), stdev = 0.010
  CI (99.9%): [2.809, 3.169] (assumes normal distribution)


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
# Warmup Iteration   1: 4.656 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.012 ms/op
Iteration   1: 3.894 ±(99.9%) 0.019 ms/op
Iteration   2: 3.925 ±(99.9%) 0.020 ms/op
Iteration   3: 3.886 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.902 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (3.886, 3.902, 3.925), stdev = 0.021
  CI (99.9%): [3.526, 4.278] (assumes normal distribution)


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.341 ms/op
                 createUser·p0.9999: 13.843 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.962 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  7.380 ms/op
                 createUser·p0.9999: 26.522 ms/op
                 createUser·p1.00:   27.099 ms/op

Iteration   3: 2.916 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.473 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  11.249 ms/op
                 createUser·p0.9999: 27.755 ms/op
                 createUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323259
  mean =      2.971 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30340 
    [ 2.500,  5.000) = 291352 
    [ 5.000,  7.500) = 1197 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      9.122 ms/op
     p(99.9900) =     27.143 ms/op
     p(99.9990) =     27.918 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.005 ms/op
Iteration   1: 2.871 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.386 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  5.991 ms/op
                 existUser·p0.9999: 15.696 ms/op
                 existUser·p1.00:   16.663 ms/op

Iteration   2: 2.847 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.101 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  6.308 ms/op
                 existUser·p0.9999: 18.998 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   3: 2.931 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  7.082 ms/op
                 existUser·p0.9999: 16.534 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333024
  mean =      2.883 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 571 
    [ 1.250,  2.500) = 35774 
    [ 2.500,  3.750) = 291920 
    [ 3.750,  5.000) = 4082 
    [ 5.000,  6.250) = 276 
    [ 6.250,  7.500) = 176 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.386 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.469 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      6.488 ms/op
     p(99.9900) =     16.977 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 2.960 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.367 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.547 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.501 ms/op
                 getUser·p0.9999: 12.144 ms/op
                 getUser·p1.00:   12.435 ms/op

Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  6.627 ms/op
                 getUser·p0.9999: 15.486 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   3: 2.970 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.307 ms/op
                 getUser·p0.999:  6.106 ms/op
                 getUser·p0.9999: 17.349 ms/op
                 getUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323176
  mean =      2.970 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 553 
    [ 1.250,  2.500) = 25142 
    [ 2.500,  3.750) = 287065 
    [ 3.750,  5.000) = 9151 
    [ 5.000,  6.250) = 744 
    [ 6.250,  7.500) = 267 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.367 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.929 ms/op
     p(99.9900) =     16.761 ms/op
     p(99.9990) =     17.614 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 5.685 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.010 ms/op
Iteration   1: 3.921 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  13.786 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   2: 3.796 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  16.019 ms/op
                 listUser·p0.9999: 18.303 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 3.866 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 20.781 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248588
  mean =      3.861 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3782 
    [ 2.500,  5.000) = 225858 
    [ 5.000,  7.500) = 17916 
    [ 7.500, 10.000) = 588 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     15.572 ms/op
     p(99.9900) =     21.046 ms/op
     p(99.9990) =     24.639 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.548 ± 3.108  ops/ms
ClientGrpc.existUser                       thrpt       3  11.164 ± 1.707  ops/ms
ClientGrpc.getUser                         thrpt       3  10.660 ± 1.170  ops/ms
ClientGrpc.listUser                        thrpt       3   8.109 ± 0.458  ops/ms
ClientGrpc.createUser                       avgt       3   3.018 ± 1.011   ms/op
ClientGrpc.existUser                        avgt       3   2.871 ± 0.201   ms/op
ClientGrpc.getUser                          avgt       3   2.989 ± 0.180   ms/op
ClientGrpc.listUser                         avgt       3   3.902 ± 0.376   ms/op
ClientGrpc.createUser                     sample  323259   2.971 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.726           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.432           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.122           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.143           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.049           ms/op
ClientGrpc.existUser                      sample  333024   2.883 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.386           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.488           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.977           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.366           ms/op
ClientGrpc.getUser                        sample  323176   2.970 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.367           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.945           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.412           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.929           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.761           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.727           ms/op
ClientGrpc.listUser                       sample  248588   3.861 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.112           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.572           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.046           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.264           ms/op
