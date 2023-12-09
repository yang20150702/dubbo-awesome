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
# Warmup Iteration   1: 4.409 ops/ms
# Warmup Iteration   2: 11.764 ops/ms
# Warmup Iteration   3: 12.026 ops/ms
Iteration   1: 12.329 ops/ms
Iteration   2: 12.374 ops/ms
Iteration   3: 12.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.394 ±(99.9%) 1.398 ops/ms [Average]
  (min, avg, max) = (12.329, 12.394, 12.478), stdev = 0.077
  CI (99.9%): [10.996, 13.792] (assumes normal distribution)


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
# Warmup Iteration   1: 8.197 ops/ms
# Warmup Iteration   2: 12.754 ops/ms
# Warmup Iteration   3: 12.877 ops/ms
Iteration   1: 12.924 ops/ms
Iteration   2: 13.007 ops/ms
Iteration   3: 12.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.974 ±(99.9%) 0.813 ops/ms [Average]
  (min, avg, max) = (12.924, 12.974, 13.007), stdev = 0.045
  CI (99.9%): [12.162, 13.787] (assumes normal distribution)


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
# Warmup Iteration   1: 7.756 ops/ms
# Warmup Iteration   2: 12.698 ops/ms
# Warmup Iteration   3: 12.746 ops/ms
Iteration   1: 12.640 ops/ms
Iteration   2: 12.907 ops/ms
Iteration   3: 12.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.776 ±(99.9%) 2.433 ops/ms [Average]
  (min, avg, max) = (12.640, 12.776, 12.907), stdev = 0.133
  CI (99.9%): [10.342, 15.209] (assumes normal distribution)


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
# Warmup Iteration   1: 6.423 ops/ms
# Warmup Iteration   2: 10.222 ops/ms
# Warmup Iteration   3: 10.311 ops/ms
Iteration   1: 10.349 ops/ms
Iteration   2: 10.363 ops/ms
Iteration   3: 10.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.334 ±(99.9%) 0.721 ops/ms [Average]
  (min, avg, max) = (10.289, 10.334, 10.363), stdev = 0.040
  CI (99.9%): [9.612, 11.055] (assumes normal distribution)


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
# Warmup Iteration   1: 4.277 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.004 ms/op
Iteration   1: 2.552 ±(99.9%) 0.004 ms/op
Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (2.552, 2.558, 2.562), stdev = 0.005
  CI (99.9%): [2.461, 2.655] (assumes normal distribution)


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.003 ms/op
Iteration   2: 2.491 ±(99.9%) 0.006 ms/op
Iteration   3: 2.468 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.471 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (2.454, 2.471, 2.491), stdev = 0.019
  CI (99.9%): [2.133, 2.808] (assumes normal distribution)


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.003 ms/op
Iteration   1: 2.532 ±(99.9%) 0.004 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.531 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (2.521, 2.531, 2.540), stdev = 0.010
  CI (99.9%): [2.357, 2.704] (assumes normal distribution)


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
Iteration   3: 3.046 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.053 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (3.046, 3.053, 3.058), stdev = 0.006
  CI (99.9%): [2.948, 3.158] (assumes normal distribution)


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.006 ms/op
Iteration   1: 2.569 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  11.297 ms/op
                 createUser·p0.9999: 14.063 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  9.412 ms/op
                 createUser·p0.9999: 13.819 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   3: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.022 ms/op
                 createUser·p0.999:  8.507 ms/op
                 createUser·p0.9999: 13.615 ms/op
                 createUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374782
  mean =      2.560 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 178140 
    [ 2.500,  3.750) = 192097 
    [ 3.750,  5.000) = 3764 
    [ 5.000,  6.250) = 297 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     13.795 ms/op
     p(99.9990) =     14.668 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.379 ms/op
                 existUser·p0.999:  5.460 ms/op
                 existUser·p0.9999: 17.138 ms/op
                 existUser·p1.00:   17.957 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  7.927 ms/op
                 existUser·p0.9999: 16.171 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  8.538 ms/op
                 existUser·p0.9999: 12.272 ms/op
                 existUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387306
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 189587 
    [ 2.500,  3.750) = 194991 
    [ 3.750,  5.000) = 2024 
    [ 5.000,  6.250) = 278 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      6.420 ms/op
     p(99.9900) =     16.263 ms/op
     p(99.9990) =     17.404 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.669 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
Iteration   1: 2.555 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  11.399 ms/op
                 getUser·p0.9999: 14.049 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  5.820 ms/op
                 getUser·p0.9999: 12.597 ms/op
                 getUser·p1.00:   12.943 ms/op

Iteration   3: 2.598 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.162 ms/op
                 getUser·p0.95:   3.359 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  8.797 ms/op
                 getUser·p0.9999: 12.856 ms/op
                 getUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 373781
  mean =      2.566 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 180655 
    [ 2.500,  3.750) = 186751 
    [ 3.750,  5.000) = 4784 
    [ 5.000,  6.250) = 1086 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =      6.895 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 4.885 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.009 ms/op
Iteration   1: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.562 ms/op
                 listUser·p0.9999: 12.059 ms/op
                 listUser·p1.00:   13.844 ms/op

Iteration   2: 3.090 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  9.504 ms/op
                 listUser·p0.9999: 12.299 ms/op
                 listUser·p1.00:   13.287 ms/op

Iteration   3: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.148 ms/op
                 listUser·p0.9999: 10.789 ms/op
                 listUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312277
  mean =      3.071 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 80797 
    [ 2.500,  3.750) = 189235 
    [ 3.750,  5.000) = 34116 
    [ 5.000,  6.250) = 6353 
    [ 6.250,  7.500) = 983 
    [ 7.500,  8.750) = 287 
    [ 8.750, 10.000) = 225 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      9.400 ms/op
     p(99.9900) =     11.957 ms/op
     p(99.9990) =     13.650 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.394 ± 1.398  ops/ms
ClientPb.existUser                       thrpt       3  12.974 ± 0.813  ops/ms
ClientPb.getUser                         thrpt       3  12.776 ± 2.433  ops/ms
ClientPb.listUser                        thrpt       3  10.334 ± 0.721  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.097   ms/op
ClientPb.existUser                        avgt       3   2.471 ± 0.338   ms/op
ClientPb.getUser                          avgt       3   2.531 ± 0.173   ms/op
ClientPb.listUser                         avgt       3   3.053 ± 0.105   ms/op
ClientPb.createUser                     sample  374782   2.560 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.938           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.585           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.795           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.893           ms/op
ClientPb.existUser                      sample  387306   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.992           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.420           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.263           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.957           ms/op
ClientPb.getUser                        sample  373781   2.566 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.906           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.593           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.141           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.895           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.337           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  312277   3.071 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.856           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.400           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.957           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.844           ms/op
