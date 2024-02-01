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
# Warmup Iteration   1: 4.803 ops/ms
# Warmup Iteration   2: 11.860 ops/ms
# Warmup Iteration   3: 12.284 ops/ms
Iteration   1: 12.357 ops/ms
Iteration   2: 12.524 ops/ms
Iteration   3: 12.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.430 ±(99.9%) 1.552 ops/ms [Average]
  (min, avg, max) = (12.357, 12.430, 12.524), stdev = 0.085
  CI (99.9%): [10.878, 13.983] (assumes normal distribution)


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
# Warmup Iteration   1: 7.878 ops/ms
# Warmup Iteration   2: 12.712 ops/ms
# Warmup Iteration   3: 12.847 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 12.842 ops/ms
Iteration   3: 12.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.812 ±(99.9%) 0.681 ops/ms [Average]
  (min, avg, max) = (12.770, 12.812, 12.842), stdev = 0.037
  CI (99.9%): [12.131, 13.493] (assumes normal distribution)


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
# Warmup Iteration   1: 7.305 ops/ms
# Warmup Iteration   2: 12.260 ops/ms
# Warmup Iteration   3: 12.476 ops/ms
Iteration   1: 12.620 ops/ms
Iteration   2: 12.605 ops/ms
Iteration   3: 12.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.523 ±(99.9%) 2.845 ops/ms [Average]
  (min, avg, max) = (12.343, 12.523, 12.620), stdev = 0.156
  CI (99.9%): [9.678, 15.368] (assumes normal distribution)


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
# Warmup Iteration   1: 6.474 ops/ms
# Warmup Iteration   2: 10.630 ops/ms
# Warmup Iteration   3: 10.693 ops/ms
Iteration   1: 10.733 ops/ms
Iteration   2: 10.698 ops/ms
Iteration   3: 10.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.687 ±(99.9%) 0.959 ops/ms [Average]
  (min, avg, max) = (10.630, 10.687, 10.733), stdev = 0.053
  CI (99.9%): [9.728, 11.646] (assumes normal distribution)


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.650 ±(99.9%) 0.005 ms/op
Iteration   1: 2.591 ±(99.9%) 0.004 ms/op
Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
Iteration   3: 2.565 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.577 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (2.565, 2.577, 2.591), stdev = 0.013
  CI (99.9%): [2.337, 2.817] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.665 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.438 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.004 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.460 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (2.458, 2.460, 2.463), stdev = 0.003
  CI (99.9%): [2.412, 2.509] (assumes normal distribution)


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.004 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.565 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.550 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (2.537, 2.550, 2.565), stdev = 0.014
  CI (99.9%): [2.291, 2.810] (assumes normal distribution)


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
# Warmup Iteration   1: 4.820 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.004 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.010 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.000, 3.010, 3.030), stdev = 0.017
  CI (99.9%): [2.702, 3.319] (assumes normal distribution)


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
# Warmup Iteration   1: 4.195 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  11.539 ms/op
                 createUser·p0.9999: 13.487 ms/op
                 createUser·p1.00:   13.697 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  9.793 ms/op
                 createUser·p0.9999: 12.224 ms/op
                 createUser·p1.00:   12.435 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 13.311 ms/op
                 createUser·p1.00:   14.434 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380058
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 185047 
    [ 2.500,  3.750) = 191177 
    [ 3.750,  5.000) = 2892 
    [ 5.000,  6.250) = 346 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      9.305 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     14.290 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  7.878 ms/op
                 existUser·p0.9999: 14.156 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  7.514 ms/op
                 existUser·p0.9999: 12.861 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.031 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  5.499 ms/op
                 existUser·p0.9999: 11.978 ms/op
                 existUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389611
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 194311 
    [ 2.500,  3.750) = 192360 
    [ 3.750,  5.000) = 2277 
    [ 5.000,  6.250) = 191 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      6.905 ms/op
     p(99.9900) =     13.323 ms/op
     p(99.9990) =     14.795 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.160 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  8.989 ms/op
                 getUser·p0.9999: 13.795 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   2: 2.557 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  8.749 ms/op
                 getUser·p0.9999: 14.197 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  8.457 ms/op
                 getUser·p0.9999: 13.124 ms/op
                 getUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380714
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 187551 
    [ 2.500,  3.750) = 187198 
    [ 3.750,  5.000) = 4292 
    [ 5.000,  6.250) = 1170 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.761 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 4.813 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.008 ms/op
Iteration   1: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.450 ms/op
                 listUser·p0.999:  8.882 ms/op
                 listUser·p0.9999: 11.411 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   2: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.091 ms/op
                 listUser·p0.9999: 10.994 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.422 ms/op
                 listUser·p0.9999: 10.705 ms/op
                 listUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315963
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 85837 
    [ 2.500,  3.750) = 189551 
    [ 3.750,  5.000) = 33468 
    [ 5.000,  6.250) = 5538 
    [ 6.250,  7.500) = 723 
    [ 7.500,  8.750) = 330 
    [ 8.750, 10.000) = 262 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.143 ms/op
     p(99.9900) =     10.994 ms/op
     p(99.9990) =     11.827 ms/op
     p(99.9999) =     12.059 ms/op
    p(100.0000) =     12.059 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.430 ± 1.552  ops/ms
ClientPb.existUser                       thrpt       3  12.812 ± 0.681  ops/ms
ClientPb.getUser                         thrpt       3  12.523 ± 2.845  ops/ms
ClientPb.listUser                        thrpt       3  10.687 ± 0.959  ops/ms
ClientPb.createUser                       avgt       3   2.577 ± 0.240   ms/op
ClientPb.existUser                        avgt       3   2.460 ± 0.048   ms/op
ClientPb.getUser                          avgt       3   2.550 ± 0.260   ms/op
ClientPb.listUser                         avgt       3   3.010 ± 0.309   ms/op
ClientPb.createUser                     sample  380058   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.783           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.305           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.434           ms/op
ClientPb.existUser                      sample  389611   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.870           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.905           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.323           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.860           ms/op
ClientPb.getUser                        sample  380714   2.519 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.882           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.520           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.779           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.139           ms/op
ClientPb.listUser                       sample  315963   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.877           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.143           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.994           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.059           ms/op
