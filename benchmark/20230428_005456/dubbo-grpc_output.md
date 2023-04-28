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
# Warmup Iteration   1: 4.093 ops/ms
# Warmup Iteration   2: 8.798 ops/ms
# Warmup Iteration   3: 9.782 ops/ms
Iteration   1: 10.306 ops/ms
Iteration   2: 10.147 ops/ms
Iteration   3: 10.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.310 ±(99.9%) 3.011 ops/ms [Average]
  (min, avg, max) = (10.147, 10.310, 10.477), stdev = 0.165
  CI (99.9%): [7.299, 13.322] (assumes normal distribution)


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
# Warmup Iteration   1: 6.868 ops/ms
# Warmup Iteration   2: 10.105 ops/ms
# Warmup Iteration   3: 10.541 ops/ms
Iteration   1: 10.650 ops/ms
Iteration   2: 10.943 ops/ms
Iteration   3: 10.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.818 ±(99.9%) 2.754 ops/ms [Average]
  (min, avg, max) = (10.650, 10.818, 10.943), stdev = 0.151
  CI (99.9%): [8.064, 13.572] (assumes normal distribution)


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
# Warmup Iteration   1: 6.805 ops/ms
# Warmup Iteration   2: 9.981 ops/ms
# Warmup Iteration   3: 10.320 ops/ms
Iteration   1: 10.317 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.405 ±(99.9%) 2.830 ops/ms [Average]
  (min, avg, max) = (10.315, 10.405, 10.585), stdev = 0.155
  CI (99.9%): [7.575, 13.236] (assumes normal distribution)


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
# Warmup Iteration   1: 5.271 ops/ms
# Warmup Iteration   2: 7.543 ops/ms
# Warmup Iteration   3: 7.828 ops/ms
Iteration   1: 7.987 ops/ms
Iteration   2: 7.913 ops/ms
Iteration   3: 7.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.950 ±(99.9%) 0.673 ops/ms [Average]
  (min, avg, max) = (7.913, 7.950, 7.987), stdev = 0.037
  CI (99.9%): [7.276, 8.623] (assumes normal distribution)


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
# Warmup Iteration   1: 4.485 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.002 ms/op
Iteration   1: 3.057 ±(99.9%) 0.004 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.148 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.104 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (3.057, 3.104, 3.148), stdev = 0.045
  CI (99.9%): [2.274, 3.933] (assumes normal distribution)


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.003 ms/op
Iteration   1: 2.984 ±(99.9%) 0.004 ms/op
Iteration   2: 2.971 ±(99.9%) 0.002 ms/op
Iteration   3: 2.931 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.962 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (2.931, 2.962, 2.984), stdev = 0.028
  CI (99.9%): [2.458, 3.466] (assumes normal distribution)


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.003 ms/op
Iteration   1: 3.116 ±(99.9%) 0.001 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.075 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.099 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (3.075, 3.099, 3.116), stdev = 0.021
  CI (99.9%): [2.708, 3.490] (assumes normal distribution)


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
# Warmup Iteration   1: 5.749 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.011 ms/op
Iteration   1: 3.998 ±(99.9%) 0.019 ms/op
Iteration   2: 4.048 ±(99.9%) 0.015 ms/op
Iteration   3: 3.995 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.014 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.995, 4.014, 4.048), stdev = 0.029
  CI (99.9%): [3.477, 4.550] (assumes normal distribution)


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
# Warmup Iteration   1: 4.289 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.972 ms/op
                 createUser·p0.9999: 14.024 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.220 ms/op
                 createUser·p0.9999: 24.958 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.157 ms/op
                 createUser·p0.999:  12.378 ms/op
                 createUser·p0.9999: 17.768 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312672
  mean =      3.069 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14591 
    [ 2.500,  5.000) = 296758 
    [ 5.000,  7.500) = 932 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.296 ms/op
     p(99.9900) =     23.093 ms/op
     p(99.9990) =     25.391 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.005 ms/op
Iteration   1: 2.964 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  6.873 ms/op
                 existUser·p0.9999: 12.924 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   2: 2.961 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.329 ms/op
                 existUser·p0.9999: 13.926 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  9.568 ms/op
                 existUser·p0.9999: 28.060 ms/op
                 existUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322856
  mean =      2.974 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14181 
    [ 2.500,  5.000) = 307585 
    [ 5.000,  7.500) = 771 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.494 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =      7.472 ms/op
     p(99.9900) =     26.907 ms/op
     p(99.9990) =     28.730 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.008 ms/op
Iteration   1: 3.089 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.823 ms/op
                 getUser·p0.9999: 14.794 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.560 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.890 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  7.406 ms/op
                 getUser·p0.9999: 15.008 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   3: 3.113 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.586 ms/op
                 getUser·p0.9999: 17.030 ms/op
                 getUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310133
  mean =      3.096 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 617 
    [ 1.250,  2.500) = 15973 
    [ 2.500,  3.750) = 273886 
    [ 3.750,  5.000) = 18300 
    [ 5.000,  6.250) = 798 
    [ 6.250,  7.500) = 300 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.298 ms/op
     p(99.9900) =     15.990 ms/op
     p(99.9990) =     18.297 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 5.052 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.011 ms/op
Iteration   1: 4.037 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  13.370 ms/op
                 listUser·p0.9999: 19.567 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 3.989 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.661 ms/op
                 listUser·p0.9999: 26.673 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   3: 4.008 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  17.304 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239423
  mean =      4.011 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2963 
    [ 2.500,  5.000) = 212713 
    [ 5.000,  7.500) = 22338 
    [ 7.500, 10.000) = 1016 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     15.223 ms/op
     p(99.9900) =     25.397 ms/op
     p(99.9990) =     27.106 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.310 ± 3.011  ops/ms
ClientGrpc.existUser                       thrpt       3  10.818 ± 2.754  ops/ms
ClientGrpc.getUser                         thrpt       3  10.405 ± 2.830  ops/ms
ClientGrpc.listUser                        thrpt       3   7.950 ± 0.673  ops/ms
ClientGrpc.createUser                       avgt       3   3.104 ± 0.829   ms/op
ClientGrpc.existUser                        avgt       3   2.962 ± 0.504   ms/op
ClientGrpc.getUser                          avgt       3   3.099 ± 0.391   ms/op
ClientGrpc.listUser                         avgt       3   4.014 ± 0.537   ms/op
ClientGrpc.createUser                     sample  312672   3.069 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.702           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.296           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.093           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.526           ms/op
ClientGrpc.existUser                      sample  322856   2.974 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.745           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.472           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.907           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.803           ms/op
ClientGrpc.getUser                        sample  310133   3.096 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.560           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.298           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.990           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.448           ms/op
ClientGrpc.listUser                       sample  239423   4.011 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.856           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.223           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.397           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.132           ms/op
