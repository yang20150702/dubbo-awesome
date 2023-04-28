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
# Warmup Iteration   1: 2.429 ops/ms
# Warmup Iteration   2: 6.227 ops/ms
# Warmup Iteration   3: 7.772 ops/ms
Iteration   1: 8.106 ops/ms
Iteration   2: 8.156 ops/ms
Iteration   3: 8.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.166 ±(99.9%) 1.178 ops/ms [Average]
  (min, avg, max) = (8.106, 8.166, 8.234), stdev = 0.065
  CI (99.9%): [6.987, 9.344] (assumes normal distribution)


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
# Warmup Iteration   1: 5.234 ops/ms
# Warmup Iteration   2: 8.155 ops/ms
# Warmup Iteration   3: 8.691 ops/ms
Iteration   1: 9.125 ops/ms
Iteration   2: 9.097 ops/ms
Iteration   3: 8.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.049 ±(99.9%) 1.987 ops/ms [Average]
  (min, avg, max) = (8.924, 9.049, 9.125), stdev = 0.109
  CI (99.9%): [7.062, 11.036] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.285 ops/ms
# Warmup Iteration   2: 7.384 ops/ms
# Warmup Iteration   3: 8.200 ops/ms
Iteration   1: 8.371 ops/ms
Iteration   2: 8.503 ops/ms
Iteration   3: 8.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.498 ±(99.9%) 2.259 ops/ms [Average]
  (min, avg, max) = (8.371, 8.498, 8.619), stdev = 0.124
  CI (99.9%): [6.238, 10.757] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.904 ops/ms
# Warmup Iteration   2: 5.588 ops/ms
# Warmup Iteration   3: 6.158 ops/ms
Iteration   1: 6.337 ops/ms
Iteration   2: 6.491 ops/ms
Iteration   3: 6.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.527 ±(99.9%) 3.846 ops/ms [Average]
  (min, avg, max) = (6.337, 6.527, 6.754), stdev = 0.211
  CI (99.9%): [2.681, 10.373] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.910 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.002 ms/op
Iteration   1: 3.801 ±(99.9%) 0.003 ms/op
Iteration   2: 3.792 ±(99.9%) 0.003 ms/op
Iteration   3: 3.854 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.816 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (3.792, 3.816, 3.854), stdev = 0.033
  CI (99.9%): [3.214, 4.418] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.710 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.003 ms/op
Iteration   1: 3.567 ±(99.9%) 0.003 ms/op
Iteration   2: 3.576 ±(99.9%) 0.003 ms/op
Iteration   3: 3.772 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.638 ±(99.9%) 2.114 ms/op [Average]
  (min, avg, max) = (3.567, 3.638, 3.772), stdev = 0.116
  CI (99.9%): [1.524, 5.753] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.984 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.002 ms/op
Iteration   1: 3.761 ±(99.9%) 0.003 ms/op
Iteration   2: 3.863 ±(99.9%) 0.002 ms/op
Iteration   3: 3.908 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.844 ±(99.9%) 1.378 ms/op [Average]
  (min, avg, max) = (3.761, 3.844, 3.908), stdev = 0.076
  CI (99.9%): [2.466, 5.222] (assumes normal distribution)


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
# Warmup Iteration   1: 7.580 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.316 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.939 ±(99.9%) 0.011 ms/op
Iteration   1: 4.957 ±(99.9%) 0.012 ms/op
Iteration   2: 5.044 ±(99.9%) 0.022 ms/op
Iteration   3: 5.020 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.007 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (4.957, 5.007, 5.044), stdev = 0.045
  CI (99.9%): [4.190, 5.824] (assumes normal distribution)


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
# Warmup Iteration   1: 6.232 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.011 ms/op
Iteration   1: 3.816 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  9.579 ms/op
                 createUser·p0.9999: 15.896 ms/op
                 createUser·p1.00:   16.286 ms/op

