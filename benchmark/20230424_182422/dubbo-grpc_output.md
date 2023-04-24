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
# Warmup Iteration   1: 4.451 ops/ms
# Warmup Iteration   2: 9.188 ops/ms
# Warmup Iteration   3: 10.188 ops/ms
Iteration   1: 10.586 ops/ms
Iteration   2: 10.492 ops/ms
Iteration   3: 10.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.556 ±(99.9%) 1.010 ops/ms [Average]
  (min, avg, max) = (10.492, 10.556, 10.589), stdev = 0.055
  CI (99.9%): [9.546, 11.566] (assumes normal distribution)


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
# Warmup Iteration   1: 7.727 ops/ms
# Warmup Iteration   2: 10.570 ops/ms
# Warmup Iteration   3: 10.997 ops/ms
Iteration   1: 11.090 ops/ms
Iteration   2: 10.910 ops/ms
Iteration   3: 11.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.034 ±(99.9%) 1.974 ops/ms [Average]
  (min, avg, max) = (10.910, 11.034, 11.103), stdev = 0.108
  CI (99.9%): [9.061, 13.008] (assumes normal distribution)


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
# Warmup Iteration   1: 6.482 ops/ms
# Warmup Iteration   2: 10.349 ops/ms
# Warmup Iteration   3: 10.482 ops/ms
Iteration   1: 10.765 ops/ms
Iteration   2: 10.473 ops/ms
Iteration   3: 10.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.629 ±(99.9%) 2.682 ops/ms [Average]
  (min, avg, max) = (10.473, 10.629, 10.765), stdev = 0.147
  CI (99.9%): [7.947, 13.310] (assumes normal distribution)


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
# Warmup Iteration   1: 5.281 ops/ms
# Warmup Iteration   2: 7.771 ops/ms
# Warmup Iteration   3: 8.035 ops/ms
Iteration   1: 8.079 ops/ms
Iteration   2: 8.071 ops/ms
Iteration   3: 8.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.086 ±(99.9%) 0.357 ops/ms [Average]
  (min, avg, max) = (8.071, 8.086, 8.108), stdev = 0.020
  CI (99.9%): [7.729, 8.443] (assumes normal distribution)


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
# Warmup Iteration   1: 4.442 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.003 ms/op
Iteration   2: 3.056 ±(99.9%) 0.003 ms/op
Iteration   3: 3.015 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.027 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (3.011, 3.027, 3.056), stdev = 0.025
  CI (99.9%): [2.571, 3.484] (assumes normal distribution)


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.002 ms/op
Iteration   1: 2.850 ±(99.9%) 0.002 ms/op
Iteration   2: 2.801 ±(99.9%) 0.003 ms/op
Iteration   3: 2.876 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.842 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (2.801, 2.842, 2.876), stdev = 0.038
  CI (99.9%): [2.141, 3.543] (assumes normal distribution)


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.003 ms/op
Iteration   1: 3.084 ±(99.9%) 0.003 ms/op
Iteration   2: 3.112 ±(99.9%) 0.003 ms/op
Iteration   3: 3.079 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.091 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (3.079, 3.091, 3.112), stdev = 0.018
  CI (99.9%): [2.769, 3.414] (assumes normal distribution)


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
# Warmup Iteration   1: 5.295 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.268 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.018 ms/op
Iteration   1: 4.118 ±(99.9%) 0.010 ms/op
Iteration   2: 3.985 ±(99.9%) 0.018 ms/op
Iteration   3: 3.984 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.029 ±(99.9%) 1.410 ms/op [Average]
  (min, avg, max) = (3.984, 4.029, 4.118), stdev = 0.077
  CI (99.9%): [2.619, 5.439] (assumes normal distribution)


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
Iteration   1: 3.054 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  9.955 ms/op
                 createUser·p0.9999: 22.201 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.464 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.686 ms/op
                 createUser·p0.9999: 18.199 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  18.317 ms/op
                 createUser·p0.9999: 25.395 ms/op
                 createUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317529
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18261 
    [ 2.500,  5.000) = 297692 
    [ 5.000,  7.500) = 1070 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =     10.739 ms/op
     p(99.9900) =     25.010 ms/op
     p(99.9990) =     25.509 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.006 ms/op
Iteration   1: 2.941 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.153 ms/op
                 existUser·p0.9999: 14.090 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.750 ms/op
                 existUser·p0.9999: 16.581 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   3: 2.911 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  9.223 ms/op
                 existUser·p0.9999: 25.231 ms/op
                 existUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326756
  mean =      2.939 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34376 
    [ 2.500,  5.000) = 290943 
    [ 5.000,  7.500) = 1140 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.219 ms/op
     p(99.9900) =     19.793 ms/op
     p(99.9990) =     25.740 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.795 ms/op
                 getUser·p0.9999: 13.379 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  6.802 ms/op
                 getUser·p0.9999: 19.956 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.336 ms/op
                 getUser·p0.999:  8.204 ms/op
                 getUser·p0.9999: 18.268 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314015
  mean =      3.056 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19479 
    [ 2.500,  5.000) = 293063 
    [ 5.000,  7.500) = 1162 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.479 ms/op
     p(99.9900) =     18.665 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 4.875 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.011 ms/op
Iteration   1: 3.932 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  12.730 ms/op
                 listUser·p0.9999: 20.663 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   2: 3.944 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  16.097 ms/op
                 listUser·p0.9999: 22.741 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   3: 3.952 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  17.252 ms/op
                 listUser·p0.9999: 25.603 ms/op
                 listUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243397
  mean =      3.942 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4051 
    [ 2.500,  5.000) = 215815 
    [ 5.000,  7.500) = 22004 
    [ 7.500, 10.000) = 1070 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     15.001 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     27.235 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.556 ± 1.010  ops/ms
ClientGrpc.existUser                       thrpt       3  11.034 ± 1.974  ops/ms
ClientGrpc.getUser                         thrpt       3  10.629 ± 2.682  ops/ms
ClientGrpc.listUser                        thrpt       3   8.086 ± 0.357  ops/ms
ClientGrpc.createUser                       avgt       3   3.027 ± 0.456   ms/op
ClientGrpc.existUser                        avgt       3   2.842 ± 0.701   ms/op
ClientGrpc.getUser                          avgt       3   3.091 ± 0.323   ms/op
ClientGrpc.listUser                         avgt       3   4.029 ± 1.410   ms/op
ClientGrpc.createUser                     sample  317529   3.024 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.464           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.739           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.010           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.625           ms/op
ClientGrpc.existUser                      sample  326756   2.939 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.577           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.219           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.793           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.952           ms/op
ClientGrpc.getUser                        sample  314015   3.056 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.638           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.479           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.665           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  243397   3.942 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.171           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.001           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.953           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.082           ms/op
