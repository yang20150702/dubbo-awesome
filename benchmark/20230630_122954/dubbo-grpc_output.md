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
# Warmup Iteration   1: 4.698 ops/ms
# Warmup Iteration   2: 8.977 ops/ms
# Warmup Iteration   3: 10.376 ops/ms
Iteration   1: 10.808 ops/ms
Iteration   2: 10.722 ops/ms
Iteration   3: 10.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.749 ±(99.9%) 0.946 ops/ms [Average]
  (min, avg, max) = (10.715, 10.749, 10.808), stdev = 0.052
  CI (99.9%): [9.803, 11.694] (assumes normal distribution)


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
# Warmup Iteration   1: 7.655 ops/ms
# Warmup Iteration   2: 10.903 ops/ms
# Warmup Iteration   3: 11.109 ops/ms
Iteration   1: 11.215 ops/ms
Iteration   2: 11.222 ops/ms
Iteration   3: 11.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.208 ±(99.9%) 0.344 ops/ms [Average]
  (min, avg, max) = (11.186, 11.208, 11.222), stdev = 0.019
  CI (99.9%): [10.864, 11.551] (assumes normal distribution)


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
# Warmup Iteration   1: 8.085 ops/ms
# Warmup Iteration   2: 10.207 ops/ms
# Warmup Iteration   3: 10.586 ops/ms
Iteration   1: 10.752 ops/ms
Iteration   2: 10.781 ops/ms
Iteration   3: 10.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.747 ±(99.9%) 0.679 ops/ms [Average]
  (min, avg, max) = (10.707, 10.747, 10.781), stdev = 0.037
  CI (99.9%): [10.067, 11.426] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.729 ops/ms
# Warmup Iteration   2: 7.714 ops/ms
# Warmup Iteration   3: 8.136 ops/ms
Iteration   1: 8.078 ops/ms
Iteration   2: 8.313 ops/ms
Iteration   3: 8.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.286 ±(99.9%) 3.566 ops/ms [Average]
  (min, avg, max) = (8.078, 8.286, 8.466), stdev = 0.195
  CI (99.9%): [4.719, 11.852] (assumes normal distribution)


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.002 ms/op
Iteration   2: 2.941 ±(99.9%) 0.002 ms/op
Iteration   3: 3.002 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.968 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (2.941, 2.968, 3.002), stdev = 0.031
  CI (99.9%): [2.400, 3.537] (assumes normal distribution)


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
# Warmup Iteration   1: 3.678 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.004 ms/op
Iteration   1: 2.821 ±(99.9%) 0.002 ms/op
Iteration   2: 2.808 ±(99.9%) 0.003 ms/op
Iteration   3: 2.806 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.812 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.806, 2.812, 2.821), stdev = 0.008
  CI (99.9%): [2.664, 2.960] (assumes normal distribution)


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
# Warmup Iteration   1: 3.576 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.002 ms/op
Iteration   1: 2.954 ±(99.9%) 0.002 ms/op
Iteration   2: 2.984 ±(99.9%) 0.003 ms/op
Iteration   3: 2.973 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.970 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (2.954, 2.970, 2.984), stdev = 0.015
  CI (99.9%): [2.701, 3.240] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.556 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.016 ms/op
Iteration   1: 3.873 ±(99.9%) 0.015 ms/op
Iteration   2: 3.899 ±(99.9%) 0.012 ms/op
Iteration   3: 3.784 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.852 ±(99.9%) 1.094 ms/op [Average]
  (min, avg, max) = (3.784, 3.852, 3.899), stdev = 0.060
  CI (99.9%): [2.758, 4.946] (assumes normal distribution)


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
Iteration   1: 2.904 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.336 ms/op
                 createUser·p0.50:   2.892 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.502 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  6.922 ms/op
                 createUser·p0.9999: 16.809 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 2.919 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.504 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  8.616 ms/op
                 createUser·p0.9999: 18.711 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 2.948 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.523 ms/op
                 createUser·p0.99:   4.157 ms/op
                 createUser·p0.999:  6.836 ms/op
                 createUser·p0.9999: 32.937 ms/op
                 createUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 328424
  mean =      2.923 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33012 
    [ 2.500,  5.000) = 294351 
    [ 5.000,  7.500) = 806 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.943 ms/op
     p(99.9900) =     26.936 ms/op
     p(99.9990) =     33.217 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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
