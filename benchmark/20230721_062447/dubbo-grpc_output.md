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
# Warmup Iteration   1: 3.241 ops/ms
# Warmup Iteration   2: 7.465 ops/ms
# Warmup Iteration   3: 8.706 ops/ms
Iteration   1: 9.180 ops/ms
Iteration   2: 8.919 ops/ms
Iteration   3: 8.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.990 ±(99.9%) 3.033 ops/ms [Average]
  (min, avg, max) = (8.871, 8.990, 9.180), stdev = 0.166
  CI (99.9%): [5.957, 12.023] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.067 ops/ms
# Warmup Iteration   2: 9.031 ops/ms
# Warmup Iteration   3: 9.361 ops/ms
Iteration   1: 9.281 ops/ms
Iteration   2: 9.417 ops/ms
Iteration   3: 9.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.372 ±(99.9%) 1.426 ops/ms [Average]
  (min, avg, max) = (9.281, 9.372, 9.417), stdev = 0.078
  CI (99.9%): [7.946, 10.798] (assumes normal distribution)


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
# Warmup Iteration   1: 5.648 ops/ms
# Warmup Iteration   2: 8.693 ops/ms
# Warmup Iteration   3: 8.873 ops/ms
Iteration   1: 8.966 ops/ms
Iteration   2: 9.060 ops/ms
Iteration   3: 9.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.052 ±(99.9%) 1.497 ops/ms [Average]
  (min, avg, max) = (8.966, 9.052, 9.129), stdev = 0.082
  CI (99.9%): [7.555, 10.549] (assumes normal distribution)


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
# Warmup Iteration   1: 4.457 ops/ms
# Warmup Iteration   2: 6.493 ops/ms
# Warmup Iteration   3: 6.956 ops/ms
Iteration   1: 6.948 ops/ms
Iteration   2: 7.191 ops/ms
Iteration   3: 7.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.072 ±(99.9%) 2.215 ops/ms [Average]
  (min, avg, max) = (6.948, 7.072, 7.191), stdev = 0.121
  CI (99.9%): [4.857, 9.287] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 4.939 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.003 ms/op
Iteration   1: 3.416 ±(99.9%) 0.004 ms/op
Iteration   2: 3.431 ±(99.9%) 0.004 ms/op
Iteration   3: 3.436 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.428 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (3.416, 3.428, 3.436), stdev = 0.011
  CI (99.9%): [3.234, 3.621] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.620 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.003 ms/op
Iteration   1: 3.489 ±(99.9%) 0.004 ms/op
Iteration   2: 3.330 ±(99.9%) 0.004 ms/op
Iteration   3: 3.503 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.440 ±(99.9%) 1.754 ms/op [Average]
  (min, avg, max) = (3.330, 3.440, 3.503), stdev = 0.096
  CI (99.9%): [1.686, 5.195] (assumes normal distribution)


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
# Warmup Iteration   1: 5.529 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.003 ms/op
Iteration   1: 3.643 ±(99.9%) 0.004 ms/op
Iteration   2: 3.711 ±(99.9%) 0.003 ms/op
Iteration   3: 3.668 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.674 ±(99.9%) 0.628 ms/op [Average]
  (min, avg, max) = (3.643, 3.674, 3.711), stdev = 0.034
  CI (99.9%): [3.046, 4.303] (assumes normal distribution)


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
# Warmup Iteration   1: 7.241 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.131 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.825 ±(99.9%) 0.014 ms/op
Iteration   1: 4.765 ±(99.9%) 0.020 ms/op
Iteration   2: 4.776 ±(99.9%) 0.016 ms/op
Iteration   3: 4.779 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.774 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (4.765, 4.774, 4.779), stdev = 0.007
  CI (99.9%): [4.640, 4.907] (assumes normal distribution)


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
# Warmup Iteration   1: 5.105 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.672 ±(99.9%) 0.009 ms/op
Iteration   1: 3.630 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  8.961 ms/op
                 createUser·p0.9999: 24.294 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   2: 3.682 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  9.198 ms/op
                 createUser·p0.9999: 22.401 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   3: 3.696 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  18.301 ms/op
                 createUser·p0.9999: 21.126 ms/op
                 createUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261420
  mean =      3.669 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4809 
    [ 2.500,  5.000) = 251290 
    [ 5.000,  7.500) = 4572 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.705 ms/op
     p(99.9900) =     21.730 ms/op
     p(99.9990) =     24.654 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 5.310 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.008 ms/op
