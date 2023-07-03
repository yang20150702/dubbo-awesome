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
# Warmup Iteration   1: 3.565 ops/ms
# Warmup Iteration   2: 7.198 ops/ms
# Warmup Iteration   3: 8.452 ops/ms
Iteration   1: 9.017 ops/ms
Iteration   2: 9.029 ops/ms
Iteration   3: 9.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.107 ±(99.9%) 2.659 ops/ms [Average]
  (min, avg, max) = (9.017, 9.107, 9.275), stdev = 0.146
  CI (99.9%): [6.448, 11.766] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.168 ops/ms
# Warmup Iteration   2: 8.915 ops/ms
# Warmup Iteration   3: 9.433 ops/ms
Iteration   1: 9.436 ops/ms
Iteration   2: 9.172 ops/ms
Iteration   3: 9.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.360 ±(99.9%) 2.986 ops/ms [Average]
  (min, avg, max) = (9.172, 9.360, 9.471), stdev = 0.164
  CI (99.9%): [6.374, 12.346] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.633 ops/ms
# Warmup Iteration   2: 8.502 ops/ms
# Warmup Iteration   3: 8.811 ops/ms
Iteration   1: 8.997 ops/ms
Iteration   2: 9.018 ops/ms
Iteration   3: 9.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.023 ±(99.9%) 0.528 ops/ms [Average]
  (min, avg, max) = (8.997, 9.023, 9.054), stdev = 0.029
  CI (99.9%): [8.495, 9.551] (assumes normal distribution)


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
# Warmup Iteration   1: 4.595 ops/ms
# Warmup Iteration   2: 6.670 ops/ms
# Warmup Iteration   3: 6.964 ops/ms
Iteration   1: 6.982 ops/ms
Iteration   2: 7.372 ops/ms
Iteration   3: 7.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.169 ±(99.9%) 3.574 ops/ms [Average]
  (min, avg, max) = (6.982, 7.169, 7.372), stdev = 0.196
  CI (99.9%): [3.595, 10.742] (assumes normal distribution)


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
# Warmup Iteration   1: 5.233 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.023 ms/op
Iteration   1: 3.617 ±(99.9%) 0.003 ms/op
Iteration   2: 3.480 ±(99.9%) 0.003 ms/op
Iteration   3: 3.536 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.544 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (3.480, 3.544, 3.617), stdev = 0.069
  CI (99.9%): [2.293, 4.795] (assumes normal distribution)


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
# Warmup Iteration   1: 4.724 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.003 ms/op
Iteration   1: 3.344 ±(99.9%) 0.003 ms/op
Iteration   2: 3.332 ±(99.9%) 0.003 ms/op
Iteration   3: 3.287 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.321 ±(99.9%) 0.543 ms/op [Average]
  (min, avg, max) = (3.287, 3.321, 3.344), stdev = 0.030
  CI (99.9%): [2.778, 3.864] (assumes normal distribution)


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
# Warmup Iteration   1: 5.177 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.005 ms/op
Iteration   1: 3.544 ±(99.9%) 0.005 ms/op
Iteration   2: 3.561 ±(99.9%) 0.003 ms/op
Iteration   3: 3.531 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.545 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (3.531, 3.545, 3.561), stdev = 0.015
  CI (99.9%): [3.264, 3.826] (assumes normal distribution)


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
# Warmup Iteration   1: 6.624 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.847 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.476 ±(99.9%) 0.014 ms/op
Iteration   1: 4.562 ±(99.9%) 0.059 ms/op
Iteration   2: 4.492 ±(99.9%) 0.019 ms/op
Iteration   3: 4.434 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.496 ±(99.9%) 1.170 ms/op [Average]
  (min, avg, max) = (4.434, 4.496, 4.562), stdev = 0.064
  CI (99.9%): [3.326, 5.666] (assumes normal distribution)


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
# Warmup Iteration   1: 5.363 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.008 ms/op
Iteration   1: 3.512 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  8.361 ms/op
                 createUser·p0.9999: 14.693 ms/op
                 createUser·p1.00:   15.024 ms/op

