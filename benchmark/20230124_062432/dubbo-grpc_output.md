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
# Warmup Iteration   1: 2.425 ops/ms
# Warmup Iteration   2: 6.369 ops/ms
# Warmup Iteration   3: 7.762 ops/ms
Iteration   1: 7.492 ops/ms
Iteration   2: 7.552 ops/ms
Iteration   3: 7.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.479 ±(99.9%) 1.450 ops/ms [Average]
  (min, avg, max) = (7.394, 7.479, 7.552), stdev = 0.079
  CI (99.9%): [6.029, 8.930] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.429 ops/ms
# Warmup Iteration   2: 7.969 ops/ms
# Warmup Iteration   3: 8.202 ops/ms
Iteration   1: 8.167 ops/ms
Iteration   2: 7.783 ops/ms
Iteration   3: 7.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.980 ±(99.9%) 3.512 ops/ms [Average]
  (min, avg, max) = (7.783, 7.980, 8.167), stdev = 0.192
  CI (99.9%): [4.468, 11.491] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.877 ops/ms
# Warmup Iteration   2: 7.111 ops/ms
# Warmup Iteration   3: 7.364 ops/ms
Iteration   1: 7.220 ops/ms
Iteration   2: 7.539 ops/ms
Iteration   3: 7.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.393 ±(99.9%) 2.936 ops/ms [Average]
  (min, avg, max) = (7.220, 7.393, 7.539), stdev = 0.161
  CI (99.9%): [4.456, 10.329] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.176 ops/ms
# Warmup Iteration   2: 6.355 ops/ms
# Warmup Iteration   3: 6.667 ops/ms
Iteration   1: 6.659 ops/ms
Iteration   2: 6.560 ops/ms
Iteration   3: 6.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.579 ±(99.9%) 1.311 ops/ms [Average]
  (min, avg, max) = (6.519, 6.579, 6.659), stdev = 0.072
  CI (99.9%): [5.268, 7.890] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.798 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.477 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.002 ms/op
Iteration   1: 4.040 ±(99.9%) 0.002 ms/op
Iteration   2: 4.015 ±(99.9%) 0.003 ms/op
Iteration   3: 4.066 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.040 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (4.015, 4.040, 4.066), stdev = 0.025
  CI (99.9%): [3.581, 4.499] (assumes normal distribution)


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
# Warmup Iteration   1: 5.605 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.002 ms/op
Iteration   1: 3.787 ±(99.9%) 0.003 ms/op
Iteration   2: 3.845 ±(99.9%) 0.003 ms/op
Iteration   3: 3.877 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.836 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (3.787, 3.836, 3.877), stdev = 0.045
  CI (99.9%): [3.007, 4.666] (assumes normal distribution)


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
# Warmup Iteration   1: 5.685 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.412 ±(99.9%) 0.003 ms/op
Iteration   1: 4.342 ±(99.9%) 0.004 ms/op
Iteration   2: 4.024 ±(99.9%) 0.002 ms/op
Iteration   3: 4.238 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.202 ±(99.9%) 2.961 ms/op [Average]
  (min, avg, max) = (4.024, 4.202, 4.342), stdev = 0.162
  CI (99.9%): [1.241, 7.162] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.518 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.309 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.242 ±(99.9%) 0.029 ms/op
Iteration   1: 5.061 ±(99.9%) 0.010 ms/op
Iteration   2: 5.032 ±(99.9%) 0.011 ms/op
Iteration   3: 5.078 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.057 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (5.032, 5.057, 5.078), stdev = 0.023
  CI (99.9%): [4.629, 5.485] (assumes normal distribution)


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
# Warmup Iteration   1: 6.397 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.010 ms/op
Iteration   1: 4.430 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.407 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.825 ms/op
                 createUser·p0.95:   6.455 ms/op
                 createUser·p0.99:   8.225 ms/op
                 createUser·p0.999:  17.052 ms/op
                 createUser·p0.9999: 26.717 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   2: 4.131 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.693 ms/op
                 createUser·p0.99:   7.741 ms/op
                 createUser·p0.999:  15.241 ms/op
                 createUser·p0.9999: 32.539 ms/op
                 createUser·p1.00:   32.965 ms/op

