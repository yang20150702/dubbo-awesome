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
# Warmup Iteration   1: 4.389 ops/ms
# Warmup Iteration   2: 8.972 ops/ms
# Warmup Iteration   3: 10.212 ops/ms
Iteration   1: 10.336 ops/ms
Iteration   2: 10.188 ops/ms
Iteration   3: 10.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.245 ±(99.9%) 1.447 ops/ms [Average]
  (min, avg, max) = (10.188, 10.245, 10.336), stdev = 0.079
  CI (99.9%): [8.799, 11.692] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.524 ops/ms
# Warmup Iteration   2: 10.383 ops/ms
# Warmup Iteration   3: 10.513 ops/ms
Iteration   1: 10.538 ops/ms
Iteration   2: 10.555 ops/ms
Iteration   3: 10.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.667 ±(99.9%) 3.826 ops/ms [Average]
  (min, avg, max) = (10.538, 10.667, 10.909), stdev = 0.210
  CI (99.9%): [6.841, 14.494] (assumes normal distribution)


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
# Warmup Iteration   1: 6.633 ops/ms
# Warmup Iteration   2: 9.785 ops/ms
# Warmup Iteration   3: 9.977 ops/ms
Iteration   1: 10.000 ops/ms
Iteration   2: 9.932 ops/ms
Iteration   3: 10.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.022 ±(99.9%) 1.862 ops/ms [Average]
  (min, avg, max) = (9.932, 10.022, 10.133), stdev = 0.102
  CI (99.9%): [8.159, 11.884] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.628 ops/ms
# Warmup Iteration   2: 7.454 ops/ms
# Warmup Iteration   3: 7.772 ops/ms
Iteration   1: 7.817 ops/ms
Iteration   2: 7.778 ops/ms
Iteration   3: 7.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.793 ±(99.9%) 0.381 ops/ms [Average]
  (min, avg, max) = (7.778, 7.793, 7.817), stdev = 0.021
  CI (99.9%): [7.412, 8.175] (assumes normal distribution)


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.004 ms/op
Iteration   1: 3.183 ±(99.9%) 0.008 ms/op
Iteration   2: 3.167 ±(99.9%) 0.002 ms/op
Iteration   3: 3.154 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.168 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (3.154, 3.168, 3.183), stdev = 0.014
  CI (99.9%): [2.906, 3.430] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.002 ms/op
Iteration   1: 3.038 ±(99.9%) 0.002 ms/op
Iteration   2: 2.975 ±(99.9%) 0.002 ms/op
Iteration   3: 2.958 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.990 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (2.958, 2.990, 3.038), stdev = 0.042
  CI (99.9%): [2.218, 3.763] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.416 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.004 ms/op
Iteration   1: 3.200 ±(99.9%) 0.003 ms/op
Iteration   2: 3.205 ±(99.9%) 0.002 ms/op
Iteration   3: 3.200 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.202 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (3.200, 3.202, 3.205), stdev = 0.003
  CI (99.9%): [3.154, 3.250] (assumes normal distribution)


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
# Warmup Iteration   1: 5.749 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.330 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.023 ms/op
Iteration   1: 4.190 ±(99.9%) 0.013 ms/op
Iteration   2: 4.092 ±(99.9%) 0.009 ms/op
Iteration   3: 4.130 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.137 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (4.092, 4.137, 4.190), stdev = 0.050
  CI (99.9%): [3.234, 5.041] (assumes normal distribution)


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
Iteration   1: 3.143 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  8.233 ms/op
                 createUser·p0.9999: 14.480 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 3.165 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  6.302 ms/op
                 createUser·p0.9999: 14.664 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   3: 3.111 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  15.958 ms/op
                 createUser·p0.9999: 22.512 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305614
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18492 
    [ 2.500,  5.000) = 285967 
    [ 5.000,  7.500) = 694 
    [ 7.500, 10.000) = 157 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      9.968 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     22.706 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
Iteration   1: 3.006 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  8.115 ms/op
                 existUser·p0.9999: 18.493 ms/op
                 existUser·p1.00:   18.874 ms/op

Iteration   2: 3.089 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  9.797 ms/op
                 existUser·p0.9999: 17.465 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   3: 3.001 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.943 ms/op
                 existUser·p0.9999: 26.389 ms/op
                 existUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316494
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42688 
    [ 2.500,  5.000) = 272601 
    [ 5.000,  7.500) = 831 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     25.603 ms/op
     p(99.9990) =     27.045 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 4.458 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.007 ms/op
Iteration   1: 3.194 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.898 ms/op
                 getUser·p0.9999: 13.434 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 3.155 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  8.045 ms/op
                 getUser·p0.9999: 15.331 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.037 ms/op
                 getUser·p0.9999: 28.567 ms/op
                 getUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302596
  mean =      3.172 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18322 
    [ 2.500,  5.000) = 283287 
    [ 5.000,  7.500) = 730 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.229 ms/op
     p(99.9900) =     27.639 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 6.116 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.011 ms/op
Iteration   1: 4.121 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.367 ms/op
                 listUser·p0.999:  15.321 ms/op
                 listUser·p0.9999: 19.796 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   2: 4.216 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.701 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  16.943 ms/op
                 listUser·p0.9999: 22.754 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   3: 4.270 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.711 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   5.661 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  18.063 ms/op
                 listUser·p0.9999: 25.494 ms/op
                 listUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228661
  mean =      4.201 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2683 
    [ 2.500,  5.000) = 188091 
    [ 5.000,  7.500) = 35907 
    [ 7.500, 10.000) = 1454 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      5.489 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     25.301 ms/op
     p(99.9990) =     26.836 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.245 ± 1.447  ops/ms
ClientGrpc.existUser                       thrpt       3  10.667 ± 3.826  ops/ms
ClientGrpc.getUser                         thrpt       3  10.022 ± 1.862  ops/ms
ClientGrpc.listUser                        thrpt       3   7.793 ± 0.381  ops/ms
ClientGrpc.createUser                       avgt       3   3.168 ± 0.262   ms/op
ClientGrpc.existUser                        avgt       3   2.990 ± 0.773   ms/op
ClientGrpc.getUser                          avgt       3   3.202 ± 0.048   ms/op
ClientGrpc.listUser                         avgt       3   4.137 ± 0.904   ms/op
ClientGrpc.createUser                     sample  305614   3.140 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.709           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.968           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.791           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.938           ms/op
ClientGrpc.existUser                      sample  316494   3.031 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.640           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.389           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.603           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.886           ms/op
ClientGrpc.getUser                        sample  302596   3.172 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.877           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.142           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.010           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.229           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.639           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.032           ms/op
ClientGrpc.listUser                       sample  228661   4.201 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.701           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.985           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.111           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.356           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.236           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.301           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.427           ms/op
