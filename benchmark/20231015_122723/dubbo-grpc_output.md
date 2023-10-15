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
# Warmup Iteration   1: 4.480 ops/ms
# Warmup Iteration   2: 8.547 ops/ms
# Warmup Iteration   3: 9.936 ops/ms
Iteration   1: 10.073 ops/ms
Iteration   2: 10.130 ops/ms
Iteration   3: 10.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.200 ±(99.9%) 3.145 ops/ms [Average]
  (min, avg, max) = (10.073, 10.200, 10.396), stdev = 0.172
  CI (99.9%): [7.055, 13.345] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.500 ops/ms
# Warmup Iteration   2: 10.521 ops/ms
# Warmup Iteration   3: 10.591 ops/ms
Iteration   1: 11.024 ops/ms
Iteration   2: 10.816 ops/ms
Iteration   3: 10.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.888 ±(99.9%) 2.146 ops/ms [Average]
  (min, avg, max) = (10.816, 10.888, 11.024), stdev = 0.118
  CI (99.9%): [8.743, 13.034] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.947 ops/ms
# Warmup Iteration   2: 9.805 ops/ms
# Warmup Iteration   3: 10.378 ops/ms
Iteration   1: 10.348 ops/ms
Iteration   2: 10.387 ops/ms
Iteration   3: 10.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.410 ±(99.9%) 1.398 ops/ms [Average]
  (min, avg, max) = (10.348, 10.410, 10.496), stdev = 0.077
  CI (99.9%): [9.012, 11.808] (assumes normal distribution)


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
# Warmup Iteration   1: 5.478 ops/ms
# Warmup Iteration   2: 8.171 ops/ms
# Warmup Iteration   3: 8.138 ops/ms
Iteration   1: 8.243 ops/ms
Iteration   2: 8.289 ops/ms
Iteration   3: 8.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.224 ±(99.9%) 1.393 ops/ms [Average]
  (min, avg, max) = (8.140, 8.224, 8.289), stdev = 0.076
  CI (99.9%): [6.831, 9.617] (assumes normal distribution)


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.003 ms/op
Iteration   1: 3.078 ±(99.9%) 0.007 ms/op
Iteration   2: 3.110 ±(99.9%) 0.005 ms/op
Iteration   3: 3.093 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.094 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (3.078, 3.094, 3.110), stdev = 0.016
  CI (99.9%): [2.804, 3.384] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.199 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.003 ms/op
Iteration   1: 2.921 ±(99.9%) 0.003 ms/op
Iteration   2: 2.952 ±(99.9%) 0.002 ms/op
Iteration   3: 2.941 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.938 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.921, 2.938, 2.952), stdev = 0.016
  CI (99.9%): [2.646, 3.230] (assumes normal distribution)


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
# Warmup Iteration   1: 4.169 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.003 ms/op
Iteration   1: 3.081 ±(99.9%) 0.002 ms/op
Iteration   2: 3.090 ±(99.9%) 0.004 ms/op
Iteration   3: 3.087 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.086 ±(99.9%) 0.082 ms/op [Average]
  (min, avg, max) = (3.081, 3.086, 3.090), stdev = 0.004
  CI (99.9%): [3.004, 3.168] (assumes normal distribution)


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
# Warmup Iteration   1: 5.238 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.009 ms/op
Iteration   1: 3.944 ±(99.9%) 0.029 ms/op
Iteration   2: 3.912 ±(99.9%) 0.047 ms/op
Iteration   3: 3.917 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.924 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (3.912, 3.924, 3.944), stdev = 0.017
  CI (99.9%): [3.612, 4.237] (assumes normal distribution)


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
Iteration   1: 3.131 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  12.403 ms/op
                 createUser·p0.9999: 16.520 ms/op
                 createUser·p1.00:   16.744 ms/op

Iteration   2: 3.092 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  9.089 ms/op
                 createUser·p0.9999: 16.690 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 3.139 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  14.713 ms/op
                 createUser·p0.9999: 26.313 ms/op
                 createUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307650
  mean =      3.120 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19252 
    [ 2.500,  5.000) = 286504 
    [ 5.000,  7.500) = 1379 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =     12.507 ms/op
     p(99.9900) =     17.506 ms/op
     p(99.9990) =     26.474 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.179 ms/op
                 existUser·p0.9999: 13.555 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  8.128 ms/op
                 existUser·p0.9999: 18.185 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.825 ms/op
                 existUser·p0.9999: 22.408 ms/op
                 existUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319351
  mean =      3.004 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31776 
    [ 2.500,  5.000) = 286049 
    [ 5.000,  7.500) = 1214 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.460 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     22.925 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 4.198 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
Iteration   1: 3.089 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.776 ms/op
                 getUser·p0.999:  8.195 ms/op
                 getUser·p0.9999: 13.450 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.618 ms/op
                 getUser·p0.9999: 14.657 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  10.923 ms/op
                 getUser·p0.9999: 16.457 ms/op
                 getUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309720
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 571 
    [ 1.250,  2.500) = 16527 
    [ 2.500,  3.750) = 267904 
    [ 3.750,  5.000) = 22973 
    [ 5.000,  6.250) = 860 
    [ 6.250,  7.500) = 369 
    [ 7.500,  8.750) = 163 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 90 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     15.254 ms/op
     p(99.9990) =     19.363 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 4.778 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.009 ms/op
Iteration   1: 3.950 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  13.156 ms/op
                 listUser·p0.9999: 15.263 ms/op
                 listUser·p1.00:   15.761 ms/op

Iteration   2: 3.936 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.313 ms/op
                 listUser·p0.9999: 17.264 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   3: 3.831 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  16.505 ms/op
                 listUser·p0.9999: 18.130 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246136
  mean =      3.905 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 3397 
    [ 2.500,  3.750) = 108183 
    [ 3.750,  5.000) = 118032 
    [ 5.000,  6.250) = 10967 
    [ 6.250,  7.500) = 4422 
    [ 7.500,  8.750) = 445 
    [ 8.750, 10.000) = 151 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 129 
    [13.750, 15.000) = 100 
    [15.000, 16.250) = 81 
    [16.250, 17.500) = 84 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     14.301 ms/op
     p(99.9900) =     17.720 ms/op
     p(99.9990) =     18.829 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.200 ± 3.145  ops/ms
ClientGrpc.existUser                       thrpt       3  10.888 ± 2.146  ops/ms
ClientGrpc.getUser                         thrpt       3  10.410 ± 1.398  ops/ms
ClientGrpc.listUser                        thrpt       3   8.224 ± 1.393  ops/ms
ClientGrpc.createUser                       avgt       3   3.094 ± 0.290   ms/op
ClientGrpc.existUser                        avgt       3   2.938 ± 0.292   ms/op
ClientGrpc.getUser                          avgt       3   3.086 ± 0.082   ms/op
ClientGrpc.listUser                         avgt       3   3.924 ± 0.313   ms/op
ClientGrpc.createUser                     sample  307650   3.120 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.828           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.507           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.506           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.477           ms/op
ClientGrpc.existUser                      sample  319351   3.004 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.672           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.460           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.400           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.167           ms/op
ClientGrpc.getUser                        sample  309720   3.099 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.648           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.470           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.254           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.464           ms/op
ClientGrpc.listUser                       sample  246136   3.905 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.126           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.473           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.301           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.720           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.137           ms/op
