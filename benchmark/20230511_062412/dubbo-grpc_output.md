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
# Warmup Iteration   1: 3.554 ops/ms
# Warmup Iteration   2: 7.071 ops/ms
# Warmup Iteration   3: 8.648 ops/ms
Iteration   1: 9.150 ops/ms
Iteration   2: 9.371 ops/ms
Iteration   3: 9.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.262 ±(99.9%) 2.012 ops/ms [Average]
  (min, avg, max) = (9.150, 9.262, 9.371), stdev = 0.110
  CI (99.9%): [7.250, 11.274] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.825 ops/ms
# Warmup Iteration   2: 8.782 ops/ms
# Warmup Iteration   3: 9.417 ops/ms
Iteration   1: 9.539 ops/ms
Iteration   2: 9.535 ops/ms
Iteration   3: 9.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.543 ±(99.9%) 0.206 ops/ms [Average]
  (min, avg, max) = (9.535, 9.543, 9.556), stdev = 0.011
  CI (99.9%): [9.337, 9.750] (assumes normal distribution)


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
# Warmup Iteration   1: 5.638 ops/ms
# Warmup Iteration   2: 8.240 ops/ms
# Warmup Iteration   3: 9.031 ops/ms
Iteration   1: 9.115 ops/ms
Iteration   2: 9.251 ops/ms
Iteration   3: 9.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.191 ±(99.9%) 1.263 ops/ms [Average]
  (min, avg, max) = (9.115, 9.191, 9.251), stdev = 0.069
  CI (99.9%): [7.927, 10.454] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.382 ops/ms
# Warmup Iteration   2: 6.827 ops/ms
# Warmup Iteration   3: 7.129 ops/ms
Iteration   1: 7.104 ops/ms
Iteration   2: 7.169 ops/ms
Iteration   3: 7.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.177 ±(99.9%) 1.406 ops/ms [Average]
  (min, avg, max) = (7.104, 7.177, 7.257), stdev = 0.077
  CI (99.9%): [5.771, 8.583] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.217 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.012 ms/op
Iteration   1: 3.383 ±(99.9%) 0.006 ms/op
Iteration   2: 3.404 ±(99.9%) 0.003 ms/op
Iteration   3: 3.417 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.402 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (3.383, 3.402, 3.417), stdev = 0.017
  CI (99.9%): [3.095, 3.708] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.762 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.416 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.002 ms/op
Iteration   1: 3.273 ±(99.9%) 0.003 ms/op
Iteration   2: 3.277 ±(99.9%) 0.003 ms/op
Iteration   3: 3.269 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.273 ±(99.9%) 0.073 ms/op [Average]
  (min, avg, max) = (3.269, 3.273, 3.277), stdev = 0.004
  CI (99.9%): [3.200, 3.346] (assumes normal distribution)


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
# Warmup Iteration   1: 5.161 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.006 ms/op
Iteration   1: 3.488 ±(99.9%) 0.002 ms/op
Iteration   2: 3.527 ±(99.9%) 0.004 ms/op
Iteration   3: 3.414 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.476 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.414, 3.476, 3.527), stdev = 0.058
  CI (99.9%): [2.425, 4.527] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.583 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.562 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.384 ±(99.9%) 0.012 ms/op
Iteration   1: 4.462 ±(99.9%) 0.007 ms/op
Iteration   2: 4.507 ±(99.9%) 0.020 ms/op
Iteration   3: 4.448 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.472 ±(99.9%) 0.555 ms/op [Average]
  (min, avg, max) = (4.448, 4.472, 4.507), stdev = 0.030
  CI (99.9%): [3.917, 5.028] (assumes normal distribution)


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
# Warmup Iteration   1: 4.860 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.007 ms/op
Iteration   1: 3.485 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  9.435 ms/op
                 createUser·p0.9999: 17.257 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   2: 3.393 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.046 ms/op
                 createUser·p0.999:  12.632 ms/op
                 createUser·p0.9999: 16.115 ms/op
                 createUser·p1.00:   16.564 ms/op

