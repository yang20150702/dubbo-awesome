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
# Warmup Iteration   1: 4.326 ops/ms
# Warmup Iteration   2: 8.440 ops/ms
# Warmup Iteration   3: 9.909 ops/ms
Iteration   1: 10.585 ops/ms
Iteration   2: 10.343 ops/ms
Iteration   3: 10.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.482 ±(99.9%) 2.281 ops/ms [Average]
  (min, avg, max) = (10.343, 10.482, 10.585), stdev = 0.125
  CI (99.9%): [8.202, 12.763] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.658 ops/ms
# Warmup Iteration   2: 11.220 ops/ms
# Warmup Iteration   3: 11.013 ops/ms
Iteration   1: 11.129 ops/ms
Iteration   2: 11.045 ops/ms
Iteration   3: 10.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.051 ±(99.9%) 1.365 ops/ms [Average]
  (min, avg, max) = (10.979, 11.051, 11.129), stdev = 0.075
  CI (99.9%): [9.686, 12.416] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.376 ops/ms
# Warmup Iteration   2: 10.213 ops/ms
# Warmup Iteration   3: 10.835 ops/ms
Iteration   1: 10.744 ops/ms
Iteration   2: 10.813 ops/ms
Iteration   3: 10.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.778 ±(99.9%) 0.630 ops/ms [Average]
  (min, avg, max) = (10.744, 10.778, 10.813), stdev = 0.035
  CI (99.9%): [10.149, 11.408] (assumes normal distribution)


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
# Warmup Iteration   1: 5.686 ops/ms
# Warmup Iteration   2: 7.698 ops/ms
# Warmup Iteration   3: 7.922 ops/ms
Iteration   1: 7.986 ops/ms
Iteration   2: 8.026 ops/ms
Iteration   3: 8.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.008 ±(99.9%) 0.362 ops/ms [Average]
  (min, avg, max) = (7.986, 8.008, 8.026), stdev = 0.020
  CI (99.9%): [7.645, 8.370] (assumes normal distribution)


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 3.043 ±(99.9%) 0.002 ms/op
Iteration   3: 3.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.039 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (3.031, 3.039, 3.044), stdev = 0.007
  CI (99.9%): [2.905, 3.173] (assumes normal distribution)


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.001 ms/op
Iteration   1: 2.925 ±(99.9%) 0.002 ms/op
Iteration   2: 2.918 ±(99.9%) 0.002 ms/op
Iteration   3: 2.844 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.895 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (2.844, 2.895, 2.925), stdev = 0.045
  CI (99.9%): [2.076, 3.714] (assumes normal distribution)


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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.003 ms/op
Iteration   1: 3.032 ±(99.9%) 0.004 ms/op
Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
Iteration   3: 2.991 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.022 ±(99.9%) 0.492 ms/op [Average]
  (min, avg, max) = (2.991, 3.022, 3.042), stdev = 0.027
  CI (99.9%): [2.529, 3.514] (assumes normal distribution)


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
# Warmup Iteration   1: 5.401 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.024 ms/op
Iteration   1: 3.971 ±(99.9%) 0.008 ms/op
Iteration   2: 3.867 ±(99.9%) 0.008 ms/op
Iteration   3: 3.982 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.940 ±(99.9%) 1.158 ms/op [Average]
  (min, avg, max) = (3.867, 3.940, 3.982), stdev = 0.063
  CI (99.9%): [2.781, 5.098] (assumes normal distribution)


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
Iteration   1: 3.012 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  10.959 ms/op
                 createUser·p0.9999: 15.111 ms/op
                 createUser·p1.00:   16.040 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.595 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  9.140 ms/op
                 createUser·p0.9999: 14.647 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  11.360 ms/op
                 createUser·p0.9999: 22.872 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317968
  mean =      3.017 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22016 
    [ 2.500,  5.000) = 294414 
    [ 5.000,  7.500) = 955 
    [ 7.500, 10.000) = 221 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.941 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  6.236 ms/op
                 existUser·p0.9999: 13.390 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 2.873 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.359 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  7.738 ms/op
                 existUser·p0.9999: 23.097 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   3: 2.882 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  6.522 ms/op
                 existUser·p0.9999: 27.034 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331004
  mean =      2.898 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39993 
    [ 2.500,  5.000) = 290073 
    [ 5.000,  7.500) = 708 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      6.980 ms/op
     p(99.9900) =     23.226 ms/op
     p(99.9990) =     27.351 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 4.472 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  8.237 ms/op
                 getUser·p0.9999: 14.792 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.386 ms/op
                 getUser·p0.9999: 15.527 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.498 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.324 ms/op
                 getUser·p0.9999: 18.083 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316981
  mean =      3.027 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 432 
    [ 1.250,  2.500) = 23905 
    [ 2.500,  3.750) = 275062 
    [ 3.750,  5.000) = 16100 
    [ 5.000,  6.250) = 823 
    [ 6.250,  7.500) = 308 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 89 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.996 ms/op
     p(99.9900) =     16.410 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 5.424 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.011 ms/op
Iteration   1: 4.053 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 16.761 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   2: 3.988 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.719 ms/op
                 listUser·p0.9999: 23.002 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   3: 3.959 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.588 ms/op
                 listUser·p0.9999: 24.112 ms/op
                 listUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239989
  mean =      4.000 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2311 
    [ 2.500,  5.000) = 212299 
    [ 5.000,  7.500) = 24042 
    [ 7.500, 10.000) = 898 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     24.701 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.482 ± 2.281  ops/ms
ClientGrpc.existUser                       thrpt       3  11.051 ± 1.365  ops/ms
ClientGrpc.getUser                         thrpt       3  10.778 ± 0.630  ops/ms
ClientGrpc.listUser                        thrpt       3   8.008 ± 0.362  ops/ms
ClientGrpc.createUser                       avgt       3   3.039 ± 0.134   ms/op
ClientGrpc.existUser                        avgt       3   2.895 ± 0.819   ms/op
ClientGrpc.getUser                          avgt       3   3.022 ± 0.492   ms/op
ClientGrpc.listUser                         avgt       3   3.940 ± 1.158   ms/op
ClientGrpc.createUser                     sample  317968   3.017 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.595           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.076           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.826           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.938           ms/op
ClientGrpc.existUser                      sample  331004   2.898 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.359           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.063           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.980           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.226           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.460           ms/op
ClientGrpc.getUser                        sample  316981   3.027 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.498           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.996           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.410           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.416           ms/op
ClientGrpc.listUser                       sample  239989   4.000 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.079           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.073           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.905           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.805           ms/op
