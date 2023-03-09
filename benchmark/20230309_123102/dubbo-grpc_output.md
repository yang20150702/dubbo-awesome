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
# Warmup Iteration   1: 1.904 ops/ms
# Warmup Iteration   2: 5.332 ops/ms
# Warmup Iteration   3: 7.051 ops/ms
Iteration   1: 7.512 ops/ms
Iteration   2: 7.340 ops/ms
Iteration   3: 7.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.449 ±(99.9%) 1.731 ops/ms [Average]
  (min, avg, max) = (7.340, 7.449, 7.512), stdev = 0.095
  CI (99.9%): [5.718, 9.180] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.680 ops/ms
# Warmup Iteration   2: 7.640 ops/ms
# Warmup Iteration   3: 8.157 ops/ms
Iteration   1: 8.177 ops/ms
Iteration   2: 8.579 ops/ms
Iteration   3: 8.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.364 ±(99.9%) 3.700 ops/ms [Average]
  (min, avg, max) = (8.177, 8.364, 8.579), stdev = 0.203
  CI (99.9%): [4.664, 12.063] (assumes normal distribution)


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
# Warmup Iteration   1: 4.670 ops/ms
# Warmup Iteration   2: 6.367 ops/ms
# Warmup Iteration   3: 7.493 ops/ms
Iteration   1: 7.704 ops/ms
Iteration   2: 7.334 ops/ms
Iteration   3: 7.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.550 ±(99.9%) 3.512 ops/ms [Average]
  (min, avg, max) = (7.334, 7.550, 7.704), stdev = 0.192
  CI (99.9%): [4.039, 11.062] (assumes normal distribution)


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
# Warmup Iteration   1: 3.728 ops/ms
# Warmup Iteration   2: 5.529 ops/ms
# Warmup Iteration   3: 5.898 ops/ms
Iteration   1: 6.100 ops/ms
Iteration   2: 6.106 ops/ms
Iteration   3: 6.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.134 ±(99.9%) 0.985 ops/ms [Average]
  (min, avg, max) = (6.100, 6.134, 6.197), stdev = 0.054
  CI (99.9%): [5.150, 7.119] (assumes normal distribution)


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
# Warmup Iteration   1: 6.442 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.408 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.192 ±(99.9%) 0.012 ms/op
Iteration   1: 4.131 ±(99.9%) 0.004 ms/op
Iteration   2: 4.059 ±(99.9%) 0.003 ms/op
Iteration   3: 4.052 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.080 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (4.052, 4.080, 4.131), stdev = 0.043
  CI (99.9%): [3.288, 4.873] (assumes normal distribution)


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
# Warmup Iteration   1: 5.955 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.003 ms/op
Iteration   1: 3.990 ±(99.9%) 0.002 ms/op
Iteration   2: 3.877 ±(99.9%) 0.003 ms/op
Iteration   3: 3.771 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.880 ±(99.9%) 1.994 ms/op [Average]
  (min, avg, max) = (3.771, 3.880, 3.990), stdev = 0.109
  CI (99.9%): [1.885, 5.874] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.597 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.003 ms/op
Iteration   1: 4.103 ±(99.9%) 0.003 ms/op
Iteration   2: 4.082 ±(99.9%) 0.005 ms/op
Iteration   3: 4.081 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.088 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (4.081, 4.088, 4.103), stdev = 0.012
  CI (99.9%): [3.862, 4.314] (assumes normal distribution)


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
# Warmup Iteration   1: 7.691 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.781 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.263 ±(99.9%) 0.017 ms/op
Iteration   1: 5.263 ±(99.9%) 0.025 ms/op
Iteration   2: 5.189 ±(99.9%) 0.015 ms/op
Iteration   3: 5.161 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.204 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (5.161, 5.204, 5.263), stdev = 0.053
  CI (99.9%): [4.242, 6.166] (assumes normal distribution)


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
# Warmup Iteration   1: 6.728 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.012 ms/op
Iteration   1: 4.061 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   5.054 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  10.092 ms/op
                 createUser·p0.9999: 26.087 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   2: 4.090 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  9.563 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   3: 4.061 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   5.014 ms/op
                 createUser·p0.95:   5.472 ms/op
                 createUser·p0.99:   7.371 ms/op
                 createUser·p0.999:  14.516 ms/op
                 createUser·p0.9999: 25.203 ms/op
                 createUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 235782
  mean =      4.071 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5632 
    [ 2.500,  5.000) = 204565 
    [ 5.000,  7.500) = 23964 
    [ 7.500, 10.000) = 1272 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     12.124 ms/op
     p(99.9900) =     25.212 ms/op
     p(99.9990) =     28.163 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 5.684 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.010 ms/op
