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
# Warmup Iteration   1: 4.008 ops/ms
# Warmup Iteration   2: 8.623 ops/ms
# Warmup Iteration   3: 10.317 ops/ms
Iteration   1: 10.450 ops/ms
Iteration   2: 10.457 ops/ms
Iteration   3: 10.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.541 ±(99.9%) 2.759 ops/ms [Average]
  (min, avg, max) = (10.450, 10.541, 10.716), stdev = 0.151
  CI (99.9%): [7.782, 13.300] (assumes normal distribution)


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
# Warmup Iteration   1: 7.623 ops/ms
# Warmup Iteration   2: 10.643 ops/ms
# Warmup Iteration   3: 11.219 ops/ms
Iteration   1: 11.046 ops/ms
Iteration   2: 11.028 ops/ms
Iteration   3: 11.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.112 ±(99.9%) 2.377 ops/ms [Average]
  (min, avg, max) = (11.028, 11.112, 11.262), stdev = 0.130
  CI (99.9%): [8.735, 13.490] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.622 ops/ms
# Warmup Iteration   2: 10.087 ops/ms
# Warmup Iteration   3: 10.455 ops/ms
Iteration   1: 10.516 ops/ms
Iteration   2: 10.532 ops/ms
Iteration   3: 10.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.463 ±(99.9%) 1.945 ops/ms [Average]
  (min, avg, max) = (10.340, 10.463, 10.532), stdev = 0.107
  CI (99.9%): [8.518, 12.407] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.641 ops/ms
# Warmup Iteration   2: 7.830 ops/ms
# Warmup Iteration   3: 7.890 ops/ms
Iteration   1: 7.656 ops/ms
Iteration   2: 7.974 ops/ms
Iteration   3: 7.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.835 ±(99.9%) 2.960 ops/ms [Average]
  (min, avg, max) = (7.656, 7.835, 7.974), stdev = 0.162
  CI (99.9%): [4.875, 10.795] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.003 ms/op
Iteration   1: 3.016 ±(99.9%) 0.007 ms/op
Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
Iteration   3: 2.992 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.004 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.992, 3.004, 3.016), stdev = 0.012
  CI (99.9%): [2.784, 3.225] (assumes normal distribution)


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.003 ms/op
Iteration   1: 2.890 ±(99.9%) 0.003 ms/op
Iteration   2: 2.874 ±(99.9%) 0.002 ms/op
Iteration   3: 2.962 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.909 ±(99.9%) 0.860 ms/op [Average]
  (min, avg, max) = (2.874, 2.909, 2.962), stdev = 0.047
  CI (99.9%): [2.048, 3.769] (assumes normal distribution)


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.003 ms/op
Iteration   1: 3.039 ±(99.9%) 0.002 ms/op
Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
Iteration   3: 3.023 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.024 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (3.011, 3.024, 3.039), stdev = 0.014
  CI (99.9%): [2.769, 3.280] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.196 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.020 ms/op
Iteration   1: 3.996 ±(99.9%) 0.007 ms/op
Iteration   2: 4.130 ±(99.9%) 0.022 ms/op
Iteration   3: 3.997 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.041 ±(99.9%) 1.412 ms/op [Average]
  (min, avg, max) = (3.996, 4.041, 4.130), stdev = 0.077
  CI (99.9%): [2.629, 5.453] (assumes normal distribution)


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
Iteration   1: 2.983 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  8.520 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  8.426 ms/op
                 createUser·p0.9999: 14.730 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   3: 3.004 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  8.791 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318515
  mean =      3.012 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32664 
    [ 2.500,  5.000) = 283405 
    [ 5.000,  7.500) = 1801 
    [ 7.500, 10.000) = 412 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.825 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     20.933 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
Iteration   1: 2.903 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  7.575 ms/op
                 existUser·p0.9999: 15.417 ms/op
                 existUser·p1.00:   16.400 ms/op

Iteration   2: 2.892 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  7.680 ms/op
                 existUser·p0.9999: 21.955 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   3: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.542 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  7.649 ms/op
                 existUser·p0.9999: 15.350 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331009
  mean =      2.897 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41810 
    [ 2.500,  5.000) = 287065 
    [ 5.000,  7.500) = 1757 
    [ 7.500, 10.000) = 179 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      7.660 ms/op
     p(99.9900) =     17.167 ms/op
     p(99.9990) =     22.141 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 4.252 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  8.015 ms/op
                 getUser·p0.9999: 12.737 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  7.488 ms/op
                 getUser·p0.9999: 14.400 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.316 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.063 ms/op
                 getUser·p0.999:  8.216 ms/op
                 getUser·p0.9999: 16.908 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315294
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1258 
    [ 1.250,  2.500) = 26233 
    [ 2.500,  3.750) = 267447 
    [ 3.750,  5.000) = 17769 
    [ 5.000,  6.250) = 1406 
    [ 6.250,  7.500) = 662 
    [ 7.500,  8.750) = 315 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 70 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.316 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      8.004 ms/op
     p(99.9900) =     16.454 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 5.696 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.223 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.011 ms/op
Iteration   1: 4.036 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  18.113 ms/op
                 listUser·p0.9999: 22.350 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 4.059 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  16.339 ms/op
                 listUser·p0.9999: 22.882 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   3: 4.042 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  18.150 ms/op
                 listUser·p0.9999: 22.046 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237292
  mean =      4.046 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3218 
    [ 2.500,  5.000) = 210036 
    [ 5.000,  7.500) = 22485 
    [ 7.500, 10.000) = 973 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     22.520 ms/op
     p(99.9990) =     23.130 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.541 ± 2.759  ops/ms
ClientGrpc.existUser                       thrpt       3  11.112 ± 2.377  ops/ms
ClientGrpc.getUser                         thrpt       3  10.463 ± 1.945  ops/ms
ClientGrpc.listUser                        thrpt       3   7.835 ± 2.960  ops/ms
ClientGrpc.createUser                       avgt       3   3.004 ± 0.221   ms/op
ClientGrpc.existUser                        avgt       3   2.909 ± 0.860   ms/op
ClientGrpc.getUser                          avgt       3   3.024 ± 0.256   ms/op
ClientGrpc.listUser                         avgt       3   4.041 ± 1.412   ms/op
ClientGrpc.createUser                     sample  318515   3.012 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.630           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.536           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.316           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.004           ms/op
ClientGrpc.existUser                      sample  331009   2.897 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.542           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.334           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.686           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.660           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.167           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.217           ms/op
ClientGrpc.getUser                        sample  315294   3.044 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.316           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.004           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.454           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.007           ms/op
ClientGrpc.listUser                       sample  237292   4.046 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.795           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.957           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.520           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.167           ms/op
