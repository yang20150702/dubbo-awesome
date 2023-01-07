# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.536 ops/ms
# Warmup Iteration   2: 3.338 ops/ms
# Warmup Iteration   3: 6.753 ops/ms
Iteration   1: 7.246 ops/ms
Iteration   2: 7.533 ops/ms
Iteration   3: 7.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.459 ±(99.9%) 3.416 ops/ms [Average]
  (min, avg, max) = (7.246, 7.459, 7.597), stdev = 0.187
  CI (99.9%): [4.043, 10.874] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.236 ops/ms
# Warmup Iteration   2: 6.595 ops/ms
# Warmup Iteration   3: 8.105 ops/ms
Iteration   1: 8.019 ops/ms
Iteration   2: 8.307 ops/ms
Iteration   3: 8.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.294 ±(99.9%) 4.911 ops/ms [Average]
  (min, avg, max) = (8.019, 8.294, 8.556), stdev = 0.269
  CI (99.9%): [3.383, 13.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.396 ops/ms
# Warmup Iteration   2: 6.864 ops/ms
# Warmup Iteration   3: 7.283 ops/ms
Iteration   1: 7.732 ops/ms
Iteration   2: 7.838 ops/ms
Iteration   3: 7.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.816 ±(99.9%) 1.368 ops/ms [Average]
  (min, avg, max) = (7.732, 7.816, 7.877), stdev = 0.075
  CI (99.9%): [6.448, 9.184] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.068 ops/ms
# Warmup Iteration   2: 5.546 ops/ms
# Warmup Iteration   3: 6.420 ops/ms
Iteration   1: 6.535 ops/ms
Iteration   2: 6.851 ops/ms
Iteration   3: 6.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.727 ±(99.9%) 3.073 ops/ms [Average]
  (min, avg, max) = (6.535, 6.727, 6.851), stdev = 0.168
  CI (99.9%): [3.654, 9.799] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.587 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.768 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.008 ms/op
Iteration   1: 4.116 ±(99.9%) 0.006 ms/op
Iteration   2: 4.075 ±(99.9%) 0.007 ms/op
Iteration   3: 4.048 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.080 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (4.048, 4.080, 4.116), stdev = 0.035
  CI (99.9%): [3.450, 4.709] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.749 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.003 ms/op
Iteration   1: 3.863 ±(99.9%) 0.010 ms/op
Iteration   2: 3.897 ±(99.9%) 0.010 ms/op
Iteration   3: 3.790 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.850 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (3.790, 3.850, 3.897), stdev = 0.055
  CI (99.9%): [2.856, 4.844] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.332 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.974 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.134 ±(99.9%) 0.004 ms/op
Iteration   1: 4.198 ±(99.9%) 0.007 ms/op
Iteration   2: 3.942 ±(99.9%) 0.009 ms/op
Iteration   3: 4.106 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.082 ±(99.9%) 2.366 ms/op [Average]
  (min, avg, max) = (3.942, 4.082, 4.198), stdev = 0.130
  CI (99.9%): [1.716, 6.448] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.526 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.595 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.982 ±(99.9%) 0.006 ms/op
Iteration   1: 4.820 ±(99.9%) 0.009 ms/op
Iteration   2: 4.490 ±(99.9%) 0.016 ms/op
Iteration   3: 4.813 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.707 ±(99.9%) 3.442 ms/op [Average]
  (min, avg, max) = (4.490, 4.707, 4.820), stdev = 0.189
  CI (99.9%): [1.266, 8.149] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.226 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 5.030 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.439 ±(99.9%) 0.018 ms/op
Iteration   1: 4.114 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.817 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.382 ms/op
                 createUser·p0.99:   8.061 ms/op
                 createUser·p0.999:  22.970 ms/op
                 createUser·p0.9999: 27.860 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   2: 3.918 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.824 ms/op
                 createUser·p0.999:  16.210 ms/op
                 createUser·p0.9999: 27.126 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   3: 4.020 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   5.235 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  29.164 ms/op
                 createUser·p0.9999: 31.589 ms/op
                 createUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239050
  mean =      4.016 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 391 
    [ 2.500,  5.000) = 224822 
    [ 5.000,  7.500) = 11094 
    [ 7.500, 10.000) = 1782 
    [10.000, 12.500) = 450 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     23.034 ms/op
     p(99.9900) =     30.346 ms/op
     p(99.9990) =     31.989 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.549 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.010 ms/op
Iteration   1: 3.736 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.907 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   7.315 ms/op
                 existUser·p0.999:  11.885 ms/op
                 existUser·p0.9999: 23.196 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 4.085 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.794 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   7.660 ms/op
                 existUser·p0.999:  22.007 ms/op
                 existUser·p0.9999: 25.598 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 3.841 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.550 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   7.274 ms/op
                 existUser·p0.999:  14.941 ms/op
                 existUser·p0.9999: 26.673 ms/op
                 existUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247048
  mean =      3.882 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 465 
    [ 2.500,  5.000) = 232861 
    [ 5.000,  7.500) = 11406 
    [ 7.500, 10.000) = 1655 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     26.388 ms/op
     p(99.9990) =     26.837 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.013 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.862 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.013 ms/op
Iteration   1: 4.050 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   7.512 ms/op
                 getUser·p0.999:  23.340 ms/op
                 getUser·p0.9999: 27.379 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   2: 3.878 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.122 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  11.733 ms/op
                 getUser·p0.9999: 27.222 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   3: 3.903 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.720 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  26.550 ms/op
                 getUser·p0.9999: 30.435 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243255
  mean =      3.942 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 235621 
    [ 5.000,  7.500) = 6156 
    [ 7.500, 10.000) = 784 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 114 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     23.085 ms/op
     p(99.9900) =     29.557 ms/op
     p(99.9990) =     31.246 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.444 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.753 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.985 ±(99.9%) 0.019 ms/op
Iteration   1: 4.814 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   7.048 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  26.825 ms/op
                 listUser·p0.9999: 29.458 ms/op
                 listUser·p1.00:   30.114 ms/op

Iteration   2: 4.944 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   7.078 ms/op
                 listUser·p0.99:   9.673 ms/op
                 listUser·p0.999:  22.482 ms/op
                 listUser·p0.9999: 28.264 ms/op
                 listUser·p1.00:   28.541 ms/op

Iteration   3: 4.714 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 22.093 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198966
  mean =      4.822 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 157583 
    [ 5.000,  7.500) = 35070 
    [ 7.500, 10.000) = 4860 
    [10.000, 12.500) = 642 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 232 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     22.610 ms/op
     p(99.9900) =     29.006 ms/op
     p(99.9990) =     29.692 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.459 ± 3.416  ops/ms
ClientPb.existUser                       thrpt       3   8.294 ± 4.911  ops/ms
ClientPb.getUser                         thrpt       3   7.816 ± 1.368  ops/ms
ClientPb.listUser                        thrpt       3   6.727 ± 3.073  ops/ms
ClientPb.createUser                       avgt       3   4.080 ± 0.630   ms/op
ClientPb.existUser                        avgt       3   3.850 ± 0.994   ms/op
ClientPb.getUser                          avgt       3   4.082 ± 2.366   ms/op
ClientPb.listUser                         avgt       3   4.707 ± 3.442   ms/op
ClientPb.createUser                     sample  239050   4.016 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.417           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.815           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.034           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.346           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.113           ms/op
ClientPb.existUser                      sample  247048   3.882 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.550           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.389           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.388           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.427           ms/op
ClientPb.getUser                        sample  243255   3.942 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.618           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.619           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.085           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.557           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.392           ms/op
ClientPb.listUser                       sample  198966   4.822 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.602           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.463           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.175           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.610           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.006           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.114           ms/op