Iteration   2: 3.553 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.038 ms/op
                 createUser·p0.999:  10.567 ms/op
                 createUser·p0.9999: 15.679 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   3: 3.527 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  12.084 ms/op
                 createUser·p0.9999: 25.882 ms/op
                 createUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 271745
  mean =      3.530 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6443 
    [ 2.500,  5.000) = 261377 
    [ 5.000,  7.500) = 3460 
    [ 7.500, 10.000) = 161 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     10.707 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     26.078 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 4.661 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.008 ms/op
Iteration   1: 3.360 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.144 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  6.010 ms/op
                 existUser·p0.9999: 14.531 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   2: 3.347 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   4.841 ms/op
                 existUser·p0.999:  7.261 ms/op
                 existUser·p0.9999: 28.377 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   3: 3.383 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   4.907 ms/op
                 existUser·p0.999:  12.345 ms/op
                 existUser·p0.9999: 19.303 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 285489
  mean =      3.363 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11790 
    [ 2.500,  5.000) = 271482 
    [ 5.000,  7.500) = 1926 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      7.582 ms/op
     p(99.9900) =     26.655 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 4.977 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.007 ms/op
Iteration   1: 3.587 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  7.732 ms/op
                 getUser·p0.9999: 13.518 ms/op
                 getUser·p1.00:   13.648 ms/op

Iteration   2: 3.550 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  13.777 ms/op
                 getUser·p0.9999: 16.678 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   3: 3.546 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  8.174 ms/op
                 getUser·p0.9999: 16.776 ms/op
                 getUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 269471
  mean =      3.561 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 7614 
    [ 2.500,  3.750) = 177811 
    [ 3.750,  5.000) = 79516 
    [ 5.000,  6.250) = 3466 
    [ 6.250,  7.500) = 442 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     10.617 ms/op
     p(99.9900) =     16.500 ms/op
     p(99.9990) =     17.414 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 6.130 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.685 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.734 ±(99.9%) 0.014 ms/op
Iteration   1: 4.575 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.619 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 16.942 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   2: 4.601 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  16.471 ms/op
                 listUser·p0.9999: 19.141 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 4.642 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  20.520 ms/op
                 listUser·p0.9999: 29.662 ms/op
                 listUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208376
  mean =      4.606 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 337 
    [ 2.500,  5.000) = 168927 
    [ 5.000,  7.500) = 34817 
    [ 7.500, 10.000) = 3697 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.996 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     15.690 ms/op
     p(99.9900) =     28.382 ms/op
     p(99.9990) =     29.950 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.107 ± 2.659  ops/ms
ClientGrpc.existUser                       thrpt       3   9.360 ± 2.986  ops/ms
ClientGrpc.getUser                         thrpt       3   9.023 ± 0.528  ops/ms
ClientGrpc.listUser                        thrpt       3   7.169 ± 3.574  ops/ms
ClientGrpc.createUser                       avgt       3   3.544 ± 1.251   ms/op
ClientGrpc.existUser                        avgt       3   3.321 ± 0.543   ms/op
ClientGrpc.getUser                          avgt       3   3.545 ± 0.281   ms/op
ClientGrpc.listUser                         avgt       3   4.496 ± 1.170   ms/op
ClientGrpc.createUser                     sample  271745   3.530 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.891           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.498           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.121           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.707           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.822           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.149           ms/op
ClientGrpc.existUser                      sample  285489   3.363 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.763           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.833           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.582           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.655           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.410           ms/op
ClientGrpc.getUser                        sample  269471   3.561 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.786           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.141           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.617           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.500           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.022           ms/op
ClientGrpc.listUser                       sample  208376   4.606 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.996           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.424           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.126           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.690           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.382           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.048           ms/op