Iteration   2: 3.934 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  9.957 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   3: 3.888 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  18.145 ms/op
                 createUser·p0.9999: 33.802 ms/op
                 createUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 247325
  mean =      3.879 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7089 
    [ 2.500,  5.000) = 223376 
    [ 5.000,  7.500) = 15559 
    [ 7.500, 10.000) = 973 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     11.393 ms/op
     p(99.9900) =     32.401 ms/op
     p(99.9990) =     34.410 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 5.003 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.010 ms/op
Iteration   1: 3.516 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  9.159 ms/op
                 existUser·p0.9999: 16.515 ms/op
                 existUser·p1.00:   17.760 ms/op

Iteration   2: 3.577 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  10.883 ms/op
                 existUser·p0.9999: 17.307 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   3: 3.564 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  11.264 ms/op
                 existUser·p0.9999: 26.215 ms/op
                 existUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270127
  mean =      3.552 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13568 
    [ 2.500,  5.000) = 248713 
    [ 5.000,  7.500) = 6897 
    [ 7.500, 10.000) = 610 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     25.788 ms/op
     p(99.9990) =     26.421 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 5.736 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.009 ms/op
Iteration   1: 3.908 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   6.641 ms/op
                 getUser·p0.999:  17.105 ms/op
                 getUser·p0.9999: 26.372 ms/op
                 getUser·p1.00:   31.031 ms/op

Iteration   2: 3.910 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  9.526 ms/op
                 getUser·p0.9999: 31.419 ms/op
                 getUser·p1.00:   31.588 ms/op

Iteration   3: 3.931 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.760 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   6.287 ms/op
                 getUser·p0.999:  13.624 ms/op
                 getUser·p0.9999: 30.961 ms/op
                 getUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 244978
  mean =      3.916 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4310 
    [ 2.500,  5.000) = 224049 
    [ 5.000,  7.500) = 15322 
    [ 7.500, 10.000) = 909 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     12.062 ms/op
     p(99.9900) =     30.999 ms/op
     p(99.9990) =     31.541 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 7.230 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.623 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.188 ±(99.9%) 0.018 ms/op
Iteration   1: 5.198 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   6.685 ms/op
                 listUser·p0.95:   7.700 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 18.237 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   2: 4.949 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   6.472 ms/op
                 listUser·p0.95:   7.356 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 19.273 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 5.170 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   6.586 ms/op
                 listUser·p0.95:   7.578 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  20.162 ms/op
                 listUser·p0.9999: 31.832 ms/op
                 listUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 188049
  mean =      5.103 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 301 
    [ 2.500,  5.000) = 103877 
    [ 5.000,  7.500) = 74106 
    [ 7.500, 10.000) = 8355 
    [10.000, 12.500) = 954 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.545 ms/op
     p(99.0000) =      9.552 ms/op
     p(99.9000) =     16.563 ms/op
     p(99.9900) =     31.142 ms/op
     p(99.9990) =     32.747 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.166 ± 1.178  ops/ms
ClientGrpc.existUser                       thrpt       3   9.049 ± 1.987  ops/ms
ClientGrpc.getUser                         thrpt       3   8.498 ± 2.259  ops/ms
ClientGrpc.listUser                        thrpt       3   6.527 ± 3.846  ops/ms
ClientGrpc.createUser                       avgt       3   3.816 ± 0.602   ms/op
ClientGrpc.existUser                        avgt       3   3.638 ± 2.114   ms/op
ClientGrpc.getUser                          avgt       3   3.844 ± 1.378   ms/op
ClientGrpc.listUser                         avgt       3   5.007 ± 0.817   ms/op
ClientGrpc.createUser                     sample  247325   3.879 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.952           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.161           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.308           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.393           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.401           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.603           ms/op
ClientGrpc.existUser                      sample  270127   3.552 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.562           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.661           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.792           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.764           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.788           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.706           ms/op
ClientGrpc.getUser                        sample  244978   3.916 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.106           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.177           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.439           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.062           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.999           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.588           ms/op
ClientGrpc.listUser                       sample  188049   5.103 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.223           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.545           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.552           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.563           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.142           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.834           ms/op
