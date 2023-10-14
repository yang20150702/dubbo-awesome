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
# Warmup Iteration   1: 3.949 ops/ms
# Warmup Iteration   2: 8.489 ops/ms
# Warmup Iteration   3: 9.668 ops/ms
Iteration   1: 9.916 ops/ms
Iteration   2: 10.061 ops/ms
Iteration   3: 10.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.038 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (9.916, 10.038, 10.138), stdev = 0.112
  CI (99.9%): [7.989, 12.087] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 7.222 ops/ms
# Warmup Iteration   2: 10.343 ops/ms
# Warmup Iteration   3: 10.702 ops/ms
Iteration   1: 10.604 ops/ms
Iteration   2: 10.635 ops/ms
Iteration   3: 10.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.638 ±(99.9%) 0.648 ops/ms [Average]
  (min, avg, max) = (10.604, 10.638, 10.675), stdev = 0.036
  CI (99.9%): [9.990, 11.286] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.566 ops/ms
# Warmup Iteration   2: 9.783 ops/ms
# Warmup Iteration   3: 10.165 ops/ms
Iteration   1: 10.075 ops/ms
Iteration   2: 10.207 ops/ms
Iteration   3: 10.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.191 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (10.075, 10.191, 10.290), stdev = 0.108
  CI (99.9%): [8.218, 12.164] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.085 ops/ms
# Warmup Iteration   2: 7.615 ops/ms
# Warmup Iteration   3: 7.932 ops/ms
Iteration   1: 7.873 ops/ms
Iteration   2: 7.762 ops/ms
Iteration   3: 8.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.906 ±(99.9%) 2.988 ops/ms [Average]
  (min, avg, max) = (7.762, 7.906, 8.084), stdev = 0.164
  CI (99.9%): [4.919, 10.894] (assumes normal distribution)


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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.004 ms/op
Iteration   1: 3.189 ±(99.9%) 0.004 ms/op
Iteration   2: 3.248 ±(99.9%) 0.009 ms/op
Iteration   3: 3.130 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.189 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (3.130, 3.189, 3.248), stdev = 0.059
  CI (99.9%): [2.109, 4.269] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.403 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.003 ms/op
Iteration   1: 3.051 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.045 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (3.025, 3.045, 3.059), stdev = 0.018
  CI (99.9%): [2.722, 3.369] (assumes normal distribution)


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
# Warmup Iteration   1: 4.503 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.004 ms/op
Iteration   1: 3.273 ±(99.9%) 0.002 ms/op
Iteration   2: 3.208 ±(99.9%) 0.002 ms/op
Iteration   3: 3.140 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.207 ±(99.9%) 1.219 ms/op [Average]
  (min, avg, max) = (3.140, 3.207, 3.273), stdev = 0.067
  CI (99.9%): [1.988, 4.426] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.559 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.021 ms/op
Iteration   1: 4.117 ±(99.9%) 0.025 ms/op
Iteration   2: 4.021 ±(99.9%) 0.017 ms/op
Iteration   3: 3.982 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.040 ±(99.9%) 1.267 ms/op [Average]
  (min, avg, max) = (3.982, 4.040, 4.117), stdev = 0.069
  CI (99.9%): [2.773, 5.307] (assumes normal distribution)


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
# Warmup Iteration   1: 4.732 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.009 ms/op
Iteration   1: 3.201 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  8.455 ms/op
                 createUser·p0.9999: 22.348 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.678 ms/op
                 createUser·p0.9999: 14.955 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   3: 3.182 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  16.180 ms/op
                 createUser·p0.9999: 19.004 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302727
  mean =      3.170 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9488 
    [ 2.500,  5.000) = 290923 
    [ 5.000,  7.500) = 1667 
    [ 7.500, 10.000) = 316 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =     10.995 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     22.445 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.987 ms/op
                 existUser·p0.9999: 17.596 ms/op
                 existUser·p1.00:   17.760 ms/op

Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  9.633 ms/op
                 existUser·p0.9999: 20.914 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   3: 2.986 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  11.370 ms/op
                 existUser·p0.9999: 21.843 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319730
  mean =      3.002 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26628 
    [ 2.500,  5.000) = 291577 
    [ 5.000,  7.500) = 969 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      9.167 ms/op
     p(99.9900) =     19.170 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.596 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.007 ms/op
Iteration   1: 3.152 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  9.823 ms/op
                 getUser·p0.9999: 20.283 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.150 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.806 ms/op
                 getUser·p0.999:  7.111 ms/op
                 getUser·p0.9999: 17.957 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   3: 3.124 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  9.159 ms/op
                 getUser·p0.9999: 28.943 ms/op
                 getUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305407
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10739 
    [ 2.500,  5.000) = 292717 
    [ 5.000,  7.500) = 1559 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      8.118 ms/op
     p(99.9900) =     28.178 ms/op
     p(99.9990) =     29.226 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.011 ms/op
Iteration   1: 4.039 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 28.748 ms/op
                 listUser·p1.00:   29.491 ms/op

Iteration   2: 4.081 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 17.077 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   3: 4.038 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  17.127 ms/op
                 listUser·p0.9999: 23.108 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236977
  mean =      4.053 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1695 
    [ 2.500,  5.000) = 219501 
    [ 5.000,  7.500) = 14184 
    [ 7.500, 10.000) = 939 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     23.711 ms/op
     p(99.9990) =     29.369 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.038 ± 2.049  ops/ms
ClientGrpc.existUser                       thrpt       3  10.638 ± 0.648  ops/ms
ClientGrpc.getUser                         thrpt       3  10.191 ± 1.973  ops/ms
ClientGrpc.listUser                        thrpt       3   7.906 ± 2.988  ops/ms
ClientGrpc.createUser                       avgt       3   3.189 ± 1.080   ms/op
ClientGrpc.existUser                        avgt       3   3.045 ± 0.323   ms/op
ClientGrpc.getUser                          avgt       3   3.207 ± 1.219   ms/op
ClientGrpc.listUser                         avgt       3   4.040 ± 1.267   ms/op
ClientGrpc.createUser                     sample  302727   3.170 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.591           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.995           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.644           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.544           ms/op
ClientGrpc.existUser                      sample  319730   3.002 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.697           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.167           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.170           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.675           ms/op
ClientGrpc.getUser                        sample  305407   3.142 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.723           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.118           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.178           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.262           ms/op
ClientGrpc.listUser                       sample  236977   4.053 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.918           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.647           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.711           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.491           ms/op
