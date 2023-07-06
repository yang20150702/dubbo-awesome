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
# Warmup Iteration   1: 4.151 ops/ms
# Warmup Iteration   2: 8.743 ops/ms
# Warmup Iteration   3: 10.125 ops/ms
Iteration   1: 10.606 ops/ms
Iteration   2: 10.602 ops/ms
Iteration   3: 10.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.558 ±(99.9%) 1.457 ops/ms [Average]
  (min, avg, max) = (10.466, 10.558, 10.606), stdev = 0.080
  CI (99.9%): [9.101, 12.015] (assumes normal distribution)


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
# Warmup Iteration   1: 7.345 ops/ms
# Warmup Iteration   2: 10.314 ops/ms
# Warmup Iteration   3: 11.035 ops/ms
Iteration   1: 10.923 ops/ms
Iteration   2: 11.140 ops/ms
Iteration   3: 11.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.073 ±(99.9%) 2.378 ops/ms [Average]
  (min, avg, max) = (10.923, 11.073, 11.156), stdev = 0.130
  CI (99.9%): [8.695, 13.451] (assumes normal distribution)


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
# Warmup Iteration   1: 7.138 ops/ms
# Warmup Iteration   2: 10.209 ops/ms
# Warmup Iteration   3: 10.404 ops/ms
Iteration   1: 10.703 ops/ms
Iteration   2: 10.349 ops/ms
Iteration   3: 10.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.536 ±(99.9%) 3.250 ops/ms [Average]
  (min, avg, max) = (10.349, 10.536, 10.703), stdev = 0.178
  CI (99.9%): [7.286, 13.786] (assumes normal distribution)


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
# Warmup Iteration   1: 6.150 ops/ms
# Warmup Iteration   2: 7.551 ops/ms
# Warmup Iteration   3: 8.048 ops/ms
Iteration   1: 7.964 ops/ms
Iteration   2: 8.116 ops/ms
Iteration   3: 8.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.097 ±(99.9%) 2.283 ops/ms [Average]
  (min, avg, max) = (7.964, 8.097, 8.212), stdev = 0.125
  CI (99.9%): [5.815, 10.380] (assumes normal distribution)


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
# Warmup Iteration   1: 4.289 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.002 ms/op
Iteration   1: 3.001 ±(99.9%) 0.003 ms/op
Iteration   2: 3.055 ±(99.9%) 0.004 ms/op
Iteration   3: 3.005 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.020 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (3.001, 3.020, 3.055), stdev = 0.030
  CI (99.9%): [2.472, 3.569] (assumes normal distribution)


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.003 ms/op
Iteration   1: 2.873 ±(99.9%) 0.002 ms/op
Iteration   2: 2.920 ±(99.9%) 0.002 ms/op
Iteration   3: 2.902 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.898 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (2.873, 2.898, 2.920), stdev = 0.024
  CI (99.9%): [2.465, 3.331] (assumes normal distribution)


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
# Warmup Iteration   1: 4.140 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.004 ms/op
Iteration   1: 3.061 ±(99.9%) 0.003 ms/op
Iteration   2: 3.046 ±(99.9%) 0.002 ms/op
Iteration   3: 3.004 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.037 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (3.004, 3.037, 3.061), stdev = 0.029
  CI (99.9%): [2.501, 3.572] (assumes normal distribution)


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
# Warmup Iteration   1: 5.630 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.016 ms/op
Iteration   1: 3.916 ±(99.9%) 0.023 ms/op
Iteration   2: 3.965 ±(99.9%) 0.023 ms/op
Iteration   3: 3.901 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.927 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (3.901, 3.927, 3.965), stdev = 0.034
  CI (99.9%): [3.316, 4.538] (assumes normal distribution)


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.252 ms/op
                 createUser·p0.9999: 18.219 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  6.287 ms/op
                 createUser·p0.9999: 17.334 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  13.603 ms/op
                 createUser·p0.9999: 20.677 ms/op
                 createUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315723
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20220 
    [ 2.500,  5.000) = 293974 
    [ 5.000,  7.500) = 1251 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.039 ms/op
     p(99.9900) =     20.232 ms/op
     p(99.9990) =     22.578 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.005 ms/op
Iteration   1: 2.867 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.213 ms/op
                 existUser·p0.9999: 12.807 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   2: 2.878 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.300 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  6.799 ms/op
                 existUser·p0.9999: 14.762 ms/op
                 existUser·p1.00:   16.384 ms/op

Iteration   3: 2.901 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   3.969 ms/op
                 existUser·p0.999:  6.210 ms/op
                 existUser·p0.9999: 16.876 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333021
  mean =      2.882 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1965 
    [ 1.250,  2.500) = 37487 
    [ 2.500,  3.750) = 285567 
    [ 3.750,  5.000) = 7098 
    [ 5.000,  6.250) = 492 
    [ 6.250,  7.500) = 249 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 89 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.300 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      6.455 ms/op
     p(99.9900) =     16.418 ms/op
     p(99.9990) =     17.204 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.008 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.975 ms/op
                 getUser·p0.9999: 19.839 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.414 ms/op
                 getUser·p0.9999: 19.919 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   3: 2.984 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.578 ms/op
                 getUser·p0.9999: 23.308 ms/op
                 getUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318252
  mean =      3.015 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20175 
    [ 2.500,  5.000) = 296918 
    [ 5.000,  7.500) = 927 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.004 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 5.838 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.011 ms/op
Iteration   1: 3.977 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  13.755 ms/op
                 listUser·p0.9999: 16.007 ms/op
                 listUser·p1.00:   16.646 ms/op

Iteration   2: 3.938 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  14.464 ms/op
                 listUser·p0.9999: 17.355 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 3.945 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  16.645 ms/op
                 listUser·p0.9999: 25.680 ms/op
                 listUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242706
  mean =      3.953 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3671 
    [ 2.500,  5.000) = 217768 
    [ 5.000,  7.500) = 20136 
    [ 7.500, 10.000) = 638 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.374 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     26.149 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.558 ± 1.457  ops/ms
ClientGrpc.existUser                       thrpt       3  11.073 ± 2.378  ops/ms
ClientGrpc.getUser                         thrpt       3  10.536 ± 3.250  ops/ms
ClientGrpc.listUser                        thrpt       3   8.097 ± 2.283  ops/ms
ClientGrpc.createUser                       avgt       3   3.020 ± 0.549   ms/op
ClientGrpc.existUser                        avgt       3   2.898 ± 0.433   ms/op
ClientGrpc.getUser                          avgt       3   3.037 ± 0.536   ms/op
ClientGrpc.listUser                         avgt       3   3.927 ± 0.611   ms/op
ClientGrpc.createUser                     sample  315723   3.042 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.577           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.039           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.232           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.970           ms/op
ClientGrpc.existUser                      sample  333021   2.882 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.300           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.314           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.455           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.418           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.269           ms/op
ClientGrpc.getUser                        sample  318252   3.015 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.754           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.004           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.217           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.560           ms/op
ClientGrpc.listUser                       sample  242706   3.953 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.924           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.374           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.183           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.149           ms/op
