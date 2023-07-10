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
# Warmup Iteration   1: 4.636 ops/ms
# Warmup Iteration   2: 9.479 ops/ms
# Warmup Iteration   3: 10.183 ops/ms
Iteration   1: 10.653 ops/ms
Iteration   2: 10.624 ops/ms
Iteration   3: 10.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.681 ±(99.9%) 1.383 ops/ms [Average]
  (min, avg, max) = (10.624, 10.681, 10.767), stdev = 0.076
  CI (99.9%): [9.298, 12.065] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.443 ops/ms
# Warmup Iteration   2: 10.733 ops/ms
# Warmup Iteration   3: 11.106 ops/ms
Iteration   1: 11.136 ops/ms
Iteration   2: 11.348 ops/ms
Iteration   3: 11.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.243 ±(99.9%) 1.935 ops/ms [Average]
  (min, avg, max) = (11.136, 11.243, 11.348), stdev = 0.106
  CI (99.9%): [9.308, 13.179] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.469 ops/ms
# Warmup Iteration   2: 10.416 ops/ms
# Warmup Iteration   3: 10.731 ops/ms
Iteration   1: 10.592 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.643 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (10.592, 10.643, 10.737), stdev = 0.082
  CI (99.9%): [9.148, 12.137] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.170 ops/ms
# Warmup Iteration   2: 7.898 ops/ms
# Warmup Iteration   3: 8.138 ops/ms
Iteration   1: 8.188 ops/ms
Iteration   2: 8.421 ops/ms
Iteration   3: 8.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.313 ±(99.9%) 2.145 ops/ms [Average]
  (min, avg, max) = (8.188, 8.313, 8.421), stdev = 0.118
  CI (99.9%): [6.168, 10.458] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.003 ms/op
Iteration   1: 2.992 ±(99.9%) 0.007 ms/op
Iteration   2: 3.014 ±(99.9%) 0.003 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.999 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.992, 2.999, 3.014), stdev = 0.013
  CI (99.9%): [2.769, 3.230] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.491 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.841 ±(99.9%) 0.003 ms/op
Iteration   1: 2.865 ±(99.9%) 0.003 ms/op
Iteration   2: 2.821 ±(99.9%) 0.003 ms/op
Iteration   3: 2.884 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.857 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (2.821, 2.857, 2.884), stdev = 0.032
  CI (99.9%): [2.265, 3.448] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.141 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.003 ms/op
Iteration   1: 2.991 ±(99.9%) 0.002 ms/op
Iteration   2: 3.009 ±(99.9%) 0.002 ms/op
Iteration   3: 2.970 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.990 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.970, 2.990, 3.009), stdev = 0.020
  CI (99.9%): [2.630, 3.350] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.026 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.018 ms/op
Iteration   1: 3.895 ±(99.9%) 0.011 ms/op
Iteration   2: 3.883 ±(99.9%) 0.008 ms/op
Iteration   3: 3.873 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.884 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (3.873, 3.884, 3.895), stdev = 0.011
  CI (99.9%): [3.690, 4.078] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.089 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.353 ms/op
                 createUser·p0.9999: 14.418 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.360 ms/op
                 createUser·p0.999:  10.715 ms/op
                 createUser·p0.9999: 14.061 ms/op
                 createUser·p1.00:   15.172 ms/op

Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.515 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 27.866 ms/op
                 createUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317570
  mean =      3.022 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22777 
    [ 2.500,  5.000) = 293009 
    [ 5.000,  7.500) = 1290 
    [ 7.500, 10.000) = 189 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     26.926 ms/op
     p(99.9990) =     28.136 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.818 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.904 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.007 ms/op
Iteration   1: 2.814 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.013 ms/op
                 existUser·p0.9999: 17.683 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   2: 2.872 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  9.748 ms/op
                 existUser·p0.9999: 20.611 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   3: 2.823 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.264 ms/op
                 existUser·p0.9999: 25.319 ms/op
                 existUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338240
  mean =      2.836 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51246 
    [ 2.500,  5.000) = 285782 
    [ 5.000,  7.500) = 760 
    [ 7.500, 10.000) = 231 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.281 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     23.899 ms/op
     p(99.9990) =     25.645 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
Iteration   1: 3.008 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  9.776 ms/op
                 getUser·p0.9999: 23.736 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   2: 3.009 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.975 ms/op
                 getUser·p0.9999: 22.020 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   3: 3.017 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.436 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  9.486 ms/op
                 getUser·p0.9999: 34.341 ms/op
                 getUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318571
  mean =      3.011 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25704 
    [ 2.500,  5.000) = 291452 
    [ 5.000,  7.500) = 983 
    [ 7.500, 10.000) = 186 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     31.705 ms/op
     p(99.9990) =     34.722 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.011 ms/op
Iteration   1: 3.860 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.524 ms/op
                 listUser·p0.999:  12.599 ms/op
                 listUser·p0.9999: 15.902 ms/op
                 listUser·p1.00:   16.744 ms/op

Iteration   2: 3.826 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  12.878 ms/op
                 listUser·p0.9999: 14.755 ms/op
                 listUser·p1.00:   15.974 ms/op

Iteration   3: 3.871 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  16.509 ms/op
                 listUser·p0.9999: 22.011 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249129
  mean =      3.852 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4203 
    [ 2.500,  5.000) = 227292 
    [ 5.000,  7.500) = 16541 
    [ 7.500, 10.000) = 546 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     13.367 ms/op
     p(99.9900) =     21.204 ms/op
     p(99.9990) =     22.398 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.681 ± 1.383  ops/ms
ClientGrpc.existUser                       thrpt       3  11.243 ± 1.935  ops/ms
ClientGrpc.getUser                         thrpt       3  10.643 ± 1.495  ops/ms
ClientGrpc.listUser                        thrpt       3   8.313 ± 2.145  ops/ms
ClientGrpc.createUser                       avgt       3   2.999 ± 0.230   ms/op
ClientGrpc.existUser                        avgt       3   2.857 ± 0.591   ms/op
ClientGrpc.getUser                          avgt       3   2.990 ± 0.360   ms/op
ClientGrpc.listUser                         avgt       3   3.884 ± 0.194   ms/op
ClientGrpc.createUser                     sample  317570   3.022 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.572           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.454           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.926           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.279           ms/op
ClientGrpc.existUser                      sample  338240   2.836 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.553           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.281           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.175           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.899           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.756           ms/op
ClientGrpc.getUser                        sample  318571   3.011 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.436           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.306           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.705           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.800           ms/op
ClientGrpc.listUser                       sample  249129   3.852 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.848           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.367           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.204           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
