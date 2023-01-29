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
# Warmup Iteration   1: 5.021 ops/ms
# Warmup Iteration   2: 9.713 ops/ms
# Warmup Iteration   3: 10.304 ops/ms
Iteration   1: 10.516 ops/ms
Iteration   2: 10.228 ops/ms
Iteration   3: 10.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.348 ±(99.9%) 2.736 ops/ms [Average]
  (min, avg, max) = (10.228, 10.348, 10.516), stdev = 0.150
  CI (99.9%): [7.612, 13.084] (assumes normal distribution)


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
# Warmup Iteration   1: 8.191 ops/ms
# Warmup Iteration   2: 10.860 ops/ms
# Warmup Iteration   3: 10.982 ops/ms
Iteration   1: 10.986 ops/ms
Iteration   2: 10.901 ops/ms
Iteration   3: 11.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.984 ±(99.9%) 1.494 ops/ms [Average]
  (min, avg, max) = (10.901, 10.984, 11.065), stdev = 0.082
  CI (99.9%): [9.490, 12.477] (assumes normal distribution)


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
# Warmup Iteration   1: 7.632 ops/ms
# Warmup Iteration   2: 10.279 ops/ms
# Warmup Iteration   3: 10.531 ops/ms
Iteration   1: 10.408 ops/ms
Iteration   2: 10.558 ops/ms
Iteration   3: 10.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.491 ±(99.9%) 1.390 ops/ms [Average]
  (min, avg, max) = (10.408, 10.491, 10.558), stdev = 0.076
  CI (99.9%): [9.101, 11.881] (assumes normal distribution)


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
# Warmup Iteration   1: 6.084 ops/ms
# Warmup Iteration   2: 7.706 ops/ms
# Warmup Iteration   3: 7.928 ops/ms
Iteration   1: 8.073 ops/ms
Iteration   2: 7.906 ops/ms
Iteration   3: 8.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.073 ±(99.9%) 3.055 ops/ms [Average]
  (min, avg, max) = (7.906, 8.073, 8.241), stdev = 0.167
  CI (99.9%): [5.018, 11.129] (assumes normal distribution)


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.002 ms/op
Iteration   1: 3.154 ±(99.9%) 0.008 ms/op
Iteration   2: 3.134 ±(99.9%) 0.001 ms/op
Iteration   3: 3.025 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.104 ±(99.9%) 1.269 ms/op [Average]
  (min, avg, max) = (3.025, 3.104, 3.154), stdev = 0.070
  CI (99.9%): [1.836, 4.373] (assumes normal distribution)


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
# Warmup Iteration   1: 3.518 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.944 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.002 ms/op
Iteration   1: 2.973 ±(99.9%) 0.002 ms/op
Iteration   2: 2.867 ±(99.9%) 0.003 ms/op
Iteration   3: 2.950 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.930 ±(99.9%) 1.021 ms/op [Average]
  (min, avg, max) = (2.867, 2.930, 2.973), stdev = 0.056
  CI (99.9%): [1.909, 3.950] (assumes normal distribution)


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.004 ms/op
Iteration   1: 3.029 ±(99.9%) 0.002 ms/op
Iteration   2: 3.140 ±(99.9%) 0.003 ms/op
Iteration   3: 3.113 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.094 ±(99.9%) 1.057 ms/op [Average]
  (min, avg, max) = (3.029, 3.094, 3.140), stdev = 0.058
  CI (99.9%): [2.037, 4.151] (assumes normal distribution)


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
# Warmup Iteration   1: 4.965 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.027 ms/op
Iteration   1: 3.982 ±(99.9%) 0.034 ms/op
Iteration   2: 3.910 ±(99.9%) 0.018 ms/op
Iteration   3: 3.971 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.954 ±(99.9%) 0.709 ms/op [Average]
  (min, avg, max) = (3.910, 3.954, 3.982), stdev = 0.039
  CI (99.9%): [3.245, 4.663] (assumes normal distribution)


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
# Warmup Iteration   1: 3.686 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
Iteration   1: 3.161 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.207 ms/op
                 createUser·p0.9999: 21.557 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   2: 3.079 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 14.084 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  8.035 ms/op
                 createUser·p0.9999: 25.535 ms/op
                 createUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308939
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30345 
    [ 2.500,  5.000) = 277549 
    [ 5.000,  7.500) = 656 
    [ 7.500, 10.000) = 193 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      8.036 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     25.818 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 2.949 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.106 ms/op
                 existUser·p0.9999: 11.324 ms/op
                 existUser·p1.00:   11.633 ms/op

Iteration   2: 2.975 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  7.946 ms/op
                 existUser·p0.9999: 19.997 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   3: 2.974 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  8.184 ms/op
                 existUser·p0.9999: 25.559 ms/op
                 existUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323601
  mean =      2.966 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43498 
    [ 2.500,  5.000) = 279117 
    [ 5.000,  7.500) = 680 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      7.376 ms/op
     p(99.9900) =     22.478 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
Iteration   1: 3.146 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.400 ms/op
                 getUser·p0.9999: 16.198 ms/op
                 getUser·p1.00:   16.744 ms/op

Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.922 ms/op
                 getUser·p0.9999: 15.516 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   3: 2.969 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.600 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  6.783 ms/op
                 getUser·p0.9999: 17.374 ms/op
                 getUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314805
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1610 
    [ 1.250,  2.500) = 26389 
    [ 2.500,  3.750) = 264521 
    [ 3.750,  5.000) = 21403 
    [ 5.000,  6.250) = 470 
    [ 6.250,  7.500) = 163 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 68 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.537 ms/op
     p(99.9900) =     17.122 ms/op
     p(99.9990) =     18.355 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 4.993 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.012 ms/op
Iteration   1: 3.955 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  12.157 ms/op
                 listUser·p0.9999: 15.912 ms/op
                 listUser·p1.00:   16.368 ms/op

Iteration   2: 3.981 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 16.628 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   3: 3.971 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.974 ms/op
                 listUser·p0.9999: 20.249 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241886
  mean =      3.969 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3966 
    [ 2.500,  5.000) = 212280 
    [ 5.000,  7.500) = 24506 
    [ 7.500, 10.000) = 712 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     19.544 ms/op
     p(99.9990) =     21.487 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.348 ± 2.736  ops/ms
ClientGrpc.existUser                       thrpt       3  10.984 ± 1.494  ops/ms
ClientGrpc.getUser                         thrpt       3  10.491 ± 1.390  ops/ms
ClientGrpc.listUser                        thrpt       3   8.073 ± 3.055  ops/ms
ClientGrpc.createUser                       avgt       3   3.104 ± 1.269   ms/op
ClientGrpc.existUser                        avgt       3   2.930 ± 1.021   ms/op
ClientGrpc.getUser                          avgt       3   3.094 ± 1.057   ms/op
ClientGrpc.listUser                         avgt       3   3.954 ± 0.709   ms/op
ClientGrpc.createUser                     sample  308939   3.107 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.553           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.036           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.658           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.919           ms/op
ClientGrpc.existUser                      sample  323601   2.966 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.529           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.376           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.478           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.985           ms/op
ClientGrpc.getUser                        sample  314805   3.050 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.600           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.537           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.122           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.169           ms/op
ClientGrpc.listUser                       sample  241886   3.969 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.761           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.550           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.544           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.791           ms/op
