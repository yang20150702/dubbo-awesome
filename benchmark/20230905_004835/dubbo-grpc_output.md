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
# Warmup Iteration   1: 3.839 ops/ms
# Warmup Iteration   2: 8.643 ops/ms
# Warmup Iteration   3: 9.893 ops/ms
Iteration   1: 10.293 ops/ms
Iteration   2: 10.342 ops/ms
Iteration   3: 10.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.435 ±(99.9%) 3.740 ops/ms [Average]
  (min, avg, max) = (10.293, 10.435, 10.670), stdev = 0.205
  CI (99.9%): [6.695, 14.175] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.779 ops/ms
# Warmup Iteration   2: 10.361 ops/ms
# Warmup Iteration   3: 10.996 ops/ms
Iteration   1: 11.083 ops/ms
Iteration   2: 10.813 ops/ms
Iteration   3: 10.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.919 ±(99.9%) 2.629 ops/ms [Average]
  (min, avg, max) = (10.813, 10.919, 11.083), stdev = 0.144
  CI (99.9%): [8.290, 13.548] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.832 ops/ms
# Warmup Iteration   2: 10.038 ops/ms
# Warmup Iteration   3: 10.041 ops/ms
Iteration   1: 10.090 ops/ms
Iteration   2: 10.377 ops/ms
Iteration   3: 10.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.308 ±(99.9%) 3.520 ops/ms [Average]
  (min, avg, max) = (10.090, 10.308, 10.456), stdev = 0.193
  CI (99.9%): [6.788, 13.828] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.651 ops/ms
# Warmup Iteration   2: 7.629 ops/ms
# Warmup Iteration   3: 7.805 ops/ms
Iteration   1: 7.851 ops/ms
Iteration   2: 7.929 ops/ms
Iteration   3: 7.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.904 ±(99.9%) 0.829 ops/ms [Average]
  (min, avg, max) = (7.851, 7.904, 7.931), stdev = 0.045
  CI (99.9%): [7.075, 8.732] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.360 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.002 ms/op
Iteration   1: 3.151 ±(99.9%) 0.002 ms/op
Iteration   2: 3.057 ±(99.9%) 0.002 ms/op
Iteration   3: 3.095 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.101 ±(99.9%) 0.866 ms/op [Average]
  (min, avg, max) = (3.057, 3.101, 3.151), stdev = 0.047
  CI (99.9%): [2.235, 3.967] (assumes normal distribution)


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
# Warmup Iteration   1: 4.135 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.002 ms/op
Iteration   1: 2.872 ±(99.9%) 0.003 ms/op
Iteration   2: 2.879 ±(99.9%) 0.003 ms/op
Iteration   3: 2.933 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.895 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (2.872, 2.895, 2.933), stdev = 0.034
  CI (99.9%): [2.283, 3.506] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.002 ms/op
Iteration   1: 3.075 ±(99.9%) 0.003 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.121 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.101 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (3.075, 3.101, 3.121), stdev = 0.024
  CI (99.9%): [2.668, 3.533] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.223 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.018 ms/op
Iteration   1: 4.065 ±(99.9%) 0.009 ms/op
Iteration   2: 4.004 ±(99.9%) 0.012 ms/op
Iteration   3: 4.098 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.056 ±(99.9%) 0.871 ms/op [Average]
  (min, avg, max) = (4.004, 4.056, 4.098), stdev = 0.048
  CI (99.9%): [3.185, 4.927] (assumes normal distribution)


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
Iteration   1: 3.110 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.621 ms/op
                 createUser·p0.9999: 12.728 ms/op
                 createUser·p1.00:   13.058 ms/op

Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.569 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   21.823 ms/op

Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  9.858 ms/op
                 createUser·p0.9999: 17.433 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312020
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13454 
    [ 2.500,  5.000) = 296466 
    [ 5.000,  7.500) = 1538 
    [ 7.500, 10.000) = 269 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      9.534 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.721 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.882 ms/op
                 existUser·p0.9999: 12.124 ms/op
                 existUser·p1.00:   12.337 ms/op

Iteration   2: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.471 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.588 ms/op
                 existUser·p0.9999: 21.467 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   3: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.866 ms/op
                 existUser·p0.999:  7.381 ms/op
                 existUser·p0.9999: 18.881 ms/op
                 existUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324487
  mean =      2.960 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24432 
    [ 2.500,  5.000) = 297950 
    [ 5.000,  7.500) = 1789 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      7.471 ms/op
     p(99.9900) =     19.838 ms/op
     p(99.9990) =     21.553 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.006 ms/op
Iteration   1: 3.101 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  9.195 ms/op
                 getUser·p0.9999: 12.764 ms/op
                 getUser·p1.00:   12.927 ms/op

Iteration   2: 3.105 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  9.618 ms/op
                 getUser·p0.9999: 18.429 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.061 ms/op
                 getUser·p0.9999: 15.843 ms/op
                 getUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309270
  mean =      3.104 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 387 
    [ 1.250,  2.500) = 13128 
    [ 2.500,  3.750) = 277888 
    [ 3.750,  5.000) = 15265 
    [ 5.000,  6.250) = 1447 
    [ 6.250,  7.500) = 680 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     16.815 ms/op
     p(99.9990) =     18.773 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 5.309 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.225 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.012 ms/op
Iteration   1: 4.080 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  12.784 ms/op
                 listUser·p0.9999: 21.862 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   2: 4.041 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 18.586 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 4.034 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.738 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  16.585 ms/op
                 listUser·p0.9999: 23.233 ms/op
                 listUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236913
  mean =      4.052 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2531 
    [ 2.500,  5.000) = 207393 
    [ 5.000,  7.500) = 25090 
    [ 7.500, 10.000) = 1307 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     15.468 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     24.748 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.435 ± 3.740  ops/ms
ClientGrpc.existUser                       thrpt       3  10.919 ± 2.629  ops/ms
ClientGrpc.getUser                         thrpt       3  10.308 ± 3.520  ops/ms
ClientGrpc.listUser                        thrpt       3   7.904 ± 0.829  ops/ms
ClientGrpc.createUser                       avgt       3   3.101 ± 0.866   ms/op
ClientGrpc.existUser                        avgt       3   2.895 ± 0.612   ms/op
ClientGrpc.getUser                          avgt       3   3.101 ± 0.433   ms/op
ClientGrpc.listUser                         avgt       3   4.056 ± 0.871   ms/op
ClientGrpc.createUser                     sample  312020   3.076 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.762           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.534           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.004           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.823           ms/op
ClientGrpc.existUser                      sample  324487   2.960 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.471           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.612           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.471           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.838           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.265           ms/op
ClientGrpc.getUser                        sample  309270   3.104 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.696           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.536           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.815           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.842           ms/op
ClientGrpc.listUser                       sample  236913   4.052 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.738           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.250           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.468           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.970           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.838           ms/op
