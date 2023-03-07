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
# Warmup Iteration   1: 1.745 ops/ms
# Warmup Iteration   2: 4.641 ops/ms
# Warmup Iteration   3: 5.958 ops/ms
Iteration   1: 6.164 ops/ms
Iteration   2: 6.333 ops/ms
Iteration   3: 6.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.286 ±(99.9%) 1.943 ops/ms [Average]
  (min, avg, max) = (6.164, 6.286, 6.360), stdev = 0.107
  CI (99.9%): [4.342, 8.229] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.907 ops/ms
# Warmup Iteration   2: 6.321 ops/ms
# Warmup Iteration   3: 6.788 ops/ms
Iteration   1: 6.874 ops/ms
Iteration   2: 6.872 ops/ms
Iteration   3: 6.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.861 ±(99.9%) 0.376 ops/ms [Average]
  (min, avg, max) = (6.837, 6.861, 6.874), stdev = 0.021
  CI (99.9%): [6.485, 7.237] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.488 ops/ms
# Warmup Iteration   2: 5.982 ops/ms
# Warmup Iteration   3: 6.129 ops/ms
Iteration   1: 6.397 ops/ms
Iteration   2: 6.289 ops/ms
Iteration   3: 6.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.348 ±(99.9%) 1.003 ops/ms [Average]
  (min, avg, max) = (6.289, 6.348, 6.397), stdev = 0.055
  CI (99.9%): [5.345, 7.351] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.222 ops/ms
# Warmup Iteration   2: 4.426 ops/ms
# Warmup Iteration   3: 4.909 ops/ms
Iteration   1: 4.962 ops/ms
Iteration   2: 4.875 ops/ms
Iteration   3: 5.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.007 ±(99.9%) 2.920 ops/ms [Average]
  (min, avg, max) = (4.875, 5.007, 5.185), stdev = 0.160
  CI (99.9%): [2.087, 7.928] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.832 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.391 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.142 ±(99.9%) 0.007 ms/op
Iteration   1: 5.109 ±(99.9%) 0.005 ms/op
Iteration   2: 4.951 ±(99.9%) 0.005 ms/op
Iteration   3: 5.135 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.065 ±(99.9%) 1.809 ms/op [Average]
  (min, avg, max) = (4.951, 5.065, 5.135), stdev = 0.099
  CI (99.9%): [3.256, 6.874] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.143 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.056 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.784 ±(99.9%) 0.012 ms/op
Iteration   1: 4.838 ±(99.9%) 0.002 ms/op
Iteration   2: 4.694 ±(99.9%) 0.004 ms/op
Iteration   3: 4.785 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.772 ±(99.9%) 1.331 ms/op [Average]
  (min, avg, max) = (4.694, 4.772, 4.838), stdev = 0.073
  CI (99.9%): [3.441, 6.104] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.824 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.299 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.131 ±(99.9%) 0.004 ms/op
Iteration   1: 5.219 ±(99.9%) 0.006 ms/op
Iteration   2: 5.179 ±(99.9%) 0.003 ms/op
Iteration   3: 5.081 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.160 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (5.081, 5.160, 5.219), stdev = 0.071
  CI (99.9%): [3.864, 6.456] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.834 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 7.135 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 6.383 ±(99.9%) 0.018 ms/op
Iteration   1: 6.531 ±(99.9%) 0.019 ms/op
Iteration   2: 6.309 ±(99.9%) 0.021 ms/op
Iteration   3: 6.483 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.441 ±(99.9%) 2.132 ms/op [Average]
  (min, avg, max) = (6.309, 6.441, 6.531), stdev = 0.117
  CI (99.9%): [4.309, 8.573] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.001 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 5.400 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.281 ±(99.9%) 0.017 ms/op
Iteration   1: 5.031 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   4.923 ms/op
                 createUser·p0.90:   6.341 ms/op
                 createUser·p0.95:   6.873 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  13.735 ms/op
                 createUser·p0.9999: 18.687 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   2: 5.177 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   6.472 ms/op
                 createUser·p0.95:   6.971 ms/op
                 createUser·p0.99:   9.355 ms/op
                 createUser·p0.999:  14.391 ms/op
                 createUser·p0.9999: 19.047 ms/op
                 createUser·p1.00:   19.759 ms/op

Iteration   3: 5.041 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.530 ms/op
                 createUser·p0.50:   4.882 ms/op
                 createUser·p0.90:   6.332 ms/op
                 createUser·p0.95:   6.865 ms/op
                 createUser·p0.99:   8.877 ms/op
                 createUser·p0.999:  22.314 ms/op
                 createUser·p0.9999: 39.167 ms/op
                 createUser·p1.00:   39.649 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 188881
  mean =      5.082 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1779 
    [ 2.500,  5.000) = 96731 
    [ 5.000,  7.500) = 85448 
    [ 7.500, 10.000) = 3865 
    [10.000, 12.500) = 613 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.390 ms/op
     p(95.0000) =      6.898 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     14.715 ms/op
     p(99.9900) =     38.142 ms/op
     p(99.9990) =     39.649 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.819 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 5.140 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.778 ±(99.9%) 0.016 ms/op
