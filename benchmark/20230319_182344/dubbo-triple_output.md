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
# Warmup Iteration   1: 1.740 ops/ms
# Warmup Iteration   2: 4.192 ops/ms
# Warmup Iteration   3: 7.777 ops/ms
Iteration   1: 7.944 ops/ms
Iteration   2: 8.487 ops/ms
Iteration   3: 8.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.377 ±(99.9%) 7.116 ops/ms [Average]
  (min, avg, max) = (7.944, 8.377, 8.700), stdev = 0.390
  CI (99.9%): [1.261, 15.493] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.416 ops/ms
# Warmup Iteration   2: 6.856 ops/ms
# Warmup Iteration   3: 8.194 ops/ms
Iteration   1: 8.644 ops/ms
Iteration   2: 8.565 ops/ms
Iteration   3: 8.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.682 ±(99.9%) 2.554 ops/ms [Average]
  (min, avg, max) = (8.565, 8.682, 8.837), stdev = 0.140
  CI (99.9%): [6.128, 11.236] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.295 ops/ms
# Warmup Iteration   2: 6.940 ops/ms
# Warmup Iteration   3: 7.618 ops/ms
Iteration   1: 8.244 ops/ms
Iteration   2: 8.163 ops/ms
Iteration   3: 8.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.207 ±(99.9%) 0.754 ops/ms [Average]
  (min, avg, max) = (8.163, 8.207, 8.244), stdev = 0.041
  CI (99.9%): [7.454, 8.961] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.199 ops/ms
# Warmup Iteration   2: 6.429 ops/ms
# Warmup Iteration   3: 6.823 ops/ms
Iteration   1: 7.086 ops/ms
Iteration   2: 7.083 ops/ms
Iteration   3: 7.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.129 ±(99.9%) 1.420 ops/ms [Average]
  (min, avg, max) = (7.083, 7.129, 7.219), stdev = 0.078
  CI (99.9%): [5.710, 8.549] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.056 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.176 ±(99.9%) 0.004 ms/op
Iteration   1: 3.759 ±(99.9%) 0.008 ms/op
Iteration   2: 3.820 ±(99.9%) 0.008 ms/op
Iteration   3: 3.708 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.762 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.708, 3.762, 3.820), stdev = 0.056
  CI (99.9%): [2.737, 4.787] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.546 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.003 ms/op
Iteration   1: 3.634 ±(99.9%) 0.007 ms/op
Iteration   2: 3.614 ±(99.9%) 0.007 ms/op
Iteration   3: 3.677 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.642 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.614, 3.642, 3.677), stdev = 0.032
  CI (99.9%): [3.052, 4.232] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.129 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.010 ms/op
Iteration   1: 3.937 ±(99.9%) 0.006 ms/op
Iteration   2: 3.745 ±(99.9%) 0.007 ms/op
Iteration   3: 3.707 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.796 ±(99.9%) 2.247 ms/op [Average]
  (min, avg, max) = (3.707, 3.796, 3.937), stdev = 0.123
  CI (99.9%): [1.550, 6.043] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.691 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.640 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.627 ±(99.9%) 0.011 ms/op
Iteration   1: 4.599 ±(99.9%) 0.012 ms/op
Iteration   2: 4.377 ±(99.9%) 0.012 ms/op
Iteration   3: 4.169 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.382 ±(99.9%) 3.919 ms/op [Average]
  (min, avg, max) = (4.169, 4.382, 4.599), stdev = 0.215
  CI (99.9%): [0.463, 8.301] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.367 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.531 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.016 ms/op
Iteration   1: 3.825 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  21.729 ms/op
                 createUser·p0.9999: 25.261 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   2: 3.712 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  18.373 ms/op
                 createUser·p0.9999: 26.391 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   3: 3.679 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  24.546 ms/op
                 createUser·p0.9999: 39.059 ms/op
                 createUser·p1.00:   39.322 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 256683
  mean =      3.738 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1420 
    [ 2.500,  5.000) = 248304 
    [ 5.000,  7.500) = 5718 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     19.914 ms/op
     p(99.9900) =     38.207 ms/op
     p(99.9990) =     39.256 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.136 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.009 ms/op
Iteration   1: 3.725 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.860 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  10.523 ms/op
                 existUser·p0.9999: 26.189 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   2: 3.973 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   7.266 ms/op
                 existUser·p0.999:  24.560 ms/op
                 existUser·p0.9999: 33.094 ms/op
                 existUser·p1.00:   34.013 ms/op

Iteration   3: 3.747 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.878 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  16.831 ms/op
                 existUser·p0.9999: 30.767 ms/op
                 existUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251889
  mean =      3.812 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1447 
    [ 2.500,  5.000) = 240245 
    [ 5.000,  7.500) = 8665 
    [ 7.500, 10.000) = 1154 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.170 ms/op
     p(99.9900) =     31.674 ms/op
     p(99.9990) =     33.746 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.055 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.017 ms/op
Iteration   1: 4.057 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.731 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   7.512 ms/op
                 getUser·p0.999:  11.442 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   2: 3.749 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   5.914 ms/op
                 getUser·p0.999:  24.861 ms/op
                 getUser·p0.9999: 32.030 ms/op
                 getUser·p1.00:   32.899 ms/op

Iteration   3: 3.965 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.382 ms/op
                 getUser·p0.99:   7.668 ms/op
                 getUser·p0.999:  25.592 ms/op
                 getUser·p0.9999: 30.800 ms/op
                 getUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244823
  mean =      3.919 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1163 
    [ 2.500,  5.000) = 230841 
    [ 5.000,  7.500) = 10858 
    [ 7.500, 10.000) = 1468 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     23.069 ms/op
     p(99.9900) =     31.212 ms/op
     p(99.9990) =     32.767 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.890 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 4.883 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.487 ±(99.9%) 0.014 ms/op
Iteration   1: 4.321 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   4.227 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  21.496 ms/op
                 listUser·p0.9999: 25.697 ms/op
                 listUser·p1.00:   26.378 ms/op

Iteration   2: 4.508 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  17.145 ms/op
                 listUser·p0.9999: 20.412 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 4.506 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  16.522 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 215818
  mean =      4.443 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 197310 
    [ 5.000,  7.500) = 14829 
    [ 7.500, 10.000) = 2654 
    [10.000, 12.500) = 471 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     19.220 ms/op
     p(99.9900) =     24.486 ms/op
     p(99.9990) =     26.214 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.377 ± 7.116  ops/ms
ClientPb.existUser                       thrpt       3   8.682 ± 2.554  ops/ms
ClientPb.getUser                         thrpt       3   8.207 ± 0.754  ops/ms
ClientPb.listUser                        thrpt       3   7.129 ± 1.420  ops/ms
ClientPb.createUser                       avgt       3   3.762 ± 1.025   ms/op
ClientPb.existUser                        avgt       3   3.642 ± 0.590   ms/op
ClientPb.getUser                          avgt       3   3.796 ± 2.247   ms/op
ClientPb.listUser                         avgt       3   4.382 ± 3.919   ms/op
ClientPb.createUser                     sample  256683   3.738 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.425           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.641           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.250           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.914           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.207           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.322           ms/op
ClientPb.existUser                      sample  251889   3.812 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.857           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.833           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.170           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.674           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.013           ms/op
ClientPb.getUser                        sample  244823   3.919 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.284           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.046           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.168           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.069           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.212           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.391           ms/op
ClientPb.listUser                       sample  215818   4.443 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.290           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.167           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.220           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.486           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.378           ms/op
