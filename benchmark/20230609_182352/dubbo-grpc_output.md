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
# Warmup Iteration   1: 3.567 ops/ms
# Warmup Iteration   2: 8.506 ops/ms
# Warmup Iteration   3: 9.549 ops/ms
Iteration   1: 10.199 ops/ms
Iteration   2: 10.422 ops/ms
Iteration   3: 10.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.246 ±(99.9%) 2.877 ops/ms [Average]
  (min, avg, max) = (10.117, 10.246, 10.422), stdev = 0.158
  CI (99.9%): [7.369, 13.123] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.039 ops/ms
# Warmup Iteration   2: 10.212 ops/ms
# Warmup Iteration   3: 10.711 ops/ms
Iteration   1: 10.837 ops/ms
Iteration   2: 10.740 ops/ms
Iteration   3: 10.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.796 ±(99.9%) 0.917 ops/ms [Average]
  (min, avg, max) = (10.740, 10.796, 10.837), stdev = 0.050
  CI (99.9%): [9.878, 11.713] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.620 ops/ms
# Warmup Iteration   2: 9.735 ops/ms
# Warmup Iteration   3: 10.127 ops/ms
Iteration   1: 10.306 ops/ms
Iteration   2: 10.311 ops/ms
Iteration   3: 10.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.256 ±(99.9%) 1.650 ops/ms [Average]
  (min, avg, max) = (10.152, 10.256, 10.311), stdev = 0.090
  CI (99.9%): [8.607, 11.906] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.607 ops/ms
# Warmup Iteration   2: 7.230 ops/ms
# Warmup Iteration   3: 7.712 ops/ms
Iteration   1: 7.710 ops/ms
Iteration   2: 7.752 ops/ms
Iteration   3: 7.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.747 ±(99.9%) 0.624 ops/ms [Average]
  (min, avg, max) = (7.710, 7.747, 7.778), stdev = 0.034
  CI (99.9%): [7.123, 8.371] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.527 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.358 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.002 ms/op
Iteration   1: 3.186 ±(99.9%) 0.002 ms/op
Iteration   2: 3.146 ±(99.9%) 0.003 ms/op
Iteration   3: 3.167 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.167 ±(99.9%) 0.363 ms/op [Average]
  (min, avg, max) = (3.146, 3.167, 3.186), stdev = 0.020
  CI (99.9%): [2.803, 3.530] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.916 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.002 ms/op
Iteration   1: 3.005 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 2.935 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (2.935, 2.974, 3.005), stdev = 0.036
  CI (99.9%): [2.319, 3.628] (assumes normal distribution)


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.002 ms/op
Iteration   1: 3.089 ±(99.9%) 0.002 ms/op
Iteration   2: 3.060 ±(99.9%) 0.002 ms/op
Iteration   3: 3.108 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.086 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (3.060, 3.086, 3.108), stdev = 0.024
  CI (99.9%): [2.650, 3.522] (assumes normal distribution)


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
# Warmup Iteration   1: 5.984 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.333 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.013 ms/op
Iteration   1: 4.092 ±(99.9%) 0.011 ms/op
Iteration   2: 4.113 ±(99.9%) 0.012 ms/op
Iteration   3: 4.056 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.087 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (4.056, 4.087, 4.113), stdev = 0.029
  CI (99.9%): [3.560, 4.614] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.754 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.007 ms/op
Iteration   1: 3.131 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  6.862 ms/op
                 createUser·p0.9999: 13.451 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.947 ms/op
                 createUser·p0.9999: 14.871 ms/op
                 createUser·p1.00:   15.188 ms/op

Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.702 ms/op
                 createUser·p0.9999: 19.763 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309419
  mean =      3.102 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14024 
    [ 2.500,  5.000) = 294204 
    [ 5.000,  7.500) = 923 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.128 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.405 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.005 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  5.644 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  11.983 ms/op
                 existUser·p0.9999: 14.481 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   3: 3.001 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  7.240 ms/op
                 existUser·p0.9999: 26.870 ms/op
                 existUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319255
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24161 
    [ 2.500,  5.000) = 293789 
    [ 5.000,  7.500) = 970 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.567 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     26.995 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.006 ms/op
Iteration   1: 3.109 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  8.488 ms/op
                 getUser·p0.9999: 13.107 ms/op
                 getUser·p1.00:   13.304 ms/op

Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.401 ms/op
                 getUser·p0.9999: 15.169 ms/op
                 getUser·p1.00:   15.892 ms/op

Iteration   3: 3.113 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.052 ms/op
                 getUser·p0.9999: 17.489 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309599
  mean =      3.101 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 600 
    [ 1.250,  2.500) = 13017 
    [ 2.500,  3.750) = 274948 
    [ 3.750,  5.000) = 19489 
    [ 5.000,  6.250) = 998 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 141 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.154 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     17.952 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 5.210 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.252 ±(99.9%) 0.014 ms/op
Iteration   1: 4.139 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 24.070 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   2: 4.118 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  19.235 ms/op
                 listUser·p0.9999: 27.034 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   3: 4.092 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  16.644 ms/op
                 listUser·p0.9999: 21.174 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233261
  mean =      4.116 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1729 
    [ 2.500,  5.000) = 207093 
    [ 5.000,  7.500) = 22518 
    [ 7.500, 10.000) = 1537 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     16.773 ms/op
     p(99.9900) =     26.127 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.246 ± 2.877  ops/ms
ClientGrpc.existUser                       thrpt       3  10.796 ± 0.917  ops/ms
ClientGrpc.getUser                         thrpt       3  10.256 ± 1.650  ops/ms
ClientGrpc.listUser                        thrpt       3   7.747 ± 0.624  ops/ms
ClientGrpc.createUser                       avgt       3   3.167 ± 0.363   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 0.655   ms/op
ClientGrpc.getUser                          avgt       3   3.086 ± 0.436   ms/op
ClientGrpc.listUser                         avgt       3   4.087 ± 0.527   ms/op
ClientGrpc.createUser                     sample  309419   3.102 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.820           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.128           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.399           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.185           ms/op
ClientGrpc.existUser                      sample  319255   3.007 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.571           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.567           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.018           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.656           ms/op
ClientGrpc.getUser                        sample  309599   3.101 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.693           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.154           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.039           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.547           ms/op
ClientGrpc.listUser                       sample  233261   4.116 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.090           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.953           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.315           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.773           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.127           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.066           ms/op
