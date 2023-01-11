# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.389 ops/ms
# Warmup Iteration   2: 7.610 ops/ms
# Warmup Iteration   3: 9.239 ops/ms
Iteration   1: 9.432 ops/ms
Iteration   2: 9.238 ops/ms
Iteration   3: 9.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.336 ±(99.9%) 1.775 ops/ms [Average]
  (min, avg, max) = (9.238, 9.336, 9.432), stdev = 0.097
  CI (99.9%): [7.561, 11.110] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.370 ops/ms
# Warmup Iteration   2: 8.544 ops/ms
# Warmup Iteration   3: 8.985 ops/ms
Iteration   1: 8.780 ops/ms
Iteration   2: 8.765 ops/ms
Iteration   3: 9.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.898 ±(99.9%) 3.950 ops/ms [Average]
  (min, avg, max) = (8.765, 8.898, 9.147), stdev = 0.217
  CI (99.9%): [4.947, 12.848] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.899 ops/ms
# Warmup Iteration   2: 8.055 ops/ms
# Warmup Iteration   3: 8.649 ops/ms
Iteration   1: 8.554 ops/ms
Iteration   2: 8.668 ops/ms
Iteration   3: 8.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.649 ±(99.9%) 1.594 ops/ms [Average]
  (min, avg, max) = (8.554, 8.649, 8.725), stdev = 0.087
  CI (99.9%): [7.055, 10.243] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.717 ops/ms
# Warmup Iteration   2: 6.791 ops/ms
# Warmup Iteration   3: 7.197 ops/ms
Iteration   1: 7.526 ops/ms
Iteration   2: 7.509 ops/ms
Iteration   3: 7.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.473 ±(99.9%) 1.425 ops/ms [Average]
  (min, avg, max) = (7.383, 7.473, 7.526), stdev = 0.078
  CI (99.9%): [6.047, 8.898] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.007 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.414 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.011 ms/op
Iteration   1: 3.239 ±(99.9%) 0.003 ms/op
Iteration   2: 3.244 ±(99.9%) 0.002 ms/op
Iteration   3: 3.070 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.184 ±(99.9%) 1.799 ms/op [Average]
  (min, avg, max) = (3.070, 3.184, 3.244), stdev = 0.099
  CI (99.9%): [1.385, 4.983] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.006 ms/op
Iteration   1: 3.244 ±(99.9%) 0.003 ms/op
Iteration   2: 3.229 ±(99.9%) 0.003 ms/op
Iteration   3: 3.284 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.253 ±(99.9%) 0.517 ms/op [Average]
  (min, avg, max) = (3.229, 3.253, 3.284), stdev = 0.028
  CI (99.9%): [2.736, 3.769] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.831 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.473 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.002 ms/op
Iteration   1: 3.504 ±(99.9%) 0.001 ms/op
Iteration   2: 3.472 ±(99.9%) 0.003 ms/op
Iteration   3: 3.453 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.476 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (3.453, 3.476, 3.504), stdev = 0.026
  CI (99.9%): [3.008, 3.944] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.436 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.406 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.013 ms/op
Iteration   1: 3.925 ±(99.9%) 0.031 ms/op
Iteration   2: 3.947 ±(99.9%) 0.049 ms/op
Iteration   3: 3.953 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.942 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (3.925, 3.942, 3.953), stdev = 0.015
  CI (99.9%): [3.666, 4.217] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.135 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.007 ms/op
Iteration   1: 3.163 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.317 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.516 ms/op
                 createUser·p0.9999: 16.417 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   2: 3.391 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  10.666 ms/op
                 createUser·p0.9999: 19.792 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   3: 3.469 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.097 ms/op
                 createUser·p0.999:  14.774 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 287944
  mean =      3.336 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12407 
    [ 2.500,  5.000) = 273261 
    [ 5.000,  7.500) = 1857 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.317 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =      9.487 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     20.975 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.007 ms/op
Iteration   1: 3.238 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   4.624 ms/op
                 existUser·p0.999:  6.252 ms/op
                 existUser·p0.9999: 12.461 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.168 ms/op
                 existUser·p0.9999: 17.983 ms/op
                 existUser·p1.00:   18.481 ms/op

Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  10.879 ms/op
                 existUser·p0.9999: 16.496 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 306572
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1531 
    [ 1.250,  2.500) = 25035 
    [ 2.500,  3.750) = 243444 
    [ 3.750,  5.000) = 35136 
    [ 5.000,  6.250) = 955 
    [ 6.250,  7.500) = 177 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     17.411 ms/op
     p(99.9990) =     18.381 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.599 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.011 ms/op
Iteration   1: 3.527 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.257 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  11.078 ms/op
                 getUser·p0.9999: 15.563 ms/op
                 getUser·p1.00:   16.712 ms/op

Iteration   2: 3.453 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  10.986 ms/op
                 getUser·p0.9999: 17.850 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   3: 3.253 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.826 ms/op
                 getUser·p0.999:  7.950 ms/op
                 getUser·p0.9999: 18.618 ms/op
                 getUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 281510
  mean =      3.407 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1072 
    [ 1.250,  2.500) = 10783 
    [ 2.500,  3.750) = 209003 
    [ 3.750,  5.000) = 54276 
    [ 5.000,  6.250) = 4614 
    [ 6.250,  7.500) = 1006 
    [ 7.500,  8.750) = 398 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.257 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.740 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     19.018 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.642 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.704 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.649 ±(99.9%) 0.016 ms/op
Iteration   1: 4.500 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.406 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  16.235 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 4.466 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   4.268 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 23.719 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   3: 4.300 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.701 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   5.710 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 217016
  mean =      4.420 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1166 
    [ 2.500,  5.000) = 173840 
    [ 5.000,  7.500) = 38882 
    [ 7.500, 10.000) = 2391 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      4.186 ms/op
     p(90.0000) =      5.702 ms/op
     p(95.0000) =      6.341 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     23.981 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.336 ± 1.775  ops/ms
ClientGrpc.existUser                       thrpt       3   8.898 ± 3.950  ops/ms
ClientGrpc.getUser                         thrpt       3   8.649 ± 1.594  ops/ms
ClientGrpc.listUser                        thrpt       3   7.473 ± 1.425  ops/ms
ClientGrpc.createUser                       avgt       3   3.184 ± 1.799   ms/op
ClientGrpc.existUser                        avgt       3   3.253 ± 0.517   ms/op
ClientGrpc.getUser                          avgt       3   3.476 ± 0.468   ms/op
ClientGrpc.listUser                         avgt       3   3.942 ± 0.276   ms/op
ClientGrpc.createUser                     sample  287944   3.336 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.317           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.281           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.907           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.487           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.792           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.103           ms/op
ClientGrpc.existUser                      sample  306572   3.132 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.665           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.101           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.055           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.604           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.406           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.411           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.481           ms/op
ClientGrpc.getUser                        sample  281510   3.407 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.257           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.338           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.149           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.740           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.924           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.169           ms/op
ClientGrpc.listUser                       sample  217016   4.420 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.701           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.186           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.341           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.848           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.579           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.626           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.756           ms/op
