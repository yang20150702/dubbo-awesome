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
# Warmup Iteration   1: 4.642 ops/ms
# Warmup Iteration   2: 9.007 ops/ms
# Warmup Iteration   3: 10.346 ops/ms
Iteration   1: 10.477 ops/ms
Iteration   2: 10.342 ops/ms
Iteration   3: 10.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.436 ±(99.9%) 1.487 ops/ms [Average]
  (min, avg, max) = (10.342, 10.436, 10.488), stdev = 0.081
  CI (99.9%): [8.949, 11.922] (assumes normal distribution)


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
# Warmup Iteration   1: 7.803 ops/ms
# Warmup Iteration   2: 10.719 ops/ms
# Warmup Iteration   3: 11.020 ops/ms
Iteration   1: 11.168 ops/ms
Iteration   2: 11.101 ops/ms
Iteration   3: 11.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.158 ±(99.9%) 0.958 ops/ms [Average]
  (min, avg, max) = (11.101, 11.158, 11.204), stdev = 0.053
  CI (99.9%): [10.200, 12.116] (assumes normal distribution)


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
# Warmup Iteration   1: 7.495 ops/ms
# Warmup Iteration   2: 10.254 ops/ms
# Warmup Iteration   3: 10.685 ops/ms
Iteration   1: 10.813 ops/ms
Iteration   2: 10.701 ops/ms
Iteration   3: 10.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.787 ±(99.9%) 1.386 ops/ms [Average]
  (min, avg, max) = (10.701, 10.787, 10.846), stdev = 0.076
  CI (99.9%): [9.401, 12.173] (assumes normal distribution)


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
# Warmup Iteration   1: 6.607 ops/ms
# Warmup Iteration   2: 7.747 ops/ms
# Warmup Iteration   3: 8.238 ops/ms
Iteration   1: 8.202 ops/ms
Iteration   2: 8.072 ops/ms
Iteration   3: 8.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.100 ±(99.9%) 1.670 ops/ms [Average]
  (min, avg, max) = (8.026, 8.100, 8.202), stdev = 0.092
  CI (99.9%): [6.430, 9.770] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.240 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.004 ms/op
Iteration   1: 3.003 ±(99.9%) 0.010 ms/op
Iteration   2: 2.962 ±(99.9%) 0.003 ms/op
Iteration   3: 3.024 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.997 ±(99.9%) 0.573 ms/op [Average]
  (min, avg, max) = (2.962, 2.997, 3.024), stdev = 0.031
  CI (99.9%): [2.424, 3.569] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.737 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.825 ±(99.9%) 0.004 ms/op
Iteration   1: 2.883 ±(99.9%) 0.003 ms/op
Iteration   2: 2.852 ±(99.9%) 0.003 ms/op
Iteration   3: 2.847 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.861 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (2.847, 2.861, 2.883), stdev = 0.019
  CI (99.9%): [2.505, 3.216] (assumes normal distribution)


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
# Warmup Iteration   1: 4.222 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.002 ms/op
Iteration   1: 2.969 ±(99.9%) 0.002 ms/op
Iteration   2: 2.896 ±(99.9%) 0.002 ms/op
Iteration   3: 2.913 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.926 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (2.896, 2.926, 2.969), stdev = 0.038
  CI (99.9%): [2.230, 3.623] (assumes normal distribution)


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
# Warmup Iteration   1: 5.238 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.006 ms/op
Iteration   1: 3.894 ±(99.9%) 0.023 ms/op
Iteration   2: 3.907 ±(99.9%) 0.022 ms/op
Iteration   3: 3.845 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.882 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (3.845, 3.882, 3.907), stdev = 0.033
  CI (99.9%): [3.285, 4.480] (assumes normal distribution)


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  5.898 ms/op
                 createUser·p0.9999: 18.842 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   2: 2.925 ±(99.9%) 0.004 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.256 ms/op
                 createUser·p0.95:   3.346 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.230 ms/op
                 createUser·p0.9999: 13.814 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   3: 2.937 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  12.782 ms/op
                 createUser·p0.9999: 18.525 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326027
  mean =      2.944 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32422 
    [ 2.500,  5.000) = 292555 
    [ 5.000,  7.500) = 699 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.077 ms/op
     p(99.9900) =     18.658 ms/op
     p(99.9990) =     20.001 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.876 ±(99.9%) 0.006 ms/op
Iteration   1: 2.935 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.014 ms/op
                 existUser·p0.9999: 13.406 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   2: 2.899 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  10.857 ms/op
                 existUser·p0.9999: 14.172 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  10.110 ms/op
                 existUser·p0.9999: 16.157 ms/op
                 existUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328753
  mean =      2.918 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 839 
    [ 1.250,  2.500) = 41735 
    [ 2.500,  3.750) = 275046 
    [ 3.750,  5.000) = 10102 
    [ 5.000,  6.250) = 343 
    [ 6.250,  7.500) = 205 
    [ 7.500,  8.750) = 97 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =     10.207 ms/op
     p(99.9900) =     15.026 ms/op
     p(99.9990) =     16.578 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.130 ms/op
                 getUser·p0.9999: 13.959 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   2: 2.950 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.310 ms/op
                 getUser·p0.95:   3.453 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.332 ms/op
                 getUser·p0.9999: 22.807 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.527 ms/op
                 getUser·p0.99:   4.092 ms/op
                 getUser·p0.999:  6.451 ms/op
                 getUser·p0.9999: 25.877 ms/op
                 getUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321951
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20188 
    [ 2.500,  5.000) = 300812 
    [ 5.000,  7.500) = 732 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.980 ms/op
     p(99.9900) =     24.592 ms/op
     p(99.9990) =     26.642 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 4.958 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.011 ms/op
Iteration   1: 3.961 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.094 ms/op
                 listUser·p0.9999: 21.526 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 3.997 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  15.668 ms/op
                 listUser·p0.9999: 17.858 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   3: 3.996 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.138 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240962
  mean =      3.984 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4106 
    [ 2.500,  5.000) = 211862 
    [ 5.000,  7.500) = 23689 
    [ 7.500, 10.000) = 927 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     15.090 ms/op
     p(99.9900) =     21.132 ms/op
     p(99.9990) =     22.485 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.436 ± 1.487  ops/ms
ClientGrpc.existUser                       thrpt       3  11.158 ± 0.958  ops/ms
ClientGrpc.getUser                         thrpt       3  10.787 ± 1.386  ops/ms
ClientGrpc.listUser                        thrpt       3   8.100 ± 1.670  ops/ms
ClientGrpc.createUser                       avgt       3   2.997 ± 0.573   ms/op
ClientGrpc.existUser                        avgt       3   2.861 ± 0.355   ms/op
ClientGrpc.getUser                          avgt       3   2.926 ± 0.697   ms/op
ClientGrpc.listUser                         avgt       3   3.882 ± 0.598   ms/op
ClientGrpc.createUser                     sample  326027   2.944 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.817           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.916           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.375           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.077           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.658           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.414           ms/op
ClientGrpc.existUser                      sample  328753   2.918 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.565           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.207           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.026           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.761           ms/op
ClientGrpc.getUser                        sample  321951   2.983 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.742           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.957           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.400           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.980           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.592           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.837           ms/op
ClientGrpc.listUser                       sample  240962   3.984 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.042           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.090           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.132           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
