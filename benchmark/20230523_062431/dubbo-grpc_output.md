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
# Warmup Iteration   1: 3.854 ops/ms
# Warmup Iteration   2: 8.554 ops/ms
# Warmup Iteration   3: 9.066 ops/ms
Iteration   1: 9.676 ops/ms
Iteration   2: 10.428 ops/ms
Iteration   3: 10.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.153 ±(99.9%) 7.576 ops/ms [Average]
  (min, avg, max) = (9.676, 10.153, 10.428), stdev = 0.415
  CI (99.9%): [2.577, 17.730] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.929 ops/ms
# Warmup Iteration   2: 9.954 ops/ms
# Warmup Iteration   3: 10.906 ops/ms
Iteration   1: 9.708 ops/ms
Iteration   2: 10.579 ops/ms
Iteration   3: 10.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.220 ±(99.9%) 8.310 ops/ms [Average]
  (min, avg, max) = (9.708, 10.220, 10.579), stdev = 0.456
  CI (99.9%): [1.910, 18.531] (assumes normal distribution)


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
# Warmup Iteration   1: 6.323 ops/ms
# Warmup Iteration   2: 9.904 ops/ms
# Warmup Iteration   3: 9.694 ops/ms
Iteration   1: 9.575 ops/ms
Iteration   2: 9.352 ops/ms
Iteration   3: 9.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.611 ±(99.9%) 5.095 ops/ms [Average]
  (min, avg, max) = (9.352, 9.611, 9.907), stdev = 0.279
  CI (99.9%): [4.516, 14.706] (assumes normal distribution)


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
# Warmup Iteration   1: 5.880 ops/ms
# Warmup Iteration   2: 7.317 ops/ms
# Warmup Iteration   3: 7.665 ops/ms
Iteration   1: 7.536 ops/ms
Iteration   2: 7.434 ops/ms
Iteration   3: 7.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.486 ±(99.9%) 0.928 ops/ms [Average]
  (min, avg, max) = (7.434, 7.486, 7.536), stdev = 0.051
  CI (99.9%): [6.558, 8.414] (assumes normal distribution)


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
# Warmup Iteration   1: 4.827 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.004 ms/op
Iteration   1: 3.427 ±(99.9%) 0.002 ms/op
Iteration   2: 3.429 ±(99.9%) 0.004 ms/op
Iteration   3: 3.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.450 ±(99.9%) 0.711 ms/op [Average]
  (min, avg, max) = (3.427, 3.450, 3.495), stdev = 0.039
  CI (99.9%): [2.739, 4.161] (assumes normal distribution)


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.002 ms/op
Iteration   1: 3.193 ±(99.9%) 0.002 ms/op
Iteration   2: 3.174 ±(99.9%) 0.002 ms/op
Iteration   3: 3.274 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.213 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (3.174, 3.213, 3.274), stdev = 0.053
  CI (99.9%): [2.248, 4.179] (assumes normal distribution)


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
# Warmup Iteration   1: 5.106 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.432 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.005 ms/op
Iteration   1: 3.393 ±(99.9%) 0.004 ms/op
Iteration   2: 3.306 ±(99.9%) 0.004 ms/op
Iteration   3: 3.311 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.337 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (3.306, 3.337, 3.393), stdev = 0.049
  CI (99.9%): [2.449, 4.224] (assumes normal distribution)


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
# Warmup Iteration   1: 5.777 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.612 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.022 ms/op
Iteration   1: 4.320 ±(99.9%) 0.018 ms/op
Iteration   2: 4.257 ±(99.9%) 0.008 ms/op
Iteration   3: 4.157 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.245 ±(99.9%) 1.506 ms/op [Average]
  (min, avg, max) = (4.157, 4.245, 4.320), stdev = 0.083
  CI (99.9%): [2.739, 5.750] (assumes normal distribution)


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
# Warmup Iteration   1: 4.988 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.008 ms/op
Iteration   1: 3.478 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  7.283 ms/op
                 createUser·p0.9999: 13.556 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   2: 3.372 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  7.826 ms/op
                 createUser·p0.9999: 18.678 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   3: 3.298 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  11.169 ms/op
                 createUser·p0.9999: 17.855 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 283784
  mean =      3.381 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 5394 
    [ 2.500,  3.750) = 231021 
    [ 3.750,  5.000) = 45044 
    [ 5.000,  6.250) = 1549 
    [ 6.250,  7.500) = 283 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =     18.325 ms/op
     p(99.9990) =     18.994 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.007 ms/op
Iteration   1: 3.168 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  7.349 ms/op
                 existUser·p0.9999: 16.279 ms/op
                 existUser·p1.00:   16.630 ms/op

Iteration   2: 3.153 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  9.585 ms/op
                 existUser·p0.9999: 15.038 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   3: 3.214 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  9.372 ms/op
                 existUser·p0.9999: 30.705 ms/op
                 existUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 301988
  mean =      3.178 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10819 
    [ 2.500,  5.000) = 289110 
    [ 5.000,  7.500) = 1625 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     29.157 ms/op
     p(99.9990) =     31.291 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 4.909 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.007 ms/op
Iteration   1: 3.304 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.374 ms/op
                 getUser·p0.999:  8.785 ms/op
                 getUser·p0.9999: 14.609 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.924 ms/op
                 getUser·p0.9999: 14.139 ms/op
                 getUser·p1.00:   15.958 ms/op

Iteration   3: 3.108 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.536 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.578 ms/op
                 getUser·p0.9999: 32.604 ms/op
                 getUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301308
  mean =      3.184 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22375 
    [ 2.500,  5.000) = 275938 
    [ 5.000,  7.500) = 2630 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.997 ms/op
     p(99.9000) =      7.960 ms/op
     p(99.9900) =     31.982 ms/op
     p(99.9990) =     32.899 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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
# Warmup Iteration   1: 5.779 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.011 ms/op
Iteration   1: 4.397 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   4.227 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.357 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  15.346 ms/op
                 listUser·p0.9999: 21.814 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 4.032 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  16.521 ms/op
                 listUser·p0.9999: 21.245 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   3: 4.052 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  16.221 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231094
  mean =      4.154 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2158 
    [ 2.500,  5.000) = 201340 
    [ 5.000,  7.500) = 25528 
    [ 7.500, 10.000) = 1600 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     16.301 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     22.504 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.153 ± 7.576  ops/ms
ClientGrpc.existUser                       thrpt       3  10.220 ± 8.310  ops/ms
ClientGrpc.getUser                         thrpt       3   9.611 ± 5.095  ops/ms
ClientGrpc.listUser                        thrpt       3   7.486 ± 0.928  ops/ms
ClientGrpc.createUser                       avgt       3   3.450 ± 0.711   ms/op
ClientGrpc.existUser                        avgt       3   3.213 ± 0.966   ms/op
ClientGrpc.getUser                          avgt       3   3.337 ± 0.887   ms/op
ClientGrpc.listUser                         avgt       3   4.245 ± 1.506   ms/op
ClientGrpc.createUser                     sample  283784   3.381 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.582           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.346           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.149           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.833           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.176           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.325           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.202           ms/op
ClientGrpc.existUser                      sample  301988   3.178 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.715           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.158           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.880           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.157           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.359           ms/op
ClientGrpc.getUser                        sample  301308   3.184 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.536           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.154           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.990           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.997           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.960           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.982           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.096           ms/op
ClientGrpc.listUser                       sample  231094   4.154 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.938           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.002           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.397           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.301           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.627           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.610           ms/op
