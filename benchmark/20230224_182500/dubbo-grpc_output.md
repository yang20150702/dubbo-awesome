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
# Warmup Iteration   1: 3.316 ops/ms
# Warmup Iteration   2: 6.845 ops/ms
# Warmup Iteration   3: 8.281 ops/ms
Iteration   1: 8.594 ops/ms
Iteration   2: 8.446 ops/ms
Iteration   3: 8.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.604 ±(99.9%) 2.982 ops/ms [Average]
  (min, avg, max) = (8.446, 8.604, 8.772), stdev = 0.163
  CI (99.9%): [5.622, 11.586] (assumes normal distribution)


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
# Warmup Iteration   1: 6.285 ops/ms
# Warmup Iteration   2: 8.637 ops/ms
# Warmup Iteration   3: 9.101 ops/ms
Iteration   1: 9.155 ops/ms
Iteration   2: 9.183 ops/ms
Iteration   3: 8.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.092 ±(99.9%) 2.435 ops/ms [Average]
  (min, avg, max) = (8.939, 9.092, 9.183), stdev = 0.133
  CI (99.9%): [6.657, 11.527] (assumes normal distribution)


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
# Warmup Iteration   1: 5.373 ops/ms
# Warmup Iteration   2: 8.351 ops/ms
# Warmup Iteration   3: 8.696 ops/ms
Iteration   1: 8.746 ops/ms
Iteration   2: 8.917 ops/ms
Iteration   3: 8.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.887 ±(99.9%) 2.355 ops/ms [Average]
  (min, avg, max) = (8.746, 8.887, 8.999), stdev = 0.129
  CI (99.9%): [6.532, 11.242] (assumes normal distribution)


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
# Warmup Iteration   1: 4.539 ops/ms
# Warmup Iteration   2: 6.294 ops/ms
# Warmup Iteration   3: 6.540 ops/ms
Iteration   1: 6.681 ops/ms
Iteration   2: 6.629 ops/ms
Iteration   3: 6.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.674 ±(99.9%) 0.771 ops/ms [Average]
  (min, avg, max) = (6.629, 6.674, 6.713), stdev = 0.042
  CI (99.9%): [5.903, 7.445] (assumes normal distribution)


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
# Warmup Iteration   1: 5.404 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.706 ±(99.9%) 0.004 ms/op
Iteration   1: 3.728 ±(99.9%) 0.002 ms/op
Iteration   2: 3.701 ±(99.9%) 0.004 ms/op
Iteration   3: 3.701 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.710 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (3.701, 3.710, 3.728), stdev = 0.016
  CI (99.9%): [3.426, 3.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.811 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.007 ms/op
Iteration   1: 3.610 ±(99.9%) 0.004 ms/op
Iteration   2: 3.608 ±(99.9%) 0.002 ms/op
Iteration   3: 3.422 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.546 ±(99.9%) 1.964 ms/op [Average]
  (min, avg, max) = (3.422, 3.546, 3.610), stdev = 0.108
  CI (99.9%): [1.583, 5.510] (assumes normal distribution)


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
# Warmup Iteration   1: 5.256 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.003 ms/op
Iteration   1: 3.854 ±(99.9%) 0.003 ms/op
Iteration   2: 3.770 ±(99.9%) 0.003 ms/op
Iteration   3: 3.722 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.782 ±(99.9%) 1.218 ms/op [Average]
  (min, avg, max) = (3.722, 3.782, 3.854), stdev = 0.067
  CI (99.9%): [2.564, 4.999] (assumes normal distribution)


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
# Warmup Iteration   1: 6.365 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.974 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.640 ±(99.9%) 0.024 ms/op
Iteration   1: 4.712 ±(99.9%) 0.013 ms/op
Iteration   2: 4.478 ±(99.9%) 0.009 ms/op
Iteration   3: 4.680 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.623 ±(99.9%) 2.319 ms/op [Average]
  (min, avg, max) = (4.478, 4.623, 4.712), stdev = 0.127
  CI (99.9%): [2.305, 6.942] (assumes normal distribution)


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
# Warmup Iteration   1: 5.359 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.745 ±(99.9%) 0.011 ms/op
Iteration   1: 3.822 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.833 ms/op
                 createUser·p0.999:  10.112 ms/op
                 createUser·p0.9999: 20.304 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   2: 3.851 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  11.076 ms/op
                 createUser·p0.9999: 28.334 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   3: 3.879 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  24.754 ms/op
                 createUser·p0.9999: 27.386 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 249404
  mean =      3.850 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6537 
    [ 2.500,  5.000) = 229054 
    [ 5.000,  7.500) = 12261 
    [ 7.500, 10.000) = 1019 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 82 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     28.443 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.601 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.011 ms/op
Iteration   1: 3.487 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  7.498 ms/op
                 existUser·p0.9999: 14.123 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   2: 3.560 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  8.508 ms/op
                 existUser·p0.9999: 17.433 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   3: 3.594 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  8.126 ms/op
                 existUser·p0.9999: 18.976 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270671
  mean =      3.546 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10685 
    [ 2.500,  5.000) = 254965 
    [ 5.000,  7.500) = 4608 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      7.987 ms/op
     p(99.9900) =     18.381 ms/op
     p(99.9990) =     21.024 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 5.406 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.009 ms/op
Iteration   1: 3.684 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.020 ms/op
                 getUser·p0.999:  10.721 ms/op
                 getUser·p0.9999: 15.013 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   2: 3.764 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  11.795 ms/op
                 getUser·p0.9999: 16.703 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   3: 3.694 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  9.470 ms/op
                 getUser·p0.9999: 19.792 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258532
  mean =      3.713 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10252 
    [ 2.500,  5.000) = 238068 
    [ 5.000,  7.500) = 9009 
    [ 7.500, 10.000) = 848 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     11.255 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     20.212 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.832 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.017 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.607 ±(99.9%) 0.014 ms/op
Iteration   1: 4.561 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.849 ms/op
                 listUser·p0.95:   6.513 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  14.739 ms/op
                 listUser·p0.9999: 22.970 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   2: 4.379 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   4.211 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   6.300 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  17.248 ms/op
                 listUser·p0.9999: 28.399 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   3: 4.286 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   4.153 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  18.302 ms/op
                 listUser·p0.9999: 21.104 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 218081
  mean =      4.406 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 852 
    [ 2.500,  5.000) = 181770 
    [ 5.000,  7.500) = 32196 
    [ 7.500, 10.000) = 2689 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.587 ms/op
     p(95.0000) =      6.308 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     16.936 ms/op
     p(99.9900) =     26.954 ms/op
     p(99.9990) =     30.248 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.604 ± 2.982  ops/ms
ClientGrpc.existUser                       thrpt       3   9.092 ± 2.435  ops/ms
ClientGrpc.getUser                         thrpt       3   8.887 ± 2.355  ops/ms
ClientGrpc.listUser                        thrpt       3   6.674 ± 0.771  ops/ms
ClientGrpc.createUser                       avgt       3   3.710 ± 0.284   ms/op
ClientGrpc.existUser                        avgt       3   3.546 ± 1.964   ms/op
ClientGrpc.getUser                          avgt       3   3.782 ± 1.218   ms/op
ClientGrpc.listUser                         avgt       3   4.623 ± 2.319   ms/op
ClientGrpc.createUser                     sample  249404   3.850 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.914           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.627           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.468           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.689           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.443           ms/op
ClientGrpc.existUser                      sample  270671   3.546 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.692           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.579           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.448           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.987           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.381           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.070           ms/op
ClientGrpc.getUser                        sample  258532   3.713 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.893           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.891           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.136           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.255           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.071           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.316           ms/op
ClientGrpc.listUser                       sample  218081   4.406 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.292           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.235           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.308           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.905           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.936           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.954           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.573           ms/op
