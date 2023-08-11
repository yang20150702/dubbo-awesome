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
# Warmup Iteration   1: 4.557 ops/ms
# Warmup Iteration   2: 9.138 ops/ms
# Warmup Iteration   3: 10.140 ops/ms
Iteration   1: 10.514 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.600 ±(99.9%) 1.516 ops/ms [Average]
  (min, avg, max) = (10.514, 10.600, 10.680), stdev = 0.083
  CI (99.9%): [9.084, 12.115] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.189 ops/ms
# Warmup Iteration   2: 10.880 ops/ms
# Warmup Iteration   3: 11.225 ops/ms
Iteration   1: 11.406 ops/ms
Iteration   2: 11.570 ops/ms
Iteration   3: 11.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.545 ±(99.9%) 2.344 ops/ms [Average]
  (min, avg, max) = (11.406, 11.545, 11.659), stdev = 0.128
  CI (99.9%): [9.201, 13.889] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.946 ops/ms
# Warmup Iteration   2: 10.354 ops/ms
# Warmup Iteration   3: 10.625 ops/ms
Iteration   1: 10.621 ops/ms
Iteration   2: 10.653 ops/ms
Iteration   3: 10.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.671 ±(99.9%) 1.106 ops/ms [Average]
  (min, avg, max) = (10.621, 10.671, 10.739), stdev = 0.061
  CI (99.9%): [9.566, 11.777] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.570 ops/ms
# Warmup Iteration   2: 7.817 ops/ms
# Warmup Iteration   3: 8.349 ops/ms
Iteration   1: 8.336 ops/ms
Iteration   2: 8.218 ops/ms
Iteration   3: 8.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.260 ±(99.9%) 1.198 ops/ms [Average]
  (min, avg, max) = (8.218, 8.260, 8.336), stdev = 0.066
  CI (99.9%): [7.062, 9.458] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.033 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.004 ms/op
Iteration   1: 2.984 ±(99.9%) 0.009 ms/op
Iteration   2: 2.969 ±(99.9%) 0.002 ms/op
Iteration   3: 2.928 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.960 ±(99.9%) 0.534 ms/op [Average]
  (min, avg, max) = (2.928, 2.960, 2.984), stdev = 0.029
  CI (99.9%): [2.426, 3.494] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.920 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.003 ms/op
Iteration   1: 2.820 ±(99.9%) 0.004 ms/op
Iteration   2: 2.807 ±(99.9%) 0.003 ms/op
Iteration   3: 2.901 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.843 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (2.807, 2.843, 2.901), stdev = 0.051
  CI (99.9%): [1.913, 3.773] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.735 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
Iteration   1: 2.978 ±(99.9%) 0.003 ms/op
Iteration   2: 2.956 ±(99.9%) 0.003 ms/op
Iteration   3: 2.981 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.971 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (2.956, 2.971, 2.981), stdev = 0.013
  CI (99.9%): [2.728, 3.215] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.241 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.017 ms/op
Iteration   1: 3.879 ±(99.9%) 0.010 ms/op
Iteration   2: 3.835 ±(99.9%) 0.027 ms/op
Iteration   3: 3.820 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.845 ±(99.9%) 0.558 ms/op [Average]
  (min, avg, max) = (3.820, 3.845, 3.879), stdev = 0.031
  CI (99.9%): [3.286, 4.403] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.803 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  7.537 ms/op
                 createUser·p0.9999: 17.145 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   2: 2.935 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.505 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  8.273 ms/op
                 createUser·p0.9999: 19.011 ms/op
                 createUser·p1.00:   19.923 ms/op

Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.568 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  12.953 ms/op
                 createUser·p0.9999: 25.854 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323208
  mean =      2.970 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37362 
    [ 2.500,  5.000) = 283389 
    [ 5.000,  7.500) = 1918 
    [ 7.500, 10.000) = 212 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =     10.200 ms/op
     p(99.9900) =     22.504 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.793 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.914 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.842 ±(99.9%) 0.007 ms/op
Iteration   1: 2.838 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  6.982 ms/op
                 existUser·p0.9999: 12.701 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   2: 2.839 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.486 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  9.542 ms/op
                 existUser·p0.9999: 14.601 ms/op
                 existUser·p1.00:   16.728 ms/op

Iteration   3: 2.855 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.946 ms/op
                 existUser·p0.9999: 17.289 ms/op
                 existUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337471
  mean =      2.844 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3833 
    [ 1.250,  2.500) = 53780 
    [ 2.500,  3.750) = 269454 
    [ 3.750,  5.000) = 8697 
    [ 5.000,  6.250) = 916 
    [ 6.250,  7.500) = 425 
    [ 7.500,  8.750) = 131 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.615 ms/op
     p(99.9900) =     15.774 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.007 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.409 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  9.077 ms/op
                 getUser·p0.9999: 12.599 ms/op
                 getUser·p1.00:   12.861 ms/op

Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.404 ms/op
                 getUser·p0.9999: 18.193 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   3: 2.946 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.148 ms/op
                 getUser·p0.9999: 20.681 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324045
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34624 
    [ 2.500,  5.000) = 287805 
    [ 5.000,  7.500) = 1155 
    [ 7.500, 10.000) = 256 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.409 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     19.776 ms/op
     p(99.9990) =     22.391 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 5.139 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.011 ms/op
Iteration   1: 3.868 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  11.948 ms/op
                 listUser·p0.9999: 16.965 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   2: 3.842 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  13.067 ms/op
                 listUser·p0.9999: 18.372 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 3.861 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.635 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  15.928 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248722
  mean =      3.857 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5158 
    [ 2.500,  5.000) = 225250 
    [ 5.000,  7.500) = 16990 
    [ 7.500, 10.000) = 846 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.781 ms/op
     p(99.9000) =     13.633 ms/op
     p(99.9900) =     18.518 ms/op
     p(99.9990) =     19.940 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.600 ± 1.516  ops/ms
ClientGrpc.existUser                       thrpt       3  11.545 ± 2.344  ops/ms
ClientGrpc.getUser                         thrpt       3  10.671 ± 1.106  ops/ms
ClientGrpc.listUser                        thrpt       3   8.260 ± 1.198  ops/ms
ClientGrpc.createUser                       avgt       3   2.960 ± 0.534   ms/op
ClientGrpc.existUser                        avgt       3   2.843 ± 0.930   ms/op
ClientGrpc.getUser                          avgt       3   2.971 ± 0.243   ms/op
ClientGrpc.listUser                         avgt       3   3.845 ± 0.558   ms/op
ClientGrpc.createUser                     sample  323208   2.970 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.568           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.945           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.200           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.504           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.214           ms/op
ClientGrpc.existUser                      sample  337471   2.844 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.486           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.615           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.774           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.088           ms/op
ClientGrpc.getUser                        sample  324045   2.961 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.409           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.086           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.776           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.938           ms/op
ClientGrpc.listUser                       sample  248722   3.857 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.635           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.723           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.781           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.633           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.518           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.513           ms/op
