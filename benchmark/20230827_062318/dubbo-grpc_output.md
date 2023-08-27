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
# Warmup Iteration   1: 4.182 ops/ms
# Warmup Iteration   2: 9.137 ops/ms
# Warmup Iteration   3: 10.129 ops/ms
Iteration   1: 10.519 ops/ms
Iteration   2: 10.527 ops/ms
Iteration   3: 10.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.562 ±(99.9%) 1.231 ops/ms [Average]
  (min, avg, max) = (10.519, 10.562, 10.640), stdev = 0.067
  CI (99.9%): [9.331, 11.793] (assumes normal distribution)


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
# Warmup Iteration   1: 7.378 ops/ms
# Warmup Iteration   2: 10.454 ops/ms
# Warmup Iteration   3: 10.823 ops/ms
Iteration   1: 11.059 ops/ms
Iteration   2: 11.155 ops/ms
Iteration   3: 11.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.164 ±(99.9%) 2.022 ops/ms [Average]
  (min, avg, max) = (11.059, 11.164, 11.280), stdev = 0.111
  CI (99.9%): [9.142, 13.187] (assumes normal distribution)


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
# Warmup Iteration   1: 7.253 ops/ms
# Warmup Iteration   2: 10.141 ops/ms
# Warmup Iteration   3: 10.348 ops/ms
Iteration   1: 10.326 ops/ms
Iteration   2: 10.589 ops/ms
Iteration   3: 10.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.485 ±(99.9%) 2.549 ops/ms [Average]
  (min, avg, max) = (10.326, 10.485, 10.589), stdev = 0.140
  CI (99.9%): [7.936, 13.034] (assumes normal distribution)


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
# Warmup Iteration   1: 5.591 ops/ms
# Warmup Iteration   2: 7.755 ops/ms
# Warmup Iteration   3: 8.064 ops/ms
Iteration   1: 8.107 ops/ms
Iteration   2: 8.187 ops/ms
Iteration   3: 7.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.090 ±(99.9%) 1.960 ops/ms [Average]
  (min, avg, max) = (7.975, 8.090, 8.187), stdev = 0.107
  CI (99.9%): [6.129, 10.050] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.209 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.011 ms/op
Iteration   1: 3.062 ±(99.9%) 0.013 ms/op
Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.057 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (3.031, 3.057, 3.077), stdev = 0.023
  CI (99.9%): [2.631, 3.482] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.002 ms/op
Iteration   1: 2.908 ±(99.9%) 0.003 ms/op
Iteration   2: 2.949 ±(99.9%) 0.002 ms/op
Iteration   3: 2.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.924 ±(99.9%) 0.392 ms/op [Average]
  (min, avg, max) = (2.908, 2.924, 2.949), stdev = 0.021
  CI (99.9%): [2.533, 3.316] (assumes normal distribution)


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.005 ms/op
Iteration   1: 2.998 ±(99.9%) 0.006 ms/op
Iteration   2: 3.036 ±(99.9%) 0.005 ms/op
Iteration   3: 2.994 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.009 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (2.994, 3.009, 3.036), stdev = 0.023
  CI (99.9%): [2.590, 3.428] (assumes normal distribution)


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
# Warmup Iteration   1: 4.721 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.020 ms/op
Iteration   1: 3.982 ±(99.9%) 0.054 ms/op
Iteration   2: 3.895 ±(99.9%) 0.083 ms/op
Iteration   3: 3.889 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.922 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (3.889, 3.922, 3.982), stdev = 0.052
  CI (99.9%): [2.968, 4.876] (assumes normal distribution)


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  8.045 ms/op
                 createUser·p0.9999: 12.969 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.720 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  7.788 ms/op
                 createUser·p0.9999: 14.297 ms/op
                 createUser·p1.00:   16.646 ms/op

Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  7.463 ms/op
                 createUser·p0.9999: 16.761 ms/op
                 createUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312854
  mean =      3.069 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 499 
    [ 1.250,  2.500) = 20395 
    [ 2.500,  3.750) = 269378 
    [ 3.750,  5.000) = 20570 
    [ 5.000,  6.250) = 1188 
    [ 6.250,  7.500) = 469 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      7.849 ms/op
     p(99.9900) =     16.663 ms/op
     p(99.9990) =     16.933 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.881 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.589 ms/op
                 existUser·p0.999:  7.783 ms/op
                 existUser·p0.9999: 13.055 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   2: 2.930 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.730 ms/op
                 existUser·p0.9999: 18.285 ms/op
                 existUser·p1.00:   18.612 ms/op

Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  7.254 ms/op
                 existUser·p0.9999: 23.169 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329551
  mean =      2.911 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39275 
    [ 2.500,  5.000) = 288694 
    [ 5.000,  7.500) = 1237 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.553 ms/op
     p(99.9900) =     18.783 ms/op
     p(99.9990) =     24.597 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 4.364 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  8.182 ms/op
                 getUser·p0.9999: 13.558 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.634 ms/op
                 getUser·p0.9999: 14.244 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  8.294 ms/op
                 getUser·p0.9999: 25.231 ms/op
                 getUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314108
  mean =      3.055 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21835 
    [ 2.500,  5.000) = 290311 
    [ 5.000,  7.500) = 1460 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.371 ms/op
     p(99.9900) =     24.104 ms/op
     p(99.9990) =     26.243 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 5.590 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
Iteration   1: 3.941 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  13.287 ms/op
                 listUser·p0.9999: 14.773 ms/op
                 listUser·p1.00:   16.253 ms/op

Iteration   2: 3.976 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 23.100 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   3: 3.900 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  18.147 ms/op
                 listUser·p0.9999: 26.935 ms/op
                 listUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243644
  mean =      3.939 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3632 
    [ 2.500,  5.000) = 216473 
    [ 5.000,  7.500) = 21907 
    [ 7.500, 10.000) = 1081 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.012 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.968 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     28.058 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.562 ± 1.231  ops/ms
ClientGrpc.existUser                       thrpt       3  11.164 ± 2.022  ops/ms
ClientGrpc.getUser                         thrpt       3  10.485 ± 2.549  ops/ms
ClientGrpc.listUser                        thrpt       3   8.090 ± 1.960  ops/ms
ClientGrpc.createUser                       avgt       3   3.057 ± 0.426   ms/op
ClientGrpc.existUser                        avgt       3   2.924 ± 0.392   ms/op
ClientGrpc.getUser                          avgt       3   3.009 ± 0.419   ms/op
ClientGrpc.listUser                         avgt       3   3.922 ± 0.954   ms/op
ClientGrpc.createUser                     sample  312854   3.069 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.569           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.849           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.663           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.302           ms/op
ClientGrpc.existUser                      sample  329551   2.911 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.668           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.553           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.783           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.740           ms/op
ClientGrpc.getUser                        sample  314108   3.055 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.551           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.371           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.104           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.477           ms/op
ClientGrpc.listUser                       sample  243644   3.939 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.012           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.968           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.111           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.385           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.723           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.213           ms/op
