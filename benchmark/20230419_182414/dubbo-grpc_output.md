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
# Warmup Iteration   1: 2.084 ops/ms
# Warmup Iteration   2: 5.357 ops/ms
# Warmup Iteration   3: 6.960 ops/ms
Iteration   1: 7.225 ops/ms
Iteration   2: 7.171 ops/ms
Iteration   3: 7.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.244 ±(99.9%) 1.550 ops/ms [Average]
  (min, avg, max) = (7.171, 7.244, 7.337), stdev = 0.085
  CI (99.9%): [5.695, 8.794] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.538 ops/ms
# Warmup Iteration   2: 6.859 ops/ms
# Warmup Iteration   3: 7.971 ops/ms
Iteration   1: 8.257 ops/ms
Iteration   2: 7.800 ops/ms
Iteration   3: 8.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.149 ±(99.9%) 5.644 ops/ms [Average]
  (min, avg, max) = (7.800, 8.149, 8.389), stdev = 0.309
  CI (99.9%): [2.504, 13.793] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.146 ops/ms
# Warmup Iteration   2: 6.921 ops/ms
# Warmup Iteration   3: 7.056 ops/ms
Iteration   1: 7.226 ops/ms
Iteration   2: 6.980 ops/ms
Iteration   3: 7.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.220 ±(99.9%) 4.334 ops/ms [Average]
  (min, avg, max) = (6.980, 7.220, 7.455), stdev = 0.238
  CI (99.9%): [2.886, 11.554] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.614 ops/ms
# Warmup Iteration   2: 5.183 ops/ms
# Warmup Iteration   3: 5.510 ops/ms
Iteration   1: 5.860 ops/ms
Iteration   2: 5.868 ops/ms
Iteration   3: 6.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.957 ±(99.9%) 2.950 ops/ms [Average]
  (min, avg, max) = (5.860, 5.957, 6.144), stdev = 0.162
  CI (99.9%): [3.007, 8.908] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.855 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.676 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.392 ±(99.9%) 0.009 ms/op
Iteration   1: 4.400 ±(99.9%) 0.004 ms/op
Iteration   2: 4.334 ±(99.9%) 0.002 ms/op
Iteration   3: 4.340 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.358 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (4.334, 4.358, 4.400), stdev = 0.037
  CI (99.9%): [3.691, 5.026] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.125 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.468 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.002 ms/op
Iteration   1: 4.330 ±(99.9%) 0.003 ms/op
Iteration   2: 4.012 ±(99.9%) 0.004 ms/op
Iteration   3: 4.068 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.137 ±(99.9%) 3.104 ms/op [Average]
  (min, avg, max) = (4.012, 4.137, 4.330), stdev = 0.170
  CI (99.9%): [1.033, 7.241] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.579 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.734 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.466 ±(99.9%) 0.005 ms/op
Iteration   1: 4.161 ±(99.9%) 0.004 ms/op
Iteration   2: 4.326 ±(99.9%) 0.002 ms/op
Iteration   3: 4.325 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.271 ±(99.9%) 1.730 ms/op [Average]
  (min, avg, max) = (4.161, 4.271, 4.326), stdev = 0.095
  CI (99.9%): [2.541, 6.001] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.032 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.898 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.411 ±(99.9%) 0.018 ms/op
Iteration   1: 5.420 ±(99.9%) 0.010 ms/op
Iteration   2: 5.273 ±(99.9%) 0.012 ms/op
Iteration   3: 5.432 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.375 ±(99.9%) 1.618 ms/op [Average]
  (min, avg, max) = (5.273, 5.375, 5.432), stdev = 0.089
  CI (99.9%): [3.757, 6.993] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.720 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.686 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.435 ±(99.9%) 0.015 ms/op
Iteration   1: 4.287 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   4.190 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   5.816 ms/op
                 createUser·p0.99:   7.143 ms/op
                 createUser·p0.999:  12.648 ms/op
                 createUser·p0.9999: 15.976 ms/op
                 createUser·p1.00:   16.450 ms/op

