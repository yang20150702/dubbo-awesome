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
# Warmup Iteration   1: 3.448 ops/ms
# Warmup Iteration   2: 6.922 ops/ms
# Warmup Iteration   3: 8.615 ops/ms
Iteration   1: 9.059 ops/ms
Iteration   2: 8.856 ops/ms
Iteration   3: 9.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.999 ±(99.9%) 2.266 ops/ms [Average]
  (min, avg, max) = (8.856, 8.999, 9.082), stdev = 0.124
  CI (99.9%): [6.733, 11.265] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.120 ops/ms
# Warmup Iteration   2: 8.922 ops/ms
# Warmup Iteration   3: 9.597 ops/ms
Iteration   1: 9.402 ops/ms
Iteration   2: 9.417 ops/ms
Iteration   3: 9.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.391 ±(99.9%) 0.620 ops/ms [Average]
  (min, avg, max) = (9.352, 9.391, 9.417), stdev = 0.034
  CI (99.9%): [8.771, 10.010] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.011 ops/ms
# Warmup Iteration   2: 8.469 ops/ms
# Warmup Iteration   3: 8.695 ops/ms
Iteration   1: 8.857 ops/ms
Iteration   2: 8.967 ops/ms
Iteration   3: 8.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.901 ±(99.9%) 1.065 ops/ms [Average]
  (min, avg, max) = (8.857, 8.901, 8.967), stdev = 0.058
  CI (99.9%): [7.836, 9.965] (assumes normal distribution)


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
# Warmup Iteration   1: 5.356 ops/ms
# Warmup Iteration   2: 6.082 ops/ms
# Warmup Iteration   3: 6.723 ops/ms
Iteration   1: 6.827 ops/ms
Iteration   2: 6.828 ops/ms
Iteration   3: 6.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.830 ±(99.9%) 0.068 ops/ms [Average]
  (min, avg, max) = (6.827, 6.830, 6.834), stdev = 0.004
  CI (99.9%): [6.762, 6.898] (assumes normal distribution)


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
# Warmup Iteration   1: 5.386 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.006 ms/op
Iteration   1: 3.525 ±(99.9%) 0.003 ms/op
Iteration   2: 3.528 ±(99.9%) 0.004 ms/op
Iteration   3: 3.539 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.531 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (3.525, 3.531, 3.539), stdev = 0.007
  CI (99.9%): [3.399, 3.663] (assumes normal distribution)


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
# Warmup Iteration   1: 4.848 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.003 ms/op
Iteration   1: 3.463 ±(99.9%) 0.002 ms/op
Iteration   2: 3.356 ±(99.9%) 0.004 ms/op
Iteration   3: 3.433 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.417 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (3.356, 3.417, 3.463), stdev = 0.055
  CI (99.9%): [2.413, 4.422] (assumes normal distribution)


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
# Warmup Iteration   1: 5.147 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.005 ms/op
Iteration   1: 3.542 ±(99.9%) 0.005 ms/op
Iteration   2: 3.558 ±(99.9%) 0.006 ms/op
Iteration   3: 3.523 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.541 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (3.523, 3.541, 3.558), stdev = 0.018
  CI (99.9%): [3.218, 3.864] (assumes normal distribution)


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
# Warmup Iteration   1: 6.538 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.890 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.644 ±(99.9%) 0.009 ms/op
Iteration   1: 4.677 ±(99.9%) 0.011 ms/op
Iteration   2: 4.575 ±(99.9%) 0.019 ms/op
Iteration   3: 4.641 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.631 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (4.575, 4.631, 4.677), stdev = 0.052
  CI (99.9%): [3.682, 5.580] (assumes normal distribution)


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
# Warmup Iteration   1: 5.377 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.008 ms/op
Iteration   1: 3.540 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.559 ms/op
                 createUser·p0.999:  10.546 ms/op
                 createUser·p0.9999: 15.596 ms/op
                 createUser·p1.00:   16.089 ms/op

