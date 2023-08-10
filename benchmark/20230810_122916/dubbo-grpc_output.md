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
# Warmup Iteration   1: 4.107 ops/ms
# Warmup Iteration   2: 8.385 ops/ms
# Warmup Iteration   3: 10.124 ops/ms
Iteration   1: 10.526 ops/ms
Iteration   2: 10.723 ops/ms
Iteration   3: 10.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.540 ±(99.9%) 3.211 ops/ms [Average]
  (min, avg, max) = (10.372, 10.540, 10.723), stdev = 0.176
  CI (99.9%): [7.329, 13.751] (assumes normal distribution)


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
# Warmup Iteration   1: 6.920 ops/ms
# Warmup Iteration   2: 10.328 ops/ms
# Warmup Iteration   3: 11.053 ops/ms
Iteration   1: 10.881 ops/ms
Iteration   2: 10.966 ops/ms
Iteration   3: 11.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.958 ±(99.9%) 1.339 ops/ms [Average]
  (min, avg, max) = (10.881, 10.958, 11.027), stdev = 0.073
  CI (99.9%): [9.618, 12.297] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.917 ops/ms
# Warmup Iteration   2: 9.990 ops/ms
# Warmup Iteration   3: 10.564 ops/ms
Iteration   1: 10.400 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 10.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.422 ±(99.9%) 0.352 ops/ms [Average]
  (min, avg, max) = (10.400, 10.422, 10.434), stdev = 0.019
  CI (99.9%): [10.070, 10.774] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.599 ops/ms
# Warmup Iteration   2: 7.529 ops/ms
# Warmup Iteration   3: 7.866 ops/ms
Iteration   1: 8.057 ops/ms
Iteration   2: 7.874 ops/ms
Iteration   3: 7.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.945 ±(99.9%) 1.800 ops/ms [Average]
  (min, avg, max) = (7.874, 7.945, 8.057), stdev = 0.099
  CI (99.9%): [6.145, 9.744] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.427 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.004 ms/op
Iteration   1: 3.095 ±(99.9%) 0.001 ms/op
Iteration   2: 3.063 ±(99.9%) 0.003 ms/op
Iteration   3: 3.046 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.068 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (3.046, 3.068, 3.095), stdev = 0.025
  CI (99.9%): [2.609, 3.527] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.206 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.003 ms/op
Iteration   1: 2.898 ±(99.9%) 0.002 ms/op
Iteration   2: 2.905 ±(99.9%) 0.002 ms/op
Iteration   3: 2.849 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.884 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (2.849, 2.884, 2.905), stdev = 0.030
  CI (99.9%): [2.332, 3.435] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.176 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.003 ms/op
Iteration   1: 3.107 ±(99.9%) 0.004 ms/op
Iteration   2: 3.082 ±(99.9%) 0.004 ms/op
Iteration   3: 3.065 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.085 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (3.065, 3.085, 3.107), stdev = 0.022
  CI (99.9%): [2.692, 3.477] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.165 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.016 ms/op
Iteration   1: 3.982 ±(99.9%) 0.006 ms/op
Iteration   2: 3.887 ±(99.9%) 0.010 ms/op
Iteration   3: 3.910 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.926 ±(99.9%) 0.902 ms/op [Average]
  (min, avg, max) = (3.887, 3.926, 3.982), stdev = 0.049
  CI (99.9%): [3.024, 4.829] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.234 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
Iteration   1: 3.110 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  8.685 ms/op
                 createUser·p0.9999: 13.196 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  9.247 ms/op
                 createUser·p0.9999: 15.617 ms/op
                 createUser·p1.00:   16.302 ms/op

Iteration   3: 3.101 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  10.847 ms/op
                 createUser·p0.9999: 17.062 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310499
  mean =      3.090 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 408 
    [ 1.250,  2.500) = 17317 
    [ 2.500,  3.750) = 271280 
    [ 3.750,  5.000) = 19272 
    [ 5.000,  6.250) = 1014 
    [ 6.250,  7.500) = 541 
    [ 7.500,  8.750) = 251 
    [ 8.750, 10.000) = 163 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      9.691 ms/op
     p(99.9900) =     16.399 ms/op
     p(99.9990) =     18.510 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.030 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.005 ms/op
Iteration   1: 2.895 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  8.040 ms/op
                 existUser·p0.9999: 12.206 ms/op
                 existUser·p1.00:   12.419 ms/op

Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  9.178 ms/op
                 existUser·p0.9999: 15.470 ms/op
                 existUser·p1.00:   15.614 ms/op

Iteration   3: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.422 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  7.782 ms/op
                 existUser·p0.9999: 17.726 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328754
  mean =      2.921 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 965 
    [ 1.250,  2.500) = 31734 
    [ 2.500,  3.750) = 286825 
    [ 3.750,  5.000) = 7927 
    [ 5.000,  6.250) = 529 
    [ 6.250,  7.500) = 281 
    [ 7.500,  8.750) = 222 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.159 ms/op
     p(99.9900) =     16.175 ms/op
     p(99.9990) =     18.678 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 4.361 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
Iteration   1: 3.098 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.310 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.981 ms/op
                 getUser·p0.999:  11.389 ms/op
                 getUser·p0.9999: 17.750 ms/op
                 getUser·p1.00:   18.612 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  9.052 ms/op
                 getUser·p0.9999: 32.258 ms/op
                 getUser·p1.00:   32.702 ms/op

Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  8.242 ms/op
                 getUser·p0.9999: 21.575 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311930
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18634 
    [ 2.500,  5.000) = 291100 
    [ 5.000,  7.500) = 1499 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      9.702 ms/op
     p(99.9900) =     31.406 ms/op
     p(99.9990) =     32.629 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


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
# Warmup Iteration   1: 6.022 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.011 ms/op
Iteration   1: 4.049 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 17.348 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   2: 4.032 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  13.670 ms/op
                 listUser·p0.9999: 15.979 ms/op
                 listUser·p1.00:   16.695 ms/op

Iteration   3: 4.009 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  17.042 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238214
  mean =      4.030 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3752 
    [ 2.500,  5.000) = 206542 
    [ 5.000,  7.500) = 25751 
    [ 7.500, 10.000) = 1595 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     14.169 ms/op
     p(99.9900) =     21.010 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.540 ± 3.211  ops/ms
ClientGrpc.existUser                       thrpt       3  10.958 ± 1.339  ops/ms
ClientGrpc.getUser                         thrpt       3  10.422 ± 0.352  ops/ms
ClientGrpc.listUser                        thrpt       3   7.945 ± 1.800  ops/ms
ClientGrpc.createUser                       avgt       3   3.068 ± 0.459   ms/op
ClientGrpc.existUser                        avgt       3   2.884 ± 0.552   ms/op
ClientGrpc.getUser                          avgt       3   3.085 ± 0.393   ms/op
ClientGrpc.listUser                         avgt       3   3.926 ± 0.902   ms/op
ClientGrpc.createUser                     sample  310499   3.090 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.708           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.691           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.399           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.645           ms/op
ClientGrpc.existUser                      sample  328754   2.921 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.422           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.159           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.175           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.743           ms/op
ClientGrpc.getUser                        sample  311930   3.077 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.310           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.702           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.406           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.702           ms/op
ClientGrpc.listUser                       sample  238214   4.030 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.133           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.029           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.397           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.169           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.010           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.052           ms/op
