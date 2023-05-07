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
# Warmup Iteration   1: 4.455 ops/ms
# Warmup Iteration   2: 9.223 ops/ms
# Warmup Iteration   3: 10.386 ops/ms
Iteration   1: 10.610 ops/ms
Iteration   2: 10.703 ops/ms
Iteration   3: 10.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.587 ±(99.9%) 2.378 ops/ms [Average]
  (min, avg, max) = (10.446, 10.587, 10.703), stdev = 0.130
  CI (99.9%): [8.209, 12.964] (assumes normal distribution)


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
# Warmup Iteration   1: 7.403 ops/ms
# Warmup Iteration   2: 10.714 ops/ms
# Warmup Iteration   3: 11.084 ops/ms
Iteration   1: 11.024 ops/ms
Iteration   2: 11.191 ops/ms
Iteration   3: 11.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.155 ±(99.9%) 2.140 ops/ms [Average]
  (min, avg, max) = (11.024, 11.155, 11.250), stdev = 0.117
  CI (99.9%): [9.015, 13.294] (assumes normal distribution)


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
# Warmup Iteration   1: 7.516 ops/ms
# Warmup Iteration   2: 10.378 ops/ms
# Warmup Iteration   3: 10.662 ops/ms
Iteration   1: 10.847 ops/ms
Iteration   2: 10.601 ops/ms
Iteration   3: 10.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.717 ±(99.9%) 2.258 ops/ms [Average]
  (min, avg, max) = (10.601, 10.717, 10.847), stdev = 0.124
  CI (99.9%): [8.459, 12.975] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.745 ops/ms
# Warmup Iteration   2: 7.920 ops/ms
# Warmup Iteration   3: 8.135 ops/ms
Iteration   1: 8.177 ops/ms
Iteration   2: 8.201 ops/ms
Iteration   3: 8.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.182 ±(99.9%) 0.305 ops/ms [Average]
  (min, avg, max) = (8.169, 8.182, 8.201), stdev = 0.017
  CI (99.9%): [7.877, 8.487] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.865 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
Iteration   1: 3.006 ±(99.9%) 0.003 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 2.978 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.990 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.978, 2.990, 3.006), stdev = 0.015
  CI (99.9%): [2.720, 3.259] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.765 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.955 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.870 ±(99.9%) 0.004 ms/op
Iteration   1: 2.874 ±(99.9%) 0.004 ms/op
Iteration   2: 2.882 ±(99.9%) 0.003 ms/op
Iteration   3: 2.960 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.905 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (2.874, 2.905, 2.960), stdev = 0.047
  CI (99.9%): [2.042, 3.769] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.948 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.003 ms/op
Iteration   1: 3.012 ±(99.9%) 0.002 ms/op
Iteration   2: 2.975 ±(99.9%) 0.004 ms/op
Iteration   3: 2.989 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.992 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (2.975, 2.992, 3.012), stdev = 0.019
  CI (99.9%): [2.648, 3.336] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.584 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.015 ms/op
Iteration   1: 3.803 ±(99.9%) 0.019 ms/op
Iteration   2: 3.884 ±(99.9%) 0.024 ms/op
Iteration   3: 3.859 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.849 ±(99.9%) 0.758 ms/op [Average]
  (min, avg, max) = (3.803, 3.849, 3.884), stdev = 0.042
  CI (99.9%): [3.091, 4.606] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.700 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.007 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  6.671 ms/op
                 createUser·p0.9999: 13.156 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   2: 2.981 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  10.112 ms/op
                 createUser·p0.9999: 26.649 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.470 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  10.841 ms/op
                 createUser·p0.9999: 16.212 ms/op
                 createUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317755
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25641 
    [ 2.500,  5.000) = 290378 
    [ 5.000,  7.500) = 1294 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     26.320 ms/op
     p(99.9990) =     26.798 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.850 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.882 ±(99.9%) 0.006 ms/op
Iteration   1: 2.872 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  5.748 ms/op
                 existUser·p0.9999: 19.460 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   2: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.253 ms/op
                 existUser·p0.9999: 15.500 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   3: 2.874 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  7.873 ms/op
                 existUser·p0.9999: 15.415 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331944
  mean =      2.891 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3205 
    [ 1.250,  2.500) = 39037 
    [ 2.500,  3.750) = 279714 
    [ 3.750,  5.000) = 8956 
    [ 5.000,  6.250) = 533 
    [ 6.250,  7.500) = 165 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.505 ms/op
     p(99.9900) =     17.151 ms/op
     p(99.9990) =     19.771 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  10.209 ms/op
                 getUser·p0.9999: 14.246 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.791 ms/op
                 getUser·p0.9999: 12.691 ms/op
                 getUser·p1.00:   12.943 ms/op

Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.115 ms/op
                 getUser·p0.9999: 25.559 ms/op
                 getUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319960
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29577 
    [ 2.500,  5.000) = 288989 
    [ 5.000,  7.500) = 996 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.996 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     25.743 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 4.615 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.010 ms/op
Iteration   1: 3.965 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.271 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   2: 3.939 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  15.414 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   3: 3.940 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.568 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 20.705 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243024
  mean =      3.948 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4275 
    [ 2.500,  5.000) = 216522 
    [ 5.000,  7.500) = 20509 
    [ 7.500, 10.000) = 1047 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     23.971 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.587 ± 2.378  ops/ms
ClientGrpc.existUser                       thrpt       3  11.155 ± 2.140  ops/ms
ClientGrpc.getUser                         thrpt       3  10.717 ± 2.258  ops/ms
ClientGrpc.listUser                        thrpt       3   8.182 ± 0.305  ops/ms
ClientGrpc.createUser                       avgt       3   2.990 ± 0.270   ms/op
ClientGrpc.existUser                        avgt       3   2.905 ± 0.863   ms/op
ClientGrpc.getUser                          avgt       3   2.992 ± 0.344   ms/op
ClientGrpc.listUser                         avgt       3   3.849 ± 0.758   ms/op
ClientGrpc.createUser                     sample  317755   3.020 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.470           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.634           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.320           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.870           ms/op
ClientGrpc.existUser                      sample  331944   2.891 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.569           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.505           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.151           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.890           ms/op
ClientGrpc.getUser                        sample  319960   2.998 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.723           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.996           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.904           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.821           ms/op
ClientGrpc.listUser                       sample  243024   3.948 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.568           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.204           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.872           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.543           ms/op
