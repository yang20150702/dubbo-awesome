# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.119 ops/ms
# Warmup Iteration   2: 12.127 ops/ms
# Warmup Iteration   3: 12.320 ops/ms
Iteration   1: 12.524 ops/ms
Iteration   2: 12.609 ops/ms
Iteration   3: 12.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.578 ±(99.9%) 0.856 ops/ms [Average]
  (min, avg, max) = (12.524, 12.578, 12.609), stdev = 0.047
  CI (99.9%): [11.722, 13.434] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.154 ops/ms
# Warmup Iteration   2: 13.030 ops/ms
# Warmup Iteration   3: 13.142 ops/ms
Iteration   1: 13.189 ops/ms
Iteration   2: 13.166 ops/ms
Iteration   3: 13.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.154 ±(99.9%) 0.766 ops/ms [Average]
  (min, avg, max) = (13.108, 13.154, 13.189), stdev = 0.042
  CI (99.9%): [12.389, 13.920] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.642 ops/ms
# Warmup Iteration   2: 12.640 ops/ms
# Warmup Iteration   3: 12.764 ops/ms
Iteration   1: 12.963 ops/ms
Iteration   2: 12.805 ops/ms
Iteration   3: 12.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.842 ±(99.9%) 1.947 ops/ms [Average]
  (min, avg, max) = (12.759, 12.842, 12.963), stdev = 0.107
  CI (99.9%): [10.895, 14.789] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.796 ops/ms
# Warmup Iteration   2: 10.599 ops/ms
# Warmup Iteration   3: 10.674 ops/ms
Iteration   1: 10.727 ops/ms
Iteration   2: 10.724 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.705 ±(99.9%) 0.649 ops/ms [Average]
  (min, avg, max) = (10.664, 10.705, 10.727), stdev = 0.036
  CI (99.9%): [10.055, 11.354] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.595 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.567 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.550 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (2.534, 2.550, 2.567), stdev = 0.016
  CI (99.9%): [2.250, 2.851] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.653 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.425 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.004 ms/op
Iteration   1: 2.442 ±(99.9%) 0.004 ms/op
Iteration   2: 2.427 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.433 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (2.427, 2.433, 2.442), stdev = 0.008
  CI (99.9%): [2.287, 2.579] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.919 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.495 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (2.476, 2.495, 2.519), stdev = 0.022
  CI (99.9%): [2.090, 2.900] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.464 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.004 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
Iteration   2: 2.991 ±(99.9%) 0.005 ms/op
Iteration   3: 2.982 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.997 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.982, 2.997, 3.017), stdev = 0.018
  CI (99.9%): [2.673, 3.321] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.072 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.006 ms/op
Iteration   1: 2.565 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  11.529 ms/op
                 createUser·p0.9999: 13.788 ms/op
                 createUser·p1.00:   14.991 ms/op

Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.527 ms/op
                 createUser·p0.999:  9.802 ms/op
                 createUser·p0.9999: 13.311 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 2.576 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  8.796 ms/op
                 createUser·p0.9999: 10.990 ms/op
                 createUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374512
  mean =      2.561 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 179781 
    [ 2.500,  3.750) = 189963 
    [ 3.750,  5.000) = 3672 
    [ 5.000,  6.250) = 600 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      8.823 ms/op
     p(99.9900) =     13.405 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.785 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  5.276 ms/op
                 existUser·p0.9999: 13.944 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 2.480 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  8.014 ms/op
                 existUser·p0.9999: 22.053 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  8.204 ms/op
                 existUser·p0.9999: 11.685 ms/op
                 existUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386207
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 187991 
    [ 2.500,  5.000) = 197636 
    [ 5.000,  7.500) = 220 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      6.468 ms/op
     p(99.9900) =     14.057 ms/op
     p(99.9990) =     22.591 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.916 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.439 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  8.436 ms/op
                 getUser·p0.9999: 13.830 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 2.557 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.346 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  9.830 ms/op
                 getUser·p0.9999: 12.419 ms/op
                 getUser·p1.00:   12.763 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.717 ms/op
                 getUser·p0.999:  7.205 ms/op
                 getUser·p0.9999: 11.502 ms/op
                 getUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382272
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 188008 
    [ 2.500,  3.750) = 188009 
    [ 3.750,  5.000) = 4728 
    [ 5.000,  6.250) = 906 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      8.466 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.126 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.663 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
Iteration   1: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.606 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 10.707 ms/op
                 listUser·p1.00:   11.010 ms/op

Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.301 ms/op
                 listUser·p0.9999: 11.567 ms/op
                 listUser·p1.00:   12.976 ms/op

Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.685 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.863 ms/op
                 listUser·p0.9999: 11.556 ms/op
                 listUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315984
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 87884 
    [ 2.500,  3.750) = 187405 
    [ 3.750,  5.000) = 33273 
    [ 5.000,  6.250) = 6113 
    [ 6.250,  7.500) = 518 
    [ 7.500,  8.750) = 153 
    [ 8.750, 10.000) = 304 
    [10.000, 11.250) = 171 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.716 ms/op
     p(99.9900) =     11.325 ms/op
     p(99.9990) =     12.237 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.578 ± 0.856  ops/ms
ClientPb.existUser                       thrpt       3  13.154 ± 0.766  ops/ms
ClientPb.getUser                         thrpt       3  12.842 ± 1.947  ops/ms
ClientPb.listUser                        thrpt       3  10.705 ± 0.649  ops/ms
ClientPb.createUser                       avgt       3   2.550 ± 0.300   ms/op
ClientPb.existUser                        avgt       3   2.433 ± 0.146   ms/op
ClientPb.getUser                          avgt       3   2.495 ± 0.405   ms/op
ClientPb.listUser                         avgt       3   2.997 ± 0.324   ms/op
ClientPb.createUser                     sample  374512   2.561 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.808           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.823           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.405           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.991           ms/op
ClientPb.existUser                      sample  386207   2.483 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.863           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.468           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.057           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.774           ms/op
ClientPb.getUser                        sample  382272   2.509 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.439           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.466           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.386           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.385           ms/op
ClientPb.listUser                       sample  315984   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.685           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.716           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.325           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.976           ms/op
