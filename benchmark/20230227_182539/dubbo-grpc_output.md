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
# Warmup Iteration   1: 3.641 ops/ms
# Warmup Iteration   2: 7.859 ops/ms
# Warmup Iteration   3: 8.715 ops/ms
Iteration   1: 8.689 ops/ms
Iteration   2: 8.732 ops/ms
Iteration   3: 8.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.723 ±(99.9%) 0.561 ops/ms [Average]
  (min, avg, max) = (8.689, 8.723, 8.749), stdev = 0.031
  CI (99.9%): [8.162, 9.284] (assumes normal distribution)


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
# Warmup Iteration   1: 6.724 ops/ms
# Warmup Iteration   2: 9.070 ops/ms
# Warmup Iteration   3: 9.350 ops/ms
Iteration   1: 9.298 ops/ms
Iteration   2: 9.316 ops/ms
Iteration   3: 9.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.377 ±(99.9%) 2.209 ops/ms [Average]
  (min, avg, max) = (9.298, 9.377, 9.516), stdev = 0.121
  CI (99.9%): [7.168, 11.585] (assumes normal distribution)


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
# Warmup Iteration   1: 6.083 ops/ms
# Warmup Iteration   2: 8.882 ops/ms
# Warmup Iteration   3: 8.993 ops/ms
Iteration   1: 9.296 ops/ms
Iteration   2: 9.322 ops/ms
Iteration   3: 9.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.305 ±(99.9%) 0.261 ops/ms [Average]
  (min, avg, max) = (9.296, 9.305, 9.322), stdev = 0.014
  CI (99.9%): [9.044, 9.566] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.561 ops/ms
# Warmup Iteration   2: 6.801 ops/ms
# Warmup Iteration   3: 6.908 ops/ms
Iteration   1: 7.179 ops/ms
Iteration   2: 6.846 ops/ms
Iteration   3: 6.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.976 ±(99.9%) 3.260 ops/ms [Average]
  (min, avg, max) = (6.846, 6.976, 7.179), stdev = 0.179
  CI (99.9%): [3.716, 10.235] (assumes normal distribution)


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
# Warmup Iteration   1: 5.107 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.671 ±(99.9%) 0.003 ms/op
Iteration   1: 3.701 ±(99.9%) 0.005 ms/op
Iteration   2: 3.705 ±(99.9%) 0.002 ms/op
Iteration   3: 3.935 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.781 ±(99.9%) 2.447 ms/op [Average]
  (min, avg, max) = (3.701, 3.781, 3.935), stdev = 0.134
  CI (99.9%): [1.333, 6.228] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 5.115 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.016 ms/op
Iteration   1: 3.712 ±(99.9%) 0.003 ms/op
Iteration   2: 3.663 ±(99.9%) 0.002 ms/op
Iteration   3: 3.592 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.656 ±(99.9%) 1.095 ms/op [Average]
  (min, avg, max) = (3.592, 3.656, 3.712), stdev = 0.060
  CI (99.9%): [2.561, 4.751] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.166 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.004 ms/op
Iteration   1: 4.052 ±(99.9%) 0.002 ms/op
Iteration   2: 4.023 ±(99.9%) 0.002 ms/op
Iteration   3: 3.988 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.021 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (3.988, 4.021, 4.052), stdev = 0.032
  CI (99.9%): [3.437, 4.604] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.275 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.357 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.870 ±(99.9%) 0.011 ms/op
Iteration   1: 4.825 ±(99.9%) 0.021 ms/op
Iteration   2: 4.919 ±(99.9%) 0.009 ms/op
Iteration   3: 4.891 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.878 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (4.825, 4.878, 4.919), stdev = 0.049
  CI (99.9%): [3.991, 5.765] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.298 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.011 ms/op
Iteration   1: 3.843 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  9.811 ms/op
                 createUser·p0.9999: 19.005 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   2: 3.787 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  10.193 ms/op
                 createUser·p0.9999: 21.350 ms/op
                 createUser·p1.00:   21.430 ms/op

