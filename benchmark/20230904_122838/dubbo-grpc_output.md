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
# Warmup Iteration   1: 4.334 ops/ms
# Warmup Iteration   2: 9.159 ops/ms
# Warmup Iteration   3: 10.337 ops/ms
Iteration   1: 10.689 ops/ms
Iteration   2: 10.573 ops/ms
Iteration   3: 10.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.563 ±(99.9%) 2.397 ops/ms [Average]
  (min, avg, max) = (10.427, 10.563, 10.689), stdev = 0.131
  CI (99.9%): [8.166, 12.960] (assumes normal distribution)


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
# Warmup Iteration   1: 7.573 ops/ms
# Warmup Iteration   2: 10.648 ops/ms
# Warmup Iteration   3: 10.945 ops/ms
Iteration   1: 10.896 ops/ms
Iteration   2: 11.075 ops/ms
Iteration   3: 10.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.976 ±(99.9%) 1.658 ops/ms [Average]
  (min, avg, max) = (10.896, 10.976, 11.075), stdev = 0.091
  CI (99.9%): [9.318, 12.634] (assumes normal distribution)


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
# Warmup Iteration   1: 7.259 ops/ms
# Warmup Iteration   2: 10.115 ops/ms
# Warmup Iteration   3: 10.546 ops/ms
Iteration   1: 10.722 ops/ms
Iteration   2: 10.601 ops/ms
Iteration   3: 10.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.681 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (10.601, 10.681, 10.722), stdev = 0.070
  CI (99.9%): [9.408, 11.954] (assumes normal distribution)


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
# Warmup Iteration   1: 5.580 ops/ms
# Warmup Iteration   2: 8.102 ops/ms
# Warmup Iteration   3: 8.217 ops/ms
Iteration   1: 8.430 ops/ms
Iteration   2: 8.266 ops/ms
Iteration   3: 8.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.368 ±(99.9%) 1.626 ops/ms [Average]
  (min, avg, max) = (8.266, 8.368, 8.430), stdev = 0.089
  CI (99.9%): [6.741, 9.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.005 ms/op
Iteration   1: 3.052 ±(99.9%) 0.004 ms/op
Iteration   2: 3.013 ±(99.9%) 0.004 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.038 ±(99.9%) 0.403 ms/op [Average]
  (min, avg, max) = (3.013, 3.038, 3.052), stdev = 0.022
  CI (99.9%): [2.635, 3.441] (assumes normal distribution)


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.003 ms/op
Iteration   1: 2.908 ±(99.9%) 0.003 ms/op
Iteration   2: 2.890 ±(99.9%) 0.005 ms/op
Iteration   3: 2.858 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.885 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (2.858, 2.885, 2.908), stdev = 0.025
  CI (99.9%): [2.429, 3.341] (assumes normal distribution)


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.003 ms/op
Iteration   1: 3.039 ±(99.9%) 0.003 ms/op
Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
Iteration   3: 2.993 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.008 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (2.992, 3.008, 3.039), stdev = 0.027
  CI (99.9%): [2.515, 3.501] (assumes normal distribution)


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.013 ms/op
Iteration   1: 3.903 ±(99.9%) 0.025 ms/op
Iteration   2: 3.872 ±(99.9%) 0.034 ms/op
Iteration   3: 3.900 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (3.872, 3.892, 3.903), stdev = 0.017
  CI (99.9%): [3.585, 4.199] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.001 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  7.722 ms/op
                 createUser·p0.9999: 12.932 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.809 ms/op
                 createUser·p0.9999: 18.557 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 17.269 ms/op
                 createUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318776
  mean =      3.013 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1955 
    [ 1.250,  2.500) = 23992 
    [ 2.500,  3.750) = 275991 
    [ 3.750,  5.000) = 14954 
    [ 5.000,  6.250) = 1010 
    [ 6.250,  7.500) = 462 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      8.217 ms/op
     p(99.9900) =     17.736 ms/op
     p(99.9990) =     19.425 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.956 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.007 ms/op
Iteration   1: 2.924 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.391 ms/op
                 existUser·p0.9999: 12.584 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   2: 2.858 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.493 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.963 ms/op
                 existUser·p0.9999: 12.377 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.890 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.522 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  7.315 ms/op
                 existUser·p0.9999: 25.068 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332106
  mean =      2.890 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45767 
    [ 2.500,  5.000) = 284625 
    [ 5.000,  7.500) = 1436 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.224 ms/op
     p(99.9900) =     16.406 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 4.309 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 14.102 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.635 ms/op
                 getUser·p0.999:  8.233 ms/op
                 getUser·p0.9999: 13.418 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.855 ms/op
                 getUser·p0.9999: 17.463 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319615
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1656 
    [ 1.250,  2.500) = 30750 
    [ 2.500,  3.750) = 267669 
    [ 3.750,  5.000) = 17601 
    [ 5.000,  6.250) = 1093 
    [ 6.250,  7.500) = 343 
    [ 7.500,  8.750) = 230 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      8.261 ms/op
     p(99.9900) =     16.516 ms/op
     p(99.9990) =     17.780 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.863 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.010 ms/op
Iteration   1: 3.957 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.343 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  11.469 ms/op
                 listUser·p0.9999: 15.116 ms/op
                 listUser·p1.00:   15.598 ms/op

Iteration   2: 3.887 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.775 ms/op
                 listUser·p0.9999: 20.276 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   3: 3.889 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.557 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.560 ms/op
                 listUser·p0.9999: 20.480 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245492
  mean =      3.911 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3885 
    [ 2.500,  5.000) = 220154 
    [ 5.000,  7.500) = 20030 
    [ 7.500, 10.000) = 925 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.343 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.099 ms/op
     p(99.9900) =     20.200 ms/op
     p(99.9990) =     20.894 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.563 ± 2.397  ops/ms
ClientGrpc.existUser                       thrpt       3  10.976 ± 1.658  ops/ms
ClientGrpc.getUser                         thrpt       3  10.681 ± 1.273  ops/ms
ClientGrpc.listUser                        thrpt       3   8.368 ± 1.626  ops/ms
ClientGrpc.createUser                       avgt       3   3.038 ± 0.403   ms/op
ClientGrpc.existUser                        avgt       3   2.885 ± 0.456   ms/op
ClientGrpc.getUser                          avgt       3   3.008 ± 0.493   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 0.307   ms/op
ClientGrpc.createUser                     sample  318776   3.013 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.676           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.217           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.736           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.497           ms/op
ClientGrpc.existUser                      sample  332106   2.890 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.493           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.224           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.406           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.968           ms/op
ClientGrpc.getUser                        sample  319615   3.006 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.607           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.261           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.516           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.859           ms/op
ClientGrpc.listUser                       sample  245492   3.911 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.343           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.099           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.200           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.168           ms/op
