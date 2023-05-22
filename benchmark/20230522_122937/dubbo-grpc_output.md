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
# Warmup Iteration   1: 3.712 ops/ms
# Warmup Iteration   2: 7.287 ops/ms
# Warmup Iteration   3: 8.426 ops/ms
Iteration   1: 8.636 ops/ms
Iteration   2: 8.950 ops/ms
Iteration   3: 8.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.783 ±(99.9%) 2.878 ops/ms [Average]
  (min, avg, max) = (8.636, 8.783, 8.950), stdev = 0.158
  CI (99.9%): [5.905, 11.661] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.175 ops/ms
# Warmup Iteration   2: 8.894 ops/ms
# Warmup Iteration   3: 9.567 ops/ms
Iteration   1: 9.212 ops/ms
Iteration   2: 9.524 ops/ms
Iteration   3: 9.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.365 ±(99.9%) 2.847 ops/ms [Average]
  (min, avg, max) = (9.212, 9.365, 9.524), stdev = 0.156
  CI (99.9%): [6.518, 12.212] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.715 ops/ms
# Warmup Iteration   2: 8.605 ops/ms
# Warmup Iteration   3: 9.447 ops/ms
Iteration   1: 9.348 ops/ms
Iteration   2: 8.902 ops/ms
Iteration   3: 9.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.133 ±(99.9%) 4.074 ops/ms [Average]
  (min, avg, max) = (8.902, 9.133, 9.348), stdev = 0.223
  CI (99.9%): [5.058, 13.207] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.146 ops/ms
# Warmup Iteration   2: 6.400 ops/ms
# Warmup Iteration   3: 6.894 ops/ms
Iteration   1: 6.902 ops/ms
Iteration   2: 7.028 ops/ms
Iteration   3: 6.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.958 ±(99.9%) 1.162 ops/ms [Average]
  (min, avg, max) = (6.902, 6.958, 7.028), stdev = 0.064
  CI (99.9%): [5.796, 8.121] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.886 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.622 ±(99.9%) 0.005 ms/op
Iteration   1: 3.715 ±(99.9%) 0.004 ms/op
Iteration   2: 3.524 ±(99.9%) 0.003 ms/op
Iteration   3: 3.483 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.574 ±(99.9%) 2.261 ms/op [Average]
  (min, avg, max) = (3.483, 3.574, 3.715), stdev = 0.124
  CI (99.9%): [1.313, 5.835] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.004 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.004 ms/op
Iteration   1: 3.467 ±(99.9%) 0.003 ms/op
Iteration   2: 3.442 ±(99.9%) 0.003 ms/op
Iteration   3: 3.460 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.456 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (3.442, 3.456, 3.467), stdev = 0.013
  CI (99.9%): [3.220, 3.692] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.206 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.008 ms/op
Iteration   1: 3.571 ±(99.9%) 0.003 ms/op
Iteration   2: 3.680 ±(99.9%) 0.003 ms/op
Iteration   3: 3.572 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.607 ±(99.9%) 1.140 ms/op [Average]
  (min, avg, max) = (3.571, 3.607, 3.680), stdev = 0.063
  CI (99.9%): [2.467, 4.748] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.600 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.994 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.585 ±(99.9%) 0.011 ms/op
Iteration   1: 4.690 ±(99.9%) 0.021 ms/op
Iteration   2: 4.700 ±(99.9%) 0.023 ms/op
Iteration   3: 4.689 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.693 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (4.689, 4.693, 4.700), stdev = 0.006
  CI (99.9%): [4.588, 4.798] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.334 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.009 ms/op
Iteration   1: 3.578 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  13.255 ms/op
                 createUser·p0.9999: 14.773 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   2: 3.490 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  11.403 ms/op
                 createUser·p0.9999: 14.223 ms/op
                 createUser·p1.00:   16.024 ms/op

Iteration   3: 3.513 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  12.598 ms/op
                 createUser·p0.9999: 19.264 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 272404
  mean =      3.526 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9296 
    [ 2.500,  5.000) = 258906 
    [ 5.000,  7.500) = 3500 
    [ 7.500, 10.000) = 309 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     12.167 ms/op
     p(99.9900) =     18.229 ms/op
     p(99.9990) =     19.707 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 5.049 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.800 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.007 ms/op
Iteration   1: 3.445 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  9.996 ms/op
                 existUser·p0.9999: 14.031 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   2: 3.350 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  9.265 ms/op
                 existUser·p0.9999: 26.640 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   3: 3.312 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 20.732 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 285152
  mean =      3.368 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12046 
    [ 2.500,  5.000) = 268237 
    [ 5.000,  7.500) = 4121 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     10.923 ms/op
     p(99.9900) =     26.165 ms/op
     p(99.9990) =     26.945 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.932 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.007 ms/op
Iteration   1: 3.732 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  12.875 ms/op
                 getUser·p0.9999: 26.322 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   2: 3.809 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  11.200 ms/op
                 getUser·p0.9999: 17.760 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   3: 3.562 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   5.512 ms/op
                 getUser·p0.999:  13.079 ms/op
                 getUser·p0.9999: 18.055 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259368
  mean =      3.698 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4921 
    [ 2.500,  5.000) = 245911 
    [ 5.000,  7.500) = 7476 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     25.367 ms/op
     p(99.9990) =     26.686 ms/op
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
# Warmup Iteration   1: 6.609 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.826 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.678 ±(99.9%) 0.014 ms/op
Iteration   1: 4.720 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.947 ms/op
                 listUser·p0.95:   6.816 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  15.498 ms/op
                 listUser·p0.9999: 18.226 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   2: 4.714 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   8.772 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 25.310 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   3: 4.699 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.972 ms/op
                 listUser·p0.95:   6.892 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  20.907 ms/op
                 listUser·p0.9999: 23.955 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203705
  mean =      4.711 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 533 
    [ 2.500,  5.000) = 156223 
    [ 5.000,  7.500) = 41174 
    [ 7.500, 10.000) = 4769 
    [10.000, 12.500) = 561 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.980 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     24.892 ms/op
     p(99.9990) =     25.852 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.783 ± 2.878  ops/ms
ClientGrpc.existUser                       thrpt       3   9.365 ± 2.847  ops/ms
ClientGrpc.getUser                         thrpt       3   9.133 ± 4.074  ops/ms
ClientGrpc.listUser                        thrpt       3   6.958 ± 1.162  ops/ms
ClientGrpc.createUser                       avgt       3   3.574 ± 2.261   ms/op
ClientGrpc.existUser                        avgt       3   3.456 ± 0.236   ms/op
ClientGrpc.getUser                          avgt       3   3.607 ± 1.140   ms/op
ClientGrpc.listUser                         avgt       3   4.693 ± 0.105   ms/op
ClientGrpc.createUser                     sample  272404   3.526 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.600           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.121           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.341           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.167           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.229           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.513           ms/op
ClientGrpc.existUser                      sample  285152   3.368 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.575           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.521           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.923           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.165           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.034           ms/op
ClientGrpc.getUser                        sample  259368   3.698 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.738           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.947           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.272           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.367           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.739           ms/op
ClientGrpc.listUser                       sample  203705   4.711 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.157           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.473           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.892           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.952           ms/op