Iteration   2: 4.230 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   4.112 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  13.894 ms/op
                 createUser·p0.9999: 27.001 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   3: 4.407 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   7.324 ms/op
                 createUser·p0.999:  13.206 ms/op
                 createUser·p0.9999: 19.595 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222815
  mean =      4.307 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3895 
    [ 2.500,  5.000) = 179518 
    [ 5.000,  7.500) = 37747 
    [ 7.500, 10.000) = 1192 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     13.061 ms/op
     p(99.9900) =     26.140 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.141 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.579 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.011 ms/op
Iteration   1: 3.951 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.891 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  12.124 ms/op
                 existUser·p0.9999: 18.380 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   2: 4.074 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.464 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  14.327 ms/op
                 existUser·p0.9999: 18.229 ms/op
                 existUser·p1.00:   18.743 ms/op

Iteration   3: 4.240 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   4.145 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   7.029 ms/op
                 existUser·p0.999:  12.326 ms/op
                 existUser·p0.9999: 21.886 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 234875
  mean =      4.085 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4192 
    [ 2.500,  5.000) = 203930 
    [ 5.000,  7.500) = 25088 
    [ 7.500, 10.000) = 1205 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     12.501 ms/op
     p(99.9900) =     19.121 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.322 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.880 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.378 ±(99.9%) 0.013 ms/op
Iteration   1: 4.419 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   7.803 ms/op
                 getUser·p0.999:  14.519 ms/op
                 getUser·p0.9999: 19.318 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   2: 4.337 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.923 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  13.795 ms/op
                 getUser·p0.9999: 18.248 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   3: 4.272 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   4.116 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  13.061 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 220907
  mean =      4.342 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3530 
    [ 2.500,  5.000) = 176466 
    [ 5.000,  7.500) = 38304 
    [ 7.500, 10.000) = 1912 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     13.780 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     19.928 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 8.825 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 5.921 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.378 ±(99.9%) 0.019 ms/op
Iteration   1: 5.437 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   7.102 ms/op
                 listUser·p0.95:   8.151 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 19.897 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   2: 5.652 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  17.152 ms/op
                 listUser·p0.9999: 20.480 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   3: 5.533 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.821 ms/op
                 listUser·p0.50:   5.300 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.126 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  18.714 ms/op
                 listUser·p0.9999: 22.180 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173273
  mean =      5.539 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189 
    [ 2.500,  5.000) = 66507 
    [ 5.000,  7.500) = 91745 
    [ 7.500, 10.000) = 12548 
    [10.000, 12.500) = 1639 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.739 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.225 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     17.522 ms/op
     p(99.9900) =     21.081 ms/op
     p(99.9990) =     22.986 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.244 ± 1.550  ops/ms
ClientGrpc.existUser                       thrpt       3   8.149 ± 5.644  ops/ms
ClientGrpc.getUser                         thrpt       3   7.220 ± 4.334  ops/ms
ClientGrpc.listUser                        thrpt       3   5.957 ± 2.950  ops/ms
ClientGrpc.createUser                       avgt       3   4.358 ± 0.667   ms/op
ClientGrpc.existUser                        avgt       3   4.137 ± 3.104   ms/op
ClientGrpc.getUser                          avgt       3   4.271 ± 1.730   ms/op
ClientGrpc.listUser                         avgt       3   5.375 ± 1.618   ms/op
ClientGrpc.createUser                     sample  222815   4.307 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.000           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.382           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.816           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.111           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.061           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.140           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.197           ms/op
ClientGrpc.existUser                      sample  234875   4.085 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.837           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.079           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.497           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.963           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.501           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.121           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.151           ms/op
ClientGrpc.getUser                        sample  220907   4.342 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.001           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.956           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.791           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.780           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.300           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.021           ms/op
ClientGrpc.listUser                       sample  173273   5.539 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.739           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.274           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.225           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.404           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.522           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.081           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.298           ms/op
