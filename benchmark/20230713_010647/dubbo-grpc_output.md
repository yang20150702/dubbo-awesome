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
# Warmup Iteration   1: 4.672 ops/ms
# Warmup Iteration   2: 9.182 ops/ms
# Warmup Iteration   3: 10.175 ops/ms
Iteration   1: 10.534 ops/ms
Iteration   2: 10.578 ops/ms
Iteration   3: 10.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.604 ±(99.9%) 1.579 ops/ms [Average]
  (min, avg, max) = (10.534, 10.604, 10.701), stdev = 0.087
  CI (99.9%): [9.025, 12.183] (assumes normal distribution)


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
# Warmup Iteration   1: 8.102 ops/ms
# Warmup Iteration   2: 10.764 ops/ms
# Warmup Iteration   3: 11.002 ops/ms
Iteration   1: 11.000 ops/ms
Iteration   2: 11.139 ops/ms
Iteration   3: 10.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.043 ±(99.9%) 1.508 ops/ms [Average]
  (min, avg, max) = (10.991, 11.043, 11.139), stdev = 0.083
  CI (99.9%): [9.536, 12.551] (assumes normal distribution)


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
# Warmup Iteration   1: 7.335 ops/ms
# Warmup Iteration   2: 10.235 ops/ms
# Warmup Iteration   3: 10.739 ops/ms
Iteration   1: 10.556 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.554 ±(99.9%) 0.587 ops/ms [Average]
  (min, avg, max) = (10.521, 10.554, 10.585), stdev = 0.032
  CI (99.9%): [9.968, 11.141] (assumes normal distribution)


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
# Warmup Iteration   1: 6.473 ops/ms
# Warmup Iteration   2: 8.007 ops/ms
# Warmup Iteration   3: 8.253 ops/ms
Iteration   1: 8.196 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 8.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.132 ±(99.9%) 1.042 ops/ms [Average]
  (min, avg, max) = (8.086, 8.132, 8.196), stdev = 0.057
  CI (99.9%): [7.090, 9.174] (assumes normal distribution)


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.003 ms/op
Iteration   1: 3.009 ±(99.9%) 0.003 ms/op
Iteration   2: 3.000 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.023 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (3.000, 3.023, 3.059), stdev = 0.032
  CI (99.9%): [2.441, 3.605] (assumes normal distribution)


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.969 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.005 ms/op
Iteration   1: 2.932 ±(99.9%) 0.002 ms/op
Iteration   2: 2.879 ±(99.9%) 0.003 ms/op
Iteration   3: 2.918 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.910 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (2.879, 2.910, 2.932), stdev = 0.027
  CI (99.9%): [2.409, 3.411] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.002 ms/op
Iteration   1: 3.043 ±(99.9%) 0.003 ms/op
Iteration   2: 3.017 ±(99.9%) 0.003 ms/op
Iteration   3: 3.047 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.036 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (3.017, 3.036, 3.047), stdev = 0.016
  CI (99.9%): [2.743, 3.328] (assumes normal distribution)


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
# Warmup Iteration   1: 4.973 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.011 ms/op
Iteration   1: 3.960 ±(99.9%) 0.006 ms/op
Iteration   2: 3.928 ±(99.9%) 0.015 ms/op
Iteration   3: 3.932 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.940 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (3.928, 3.940, 3.960), stdev = 0.018
  CI (99.9%): [3.619, 4.261] (assumes normal distribution)


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.006 ms/op
Iteration   1: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  7.389 ms/op
                 createUser·p0.9999: 16.212 ms/op
                 createUser·p1.00:   16.679 ms/op

Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  7.999 ms/op
                 createUser·p0.9999: 15.780 ms/op
                 createUser·p1.00:   16.482 ms/op

Iteration   3: 3.094 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  11.846 ms/op
                 createUser·p0.9999: 30.635 ms/op
                 createUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314246
  mean =      3.056 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22751 
    [ 2.500,  5.000) = 289481 
    [ 5.000,  7.500) = 1558 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =     10.191 ms/op
     p(99.9900) =     29.707 ms/op
     p(99.9990) =     32.398 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  6.406 ms/op
                 existUser·p0.9999: 16.485 ms/op
                 existUser·p1.00:   18.645 ms/op

Iteration   2: 2.929 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.311 ms/op
                 existUser·p0.999:  6.892 ms/op
                 existUser·p0.9999: 13.143 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   3: 2.904 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  6.754 ms/op
                 existUser·p0.9999: 16.433 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328784
  mean =      2.918 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3086 
    [ 1.250,  2.500) = 35316 
    [ 2.500,  3.750) = 278796 
    [ 3.750,  5.000) = 10281 
    [ 5.000,  6.250) = 892 
    [ 6.250,  7.500) = 179 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      6.564 ms/op
     p(99.9900) =     16.304 ms/op
     p(99.9990) =     17.874 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
Iteration   1: 3.052 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.137 ms/op
                 getUser·p0.9999: 15.410 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.957 ms/op
                 getUser·p0.9999: 18.069 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.700 ms/op
                 getUser·p0.9999: 20.021 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315698
  mean =      3.042 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17919 
    [ 2.500,  5.000) = 296545 
    [ 5.000,  7.500) = 970 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.941 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     20.508 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 5.341 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.011 ms/op
Iteration   1: 3.916 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  12.212 ms/op
                 listUser·p0.9999: 14.939 ms/op
                 listUser·p1.00:   15.335 ms/op

Iteration   2: 4.010 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.047 ms/op
                 listUser·p0.9999: 23.726 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   3: 3.997 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  21.103 ms/op
                 listUser·p0.9999: 24.968 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241452
  mean =      3.974 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4365 
    [ 2.500,  5.000) = 211808 
    [ 5.000,  7.500) = 23795 
    [ 7.500, 10.000) = 974 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     23.846 ms/op
     p(99.9990) =     25.087 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.604 ± 1.579  ops/ms
ClientGrpc.existUser                       thrpt       3  11.043 ± 1.508  ops/ms
ClientGrpc.getUser                         thrpt       3  10.554 ± 0.587  ops/ms
ClientGrpc.listUser                        thrpt       3   8.132 ± 1.042  ops/ms
ClientGrpc.createUser                       avgt       3   3.023 ± 0.582   ms/op
ClientGrpc.existUser                        avgt       3   2.910 ± 0.501   ms/op
ClientGrpc.getUser                          avgt       3   3.036 ± 0.292   ms/op
ClientGrpc.listUser                         avgt       3   3.940 ± 0.321   ms/op
ClientGrpc.createUser                     sample  314246   3.056 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.806           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.191           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.707           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.539           ms/op
ClientGrpc.existUser                      sample  328784   2.918 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.585           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.564           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.304           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.645           ms/op
ClientGrpc.getUser                        sample  315698   3.042 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.648           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.941           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.383           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.677           ms/op
ClientGrpc.listUser                       sample  241452   3.974 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.816           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.846           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.133           ms/op
