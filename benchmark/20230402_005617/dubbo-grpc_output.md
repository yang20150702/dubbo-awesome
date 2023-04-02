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
# Warmup Iteration   1: 3.189 ops/ms
# Warmup Iteration   2: 7.086 ops/ms
# Warmup Iteration   3: 8.463 ops/ms
Iteration   1: 8.740 ops/ms
Iteration   2: 8.887 ops/ms
Iteration   3: 8.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.864 ±(99.9%) 2.097 ops/ms [Average]
  (min, avg, max) = (8.740, 8.864, 8.967), stdev = 0.115
  CI (99.9%): [6.767, 10.962] (assumes normal distribution)


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
# Warmup Iteration   1: 5.707 ops/ms
# Warmup Iteration   2: 8.865 ops/ms
# Warmup Iteration   3: 9.221 ops/ms
Iteration   1: 9.337 ops/ms
Iteration   2: 9.390 ops/ms
Iteration   3: 9.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.385 ±(99.9%) 0.823 ops/ms [Average]
  (min, avg, max) = (9.337, 9.385, 9.427), stdev = 0.045
  CI (99.9%): [8.562, 10.208] (assumes normal distribution)


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
# Warmup Iteration   1: 5.448 ops/ms
# Warmup Iteration   2: 8.343 ops/ms
# Warmup Iteration   3: 8.538 ops/ms
Iteration   1: 8.737 ops/ms
Iteration   2: 8.850 ops/ms
Iteration   3: 9.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.866 ±(99.9%) 2.499 ops/ms [Average]
  (min, avg, max) = (8.737, 8.866, 9.010), stdev = 0.137
  CI (99.9%): [6.367, 11.365] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.845 ops/ms
# Warmup Iteration   2: 6.352 ops/ms
# Warmup Iteration   3: 6.810 ops/ms
Iteration   1: 6.938 ops/ms
Iteration   2: 6.972 ops/ms
Iteration   3: 7.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.995 ±(99.9%) 1.316 ops/ms [Average]
  (min, avg, max) = (6.938, 6.995, 7.076), stdev = 0.072
  CI (99.9%): [5.679, 8.312] (assumes normal distribution)


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
# Warmup Iteration   1: 5.439 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.008 ms/op
Iteration   1: 3.596 ±(99.9%) 0.002 ms/op
Iteration   2: 3.442 ±(99.9%) 0.004 ms/op
Iteration   3: 3.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.513 ±(99.9%) 1.418 ms/op [Average]
  (min, avg, max) = (3.442, 3.513, 3.596), stdev = 0.078
  CI (99.9%): [2.095, 4.932] (assumes normal distribution)


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.003 ms/op
Iteration   1: 3.410 ±(99.9%) 0.003 ms/op
Iteration   2: 3.430 ±(99.9%) 0.002 ms/op
Iteration   3: 3.372 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.404 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (3.372, 3.404, 3.430), stdev = 0.030
  CI (99.9%): [2.863, 3.944] (assumes normal distribution)


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
# Warmup Iteration   1: 5.313 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.003 ms/op
Iteration   1: 3.507 ±(99.9%) 0.005 ms/op
Iteration   2: 3.655 ±(99.9%) 0.002 ms/op
Iteration   3: 3.534 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.565 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (3.507, 3.565, 3.655), stdev = 0.079
  CI (99.9%): [2.124, 5.007] (assumes normal distribution)


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
# Warmup Iteration   1: 6.783 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.802 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.570 ±(99.9%) 0.030 ms/op
Iteration   1: 4.648 ±(99.9%) 0.019 ms/op
Iteration   2: 4.625 ±(99.9%) 0.018 ms/op
Iteration   3: 4.583 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.619 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (4.583, 4.619, 4.648), stdev = 0.033
  CI (99.9%): [4.012, 5.225] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.001 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.007 ms/op
Iteration   1: 3.463 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  7.677 ms/op
                 createUser·p0.9999: 15.987 ms/op
                 createUser·p1.00:   16.564 ms/op

