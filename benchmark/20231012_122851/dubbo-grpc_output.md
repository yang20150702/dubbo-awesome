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
# Warmup Iteration   1: 3.671 ops/ms
# Warmup Iteration   2: 7.343 ops/ms
# Warmup Iteration   3: 8.343 ops/ms
Iteration   1: 9.060 ops/ms
Iteration   2: 8.735 ops/ms
Iteration   3: 8.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.886 ±(99.9%) 2.989 ops/ms [Average]
  (min, avg, max) = (8.735, 8.886, 9.060), stdev = 0.164
  CI (99.9%): [5.897, 11.876] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.114 ops/ms
# Warmup Iteration   2: 8.709 ops/ms
# Warmup Iteration   3: 9.128 ops/ms
Iteration   1: 9.261 ops/ms
Iteration   2: 9.026 ops/ms
Iteration   3: 9.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.258 ±(99.9%) 4.224 ops/ms [Average]
  (min, avg, max) = (9.026, 9.258, 9.489), stdev = 0.232
  CI (99.9%): [5.035, 13.482] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.397 ops/ms
# Warmup Iteration   2: 8.349 ops/ms
# Warmup Iteration   3: 8.588 ops/ms
Iteration   1: 8.717 ops/ms
Iteration   2: 8.932 ops/ms
Iteration   3: 8.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.798 ±(99.9%) 2.135 ops/ms [Average]
  (min, avg, max) = (8.717, 8.798, 8.932), stdev = 0.117
  CI (99.9%): [6.663, 10.933] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.329 ops/ms
# Warmup Iteration   2: 6.526 ops/ms
# Warmup Iteration   3: 6.854 ops/ms
Iteration   1: 6.754 ops/ms
Iteration   2: 6.858 ops/ms
Iteration   3: 6.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.774 ±(99.9%) 1.377 ops/ms [Average]
  (min, avg, max) = (6.712, 6.774, 6.858), stdev = 0.075
  CI (99.9%): [5.397, 8.151] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.743 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.003 ms/op
Iteration   1: 3.669 ±(99.9%) 0.003 ms/op
Iteration   2: 3.743 ±(99.9%) 0.002 ms/op
Iteration   3: 3.695 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.702 ±(99.9%) 0.692 ms/op [Average]
  (min, avg, max) = (3.669, 3.702, 3.743), stdev = 0.038
  CI (99.9%): [3.011, 4.394] (assumes normal distribution)


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
# Warmup Iteration   1: 4.919 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.002 ms/op
Iteration   1: 3.586 ±(99.9%) 0.001 ms/op
Iteration   2: 3.444 ±(99.9%) 0.003 ms/op
Iteration   3: 3.556 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.529 ±(99.9%) 1.371 ms/op [Average]
  (min, avg, max) = (3.444, 3.529, 3.586), stdev = 0.075
  CI (99.9%): [2.158, 4.900] (assumes normal distribution)


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
# Warmup Iteration   1: 4.942 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.003 ms/op
Iteration   1: 3.708 ±(99.9%) 0.003 ms/op
Iteration   2: 3.634 ±(99.9%) 0.003 ms/op
Iteration   3: 3.661 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.668 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.634, 3.668, 3.708), stdev = 0.038
  CI (99.9%): [2.983, 4.352] (assumes normal distribution)


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
# Warmup Iteration   1: 6.677 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.851 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.582 ±(99.9%) 0.030 ms/op
Iteration   1: 4.597 ±(99.9%) 0.009 ms/op
Iteration   2: 4.527 ±(99.9%) 0.026 ms/op
Iteration   3: 4.445 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.523 ±(99.9%) 1.390 ms/op [Average]
  (min, avg, max) = (4.445, 4.523, 4.597), stdev = 0.076
  CI (99.9%): [3.133, 5.913] (assumes normal distribution)


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
# Warmup Iteration   1: 5.637 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.008 ms/op
Iteration   1: 3.706 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  8.995 ms/op
                 createUser·p0.9999: 14.645 ms/op
                 createUser·p1.00:   15.319 ms/op

