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
# Warmup Iteration   1: 1.902 ops/ms
# Warmup Iteration   2: 4.890 ops/ms
# Warmup Iteration   3: 6.418 ops/ms
Iteration   1: 6.631 ops/ms
Iteration   2: 6.690 ops/ms
Iteration   3: 6.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.694 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (6.631, 6.694, 6.762), stdev = 0.066
  CI (99.9%): [5.494, 7.894] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.230 ops/ms
# Warmup Iteration   2: 6.854 ops/ms
# Warmup Iteration   3: 7.116 ops/ms
Iteration   1: 7.008 ops/ms
Iteration   2: 6.877 ops/ms
Iteration   3: 7.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.001 ±(99.9%) 2.214 ops/ms [Average]
  (min, avg, max) = (6.877, 7.001, 7.119), stdev = 0.121
  CI (99.9%): [4.787, 9.215] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ops/ms
# Warmup Iteration   2: 6.320 ops/ms
# Warmup Iteration   3: 6.657 ops/ms
Iteration   1: 6.837 ops/ms
Iteration   2: 6.863 ops/ms
Iteration   3: 6.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.867 ±(99.9%) 0.562 ops/ms [Average]
  (min, avg, max) = (6.837, 6.867, 6.899), stdev = 0.031
  CI (99.9%): [6.305, 7.428] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.472 ops/ms
# Warmup Iteration   2: 4.905 ops/ms
# Warmup Iteration   3: 5.363 ops/ms
Iteration   1: 5.420 ops/ms
Iteration   2: 5.446 ops/ms
Iteration   3: 5.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.339 ±(99.9%) 2.982 ops/ms [Average]
  (min, avg, max) = (5.151, 5.339, 5.446), stdev = 0.163
  CI (99.9%): [2.357, 8.322] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.030 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.158 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.834 ±(99.9%) 0.013 ms/op
Iteration   1: 4.702 ±(99.9%) 0.004 ms/op
Iteration   2: 4.706 ±(99.9%) 0.005 ms/op
Iteration   3: 4.681 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.696 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (4.681, 4.696, 4.706), stdev = 0.014
  CI (99.9%): [4.448, 4.945] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.782 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.805 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.459 ±(99.9%) 0.007 ms/op
Iteration   1: 4.318 ±(99.9%) 0.005 ms/op
Iteration   2: 4.334 ±(99.9%) 0.004 ms/op
Iteration   3: 4.410 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.354 ±(99.9%) 0.892 ms/op [Average]
  (min, avg, max) = (4.318, 4.354, 4.410), stdev = 0.049
  CI (99.9%): [3.462, 5.246] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.098 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.059 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.760 ±(99.9%) 0.005 ms/op
Iteration   1: 4.607 ±(99.9%) 0.013 ms/op
Iteration   2: 4.638 ±(99.9%) 0.004 ms/op
Iteration   3: 4.630 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.625 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (4.607, 4.625, 4.638), stdev = 0.016
  CI (99.9%): [4.329, 4.921] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.877 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 6.672 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 6.042 ±(99.9%) 0.011 ms/op
Iteration   1: 5.986 ±(99.9%) 0.012 ms/op
Iteration   2: 6.052 ±(99.9%) 0.027 ms/op
Iteration   3: 6.017 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.018 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (5.986, 6.018, 6.052), stdev = 0.033
  CI (99.9%): [5.415, 6.622] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.370 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 5.044 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.706 ±(99.9%) 0.015 ms/op
Iteration   1: 4.646 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.988 ms/op
                 createUser·p0.95:   6.783 ms/op
                 createUser·p0.99:   9.044 ms/op
                 createUser·p0.999:  13.748 ms/op
                 createUser·p0.9999: 35.142 ms/op
                 createUser·p1.00:   35.389 ms/op

Iteration   2: 4.611 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.890 ms/op
                 createUser·p0.95:   6.521 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  14.439 ms/op
                 createUser·p0.9999: 33.002 ms/op
                 createUser·p1.00:   33.423 ms/op

Iteration   3: 4.604 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   6.005 ms/op
                 createUser·p0.95:   6.791 ms/op
                 createUser·p0.99:   9.552 ms/op
                 createUser·p0.999:  15.737 ms/op
                 createUser·p0.9999: 38.542 ms/op
                 createUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 207703
  mean =      4.620 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6072 
    [ 2.500,  5.000) = 143840 
    [ 5.000,  7.500) = 52031 
    [ 7.500, 10.000) = 4499 
    [10.000, 12.500) = 805 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.964 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     35.826 ms/op
     p(99.9990) =     38.989 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.610 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.956 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.429 ±(99.9%) 0.014 ms/op
Iteration   1: 4.448 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.702 ms/op
                 existUser·p0.95:   6.316 ms/op
                 existUser·p0.99:   8.176 ms/op
                 existUser·p0.999:  16.728 ms/op
                 existUser·p0.9999: 19.005 ms/op
                 existUser·p1.00:   19.038 ms/op

