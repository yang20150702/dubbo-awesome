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
# Warmup Iteration   1: 4.259 ops/ms
# Warmup Iteration   2: 8.987 ops/ms
# Warmup Iteration   3: 9.938 ops/ms
Iteration   1: 10.214 ops/ms
Iteration   2: 10.299 ops/ms
Iteration   3: 10.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.360 ±(99.9%) 3.380 ops/ms [Average]
  (min, avg, max) = (10.214, 10.360, 10.569), stdev = 0.185
  CI (99.9%): [6.981, 13.740] (assumes normal distribution)


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
# Warmup Iteration   1: 7.559 ops/ms
# Warmup Iteration   2: 10.350 ops/ms
# Warmup Iteration   3: 10.700 ops/ms
Iteration   1: 10.684 ops/ms
Iteration   2: 10.619 ops/ms
Iteration   3: 11.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.774 ±(99.9%) 3.929 ops/ms [Average]
  (min, avg, max) = (10.619, 10.774, 11.020), stdev = 0.215
  CI (99.9%): [6.845, 14.703] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.362 ops/ms
# Warmup Iteration   2: 10.091 ops/ms
# Warmup Iteration   3: 10.235 ops/ms
Iteration   1: 10.287 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 10.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.359 ±(99.9%) 1.340 ops/ms [Average]
  (min, avg, max) = (10.287, 10.359, 10.434), stdev = 0.073
  CI (99.9%): [9.020, 11.699] (assumes normal distribution)


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
# Warmup Iteration   1: 5.302 ops/ms
# Warmup Iteration   2: 7.728 ops/ms
# Warmup Iteration   3: 7.974 ops/ms
Iteration   1: 7.990 ops/ms
Iteration   2: 7.897 ops/ms
Iteration   3: 8.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.004 ±(99.9%) 2.088 ops/ms [Average]
  (min, avg, max) = (7.897, 8.004, 8.125), stdev = 0.114
  CI (99.9%): [5.916, 10.092] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.422 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.005 ms/op
Iteration   1: 3.086 ±(99.9%) 0.008 ms/op
Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
Iteration   3: 3.069 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.067 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (3.046, 3.067, 3.086), stdev = 0.020
  CI (99.9%): [2.693, 3.441] (assumes normal distribution)


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.005 ms/op
Iteration   1: 2.909 ±(99.9%) 0.004 ms/op
Iteration   2: 2.882 ±(99.9%) 0.004 ms/op
Iteration   3: 2.913 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.901 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (2.882, 2.901, 2.913), stdev = 0.017
  CI (99.9%): [2.592, 3.211] (assumes normal distribution)


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.002 ms/op
Iteration   1: 3.078 ±(99.9%) 0.002 ms/op
Iteration   2: 3.007 ±(99.9%) 0.003 ms/op
Iteration   3: 3.047 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.044 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.007, 3.044, 3.078), stdev = 0.036
  CI (99.9%): [2.396, 3.693] (assumes normal distribution)


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
# Warmup Iteration   1: 4.914 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.023 ms/op
Iteration   1: 3.982 ±(99.9%) 0.015 ms/op
Iteration   2: 4.042 ±(99.9%) 0.015 ms/op
Iteration   3: 4.042 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.022 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (3.982, 4.022, 4.042), stdev = 0.035
  CI (99.9%): [3.389, 4.655] (assumes normal distribution)


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
# Warmup Iteration   1: 4.567 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  6.978 ms/op
                 createUser·p0.9999: 12.861 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.700 ms/op
                 createUser·p0.9999: 22.020 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.825 ms/op
                 createUser·p0.999:  8.348 ms/op
                 createUser·p0.9999: 24.037 ms/op
                 createUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313621
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19786 
    [ 2.500,  5.000) = 292052 
    [ 5.000,  7.500) = 1380 
    [ 7.500, 10.000) = 179 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      7.897 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     28.106 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.005 ms/op
Iteration   1: 2.933 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.005 ms/op
                 existUser·p0.9999: 14.942 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   2: 2.903 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.234 ms/op
                 existUser·p0.9999: 15.138 ms/op
                 existUser·p1.00:   15.548 ms/op

Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   3.961 ms/op
                 existUser·p0.999:  11.682 ms/op
                 existUser·p0.9999: 24.092 ms/op
                 existUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326904
  mean =      2.936 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31484 
    [ 2.500,  5.000) = 294459 
    [ 5.000,  7.500) = 652 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.269 ms/op
     p(99.9900) =     19.546 ms/op
     p(99.9990) =     24.919 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.006 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.808 ms/op
                 getUser·p0.9999: 12.936 ms/op
                 getUser·p1.00:   13.189 ms/op

Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.472 ms/op
                 getUser·p0.999:  7.038 ms/op
                 getUser·p0.9999: 20.219 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   3: 3.052 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  6.275 ms/op
                 getUser·p0.9999: 17.449 ms/op
                 getUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314266
  mean =      3.055 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15469 
    [ 2.500,  5.000) = 297581 
    [ 5.000,  7.500) = 993 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.410 ms/op
     p(99.9000) =      6.832 ms/op
     p(99.9900) =     18.322 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 5.650 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.011 ms/op
Iteration   1: 4.062 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  16.079 ms/op
                 listUser·p0.9999: 21.696 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 4.106 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.056 ms/op
                 listUser·p0.9999: 24.675 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   3: 4.118 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  16.324 ms/op
                 listUser·p0.9999: 25.723 ms/op
                 listUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234521
  mean =      4.095 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1935 
    [ 2.500,  5.000) = 209088 
    [ 5.000,  7.500) = 21862 
    [ 7.500, 10.000) = 1099 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     16.212 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     25.854 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.360 ± 3.380  ops/ms
ClientGrpc.existUser                       thrpt       3  10.774 ± 3.929  ops/ms
ClientGrpc.getUser                         thrpt       3  10.359 ± 1.340  ops/ms
ClientGrpc.listUser                        thrpt       3   8.004 ± 2.088  ops/ms
ClientGrpc.createUser                       avgt       3   3.067 ± 0.374   ms/op
ClientGrpc.existUser                        avgt       3   2.901 ± 0.310   ms/op
ClientGrpc.getUser                          avgt       3   3.044 ± 0.649   ms/op
ClientGrpc.listUser                         avgt       3   4.022 ± 0.633   ms/op
ClientGrpc.createUser                     sample  313621   3.063 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.603           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.897           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.331           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.180           ms/op
ClientGrpc.existUser                      sample  326904   2.936 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.730           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.269           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.546           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.559           ms/op
ClientGrpc.getUser                        sample  314266   3.055 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.717           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.410           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.832           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.322           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.546           ms/op
ClientGrpc.listUser                       sample  234521   4.095 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.947           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.936           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.212           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.461           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.952           ms/op
