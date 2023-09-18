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
# Warmup Iteration   1: 1.812 ops/ms
# Warmup Iteration   2: 4.239 ops/ms
# Warmup Iteration   3: 5.920 ops/ms
Iteration   1: 6.171 ops/ms
Iteration   2: 6.355 ops/ms
Iteration   3: 6.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.307 ±(99.9%) 2.190 ops/ms [Average]
  (min, avg, max) = (6.171, 6.307, 6.396), stdev = 0.120
  CI (99.9%): [4.117, 8.497] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.049 ops/ms
# Warmup Iteration   2: 5.909 ops/ms
# Warmup Iteration   3: 6.422 ops/ms
Iteration   1: 6.616 ops/ms
Iteration   2: 6.678 ops/ms
Iteration   3: 6.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.685 ±(99.9%) 1.340 ops/ms [Average]
  (min, avg, max) = (6.616, 6.685, 6.762), stdev = 0.073
  CI (99.9%): [5.345, 8.026] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.457 ops/ms
# Warmup Iteration   2: 5.671 ops/ms
# Warmup Iteration   3: 6.218 ops/ms
Iteration   1: 6.122 ops/ms
Iteration   2: 6.469 ops/ms
Iteration   3: 6.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.308 ±(99.9%) 3.195 ops/ms [Average]
  (min, avg, max) = (6.122, 6.308, 6.469), stdev = 0.175
  CI (99.9%): [3.113, 9.503] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.851 ops/ms
# Warmup Iteration   2: 4.406 ops/ms
# Warmup Iteration   3: 4.747 ops/ms
Iteration   1: 5.130 ops/ms
Iteration   2: 5.089 ops/ms
Iteration   3: 5.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.082 ±(99.9%) 0.959 ops/ms [Average]
  (min, avg, max) = (5.026, 5.082, 5.130), stdev = 0.053
  CI (99.9%): [4.122, 6.041] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.329 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.282 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.105 ±(99.9%) 0.005 ms/op
Iteration   1: 5.052 ±(99.9%) 0.006 ms/op
Iteration   2: 5.069 ±(99.9%) 0.003 ms/op
Iteration   3: 5.122 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.081 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (5.052, 5.081, 5.122), stdev = 0.037
  CI (99.9%): [4.412, 5.749] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.607 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.152 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.870 ±(99.9%) 0.008 ms/op
Iteration   1: 4.950 ±(99.9%) 0.004 ms/op
Iteration   2: 4.647 ±(99.9%) 0.006 ms/op
Iteration   3: 4.709 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.769 ±(99.9%) 2.922 ms/op [Average]
  (min, avg, max) = (4.647, 4.769, 4.950), stdev = 0.160
  CI (99.9%): [1.847, 7.691] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.240 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.981 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.217 ±(99.9%) 0.004 ms/op
Iteration   1: 4.991 ±(99.9%) 0.005 ms/op
Iteration   2: 5.039 ±(99.9%) 0.004 ms/op
Iteration   3: 5.147 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.059 ±(99.9%) 1.458 ms/op [Average]
  (min, avg, max) = (4.991, 5.059, 5.147), stdev = 0.080
  CI (99.9%): [3.601, 6.517] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.733 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 7.614 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 6.770 ±(99.9%) 0.014 ms/op
Iteration   1: 6.669 ±(99.9%) 0.023 ms/op
Iteration   2: 6.570 ±(99.9%) 0.021 ms/op
Iteration   3: 6.539 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.593 ±(99.9%) 1.241 ms/op [Average]
  (min, avg, max) = (6.539, 6.593, 6.669), stdev = 0.068
  CI (99.9%): [5.352, 7.834] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 8.634 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 5.544 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.179 ±(99.9%) 0.021 ms/op
Iteration   1: 5.053 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   4.825 ms/op
                 createUser·p0.90:   6.570 ms/op
                 createUser·p0.95:   7.455 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  15.112 ms/op
                 createUser·p0.9999: 24.663 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   2: 4.958 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   4.727 ms/op
                 createUser·p0.90:   6.373 ms/op
                 createUser·p0.95:   7.184 ms/op
                 createUser·p0.99:   9.945 ms/op
                 createUser·p0.999:  18.048 ms/op
                 createUser·p0.9999: 26.562 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   3: 5.046 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   4.801 ms/op
                 createUser·p0.90:   6.545 ms/op
                 createUser·p0.95:   7.422 ms/op
                 createUser·p0.99:   11.122 ms/op
                 createUser·p0.999:  20.265 ms/op
                 createUser·p0.9999: 26.781 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 191411
  mean =      5.019 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3362 
    [ 2.500,  5.000) = 108638 
    [ 5.000,  7.500) = 70754 
    [ 7.500, 10.000) = 6425 
    [10.000, 12.500) = 1551 
    [12.500, 15.000) = 411 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.496 ms/op
     p(95.0000) =      7.360 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     17.059 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     27.075 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 7.058 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 4.954 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.617 ±(99.9%) 0.016 ms/op
