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
# Warmup Iteration   1: 3.409 ops/ms
# Warmup Iteration   2: 7.527 ops/ms
# Warmup Iteration   3: 7.983 ops/ms
Iteration   1: 8.400 ops/ms
Iteration   2: 8.985 ops/ms
Iteration   3: 8.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.629 ±(99.9%) 5.703 ops/ms [Average]
  (min, avg, max) = (8.400, 8.629, 8.985), stdev = 0.313
  CI (99.9%): [2.926, 14.331] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.540 ops/ms
# Warmup Iteration   2: 8.416 ops/ms
# Warmup Iteration   3: 8.863 ops/ms
Iteration   1: 9.050 ops/ms
Iteration   2: 9.441 ops/ms
Iteration   3: 9.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.319 ±(99.9%) 4.252 ops/ms [Average]
  (min, avg, max) = (9.050, 9.319, 9.465), stdev = 0.233
  CI (99.9%): [5.067, 13.571] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.470 ops/ms
# Warmup Iteration   2: 8.084 ops/ms
# Warmup Iteration   3: 8.624 ops/ms
Iteration   1: 9.264 ops/ms
Iteration   2: 9.123 ops/ms
Iteration   3: 9.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.150 ±(99.9%) 1.885 ops/ms [Average]
  (min, avg, max) = (9.063, 9.150, 9.264), stdev = 0.103
  CI (99.9%): [7.265, 11.035] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.725 ops/ms
# Warmup Iteration   2: 6.838 ops/ms
# Warmup Iteration   3: 6.642 ops/ms
Iteration   1: 7.247 ops/ms
Iteration   2: 6.711 ops/ms
Iteration   3: 7.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.032 ±(99.9%) 5.170 ops/ms [Average]
  (min, avg, max) = (6.711, 7.032, 7.247), stdev = 0.283
  CI (99.9%): [1.862, 12.201] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.293 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.005 ms/op
Iteration   1: 3.414 ±(99.9%) 0.003 ms/op
Iteration   2: 3.417 ±(99.9%) 0.003 ms/op
Iteration   3: 3.418 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.416 ±(99.9%) 0.040 ms/op [Average]
  (min, avg, max) = (3.414, 3.416, 3.418), stdev = 0.002
  CI (99.9%): [3.376, 3.457] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.970 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.355 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.003 ms/op
Iteration   1: 3.402 ±(99.9%) 0.002 ms/op
Iteration   2: 3.226 ±(99.9%) 0.005 ms/op
Iteration   3: 3.354 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.327 ±(99.9%) 1.657 ms/op [Average]
  (min, avg, max) = (3.226, 3.327, 3.402), stdev = 0.091
  CI (99.9%): [1.670, 4.984] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.183 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.004 ms/op
Iteration   1: 3.504 ±(99.9%) 0.003 ms/op
Iteration   2: 3.570 ±(99.9%) 0.004 ms/op
Iteration   3: 3.566 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.547 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (3.504, 3.547, 3.570), stdev = 0.037
  CI (99.9%): [2.873, 4.221] (assumes normal distribution)


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
# Warmup Iteration   1: 5.415 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 5.173 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.857 ±(99.9%) 0.016 ms/op
Iteration   1: 4.559 ±(99.9%) 0.009 ms/op
Iteration   2: 4.778 ±(99.9%) 0.012 ms/op
Iteration   3: 4.519 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.619 ±(99.9%) 2.547 ms/op [Average]
  (min, avg, max) = (4.519, 4.619, 4.778), stdev = 0.140
  CI (99.9%): [2.071, 7.166] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.813 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.010 ms/op
Iteration   1: 3.637 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  9.894 ms/op
                 createUser·p0.9999: 22.930 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   2: 3.557 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  12.239 ms/op
                 createUser·p0.9999: 26.313 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   3: 3.711 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  10.384 ms/op
                 createUser·p0.9999: 28.292 ms/op
                 createUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264221
  mean =      3.634 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9043 
    [ 2.500,  5.000) = 247243 
    [ 5.000,  7.500) = 6858 
    [ 7.500, 10.000) = 777 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     10.306 ms/op
     p(99.9900) =     27.325 ms/op
     p(99.9990) =     29.274 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.008 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.009 ms/op
Iteration   1: 3.327 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 13.742 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 3.418 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  10.688 ms/op
                 existUser·p0.9999: 25.645 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   3: 3.460 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 18.949 ms/op
                 existUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 282253
  mean =      3.401 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16197 
    [ 2.500,  5.000) = 260376 
    [ 5.000,  7.500) = 4737 
    [ 7.500, 10.000) = 711 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     25.282 ms/op
     p(99.9990) =     25.860 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 5.537 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.666 ±(99.9%) 0.009 ms/op
Iteration   1: 3.670 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  11.633 ms/op
                 getUser·p0.9999: 19.605 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   2: 3.674 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.156 ms/op
                 getUser·p0.999:  16.024 ms/op
                 getUser·p0.9999: 22.095 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   3: 3.576 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  8.815 ms/op
                 getUser·p0.9999: 27.591 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263634
  mean =      3.639 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8391 
    [ 2.500,  5.000) = 247008 
    [ 5.000,  7.500) = 7019 
    [ 7.500, 10.000) = 908 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     10.836 ms/op
     p(99.9900) =     25.383 ms/op
     p(99.9990) =     27.722 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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
# Warmup Iteration   1: 5.628 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.296 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.918 ±(99.9%) 0.018 ms/op
Iteration   1: 4.659 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   7.004 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  15.281 ms/op
                 listUser·p0.9999: 18.227 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   2: 4.678 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  18.783 ms/op
                 listUser·p0.9999: 21.900 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 4.960 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.709 ms/op
                 listUser·p0.95:   7.512 ms/op
                 listUser·p0.99:   9.519 ms/op
                 listUser·p0.999:  26.911 ms/op
                 listUser·p0.9999: 37.632 ms/op
                 listUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201613
  mean =      4.762 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 493 
    [ 2.500,  5.000) = 147239 
    [ 5.000,  7.500) = 46698 
    [ 7.500, 10.000) = 6160 
    [10.000, 12.500) = 574 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      6.316 ms/op
     p(95.0000) =      7.160 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     37.944 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.629 ± 5.703  ops/ms
ClientGrpc.existUser                       thrpt       3   9.319 ± 4.252  ops/ms
ClientGrpc.getUser                         thrpt       3   9.150 ± 1.885  ops/ms
ClientGrpc.listUser                        thrpt       3   7.032 ± 5.170  ops/ms
ClientGrpc.createUser                       avgt       3   3.416 ± 0.040   ms/op
ClientGrpc.existUser                        avgt       3   3.327 ± 1.657   ms/op
ClientGrpc.getUser                          avgt       3   3.547 ± 0.674   ms/op
ClientGrpc.listUser                         avgt       3   4.619 ± 2.547   ms/op
ClientGrpc.createUser                     sample  264221   3.634 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.762           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.087           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.306           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.325           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.802           ms/op
ClientGrpc.existUser                      sample  282253   3.401 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.731           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.088           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.603           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.388           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.282           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.919           ms/op
ClientGrpc.getUser                        sample  263634   3.639 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.725           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.136           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.836           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.383           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.722           ms/op
ClientGrpc.listUser                       sample  201613   4.762 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.149           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.316           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.160           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.946           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.564           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.472           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.142           ms/op
