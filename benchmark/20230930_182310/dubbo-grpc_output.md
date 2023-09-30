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
# Warmup Iteration   1: 3.914 ops/ms
# Warmup Iteration   2: 8.265 ops/ms
# Warmup Iteration   3: 9.536 ops/ms
Iteration   1: 10.088 ops/ms
Iteration   2: 9.935 ops/ms
Iteration   3: 10.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.014 ±(99.9%) 1.403 ops/ms [Average]
  (min, avg, max) = (9.935, 10.014, 10.088), stdev = 0.077
  CI (99.9%): [8.611, 11.417] (assumes normal distribution)


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
# Warmup Iteration   1: 7.173 ops/ms
# Warmup Iteration   2: 9.986 ops/ms
# Warmup Iteration   3: 10.250 ops/ms
Iteration   1: 10.498 ops/ms
Iteration   2: 10.441 ops/ms
Iteration   3: 10.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.427 ±(99.9%) 1.429 ops/ms [Average]
  (min, avg, max) = (10.343, 10.427, 10.498), stdev = 0.078
  CI (99.9%): [8.998, 11.857] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.939 ops/ms
# Warmup Iteration   2: 9.481 ops/ms
# Warmup Iteration   3: 9.903 ops/ms
Iteration   1: 9.974 ops/ms
Iteration   2: 10.007 ops/ms
Iteration   3: 10.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.058 ±(99.9%) 2.154 ops/ms [Average]
  (min, avg, max) = (9.974, 10.058, 10.193), stdev = 0.118
  CI (99.9%): [7.904, 12.212] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.972 ops/ms
# Warmup Iteration   2: 7.689 ops/ms
# Warmup Iteration   3: 7.873 ops/ms
Iteration   1: 7.941 ops/ms
Iteration   2: 8.253 ops/ms
Iteration   3: 8.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.135 ±(99.9%) 3.095 ops/ms [Average]
  (min, avg, max) = (7.941, 8.135, 8.253), stdev = 0.170
  CI (99.9%): [5.041, 11.230] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.753 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.003 ms/op
Iteration   1: 3.233 ±(99.9%) 0.002 ms/op
Iteration   2: 3.204 ±(99.9%) 0.005 ms/op
Iteration   3: 3.172 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.203 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (3.172, 3.203, 3.233), stdev = 0.031
  CI (99.9%): [2.641, 3.765] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.274 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.003 ms/op
Iteration   1: 3.092 ±(99.9%) 0.002 ms/op
Iteration   2: 2.966 ±(99.9%) 0.003 ms/op
Iteration   3: 2.946 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.001 ±(99.9%) 1.441 ms/op [Average]
  (min, avg, max) = (2.946, 3.001, 3.092), stdev = 0.079
  CI (99.9%): [1.560, 4.443] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.562 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.004 ms/op
Iteration   1: 3.204 ±(99.9%) 0.003 ms/op
Iteration   2: 3.149 ±(99.9%) 0.004 ms/op
Iteration   3: 3.168 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.174 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (3.149, 3.174, 3.204), stdev = 0.028
  CI (99.9%): [2.666, 3.682] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.033 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.018 ms/op
Iteration   1: 4.003 ±(99.9%) 0.035 ms/op
Iteration   2: 3.938 ±(99.9%) 0.015 ms/op
Iteration   3: 3.975 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.972 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (3.938, 3.972, 4.003), stdev = 0.033
  CI (99.9%): [3.378, 4.566] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.777 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.008 ms/op
Iteration   1: 3.199 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.724 ms/op
                 createUser·p0.9999: 17.367 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   2: 3.250 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  8.847 ms/op
                 createUser·p0.9999: 23.486 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   3: 3.200 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  13.272 ms/op
                 createUser·p0.9999: 35.259 ms/op
                 createUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298493
  mean =      3.216 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6341 
    [ 2.500,  5.000) = 290110 
    [ 5.000,  7.500) = 1470 
    [ 7.500, 10.000) = 273 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =     10.093 ms/op
     p(99.9900) =     33.527 ms/op
     p(99.9990) =     35.521 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.599 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 3.055 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  7.900 ms/op
                 existUser·p0.9999: 13.822 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.572 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  12.556 ms/op
                 existUser·p0.9999: 17.381 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   3: 2.978 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.743 ms/op
                 existUser·p0.999:  10.896 ms/op
                 existUser·p0.9999: 17.564 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317624
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2057 
    [ 1.250,  2.500) = 20085 
    [ 2.500,  3.750) = 279920 
    [ 3.750,  5.000) = 13508 
    [ 5.000,  6.250) = 978 
    [ 6.250,  7.500) = 491 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =     10.744 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     19.098 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.345 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.007 ms/op
Iteration   1: 3.268 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   5.484 ms/op
                 getUser·p0.999:  12.403 ms/op
                 getUser·p0.9999: 16.214 ms/op
                 getUser·p1.00:   16.663 ms/op

Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.414 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  9.802 ms/op
                 getUser·p0.9999: 28.217 ms/op
                 getUser·p1.00:   29.065 ms/op

Iteration   3: 3.177 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.630 ms/op
                 getUser·p0.999:  9.955 ms/op
                 getUser·p0.9999: 19.005 ms/op
                 getUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297398
  mean =      3.226 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8216 
    [ 2.500,  5.000) = 286690 
    [ 5.000,  7.500) = 1774 
    [ 7.500, 10.000) = 354 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.414 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =     11.141 ms/op
     p(99.9900) =     25.576 ms/op
     p(99.9990) =     28.313 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 6.028 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.011 ms/op
Iteration   1: 4.040 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  13.463 ms/op
                 listUser·p0.9999: 26.753 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   2: 4.018 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  14.867 ms/op
                 listUser·p0.9999: 27.035 ms/op
                 listUser·p1.00:   30.179 ms/op

Iteration   3: 4.043 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237874
  mean =      4.033 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2796 
    [ 2.500,  5.000) = 216492 
    [ 5.000,  7.500) = 16815 
    [ 7.500, 10.000) = 1083 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     14.993 ms/op
     p(99.9900) =     26.825 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.014 ± 1.403  ops/ms
ClientGrpc.existUser                       thrpt       3  10.427 ± 1.429  ops/ms
ClientGrpc.getUser                         thrpt       3  10.058 ± 2.154  ops/ms
ClientGrpc.listUser                        thrpt       3   8.135 ± 3.095  ops/ms
ClientGrpc.createUser                       avgt       3   3.203 ± 0.562   ms/op
ClientGrpc.existUser                        avgt       3   3.001 ± 1.441   ms/op
ClientGrpc.getUser                          avgt       3   3.174 ± 0.508   ms/op
ClientGrpc.listUser                         avgt       3   3.972 ± 0.594   ms/op
ClientGrpc.createUser                     sample  298493   3.216 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.728           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.162           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.093           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.527           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.241           ms/op
ClientGrpc.existUser                      sample  317624   3.020 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.572           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.744           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.465           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.268           ms/op
ClientGrpc.getUser                        sample  297398   3.226 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.414           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.178           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.969           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.141           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.576           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.065           ms/op
ClientGrpc.listUser                       sample  237874   4.033 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.997           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.694           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.111           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.993           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.825           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.372           ms/op
