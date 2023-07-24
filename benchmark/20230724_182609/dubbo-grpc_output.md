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
# Warmup Iteration   1: 4.322 ops/ms
# Warmup Iteration   2: 9.118 ops/ms
# Warmup Iteration   3: 10.373 ops/ms
Iteration   1: 11.060 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.692 ±(99.9%) 5.999 ops/ms [Average]
  (min, avg, max) = (10.427, 10.692, 11.060), stdev = 0.329
  CI (99.9%): [4.693, 16.692] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.038 ops/ms
# Warmup Iteration   2: 10.882 ops/ms
# Warmup Iteration   3: 11.252 ops/ms
Iteration   1: 11.444 ops/ms
Iteration   2: 11.158 ops/ms
Iteration   3: 11.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.284 ±(99.9%) 2.658 ops/ms [Average]
  (min, avg, max) = (11.158, 11.284, 11.444), stdev = 0.146
  CI (99.9%): [8.626, 13.942] (assumes normal distribution)


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
# Warmup Iteration   1: 7.455 ops/ms
# Warmup Iteration   2: 10.669 ops/ms
# Warmup Iteration   3: 10.905 ops/ms
Iteration   1: 10.619 ops/ms
Iteration   2: 10.655 ops/ms
Iteration   3: 10.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.680 ±(99.9%) 1.390 ops/ms [Average]
  (min, avg, max) = (10.619, 10.680, 10.765), stdev = 0.076
  CI (99.9%): [9.290, 12.069] (assumes normal distribution)


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
# Warmup Iteration   1: 6.111 ops/ms
# Warmup Iteration   2: 7.921 ops/ms
# Warmup Iteration   3: 8.205 ops/ms
Iteration   1: 7.993 ops/ms
Iteration   2: 8.159 ops/ms
Iteration   3: 8.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.090 ±(99.9%) 1.576 ops/ms [Average]
  (min, avg, max) = (7.993, 8.090, 8.159), stdev = 0.086
  CI (99.9%): [6.515, 9.666] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.256 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.003 ms/op
Iteration   1: 2.996 ±(99.9%) 0.003 ms/op
Iteration   2: 2.940 ±(99.9%) 0.002 ms/op
Iteration   3: 2.911 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.949 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (2.911, 2.949, 2.996), stdev = 0.043
  CI (99.9%): [2.163, 3.735] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.707 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.920 ±(99.9%) 0.003 ms/op
Iteration   1: 2.865 ±(99.9%) 0.004 ms/op
Iteration   2: 2.829 ±(99.9%) 0.003 ms/op
Iteration   3: 2.824 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.839 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (2.824, 2.839, 2.865), stdev = 0.023
  CI (99.9%): [2.425, 3.254] (assumes normal distribution)


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.002 ms/op
Iteration   1: 2.992 ±(99.9%) 0.002 ms/op
Iteration   2: 2.961 ±(99.9%) 0.002 ms/op
Iteration   3: 2.981 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.978 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.961, 2.978, 2.992), stdev = 0.016
  CI (99.9%): [2.693, 3.262] (assumes normal distribution)


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.012 ms/op
Iteration   1: 3.949 ±(99.9%) 0.013 ms/op
Iteration   2: 3.961 ±(99.9%) 0.015 ms/op
Iteration   3: 3.934 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.948 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (3.934, 3.948, 3.961), stdev = 0.014
  CI (99.9%): [3.698, 4.198] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
Iteration   1: 2.972 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.245 ms/op
                 createUser·p0.9999: 17.735 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   2: 2.966 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.620 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.547 ms/op
                 createUser·p0.9999: 13.025 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  9.401 ms/op
                 createUser·p0.9999: 17.775 ms/op
                 createUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322666
  mean =      2.975 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1768 
    [ 1.250,  2.500) = 26998 
    [ 2.500,  3.750) = 281246 
    [ 3.750,  5.000) = 11556 
    [ 5.000,  6.250) = 498 
    [ 6.250,  7.500) = 198 
    [ 7.500,  8.750) = 101 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.334 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     18.212 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.006 ms/op
Iteration   1: 2.899 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.516 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.418 ms/op
                 existUser·p0.999:  6.506 ms/op
                 existUser·p0.9999: 11.370 ms/op
                 existUser·p1.00:   11.764 ms/op

Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.486 ms/op
                 existUser·p0.9999: 23.206 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   3: 2.880 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.427 ms/op
                 existUser·p0.999:  9.059 ms/op
                 existUser·p0.9999: 26.571 ms/op
                 existUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329711
  mean =      2.911 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45469 
    [ 2.500,  5.000) = 283233 
    [ 5.000,  7.500) = 667 
    [ 7.500, 10.000) = 113 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.569 ms/op
     p(99.9900) =     23.633 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 3.958 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  8.680 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   2: 2.922 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.326 ms/op
                 getUser·p0.95:   3.523 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.857 ms/op
                 getUser·p0.9999: 19.470 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   3: 3.023 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.393 ms/op
                 getUser·p0.9999: 15.286 ms/op
                 getUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322434
  mean =      2.976 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1902 
    [ 1.250,  2.500) = 22013 
    [ 2.500,  3.750) = 286699 
    [ 3.750,  5.000) = 10630 
    [ 5.000,  6.250) = 546 
    [ 6.250,  7.500) = 308 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.934 ms/op
     p(99.9900) =     19.096 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 5.312 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.010 ms/op
Iteration   1: 3.887 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  13.074 ms/op
                 listUser·p0.9999: 19.351 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 3.943 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  13.335 ms/op
                 listUser·p0.9999: 16.044 ms/op
                 listUser·p1.00:   16.728 ms/op

Iteration   3: 3.983 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   7.116 ms/op
                 listUser·p0.999:  20.546 ms/op
                 listUser·p0.9999: 31.717 ms/op
                 listUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243796
  mean =      3.937 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4283 
    [ 2.500,  5.000) = 218445 
    [ 5.000,  7.500) = 19883 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     13.831 ms/op
     p(99.9900) =     31.105 ms/op
     p(99.9990) =     32.074 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.692 ± 5.999  ops/ms
ClientGrpc.existUser                       thrpt       3  11.284 ± 2.658  ops/ms
ClientGrpc.getUser                         thrpt       3  10.680 ± 1.390  ops/ms
ClientGrpc.listUser                        thrpt       3   8.090 ± 1.576  ops/ms
ClientGrpc.createUser                       avgt       3   2.949 ± 0.786   ms/op
ClientGrpc.existUser                        avgt       3   2.839 ± 0.414   ms/op
ClientGrpc.getUser                          avgt       3   2.978 ± 0.285   ms/op
ClientGrpc.listUser                         avgt       3   3.948 ± 0.250   ms/op
ClientGrpc.createUser                     sample  322666   2.975 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.620           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.334           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.596           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.383           ms/op
ClientGrpc.existUser                      sample  329711   2.911 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.516           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.569           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.633           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.197           ms/op
ClientGrpc.getUser                        sample  322434   2.976 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.625           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.400           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.934           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.096           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.825           ms/op
ClientGrpc.listUser                       sample  243796   3.937 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.919           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.831           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.105           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.178           ms/op