Iteration   1: 4.512 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.849 ms/op
                 existUser·p0.95:   6.619 ms/op
                 existUser·p0.99:   9.470 ms/op
                 existUser·p0.999:  14.631 ms/op
                 existUser·p0.9999: 17.853 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   2: 4.536 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   5.734 ms/op
                 existUser·p0.95:   6.545 ms/op
                 existUser·p0.99:   9.284 ms/op
                 existUser·p0.999:  16.461 ms/op
                 existUser·p0.9999: 24.958 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   3: 4.660 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   4.456 ms/op
                 existUser·p0.90:   5.865 ms/op
                 existUser·p0.95:   6.537 ms/op
                 existUser·p0.99:   9.011 ms/op
                 existUser·p0.999:  14.172 ms/op
                 existUser·p0.9999: 22.254 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 209965
  mean =      4.568 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6042 
    [ 2.500,  5.000) = 150692 
    [ 5.000,  7.500) = 47974 
    [ 7.500, 10.000) = 3800 
    [10.000, 12.500) = 998 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.562 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     14.681 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     25.880 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.213 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 5.651 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.167 ±(99.9%) 0.020 ms/op
Iteration   1: 5.026 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   4.776 ms/op
                 getUser·p0.90:   6.554 ms/op
                 getUser·p0.95:   7.414 ms/op
                 getUser·p0.99:   10.405 ms/op
                 getUser·p0.999:  14.713 ms/op
                 getUser·p0.9999: 19.576 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   2: 5.199 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   7.045 ms/op
                 getUser·p0.95:   8.135 ms/op
                 getUser·p0.99:   10.928 ms/op
                 getUser·p0.999:  14.361 ms/op
                 getUser·p0.9999: 22.900 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   3: 4.955 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   4.751 ms/op
                 getUser·p0.90:   6.373 ms/op
                 getUser·p0.95:   7.111 ms/op
                 getUser·p0.99:   10.076 ms/op
                 getUser·p0.999:  16.696 ms/op
                 getUser·p0.9999: 24.021 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 189792
  mean =      5.058 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3448 
    [ 2.500,  5.000) = 105984 
    [ 5.000,  7.500) = 70353 
    [ 7.500, 10.000) = 7555 
    [10.000, 12.500) = 1747 
    [12.500, 15.000) = 523 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      6.644 ms/op
     p(95.0000) =      7.578 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     14.946 ms/op
     p(99.9900) =     23.235 ms/op
     p(99.9990) =     24.222 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.484 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 7.128 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.590 ±(99.9%) 0.030 ms/op
Iteration   1: 6.538 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   10.191 ms/op
                 listUser·p0.99:   12.943 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 25.989 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   2: 6.431 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   8.782 ms/op
                 listUser·p0.95:   10.011 ms/op
                 listUser·p0.99:   13.009 ms/op
                 listUser·p0.999:  22.936 ms/op
                 listUser·p0.9999: 28.256 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   3: 6.583 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   6.029 ms/op
                 listUser·p0.90:   9.421 ms/op
                 listUser·p0.95:   10.715 ms/op
                 listUser·p0.99:   14.172 ms/op
                 listUser·p0.999:  24.576 ms/op
                 listUser·p0.9999: 31.921 ms/op
                 listUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 147272
  mean =      6.517 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 26520 
    [ 5.000,  7.500) = 87117 
    [ 7.500, 10.000) = 24737 
    [10.000, 12.500) = 6481 
    [12.500, 15.000) = 1567 
    [15.000, 17.500) = 418 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      6.021 ms/op
     p(90.0000) =      9.044 ms/op
     p(95.0000) =     10.306 ms/op
     p(99.0000) =     13.418 ms/op
     p(99.9000) =     22.568 ms/op
     p(99.9900) =     29.134 ms/op
     p(99.9990) =     32.284 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.307 ± 2.190  ops/ms
ClientGrpc.existUser                       thrpt       3   6.685 ± 1.340  ops/ms
ClientGrpc.getUser                         thrpt       3   6.308 ± 3.195  ops/ms
ClientGrpc.listUser                        thrpt       3   5.082 ± 0.959  ops/ms
ClientGrpc.createUser                       avgt       3   5.081 ± 0.668   ms/op
ClientGrpc.existUser                        avgt       3   4.769 ± 2.922   ms/op
ClientGrpc.getUser                          avgt       3   5.059 ± 1.458   ms/op
ClientGrpc.listUser                         avgt       3   6.593 ± 1.241   ms/op
ClientGrpc.createUser                     sample  191411   5.019 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.067           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.496           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.360           ms/op
ClientGrpc.createUser:createUser·p0.99    sample          10.289           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          17.059           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.509           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.165           ms/op
ClientGrpc.existUser                      sample  209965   4.568 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.059           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.825           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.562           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.224           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.681           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.757           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.444           ms/op
ClientGrpc.getUser                        sample  189792   5.058 ± 0.011   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.053           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.801           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.644           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.578           ms/op
ClientGrpc.getUser:getUser·p0.99          sample          10.617           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.946           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.235           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.281           ms/op
ClientGrpc.listUser                       sample  147272   6.517 ± 0.018   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.462           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           6.021           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           9.044           ms/op
ClientGrpc.listUser:listUser·p0.95        sample          10.306           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          13.418           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.568           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.134           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.408           ms/op
