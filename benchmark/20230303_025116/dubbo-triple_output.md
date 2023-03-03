# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.527 ops/ms
# Warmup Iteration   2: 6.440 ops/ms
# Warmup Iteration   3: 9.495 ops/ms
Iteration   1: 9.621 ops/ms
Iteration   2: 10.299 ops/ms
Iteration   3: 9.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.916 ±(99.9%) 6.345 ops/ms [Average]
  (min, avg, max) = (9.621, 9.916, 10.299), stdev = 0.348
  CI (99.9%): [3.571, 16.261] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ops/ms
# Warmup Iteration   2: 9.235 ops/ms
# Warmup Iteration   3: 9.995 ops/ms
Iteration   1: 10.165 ops/ms
Iteration   2: 10.398 ops/ms
Iteration   3: 10.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.328 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (10.165, 10.328, 10.420), stdev = 0.142
  CI (99.9%): [7.746, 12.910] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.429 ops/ms
# Warmup Iteration   2: 9.167 ops/ms
# Warmup Iteration   3: 10.113 ops/ms
Iteration   1: 9.704 ops/ms
Iteration   2: 9.749 ops/ms
Iteration   3: 9.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.768 ±(99.9%) 1.365 ops/ms [Average]
  (min, avg, max) = (9.704, 9.768, 9.850), stdev = 0.075
  CI (99.9%): [8.403, 11.133] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.360 ops/ms
# Warmup Iteration   2: 7.969 ops/ms
# Warmup Iteration   3: 8.313 ops/ms
Iteration   1: 8.702 ops/ms
Iteration   2: 8.617 ops/ms
Iteration   3: 8.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.620 ±(99.9%) 1.480 ops/ms [Average]
  (min, avg, max) = (8.540, 8.620, 8.702), stdev = 0.081
  CI (99.9%): [7.140, 10.099] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.199 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.458 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.005 ms/op
Iteration   1: 3.216 ±(99.9%) 0.007 ms/op
Iteration   2: 3.192 ±(99.9%) 0.005 ms/op
Iteration   3: 3.084 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.164 ±(99.9%) 1.285 ms/op [Average]
  (min, avg, max) = (3.084, 3.164, 3.216), stdev = 0.070
  CI (99.9%): [1.879, 4.449] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.117 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.003 ms/op
Iteration   1: 3.124 ±(99.9%) 0.003 ms/op
Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
Iteration   3: 3.141 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.133 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (3.124, 3.133, 3.141), stdev = 0.008
  CI (99.9%): [2.978, 3.287] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.172 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.006 ms/op
Iteration   1: 3.212 ±(99.9%) 0.002 ms/op
Iteration   2: 3.275 ±(99.9%) 0.002 ms/op
Iteration   3: 3.248 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.245 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (3.212, 3.245, 3.275), stdev = 0.031
  CI (99.9%): [2.677, 3.813] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.581 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.005 ms/op
Iteration   1: 3.809 ±(99.9%) 0.006 ms/op
Iteration   2: 3.765 ±(99.9%) 0.010 ms/op
Iteration   3: 3.696 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.757 ±(99.9%) 1.030 ms/op [Average]
  (min, avg, max) = (3.696, 3.757, 3.809), stdev = 0.056
  CI (99.9%): [2.727, 4.787] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.462 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
Iteration   1: 3.199 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  18.223 ms/op
                 createUser·p0.9999: 20.448 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   2: 3.231 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  18.077 ms/op
                 createUser·p0.9999: 26.743 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   3: 3.148 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.322 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  12.925 ms/op
                 createUser·p0.9999: 28.274 ms/op
                 createUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300564
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12418 
    [ 2.500,  5.000) = 282497 
    [ 5.000,  7.500) = 4573 
    [ 7.500, 10.000) = 600 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     16.162 ms/op
     p(99.9900) =     26.922 ms/op
     p(99.9990) =     28.443 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.309 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.108 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  13.144 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   19.988 ms/op

Iteration   2: 3.068 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  9.746 ms/op
                 existUser·p0.9999: 27.460 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 3.187 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  15.117 ms/op
                 existUser·p0.9999: 22.673 ms/op
                 existUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307439
  mean =      3.120 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22018 
    [ 2.500,  5.000) = 279984 
    [ 5.000,  7.500) = 4521 
    [ 7.500, 10.000) = 467 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     26.387 ms/op
     p(99.9990) =     27.621 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.962 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.483 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.010 ms/op
Iteration   1: 3.291 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  18.448 ms/op
                 getUser·p0.9999: 24.094 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  13.173 ms/op
                 getUser·p0.9999: 22.440 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 3.151 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  15.664 ms/op
                 getUser·p0.9999: 23.555 ms/op
                 getUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300465
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10621 
    [ 2.500,  5.000) = 283779 
    [ 5.000,  7.500) = 5140 
    [ 7.500, 10.000) = 400 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     16.442 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.720 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.011 ms/op
Iteration   1: 3.717 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  15.319 ms/op
                 listUser·p0.9999: 20.952 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   2: 3.751 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.038 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 3.805 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.242 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 15.554 ms/op
                 listUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255352
  mean =      3.757 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 249139 
    [ 5.000,  7.500) = 4235 
    [ 7.500, 10.000) = 1217 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 334 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.038 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     21.642 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.916 ± 6.345  ops/ms
ClientPb.existUser                       thrpt       3  10.328 ± 2.582  ops/ms
ClientPb.getUser                         thrpt       3   9.768 ± 1.365  ops/ms
ClientPb.listUser                        thrpt       3   8.620 ± 1.480  ops/ms
ClientPb.createUser                       avgt       3   3.164 ± 1.285   ms/op
ClientPb.existUser                        avgt       3   3.133 ± 0.155   ms/op
ClientPb.getUser                          avgt       3   3.245 ± 0.568   ms/op
ClientPb.listUser                         avgt       3   3.757 ± 1.030   ms/op
ClientPb.createUser                     sample  300564   3.192 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.761           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.162           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.922           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.967           ms/op
ClientPb.existUser                      sample  307439   3.120 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.868           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.371           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.467           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.387           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.722           ms/op
ClientPb.getUser                        sample  300465   3.192 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.871           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.514           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.636           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.442           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.560           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.132           ms/op
ClientPb.listUser                       sample  255352   3.757 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.038           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.808           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.254           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.792           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.151           ms/op
