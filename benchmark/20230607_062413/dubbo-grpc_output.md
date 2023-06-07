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
# Warmup Iteration   1: 4.317 ops/ms
# Warmup Iteration   2: 9.068 ops/ms
# Warmup Iteration   3: 10.177 ops/ms
Iteration   1: 10.708 ops/ms
Iteration   2: 10.544 ops/ms
Iteration   3: 10.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.599 ±(99.9%) 1.710 ops/ms [Average]
  (min, avg, max) = (10.544, 10.599, 10.708), stdev = 0.094
  CI (99.9%): [8.889, 12.310] (assumes normal distribution)


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
# Warmup Iteration   1: 7.552 ops/ms
# Warmup Iteration   2: 10.417 ops/ms
# Warmup Iteration   3: 10.976 ops/ms
Iteration   1: 11.198 ops/ms
Iteration   2: 11.175 ops/ms
Iteration   3: 11.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.136 ±(99.9%) 1.601 ops/ms [Average]
  (min, avg, max) = (11.035, 11.136, 11.198), stdev = 0.088
  CI (99.9%): [9.535, 12.737] (assumes normal distribution)


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
# Warmup Iteration   1: 7.668 ops/ms
# Warmup Iteration   2: 10.270 ops/ms
# Warmup Iteration   3: 10.629 ops/ms
Iteration   1: 10.584 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.604 ±(99.9%) 0.490 ops/ms [Average]
  (min, avg, max) = (10.584, 10.604, 10.634), stdev = 0.027
  CI (99.9%): [10.114, 11.093] (assumes normal distribution)


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
# Warmup Iteration   1: 5.491 ops/ms
# Warmup Iteration   2: 7.589 ops/ms
# Warmup Iteration   3: 8.016 ops/ms
Iteration   1: 8.005 ops/ms
Iteration   2: 8.197 ops/ms
Iteration   3: 7.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.053 ±(99.9%) 2.311 ops/ms [Average]
  (min, avg, max) = (7.958, 8.053, 8.197), stdev = 0.127
  CI (99.9%): [5.742, 10.364] (assumes normal distribution)


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.002 ms/op
Iteration   1: 3.060 ±(99.9%) 0.004 ms/op
Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
Iteration   3: 3.037 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.052 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (3.037, 3.052, 3.061), stdev = 0.013
  CI (99.9%): [2.809, 3.296] (assumes normal distribution)


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.903 ±(99.9%) 0.003 ms/op
Iteration   1: 2.873 ±(99.9%) 0.003 ms/op
Iteration   2: 2.929 ±(99.9%) 0.003 ms/op
Iteration   3: 2.894 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.899 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (2.873, 2.899, 2.929), stdev = 0.028
  CI (99.9%): [2.388, 3.409] (assumes normal distribution)


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.004 ms/op
Iteration   1: 3.057 ±(99.9%) 0.008 ms/op
Iteration   2: 2.984 ±(99.9%) 0.003 ms/op
Iteration   3: 3.033 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.025 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (2.984, 3.025, 3.057), stdev = 0.038
  CI (99.9%): [2.340, 3.710] (assumes normal distribution)


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
# Warmup Iteration   1: 5.354 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.031 ms/op
Iteration   1: 4.020 ±(99.9%) 0.013 ms/op
Iteration   2: 3.956 ±(99.9%) 0.013 ms/op
Iteration   3: 4.124 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.033 ±(99.9%) 1.547 ms/op [Average]
  (min, avg, max) = (3.956, 4.033, 4.124), stdev = 0.085
  CI (99.9%): [2.486, 5.580] (assumes normal distribution)


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
# Warmup Iteration   1: 3.729 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
Iteration   1: 3.043 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  6.693 ms/op
                 createUser·p0.9999: 12.460 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 13.992 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  6.268 ms/op
                 createUser·p0.9999: 28.895 ms/op
                 createUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315931
  mean =      3.039 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24195 
    [ 2.500,  5.000) = 290498 
    [ 5.000,  7.500) = 899 
    [ 7.500, 10.000) = 129 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.898 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     29.519 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
Iteration   1: 2.934 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.423 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.257 ms/op
                 existUser·p0.9999: 18.809 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  5.817 ms/op
                 existUser·p0.9999: 12.983 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 2.985 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  6.693 ms/op
                 existUser·p0.9999: 15.722 ms/op
                 existUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322203
  mean =      2.980 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1713 
    [ 1.250,  2.500) = 31921 
    [ 2.500,  3.750) = 271247 
    [ 3.750,  5.000) = 16175 
    [ 5.000,  6.250) = 759 
    [ 6.250,  7.500) = 171 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     17.625 ms/op
     p(99.9990) =     19.122 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 3.689 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
Iteration   1: 3.054 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  9.212 ms/op
                 getUser·p0.9999: 18.793 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.962 ms/op
                 getUser·p0.9999: 23.233 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.598 ms/op
                 getUser·p0.9999: 14.171 ms/op
                 getUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311412
  mean =      3.080 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20143 
    [ 2.500,  5.000) = 289805 
    [ 5.000,  7.500) = 1124 
    [ 7.500, 10.000) = 159 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.738 ms/op
     p(99.9900) =     22.554 ms/op
     p(99.9990) =     23.720 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 5.373 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.011 ms/op
Iteration   1: 3.971 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  12.626 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   2: 3.972 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 15.056 ms/op
                 listUser·p1.00:   15.303 ms/op

Iteration   3: 3.982 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.787 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  15.548 ms/op
                 listUser·p0.9999: 18.414 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241422
  mean =      3.975 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 3583 
    [ 2.500,  3.750) = 97104 
    [ 3.750,  5.000) = 118641 
    [ 5.000,  6.250) = 16679 
    [ 6.250,  7.500) = 4362 
    [ 7.500,  8.750) = 525 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 67 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     13.601 ms/op
     p(99.9900) =     18.739 ms/op
     p(99.9990) =     19.287 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.599 ± 1.710  ops/ms
ClientGrpc.existUser                       thrpt       3  11.136 ± 1.601  ops/ms
ClientGrpc.getUser                         thrpt       3  10.604 ± 0.490  ops/ms
ClientGrpc.listUser                        thrpt       3   8.053 ± 2.311  ops/ms
ClientGrpc.createUser                       avgt       3   3.052 ± 0.244   ms/op
ClientGrpc.existUser                        avgt       3   2.899 ± 0.510   ms/op
ClientGrpc.getUser                          avgt       3   3.025 ± 0.685   ms/op
ClientGrpc.listUser                         avgt       3   4.033 ± 1.547   ms/op
ClientGrpc.createUser                     sample  315931   3.039 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.657           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.898           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.492           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.622           ms/op
ClientGrpc.existUser                      sample  322203   2.980 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.578           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.726           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.625           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.202           ms/op
ClientGrpc.getUser                        sample  311412   3.080 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.667           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.738           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.554           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.150           ms/op
ClientGrpc.listUser                       sample  241422   3.975 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.787           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.601           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.739           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.431           ms/op
