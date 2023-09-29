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
# Warmup Iteration   1: 4.353 ops/ms
# Warmup Iteration   2: 8.816 ops/ms
# Warmup Iteration   3: 9.512 ops/ms
Iteration   1: 10.125 ops/ms
Iteration   2: 10.012 ops/ms
Iteration   3: 10.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.088 ±(99.9%) 1.207 ops/ms [Average]
  (min, avg, max) = (10.012, 10.088, 10.128), stdev = 0.066
  CI (99.9%): [8.882, 11.295] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.537 ops/ms
# Warmup Iteration   2: 10.257 ops/ms
# Warmup Iteration   3: 10.555 ops/ms
Iteration   1: 10.576 ops/ms
Iteration   2: 10.493 ops/ms
Iteration   3: 10.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.547 ±(99.9%) 0.842 ops/ms [Average]
  (min, avg, max) = (10.493, 10.547, 10.576), stdev = 0.046
  CI (99.9%): [9.705, 11.389] (assumes normal distribution)


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
# Warmup Iteration   1: 7.348 ops/ms
# Warmup Iteration   2: 9.731 ops/ms
# Warmup Iteration   3: 10.144 ops/ms
Iteration   1: 10.193 ops/ms
Iteration   2: 10.320 ops/ms
Iteration   3: 9.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.160 ±(99.9%) 3.267 ops/ms [Average]
  (min, avg, max) = (9.967, 10.160, 10.320), stdev = 0.179
  CI (99.9%): [6.893, 13.427] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.619 ops/ms
# Warmup Iteration   2: 8.045 ops/ms
# Warmup Iteration   3: 8.090 ops/ms
Iteration   1: 8.291 ops/ms
Iteration   2: 8.361 ops/ms
Iteration   3: 8.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.268 ±(99.9%) 1.950 ops/ms [Average]
  (min, avg, max) = (8.151, 8.268, 8.361), stdev = 0.107
  CI (99.9%): [6.317, 10.218] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.034 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.001 ms/op
Iteration   1: 3.132 ±(99.9%) 0.023 ms/op
Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
Iteration   3: 3.125 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.102 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (3.051, 3.102, 3.132), stdev = 0.045
  CI (99.9%): [2.285, 3.920] (assumes normal distribution)


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.081 ±(99.9%) 0.001 ms/op
Iteration   2: 3.052 ±(99.9%) 0.003 ms/op
Iteration   3: 3.034 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.056 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (3.034, 3.056, 3.081), stdev = 0.024
  CI (99.9%): [2.623, 3.489] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.374 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.002 ms/op
Iteration   1: 3.118 ±(99.9%) 0.002 ms/op
Iteration   2: 3.163 ±(99.9%) 0.002 ms/op
Iteration   3: 3.106 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.129 ±(99.9%) 0.543 ms/op [Average]
  (min, avg, max) = (3.106, 3.129, 3.163), stdev = 0.030
  CI (99.9%): [2.586, 3.673] (assumes normal distribution)


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
# Warmup Iteration   1: 5.395 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.018 ms/op
Iteration   1: 3.872 ±(99.9%) 0.012 ms/op
Iteration   2: 3.833 ±(99.9%) 0.030 ms/op
Iteration   3: 3.664 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.789 ±(99.9%) 2.019 ms/op [Average]
  (min, avg, max) = (3.664, 3.789, 3.872), stdev = 0.111
  CI (99.9%): [1.770, 5.808] (assumes normal distribution)


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.005 ms/op
Iteration   1: 3.121 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.359 ms/op
                 createUser·p0.999:  6.650 ms/op
                 createUser·p0.9999: 15.511 ms/op
                 createUser·p1.00:   15.909 ms/op

