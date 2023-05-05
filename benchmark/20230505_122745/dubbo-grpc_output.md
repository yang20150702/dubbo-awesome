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
# Warmup Iteration   1: 4.153 ops/ms
# Warmup Iteration   2: 8.827 ops/ms
# Warmup Iteration   3: 10.155 ops/ms
Iteration   1: 10.644 ops/ms
Iteration   2: 10.454 ops/ms
Iteration   3: 10.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.550 ±(99.9%) 1.725 ops/ms [Average]
  (min, avg, max) = (10.454, 10.550, 10.644), stdev = 0.095
  CI (99.9%): [8.825, 12.276] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.604 ops/ms
# Warmup Iteration   2: 10.343 ops/ms
# Warmup Iteration   3: 11.248 ops/ms
Iteration   1: 11.252 ops/ms
Iteration   2: 11.031 ops/ms
Iteration   3: 11.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.112 ±(99.9%) 2.222 ops/ms [Average]
  (min, avg, max) = (11.031, 11.112, 11.252), stdev = 0.122
  CI (99.9%): [8.891, 13.334] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.252 ops/ms
# Warmup Iteration   2: 10.147 ops/ms
# Warmup Iteration   3: 10.318 ops/ms
Iteration   1: 10.332 ops/ms
Iteration   2: 10.539 ops/ms
Iteration   3: 10.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.436 ±(99.9%) 1.882 ops/ms [Average]
  (min, avg, max) = (10.332, 10.436, 10.539), stdev = 0.103
  CI (99.9%): [8.554, 12.318] (assumes normal distribution)


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
# Warmup Iteration   1: 5.320 ops/ms
# Warmup Iteration   2: 7.785 ops/ms
# Warmup Iteration   3: 8.082 ops/ms
Iteration   1: 8.027 ops/ms
Iteration   2: 8.162 ops/ms
Iteration   3: 8.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.110 ±(99.9%) 1.328 ops/ms [Average]
  (min, avg, max) = (8.027, 8.110, 8.162), stdev = 0.073
  CI (99.9%): [6.782, 9.439] (assumes normal distribution)


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.002 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
Iteration   2: 3.096 ±(99.9%) 0.003 ms/op
Iteration   3: 3.108 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.070 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (3.007, 3.070, 3.108), stdev = 0.055
  CI (99.9%): [2.060, 4.080] (assumes normal distribution)


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.004 ms/op
Iteration   1: 2.905 ±(99.9%) 0.002 ms/op
Iteration   2: 2.890 ±(99.9%) 0.003 ms/op
Iteration   3: 2.896 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.897 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (2.890, 2.897, 2.905), stdev = 0.008
  CI (99.9%): [2.757, 3.037] (assumes normal distribution)


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
# Warmup Iteration   1: 4.421 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.004 ms/op
Iteration   1: 3.023 ±(99.9%) 0.002 ms/op
Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
Iteration   3: 3.034 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.042 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (3.023, 3.042, 3.071), stdev = 0.025
  CI (99.9%): [2.584, 3.500] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.054 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.016 ms/op
Iteration   1: 3.886 ±(99.9%) 0.046 ms/op
Iteration   2: 3.940 ±(99.9%) 0.020 ms/op
Iteration   3: 3.944 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.923 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (3.886, 3.923, 3.944), stdev = 0.033
  CI (99.9%): [3.329, 4.518] (assumes normal distribution)


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
# Warmup Iteration   1: 4.516 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.452 ms/op
                 createUser·p0.9999: 16.318 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 3.097 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  6.992 ms/op
                 createUser·p0.9999: 17.433 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   3: 3.080 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  12.747 ms/op
                 createUser·p0.9999: 21.811 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311777
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19570 
    [ 2.500,  5.000) = 290398 
    [ 5.000,  7.500) = 1415 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =     11.125 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.866 ±(99.9%) 0.006 ms/op
Iteration   1: 2.919 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.580 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.730 ms/op
                 existUser·p0.9999: 17.598 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   2: 2.885 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  11.010 ms/op
                 existUser·p0.9999: 13.713 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   3: 2.891 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  6.645 ms/op
                 existUser·p0.9999: 14.709 ms/op
                 existUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331119
  mean =      2.898 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2776 
    [ 1.250,  2.500) = 32127 
    [ 2.500,  3.750) = 287570 
    [ 3.750,  5.000) = 7699 
    [ 5.000,  6.250) = 426 
    [ 6.250,  7.500) = 191 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      7.431 ms/op
     p(99.9900) =     16.147 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
Iteration   1: 3.072 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.183 ms/op
                 getUser·p0.9999: 19.320 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  8.554 ms/op
                 getUser·p0.9999: 14.348 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.490 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.758 ms/op
                 getUser·p0.9999: 16.619 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313803
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1519 
    [ 1.250,  2.500) = 22903 
    [ 2.500,  3.750) = 267577 
    [ 3.750,  5.000) = 19860 
    [ 5.000,  6.250) = 1397 
    [ 6.250,  7.500) = 203 
    [ 7.500,  8.750) = 90 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      7.925 ms/op
     p(99.9900) =     18.090 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 5.283 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.011 ms/op
Iteration   1: 3.954 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 20.572 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   2: 3.960 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.288 ms/op
                 listUser·p0.9999: 21.329 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 3.928 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 25.642 ms/op
                 listUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243415
  mean =      3.947 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3099 
    [ 2.500,  5.000) = 218474 
    [ 5.000,  7.500) = 20602 
    [ 7.500, 10.000) = 799 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.909 ms/op
     p(99.9900) =     24.729 ms/op
     p(99.9990) =     26.266 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.550 ± 1.725  ops/ms
ClientGrpc.existUser                       thrpt       3  11.112 ± 2.222  ops/ms
ClientGrpc.getUser                         thrpt       3  10.436 ± 1.882  ops/ms
ClientGrpc.listUser                        thrpt       3   8.110 ± 1.328  ops/ms
ClientGrpc.createUser                       avgt       3   3.070 ± 1.010   ms/op
ClientGrpc.existUser                        avgt       3   2.897 ± 0.140   ms/op
ClientGrpc.getUser                          avgt       3   3.042 ± 0.458   ms/op
ClientGrpc.listUser                         avgt       3   3.923 ± 0.594   ms/op
ClientGrpc.createUser                     sample  311777   3.078 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.641           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.125           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.332           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  331119   2.898 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.580           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.431           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.147           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.891           ms/op
ClientGrpc.getUser                        sample  313803   3.058 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.490           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.925           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.090           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.857           ms/op
ClientGrpc.listUser                       sample  243415   3.947 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.968           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.909           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.729           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.378           ms/op