Iteration   1: 3.503 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  8.597 ms/op
                 existUser·p0.9999: 15.382 ms/op
                 existUser·p1.00:   15.827 ms/op

Iteration   2: 3.364 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  8.134 ms/op
                 existUser·p0.9999: 17.907 ms/op
                 existUser·p1.00:   19.137 ms/op

Iteration   3: 3.507 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.473 ms/op
                 existUser·p0.999:  11.397 ms/op
                 existUser·p0.9999: 21.168 ms/op
                 existUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277544
  mean =      3.457 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9587 
    [ 2.500,  5.000) = 263358 
    [ 5.000,  7.500) = 3964 
    [ 7.500, 10.000) = 407 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      8.551 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     21.412 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 5.167 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.009 ms/op
Iteration   1: 3.644 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 13.675 ms/op
                 getUser·p1.00:   14.041 ms/op

Iteration   2: 3.658 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  9.044 ms/op
                 getUser·p0.9999: 16.843 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   3: 3.672 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  7.902 ms/op
                 getUser·p0.9999: 19.211 ms/op
                 getUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262450
  mean =      3.658 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 7238 
    [ 2.500,  3.750) = 156403 
    [ 3.750,  5.000) = 91557 
    [ 5.000,  6.250) = 5291 
    [ 6.250,  7.500) = 1159 
    [ 7.500,  8.750) = 480 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.943 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     18.295 ms/op
     p(99.9990) =     19.489 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 5.922 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.137 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.835 ±(99.9%) 0.015 ms/op
Iteration   1: 4.704 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  15.026 ms/op
                 listUser·p0.9999: 22.027 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   2: 4.691 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   6.005 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  18.711 ms/op
                 listUser·p0.9999: 21.928 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   3: 4.745 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.947 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  28.901 ms/op
                 listUser·p0.9999: 31.883 ms/op
                 listUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203507
  mean =      4.713 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 460 
    [ 2.500,  5.000) = 155805 
    [ 5.000,  7.500) = 42042 
    [ 7.500, 10.000) = 4409 
    [10.000, 12.500) = 438 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.956 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     19.791 ms/op
     p(99.9900) =     30.889 ms/op
     p(99.9990) =     32.502 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.990 ± 3.033  ops/ms
ClientGrpc.existUser                       thrpt       3   9.372 ± 1.426  ops/ms
ClientGrpc.getUser                         thrpt       3   9.052 ± 1.497  ops/ms
ClientGrpc.listUser                        thrpt       3   7.072 ± 2.215  ops/ms
ClientGrpc.createUser                       avgt       3   3.428 ± 0.194   ms/op
ClientGrpc.existUser                        avgt       3   3.440 ± 1.754   ms/op
ClientGrpc.getUser                          avgt       3   3.674 ± 0.628   ms/op
ClientGrpc.listUser                         avgt       3   4.774 ± 0.133   ms/op
ClientGrpc.createUser                     sample  261420   3.669 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.827           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.705           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.730           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.740           ms/op
ClientGrpc.existUser                      sample  277544   3.457 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.868           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.014           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.505           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.551           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.103           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.692           ms/op
ClientGrpc.getUser                        sample  262450   3.658 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.844           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.661           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.943           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.552           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.295           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.595           ms/op
ClientGrpc.listUser                       sample  203507   4.713 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.262           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.791           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.889           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.899           ms/op
