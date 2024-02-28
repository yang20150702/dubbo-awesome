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
# Warmup Iteration   1: 4.692 ops/ms
# Warmup Iteration   2: 12.035 ops/ms
# Warmup Iteration   3: 12.145 ops/ms
Iteration   1: 12.432 ops/ms
Iteration   2: 12.609 ops/ms
Iteration   3: 12.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.545 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (12.432, 12.545, 12.609), stdev = 0.098
  CI (99.9%): [10.750, 14.340] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.570 ops/ms
# Warmup Iteration   2: 13.106 ops/ms
# Warmup Iteration   3: 13.263 ops/ms
Iteration   1: 13.324 ops/ms
Iteration   2: 13.159 ops/ms
Iteration   3: 13.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.276 ±(99.9%) 1.857 ops/ms [Average]
  (min, avg, max) = (13.159, 13.276, 13.344), stdev = 0.102
  CI (99.9%): [11.419, 15.132] (assumes normal distribution)


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
# Warmup Iteration   1: 8.197 ops/ms
# Warmup Iteration   2: 12.676 ops/ms
# Warmup Iteration   3: 12.892 ops/ms
Iteration   1: 13.073 ops/ms
Iteration   2: 12.943 ops/ms
Iteration   3: 12.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.950 ±(99.9%) 2.186 ops/ms [Average]
  (min, avg, max) = (12.833, 12.950, 13.073), stdev = 0.120
  CI (99.9%): [10.764, 15.136] (assumes normal distribution)


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
# Warmup Iteration   1: 6.987 ops/ms
# Warmup Iteration   2: 10.569 ops/ms
# Warmup Iteration   3: 10.676 ops/ms
Iteration   1: 10.783 ops/ms
Iteration   2: 10.654 ops/ms
Iteration   3: 10.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.728 ±(99.9%) 1.204 ops/ms [Average]
  (min, avg, max) = (10.654, 10.728, 10.783), stdev = 0.066
  CI (99.9%): [9.523, 11.932] (assumes normal distribution)


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.003 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.449 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.472 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (2.449, 2.472, 2.494), stdev = 0.022
  CI (99.9%): [2.063, 2.880] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.837 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.004 ms/op
Iteration   1: 2.417 ±(99.9%) 0.004 ms/op
Iteration   2: 2.418 ±(99.9%) 0.003 ms/op
Iteration   3: 2.432 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.422 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (2.417, 2.422, 2.432), stdev = 0.008
  CI (99.9%): [2.273, 2.571] (assumes normal distribution)


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
# Warmup Iteration   1: 3.832 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.467 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (2.464, 2.467, 2.474), stdev = 0.006
  CI (99.9%): [2.360, 2.575] (assumes normal distribution)


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
# Warmup Iteration   1: 4.595 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.005 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
Iteration   2: 3.012 ±(99.9%) 0.004 ms/op
Iteration   3: 2.967 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.989 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (2.967, 2.989, 3.012), stdev = 0.022
  CI (99.9%): [2.579, 3.398] (assumes normal distribution)


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.701 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 13.304 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  7.940 ms/op
                 createUser·p0.9999: 12.225 ms/op
                 createUser·p1.00:   12.468 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  8.442 ms/op
                 createUser·p0.9999: 10.897 ms/op
                 createUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385211
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 186864 
    [ 2.500,  3.750) = 194352 
    [ 3.750,  5.000) = 3120 
    [ 5.000,  6.250) = 339 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      8.434 ms/op
     p(99.9900) =     12.926 ms/op
     p(99.9990) =     13.723 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 3.625 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.409 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.395 ±(99.9%) 0.005 ms/op
Iteration   1: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  5.531 ms/op
                 existUser·p0.9999: 13.771 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.396 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   3.550 ms/op
                 existUser·p0.999:  7.406 ms/op
                 existUser·p0.9999: 12.107 ms/op
                 existUser·p1.00:   12.567 ms/op

Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.450 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  6.425 ms/op
                 existUser·p0.9999: 11.493 ms/op
                 existUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398452
  mean =      2.407 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 200980 
    [ 2.500,  3.750) = 194103 
    [ 3.750,  5.000) = 2495 
    [ 5.000,  6.250) = 370 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      6.447 ms/op
     p(99.9900) =     13.061 ms/op
     p(99.9990) =     14.501 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 3.958 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  11.155 ms/op
                 getUser·p0.9999: 13.714 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  7.515 ms/op
                 getUser·p0.9999: 12.534 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  6.583 ms/op
                 getUser·p0.9999: 11.406 ms/op
                 getUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385693
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 192762 
    [ 2.500,  3.750) = 188403 
    [ 3.750,  5.000) = 3399 
    [ 5.000,  6.250) = 659 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      8.251 ms/op
     p(99.9900) =     13.278 ms/op
     p(99.9990) =     14.039 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 4.665 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.009 ms/op
Iteration   1: 2.957 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.846 ms/op
                 listUser·p0.9999: 10.069 ms/op
                 listUser·p1.00:   12.354 ms/op

Iteration   2: 2.955 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.074 ms/op
                 listUser·p0.9999: 10.866 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   3: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.707 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.615 ms/op
                 listUser·p0.999:  8.810 ms/op
                 listUser·p0.9999: 11.092 ms/op
                 listUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323512
  mean =      2.964 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 99311 
    [ 2.500,  3.750) = 187576 
    [ 3.750,  5.000) = 29680 
    [ 5.000,  6.250) = 5550 
    [ 6.250,  7.500) = 639 
    [ 7.500,  8.750) = 285 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     10.988 ms/op
     p(99.9990) =     12.044 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.545 ± 1.795  ops/ms
ClientPb.existUser                       thrpt       3  13.276 ± 1.857  ops/ms
ClientPb.getUser                         thrpt       3  12.950 ± 2.186  ops/ms
ClientPb.listUser                        thrpt       3  10.728 ± 1.204  ops/ms
ClientPb.createUser                       avgt       3   2.472 ± 0.409   ms/op
ClientPb.existUser                        avgt       3   2.422 ± 0.149   ms/op
ClientPb.getUser                          avgt       3   2.467 ± 0.107   ms/op
ClientPb.listUser                         avgt       3   2.989 ± 0.410   ms/op
ClientPb.createUser                     sample  385211   2.490 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.586           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.434           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.926           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.959           ms/op
ClientPb.existUser                      sample  398452   2.407 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.450           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.447           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.061           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.795           ms/op
ClientPb.getUser                        sample  385693   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.732           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.251           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.278           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.221           ms/op
ClientPb.listUser                       sample  323512   2.964 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.707           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.897           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.988           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.354           ms/op
