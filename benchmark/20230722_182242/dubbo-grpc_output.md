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
# Warmup Iteration   1: 4.310 ops/ms
# Warmup Iteration   2: 9.237 ops/ms
# Warmup Iteration   3: 10.063 ops/ms
Iteration   1: 10.091 ops/ms
Iteration   2: 10.409 ops/ms
Iteration   3: 10.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.321 ±(99.9%) 3.677 ops/ms [Average]
  (min, avg, max) = (10.091, 10.321, 10.464), stdev = 0.202
  CI (99.9%): [6.644, 13.998] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.571 ops/ms
# Warmup Iteration   2: 10.428 ops/ms
# Warmup Iteration   3: 10.969 ops/ms
Iteration   1: 10.924 ops/ms
Iteration   2: 11.060 ops/ms
Iteration   3: 10.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.966 ±(99.9%) 1.490 ops/ms [Average]
  (min, avg, max) = (10.913, 10.966, 11.060), stdev = 0.082
  CI (99.9%): [9.475, 12.456] (assumes normal distribution)


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
# Warmup Iteration   1: 7.082 ops/ms
# Warmup Iteration   2: 10.268 ops/ms
# Warmup Iteration   3: 10.552 ops/ms
Iteration   1: 10.691 ops/ms
Iteration   2: 10.947 ops/ms
Iteration   3: 10.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.671 ±(99.9%) 5.229 ops/ms [Average]
  (min, avg, max) = (10.375, 10.671, 10.947), stdev = 0.287
  CI (99.9%): [5.442, 15.900] (assumes normal distribution)


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
# Warmup Iteration   1: 6.204 ops/ms
# Warmup Iteration   2: 7.812 ops/ms
# Warmup Iteration   3: 8.181 ops/ms
Iteration   1: 8.034 ops/ms
Iteration   2: 8.176 ops/ms
Iteration   3: 8.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.095 ±(99.9%) 1.337 ops/ms [Average]
  (min, avg, max) = (8.034, 8.095, 8.176), stdev = 0.073
  CI (99.9%): [6.758, 9.432] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.045 ±(99.9%) 0.001 ms/op
Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
Iteration   3: 3.054 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.030 ±(99.9%) 0.608 ms/op [Average]
  (min, avg, max) = (2.992, 3.030, 3.054), stdev = 0.033
  CI (99.9%): [2.422, 3.638] (assumes normal distribution)


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.002 ms/op
Iteration   1: 2.873 ±(99.9%) 0.002 ms/op
Iteration   2: 2.904 ±(99.9%) 0.003 ms/op
Iteration   3: 2.891 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.890 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (2.873, 2.890, 2.904), stdev = 0.016
  CI (99.9%): [2.606, 3.173] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.237 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.004 ms/op
Iteration   1: 3.002 ±(99.9%) 0.003 ms/op
Iteration   2: 2.978 ±(99.9%) 0.004 ms/op
Iteration   3: 2.990 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.990 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.978, 2.990, 3.002), stdev = 0.012
  CI (99.9%): [2.778, 3.201] (assumes normal distribution)


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
# Warmup Iteration   1: 5.523 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.004 ms/op
Iteration   1: 3.953 ±(99.9%) 0.013 ms/op
Iteration   2: 4.008 ±(99.9%) 0.006 ms/op
Iteration   3: 3.902 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.954 ±(99.9%) 0.970 ms/op [Average]
  (min, avg, max) = (3.902, 3.954, 4.008), stdev = 0.053
  CI (99.9%): [2.985, 4.924] (assumes normal distribution)


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
# Warmup Iteration   1: 4.186 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  6.865 ms/op
                 createUser·p0.9999: 13.315 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.451 ms/op
                 createUser·p0.999:  8.524 ms/op
                 createUser·p0.9999: 14.571 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  9.565 ms/op
                 createUser·p0.9999: 16.343 ms/op
                 createUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317430
  mean =      3.024 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 590 
    [ 1.250,  2.500) = 24619 
    [ 2.500,  3.750) = 273543 
    [ 3.750,  5.000) = 16896 
    [ 5.000,  6.250) = 1006 
    [ 6.250,  7.500) = 339 
    [ 7.500,  8.750) = 140 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     15.946 ms/op
     p(99.9990) =     16.624 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.917 ±(99.9%) 0.005 ms/op
Iteration   1: 2.875 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.550 ms/op
                 existUser·p0.9999: 12.630 ms/op
                 existUser·p1.00:   13.058 ms/op

Iteration   2: 2.863 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  5.379 ms/op
                 existUser·p0.9999: 13.421 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.117 ms/op
                 existUser·p0.999:  7.269 ms/op
                 existUser·p0.9999: 18.029 ms/op
                 existUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331172
  mean =      2.896 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1011 
    [ 1.250,  2.500) = 39786 
    [ 2.500,  3.750) = 283104 
    [ 3.750,  5.000) = 6435 
    [ 5.000,  6.250) = 439 
    [ 6.250,  7.500) = 190 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      6.487 ms/op
     p(99.9900) =     15.998 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.930 ms/op
                 getUser·p0.9999: 12.454 ms/op
                 getUser·p1.00:   12.698 ms/op

Iteration   2: 3.034 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  10.364 ms/op
                 getUser·p0.9999: 22.017 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.440 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.750 ms/op
                 getUser·p0.9999: 18.548 ms/op
                 getUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320769
  mean =      2.993 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25082 
    [ 2.500,  5.000) = 294435 
    [ 5.000,  7.500) = 851 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     20.923 ms/op
     p(99.9990) =     23.783 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 5.019 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.010 ms/op
Iteration   1: 3.909 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 16.126 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 3.986 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 25.689 ms/op
                 listUser·p1.00:   26.280 ms/op

Iteration   3: 3.933 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.784 ms/op
                 listUser·p0.9999: 18.379 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243367
  mean =      3.942 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2612 
    [ 2.500,  5.000) = 218808 
    [ 5.000,  7.500) = 20652 
    [ 7.500, 10.000) = 790 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     25.155 ms/op
     p(99.9990) =     26.172 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.321 ± 3.677  ops/ms
ClientGrpc.existUser                       thrpt       3  10.966 ± 1.490  ops/ms
ClientGrpc.getUser                         thrpt       3  10.671 ± 5.229  ops/ms
ClientGrpc.listUser                        thrpt       3   8.095 ± 1.337  ops/ms
ClientGrpc.createUser                       avgt       3   3.030 ± 0.608   ms/op
ClientGrpc.existUser                        avgt       3   2.890 ± 0.284   ms/op
ClientGrpc.getUser                          avgt       3   2.990 ± 0.211   ms/op
ClientGrpc.listUser                         avgt       3   3.954 ± 0.970   ms/op
ClientGrpc.createUser                     sample  317430   3.024 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.802           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.536           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.946           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.744           ms/op
ClientGrpc.existUser                      sample  331172   2.896 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.665           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.487           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.998           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.514           ms/op
ClientGrpc.getUser                        sample  320769   2.993 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.440           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.290           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.923           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.888           ms/op
ClientGrpc.listUser                       sample  243367   3.942 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.100           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.647           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.155           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.280           ms/op
