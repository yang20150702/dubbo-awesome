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
# Warmup Iteration   1: 2.542 ops/ms
# Warmup Iteration   2: 6.347 ops/ms
# Warmup Iteration   3: 7.613 ops/ms
Iteration   1: 7.675 ops/ms
Iteration   2: 7.505 ops/ms
Iteration   3: 7.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.585 ±(99.9%) 1.554 ops/ms [Average]
  (min, avg, max) = (7.505, 7.585, 7.675), stdev = 0.085
  CI (99.9%): [6.031, 9.139] (assumes normal distribution)


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
# Warmup Iteration   1: 5.349 ops/ms
# Warmup Iteration   2: 8.018 ops/ms
# Warmup Iteration   3: 8.540 ops/ms
Iteration   1: 8.557 ops/ms
Iteration   2: 8.153 ops/ms
Iteration   3: 8.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.342 ±(99.9%) 3.707 ops/ms [Average]
  (min, avg, max) = (8.153, 8.342, 8.557), stdev = 0.203
  CI (99.9%): [4.635, 12.049] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.916 ops/ms
# Warmup Iteration   2: 7.040 ops/ms
# Warmup Iteration   3: 7.678 ops/ms
Iteration   1: 7.730 ops/ms
Iteration   2: 7.699 ops/ms
Iteration   3: 7.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.631 ±(99.9%) 2.643 ops/ms [Average]
  (min, avg, max) = (7.465, 7.631, 7.730), stdev = 0.145
  CI (99.9%): [4.988, 10.275] (assumes normal distribution)


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
# Warmup Iteration   1: 4.172 ops/ms
# Warmup Iteration   2: 5.622 ops/ms
# Warmup Iteration   3: 5.893 ops/ms
Iteration   1: 6.151 ops/ms
Iteration   2: 5.700 ops/ms
Iteration   3: 5.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.805 ±(99.9%) 5.613 ops/ms [Average]
  (min, avg, max) = (5.563, 5.805, 6.151), stdev = 0.308
  CI (99.9%): [0.192, 11.418] (assumes normal distribution)


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
# Warmup Iteration   1: 5.916 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.003 ms/op
Iteration   1: 4.178 ±(99.9%) 0.004 ms/op
Iteration   2: 3.994 ±(99.9%) 0.002 ms/op
Iteration   3: 4.290 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.154 ±(99.9%) 2.730 ms/op [Average]
  (min, avg, max) = (3.994, 4.154, 4.290), stdev = 0.150
  CI (99.9%): [1.424, 6.884] (assumes normal distribution)


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
# Warmup Iteration   1: 5.666 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.003 ms/op
Iteration   1: 3.738 ±(99.9%) 0.002 ms/op
Iteration   2: 3.885 ±(99.9%) 0.002 ms/op
Iteration   3: 3.806 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.810 ±(99.9%) 1.338 ms/op [Average]
  (min, avg, max) = (3.738, 3.810, 3.885), stdev = 0.073
  CI (99.9%): [2.472, 5.148] (assumes normal distribution)


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
# Warmup Iteration   1: 5.774 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.003 ms/op
Iteration   1: 3.902 ±(99.9%) 0.004 ms/op
Iteration   2: 3.693 ±(99.9%) 0.002 ms/op
Iteration   3: 3.872 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.822 ±(99.9%) 2.059 ms/op [Average]
  (min, avg, max) = (3.693, 3.822, 3.902), stdev = 0.113
  CI (99.9%): [1.763, 5.882] (assumes normal distribution)


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
# Warmup Iteration   1: 7.513 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.233 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.805 ±(99.9%) 0.012 ms/op
Iteration   1: 4.681 ±(99.9%) 0.016 ms/op
Iteration   2: 4.755 ±(99.9%) 0.015 ms/op
Iteration   3: 5.037 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.824 ±(99.9%) 3.427 ms/op [Average]
  (min, avg, max) = (4.681, 4.824, 5.037), stdev = 0.188
  CI (99.9%): [1.397, 8.251] (assumes normal distribution)


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
# Warmup Iteration   1: 5.677 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.011 ms/op
Iteration   1: 3.559 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  11.749 ms/op
                 createUser·p0.9999: 21.136 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   2: 3.610 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.837 ms/op
                 createUser·p0.999:  12.775 ms/op
                 createUser·p0.9999: 22.619 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   3: 3.820 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   7.087 ms/op
                 createUser·p0.999:  15.261 ms/op
                 createUser·p0.9999: 23.036 ms/op
                 createUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262431
  mean =      3.659 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8652 
    [ 2.500,  5.000) = 237807 
    [ 5.000,  7.500) = 14255 
    [ 7.500, 10.000) = 1128 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.461 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 5.220 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.010 ms/op
Iteration   1: 3.497 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  10.314 ms/op
                 existUser·p0.9999: 20.808 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   2: 3.336 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  9.290 ms/op
                 existUser·p0.9999: 17.230 ms/op
                 existUser·p1.00:   19.038 ms/op

Iteration   3: 3.541 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  10.569 ms/op
                 existUser·p0.9999: 24.672 ms/op
                 existUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277760
  mean =      3.456 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13820 
    [ 2.500,  5.000) = 253465 
    [ 5.000,  7.500) = 9390 
    [ 7.500, 10.000) = 811 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =      9.949 ms/op
     p(99.9900) =     23.438 ms/op
     p(99.9990) =     25.843 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 5.255 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.645 ±(99.9%) 0.009 ms/op
