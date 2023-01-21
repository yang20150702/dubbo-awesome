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
# Warmup Iteration   1: 4.891 ops/ms
# Warmup Iteration   2: 9.843 ops/ms
# Warmup Iteration   3: 10.440 ops/ms
Iteration   1: 10.808 ops/ms
Iteration   2: 10.455 ops/ms
Iteration   3: 10.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.627 ±(99.9%) 3.216 ops/ms [Average]
  (min, avg, max) = (10.455, 10.627, 10.808), stdev = 0.176
  CI (99.9%): [7.411, 13.844] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.761 ops/ms
# Warmup Iteration   2: 10.769 ops/ms
# Warmup Iteration   3: 10.795 ops/ms
Iteration   1: 10.777 ops/ms
Iteration   2: 10.706 ops/ms
Iteration   3: 10.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.789 ±(99.9%) 1.628 ops/ms [Average]
  (min, avg, max) = (10.706, 10.789, 10.883), stdev = 0.089
  CI (99.9%): [9.161, 12.417] (assumes normal distribution)


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
# Warmup Iteration   1: 7.719 ops/ms
# Warmup Iteration   2: 10.345 ops/ms
# Warmup Iteration   3: 10.462 ops/ms
Iteration   1: 10.417 ops/ms
Iteration   2: 10.274 ops/ms
Iteration   3: 10.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.337 ±(99.9%) 1.329 ops/ms [Average]
  (min, avg, max) = (10.274, 10.337, 10.417), stdev = 0.073
  CI (99.9%): [9.008, 11.666] (assumes normal distribution)


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
# Warmup Iteration   1: 6.281 ops/ms
# Warmup Iteration   2: 7.867 ops/ms
# Warmup Iteration   3: 8.375 ops/ms
Iteration   1: 8.199 ops/ms
Iteration   2: 8.040 ops/ms
Iteration   3: 8.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.188 ±(99.9%) 2.613 ops/ms [Average]
  (min, avg, max) = (8.040, 8.188, 8.326), stdev = 0.143
  CI (99.9%): [5.575, 10.802] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.038 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.002 ms/op
Iteration   1: 3.197 ±(99.9%) 0.002 ms/op
Iteration   2: 3.044 ±(99.9%) 0.002 ms/op
Iteration   3: 3.188 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.143 ±(99.9%) 1.563 ms/op [Average]
  (min, avg, max) = (3.044, 3.143, 3.197), stdev = 0.086
  CI (99.9%): [1.580, 4.706] (assumes normal distribution)


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.004 ms/op
Iteration   1: 2.965 ±(99.9%) 0.002 ms/op
Iteration   2: 2.881 ±(99.9%) 0.002 ms/op
Iteration   3: 2.955 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.934 ±(99.9%) 0.830 ms/op [Average]
  (min, avg, max) = (2.881, 2.934, 2.965), stdev = 0.045
  CI (99.9%): [2.104, 3.764] (assumes normal distribution)


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.004 ms/op
Iteration   1: 2.977 ±(99.9%) 0.003 ms/op
Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
Iteration   3: 3.109 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.039 ±(99.9%) 1.205 ms/op [Average]
  (min, avg, max) = (2.977, 3.039, 3.109), stdev = 0.066
  CI (99.9%): [1.834, 4.243] (assumes normal distribution)


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
# Warmup Iteration   1: 5.191 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.033 ms/op
Iteration   1: 3.972 ±(99.9%) 0.021 ms/op
Iteration   2: 3.768 ±(99.9%) 0.006 ms/op
Iteration   3: 3.895 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.878 ±(99.9%) 1.877 ms/op [Average]
  (min, avg, max) = (3.768, 3.878, 3.972), stdev = 0.103
  CI (99.9%): [2.001, 5.755] (assumes normal distribution)


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.104 ms/op
                 createUser·p0.999:  6.848 ms/op
                 createUser·p0.9999: 12.878 ms/op
                 createUser·p1.00:   13.386 ms/op

Iteration   2: 3.143 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  11.305 ms/op
                 createUser·p0.9999: 15.751 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 3.120 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  14.328 ms/op
                 createUser·p0.9999: 24.125 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310697
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24038 
    [ 2.500,  5.000) = 285755 
    [ 5.000,  7.500) = 493 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.884 ms/op
     p(99.9900) =     23.228 ms/op
     p(99.9990) =     26.853 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 3.638 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
Iteration   1: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  5.989 ms/op
                 existUser·p0.9999: 11.078 ms/op
                 existUser·p1.00:   11.469 ms/op

Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  7.785 ms/op
                 existUser·p0.9999: 17.112 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.500 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  7.735 ms/op
                 existUser·p0.9999: 17.332 ms/op
                 existUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324269
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2589 
    [ 1.250,  2.500) = 48287 
    [ 2.500,  3.750) = 251780 
    [ 3.750,  5.000) = 20795 
    [ 5.000,  6.250) = 306 
    [ 6.250,  7.500) = 214 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      7.373 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     17.490 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.126 ms/op
                 getUser·p0.9999: 16.728 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.322 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  9.907 ms/op
                 getUser·p0.9999: 15.385 ms/op
                 getUser·p1.00:   16.482 ms/op

Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.275 ms/op
                 getUser·p0.9999: 22.472 ms/op
                 getUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318451
  mean =      3.014 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33837 
    [ 2.500,  5.000) = 283781 
    [ 5.000,  7.500) = 540 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.322 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.009 ms/op
     p(99.9900) =     19.862 ms/op
     p(99.9990) =     23.640 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 4.937 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.010 ms/op
Iteration   1: 3.814 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.469 ms/op
                 listUser·p0.999:  12.913 ms/op
                 listUser·p0.9999: 16.083 ms/op
                 listUser·p1.00:   16.663 ms/op

Iteration   2: 3.940 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.587 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  12.791 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 3.972 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  13.924 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245653
  mean =      3.907 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3499 
    [ 2.500,  5.000) = 219250 
    [ 5.000,  7.500) = 21963 
    [ 7.500, 10.000) = 507 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     19.544 ms/op
     p(99.9990) =     20.221 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.627 ± 3.216  ops/ms
ClientGrpc.existUser                       thrpt       3  10.789 ± 1.628  ops/ms
ClientGrpc.getUser                         thrpt       3  10.337 ± 1.329  ops/ms
ClientGrpc.listUser                        thrpt       3   8.188 ± 2.613  ops/ms
ClientGrpc.createUser                       avgt       3   3.143 ± 1.563   ms/op
ClientGrpc.existUser                        avgt       3   2.934 ± 0.830   ms/op
ClientGrpc.getUser                          avgt       3   3.039 ± 1.205   ms/op
ClientGrpc.listUser                         avgt       3   3.878 ± 1.877   ms/op
ClientGrpc.createUser                     sample  310697   3.087 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.558           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.884           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.228           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.034           ms/op
ClientGrpc.existUser                      sample  324269   2.961 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.500           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.373           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.908           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.531           ms/op
ClientGrpc.getUser                        sample  318451   3.014 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.322           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.009           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.862           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.757           ms/op
ClientGrpc.listUser                       sample  245653   3.907 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.587           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.595           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.189           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.544           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.316           ms/op
