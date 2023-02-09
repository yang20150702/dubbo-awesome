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
# Warmup Iteration   1: 4.313 ops/ms
# Warmup Iteration   2: 8.805 ops/ms
# Warmup Iteration   3: 9.913 ops/ms
Iteration   1: 10.056 ops/ms
Iteration   2: 9.846 ops/ms
Iteration   3: 9.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.924 ±(99.9%) 2.094 ops/ms [Average]
  (min, avg, max) = (9.846, 9.924, 10.056), stdev = 0.115
  CI (99.9%): [7.830, 12.018] (assumes normal distribution)


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
# Warmup Iteration   1: 7.929 ops/ms
# Warmup Iteration   2: 10.472 ops/ms
# Warmup Iteration   3: 10.322 ops/ms
Iteration   1: 10.557 ops/ms
Iteration   2: 10.614 ops/ms
Iteration   3: 10.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.511 ±(99.9%) 2.424 ops/ms [Average]
  (min, avg, max) = (10.361, 10.511, 10.614), stdev = 0.133
  CI (99.9%): [8.087, 12.935] (assumes normal distribution)


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
# Warmup Iteration   1: 6.649 ops/ms
# Warmup Iteration   2: 9.889 ops/ms
# Warmup Iteration   3: 10.015 ops/ms
Iteration   1: 9.968 ops/ms
Iteration   2: 9.883 ops/ms
Iteration   3: 10.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.015 ±(99.9%) 2.923 ops/ms [Average]
  (min, avg, max) = (9.883, 10.015, 10.193), stdev = 0.160
  CI (99.9%): [7.092, 12.937] (assumes normal distribution)


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
# Warmup Iteration   1: 6.187 ops/ms
# Warmup Iteration   2: 7.314 ops/ms
# Warmup Iteration   3: 7.760 ops/ms
Iteration   1: 7.868 ops/ms
Iteration   2: 7.866 ops/ms
Iteration   3: 7.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.862 ±(99.9%) 0.153 ops/ms [Average]
  (min, avg, max) = (7.852, 7.862, 7.868), stdev = 0.008
  CI (99.9%): [7.709, 8.016] (assumes normal distribution)


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.003 ms/op
Iteration   1: 3.165 ±(99.9%) 0.005 ms/op
Iteration   2: 3.214 ±(99.9%) 0.002 ms/op
Iteration   3: 3.177 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.185 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.165, 3.185, 3.214), stdev = 0.026
  CI (99.9%): [2.713, 3.657] (assumes normal distribution)


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.003 ms/op
Iteration   1: 3.008 ±(99.9%) 0.003 ms/op
Iteration   2: 3.141 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.048 ±(99.9%) 1.467 ms/op [Average]
  (min, avg, max) = (2.996, 3.048, 3.141), stdev = 0.080
  CI (99.9%): [1.581, 4.515] (assumes normal distribution)


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
# Warmup Iteration   1: 4.259 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.002 ms/op
Iteration   1: 3.202 ±(99.9%) 0.002 ms/op
Iteration   2: 3.143 ±(99.9%) 0.003 ms/op
Iteration   3: 3.198 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.181 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (3.143, 3.181, 3.202), stdev = 0.033
  CI (99.9%): [2.583, 3.779] (assumes normal distribution)


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
# Warmup Iteration   1: 5.288 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.008 ms/op
Iteration   1: 4.159 ±(99.9%) 0.019 ms/op
Iteration   2: 4.143 ±(99.9%) 0.030 ms/op
Iteration   3: 4.054 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.119 ±(99.9%) 1.037 ms/op [Average]
  (min, avg, max) = (4.054, 4.119, 4.159), stdev = 0.057
  CI (99.9%): [3.082, 5.155] (assumes normal distribution)


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.008 ms/op
Iteration   1: 3.208 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.840 ms/op
                 createUser·p0.9999: 19.694 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  6.837 ms/op
                 createUser·p0.9999: 19.038 ms/op
                 createUser·p1.00:   19.530 ms/op

Iteration   3: 3.221 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.290 ms/op
                 createUser·p0.9999: 22.907 ms/op
                 createUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300934
  mean =      3.191 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18239 
    [ 2.500,  5.000) = 281691 
    [ 5.000,  7.500) = 625 
    [ 7.500, 10.000) = 219 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.037 ms/op
     p(99.9900) =     20.471 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 4.119 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  6.328 ms/op
                 existUser·p0.9999: 16.279 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.071 ms/op
                 existUser·p0.9999: 18.383 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.032 ms/op
                 existUser·p0.9999: 20.600 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314970
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36148 
    [ 2.500,  5.000) = 278094 
    [ 5.000,  7.500) = 498 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      6.595 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     21.152 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
Iteration   1: 3.162 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.003 ms/op
                 getUser·p0.9999: 12.567 ms/op
                 getUser·p1.00:   12.796 ms/op

Iteration   2: 3.168 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.504 ms/op
                 getUser·p0.9999: 14.513 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   3: 3.162 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.346 ms/op
                 getUser·p0.9999: 16.460 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303350
  mean =      3.164 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 393 
    [ 1.250,  2.500) = 18969 
    [ 2.500,  3.750) = 247458 
    [ 3.750,  5.000) = 35641 
    [ 5.000,  6.250) = 491 
    [ 6.250,  7.500) = 194 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      6.715 ms/op
     p(99.9900) =     15.275 ms/op
     p(99.9990) =     17.560 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 5.638 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.011 ms/op
Iteration   1: 4.052 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.107 ms/op
                 listUser·p0.9999: 15.237 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   2: 4.052 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.571 ms/op
                 listUser·p0.9999: 15.310 ms/op
                 listUser·p1.00:   16.466 ms/op

Iteration   3: 3.985 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.486 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 25.001 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238223
  mean =      4.029 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2727 
    [ 2.500,  5.000) = 210135 
    [ 5.000,  7.500) = 23977 
    [ 7.500, 10.000) = 1020 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     25.239 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.924 ± 2.094  ops/ms
ClientGrpc.existUser                       thrpt       3  10.511 ± 2.424  ops/ms
ClientGrpc.getUser                         thrpt       3  10.015 ± 2.923  ops/ms
ClientGrpc.listUser                        thrpt       3   7.862 ± 0.153  ops/ms
ClientGrpc.createUser                       avgt       3   3.185 ± 0.472   ms/op
ClientGrpc.existUser                        avgt       3   3.048 ± 1.467   ms/op
ClientGrpc.getUser                          avgt       3   3.181 ± 0.598   ms/op
ClientGrpc.listUser                         avgt       3   4.119 ± 1.037   ms/op
ClientGrpc.createUser                     sample  300934   3.191 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.616           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.158           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.037           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.471           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.970           ms/op
ClientGrpc.existUser                      sample  314970   3.050 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.550           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.019           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.875           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.595           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.792           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.234           ms/op
ClientGrpc.getUser                        sample  303350   3.164 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.510           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.146           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.994           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.715           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.275           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.695           ms/op
ClientGrpc.listUser                       sample  238223   4.029 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.486           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.713           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.921           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.247           ms/op
