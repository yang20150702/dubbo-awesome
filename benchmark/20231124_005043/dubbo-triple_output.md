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
# Warmup Iteration   1: 4.567 ops/ms
# Warmup Iteration   2: 12.059 ops/ms
# Warmup Iteration   3: 12.381 ops/ms
Iteration   1: 12.407 ops/ms
Iteration   2: 12.584 ops/ms
Iteration   3: 12.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.598 ±(99.9%) 3.595 ops/ms [Average]
  (min, avg, max) = (12.407, 12.598, 12.801), stdev = 0.197
  CI (99.9%): [9.002, 16.193] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.356 ops/ms
# Warmup Iteration   2: 13.067 ops/ms
# Warmup Iteration   3: 12.994 ops/ms
Iteration   1: 13.076 ops/ms
Iteration   2: 13.159 ops/ms
Iteration   3: 13.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.117 ±(99.9%) 0.761 ops/ms [Average]
  (min, avg, max) = (13.076, 13.117, 13.159), stdev = 0.042
  CI (99.9%): [12.355, 13.878] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.596 ops/ms
# Warmup Iteration   2: 12.615 ops/ms
# Warmup Iteration   3: 12.783 ops/ms
Iteration   1: 12.913 ops/ms
Iteration   2: 12.875 ops/ms
Iteration   3: 12.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.855 ±(99.9%) 1.264 ops/ms [Average]
  (min, avg, max) = (12.779, 12.855, 12.913), stdev = 0.069
  CI (99.9%): [11.591, 14.120] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.403 ops/ms
# Warmup Iteration   2: 10.273 ops/ms
# Warmup Iteration   3: 10.373 ops/ms
Iteration   1: 10.449 ops/ms
Iteration   2: 10.555 ops/ms
Iteration   3: 10.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.518 ±(99.9%) 1.095 ops/ms [Average]
  (min, avg, max) = (10.449, 10.518, 10.555), stdev = 0.060
  CI (99.9%): [9.423, 11.613] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.225 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.004 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.478 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.497 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (2.478, 2.497, 2.519), stdev = 0.021
  CI (99.9%): [2.120, 2.874] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.484 ±(99.9%) 0.003 ms/op
Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
Iteration   3: 2.517 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.498 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (2.484, 2.498, 2.517), stdev = 0.017
  CI (99.9%): [2.180, 2.816] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.089 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
Iteration   1: 2.561 ±(99.9%) 0.005 ms/op
Iteration   2: 2.555 ±(99.9%) 0.003 ms/op
Iteration   3: 2.543 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.553 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.543, 2.553, 2.561), stdev = 0.009
  CI (99.9%): [2.385, 2.722] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.820 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.005 ms/op
Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
Iteration   3: 2.998 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.020 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.998, 3.020, 3.032), stdev = 0.020
  CI (99.9%): [2.660, 3.381] (assumes normal distribution)


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  11.954 ms/op
                 createUser·p0.9999: 14.729 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  9.913 ms/op
                 createUser·p0.9999: 12.801 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  7.553 ms/op
                 createUser·p0.9999: 11.289 ms/op
                 createUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380855
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 182945 
    [ 2.500,  3.750) = 193450 
    [ 3.750,  5.000) = 3291 
    [ 5.000,  6.250) = 658 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      7.722 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.689 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  11.075 ms/op
                 existUser·p0.9999: 16.253 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  6.061 ms/op
                 existUser·p0.9999: 12.681 ms/op
                 existUser·p1.00:   13.369 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  8.025 ms/op
                 existUser·p0.9999: 11.797 ms/op
                 existUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387648
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 187866 
    [ 2.500,  3.750) = 195159 
    [ 3.750,  5.000) = 3065 
    [ 5.000,  6.250) = 1069 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      7.070 ms/op
     p(99.9900) =     13.740 ms/op
     p(99.9990) =     16.286 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.034 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  5.724 ms/op
                 getUser·p0.9999: 13.929 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  9.873 ms/op
                 getUser·p0.9999: 12.816 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  7.402 ms/op
                 getUser·p0.9999: 10.914 ms/op
                 getUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384429
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 190421 
    [ 2.500,  3.750) = 188411 
    [ 3.750,  5.000) = 4029 
    [ 5.000,  6.250) = 1013 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =      8.197 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     14.060 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.964 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.009 ms/op
Iteration   1: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.600 ms/op
                 listUser·p1.00:   11.256 ms/op

Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.858 ms/op
                 listUser·p0.9999: 11.469 ms/op
                 listUser·p1.00:   11.829 ms/op

Iteration   3: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.173 ms/op
                 listUser·p0.9999: 15.727 ms/op
                 listUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316167
  mean =      3.034 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 88295 
    [ 2.500,  3.750) = 187202 
    [ 3.750,  5.000) = 32505 
    [ 5.000,  6.250) = 6459 
    [ 6.250,  7.500) = 859 
    [ 7.500,  8.750) = 272 
    [ 8.750, 10.000) = 234 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.320 ms/op
     p(99.9900) =     13.929 ms/op
     p(99.9990) =     16.002 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.598 ± 3.595  ops/ms
ClientPb.existUser                       thrpt       3  13.117 ± 0.761  ops/ms
ClientPb.getUser                         thrpt       3  12.855 ± 1.264  ops/ms
ClientPb.listUser                        thrpt       3  10.518 ± 1.095  ops/ms
ClientPb.createUser                       avgt       3   2.497 ± 0.377   ms/op
ClientPb.existUser                        avgt       3   2.498 ± 0.318   ms/op
ClientPb.getUser                          avgt       3   2.553 ± 0.168   ms/op
ClientPb.listUser                         avgt       3   3.020 ± 0.360   ms/op
ClientPb.createUser                     sample  380855   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.843           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.722           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.779           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.828           ms/op
ClientPb.existUser                      sample  387648   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.861           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.070           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.740           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.072           ms/op
ClientPb.getUser                        sample  384429   2.495 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.860           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.197           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.533           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  316167   3.034 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.815           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.320           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.929           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.482           ms/op
