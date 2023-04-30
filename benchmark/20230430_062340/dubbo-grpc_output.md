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
# Warmup Iteration   1: 4.238 ops/ms
# Warmup Iteration   2: 8.825 ops/ms
# Warmup Iteration   3: 10.341 ops/ms
Iteration   1: 10.411 ops/ms
Iteration   2: 10.535 ops/ms
Iteration   3: 10.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.497 ±(99.9%) 1.358 ops/ms [Average]
  (min, avg, max) = (10.411, 10.497, 10.545), stdev = 0.074
  CI (99.9%): [9.139, 11.855] (assumes normal distribution)


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
# Warmup Iteration   1: 7.331 ops/ms
# Warmup Iteration   2: 10.493 ops/ms
# Warmup Iteration   3: 10.873 ops/ms
Iteration   1: 10.964 ops/ms
Iteration   2: 10.957 ops/ms
Iteration   3: 11.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.999 ±(99.9%) 1.202 ops/ms [Average]
  (min, avg, max) = (10.957, 10.999, 11.075), stdev = 0.066
  CI (99.9%): [9.796, 12.201] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.753 ops/ms
# Warmup Iteration   2: 10.097 ops/ms
# Warmup Iteration   3: 10.519 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.456 ops/ms
Iteration   3: 10.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.494 ±(99.9%) 1.289 ops/ms [Average]
  (min, avg, max) = (10.450, 10.494, 10.575), stdev = 0.071
  CI (99.9%): [9.205, 11.782] (assumes normal distribution)


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
# Warmup Iteration   1: 5.594 ops/ms
# Warmup Iteration   2: 7.918 ops/ms
# Warmup Iteration   3: 8.138 ops/ms
Iteration   1: 8.172 ops/ms
Iteration   2: 8.026 ops/ms
Iteration   3: 8.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.088 ±(99.9%) 1.376 ops/ms [Average]
  (min, avg, max) = (8.026, 8.088, 8.172), stdev = 0.075
  CI (99.9%): [6.712, 9.465] (assumes normal distribution)


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.003 ms/op
Iteration   1: 3.100 ±(99.9%) 0.002 ms/op
Iteration   2: 3.005 ±(99.9%) 0.003 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.045 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (3.005, 3.045, 3.100), stdev = 0.049
  CI (99.9%): [2.156, 3.935] (assumes normal distribution)


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.002 ms/op
Iteration   1: 2.899 ±(99.9%) 0.003 ms/op
Iteration   2: 2.934 ±(99.9%) 0.002 ms/op
Iteration   3: 2.918 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.917 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.899, 2.917, 2.934), stdev = 0.017
  CI (99.9%): [2.603, 3.231] (assumes normal distribution)


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
# Warmup Iteration   1: 4.361 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.004 ms/op
Iteration   1: 3.063 ±(99.9%) 0.003 ms/op
Iteration   2: 3.054 ±(99.9%) 0.001 ms/op
Iteration   3: 3.088 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.069 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.054, 3.069, 3.088), stdev = 0.018
  CI (99.9%): [2.747, 3.390] (assumes normal distribution)


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
# Warmup Iteration   1: 4.808 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.015 ms/op
Iteration   1: 4.014 ±(99.9%) 0.025 ms/op
Iteration   2: 3.985 ±(99.9%) 0.028 ms/op
Iteration   3: 3.950 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.983 ±(99.9%) 0.585 ms/op [Average]
  (min, avg, max) = (3.950, 3.983, 4.014), stdev = 0.032
  CI (99.9%): [3.398, 4.567] (assumes normal distribution)


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  7.440 ms/op
                 createUser·p0.9999: 16.679 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.677 ms/op
                 createUser·p0.9999: 23.587 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.495 ms/op
                 createUser·p0.999:  9.073 ms/op
                 createUser·p0.9999: 21.413 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316731
  mean =      3.029 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20942 
    [ 2.500,  5.000) = 294147 
    [ 5.000,  7.500) = 1248 
    [ 7.500, 10.000) = 137 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     24.079 ms/op
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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.006 ms/op
Iteration   1: 2.942 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  6.990 ms/op
                 existUser·p0.9999: 12.292 ms/op
                 existUser·p1.00:   12.550 ms/op

Iteration   2: 2.950 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.523 ms/op
                 existUser·p0.9999: 13.107 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  11.195 ms/op
                 existUser·p0.9999: 18.018 ms/op
                 existUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322872
  mean =      2.972 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 408 
    [ 1.250,  2.500) = 27724 
    [ 2.500,  3.750) = 280916 
    [ 3.750,  5.000) = 12826 
    [ 5.000,  6.250) = 389 
    [ 6.250,  7.500) = 291 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.479 ms/op
     p(99.9900) =     17.194 ms/op
     p(99.9990) =     18.368 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
Iteration   1: 3.096 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.628 ms/op
                 getUser·p0.9999: 21.092 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  8.018 ms/op
                 getUser·p0.9999: 19.744 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  7.836 ms/op
                 getUser·p0.9999: 25.871 ms/op
                 getUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312728
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17714 
    [ 2.500,  5.000) = 293500 
    [ 5.000,  7.500) = 1143 
    [ 7.500, 10.000) = 159 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.922 ms/op
     p(99.9900) =     25.035 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 5.762 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.012 ms/op
Iteration   1: 3.943 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.664 ms/op
                 listUser·p0.9999: 15.390 ms/op
                 listUser·p1.00:   15.991 ms/op

Iteration   2: 3.928 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 17.789 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   3: 3.947 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.966 ms/op
                 listUser·p0.9999: 18.366 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243573
  mean =      3.939 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 4101 
    [ 2.500,  3.750) = 108902 
    [ 3.750,  5.000) = 108899 
    [ 5.000,  6.250) = 15250 
    [ 6.250,  7.500) = 5203 
    [ 7.500,  8.750) = 601 
    [ 8.750, 10.000) = 162 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 90 
    [15.000, 16.250) = 92 
    [16.250, 17.500) = 100 
    [17.500, 18.750) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     14.970 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     19.436 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.497 ± 1.358  ops/ms
ClientGrpc.existUser                       thrpt       3  10.999 ± 1.202  ops/ms
ClientGrpc.getUser                         thrpt       3  10.494 ± 1.289  ops/ms
ClientGrpc.listUser                        thrpt       3   8.088 ± 1.376  ops/ms
ClientGrpc.createUser                       avgt       3   3.045 ± 0.889   ms/op
ClientGrpc.existUser                        avgt       3   2.917 ± 0.314   ms/op
ClientGrpc.getUser                          avgt       3   3.069 ± 0.322   ms/op
ClientGrpc.listUser                         avgt       3   3.983 ± 0.585   ms/op
ClientGrpc.createUser                     sample  316731   3.029 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.653           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.389           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.839           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.478           ms/op
ClientGrpc.existUser                      sample  322872   2.972 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.731           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.479           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.194           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.514           ms/op
ClientGrpc.getUser                        sample  312728   3.067 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.657           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.922           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.035           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.361           ms/op
ClientGrpc.listUser                       sample  243573   3.939 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.212           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.970           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.826           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.562           ms/op
