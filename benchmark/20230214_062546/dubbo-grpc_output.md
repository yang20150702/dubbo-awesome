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
# Warmup Iteration   1: 4.216 ops/ms
# Warmup Iteration   2: 9.210 ops/ms
# Warmup Iteration   3: 10.058 ops/ms
Iteration   1: 10.210 ops/ms
Iteration   2: 10.069 ops/ms
Iteration   3: 10.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.151 ±(99.9%) 1.339 ops/ms [Average]
  (min, avg, max) = (10.069, 10.151, 10.210), stdev = 0.073
  CI (99.9%): [8.812, 11.491] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.321 ops/ms
# Warmup Iteration   2: 10.329 ops/ms
# Warmup Iteration   3: 11.233 ops/ms
Iteration   1: 10.716 ops/ms
Iteration   2: 10.781 ops/ms
Iteration   3: 10.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.743 ±(99.9%) 0.623 ops/ms [Average]
  (min, avg, max) = (10.716, 10.743, 10.781), stdev = 0.034
  CI (99.9%): [10.119, 11.366] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.155 ops/ms
# Warmup Iteration   2: 10.130 ops/ms
# Warmup Iteration   3: 10.150 ops/ms
Iteration   1: 10.217 ops/ms
Iteration   2: 10.336 ops/ms
Iteration   3: 9.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.175 ±(99.9%) 3.403 ops/ms [Average]
  (min, avg, max) = (9.971, 10.175, 10.336), stdev = 0.187
  CI (99.9%): [6.772, 13.577] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.426 ops/ms
# Warmup Iteration   2: 7.807 ops/ms
# Warmup Iteration   3: 7.825 ops/ms
Iteration   1: 7.894 ops/ms
Iteration   2: 8.107 ops/ms
Iteration   3: 7.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.989 ±(99.9%) 1.977 ops/ms [Average]
  (min, avg, max) = (7.894, 7.989, 8.107), stdev = 0.108
  CI (99.9%): [6.012, 9.966] (assumes normal distribution)


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.002 ms/op
Iteration   1: 3.186 ±(99.9%) 0.002 ms/op
Iteration   2: 3.252 ±(99.9%) 0.002 ms/op
Iteration   3: 3.187 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.208 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (3.186, 3.208, 3.252), stdev = 0.038
  CI (99.9%): [2.522, 3.895] (assumes normal distribution)


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.002 ms/op
Iteration   1: 3.035 ±(99.9%) 0.002 ms/op
Iteration   2: 3.013 ±(99.9%) 0.002 ms/op
Iteration   3: 2.921 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.989 ±(99.9%) 1.100 ms/op [Average]
  (min, avg, max) = (2.921, 2.989, 3.035), stdev = 0.060
  CI (99.9%): [1.890, 4.089] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.044 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.003 ms/op
Iteration   1: 3.122 ±(99.9%) 0.001 ms/op
Iteration   2: 3.156 ±(99.9%) 0.002 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.117 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (3.072, 3.117, 3.156), stdev = 0.042
  CI (99.9%): [2.345, 3.888] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.323 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.013 ms/op
Iteration   1: 4.035 ±(99.9%) 0.028 ms/op
Iteration   2: 3.922 ±(99.9%) 0.008 ms/op
Iteration   3: 3.863 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.940 ±(99.9%) 1.596 ms/op [Average]
  (min, avg, max) = (3.863, 3.940, 4.035), stdev = 0.087
  CI (99.9%): [2.345, 5.536] (assumes normal distribution)


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.006 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.652 ms/op
                 createUser·p0.9999: 14.418 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.397 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.811 ms/op
                 createUser·p0.9999: 16.449 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   3: 3.194 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.627 ms/op
                 createUser·p0.9999: 20.020 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306753
  mean =      3.130 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22953 
    [ 2.500,  5.000) = 282996 
    [ 5.000,  7.500) = 498 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.502 ms/op
     p(99.9900) =     17.836 ms/op
     p(99.9990) =     20.412 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.428 ms/op
                 existUser·p0.9999: 11.611 ms/op
                 existUser·p1.00:   12.141 ms/op

Iteration   2: 2.901 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  5.430 ms/op
                 existUser·p0.9999: 12.730 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   3: 2.978 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  11.787 ms/op
                 existUser·p0.9999: 15.462 ms/op
                 existUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324413
  mean =      2.959 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2521 
    [ 1.250,  2.500) = 44447 
    [ 2.500,  3.750) = 257589 
    [ 3.750,  5.000) = 18962 
    [ 5.000,  6.250) = 390 
    [ 6.250,  7.500) = 166 
    [ 7.500,  8.750) = 101 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.623 ms/op
     p(99.9900) =     14.626 ms/op
     p(99.9990) =     15.876 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.971 ms/op
                 getUser·p0.9999: 11.213 ms/op
                 getUser·p1.00:   11.649 ms/op

Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.787 ms/op
                 getUser·p0.9999: 16.941 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   3: 3.065 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  6.488 ms/op
                 getUser·p0.9999: 14.495 ms/op
                 getUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311562
  mean =      3.080 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1534 
    [ 1.250,  2.500) = 21853 
    [ 2.500,  3.750) = 262107 
    [ 3.750,  5.000) = 25181 
    [ 5.000,  6.250) = 375 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.147 ms/op
     p(99.9900) =     16.069 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.011 ms/op
Iteration   1: 3.963 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  12.045 ms/op
                 listUser·p0.9999: 15.853 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   2: 4.014 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.315 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  14.123 ms/op
                 listUser·p0.9999: 27.002 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   3: 3.924 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  16.015 ms/op
                 listUser·p0.9999: 21.982 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242106
  mean =      3.967 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5130 
    [ 2.500,  5.000) = 208165 
    [ 5.000,  7.500) = 27450 
    [ 7.500, 10.000) = 915 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.315 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     23.062 ms/op
     p(99.9990) =     27.249 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.151 ± 1.339  ops/ms
ClientGrpc.existUser                       thrpt       3  10.743 ± 0.623  ops/ms
ClientGrpc.getUser                         thrpt       3  10.175 ± 3.403  ops/ms
ClientGrpc.listUser                        thrpt       3   7.989 ± 1.977  ops/ms
ClientGrpc.createUser                       avgt       3   3.208 ± 0.687   ms/op
ClientGrpc.existUser                        avgt       3   2.989 ± 1.100   ms/op
ClientGrpc.getUser                          avgt       3   3.117 ± 0.771   ms/op
ClientGrpc.listUser                         avgt       3   3.940 ± 1.596   ms/op
ClientGrpc.createUser                     sample  306753   3.130 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.397           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.502           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.836           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.513           ms/op
ClientGrpc.existUser                      sample  324413   2.959 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.517           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.623           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.626           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.991           ms/op
ClientGrpc.getUser                        sample  311562   3.080 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.727           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.147           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.069           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.269           ms/op
ClientGrpc.listUser                       sample  242106   3.967 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.315           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.090           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.062           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.296           ms/op
