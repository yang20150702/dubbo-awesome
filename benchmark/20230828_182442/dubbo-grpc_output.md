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
# Warmup Iteration   1: 3.444 ops/ms
# Warmup Iteration   2: 7.309 ops/ms
# Warmup Iteration   3: 8.343 ops/ms
Iteration   1: 8.701 ops/ms
Iteration   2: 8.920 ops/ms
Iteration   3: 9.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.880 ±(99.9%) 2.972 ops/ms [Average]
  (min, avg, max) = (8.701, 8.880, 9.020), stdev = 0.163
  CI (99.9%): [5.908, 11.852] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.344 ops/ms
# Warmup Iteration   2: 9.706 ops/ms
# Warmup Iteration   3: 10.230 ops/ms
Iteration   1: 10.283 ops/ms
Iteration   2: 10.991 ops/ms
Iteration   3: 9.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.355 ±(99.9%) 11.020 ops/ms [Average]
  (min, avg, max) = (9.790, 10.355, 10.991), stdev = 0.604
  CI (99.9%): [≈ 0, 21.375] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.773 ops/ms
# Warmup Iteration   2: 8.467 ops/ms
# Warmup Iteration   3: 9.207 ops/ms
Iteration   1: 9.091 ops/ms
Iteration   2: 9.328 ops/ms
Iteration   3: 9.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.302 ±(99.9%) 3.627 ops/ms [Average]
  (min, avg, max) = (9.091, 9.302, 9.486), stdev = 0.199
  CI (99.9%): [5.675, 12.929] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.071 ops/ms
# Warmup Iteration   2: 7.142 ops/ms
# Warmup Iteration   3: 7.325 ops/ms
Iteration   1: 7.237 ops/ms
Iteration   2: 7.089 ops/ms
Iteration   3: 7.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.111 ±(99.9%) 2.140 ops/ms [Average]
  (min, avg, max) = (7.006, 7.111, 7.237), stdev = 0.117
  CI (99.9%): [4.971, 9.251] (assumes normal distribution)


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
# Warmup Iteration   1: 5.203 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.012 ms/op
Iteration   1: 3.449 ±(99.9%) 0.004 ms/op
Iteration   2: 3.469 ±(99.9%) 0.004 ms/op
Iteration   3: 3.459 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.459 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (3.449, 3.459, 3.469), stdev = 0.010
  CI (99.9%): [3.284, 3.634] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.729 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.003 ms/op
Iteration   1: 3.447 ±(99.9%) 0.003 ms/op
Iteration   2: 3.429 ±(99.9%) 0.002 ms/op
Iteration   3: 3.297 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.391 ±(99.9%) 1.497 ms/op [Average]
  (min, avg, max) = (3.297, 3.391, 3.447), stdev = 0.082
  CI (99.9%): [1.894, 4.888] (assumes normal distribution)


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
# Warmup Iteration   1: 4.663 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.005 ms/op
Iteration   1: 3.493 ±(99.9%) 0.004 ms/op
Iteration   2: 3.517 ±(99.9%) 0.004 ms/op
Iteration   3: 3.436 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.482 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (3.436, 3.482, 3.517), stdev = 0.042
  CI (99.9%): [2.720, 4.244] (assumes normal distribution)


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
# Warmup Iteration   1: 5.973 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.515 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.435 ±(99.9%) 0.007 ms/op
Iteration   1: 4.381 ±(99.9%) 0.012 ms/op
Iteration   2: 4.438 ±(99.9%) 0.021 ms/op
Iteration   3: 4.343 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.387 ±(99.9%) 0.872 ms/op [Average]
  (min, avg, max) = (4.343, 4.387, 4.438), stdev = 0.048
  CI (99.9%): [3.515, 5.259] (assumes normal distribution)


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
# Warmup Iteration   1: 5.104 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.008 ms/op
Iteration   1: 3.470 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  10.874 ms/op
                 createUser·p0.9999: 18.860 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   2: 3.349 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  9.534 ms/op
                 createUser·p0.9999: 23.346 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   3: 3.307 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  8.872 ms/op
                 createUser·p0.9999: 29.568 ms/op
                 createUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 284352
  mean =      3.374 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18450 
    [ 2.500,  5.000) = 261753 
    [ 5.000,  7.500) = 3392 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     10.070 ms/op
     p(99.9900) =     29.215 ms/op
     p(99.9990) =     29.917 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 4.608 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.007 ms/op
