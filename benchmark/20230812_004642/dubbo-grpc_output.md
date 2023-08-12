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
# Warmup Iteration   1: 4.516 ops/ms
# Warmup Iteration   2: 8.699 ops/ms
# Warmup Iteration   3: 10.188 ops/ms
Iteration   1: 10.468 ops/ms
Iteration   2: 10.603 ops/ms
Iteration   3: 10.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.635 ±(99.9%) 3.375 ops/ms [Average]
  (min, avg, max) = (10.468, 10.635, 10.834), stdev = 0.185
  CI (99.9%): [7.260, 14.010] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.492 ops/ms
# Warmup Iteration   2: 10.658 ops/ms
# Warmup Iteration   3: 11.027 ops/ms
Iteration   1: 11.065 ops/ms
Iteration   2: 11.199 ops/ms
Iteration   3: 11.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.193 ±(99.9%) 2.280 ops/ms [Average]
  (min, avg, max) = (11.065, 11.193, 11.314), stdev = 0.125
  CI (99.9%): [8.913, 13.472] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.349 ops/ms
# Warmup Iteration   2: 10.256 ops/ms
# Warmup Iteration   3: 10.862 ops/ms
Iteration   1: 10.655 ops/ms
Iteration   2: 10.610 ops/ms
Iteration   3: 10.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.683 ±(99.9%) 1.625 ops/ms [Average]
  (min, avg, max) = (10.610, 10.683, 10.782), stdev = 0.089
  CI (99.9%): [9.057, 12.308] (assumes normal distribution)


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
# Warmup Iteration   1: 5.840 ops/ms
# Warmup Iteration   2: 8.009 ops/ms
# Warmup Iteration   3: 8.102 ops/ms
Iteration   1: 8.293 ops/ms
Iteration   2: 8.019 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.171 ±(99.9%) 2.550 ops/ms [Average]
  (min, avg, max) = (8.019, 8.171, 8.293), stdev = 0.140
  CI (99.9%): [5.621, 10.721] (assumes normal distribution)


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.002 ms/op
Iteration   1: 3.002 ±(99.9%) 0.002 ms/op
Iteration   2: 2.963 ±(99.9%) 0.004 ms/op
Iteration   3: 2.978 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.981 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.963, 2.981, 3.002), stdev = 0.020
  CI (99.9%): [2.621, 3.341] (assumes normal distribution)


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
# Warmup Iteration   1: 3.861 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.003 ms/op
Iteration   1: 2.905 ±(99.9%) 0.003 ms/op
Iteration   2: 2.875 ±(99.9%) 0.004 ms/op
Iteration   3: 2.846 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.875 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (2.846, 2.875, 2.905), stdev = 0.029
  CI (99.9%): [2.341, 3.410] (assumes normal distribution)


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.002 ms/op
Iteration   1: 3.007 ±(99.9%) 0.003 ms/op
Iteration   2: 2.953 ±(99.9%) 0.002 ms/op
Iteration   3: 2.981 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.980 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (2.953, 2.980, 3.007), stdev = 0.027
  CI (99.9%): [2.483, 3.478] (assumes normal distribution)


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
# Warmup Iteration   1: 4.470 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.012 ms/op
Iteration   1: 3.945 ±(99.9%) 0.013 ms/op
Iteration   2: 3.918 ±(99.9%) 0.024 ms/op
Iteration   3: 3.891 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.918 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (3.891, 3.918, 3.945), stdev = 0.027
  CI (99.9%): [3.431, 4.405] (assumes normal distribution)


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.007 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.467 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.699 ms/op
                 createUser·p0.9999: 12.457 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.661 ms/op
                 createUser·p0.9999: 15.297 ms/op
                 createUser·p1.00:   15.761 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.700 ms/op
                 createUser·p0.9999: 22.050 ms/op
                 createUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319318
  mean =      3.009 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24197 
    [ 2.500,  5.000) = 293475 
    [ 5.000,  7.500) = 1191 
    [ 7.500, 10.000) = 239 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.031 ms/op
     p(99.9900) =     19.368 ms/op
     p(99.9990) =     22.433 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.982 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.781 ±(99.9%) 0.008 ms/op
Iteration   1: 2.913 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  7.282 ms/op
                 existUser·p0.9999: 15.615 ms/op
                 existUser·p1.00:   15.909 ms/op

Iteration   2: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  7.840 ms/op
                 existUser·p0.9999: 16.880 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   3: 2.933 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.774 ms/op
                 existUser·p0.9999: 24.740 ms/op
                 existUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327401
  mean =      2.931 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38254 
    [ 2.500,  5.000) = 287600 
    [ 5.000,  7.500) = 1148 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.700 ms/op
     p(99.9900) =     19.028 ms/op
     p(99.9990) =     24.838 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.961 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  9.797 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   19.595 ms/op

Iteration   2: 3.020 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.326 ms/op
                 getUser·p0.9999: 16.608 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  8.025 ms/op
                 getUser·p0.9999: 18.252 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320268
  mean =      2.997 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32195 
    [ 2.500,  5.000) = 286046 
    [ 5.000,  7.500) = 1395 
    [ 7.500, 10.000) = 373 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     18.938 ms/op
     p(99.9990) =     20.353 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.010 ms/op
Iteration   1: 3.935 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.069 ms/op
                 listUser·p0.999:  11.885 ms/op
                 listUser·p0.9999: 13.195 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   2: 3.805 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.759 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  15.253 ms/op
                 listUser·p0.9999: 21.122 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 3.935 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.655 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  14.686 ms/op
                 listUser·p0.9999: 21.797 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246657
  mean =      3.891 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4745 
    [ 2.500,  5.000) = 221354 
    [ 5.000,  7.500) = 19076 
    [ 7.500, 10.000) = 968 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     13.703 ms/op
     p(99.9900) =     21.015 ms/op
     p(99.9990) =     23.187 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.635 ± 3.375  ops/ms
ClientGrpc.existUser                       thrpt       3  11.193 ± 2.280  ops/ms
ClientGrpc.getUser                         thrpt       3  10.683 ± 1.625  ops/ms
ClientGrpc.listUser                        thrpt       3   8.171 ± 2.550  ops/ms
ClientGrpc.createUser                       avgt       3   2.981 ± 0.360   ms/op
ClientGrpc.existUser                        avgt       3   2.875 ± 0.535   ms/op
ClientGrpc.getUser                          avgt       3   2.980 ± 0.497   ms/op
ClientGrpc.listUser                         avgt       3   3.918 ± 0.487   ms/op
ClientGrpc.createUser                     sample  319318   3.009 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.467           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.031           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.368           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.544           ms/op
ClientGrpc.existUser                      sample  327401   2.931 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.719           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.700           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.028           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.871           ms/op
ClientGrpc.getUser                        sample  320268   2.997 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.545           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.175           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.938           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.677           ms/op
ClientGrpc.listUser                       sample  246657   3.891 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.655           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.703           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.015           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.265           ms/op
