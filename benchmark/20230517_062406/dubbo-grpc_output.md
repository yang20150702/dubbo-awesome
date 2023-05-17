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
# Warmup Iteration   1: 3.344 ops/ms
# Warmup Iteration   2: 7.967 ops/ms
# Warmup Iteration   3: 8.971 ops/ms
Iteration   1: 9.257 ops/ms
Iteration   2: 8.980 ops/ms
Iteration   3: 8.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.018 ±(99.9%) 4.064 ops/ms [Average]
  (min, avg, max) = (8.816, 9.018, 9.257), stdev = 0.223
  CI (99.9%): [4.953, 13.082] (assumes normal distribution)


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
# Warmup Iteration   1: 6.432 ops/ms
# Warmup Iteration   2: 8.797 ops/ms
# Warmup Iteration   3: 9.432 ops/ms
Iteration   1: 10.286 ops/ms
Iteration   2: 9.632 ops/ms
Iteration   3: 9.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.917 ±(99.9%) 6.112 ops/ms [Average]
  (min, avg, max) = (9.632, 9.917, 10.286), stdev = 0.335
  CI (99.9%): [3.805, 16.029] (assumes normal distribution)


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
# Warmup Iteration   1: 5.799 ops/ms
# Warmup Iteration   2: 8.741 ops/ms
# Warmup Iteration   3: 9.188 ops/ms
Iteration   1: 9.202 ops/ms
Iteration   2: 8.930 ops/ms
Iteration   3: 9.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.107 ±(99.9%) 2.807 ops/ms [Average]
  (min, avg, max) = (8.930, 9.107, 9.202), stdev = 0.154
  CI (99.9%): [6.300, 11.915] (assumes normal distribution)


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
# Warmup Iteration   1: 4.565 ops/ms
# Warmup Iteration   2: 6.704 ops/ms
# Warmup Iteration   3: 7.071 ops/ms
Iteration   1: 7.080 ops/ms
Iteration   2: 7.130 ops/ms
Iteration   3: 7.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.108 ±(99.9%) 0.460 ops/ms [Average]
  (min, avg, max) = (7.080, 7.108, 7.130), stdev = 0.025
  CI (99.9%): [6.649, 7.568] (assumes normal distribution)


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
# Warmup Iteration   1: 4.885 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.003 ms/op
Iteration   1: 3.464 ±(99.9%) 0.005 ms/op
Iteration   2: 3.364 ±(99.9%) 0.003 ms/op
Iteration   3: 3.615 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.481 ±(99.9%) 2.305 ms/op [Average]
  (min, avg, max) = (3.364, 3.481, 3.615), stdev = 0.126
  CI (99.9%): [1.176, 5.786] (assumes normal distribution)


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
# Warmup Iteration   1: 5.009 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.003 ms/op
Iteration   1: 3.449 ±(99.9%) 0.002 ms/op
Iteration   2: 3.441 ±(99.9%) 0.002 ms/op
Iteration   3: 3.407 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.432 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.407, 3.432, 3.449), stdev = 0.022
  CI (99.9%): [3.022, 3.843] (assumes normal distribution)


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
# Warmup Iteration   1: 4.960 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.004 ms/op
Iteration   1: 3.583 ±(99.9%) 0.004 ms/op
Iteration   2: 3.644 ±(99.9%) 0.005 ms/op
Iteration   3: 3.486 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.571 ±(99.9%) 1.453 ms/op [Average]
  (min, avg, max) = (3.486, 3.571, 3.644), stdev = 0.080
  CI (99.9%): [2.118, 5.024] (assumes normal distribution)


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
# Warmup Iteration   1: 6.205 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.840 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.733 ±(99.9%) 0.010 ms/op
Iteration   1: 4.428 ±(99.9%) 0.012 ms/op
Iteration   2: 4.495 ±(99.9%) 0.015 ms/op
Iteration   3: 4.441 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.454 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (4.428, 4.454, 4.495), stdev = 0.035
  CI (99.9%): [3.810, 5.098] (assumes normal distribution)


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
# Warmup Iteration   1: 5.213 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.009 ms/op
Iteration   1: 3.427 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  9.596 ms/op
                 createUser·p0.9999: 15.652 ms/op
                 createUser·p1.00:   16.646 ms/op

