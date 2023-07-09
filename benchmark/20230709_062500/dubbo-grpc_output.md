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
# Warmup Iteration   1: 1.970 ops/ms
# Warmup Iteration   2: 4.562 ops/ms
# Warmup Iteration   3: 6.563 ops/ms
Iteration   1: 6.854 ops/ms
Iteration   2: 6.979 ops/ms
Iteration   3: 7.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.008 ±(99.9%) 3.115 ops/ms [Average]
  (min, avg, max) = (6.854, 7.008, 7.192), stdev = 0.171
  CI (99.9%): [3.894, 10.123] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.502 ops/ms
# Warmup Iteration   2: 7.064 ops/ms
# Warmup Iteration   3: 7.536 ops/ms
Iteration   1: 7.724 ops/ms
Iteration   2: 7.799 ops/ms
Iteration   3: 7.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.767 ±(99.9%) 0.714 ops/ms [Average]
  (min, avg, max) = (7.724, 7.767, 7.799), stdev = 0.039
  CI (99.9%): [7.053, 8.481] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.368 ops/ms
# Warmup Iteration   2: 6.164 ops/ms
# Warmup Iteration   3: 6.756 ops/ms
Iteration   1: 7.022 ops/ms
Iteration   2: 7.215 ops/ms
Iteration   3: 7.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.185 ±(99.9%) 2.754 ops/ms [Average]
  (min, avg, max) = (7.022, 7.185, 7.319), stdev = 0.151
  CI (99.9%): [4.431, 9.939] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.677 ops/ms
# Warmup Iteration   2: 5.122 ops/ms
# Warmup Iteration   3: 5.469 ops/ms
Iteration   1: 5.594 ops/ms
Iteration   2: 5.817 ops/ms
Iteration   3: 5.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.739 ±(99.9%) 2.284 ops/ms [Average]
  (min, avg, max) = (5.594, 5.739, 5.817), stdev = 0.125
  CI (99.9%): [3.455, 8.022] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.255 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.667 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.547 ±(99.9%) 0.015 ms/op
Iteration   1: 4.305 ±(99.9%) 0.003 ms/op
Iteration   2: 4.460 ±(99.9%) 0.004 ms/op
Iteration   3: 4.414 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.393 ±(99.9%) 1.452 ms/op [Average]
  (min, avg, max) = (4.305, 4.393, 4.460), stdev = 0.080
  CI (99.9%): [2.941, 5.844] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.904 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.469 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.364 ±(99.9%) 0.003 ms/op
Iteration   1: 4.257 ±(99.9%) 0.002 ms/op
Iteration   2: 4.261 ±(99.9%) 0.003 ms/op
Iteration   3: 4.254 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.257 ±(99.9%) 0.063 ms/op [Average]
  (min, avg, max) = (4.254, 4.257, 4.261), stdev = 0.003
  CI (99.9%): [4.194, 4.320] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.011 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.820 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.460 ±(99.9%) 0.004 ms/op
Iteration   1: 4.434 ±(99.9%) 0.002 ms/op
Iteration   2: 4.507 ±(99.9%) 0.002 ms/op
Iteration   3: 4.564 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.502 ±(99.9%) 1.195 ms/op [Average]
  (min, avg, max) = (4.434, 4.502, 4.564), stdev = 0.066
  CI (99.9%): [3.307, 5.697] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 7.880 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 6.287 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.600 ±(99.9%) 0.014 ms/op
Iteration   1: 5.364 ±(99.9%) 0.014 ms/op
Iteration   2: 5.431 ±(99.9%) 0.014 ms/op
Iteration   3: 5.457 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.417 ±(99.9%) 0.873 ms/op [Average]
  (min, avg, max) = (5.364, 5.417, 5.457), stdev = 0.048
  CI (99.9%): [4.544, 6.290] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.013 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.988 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.541 ±(99.9%) 0.012 ms/op
