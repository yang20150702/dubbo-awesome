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
# Warmup Iteration   1: 4.533 ops/ms
# Warmup Iteration   2: 9.078 ops/ms
# Warmup Iteration   3: 10.046 ops/ms
Iteration   1: 10.443 ops/ms
Iteration   2: 10.371 ops/ms
Iteration   3: 10.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.354 ±(99.9%) 1.812 ops/ms [Average]
  (min, avg, max) = (10.247, 10.354, 10.443), stdev = 0.099
  CI (99.9%): [8.541, 12.166] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.866 ops/ms
# Warmup Iteration   2: 10.106 ops/ms
# Warmup Iteration   3: 10.949 ops/ms
Iteration   1: 11.082 ops/ms
Iteration   2: 10.891 ops/ms
Iteration   3: 10.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.969 ±(99.9%) 1.818 ops/ms [Average]
  (min, avg, max) = (10.891, 10.969, 11.082), stdev = 0.100
  CI (99.9%): [9.151, 12.788] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.744 ops/ms
# Warmup Iteration   2: 9.949 ops/ms
# Warmup Iteration   3: 10.370 ops/ms
Iteration   1: 10.548 ops/ms
Iteration   2: 10.542 ops/ms
Iteration   3: 10.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.513 ±(99.9%) 1.025 ops/ms [Average]
  (min, avg, max) = (10.448, 10.513, 10.548), stdev = 0.056
  CI (99.9%): [9.488, 11.537] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.813 ops/ms
# Warmup Iteration   2: 7.633 ops/ms
# Warmup Iteration   3: 7.840 ops/ms
Iteration   1: 8.010 ops/ms
Iteration   2: 7.825 ops/ms
Iteration   3: 7.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.887 ±(99.9%) 1.942 ops/ms [Average]
  (min, avg, max) = (7.825, 7.887, 8.010), stdev = 0.106
  CI (99.9%): [5.944, 9.829] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.465 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.002 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
Iteration   2: 3.050 ±(99.9%) 0.004 ms/op
Iteration   3: 3.033 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.038 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (3.032, 3.038, 3.050), stdev = 0.010
  CI (99.9%): [2.855, 3.222] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.794 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.003 ms/op
Iteration   1: 2.938 ±(99.9%) 0.002 ms/op
Iteration   2: 2.839 ±(99.9%) 0.003 ms/op
Iteration   3: 2.849 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.875 ±(99.9%) 0.991 ms/op [Average]
  (min, avg, max) = (2.839, 2.875, 2.938), stdev = 0.054
  CI (99.9%): [1.884, 3.866] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.214 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.004 ms/op
Iteration   2: 3.032 ±(99.9%) 0.003 ms/op
Iteration   3: 3.083 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.057 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.032, 3.057, 3.083), stdev = 0.025
  CI (99.9%): [2.597, 3.518] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.318 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.007 ms/op
Iteration   1: 4.070 ±(99.9%) 0.013 ms/op
Iteration   2: 3.971 ±(99.9%) 0.023 ms/op
Iteration   3: 3.941 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.994 ±(99.9%) 1.234 ms/op [Average]
  (min, avg, max) = (3.941, 3.994, 4.070), stdev = 0.068
  CI (99.9%): [2.760, 5.228] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.236 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.007 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  11.264 ms/op
                 createUser·p0.9999: 15.597 ms/op
                 createUser·p1.00:   15.778 ms/op

Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  6.414 ms/op
                 createUser·p0.9999: 15.692 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  10.207 ms/op
                 createUser·p0.9999: 16.190 ms/op
                 createUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315475
  mean =      3.043 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 474 
    [ 1.250,  2.500) = 19556 
    [ 2.500,  3.750) = 279676 
    [ 3.750,  5.000) = 14136 
    [ 5.000,  6.250) = 987 
    [ 6.250,  7.500) = 232 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 148 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     15.809 ms/op
     p(99.9990) =     16.463 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.959 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.005 ms/op
Iteration   1: 2.922 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  6.025 ms/op
                 existUser·p0.9999: 12.371 ms/op
                 existUser·p1.00:   12.616 ms/op

Iteration   2: 2.788 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  6.916 ms/op
                 existUser·p0.9999: 16.754 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   3: 2.842 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  10.199 ms/op
                 existUser·p0.9999: 19.882 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336757
  mean =      2.850 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47491 
    [ 2.500,  5.000) = 288375 
    [ 5.000,  7.500) = 606 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      6.893 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     20.140 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.243 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.484 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.679 ms/op
                 getUser·p0.9999: 20.293 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   2: 3.050 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  8.269 ms/op
                 getUser·p0.9999: 29.622 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.358 ms/op
                 getUser·p0.9999: 21.208 ms/op
                 getUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316092
  mean =      3.036 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18580 
    [ 2.500,  5.000) = 296077 
    [ 5.000,  7.500) = 1111 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.673 ms/op
     p(99.9900) =     28.940 ms/op
     p(99.9990) =     29.846 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.475 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.011 ms/op
Iteration   1: 4.045 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  13.482 ms/op
                 listUser·p0.9999: 15.714 ms/op
                 listUser·p1.00:   16.712 ms/op

Iteration   2: 4.059 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.789 ms/op
                 listUser·p0.9999: 24.517 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 3.879 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  17.025 ms/op
                 listUser·p0.9999: 25.462 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240431
  mean =      3.993 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1554 
    [ 2.500,  5.000) = 214900 
    [ 5.000,  7.500) = 22460 
    [ 7.500, 10.000) = 1030 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.640 ms/op
     p(99.9900) =     24.837 ms/op
     p(99.9990) =     25.795 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.354 ± 1.812  ops/ms
ClientGrpc.existUser                       thrpt       3  10.969 ± 1.818  ops/ms
ClientGrpc.getUser                         thrpt       3  10.513 ± 1.025  ops/ms
ClientGrpc.listUser                        thrpt       3   7.887 ± 1.942  ops/ms
ClientGrpc.createUser                       avgt       3   3.038 ± 0.183   ms/op
ClientGrpc.existUser                        avgt       3   2.875 ± 0.991   ms/op
ClientGrpc.getUser                          avgt       3   3.057 ± 0.460   ms/op
ClientGrpc.listUser                         avgt       3   3.994 ± 1.234   ms/op
ClientGrpc.createUser                     sample  315475   3.043 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.585           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.060           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.809           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.548           ms/op
ClientGrpc.existUser                      sample  336757   2.850 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.641           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.893           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.777           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.398           ms/op
ClientGrpc.getUser                        sample  316092   3.036 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.530           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.673           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.940           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.884           ms/op
ClientGrpc.listUser                       sample  240431   3.993 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.907           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.640           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.837           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.919           ms/op
