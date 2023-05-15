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
# Warmup Iteration   1: 4.724 ops/ms
# Warmup Iteration   2: 9.222 ops/ms
# Warmup Iteration   3: 10.277 ops/ms
Iteration   1: 10.513 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.578 ±(99.9%) 1.045 ops/ms [Average]
  (min, avg, max) = (10.513, 10.578, 10.621), stdev = 0.057
  CI (99.9%): [9.533, 11.623] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.117 ops/ms
# Warmup Iteration   2: 10.603 ops/ms
# Warmup Iteration   3: 10.993 ops/ms
Iteration   1: 11.123 ops/ms
Iteration   2: 11.005 ops/ms
Iteration   3: 11.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.138 ±(99.9%) 2.580 ops/ms [Average]
  (min, avg, max) = (11.005, 11.138, 11.286), stdev = 0.141
  CI (99.9%): [8.558, 13.718] (assumes normal distribution)


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
# Warmup Iteration   1: 7.401 ops/ms
# Warmup Iteration   2: 10.307 ops/ms
# Warmup Iteration   3: 10.564 ops/ms
Iteration   1: 10.666 ops/ms
Iteration   2: 10.693 ops/ms
Iteration   3: 10.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.751 ±(99.9%) 2.259 ops/ms [Average]
  (min, avg, max) = (10.666, 10.751, 10.893), stdev = 0.124
  CI (99.9%): [8.492, 13.010] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.645 ops/ms
# Warmup Iteration   2: 7.907 ops/ms
# Warmup Iteration   3: 8.101 ops/ms
Iteration   1: 8.161 ops/ms
Iteration   2: 8.194 ops/ms
Iteration   3: 8.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.244 ±(99.9%) 2.111 ops/ms [Average]
  (min, avg, max) = (8.161, 8.244, 8.376), stdev = 0.116
  CI (99.9%): [6.133, 10.354] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.149 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.003 ms/op
Iteration   1: 3.012 ±(99.9%) 0.003 ms/op
Iteration   2: 3.009 ±(99.9%) 0.002 ms/op
Iteration   3: 2.970 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.997 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (2.970, 2.997, 3.012), stdev = 0.024
  CI (99.9%): [2.564, 3.430] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.087 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.871 ±(99.9%) 0.003 ms/op
Iteration   1: 2.888 ±(99.9%) 0.003 ms/op
Iteration   2: 2.856 ±(99.9%) 0.003 ms/op
Iteration   3: 2.796 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.847 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (2.796, 2.847, 2.888), stdev = 0.047
  CI (99.9%): [1.993, 3.700] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.003 ms/op
Iteration   1: 2.986 ±(99.9%) 0.003 ms/op
Iteration   2: 3.007 ±(99.9%) 0.002 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.002 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (2.986, 3.002, 3.013), stdev = 0.014
  CI (99.9%): [2.742, 3.262] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.253 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.013 ms/op
Iteration   1: 3.902 ±(99.9%) 0.040 ms/op
Iteration   2: 3.856 ±(99.9%) 0.016 ms/op
Iteration   3: 3.828 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.862 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (3.828, 3.862, 3.902), stdev = 0.037
  CI (99.9%): [3.182, 4.542] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.222 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  8.654 ms/op
                 createUser·p0.9999: 12.754 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  7.299 ms/op
                 createUser·p0.9999: 14.374 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.348 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  9.445 ms/op
                 createUser·p0.9999: 15.286 ms/op
                 createUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320183
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1502 
    [ 1.250,  2.500) = 29664 
    [ 2.500,  3.750) = 270259 
    [ 3.750,  5.000) = 17054 
    [ 5.000,  6.250) = 899 
    [ 6.250,  7.500) = 382 
    [ 7.500,  8.750) = 131 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.348 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.435 ms/op
     p(99.9900) =     14.926 ms/op
     p(99.9990) =     15.476 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.684 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.986 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
Iteration   1: 2.901 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  8.066 ms/op
                 existUser·p0.9999: 13.139 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   2: 2.881 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  6.619 ms/op
                 existUser·p0.9999: 23.101 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   3: 2.874 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  9.601 ms/op
                 existUser·p0.9999: 27.160 ms/op
                 existUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332595
  mean =      2.885 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38781 
    [ 2.500,  5.000) = 292619 
    [ 5.000,  7.500) = 854 
    [ 7.500, 10.000) = 113 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.622 ms/op
     p(99.9900) =     24.595 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
Iteration   1: 3.020 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.045 ms/op
                 getUser·p0.9999: 12.449 ms/op
                 getUser·p1.00:   12.665 ms/op

Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.544 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  6.845 ms/op
                 getUser·p0.9999: 15.862 ms/op
                 getUser·p1.00:   16.695 ms/op

Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.673 ms/op
                 getUser·p0.9999: 15.368 ms/op
                 getUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319369
  mean =      3.005 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1707 
    [ 1.250,  2.500) = 22265 
    [ 2.500,  3.750) = 280875 
    [ 3.750,  5.000) = 13356 
    [ 5.000,  6.250) = 541 
    [ 6.250,  7.500) = 291 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 73 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.717 ms/op
     p(99.9900) =     15.615 ms/op
     p(99.9990) =     16.080 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 4.496 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.011 ms/op
Iteration   1: 3.885 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.265 ms/op
                 listUser·p0.9999: 14.562 ms/op
                 listUser·p1.00:   15.155 ms/op

Iteration   2: 3.969 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  17.480 ms/op
                 listUser·p0.9999: 24.345 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   3: 3.931 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  18.939 ms/op
                 listUser·p0.9999: 24.795 ms/op
                 listUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244411
  mean =      3.928 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5334 
    [ 2.500,  5.000) = 213525 
    [ 5.000,  7.500) = 24297 
    [ 7.500, 10.000) = 782 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     24.037 ms/op
     p(99.9990) =     25.202 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.578 ± 1.045  ops/ms
ClientGrpc.existUser                       thrpt       3  11.138 ± 2.580  ops/ms
ClientGrpc.getUser                         thrpt       3  10.751 ± 2.259  ops/ms
ClientGrpc.listUser                        thrpt       3   8.244 ± 2.111  ops/ms
ClientGrpc.createUser                       avgt       3   2.997 ± 0.433   ms/op
ClientGrpc.existUser                        avgt       3   2.847 ± 0.853   ms/op
ClientGrpc.getUser                          avgt       3   3.002 ± 0.260   ms/op
ClientGrpc.listUser                         avgt       3   3.862 ± 0.680   ms/op
ClientGrpc.createUser                     sample  320183   2.998 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.348           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.435           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.926           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.007           ms/op
ClientGrpc.existUser                      sample  332595   2.885 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.592           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.334           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.622           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.595           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.329           ms/op
ClientGrpc.getUser                        sample  319369   3.005 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.544           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.717           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.615           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.695           ms/op
ClientGrpc.listUser                       sample  244411   3.928 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.850           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.893           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.037           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.330           ms/op
