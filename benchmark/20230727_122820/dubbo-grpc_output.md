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
# Warmup Iteration   1: 4.517 ops/ms
# Warmup Iteration   2: 9.070 ops/ms
# Warmup Iteration   3: 10.102 ops/ms
Iteration   1: 10.553 ops/ms
Iteration   2: 10.603 ops/ms
Iteration   3: 10.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.656 ±(99.9%) 2.509 ops/ms [Average]
  (min, avg, max) = (10.553, 10.656, 10.813), stdev = 0.138
  CI (99.9%): [8.147, 13.165] (assumes normal distribution)


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
# Warmup Iteration   1: 7.713 ops/ms
# Warmup Iteration   2: 10.665 ops/ms
# Warmup Iteration   3: 11.099 ops/ms
Iteration   1: 11.216 ops/ms
Iteration   2: 11.256 ops/ms
Iteration   3: 11.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.216 ±(99.9%) 0.737 ops/ms [Average]
  (min, avg, max) = (11.175, 11.216, 11.256), stdev = 0.040
  CI (99.9%): [10.479, 11.953] (assumes normal distribution)


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
# Warmup Iteration   1: 7.323 ops/ms
# Warmup Iteration   2: 10.275 ops/ms
# Warmup Iteration   3: 10.570 ops/ms
Iteration   1: 10.530 ops/ms
Iteration   2: 10.876 ops/ms
Iteration   3: 10.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.629 ±(99.9%) 3.922 ops/ms [Average]
  (min, avg, max) = (10.481, 10.629, 10.876), stdev = 0.215
  CI (99.9%): [6.707, 14.551] (assumes normal distribution)


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
# Warmup Iteration   1: 6.157 ops/ms
# Warmup Iteration   2: 8.152 ops/ms
# Warmup Iteration   3: 8.201 ops/ms
Iteration   1: 8.148 ops/ms
Iteration   2: 8.567 ops/ms
Iteration   3: 8.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.407 ±(99.9%) 4.139 ops/ms [Average]
  (min, avg, max) = (8.148, 8.407, 8.567), stdev = 0.227
  CI (99.9%): [4.268, 12.546] (assumes normal distribution)


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
# Warmup Iteration   1: 4.165 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.002 ms/op
Iteration   1: 3.006 ±(99.9%) 0.002 ms/op
Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
Iteration   3: 3.062 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.028 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (3.006, 3.028, 3.062), stdev = 0.030
  CI (99.9%): [2.475, 3.581] (assumes normal distribution)


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.811 ±(99.9%) 0.004 ms/op
Iteration   1: 2.879 ±(99.9%) 0.004 ms/op
Iteration   2: 2.832 ±(99.9%) 0.004 ms/op
Iteration   3: 2.865 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.858 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (2.832, 2.858, 2.879), stdev = 0.024
  CI (99.9%): [2.419, 3.298] (assumes normal distribution)


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.003 ms/op
Iteration   1: 2.979 ±(99.9%) 0.003 ms/op
Iteration   2: 2.937 ±(99.9%) 0.003 ms/op
Iteration   3: 2.957 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.958 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (2.937, 2.958, 2.979), stdev = 0.021
  CI (99.9%): [2.576, 3.339] (assumes normal distribution)


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
# Warmup Iteration   1: 4.814 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.030 ms/op
Iteration   1: 3.831 ±(99.9%) 0.015 ms/op
Iteration   2: 3.779 ±(99.9%) 0.018 ms/op
Iteration   3: 3.762 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.791 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (3.762, 3.791, 3.831), stdev = 0.036
  CI (99.9%): [3.137, 4.444] (assumes normal distribution)


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
Iteration   1: 2.977 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  9.348 ms/op
                 createUser·p0.9999: 20.554 ms/op
                 createUser·p1.00:   20.939 ms/op

Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  6.882 ms/op
                 createUser·p0.9999: 16.211 ms/op
                 createUser·p1.00:   16.663 ms/op

Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.170 ms/op
                 createUser·p0.999:  10.437 ms/op
                 createUser·p0.9999: 18.416 ms/op
                 createUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322273
  mean =      2.977 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29944 
    [ 2.500,  5.000) = 291196 
    [ 5.000,  7.500) = 719 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.675 ms/op
     p(99.9900) =     18.630 ms/op
     p(99.9990) =     20.866 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.005 ms/op
Iteration   1: 2.872 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  5.947 ms/op
                 existUser·p0.9999: 12.054 ms/op
                 existUser·p1.00:   12.337 ms/op

Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.131 ms/op
                 existUser·p0.9999: 19.628 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   3: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  6.114 ms/op
                 existUser·p0.9999: 14.200 ms/op
                 existUser·p1.00:   14.631 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332100
  mean =      2.889 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1363 
    [ 1.250,  2.500) = 48383 
    [ 2.500,  3.750) = 271628 
    [ 3.750,  5.000) = 9784 
    [ 5.000,  6.250) = 599 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      6.291 ms/op
     p(99.9900) =     14.614 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.007 ms/op
Iteration   1: 2.944 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.559 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.684 ms/op
                 getUser·p0.9999: 27.792 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   2: 3.008 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  11.687 ms/op
                 getUser·p0.9999: 57.368 ms/op
                 getUser·p1.00:   62.783 ms/op

Iteration   3: 2.985 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  9.894 ms/op
                 getUser·p0.9999: 21.628 ms/op
                 getUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322112
  mean =      2.979 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 320717 
    [ 5.000, 10.000) = 1110 
    [10.000, 15.000) = 54 
    [15.000, 20.000) = 103 
    [20.000, 25.000) = 62 
    [25.000, 30.000) = 34 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 16 
    [60.000, 65.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.345 ms/op
     p(99.9900) =     31.133 ms/op
     p(99.9990) =     58.430 ms/op
     p(99.9999) =     62.783 ms/op
    p(100.0000) =     62.783 ms/op


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
# Warmup Iteration   1: 4.956 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.010 ms/op
Iteration   1: 3.834 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.787 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  12.250 ms/op
                 listUser·p0.9999: 19.420 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   2: 3.758 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  15.349 ms/op
                 listUser·p0.9999: 20.184 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   3: 3.922 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.670 ms/op
                 listUser·p0.999:  15.062 ms/op
                 listUser·p0.9999: 25.952 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250269
  mean =      3.837 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6984 
    [ 2.500,  5.000) = 221759 
    [ 5.000,  7.500) = 20481 
    [ 7.500, 10.000) = 589 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     25.165 ms/op
     p(99.9990) =     26.181 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.656 ± 2.509  ops/ms
ClientGrpc.existUser                       thrpt       3  11.216 ± 0.737  ops/ms
ClientGrpc.getUser                         thrpt       3  10.629 ± 3.922  ops/ms
ClientGrpc.listUser                        thrpt       3   8.407 ± 4.139  ops/ms
ClientGrpc.createUser                       avgt       3   3.028 ± 0.553   ms/op
ClientGrpc.existUser                        avgt       3   2.858 ± 0.440   ms/op
ClientGrpc.getUser                          avgt       3   2.958 ± 0.382   ms/op
ClientGrpc.listUser                         avgt       3   3.791 ± 0.654   ms/op
ClientGrpc.createUser                     sample  322273   2.977 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.553           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.675           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.630           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.939           ms/op
ClientGrpc.existUser                      sample  332100   2.889 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.721           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.291           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.614           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.857           ms/op
ClientGrpc.getUser                        sample  322112   2.979 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.555           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.345           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.133           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          62.783           ms/op
ClientGrpc.listUser                       sample  250269   3.837 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.787           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.762           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.165           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.247           ms/op