Iteration   2: 3.182 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.765 ms/op
                 createUser·p0.9999: 16.350 ms/op
                 createUser·p1.00:   16.761 ms/op

Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.608 ms/op
                 createUser·p0.999:  10.891 ms/op
                 createUser·p0.9999: 17.334 ms/op
                 createUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306740
  mean =      3.130 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1326 
    [ 1.250,  2.500) = 11251 
    [ 2.500,  3.750) = 266340 
    [ 3.750,  5.000) = 26099 
    [ 5.000,  6.250) = 966 
    [ 6.250,  7.500) = 316 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 72 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      9.765 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     17.491 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.005 ms/op
Iteration   1: 2.980 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.911 ms/op
                 existUser·p0.9999: 11.093 ms/op
                 existUser·p1.00:   11.731 ms/op

Iteration   2: 3.027 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.156 ms/op
                 existUser·p0.999:  8.739 ms/op
                 existUser·p0.9999: 13.187 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  10.497 ms/op
                 existUser·p0.9999: 16.574 ms/op
                 existUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317278
  mean =      3.024 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1314 
    [ 1.250,  2.500) = 18637 
    [ 2.500,  3.750) = 277608 
    [ 3.750,  5.000) = 18243 
    [ 5.000,  6.250) = 740 
    [ 6.250,  7.500) = 293 
    [ 7.500,  8.750) = 131 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     16.073 ms/op
     p(99.9990) =     17.022 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.006 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.990 ms/op
                 getUser·p0.9999: 11.665 ms/op
                 getUser·p1.00:   11.911 ms/op

Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  9.585 ms/op
                 getUser·p0.9999: 12.698 ms/op
                 getUser·p1.00:   13.337 ms/op

Iteration   3: 3.184 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.970 ms/op
                 getUser·p0.9999: 14.645 ms/op
                 getUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303955
  mean =      3.156 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 667 
    [ 1.250,  2.500) = 10807 
    [ 2.500,  3.750) = 263207 
    [ 3.750,  5.000) = 27207 
    [ 5.000,  6.250) = 1009 
    [ 6.250,  7.500) = 480 
    [ 7.500,  8.750) = 279 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     13.930 ms/op
     p(99.9990) =     15.956 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 5.051 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.011 ms/op
Iteration   1: 4.088 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  13.607 ms/op
                 listUser·p0.9999: 15.535 ms/op
                 listUser·p1.00:   16.024 ms/op

Iteration   2: 4.028 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.296 ms/op
                 listUser·p0.9999: 17.289 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 4.006 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 18.908 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237521
  mean =      4.040 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 2326 
    [ 2.500,  3.750) = 70247 
    [ 3.750,  5.000) = 148987 
    [ 5.000,  6.250) = 9977 
    [ 6.250,  7.500) = 4978 
    [ 7.500,  8.750) = 374 
    [ 8.750, 10.000) = 166 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 148 
    [15.000, 16.250) = 106 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     17.433 ms/op
     p(99.9990) =     19.395 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.088 ± 1.207  ops/ms
ClientGrpc.existUser                       thrpt       3  10.547 ± 0.842  ops/ms
ClientGrpc.getUser                         thrpt       3  10.160 ± 3.267  ops/ms
ClientGrpc.listUser                        thrpt       3   8.268 ± 1.950  ops/ms
ClientGrpc.createUser                       avgt       3   3.102 ± 0.817   ms/op
ClientGrpc.existUser                        avgt       3   3.056 ± 0.433   ms/op
ClientGrpc.getUser                          avgt       3   3.129 ± 0.543   ms/op
ClientGrpc.listUser                         avgt       3   3.789 ± 2.019   ms/op
ClientGrpc.createUser                     sample  306740   3.130 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.696           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.765           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.105           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.564           ms/op
ClientGrpc.existUser                      sample  317278   3.024 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.540           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.982           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.716           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.073           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.433           ms/op
ClientGrpc.getUser                        sample  303955   3.156 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.598           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.113           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.667           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.930           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.056           ms/op
ClientGrpc.listUser                       sample  237521   4.040 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.942           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.949           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.303           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.433           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.497           ms/op