Iteration   2: 3.602 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.219 ms/op
                 createUser·p0.999:  13.515 ms/op
                 createUser·p0.9999: 25.202 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.470 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  16.974 ms/op
                 createUser·p0.9999: 19.614 ms/op
                 createUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 273514
  mean =      3.511 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17122 
    [ 2.500,  5.000) = 252977 
    [ 5.000,  7.500) = 2932 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.153 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     24.728 ms/op
     p(99.9990) =     25.330 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 4.841 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.006 ms/op
Iteration   1: 3.399 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   4.866 ms/op
                 existUser·p0.999:  8.884 ms/op
                 existUser·p0.9999: 18.590 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   2: 3.454 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  8.349 ms/op
                 existUser·p0.9999: 27.623 ms/op
                 existUser·p1.00:   28.508 ms/op

Iteration   3: 3.457 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  11.198 ms/op
                 existUser·p0.9999: 20.545 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279324
  mean =      3.436 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9315 
    [ 2.500,  5.000) = 267106 
    [ 5.000,  7.500) = 2420 
    [ 7.500, 10.000) = 227 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.046 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     28.443 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 5.304 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.008 ms/op
Iteration   1: 3.568 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  8.594 ms/op
                 getUser·p0.9999: 14.861 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   2: 3.599 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.568 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  7.864 ms/op
                 getUser·p0.9999: 25.431 ms/op
                 getUser·p1.00:   26.247 ms/op

Iteration   3: 3.558 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  9.343 ms/op
                 getUser·p0.9999: 18.908 ms/op
                 getUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268523
  mean =      3.575 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8352 
    [ 2.500,  5.000) = 256279 
    [ 5.000,  7.500) = 3451 
    [ 7.500, 10.000) = 271 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     24.777 ms/op
     p(99.9990) =     26.169 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 6.575 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.883 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.692 ±(99.9%) 0.013 ms/op
Iteration   1: 4.668 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.775 ms/op
                 listUser·p0.95:   6.488 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  16.597 ms/op
                 listUser·p0.9999: 27.731 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 4.684 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.759 ms/op
                 listUser·p0.95:   6.775 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  15.949 ms/op
                 listUser·p0.9999: 19.940 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   3: 4.485 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   8.115 ms/op
                 listUser·p0.999:  21.981 ms/op
                 listUser·p0.9999: 28.503 ms/op
                 listUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208220
  mean =      4.610 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 370 
    [ 2.500,  5.000) = 170467 
    [ 5.000,  7.500) = 33347 
    [ 7.500, 10.000) = 3452 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.455 ms/op
     p(99.0000) =      8.159 ms/op
     p(99.9000) =     18.237 ms/op
     p(99.9900) =     27.329 ms/op
     p(99.9990) =     29.388 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.864 ± 2.097  ops/ms
ClientGrpc.existUser                       thrpt       3   9.385 ± 0.823  ops/ms
ClientGrpc.getUser                         thrpt       3   8.866 ± 2.499  ops/ms
ClientGrpc.listUser                        thrpt       3   6.995 ± 1.316  ops/ms
ClientGrpc.createUser                       avgt       3   3.513 ± 1.418   ms/op
ClientGrpc.existUser                        avgt       3   3.404 ± 0.540   ms/op
ClientGrpc.getUser                          avgt       3   3.565 ± 1.442   ms/op
ClientGrpc.listUser                         avgt       3   4.619 ± 0.606   ms/op
ClientGrpc.createUser                     sample  273514   3.511 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.731           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.186           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.153           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.813           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.728           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.428           ms/op
ClientGrpc.existUser                      sample  279324   3.436 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.761           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.969           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.046           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.388           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.673           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.508           ms/op
ClientGrpc.getUser                        sample  268523   3.575 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.796           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.308           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.503           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.777           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.247           ms/op
ClientGrpc.listUser                       sample  208220   4.610 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.096           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.455           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.159           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.237           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.329           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.426           ms/op
