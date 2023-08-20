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
# Warmup Iteration   1: 3.486 ops/ms
# Warmup Iteration   2: 7.125 ops/ms
# Warmup Iteration   3: 8.220 ops/ms
Iteration   1: 8.438 ops/ms
Iteration   2: 8.953 ops/ms
Iteration   3: 8.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.744 ±(99.9%) 4.940 ops/ms [Average]
  (min, avg, max) = (8.438, 8.744, 8.953), stdev = 0.271
  CI (99.9%): [3.804, 13.684] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.770 ops/ms
# Warmup Iteration   2: 8.737 ops/ms
# Warmup Iteration   3: 9.146 ops/ms
Iteration   1: 9.364 ops/ms
Iteration   2: 9.292 ops/ms
Iteration   3: 9.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.283 ±(99.9%) 1.568 ops/ms [Average]
  (min, avg, max) = (9.193, 9.283, 9.364), stdev = 0.086
  CI (99.9%): [7.716, 10.851] (assumes normal distribution)


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
# Warmup Iteration   1: 5.802 ops/ms
# Warmup Iteration   2: 8.220 ops/ms
# Warmup Iteration   3: 8.662 ops/ms
Iteration   1: 8.682 ops/ms
Iteration   2: 8.794 ops/ms
Iteration   3: 8.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.762 ±(99.9%) 1.270 ops/ms [Average]
  (min, avg, max) = (8.682, 8.762, 8.810), stdev = 0.070
  CI (99.9%): [7.491, 10.032] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.556 ops/ms
# Warmup Iteration   2: 5.712 ops/ms
# Warmup Iteration   3: 6.546 ops/ms
Iteration   1: 6.591 ops/ms
Iteration   2: 6.672 ops/ms
Iteration   3: 6.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.640 ±(99.9%) 0.793 ops/ms [Average]
  (min, avg, max) = (6.591, 6.640, 6.672), stdev = 0.043
  CI (99.9%): [5.847, 7.433] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.391 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.011 ms/op
Iteration   1: 3.664 ±(99.9%) 0.003 ms/op
Iteration   2: 3.624 ±(99.9%) 0.004 ms/op
Iteration   3: 3.612 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.634 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (3.612, 3.634, 3.664), stdev = 0.027
  CI (99.9%): [3.136, 4.132] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.303 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.004 ms/op
Iteration   1: 3.411 ±(99.9%) 0.003 ms/op
Iteration   2: 3.232 ±(99.9%) 0.004 ms/op
Iteration   3: 3.409 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.351 ±(99.9%) 1.875 ms/op [Average]
  (min, avg, max) = (3.232, 3.351, 3.411), stdev = 0.103
  CI (99.9%): [1.476, 5.226] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.161 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.651 ±(99.9%) 0.005 ms/op
Iteration   1: 3.633 ±(99.9%) 0.004 ms/op
Iteration   2: 3.615 ±(99.9%) 0.004 ms/op
Iteration   3: 3.647 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.632 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (3.615, 3.632, 3.647), stdev = 0.016
  CI (99.9%): [3.346, 3.917] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.897 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.081 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 4.774 ±(99.9%) 0.011 ms/op
Iteration   1: 4.536 ±(99.9%) 0.012 ms/op
Iteration   2: 4.730 ±(99.9%) 0.009 ms/op
Iteration   3: 4.749 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.672 ±(99.9%) 2.142 ms/op [Average]
  (min, avg, max) = (4.536, 4.672, 4.749), stdev = 0.117
  CI (99.9%): [2.529, 6.814] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.714 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.731 ±(99.9%) 0.009 ms/op
Iteration   1: 3.731 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  12.288 ms/op
                 createUser·p0.9999: 16.112 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   2: 3.653 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  9.837 ms/op
                 createUser·p0.9999: 18.645 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   3: 3.734 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  10.957 ms/op
                 createUser·p0.9999: 24.689 ms/op
                 createUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258895
  mean =      3.706 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6251 
    [ 2.500,  5.000) = 245799 
    [ 5.000,  7.500) = 5794 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     10.846 ms/op
     p(99.9900) =     21.143 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.090 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.008 ms/op
Iteration   1: 3.461 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  9.275 ms/op
                 existUser·p0.9999: 21.152 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   2: 3.347 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  11.310 ms/op
                 existUser·p0.9999: 21.159 ms/op
                 existUser·p1.00:   22.020 ms/op

Iteration   3: 3.564 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  17.400 ms/op
                 existUser·p0.9999: 19.530 ms/op
                 existUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277859
  mean =      3.455 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17011 
    [ 2.500,  5.000) = 256168 
    [ 5.000,  7.500) = 3929 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     11.651 ms/op
     p(99.9900) =     20.847 ms/op
     p(99.9990) =     21.936 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 5.206 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.712 ±(99.9%) 0.010 ms/op
Iteration   1: 3.701 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  10.837 ms/op
                 getUser·p0.9999: 14.948 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 3.735 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  13.359 ms/op
                 getUser·p0.9999: 18.823 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   3: 3.672 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  9.400 ms/op
                 getUser·p0.9999: 21.342 ms/op
                 getUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259268
  mean =      3.702 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7917 
    [ 2.500,  5.000) = 244664 
    [ 5.000,  7.500) = 5921 
    [ 7.500, 10.000) = 483 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     10.387 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 6.780 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.134 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.757 ±(99.9%) 0.013 ms/op
Iteration   1: 4.649 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  14.799 ms/op
                 listUser·p0.9999: 18.587 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   2: 4.708 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.756 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   6.840 ms/op
                 listUser·p0.99:   8.502 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 19.798 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 4.736 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   6.070 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   8.663 ms/op
                 listUser·p0.999:  22.131 ms/op
                 listUser·p0.9999: 28.071 ms/op
                 listUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204497
  mean =      4.697 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 476 
    [ 2.500,  5.000) = 160493 
    [ 5.000,  7.500) = 38543 
    [ 7.500, 10.000) = 4192 
    [10.000, 12.500) = 391 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.874 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     29.566 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.744 ± 4.940  ops/ms
ClientGrpc.existUser                       thrpt       3   9.283 ± 1.568  ops/ms
ClientGrpc.getUser                         thrpt       3   8.762 ± 1.270  ops/ms
ClientGrpc.listUser                        thrpt       3   6.640 ± 0.793  ops/ms
ClientGrpc.createUser                       avgt       3   3.634 ± 0.498   ms/op
ClientGrpc.existUser                        avgt       3   3.351 ± 1.875   ms/op
ClientGrpc.getUser                          avgt       3   3.632 ± 0.286   ms/op
ClientGrpc.listUser                         avgt       3   4.672 ± 2.142   ms/op
ClientGrpc.createUser                     sample  258895   3.706 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.721           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.931           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.846           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.143           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.230           ms/op
ClientGrpc.existUser                      sample  277859   3.455 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.581           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.055           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.651           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.847           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.020           ms/op
ClientGrpc.getUser                        sample  259268   3.702 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.898           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.661           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.710           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.387           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.988           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.413           ms/op
ClientGrpc.listUser                       sample  204497   4.697 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.756           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.438           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.007           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.263           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.540           ms/op
