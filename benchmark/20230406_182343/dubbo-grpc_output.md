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
# Warmup Iteration   1: 3.092 ops/ms
# Warmup Iteration   2: 6.750 ops/ms
# Warmup Iteration   3: 8.295 ops/ms
Iteration   1: 8.409 ops/ms
Iteration   2: 8.832 ops/ms
Iteration   3: 8.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.604 ±(99.9%) 3.893 ops/ms [Average]
  (min, avg, max) = (8.409, 8.604, 8.832), stdev = 0.213
  CI (99.9%): [4.711, 12.497] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.860 ops/ms
# Warmup Iteration   2: 8.501 ops/ms
# Warmup Iteration   3: 8.910 ops/ms
Iteration   1: 9.314 ops/ms
Iteration   2: 9.339 ops/ms
Iteration   3: 9.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.325 ±(99.9%) 0.239 ops/ms [Average]
  (min, avg, max) = (9.314, 9.325, 9.339), stdev = 0.013
  CI (99.9%): [9.086, 9.563] (assumes normal distribution)


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
# Warmup Iteration   1: 5.951 ops/ms
# Warmup Iteration   2: 7.939 ops/ms
# Warmup Iteration   3: 8.399 ops/ms
Iteration   1: 8.902 ops/ms
Iteration   2: 8.731 ops/ms
Iteration   3: 8.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.803 ±(99.9%) 1.617 ops/ms [Average]
  (min, avg, max) = (8.731, 8.803, 8.902), stdev = 0.089
  CI (99.9%): [7.186, 10.420] (assumes normal distribution)


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
# Warmup Iteration   1: 4.339 ops/ms
# Warmup Iteration   2: 6.188 ops/ms
# Warmup Iteration   3: 6.503 ops/ms
Iteration   1: 6.807 ops/ms
Iteration   2: 7.054 ops/ms
Iteration   3: 6.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.900 ±(99.9%) 2.458 ops/ms [Average]
  (min, avg, max) = (6.807, 6.900, 7.054), stdev = 0.135
  CI (99.9%): [4.441, 9.358] (assumes normal distribution)


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
# Warmup Iteration   1: 5.346 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.004 ms/op
Iteration   1: 3.606 ±(99.9%) 0.004 ms/op
Iteration   2: 3.666 ±(99.9%) 0.003 ms/op
Iteration   3: 3.621 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.631 ±(99.9%) 0.570 ms/op [Average]
  (min, avg, max) = (3.606, 3.631, 3.666), stdev = 0.031
  CI (99.9%): [3.061, 4.201] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.005 ms/op
Iteration   1: 3.582 ±(99.9%) 0.003 ms/op
Iteration   2: 3.328 ±(99.9%) 0.004 ms/op
Iteration   3: 3.481 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.464 ±(99.9%) 2.330 ms/op [Average]
  (min, avg, max) = (3.328, 3.464, 3.582), stdev = 0.128
  CI (99.9%): [1.134, 5.794] (assumes normal distribution)


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
# Warmup Iteration   1: 5.452 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.004 ms/op
Iteration   1: 3.644 ±(99.9%) 0.002 ms/op
Iteration   2: 3.725 ±(99.9%) 0.005 ms/op
Iteration   3: 3.792 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.720 ±(99.9%) 1.349 ms/op [Average]
  (min, avg, max) = (3.644, 3.720, 3.792), stdev = 0.074
  CI (99.9%): [2.371, 5.070] (assumes normal distribution)


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
# Warmup Iteration   1: 7.153 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.132 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.838 ±(99.9%) 0.013 ms/op
Iteration   1: 4.671 ±(99.9%) 0.022 ms/op
Iteration   2: 4.732 ±(99.9%) 0.016 ms/op
Iteration   3: 4.699 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.701 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (4.671, 4.701, 4.732), stdev = 0.030
  CI (99.9%): [4.145, 5.257] (assumes normal distribution)


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
# Warmup Iteration   1: 5.419 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.008 ms/op
Iteration   1: 3.626 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   5.924 ms/op
                 createUser·p0.999:  13.678 ms/op
                 createUser·p0.9999: 22.616 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 3.608 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   5.883 ms/op
                 createUser·p0.999:  10.804 ms/op
                 createUser·p0.9999: 14.895 ms/op
                 createUser·p1.00:   16.105 ms/op

