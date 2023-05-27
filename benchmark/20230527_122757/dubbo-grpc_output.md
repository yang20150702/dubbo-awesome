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
# Warmup Iteration   1: 4.712 ops/ms
# Warmup Iteration   2: 9.188 ops/ms
# Warmup Iteration   3: 10.277 ops/ms
Iteration   1: 10.627 ops/ms
Iteration   2: 10.724 ops/ms
Iteration   3: 10.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.697 ±(99.9%) 1.112 ops/ms [Average]
  (min, avg, max) = (10.627, 10.697, 10.739), stdev = 0.061
  CI (99.9%): [9.585, 11.809] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 7.990 ops/ms
# Warmup Iteration   2: 10.740 ops/ms
# Warmup Iteration   3: 11.200 ops/ms
Iteration   1: 11.221 ops/ms
Iteration   2: 11.037 ops/ms
Iteration   3: 11.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.201 ±(99.9%) 2.837 ops/ms [Average]
  (min, avg, max) = (11.037, 11.201, 11.346), stdev = 0.156
  CI (99.9%): [8.364, 14.038] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.486 ops/ms
# Warmup Iteration   2: 10.128 ops/ms
# Warmup Iteration   3: 10.703 ops/ms
Iteration   1: 10.876 ops/ms
Iteration   2: 10.649 ops/ms
Iteration   3: 10.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.741 ±(99.9%) 2.178 ops/ms [Average]
  (min, avg, max) = (10.649, 10.741, 10.876), stdev = 0.119
  CI (99.9%): [8.563, 12.919] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.209 ops/ms
# Warmup Iteration   2: 7.961 ops/ms
# Warmup Iteration   3: 8.356 ops/ms
Iteration   1: 8.238 ops/ms
Iteration   2: 8.363 ops/ms
Iteration   3: 8.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.314 ±(99.9%) 1.229 ops/ms [Average]
  (min, avg, max) = (8.238, 8.314, 8.363), stdev = 0.067
  CI (99.9%): [7.085, 9.544] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.926 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 2.972 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.985 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.972, 2.985, 2.996), stdev = 0.012
  CI (99.9%): [2.757, 3.213] (assumes normal distribution)


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
# Warmup Iteration   1: 3.728 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.816 ±(99.9%) 0.004 ms/op
Iteration   1: 2.834 ±(99.9%) 0.003 ms/op
Iteration   2: 2.840 ±(99.9%) 0.003 ms/op
Iteration   3: 2.841 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.838 ±(99.9%) 0.067 ms/op [Average]
  (min, avg, max) = (2.834, 2.838, 2.841), stdev = 0.004
  CI (99.9%): [2.771, 2.905] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.003 ms/op
Iteration   1: 3.037 ±(99.9%) 0.003 ms/op
Iteration   2: 3.035 ±(99.9%) 0.002 ms/op
Iteration   3: 3.043 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.038 ±(99.9%) 0.076 ms/op [Average]
  (min, avg, max) = (3.035, 3.038, 3.043), stdev = 0.004
  CI (99.9%): [2.962, 3.115] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.749 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.007 ms/op
Iteration   1: 3.746 ±(99.9%) 0.012 ms/op
Iteration   2: 3.842 ±(99.9%) 0.029 ms/op
Iteration   3: 3.793 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.794 ±(99.9%) 0.883 ms/op [Average]
  (min, avg, max) = (3.746, 3.794, 3.842), stdev = 0.048
  CI (99.9%): [2.911, 4.677] (assumes normal distribution)


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 3.070 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.342 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.742 ms/op
                 createUser·p0.9999: 12.037 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.460 ms/op
                 createUser·p0.9999: 13.340 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   3: 3.011 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  7.798 ms/op
                 createUser·p0.9999: 18.767 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315168
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1331 
    [ 1.250,  2.500) = 22284 
    [ 2.500,  3.750) = 270131 
    [ 3.750,  5.000) = 19903 
    [ 5.000,  6.250) = 963 
    [ 6.250,  7.500) = 232 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.342 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.692 ms/op
     p(99.9900) =     18.152 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.006 ms/op
Iteration   1: 2.909 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  5.857 ms/op
                 existUser·p0.9999: 11.469 ms/op
                 existUser·p1.00:   11.993 ms/op

Iteration   2: 2.873 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  5.612 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   3: 2.825 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.811 ms/op
                 existUser·p0.9999: 14.358 ms/op
                 existUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334572
  mean =      2.868 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47067 
    [ 2.500,  5.000) = 286423 
    [ 5.000,  7.500) = 884 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      5.980 ms/op
     p(99.9900) =     14.912 ms/op
     p(99.9990) =     22.533 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.005 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  6.722 ms/op
                 getUser·p0.9999: 21.279 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.562 ms/op
                 getUser·p0.9999: 15.003 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   3: 3.004 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.286 ms/op
                 getUser·p0.9999: 25.461 ms/op
                 getUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319450
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28489 
    [ 2.500,  5.000) = 289872 
    [ 5.000,  7.500) = 860 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.504 ms/op
     p(99.9900) =     24.166 ms/op
     p(99.9990) =     25.651 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 4.773 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.010 ms/op
Iteration   1: 3.830 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.576 ms/op
                 listUser·p0.999:  12.312 ms/op
                 listUser·p0.9999: 18.884 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 3.701 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   6.390 ms/op
                 listUser·p0.999:  15.001 ms/op
                 listUser·p0.9999: 23.223 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   3: 3.812 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  14.354 ms/op
                 listUser·p0.9999: 20.618 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 253811
  mean =      3.780 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4750 
    [ 2.500,  5.000) = 229665 
    [ 5.000,  7.500) = 18195 
    [ 7.500, 10.000) = 638 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     23.444 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.697 ± 1.112  ops/ms
ClientGrpc.existUser                       thrpt       3  11.201 ± 2.837  ops/ms
ClientGrpc.getUser                         thrpt       3  10.741 ± 2.178  ops/ms
ClientGrpc.listUser                        thrpt       3   8.314 ± 1.229  ops/ms
ClientGrpc.createUser                       avgt       3   2.985 ± 0.228   ms/op
ClientGrpc.existUser                        avgt       3   2.838 ± 0.067   ms/op
ClientGrpc.getUser                          avgt       3   3.038 ± 0.076   ms/op
ClientGrpc.listUser                         avgt       3   3.794 ± 0.883   ms/op
ClientGrpc.createUser                     sample  315168   3.047 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.342           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.692           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.152           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.169           ms/op
ClientGrpc.existUser                      sample  334572   2.868 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.543           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.980           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.912           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.643           ms/op
ClientGrpc.getUser                        sample  319450   3.006 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.731           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.504           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.166           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.723           ms/op
ClientGrpc.listUser                       sample  253811   3.780 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.133           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.025           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.758           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.560           ms/op
