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
# Warmup Iteration   1: 3.080 ops/ms
# Warmup Iteration   2: 6.696 ops/ms
# Warmup Iteration   3: 7.561 ops/ms
Iteration   1: 7.939 ops/ms
Iteration   2: 8.014 ops/ms
Iteration   3: 8.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.113 ±(99.9%) 4.375 ops/ms [Average]
  (min, avg, max) = (7.939, 8.113, 8.387), stdev = 0.240
  CI (99.9%): [3.738, 12.489] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.649 ops/ms
# Warmup Iteration   2: 7.872 ops/ms
# Warmup Iteration   3: 8.000 ops/ms
Iteration   1: 8.759 ops/ms
Iteration   2: 8.785 ops/ms
Iteration   3: 8.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.712 ±(99.9%) 1.920 ops/ms [Average]
  (min, avg, max) = (8.591, 8.712, 8.785), stdev = 0.105
  CI (99.9%): [6.791, 10.632] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.030 ops/ms
# Warmup Iteration   2: 7.495 ops/ms
# Warmup Iteration   3: 7.796 ops/ms
Iteration   1: 7.867 ops/ms
Iteration   2: 8.021 ops/ms
Iteration   3: 7.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.899 ±(99.9%) 2.004 ops/ms [Average]
  (min, avg, max) = (7.808, 7.899, 8.021), stdev = 0.110
  CI (99.9%): [5.895, 9.903] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.357 ops/ms
# Warmup Iteration   2: 5.825 ops/ms
# Warmup Iteration   3: 6.310 ops/ms
Iteration   1: 6.286 ops/ms
Iteration   2: 6.395 ops/ms
Iteration   3: 6.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.326 ±(99.9%) 1.096 ops/ms [Average]
  (min, avg, max) = (6.286, 6.326, 6.395), stdev = 0.060
  CI (99.9%): [5.230, 7.423] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.732 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.005 ms/op
Iteration   1: 3.978 ±(99.9%) 0.005 ms/op
Iteration   2: 4.020 ±(99.9%) 0.002 ms/op
Iteration   3: 3.791 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.930 ±(99.9%) 2.228 ms/op [Average]
  (min, avg, max) = (3.791, 3.930, 4.020), stdev = 0.122
  CI (99.9%): [1.702, 6.157] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.260 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.004 ms/op
Iteration   1: 3.816 ±(99.9%) 0.003 ms/op
Iteration   2: 3.899 ±(99.9%) 0.003 ms/op
Iteration   3: 3.740 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.818 ±(99.9%) 1.450 ms/op [Average]
  (min, avg, max) = (3.740, 3.818, 3.899), stdev = 0.079
  CI (99.9%): [2.369, 5.268] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.795 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.295 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.234 ±(99.9%) 0.003 ms/op
Iteration   1: 4.095 ±(99.9%) 0.007 ms/op
Iteration   2: 4.213 ±(99.9%) 0.003 ms/op
Iteration   3: 4.135 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.148 ±(99.9%) 1.095 ms/op [Average]
  (min, avg, max) = (4.095, 4.148, 4.213), stdev = 0.060
  CI (99.9%): [3.053, 5.243] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.692 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.305 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.294 ±(99.9%) 0.015 ms/op
Iteration   1: 5.133 ±(99.9%) 0.011 ms/op
Iteration   2: 5.169 ±(99.9%) 0.015 ms/op
Iteration   3: 5.086 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.130 ±(99.9%) 0.758 ms/op [Average]
  (min, avg, max) = (5.086, 5.130, 5.169), stdev = 0.042
  CI (99.9%): [4.372, 5.887] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.613 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.012 ms/op
Iteration   1: 4.084 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   7.864 ms/op
                 createUser·p0.999:  13.058 ms/op
                 createUser·p0.9999: 17.662 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   2: 4.201 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.218 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   7.713 ms/op
                 createUser·p0.999:  13.155 ms/op
                 createUser·p0.9999: 23.827 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   3: 3.988 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.997 ms/op
                 createUser·p0.95:   5.472 ms/op
                 createUser·p0.99:   7.127 ms/op
                 createUser·p0.999:  13.014 ms/op
                 createUser·p0.9999: 20.906 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 234803
  mean =      4.089 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10009 
    [ 2.500,  5.000) = 196698 
    [ 5.000,  7.500) = 25611 
    [ 7.500, 10.000) = 1875 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     13.045 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.365 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.012 ms/op
