# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.304 ops/ms
# Warmup Iteration   2: 9.459 ops/ms
# Warmup Iteration   3: 10.345 ops/ms
Iteration   1: 10.873 ops/ms
Iteration   2: 10.782 ops/ms
Iteration   3: 10.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.755 ±(99.9%) 2.453 ops/ms [Average]
  (min, avg, max) = (10.609, 10.755, 10.873), stdev = 0.134
  CI (99.9%): [8.302, 13.208] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.005 ops/ms
# Warmup Iteration   2: 10.751 ops/ms
# Warmup Iteration   3: 11.129 ops/ms
Iteration   1: 11.304 ops/ms
Iteration   2: 11.153 ops/ms
Iteration   3: 11.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.318 ±(99.9%) 3.159 ops/ms [Average]
  (min, avg, max) = (11.153, 11.318, 11.499), stdev = 0.173
  CI (99.9%): [8.160, 14.477] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.214 ops/ms
# Warmup Iteration   2: 10.380 ops/ms
# Warmup Iteration   3: 10.761 ops/ms
Iteration   1: 10.675 ops/ms
Iteration   2: 10.706 ops/ms
Iteration   3: 10.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.667 ±(99.9%) 0.802 ops/ms [Average]
  (min, avg, max) = (10.620, 10.667, 10.706), stdev = 0.044
  CI (99.9%): [9.865, 11.469] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.090 ops/ms
# Warmup Iteration   2: 7.848 ops/ms
# Warmup Iteration   3: 8.117 ops/ms
Iteration   1: 8.288 ops/ms
Iteration   2: 8.146 ops/ms
Iteration   3: 8.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.213 ±(99.9%) 1.296 ops/ms [Average]
  (min, avg, max) = (8.146, 8.213, 8.288), stdev = 0.071
  CI (99.9%): [6.917, 9.509] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.514 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.003 ms/op
Iteration   1: 2.944 ±(99.9%) 0.007 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 2.986 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.975 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (2.944, 2.975, 2.994), stdev = 0.027
  CI (99.9%): [2.487, 3.462] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.002 ms/op
Iteration   1: 2.969 ±(99.9%) 0.003 ms/op
Iteration   2: 2.849 ±(99.9%) 0.002 ms/op
Iteration   3: 2.927 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.915 ±(99.9%) 1.119 ms/op [Average]
  (min, avg, max) = (2.849, 2.915, 2.969), stdev = 0.061
  CI (99.9%): [1.796, 4.034] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.106 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 3.000 ±(99.9%) 0.004 ms/op
Iteration   2: 2.973 ±(99.9%) 0.002 ms/op
Iteration   3: 2.918 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.964 ±(99.9%) 0.767 ms/op [Average]
  (min, avg, max) = (2.918, 2.964, 3.000), stdev = 0.042
  CI (99.9%): [2.197, 3.730] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.501 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.014 ms/op
Iteration   1: 3.847 ±(99.9%) 0.021 ms/op
Iteration   2: 3.888 ±(99.9%) 0.034 ms/op
Iteration   3: 3.868 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.868 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.847, 3.868, 3.888), stdev = 0.021
  CI (99.9%): [3.493, 4.243] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.219 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.293 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.605 ms/op
                 createUser·p0.9999: 12.115 ms/op
                 createUser·p1.00:   12.452 ms/op

Iteration   2: 2.990 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  6.576 ms/op
                 createUser·p0.9999: 13.587 ms/op
                 createUser·p1.00:   13.828 ms/op

Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  14.549 ms/op
                 createUser·p0.9999: 17.882 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319120
  mean =      3.009 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1183 
    [ 1.250,  2.500) = 29484 
    [ 2.500,  3.750) = 274357 
    [ 3.750,  5.000) = 12645 
    [ 5.000,  6.250) = 757 
    [ 6.250,  7.500) = 305 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.293 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.897 ms/op
     p(99.9900) =     16.487 ms/op
     p(99.9990) =     18.305 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.645 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.005 ms/op
Iteration   1: 2.846 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.310 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  5.985 ms/op
                 existUser·p0.9999: 16.626 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   2: 2.886 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  7.012 ms/op
                 existUser·p0.9999: 19.956 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   3: 2.800 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.334 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  11.301 ms/op
                 existUser·p0.9999: 15.642 ms/op
                 existUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337692
  mean =      2.843 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46906 
    [ 2.500,  5.000) = 289970 
    [ 5.000,  7.500) = 490 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.224 ms/op
     p(95.0000) =      3.367 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      7.121 ms/op
     p(99.9900) =     16.850 ms/op
     p(99.9990) =     20.140 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.136 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.438 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.299 ms/op
                 getUser·p0.9999: 18.754 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  9.559 ms/op
                 getUser·p0.9999: 17.269 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.245 ms/op
                 getUser·p0.9999: 27.654 ms/op
                 getUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318513
  mean =      3.014 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24519 
    [ 2.500,  5.000) = 292611 
    [ 5.000,  7.500) = 1009 
    [ 7.500, 10.000) = 139 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.544 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     28.011 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.338 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.010 ms/op
Iteration   1: 3.930 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.907 ms/op
                 listUser·p0.999:  13.213 ms/op
                 listUser·p0.9999: 17.100 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   2: 3.902 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.612 ms/op
                 listUser·p0.9999: 21.522 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 3.937 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  16.630 ms/op
                 listUser·p0.9999: 23.712 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244715
  mean =      3.923 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2433 
    [ 2.500,  5.000) = 221392 
    [ 5.000,  7.500) = 19513 
    [ 7.500, 10.000) = 907 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     15.148 ms/op
     p(99.9900) =     22.660 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.755 ± 2.453  ops/ms
ClientGrpc.existUser                       thrpt       3  11.318 ± 3.159  ops/ms
ClientGrpc.getUser                         thrpt       3  10.667 ± 0.802  ops/ms
ClientGrpc.listUser                        thrpt       3   8.213 ± 1.296  ops/ms
ClientGrpc.createUser                       avgt       3   2.975 ± 0.488   ms/op
ClientGrpc.existUser                        avgt       3   2.915 ± 1.119   ms/op
ClientGrpc.getUser                          avgt       3   2.964 ± 0.767   ms/op
ClientGrpc.listUser                         avgt       3   3.868 ± 0.375   ms/op
ClientGrpc.createUser                     sample  319120   3.009 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.293           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.897           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.487           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.645           ms/op
ClientGrpc.existUser                      sample  337692   2.843 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.769           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.843           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.224           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.121           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.850           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.382           ms/op
ClientGrpc.getUser                        sample  318513   3.014 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.785           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.544           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.804           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.082           ms/op
ClientGrpc.listUser                       sample  244715   3.923 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.167           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.148           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.660           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.117           ms/op
