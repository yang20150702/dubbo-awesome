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
# Warmup Iteration   1: 3.357 ops/ms
# Warmup Iteration   2: 7.582 ops/ms
# Warmup Iteration   3: 8.415 ops/ms
Iteration   1: 8.983 ops/ms
Iteration   2: 9.078 ops/ms
Iteration   3: 9.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.066 ±(99.9%) 1.402 ops/ms [Average]
  (min, avg, max) = (8.983, 9.066, 9.135), stdev = 0.077
  CI (99.9%): [7.663, 10.468] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.428 ops/ms
# Warmup Iteration   2: 8.780 ops/ms
# Warmup Iteration   3: 9.396 ops/ms
Iteration   1: 9.385 ops/ms
Iteration   2: 9.484 ops/ms
Iteration   3: 9.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.509 ±(99.9%) 2.548 ops/ms [Average]
  (min, avg, max) = (9.385, 9.509, 9.660), stdev = 0.140
  CI (99.9%): [6.962, 12.057] (assumes normal distribution)


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
# Warmup Iteration   1: 5.280 ops/ms
# Warmup Iteration   2: 8.495 ops/ms
# Warmup Iteration   3: 9.021 ops/ms
Iteration   1: 8.889 ops/ms
Iteration   2: 9.207 ops/ms
Iteration   3: 9.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.086 ±(99.9%) 3.146 ops/ms [Average]
  (min, avg, max) = (8.889, 9.086, 9.207), stdev = 0.172
  CI (99.9%): [5.940, 12.232] (assumes normal distribution)


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
# Warmup Iteration   1: 4.593 ops/ms
# Warmup Iteration   2: 6.611 ops/ms
# Warmup Iteration   3: 7.096 ops/ms
Iteration   1: 7.071 ops/ms
Iteration   2: 7.130 ops/ms
Iteration   3: 7.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.137 ±(99.9%) 1.257 ops/ms [Average]
  (min, avg, max) = (7.071, 7.137, 7.208), stdev = 0.069
  CI (99.9%): [5.880, 8.393] (assumes normal distribution)


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
# Warmup Iteration   1: 5.060 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.004 ms/op
Iteration   1: 3.537 ±(99.9%) 0.003 ms/op
Iteration   2: 3.501 ±(99.9%) 0.003 ms/op
Iteration   3: 3.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.523 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (3.501, 3.523, 3.537), stdev = 0.019
  CI (99.9%): [3.179, 3.866] (assumes normal distribution)


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.004 ms/op
Iteration   1: 3.349 ±(99.9%) 0.002 ms/op
Iteration   2: 3.316 ±(99.9%) 0.004 ms/op
Iteration   3: 3.344 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.336 ±(99.9%) 0.325 ms/op [Average]
  (min, avg, max) = (3.316, 3.336, 3.349), stdev = 0.018
  CI (99.9%): [3.011, 3.661] (assumes normal distribution)


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
# Warmup Iteration   1: 4.926 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.004 ms/op
Iteration   1: 3.486 ±(99.9%) 0.005 ms/op
Iteration   2: 3.496 ±(99.9%) 0.002 ms/op
Iteration   3: 3.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.486 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (3.476, 3.486, 3.496), stdev = 0.010
  CI (99.9%): [3.302, 3.670] (assumes normal distribution)


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
# Warmup Iteration   1: 6.226 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.896 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.507 ±(99.9%) 0.032 ms/op
Iteration   1: 4.558 ±(99.9%) 0.026 ms/op
Iteration   2: 4.518 ±(99.9%) 0.017 ms/op
Iteration   3: 4.540 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.539 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (4.518, 4.539, 4.558), stdev = 0.020
  CI (99.9%): [4.177, 4.900] (assumes normal distribution)


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
# Warmup Iteration   1: 5.215 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.009 ms/op
Iteration   1: 3.602 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.742 ms/op
                 createUser·p0.999:  11.358 ms/op
                 createUser·p0.9999: 21.958 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 3.521 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.344 ms/op
                 createUser·p0.999:  7.726 ms/op
                 createUser·p0.9999: 14.875 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   3: 3.524 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.095 ms/op
                 createUser·p0.999:  16.783 ms/op
                 createUser·p0.9999: 19.855 ms/op
                 createUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 270678
  mean =      3.548 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6781 
    [ 2.500,  5.000) = 259847 
    [ 5.000,  7.500) = 3344 
    [ 7.500, 10.000) = 367 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     22.194 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 4.685 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.007 ms/op