Iteration   2: 4.503 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   4.309 ms/op
                 existUser·p0.90:   5.734 ms/op
                 existUser·p0.95:   6.357 ms/op
                 existUser·p0.99:   8.339 ms/op
                 existUser·p0.999:  11.974 ms/op
                 existUser·p0.9999: 24.179 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   3: 4.363 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   5.472 ms/op
                 existUser·p0.95:   6.242 ms/op
                 existUser·p0.99:   8.700 ms/op
                 existUser·p0.999:  13.578 ms/op
                 existUser·p0.9999: 22.097 ms/op
                 existUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 216350
  mean =      4.437 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5198 
    [ 2.500,  5.000) = 165598 
    [ 5.000,  7.500) = 41394 
    [ 7.500, 10.000) = 3380 
    [10.000, 12.500) = 464 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.652 ms/op
     p(95.0000) =      6.308 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     14.658 ms/op
     p(99.9900) =     22.318 ms/op
     p(99.9990) =     24.609 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.690 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.961 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.779 ±(99.9%) 0.017 ms/op
Iteration   1: 4.665 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   4.481 ms/op
                 getUser·p0.90:   5.988 ms/op
                 getUser·p0.95:   6.693 ms/op
                 getUser·p0.99:   8.733 ms/op
                 getUser·p0.999:  13.459 ms/op
                 getUser·p0.9999: 17.933 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   2: 4.694 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   4.497 ms/op
                 getUser·p0.90:   5.890 ms/op
                 getUser·p0.95:   6.676 ms/op
                 getUser·p0.99:   8.946 ms/op
                 getUser·p0.999:  12.976 ms/op
                 getUser·p0.9999: 20.650 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   3: 4.487 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.693 ms/op
                 getUser·p0.95:   6.365 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  13.500 ms/op
                 getUser·p0.9999: 24.990 ms/op
                 getUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 208139
  mean =      4.613 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4383 
    [ 2.500,  5.000) = 149360 
    [ 5.000,  7.500) = 49379 
    [ 7.500, 10.000) = 4050 
    [10.000, 12.500) = 678 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     21.600 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.288 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.796 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.062 ±(99.9%) 0.025 ms/op
Iteration   1: 6.071 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   8.126 ms/op
                 listUser·p0.95:   9.289 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  29.106 ms/op
                 listUser·p0.9999: 31.075 ms/op
                 listUser·p1.00:   31.588 ms/op

Iteration   2: 5.957 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   7.832 ms/op
                 listUser·p0.95:   8.864 ms/op
                 listUser·p0.99:   11.928 ms/op
                 listUser·p0.999:  19.224 ms/op
                 listUser·p0.9999: 24.102 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   3: 6.089 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   8.069 ms/op
                 listUser·p0.95:   9.110 ms/op
                 listUser·p0.99:   12.534 ms/op
                 listUser·p0.999:  25.490 ms/op
                 listUser·p0.9999: 39.534 ms/op
                 listUser·p1.00:   45.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 158951
  mean =      6.038 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 37381 
    [ 5.000, 10.000) = 116846 
    [10.000, 15.000) = 4269 
    [15.000, 20.000) = 230 
    [20.000, 25.000) = 102 
    [25.000, 30.000) = 63 
    [30.000, 35.000) = 28 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      5.652 ms/op
     p(90.0000) =      8.004 ms/op
     p(95.0000) =      9.093 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     22.249 ms/op
     p(99.9900) =     37.714 ms/op
     p(99.9990) =     45.516 ms/op
     p(99.9999) =     45.941 ms/op
    p(100.0000) =     45.941 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.694 ± 1.200  ops/ms
ClientGrpc.existUser                       thrpt       3   7.001 ± 2.214  ops/ms
ClientGrpc.getUser                         thrpt       3   6.867 ± 0.562  ops/ms
ClientGrpc.listUser                        thrpt       3   5.339 ± 2.982  ops/ms
ClientGrpc.createUser                       avgt       3   4.696 ± 0.249   ms/op
ClientGrpc.existUser                        avgt       3   4.354 ± 0.892   ms/op
ClientGrpc.getUser                          avgt       3   4.625 ± 0.296   ms/op
ClientGrpc.listUser                         avgt       3   6.018 ± 0.604   ms/op
ClientGrpc.createUser                     sample  207703   4.620 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.884           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.964           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.693           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.110           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.942           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.826           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          39.059           ms/op
ClientGrpc.existUser                      sample  216350   4.437 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.949           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.652           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.308           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.438           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.658           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.318           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.838           ms/op
ClientGrpc.getUser                        sample  208139   4.613 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.769           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.857           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.570           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.749           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.353           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.600           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.723           ms/op
ClientGrpc.listUser                       sample  158951   6.038 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.824           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.004           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.093           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.075           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.249           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          37.714           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          45.941           ms/op
