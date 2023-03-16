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
# Warmup Iteration   1: 3.174 ops/ms
# Warmup Iteration   2: 6.615 ops/ms
# Warmup Iteration   3: 7.805 ops/ms
Iteration   1: 8.430 ops/ms
Iteration   2: 8.551 ops/ms
Iteration   3: 8.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.516 ±(99.9%) 1.370 ops/ms [Average]
  (min, avg, max) = (8.430, 8.516, 8.568), stdev = 0.075
  CI (99.9%): [7.146, 9.886] (assumes normal distribution)


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
# Warmup Iteration   1: 5.872 ops/ms
# Warmup Iteration   2: 8.404 ops/ms
# Warmup Iteration   3: 9.021 ops/ms
Iteration   1: 9.138 ops/ms
Iteration   2: 9.250 ops/ms
Iteration   3: 9.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.199 ±(99.9%) 1.027 ops/ms [Average]
  (min, avg, max) = (9.138, 9.199, 9.250), stdev = 0.056
  CI (99.9%): [8.172, 10.226] (assumes normal distribution)


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
# Warmup Iteration   1: 5.178 ops/ms
# Warmup Iteration   2: 7.999 ops/ms
# Warmup Iteration   3: 8.520 ops/ms
Iteration   1: 8.709 ops/ms
Iteration   2: 8.644 ops/ms
Iteration   3: 8.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.601 ±(99.9%) 2.471 ops/ms [Average]
  (min, avg, max) = (8.449, 8.601, 8.709), stdev = 0.135
  CI (99.9%): [6.130, 11.071] (assumes normal distribution)


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
# Warmup Iteration   1: 4.846 ops/ms
# Warmup Iteration   2: 6.056 ops/ms
# Warmup Iteration   3: 6.638 ops/ms
Iteration   1: 6.644 ops/ms
Iteration   2: 6.683 ops/ms
Iteration   3: 6.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.669 ±(99.9%) 0.400 ops/ms [Average]
  (min, avg, max) = (6.644, 6.669, 6.683), stdev = 0.022
  CI (99.9%): [6.269, 7.070] (assumes normal distribution)


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
# Warmup Iteration   1: 5.459 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.017 ms/op
Iteration   1: 3.659 ±(99.9%) 0.003 ms/op
Iteration   2: 3.670 ±(99.9%) 0.003 ms/op
Iteration   3: 3.621 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.650 ±(99.9%) 0.467 ms/op [Average]
  (min, avg, max) = (3.621, 3.650, 3.670), stdev = 0.026
  CI (99.9%): [3.182, 4.117] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.139 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.004 ms/op
Iteration   1: 3.537 ±(99.9%) 0.003 ms/op
Iteration   2: 3.518 ±(99.9%) 0.003 ms/op
Iteration   3: 3.536 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.531 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.518, 3.531, 3.537), stdev = 0.011
  CI (99.9%): [3.331, 3.730] (assumes normal distribution)


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
# Warmup Iteration   1: 5.742 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.004 ms/op
Iteration   1: 3.767 ±(99.9%) 0.004 ms/op
Iteration   2: 3.708 ±(99.9%) 0.003 ms/op
Iteration   3: 3.723 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.733 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.708, 3.733, 3.767), stdev = 0.031
  CI (99.9%): [3.172, 4.294] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.190 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.962 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.861 ±(99.9%) 0.021 ms/op
Iteration   1: 4.761 ±(99.9%) 0.013 ms/op
Iteration   2: 4.685 ±(99.9%) 0.021 ms/op
Iteration   3: 4.743 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.730 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (4.685, 4.730, 4.761), stdev = 0.040
  CI (99.9%): [4.006, 5.453] (assumes normal distribution)


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
# Warmup Iteration   1: 5.233 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.009 ms/op
Iteration   1: 3.672 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.529 ms/op
                 createUser·p0.999:  8.434 ms/op
                 createUser·p0.9999: 15.427 ms/op
                 createUser·p1.00:   15.778 ms/op

Iteration   2: 3.788 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.040 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  13.067 ms/op
                 createUser·p0.9999: 20.353 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   3: 3.698 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  15.041 ms/op
                 createUser·p0.9999: 23.451 ms/op
                 createUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258247
  mean =      3.718 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4551 
    [ 2.500,  5.000) = 247050 
    [ 5.000,  7.500) = 5959 
    [ 7.500, 10.000) = 356 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     11.108 ms/op
     p(99.9900) =     22.326 ms/op
     p(99.9990) =     27.828 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.017 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.008 ms/op
Iteration   1: 3.587 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  9.568 ms/op
                 existUser·p0.9999: 14.829 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   2: 3.599 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  8.999 ms/op
                 existUser·p0.9999: 16.289 ms/op
                 existUser·p1.00:   16.597 ms/op

Iteration   3: 3.592 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  7.601 ms/op
                 existUser·p0.9999: 25.494 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267345
  mean =      3.593 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5530 
    [ 2.500,  5.000) = 256622 
    [ 5.000,  7.500) = 4666 
    [ 7.500, 10.000) = 362 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     25.338 ms/op
     p(99.9990) =     25.667 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 5.352 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.010 ms/op
Iteration   1: 3.729 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   5.943 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 18.397 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   2: 3.783 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  11.951 ms/op
                 getUser·p0.9999: 27.513 ms/op
                 getUser·p1.00:   28.770 ms/op

Iteration   3: 3.730 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   5.829 ms/op
                 getUser·p0.999:  8.571 ms/op
                 getUser·p0.9999: 23.364 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256111
  mean =      3.747 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5328 
    [ 2.500,  5.000) = 242949 
    [ 5.000,  7.500) = 7134 
    [ 7.500, 10.000) = 477 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =      9.485 ms/op
     p(99.9900) =     25.788 ms/op
     p(99.9990) =     28.529 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 6.533 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.212 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.926 ±(99.9%) 0.015 ms/op
Iteration   1: 4.836 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.675 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.988 ms/op
                 listUser·p0.95:   6.842 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  15.871 ms/op
                 listUser·p0.9999: 27.956 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   2: 4.919 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   7.094 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  16.466 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   3: 4.928 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.226 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  20.482 ms/op
                 listUser·p0.9999: 31.245 ms/op
                 listUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196085
  mean =      4.894 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 158 
    [ 2.500,  5.000) = 137011 
    [ 5.000,  7.500) = 52029 
    [ 7.500, 10.000) = 5873 
    [10.000, 12.500) = 596 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      7.029 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     31.985 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.516 ± 1.370  ops/ms
ClientGrpc.existUser                       thrpt       3   9.199 ± 1.027  ops/ms
ClientGrpc.getUser                         thrpt       3   8.601 ± 2.471  ops/ms
ClientGrpc.listUser                        thrpt       3   6.669 ± 0.400  ops/ms
ClientGrpc.createUser                       avgt       3   3.650 ± 0.467   ms/op
ClientGrpc.existUser                        avgt       3   3.531 ± 0.199   ms/op
ClientGrpc.getUser                          avgt       3   3.733 ± 0.561   ms/op
ClientGrpc.listUser                         avgt       3   4.730 ± 0.723   ms/op
ClientGrpc.createUser                     sample  258247   3.718 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.952           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.636           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.108           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.326           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.049           ms/op
ClientGrpc.existUser                      sample  267345   3.593 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.644           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.995           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.338           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.919           ms/op
ClientGrpc.getUser                        sample  256111   3.747 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.942           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.972           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.485           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.788           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.770           ms/op
ClientGrpc.listUser                       sample  196085   4.894 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.069           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.978           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.760           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.229           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.080           ms/op
