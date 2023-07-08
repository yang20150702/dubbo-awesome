# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ops/ms
# Warmup Iteration   2: 7.895 ops/ms
# Warmup Iteration   3: 8.439 ops/ms
Iteration   1: 9.117 ops/ms
Iteration   2: 9.652 ops/ms
Iteration   3: 9.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.457 ±(99.9%) 5.401 ops/ms [Average]
  (min, avg, max) = (9.117, 9.457, 9.652), stdev = 0.296
  CI (99.9%): [4.057, 14.858] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.970 ops/ms
# Warmup Iteration   2: 8.580 ops/ms
# Warmup Iteration   3: 9.283 ops/ms
Iteration   1: 9.758 ops/ms
Iteration   2: 9.548 ops/ms
Iteration   3: 9.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.575 ±(99.9%) 3.143 ops/ms [Average]
  (min, avg, max) = (9.417, 9.575, 9.758), stdev = 0.172
  CI (99.9%): [6.432, 12.718] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 5.782 ops/ms
# Warmup Iteration   2: 8.544 ops/ms
# Warmup Iteration   3: 9.246 ops/ms
Iteration   1: 8.736 ops/ms
Iteration   2: 8.941 ops/ms
Iteration   3: 8.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.876 ±(99.9%) 2.206 ops/ms [Average]
  (min, avg, max) = (8.736, 8.876, 8.950), stdev = 0.121
  CI (99.9%): [6.670, 11.081] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.126 ops/ms
# Warmup Iteration   2: 7.596 ops/ms
# Warmup Iteration   3: 7.739 ops/ms
Iteration   1: 7.171 ops/ms
Iteration   2: 6.973 ops/ms
Iteration   3: 7.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.089 ±(99.9%) 1.885 ops/ms [Average]
  (min, avg, max) = (6.973, 7.089, 7.171), stdev = 0.103
  CI (99.9%): [5.204, 8.974] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.159 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.008 ms/op
Iteration   1: 3.538 ±(99.9%) 0.003 ms/op
Iteration   2: 3.615 ±(99.9%) 0.003 ms/op
Iteration   3: 3.930 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.694 ±(99.9%) 3.795 ms/op [Average]
  (min, avg, max) = (3.538, 3.694, 3.930), stdev = 0.208
  CI (99.9%): [≈ 0, 7.489] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.914 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.003 ms/op
Iteration   1: 3.419 ±(99.9%) 0.002 ms/op
Iteration   2: 3.348 ±(99.9%) 0.005 ms/op
Iteration   3: 3.427 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.398 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (3.348, 3.398, 3.427), stdev = 0.043
  CI (99.9%): [2.605, 4.191] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.021 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.003 ms/op
Iteration   1: 3.578 ±(99.9%) 0.004 ms/op
Iteration   2: 3.731 ±(99.9%) 0.005 ms/op
Iteration   3: 3.664 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.658 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (3.578, 3.658, 3.731), stdev = 0.077
  CI (99.9%): [2.255, 5.061] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.921 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 5.091 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.781 ±(99.9%) 0.012 ms/op
Iteration   1: 13.782 ±(99.9%) 0.073 ms/op
Iteration   2: 6.435 ±(99.9%) 0.031 ms/op
Iteration   3: 4.839 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.352 ±(99.9%) 87.021 ms/op [Average]
  (min, avg, max) = (4.839, 8.352, 13.782), stdev = 4.770
  CI (99.9%): [≈ 0, 95.373] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.230 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.724 ±(99.9%) 0.011 ms/op
Iteration   1: 3.577 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  11.911 ms/op
                 createUser·p0.9999: 15.076 ms/op
                 createUser·p1.00:   15.450 ms/op