Iteration   1: 4.481 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   4.366 ms/op
                 createUser·p0.90:   5.497 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   7.586 ms/op
                 createUser·p0.999:  14.270 ms/op
                 createUser·p0.9999: 21.895 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   2: 4.478 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  10.771 ms/op
                 createUser·p0.9999: 23.790 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   3: 4.548 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  10.361 ms/op
                 createUser·p0.9999: 30.571 ms/op
                 createUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 213202
  mean =      4.502 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2939 
    [ 2.500,  5.000) = 160529 
    [ 5.000,  7.500) = 47824 
    [ 7.500, 10.000) = 1434 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     13.890 ms/op
     p(99.9900) =     27.744 ms/op
     p(99.9990) =     30.920 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.393 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.754 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.011 ms/op
Iteration   1: 4.152 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.071 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 15.973 ms/op
                 existUser·p1.00:   16.531 ms/op

Iteration   2: 4.225 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   4.129 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   5.530 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  10.760 ms/op
                 existUser·p0.9999: 21.772 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   3: 4.242 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   4.141 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.538 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  9.720 ms/op
                 existUser·p0.9999: 21.574 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 228176
  mean =      4.206 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3052 
    [ 2.500,  5.000) = 195907 
    [ 5.000,  7.500) = 28033 
    [ 7.500, 10.000) = 915 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     10.666 ms/op
     p(99.9900) =     21.409 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.659 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.818 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.422 ±(99.9%) 0.012 ms/op
Iteration   1: 4.414 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   4.350 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   7.190 ms/op
                 getUser·p0.999:  16.337 ms/op
                 getUser·p0.9999: 18.326 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   2: 4.414 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  10.175 ms/op
                 getUser·p0.9999: 16.589 ms/op
                 getUser·p1.00:   16.761 ms/op

Iteration   3: 4.368 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  8.765 ms/op
                 getUser·p0.9999: 19.912 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218231
  mean =      4.399 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2885 
    [ 2.500,  5.000) = 172714 
    [ 5.000,  7.500) = 41358 
    [ 7.500, 10.000) = 924 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.731 ms/op
     p(99.9000) =     12.284 ms/op
     p(99.9900) =     19.601 ms/op
     p(99.9990) =     20.403 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.900 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.268 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.650 ±(99.9%) 0.019 ms/op
Iteration   1: 5.642 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   10.486 ms/op
                 listUser·p0.999:  19.167 ms/op
                 listUser·p0.9999: 24.893 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   2: 5.507 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.709 ms/op
                 listUser·p0.99:   10.106 ms/op
                 listUser·p0.999:  24.501 ms/op
                 listUser·p0.9999: 28.913 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   3: 5.582 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.632 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.078 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   10.109 ms/op
                 listUser·p0.999:  20.921 ms/op
                 listUser·p0.9999: 26.161 ms/op
                 listUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172181
  mean =      5.576 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 57391 
    [ 5.000,  7.500) = 101621 
    [ 7.500, 10.000) = 11051 
    [10.000, 12.500) = 1475 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.093 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     20.114 ms/op
     p(99.9900) =     28.403 ms/op
     p(99.9990) =     30.547 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.008 ± 3.115  ops/ms
ClientGrpc.existUser                       thrpt       3   7.767 ± 0.714  ops/ms
ClientGrpc.getUser                         thrpt       3   7.185 ± 2.754  ops/ms
ClientGrpc.listUser                        thrpt       3   5.739 ± 2.284  ops/ms
ClientGrpc.createUser                       avgt       3   4.393 ± 1.452   ms/op
ClientGrpc.existUser                        avgt       3   4.257 ± 0.063   ms/op
ClientGrpc.getUser                          avgt       3   4.502 ± 1.195   ms/op
ClientGrpc.listUser                         avgt       3   5.417 ± 0.873   ms/op
ClientGrpc.createUser                     sample  213202   4.502 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.118           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.038           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.365           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.890           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.744           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.031           ms/op
ClientGrpc.existUser                      sample  228176   4.206 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.902           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.145           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.521           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.611           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.666           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.409           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.151           ms/op
ClientGrpc.getUser                        sample  218231   4.399 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.276           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.349           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.661           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.731           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.284           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.601           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.447           ms/op
ClientGrpc.listUser                       sample  172181   5.576 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.632           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.093           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.240           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.114           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.403           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.162           ms/op
