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
# Warmup Iteration   1: 4.084 ops/ms
# Warmup Iteration   2: 8.746 ops/ms
# Warmup Iteration   3: 9.906 ops/ms
Iteration   1: 10.378 ops/ms
Iteration   2: 10.266 ops/ms
Iteration   3: 10.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.389 ±(99.9%) 2.347 ops/ms [Average]
  (min, avg, max) = (10.266, 10.389, 10.522), stdev = 0.129
  CI (99.9%): [8.042, 12.736] (assumes normal distribution)


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
# Warmup Iteration   1: 7.897 ops/ms
# Warmup Iteration   2: 10.377 ops/ms
# Warmup Iteration   3: 10.835 ops/ms
Iteration   1: 10.988 ops/ms
Iteration   2: 11.029 ops/ms
Iteration   3: 10.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.941 ±(99.9%) 2.153 ops/ms [Average]
  (min, avg, max) = (10.807, 10.941, 11.029), stdev = 0.118
  CI (99.9%): [8.789, 13.094] (assumes normal distribution)


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
# Warmup Iteration   1: 6.787 ops/ms
# Warmup Iteration   2: 9.991 ops/ms
# Warmup Iteration   3: 10.443 ops/ms
Iteration   1: 10.448 ops/ms
Iteration   2: 10.419 ops/ms
Iteration   3: 10.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.425 ±(99.9%) 0.387 ops/ms [Average]
  (min, avg, max) = (10.407, 10.425, 10.448), stdev = 0.021
  CI (99.9%): [10.038, 10.812] (assumes normal distribution)


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
# Warmup Iteration   1: 5.173 ops/ms
# Warmup Iteration   2: 7.544 ops/ms
# Warmup Iteration   3: 7.861 ops/ms
Iteration   1: 7.863 ops/ms
Iteration   2: 7.937 ops/ms
Iteration   3: 8.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.972 ±(99.9%) 2.396 ops/ms [Average]
  (min, avg, max) = (7.863, 7.972, 8.118), stdev = 0.131
  CI (99.9%): [5.576, 10.369] (assumes normal distribution)


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
# Warmup Iteration   1: 4.385 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.006 ms/op
Iteration   2: 3.088 ±(99.9%) 0.003 ms/op
Iteration   3: 3.028 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.064 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (3.028, 3.064, 3.088), stdev = 0.032
  CI (99.9%): [2.476, 3.652] (assumes normal distribution)


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
# Warmup Iteration   1: 4.276 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.002 ms/op
Iteration   1: 2.976 ±(99.9%) 0.003 ms/op
Iteration   2: 2.953 ±(99.9%) 0.002 ms/op
Iteration   3: 2.957 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.962 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.953, 2.962, 2.976), stdev = 0.012
  CI (99.9%): [2.739, 3.184] (assumes normal distribution)


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.004 ms/op
Iteration   1: 3.109 ±(99.9%) 0.003 ms/op
Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
Iteration   3: 3.079 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.083 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (3.061, 3.083, 3.109), stdev = 0.024
  CI (99.9%): [2.641, 3.525] (assumes normal distribution)


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
# Warmup Iteration   1: 5.404 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.022 ms/op
Iteration   1: 4.035 ±(99.9%) 0.011 ms/op
Iteration   2: 4.015 ±(99.9%) 0.021 ms/op
Iteration   3: 3.981 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.010 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (3.981, 4.010, 4.035), stdev = 0.027
  CI (99.9%): [3.509, 4.511] (assumes normal distribution)


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
# Warmup Iteration   1: 4.404 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  9.630 ms/op
                 createUser·p0.9999: 28.003 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   2: 3.099 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.638 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  11.239 ms/op
                 createUser·p0.9999: 25.909 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   3: 3.093 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  10.273 ms/op
                 createUser·p0.9999: 23.986 ms/op
                 createUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310918
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19761 
    [ 2.500,  5.000) = 289030 
    [ 5.000,  7.500) = 1410 
    [ 7.500, 10.000) = 389 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     27.522 ms/op
     p(99.9990) =     28.242 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
Iteration   1: 2.962 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.864 ms/op
                 existUser·p0.9999: 12.341 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  9.732 ms/op
                 existUser·p0.9999: 12.819 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.962 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  9.757 ms/op
                 existUser·p0.9999: 27.729 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324429
  mean =      2.955 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36468 
    [ 2.500,  5.000) = 286005 
    [ 5.000,  7.500) = 1421 
    [ 7.500, 10.000) = 271 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.875 ms/op
     p(99.9900) =     22.809 ms/op
     p(99.9990) =     28.009 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
Iteration   1: 3.126 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  10.659 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  9.853 ms/op
                 getUser·p0.9999: 20.299 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.789 ms/op
                 getUser·p0.999:  8.316 ms/op
                 getUser·p0.9999: 22.761 ms/op
                 getUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306954
  mean =      3.128 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18398 
    [ 2.500,  5.000) = 286162 
    [ 5.000,  7.500) = 1681 
    [ 7.500, 10.000) = 406 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =     10.012 ms/op
     p(99.9900) =     21.955 ms/op
     p(99.9990) =     23.492 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 5.056 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.242 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.011 ms/op
Iteration   1: 4.050 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.698 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  18.613 ms/op
                 listUser·p0.9999: 20.814 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 4.009 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.982 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.293 ms/op
                 listUser·p0.999:  17.997 ms/op
                 listUser·p0.9999: 29.854 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   3: 4.007 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  16.728 ms/op
                 listUser·p0.9999: 18.778 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238562
  mean =      4.022 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2420 
    [ 2.500,  5.000) = 212439 
    [ 5.000,  7.500) = 21916 
    [ 7.500, 10.000) = 1263 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     27.544 ms/op
     p(99.9990) =     30.351 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.389 ± 2.347  ops/ms
ClientGrpc.existUser                       thrpt       3  10.941 ± 2.153  ops/ms
ClientGrpc.getUser                         thrpt       3  10.425 ± 0.387  ops/ms
ClientGrpc.listUser                        thrpt       3   7.972 ± 2.396  ops/ms
ClientGrpc.createUser                       avgt       3   3.064 ± 0.588   ms/op
ClientGrpc.existUser                        avgt       3   2.962 ± 0.223   ms/op
ClientGrpc.getUser                          avgt       3   3.083 ± 0.442   ms/op
ClientGrpc.listUser                         avgt       3   4.010 ± 0.501   ms/op
ClientGrpc.createUser                     sample  310918   3.087 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.638           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.240           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.522           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.344           ms/op
ClientGrpc.existUser                      sample  324429   2.955 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.799           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.875           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.809           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.115           ms/op
ClientGrpc.getUser                        sample  306954   3.128 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.745           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.012           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.955           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.560           ms/op
ClientGrpc.listUser                       sample  238562   4.022 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.698           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.544           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.409           ms/op
