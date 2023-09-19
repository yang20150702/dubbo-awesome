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
# Warmup Iteration   1: 2.129 ops/ms
# Warmup Iteration   2: 4.684 ops/ms
# Warmup Iteration   3: 6.211 ops/ms
Iteration   1: 6.603 ops/ms
Iteration   2: 6.777 ops/ms
Iteration   3: 6.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.748 ±(99.9%) 2.417 ops/ms [Average]
  (min, avg, max) = (6.603, 6.748, 6.863), stdev = 0.132
  CI (99.9%): [4.331, 9.165] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.332 ops/ms
# Warmup Iteration   2: 6.677 ops/ms
# Warmup Iteration   3: 7.200 ops/ms
Iteration   1: 7.367 ops/ms
Iteration   2: 7.278 ops/ms
Iteration   3: 7.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.395 ±(99.9%) 2.436 ops/ms [Average]
  (min, avg, max) = (7.278, 7.395, 7.541), stdev = 0.134
  CI (99.9%): [4.960, 9.831] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.807 ops/ms
# Warmup Iteration   2: 6.341 ops/ms
# Warmup Iteration   3: 6.604 ops/ms
Iteration   1: 6.704 ops/ms
Iteration   2: 6.758 ops/ms
Iteration   3: 6.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.774 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (6.704, 6.774, 6.861), stdev = 0.080
  CI (99.9%): [5.313, 8.235] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.431 ops/ms
# Warmup Iteration   2: 5.151 ops/ms
# Warmup Iteration   3: 5.496 ops/ms
Iteration   1: 5.408 ops/ms
Iteration   2: 5.633 ops/ms
Iteration   3: 5.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.590 ±(99.9%) 3.010 ops/ms [Average]
  (min, avg, max) = (5.408, 5.590, 5.730), stdev = 0.165
  CI (99.9%): [2.580, 8.601] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.809 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.656 ±(99.9%) 0.008 ms/op
Iteration   1: 4.577 ±(99.9%) 0.004 ms/op
Iteration   2: 4.758 ±(99.9%) 0.004 ms/op
Iteration   3: 4.560 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.632 ±(99.9%) 2.005 ms/op [Average]
  (min, avg, max) = (4.560, 4.632, 4.758), stdev = 0.110
  CI (99.9%): [2.627, 6.637] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.627 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.634 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.363 ±(99.9%) 0.004 ms/op
Iteration   1: 4.189 ±(99.9%) 0.004 ms/op
Iteration   2: 4.233 ±(99.9%) 0.002 ms/op
Iteration   3: 4.226 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.216 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (4.189, 4.216, 4.233), stdev = 0.023
  CI (99.9%): [3.789, 4.643] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.754 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.817 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.007 ms/op
Iteration   1: 4.510 ±(99.9%) 0.003 ms/op
Iteration   2: 4.431 ±(99.9%) 0.004 ms/op
Iteration   3: 4.562 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.501 ±(99.9%) 1.196 ms/op [Average]
  (min, avg, max) = (4.431, 4.501, 4.562), stdev = 0.066
  CI (99.9%): [3.305, 5.697] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.051 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 6.423 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.978 ±(99.9%) 0.014 ms/op
Iteration   1: 5.688 ±(99.9%) 0.012 ms/op
Iteration   2: 5.596 ±(99.9%) 0.014 ms/op
Iteration   3: 5.841 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.708 ±(99.9%) 2.253 ms/op [Average]
  (min, avg, max) = (5.596, 5.708, 5.841), stdev = 0.124
  CI (99.9%): [3.455, 7.962] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.282 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.969 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.819 ±(99.9%) 0.017 ms/op
