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
# Warmup Iteration   1: 4.923 ops/ms
# Warmup Iteration   2: 9.633 ops/ms
# Warmup Iteration   3: 10.166 ops/ms
Iteration   1: 10.535 ops/ms
Iteration   2: 10.404 ops/ms
Iteration   3: 10.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.422 ±(99.9%) 1.905 ops/ms [Average]
  (min, avg, max) = (10.329, 10.422, 10.535), stdev = 0.104
  CI (99.9%): [8.518, 12.327] (assumes normal distribution)


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
# Warmup Iteration   1: 7.973 ops/ms
# Warmup Iteration   2: 10.692 ops/ms
# Warmup Iteration   3: 11.133 ops/ms
Iteration   1: 10.624 ops/ms
Iteration   2: 10.974 ops/ms
Iteration   3: 10.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.761 ±(99.9%) 3.422 ops/ms [Average]
  (min, avg, max) = (10.624, 10.761, 10.974), stdev = 0.188
  CI (99.9%): [7.339, 14.182] (assumes normal distribution)


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
# Warmup Iteration   1: 7.525 ops/ms
# Warmup Iteration   2: 10.292 ops/ms
# Warmup Iteration   3: 10.458 ops/ms
Iteration   1: 10.179 ops/ms
Iteration   2: 10.348 ops/ms
Iteration   3: 10.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.360 ±(99.9%) 3.407 ops/ms [Average]
  (min, avg, max) = (10.179, 10.360, 10.552), stdev = 0.187
  CI (99.9%): [6.953, 13.767] (assumes normal distribution)


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
# Warmup Iteration   1: 6.769 ops/ms
# Warmup Iteration   2: 7.711 ops/ms
# Warmup Iteration   3: 7.782 ops/ms
Iteration   1: 7.942 ops/ms
Iteration   2: 8.107 ops/ms
Iteration   3: 7.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.015 ±(99.9%) 1.529 ops/ms [Average]
  (min, avg, max) = (7.942, 8.015, 8.107), stdev = 0.084
  CI (99.9%): [6.486, 9.545] (assumes normal distribution)


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
# Warmup Iteration   1: 3.659 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.002 ms/op
Iteration   1: 3.081 ±(99.9%) 0.001 ms/op
Iteration   2: 3.056 ±(99.9%) 0.002 ms/op
Iteration   3: 3.190 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.109 ±(99.9%) 1.294 ms/op [Average]
  (min, avg, max) = (3.056, 3.109, 3.190), stdev = 0.071
  CI (99.9%): [1.815, 4.404] (assumes normal distribution)


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.002 ms/op
Iteration   1: 3.016 ±(99.9%) 0.002 ms/op
Iteration   2: 2.966 ±(99.9%) 0.003 ms/op
Iteration   3: 2.972 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.985 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (2.966, 2.985, 3.016), stdev = 0.028
  CI (99.9%): [2.479, 3.490] (assumes normal distribution)


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
# Warmup Iteration   1: 3.974 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.002 ms/op
Iteration   1: 3.140 ±(99.9%) 0.002 ms/op
Iteration   2: 3.099 ±(99.9%) 0.002 ms/op
Iteration   3: 3.034 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.091 ±(99.9%) 0.970 ms/op [Average]
  (min, avg, max) = (3.034, 3.091, 3.140), stdev = 0.053
  CI (99.9%): [2.121, 4.061] (assumes normal distribution)


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
# Warmup Iteration   1: 4.793 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.033 ms/op
Iteration   1: 4.013 ±(99.9%) 0.010 ms/op
Iteration   2: 4.048 ±(99.9%) 0.020 ms/op
Iteration   3: 4.002 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.021 ±(99.9%) 0.444 ms/op [Average]
  (min, avg, max) = (4.002, 4.021, 4.048), stdev = 0.024
  CI (99.9%): [3.577, 4.465] (assumes normal distribution)


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
Iteration   1: 3.040 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.008 ms/op
                 createUser·p0.9999: 11.558 ms/op
                 createUser·p1.00:   11.846 ms/op

Iteration   2: 3.078 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  8.920 ms/op
                 createUser·p0.9999: 15.185 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.441 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 20.560 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314654
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33229 
    [ 2.500,  5.000) = 280369 
    [ 5.000,  7.500) = 679 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.441 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.558 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     20.737 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.688 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.685 ms/op
                 existUser·p0.9999: 17.638 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   2: 2.960 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  5.397 ms/op
                 existUser·p0.9999: 15.055 ms/op
                 existUser·p1.00:   15.401 ms/op

Iteration   3: 2.915 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 24.151 ms/op
                 existUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325267
  mean =      2.953 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44325 
    [ 2.500,  5.000) = 279905 
    [ 5.000,  7.500) = 757 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.971 ms/op
     p(99.9900) =     19.751 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.112 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.842 ms/op
                 getUser·p0.9999: 12.467 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.286 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.006 ms/op
                 getUser·p0.9999: 13.118 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.054 ms/op
                 getUser·p0.9999: 15.217 ms/op
                 getUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311519
  mean =      3.080 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1533 
    [ 1.250,  2.500) = 24177 
    [ 2.500,  3.750) = 258267 
    [ 3.750,  5.000) = 26595 
    [ 5.000,  6.250) = 526 
    [ 6.250,  7.500) = 229 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.286 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.767 ms/op
     p(99.9900) =     14.270 ms/op
     p(99.9990) =     15.779 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 5.011 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.012 ms/op
Iteration   1: 4.037 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.741 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   2: 3.982 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.150 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.598 ms/op
                 listUser·p0.9999: 22.315 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   3: 4.062 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.983 ms/op
                 listUser·p0.9999: 19.452 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238329
  mean =      4.027 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5056 
    [ 2.500,  5.000) = 204235 
    [ 5.000,  7.500) = 27679 
    [ 7.500, 10.000) = 787 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.264 ms/op
     p(99.9900) =     20.027 ms/op
     p(99.9990) =     22.532 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.422 ± 1.905  ops/ms
ClientGrpc.existUser                       thrpt       3  10.761 ± 3.422  ops/ms
ClientGrpc.getUser                         thrpt       3  10.360 ± 3.407  ops/ms
ClientGrpc.listUser                        thrpt       3   8.015 ± 1.529  ops/ms
ClientGrpc.createUser                       avgt       3   3.109 ± 1.294   ms/op
ClientGrpc.existUser                        avgt       3   2.985 ± 0.505   ms/op
ClientGrpc.getUser                          avgt       3   3.091 ± 0.970   ms/op
ClientGrpc.listUser                         avgt       3   4.021 ± 0.444   ms/op
ClientGrpc.createUser                     sample  314654   3.050 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.441           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.558           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.087           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.775           ms/op
ClientGrpc.existUser                      sample  325267   2.953 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.593           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.971           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.751           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.576           ms/op
ClientGrpc.getUser                        sample  311519   3.080 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.286           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.767           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.270           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.974           ms/op
ClientGrpc.listUser                       sample  238329   4.027 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.741           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.264           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.027           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.610           ms/op