Iteration   1: 3.524 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  12.440 ms/op
                 getUser·p0.9999: 21.100 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 3.646 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.290 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  17.452 ms/op
                 getUser·p0.9999: 249.572 ms/op
                 getUser·p1.00:   262.406 ms/op

Iteration   3: 3.702 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  10.977 ms/op
                 getUser·p0.9999: 19.038 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 267043
  mean =      3.623 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [  0.000,  25.000) = 266994 
    [ 25.000,  50.000) = 9 
    [ 50.000,  75.000) = 7 
    [ 75.000, 100.000) = 2 
    [100.000, 125.000) = 2 
    [125.000, 150.000) = 2 
    [150.000, 175.000) = 2 
    [175.000, 200.000) = 5 
    [200.000, 225.000) = 3 
    [225.000, 250.000) = 9 
    [250.000, 275.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.290 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     12.320 ms/op
     p(99.9900) =    166.354 ms/op
     p(99.9990) =    260.920 ms/op
     p(99.9999) =    262.406 ms/op
    p(100.0000) =    262.406 ms/op


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
# Warmup Iteration   1: 7.036 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.859 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.970 ±(99.9%) 0.019 ms/op
Iteration   1: 4.870 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.447 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.455 ms/op
                 listUser·p0.95:   7.283 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  21.070 ms/op
                 listUser·p0.9999: 25.199 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   2: 4.765 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   7.094 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  28.734 ms/op
                 listUser·p0.9999: 32.539 ms/op
                 listUser·p1.00:   33.948 ms/op

Iteration   3: 4.860 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.570 ms/op
                 listUser·p0.95:   7.660 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  19.399 ms/op
                 listUser·p0.9999: 23.345 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198551
  mean =      4.831 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 813 
    [ 2.500,  5.000) = 133959 
    [ 5.000,  7.500) = 54882 
    [ 7.500, 10.000) = 7038 
    [10.000, 12.500) = 1178 
    [12.500, 15.000) = 305 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     20.382 ms/op
     p(99.9900) =     31.631 ms/op
     p(99.9990) =     33.818 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt    Score   Error   Units
ClientGrpc.createUser                      thrpt       3    7.585 ± 1.554  ops/ms
ClientGrpc.existUser                       thrpt       3    8.342 ± 3.707  ops/ms
ClientGrpc.getUser                         thrpt       3    7.631 ± 2.643  ops/ms
ClientGrpc.listUser                        thrpt       3    5.805 ± 5.613  ops/ms
ClientGrpc.createUser                       avgt       3    4.154 ± 2.730   ms/op
ClientGrpc.existUser                        avgt       3    3.810 ± 1.338   ms/op
ClientGrpc.getUser                          avgt       3    3.822 ± 2.059   ms/op
ClientGrpc.listUser                         avgt       3    4.824 ± 3.427   ms/op
ClientGrpc.createUser                     sample  262431    3.659 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample            0.748           ms/op
ClientGrpc.createUser:createUser·p0.50    sample            3.502           ms/op
ClientGrpc.createUser:createUser·p0.90    sample            4.669           ms/op
ClientGrpc.createUser:createUser·p0.95    sample            5.136           ms/op
ClientGrpc.createUser:createUser·p0.99    sample            6.865           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           13.461           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample           22.643           ms/op
ClientGrpc.createUser:createUser·p1.00    sample           23.855           ms/op
ClientGrpc.existUser                      sample  277760    3.456 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample            0.639           ms/op
ClientGrpc.existUser:existUser·p0.50      sample            3.334           ms/op
ClientGrpc.existUser:existUser·p0.90      sample            4.309           ms/op
ClientGrpc.existUser:existUser·p0.95      sample            4.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample            6.316           ms/op
ClientGrpc.existUser:existUser·p0.999     sample            9.949           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample           23.438           ms/op
ClientGrpc.existUser:existUser·p1.00      sample           26.018           ms/op
ClientGrpc.getUser                        sample  267043    3.623 ± 0.016   ms/op
ClientGrpc.getUser:getUser·p0.00          sample            0.290           ms/op
ClientGrpc.getUser:getUser·p0.50          sample            3.482           ms/op
ClientGrpc.getUser:getUser·p0.90          sample            4.530           ms/op
ClientGrpc.getUser:getUser·p0.95          sample            4.948           ms/op
ClientGrpc.getUser:getUser·p0.99          sample            6.390           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           12.320           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          166.354           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          262.406           ms/op
ClientGrpc.listUser                       sample  198551    4.831 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample            0.447           ms/op
ClientGrpc.listUser:listUser·p0.50        sample            4.547           ms/op
ClientGrpc.listUser:listUser·p0.90        sample            6.398           ms/op
ClientGrpc.listUser:listUser·p0.95        sample            7.340           ms/op
ClientGrpc.listUser:listUser·p0.99        sample            9.863           ms/op
ClientGrpc.listUser:listUser·p0.999       sample           20.382           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample           31.631           ms/op
ClientGrpc.listUser:listUser·p1.00        sample           33.948           ms/op
