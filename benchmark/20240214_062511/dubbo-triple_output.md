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
# Warmup Iteration   1: 5.100 ops/ms
# Warmup Iteration   2: 12.323 ops/ms
# Warmup Iteration   3: 12.367 ops/ms
Iteration   1: 12.613 ops/ms
Iteration   2: 12.536 ops/ms
Iteration   3: 12.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.554 ±(99.9%) 0.966 ops/ms [Average]
  (min, avg, max) = (12.512, 12.554, 12.613), stdev = 0.053
  CI (99.9%): [11.588, 13.519] (assumes normal distribution)


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
# Warmup Iteration   1: 8.360 ops/ms
# Warmup Iteration   2: 12.965 ops/ms
# Warmup Iteration   3: 13.065 ops/ms
Iteration   1: 13.065 ops/ms
Iteration   2: 13.149 ops/ms
Iteration   3: 13.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.076 ±(99.9%) 1.243 ops/ms [Average]
  (min, avg, max) = (13.014, 13.076, 13.149), stdev = 0.068
  CI (99.9%): [11.833, 14.319] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.707 ops/ms
# Warmup Iteration   2: 12.480 ops/ms
# Warmup Iteration   3: 12.639 ops/ms
Iteration   1: 12.701 ops/ms
Iteration   2: 12.880 ops/ms
Iteration   3: 12.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.765 ±(99.9%) 1.817 ops/ms [Average]
  (min, avg, max) = (12.701, 12.765, 12.880), stdev = 0.100
  CI (99.9%): [10.948, 14.582] (assumes normal distribution)


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
# Warmup Iteration   1: 6.895 ops/ms
# Warmup Iteration   2: 10.527 ops/ms
# Warmup Iteration   3: 10.726 ops/ms
Iteration   1: 10.629 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.627 ±(99.9%) 0.047 ops/ms [Average]
  (min, avg, max) = (10.624, 10.627, 10.629), stdev = 0.003
  CI (99.9%): [10.579, 10.674] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.049 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.003 ms/op
Iteration   1: 2.568 ±(99.9%) 0.005 ms/op
Iteration   2: 2.594 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.567 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (2.538, 2.567, 2.594), stdev = 0.028
  CI (99.9%): [2.048, 3.085] (assumes normal distribution)


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
# Warmup Iteration   1: 3.645 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.483 ±(99.9%) 0.004 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.480 ±(99.9%) 0.061 ms/op [Average]
  (min, avg, max) = (2.476, 2.480, 2.483), stdev = 0.003
  CI (99.9%): [2.419, 2.540] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.776 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.003 ms/op
Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.495 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (2.482, 2.495, 2.504), stdev = 0.011
  CI (99.9%): [2.290, 2.700] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.502 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
Iteration   2: 2.994 ±(99.9%) 0.005 ms/op
Iteration   3: 2.971 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (2.971, 2.987, 2.997), stdev = 0.015
  CI (99.9%): [2.723, 3.252] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.227 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.557 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  11.858 ms/op
                 createUser·p0.9999: 13.926 ms/op
                 createUser·p1.00:   14.811 ms/op

Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  10.021 ms/op
                 createUser·p0.9999: 15.090 ms/op
                 createUser·p1.00:   15.958 ms/op

Iteration   3: 2.565 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  8.492 ms/op
                 createUser·p0.9999: 11.461 ms/op
                 createUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374449
  mean =      2.561 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 180949 
    [ 2.500,  3.750) = 189978 
    [ 3.750,  5.000) = 2657 
    [ 5.000,  6.250) = 326 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      8.554 ms/op
     p(99.9900) =     14.270 ms/op
     p(99.9990) =     15.925 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.619 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  7.322 ms/op
                 existUser·p0.9999: 13.662 ms/op
                 existUser·p1.00:   15.761 ms/op

Iteration   2: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.445 ms/op
                 existUser·p0.999:  6.360 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  8.169 ms/op
                 existUser·p0.9999: 12.248 ms/op
                 existUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393328
  mean =      2.439 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 195081 
    [ 2.500,  3.750) = 195402 
    [ 3.750,  5.000) = 1946 
    [ 5.000,  6.250) = 342 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      6.922 ms/op
     p(99.9900) =     13.200 ms/op
     p(99.9990) =     14.110 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  10.854 ms/op
                 getUser·p0.9999: 13.225 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  9.530 ms/op
                 getUser·p0.9999: 12.354 ms/op
                 getUser·p1.00:   13.025 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  6.021 ms/op
                 getUser·p0.9999: 12.669 ms/op
                 getUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383012
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 190566 
    [ 2.500,  3.750) = 188458 
    [ 3.750,  5.000) = 2925 
    [ 5.000,  6.250) = 555 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      6.906 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     13.607 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.498 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.009 ms/op
Iteration   1: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  8.654 ms/op
                 listUser·p0.9999: 9.753 ms/op
                 listUser·p1.00:   10.650 ms/op

Iteration   2: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.716 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 11.589 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.698 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  10.043 ms/op
                 listUser·p0.9999: 11.796 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320690
  mean =      2.991 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 96486 
    [ 2.500,  3.750) = 186176 
    [ 3.750,  5.000) = 30835 
    [ 5.000,  6.250) = 5632 
    [ 6.250,  7.500) = 776 
    [ 7.500,  8.750) = 210 
    [ 8.750, 10.000) = 250 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     11.387 ms/op
     p(99.9990) =     12.260 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.554 ± 0.966  ops/ms
ClientPb.existUser                       thrpt       3  13.076 ± 1.243  ops/ms
ClientPb.getUser                         thrpt       3  12.765 ± 1.817  ops/ms
ClientPb.listUser                        thrpt       3  10.627 ± 0.047  ops/ms
ClientPb.createUser                       avgt       3   2.567 ± 0.518   ms/op
ClientPb.existUser                        avgt       3   2.480 ± 0.061   ms/op
ClientPb.getUser                          avgt       3   2.495 ± 0.205   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.265   ms/op
ClientPb.createUser                     sample  374449   2.561 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.957           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.554           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.270           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.958           ms/op
ClientPb.existUser                      sample  393328   2.439 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.859           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.922           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.200           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.761           ms/op
ClientPb.getUser                        sample  383012   2.504 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.826           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.906           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.943           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.812           ms/op
ClientPb.listUser                       sample  320690   2.991 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.698           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.501           ms/op
