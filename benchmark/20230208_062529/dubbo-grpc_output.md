# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.484 ops/ms
# Warmup Iteration   2: 9.181 ops/ms
# Warmup Iteration   3: 10.610 ops/ms
Iteration   1: 10.563 ops/ms
Iteration   2: 10.619 ops/ms
Iteration   3: 10.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.509 ±(99.9%) 2.656 ops/ms [Average]
  (min, avg, max) = (10.344, 10.509, 10.619), stdev = 0.146
  CI (99.9%): [7.853, 13.164] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.955 ops/ms
# Warmup Iteration   2: 10.247 ops/ms
# Warmup Iteration   3: 10.778 ops/ms
Iteration   1: 11.075 ops/ms
Iteration   2: 10.816 ops/ms
Iteration   3: 10.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.946 ±(99.9%) 2.365 ops/ms [Average]
  (min, avg, max) = (10.816, 10.946, 11.075), stdev = 0.130
  CI (99.9%): [8.581, 13.311] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.741 ops/ms
# Warmup Iteration   2: 10.342 ops/ms
# Warmup Iteration   3: 10.456 ops/ms
Iteration   1: 10.585 ops/ms
Iteration   2: 10.241 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.481 ±(99.9%) 3.788 ops/ms [Average]
  (min, avg, max) = (10.241, 10.481, 10.615), stdev = 0.208
  CI (99.9%): [6.692, 14.269] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.724 ops/ms
# Warmup Iteration   2: 7.689 ops/ms
# Warmup Iteration   3: 7.965 ops/ms
Iteration   1: 7.784 ops/ms
Iteration   2: 7.828 ops/ms
Iteration   3: 8.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.911 ±(99.9%) 3.335 ops/ms [Average]
  (min, avg, max) = (7.784, 7.911, 8.120), stdev = 0.183
  CI (99.9%): [4.576, 11.246] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.002 ms/op
Iteration   1: 3.161 ±(99.9%) 0.002 ms/op
Iteration   2: 3.127 ±(99.9%) 0.001 ms/op
Iteration   3: 3.049 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.112 ±(99.9%) 1.048 ms/op [Average]
  (min, avg, max) = (3.049, 3.112, 3.161), stdev = 0.057
  CI (99.9%): [2.064, 4.161] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.674 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.003 ms/op
Iteration   1: 2.921 ±(99.9%) 0.003 ms/op
Iteration   2: 2.944 ±(99.9%) 0.002 ms/op
Iteration   3: 2.955 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.940 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (2.921, 2.940, 2.955), stdev = 0.017
  CI (99.9%): [2.622, 3.259] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.027 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.004 ms/op
Iteration   1: 3.065 ±(99.9%) 0.002 ms/op
Iteration   2: 3.111 ±(99.9%) 0.002 ms/op
Iteration   3: 3.096 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.091 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (3.065, 3.091, 3.111), stdev = 0.024
  CI (99.9%): [2.662, 3.520] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.557 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.013 ms/op
Iteration   1: 3.988 ±(99.9%) 0.027 ms/op
Iteration   2: 4.130 ±(99.9%) 0.008 ms/op
Iteration   3: 3.910 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.009 ±(99.9%) 2.036 ms/op [Average]
  (min, avg, max) = (3.910, 4.009, 4.130), stdev = 0.112
  CI (99.9%): [1.973, 6.045] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.007 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.657 ms/op
                 createUser·p0.9999: 11.601 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  5.766 ms/op
                 createUser·p0.9999: 12.819 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  8.418 ms/op
                 createUser·p0.9999: 15.421 ms/op
                 createUser·p1.00:   15.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310338
  mean =      3.093 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1103 
    [ 1.250,  2.500) = 28718 
    [ 2.500,  3.750) = 249262 
    [ 3.750,  5.000) = 30157 
    [ 5.000,  6.250) = 550 
    [ 6.250,  7.500) = 237 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.517 ms/op
     p(99.9900) =     14.630 ms/op
     p(99.9990) =     15.707 ms/op
     p(99.9999) =     15.843 ms/op
    p(100.0000) =     15.843 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.864 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
Iteration   1: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.572 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  5.504 ms/op
                 existUser·p0.9999: 11.735 ms/op
                 existUser·p1.00:   12.108 ms/op

Iteration   2: 2.891 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.483 ms/op
                 existUser·p0.9999: 12.876 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   3: 2.936 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.498 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 23.371 ms/op
                 existUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327205
  mean =      2.931 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47852 
    [ 2.500,  5.000) = 278622 
    [ 5.000,  7.500) = 419 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      7.455 ms/op
     p(99.9900) =     17.099 ms/op
     p(99.9990) =     23.828 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.928 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.006 ms/op
Iteration   1: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.971 ms/op
                 getUser·p0.9999: 13.232 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.236 ms/op
                 getUser·p0.9999: 20.314 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  9.590 ms/op
                 getUser·p0.9999: 14.498 ms/op
                 getUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309919
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25500 
    [ 2.500,  5.000) = 283577 
    [ 5.000,  7.500) = 552 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.332 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     20.572 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.101 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.010 ms/op
Iteration   1: 3.857 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  12.648 ms/op
                 listUser·p0.9999: 18.724 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 3.876 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  13.721 ms/op
                 listUser·p0.9999: 16.744 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   3: 3.804 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.622 ms/op
                 listUser·p0.999:  14.482 ms/op
                 listUser·p0.9999: 19.516 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249484
  mean =      3.845 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5496 
    [ 2.500,  5.000) = 225022 
    [ 5.000,  7.500) = 18003 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     19.204 ms/op
     p(99.9990) =     20.169 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.509 ± 2.656  ops/ms
ClientGrpc.existUser                       thrpt       3  10.946 ± 2.365  ops/ms
ClientGrpc.getUser                         thrpt       3  10.481 ± 3.788  ops/ms
ClientGrpc.listUser                        thrpt       3   7.911 ± 3.335  ops/ms
ClientGrpc.createUser                       avgt       3   3.112 ± 1.048   ms/op
ClientGrpc.existUser                        avgt       3   2.940 ± 0.318   ms/op
ClientGrpc.getUser                          avgt       3   3.091 ± 0.429   ms/op
ClientGrpc.listUser                         avgt       3   4.009 ± 2.036   ms/op
ClientGrpc.createUser                     sample  310338   3.093 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.606           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.944           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.517           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.630           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.843           ms/op
ClientGrpc.existUser                      sample  327205   2.931 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.498           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.455           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.099           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.888           ms/op
ClientGrpc.getUser                        sample  309919   3.098 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.566           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.936           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.332           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.973           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.742           ms/op
ClientGrpc.listUser                       sample  249484   3.845 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.128           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.615           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.204           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.251           ms/op
