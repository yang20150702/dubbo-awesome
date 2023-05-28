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
# Warmup Iteration   1: 3.519 ops/ms
# Warmup Iteration   2: 7.304 ops/ms
# Warmup Iteration   3: 8.451 ops/ms
Iteration   1: 9.049 ops/ms
Iteration   2: 9.153 ops/ms
Iteration   3: 8.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.064 ±(99.9%) 1.487 ops/ms [Average]
  (min, avg, max) = (8.992, 9.064, 9.153), stdev = 0.081
  CI (99.9%): [7.578, 10.551] (assumes normal distribution)


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
# Warmup Iteration   1: 5.868 ops/ms
# Warmup Iteration   2: 8.796 ops/ms
# Warmup Iteration   3: 9.309 ops/ms
Iteration   1: 9.442 ops/ms
Iteration   2: 9.355 ops/ms
Iteration   3: 9.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.419 ±(99.9%) 1.027 ops/ms [Average]
  (min, avg, max) = (9.355, 9.419, 9.460), stdev = 0.056
  CI (99.9%): [8.393, 10.446] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.711 ops/ms
# Warmup Iteration   2: 8.592 ops/ms
# Warmup Iteration   3: 8.832 ops/ms
Iteration   1: 9.089 ops/ms
Iteration   2: 8.973 ops/ms
Iteration   3: 9.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.091 ±(99.9%) 2.178 ops/ms [Average]
  (min, avg, max) = (8.973, 9.091, 9.211), stdev = 0.119
  CI (99.9%): [6.913, 11.269] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.864 ops/ms
# Warmup Iteration   2: 6.525 ops/ms
# Warmup Iteration   3: 6.872 ops/ms
Iteration   1: 7.043 ops/ms
Iteration   2: 7.083 ops/ms
Iteration   3: 6.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.029 ±(99.9%) 1.118 ops/ms [Average]
  (min, avg, max) = (6.962, 7.029, 7.083), stdev = 0.061
  CI (99.9%): [5.912, 8.147] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.089 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.005 ms/op
Iteration   1: 3.608 ±(99.9%) 0.015 ms/op
Iteration   2: 3.492 ±(99.9%) 0.004 ms/op
Iteration   3: 3.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.522 ±(99.9%) 1.375 ms/op [Average]
  (min, avg, max) = (3.467, 3.522, 3.608), stdev = 0.075
  CI (99.9%): [2.147, 4.898] (assumes normal distribution)


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
# Warmup Iteration   1: 4.717 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.004 ms/op
Iteration   1: 3.429 ±(99.9%) 0.004 ms/op
Iteration   2: 3.291 ±(99.9%) 0.005 ms/op
Iteration   3: 3.317 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.346 ±(99.9%) 1.341 ms/op [Average]
  (min, avg, max) = (3.291, 3.346, 3.429), stdev = 0.074
  CI (99.9%): [2.005, 4.687] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.247 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.003 ms/op
Iteration   1: 3.477 ±(99.9%) 0.004 ms/op
Iteration   2: 3.552 ±(99.9%) 0.005 ms/op
Iteration   3: 3.517 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.515 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (3.477, 3.515, 3.552), stdev = 0.038
  CI (99.9%): [2.827, 4.204] (assumes normal distribution)


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
# Warmup Iteration   1: 6.574 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.867 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.656 ±(99.9%) 0.020 ms/op
Iteration   1: 4.636 ±(99.9%) 0.022 ms/op
Iteration   2: 4.620 ±(99.9%) 0.017 ms/op
Iteration   3: 4.611 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.622 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (4.611, 4.622, 4.636), stdev = 0.013
  CI (99.9%): [4.386, 4.859] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.037 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.009 ms/op
Iteration   1: 3.577 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  9.681 ms/op
                 createUser·p0.9999: 39.260 ms/op
                 createUser·p1.00:   39.911 ms/op

Iteration   2: 3.543 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  8.353 ms/op
                 createUser·p0.9999: 25.916 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   3: 3.544 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.063 ms/op
                 createUser·p0.999:  14.987 ms/op
                 createUser·p0.9999: 31.289 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 270049
  mean =      3.554 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5315 
    [ 2.500,  5.000) = 260747 
    [ 5.000,  7.500) = 3266 
    [ 7.500, 10.000) = 408 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     10.469 ms/op
     p(99.9900) =     38.271 ms/op
     p(99.9990) =     39.846 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


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
# Warmup Iteration   1: 4.877 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.007 ms/op
Iteration   1: 3.333 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 13.360 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   2: 3.354 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  7.165 ms/op
                 existUser·p0.9999: 17.677 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  7.383 ms/op
                 existUser·p0.9999: 33.185 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 286092
  mean =      3.355 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13879 
    [ 2.500,  5.000) = 268686 
    [ 5.000,  7.500) = 3204 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =      7.627 ms/op
     p(99.9900) =     30.028 ms/op
     p(99.9990) =     33.564 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 5.323 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.007 ms/op
Iteration   1: 3.559 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  10.390 ms/op
                 getUser·p0.9999: 28.705 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   2: 3.518 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  12.147 ms/op
                 getUser·p0.9999: 22.381 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   3: 3.574 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  7.118 ms/op
                 getUser·p0.9999: 24.907 ms/op
                 getUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 270297
  mean =      3.550 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8227 
    [ 2.500,  5.000) = 257133 
    [ 5.000,  7.500) = 4562 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     10.109 ms/op
     p(99.9900) =     25.226 ms/op
     p(99.9990) =     28.921 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 6.031 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.994 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.702 ±(99.9%) 0.014 ms/op
Iteration   1: 4.602 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  15.130 ms/op
                 listUser·p0.9999: 16.909 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   2: 4.603 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.442 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.300 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  16.033 ms/op
                 listUser·p0.9999: 23.564 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   3: 4.635 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   6.365 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 32.493 ms/op
                 listUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207912
  mean =      4.613 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 328 
    [ 2.500,  5.000) = 172513 
    [ 5.000,  7.500) = 31146 
    [ 7.500, 10.000) = 3293 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     15.894 ms/op
     p(99.9900) =     31.235 ms/op
     p(99.9990) =     32.927 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.064 ± 1.487  ops/ms
ClientGrpc.existUser                       thrpt       3   9.419 ± 1.027  ops/ms
ClientGrpc.getUser                         thrpt       3   9.091 ± 2.178  ops/ms
ClientGrpc.listUser                        thrpt       3   7.029 ± 1.118  ops/ms
ClientGrpc.createUser                       avgt       3   3.522 ± 1.375   ms/op
ClientGrpc.existUser                        avgt       3   3.346 ± 1.341   ms/op
ClientGrpc.getUser                          avgt       3   3.515 ± 0.689   ms/op
ClientGrpc.listUser                         avgt       3   4.622 ± 0.237   ms/op
ClientGrpc.createUser                     sample  270049   3.554 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.703           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.096           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.469           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          38.271           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          39.911           ms/op
ClientGrpc.existUser                      sample  286092   3.355 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.805           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.627           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.028           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.472           ms/op
ClientGrpc.getUser                        sample  270297   3.550 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.737           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.157           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.109           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.226           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.032           ms/op
ClientGrpc.listUser                       sample  207912   4.613 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.442           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.440           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.398           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.126           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.894           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.235           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.030           ms/op