Iteration   1: 3.897 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.284 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  13.041 ms/op
                 existUser·p0.9999: 15.434 ms/op
                 existUser·p1.00:   16.318 ms/op

Iteration   2: 3.943 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   7.554 ms/op
                 existUser·p0.999:  10.378 ms/op
                 existUser·p0.9999: 19.522 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   3: 3.830 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  11.960 ms/op
                 existUser·p0.9999: 20.030 ms/op
                 existUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 246730
  mean =      3.890 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10977 
    [ 2.500,  5.000) = 217712 
    [ 5.000,  7.500) = 15731 
    [ 7.500, 10.000) = 1815 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      7.395 ms/op
     p(99.9000) =     11.625 ms/op
     p(99.9900) =     19.409 ms/op
     p(99.9990) =     24.502 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.538 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.023 ±(99.9%) 0.011 ms/op
Iteration   1: 3.932 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  10.841 ms/op
                 getUser·p0.9999: 15.296 ms/op
                 getUser·p1.00:   15.598 ms/op

Iteration   2: 3.810 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  11.032 ms/op
                 getUser·p0.9999: 24.301 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   3: 3.771 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.483 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  10.160 ms/op
                 getUser·p0.9999: 22.561 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250145
  mean =      3.836 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11744 
    [ 2.500,  5.000) = 221953 
    [ 5.000,  7.500) = 14906 
    [ 7.500, 10.000) = 1260 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     10.207 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     25.607 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 7.216 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.535 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.356 ±(99.9%) 0.021 ms/op
Iteration   1: 5.228 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   7.799 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  21.130 ms/op
                 listUser·p0.9999: 29.451 ms/op
                 listUser·p1.00:   29.721 ms/op

Iteration   2: 5.035 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   6.496 ms/op
                 listUser·p0.95:   7.291 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  18.136 ms/op
                 listUser·p0.9999: 21.330 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 5.138 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   6.775 ms/op
                 listUser·p0.95:   7.651 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  22.996 ms/op
                 listUser·p0.9999: 34.705 ms/op
                 listUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186881
  mean =      5.132 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 281 
    [ 2.500,  5.000) = 110797 
    [ 5.000,  7.500) = 65753 
    [ 7.500, 10.000) = 8525 
    [10.000, 12.500) = 932 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.726 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =      9.699 ms/op
     p(99.9000) =     19.435 ms/op
     p(99.9900) =     32.510 ms/op
     p(99.9990) =     35.276 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.113 ± 4.375  ops/ms
ClientGrpc.existUser                       thrpt       3   8.712 ± 1.920  ops/ms
ClientGrpc.getUser                         thrpt       3   7.899 ± 2.004  ops/ms
ClientGrpc.listUser                        thrpt       3   6.326 ± 1.096  ops/ms
ClientGrpc.createUser                       avgt       3   3.930 ± 2.228   ms/op
ClientGrpc.existUser                        avgt       3   3.818 ± 1.450   ms/op
ClientGrpc.getUser                          avgt       3   4.148 ± 1.095   ms/op
ClientGrpc.listUser                         avgt       3   5.130 ± 0.758   ms/op
ClientGrpc.createUser                     sample  234803   4.089 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.902           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.112           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.594           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.045           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.840           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.314           ms/op
ClientGrpc.existUser                      sample  246730   3.890 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.855           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.817           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.259           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.395           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.625           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.409           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.609           ms/op
ClientGrpc.getUser                        sample  250145   3.836 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.483           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.694           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.210           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.816           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.207           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.675           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.018           ms/op
ClientGrpc.listUser                       sample  186881   5.132 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.333           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.586           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.699           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.435           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.510           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.389           ms/op