Iteration   2: 3.591 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  14.004 ms/op
                 createUser·p0.9999: 16.597 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   3: 3.636 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.246 ms/op
                 createUser·p0.999:  9.061 ms/op
                 createUser·p0.9999: 20.290 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263408
  mean =      3.643 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2378 
    [ 2.500,  5.000) = 257348 
    [ 5.000,  7.500) = 2994 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     12.045 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     20.582 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 4.870 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.006 ms/op
Iteration   1: 3.539 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.434 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   5.296 ms/op
                 existUser·p0.999:  8.858 ms/op
                 existUser·p0.9999: 16.022 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   2: 3.503 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  7.943 ms/op
                 existUser·p0.9999: 15.008 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   3: 3.556 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 18.153 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271898
  mean =      3.533 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 3951 
    [ 2.500,  3.750) = 189232 
    [ 3.750,  5.000) = 74841 
    [ 5.000,  6.250) = 2382 
    [ 6.250,  7.500) = 607 
    [ 7.500,  8.750) = 496 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =      8.685 ms/op
     p(99.9900) =     16.565 ms/op
     p(99.9990) =     18.673 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 5.048 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.010 ms/op
Iteration   1: 3.766 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 14.762 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   2: 3.753 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   5.867 ms/op
                 getUser·p0.999:  9.376 ms/op
                 getUser·p0.9999: 16.014 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   3: 3.744 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  9.267 ms/op
                 getUser·p0.9999: 18.907 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255550
  mean =      3.754 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 5201 
    [ 2.500,  3.750) = 133327 
    [ 3.750,  5.000) = 108587 
    [ 5.000,  6.250) = 6249 
    [ 6.250,  7.500) = 1110 
    [ 7.500,  8.750) = 587 
    [ 8.750, 10.000) = 234 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     19.213 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 7.138 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.734 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.668 ±(99.9%) 0.013 ms/op
Iteration   1: 4.678 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  19.005 ms/op
                 listUser·p0.9999: 22.615 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   2: 4.602 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.676 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  18.071 ms/op
                 listUser·p0.9999: 22.713 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.595 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.283 ms/op
                 listUser·p0.99:   7.839 ms/op
                 listUser·p0.999:  17.740 ms/op
                 listUser·p0.9999: 20.074 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207502
  mean =      4.625 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 507 
    [ 2.500,  5.000) = 166650 
    [ 5.000,  7.500) = 36045 
    [ 7.500, 10.000) = 3530 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 168 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.529 ms/op
     p(99.0000) =      8.282 ms/op
     p(99.9000) =     18.301 ms/op
     p(99.9900) =     22.462 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.886 ± 2.989  ops/ms
ClientGrpc.existUser                       thrpt       3   9.258 ± 4.224  ops/ms
ClientGrpc.getUser                         thrpt       3   8.798 ± 2.135  ops/ms
ClientGrpc.listUser                        thrpt       3   6.774 ± 1.377  ops/ms
ClientGrpc.createUser                       avgt       3   3.702 ± 0.692   ms/op
ClientGrpc.existUser                        avgt       3   3.529 ± 1.371   ms/op
ClientGrpc.getUser                          avgt       3   3.668 ± 0.684   ms/op
ClientGrpc.listUser                         avgt       3   4.523 ± 1.390   ms/op
ClientGrpc.createUser                     sample  263408   3.643 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.850           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.292           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.045           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.088           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.742           ms/op
ClientGrpc.existUser                      sample  271898   3.533 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.434           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.685           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.565           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.809           ms/op
ClientGrpc.getUser                        sample  255550   3.754 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.874           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.005           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.388           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.579           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.268           ms/op
ClientGrpc.listUser                       sample  207502   4.625 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.942           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.282           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.301           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.462           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.331           ms/op
