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
# Warmup Iteration   1: 4.374 ops/ms
# Warmup Iteration   2: 9.154 ops/ms
# Warmup Iteration   3: 10.112 ops/ms
Iteration   1: 10.607 ops/ms
Iteration   2: 10.638 ops/ms
Iteration   3: 10.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.628 ±(99.9%) 0.332 ops/ms [Average]
  (min, avg, max) = (10.607, 10.628, 10.639), stdev = 0.018
  CI (99.9%): [10.296, 10.959] (assumes normal distribution)


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
# Warmup Iteration   1: 7.844 ops/ms
# Warmup Iteration   2: 10.540 ops/ms
# Warmup Iteration   3: 11.186 ops/ms
Iteration   1: 10.919 ops/ms
Iteration   2: 10.924 ops/ms
Iteration   3: 11.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.983 ±(99.9%) 1.944 ops/ms [Average]
  (min, avg, max) = (10.919, 10.983, 11.106), stdev = 0.107
  CI (99.9%): [9.039, 12.927] (assumes normal distribution)


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
# Warmup Iteration   1: 7.232 ops/ms
# Warmup Iteration   2: 10.325 ops/ms
# Warmup Iteration   3: 10.674 ops/ms
Iteration   1: 10.618 ops/ms
Iteration   2: 10.428 ops/ms
Iteration   3: 10.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.472 ±(99.9%) 2.355 ops/ms [Average]
  (min, avg, max) = (10.372, 10.472, 10.618), stdev = 0.129
  CI (99.9%): [8.117, 12.827] (assumes normal distribution)


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
# Warmup Iteration   1: 5.510 ops/ms
# Warmup Iteration   2: 7.679 ops/ms
# Warmup Iteration   3: 8.139 ops/ms
Iteration   1: 8.136 ops/ms
Iteration   2: 8.115 ops/ms
Iteration   3: 8.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.142 ±(99.9%) 0.554 ops/ms [Average]
  (min, avg, max) = (8.115, 8.142, 8.175), stdev = 0.030
  CI (99.9%): [7.588, 8.696] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.002 ms/op
Iteration   1: 3.065 ±(99.9%) 0.002 ms/op
Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
Iteration   3: 3.040 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.043 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (3.026, 3.043, 3.065), stdev = 0.020
  CI (99.9%): [2.678, 3.409] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.103 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.004 ms/op
Iteration   1: 2.830 ±(99.9%) 0.005 ms/op
Iteration   2: 2.904 ±(99.9%) 0.003 ms/op
Iteration   3: 2.883 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.872 ±(99.9%) 0.692 ms/op [Average]
  (min, avg, max) = (2.830, 2.872, 2.904), stdev = 0.038
  CI (99.9%): [2.180, 3.565] (assumes normal distribution)


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.002 ms/op
Iteration   1: 3.141 ±(99.9%) 0.003 ms/op
Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
Iteration   3: 3.043 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.087 ±(99.9%) 0.910 ms/op [Average]
  (min, avg, max) = (3.043, 3.087, 3.141), stdev = 0.050
  CI (99.9%): [2.177, 3.997] (assumes normal distribution)


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
# Warmup Iteration   1: 5.639 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.020 ms/op
Iteration   1: 3.909 ±(99.9%) 0.049 ms/op
Iteration   2: 3.915 ±(99.9%) 0.012 ms/op
Iteration   3: 3.983 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.936 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (3.909, 3.936, 3.983), stdev = 0.042
  CI (99.9%): [3.177, 4.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.568 ms/op
                 createUser·p0.9999: 11.379 ms/op
                 createUser·p1.00:   11.600 ms/op

Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.298 ms/op
                 createUser·p0.9999: 17.222 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 3.095 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.701 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  12.430 ms/op
                 createUser·p0.9999: 21.944 ms/op
                 createUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312302
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23127 
    [ 2.500,  5.000) = 287702 
    [ 5.000,  7.500) = 1016 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     20.604 ms/op
     p(99.9990) =     22.372 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
Iteration   1: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  7.864 ms/op
                 existUser·p0.9999: 20.575 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   2: 2.926 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  5.546 ms/op
                 existUser·p0.9999: 18.158 ms/op
                 existUser·p1.00:   18.874 ms/op

Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  5.719 ms/op
                 existUser·p0.9999: 17.800 ms/op
                 existUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328719
  mean =      2.919 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28907 
    [ 2.500,  5.000) = 298957 
    [ 5.000,  7.500) = 635 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.201 ms/op
     p(99.9900) =     19.403 ms/op
     p(99.9990) =     20.854 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 4.304 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.006 ms/op
Iteration   1: 3.050 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.938 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.575 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.463 ms/op
                 getUser·p0.9999: 13.659 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   3: 3.066 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.277 ms/op
                 getUser·p0.9999: 14.111 ms/op
                 getUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312631
  mean =      3.069 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1326 
    [ 1.250,  2.500) = 19906 
    [ 2.500,  3.750) = 272860 
    [ 3.750,  5.000) = 16851 
    [ 5.000,  6.250) = 926 
    [ 6.250,  7.500) = 338 
    [ 7.500,  8.750) = 186 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.203 ms/op
     p(99.9900) =     13.844 ms/op
     p(99.9990) =     15.055 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


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
# Warmup Iteration   1: 4.932 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.271 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  12.053 ms/op
                 listUser·p0.9999: 18.808 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 3.997 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.470 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.139 ms/op
                 listUser·p0.9999: 17.891 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 4.119 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.572 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  16.220 ms/op
                 listUser·p0.9999: 22.362 ms/op
                 listUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238164
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3379 
    [ 2.500,  5.000) = 208130 
    [ 5.000,  7.500) = 25200 
    [ 7.500, 10.000) = 991 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.048 ms/op
     p(99.9000) =     14.972 ms/op
     p(99.9900) =     21.955 ms/op
     p(99.9990) =     22.928 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.628 ± 0.332  ops/ms
ClientGrpc.existUser                       thrpt       3  10.983 ± 1.944  ops/ms
ClientGrpc.getUser                         thrpt       3  10.472 ± 2.355  ops/ms
ClientGrpc.listUser                        thrpt       3   8.142 ± 0.554  ops/ms
ClientGrpc.createUser                       avgt       3   3.043 ± 0.365   ms/op
ClientGrpc.existUser                        avgt       3   2.872 ± 0.692   ms/op
ClientGrpc.getUser                          avgt       3   3.087 ± 0.910   ms/op
ClientGrpc.listUser                         avgt       3   3.936 ± 0.759   ms/op
ClientGrpc.createUser                     sample  312302   3.072 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.701           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.028           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.604           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.479           ms/op
ClientGrpc.existUser                      sample  328719   2.919 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.607           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.201           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.403           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.972           ms/op
ClientGrpc.getUser                        sample  312631   3.069 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.575           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.203           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.844           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.400           ms/op
ClientGrpc.listUser                       sample  238164   4.032 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.572           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.048           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.972           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.955           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.036           ms/op
