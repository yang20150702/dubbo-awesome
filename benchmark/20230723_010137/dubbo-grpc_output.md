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
# Warmup Iteration   1: 4.342 ops/ms
# Warmup Iteration   2: 8.929 ops/ms
# Warmup Iteration   3: 10.042 ops/ms
Iteration   1: 10.434 ops/ms
Iteration   2: 10.440 ops/ms
Iteration   3: 10.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.467 ±(99.9%) 0.952 ops/ms [Average]
  (min, avg, max) = (10.434, 10.467, 10.527), stdev = 0.052
  CI (99.9%): [9.515, 11.419] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.195 ops/ms
# Warmup Iteration   2: 10.544 ops/ms
# Warmup Iteration   3: 11.008 ops/ms
Iteration   1: 10.676 ops/ms
Iteration   2: 10.849 ops/ms
Iteration   3: 11.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.910 ±(99.9%) 4.933 ops/ms [Average]
  (min, avg, max) = (10.676, 10.910, 11.206), stdev = 0.270
  CI (99.9%): [5.977, 15.844] (assumes normal distribution)


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
# Warmup Iteration   1: 7.378 ops/ms
# Warmup Iteration   2: 10.122 ops/ms
# Warmup Iteration   3: 10.482 ops/ms
Iteration   1: 10.327 ops/ms
Iteration   2: 10.369 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.379 ±(99.9%) 1.060 ops/ms [Average]
  (min, avg, max) = (10.327, 10.379, 10.442), stdev = 0.058
  CI (99.9%): [9.319, 11.439] (assumes normal distribution)


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
# Warmup Iteration   1: 6.812 ops/ms
# Warmup Iteration   2: 7.640 ops/ms
# Warmup Iteration   3: 8.105 ops/ms
Iteration   1: 7.987 ops/ms
Iteration   2: 7.955 ops/ms
Iteration   3: 8.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.000 ±(99.9%) 0.965 ops/ms [Average]
  (min, avg, max) = (7.955, 8.000, 8.058), stdev = 0.053
  CI (99.9%): [7.035, 8.965] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.003 ms/op
Iteration   2: 3.038 ±(99.9%) 0.005 ms/op
Iteration   3: 3.068 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.055 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (3.038, 3.055, 3.068), stdev = 0.015
  CI (99.9%): [2.779, 3.330] (assumes normal distribution)


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.929 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.003 ms/op
Iteration   1: 2.935 ±(99.9%) 0.007 ms/op
Iteration   2: 2.933 ±(99.9%) 0.002 ms/op
Iteration   3: 2.811 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.893 ±(99.9%) 1.290 ms/op [Average]
  (min, avg, max) = (2.811, 2.893, 2.935), stdev = 0.071
  CI (99.9%): [1.603, 4.183] (assumes normal distribution)


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
# Warmup Iteration   1: 4.195 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.003 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
Iteration   2: 3.045 ±(99.9%) 0.002 ms/op
Iteration   3: 2.999 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.025 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (2.999, 3.025, 3.045), stdev = 0.023
  CI (99.9%): [2.598, 3.451] (assumes normal distribution)


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
# Warmup Iteration   1: 4.946 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.022 ms/op
Iteration   1: 4.022 ±(99.9%) 0.027 ms/op
Iteration   2: 3.930 ±(99.9%) 0.014 ms/op
Iteration   3: 3.912 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.955 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (3.912, 3.955, 4.022), stdev = 0.059
  CI (99.9%): [2.881, 5.029] (assumes normal distribution)


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
# Warmup Iteration   1: 4.147 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  6.484 ms/op
                 createUser·p0.9999: 16.854 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.290 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  11.141 ms/op
                 createUser·p0.9999: 21.856 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  6.853 ms/op
                 createUser·p0.9999: 19.796 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317915
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25212 
    [ 2.500,  5.000) = 291219 
    [ 5.000,  7.500) = 1105 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.290 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.365 ms/op
     p(99.9900) =     20.428 ms/op
     p(99.9990) =     22.107 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.005 ms/op
Iteration   1: 2.936 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  8.025 ms/op
                 existUser·p0.9999: 16.093 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   2: 2.884 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  5.234 ms/op
                 existUser·p0.9999: 13.759 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   3: 2.736 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   2.789 ms/op
                 existUser·p0.90:   3.178 ms/op
                 existUser·p0.95:   3.305 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.571 ms/op
                 existUser·p0.9999: 15.717 ms/op
                 existUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336812
  mean =      2.849 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2609 
    [ 1.250,  2.500) = 48063 
    [ 2.500,  3.750) = 276296 
    [ 3.750,  5.000) = 8839 
    [ 5.000,  6.250) = 464 
    [ 6.250,  7.500) = 285 
    [ 7.500,  8.750) = 96 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     15.712 ms/op
     p(99.9990) =     18.150 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.005 ms/op
Iteration   1: 3.056 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.229 ms/op
                 getUser·p0.9999: 25.347 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.302 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  6.966 ms/op
                 getUser·p0.9999: 18.430 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   3: 3.030 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.523 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  6.963 ms/op
                 getUser·p0.9999: 20.363 ms/op
                 getUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315976
  mean =      3.039 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16637 
    [ 2.500,  5.000) = 298016 
    [ 5.000,  7.500) = 1089 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.302 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.070 ms/op
     p(99.9900) =     24.504 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 5.482 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.011 ms/op
Iteration   1: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  13.171 ms/op
                 listUser·p0.9999: 19.531 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   2: 4.042 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.873 ms/op
                 listUser·p0.9999: 20.679 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   3: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  16.542 ms/op
                 listUser·p0.9999: 25.463 ms/op
                 listUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238334
  mean =      4.028 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3493 
    [ 2.500,  5.000) = 209908 
    [ 5.000,  7.500) = 23633 
    [ 7.500, 10.000) = 855 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     25.882 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.467 ± 0.952  ops/ms
ClientGrpc.existUser                       thrpt       3  10.910 ± 4.933  ops/ms
ClientGrpc.getUser                         thrpt       3  10.379 ± 1.060  ops/ms
ClientGrpc.listUser                        thrpt       3   8.000 ± 0.965  ops/ms
ClientGrpc.createUser                       avgt       3   3.055 ± 0.276   ms/op
ClientGrpc.existUser                        avgt       3   2.893 ± 1.290   ms/op
ClientGrpc.getUser                          avgt       3   3.025 ± 0.427   ms/op
ClientGrpc.listUser                         avgt       3   3.955 ± 1.074   ms/op
ClientGrpc.createUser                     sample  317915   3.020 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.290           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.365           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.428           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.118           ms/op
ClientGrpc.existUser                      sample  336812   2.849 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.555           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.963           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.712           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.219           ms/op
ClientGrpc.getUser                        sample  315976   3.039 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.302           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.070           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.504           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.690           ms/op
ClientGrpc.listUser                       sample  238334   4.028 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.949           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.822           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.051           ms/op
