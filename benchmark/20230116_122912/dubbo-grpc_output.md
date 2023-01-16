# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.235 ops/ms
# Warmup Iteration   2: 7.458 ops/ms
# Warmup Iteration   3: 8.406 ops/ms
Iteration   1: 8.992 ops/ms
Iteration   2: 9.430 ops/ms
Iteration   3: 8.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.102 ±(99.9%) 5.268 ops/ms [Average]
  (min, avg, max) = (8.884, 9.102, 9.430), stdev = 0.289
  CI (99.9%): [3.834, 14.370] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.274 ops/ms
# Warmup Iteration   2: 9.005 ops/ms
# Warmup Iteration   3: 9.214 ops/ms
Iteration   1: 9.215 ops/ms
Iteration   2: 9.373 ops/ms
Iteration   3: 9.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.432 ±(99.9%) 4.572 ops/ms [Average]
  (min, avg, max) = (9.215, 9.432, 9.706), stdev = 0.251
  CI (99.9%): [4.860, 14.003] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.348 ops/ms
# Warmup Iteration   2: 8.795 ops/ms
# Warmup Iteration   3: 8.769 ops/ms
Iteration   1: 8.868 ops/ms
Iteration   2: 9.285 ops/ms
Iteration   3: 9.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.070 ±(99.9%) 3.806 ops/ms [Average]
  (min, avg, max) = (8.868, 9.070, 9.285), stdev = 0.209
  CI (99.9%): [5.264, 12.876] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.826 ops/ms
# Warmup Iteration   2: 6.702 ops/ms
# Warmup Iteration   3: 6.346 ops/ms
Iteration   1: 6.700 ops/ms
Iteration   2: 6.665 ops/ms
Iteration   3: 6.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.648 ±(99.9%) 1.121 ops/ms [Average]
  (min, avg, max) = (6.580, 6.648, 6.700), stdev = 0.061
  CI (99.9%): [5.527, 7.770] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.157 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.003 ms/op
Iteration   1: 3.673 ±(99.9%) 0.007 ms/op
Iteration   2: 3.601 ±(99.9%) 0.002 ms/op
Iteration   3: 3.590 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.621 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (3.590, 3.621, 3.673), stdev = 0.045
  CI (99.9%): [2.797, 4.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.334 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.002 ms/op
Iteration   1: 3.486 ±(99.9%) 0.002 ms/op
Iteration   2: 3.512 ±(99.9%) 0.001 ms/op
Iteration   3: 3.349 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.449 ±(99.9%) 1.595 ms/op [Average]
  (min, avg, max) = (3.349, 3.449, 3.512), stdev = 0.087
  CI (99.9%): [1.854, 5.044] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.958 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.003 ms/op
Iteration   1: 3.654 ±(99.9%) 0.002 ms/op
Iteration   2: 3.530 ±(99.9%) 0.002 ms/op
Iteration   3: 3.716 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.633 ±(99.9%) 1.728 ms/op [Average]
  (min, avg, max) = (3.530, 3.633, 3.716), stdev = 0.095
  CI (99.9%): [1.905, 5.361] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.568 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.949 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.030 ±(99.9%) 0.008 ms/op
Iteration   1: 4.598 ±(99.9%) 0.007 ms/op
Iteration   2: 4.512 ±(99.9%) 0.019 ms/op
Iteration   3: 4.497 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.535 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (4.497, 4.535, 4.598), stdev = 0.054
  CI (99.9%): [3.546, 5.525] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.144 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.010 ms/op
Iteration   1: 3.428 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  8.767 ms/op
                 createUser·p0.9999: 17.138 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   2: 3.479 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  8.250 ms/op
                 createUser·p0.9999: 27.584 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   3: 3.607 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  10.645 ms/op
                 createUser·p0.9999: 20.657 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 273990
  mean =      3.503 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14289 
    [ 2.500,  5.000) = 252656 
    [ 5.000,  7.500) = 6400 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     26.824 ms/op
     p(99.9990) =     28.132 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.595 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.008 ms/op
Iteration   1: 3.461 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  9.306 ms/op
                 existUser·p0.9999: 14.926 ms/op
                 existUser·p1.00:   15.237 ms/op

Iteration   2: 3.436 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  10.090 ms/op
                 existUser·p0.9999: 15.910 ms/op
                 existUser·p1.00:   16.761 ms/op

Iteration   3: 3.554 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  10.090 ms/op
                 existUser·p0.9999: 18.677 ms/op
                 existUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275554
  mean =      3.483 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 567 
    [ 1.250,  2.500) = 22860 
    [ 2.500,  3.750) = 157653 
    [ 3.750,  5.000) = 85566 
    [ 5.000,  6.250) = 7321 
    [ 6.250,  7.500) = 944 
    [ 7.500,  8.750) = 291 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     16.544 ms/op
     p(99.9990) =     19.120 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.833 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.011 ms/op
Iteration   1: 3.715 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  10.826 ms/op
                 getUser·p0.9999: 21.939 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   2: 3.762 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.800 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  12.764 ms/op
                 getUser·p0.9999: 19.841 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   3: 3.841 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.399 ms/op
                 getUser·p0.99:   6.609 ms/op
                 getUser·p0.999:  9.679 ms/op
                 getUser·p0.9999: 27.012 ms/op
                 getUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254432
  mean =      3.772 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8120 
    [ 2.500,  5.000) = 226898 
    [ 5.000,  7.500) = 18393 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     11.158 ms/op
     p(99.9900) =     24.875 ms/op
     p(99.9990) =     27.242 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.383 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.946 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.727 ±(99.9%) 0.015 ms/op
Iteration   1: 4.612 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.733 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  13.156 ms/op
                 listUser·p0.9999: 15.999 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   2: 4.476 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   6.570 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  14.534 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 4.695 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  20.050 ms/op
                 listUser·p0.9999: 26.745 ms/op
                 listUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208929
  mean =      4.593 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 409 
    [ 2.500,  5.000) = 158504 
    [ 5.000,  7.500) = 45597 
    [ 7.500, 10.000) = 3677 
    [10.000, 12.500) = 338 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.972 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      8.380 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     26.185 ms/op
     p(99.9990) =     28.058 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.102 ± 5.268  ops/ms
ClientGrpc.existUser                       thrpt       3   9.432 ± 4.572  ops/ms
ClientGrpc.getUser                         thrpt       3   9.070 ± 3.806  ops/ms
ClientGrpc.listUser                        thrpt       3   6.648 ± 1.121  ops/ms
ClientGrpc.createUser                       avgt       3   3.621 ± 0.824   ms/op
ClientGrpc.existUser                        avgt       3   3.449 ± 1.595   ms/op
ClientGrpc.getUser                          avgt       3   3.633 ± 1.728   ms/op
ClientGrpc.listUser                         avgt       3   4.535 ± 0.990   ms/op
ClientGrpc.createUser                     sample  273990   3.503 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.767           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.428           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.339           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.824           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.279           ms/op
ClientGrpc.existUser                      sample  275554   3.483 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.819           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.726           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.519           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.544           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.268           ms/op
ClientGrpc.getUser                        sample  254432   3.772 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.637           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.850           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.243           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.316           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.158           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.875           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.394           ms/op
ClientGrpc.listUser                       sample  208929   4.593 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.948           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.391           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.972           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.380           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.335           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.185           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.312           ms/op
