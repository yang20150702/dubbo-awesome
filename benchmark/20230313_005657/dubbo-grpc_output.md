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
# Warmup Iteration   1: 2.759 ops/ms
# Warmup Iteration   2: 7.012 ops/ms
# Warmup Iteration   3: 8.548 ops/ms
Iteration   1: 8.972 ops/ms
Iteration   2: 9.000 ops/ms
Iteration   3: 9.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.001 ±(99.9%) 0.529 ops/ms [Average]
  (min, avg, max) = (8.972, 9.001, 9.030), stdev = 0.029
  CI (99.9%): [8.471, 9.530] (assumes normal distribution)


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
# Warmup Iteration   1: 5.690 ops/ms
# Warmup Iteration   2: 8.752 ops/ms
# Warmup Iteration   3: 9.235 ops/ms
Iteration   1: 9.287 ops/ms
Iteration   2: 9.522 ops/ms
Iteration   3: 9.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.404 ±(99.9%) 2.146 ops/ms [Average]
  (min, avg, max) = (9.287, 9.404, 9.522), stdev = 0.118
  CI (99.9%): [7.258, 11.550] (assumes normal distribution)


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
# Warmup Iteration   1: 5.358 ops/ms
# Warmup Iteration   2: 8.563 ops/ms
# Warmup Iteration   3: 8.877 ops/ms
Iteration   1: 9.058 ops/ms
Iteration   2: 9.031 ops/ms
Iteration   3: 8.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.026 ±(99.9%) 0.644 ops/ms [Average]
  (min, avg, max) = (8.988, 9.026, 9.058), stdev = 0.035
  CI (99.9%): [8.382, 9.670] (assumes normal distribution)


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
# Warmup Iteration   1: 4.773 ops/ms
# Warmup Iteration   2: 6.204 ops/ms
# Warmup Iteration   3: 6.653 ops/ms
Iteration   1: 6.763 ops/ms
Iteration   2: 6.731 ops/ms
Iteration   3: 6.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.766 ±(99.9%) 0.663 ops/ms [Average]
  (min, avg, max) = (6.731, 6.766, 6.803), stdev = 0.036
  CI (99.9%): [6.102, 7.429] (assumes normal distribution)


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
# Warmup Iteration   1: 5.403 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.651 ±(99.9%) 0.007 ms/op
Iteration   1: 3.560 ±(99.9%) 0.003 ms/op
Iteration   2: 3.533 ±(99.9%) 0.003 ms/op
Iteration   3: 3.532 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.542 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (3.532, 3.542, 3.560), stdev = 0.016
  CI (99.9%): [3.254, 3.829] (assumes normal distribution)


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
# Warmup Iteration   1: 4.919 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.003 ms/op
Iteration   1: 3.384 ±(99.9%) 0.004 ms/op
Iteration   2: 3.411 ±(99.9%) 0.003 ms/op
Iteration   3: 3.407 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.401 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (3.384, 3.401, 3.411), stdev = 0.015
  CI (99.9%): [3.136, 3.665] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.067 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.680 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.005 ms/op
Iteration   1: 3.621 ±(99.9%) 0.002 ms/op
Iteration   2: 3.559 ±(99.9%) 0.006 ms/op
Iteration   3: 3.547 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.576 ±(99.9%) 0.725 ms/op [Average]
  (min, avg, max) = (3.547, 3.576, 3.621), stdev = 0.040
  CI (99.9%): [2.850, 4.301] (assumes normal distribution)


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
# Warmup Iteration   1: 6.432 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.907 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.656 ±(99.9%) 0.006 ms/op
Iteration   1: 4.682 ±(99.9%) 0.012 ms/op
Iteration   2: 4.626 ±(99.9%) 0.010 ms/op
Iteration   3: 4.686 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.665 ±(99.9%) 0.607 ms/op [Average]
  (min, avg, max) = (4.626, 4.665, 4.686), stdev = 0.033
  CI (99.9%): [4.058, 5.271] (assumes normal distribution)


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
# Warmup Iteration   1: 5.370 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.008 ms/op
Iteration   1: 3.550 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.095 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  7.750 ms/op
                 createUser·p0.9999: 13.580 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   2: 3.520 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  7.545 ms/op
                 createUser·p0.9999: 14.500 ms/op
                 createUser·p1.00:   15.925 ms/op

