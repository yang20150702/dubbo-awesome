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
# Warmup Iteration   1: 2.201 ops/ms
# Warmup Iteration   2: 5.677 ops/ms
# Warmup Iteration   3: 8.668 ops/ms
Iteration   1: 9.010 ops/ms
Iteration   2: 9.201 ops/ms
Iteration   3: 9.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.075 ±(99.9%) 1.989 ops/ms [Average]
  (min, avg, max) = (9.010, 9.075, 9.201), stdev = 0.109
  CI (99.9%): [7.086, 11.064] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.128 ops/ms
# Warmup Iteration   2: 8.973 ops/ms
# Warmup Iteration   3: 9.078 ops/ms
Iteration   1: 9.406 ops/ms
Iteration   2: 9.630 ops/ms
Iteration   3: 9.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.505 ±(99.9%) 2.082 ops/ms [Average]
  (min, avg, max) = (9.406, 9.505, 9.630), stdev = 0.114
  CI (99.9%): [7.423, 11.587] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.764 ops/ms
# Warmup Iteration   2: 8.135 ops/ms
# Warmup Iteration   3: 8.737 ops/ms
Iteration   1: 9.033 ops/ms
Iteration   2: 9.170 ops/ms
Iteration   3: 9.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.120 ±(99.9%) 1.376 ops/ms [Average]
  (min, avg, max) = (9.033, 9.120, 9.170), stdev = 0.075
  CI (99.9%): [7.744, 10.496] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.771 ops/ms
# Warmup Iteration   2: 6.987 ops/ms
# Warmup Iteration   3: 7.895 ops/ms
Iteration   1: 7.761 ops/ms
Iteration   2: 8.057 ops/ms
Iteration   3: 7.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.896 ±(99.9%) 2.726 ops/ms [Average]
  (min, avg, max) = (7.761, 7.896, 8.057), stdev = 0.149
  CI (99.9%): [5.169, 10.622] (assumes normal distribution)


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
# Warmup Iteration   1: 8.958 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.007 ms/op
Iteration   1: 3.806 ±(99.9%) 0.003 ms/op
Iteration   2: 3.439 ±(99.9%) 0.010 ms/op
Iteration   3: 3.419 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.555 ±(99.9%) 3.980 ms/op [Average]
  (min, avg, max) = (3.419, 3.555, 3.806), stdev = 0.218
  CI (99.9%): [≈ 0, 7.535] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.214 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.005 ms/op
Iteration   1: 3.304 ±(99.9%) 0.012 ms/op
Iteration   2: 3.477 ±(99.9%) 0.005 ms/op
Iteration   3: 3.344 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.375 ±(99.9%) 1.650 ms/op [Average]
  (min, avg, max) = (3.304, 3.375, 3.477), stdev = 0.090
  CI (99.9%): [1.724, 5.025] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.533 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.006 ms/op
Iteration   1: 3.553 ±(99.9%) 0.008 ms/op
Iteration   2: 3.478 ±(99.9%) 0.007 ms/op
Iteration   3: 3.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.498 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (3.461, 3.498, 3.553), stdev = 0.049
  CI (99.9%): [2.609, 4.386] (assumes normal distribution)


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
# Warmup Iteration   1: 10.897 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.322 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.010 ms/op
Iteration   1: 4.031 ±(99.9%) 0.010 ms/op
Iteration   2: 3.981 ±(99.9%) 0.011 ms/op
Iteration   3: 4.015 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.009 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (3.981, 4.009, 4.031), stdev = 0.026
  CI (99.9%): [3.541, 4.477] (assumes normal distribution)


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
# Warmup Iteration   1: 9.160 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.009 ms/op
Iteration   1: 3.348 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.898 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.495 ms/op
                 createUser·p0.999:  19.020 ms/op
                 createUser·p0.9999: 21.740 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   2: 3.448 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  19.902 ms/op
                 createUser·p0.9999: 27.128 ms/op
                 createUser·p1.00:   29.819 ms/op

Iteration   3: 3.552 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  18.973 ms/op
                 createUser·p0.9999: 29.130 ms/op
                 createUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278272
  mean =      3.447 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3617 
    [ 2.500,  5.000) = 268301 
    [ 5.000,  7.500) = 5415 
    [ 7.500, 10.000) = 445 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     28.108 ms/op
     p(99.9990) =     29.735 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 9.692 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.007 ms/op
Iteration   1: 3.370 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  18.882 ms/op
                 existUser·p0.9999: 21.629 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   2: 3.341 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  22.236 ms/op
                 existUser·p0.9999: 28.499 ms/op
                 existUser·p1.00:   29.098 ms/op

Iteration   3: 3.307 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  12.730 ms/op
                 existUser·p0.9999: 27.318 ms/op
                 existUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287211
  mean =      3.339 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6242 
    [ 2.500,  5.000) = 276368 
    [ 5.000,  7.500) = 3743 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     12.743 ms/op
     p(99.9900) =     27.314 ms/op
     p(99.9990) =     28.873 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 9.056 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.009 ms/op
Iteration   1: 3.549 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.407 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  16.244 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   2: 3.485 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.896 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  21.537 ms/op
                 getUser·p0.9999: 25.002 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   3: 3.664 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  17.891 ms/op
                 getUser·p0.9999: 26.608 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269223
  mean =      3.564 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3549 
    [ 2.500,  5.000) = 257620 
    [ 5.000,  7.500) = 6591 
    [ 7.500, 10.000) = 843 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     17.065 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     27.250 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 11.684 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.731 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.307 ±(99.9%) 0.014 ms/op
Iteration   1: 4.209 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  22.086 ms/op
                 listUser·p0.9999: 27.190 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   2: 3.996 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.577 ms/op
                 listUser·p0.999:  15.876 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 4.117 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.238 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 16.503 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233766
  mean =      4.106 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 225336 
    [ 5.000,  7.500) = 6460 
    [ 7.500, 10.000) = 1165 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 228 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     15.896 ms/op
     p(99.9900) =     25.534 ms/op
     p(99.9990) =     27.885 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.075 ± 1.989  ops/ms
ClientPb.existUser                       thrpt       3   9.505 ± 2.082  ops/ms
ClientPb.getUser                         thrpt       3   9.120 ± 1.376  ops/ms
ClientPb.listUser                        thrpt       3   7.896 ± 2.726  ops/ms
ClientPb.createUser                       avgt       3   3.555 ± 3.980   ms/op
ClientPb.existUser                        avgt       3   3.375 ± 1.650   ms/op
ClientPb.getUser                          avgt       3   3.498 ± 0.889   ms/op
ClientPb.listUser                         avgt       3   4.009 ± 0.468   ms/op
ClientPb.createUser                     sample  278272   3.447 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.403           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.833           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.973           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.108           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.819           ms/op
ClientPb.existUser                      sample  287211   3.339 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.204           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.899           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.833           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.743           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.314           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.098           ms/op
ClientPb.getUser                        sample  269223   3.564 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.407           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.065           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.083           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.296           ms/op
ClientPb.listUser                       sample  233766   4.106 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.495           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.896           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.534           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.639           ms/op
