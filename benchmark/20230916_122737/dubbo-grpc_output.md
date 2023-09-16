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
# Warmup Iteration   1: 3.001 ops/ms
# Warmup Iteration   2: 6.718 ops/ms
# Warmup Iteration   3: 7.985 ops/ms
Iteration   1: 8.197 ops/ms
Iteration   2: 8.311 ops/ms
Iteration   3: 8.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.332 ±(99.9%) 2.686 ops/ms [Average]
  (min, avg, max) = (8.197, 8.332, 8.489), stdev = 0.147
  CI (99.9%): [5.647, 11.018] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.635 ops/ms
# Warmup Iteration   2: 8.607 ops/ms
# Warmup Iteration   3: 8.824 ops/ms
Iteration   1: 9.015 ops/ms
Iteration   2: 8.849 ops/ms
Iteration   3: 8.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.916 ±(99.9%) 1.591 ops/ms [Average]
  (min, avg, max) = (8.849, 8.916, 9.015), stdev = 0.087
  CI (99.9%): [7.325, 10.508] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.873 ops/ms
# Warmup Iteration   2: 8.145 ops/ms
# Warmup Iteration   3: 8.561 ops/ms
Iteration   1: 8.491 ops/ms
Iteration   2: 8.420 ops/ms
Iteration   3: 8.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.501 ±(99.9%) 1.569 ops/ms [Average]
  (min, avg, max) = (8.420, 8.501, 8.591), stdev = 0.086
  CI (99.9%): [6.932, 10.069] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.060 ops/ms
# Warmup Iteration   2: 6.128 ops/ms
# Warmup Iteration   3: 6.934 ops/ms
Iteration   1: 6.705 ops/ms
Iteration   2: 6.747 ops/ms
Iteration   3: 6.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.742 ±(99.9%) 0.635 ops/ms [Average]
  (min, avg, max) = (6.705, 6.742, 6.774), stdev = 0.035
  CI (99.9%): [6.107, 7.377] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.393 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.013 ms/op
Iteration   1: 3.854 ±(99.9%) 0.002 ms/op
Iteration   2: 3.727 ±(99.9%) 0.002 ms/op
Iteration   3: 3.609 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.730 ±(99.9%) 2.232 ms/op [Average]
  (min, avg, max) = (3.609, 3.730, 3.854), stdev = 0.122
  CI (99.9%): [1.498, 5.962] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.843 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.003 ms/op
Iteration   1: 3.677 ±(99.9%) 0.002 ms/op
Iteration   2: 3.645 ±(99.9%) 0.003 ms/op
Iteration   3: 3.649 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.657 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (3.645, 3.657, 3.677), stdev = 0.018
  CI (99.9%): [3.334, 3.981] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.315 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.004 ms/op
Iteration   1: 3.913 ±(99.9%) 0.002 ms/op
Iteration   2: 3.742 ±(99.9%) 0.005 ms/op
Iteration   3: 3.838 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.831 ±(99.9%) 1.571 ms/op [Average]
  (min, avg, max) = (3.742, 3.831, 3.913), stdev = 0.086
  CI (99.9%): [2.260, 5.402] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.285 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.976 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.662 ±(99.9%) 0.012 ms/op
Iteration   1: 4.782 ±(99.9%) 0.012 ms/op
Iteration   2: 4.740 ±(99.9%) 0.013 ms/op
Iteration   3: 4.574 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.699 ±(99.9%) 2.009 ms/op [Average]
  (min, avg, max) = (4.574, 4.699, 4.782), stdev = 0.110
  CI (99.9%): [2.690, 6.707] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.631 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.008 ms/op
Iteration   1: 3.729 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.754 ms/op
                 createUser·p0.99:   6.385 ms/op
                 createUser·p0.999:  12.210 ms/op
                 createUser·p0.9999: 19.249 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   2: 3.789 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  9.181 ms/op
                 createUser·p0.9999: 15.887 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   3: 3.718 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  17.072 ms/op
                 createUser·p0.9999: 23.573 ms/op
                 createUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256278
  mean =      3.745 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4611 
    [ 2.500,  5.000) = 243507 
    [ 5.000,  7.500) = 7240 
    [ 7.500, 10.000) = 617 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     12.087 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     23.753 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.092 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.622 ±(99.9%) 0.009 ms/op
Iteration   1: 3.594 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  7.799 ms/op
                 existUser·p0.9999: 14.716 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   2: 3.687 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 16.264 ms/op
                 existUser·p1.00:   16.433 ms/op

Iteration   3: 3.603 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  9.281 ms/op
                 existUser·p0.9999: 18.190 ms/op
                 existUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264529
  mean =      3.628 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 220 
    [ 1.250,  2.500) = 6212 
    [ 2.500,  3.750) = 164330 
    [ 3.750,  5.000) = 86008 
    [ 5.000,  6.250) = 5475 
    [ 6.250,  7.500) = 1352 
    [ 7.500,  8.750) = 579 
    [ 8.750, 10.000) = 137 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.427 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.447 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.010 ms/op
Iteration   1: 3.764 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  9.536 ms/op
                 getUser·p0.9999: 19.382 ms/op
                 getUser·p1.00:   19.661 ms/op

Iteration   2: 3.772 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  13.213 ms/op
                 getUser·p0.9999: 24.757 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   3: 3.692 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.374 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.528 ms/op
                 getUser·p0.999:  11.662 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256472
  mean =      3.742 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4531 
    [ 2.500,  5.000) = 241304 
    [ 5.000,  7.500) = 9466 
    [ 7.500, 10.000) = 838 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     10.797 ms/op
     p(99.9900) =     22.436 ms/op
     p(99.9990) =     25.031 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 6.676 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.999 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.700 ±(99.9%) 0.014 ms/op
Iteration   1: 4.562 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  14.886 ms/op
                 listUser·p0.9999: 17.235 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   2: 4.642 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.636 ms/op
                 listUser·p0.95:   6.537 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  16.174 ms/op
                 listUser·p0.9999: 18.583 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   3: 4.721 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.496 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  19.917 ms/op
                 listUser·p0.9999: 21.806 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206622
  mean =      4.641 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 213 
    [ 2.500,  5.000) = 166298 
    [ 5.000,  7.500) = 35967 
    [ 7.500, 10.000) = 3435 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      8.176 ms/op
     p(99.9000) =     15.948 ms/op
     p(99.9900) =     21.441 ms/op
     p(99.9990) =     22.352 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.332 ± 2.686  ops/ms
ClientGrpc.existUser                       thrpt       3   8.916 ± 1.591  ops/ms
ClientGrpc.getUser                         thrpt       3   8.501 ± 1.569  ops/ms
ClientGrpc.listUser                        thrpt       3   6.742 ± 0.635  ops/ms
ClientGrpc.createUser                       avgt       3   3.730 ± 2.232   ms/op
ClientGrpc.existUser                        avgt       3   3.657 ± 0.324   ms/op
ClientGrpc.getUser                          avgt       3   3.831 ± 1.571   ms/op
ClientGrpc.listUser                         avgt       3   4.699 ± 2.009   ms/op
ClientGrpc.createUser                     sample  256278   3.745 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.011           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.119           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.087           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.069           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.855           ms/op
ClientGrpc.existUser                      sample  264529   3.628 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.674           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.095           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.191           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.022           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.514           ms/op
ClientGrpc.getUser                        sample  256472   3.742 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.374           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.874           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.439           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.797           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.436           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.166           ms/op
ClientGrpc.listUser                       sample  206622   4.641 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.761           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.473           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.398           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.948           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.441           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.741           ms/op