Iteration   3: 3.856 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  11.604 ms/op
                 createUser·p0.9999: 24.098 ms/op
                 createUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 232538
  mean =      4.126 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4470 
    [ 2.500,  5.000) = 191570 
    [ 5.000,  7.500) = 33970 
    [ 7.500, 10.000) = 1960 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     13.295 ms/op
     p(99.9900) =     31.028 ms/op
     p(99.9990) =     32.867 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 5.513 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
Iteration   1: 3.918 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  9.668 ms/op
                 existUser·p0.9999: 13.553 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   2: 4.070 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   5.169 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  11.355 ms/op
                 existUser·p0.9999: 16.777 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   3: 3.976 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.404 ms/op
                 existUser·p0.50:   3.924 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  9.469 ms/op
                 existUser·p0.9999: 25.883 ms/op
                 existUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 240731
  mean =      3.987 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7322 
    [ 2.500,  5.000) = 201919 
    [ 5.000,  7.500) = 30501 
    [ 7.500, 10.000) = 707 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     10.425 ms/op
     p(99.9900) =     25.151 ms/op
     p(99.9990) =     28.809 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 6.092 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.289 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.011 ms/op
Iteration   1: 4.067 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.587 ms/op
                 getUser·p0.99:   7.184 ms/op
                 getUser·p0.999:  12.232 ms/op
                 getUser·p0.9999: 15.164 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   2: 4.077 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   4.039 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  10.081 ms/op
                 getUser·p0.9999: 16.550 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   3: 4.068 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   3.985 ms/op
                 getUser·p0.90:   5.030 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  13.464 ms/op
                 getUser·p0.9999: 20.485 ms/op
                 getUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235890
  mean =      4.071 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4437 
    [ 2.500,  5.000) = 200397 
    [ 5.000,  7.500) = 29893 
    [ 7.500, 10.000) = 789 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     12.208 ms/op
     p(99.9900) =     19.314 ms/op
     p(99.9990) =     21.284 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 8.496 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.341 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.122 ±(99.9%) 0.017 ms/op
Iteration   1: 5.181 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.348 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  16.648 ms/op
                 listUser·p0.9999: 22.981 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 4.993 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  16.841 ms/op
                 listUser·p0.9999: 19.352 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 5.033 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   6.316 ms/op
                 listUser·p0.95:   7.102 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  17.708 ms/op
                 listUser·p0.9999: 26.924 ms/op
                 listUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 189375
  mean =      5.068 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 287 
    [ 2.500,  5.000) = 107412 
    [ 5.000,  7.500) = 74930 
    [ 7.500, 10.000) = 5840 
    [10.000, 12.500) = 565 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.176 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     17.093 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     30.397 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.479 ± 1.450  ops/ms
ClientGrpc.existUser                       thrpt       3   7.980 ± 3.512  ops/ms
ClientGrpc.getUser                         thrpt       3   7.393 ± 2.936  ops/ms
ClientGrpc.listUser                        thrpt       3   6.579 ± 1.311  ops/ms
ClientGrpc.createUser                       avgt       3   4.040 ± 0.459   ms/op
ClientGrpc.existUser                        avgt       3   3.836 ± 0.829   ms/op
ClientGrpc.getUser                          avgt       3   4.202 ± 2.961   ms/op
ClientGrpc.listUser                         avgt       3   5.057 ± 0.428   ms/op
ClientGrpc.createUser                     sample  232538   4.126 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.407           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.333           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.816           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.610           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.295           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.028           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.965           ms/op
ClientGrpc.existUser                      sample  240731   3.987 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.404           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.145           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.456           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.332           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.425           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.151           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.655           ms/op
ClientGrpc.getUser                        sample  235890   4.071 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.969           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.145           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.464           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.472           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.208           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.314           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.955           ms/op
ClientGrpc.listUser                       sample  189375   5.068 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.124           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.480           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.897           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.093           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.117           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.573           ms/op
