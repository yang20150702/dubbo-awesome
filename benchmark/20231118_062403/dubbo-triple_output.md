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
# Warmup Iteration   1: 4.737 ops/ms
# Warmup Iteration   2: 11.735 ops/ms
# Warmup Iteration   3: 12.100 ops/ms
Iteration   1: 12.175 ops/ms
Iteration   2: 12.369 ops/ms
Iteration   3: 12.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.313 ±(99.9%) 2.206 ops/ms [Average]
  (min, avg, max) = (12.175, 12.313, 12.396), stdev = 0.121
  CI (99.9%): [10.108, 14.519] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.705 ops/ms
# Warmup Iteration   2: 12.701 ops/ms
# Warmup Iteration   3: 12.809 ops/ms
Iteration   1: 12.731 ops/ms
Iteration   2: 12.805 ops/ms
Iteration   3: 12.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.815 ±(99.9%) 1.628 ops/ms [Average]
  (min, avg, max) = (12.731, 12.815, 12.909), stdev = 0.089
  CI (99.9%): [11.187, 14.443] (assumes normal distribution)


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
# Warmup Iteration   1: 7.261 ops/ms
# Warmup Iteration   2: 12.377 ops/ms
# Warmup Iteration   3: 12.622 ops/ms
Iteration   1: 12.788 ops/ms
Iteration   2: 12.698 ops/ms
Iteration   3: 12.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.704 ±(99.9%) 1.479 ops/ms [Average]
  (min, avg, max) = (12.627, 12.704, 12.788), stdev = 0.081
  CI (99.9%): [11.226, 14.183] (assumes normal distribution)


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
# Warmup Iteration   1: 6.221 ops/ms
# Warmup Iteration   2: 10.247 ops/ms
# Warmup Iteration   3: 10.398 ops/ms
Iteration   1: 10.429 ops/ms
Iteration   2: 10.489 ops/ms
Iteration   3: 10.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.416 ±(99.9%) 1.476 ops/ms [Average]
  (min, avg, max) = (10.329, 10.416, 10.489), stdev = 0.081
  CI (99.9%): [8.939, 11.892] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.127 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.004 ms/op
Iteration   1: 2.542 ±(99.9%) 0.004 ms/op
Iteration   2: 2.591 ±(99.9%) 0.004 ms/op
Iteration   3: 2.523 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.552 ±(99.9%) 0.639 ms/op [Average]
  (min, avg, max) = (2.523, 2.552, 2.591), stdev = 0.035
  CI (99.9%): [1.913, 3.192] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.498 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (2.479, 2.498, 2.524), stdev = 0.024
  CI (99.9%): [2.066, 2.930] (assumes normal distribution)


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.004 ms/op
Iteration   1: 2.562 ±(99.9%) 0.004 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.553 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.557 ±(99.9%) 0.085 ms/op [Average]
  (min, avg, max) = (2.553, 2.557, 2.562), stdev = 0.005
  CI (99.9%): [2.472, 2.641] (assumes normal distribution)


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
# Warmup Iteration   1: 4.745 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.004 ms/op
Iteration   1: 3.099 ±(99.9%) 0.006 ms/op
Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
Iteration   3: 3.069 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.080 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (3.069, 3.080, 3.099), stdev = 0.017
  CI (99.9%): [2.769, 3.390] (assumes normal distribution)


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.689 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.607 ±(99.9%) 0.006 ms/op
Iteration   1: 2.555 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  12.049 ms/op
                 createUser·p0.9999: 13.697 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  10.929 ms/op
                 createUser·p0.9999: 12.812 ms/op
                 createUser·p1.00:   13.238 ms/op

Iteration   3: 2.575 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.660 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  8.256 ms/op
                 createUser·p0.9999: 10.725 ms/op
                 createUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374243
  mean =      2.562 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 176989 
    [ 2.500,  3.750) = 192725 
    [ 3.750,  5.000) = 3488 
    [ 5.000,  6.250) = 549 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      9.057 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     13.952 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  11.502 ms/op
                 existUser·p0.9999: 13.688 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  8.394 ms/op
                 existUser·p0.9999: 14.340 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.965 ms/op
                 existUser·p0.999:  6.005 ms/op
                 existUser·p0.9999: 12.108 ms/op
                 existUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381988
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 186620 
    [ 2.500,  3.750) = 191531 
    [ 3.750,  5.000) = 2932 
    [ 5.000,  6.250) = 444 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 148 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      6.791 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.689 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  12.141 ms/op
                 getUser·p0.9999: 17.513 ms/op
                 getUser·p1.00:   18.678 ms/op

Iteration   2: 2.551 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  10.606 ms/op
                 getUser·p0.9999: 13.304 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  5.115 ms/op
                 getUser·p0.9999: 10.350 ms/op
                 getUser·p1.00:   10.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377508
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 183906 
    [ 2.500,  3.750) = 188404 
    [ 3.750,  5.000) = 4050 
    [ 5.000,  6.250) = 749 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      6.160 ms/op
     p(99.9900) =     14.111 ms/op
     p(99.9990) =     18.333 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 5.005 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.009 ms/op
Iteration   1: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.706 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 11.739 ms/op
                 listUser·p1.00:   12.435 ms/op

Iteration   2: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  10.450 ms/op
                 listUser·p0.9999: 14.319 ms/op
                 listUser·p1.00:   15.057 ms/op

Iteration   3: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  10.528 ms/op
                 listUser·p0.9999: 12.215 ms/op
                 listUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314789
  mean =      3.047 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 87732 
    [ 2.500,  3.750) = 186075 
    [ 3.750,  5.000) = 33026 
    [ 5.000,  6.250) = 6195 
    [ 6.250,  7.500) = 887 
    [ 7.500,  8.750) = 135 
    [ 8.750, 10.000) = 269 
    [10.000, 11.250) = 204 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     10.142 ms/op
     p(99.9900) =     13.354 ms/op
     p(99.9990) =     14.780 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.313 ± 2.206  ops/ms
ClientPb.existUser                       thrpt       3  12.815 ± 1.628  ops/ms
ClientPb.getUser                         thrpt       3  12.704 ± 1.479  ops/ms
ClientPb.listUser                        thrpt       3  10.416 ± 1.476  ops/ms
ClientPb.createUser                       avgt       3   2.552 ± 0.639   ms/op
ClientPb.existUser                        avgt       3   2.498 ± 0.432   ms/op
ClientPb.getUser                          avgt       3   2.557 ± 0.085   ms/op
ClientPb.listUser                         avgt       3   3.080 ± 0.311   ms/op
ClientPb.createUser                     sample  374243   2.562 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.824           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.650           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.057           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  381988   2.510 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.846           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.791           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.713           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.647           ms/op
ClientPb.getUser                        sample  377508   2.541 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.946           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.160           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.111           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.678           ms/op
ClientPb.listUser                       sample  314789   3.047 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.818           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.354           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.057           ms/op