Iteration   3: 3.653 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.604 ms/op
                 createUser·p0.999:  12.781 ms/op
                 createUser·p0.9999: 28.246 ms/op
                 createUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264866
  mean =      3.629 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4660 
    [ 2.500,  5.000) = 253582 
    [ 5.000,  7.500) = 5848 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     11.864 ms/op
     p(99.9900) =     27.870 ms/op
     p(99.9990) =     28.379 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.156 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.007 ms/op
Iteration   1: 3.375 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  8.390 ms/op
                 existUser·p0.9999: 14.427 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 3.476 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 16.001 ms/op
                 existUser·p1.00:   16.400 ms/op

Iteration   3: 3.448 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  8.505 ms/op
                 existUser·p0.9999: 18.767 ms/op
                 existUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279780
  mean =      3.432 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 451 
    [ 1.250,  2.500) = 13717 
    [ 2.500,  3.750) = 209517 
    [ 3.750,  5.000) = 50596 
    [ 5.000,  6.250) = 4239 
    [ 6.250,  7.500) = 615 
    [ 7.500,  8.750) = 343 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      8.851 ms/op
     p(99.9900) =     17.238 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 5.233 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.722 ±(99.9%) 0.010 ms/op
Iteration   1: 3.678 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  9.487 ms/op
                 getUser·p0.9999: 15.100 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   2: 3.804 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  14.038 ms/op
                 getUser·p0.9999: 18.304 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   3: 3.657 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  9.028 ms/op
                 getUser·p0.9999: 28.010 ms/op
                 getUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258480
  mean =      3.712 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7456 
    [ 2.500,  5.000) = 242308 
    [ 5.000,  7.500) = 7895 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =      9.978 ms/op
     p(99.9900) =     26.711 ms/op
     p(99.9990) =     28.994 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 6.788 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.266 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.756 ±(99.9%) 0.017 ms/op
Iteration   1: 4.779 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.234 ms/op
                 listUser·p0.95:   7.111 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  16.318 ms/op
                 listUser·p0.9999: 24.353 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   2: 4.737 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  16.015 ms/op
                 listUser·p0.9999: 21.471 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   3: 4.759 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   6.455 ms/op
                 listUser·p0.95:   7.250 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  20.775 ms/op
                 listUser·p0.9999: 36.588 ms/op
                 listUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201687
  mean =      4.759 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1065 
    [ 2.500,  5.000) = 149138 
    [ 5.000,  7.500) = 44587 
    [ 7.500, 10.000) = 6057 
    [10.000, 12.500) = 396 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      6.300 ms/op
     p(95.0000) =      7.143 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     17.004 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     36.700 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.604 ± 3.893  ops/ms
ClientGrpc.existUser                       thrpt       3   9.325 ± 0.239  ops/ms
ClientGrpc.getUser                         thrpt       3   8.803 ± 1.617  ops/ms
ClientGrpc.listUser                        thrpt       3   6.900 ± 2.458  ops/ms
ClientGrpc.createUser                       avgt       3   3.631 ± 0.570   ms/op
ClientGrpc.existUser                        avgt       3   3.464 ± 2.330   ms/op
ClientGrpc.getUser                          avgt       3   3.720 ± 1.349   ms/op
ClientGrpc.listUser                         avgt       3   4.701 ± 0.556   ms/op
ClientGrpc.createUser                     sample  264866   3.629 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.947           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.833           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.870           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.443           ms/op
ClientGrpc.existUser                      sample  279780   3.432 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.677           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.851           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.238           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.038           ms/op
ClientGrpc.getUser                        sample  258480   3.712 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.740           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.931           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.978           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.711           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.098           ms/op
ClientGrpc.listUser                       sample  201687   4.759 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.120           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.300           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.651           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.004           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.472           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.552           ms/op