Iteration   2: 3.401 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  8.577 ms/op
                 createUser·p0.9999: 24.057 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   3: 3.410 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  7.161 ms/op
                 createUser·p0.9999: 18.307 ms/op
                 createUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 281432
  mean =      3.413 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6051 
    [ 2.500,  5.000) = 272038 
    [ 5.000,  7.500) = 2901 
    [ 7.500, 10.000) = 235 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =      8.709 ms/op
     p(99.9900) =     23.158 ms/op
     p(99.9990) =     24.353 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.006 ms/op
Iteration   1: 3.313 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  8.127 ms/op
                 existUser·p0.9999: 14.080 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 3.257 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.841 ms/op
                 existUser·p0.999:  7.553 ms/op
                 existUser·p0.9999: 16.436 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   3: 3.338 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 19.019 ms/op
                 existUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 290593
  mean =      3.302 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 400 
    [ 1.250,  2.500) = 7304 
    [ 2.500,  3.750) = 246961 
    [ 3.750,  5.000) = 33204 
    [ 5.000,  6.250) = 1850 
    [ 6.250,  7.500) = 432 
    [ 7.500,  8.750) = 164 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     16.612 ms/op
     p(99.9990) =     19.339 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 4.902 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.007 ms/op
Iteration   1: 3.419 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  8.121 ms/op
                 getUser·p0.9999: 14.052 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 3.339 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  8.340 ms/op
                 getUser·p0.9999: 16.194 ms/op
                 getUser·p1.00:   16.548 ms/op

Iteration   3: 3.402 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  7.644 ms/op
                 getUser·p0.9999: 18.088 ms/op
                 getUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 283493
  mean =      3.387 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 304 
    [ 1.250,  2.500) = 14293 
    [ 2.500,  3.750) = 212831 
    [ 3.750,  5.000) = 51616 
    [ 5.000,  6.250) = 3421 
    [ 6.250,  7.500) = 651 
    [ 7.500,  8.750) = 169 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =      8.163 ms/op
     p(99.9900) =     16.663 ms/op
     p(99.9990) =     18.497 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 5.996 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.657 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.433 ±(99.9%) 0.013 ms/op
Iteration   1: 4.277 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   4.125 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  14.634 ms/op
                 listUser·p0.9999: 17.416 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   2: 4.508 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   5.636 ms/op
                 listUser·p0.95:   6.382 ms/op
                 listUser·p0.99:   8.053 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 19.716 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   3: 4.418 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  17.518 ms/op
                 listUser·p0.9999: 26.640 ms/op
                 listUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 218323
  mean =      4.399 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 965 
    [ 2.500,  5.000) = 186626 
    [ 5.000,  7.500) = 27762 
    [ 7.500, 10.000) = 2469 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      6.242 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     25.788 ms/op
     p(99.9990) =     26.765 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.018 ± 4.064  ops/ms
ClientGrpc.existUser                       thrpt       3   9.917 ± 6.112  ops/ms
ClientGrpc.getUser                         thrpt       3   9.107 ± 2.807  ops/ms
ClientGrpc.listUser                        thrpt       3   7.108 ± 0.460  ops/ms
ClientGrpc.createUser                       avgt       3   3.481 ± 2.305   ms/op
ClientGrpc.existUser                        avgt       3   3.432 ± 0.410   ms/op
ClientGrpc.getUser                          avgt       3   3.571 ± 1.453   ms/op
ClientGrpc.listUser                         avgt       3   4.454 ± 0.644   ms/op
ClientGrpc.createUser                     sample  281432   3.413 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.804           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.367           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.985           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.169           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.709           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.158           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.445           ms/op
ClientGrpc.existUser                      sample  290593   3.302 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.654           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.260           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.940           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.405           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.612           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.431           ms/op
ClientGrpc.getUser                        sample  283493   3.387 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.676           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.363           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.163           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.663           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.645           ms/op
ClientGrpc.listUser                       sample  218323   4.399 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.980           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.243           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.242           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.815           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.811           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.788           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.771           ms/op