Iteration   1: 4.988 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.357 ms/op
                 existUser·p0.95:   6.832 ms/op
                 existUser·p0.99:   8.970 ms/op
                 existUser·p0.999:  13.156 ms/op
                 existUser·p0.9999: 18.828 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   2: 4.876 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   4.760 ms/op
                 existUser·p0.90:   6.177 ms/op
                 existUser·p0.95:   6.603 ms/op
                 existUser·p0.99:   8.241 ms/op
                 existUser·p0.999:  12.441 ms/op
                 existUser·p0.9999: 20.934 ms/op
                 existUser·p1.00:   21.430 ms/op

Iteration   3: 4.828 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   4.694 ms/op
                 existUser·p0.90:   6.169 ms/op
                 existUser·p0.95:   6.676 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  14.385 ms/op
                 existUser·p0.9999: 21.196 ms/op
                 existUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 196147
  mean =      4.897 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2450 
    [ 2.500,  5.000) = 112084 
    [ 5.000,  7.500) = 77448 
    [ 7.500, 10.000) = 3198 
    [10.000, 12.500) = 636 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.242 ms/op
     p(95.0000) =      6.709 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     13.610 ms/op
     p(99.9900) =     20.800 ms/op
     p(99.9990) =     24.136 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.013 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.262 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.217 ±(99.9%) 0.017 ms/op
Iteration   1: 5.120 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.480 ms/op
                 getUser·p0.95:   7.062 ms/op
                 getUser·p0.99:   8.995 ms/op
                 getUser·p0.999:  18.053 ms/op
                 getUser·p0.9999: 25.395 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   2: 5.063 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   4.948 ms/op
                 getUser·p0.90:   6.472 ms/op
                 getUser·p0.95:   7.037 ms/op
                 getUser·p0.99:   8.815 ms/op
                 getUser·p0.999:  13.055 ms/op
                 getUser·p0.9999: 23.464 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   3: 5.032 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   6.341 ms/op
                 getUser·p0.95:   6.881 ms/op
                 getUser·p0.99:   8.700 ms/op
                 getUser·p0.999:  14.026 ms/op
                 getUser·p0.9999: 24.190 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 189194
  mean =      5.071 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2193 
    [ 2.500,  5.000) = 97499 
    [ 5.000,  7.500) = 84043 
    [ 7.500, 10.000) = 4597 
    [10.000, 12.500) = 548 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.431 ms/op
     p(95.0000) =      6.996 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     24.942 ms/op
     p(99.9990) =     25.664 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.830 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 6.975 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 6.652 ±(99.9%) 0.029 ms/op
Iteration   1: 6.479 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   8.536 ms/op
                 listUser·p0.95:   9.568 ms/op
                 listUser·p0.99:   12.050 ms/op
                 listUser·p0.999:  19.125 ms/op
                 listUser·p0.9999: 34.020 ms/op
                 listUser·p1.00:   34.406 ms/op

Iteration   2: 6.365 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   9.601 ms/op
                 listUser·p0.99:   12.199 ms/op
                 listUser·p0.999:  18.244 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   3: 6.314 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.509 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   8.454 ms/op
                 listUser·p0.95:   9.430 ms/op
                 listUser·p0.99:   12.182 ms/op
                 listUser·p0.999:  22.282 ms/op
                 listUser·p0.9999: 25.610 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 150342
  mean =      6.385 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 24845 
    [ 5.000,  7.500) = 97414 
    [ 7.500, 10.000) = 22428 
    [10.000, 12.500) = 4338 
    [12.500, 15.000) = 784 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      6.042 ms/op
     p(90.0000) =      8.520 ms/op
     p(95.0000) =      9.535 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     20.108 ms/op
     p(99.9900) =     31.716 ms/op
     p(99.9990) =     34.340 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.286 ± 1.943  ops/ms
ClientGrpc.existUser                       thrpt       3   6.861 ± 0.376  ops/ms
ClientGrpc.getUser                         thrpt       3   6.348 ± 1.003  ops/ms
ClientGrpc.listUser                        thrpt       3   5.007 ± 2.920  ops/ms
ClientGrpc.createUser                       avgt       3   5.065 ± 1.809   ms/op
ClientGrpc.existUser                        avgt       3   4.772 ± 1.331   ms/op
ClientGrpc.getUser                          avgt       3   5.160 ± 1.296   ms/op
ClientGrpc.listUser                         avgt       3   6.441 ± 2.132   ms/op
ClientGrpc.createUser                     sample  188881   5.082 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.530           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.948           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.390           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.898           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.897           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.715           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          38.142           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          39.649           ms/op
ClientGrpc.existUser                      sample  196147   4.897 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.017           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.776           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.242           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.709           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.667           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.610           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.800           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.609           ms/op
ClientGrpc.getUser                        sample  189194   5.071 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.292           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.940           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.431           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.996           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.847           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.926           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.942           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.723           ms/op
ClientGrpc.listUser                       sample  150342   6.385 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.468           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           6.042           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.535           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.141           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.108           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.716           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.406           ms/op
