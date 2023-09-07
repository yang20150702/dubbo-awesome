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
# Warmup Iteration   1: 4.054 ops/ms
# Warmup Iteration   2: 8.185 ops/ms
# Warmup Iteration   3: 9.920 ops/ms
Iteration   1: 10.288 ops/ms
Iteration   2: 10.361 ops/ms
Iteration   3: 10.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.318 ±(99.9%) 0.702 ops/ms [Average]
  (min, avg, max) = (10.288, 10.318, 10.361), stdev = 0.038
  CI (99.9%): [9.616, 11.020] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.070 ops/ms
# Warmup Iteration   2: 10.213 ops/ms
# Warmup Iteration   3: 11.181 ops/ms
Iteration   1: 10.955 ops/ms
Iteration   2: 11.212 ops/ms
Iteration   3: 10.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.010 ±(99.9%) 3.305 ops/ms [Average]
  (min, avg, max) = (10.863, 11.010, 11.212), stdev = 0.181
  CI (99.9%): [7.705, 14.315] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.065 ops/ms
# Warmup Iteration   2: 9.686 ops/ms
# Warmup Iteration   3: 10.291 ops/ms
Iteration   1: 10.461 ops/ms
Iteration   2: 10.307 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.407 ±(99.9%) 1.587 ops/ms [Average]
  (min, avg, max) = (10.307, 10.407, 10.461), stdev = 0.087
  CI (99.9%): [8.820, 11.995] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.716 ops/ms
# Warmup Iteration   2: 7.377 ops/ms
# Warmup Iteration   3: 7.803 ops/ms
Iteration   1: 7.861 ops/ms
Iteration   2: 7.923 ops/ms
Iteration   3: 7.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.886 ±(99.9%) 0.597 ops/ms [Average]
  (min, avg, max) = (7.861, 7.886, 7.923), stdev = 0.033
  CI (99.9%): [7.288, 8.483] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.396 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.003 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 3.034 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (2.994, 3.013, 3.034), stdev = 0.020
  CI (99.9%): [2.645, 3.381] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.187 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.003 ms/op
Iteration   1: 2.976 ±(99.9%) 0.002 ms/op
Iteration   2: 2.993 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.978 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (2.965, 2.978, 2.993), stdev = 0.014
  CI (99.9%): [2.716, 3.239] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.025 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.004 ms/op
Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
Iteration   3: 3.061 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.077 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (3.061, 3.077, 3.089), stdev = 0.015
  CI (99.9%): [2.805, 3.350] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.417 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.030 ms/op
Iteration   1: 4.125 ±(99.9%) 0.012 ms/op
Iteration   2: 4.108 ±(99.9%) 0.035 ms/op
Iteration   3: 4.077 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.103 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (4.077, 4.103, 4.125), stdev = 0.024
  CI (99.9%): [3.666, 4.540] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.465 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.007 ms/op
Iteration   1: 3.114 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  8.266 ms/op
                 createUser·p0.9999: 16.691 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.612 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  10.229 ms/op
                 createUser·p0.9999: 22.994 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   3: 3.060 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  10.355 ms/op
                 createUser·p0.9999: 19.220 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310189
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21689 
    [ 2.500,  5.000) = 286174 
    [ 5.000,  7.500) = 1631 
    [ 7.500, 10.000) = 401 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      9.847 ms/op
     p(99.9900) =     22.018 ms/op
     p(99.9990) =     24.376 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.132 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.007 ms/op
Iteration   1: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  9.659 ms/op
                 existUser·p0.9999: 13.178 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   2: 2.920 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.419 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  8.986 ms/op
                 existUser·p0.9999: 14.926 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  10.355 ms/op
                 existUser·p0.9999: 29.360 ms/op
                 existUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326178
  mean =      2.942 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36936 
    [ 2.500,  5.000) = 287333 
    [ 5.000,  7.500) = 1242 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.419 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      9.762 ms/op
     p(99.9900) =     21.483 ms/op
     p(99.9990) =     30.040 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.605 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.006 ms/op
Iteration   1: 3.161 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  10.256 ms/op
                 getUser·p0.9999: 13.871 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 3.128 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.329 ms/op
                 getUser·p0.9999: 14.928 ms/op
                 getUser·p1.00:   16.351 ms/op

Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  9.069 ms/op
                 getUser·p0.9999: 16.810 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305241
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 444 
    [ 1.250,  2.500) = 13282 
    [ 2.500,  3.750) = 264698 
    [ 3.750,  5.000) = 24596 
    [ 5.000,  6.250) = 1056 
    [ 6.250,  7.500) = 595 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      9.737 ms/op
     p(99.9900) =     16.334 ms/op
     p(99.9990) =     17.038 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 5.325 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.012 ms/op
Iteration   1: 4.138 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 20.259 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   2: 4.098 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  18.598 ms/op
                 listUser·p0.9999: 28.836 ms/op
                 listUser·p1.00:   29.295 ms/op

Iteration   3: 4.092 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  17.653 ms/op
                 listUser·p0.9999: 31.431 ms/op
                 listUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233595
  mean =      4.109 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2325 
    [ 2.500,  5.000) = 203691 
    [ 5.000,  7.500) = 25396 
    [ 7.500, 10.000) = 1520 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      6.070 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     16.922 ms/op
     p(99.9900) =     30.802 ms/op
     p(99.9990) =     31.916 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.318 ± 0.702  ops/ms
ClientGrpc.existUser                       thrpt       3  11.010 ± 3.305  ops/ms
ClientGrpc.getUser                         thrpt       3  10.407 ± 1.587  ops/ms
ClientGrpc.listUser                        thrpt       3   7.886 ± 0.597  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.368   ms/op
ClientGrpc.existUser                        avgt       3   2.978 ± 0.261   ms/op
ClientGrpc.getUser                          avgt       3   3.077 ± 0.273   ms/op
ClientGrpc.listUser                         avgt       3   4.103 ± 0.437   ms/op
ClientGrpc.createUser                     sample  310189   3.094 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.612           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.727           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.847           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.018           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.543           ms/op
ClientGrpc.existUser                      sample  326178   2.942 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.419           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.762           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.483           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.114           ms/op
ClientGrpc.getUser                        sample  305241   3.143 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.898           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.936           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.737           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.334           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.170           ms/op
ClientGrpc.listUser                       sample  233595   4.109 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.912           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.912           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.070           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.430           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.922           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.802           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.113           ms/op
