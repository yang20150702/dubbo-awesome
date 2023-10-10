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
# Warmup Iteration   1: 3.673 ops/ms
# Warmup Iteration   2: 8.469 ops/ms
# Warmup Iteration   3: 9.745 ops/ms
Iteration   1: 10.048 ops/ms
Iteration   2: 10.144 ops/ms
Iteration   3: 10.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.103 ±(99.9%) 0.902 ops/ms [Average]
  (min, avg, max) = (10.048, 10.103, 10.144), stdev = 0.049
  CI (99.9%): [9.201, 11.004] (assumes normal distribution)


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
# Warmup Iteration   1: 7.103 ops/ms
# Warmup Iteration   2: 10.131 ops/ms
# Warmup Iteration   3: 10.665 ops/ms
Iteration   1: 10.729 ops/ms
Iteration   2: 10.618 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.600 ±(99.9%) 2.524 ops/ms [Average]
  (min, avg, max) = (10.454, 10.600, 10.729), stdev = 0.138
  CI (99.9%): [8.076, 13.124] (assumes normal distribution)


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
# Warmup Iteration   1: 6.939 ops/ms
# Warmup Iteration   2: 9.723 ops/ms
# Warmup Iteration   3: 10.059 ops/ms
Iteration   1: 9.926 ops/ms
Iteration   2: 10.149 ops/ms
Iteration   3: 10.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.112 ±(99.9%) 3.131 ops/ms [Average]
  (min, avg, max) = (9.926, 10.112, 10.263), stdev = 0.172
  CI (99.9%): [6.981, 13.244] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.183 ops/ms
# Warmup Iteration   2: 7.304 ops/ms
# Warmup Iteration   3: 7.873 ops/ms
Iteration   1: 7.954 ops/ms
Iteration   2: 8.087 ops/ms
Iteration   3: 7.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.996 ±(99.9%) 1.446 ops/ms [Average]
  (min, avg, max) = (7.946, 7.996, 8.087), stdev = 0.079
  CI (99.9%): [6.550, 9.442] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.595 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.004 ms/op
Iteration   1: 3.177 ±(99.9%) 0.002 ms/op
Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
Iteration   3: 3.177 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.181 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (3.177, 3.181, 3.189), stdev = 0.007
  CI (99.9%): [3.052, 3.310] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.319 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.002 ms/op
Iteration   1: 2.999 ±(99.9%) 0.003 ms/op
Iteration   2: 2.980 ±(99.9%) 0.004 ms/op
Iteration   3: 2.960 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.980 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (2.960, 2.980, 2.999), stdev = 0.020
  CI (99.9%): [2.622, 3.338] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.343 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.003 ms/op
Iteration   1: 3.061 ±(99.9%) 0.005 ms/op
Iteration   2: 3.130 ±(99.9%) 0.003 ms/op
Iteration   3: 3.115 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.102 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (3.061, 3.102, 3.130), stdev = 0.036
  CI (99.9%): [2.439, 3.765] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.230 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.032 ms/op
Iteration   1: 4.029 ±(99.9%) 0.018 ms/op
Iteration   2: 3.831 ±(99.9%) 0.022 ms/op
Iteration   3: 3.995 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.952 ±(99.9%) 1.931 ms/op [Average]
  (min, avg, max) = (3.831, 3.952, 4.029), stdev = 0.106
  CI (99.9%): [2.021, 5.883] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.407 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.006 ms/op
Iteration   1: 3.158 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  10.001 ms/op
                 createUser·p0.9999: 17.531 ms/op
                 createUser·p1.00:   17.727 ms/op

Iteration   2: 3.123 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.815 ms/op
                 createUser·p0.999:  11.779 ms/op
                 createUser·p0.9999: 14.754 ms/op
                 createUser·p1.00:   16.024 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  12.806 ms/op
                 createUser·p0.9999: 26.272 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306187
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13305 
    [ 2.500,  5.000) = 290738 
    [ 5.000,  7.500) = 1617 
    [ 7.500, 10.000) = 180 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =     11.843 ms/op
     p(99.9900) =     17.662 ms/op
     p(99.9990) =     26.731 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.256 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.974 ms/op
                 existUser·p0.9999: 13.544 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  11.801 ms/op
                 existUser·p0.9999: 17.682 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.743 ms/op
                 existUser·p0.999:  10.060 ms/op
                 existUser·p0.9999: 17.312 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313281
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1064 
    [ 1.250,  2.500) = 19245 
    [ 2.500,  3.750) = 272619 
    [ 3.750,  5.000) = 18530 
    [ 5.000,  6.250) = 820 
    [ 6.250,  7.500) = 335 
    [ 7.500,  8.750) = 290 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     17.291 ms/op
     p(99.9990) =     18.178 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  13.238 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   2: 3.187 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  12.932 ms/op
                 getUser·p0.9999: 18.643 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.077 ms/op
                 getUser·p0.9999: 19.530 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304654
  mean =      3.151 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 351 
    [ 1.250,  2.500) = 8826 
    [ 2.500,  3.750) = 267175 
    [ 3.750,  5.000) = 26002 
    [ 5.000,  6.250) = 1265 
    [ 6.250,  7.500) = 348 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.721 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     19.154 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 5.360 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.010 ms/op
Iteration   1: 4.000 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.529 ms/op
                 listUser·p0.9999: 22.152 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   2: 3.978 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   6.916 ms/op
                 listUser·p0.999:  14.379 ms/op
                 listUser·p0.9999: 20.242 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   3: 3.991 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 18.873 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240471
  mean =      3.990 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2153 
    [ 2.500,  5.000) = 222354 
    [ 5.000,  7.500) = 14190 
    [ 7.500, 10.000) = 1086 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     15.082 ms/op
     p(99.9900) =     20.240 ms/op
     p(99.9990) =     22.354 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.103 ± 0.902  ops/ms
ClientGrpc.existUser                       thrpt       3  10.600 ± 2.524  ops/ms
ClientGrpc.getUser                         thrpt       3  10.112 ± 3.131  ops/ms
ClientGrpc.listUser                        thrpt       3   7.996 ± 1.446  ops/ms
ClientGrpc.createUser                       avgt       3   3.181 ± 0.129   ms/op
ClientGrpc.existUser                        avgt       3   2.980 ± 0.358   ms/op
ClientGrpc.getUser                          avgt       3   3.102 ± 0.663   ms/op
ClientGrpc.listUser                         avgt       3   3.952 ± 1.931   ms/op
ClientGrpc.createUser                     sample  306187   3.136 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.713           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.843           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.662           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.935           ms/op
ClientGrpc.existUser                      sample  313281   3.063 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.582           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.019           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.667           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.291           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.317           ms/op
ClientGrpc.getUser                        sample  304654   3.151 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.717           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.721           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.944           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.943           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.154           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.661           ms/op
ClientGrpc.listUser                       sample  240471   3.990 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.835           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.082           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.240           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.643           ms/op
