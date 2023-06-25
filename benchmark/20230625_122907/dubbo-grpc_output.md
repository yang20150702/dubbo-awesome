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
# Warmup Iteration   1: 3.489 ops/ms
# Warmup Iteration   2: 7.548 ops/ms
# Warmup Iteration   3: 8.872 ops/ms
Iteration   1: 8.963 ops/ms
Iteration   2: 9.012 ops/ms
Iteration   3: 8.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.979 ±(99.9%) 0.517 ops/ms [Average]
  (min, avg, max) = (8.963, 8.979, 9.012), stdev = 0.028
  CI (99.9%): [8.463, 9.496] (assumes normal distribution)


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
# Warmup Iteration   1: 5.777 ops/ms
# Warmup Iteration   2: 8.877 ops/ms
# Warmup Iteration   3: 9.348 ops/ms
Iteration   1: 9.557 ops/ms
Iteration   2: 9.359 ops/ms
Iteration   3: 9.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.386 ±(99.9%) 2.912 ops/ms [Average]
  (min, avg, max) = (9.241, 9.386, 9.557), stdev = 0.160
  CI (99.9%): [6.474, 12.298] (assumes normal distribution)


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
# Warmup Iteration   1: 5.446 ops/ms
# Warmup Iteration   2: 8.301 ops/ms
# Warmup Iteration   3: 8.829 ops/ms
Iteration   1: 9.003 ops/ms
Iteration   2: 8.880 ops/ms
Iteration   3: 8.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.951 ±(99.9%) 1.156 ops/ms [Average]
  (min, avg, max) = (8.880, 8.951, 9.003), stdev = 0.063
  CI (99.9%): [7.794, 10.107] (assumes normal distribution)


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
# Warmup Iteration   1: 4.623 ops/ms
# Warmup Iteration   2: 6.348 ops/ms
# Warmup Iteration   3: 6.939 ops/ms
Iteration   1: 6.903 ops/ms
Iteration   2: 6.909 ops/ms
Iteration   3: 6.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.903 ±(99.9%) 0.104 ops/ms [Average]
  (min, avg, max) = (6.898, 6.903, 6.909), stdev = 0.006
  CI (99.9%): [6.799, 7.007] (assumes normal distribution)


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
# Warmup Iteration   1: 5.336 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.786 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.012 ms/op
Iteration   1: 3.573 ±(99.9%) 0.004 ms/op
Iteration   2: 3.598 ±(99.9%) 0.002 ms/op
Iteration   3: 3.543 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.572 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.543, 3.572, 3.598), stdev = 0.028
  CI (99.9%): [3.070, 4.074] (assumes normal distribution)


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
# Warmup Iteration   1: 4.829 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.003 ms/op
Iteration   1: 3.318 ±(99.9%) 0.005 ms/op
Iteration   2: 3.478 ±(99.9%) 0.003 ms/op
Iteration   3: 3.433 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.410 ±(99.9%) 1.514 ms/op [Average]
  (min, avg, max) = (3.318, 3.410, 3.478), stdev = 0.083
  CI (99.9%): [1.896, 4.923] (assumes normal distribution)


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
# Warmup Iteration   1: 5.317 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.004 ms/op
Iteration   1: 3.540 ±(99.9%) 0.005 ms/op
Iteration   2: 3.495 ±(99.9%) 0.005 ms/op
Iteration   3: 3.516 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.517 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (3.495, 3.517, 3.540), stdev = 0.022
  CI (99.9%): [3.109, 3.926] (assumes normal distribution)


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
# Warmup Iteration   1: 5.868 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.908 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.717 ±(99.9%) 0.025 ms/op
Iteration   1: 4.616 ±(99.9%) 0.016 ms/op
Iteration   2: 4.624 ±(99.9%) 0.021 ms/op
Iteration   3: 4.505 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.582 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (4.505, 4.582, 4.624), stdev = 0.066
  CI (99.9%): [3.369, 5.794] (assumes normal distribution)


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
# Warmup Iteration   1: 4.922 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.009 ms/op
Iteration   1: 3.586 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  9.270 ms/op
                 createUser·p0.9999: 33.426 ms/op
                 createUser·p1.00:   33.817 ms/op

