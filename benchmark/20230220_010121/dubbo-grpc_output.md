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
# Warmup Iteration   1: 4.865 ops/ms
# Warmup Iteration   2: 9.400 ops/ms
# Warmup Iteration   3: 10.655 ops/ms
Iteration   1: 10.834 ops/ms
Iteration   2: 10.520 ops/ms
Iteration   3: 10.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.613 ±(99.9%) 3.505 ops/ms [Average]
  (min, avg, max) = (10.485, 10.613, 10.834), stdev = 0.192
  CI (99.9%): [7.108, 14.118] (assumes normal distribution)


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
# Warmup Iteration   1: 8.316 ops/ms
# Warmup Iteration   2: 10.592 ops/ms
# Warmup Iteration   3: 10.760 ops/ms
Iteration   1: 11.169 ops/ms
Iteration   2: 10.877 ops/ms
Iteration   3: 11.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.111 ±(99.9%) 3.840 ops/ms [Average]
  (min, avg, max) = (10.877, 11.111, 11.286), stdev = 0.210
  CI (99.9%): [7.271, 14.951] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.502 ops/ms
# Warmup Iteration   2: 10.320 ops/ms
# Warmup Iteration   3: 10.695 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.980 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.744 ±(99.9%) 3.854 ops/ms [Average]
  (min, avg, max) = (10.572, 10.744, 10.980), stdev = 0.211
  CI (99.9%): [6.891, 14.598] (assumes normal distribution)


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
# Warmup Iteration   1: 5.877 ops/ms
# Warmup Iteration   2: 8.045 ops/ms
# Warmup Iteration   3: 8.103 ops/ms
Iteration   1: 8.213 ops/ms
Iteration   2: 8.290 ops/ms
Iteration   3: 8.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.351 ±(99.9%) 3.228 ops/ms [Average]
  (min, avg, max) = (8.213, 8.351, 8.551), stdev = 0.177
  CI (99.9%): [5.123, 11.579] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.002 ms/op
Iteration   1: 3.097 ±(99.9%) 0.004 ms/op
Iteration   2: 3.194 ±(99.9%) 0.002 ms/op
Iteration   3: 3.239 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.177 ±(99.9%) 1.320 ms/op [Average]
  (min, avg, max) = (3.097, 3.177, 3.239), stdev = 0.072
  CI (99.9%): [1.856, 4.497] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.171 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.002 ms/op
Iteration   1: 3.044 ±(99.9%) 0.002 ms/op
Iteration   2: 3.033 ±(99.9%) 0.001 ms/op
Iteration   3: 3.040 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.039 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (3.033, 3.039, 3.044), stdev = 0.006
  CI (99.9%): [2.937, 3.141] (assumes normal distribution)


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
# Warmup Iteration   1: 4.198 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.265 ±(99.9%) 0.002 ms/op
Iteration   1: 3.132 ±(99.9%) 0.002 ms/op
Iteration   2: 3.198 ±(99.9%) 0.002 ms/op
Iteration   3: 3.210 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.180 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (3.132, 3.180, 3.210), stdev = 0.042
  CI (99.9%): [2.412, 3.948] (assumes normal distribution)


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
# Warmup Iteration   1: 5.737 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.009 ms/op
Iteration   1: 4.095 ±(99.9%) 0.013 ms/op
Iteration   2: 4.067 ±(99.9%) 0.012 ms/op
Iteration   3: 4.089 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.084 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (4.067, 4.084, 4.095), stdev = 0.015
  CI (99.9%): [3.813, 4.354] (assumes normal distribution)


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
# Warmup Iteration   1: 4.587 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.008 ms/op
Iteration   1: 3.232 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.557 ms/op
                 createUser·p0.9999: 22.257 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.277 ms/op
                 createUser·p0.9999: 23.904 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 3.234 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.809 ms/op
                 createUser·p0.9999: 26.545 ms/op
                 createUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297697
  mean =      3.225 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20890 
    [ 2.500,  5.000) = 275690 
    [ 5.000,  7.500) = 721 
    [ 7.500, 10.000) = 201 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.170 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     26.904 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 4.057 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.007 ms/op
Iteration   1: 2.947 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  7.893 ms/op
                 existUser·p0.9999: 20.288 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.433 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  9.670 ms/op
                 existUser·p0.9999: 17.596 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  9.229 ms/op
                 existUser·p0.9999: 27.418 ms/op
                 existUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316973
  mean =      3.027 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41656 
    [ 2.500,  5.000) = 274313 
    [ 5.000,  7.500) = 559 
    [ 7.500, 10.000) = 169 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      9.307 ms/op
     p(99.9900) =     25.317 ms/op
     p(99.9990) =     27.716 ms/op
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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.006 ms/op
Iteration   1: 3.190 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  8.684 ms/op
                 getUser·p0.9999: 14.450 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   2: 3.157 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.750 ms/op
                 getUser·p0.9999: 18.668 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.892 ms/op
                 getUser·p0.9999: 18.693 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305352
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 363 
    [ 1.250,  2.500) = 20830 
    [ 2.500,  3.750) = 253147 
    [ 3.750,  5.000) = 29841 
    [ 5.000,  6.250) = 557 
    [ 6.250,  7.500) = 297 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.561 ms/op
     p(99.9900) =     18.365 ms/op
     p(99.9990) =     19.200 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 6.130 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.011 ms/op
Iteration   1: 4.098 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.629 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   2: 4.068 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  15.889 ms/op
                 listUser·p0.9999: 18.879 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 4.135 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  17.193 ms/op
                 listUser·p0.9999: 23.226 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234089
  mean =      4.100 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1831 
    [ 2.500,  5.000) = 203753 
    [ 5.000,  7.500) = 27164 
    [ 7.500, 10.000) = 946 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     15.417 ms/op
     p(99.9900) =     22.124 ms/op
     p(99.9990) =     23.571 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.613 ± 3.505  ops/ms
ClientGrpc.existUser                       thrpt       3  11.111 ± 3.840  ops/ms
ClientGrpc.getUser                         thrpt       3  10.744 ± 3.854  ops/ms
ClientGrpc.listUser                        thrpt       3   8.351 ± 3.228  ops/ms
ClientGrpc.createUser                       avgt       3   3.177 ± 1.320   ms/op
ClientGrpc.existUser                        avgt       3   3.039 ± 0.102   ms/op
ClientGrpc.getUser                          avgt       3   3.180 ± 0.768   ms/op
ClientGrpc.listUser                         avgt       3   4.084 ± 0.271   ms/op
ClientGrpc.createUser                     sample  297697   3.225 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.580           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.195           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.100           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.170           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.985           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.034           ms/op
ClientGrpc.existUser                      sample  316973   3.027 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.433           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.307           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.317           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.886           ms/op
ClientGrpc.getUser                        sample  305352   3.145 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.854           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.944           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.561           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.365           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.988           ms/op
ClientGrpc.listUser                       sample  234089   4.100 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.007           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.417           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.124           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.691           ms/op
