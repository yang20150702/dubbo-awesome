# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.692 ops/ms
# Warmup Iteration   2: 9.639 ops/ms
# Warmup Iteration   3: 10.497 ops/ms
Iteration   1: 10.403 ops/ms
Iteration   2: 10.539 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.491 ±(99.9%) 1.384 ops/ms [Average]
  (min, avg, max) = (10.403, 10.491, 10.539), stdev = 0.076
  CI (99.9%): [9.107, 11.875] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.754 ops/ms
# Warmup Iteration   2: 10.861 ops/ms
# Warmup Iteration   3: 10.752 ops/ms
Iteration   1: 10.699 ops/ms
Iteration   2: 10.933 ops/ms
Iteration   3: 10.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.874 ±(99.9%) 2.801 ops/ms [Average]
  (min, avg, max) = (10.699, 10.874, 10.989), stdev = 0.154
  CI (99.9%): [8.072, 13.675] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.055 ops/ms
# Warmup Iteration   2: 10.446 ops/ms
# Warmup Iteration   3: 10.776 ops/ms
Iteration   1: 10.313 ops/ms
Iteration   2: 10.466 ops/ms
Iteration   3: 10.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.419 ±(99.9%) 1.669 ops/ms [Average]
  (min, avg, max) = (10.313, 10.419, 10.477), stdev = 0.091
  CI (99.9%): [8.750, 12.087] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.106 ops/ms
# Warmup Iteration   2: 7.899 ops/ms
# Warmup Iteration   3: 7.935 ops/ms
Iteration   1: 7.859 ops/ms
Iteration   2: 7.904 ops/ms
Iteration   3: 7.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.915 ±(99.9%) 1.141 ops/ms [Average]
  (min, avg, max) = (7.859, 7.915, 7.982), stdev = 0.063
  CI (99.9%): [6.774, 9.056] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.914 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.003 ms/op
Iteration   1: 3.048 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 3.116 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.071 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (3.047, 3.071, 3.116), stdev = 0.039
  CI (99.9%): [2.355, 3.786] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.797 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.004 ms/op
Iteration   1: 2.969 ±(99.9%) 0.002 ms/op
Iteration   2: 2.923 ±(99.9%) 0.002 ms/op
Iteration   3: 2.966 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.953 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (2.923, 2.953, 2.969), stdev = 0.025
  CI (99.9%): [2.489, 3.416] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.916 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.003 ms/op
Iteration   1: 3.084 ±(99.9%) 0.002 ms/op
Iteration   2: 3.028 ±(99.9%) 0.003 ms/op
Iteration   3: 3.085 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (3.028, 3.066, 3.085), stdev = 0.033
  CI (99.9%): [2.468, 3.664] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.196 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.041 ms/op
Iteration   1: 4.126 ±(99.9%) 0.013 ms/op
Iteration   2: 4.069 ±(99.9%) 0.018 ms/op
Iteration   3: 4.053 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.083 ±(99.9%) 0.702 ms/op [Average]
  (min, avg, max) = (4.053, 4.083, 4.126), stdev = 0.038
  CI (99.9%): [3.381, 4.785] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.007 ms/op
Iteration   1: 3.152 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.627 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.931 ms/op
                 createUser·p0.9999: 12.007 ms/op
                 createUser·p1.00:   12.337 ms/op

Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.789 ms/op
                 createUser·p0.9999: 23.746 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  13.079 ms/op
                 createUser·p0.9999: 23.121 ms/op
                 createUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307117
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26239 
    [ 2.500,  5.000) = 279644 
    [ 5.000,  7.500) = 858 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     24.014 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.783 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.884 ±(99.9%) 0.006 ms/op
Iteration   1: 2.908 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  5.995 ms/op
                 existUser·p0.9999: 11.402 ms/op
                 existUser·p1.00:   11.977 ms/op

Iteration   2: 2.938 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  7.488 ms/op
                 existUser·p0.9999: 14.325 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   3: 2.894 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  10.813 ms/op
                 existUser·p0.9999: 16.218 ms/op
                 existUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329642
  mean =      2.913 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3560 
    [ 1.250,  2.500) = 49409 
    [ 2.500,  3.750) = 264259 
    [ 3.750,  5.000) = 11590 
    [ 5.000,  6.250) = 334 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =      7.526 ms/op
     p(99.9900) =     15.339 ms/op
     p(99.9990) =     16.397 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.919 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.149 ms/op
                 getUser·p0.9999: 12.620 ms/op
                 getUser·p1.00:   13.042 ms/op

Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  9.877 ms/op
                 getUser·p0.9999: 14.314 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   3: 3.003 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.612 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  10.740 ms/op
                 getUser·p0.9999: 24.009 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317276
  mean =      3.025 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28713 
    [ 2.500,  5.000) = 287646 
    [ 5.000,  7.500) = 542 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      9.896 ms/op
     p(99.9900) =     23.414 ms/op
     p(99.9990) =     24.368 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.478 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.012 ms/op
Iteration   1: 3.999 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  10.911 ms/op
                 listUser·p0.9999: 16.217 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   2: 3.971 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.676 ms/op
                 listUser·p0.9999: 16.612 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 4.001 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.237 ms/op
                 listUser·p0.9999: 23.495 ms/op
                 listUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240353
  mean =      3.990 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5840 
    [ 2.500,  5.000) = 205796 
    [ 5.000,  7.500) = 27438 
    [ 7.500, 10.000) = 829 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     14.035 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     26.011 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.491 ± 1.384  ops/ms
ClientGrpc.existUser                       thrpt       3  10.874 ± 2.801  ops/ms
ClientGrpc.getUser                         thrpt       3  10.419 ± 1.669  ops/ms
ClientGrpc.listUser                        thrpt       3   7.915 ± 1.141  ops/ms
ClientGrpc.createUser                       avgt       3   3.071 ± 0.715   ms/op
ClientGrpc.existUser                        avgt       3   2.953 ± 0.463   ms/op
ClientGrpc.getUser                          avgt       3   3.066 ± 0.598   ms/op
ClientGrpc.listUser                         avgt       3   4.083 ± 0.702   ms/op
ClientGrpc.createUser                     sample  307117   3.125 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.561           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.798           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.167           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.117           ms/op
ClientGrpc.existUser                      sample  329642   2.913 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.616           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.526           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.339           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.548           ms/op
ClientGrpc.getUser                        sample  317276   3.025 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.612           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.896           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.414           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.478           ms/op
ClientGrpc.listUser                       sample  240353   3.990 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.968           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.035           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.578           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.149           ms/op
