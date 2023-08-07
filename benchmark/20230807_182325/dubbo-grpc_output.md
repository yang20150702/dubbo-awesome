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
# Warmup Iteration   1: 4.129 ops/ms
# Warmup Iteration   2: 9.400 ops/ms
# Warmup Iteration   3: 10.065 ops/ms
Iteration   1: 10.576 ops/ms
Iteration   2: 10.563 ops/ms
Iteration   3: 10.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.521 ±(99.9%) 1.541 ops/ms [Average]
  (min, avg, max) = (10.423, 10.521, 10.576), stdev = 0.084
  CI (99.9%): [8.980, 12.062] (assumes normal distribution)


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
# Warmup Iteration   1: 7.615 ops/ms
# Warmup Iteration   2: 10.589 ops/ms
# Warmup Iteration   3: 11.004 ops/ms
Iteration   1: 10.940 ops/ms
Iteration   2: 11.078 ops/ms
Iteration   3: 11.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.061 ±(99.9%) 2.058 ops/ms [Average]
  (min, avg, max) = (10.940, 11.061, 11.164), stdev = 0.113
  CI (99.9%): [9.002, 13.119] (assumes normal distribution)


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
# Warmup Iteration   1: 6.935 ops/ms
# Warmup Iteration   2: 10.157 ops/ms
# Warmup Iteration   3: 10.658 ops/ms
Iteration   1: 10.610 ops/ms
Iteration   2: 10.656 ops/ms
Iteration   3: 10.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.602 ±(99.9%) 1.061 ops/ms [Average]
  (min, avg, max) = (10.541, 10.602, 10.656), stdev = 0.058
  CI (99.9%): [9.541, 11.664] (assumes normal distribution)


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
# Warmup Iteration   1: 5.265 ops/ms
# Warmup Iteration   2: 7.780 ops/ms
# Warmup Iteration   3: 7.868 ops/ms
Iteration   1: 7.958 ops/ms
Iteration   2: 7.892 ops/ms
Iteration   3: 7.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.909 ±(99.9%) 0.784 ops/ms [Average]
  (min, avg, max) = (7.878, 7.909, 7.958), stdev = 0.043
  CI (99.9%): [7.126, 8.693] (assumes normal distribution)


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
# Warmup Iteration   1: 4.319 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.004 ms/op
Iteration   1: 3.027 ±(99.9%) 0.002 ms/op
Iteration   2: 3.014 ±(99.9%) 0.003 ms/op
Iteration   3: 3.071 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.038 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (3.014, 3.038, 3.071), stdev = 0.029
  CI (99.9%): [2.501, 3.574] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.002 ms/op
Iteration   1: 2.876 ±(99.9%) 0.002 ms/op
Iteration   2: 2.845 ±(99.9%) 0.002 ms/op
Iteration   3: 2.878 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.867 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.845, 2.867, 2.878), stdev = 0.018
  CI (99.9%): [2.533, 3.201] (assumes normal distribution)


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
# Warmup Iteration   1: 4.378 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.002 ms/op
Iteration   1: 3.063 ±(99.9%) 0.003 ms/op
Iteration   2: 3.020 ±(99.9%) 0.004 ms/op
Iteration   3: 2.993 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.025 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (2.993, 3.025, 3.063), stdev = 0.036
  CI (99.9%): [2.378, 3.673] (assumes normal distribution)


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
# Warmup Iteration   1: 5.230 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.216 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.013 ms/op
Iteration   1: 3.959 ±(99.9%) 0.010 ms/op
Iteration   2: 3.961 ±(99.9%) 0.009 ms/op
Iteration   3: 4.033 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.984 ±(99.9%) 0.764 ms/op [Average]
  (min, avg, max) = (3.959, 3.984, 4.033), stdev = 0.042
  CI (99.9%): [3.220, 4.749] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  7.897 ms/op
                 createUser·p0.9999: 12.747 ms/op
                 createUser·p1.00:   12.960 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.660 ms/op
                 createUser·p0.9999: 16.552 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.907 ms/op
                 createUser·p0.999:  10.262 ms/op
                 createUser·p0.9999: 17.629 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317604
  mean =      3.021 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1683 
    [ 1.250,  2.500) = 25623 
    [ 2.500,  3.750) = 270968 
    [ 3.750,  5.000) = 17072 
    [ 5.000,  6.250) = 1202 
    [ 6.250,  7.500) = 533 
    [ 7.500,  8.750) = 254 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      8.198 ms/op
     p(99.9900) =     17.080 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 2.889 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.865 ms/op
                 existUser·p0.9999: 18.769 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   2: 2.900 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.812 ms/op
                 existUser·p0.9999: 13.844 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.548 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  10.863 ms/op
                 existUser·p0.9999: 18.874 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331455
  mean =      2.897 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1477 
    [ 1.250,  2.500) = 35919 
    [ 2.500,  3.750) = 284540 
    [ 3.750,  5.000) = 7941 
    [ 5.000,  6.250) = 730 
    [ 6.250,  7.500) = 465 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.705 ms/op
     p(99.9900) =     18.706 ms/op
     p(99.9990) =     19.323 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 4.429 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
Iteration   1: 3.151 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.594 ms/op
                 getUser·p0.9999: 13.959 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  7.633 ms/op
                 getUser·p0.9999: 15.041 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.237 ms/op
                 getUser·p0.9999: 16.963 ms/op
                 getUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308980
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 592 
    [ 1.250,  2.500) = 16061 
    [ 2.500,  3.750) = 268650 
    [ 3.750,  5.000) = 21677 
    [ 5.000,  6.250) = 925 
    [ 6.250,  7.500) = 599 
    [ 7.500,  8.750) = 270 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      8.184 ms/op
     p(99.9900) =     16.566 ms/op
     p(99.9990) =     18.521 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 5.768 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.011 ms/op
Iteration   1: 4.080 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.448 ms/op
                 listUser·p0.999:  14.855 ms/op
                 listUser·p0.9999: 20.289 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 4.030 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  15.084 ms/op
                 listUser·p0.9999: 23.923 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   3: 4.035 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  14.942 ms/op
                 listUser·p0.9999: 30.842 ms/op
                 listUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237009
  mean =      4.048 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1710 
    [ 2.500,  5.000) = 209658 
    [ 5.000,  7.500) = 23830 
    [ 7.500, 10.000) = 1292 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     29.491 ms/op
     p(99.9990) =     31.302 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.521 ± 1.541  ops/ms
ClientGrpc.existUser                       thrpt       3  11.061 ± 2.058  ops/ms
ClientGrpc.getUser                         thrpt       3  10.602 ± 1.061  ops/ms
ClientGrpc.listUser                        thrpt       3   7.909 ± 0.784  ops/ms
ClientGrpc.createUser                       avgt       3   3.038 ± 0.536   ms/op
ClientGrpc.existUser                        avgt       3   2.867 ± 0.334   ms/op
ClientGrpc.getUser                          avgt       3   3.025 ± 0.648   ms/op
ClientGrpc.listUser                         avgt       3   3.984 ± 0.764   ms/op
ClientGrpc.createUser                     sample  317604   3.021 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.790           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.198           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.080           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.038           ms/op
ClientGrpc.existUser                      sample  331455   2.897 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.548           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.705           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.706           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.530           ms/op
ClientGrpc.getUser                        sample  308980   3.106 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.726           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.903           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.184           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.566           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.842           ms/op
ClientGrpc.listUser                       sample  237009   4.048 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.128           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.942           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.491           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.425           ms/op
