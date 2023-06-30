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
# Warmup Iteration   1: 4.316 ops/ms
# Warmup Iteration   2: 9.010 ops/ms
# Warmup Iteration   3: 10.125 ops/ms
Iteration   1: 10.555 ops/ms
Iteration   2: 10.589 ops/ms
Iteration   3: 10.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.557 ±(99.9%) 0.557 ops/ms [Average]
  (min, avg, max) = (10.528, 10.557, 10.589), stdev = 0.031
  CI (99.9%): [10.000, 11.115] (assumes normal distribution)


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
# Warmup Iteration   1: 7.156 ops/ms
# Warmup Iteration   2: 10.576 ops/ms
# Warmup Iteration   3: 11.303 ops/ms
Iteration   1: 11.037 ops/ms
Iteration   2: 10.954 ops/ms
Iteration   3: 11.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.000 ±(99.9%) 0.762 ops/ms [Average]
  (min, avg, max) = (10.954, 11.000, 11.037), stdev = 0.042
  CI (99.9%): [10.238, 11.762] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.462 ops/ms
# Warmup Iteration   2: 10.021 ops/ms
# Warmup Iteration   3: 10.301 ops/ms
Iteration   1: 10.409 ops/ms
Iteration   2: 10.544 ops/ms
Iteration   3: 10.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.497 ±(99.9%) 1.394 ops/ms [Average]
  (min, avg, max) = (10.409, 10.497, 10.544), stdev = 0.076
  CI (99.9%): [9.103, 11.890] (assumes normal distribution)


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
# Warmup Iteration   1: 6.461 ops/ms
# Warmup Iteration   2: 7.106 ops/ms
# Warmup Iteration   3: 7.849 ops/ms
Iteration   1: 7.889 ops/ms
Iteration   2: 7.934 ops/ms
Iteration   3: 7.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.902 ±(99.9%) 0.511 ops/ms [Average]
  (min, avg, max) = (7.883, 7.902, 7.934), stdev = 0.028
  CI (99.9%): [7.391, 8.414] (assumes normal distribution)


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
# Warmup Iteration   1: 4.554 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.005 ms/op
Iteration   1: 3.147 ±(99.9%) 0.005 ms/op
Iteration   2: 3.079 ±(99.9%) 0.003 ms/op
Iteration   3: 3.097 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.108 ±(99.9%) 0.639 ms/op [Average]
  (min, avg, max) = (3.079, 3.108, 3.147), stdev = 0.035
  CI (99.9%): [2.468, 3.747] (assumes normal distribution)


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.002 ms/op
Iteration   1: 2.978 ±(99.9%) 0.001 ms/op
Iteration   2: 3.064 ±(99.9%) 0.001 ms/op
Iteration   3: 2.985 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.009 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (2.978, 3.009, 3.064), stdev = 0.048
  CI (99.9%): [2.140, 3.878] (assumes normal distribution)


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.003 ms/op
Iteration   1: 3.145 ±(99.9%) 0.002 ms/op
Iteration   2: 3.182 ±(99.9%) 0.002 ms/op
Iteration   3: 3.159 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.162 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (3.145, 3.162, 3.182), stdev = 0.019
  CI (99.9%): [2.817, 3.507] (assumes normal distribution)


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
# Warmup Iteration   1: 5.865 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.186 ±(99.9%) 0.013 ms/op
Iteration   1: 4.131 ±(99.9%) 0.024 ms/op
Iteration   2: 4.225 ±(99.9%) 0.015 ms/op
Iteration   3: 4.263 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.207 ±(99.9%) 1.237 ms/op [Average]
  (min, avg, max) = (4.131, 4.207, 4.263), stdev = 0.068
  CI (99.9%): [2.969, 5.444] (assumes normal distribution)


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.339 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
Iteration   1: 3.192 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  12.094 ms/op
                 createUser·p0.9999: 14.598 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  12.052 ms/op
                 createUser·p0.9999: 18.252 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 18.569 ms/op
                 createUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305760
  mean =      3.138 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 371 
    [ 1.250,  2.500) = 12615 
    [ 2.500,  3.750) = 270615 
    [ 3.750,  5.000) = 20071 
    [ 5.000,  6.250) = 1034 
    [ 6.250,  7.500) = 425 
    [ 7.500,  8.750) = 162 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 63 
    [17.500, 18.750) = 61 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =     11.993 ms/op
     p(99.9900) =     18.233 ms/op
     p(99.9990) =     18.936 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.972 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.884 ms/op
                 existUser·p0.9999: 12.632 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 2.962 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   3.940 ms/op
                 existUser·p0.999:  5.217 ms/op
                 existUser·p0.9999: 14.785 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  12.152 ms/op
                 existUser·p0.9999: 17.081 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323022
  mean =      2.971 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1099 
    [ 1.250,  2.500) = 16841 
    [ 2.500,  3.750) = 295028 
    [ 3.750,  5.000) = 9073 
    [ 5.000,  6.250) = 462 
    [ 6.250,  7.500) = 195 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      7.512 ms/op
     p(99.9900) =     16.739 ms/op
     p(99.9990) =     17.319 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.731 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.006 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  6.864 ms/op
                 getUser·p0.9999: 17.818 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.939 ms/op
                 getUser·p0.9999: 15.311 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   3: 3.034 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  5.739 ms/op
                 getUser·p0.9999: 17.185 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312739
  mean =      3.068 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 370 
    [ 1.250,  2.500) = 14895 
    [ 2.500,  3.750) = 278586 
    [ 3.750,  5.000) = 17569 
    [ 5.000,  6.250) = 847 
    [ 6.250,  7.500) = 306 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      6.720 ms/op
     p(99.9900) =     17.284 ms/op
     p(99.9990) =     19.061 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 5.534 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.011 ms/op
Iteration   1: 4.087 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  14.773 ms/op
                 listUser·p0.9999: 16.045 ms/op
                 listUser·p1.00:   16.318 ms/op

Iteration   2: 4.069 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  17.021 ms/op
                 listUser·p0.9999: 19.403 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 4.104 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  15.990 ms/op
                 listUser·p0.9999: 21.535 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234979
  mean =      4.087 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1838 
    [ 2.500,  5.000) = 205828 
    [ 5.000,  7.500) = 25517 
    [ 7.500, 10.000) = 1338 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     15.616 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     21.996 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.557 ± 0.557  ops/ms
ClientGrpc.existUser                       thrpt       3  11.000 ± 0.762  ops/ms
ClientGrpc.getUser                         thrpt       3  10.497 ± 1.394  ops/ms
ClientGrpc.listUser                        thrpt       3   7.902 ± 0.511  ops/ms
ClientGrpc.createUser                       avgt       3   3.108 ± 0.639   ms/op
ClientGrpc.existUser                        avgt       3   3.009 ± 0.869   ms/op
ClientGrpc.getUser                          avgt       3   3.162 ± 0.345   ms/op
ClientGrpc.listUser                         avgt       3   4.207 ± 1.237   ms/op
ClientGrpc.createUser                     sample  305760   3.138 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.794           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.993           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.233           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.137           ms/op
ClientGrpc.existUser                      sample  323022   2.971 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.590           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.512           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.739           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.465           ms/op
ClientGrpc.getUser                        sample  312739   3.068 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.862           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.720           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.284           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.431           ms/op
ClientGrpc.listUser                       sample  234979   4.087 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.075           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.266           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.616           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.087           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.184           ms/op
