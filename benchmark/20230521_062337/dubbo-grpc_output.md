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
# Warmup Iteration   1: 4.114 ops/ms
# Warmup Iteration   2: 9.166 ops/ms
# Warmup Iteration   3: 10.074 ops/ms
Iteration   1: 10.745 ops/ms
Iteration   2: 10.637 ops/ms
Iteration   3: 10.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.602 ±(99.9%) 2.964 ops/ms [Average]
  (min, avg, max) = (10.425, 10.602, 10.745), stdev = 0.162
  CI (99.9%): [7.639, 13.566] (assumes normal distribution)


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
# Warmup Iteration   1: 7.249 ops/ms
# Warmup Iteration   2: 10.752 ops/ms
# Warmup Iteration   3: 11.177 ops/ms
Iteration   1: 11.277 ops/ms
Iteration   2: 11.083 ops/ms
Iteration   3: 11.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.137 ±(99.9%) 2.223 ops/ms [Average]
  (min, avg, max) = (11.051, 11.137, 11.277), stdev = 0.122
  CI (99.9%): [8.914, 13.360] (assumes normal distribution)


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
# Warmup Iteration   1: 7.354 ops/ms
# Warmup Iteration   2: 10.345 ops/ms
# Warmup Iteration   3: 10.659 ops/ms
Iteration   1: 10.471 ops/ms
Iteration   2: 10.620 ops/ms
Iteration   3: 10.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.589 ±(99.9%) 1.934 ops/ms [Average]
  (min, avg, max) = (10.471, 10.589, 10.676), stdev = 0.106
  CI (99.9%): [8.655, 12.524] (assumes normal distribution)


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
# Warmup Iteration   1: 5.558 ops/ms
# Warmup Iteration   2: 7.743 ops/ms
# Warmup Iteration   3: 8.144 ops/ms
Iteration   1: 8.252 ops/ms
Iteration   2: 8.139 ops/ms
Iteration   3: 8.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.238 ±(99.9%) 1.690 ops/ms [Average]
  (min, avg, max) = (8.139, 8.238, 8.323), stdev = 0.093
  CI (99.9%): [6.549, 9.928] (assumes normal distribution)


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.003 ms/op
Iteration   1: 3.013 ±(99.9%) 0.003 ms/op
Iteration   2: 3.035 ±(99.9%) 0.004 ms/op
Iteration   3: 3.020 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.023 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (3.013, 3.023, 3.035), stdev = 0.011
  CI (99.9%): [2.817, 3.228] (assumes normal distribution)


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.831 ±(99.9%) 0.003 ms/op
Iteration   1: 2.879 ±(99.9%) 0.002 ms/op
Iteration   2: 2.915 ±(99.9%) 0.002 ms/op
Iteration   3: 2.838 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.877 ±(99.9%) 0.705 ms/op [Average]
  (min, avg, max) = (2.838, 2.877, 2.915), stdev = 0.039
  CI (99.9%): [2.172, 3.583] (assumes normal distribution)


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
# Warmup Iteration   1: 4.350 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.002 ms/op
Iteration   1: 3.007 ±(99.9%) 0.003 ms/op
Iteration   2: 3.000 ±(99.9%) 0.003 ms/op
Iteration   3: 2.977 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.995 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (2.977, 2.995, 3.007), stdev = 0.016
  CI (99.9%): [2.706, 3.284] (assumes normal distribution)


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
# Warmup Iteration   1: 5.372 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.018 ms/op
Iteration   1: 3.977 ±(99.9%) 0.044 ms/op
Iteration   2: 3.855 ±(99.9%) 0.017 ms/op
Iteration   3: 3.930 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.921 ±(99.9%) 1.122 ms/op [Average]
  (min, avg, max) = (3.855, 3.921, 3.977), stdev = 0.062
  CI (99.9%): [2.799, 5.043] (assumes normal distribution)


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.008 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  10.827 ms/op
                 createUser·p0.9999: 18.191 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  8.183 ms/op
                 createUser·p0.9999: 18.589 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.431 ms/op
                 createUser·p0.9999: 21.077 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313228
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23851 
    [ 2.500,  5.000) = 287673 
    [ 5.000,  7.500) = 1241 
    [ 7.500, 10.000) = 184 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.844 ms/op
     p(99.9900) =     20.011 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.005 ms/op
Iteration   1: 2.801 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.310 ms/op
                 existUser·p0.99:   3.871 ms/op
                 existUser·p0.999:  6.532 ms/op
                 existUser·p0.9999: 12.674 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   2: 2.908 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.324 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  7.071 ms/op
                 existUser·p0.9999: 15.303 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   3: 2.853 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.303 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  7.609 ms/op
                 existUser·p0.9999: 17.105 ms/op
                 existUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336508
  mean =      2.853 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2062 
    [ 1.250,  2.500) = 46467 
    [ 2.500,  3.750) = 281466 
    [ 3.750,  5.000) = 5774 
    [ 5.000,  6.250) = 246 
    [ 6.250,  7.500) = 225 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.324 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      7.016 ms/op
     p(99.9900) =     15.516 ms/op
     p(99.9990) =     17.355 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 4.346 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.155 ms/op
                 getUser·p0.9999: 20.251 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.407 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.444 ms/op
                 getUser·p0.9999: 22.654 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   3: 2.978 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.298 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.330 ms/op
                 getUser·p0.95:   3.494 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  7.909 ms/op
                 getUser·p0.9999: 24.027 ms/op
                 getUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320690
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20666 
    [ 2.500,  5.000) = 298738 
    [ 5.000,  7.500) = 984 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.324 ms/op
     p(99.9900) =     23.490 ms/op
     p(99.9990) =     24.562 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 5.618 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.012 ms/op
Iteration   1: 3.984 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.036 ms/op
                 listUser·p0.9999: 18.971 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 3.933 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.014 ms/op
                 listUser·p0.999:  18.585 ms/op
                 listUser·p0.9999: 22.995 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 3.902 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  20.153 ms/op
                 listUser·p0.9999: 27.125 ms/op
                 listUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243595
  mean =      3.939 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2449 
    [ 2.500,  5.000) = 220566 
    [ 5.000,  7.500) = 19285 
    [ 7.500, 10.000) = 886 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     26.837 ms/op
     p(99.9990) =     27.992 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.602 ± 2.964  ops/ms
ClientGrpc.existUser                       thrpt       3  11.137 ± 2.223  ops/ms
ClientGrpc.getUser                         thrpt       3  10.589 ± 1.934  ops/ms
ClientGrpc.listUser                        thrpt       3   8.238 ± 1.690  ops/ms
ClientGrpc.createUser                       avgt       3   3.023 ± 0.205   ms/op
ClientGrpc.existUser                        avgt       3   2.877 ± 0.705   ms/op
ClientGrpc.getUser                          avgt       3   2.995 ± 0.289   ms/op
ClientGrpc.listUser                         avgt       3   3.921 ± 1.122   ms/op
ClientGrpc.createUser                     sample  313228   3.062 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.705           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.844           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.011           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.381           ms/op
ClientGrpc.existUser                      sample  336508   2.853 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.324           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.297           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.944           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.016           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.516           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.498           ms/op
ClientGrpc.getUser                        sample  320690   2.995 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.298           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.424           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.324           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.490           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.068           ms/op
ClientGrpc.listUser                       sample  243595   3.939 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.879           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.941           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.837           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.148           ms/op
