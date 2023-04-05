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
# Warmup Iteration   1: 4.165 ops/ms
# Warmup Iteration   2: 8.766 ops/ms
# Warmup Iteration   3: 9.681 ops/ms
Iteration   1: 10.358 ops/ms
Iteration   2: 10.356 ops/ms
Iteration   3: 10.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.472 ±(99.9%) 3.618 ops/ms [Average]
  (min, avg, max) = (10.356, 10.472, 10.700), stdev = 0.198
  CI (99.9%): [6.854, 14.089] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.107 ops/ms
# Warmup Iteration   2: 10.308 ops/ms
# Warmup Iteration   3: 10.869 ops/ms
Iteration   1: 10.678 ops/ms
Iteration   2: 10.882 ops/ms
Iteration   3: 10.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.818 ±(99.9%) 2.216 ops/ms [Average]
  (min, avg, max) = (10.678, 10.818, 10.894), stdev = 0.121
  CI (99.9%): [8.602, 13.034] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.177 ops/ms
# Warmup Iteration   2: 10.002 ops/ms
# Warmup Iteration   3: 10.118 ops/ms
Iteration   1: 10.470 ops/ms
Iteration   2: 10.256 ops/ms
Iteration   3: 10.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.325 ±(99.9%) 2.292 ops/ms [Average]
  (min, avg, max) = (10.250, 10.325, 10.470), stdev = 0.126
  CI (99.9%): [8.033, 12.617] (assumes normal distribution)


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
# Warmup Iteration   1: 6.133 ops/ms
# Warmup Iteration   2: 7.489 ops/ms
# Warmup Iteration   3: 7.918 ops/ms
Iteration   1: 8.060 ops/ms
Iteration   2: 8.004 ops/ms
Iteration   3: 7.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.002 ±(99.9%) 1.085 ops/ms [Average]
  (min, avg, max) = (7.941, 8.002, 8.060), stdev = 0.059
  CI (99.9%): [6.917, 9.087] (assumes normal distribution)


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.003 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
Iteration   2: 2.994 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (2.994, 3.013, 3.039), stdev = 0.023
  CI (99.9%): [2.587, 3.438] (assumes normal distribution)


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.003 ms/op
Iteration   1: 2.903 ±(99.9%) 0.003 ms/op
Iteration   2: 2.908 ±(99.9%) 0.002 ms/op
Iteration   3: 2.883 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.898 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (2.883, 2.898, 2.908), stdev = 0.013
  CI (99.9%): [2.656, 3.140] (assumes normal distribution)


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
# Warmup Iteration   1: 4.346 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 2.992 ±(99.9%) 0.003 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 3.020 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.002 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (2.992, 3.002, 3.020), stdev = 0.016
  CI (99.9%): [2.718, 3.286] (assumes normal distribution)


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
# Warmup Iteration   1: 5.672 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.010 ms/op
Iteration   1: 3.938 ±(99.9%) 0.008 ms/op
Iteration   2: 3.966 ±(99.9%) 0.013 ms/op
Iteration   3: 4.020 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.975 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (3.938, 3.975, 4.020), stdev = 0.042
  CI (99.9%): [3.212, 4.737] (assumes normal distribution)


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
# Warmup Iteration   1: 4.323 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
Iteration   1: 3.082 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.166 ms/op
                 createUser·p0.999:  7.098 ms/op
                 createUser·p0.9999: 12.691 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.447 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  6.858 ms/op
                 createUser·p0.9999: 16.040 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  9.650 ms/op
                 createUser·p0.9999: 17.793 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311344
  mean =      3.082 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 584 
    [ 1.250,  2.500) = 16531 
    [ 2.500,  3.750) = 276220 
    [ 3.750,  5.000) = 16613 
    [ 5.000,  6.250) = 653 
    [ 6.250,  7.500) = 343 
    [ 7.500,  8.750) = 83 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.934 ms/op
     p(99.9900) =     16.546 ms/op
     p(99.9990) =     17.953 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  7.008 ms/op
                 existUser·p0.9999: 13.397 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   2: 2.891 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.832 ms/op
                 existUser·p0.9999: 15.432 ms/op
                 existUser·p1.00:   16.024 ms/op

Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.670 ms/op
                 existUser·p0.9999: 23.248 ms/op
                 existUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322642
  mean =      2.974 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36323 
    [ 2.500,  5.000) = 284824 
    [ 5.000,  7.500) = 1238 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     21.213 ms/op
     p(99.9990) =     23.472 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 4.403 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.794 ms/op
                 getUser·p0.9999: 13.619 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   2: 3.045 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.111 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.932 ms/op
                 getUser·p0.9999: 24.301 ms/op
                 getUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312816
  mean =      3.068 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13445 
    [ 2.500,  5.000) = 298073 
    [ 5.000,  7.500) = 1003 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.381 ms/op
     p(99.9900) =     23.296 ms/op
     p(99.9990) =     24.764 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 5.369 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.013 ms/op
Iteration   1: 4.089 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  19.404 ms/op
                 listUser·p0.9999: 22.386 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 4.026 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   3: 4.060 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  17.342 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236574
  mean =      4.058 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3860 
    [ 2.500,  5.000) = 206548 
    [ 5.000,  7.500) = 24633 
    [ 7.500, 10.000) = 1070 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     17.774 ms/op
     p(99.9900) =     21.813 ms/op
     p(99.9990) =     22.681 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.472 ± 3.618  ops/ms
ClientGrpc.existUser                       thrpt       3  10.818 ± 2.216  ops/ms
ClientGrpc.getUser                         thrpt       3  10.325 ± 2.292  ops/ms
ClientGrpc.listUser                        thrpt       3   8.002 ± 1.085  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.425   ms/op
ClientGrpc.existUser                        avgt       3   2.898 ± 0.242   ms/op
ClientGrpc.getUser                          avgt       3   3.002 ± 0.284   ms/op
ClientGrpc.listUser                         avgt       3   3.975 ± 0.762   ms/op
ClientGrpc.createUser                     sample  311344   3.082 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.447           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.934           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.546           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.055           ms/op
ClientGrpc.existUser                      sample  322642   2.974 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.680           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.152           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.213           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.100           ms/op
ClientGrpc.getUser                        sample  312816   3.068 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.724           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.381           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.296           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.904           ms/op
ClientGrpc.listUser                       sample  236574   4.058 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.814           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.111           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.774           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.813           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.167           ms/op