Iteration   2: 3.550 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.592 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  7.643 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   3: 3.603 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  14.298 ms/op
                 createUser·p0.9999: 39.256 ms/op
                 createUser·p1.00:   39.584 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 267964
  mean =      3.579 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9027 
    [ 2.500,  5.000) = 252815 
    [ 5.000,  7.500) = 5367 
    [ 7.500, 10.000) = 502 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.750 ms/op
     p(99.9900) =     38.680 ms/op
     p(99.9990) =     39.584 ms/op
     p(99.9999) =     39.584 ms/op
    p(100.0000) =     39.584 ms/op


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
# Warmup Iteration   1: 4.880 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.007 ms/op
Iteration   1: 3.376 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 18.301 ms/op
                 existUser·p1.00:   19.792 ms/op

Iteration   2: 3.352 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   4.792 ms/op
                 existUser·p0.999:  10.119 ms/op
                 existUser·p0.9999: 15.187 ms/op
                 existUser·p1.00:   15.614 ms/op

Iteration   3: 3.496 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  13.730 ms/op
                 existUser·p0.9999: 29.645 ms/op
                 existUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 281759
  mean =      3.407 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7095 
    [ 2.500,  5.000) = 271858 
    [ 5.000,  7.500) = 2273 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      4.997 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     27.290 ms/op
     p(99.9990) =     29.792 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 5.469 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.603 ±(99.9%) 0.008 ms/op
Iteration   1: 3.510 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  10.353 ms/op
                 getUser·p0.9999: 14.631 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   2: 3.578 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.364 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  7.594 ms/op
                 getUser·p0.9999: 16.747 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   3: 3.547 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  12.359 ms/op
                 getUser·p0.9999: 25.165 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 270679
  mean =      3.545 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9655 
    [ 2.500,  5.000) = 256281 
    [ 5.000,  7.500) = 4275 
    [ 7.500, 10.000) = 180 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.364 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     10.327 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 6.695 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.919 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.554 ±(99.9%) 0.012 ms/op
Iteration   1: 4.686 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.849 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  16.581 ms/op
                 listUser·p0.9999: 21.310 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   2: 4.626 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   6.474 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  16.347 ms/op
                 listUser·p0.9999: 18.034 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   3: 4.736 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.644 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  26.769 ms/op
                 listUser·p0.9999: 29.655 ms/op
                 listUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205007
  mean =      4.682 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 439 
    [ 2.500,  5.000) = 159962 
    [ 5.000,  7.500) = 40670 
    [ 7.500, 10.000) = 3346 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      8.151 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     29.573 ms/op
     p(99.9990) =     31.682 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.979 ± 0.517  ops/ms
ClientGrpc.existUser                       thrpt       3   9.386 ± 2.912  ops/ms
ClientGrpc.getUser                         thrpt       3   8.951 ± 1.156  ops/ms
ClientGrpc.listUser                        thrpt       3   6.903 ± 0.104  ops/ms
ClientGrpc.createUser                       avgt       3   3.572 ± 0.502   ms/op
ClientGrpc.existUser                        avgt       3   3.410 ± 1.514   ms/op
ClientGrpc.getUser                          avgt       3   3.517 ± 0.409   ms/op
ClientGrpc.listUser                         avgt       3   4.582 ± 1.213   ms/op
ClientGrpc.createUser                     sample  267964   3.579 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.592           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.661           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.750           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          38.680           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          39.584           ms/op
ClientGrpc.existUser                      sample  281759   3.407 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.811           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.928           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.997           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.304           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.290           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.884           ms/op
ClientGrpc.getUser                        sample  270679   3.545 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.364           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.472           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.327           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.544           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.199           ms/op
ClientGrpc.listUser                       sample  205007   4.682 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.912           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.151           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.941           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.573           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.785           ms/op
