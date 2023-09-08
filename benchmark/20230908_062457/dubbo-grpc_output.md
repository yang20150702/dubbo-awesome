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
# Warmup Iteration   1: 4.403 ops/ms
# Warmup Iteration   2: 8.996 ops/ms
# Warmup Iteration   3: 10.039 ops/ms
Iteration   1: 10.541 ops/ms
Iteration   2: 10.773 ops/ms
Iteration   3: 10.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.649 ±(99.9%) 2.130 ops/ms [Average]
  (min, avg, max) = (10.541, 10.649, 10.773), stdev = 0.117
  CI (99.9%): [8.520, 12.779] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.248 ops/ms
# Warmup Iteration   2: 10.473 ops/ms
# Warmup Iteration   3: 10.882 ops/ms
Iteration   1: 11.059 ops/ms
Iteration   2: 10.878 ops/ms
Iteration   3: 11.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.003 ±(99.9%) 1.967 ops/ms [Average]
  (min, avg, max) = (10.878, 11.003, 11.071), stdev = 0.108
  CI (99.9%): [9.036, 12.969] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.774 ops/ms
# Warmup Iteration   2: 9.926 ops/ms
# Warmup Iteration   3: 10.414 ops/ms
Iteration   1: 10.468 ops/ms
Iteration   2: 10.437 ops/ms
Iteration   3: 10.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.415 ±(99.9%) 1.222 ops/ms [Average]
  (min, avg, max) = (10.340, 10.415, 10.468), stdev = 0.067
  CI (99.9%): [9.193, 11.637] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.316 ops/ms
# Warmup Iteration   2: 7.791 ops/ms
# Warmup Iteration   3: 7.984 ops/ms
Iteration   1: 7.814 ops/ms
Iteration   2: 8.087 ops/ms
Iteration   3: 7.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.957 ±(99.9%) 2.498 ops/ms [Average]
  (min, avg, max) = (7.814, 7.957, 8.087), stdev = 0.137
  CI (99.9%): [5.459, 10.455] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.161 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.003 ms/op
Iteration   1: 2.992 ±(99.9%) 0.003 ms/op
Iteration   2: 3.019 ±(99.9%) 0.003 ms/op
Iteration   3: 3.018 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.010 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (2.992, 3.010, 3.019), stdev = 0.015
  CI (99.9%): [2.733, 3.287] (assumes normal distribution)


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
# Warmup Iteration   1: 3.893 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.003 ms/op
Iteration   1: 2.832 ±(99.9%) 0.002 ms/op
Iteration   2: 2.907 ±(99.9%) 0.002 ms/op
Iteration   3: 2.873 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.871 ±(99.9%) 0.693 ms/op [Average]
  (min, avg, max) = (2.832, 2.871, 2.907), stdev = 0.038
  CI (99.9%): [2.178, 3.563] (assumes normal distribution)


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.004 ms/op
Iteration   1: 3.031 ±(99.9%) 0.004 ms/op
Iteration   2: 3.061 ±(99.9%) 0.004 ms/op
Iteration   3: 3.042 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.045 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (3.031, 3.045, 3.061), stdev = 0.015
  CI (99.9%): [2.766, 3.323] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.391 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.020 ms/op
Iteration   1: 4.032 ±(99.9%) 0.017 ms/op
Iteration   2: 4.010 ±(99.9%) 0.033 ms/op
Iteration   3: 4.026 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.022 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (4.010, 4.022, 4.032), stdev = 0.011
  CI (99.9%): [3.815, 4.230] (assumes normal distribution)


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.031 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.344 ms/op
                 createUser·p0.999:  7.720 ms/op
                 createUser·p0.9999: 15.883 ms/op
                 createUser·p1.00:   16.040 ms/op

Iteration   2: 3.004 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.949 ms/op
                 createUser·p0.9999: 13.533 ms/op
                 createUser·p1.00:   17.400 ms/op

Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.419 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.565 ms/op
                 createUser·p0.999:  11.237 ms/op
                 createUser·p0.9999: 17.108 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316856
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1301 
    [ 1.250,  2.500) = 18397 
    [ 2.500,  3.750) = 282626 
    [ 3.750,  5.000) = 12411 
    [ 5.000,  6.250) = 975 
    [ 6.250,  7.500) = 566 
    [ 7.500,  8.750) = 244 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.419 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      9.704 ms/op
     p(99.9900) =     16.755 ms/op
     p(99.9990) =     18.694 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
Iteration   1: 2.926 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.878 ms/op
                 existUser·p0.9999: 12.977 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   2: 2.959 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.954 ms/op
                 existUser·p0.9999: 13.484 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.918 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  11.722 ms/op
                 existUser·p0.9999: 25.854 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326882
  mean =      2.934 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27728 
    [ 2.500,  5.000) = 297552 
    [ 5.000,  7.500) = 1088 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     18.681 ms/op
     p(99.9990) =     26.197 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
Iteration   1: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.220 ms/op
                 getUser·p0.9999: 16.071 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  9.241 ms/op
                 getUser·p0.9999: 17.005 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.376 ms/op
                 getUser·p0.999:  7.881 ms/op
                 getUser·p0.9999: 16.929 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310866
  mean =      3.090 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 291 
    [ 1.250,  2.500) = 12294 
    [ 2.500,  3.750) = 280044 
    [ 3.750,  5.000) = 16226 
    [ 5.000,  6.250) = 899 
    [ 6.250,  7.500) = 645 
    [ 7.500,  8.750) = 184 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 65 
    [16.250, 17.500) = 62 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.218 ms/op
     p(99.9900) =     16.710 ms/op
     p(99.9990) =     17.294 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 5.165 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.312 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.012 ms/op
Iteration   1: 4.022 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.951 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  13.041 ms/op
                 listUser·p0.9999: 17.369 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 4.066 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  16.272 ms/op
                 listUser·p0.9999: 26.218 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   3: 4.041 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.241 ms/op
                 listUser·p0.999:  15.616 ms/op
                 listUser·p0.9999: 23.396 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237528
  mean =      4.043 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2130 
    [ 2.500,  5.000) = 211650 
    [ 5.000,  7.500) = 21716 
    [ 7.500, 10.000) = 1565 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     25.747 ms/op
     p(99.9990) =     26.567 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.649 ± 2.130  ops/ms
ClientGrpc.existUser                       thrpt       3  11.003 ± 1.967  ops/ms
ClientGrpc.getUser                         thrpt       3  10.415 ± 1.222  ops/ms
ClientGrpc.listUser                        thrpt       3   7.957 ± 2.498  ops/ms
ClientGrpc.createUser                       avgt       3   3.010 ± 0.277   ms/op
ClientGrpc.existUser                        avgt       3   2.871 ± 0.693   ms/op
ClientGrpc.getUser                          avgt       3   3.045 ± 0.279   ms/op
ClientGrpc.listUser                         avgt       3   4.022 ± 0.207   ms/op
ClientGrpc.createUser                     sample  316856   3.031 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.419           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.704           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.755           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.562           ms/op
ClientGrpc.existUser                      sample  326882   2.934 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.642           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.864           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.681           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.787           ms/op
ClientGrpc.getUser                        sample  310866   3.090 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.743           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.218           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.710           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.400           ms/op
ClientGrpc.listUser                       sample  237528   4.043 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.855           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.307           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.991           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.747           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.706           ms/op
