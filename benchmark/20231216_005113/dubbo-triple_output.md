# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.598 ops/ms
# Warmup Iteration   2: 11.692 ops/ms
# Warmup Iteration   3: 12.225 ops/ms
Iteration   1: 12.320 ops/ms
Iteration   2: 12.506 ops/ms
Iteration   3: 12.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.450 ±(99.9%) 2.061 ops/ms [Average]
  (min, avg, max) = (12.320, 12.450, 12.525), stdev = 0.113
  CI (99.9%): [10.389, 14.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.056 ops/ms
# Warmup Iteration   2: 12.391 ops/ms
# Warmup Iteration   3: 12.820 ops/ms
Iteration   1: 12.664 ops/ms
Iteration   2: 12.757 ops/ms
Iteration   3: 12.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.707 ±(99.9%) 0.847 ops/ms [Average]
  (min, avg, max) = (12.664, 12.707, 12.757), stdev = 0.046
  CI (99.9%): [11.860, 13.555] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.364 ops/ms
# Warmup Iteration   2: 12.512 ops/ms
# Warmup Iteration   3: 12.517 ops/ms
Iteration   1: 12.551 ops/ms
Iteration   2: 12.637 ops/ms
Iteration   3: 12.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.549 ±(99.9%) 1.634 ops/ms [Average]
  (min, avg, max) = (12.458, 12.549, 12.637), stdev = 0.090
  CI (99.9%): [10.915, 14.183] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.294 ops/ms
# Warmup Iteration   2: 10.049 ops/ms
# Warmup Iteration   3: 10.325 ops/ms
Iteration   1: 10.208 ops/ms
Iteration   2: 10.149 ops/ms
Iteration   3: 10.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.176 ±(99.9%) 0.540 ops/ms [Average]
  (min, avg, max) = (10.149, 10.176, 10.208), stdev = 0.030
  CI (99.9%): [9.636, 10.716] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.268 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.004 ms/op
Iteration   1: 2.590 ±(99.9%) 0.004 ms/op
Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
Iteration   3: 2.577 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.589 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (2.577, 2.589, 2.600), stdev = 0.012
  CI (99.9%): [2.371, 2.807] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.825 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.003 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.458, 2.472, 2.481), stdev = 0.013
  CI (99.9%): [2.242, 2.702] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.238 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.004 ms/op
Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
Iteration   3: 2.553 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.558 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (2.553, 2.558, 2.566), stdev = 0.007
  CI (99.9%): [2.431, 2.685] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.701 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.005 ms/op
Iteration   1: 3.094 ±(99.9%) 0.005 ms/op
Iteration   2: 3.097 ±(99.9%) 0.006 ms/op
Iteration   3: 3.084 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.092 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (3.084, 3.092, 3.097), stdev = 0.007
  CI (99.9%): [2.963, 3.221] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  11.393 ms/op
                 createUser·p0.9999: 15.539 ms/op
                 createUser·p1.00:   15.729 ms/op

Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  9.470 ms/op
                 createUser·p0.9999: 12.747 ms/op
                 createUser·p1.00:   13.697 ms/op

Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.338 ms/op
                 createUser·p0.99:   4.230 ms/op
                 createUser·p0.999:  8.699 ms/op
                 createUser·p0.9999: 13.477 ms/op
                 createUser·p1.00:   15.319 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374867
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 176973 
    [ 2.500,  3.750) = 192478 
    [ 3.750,  5.000) = 4413 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      8.915 ms/op
     p(99.9900) =     14.631 ms/op
     p(99.9990) =     15.630 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.787 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  5.327 ms/op
                 existUser·p0.9999: 14.008 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  8.484 ms/op
                 existUser·p0.9999: 14.324 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.410 ms/op
                 existUser·p0.999:  6.920 ms/op
                 existUser·p0.9999: 12.354 ms/op
                 existUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386385
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 190992 
    [ 2.500,  3.750) = 192710 
    [ 3.750,  5.000) = 2051 
    [ 5.000,  6.250) = 221 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.535 ms/op
     p(99.9000) =      5.977 ms/op
     p(99.9900) =     14.031 ms/op
     p(99.9990) =     14.928 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.847 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.560 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.187 ms/op
                 getUser·p0.999:  11.207 ms/op
                 getUser·p0.9999: 14.746 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  7.873 ms/op
                 getUser·p0.9999: 13.149 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  9.117 ms/op
                 getUser·p0.9999: 13.795 ms/op
                 getUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376043
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 182923 
    [ 2.500,  3.750) = 186598 
    [ 3.750,  5.000) = 4897 
    [ 5.000,  6.250) = 1076 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     14.457 ms/op
     p(99.9990) =     15.339 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.703 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.009 ms/op
Iteration   1: 3.121 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 12.423 ms/op
                 listUser·p1.00:   13.124 ms/op

Iteration   2: 3.102 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 12.122 ms/op
                 listUser·p1.00:   12.567 ms/op

Iteration   3: 3.098 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  10.185 ms/op
                 listUser·p0.9999: 12.245 ms/op
                 listUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 308653
  mean =      3.107 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 75464 
    [ 2.500,  3.750) = 186524 
    [ 3.750,  5.000) = 37590 
    [ 5.000,  6.250) = 7328 
    [ 6.250,  7.500) = 932 
    [ 7.500,  8.750) = 223 
    [ 8.750, 10.000) = 188 
    [10.000, 11.250) = 193 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     12.227 ms/op
     p(99.9990) =     13.089 ms/op
     p(99.9999) =     13.124 ms/op
    p(100.0000) =     13.124 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.450 ± 2.061  ops/ms
ClientPb.existUser                       thrpt       3  12.707 ± 0.847  ops/ms
ClientPb.getUser                         thrpt       3  12.549 ± 1.634  ops/ms
ClientPb.listUser                        thrpt       3  10.176 ± 0.540  ops/ms
ClientPb.createUser                       avgt       3   2.589 ± 0.218   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.230   ms/op
ClientPb.getUser                          avgt       3   2.558 ± 0.127   ms/op
ClientPb.listUser                         avgt       3   3.092 ± 0.129   ms/op
ClientPb.createUser                     sample  374867   2.558 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.005           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.915           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.631           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.729           ms/op
ClientPb.existUser                      sample  386385   2.482 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.919           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.977           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.031           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.106           ms/op
ClientPb.getUser                        sample  376043   2.551 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.959           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.536           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.457           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.516           ms/op
ClientPb.listUser                       sample  308653   3.107 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.795           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.035           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.784           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.945           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.227           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.124           ms/op