# Warmup Iteration   1: 3.599 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.943 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.882 ±(99.9%) 0.006 ms/op
Iteration   1: 2.883 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  5.343 ms/op
                 existUser·p0.9999: 11.924 ms/op
                 existUser·p1.00:   12.091 ms/op

Iteration   2: 2.835 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  5.761 ms/op
                 existUser·p0.9999: 12.939 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   3: 2.846 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  6.783 ms/op
                 existUser·p0.9999: 15.967 ms/op
                 existUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336057
  mean =      2.854 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2853 
    [ 1.250,  2.500) = 47035 
    [ 2.500,  3.750) = 275978 
    [ 3.750,  5.000) = 9406 
    [ 5.000,  6.250) = 463 
    [ 6.250,  7.500) = 121 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.160 ms/op
     p(99.9900) =     14.290 ms/op
     p(99.9990) =     16.499 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 2.942 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.905 ms/op
                 getUser·p0.9999: 17.568 ms/op
                 getUser·p1.00:   17.891 ms/op

Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  8.673 ms/op
                 getUser·p0.9999: 12.638 ms/op
                 getUser·p1.00:   12.894 ms/op

Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.476 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.282 ms/op
                 getUser·p0.999:  6.468 ms/op
                 getUser·p0.9999: 24.620 ms/op
                 getUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321773
  mean =      2.982 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34355 
    [ 2.500,  5.000) = 285970 
    [ 5.000,  7.500) = 1113 
    [ 7.500, 10.000) = 137 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.635 ms/op
     p(99.9900) =     22.797 ms/op
     p(99.9990) =     24.889 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 4.855 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.009 ms/op
Iteration   1: 3.731 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.685 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   6.673 ms/op
                 listUser·p0.999:  11.471 ms/op
                 listUser·p0.9999: 13.903 ms/op
                 listUser·p1.00:   14.959 ms/op

Iteration   2: 3.883 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.987 ms/op
                 listUser·p0.999:  13.740 ms/op
                 listUser·p0.9999: 18.375 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 3.856 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  13.729 ms/op
                 listUser·p0.9999: 17.128 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251263
  mean =      3.822 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 3823 
    [ 2.500,  3.750) = 134752 
    [ 3.750,  5.000) = 94359 
    [ 5.000,  6.250) = 13730 
    [ 6.250,  7.500) = 3516 
    [ 7.500,  8.750) = 461 
    [ 8.750, 10.000) = 181 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 132 
    [13.750, 15.000) = 107 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     18.840 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.749 ± 0.946  ops/ms
ClientGrpc.existUser                       thrpt       3  11.208 ± 0.344  ops/ms
ClientGrpc.getUser                         thrpt       3  10.747 ± 0.679  ops/ms
ClientGrpc.listUser                        thrpt       3   8.286 ± 3.566  ops/ms
ClientGrpc.createUser                       avgt       3   2.968 ± 0.568   ms/op
ClientGrpc.existUser                        avgt       3   2.812 ± 0.148   ms/op
ClientGrpc.getUser                          avgt       3   2.970 ± 0.269   ms/op
ClientGrpc.listUser                         avgt       3   3.852 ± 1.094   ms/op
ClientGrpc.createUser                     sample  328424   2.923 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.336           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.916           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.351           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.943           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.936           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.292           ms/op
ClientGrpc.existUser                      sample  336057   2.854 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.594           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.334           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.160           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.290           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.515           ms/op
ClientGrpc.getUser                        sample  321773   2.982 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.476           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.635           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.797           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.002           ms/op
ClientGrpc.listUser                       sample  251263   3.822 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.685           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.695           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.206           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.039           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.940           ms/op