Iteration   2: 3.627 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  15.393 ms/op
                 createUser·p0.9999: 18.761 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   3: 3.654 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   6.180 ms/op
                 createUser·p0.999:  15.186 ms/op
                 createUser·p0.9999: 22.020 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265218
  mean =      3.619 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17895 
    [ 2.500,  5.000) = 236652 
    [ 5.000,  7.500) = 9352 
    [ 7.500, 10.000) = 950 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     12.667 ms/op
     p(99.9900) =     21.625 ms/op
     p(99.9990) =     22.654 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.685 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.007 ms/op
Iteration   1: 3.502 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  9.055 ms/op
                 existUser·p0.9999: 18.903 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   2: 3.319 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  7.578 ms/op
                 existUser·p0.9999: 21.093 ms/op
                 existUser·p1.00:   21.660 ms/op

Iteration   3: 3.407 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  8.161 ms/op
                 existUser·p0.9999: 34.708 ms/op
                 existUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 281776
  mean =      3.407 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14891 
    [ 2.500,  5.000) = 262200 
    [ 5.000,  7.500) = 4188 
    [ 7.500, 10.000) = 304 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     32.434 ms/op
     p(99.9990) =     34.812 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.871 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.008 ms/op
Iteration   1: 3.643 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  11.277 ms/op
                 getUser·p0.9999: 15.850 ms/op
                 getUser·p1.00:   15.974 ms/op

Iteration   2: 3.633 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  7.905 ms/op
                 getUser·p0.9999: 17.085 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   3: 3.598 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  9.227 ms/op
                 getUser·p0.9999: 23.040 ms/op
                 getUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 264810
  mean =      3.625 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8264 
    [ 2.500,  5.000) = 248935 
    [ 5.000,  7.500) = 7044 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =      8.916 ms/op
     p(99.9900) =     20.122 ms/op
     p(99.9990) =     23.857 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.482 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.173 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.850 ±(99.9%) 0.016 ms/op
Iteration   1: 4.801 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.729 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   7.053 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  14.801 ms/op
                 listUser·p0.9999: 22.293 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 4.895 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.390 ms/op
                 listUser·p0.95:   7.201 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  16.259 ms/op
                 listUser·p0.9999: 26.815 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   3: 4.673 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.947 ms/op
                 listUser·p0.95:   6.701 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  19.684 ms/op
                 listUser·p0.9999: 25.236 ms/op
                 listUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200385
  mean =      4.788 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 428 
    [ 2.500,  5.000) = 145175 
    [ 5.000,  7.500) = 48546 
    [ 7.500, 10.000) = 5464 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      6.996 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     16.981 ms/op
     p(99.9900) =     25.165 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score    Error   Units
ClientGrpc.createUser                      thrpt       3   9.457 ±  5.401  ops/ms
ClientGrpc.existUser                       thrpt       3   9.575 ±  3.143  ops/ms
ClientGrpc.getUser                         thrpt       3   8.876 ±  2.206  ops/ms
ClientGrpc.listUser                        thrpt       3   7.089 ±  1.885  ops/ms
ClientGrpc.createUser                       avgt       3   3.694 ±  3.795   ms/op
ClientGrpc.existUser                        avgt       3   3.398 ±  0.793   ms/op
ClientGrpc.getUser                          avgt       3   3.658 ±  1.403   ms/op
ClientGrpc.listUser                         avgt       3   8.352 ± 87.021   ms/op
ClientGrpc.createUser                     sample  265218   3.619 ±  0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.756            ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.584            ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.383            ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.841            ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.349            ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.667            ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.625            ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.708            ms/op
ClientGrpc.existUser                      sample  281776   3.407 ±  0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.654            ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.367            ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.063            ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.383            ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.407            ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.552            ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.434            ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.865            ms/op
ClientGrpc.getUser                        sample  264810   3.625 ±  0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.881            ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.572            ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.301            ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.653            ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.808            ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.916            ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.122            ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.166            ms/op
ClientGrpc.listUser                       sample  200385   4.788 ±  0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.260            ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.547            ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.144            ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.996            ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.749            ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.981            ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.165            ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.165            ms/op