Iteration   3: 3.409 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  9.873 ms/op
                 createUser·p0.9999: 18.579 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 280077
  mean =      3.428 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 322 
    [ 1.250,  2.500) = 11932 
    [ 2.500,  3.750) = 198118 
    [ 3.750,  5.000) = 66287 
    [ 5.000,  6.250) = 2472 
    [ 6.250,  7.500) = 390 
    [ 7.500,  8.750) = 172 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.122 ms/op
     p(99.9000) =     10.304 ms/op
     p(99.9900) =     18.120 ms/op
     p(99.9990) =     18.966 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 4.703 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.007 ms/op
Iteration   1: 3.331 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  13.108 ms/op
                 existUser·p0.9999: 21.116 ms/op
                 existUser·p1.00:   21.463 ms/op

Iteration   2: 3.198 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  5.530 ms/op
                 existUser·p0.9999: 15.139 ms/op
                 existUser·p1.00:   15.745 ms/op

Iteration   3: 3.239 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  6.922 ms/op
                 existUser·p0.9999: 18.526 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 294735
  mean =      3.255 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14082 
    [ 2.500,  5.000) = 278914 
    [ 5.000,  7.500) = 1517 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      6.767 ms/op
     p(99.9900) =     20.661 ms/op
     p(99.9990) =     21.334 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.925 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.008 ms/op
Iteration   1: 3.438 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  10.748 ms/op
                 getUser·p0.9999: 16.363 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   2: 3.331 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  11.058 ms/op
                 getUser·p0.9999: 18.743 ms/op
                 getUser·p1.00:   19.038 ms/op

Iteration   3: 3.248 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.945 ms/op
                 getUser·p0.999:  6.878 ms/op
                 getUser·p0.9999: 20.873 ms/op
                 getUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 287450
  mean =      3.337 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17582 
    [ 2.500,  5.000) = 265992 
    [ 5.000,  7.500) = 3494 
    [ 7.500, 10.000) = 155 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =      8.394 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 6.114 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.439 ±(99.9%) 0.013 ms/op
Iteration   1: 4.298 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   4.162 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  14.037 ms/op
                 listUser·p0.9999: 21.415 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   2: 4.442 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   4.268 ms/op
                 listUser·p0.90:   5.644 ms/op
                 listUser·p0.95:   6.496 ms/op
                 listUser·p0.99:   7.906 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 4.398 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.631 ms/op
                 listUser·p0.50:   4.268 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.283 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 21.192 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 219218
  mean =      4.379 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 831 
    [ 2.500,  5.000) = 186744 
    [ 5.000,  7.500) = 28641 
    [ 7.500, 10.000) = 2488 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      6.308 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     15.561 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.262 ± 2.012  ops/ms
ClientGrpc.existUser                       thrpt       3   9.543 ± 0.206  ops/ms
ClientGrpc.getUser                         thrpt       3   9.191 ± 1.263  ops/ms
ClientGrpc.listUser                        thrpt       3   7.177 ± 1.406  ops/ms
ClientGrpc.createUser                       avgt       3   3.402 ± 0.307   ms/op
ClientGrpc.existUser                        avgt       3   3.273 ± 0.073   ms/op
ClientGrpc.getUser                          avgt       3   3.476 ± 1.051   ms/op
ClientGrpc.listUser                         avgt       3   4.472 ± 0.555   ms/op
ClientGrpc.createUser                     sample  280077   3.428 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.715           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.383           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.149           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.122           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.304           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.120           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.104           ms/op
ClientGrpc.existUser                      sample  294735   3.255 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.670           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.228           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.035           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.686           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.767           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.661           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.463           ms/op
ClientGrpc.getUser                        sample  287450   3.337 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.700           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.305           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.251           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.394           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.842           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.627           ms/op
ClientGrpc.listUser                       sample  219218   4.379 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.631           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.227           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.308           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.561           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.135           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.725           ms/op
