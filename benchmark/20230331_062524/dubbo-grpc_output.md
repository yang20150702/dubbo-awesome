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
# Warmup Iteration   1: 2.740 ops/ms
# Warmup Iteration   2: 6.524 ops/ms
# Warmup Iteration   3: 8.058 ops/ms
Iteration   1: 8.312 ops/ms
Iteration   2: 8.348 ops/ms
Iteration   3: 8.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.363 ±(99.9%) 1.084 ops/ms [Average]
  (min, avg, max) = (8.312, 8.363, 8.428), stdev = 0.059
  CI (99.9%): [7.279, 9.447] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.754 ops/ms
# Warmup Iteration   2: 8.654 ops/ms
# Warmup Iteration   3: 9.318 ops/ms
Iteration   1: 8.851 ops/ms
Iteration   2: 9.220 ops/ms
Iteration   3: 9.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.134 ±(99.9%) 4.569 ops/ms [Average]
  (min, avg, max) = (8.851, 9.134, 9.330), stdev = 0.250
  CI (99.9%): [4.565, 13.702] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.575 ops/ms
# Warmup Iteration   2: 7.701 ops/ms
# Warmup Iteration   3: 8.205 ops/ms
Iteration   1: 8.305 ops/ms
Iteration   2: 8.647 ops/ms
Iteration   3: 8.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.547 ±(99.9%) 3.847 ops/ms [Average]
  (min, avg, max) = (8.305, 8.547, 8.689), stdev = 0.211
  CI (99.9%): [4.700, 12.394] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.271 ops/ms
# Warmup Iteration   2: 6.150 ops/ms
# Warmup Iteration   3: 6.555 ops/ms
Iteration   1: 6.566 ops/ms
Iteration   2: 6.452 ops/ms
Iteration   3: 6.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.518 ±(99.9%) 1.080 ops/ms [Average]
  (min, avg, max) = (6.452, 6.518, 6.566), stdev = 0.059
  CI (99.9%): [5.439, 7.598] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.468 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.013 ms/op
Iteration   1: 3.689 ±(99.9%) 0.003 ms/op
Iteration   2: 3.559 ±(99.9%) 0.003 ms/op
Iteration   3: 3.623 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.623 ±(99.9%) 1.186 ms/op [Average]
  (min, avg, max) = (3.559, 3.623, 3.689), stdev = 0.065
  CI (99.9%): [2.437, 4.810] (assumes normal distribution)


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
# Warmup Iteration   1: 4.806 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.003 ms/op
Iteration   1: 3.463 ±(99.9%) 0.002 ms/op
Iteration   2: 3.500 ±(99.9%) 0.003 ms/op
Iteration   3: 3.454 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.472 ±(99.9%) 0.441 ms/op [Average]
  (min, avg, max) = (3.454, 3.472, 3.500), stdev = 0.024
  CI (99.9%): [3.031, 3.913] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.754 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.003 ms/op
Iteration   1: 3.717 ±(99.9%) 0.003 ms/op
Iteration   2: 3.623 ±(99.9%) 0.004 ms/op
Iteration   3: 3.607 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.649 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (3.607, 3.649, 3.717), stdev = 0.059
  CI (99.9%): [2.568, 4.730] (assumes normal distribution)


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
# Warmup Iteration   1: 7.071 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.199 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.907 ±(99.9%) 0.011 ms/op
Iteration   1: 4.880 ±(99.9%) 0.013 ms/op
Iteration   2: 4.754 ±(99.9%) 0.017 ms/op
Iteration   3: 4.866 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.833 ±(99.9%) 1.263 ms/op [Average]
  (min, avg, max) = (4.754, 4.833, 4.880), stdev = 0.069
  CI (99.9%): [3.570, 6.096] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.299 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.010 ms/op
Iteration   1: 3.781 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  13.468 ms/op
                 createUser·p0.9999: 15.108 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   2: 3.856 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 19.621 ms/op
                 createUser·p1.00:   20.316 ms/op

Iteration   3: 3.889 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  16.526 ms/op
                 createUser·p0.9999: 19.113 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250079
  mean =      3.842 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5187 
    [ 2.500,  5.000) = 229298 
    [ 5.000,  7.500) = 14044 
    [ 7.500, 10.000) = 857 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     20.267 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 5.180 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.008 ms/op
Iteration   1: 3.451 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  12.960 ms/op
                 existUser·p0.9999: 17.859 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   2: 3.481 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.631 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 17.138 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   3: 3.534 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  13.459 ms/op
                 existUser·p0.9999: 19.526 ms/op
                 existUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275034
  mean =      3.488 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11512 
    [ 2.500,  5.000) = 256621 
    [ 5.000,  7.500) = 5719 
    [ 7.500, 10.000) = 531 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     18.858 ms/op
     p(99.9990) =     19.841 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 5.741 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.009 ms/op
Iteration   1: 3.858 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.276 ms/op
                 getUser·p0.99:   7.169 ms/op
                 getUser·p0.999:  14.180 ms/op
                 getUser·p0.9999: 22.319 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   2: 3.715 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  13.155 ms/op
                 getUser·p0.9999: 18.376 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   3: 3.717 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  11.696 ms/op
                 getUser·p0.9999: 20.879 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255076
  mean =      3.762 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6711 
    [ 2.500,  5.000) = 234633 
    [ 5.000,  7.500) = 12144 
    [ 7.500, 10.000) = 780 
    [10.000, 12.500) = 428 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.598 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     13.236 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 6.591 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.315 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.816 ±(99.9%) 0.017 ms/op
Iteration   1: 5.017 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.365 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  17.699 ms/op
                 listUser·p0.9999: 21.713 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   2: 4.963 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.472 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  18.321 ms/op
                 listUser·p0.9999: 23.007 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 5.003 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.849 ms/op
                 listUser·p0.95:   7.617 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  18.089 ms/op
                 listUser·p0.9999: 26.962 ms/op
                 listUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192201
  mean =      4.994 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 423 
    [ 2.500,  5.000) = 120394 
    [ 5.000,  7.500) = 62161 
    [ 7.500, 10.000) = 7720 
    [10.000, 12.500) = 774 
    [12.500, 15.000) = 306 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.455 ms/op
     p(99.0000) =      9.535 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     25.126 ms/op
     p(99.9990) =     27.470 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.363 ± 1.084  ops/ms
ClientGrpc.existUser                       thrpt       3   9.134 ± 4.569  ops/ms
ClientGrpc.getUser                         thrpt       3   8.547 ± 3.847  ops/ms
ClientGrpc.listUser                        thrpt       3   6.518 ± 1.080  ops/ms
ClientGrpc.createUser                       avgt       3   3.623 ± 1.186   ms/op
ClientGrpc.existUser                        avgt       3   3.472 ± 0.441   ms/op
ClientGrpc.getUser                          avgt       3   3.649 ± 1.081   ms/op
ClientGrpc.listUser                         avgt       3   4.833 ± 1.263   ms/op
ClientGrpc.createUser                     sample  250079   3.842 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.787           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.120           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.431           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.074           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.907           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.316           ms/op
ClientGrpc.existUser                      sample  275034   3.488 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.782           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.816           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.894           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.858           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.021           ms/op
ClientGrpc.getUser                        sample  255076   3.762 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.939           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.598           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.054           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.521           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.236           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.398           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.774           ms/op
ClientGrpc.listUser                       sample  192201   4.994 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.916           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.627           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.455           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.535           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.957           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.126           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.591           ms/op
