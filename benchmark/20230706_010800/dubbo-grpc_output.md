# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.951 ops/ms
# Warmup Iteration   2: 6.638 ops/ms
# Warmup Iteration   3: 7.798 ops/ms
Iteration   1: 8.556 ops/ms
Iteration   2: 8.571 ops/ms
Iteration   3: 8.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.588 ±(99.9%) 0.804 ops/ms [Average]
  (min, avg, max) = (8.556, 8.588, 8.639), stdev = 0.044
  CI (99.9%): [7.784, 9.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.254 ops/ms
# Warmup Iteration   2: 8.532 ops/ms
# Warmup Iteration   3: 9.096 ops/ms
Iteration   1: 9.103 ops/ms
Iteration   2: 9.134 ops/ms
Iteration   3: 9.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.135 ±(99.9%) 0.595 ops/ms [Average]
  (min, avg, max) = (9.103, 9.135, 9.168), stdev = 0.033
  CI (99.9%): [8.540, 9.730] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.548 ops/ms
# Warmup Iteration   2: 8.071 ops/ms
# Warmup Iteration   3: 8.344 ops/ms
Iteration   1: 8.564 ops/ms
Iteration   2: 8.665 ops/ms
Iteration   3: 8.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.622 ±(99.9%) 0.952 ops/ms [Average]
  (min, avg, max) = (8.564, 8.622, 8.665), stdev = 0.052
  CI (99.9%): [7.670, 9.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.014 ops/ms
# Warmup Iteration   2: 6.326 ops/ms
# Warmup Iteration   3: 6.591 ops/ms
Iteration   1: 6.637 ops/ms
Iteration   2: 6.852 ops/ms
Iteration   3: 6.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.738 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (6.637, 6.738, 6.852), stdev = 0.108
  CI (99.9%): [4.765, 8.711] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.422 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.010 ms/op
Iteration   1: 3.647 ±(99.9%) 0.003 ms/op
Iteration   2: 3.626 ±(99.9%) 0.003 ms/op
Iteration   3: 3.593 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.622 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.593, 3.622, 3.647), stdev = 0.027
  CI (99.9%): [3.125, 4.118] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.369 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.003 ms/op
Iteration   1: 3.505 ±(99.9%) 0.003 ms/op
Iteration   2: 3.566 ±(99.9%) 0.002 ms/op
Iteration   3: 3.380 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.484 ±(99.9%) 1.729 ms/op [Average]
  (min, avg, max) = (3.380, 3.484, 3.566), stdev = 0.095
  CI (99.9%): [1.755, 5.212] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.494 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.004 ms/op
Iteration   1: 3.666 ±(99.9%) 0.003 ms/op
Iteration   2: 3.633 ±(99.9%) 0.004 ms/op
Iteration   3: 3.650 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.650 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (3.633, 3.650, 3.666), stdev = 0.016
  CI (99.9%): [3.354, 3.945] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.997 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.074 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.712 ±(99.9%) 0.013 ms/op
Iteration   1: 4.862 ±(99.9%) 0.022 ms/op
Iteration   2: 4.794 ±(99.9%) 0.022 ms/op
Iteration   3: 4.728 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.795 ±(99.9%) 1.221 ms/op [Average]
  (min, avg, max) = (4.728, 4.795, 4.862), stdev = 0.067
  CI (99.9%): [3.573, 6.016] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.384 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.009 ms/op
Iteration   1: 3.654 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  12.494 ms/op
                 createUser·p0.9999: 15.093 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 3.740 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.482 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  9.773 ms/op
                 createUser·p0.9999: 15.136 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   3: 3.673 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  19.294 ms/op
                 createUser·p0.9999: 22.488 ms/op
                 createUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260386
  mean =      3.689 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6639 
    [ 2.500,  5.000) = 247046 
    [ 5.000,  7.500) = 5666 
    [ 7.500, 10.000) = 655 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     12.390 ms/op
     p(99.9900) =     21.986 ms/op
     p(99.9990) =     22.800 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.996 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.008 ms/op
Iteration   1: 3.582 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  7.927 ms/op
                 existUser·p0.9999: 14.926 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   2: 3.579 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.466 ms/op
                 existUser·p0.999:  7.610 ms/op
                 existUser·p0.9999: 24.938 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 3.559 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  12.059 ms/op
                 existUser·p0.9999: 21.430 ms/op
                 existUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268729
  mean =      3.573 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6628 
    [ 2.500,  5.000) = 256685 
    [ 5.000,  7.500) = 4874 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     10.879 ms/op
     p(99.9900) =     23.155 ms/op
     p(99.9990) =     25.197 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.540 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.008 ms/op
Iteration   1: 3.747 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  10.768 ms/op
                 getUser·p0.9999: 23.953 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   2: 3.757 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   5.853 ms/op
                 getUser·p0.999:  10.304 ms/op
                 getUser·p0.9999: 15.867 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   3: 3.667 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  12.049 ms/op
                 getUser·p0.9999: 28.141 ms/op
                 getUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257902
  mean =      3.723 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4194 
    [ 2.500,  5.000) = 245679 
    [ 5.000,  7.500) = 7167 
    [ 7.500, 10.000) = 503 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     11.456 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     28.498 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.599 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.047 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.861 ±(99.9%) 0.015 ms/op
Iteration   1: 4.820 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.808 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  16.695 ms/op
                 listUser·p0.9999: 28.192 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   2: 4.901 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.210 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  17.362 ms/op
                 listUser·p0.9999: 23.082 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.788 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  20.191 ms/op
                 listUser·p0.9999: 29.332 ms/op
                 listUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198651
  mean =      4.836 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 220 
    [ 2.500,  5.000) = 144400 
    [ 5.000,  7.500) = 48478 
    [ 7.500, 10.000) = 4768 
    [10.000, 12.500) = 377 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.832 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     28.545 ms/op
     p(99.9990) =     30.739 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.588 ± 0.804  ops/ms
ClientGrpc.existUser                       thrpt       3   9.135 ± 0.595  ops/ms
ClientGrpc.getUser                         thrpt       3   8.622 ± 0.952  ops/ms
ClientGrpc.listUser                        thrpt       3   6.738 ± 1.973  ops/ms
ClientGrpc.createUser                       avgt       3   3.622 ± 0.496   ms/op
ClientGrpc.existUser                        avgt       3   3.484 ± 1.729   ms/op
ClientGrpc.getUser                          avgt       3   3.650 ± 0.296   ms/op
ClientGrpc.listUser                         avgt       3   4.795 ± 1.221   ms/op
ClientGrpc.createUser                     sample  260386   3.689 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.482           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.759           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.390           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.986           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.003           ms/op
ClientGrpc.existUser                      sample  268729   3.573 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.797           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.879           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.155           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.345           ms/op
ClientGrpc.getUser                        sample  257902   3.723 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.909           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.898           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.456           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.804           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.770           ms/op
ClientGrpc.listUser                       sample  198651   4.836 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.928           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.634           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.121           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.545           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.933           ms/op
