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
# Warmup Iteration   1: 4.249 ops/ms
# Warmup Iteration   2: 8.961 ops/ms
# Warmup Iteration   3: 10.398 ops/ms
Iteration   1: 10.953 ops/ms
Iteration   2: 10.516 ops/ms
Iteration   3: 10.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.688 ±(99.9%) 4.255 ops/ms [Average]
  (min, avg, max) = (10.516, 10.688, 10.953), stdev = 0.233
  CI (99.9%): [6.433, 14.943] (assumes normal distribution)


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
# Warmup Iteration   1: 7.909 ops/ms
# Warmup Iteration   2: 10.589 ops/ms
# Warmup Iteration   3: 11.084 ops/ms
Iteration   1: 11.006 ops/ms
Iteration   2: 11.147 ops/ms
Iteration   3: 11.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.166 ±(99.9%) 3.107 ops/ms [Average]
  (min, avg, max) = (11.006, 11.166, 11.345), stdev = 0.170
  CI (99.9%): [8.059, 14.273] (assumes normal distribution)


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
# Warmup Iteration   1: 6.958 ops/ms
# Warmup Iteration   2: 10.104 ops/ms
# Warmup Iteration   3: 10.478 ops/ms
Iteration   1: 10.641 ops/ms
Iteration   2: 10.677 ops/ms
Iteration   3: 10.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.606 ±(99.9%) 1.716 ops/ms [Average]
  (min, avg, max) = (10.499, 10.606, 10.677), stdev = 0.094
  CI (99.9%): [8.890, 12.321] (assumes normal distribution)


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
# Warmup Iteration   1: 5.534 ops/ms
# Warmup Iteration   2: 7.676 ops/ms
# Warmup Iteration   3: 7.857 ops/ms
Iteration   1: 8.035 ops/ms
Iteration   2: 7.878 ops/ms
Iteration   3: 7.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.943 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (7.878, 7.943, 8.035), stdev = 0.082
  CI (99.9%): [6.448, 9.437] (assumes normal distribution)


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.002 ms/op
Iteration   1: 2.967 ±(99.9%) 0.002 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.986 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (2.967, 2.986, 3.006), stdev = 0.019
  CI (99.9%): [2.634, 3.338] (assumes normal distribution)


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.002 ms/op
Iteration   1: 2.891 ±(99.9%) 0.002 ms/op
Iteration   2: 2.932 ±(99.9%) 0.001 ms/op
Iteration   3: 2.911 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.911 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (2.891, 2.911, 2.932), stdev = 0.021
  CI (99.9%): [2.537, 3.286] (assumes normal distribution)


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
# Warmup Iteration   1: 4.336 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.002 ms/op
Iteration   1: 3.026 ±(99.9%) 0.002 ms/op
Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
Iteration   3: 3.020 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.028 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (3.020, 3.028, 3.036), stdev = 0.008
  CI (99.9%): [2.879, 3.176] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.926 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.015 ms/op
Iteration   1: 3.958 ±(99.9%) 0.013 ms/op
Iteration   2: 3.952 ±(99.9%) 0.026 ms/op
Iteration   3: 3.995 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.969 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.952, 3.969, 3.995), stdev = 0.023
  CI (99.9%): [3.546, 4.391] (assumes normal distribution)


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.009 ms/op
Iteration   1: 2.974 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.137 ms/op
                 createUser·p0.999:  6.881 ms/op
                 createUser·p0.9999: 22.217 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   2: 2.970 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.367 ms/op
                 createUser·p0.9999: 23.346 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  9.785 ms/op
                 createUser·p0.9999: 26.061 ms/op
                 createUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321997
  mean =      2.980 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25877 
    [ 2.500,  5.000) = 294609 
    [ 5.000,  7.500) = 1166 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.676 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.005 ms/op
Iteration   1: 2.873 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   3.999 ms/op
                 existUser·p0.999:  5.288 ms/op
                 existUser·p0.9999: 18.378 ms/op
                 existUser·p1.00:   18.547 ms/op

Iteration   2: 2.949 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.221 ms/op
                 existUser·p0.999:  6.647 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   3: 2.924 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.139 ms/op
                 existUser·p0.9999: 24.479 ms/op
                 existUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329562
  mean =      2.915 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38958 
    [ 2.500,  5.000) = 289490 
    [ 5.000,  7.500) = 858 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      6.737 ms/op
     p(99.9900) =     18.764 ms/op
     p(99.9990) =     25.563 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.612 ms/op
                 getUser·p0.9999: 21.036 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   2: 3.031 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.732 ms/op
                 getUser·p0.9999: 16.317 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.995 ms/op
                 getUser·p0.9999: 19.073 ms/op
                 getUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315315
  mean =      3.043 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18961 
    [ 2.500,  5.000) = 294806 
    [ 5.000,  7.500) = 1205 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.755 ms/op
     p(99.9900) =     19.480 ms/op
     p(99.9990) =     21.425 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 4.888 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.011 ms/op
Iteration   1: 3.677 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  13.894 ms/op
                 listUser·p0.9999: 16.665 ms/op
                 listUser·p1.00:   17.891 ms/op

Iteration   2: 4.006 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.420 ms/op
                 listUser·p0.9999: 25.428 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   3: 3.932 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.969 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.018 ms/op
                 listUser·p0.999:  16.253 ms/op
                 listUser·p0.9999: 22.044 ms/op
                 listUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248302
  mean =      3.866 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5528 
    [ 2.500,  5.000) = 220569 
    [ 5.000,  7.500) = 20680 
    [ 7.500, 10.000) = 974 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     15.150 ms/op
     p(99.9900) =     24.745 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.688 ± 4.255  ops/ms
ClientGrpc.existUser                       thrpt       3  11.166 ± 3.107  ops/ms
ClientGrpc.getUser                         thrpt       3  10.606 ± 1.716  ops/ms
ClientGrpc.listUser                        thrpt       3   7.943 ± 1.495  ops/ms
ClientGrpc.createUser                       avgt       3   2.986 ± 0.352   ms/op
ClientGrpc.existUser                        avgt       3   2.911 ± 0.374   ms/op
ClientGrpc.getUser                          avgt       3   3.028 ± 0.149   ms/op
ClientGrpc.listUser                         avgt       3   3.969 ± 0.423   ms/op
ClientGrpc.createUser                     sample  321997   2.980 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.741           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.404           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.676           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.133           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.197           ms/op
ClientGrpc.existUser                      sample  329562   2.915 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.573           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.737           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.764           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.723           ms/op
ClientGrpc.getUser                        sample  315315   3.043 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.795           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.755           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.480           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.496           ms/op
ClientGrpc.listUser                       sample  248302   3.866 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.761           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.150           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.745           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.723           ms/op
