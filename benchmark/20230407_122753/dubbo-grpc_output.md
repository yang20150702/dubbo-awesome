# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.061 ops/ms
# Warmup Iteration   2: 8.919 ops/ms
# Warmup Iteration   3: 10.227 ops/ms
Iteration   1: 10.625 ops/ms
Iteration   2: 10.546 ops/ms
Iteration   3: 10.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.631 ±(99.9%) 1.601 ops/ms [Average]
  (min, avg, max) = (10.546, 10.631, 10.721), stdev = 0.088
  CI (99.9%): [9.030, 12.231] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.115 ops/ms
# Warmup Iteration   2: 10.432 ops/ms
# Warmup Iteration   3: 10.974 ops/ms
Iteration   1: 11.060 ops/ms
Iteration   2: 11.079 ops/ms
Iteration   3: 11.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.119 ±(99.9%) 1.556 ops/ms [Average]
  (min, avg, max) = (11.060, 11.119, 11.217), stdev = 0.085
  CI (99.9%): [9.563, 12.675] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.983 ops/ms
# Warmup Iteration   2: 10.199 ops/ms
# Warmup Iteration   3: 10.568 ops/ms
Iteration   1: 10.667 ops/ms
Iteration   2: 10.667 ops/ms
Iteration   3: 10.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.649 ±(99.9%) 0.568 ops/ms [Average]
  (min, avg, max) = (10.613, 10.649, 10.667), stdev = 0.031
  CI (99.9%): [10.082, 11.217] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.671 ops/ms
# Warmup Iteration   2: 7.604 ops/ms
# Warmup Iteration   3: 8.088 ops/ms
Iteration   1: 7.941 ops/ms
Iteration   2: 8.039 ops/ms
Iteration   3: 8.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.997 ±(99.9%) 0.929 ops/ms [Average]
  (min, avg, max) = (7.941, 7.997, 8.039), stdev = 0.051
  CI (99.9%): [7.068, 8.926] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.514 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.002 ms/op
Iteration   1: 3.024 ±(99.9%) 0.002 ms/op
Iteration   2: 2.987 ±(99.9%) 0.003 ms/op
Iteration   3: 2.964 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.992 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (2.964, 2.992, 3.024), stdev = 0.031
  CI (99.9%): [2.433, 3.550] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.142 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.938 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.002 ms/op
Iteration   1: 2.877 ±(99.9%) 0.002 ms/op
Iteration   2: 2.877 ±(99.9%) 0.003 ms/op
Iteration   3: 2.881 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.878 ±(99.9%) 0.045 ms/op [Average]
  (min, avg, max) = (2.877, 2.878, 2.881), stdev = 0.002
  CI (99.9%): [2.834, 2.923] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.023 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.002 ms/op
Iteration   1: 3.026 ±(99.9%) 0.003 ms/op
Iteration   2: 3.020 ±(99.9%) 0.003 ms/op
Iteration   3: 2.966 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.004 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (2.966, 3.004, 3.026), stdev = 0.033
  CI (99.9%): [2.405, 3.603] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.617 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.018 ms/op
Iteration   1: 3.975 ±(99.9%) 0.027 ms/op
Iteration   2: 3.974 ±(99.9%) 0.017 ms/op
Iteration   3: 3.994 ±(99.9%) 0.059 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.981 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.974, 3.981, 3.994), stdev = 0.011
  CI (99.9%): [3.781, 4.180] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.326 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.236 ms/op
                 createUser·p0.9999: 12.976 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  7.339 ms/op
                 createUser·p0.9999: 21.966 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  8.554 ms/op
                 createUser·p0.9999: 21.179 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319885
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27818 
    [ 2.500,  5.000) = 290803 
    [ 5.000,  7.500) = 894 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.201 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     22.210 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 2.885 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.291 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 20.047 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   2: 2.881 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 15.054 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   3: 2.895 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.738 ms/op
                 existUser·p0.9999: 18.905 ms/op
                 existUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332507
  mean =      2.887 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41944 
    [ 2.500,  5.000) = 289495 
    [ 5.000,  7.500) = 809 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      7.070 ms/op
     p(99.9900) =     19.251 ms/op
     p(99.9990) =     20.229 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.381 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.066 ms/op
                 getUser·p0.9999: 19.366 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   2: 3.062 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.293 ms/op
                 getUser·p0.9999: 14.338 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   3: 3.001 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.112 ms/op
                 getUser·p0.999:  7.258 ms/op
                 getUser·p0.9999: 15.412 ms/op
                 getUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316460
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 294 
    [ 1.250,  2.500) = 20373 
    [ 2.500,  3.750) = 282700 
    [ 3.750,  5.000) = 11928 
    [ 5.000,  6.250) = 647 
    [ 6.250,  7.500) = 184 
    [ 7.500,  8.750) = 106 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     17.816 ms/op
     p(99.9990) =     19.492 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.472 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.010 ms/op
Iteration   1: 3.959 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.404 ms/op
                 listUser·p0.9999: 21.392 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   2: 3.972 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.435 ms/op
                 listUser·p0.9999: 17.498 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   3: 3.979 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   6.882 ms/op
                 listUser·p0.999:  17.387 ms/op
                 listUser·p0.9999: 26.342 ms/op
                 listUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241704
  mean =      3.970 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2772 
    [ 2.500,  5.000) = 216370 
    [ 5.000,  7.500) = 21245 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.980 ms/op
     p(99.9900) =     25.848 ms/op
     p(99.9990) =     28.950 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.631 ± 1.601  ops/ms
ClientGrpc.existUser                       thrpt       3  11.119 ± 1.556  ops/ms
ClientGrpc.getUser                         thrpt       3  10.649 ± 0.568  ops/ms
ClientGrpc.listUser                        thrpt       3   7.997 ± 0.929  ops/ms
ClientGrpc.createUser                       avgt       3   2.992 ± 0.559   ms/op
ClientGrpc.existUser                        avgt       3   2.878 ± 0.045   ms/op
ClientGrpc.getUser                          avgt       3   3.004 ± 0.599   ms/op
ClientGrpc.listUser                         avgt       3   3.981 ± 0.199   ms/op
ClientGrpc.createUser                     sample  319885   3.001 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.637           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.201           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.529           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.315           ms/op
ClientGrpc.existUser                      sample  332507   2.887 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.717           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.314           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.070           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.251           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.382           ms/op
ClientGrpc.getUser                        sample  316460   3.032 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.780           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.799           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.816           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.890           ms/op
ClientGrpc.listUser                       sample  241704   3.970 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.815           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.980           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.848           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.032           ms/op
