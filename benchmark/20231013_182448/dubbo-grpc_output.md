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
# Warmup Iteration   1: 3.894 ops/ms
# Warmup Iteration   2: 8.190 ops/ms
# Warmup Iteration   3: 9.350 ops/ms
Iteration   1: 9.768 ops/ms
Iteration   2: 10.197 ops/ms
Iteration   3: 9.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.968 ±(99.9%) 3.942 ops/ms [Average]
  (min, avg, max) = (9.768, 9.968, 10.197), stdev = 0.216
  CI (99.9%): [6.026, 13.911] (assumes normal distribution)


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
# Warmup Iteration   1: 6.595 ops/ms
# Warmup Iteration   2: 9.949 ops/ms
# Warmup Iteration   3: 10.545 ops/ms
Iteration   1: 10.718 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.624 ±(99.9%) 1.729 ops/ms [Average]
  (min, avg, max) = (10.529, 10.624, 10.718), stdev = 0.095
  CI (99.9%): [8.895, 12.353] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.434 ops/ms
# Warmup Iteration   2: 9.539 ops/ms
# Warmup Iteration   3: 9.986 ops/ms
Iteration   1: 10.275 ops/ms
Iteration   2: 9.954 ops/ms
Iteration   3: 10.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.118 ±(99.9%) 2.931 ops/ms [Average]
  (min, avg, max) = (9.954, 10.118, 10.275), stdev = 0.161
  CI (99.9%): [7.187, 13.049] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.652 ops/ms
# Warmup Iteration   2: 7.784 ops/ms
# Warmup Iteration   3: 8.180 ops/ms
Iteration   1: 8.063 ops/ms
Iteration   2: 8.140 ops/ms
Iteration   3: 8.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.149 ±(99.9%) 1.648 ops/ms [Average]
  (min, avg, max) = (8.063, 8.149, 8.243), stdev = 0.090
  CI (99.9%): [6.500, 9.797] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.616 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.438 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.002 ms/op
Iteration   1: 3.219 ±(99.9%) 0.007 ms/op
Iteration   2: 3.068 ±(99.9%) 0.004 ms/op
Iteration   3: 3.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.128 ±(99.9%) 1.458 ms/op [Average]
  (min, avg, max) = (3.068, 3.128, 3.219), stdev = 0.080
  CI (99.9%): [1.670, 4.586] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.071 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.002 ms/op
Iteration   1: 3.079 ±(99.9%) 0.002 ms/op
Iteration   2: 3.006 ±(99.9%) 0.003 ms/op
Iteration   3: 2.976 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.020 ±(99.9%) 0.973 ms/op [Average]
  (min, avg, max) = (2.976, 3.020, 3.079), stdev = 0.053
  CI (99.9%): [2.047, 3.993] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.706 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.002 ms/op
Iteration   1: 3.260 ±(99.9%) 0.002 ms/op
Iteration   2: 3.196 ±(99.9%) 0.002 ms/op
Iteration   3: 3.173 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.210 ±(99.9%) 0.818 ms/op [Average]
  (min, avg, max) = (3.173, 3.210, 3.260), stdev = 0.045
  CI (99.9%): [2.392, 4.027] (assumes normal distribution)


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
# Warmup Iteration   1: 6.519 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.008 ms/op
Iteration   1: 3.982 ±(99.9%) 0.019 ms/op
Iteration   2: 3.970 ±(99.9%) 0.013 ms/op
Iteration   3: 3.943 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.965 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.943, 3.965, 3.982), stdev = 0.020
  CI (99.9%): [3.598, 4.332] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.829 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.008 ms/op
Iteration   1: 3.254 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  9.985 ms/op
                 createUser·p0.9999: 17.012 ms/op
                 createUser·p1.00:   17.596 ms/op

Iteration   2: 3.262 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.827 ms/op
                 createUser·p0.999:  7.782 ms/op
                 createUser·p0.9999: 19.759 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   3: 3.221 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.054 ms/op
                 createUser·p0.999:  16.644 ms/op
                 createUser·p0.9999: 20.382 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 295588
  mean =      3.246 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5334 
    [ 2.500,  5.000) = 287174 
    [ 5.000,  7.500) = 2477 
    [ 7.500, 10.000) = 311 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.046 ms/op
     p(99.9000) =      9.935 ms/op
     p(99.9900) =     20.134 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.882 ms/op
                 existUser·p0.999:  8.550 ms/op
                 existUser·p0.9999: 12.464 ms/op
                 existUser·p1.00:   12.796 ms/op

Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  7.740 ms/op
                 existUser·p0.9999: 14.601 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  7.629 ms/op
                 existUser·p0.9999: 16.697 ms/op
                 existUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316205
  mean =      3.037 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1370 
    [ 1.250,  2.500) = 19870 
    [ 2.500,  3.750) = 273487 
    [ 3.750,  5.000) = 18699 
    [ 5.000,  6.250) = 1674 
    [ 6.250,  7.500) = 680 
    [ 7.500,  8.750) = 193 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      7.928 ms/op
     p(99.9900) =     15.043 ms/op
     p(99.9990) =     17.023 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 4.599 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
Iteration   1: 3.163 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  8.569 ms/op
                 getUser·p0.9999: 17.261 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   2: 3.155 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.145 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 18.973 ms/op
                 getUser·p1.00:   19.661 ms/op

Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  7.751 ms/op
                 getUser·p0.9999: 19.805 ms/op
                 getUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303610
  mean =      3.165 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13821 
    [ 2.500,  5.000) = 285848 
    [ 5.000,  7.500) = 3331 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.291 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     20.970 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 5.025 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.011 ms/op
Iteration   1: 4.047 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 15.776 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   2: 3.990 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  15.149 ms/op
                 listUser·p0.9999: 17.039 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 4.083 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237565
  mean =      4.040 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1291 
    [ 2.500,  3.750) = 78236 
    [ 3.750,  5.000) = 140802 
    [ 5.000,  6.250) = 11799 
    [ 6.250,  7.500) = 3821 
    [ 7.500,  8.750) = 635 
    [ 8.750, 10.000) = 301 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 105 
    [15.000, 16.250) = 109 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     19.013 ms/op
     p(99.9990) =     19.620 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.968 ± 3.942  ops/ms
ClientGrpc.existUser                       thrpt       3  10.624 ± 1.729  ops/ms
ClientGrpc.getUser                         thrpt       3  10.118 ± 2.931  ops/ms
ClientGrpc.listUser                        thrpt       3   8.149 ± 1.648  ops/ms
ClientGrpc.createUser                       avgt       3   3.128 ± 1.458   ms/op
ClientGrpc.existUser                        avgt       3   3.020 ± 0.973   ms/op
ClientGrpc.getUser                          avgt       3   3.210 ± 0.818   ms/op
ClientGrpc.listUser                         avgt       3   3.965 ± 0.367   ms/op
ClientGrpc.createUser                     sample  295588   3.246 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.808           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.191           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.935           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.134           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.037           ms/op
ClientGrpc.existUser                      sample  316205   3.037 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.765           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.866           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.928           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.043           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.203           ms/op
ClientGrpc.getUser                        sample  303610   3.165 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.699           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.002           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.291           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.405           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.268           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.103           ms/op
ClientGrpc.listUser                       sample  237565   4.040 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.221           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.399           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.991           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.013           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.726           ms/op
