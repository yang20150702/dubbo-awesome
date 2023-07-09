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
# Warmup Iteration   1: 4.938 ops/ms
# Warmup Iteration   2: 9.080 ops/ms
# Warmup Iteration   3: 10.220 ops/ms
Iteration   1: 10.892 ops/ms
Iteration   2: 10.756 ops/ms
Iteration   3: 10.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.875 ±(99.9%) 2.026 ops/ms [Average]
  (min, avg, max) = (10.756, 10.875, 10.976), stdev = 0.111
  CI (99.9%): [8.849, 12.901] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.303 ops/ms
# Warmup Iteration   2: 10.826 ops/ms
# Warmup Iteration   3: 11.172 ops/ms
Iteration   1: 10.931 ops/ms
Iteration   2: 11.651 ops/ms
Iteration   3: 11.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.322 ±(99.9%) 6.641 ops/ms [Average]
  (min, avg, max) = (10.931, 11.322, 11.651), stdev = 0.364
  CI (99.9%): [4.682, 17.963] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.615 ops/ms
# Warmup Iteration   2: 10.438 ops/ms
# Warmup Iteration   3: 10.951 ops/ms
Iteration   1: 10.805 ops/ms
Iteration   2: 10.804 ops/ms
Iteration   3: 10.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.818 ±(99.9%) 0.410 ops/ms [Average]
  (min, avg, max) = (10.804, 10.818, 10.844), stdev = 0.022
  CI (99.9%): [10.408, 11.228] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.797 ops/ms
# Warmup Iteration   2: 8.249 ops/ms
# Warmup Iteration   3: 8.221 ops/ms
Iteration   1: 8.475 ops/ms
Iteration   2: 8.430 ops/ms
Iteration   3: 8.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.435 ±(99.9%) 0.696 ops/ms [Average]
  (min, avg, max) = (8.399, 8.435, 8.475), stdev = 0.038
  CI (99.9%): [7.739, 9.130] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.075 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.004 ms/op
Iteration   1: 2.991 ±(99.9%) 0.003 ms/op
Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
Iteration   3: 3.028 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.994 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (2.963, 2.994, 3.028), stdev = 0.033
  CI (99.9%): [2.400, 3.588] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.805 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.865 ±(99.9%) 0.004 ms/op
Iteration   1: 2.914 ±(99.9%) 0.003 ms/op
Iteration   2: 2.882 ±(99.9%) 0.003 ms/op
Iteration   3: 2.896 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.897 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (2.882, 2.897, 2.914), stdev = 0.016
  CI (99.9%): [2.602, 3.192] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.621 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.002 ms/op
Iteration   1: 2.887 ±(99.9%) 0.004 ms/op
Iteration   2: 2.974 ±(99.9%) 0.003 ms/op
Iteration   3: 2.960 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.940 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (2.887, 2.940, 2.974), stdev = 0.047
  CI (99.9%): [2.083, 3.797] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.202 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.035 ms/op
Iteration   1: 3.852 ±(99.9%) 0.053 ms/op
Iteration   2: 3.925 ±(99.9%) 0.007 ms/op
Iteration   3: 3.882 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.886 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (3.852, 3.886, 3.925), stdev = 0.037
  CI (99.9%): [3.216, 4.557] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.663 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  6.480 ms/op
                 createUser·p0.9999: 11.764 ms/op
                 createUser·p1.00:   11.993 ms/op

Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.612 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  9.136 ms/op
                 createUser·p0.9999: 17.072 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.607 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.332 ms/op
                 createUser·p0.9999: 25.323 ms/op
                 createUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320004
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29365 
    [ 2.500,  5.000) = 289276 
    [ 5.000,  7.500) = 983 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.750 ms/op
     p(99.9900) =     24.443 ms/op
     p(99.9990) =     25.520 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.762 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.847 ±(99.9%) 0.006 ms/op
Iteration   1: 2.926 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.384 ms/op
                 existUser·p0.999:  5.960 ms/op
                 existUser·p0.9999: 11.816 ms/op
                 existUser·p1.00:   12.108 ms/op

Iteration   2: 2.866 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  6.287 ms/op
                 existUser·p0.9999: 13.577 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   3: 2.875 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.489 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  10.219 ms/op
                 existUser·p0.9999: 14.514 ms/op
                 existUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332113
  mean =      2.889 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1968 
    [ 1.250,  2.500) = 44418 
    [ 2.500,  3.750) = 273119 
    [ 3.750,  5.000) = 11602 
    [ 5.000,  6.250) = 566 
    [ 6.250,  7.500) = 125 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.183 ms/op
     p(99.9900) =     13.644 ms/op
     p(99.9990) =     14.795 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.912 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.010 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.830 ms/op
                 getUser·p0.9999: 20.445 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   2: 2.991 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.357 ms/op
                 getUser·p0.9999: 12.855 ms/op
                 getUser·p1.00:   13.287 ms/op

Iteration   3: 2.986 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.651 ms/op
                 getUser·p0.9999: 21.604 ms/op
                 getUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319478
  mean =      3.004 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30892 
    [ 2.500,  5.000) = 287526 
    [ 5.000,  7.500) = 812 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      6.857 ms/op
     p(99.9900) =     20.908 ms/op
     p(99.9990) =     23.030 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 5.183 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.011 ms/op
Iteration   1: 3.840 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  12.075 ms/op
                 listUser·p0.9999: 14.150 ms/op
                 listUser·p1.00:   15.041 ms/op

Iteration   2: 3.735 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.351 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  12.981 ms/op
                 listUser·p0.9999: 14.418 ms/op
                 listUser·p1.00:   14.598 ms/op

Iteration   3: 3.836 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  16.556 ms/op
                 listUser·p0.9999: 20.041 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252483
  mean =      3.803 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6385 
    [ 2.500,  5.000) = 227040 
    [ 5.000,  7.500) = 17898 
    [ 7.500, 10.000) = 616 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.345 ms/op
     p(99.9900) =     18.899 ms/op
     p(99.9990) =     21.425 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.875 ± 2.026  ops/ms
ClientGrpc.existUser                       thrpt       3  11.322 ± 6.641  ops/ms
ClientGrpc.getUser                         thrpt       3  10.818 ± 0.410  ops/ms
ClientGrpc.listUser                        thrpt       3   8.435 ± 0.696  ops/ms
ClientGrpc.createUser                       avgt       3   2.994 ± 0.594   ms/op
ClientGrpc.existUser                        avgt       3   2.897 ± 0.295   ms/op
ClientGrpc.getUser                          avgt       3   2.940 ± 0.857   ms/op
ClientGrpc.listUser                         avgt       3   3.886 ± 0.670   ms/op
ClientGrpc.createUser                     sample  320004   3.001 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.561           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.750           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.443           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.625           ms/op
ClientGrpc.existUser                      sample  332113   2.889 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.489           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.183           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.644           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.942           ms/op
ClientGrpc.getUser                        sample  319478   3.004 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.592           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.857           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.908           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.527           ms/op
ClientGrpc.listUser                       sample  252483   3.803 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.351           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.674           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.345           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.899           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.594           ms/op
