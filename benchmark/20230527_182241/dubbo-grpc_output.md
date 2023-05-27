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
# Warmup Iteration   1: 3.239 ops/ms
# Warmup Iteration   2: 6.988 ops/ms
# Warmup Iteration   3: 8.344 ops/ms
Iteration   1: 8.953 ops/ms
Iteration   2: 8.928 ops/ms
Iteration   3: 9.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.979 ±(99.9%) 1.240 ops/ms [Average]
  (min, avg, max) = (8.928, 8.979, 9.056), stdev = 0.068
  CI (99.9%): [7.739, 10.218] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.256 ops/ms
# Warmup Iteration   2: 8.860 ops/ms
# Warmup Iteration   3: 9.321 ops/ms
Iteration   1: 9.128 ops/ms
Iteration   2: 9.400 ops/ms
Iteration   3: 9.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.297 ±(99.9%) 2.693 ops/ms [Average]
  (min, avg, max) = (9.128, 9.297, 9.400), stdev = 0.148
  CI (99.9%): [6.605, 11.990] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.636 ops/ms
# Warmup Iteration   2: 8.736 ops/ms
# Warmup Iteration   3: 8.849 ops/ms
Iteration   1: 9.165 ops/ms
Iteration   2: 9.366 ops/ms
Iteration   3: 9.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.189 ±(99.9%) 3.033 ops/ms [Average]
  (min, avg, max) = (9.036, 9.189, 9.366), stdev = 0.166
  CI (99.9%): [6.156, 12.222] (assumes normal distribution)


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
# Warmup Iteration   1: 4.174 ops/ms
# Warmup Iteration   2: 6.405 ops/ms
# Warmup Iteration   3: 6.809 ops/ms
Iteration   1: 7.094 ops/ms
Iteration   2: 7.118 ops/ms
Iteration   3: 6.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.051 ±(99.9%) 1.757 ops/ms [Average]
  (min, avg, max) = (6.941, 7.051, 7.118), stdev = 0.096
  CI (99.9%): [5.294, 8.808] (assumes normal distribution)


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
# Warmup Iteration   1: 5.181 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.004 ms/op
Iteration   1: 3.540 ±(99.9%) 0.003 ms/op
Iteration   2: 3.564 ±(99.9%) 0.004 ms/op
Iteration   3: 3.564 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.556 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (3.540, 3.556, 3.564), stdev = 0.014
  CI (99.9%): [3.307, 3.805] (assumes normal distribution)


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
# Warmup Iteration   1: 4.726 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.002 ms/op
Iteration   1: 3.389 ±(99.9%) 0.002 ms/op
Iteration   2: 3.377 ±(99.9%) 0.003 ms/op
Iteration   3: 3.392 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.386 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (3.377, 3.386, 3.392), stdev = 0.008
  CI (99.9%): [3.236, 3.537] (assumes normal distribution)


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
# Warmup Iteration   1: 4.906 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.003 ms/op
Iteration   1: 3.531 ±(99.9%) 0.004 ms/op
Iteration   2: 3.501 ±(99.9%) 0.003 ms/op
Iteration   3: 3.445 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.492 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.445, 3.492, 3.531), stdev = 0.044
  CI (99.9%): [2.695, 4.290] (assumes normal distribution)


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
# Warmup Iteration   1: 6.028 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.856 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.579 ±(99.9%) 0.015 ms/op
Iteration   1: 4.614 ±(99.9%) 0.018 ms/op
Iteration   2: 4.744 ±(99.9%) 0.020 ms/op
Iteration   3: 4.754 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.704 ±(99.9%) 1.422 ms/op [Average]
  (min, avg, max) = (4.614, 4.704, 4.754), stdev = 0.078
  CI (99.9%): [3.282, 6.127] (assumes normal distribution)


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
# Warmup Iteration   1: 5.028 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.008 ms/op
Iteration   1: 3.592 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.589 ms/op
                 createUser·p0.999:  11.960 ms/op
                 createUser·p0.9999: 15.632 ms/op
                 createUser·p1.00:   15.811 ms/op

Iteration   2: 3.571 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 17.239 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   3: 3.634 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  9.911 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 266661
  mean =      3.599 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9101 
    [ 2.500,  5.000) = 248642 
    [ 5.000,  7.500) = 7637 
    [ 7.500, 10.000) = 971 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     11.343 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     20.491 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.010 ms/op
Iteration   1: 3.347 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  8.690 ms/op
                 existUser·p0.9999: 16.410 ms/op
                 existUser·p1.00:   17.629 ms/op

Iteration   2: 3.488 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  9.343 ms/op
                 existUser·p0.9999: 17.891 ms/op
                 existUser·p1.00:   18.252 ms/op

Iteration   3: 3.282 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  9.247 ms/op
                 existUser·p0.9999: 33.620 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 284742
  mean =      3.370 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18454 
    [ 2.500,  5.000) = 260007 
    [ 5.000,  7.500) = 5528 
    [ 7.500, 10.000) = 541 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =      9.081 ms/op
     p(99.9900) =     33.065 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 5.092 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.009 ms/op
Iteration   1: 3.578 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  9.519 ms/op
                 getUser·p0.9999: 15.615 ms/op
                 getUser·p1.00:   15.794 ms/op

Iteration   2: 3.564 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  8.221 ms/op
                 getUser·p0.9999: 19.694 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   3: 3.575 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  10.586 ms/op
                 getUser·p0.9999: 22.151 ms/op
                 getUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268543
  mean =      3.573 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8009 
    [ 2.500,  5.000) = 252248 
    [ 5.000,  7.500) = 7381 
    [ 7.500, 10.000) = 694 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 6.545 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.818 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.609 ±(99.9%) 0.016 ms/op
Iteration   1: 4.607 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.554 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  15.386 ms/op
                 listUser·p0.9999: 18.549 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   2: 4.496 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.658 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  17.232 ms/op
                 listUser·p0.9999: 21.252 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   3: 4.637 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   6.013 ms/op
                 listUser·p0.95:   6.840 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  22.086 ms/op
                 listUser·p0.9999: 28.180 ms/op
                 listUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 209535
  mean =      4.579 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 938 
    [ 2.500,  5.000) = 161020 
    [ 5.000,  7.500) = 42506 
    [ 7.500, 10.000) = 4152 
    [10.000, 12.500) = 482 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      6.701 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     17.839 ms/op
     p(99.9900) =     27.002 ms/op
     p(99.9990) =     28.513 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.979 ± 1.240  ops/ms
ClientGrpc.existUser                       thrpt       3   9.297 ± 2.693  ops/ms
ClientGrpc.getUser                         thrpt       3   9.189 ± 3.033  ops/ms
ClientGrpc.listUser                        thrpt       3   7.051 ± 1.757  ops/ms
ClientGrpc.createUser                       avgt       3   3.556 ± 0.249   ms/op
ClientGrpc.existUser                        avgt       3   3.386 ± 0.150   ms/op
ClientGrpc.getUser                          avgt       3   3.492 ± 0.798   ms/op
ClientGrpc.listUser                         avgt       3   4.704 ± 1.422   ms/op
ClientGrpc.createUser                     sample  266661   3.599 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.948           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.201           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.343           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.726           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.758           ms/op
ClientGrpc.existUser                      sample  284742   3.370 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.778           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.084           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.743           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.081           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.065           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.948           ms/op
ClientGrpc.getUser                        sample  268543   3.573 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.755           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.988           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.175           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.758           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.282           ms/op
ClientGrpc.listUser                       sample  209535   4.579 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.658           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.342           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.602           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.839           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.002           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.574           ms/op