Iteration   1: 4.763 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   4.645 ms/op
                 createUser·p0.90:   5.931 ms/op
                 createUser·p0.95:   6.463 ms/op
                 createUser·p0.99:   8.307 ms/op
                 createUser·p0.999:  14.765 ms/op
                 createUser·p0.9999: 21.374 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 4.749 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   4.571 ms/op
                 createUser·p0.90:   5.947 ms/op
                 createUser·p0.95:   6.537 ms/op
                 createUser·p0.99:   9.093 ms/op
                 createUser·p0.999:  23.209 ms/op
                 createUser·p0.9999: 27.501 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   3: 4.771 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   4.547 ms/op
                 createUser·p0.90:   5.915 ms/op
                 createUser·p0.95:   6.529 ms/op
                 createUser·p0.99:   8.831 ms/op
                 createUser·p0.999:  19.710 ms/op
                 createUser·p0.9999: 82.742 ms/op
                 createUser·p1.00:   83.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 201753
  mean =      4.761 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 137825 
    [ 5.000, 10.000) = 62848 
    [10.000, 15.000) = 762 
    [15.000, 20.000) = 137 
    [20.000, 25.000) = 76 
    [25.000, 30.000) = 74 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 1 
    [75.000, 80.000) = 1 
    [80.000, 85.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     82.313 ms/op
     p(99.9990) =     83.228 ms/op
     p(99.9999) =     83.362 ms/op
    p(100.0000) =     83.362 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.531 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.697 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.478 ±(99.9%) 0.014 ms/op
Iteration   1: 4.356 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.579 ms/op
                 existUser·p0.95:   6.103 ms/op
                 existUser·p0.99:   8.086 ms/op
                 existUser·p0.999:  15.352 ms/op
                 existUser·p0.9999: 17.618 ms/op
                 existUser·p1.00:   17.859 ms/op

Iteration   2: 4.510 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   4.366 ms/op
                 existUser·p0.90:   5.669 ms/op
                 existUser·p0.95:   6.136 ms/op
                 existUser·p0.99:   7.954 ms/op
                 existUser·p0.999:  14.175 ms/op
                 existUser·p0.9999: 26.015 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   3: 4.514 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.571 ms/op
                 existUser·p0.95:   5.988 ms/op
                 existUser·p0.99:   7.979 ms/op
                 existUser·p0.999:  13.812 ms/op
                 existUser·p0.9999: 22.408 ms/op
                 existUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 215218
  mean =      4.459 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5101 
    [ 2.500,  5.000) = 161987 
    [ 5.000,  7.500) = 45217 
    [ 7.500, 10.000) = 2165 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      8.018 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     25.476 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.427 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.693 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.546 ±(99.9%) 0.014 ms/op
Iteration   1: 4.647 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   4.481 ms/op
                 getUser·p0.90:   5.767 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  14.696 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   21.758 ms/op

Iteration   2: 4.508 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.029 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  12.960 ms/op
                 getUser·p0.9999: 22.476 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   3: 4.546 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   4.432 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.111 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  11.043 ms/op
                 getUser·p0.9999: 28.175 ms/op
                 getUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 210105
  mean =      4.566 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2747 
    [ 2.500,  5.000) = 153850 
    [ 5.000,  7.500) = 51081 
    [ 7.500, 10.000) = 1706 
    [10.000, 12.500) = 421 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     28.829 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.782 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 6.237 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.802 ±(99.9%) 0.022 ms/op
Iteration   1: 5.805 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   7.643 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.472 ms/op
                 listUser·p0.999:  16.648 ms/op
                 listUser·p0.9999: 22.296 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   2: 5.828 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   10.797 ms/op
                 listUser·p0.999:  19.662 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   3: 5.805 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.520 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  20.185 ms/op
                 listUser·p0.9999: 25.985 ms/op
                 listUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 165269
  mean =      5.813 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 121 
    [ 2.500,  5.000) = 47397 
    [ 5.000,  7.500) = 99577 
    [ 7.500, 10.000) = 15089 
    [10.000, 12.500) = 2215 
    [12.500, 15.000) = 476 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      5.505 ms/op
     p(90.0000) =      7.635 ms/op
     p(95.0000) =      8.618 ms/op
     p(99.0000) =     11.026 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     27.603 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.748 ± 2.417  ops/ms
ClientGrpc.existUser                       thrpt       3   7.395 ± 2.436  ops/ms
ClientGrpc.getUser                         thrpt       3   6.774 ± 1.461  ops/ms
ClientGrpc.listUser                        thrpt       3   5.590 ± 3.010  ops/ms
ClientGrpc.createUser                       avgt       3   4.632 ± 2.005   ms/op
ClientGrpc.existUser                        avgt       3   4.216 ± 0.427   ms/op
ClientGrpc.getUser                          avgt       3   4.501 ± 1.196   ms/op
ClientGrpc.listUser                         avgt       3   5.708 ± 2.253   ms/op
ClientGrpc.createUser                     sample  201753   4.761 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.898           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.931           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.513           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.700           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          19.268           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          82.313           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          83.362           ms/op
ClientGrpc.existUser                      sample  215218   4.459 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.974           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.603           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.078           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.018           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.090           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.476           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.149           ms/op
ClientGrpc.getUser                        sample  210105   4.566 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.859           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.677           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.128           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.692           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.238           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.559           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.967           ms/op
ClientGrpc.listUser                       sample  165269   5.813 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.190           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.635           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.026           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.038           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.495           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.689           ms/op
