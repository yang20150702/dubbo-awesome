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
# Warmup Iteration   1: 3.674 ops/ms
# Warmup Iteration   2: 8.326 ops/ms
# Warmup Iteration   3: 9.866 ops/ms
Iteration   1: 9.922 ops/ms
Iteration   2: 9.888 ops/ms
Iteration   3: 9.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.923 ±(99.9%) 0.638 ops/ms [Average]
  (min, avg, max) = (9.888, 9.923, 9.958), stdev = 0.035
  CI (99.9%): [9.285, 10.561] (assumes normal distribution)


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
# Warmup Iteration   1: 6.748 ops/ms
# Warmup Iteration   2: 10.328 ops/ms
# Warmup Iteration   3: 10.772 ops/ms
Iteration   1: 10.769 ops/ms
Iteration   2: 10.836 ops/ms
Iteration   3: 10.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.738 ±(99.9%) 2.110 ops/ms [Average]
  (min, avg, max) = (10.611, 10.738, 10.836), stdev = 0.116
  CI (99.9%): [8.628, 12.848] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.719 ops/ms
# Warmup Iteration   2: 10.007 ops/ms
# Warmup Iteration   3: 10.356 ops/ms
Iteration   1: 10.545 ops/ms
Iteration   2: 10.268 ops/ms
Iteration   3: 10.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.345 ±(99.9%) 3.196 ops/ms [Average]
  (min, avg, max) = (10.221, 10.345, 10.545), stdev = 0.175
  CI (99.9%): [7.149, 13.541] (assumes normal distribution)


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
# Warmup Iteration   1: 5.669 ops/ms
# Warmup Iteration   2: 7.313 ops/ms
# Warmup Iteration   3: 7.709 ops/ms
Iteration   1: 7.847 ops/ms
Iteration   2: 7.887 ops/ms
Iteration   3: 7.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.861 ±(99.9%) 0.413 ops/ms [Average]
  (min, avg, max) = (7.847, 7.861, 7.887), stdev = 0.023
  CI (99.9%): [7.447, 8.274] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.617 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.002 ms/op
Iteration   1: 3.075 ±(99.9%) 0.003 ms/op
Iteration   2: 3.127 ±(99.9%) 0.002 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.091 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (3.072, 3.091, 3.127), stdev = 0.030
  CI (99.9%): [2.536, 3.647] (assumes normal distribution)


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.002 ms/op
Iteration   1: 2.944 ±(99.9%) 0.002 ms/op
Iteration   2: 2.931 ±(99.9%) 0.002 ms/op
Iteration   3: 2.959 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.945 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (2.931, 2.945, 2.959), stdev = 0.014
  CI (99.9%): [2.695, 3.194] (assumes normal distribution)


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.003 ms/op
Iteration   1: 3.126 ±(99.9%) 0.002 ms/op
Iteration   2: 3.058 ±(99.9%) 0.003 ms/op
Iteration   3: 3.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.094 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.058, 3.094, 3.126), stdev = 0.034
  CI (99.9%): [2.472, 3.717] (assumes normal distribution)


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
# Warmup Iteration   1: 5.559 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.044 ms/op
Iteration   1: 4.062 ±(99.9%) 0.012 ms/op
Iteration   2: 4.097 ±(99.9%) 0.013 ms/op
Iteration   3: 4.098 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.086 ±(99.9%) 0.373 ms/op [Average]
  (min, avg, max) = (4.062, 4.086, 4.098), stdev = 0.020
  CI (99.9%): [3.713, 4.459] (assumes normal distribution)


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
# Warmup Iteration   1: 4.525 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
Iteration   1: 3.053 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  10.341 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.907 ms/op
                 createUser·p0.999:  8.105 ms/op
                 createUser·p0.9999: 19.137 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   3: 3.134 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.461 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  9.117 ms/op
                 createUser·p0.9999: 24.438 ms/op
                 createUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309750
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20370 
    [ 2.500,  5.000) = 286751 
    [ 5.000,  7.500) = 1945 
    [ 7.500, 10.000) = 412 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =      9.589 ms/op
     p(99.9900) =     22.022 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  10.071 ms/op
                 existUser·p0.9999: 16.148 ms/op
                 existUser·p1.00:   16.728 ms/op

Iteration   2: 2.980 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.127 ms/op
                 existUser·p0.9999: 14.287 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   3: 2.994 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  6.767 ms/op
                 existUser·p0.9999: 16.993 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322110
  mean =      2.981 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 249 
    [ 1.250,  2.500) = 24420 
    [ 2.500,  3.750) = 286298 
    [ 3.750,  5.000) = 9965 
    [ 5.000,  6.250) = 595 
    [ 6.250,  7.500) = 294 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.176 ms/op
     p(99.9900) =     16.495 ms/op
     p(99.9990) =     17.556 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.154 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  9.068 ms/op
                 getUser·p0.9999: 22.010 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.005 ms/op
                 getUser·p0.999:  8.890 ms/op
                 getUser·p0.9999: 15.923 ms/op
                 getUser·p1.00:   16.417 ms/op

Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  7.896 ms/op
                 getUser·p0.9999: 25.035 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306011
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13951 
    [ 2.500,  5.000) = 289745 
    [ 5.000,  7.500) = 1838 
    [ 7.500, 10.000) = 271 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     23.803 ms/op
     p(99.9990) =     25.229 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 5.918 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.325 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.013 ms/op
Iteration   1: 4.159 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 17.186 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   2: 4.055 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 19.664 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 4.195 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   7.482 ms/op
                 listUser·p0.999:  16.856 ms/op
                 listUser·p0.9999: 19.325 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232152
  mean =      4.135 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2282 
    [ 2.500,  5.000) = 195983 
    [ 5.000,  7.500) = 31354 
    [ 7.500, 10.000) = 1857 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      6.144 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     16.283 ms/op
     p(99.9900) =     19.417 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.923 ± 0.638  ops/ms
ClientGrpc.existUser                       thrpt       3  10.738 ± 2.110  ops/ms
ClientGrpc.getUser                         thrpt       3  10.345 ± 3.196  ops/ms
ClientGrpc.listUser                        thrpt       3   7.861 ± 0.413  ops/ms
ClientGrpc.createUser                       avgt       3   3.091 ± 0.556   ms/op
ClientGrpc.existUser                        avgt       3   2.945 ± 0.250   ms/op
ClientGrpc.getUser                          avgt       3   3.094 ± 0.622   ms/op
ClientGrpc.listUser                         avgt       3   4.086 ± 0.373   ms/op
ClientGrpc.createUser                     sample  309750   3.099 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.461           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.850           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.589           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.022           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.478           ms/op
ClientGrpc.existUser                      sample  322110   2.981 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.773           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.176           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.495           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.629           ms/op
ClientGrpc.getUser                        sample  306011   3.136 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.848           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.765           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.803           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.887           ms/op
ClientGrpc.listUser                       sample  232152   4.135 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.861           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.912           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.144           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.594           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.283           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.417           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.972           ms/op
