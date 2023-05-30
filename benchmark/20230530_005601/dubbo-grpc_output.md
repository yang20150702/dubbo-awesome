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
# Warmup Iteration   1: 4.098 ops/ms
# Warmup Iteration   2: 8.563 ops/ms
# Warmup Iteration   3: 10.300 ops/ms
Iteration   1: 10.509 ops/ms
Iteration   2: 10.672 ops/ms
Iteration   3: 10.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.547 ±(99.9%) 2.020 ops/ms [Average]
  (min, avg, max) = (10.460, 10.547, 10.672), stdev = 0.111
  CI (99.9%): [8.527, 12.567] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.458 ops/ms
# Warmup Iteration   2: 10.685 ops/ms
# Warmup Iteration   3: 11.349 ops/ms
Iteration   1: 11.397 ops/ms
Iteration   2: 11.173 ops/ms
Iteration   3: 11.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.329 ±(99.9%) 2.474 ops/ms [Average]
  (min, avg, max) = (11.173, 11.329, 11.418), stdev = 0.136
  CI (99.9%): [8.856, 13.803] (assumes normal distribution)


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
# Warmup Iteration   1: 6.705 ops/ms
# Warmup Iteration   2: 10.430 ops/ms
# Warmup Iteration   3: 10.716 ops/ms
Iteration   1: 10.756 ops/ms
Iteration   2: 10.735 ops/ms
Iteration   3: 10.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.683 ±(99.9%) 2.009 ops/ms [Average]
  (min, avg, max) = (10.556, 10.683, 10.756), stdev = 0.110
  CI (99.9%): [8.674, 12.691] (assumes normal distribution)


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
# Warmup Iteration   1: 5.761 ops/ms
# Warmup Iteration   2: 7.803 ops/ms
# Warmup Iteration   3: 8.183 ops/ms
Iteration   1: 8.232 ops/ms
Iteration   2: 8.478 ops/ms
Iteration   3: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.356 ±(99.9%) 2.251 ops/ms [Average]
  (min, avg, max) = (8.232, 8.356, 8.478), stdev = 0.123
  CI (99.9%): [6.105, 10.607] (assumes normal distribution)


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.003 ms/op
Iteration   1: 3.010 ±(99.9%) 0.004 ms/op
Iteration   2: 2.936 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.970 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (2.936, 2.970, 3.010), stdev = 0.037
  CI (99.9%): [2.291, 3.649] (assumes normal distribution)


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.001 ms/op
Iteration   1: 2.839 ±(99.9%) 0.003 ms/op
Iteration   2: 2.797 ±(99.9%) 0.003 ms/op
Iteration   3: 2.807 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.814 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (2.797, 2.814, 2.839), stdev = 0.022
  CI (99.9%): [2.412, 3.216] (assumes normal distribution)


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
# Warmup Iteration   1: 4.160 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.002 ms/op
Iteration   1: 3.005 ±(99.9%) 0.002 ms/op
Iteration   2: 3.031 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.014 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (3.005, 3.014, 3.031), stdev = 0.015
  CI (99.9%): [2.747, 3.281] (assumes normal distribution)


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
# Warmup Iteration   1: 5.504 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.024 ms/op
Iteration   1: 3.887 ±(99.9%) 0.031 ms/op
Iteration   2: 3.811 ±(99.9%) 0.014 ms/op
Iteration   3: 3.824 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.840 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (3.811, 3.840, 3.887), stdev = 0.041
  CI (99.9%): [3.100, 4.581] (assumes normal distribution)


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  6.662 ms/op
                 createUser·p0.9999: 23.240 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   2: 3.028 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.363 ms/op
                 createUser·p0.999:  8.692 ms/op
                 createUser·p0.9999: 26.982 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.440 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  9.580 ms/op
                 createUser·p0.9999: 27.182 ms/op
                 createUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320831
  mean =      2.994 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28240 
    [ 2.500,  5.000) = 291115 
    [ 5.000,  7.500) = 1118 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.195 ms/op
     p(99.9900) =     26.111 ms/op
     p(99.9990) =     27.649 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 4.045 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.866 ±(99.9%) 0.005 ms/op
Iteration   1: 2.876 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   3.928 ms/op
                 existUser·p0.999:  6.126 ms/op
                 existUser·p0.9999: 12.466 ms/op
                 existUser·p1.00:   12.665 ms/op

Iteration   2: 2.878 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  5.538 ms/op
                 existUser·p0.9999: 13.741 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   3: 2.825 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.791 ms/op
                 existUser·p0.9999: 15.942 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335671
  mean =      2.860 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1782 
    [ 1.250,  2.500) = 47679 
    [ 2.500,  3.750) = 279652 
    [ 3.750,  5.000) = 5831 
    [ 5.000,  6.250) = 424 
    [ 6.250,  7.500) = 126 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      6.062 ms/op
     p(99.9900) =     14.940 ms/op
     p(99.9990) =     16.245 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 4.300 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.993 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.025 ms/op
                 getUser·p0.9999: 18.317 ms/op
                 getUser·p1.00:   18.645 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.378 ms/op
                 getUser·p0.9999: 14.336 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   3: 2.940 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.527 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  6.967 ms/op
                 getUser·p0.9999: 16.361 ms/op
                 getUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321316
  mean =      2.987 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1272 
    [ 1.250,  2.500) = 28838 
    [ 2.500,  3.750) = 276605 
    [ 3.750,  5.000) = 13293 
    [ 5.000,  6.250) = 799 
    [ 6.250,  7.500) = 219 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.135 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 5.686 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.010 ms/op
Iteration   1: 3.943 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.728 ms/op
                 listUser·p0.9999: 16.540 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   2: 3.881 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.259 ms/op
                 listUser·p0.9999: 22.864 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 3.928 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.769 ms/op
                 listUser·p0.9999: 25.380 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245253
  mean =      3.917 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2175 
    [ 2.500,  5.000) = 222515 
    [ 5.000,  7.500) = 19409 
    [ 7.500, 10.000) = 714 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.507 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.479 ms/op
     p(99.9900) =     24.297 ms/op
     p(99.9990) =     25.824 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.547 ± 2.020  ops/ms
ClientGrpc.existUser                       thrpt       3  11.329 ± 2.474  ops/ms
ClientGrpc.getUser                         thrpt       3  10.683 ± 2.009  ops/ms
ClientGrpc.listUser                        thrpt       3   8.356 ± 2.251  ops/ms
ClientGrpc.createUser                       avgt       3   2.970 ± 0.679   ms/op
ClientGrpc.existUser                        avgt       3   2.814 ± 0.402   ms/op
ClientGrpc.getUser                          avgt       3   3.014 ± 0.267   ms/op
ClientGrpc.listUser                         avgt       3   3.840 ± 0.741   ms/op
ClientGrpc.createUser                     sample  320831   2.994 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.440           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.195           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.111           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.213           ms/op
ClientGrpc.existUser                      sample  335671   2.860 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.674           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.062           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.940           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.777           ms/op
ClientGrpc.getUser                        sample  321316   2.987 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.624           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.135           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.629           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.645           ms/op
ClientGrpc.listUser                       sample  245253   3.917 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.925           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.507           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.479           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.297           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.854           ms/op
