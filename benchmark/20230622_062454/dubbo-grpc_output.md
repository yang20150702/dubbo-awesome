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
# Warmup Iteration   1: 4.538 ops/ms
# Warmup Iteration   2: 9.543 ops/ms
# Warmup Iteration   3: 10.212 ops/ms
Iteration   1: 10.683 ops/ms
Iteration   2: 10.890 ops/ms
Iteration   3: 10.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.761 ±(99.9%) 2.060 ops/ms [Average]
  (min, avg, max) = (10.683, 10.761, 10.890), stdev = 0.113
  CI (99.9%): [8.701, 12.821] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.677 ops/ms
# Warmup Iteration   2: 10.803 ops/ms
# Warmup Iteration   3: 10.971 ops/ms
Iteration   1: 10.987 ops/ms
Iteration   2: 11.081 ops/ms
Iteration   3: 11.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.118 ±(99.9%) 2.782 ops/ms [Average]
  (min, avg, max) = (10.987, 11.118, 11.285), stdev = 0.152
  CI (99.9%): [8.336, 13.899] (assumes normal distribution)


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
# Warmup Iteration   1: 7.416 ops/ms
# Warmup Iteration   2: 10.116 ops/ms
# Warmup Iteration   3: 10.549 ops/ms
Iteration   1: 10.704 ops/ms
Iteration   2: 10.744 ops/ms
Iteration   3: 10.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.724 ±(99.9%) 0.362 ops/ms [Average]
  (min, avg, max) = (10.704, 10.724, 10.744), stdev = 0.020
  CI (99.9%): [10.361, 11.086] (assumes normal distribution)


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
# Warmup Iteration   1: 7.429 ops/ms
# Warmup Iteration   2: 8.129 ops/ms
# Warmup Iteration   3: 8.356 ops/ms
Iteration   1: 8.398 ops/ms
Iteration   2: 8.537 ops/ms
Iteration   3: 8.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.438 ±(99.9%) 1.563 ops/ms [Average]
  (min, avg, max) = (8.381, 8.438, 8.537), stdev = 0.086
  CI (99.9%): [6.875, 10.002] (assumes normal distribution)


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.002 ms/op
Iteration   1: 3.006 ±(99.9%) 0.008 ms/op
Iteration   2: 3.041 ±(99.9%) 0.002 ms/op
Iteration   3: 2.964 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.004 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (2.964, 3.004, 3.041), stdev = 0.038
  CI (99.9%): [2.303, 3.705] (assumes normal distribution)


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.943 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.002 ms/op
Iteration   1: 2.939 ±(99.9%) 0.003 ms/op
Iteration   2: 2.893 ±(99.9%) 0.003 ms/op
Iteration   3: 2.835 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.889 ±(99.9%) 0.955 ms/op [Average]
  (min, avg, max) = (2.835, 2.889, 2.939), stdev = 0.052
  CI (99.9%): [1.934, 3.844] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.863 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.003 ms/op
Iteration   1: 3.023 ±(99.9%) 0.002 ms/op
Iteration   2: 3.059 ±(99.9%) 0.002 ms/op
Iteration   3: 3.074 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.052 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.023, 3.052, 3.074), stdev = 0.026
  CI (99.9%): [2.580, 3.525] (assumes normal distribution)


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
# Warmup Iteration   1: 5.081 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.013 ms/op
Iteration   1: 3.838 ±(99.9%) 0.056 ms/op
Iteration   2: 3.769 ±(99.9%) 0.017 ms/op
Iteration   3: 3.712 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.773 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (3.712, 3.773, 3.838), stdev = 0.063
  CI (99.9%): [2.624, 4.922] (assumes normal distribution)


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
Iteration   1: 3.003 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.942 ms/op
                 createUser·p0.9999: 21.299 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  5.964 ms/op
                 createUser·p0.9999: 15.291 ms/op
                 createUser·p1.00:   15.499 ms/op

Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.540 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  10.682 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319611
  mean =      3.002 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21395 
    [ 2.500,  5.000) = 296620 
    [ 5.000,  7.500) = 1132 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     21.333 ms/op
     p(99.9990) =     21.922 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.005 ms/op
Iteration   1: 2.872 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.848 ms/op
                 existUser·p0.9999: 11.237 ms/op
                 existUser·p1.00:   11.387 ms/op

Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.738 ms/op
                 existUser·p0.9999: 17.538 ms/op
                 existUser·p1.00:   18.186 ms/op

Iteration   3: 2.855 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.272 ms/op
                 existUser·p0.9999: 14.346 ms/op
                 existUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331160
  mean =      2.897 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1830 
    [ 1.250,  2.500) = 42921 
    [ 2.500,  3.750) = 275271 
    [ 3.750,  5.000) = 9788 
    [ 5.000,  6.250) = 798 
    [ 6.250,  7.500) = 277 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.929 ms/op
     p(99.9900) =     16.595 ms/op
     p(99.9990) =     18.027 ms/op
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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
Iteration   1: 2.949 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.430 ms/op
                 getUser·p0.9999: 11.867 ms/op
                 getUser·p1.00:   12.042 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  8.934 ms/op
                 getUser·p0.9999: 15.519 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.506 ms/op
                 getUser·p0.99:   4.018 ms/op
                 getUser·p0.999:  7.723 ms/op
                 getUser·p0.9999: 23.331 ms/op
                 getUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323393
  mean =      2.970 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24301 
    [ 2.500,  5.000) = 297903 
    [ 5.000,  7.500) = 805 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.638 ms/op
     p(99.9900) =     21.313 ms/op
     p(99.9990) =     23.520 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 5.283 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.010 ms/op
Iteration   1: 3.828 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.011 ms/op
                 listUser·p0.9999: 25.154 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   2: 3.808 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  22.835 ms/op
                 listUser·p0.9999: 26.477 ms/op
                 listUser·p1.00:   27.427 ms/op

Iteration   3: 3.893 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.547 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  14.037 ms/op
                 listUser·p0.9999: 22.766 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249991
  mean =      3.843 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5794 
    [ 2.500,  5.000) = 223081 
    [ 5.000,  7.500) = 19929 
    [ 7.500, 10.000) = 803 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     14.697 ms/op
     p(99.9900) =     25.920 ms/op
     p(99.9990) =     27.312 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.761 ± 2.060  ops/ms
ClientGrpc.existUser                       thrpt       3  11.118 ± 2.782  ops/ms
ClientGrpc.getUser                         thrpt       3  10.724 ± 0.362  ops/ms
ClientGrpc.listUser                        thrpt       3   8.438 ± 1.563  ops/ms
ClientGrpc.createUser                       avgt       3   3.004 ± 0.701   ms/op
ClientGrpc.existUser                        avgt       3   2.889 ± 0.955   ms/op
ClientGrpc.getUser                          avgt       3   3.052 ± 0.472   ms/op
ClientGrpc.listUser                         avgt       3   3.773 ± 1.149   ms/op
ClientGrpc.createUser                     sample  319611   3.002 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.528           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.428           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.585           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.333           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.922           ms/op
ClientGrpc.existUser                      sample  331160   2.897 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.577           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.929           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.595           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  323393   2.970 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.570           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.412           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.638           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.313           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.593           ms/op
ClientGrpc.listUser                       sample  249991   3.843 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.547           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.697           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.920           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.427           ms/op
