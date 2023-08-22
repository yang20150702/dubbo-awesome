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
# Warmup Iteration   1: 4.632 ops/ms
# Warmup Iteration   2: 9.458 ops/ms
# Warmup Iteration   3: 10.126 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.679 ops/ms
Iteration   3: 10.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.678 ±(99.9%) 0.789 ops/ms [Average]
  (min, avg, max) = (10.634, 10.678, 10.720), stdev = 0.043
  CI (99.9%): [9.888, 11.467] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.252 ops/ms
# Warmup Iteration   2: 10.799 ops/ms
# Warmup Iteration   3: 10.969 ops/ms
Iteration   1: 11.259 ops/ms
Iteration   2: 11.391 ops/ms
Iteration   3: 11.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.223 ±(99.9%) 3.446 ops/ms [Average]
  (min, avg, max) = (11.019, 11.223, 11.391), stdev = 0.189
  CI (99.9%): [7.777, 14.668] (assumes normal distribution)


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
# Warmup Iteration   1: 7.085 ops/ms
# Warmup Iteration   2: 10.241 ops/ms
# Warmup Iteration   3: 10.558 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.602 ops/ms
Iteration   3: 11.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.754 ±(99.9%) 4.330 ops/ms [Average]
  (min, avg, max) = (10.602, 10.754, 11.028), stdev = 0.237
  CI (99.9%): [6.424, 15.085] (assumes normal distribution)


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
# Warmup Iteration   1: 5.923 ops/ms
# Warmup Iteration   2: 8.080 ops/ms
# Warmup Iteration   3: 8.225 ops/ms
Iteration   1: 8.190 ops/ms
Iteration   2: 8.380 ops/ms
Iteration   3: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.310 ±(99.9%) 1.895 ops/ms [Average]
  (min, avg, max) = (8.190, 8.310, 8.380), stdev = 0.104
  CI (99.9%): [6.415, 10.204] (assumes normal distribution)


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.003 ms/op
Iteration   1: 3.066 ±(99.9%) 0.003 ms/op
Iteration   2: 3.020 ±(99.9%) 0.003 ms/op
Iteration   3: 2.962 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.016 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (2.962, 3.016, 3.066), stdev = 0.052
  CI (99.9%): [2.066, 3.966] (assumes normal distribution)


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.915 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.004 ms/op
Iteration   1: 2.811 ±(99.9%) 0.004 ms/op
Iteration   2: 2.862 ±(99.9%) 0.003 ms/op
Iteration   3: 2.790 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.821 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (2.790, 2.821, 2.862), stdev = 0.037
  CI (99.9%): [2.144, 3.498] (assumes normal distribution)


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
# Warmup Iteration   1: 3.949 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.005 ms/op
Iteration   1: 2.974 ±(99.9%) 0.003 ms/op
Iteration   2: 3.003 ±(99.9%) 0.002 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.995 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (2.974, 2.995, 3.007), stdev = 0.018
  CI (99.9%): [2.658, 3.331] (assumes normal distribution)


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
# Warmup Iteration   1: 5.087 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.010 ms/op
Iteration   1: 3.820 ±(99.9%) 0.015 ms/op
Iteration   2: 3.862 ±(99.9%) 0.034 ms/op
Iteration   3: 3.876 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.853 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (3.820, 3.853, 3.876), stdev = 0.029
  CI (99.9%): [3.320, 4.385] (assumes normal distribution)


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
# Warmup Iteration   1: 3.906 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.564 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  8.141 ms/op
                 createUser·p0.9999: 11.326 ms/op
                 createUser·p1.00:   11.469 ms/op

Iteration   2: 3.030 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  8.272 ms/op
                 createUser·p0.9999: 24.740 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.569 ms/op
                 createUser·p0.9999: 14.707 ms/op
                 createUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320910
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31502 
    [ 2.500,  5.000) = 287624 
    [ 5.000,  7.500) = 1338 
    [ 7.500, 10.000) = 205 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.913 ms/op
     p(99.9900) =     23.637 ms/op
     p(99.9990) =     24.831 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 3.599 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.937 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.007 ms/op
Iteration   1: 2.815 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  7.306 ms/op
                 existUser·p0.9999: 21.145 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   2: 2.887 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  7.438 ms/op
                 existUser·p0.9999: 17.629 ms/op
                 existUser·p1.00:   17.859 ms/op

Iteration   3: 2.886 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.025 ms/op
                 existUser·p0.9999: 19.839 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335312
  mean =      2.862 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57125 
    [ 2.500,  5.000) = 276468 
    [ 5.000,  7.500) = 1363 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      7.660 ms/op
     p(99.9900) =     20.299 ms/op
     p(99.9990) =     22.762 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.735 ms/op
                 getUser·p0.9999: 15.773 ms/op
                 getUser·p1.00:   16.122 ms/op

Iteration   2: 2.985 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.634 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.053 ms/op
                 getUser·p0.9999: 13.488 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  8.381 ms/op
                 getUser·p0.9999: 15.385 ms/op
                 getUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319627
  mean =      3.003 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1291 
    [ 1.250,  2.500) = 23746 
    [ 2.500,  3.750) = 279010 
    [ 3.750,  5.000) = 13747 
    [ 5.000,  6.250) = 897 
    [ 6.250,  7.500) = 431 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      8.380 ms/op
     p(99.9900) =     15.418 ms/op
     p(99.9990) =     16.207 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.011 ms/op
Iteration   1: 3.824 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 14.747 ms/op
                 listUser·p1.00:   15.385 ms/op

Iteration   2: 3.896 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.318 ms/op
                 listUser·p0.9999: 18.016 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 3.899 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  21.092 ms/op
                 listUser·p0.9999: 31.326 ms/op
                 listUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248175
  mean =      3.873 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5010 
    [ 2.500,  5.000) = 220525 
    [ 5.000,  7.500) = 21195 
    [ 7.500, 10.000) = 888 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     29.021 ms/op
     p(99.9990) =     31.770 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.678 ± 0.789  ops/ms
ClientGrpc.existUser                       thrpt       3  11.223 ± 3.446  ops/ms
ClientGrpc.getUser                         thrpt       3  10.754 ± 4.330  ops/ms
ClientGrpc.listUser                        thrpt       3   8.310 ± 1.895  ops/ms
ClientGrpc.createUser                       avgt       3   3.016 ± 0.950   ms/op
ClientGrpc.existUser                        avgt       3   2.821 ± 0.677   ms/op
ClientGrpc.getUser                          avgt       3   2.995 ± 0.336   ms/op
ClientGrpc.listUser                         avgt       3   3.853 ± 0.533   ms/op
ClientGrpc.createUser                     sample  320910   2.992 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.564           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.913           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.637           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.969           ms/op
ClientGrpc.existUser                      sample  335312   2.862 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.578           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.660           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.299           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.872           ms/op
ClientGrpc.getUser                        sample  319627   3.003 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.593           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.380           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.418           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.237           ms/op
ClientGrpc.listUser                       sample  248175   3.873 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.896           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.976           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.021           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.818           ms/op
