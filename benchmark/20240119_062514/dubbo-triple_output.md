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
# Warmup Iteration   1: 5.059 ops/ms
# Warmup Iteration   2: 11.977 ops/ms
# Warmup Iteration   3: 12.330 ops/ms
Iteration   1: 12.478 ops/ms
Iteration   2: 12.585 ops/ms
Iteration   3: 12.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.572 ±(99.9%) 1.590 ops/ms [Average]
  (min, avg, max) = (12.478, 12.572, 12.651), stdev = 0.087
  CI (99.9%): [10.981, 14.162] (assumes normal distribution)


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
# Warmup Iteration   1: 8.182 ops/ms
# Warmup Iteration   2: 12.978 ops/ms
# Warmup Iteration   3: 13.052 ops/ms
Iteration   1: 12.987 ops/ms
Iteration   2: 13.017 ops/ms
Iteration   3: 12.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.943 ±(99.9%) 1.888 ops/ms [Average]
  (min, avg, max) = (12.825, 12.943, 13.017), stdev = 0.104
  CI (99.9%): [11.055, 14.831] (assumes normal distribution)


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
# Warmup Iteration   1: 8.020 ops/ms
# Warmup Iteration   2: 12.341 ops/ms
# Warmup Iteration   3: 12.751 ops/ms
Iteration   1: 12.780 ops/ms
Iteration   2: 12.792 ops/ms
Iteration   3: 12.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.766 ±(99.9%) 0.625 ops/ms [Average]
  (min, avg, max) = (12.727, 12.766, 12.792), stdev = 0.034
  CI (99.9%): [12.142, 13.391] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.642 ops/ms
# Warmup Iteration   2: 10.629 ops/ms
# Warmup Iteration   3: 10.766 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.739 ops/ms
Iteration   3: 10.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.717 ±(99.9%) 0.556 ops/ms [Average]
  (min, avg, max) = (10.682, 10.717, 10.739), stdev = 0.030
  CI (99.9%): [10.161, 11.273] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.115 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.003 ms/op
Iteration   1: 2.581 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
Iteration   3: 2.496 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (2.496, 2.530, 2.581), stdev = 0.045
  CI (99.9%): [1.710, 3.350] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.623 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.003 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.488 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.483, 2.488, 2.496), stdev = 0.007
  CI (99.9%): [2.357, 2.619] (assumes normal distribution)


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.008 ms/op
Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
Iteration   3: 2.419 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.460 ±(99.9%) 0.672 ms/op [Average]
  (min, avg, max) = (2.419, 2.460, 2.489), stdev = 0.037
  CI (99.9%): [1.789, 3.132] (assumes normal distribution)


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.007 ms/op
Iteration   1: 2.939 ±(99.9%) 0.006 ms/op
Iteration   2: 2.940 ±(99.9%) 0.006 ms/op
Iteration   3: 2.941 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.940 ±(99.9%) 0.023 ms/op [Average]
  (min, avg, max) = (2.939, 2.940, 2.941), stdev = 0.001
  CI (99.9%): [2.917, 2.963] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.096 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
Iteration   1: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  10.931 ms/op
                 createUser·p0.9999: 13.933 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  9.482 ms/op
                 createUser·p0.9999: 12.393 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   3: 2.572 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.847 ms/op
                 createUser·p0.9999: 11.479 ms/op
                 createUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375399
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 178905 
    [ 2.500,  3.750) = 191923 
    [ 3.750,  5.000) = 3251 
    [ 5.000,  6.250) = 618 
    [ 6.250,  7.500) = 172 
    [ 7.500,  8.750) = 101 
    [ 8.750, 10.000) = 135 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      8.890 ms/op
     p(99.9900) =     13.180 ms/op
     p(99.9990) =     14.250 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 3.694 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
Iteration   1: 2.395 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.409 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  7.852 ms/op
                 existUser·p0.9999: 13.151 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.394 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.841 ms/op
                 existUser·p0.50:   2.351 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 13.779 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  6.744 ms/op
                 existUser·p0.9999: 13.236 ms/op
                 existUser·p1.00:   14.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398434
  mean =      2.407 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 210555 
    [ 2.500,  3.750) = 184994 
    [ 3.750,  5.000) = 2119 
    [ 5.000,  6.250) = 227 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.409 ms/op
     p(50.0000) =      2.408 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      7.190 ms/op
     p(99.9900) =     13.405 ms/op
     p(99.9990) =     14.288 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  8.629 ms/op
                 getUser·p0.9999: 15.132 ms/op
                 getUser·p1.00:   15.892 ms/op

Iteration   2: 2.531 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  9.268 ms/op
                 getUser·p0.9999: 13.556 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  6.340 ms/op
                 getUser·p0.9999: 11.569 ms/op
                 getUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383791
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 190972 
    [ 2.500,  3.750) = 187249 
    [ 3.750,  5.000) = 4365 
    [ 5.000,  6.250) = 691 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     15.665 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 5.327 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.009 ms/op
Iteration   1: 3.097 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  8.716 ms/op
                 listUser·p0.9999: 10.224 ms/op
                 listUser·p1.00:   11.043 ms/op

Iteration   2: 3.095 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.787 ms/op
                 listUser·p0.9999: 11.420 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   3: 3.103 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 11.497 ms/op
                 listUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309624
  mean =      3.098 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 77902 
    [ 2.500,  3.750) = 185946 
    [ 3.750,  5.000) = 36943 
    [ 5.000,  6.250) = 7172 
    [ 6.250,  7.500) = 872 
    [ 7.500,  8.750) = 256 
    [ 8.750, 10.000) = 262 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.404 ms/op
     p(99.9990) =     12.205 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.572 ± 1.590  ops/ms
ClientPb.existUser                       thrpt       3  12.943 ± 1.888  ops/ms
ClientPb.getUser                         thrpt       3  12.766 ± 0.625  ops/ms
ClientPb.listUser                        thrpt       3  10.717 ± 0.556  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.820   ms/op
ClientPb.existUser                        avgt       3   2.488 ± 0.131   ms/op
ClientPb.getUser                          avgt       3   2.460 ± 0.672   ms/op
ClientPb.listUser                         avgt       3   2.940 ± 0.023   ms/op
ClientPb.createUser                     sample  375399   2.555 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.524           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.890           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.180           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.008           ms/op
ClientPb.existUser                      sample  398434   2.407 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.409           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.408           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.190           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.405           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.483           ms/op
ClientPb.getUser                        sample  383791   2.499 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.701           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.536           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.008           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.892           ms/op
ClientPb.listUser                       sample  309624   3.098 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.770           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.039           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.404           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.960           ms/op
