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
# Warmup Iteration   1: 4.684 ops/ms
# Warmup Iteration   2: 9.072 ops/ms
# Warmup Iteration   3: 10.174 ops/ms
Iteration   1: 10.558 ops/ms
Iteration   2: 10.576 ops/ms
Iteration   3: 10.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.623 ±(99.9%) 1.765 ops/ms [Average]
  (min, avg, max) = (10.558, 10.623, 10.734), stdev = 0.097
  CI (99.9%): [8.858, 12.388] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.130 ops/ms
# Warmup Iteration   2: 10.626 ops/ms
# Warmup Iteration   3: 11.063 ops/ms
Iteration   1: 11.037 ops/ms
Iteration   2: 11.248 ops/ms
Iteration   3: 11.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.137 ±(99.9%) 1.931 ops/ms [Average]
  (min, avg, max) = (11.037, 11.137, 11.248), stdev = 0.106
  CI (99.9%): [9.206, 13.068] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.198 ops/ms
# Warmup Iteration   2: 10.532 ops/ms
# Warmup Iteration   3: 10.343 ops/ms
Iteration   1: 10.700 ops/ms
Iteration   2: 10.627 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.635 ±(99.9%) 1.130 ops/ms [Average]
  (min, avg, max) = (10.577, 10.635, 10.700), stdev = 0.062
  CI (99.9%): [9.505, 11.764] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.166 ops/ms
# Warmup Iteration   2: 7.944 ops/ms
# Warmup Iteration   3: 8.247 ops/ms
Iteration   1: 8.249 ops/ms
Iteration   2: 8.261 ops/ms
Iteration   3: 8.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.272 ±(99.9%) 0.544 ops/ms [Average]
  (min, avg, max) = (8.249, 8.272, 8.306), stdev = 0.030
  CI (99.9%): [7.728, 8.816] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.087 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.010 ms/op
Iteration   1: 3.013 ±(99.9%) 0.004 ms/op
Iteration   2: 2.983 ±(99.9%) 0.003 ms/op
Iteration   3: 3.054 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.016 ±(99.9%) 0.652 ms/op [Average]
  (min, avg, max) = (2.983, 3.016, 3.054), stdev = 0.036
  CI (99.9%): [2.364, 3.669] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.656 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.936 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.002 ms/op
Iteration   1: 2.903 ±(99.9%) 0.003 ms/op
Iteration   2: 2.949 ±(99.9%) 0.002 ms/op
Iteration   3: 2.823 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 1.158 ms/op [Average]
  (min, avg, max) = (2.823, 2.892, 2.949), stdev = 0.063
  CI (99.9%): [1.733, 4.050] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.002 ms/op
Iteration   1: 3.010 ±(99.9%) 0.002 ms/op
Iteration   2: 2.941 ±(99.9%) 0.002 ms/op
Iteration   3: 2.951 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.968 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (2.941, 2.968, 3.010), stdev = 0.037
  CI (99.9%): [2.284, 3.651] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.112 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.021 ms/op
Iteration   1: 3.911 ±(99.9%) 0.012 ms/op
Iteration   2: 3.864 ±(99.9%) 0.011 ms/op
Iteration   3: 3.901 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (3.864, 3.892, 3.911), stdev = 0.025
  CI (99.9%): [3.440, 4.344] (assumes normal distribution)


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
# Warmup Iteration   1: 4.021 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  7.205 ms/op
                 createUser·p0.9999: 12.091 ms/op
                 createUser·p1.00:   13.386 ms/op

Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.127 ms/op
                 createUser·p0.9999: 13.095 ms/op
                 createUser·p1.00:   13.271 ms/op

Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.478 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.480 ms/op
                 createUser·p0.9999: 26.726 ms/op
                 createUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320282
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34083 
    [ 2.500,  5.000) = 284943 
    [ 5.000,  7.500) = 984 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.289 ms/op
     p(99.9900) =     25.044 ms/op
     p(99.9990) =     27.204 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 3.854 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.006 ms/op
Iteration   1: 2.909 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.530 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  6.946 ms/op
                 existUser·p0.9999: 17.826 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   2: 2.924 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  6.637 ms/op
                 existUser·p0.9999: 13.029 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   3: 2.911 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.460 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  7.857 ms/op
                 existUser·p0.9999: 22.807 ms/op
                 existUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329365
  mean =      2.915 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38185 
    [ 2.500,  5.000) = 289581 
    [ 5.000,  7.500) = 1309 
    [ 7.500, 10.000) = 100 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      7.159 ms/op
     p(99.9900) =     22.057 ms/op
     p(99.9990) =     24.046 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.562 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.535 ms/op
                 getUser·p0.9999: 12.807 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   2: 2.985 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.351 ms/op
                 getUser·p0.9999: 13.489 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   3: 3.034 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.229 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  9.694 ms/op
                 getUser·p0.9999: 26.376 ms/op
                 getUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318087
  mean =      3.016 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27074 
    [ 2.500,  5.000) = 289582 
    [ 5.000,  7.500) = 1048 
    [ 7.500, 10.000) = 184 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.229 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.066 ms/op
     p(99.9900) =     25.572 ms/op
     p(99.9990) =     26.661 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 4.753 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.983 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.011 ms/op
Iteration   1: 3.898 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 18.499 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 3.916 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.326 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 3.861 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.437 ms/op
                 listUser·p0.9999: 34.931 ms/op
                 listUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246924
  mean =      3.892 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3576 
    [ 2.500,  5.000) = 222777 
    [ 5.000,  7.500) = 19263 
    [ 7.500, 10.000) = 777 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.780 ms/op
     p(99.9900) =     33.128 ms/op
     p(99.9990) =     35.328 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.623 ± 1.765  ops/ms
ClientGrpc.existUser                       thrpt       3  11.137 ± 1.931  ops/ms
ClientGrpc.getUser                         thrpt       3  10.635 ± 1.130  ops/ms
ClientGrpc.listUser                        thrpt       3   8.272 ± 0.544  ops/ms
ClientGrpc.createUser                       avgt       3   3.016 ± 0.652   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 1.158   ms/op
ClientGrpc.getUser                          avgt       3   2.968 ± 0.684   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 0.452   ms/op
ClientGrpc.createUser                     sample  320282   2.995 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.478           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.289           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.044           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.329           ms/op
ClientGrpc.existUser                      sample  329365   2.915 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.460           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.159           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.057           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.805           ms/op
ClientGrpc.getUser                        sample  318087   3.016 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.229           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.066           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.572           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.739           ms/op
ClientGrpc.listUser                       sample  246924   3.892 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.815           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.780           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.128           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.455           ms/op
