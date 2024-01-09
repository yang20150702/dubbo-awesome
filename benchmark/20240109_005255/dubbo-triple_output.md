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
# Warmup Iteration   1: 4.947 ops/ms
# Warmup Iteration   2: 11.941 ops/ms
# Warmup Iteration   3: 12.132 ops/ms
Iteration   1: 12.355 ops/ms
Iteration   2: 12.354 ops/ms
Iteration   3: 12.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.424 ±(99.9%) 2.193 ops/ms [Average]
  (min, avg, max) = (12.354, 12.424, 12.563), stdev = 0.120
  CI (99.9%): [10.231, 14.617] (assumes normal distribution)


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
# Warmup Iteration   1: 8.004 ops/ms
# Warmup Iteration   2: 12.959 ops/ms
# Warmup Iteration   3: 12.980 ops/ms
Iteration   1: 13.108 ops/ms
Iteration   2: 13.161 ops/ms
Iteration   3: 13.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.156 ±(99.9%) 0.846 ops/ms [Average]
  (min, avg, max) = (13.108, 13.156, 13.200), stdev = 0.046
  CI (99.9%): [12.311, 14.002] (assumes normal distribution)


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
# Warmup Iteration   1: 7.523 ops/ms
# Warmup Iteration   2: 12.632 ops/ms
# Warmup Iteration   3: 12.698 ops/ms
Iteration   1: 12.727 ops/ms
Iteration   2: 12.865 ops/ms
Iteration   3: 12.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.824 ±(99.9%) 1.532 ops/ms [Average]
  (min, avg, max) = (12.727, 12.824, 12.879), stdev = 0.084
  CI (99.9%): [11.292, 14.356] (assumes normal distribution)


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
# Warmup Iteration   1: 6.498 ops/ms
# Warmup Iteration   2: 10.438 ops/ms
# Warmup Iteration   3: 10.453 ops/ms
Iteration   1: 10.498 ops/ms
Iteration   2: 10.617 ops/ms
Iteration   3: 10.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.571 ±(99.9%) 1.171 ops/ms [Average]
  (min, avg, max) = (10.498, 10.571, 10.617), stdev = 0.064
  CI (99.9%): [9.400, 11.742] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
Iteration   1: 2.552 ±(99.9%) 0.004 ms/op
Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
Iteration   3: 2.518 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.536 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (2.518, 2.536, 2.552), stdev = 0.017
  CI (99.9%): [2.228, 2.845] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.466 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.455, 2.466, 2.475), stdev = 0.010
  CI (99.9%): [2.278, 2.655] (assumes normal distribution)


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.108 ms/op [Average]
  (min, avg, max) = (2.490, 2.494, 2.501), stdev = 0.006
  CI (99.9%): [2.386, 2.601] (assumes normal distribution)


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
# Warmup Iteration   1: 4.721 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.005 ms/op
Iteration   1: 3.035 ±(99.9%) 0.007 ms/op
Iteration   2: 3.024 ±(99.9%) 0.004 ms/op
Iteration   3: 3.010 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.023 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.010, 3.023, 3.035), stdev = 0.012
  CI (99.9%): [2.800, 3.246] (assumes normal distribution)


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.690 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.006 ms/op
Iteration   1: 2.566 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  11.443 ms/op
                 createUser·p0.9999: 17.516 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  10.724 ms/op
                 createUser·p0.9999: 12.187 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.977 ms/op
                 createUser·p0.999:  8.999 ms/op
                 createUser·p0.9999: 13.378 ms/op
                 createUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376133
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 179750 
    [ 2.500,  3.750) = 191838 
    [ 3.750,  5.000) = 3487 
    [ 5.000,  6.250) = 583 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      9.025 ms/op
     p(99.9900) =     14.205 ms/op
     p(99.9990) =     18.177 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  4.946 ms/op
                 existUser·p0.9999: 13.946 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  7.905 ms/op
                 existUser·p0.9999: 12.599 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   4.052 ms/op
                 existUser·p0.999:  6.175 ms/op
                 existUser·p0.9999: 12.162 ms/op
                 existUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384603
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 189796 
    [ 2.500,  3.750) = 191053 
    [ 3.750,  5.000) = 2948 
    [ 5.000,  6.250) = 370 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      6.262 ms/op
     p(99.9900) =     13.387 ms/op
     p(99.9990) =     14.768 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  5.351 ms/op
                 getUser·p0.9999: 12.931 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  10.109 ms/op
                 getUser·p0.9999: 13.147 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.300 ms/op
                 getUser·p0.9999: 11.420 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378454
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 184430 
    [ 2.500,  3.750) = 187190 
    [ 3.750,  5.000) = 5085 
    [ 5.000,  6.250) = 1287 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.452 ms/op
     p(99.9900) =     12.930 ms/op
     p(99.9990) =     13.931 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 4.853 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.008 ms/op
Iteration   1: 2.927 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.756 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   5.300 ms/op
                 listUser·p0.999:  9.097 ms/op
                 listUser·p0.9999: 11.207 ms/op
                 listUser·p1.00:   11.731 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.711 ms/op
                 listUser·p0.9999: 12.546 ms/op
                 listUser·p1.00:   13.484 ms/op

Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.567 ms/op
                 listUser·p0.9999: 12.217 ms/op
                 listUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322212
  mean =      2.977 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 172 
    [ 1.250,  2.500) = 95648 
    [ 2.500,  3.750) = 190562 
    [ 3.750,  5.000) = 29748 
    [ 5.000,  6.250) = 5016 
    [ 6.250,  7.500) = 503 
    [ 7.500,  8.750) = 149 
    [ 8.750, 10.000) = 190 
    [10.000, 11.250) = 151 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      9.335 ms/op
     p(99.9900) =     11.864 ms/op
     p(99.9990) =     13.133 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.424 ± 2.193  ops/ms
ClientPb.existUser                       thrpt       3  13.156 ± 0.846  ops/ms
ClientPb.getUser                         thrpt       3  12.824 ± 1.532  ops/ms
ClientPb.listUser                        thrpt       3  10.571 ± 1.171  ops/ms
ClientPb.createUser                       avgt       3   2.536 ± 0.309   ms/op
ClientPb.existUser                        avgt       3   2.466 ± 0.188   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.108   ms/op
ClientPb.listUser                         avgt       3   3.023 ± 0.223   ms/op
ClientPb.createUser                     sample  376133   2.550 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.877           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.025           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.205           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.104           ms/op
ClientPb.existUser                      sample  384603   2.494 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.902           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.262           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.387           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.630           ms/op
ClientPb.getUser                        sample  378454   2.535 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.935           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.452           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.930           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.107           ms/op
ClientPb.listUser                       sample  322212   2.977 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.807           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.335           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.864           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.484           ms/op