Iteration   2: 3.627 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.261 ms/op
                 createUser·p0.999:  12.725 ms/op
                 createUser·p0.9999: 16.016 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   3: 3.551 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  14.549 ms/op
                 createUser·p0.9999: 20.185 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 268613
  mean =      3.572 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6498 
    [ 2.500,  5.000) = 257575 
    [ 5.000,  7.500) = 3866 
    [ 7.500, 10.000) = 307 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     11.360 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     20.544 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.007 ms/op
Iteration   1: 3.377 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  7.031 ms/op
                 existUser·p0.9999: 14.140 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 3.411 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.196 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  14.057 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   3: 3.386 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   4.801 ms/op
                 existUser·p0.999:  7.566 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 283067
  mean =      3.391 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 517 
    [ 1.250,  2.500) = 8879 
    [ 2.500,  3.750) = 229786 
    [ 3.750,  5.000) = 41037 
    [ 5.000,  6.250) = 2080 
    [ 6.250,  7.500) = 404 
    [ 7.500,  8.750) = 128 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =      8.118 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     19.344 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 5.302 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.008 ms/op
Iteration   1: 3.516 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  8.208 ms/op
                 getUser·p0.9999: 17.888 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   2: 3.493 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  9.639 ms/op
                 getUser·p0.9999: 16.772 ms/op
                 getUser·p1.00:   17.859 ms/op

Iteration   3: 3.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  8.778 ms/op
                 getUser·p0.9999: 17.564 ms/op
                 getUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 273384
  mean =      3.515 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 250 
    [ 1.250,  2.500) = 12426 
    [ 2.500,  3.750) = 186327 
    [ 3.750,  5.000) = 69474 
    [ 5.000,  6.250) = 3819 
    [ 6.250,  7.500) = 528 
    [ 7.500,  8.750) = 261 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     18.475 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 5.484 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.085 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.689 ±(99.9%) 0.014 ms/op
Iteration   1: 4.676 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   6.382 ms/op
                 listUser·p0.99:   8.208 ms/op
                 listUser·p0.999:  15.689 ms/op
                 listUser·p0.9999: 23.268 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 4.658 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 27.763 ms/op
                 listUser·p1.00:   28.213 ms/op

Iteration   3: 4.635 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  19.694 ms/op
                 listUser·p0.9999: 29.473 ms/op
                 listUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206188
  mean =      4.657 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 154 
    [ 2.500,  5.000) = 168851 
    [ 5.000,  7.500) = 33272 
    [ 7.500, 10.000) = 3482 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      6.414 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     16.266 ms/op
     p(99.9900) =     28.606 ms/op
     p(99.9990) =     31.713 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.999 ± 2.266  ops/ms
ClientGrpc.existUser                       thrpt       3   9.391 ± 0.620  ops/ms
ClientGrpc.getUser                         thrpt       3   8.901 ± 1.065  ops/ms
ClientGrpc.listUser                        thrpt       3   6.830 ± 0.068  ops/ms
ClientGrpc.createUser                       avgt       3   3.531 ± 0.132   ms/op
ClientGrpc.existUser                        avgt       3   3.417 ± 1.004   ms/op
ClientGrpc.getUser                          avgt       3   3.541 ± 0.323   ms/op
ClientGrpc.listUser                         avgt       3   4.631 ± 0.949   ms/op
ClientGrpc.createUser                     sample  268613   3.572 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.897           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.121           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.360           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.514           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.709           ms/op
ClientGrpc.existUser                      sample  283067   3.391 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.676           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.005           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.118           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.629           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.464           ms/op
ClientGrpc.getUser                        sample  273384   3.515 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.848           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.100           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.978           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.629           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.842           ms/op
ClientGrpc.listUser                       sample  206188   4.657 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.235           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.414           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.020           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.266           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.606           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.818           ms/op
