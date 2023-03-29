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
# Warmup Iteration   1: 3.379 ops/ms
# Warmup Iteration   2: 7.281 ops/ms
# Warmup Iteration   3: 8.585 ops/ms
Iteration   1: 9.083 ops/ms
Iteration   2: 9.147 ops/ms
Iteration   3: 9.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.150 ±(99.9%) 1.242 ops/ms [Average]
  (min, avg, max) = (9.083, 9.150, 9.219), stdev = 0.068
  CI (99.9%): [7.908, 10.391] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.227 ops/ms
# Warmup Iteration   2: 9.038 ops/ms
# Warmup Iteration   3: 9.592 ops/ms
Iteration   1: 9.784 ops/ms
Iteration   2: 9.887 ops/ms
Iteration   3: 9.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.841 ±(99.9%) 0.953 ops/ms [Average]
  (min, avg, max) = (9.784, 9.841, 9.887), stdev = 0.052
  CI (99.9%): [8.888, 10.794] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.073 ops/ms
# Warmup Iteration   2: 8.806 ops/ms
# Warmup Iteration   3: 9.307 ops/ms
Iteration   1: 9.304 ops/ms
Iteration   2: 8.980 ops/ms
Iteration   3: 9.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.226 ±(99.9%) 3.971 ops/ms [Average]
  (min, avg, max) = (8.980, 9.226, 9.394), stdev = 0.218
  CI (99.9%): [5.256, 13.197] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.943 ops/ms
# Warmup Iteration   2: 6.692 ops/ms
# Warmup Iteration   3: 7.143 ops/ms
Iteration   1: 7.032 ops/ms
Iteration   2: 7.094 ops/ms
Iteration   3: 7.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.096 ±(99.9%) 1.173 ops/ms [Average]
  (min, avg, max) = (7.032, 7.096, 7.161), stdev = 0.064
  CI (99.9%): [5.923, 8.269] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.944 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.012 ms/op
Iteration   1: 3.484 ±(99.9%) 0.003 ms/op
Iteration   2: 3.442 ±(99.9%) 0.003 ms/op
Iteration   3: 3.405 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.444 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.405, 3.444, 3.484), stdev = 0.040
  CI (99.9%): [2.721, 4.167] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.418 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.002 ms/op
Iteration   1: 3.233 ±(99.9%) 0.003 ms/op
Iteration   2: 3.259 ±(99.9%) 0.002 ms/op
Iteration   3: 3.187 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.226 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (3.187, 3.226, 3.259), stdev = 0.037
  CI (99.9%): [2.559, 3.894] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.961 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.003 ms/op
Iteration   1: 3.457 ±(99.9%) 0.005 ms/op
Iteration   2: 3.462 ±(99.9%) 0.004 ms/op
Iteration   3: 3.460 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.459 ±(99.9%) 0.051 ms/op [Average]
  (min, avg, max) = (3.457, 3.459, 3.462), stdev = 0.003
  CI (99.9%): [3.408, 3.511] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.401 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.010 ms/op
Iteration   1: 4.462 ±(99.9%) 0.010 ms/op
Iteration   2: 4.374 ±(99.9%) 0.011 ms/op
Iteration   3: 4.418 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.418 ±(99.9%) 0.803 ms/op [Average]
  (min, avg, max) = (4.374, 4.418, 4.462), stdev = 0.044
  CI (99.9%): [3.616, 5.221] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.667 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.008 ms/op
Iteration   1: 3.444 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  12.681 ms/op
                 createUser·p0.9999: 16.386 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   2: 3.464 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  13.364 ms/op
                 createUser·p0.9999: 17.891 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   3: 3.459 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  16.581 ms/op
                 createUser·p0.9999: 19.980 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 277627
  mean =      3.456 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9458 
    [ 2.500,  5.000) = 263616 
    [ 5.000,  7.500) = 3828 
    [ 7.500, 10.000) = 274 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     13.087 ms/op
     p(99.9900) =     19.595 ms/op
     p(99.9990) =     20.094 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.128 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.008 ms/op
Iteration   1: 3.245 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  9.002 ms/op
                 existUser·p0.9999: 16.204 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  11.457 ms/op
                 existUser·p0.9999: 13.775 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  11.728 ms/op
                 existUser·p0.9999: 27.460 ms/op
                 existUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 300505
  mean =      3.196 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14750 
    [ 2.500,  5.000) = 282777 
    [ 5.000,  7.500) = 2330 
    [ 7.500, 10.000) = 288 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.989 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     25.444 ms/op
     p(99.9990) =     29.294 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.190 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.007 ms/op
Iteration   1: 3.643 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  10.633 ms/op
                 getUser·p0.9999: 14.638 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   2: 3.433 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  11.900 ms/op
                 getUser·p0.9999: 14.571 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   3: 3.453 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   5.414 ms/op
                 getUser·p0.999:  9.882 ms/op
                 getUser·p0.9999: 17.653 ms/op
                 getUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 273612
  mean =      3.507 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 7883 
    [ 2.500,  3.750) = 190357 
    [ 3.750,  5.000) = 69520 
    [ 5.000,  6.250) = 4291 
    [ 6.250,  7.500) = 738 
    [ 7.500,  8.750) = 293 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     10.148 ms/op
     p(99.9900) =     16.717 ms/op
     p(99.9990) =     17.998 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 6.159 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.767 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.476 ±(99.9%) 0.014 ms/op
Iteration   1: 4.513 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  14.764 ms/op
                 listUser·p0.9999: 19.000 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   2: 4.433 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   4.211 ms/op
                 listUser·p0.90:   5.702 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   7.913 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   3: 4.526 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.772 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   5.652 ms/op
                 listUser·p0.95:   6.365 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 32.587 ms/op
                 listUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 213749
  mean =      4.490 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 909 
    [ 2.500,  5.000) = 172621 
    [ 5.000,  7.500) = 36577 
    [ 7.500, 10.000) = 2954 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.012 ms/op
     p(99.9000) =     16.466 ms/op
     p(99.9900) =     31.687 ms/op
     p(99.9990) =     33.930 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.150 ± 1.242  ops/ms
ClientGrpc.existUser                       thrpt       3   9.841 ± 0.953  ops/ms
ClientGrpc.getUser                         thrpt       3   9.226 ± 3.971  ops/ms
ClientGrpc.listUser                        thrpt       3   7.096 ± 1.173  ops/ms
ClientGrpc.createUser                       avgt       3   3.444 ± 0.723   ms/op
ClientGrpc.existUser                        avgt       3   3.226 ± 0.668   ms/op
ClientGrpc.getUser                          avgt       3   3.459 ± 0.051   ms/op
ClientGrpc.listUser                         avgt       3   4.418 ± 0.803   ms/op
ClientGrpc.createUser                     sample  277627   3.456 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.672           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.396           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.133           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.382           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.087           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.595           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.185           ms/op
ClientGrpc.existUser                      sample  300505   3.196 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.599           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.154           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.989           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.354           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.444           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.426           ms/op
ClientGrpc.getUser                        sample  273612   3.507 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.848           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.190           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.148           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.717           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.055           ms/op
ClientGrpc.listUser                       sample  213749   4.490 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.772           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.276           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.466           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.687           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.013           ms/op
