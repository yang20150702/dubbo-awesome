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
# Warmup Iteration   1: 4.700 ops/ms
# Warmup Iteration   2: 12.025 ops/ms
# Warmup Iteration   3: 12.258 ops/ms
Iteration   1: 12.660 ops/ms
Iteration   2: 12.927 ops/ms
Iteration   3: 13.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.896 ±(99.9%) 4.048 ops/ms [Average]
  (min, avg, max) = (12.660, 12.896, 13.100), stdev = 0.222
  CI (99.9%): [8.848, 16.943] (assumes normal distribution)


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
# Warmup Iteration   1: 7.992 ops/ms
# Warmup Iteration   2: 12.975 ops/ms
# Warmup Iteration   3: 13.030 ops/ms
Iteration   1: 12.933 ops/ms
Iteration   2: 13.082 ops/ms
Iteration   3: 12.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.946 ±(99.9%) 2.371 ops/ms [Average]
  (min, avg, max) = (12.823, 12.946, 13.082), stdev = 0.130
  CI (99.9%): [10.575, 15.317] (assumes normal distribution)


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
# Warmup Iteration   1: 7.424 ops/ms
# Warmup Iteration   2: 12.589 ops/ms
# Warmup Iteration   3: 12.873 ops/ms
Iteration   1: 12.899 ops/ms
Iteration   2: 12.760 ops/ms
Iteration   3: 12.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.831 ±(99.9%) 1.267 ops/ms [Average]
  (min, avg, max) = (12.760, 12.831, 12.899), stdev = 0.069
  CI (99.9%): [11.564, 14.098] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.864 ops/ms
# Warmup Iteration   2: 10.669 ops/ms
# Warmup Iteration   3: 10.731 ops/ms
Iteration   1: 10.754 ops/ms
Iteration   2: 10.698 ops/ms
Iteration   3: 10.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.707 ±(99.9%) 0.790 ops/ms [Average]
  (min, avg, max) = (10.669, 10.707, 10.754), stdev = 0.043
  CI (99.9%): [9.917, 11.497] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.169 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.006 ms/op
Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
Iteration   3: 2.498 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.488, 2.502, 2.519), stdev = 0.016
  CI (99.9%): [2.216, 2.788] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.003 ms/op
Iteration   1: 2.469 ±(99.9%) 0.003 ms/op
Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.471 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.462, 2.471, 2.482), stdev = 0.010
  CI (99.9%): [2.285, 2.657] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.486 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (2.444, 2.486, 2.510), stdev = 0.037
  CI (99.9%): [1.815, 3.157] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.528 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
Iteration   2: 2.970 ±(99.9%) 0.010 ms/op
Iteration   3: 2.904 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.963 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (2.904, 2.963, 3.015), stdev = 0.056
  CI (99.9%): [1.943, 3.983] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.147 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.592 ms/op
                 createUser·p0.999:  11.714 ms/op
                 createUser·p0.9999: 14.025 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  9.421 ms/op
                 createUser·p0.9999: 11.738 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  7.952 ms/op
                 createUser·p0.9999: 16.892 ms/op
                 createUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383391
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 187134 
    [ 2.500,  3.750) = 193208 
    [ 3.750,  5.000) = 2370 
    [ 5.000,  6.250) = 226 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      8.000 ms/op
     p(99.9900) =     14.134 ms/op
     p(99.9990) =     17.372 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  6.075 ms/op
                 existUser·p0.9999: 14.631 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   2: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.346 ms/op
                 existUser·p0.999:  7.361 ms/op
                 existUser·p0.9999: 14.336 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  5.739 ms/op
                 existUser·p0.9999: 11.750 ms/op
                 existUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393353
  mean =      2.438 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 194493 
    [ 2.500,  3.750) = 196131 
    [ 3.750,  5.000) = 1961 
    [ 5.000,  6.250) = 342 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.514 ms/op
     p(99.9000) =      6.135 ms/op
     p(99.9900) =     14.276 ms/op
     p(99.9990) =     15.075 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  6.090 ms/op
                 getUser·p0.9999: 13.893 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.308 ms/op
                 getUser·p0.9999: 13.255 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  5.871 ms/op
                 getUser·p0.9999: 11.207 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390614
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 197693 
    [ 2.500,  3.750) = 188572 
    [ 3.750,  5.000) = 3057 
    [ 5.000,  6.250) = 810 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      7.022 ms/op
     p(99.9900) =     13.564 ms/op
     p(99.9990) =     14.141 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 5.008 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.009 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.723 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.122 ms/op
                 listUser·p0.9999: 11.187 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   2: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 11.508 ms/op
                 listUser·p1.00:   11.993 ms/op

Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.374 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.550 ms/op
                 listUser·p0.9999: 12.199 ms/op
                 listUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318911
  mean =      3.007 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 92289 
    [ 2.500,  3.750) = 186605 
    [ 3.750,  5.000) = 32805 
    [ 5.000,  6.250) = 5698 
    [ 6.250,  7.500) = 693 
    [ 7.500,  8.750) = 249 
    [ 8.750, 10.000) = 183 
    [10.000, 11.250) = 175 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.487 ms/op
     p(99.9990) =     12.432 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.896 ± 4.048  ops/ms
ClientPb.existUser                       thrpt       3  12.946 ± 2.371  ops/ms
ClientPb.getUser                         thrpt       3  12.831 ± 1.267  ops/ms
ClientPb.listUser                        thrpt       3  10.707 ± 0.790  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.286   ms/op
ClientPb.existUser                        avgt       3   2.471 ± 0.186   ms/op
ClientPb.getUser                          avgt       3   2.486 ± 0.671   ms/op
ClientPb.listUser                         avgt       3   2.963 ± 1.020   ms/op
ClientPb.createUser                     sample  383391   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.863           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.000           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.134           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.498           ms/op
ClientPb.existUser                      sample  393353   2.438 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.929           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.135           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.276           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.188           ms/op
ClientPb.getUser                        sample  390614   2.455 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.893           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.022           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.564           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.467           ms/op
ClientPb.listUser                       sample  318911   3.007 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.723           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.487           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.517           ms/op