Iteration   1: 3.273 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   4.981 ms/op
                 existUser·p0.999:  9.771 ms/op
                 existUser·p0.9999: 20.461 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 3.197 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  7.963 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   3: 3.262 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  10.651 ms/op
                 existUser·p0.9999: 20.644 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 295847
  mean =      3.244 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19479 
    [ 2.500,  5.000) = 273384 
    [ 5.000,  7.500) = 2324 
    [ 7.500, 10.000) = 442 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     23.129 ms/op
     p(99.9990) =     23.989 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 4.801 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.009 ms/op
Iteration   1: 3.506 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.422 ms/op
                 getUser·p0.999:  10.171 ms/op
                 getUser·p0.9999: 36.070 ms/op
                 getUser·p1.00:   37.159 ms/op

Iteration   2: 3.397 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  7.919 ms/op
                 getUser·p0.9999: 25.873 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   3: 3.338 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  7.606 ms/op
                 getUser·p0.9999: 24.328 ms/op
                 getUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 281149
  mean =      3.413 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11504 
    [ 2.500,  5.000) = 265708 
    [ 5.000,  7.500) = 3422 
    [ 7.500, 10.000) = 312 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =      8.534 ms/op
     p(99.9900) =     32.826 ms/op
     p(99.9990) =     37.106 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 6.221 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.841 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.643 ±(99.9%) 0.013 ms/op
Iteration   1: 4.576 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.583 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.652 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  15.075 ms/op
                 listUser·p0.9999: 16.761 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   2: 4.484 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.390 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  16.166 ms/op
                 listUser·p0.9999: 17.837 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 4.628 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.685 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 28.353 ms/op
                 listUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 210330
  mean =      4.562 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 750 
    [ 2.500,  5.000) = 173569 
    [ 5.000,  7.500) = 31453 
    [ 7.500, 10.000) = 3781 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.595 ms/op
     p(99.0000) =      8.280 ms/op
     p(99.9000) =     16.586 ms/op
     p(99.9900) =     26.607 ms/op
     p(99.9990) =     28.990 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score    Error   Units
ClientGrpc.createUser                      thrpt       3   8.880 ±  2.972  ops/ms
ClientGrpc.existUser                       thrpt       3  10.355 ± 11.020  ops/ms
ClientGrpc.getUser                         thrpt       3   9.302 ±  3.627  ops/ms
ClientGrpc.listUser                        thrpt       3   7.111 ±  2.140  ops/ms
ClientGrpc.createUser                       avgt       3   3.459 ±  0.175   ms/op
ClientGrpc.existUser                        avgt       3   3.391 ±  1.497   ms/op
ClientGrpc.getUser                          avgt       3   3.482 ±  0.762   ms/op
ClientGrpc.listUser                         avgt       3   4.387 ±  0.872   ms/op
ClientGrpc.createUser                     sample  284352   3.374 ±  0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.730            ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.342            ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.080            ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.358            ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.325            ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.070            ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.215            ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.212            ms/op
ClientGrpc.existUser                      sample  295847   3.244 ±  0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.752            ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.224            ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.822            ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.076            ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.005            ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.257            ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.129            ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.052            ms/op
ClientGrpc.getUser                        sample  281149   3.413 ±  0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.744            ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.367            ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.035            ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.342            ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.267            ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.534            ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.826            ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.159            ms/op
ClientGrpc.listUser                       sample  210330   4.562 ±  0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.108            ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.383            ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.620            ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.595            ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.280            ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.586            ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.607            ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.098            ms/op