Iteration   1: 3.885 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.486 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 20.021 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   2: 3.823 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  10.114 ms/op
                 existUser·p0.9999: 17.257 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   3: 3.763 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 33.587 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 250999
  mean =      3.823 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6231 
    [ 2.500,  5.000) = 232038 
    [ 5.000,  7.500) = 11736 
    [ 7.500, 10.000) = 712 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     10.338 ms/op
     p(99.9900) =     33.220 ms/op
     p(99.9990) =     33.783 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 5.961 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.197 ±(99.9%) 0.011 ms/op
Iteration   1: 4.104 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  13.254 ms/op
                 getUser·p0.9999: 17.668 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   2: 4.139 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.223 ms/op
                 getUser·p0.50:   4.014 ms/op
                 getUser·p0.90:   5.087 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  12.819 ms/op
                 getUser·p0.9999: 29.009 ms/op
                 getUser·p1.00:   29.491 ms/op

Iteration   3: 4.180 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   4.067 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.579 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  11.101 ms/op
                 getUser·p0.9999: 22.425 ms/op
                 getUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 231746
  mean =      4.141 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3935 
    [ 2.500,  5.000) = 199614 
    [ 5.000,  7.500) = 26855 
    [ 7.500, 10.000) = 966 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     12.747 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     29.448 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 8.041 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.588 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.161 ±(99.9%) 0.016 ms/op
Iteration   1: 5.183 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   6.930 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   9.748 ms/op
                 listUser·p0.999:  15.570 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   2: 5.149 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   6.586 ms/op
                 listUser·p0.95:   7.594 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 20.958 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 5.290 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.873 ms/op
                 listUser·p0.99:   10.338 ms/op
                 listUser·p0.999:  23.233 ms/op
                 listUser·p0.9999: 34.797 ms/op
                 listUser·p1.00:   38.535 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184234
  mean =      5.207 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 201 
    [ 2.500,  5.000) = 97646 
    [ 5.000,  7.500) = 75270 
    [ 7.500, 10.000) = 9328 
    [10.000, 12.500) = 1236 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.791 ms/op
     p(95.0000) =      7.741 ms/op
     p(99.0000) =      9.961 ms/op
     p(99.9000) =     17.753 ms/op
     p(99.9900) =     31.336 ms/op
     p(99.9990) =     36.051 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.449 ± 1.731  ops/ms
ClientGrpc.existUser                       thrpt       3   8.364 ± 3.700  ops/ms
ClientGrpc.getUser                         thrpt       3   7.550 ± 3.512  ops/ms
ClientGrpc.listUser                        thrpt       3   6.134 ± 0.985  ops/ms
ClientGrpc.createUser                       avgt       3   4.080 ± 0.793   ms/op
ClientGrpc.existUser                        avgt       3   3.880 ± 1.994   ms/op
ClientGrpc.getUser                          avgt       3   4.088 ± 0.226   ms/op
ClientGrpc.listUser                         avgt       3   5.204 ± 0.962   ms/op
ClientGrpc.createUser                     sample  235782   4.071 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.633           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.054           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.489           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.930           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.124           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.212           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.672           ms/op
ClientGrpc.existUser                      sample  250999   3.823 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.909           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.612           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.014           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.210           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.338           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.220           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.882           ms/op
ClientGrpc.getUser                        sample  231746   4.141 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.075           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.030           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.112           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.791           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.747           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.919           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.491           ms/op
ClientGrpc.listUser                       sample  184234   5.207 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.430           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.741           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.961           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.753           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.336           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.535           ms/op
