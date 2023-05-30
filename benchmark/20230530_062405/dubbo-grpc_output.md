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
# Warmup Iteration   1: 3.730 ops/ms
# Warmup Iteration   2: 8.498 ops/ms
# Warmup Iteration   3: 10.137 ops/ms
Iteration   1: 10.539 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.593 ±(99.9%) 0.927 ops/ms [Average]
  (min, avg, max) = (10.539, 10.593, 10.640), stdev = 0.051
  CI (99.9%): [9.665, 11.520] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.454 ops/ms
# Warmup Iteration   2: 10.619 ops/ms
# Warmup Iteration   3: 10.921 ops/ms
Iteration   1: 11.065 ops/ms
Iteration   2: 10.869 ops/ms
Iteration   3: 11.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.989 ±(99.9%) 1.916 ops/ms [Average]
  (min, avg, max) = (10.869, 10.989, 11.065), stdev = 0.105
  CI (99.9%): [9.073, 12.906] (assumes normal distribution)


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
# Warmup Iteration   1: 6.593 ops/ms
# Warmup Iteration   2: 9.910 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.741 ops/ms
Iteration   2: 10.684 ops/ms
Iteration   3: 10.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.662 ±(99.9%) 1.681 ops/ms [Average]
  (min, avg, max) = (10.561, 10.662, 10.741), stdev = 0.092
  CI (99.9%): [8.981, 12.343] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.217 ops/ms
# Warmup Iteration   2: 7.789 ops/ms
# Warmup Iteration   3: 8.143 ops/ms
Iteration   1: 8.186 ops/ms
Iteration   2: 8.298 ops/ms
Iteration   3: 8.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.311 ±(99.9%) 2.419 ops/ms [Average]
  (min, avg, max) = (8.186, 8.311, 8.450), stdev = 0.133
  CI (99.9%): [5.893, 10.730] (assumes normal distribution)


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.003 ms/op
Iteration   1: 3.063 ±(99.9%) 0.002 ms/op
Iteration   2: 3.079 ±(99.9%) 0.002 ms/op
Iteration   3: 2.991 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.044 ±(99.9%) 0.860 ms/op [Average]
  (min, avg, max) = (2.991, 3.044, 3.079), stdev = 0.047
  CI (99.9%): [2.185, 3.904] (assumes normal distribution)


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.890 ±(99.9%) 0.002 ms/op
Iteration   1: 2.942 ±(99.9%) 0.001 ms/op
Iteration   2: 2.782 ±(99.9%) 0.002 ms/op
Iteration   3: 2.934 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.886 ±(99.9%) 1.644 ms/op [Average]
  (min, avg, max) = (2.782, 2.886, 2.942), stdev = 0.090
  CI (99.9%): [1.242, 4.530] (assumes normal distribution)


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
# Warmup Iteration   1: 4.162 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 2.956 ±(99.9%) 0.003 ms/op
Iteration   2: 3.007 ±(99.9%) 0.004 ms/op
Iteration   3: 3.002 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.988 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (2.956, 2.988, 3.007), stdev = 0.028
  CI (99.9%): [2.474, 3.502] (assumes normal distribution)


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
# Warmup Iteration   1: 5.437 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.018 ms/op
Iteration   1: 3.808 ±(99.9%) 0.015 ms/op
Iteration   2: 3.805 ±(99.9%) 0.010 ms/op
Iteration   3: 3.837 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.817 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (3.805, 3.817, 3.837), stdev = 0.018
  CI (99.9%): [3.494, 4.139] (assumes normal distribution)


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  8.308 ms/op
                 createUser·p0.9999: 16.334 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.686 ms/op
                 createUser·p0.9999: 18.607 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   3: 3.018 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  7.520 ms/op
                 createUser·p0.9999: 23.638 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315802
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25036 
    [ 2.500,  5.000) = 289065 
    [ 5.000,  7.500) = 1331 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      8.077 ms/op
     p(99.9900) =     21.510 ms/op
     p(99.9990) =     24.202 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.890 ±(99.9%) 0.006 ms/op
Iteration   1: 2.817 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  5.600 ms/op
                 existUser·p0.9999: 15.743 ms/op
                 existUser·p1.00:   15.991 ms/op

Iteration   2: 2.818 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.265 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  6.275 ms/op
                 existUser·p0.9999: 14.379 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   3: 2.921 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   3.928 ms/op
                 existUser·p0.999:  7.078 ms/op
                 existUser·p0.9999: 16.319 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336711
  mean =      2.851 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3732 
    [ 1.250,  2.500) = 44817 
    [ 2.500,  3.750) = 282393 
    [ 3.750,  5.000) = 5084 
    [ 5.000,  6.250) = 331 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.469 ms/op
     p(99.0000) =      3.915 ms/op
     p(99.9000) =      6.373 ms/op
     p(99.9900) =     15.870 ms/op
     p(99.9990) =     18.097 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.445 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  9.063 ms/op
                 getUser·p0.9999: 12.603 ms/op
                 getUser·p1.00:   12.894 ms/op

Iteration   2: 2.986 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.452 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  6.540 ms/op
                 getUser·p0.9999: 21.604 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   3: 2.969 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.165 ms/op
                 getUser·p0.999:  6.295 ms/op
                 getUser·p0.9999: 17.079 ms/op
                 getUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320746
  mean =      2.992 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28765 
    [ 2.500,  5.000) = 290832 
    [ 5.000,  7.500) = 857 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.452 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.031 ms/op
     p(99.9900) =     20.420 ms/op
     p(99.9990) =     21.817 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 5.384 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.010 ms/op
Iteration   1: 3.889 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.475 ms/op
                 listUser·p0.99:   6.615 ms/op
                 listUser·p0.999:  13.693 ms/op
                 listUser·p0.9999: 15.974 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   2: 3.845 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.669 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.534 ms/op
                 listUser·p0.9999: 19.173 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   3: 3.837 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.888 ms/op
                 listUser·p0.9999: 23.812 ms/op
                 listUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248716
  mean =      3.857 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4955 
    [ 2.500,  5.000) = 223371 
    [ 5.000,  7.500) = 19287 
    [ 7.500, 10.000) = 644 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     14.996 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     24.970 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.593 ± 0.927  ops/ms
ClientGrpc.existUser                       thrpt       3  10.989 ± 1.916  ops/ms
ClientGrpc.getUser                         thrpt       3  10.662 ± 1.681  ops/ms
ClientGrpc.listUser                        thrpt       3   8.311 ± 2.419  ops/ms
ClientGrpc.createUser                       avgt       3   3.044 ± 0.860   ms/op
ClientGrpc.existUser                        avgt       3   2.886 ± 1.644   ms/op
ClientGrpc.getUser                          avgt       3   2.988 ± 0.514   ms/op
ClientGrpc.listUser                         avgt       3   3.817 ± 0.323   ms/op
ClientGrpc.createUser                     sample  315802   3.040 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.572           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.077           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.510           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.248           ms/op
ClientGrpc.existUser                      sample  336711   2.851 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.641           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.915           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.373           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.870           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  320746   2.992 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.452           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.031           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.420           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.889           ms/op
ClientGrpc.listUser                       sample  248716   3.857 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.669           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.996           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.364           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.788           ms/op
