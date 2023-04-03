# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.415 ops/ms
# Warmup Iteration   2: 7.021 ops/ms
# Warmup Iteration   3: 8.617 ops/ms
Iteration   1: 8.889 ops/ms
Iteration   2: 9.073 ops/ms
Iteration   3: 8.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.978 ±(99.9%) 1.677 ops/ms [Average]
  (min, avg, max) = (8.889, 8.978, 9.073), stdev = 0.092
  CI (99.9%): [7.301, 10.654] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.288 ops/ms
# Warmup Iteration   2: 8.855 ops/ms
# Warmup Iteration   3: 9.493 ops/ms
Iteration   1: 9.524 ops/ms
Iteration   2: 9.453 ops/ms
Iteration   3: 9.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.415 ±(99.9%) 2.403 ops/ms [Average]
  (min, avg, max) = (9.269, 9.415, 9.524), stdev = 0.132
  CI (99.9%): [7.012, 11.818] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.004 ops/ms
# Warmup Iteration   2: 8.459 ops/ms
# Warmup Iteration   3: 8.821 ops/ms
Iteration   1: 8.985 ops/ms
Iteration   2: 8.857 ops/ms
Iteration   3: 9.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.962 ±(99.9%) 1.734 ops/ms [Average]
  (min, avg, max) = (8.857, 8.962, 9.043), stdev = 0.095
  CI (99.9%): [7.227, 10.696] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.655 ops/ms
# Warmup Iteration   2: 6.655 ops/ms
# Warmup Iteration   3: 6.935 ops/ms
Iteration   1: 7.037 ops/ms
Iteration   2: 7.233 ops/ms
Iteration   3: 7.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.115 ±(99.9%) 1.888 ops/ms [Average]
  (min, avg, max) = (7.037, 7.115, 7.233), stdev = 0.103
  CI (99.9%): [5.228, 9.003] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.425 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.007 ms/op
Iteration   1: 3.695 ±(99.9%) 0.003 ms/op
Iteration   2: 3.533 ±(99.9%) 0.003 ms/op
Iteration   3: 3.534 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.587 ±(99.9%) 1.703 ms/op [Average]
  (min, avg, max) = (3.533, 3.587, 3.695), stdev = 0.093
  CI (99.9%): [1.885, 5.290] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.916 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.003 ms/op
Iteration   1: 3.308 ±(99.9%) 0.003 ms/op
Iteration   2: 3.343 ±(99.9%) 0.002 ms/op
Iteration   3: 3.371 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.341 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.308, 3.341, 3.371), stdev = 0.032
  CI (99.9%): [2.761, 3.920] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.043 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.006 ms/op
Iteration   1: 3.533 ±(99.9%) 0.004 ms/op
Iteration   2: 3.533 ±(99.9%) 0.004 ms/op
Iteration   3: 3.526 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.531 ±(99.9%) 0.083 ms/op [Average]
  (min, avg, max) = (3.526, 3.531, 3.533), stdev = 0.005
  CI (99.9%): [3.448, 3.613] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.018 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.787 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.741 ±(99.9%) 0.030 ms/op
Iteration   1: 4.632 ±(99.9%) 0.013 ms/op
Iteration   2: 4.526 ±(99.9%) 0.014 ms/op
Iteration   3: 4.556 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.571 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (4.526, 4.571, 4.632), stdev = 0.055
  CI (99.9%): [3.570, 5.572] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.675 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.009 ms/op
Iteration   1: 3.519 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  9.393 ms/op
                 createUser·p0.9999: 23.396 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.455 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  8.294 ms/op
                 createUser·p0.9999: 16.843 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   3: 3.535 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.459 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  15.097 ms/op
                 createUser·p0.9999: 22.083 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 273912
  mean =      3.502 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7896 
    [ 2.500,  5.000) = 262219 
    [ 5.000,  7.500) = 3203 
    [ 7.500, 10.000) = 321 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =      9.982 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     24.102 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.822 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.008 ms/op
Iteration   1: 3.338 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  8.277 ms/op
                 existUser·p0.9999: 14.239 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   2: 3.373 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   4.839 ms/op
                 existUser·p0.999:  9.719 ms/op
                 existUser·p0.9999: 16.524 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   3: 3.346 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  7.217 ms/op
                 existUser·p0.9999: 16.425 ms/op
                 existUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 286252
  mean =      3.352 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 550 
    [ 1.250,  2.500) = 8720 
    [ 2.500,  3.750) = 236937 
    [ 3.750,  5.000) = 36962 
    [ 5.000,  6.250) = 2148 
    [ 6.250,  7.500) = 523 
    [ 7.500,  8.750) = 182 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.071 ms/op
     p(99.9000) =      8.315 ms/op
     p(99.9900) =     15.976 ms/op
     p(99.9990) =     18.420 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.211 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.008 ms/op
Iteration   1: 3.500 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  8.782 ms/op
                 getUser·p0.9999: 14.657 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   2: 3.544 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  10.994 ms/op
                 getUser·p0.9999: 24.411 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   3: 3.518 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  12.340 ms/op
                 getUser·p0.9999: 20.608 ms/op
                 getUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 272532
  mean =      3.520 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7959 
    [ 2.500,  5.000) = 258726 
    [ 5.000,  7.500) = 5056 
    [ 7.500, 10.000) = 512 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     10.067 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     24.674 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.166 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.948 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.559 ±(99.9%) 0.014 ms/op
Iteration   1: 4.677 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  15.483 ms/op
                 listUser·p0.9999: 17.378 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   2: 4.591 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  18.154 ms/op
                 listUser·p0.9999: 24.936 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   3: 4.608 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.291 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 21.432 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207366
  mean =      4.625 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 311 
    [ 2.500,  5.000) = 166738 
    [ 5.000,  7.500) = 35946 
    [ 7.500, 10.000) = 3650 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.562 ms/op
     p(99.0000) =      8.274 ms/op
     p(99.9000) =     16.526 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.063 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.978 ± 1.677  ops/ms
ClientGrpc.existUser                       thrpt       3   9.415 ± 2.403  ops/ms
ClientGrpc.getUser                         thrpt       3   8.962 ± 1.734  ops/ms
ClientGrpc.listUser                        thrpt       3   7.115 ± 1.888  ops/ms
ClientGrpc.createUser                       avgt       3   3.587 ± 1.703   ms/op
ClientGrpc.existUser                        avgt       3   3.341 ± 0.579   ms/op
ClientGrpc.getUser                          avgt       3   3.531 ± 0.083   ms/op
ClientGrpc.listUser                         avgt       3   4.571 ± 1.001   ms/op
ClientGrpc.createUser                     sample  273912   3.502 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.858           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.457           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.982           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.675           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.183           ms/op
ClientGrpc.existUser                      sample  286252   3.352 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.781           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.854           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.071           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.315           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.976           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.579           ms/op
ClientGrpc.getUser                        sample  272532   3.520 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.529           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.112           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.726           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.067           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.953           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.740           ms/op
ClientGrpc.listUser                       sample  207366   4.625 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.268           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.432           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.274           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.526           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.150           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.166           ms/op