Iteration   3: 3.599 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  15.868 ms/op
                 createUser·p0.9999: 19.796 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 270024
  mean =      3.556 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3537 
    [ 2.500,  5.000) = 263365 
    [ 5.000,  7.500) = 2752 
    [ 7.500, 10.000) = 146 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =      8.126 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     20.329 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 4.877 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.007 ms/op
Iteration   1: 3.386 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   4.981 ms/op
                 existUser·p0.999:  7.476 ms/op
                 existUser·p0.9999: 14.782 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   2: 3.350 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  6.591 ms/op
                 existUser·p0.9999: 13.670 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 3.275 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   4.891 ms/op
                 existUser·p0.999:  9.008 ms/op
                 existUser·p0.9999: 20.054 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 287692
  mean =      3.336 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15728 
    [ 2.500,  5.000) = 268687 
    [ 5.000,  7.500) = 3027 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =      7.291 ms/op
     p(99.9900) =     19.709 ms/op
     p(99.9990) =     21.446 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 5.088 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.008 ms/op
Iteration   1: 3.569 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  7.201 ms/op
                 getUser·p0.9999: 14.190 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   2: 3.562 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  9.899 ms/op
                 getUser·p0.9999: 17.369 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   3: 3.546 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  7.928 ms/op
                 getUser·p0.9999: 18.711 ms/op
                 getUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 269647
  mean =      3.559 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8157 
    [ 2.500,  5.000) = 257358 
    [ 5.000,  7.500) = 3798 
    [ 7.500, 10.000) = 181 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =      7.777 ms/op
     p(99.9900) =     18.091 ms/op
     p(99.9990) =     21.067 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 5.597 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.257 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.728 ±(99.9%) 0.013 ms/op
Iteration   1: 4.657 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.586 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 23.106 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 4.733 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.997 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  18.586 ms/op
                 listUser·p0.9999: 23.412 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 4.733 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.805 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   8.367 ms/op
                 listUser·p0.999:  20.134 ms/op
                 listUser·p0.9999: 24.960 ms/op
                 listUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203837
  mean =      4.707 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 637 
    [ 2.500,  5.000) = 160658 
    [ 5.000,  7.500) = 37671 
    [ 7.500, 10.000) = 4186 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.751 ms/op
     p(95.0000) =      6.783 ms/op
     p(99.0000) =      8.176 ms/op
     p(99.9000) =     18.847 ms/op
     p(99.9900) =     23.797 ms/op
     p(99.9990) =     25.229 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.001 ± 0.529  ops/ms
ClientGrpc.existUser                       thrpt       3   9.404 ± 2.146  ops/ms
ClientGrpc.getUser                         thrpt       3   9.026 ± 0.644  ops/ms
ClientGrpc.listUser                        thrpt       3   6.766 ± 0.663  ops/ms
ClientGrpc.createUser                       avgt       3   3.542 ± 0.288   ms/op
ClientGrpc.existUser                        avgt       3   3.401 ± 0.265   ms/op
ClientGrpc.getUser                          avgt       3   3.576 ± 0.725   ms/op
ClientGrpc.listUser                         avgt       3   4.665 ± 0.607   ms/op
ClientGrpc.createUser                     sample  270024   3.556 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.000           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.108           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.128           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.126           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.235           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.004           ms/op
ClientGrpc.existUser                      sample  287692   3.336 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.851           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.136           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.291           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.709           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.020           ms/op
ClientGrpc.getUser                        sample  269647   3.559 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.673           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.777           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.091           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.201           ms/op
ClientGrpc.listUser                       sample  203837   4.707 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.135           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.547           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.847           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.797           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.330           ms/op
