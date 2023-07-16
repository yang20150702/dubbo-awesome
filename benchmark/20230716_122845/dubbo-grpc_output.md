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
# Warmup Iteration   1: 4.491 ops/ms
# Warmup Iteration   2: 9.064 ops/ms
# Warmup Iteration   3: 10.123 ops/ms
Iteration   1: 10.383 ops/ms
Iteration   2: 10.441 ops/ms
Iteration   3: 10.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.410 ±(99.9%) 0.532 ops/ms [Average]
  (min, avg, max) = (10.383, 10.410, 10.441), stdev = 0.029
  CI (99.9%): [9.877, 10.942] (assumes normal distribution)


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
# Warmup Iteration   1: 7.374 ops/ms
# Warmup Iteration   2: 10.492 ops/ms
# Warmup Iteration   3: 11.142 ops/ms
Iteration   1: 11.065 ops/ms
Iteration   2: 11.086 ops/ms
Iteration   3: 10.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.992 ±(99.9%) 2.653 ops/ms [Average]
  (min, avg, max) = (10.824, 10.992, 11.086), stdev = 0.145
  CI (99.9%): [8.339, 13.644] (assumes normal distribution)


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
# Warmup Iteration   1: 7.081 ops/ms
# Warmup Iteration   2: 9.844 ops/ms
# Warmup Iteration   3: 10.271 ops/ms
Iteration   1: 10.325 ops/ms
Iteration   2: 10.368 ops/ms
Iteration   3: 10.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.391 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (10.325, 10.391, 10.481), stdev = 0.081
  CI (99.9%): [8.918, 11.864] (assumes normal distribution)


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
# Warmup Iteration   1: 5.787 ops/ms
# Warmup Iteration   2: 7.768 ops/ms
# Warmup Iteration   3: 7.957 ops/ms
Iteration   1: 8.161 ops/ms
Iteration   2: 8.113 ops/ms
Iteration   3: 8.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.173 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (8.113, 8.173, 8.243), stdev = 0.066
  CI (99.9%): [6.973, 9.372] (assumes normal distribution)


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.002 ms/op
Iteration   2: 3.052 ±(99.9%) 0.004 ms/op
Iteration   3: 3.094 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.072 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.052, 3.072, 3.094), stdev = 0.021
  CI (99.9%): [2.689, 3.455] (assumes normal distribution)


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.003 ms/op
Iteration   1: 2.940 ±(99.9%) 0.002 ms/op
Iteration   2: 2.871 ±(99.9%) 0.001 ms/op
Iteration   3: 2.967 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.926 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (2.871, 2.926, 2.967), stdev = 0.050
  CI (99.9%): [2.022, 3.830] (assumes normal distribution)


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.002 ms/op
Iteration   1: 3.030 ±(99.9%) 0.003 ms/op
Iteration   2: 3.020 ±(99.9%) 0.004 ms/op
Iteration   3: 3.040 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.030 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (3.020, 3.030, 3.040), stdev = 0.010
  CI (99.9%): [2.850, 3.209] (assumes normal distribution)


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
# Warmup Iteration   1: 5.723 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.007 ms/op
Iteration   1: 3.858 ±(99.9%) 0.012 ms/op
Iteration   2: 3.768 ±(99.9%) 0.011 ms/op
Iteration   3: 3.918 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.848 ±(99.9%) 1.375 ms/op [Average]
  (min, avg, max) = (3.768, 3.848, 3.918), stdev = 0.075
  CI (99.9%): [2.473, 5.223] (assumes normal distribution)


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
# Warmup Iteration   1: 4.366 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  6.855 ms/op
                 createUser·p0.9999: 12.370 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   2: 3.040 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.615 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.348 ms/op
                 createUser·p0.9999: 15.122 ms/op
                 createUser·p1.00:   15.712 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.643 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  10.293 ms/op
                 createUser·p0.9999: 16.177 ms/op
                 createUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318182
  mean =      3.015 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 744 
    [ 1.250,  2.500) = 21955 
    [ 2.500,  3.750) = 282012 
    [ 3.750,  5.000) = 11351 
    [ 5.000,  6.250) = 1237 
    [ 6.250,  7.500) = 447 
    [ 7.500,  8.750) = 151 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      8.076 ms/op
     p(99.9900) =     15.122 ms/op
     p(99.9990) =     16.388 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.831 ±(99.9%) 0.006 ms/op
Iteration   1: 2.926 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.020 ms/op
                 existUser·p0.999:  6.324 ms/op
                 existUser·p0.9999: 17.729 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 2.928 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.266 ms/op
                 existUser·p0.9999: 16.539 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   3: 2.922 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.391 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  11.197 ms/op
                 existUser·p0.9999: 26.773 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328127
  mean =      2.925 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31431 
    [ 2.500,  5.000) = 295450 
    [ 5.000,  7.500) = 876 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      8.264 ms/op
     p(99.9900) =     19.602 ms/op
     p(99.9990) =     26.935 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  6.644 ms/op
                 getUser·p0.9999: 13.395 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.560 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.159 ms/op
                 getUser·p0.9999: 30.081 ms/op
                 getUser·p1.00:   30.310 ms/op

Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.771 ms/op
                 getUser·p0.9999: 18.955 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313088
  mean =      3.064 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19349 
    [ 2.500,  5.000) = 292483 
    [ 5.000,  7.500) = 990 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.028 ms/op
     p(99.9900) =     18.995 ms/op
     p(99.9990) =     30.245 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 5.615 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.011 ms/op
Iteration   1: 3.815 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.156 ms/op
                 listUser·p0.9999: 20.291 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   2: 3.950 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  15.006 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   3: 3.901 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 26.116 ms/op
                 listUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246950
  mean =      3.888 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4593 
    [ 2.500,  5.000) = 219531 
    [ 5.000,  7.500) = 21777 
    [ 7.500, 10.000) = 648 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     13.813 ms/op
     p(99.9900) =     25.448 ms/op
     p(99.9990) =     27.020 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.410 ± 0.532  ops/ms
ClientGrpc.existUser                       thrpt       3  10.992 ± 2.653  ops/ms
ClientGrpc.getUser                         thrpt       3  10.391 ± 1.473  ops/ms
ClientGrpc.listUser                        thrpt       3   8.173 ± 1.200  ops/ms
ClientGrpc.createUser                       avgt       3   3.072 ± 0.383   ms/op
ClientGrpc.existUser                        avgt       3   2.926 ± 0.904   ms/op
ClientGrpc.getUser                          avgt       3   3.030 ± 0.180   ms/op
ClientGrpc.listUser                         avgt       3   3.848 ± 1.375   ms/op
ClientGrpc.createUser                     sample  318182   3.015 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.615           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.076           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.122           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.826           ms/op
ClientGrpc.existUser                      sample  328127   2.925 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.499           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.264           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.602           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.034           ms/op
ClientGrpc.getUser                        sample  313088   3.064 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.560           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.028           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.995           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.310           ms/op
ClientGrpc.listUser                       sample  246950   3.888 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.075           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.813           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.448           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.132           ms/op