Iteration   1: 3.385 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  6.786 ms/op
                 existUser·p0.9999: 22.318 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   2: 3.418 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   4.891 ms/op
                 existUser·p0.999:  8.003 ms/op
                 existUser·p0.9999: 15.454 ms/op
                 existUser·p1.00:   15.909 ms/op

Iteration   3: 3.362 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  12.833 ms/op
                 existUser·p0.9999: 20.004 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 283556
  mean =      3.388 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8651 
    [ 2.500,  5.000) = 272764 
    [ 5.000,  7.500) = 1859 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =      7.478 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     22.495 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 4.909 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.008 ms/op
Iteration   1: 3.485 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  8.737 ms/op
                 getUser·p0.9999: 14.327 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   2: 3.546 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  8.729 ms/op
                 getUser·p0.9999: 16.301 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   3: 3.512 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  10.419 ms/op
                 getUser·p0.9999: 18.969 ms/op
                 getUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 272973
  mean =      3.514 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 311 
    [ 1.250,  2.500) = 10394 
    [ 2.500,  3.750) = 186409 
    [ 3.750,  5.000) = 71109 
    [ 5.000,  6.250) = 3689 
    [ 6.250,  7.500) = 589 
    [ 7.500,  8.750) = 168 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      8.979 ms/op
     p(99.9900) =     18.363 ms/op
     p(99.9990) =     19.270 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 6.498 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.805 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.522 ±(99.9%) 0.015 ms/op
Iteration   1: 4.432 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.341 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  25.016 ms/op
                 listUser·p0.9999: 27.914 ms/op
                 listUser·p1.00:   28.934 ms/op

Iteration   2: 4.543 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   7.841 ms/op
                 listUser·p0.999:  21.823 ms/op
                 listUser·p0.9999: 25.656 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   3: 4.533 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.365 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  19.798 ms/op
                 listUser·p0.9999: 28.148 ms/op
                 listUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 213268
  mean =      4.502 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 584 
    [ 2.500,  5.000) = 180538 
    [ 5.000,  7.500) = 29143 
    [ 7.500, 10.000) = 2496 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 127 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.373 ms/op
     p(99.0000) =      7.777 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     27.940 ms/op
     p(99.9990) =     28.818 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.066 ± 1.402  ops/ms
ClientGrpc.existUser                       thrpt       3   9.509 ± 2.548  ops/ms
ClientGrpc.getUser                         thrpt       3   9.086 ± 3.146  ops/ms
ClientGrpc.listUser                        thrpt       3   7.137 ± 1.257  ops/ms
ClientGrpc.createUser                       avgt       3   3.523 ± 0.344   ms/op
ClientGrpc.existUser                        avgt       3   3.336 ± 0.325   ms/op
ClientGrpc.getUser                          avgt       3   3.486 ± 0.184   ms/op
ClientGrpc.listUser                         avgt       3   4.539 ± 0.362   ms/op
ClientGrpc.createUser                     sample  270678   3.548 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.873           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.133           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.423           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.764           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.660           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.315           ms/op
ClientGrpc.existUser                      sample  283556   3.388 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.634           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.478           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.627           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.643           ms/op
ClientGrpc.getUser                        sample  272973   3.514 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.788           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.153           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.979           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.363           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.628           ms/op
ClientGrpc.listUser                       sample  213268   4.502 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.002           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.334           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.373           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.777           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          23.855           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.940           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.934           ms/op
