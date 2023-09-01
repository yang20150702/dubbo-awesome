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
# Warmup Iteration   1: 4.637 ops/ms
# Warmup Iteration   2: 9.175 ops/ms
# Warmup Iteration   3: 10.280 ops/ms
Iteration   1: 10.495 ops/ms
Iteration   2: 10.463 ops/ms
Iteration   3: 10.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.612 ±(99.9%) 4.208 ops/ms [Average]
  (min, avg, max) = (10.463, 10.612, 10.878), stdev = 0.231
  CI (99.9%): [6.403, 14.820] (assumes normal distribution)


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
# Warmup Iteration   1: 7.919 ops/ms
# Warmup Iteration   2: 10.691 ops/ms
# Warmup Iteration   3: 11.163 ops/ms
Iteration   1: 11.132 ops/ms
Iteration   2: 11.172 ops/ms
Iteration   3: 11.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.215 ±(99.9%) 2.023 ops/ms [Average]
  (min, avg, max) = (11.132, 11.215, 11.341), stdev = 0.111
  CI (99.9%): [9.192, 13.238] (assumes normal distribution)


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
# Warmup Iteration   1: 7.559 ops/ms
# Warmup Iteration   2: 10.494 ops/ms
# Warmup Iteration   3: 10.783 ops/ms
Iteration   1: 10.845 ops/ms
Iteration   2: 10.689 ops/ms
Iteration   3: 10.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.718 ±(99.9%) 2.087 ops/ms [Average]
  (min, avg, max) = (10.622, 10.718, 10.845), stdev = 0.114
  CI (99.9%): [8.631, 12.806] (assumes normal distribution)


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
# Warmup Iteration   1: 6.405 ops/ms
# Warmup Iteration   2: 8.068 ops/ms
# Warmup Iteration   3: 8.303 ops/ms
Iteration   1: 8.401 ops/ms
Iteration   2: 8.398 ops/ms
Iteration   3: 8.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.444 ±(99.9%) 1.404 ops/ms [Average]
  (min, avg, max) = (8.398, 8.444, 8.533), stdev = 0.077
  CI (99.9%): [7.039, 9.848] (assumes normal distribution)


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.003 ms/op
Iteration   1: 2.967 ±(99.9%) 0.003 ms/op
Iteration   2: 2.988 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.973 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (2.965, 2.973, 2.988), stdev = 0.012
  CI (99.9%): [2.747, 3.200] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.919 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.860 ±(99.9%) 0.008 ms/op
Iteration   1: 2.872 ±(99.9%) 0.004 ms/op
Iteration   2: 2.869 ±(99.9%) 0.003 ms/op
Iteration   3: 2.868 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.869 ±(99.9%) 0.038 ms/op [Average]
  (min, avg, max) = (2.868, 2.869, 2.872), stdev = 0.002
  CI (99.9%): [2.831, 2.907] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.813 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.002 ms/op
Iteration   1: 2.982 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
Iteration   3: 3.000 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.988 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (2.981, 2.988, 3.000), stdev = 0.011
  CI (99.9%): [2.794, 3.181] (assumes normal distribution)


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
# Warmup Iteration   1: 4.585 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.031 ms/op
Iteration   1: 3.797 ±(99.9%) 0.013 ms/op
Iteration   2: 3.812 ±(99.9%) 0.010 ms/op
Iteration   3: 3.754 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.788 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (3.754, 3.788, 3.812), stdev = 0.030
  CI (99.9%): [3.236, 4.339] (assumes normal distribution)


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
# Warmup Iteration   1: 4.435 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.008 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  9.503 ms/op
                 createUser·p0.9999: 15.343 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   2: 3.043 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  9.003 ms/op
                 createUser·p0.9999: 17.138 ms/op
                 createUser·p1.00:   17.596 ms/op

Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  7.784 ms/op
                 createUser·p0.9999: 18.252 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315137
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 857 
    [ 1.250,  2.500) = 21000 
    [ 2.500,  3.750) = 275610 
    [ 3.750,  5.000) = 15570 
    [ 5.000,  6.250) = 1009 
    [ 6.250,  7.500) = 389 
    [ 7.500,  8.750) = 342 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 3.469 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.969 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.007 ms/op
Iteration   1: 2.861 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.376 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.801 ms/op
                 existUser·p0.999:  7.742 ms/op
                 existUser·p0.9999: 12.747 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   2: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.510 ms/op
                 existUser·p0.9999: 16.842 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 2.867 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  6.545 ms/op
                 existUser·p0.9999: 14.746 ms/op
                 existUser·p1.00:   15.122 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333588
  mean =      2.877 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3350 
    [ 1.250,  2.500) = 42569 
    [ 2.500,  3.750) = 275813 
    [ 3.750,  5.000) = 9903 
    [ 5.000,  6.250) = 1110 
    [ 6.250,  7.500) = 505 
    [ 7.500,  8.750) = 125 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.376 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      7.507 ms/op
     p(99.9900) =     15.105 ms/op
     p(99.9990) =     17.061 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 2.987 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  8.686 ms/op
                 getUser·p0.9999: 16.476 ms/op
                 getUser·p1.00:   23.790 ms/op

Iteration   2: 2.976 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.450 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.794 ms/op
                 getUser·p0.9999: 23.069 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.247 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  8.266 ms/op
                 getUser·p0.9999: 15.925 ms/op
                 getUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322312
  mean =      2.979 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28207 
    [ 2.500,  5.000) = 292155 
    [ 5.000,  7.500) = 1421 
    [ 7.500, 10.000) = 333 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.247 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.045 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     23.192 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 5.454 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.010 ms/op
Iteration   1: 3.763 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.792 ms/op
                 listUser·p0.999:  12.157 ms/op
                 listUser·p0.9999: 15.507 ms/op
                 listUser·p1.00:   16.204 ms/op

Iteration   2: 3.785 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  16.044 ms/op
                 listUser·p0.9999: 26.339 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   3: 3.845 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.806 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  16.166 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252877
  mean =      3.797 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6623 
    [ 2.500,  5.000) = 223908 
    [ 5.000,  7.500) = 20921 
    [ 7.500, 10.000) = 909 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     15.075 ms/op
     p(99.9900) =     22.535 ms/op
     p(99.9990) =     26.932 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.612 ± 4.208  ops/ms
ClientGrpc.existUser                       thrpt       3  11.215 ± 2.023  ops/ms
ClientGrpc.getUser                         thrpt       3  10.718 ± 2.087  ops/ms
ClientGrpc.listUser                        thrpt       3   8.444 ± 1.404  ops/ms
ClientGrpc.createUser                       avgt       3   2.973 ± 0.227   ms/op
ClientGrpc.existUser                        avgt       3   2.869 ± 0.038   ms/op
ClientGrpc.getUser                          avgt       3   2.988 ± 0.194   ms/op
ClientGrpc.listUser                         avgt       3   3.788 ± 0.552   ms/op
ClientGrpc.createUser                     sample  315137   3.046 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.604           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.372           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.891           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.547           ms/op
ClientGrpc.existUser                      sample  333588   2.877 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.376           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.507           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.105           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.269           ms/op
ClientGrpc.getUser                        sample  322312   2.979 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.247           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.437           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.045           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.643           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.790           ms/op
ClientGrpc.listUser                       sample  252877   3.797 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.806           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.075           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.535           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.066           ms/op
