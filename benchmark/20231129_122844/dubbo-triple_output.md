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
# Warmup Iteration   1: 4.398 ops/ms
# Warmup Iteration   2: 11.491 ops/ms
# Warmup Iteration   3: 11.857 ops/ms
Iteration   1: 12.130 ops/ms
Iteration   2: 12.118 ops/ms
Iteration   3: 12.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.136 ±(99.9%) 0.382 ops/ms [Average]
  (min, avg, max) = (12.118, 12.136, 12.159), stdev = 0.021
  CI (99.9%): [11.754, 12.517] (assumes normal distribution)


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
# Warmup Iteration   1: 7.411 ops/ms
# Warmup Iteration   2: 12.617 ops/ms
# Warmup Iteration   3: 12.707 ops/ms
Iteration   1: 12.592 ops/ms
Iteration   2: 12.743 ops/ms
Iteration   3: 12.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.645 ±(99.9%) 1.556 ops/ms [Average]
  (min, avg, max) = (12.592, 12.645, 12.743), stdev = 0.085
  CI (99.9%): [11.089, 14.201] (assumes normal distribution)


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
# Warmup Iteration   1: 7.333 ops/ms
# Warmup Iteration   2: 12.247 ops/ms
# Warmup Iteration   3: 12.780 ops/ms
Iteration   1: 12.673 ops/ms
Iteration   2: 12.700 ops/ms
Iteration   3: 12.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.667 ±(99.9%) 0.674 ops/ms [Average]
  (min, avg, max) = (12.627, 12.667, 12.700), stdev = 0.037
  CI (99.9%): [11.992, 13.341] (assumes normal distribution)


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
# Warmup Iteration   1: 6.584 ops/ms
# Warmup Iteration   2: 10.214 ops/ms
# Warmup Iteration   3: 10.252 ops/ms
Iteration   1: 10.427 ops/ms
Iteration   2: 10.292 ops/ms
Iteration   3: 10.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.330 ±(99.9%) 1.534 ops/ms [Average]
  (min, avg, max) = (10.272, 10.330, 10.427), stdev = 0.084
  CI (99.9%): [8.796, 11.864] (assumes normal distribution)


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.003 ms/op
Iteration   1: 2.546 ±(99.9%) 0.004 ms/op
Iteration   2: 2.572 ±(99.9%) 0.004 ms/op
Iteration   3: 2.525 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.548 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (2.525, 2.548, 2.572), stdev = 0.024
  CI (99.9%): [2.119, 2.977] (assumes normal distribution)


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
# Warmup Iteration   1: 3.861 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.472 ±(99.9%) 0.003 ms/op
Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.479 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (2.468, 2.479, 2.498), stdev = 0.016
  CI (99.9%): [2.185, 2.773] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.018 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.003 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.516 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (2.479, 2.502, 2.516), stdev = 0.021
  CI (99.9%): [2.127, 2.878] (assumes normal distribution)


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
# Warmup Iteration   1: 4.753 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
Iteration   3: 3.017 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.026 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (3.017, 3.026, 3.034), stdev = 0.009
  CI (99.9%): [2.864, 3.188] (assumes normal distribution)


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.544 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  11.633 ms/op
                 createUser·p0.9999: 18.317 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  10.580 ms/op
                 createUser·p0.9999: 12.417 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.104 ms/op
                 createUser·p0.999:  8.392 ms/op
                 createUser·p0.9999: 11.032 ms/op
                 createUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379128
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 182059 
    [ 2.500,  3.750) = 192414 
    [ 3.750,  5.000) = 3256 
    [ 5.000,  6.250) = 867 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      8.681 ms/op
     p(99.9900) =     14.878 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.006 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  6.782 ms/op
                 existUser·p0.9999: 15.112 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   2: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.488 ms/op
                 existUser·p0.999:  8.159 ms/op
                 existUser·p0.9999: 13.120 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  8.892 ms/op
                 existUser·p0.9999: 15.152 ms/op
                 existUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395745
  mean =      2.424 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 197295 
    [ 2.500,  3.750) = 194883 
    [ 3.750,  5.000) = 2600 
    [ 5.000,  6.250) = 431 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 87 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      8.167 ms/op
     p(99.9900) =     14.418 ms/op
     p(99.9990) =     15.419 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.982 ms/op
                 getUser·p0.999:  10.970 ms/op
                 getUser·p0.9999: 18.171 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  9.053 ms/op
                 getUser·p0.9999: 13.603 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  8.307 ms/op
                 getUser·p0.9999: 11.487 ms/op
                 getUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382629
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 189383 
    [ 2.500,  3.750) = 187242 
    [ 3.750,  5.000) = 4560 
    [ 5.000,  6.250) = 932 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      8.282 ms/op
     p(99.9900) =     17.153 ms/op
     p(99.9990) =     18.373 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 4.986 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.009 ms/op
Iteration   1: 3.107 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.487 ms/op
                 listUser·p1.00:   12.239 ms/op

Iteration   2: 3.119 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.758 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.923 ms/op
                 listUser·p0.999:  10.461 ms/op
                 listUser·p0.9999: 12.644 ms/op
                 listUser·p1.00:   13.910 ms/op

Iteration   3: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.752 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 10.863 ms/op
                 listUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309290
  mean =      3.101 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 78480 
    [ 2.500,  3.750) = 184933 
    [ 3.750,  5.000) = 36681 
    [ 5.000,  6.250) = 7395 
    [ 6.250,  7.500) = 933 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 290 
    [10.000, 11.250) = 192 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =      9.847 ms/op
     p(99.9900) =     12.109 ms/op
     p(99.9990) =     13.247 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.136 ± 0.382  ops/ms
ClientPb.existUser                       thrpt       3  12.645 ± 1.556  ops/ms
ClientPb.getUser                         thrpt       3  12.667 ± 0.674  ops/ms
ClientPb.listUser                        thrpt       3  10.330 ± 1.534  ops/ms
ClientPb.createUser                       avgt       3   2.548 ± 0.429   ms/op
ClientPb.existUser                        avgt       3   2.479 ± 0.294   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.375   ms/op
ClientPb.listUser                         avgt       3   3.026 ± 0.162   ms/op
ClientPb.createUser                     sample  379128   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.798           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.681           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.878           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.268           ms/op
ClientPb.existUser                      sample  395745   2.424 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.853           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.167           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.418           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.073           ms/op
ClientPb.getUser                        sample  382629   2.507 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.641           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.282           ms/op
ClientPb.getUser:getUser·p0.9999        sample          17.153           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.547           ms/op
ClientPb.listUser                       sample  309290   3.101 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.752           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.035           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.841           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.847           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.109           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.910           ms/op