Iteration   3: 3.879 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  11.050 ms/op
                 createUser·p0.9999: 25.943 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250449
  mean =      3.836 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7226 
    [ 2.500,  5.000) = 228781 
    [ 5.000,  7.500) = 13548 
    [ 7.500, 10.000) = 625 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     10.340 ms/op
     p(99.9900) =     25.587 ms/op
     p(99.9990) =     26.214 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.167 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.008 ms/op
Iteration   1: 3.680 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  9.191 ms/op
                 existUser·p0.9999: 19.386 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   2: 3.633 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  13.517 ms/op
                 existUser·p0.9999: 19.608 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   3: 3.779 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   7.168 ms/op
                 existUser·p0.999:  14.717 ms/op
                 existUser·p0.9999: 19.565 ms/op
                 existUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 259600
  mean =      3.696 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11629 
    [ 2.500,  5.000) = 237123 
    [ 5.000,  7.500) = 9196 
    [ 7.500, 10.000) = 1045 
    [10.000, 12.500) = 355 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     12.370 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     20.395 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.348 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.011 ms/op
Iteration   1: 4.102 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   5.112 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   7.655 ms/op
                 getUser·p0.999:  12.338 ms/op
                 getUser·p0.9999: 15.821 ms/op
                 getUser·p1.00:   16.302 ms/op

Iteration   2: 4.036 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.565 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  11.380 ms/op
                 getUser·p0.9999: 21.471 ms/op
                 getUser·p1.00:   22.282 ms/op

Iteration   3: 3.970 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.956 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  8.118 ms/op
                 getUser·p0.9999: 22.018 ms/op
                 getUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 237750
  mean =      4.036 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6700 
    [ 2.500,  5.000) = 206892 
    [ 5.000,  7.500) = 22562 
    [ 7.500, 10.000) = 1221 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     11.469 ms/op
     p(99.9900) =     21.372 ms/op
     p(99.9990) =     22.389 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.651 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.272 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.042 ±(99.9%) 0.017 ms/op
Iteration   1: 4.970 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.496 ms/op
                 listUser·p0.95:   7.217 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  18.021 ms/op
                 listUser·p0.9999: 23.405 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 4.901 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.275 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  24.925 ms/op
                 listUser·p0.9999: 26.819 ms/op
                 listUser·p1.00:   28.541 ms/op

Iteration   3: 4.927 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  19.857 ms/op
                 listUser·p0.9999: 31.439 ms/op
                 listUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194706
  mean =      4.933 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 509 
    [ 2.500,  5.000) = 127918 
    [ 5.000,  7.500) = 59756 
    [ 7.500, 10.000) = 5414 
    [10.000, 12.500) = 671 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.086 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     19.825 ms/op
     p(99.9900) =     29.428 ms/op
     p(99.9990) =     35.069 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.723 ± 0.561  ops/ms
ClientGrpc.existUser                       thrpt       3   9.377 ± 2.209  ops/ms
ClientGrpc.getUser                         thrpt       3   9.305 ± 0.261  ops/ms
ClientGrpc.listUser                        thrpt       3   6.976 ± 3.260  ops/ms
ClientGrpc.createUser                       avgt       3   3.781 ± 2.447   ms/op
ClientGrpc.existUser                        avgt       3   3.656 ± 1.095   ms/op
ClientGrpc.getUser                          avgt       3   4.021 ± 0.584   ms/op
ClientGrpc.listUser                         avgt       3   4.878 ± 0.887   ms/op
ClientGrpc.createUser                     sample  250449   3.836 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.840           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.768           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.070           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.340           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.587           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.345           ms/op
ClientGrpc.existUser                      sample  259600   3.696 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.802           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.899           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.603           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.370           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.497           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.378           ms/op
ClientGrpc.getUser                        sample  237750   4.036 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.565           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.014           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.366           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.914           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.469           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.372           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.479           ms/op
ClientGrpc.listUser                       sample  194706   4.933 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.805           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.678           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.382           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.929           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.825           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.428           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.193           ms/op
