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
# Warmup Iteration   1: 5.087 ops/ms
# Warmup Iteration   2: 12.148 ops/ms
# Warmup Iteration   3: 12.505 ops/ms
Iteration   1: 12.729 ops/ms
Iteration   2: 12.922 ops/ms
Iteration   3: 12.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.830 ±(99.9%) 1.764 ops/ms [Average]
  (min, avg, max) = (12.729, 12.830, 12.922), stdev = 0.097
  CI (99.9%): [11.067, 14.594] (assumes normal distribution)


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
# Warmup Iteration   1: 8.392 ops/ms
# Warmup Iteration   2: 13.209 ops/ms
# Warmup Iteration   3: 13.376 ops/ms
Iteration   1: 13.277 ops/ms
Iteration   2: 13.385 ops/ms
Iteration   3: 13.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.399 ±(99.9%) 2.342 ops/ms [Average]
  (min, avg, max) = (13.277, 13.399, 13.533), stdev = 0.128
  CI (99.9%): [11.057, 15.740] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.318 ops/ms
# Warmup Iteration   2: 12.755 ops/ms
# Warmup Iteration   3: 12.832 ops/ms
Iteration   1: 12.970 ops/ms
Iteration   2: 12.781 ops/ms
Iteration   3: 12.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.771 ±(99.9%) 3.713 ops/ms [Average]
  (min, avg, max) = (12.563, 12.771, 12.970), stdev = 0.204
  CI (99.9%): [9.058, 16.484] (assumes normal distribution)


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
# Warmup Iteration   1: 6.514 ops/ms
# Warmup Iteration   2: 10.510 ops/ms
# Warmup Iteration   3: 10.560 ops/ms
Iteration   1: 10.723 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.681 ±(99.9%) 0.864 ops/ms [Average]
  (min, avg, max) = (10.630, 10.681, 10.723), stdev = 0.047
  CI (99.9%): [9.818, 11.545] (assumes normal distribution)


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.004 ms/op
Iteration   1: 2.547 ±(99.9%) 0.005 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.584 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.560 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.547, 2.560, 2.584), stdev = 0.021
  CI (99.9%): [2.174, 2.946] (assumes normal distribution)


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
# Warmup Iteration   1: 3.458 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.003 ms/op
Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
Iteration   3: 2.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.032 ms/op [Average]
  (min, avg, max) = (2.442, 2.443, 2.445), stdev = 0.002
  CI (99.9%): [2.411, 2.476] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.003 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.484, 2.501, 2.519), stdev = 0.018
  CI (99.9%): [2.177, 2.825] (assumes normal distribution)


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.004 ms/op
Iteration   1: 3.009 ±(99.9%) 0.005 ms/op
Iteration   2: 3.019 ±(99.9%) 0.004 ms/op
Iteration   3: 2.988 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.005 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.988, 3.005, 3.019), stdev = 0.016
  CI (99.9%): [2.713, 3.297] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.631 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.804 ms/op
                 createUser·p0.999:  11.277 ms/op
                 createUser·p0.9999: 15.167 ms/op
                 createUser·p1.00:   16.482 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  6.449 ms/op
                 createUser·p0.9999: 12.239 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  9.311 ms/op
                 createUser·p0.9999: 11.948 ms/op
                 createUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385241
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 186177 
    [ 2.500,  3.750) = 194968 
    [ 3.750,  5.000) = 3313 
    [ 5.000,  6.250) = 330 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      9.219 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     16.014 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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
# Warmup Iteration   1: 3.609 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  6.024 ms/op
                 existUser·p0.9999: 13.926 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   2: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  5.620 ms/op
                 existUser·p0.9999: 12.726 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  6.088 ms/op
                 existUser·p0.9999: 11.993 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395053
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 199174 
    [ 2.500,  3.750) = 193312 
    [ 3.750,  5.000) = 1786 
    [ 5.000,  6.250) = 365 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.473 ms/op
     p(99.9000) =      5.865 ms/op
     p(99.9900) =     13.001 ms/op
     p(99.9990) =     14.011 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.428 ms/op
                 getUser·p0.999:  6.282 ms/op
                 getUser·p0.9999: 13.846 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  8.683 ms/op
                 getUser·p0.9999: 12.785 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  9.208 ms/op
                 getUser·p0.9999: 11.993 ms/op
                 getUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383286
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 188858 
    [ 2.500,  3.750) = 189072 
    [ 3.750,  5.000) = 4297 
    [ 5.000,  6.250) = 602 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      8.850 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 4.762 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.008 ms/op
Iteration   1: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  9.485 ms/op
                 listUser·p0.9999: 10.781 ms/op
                 listUser·p1.00:   11.059 ms/op

Iteration   2: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 12.200 ms/op
                 listUser·p1.00:   12.845 ms/op

Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 10.560 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316205
  mean =      3.033 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 90258 
    [ 2.500,  3.750) = 185782 
    [ 3.750,  5.000) = 32323 
    [ 5.000,  6.250) = 6232 
    [ 6.250,  7.500) = 791 
    [ 7.500,  8.750) = 220 
    [ 8.750, 10.000) = 350 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     11.383 ms/op
     p(99.9990) =     12.564 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.830 ± 1.764  ops/ms
ClientPb.existUser                       thrpt       3  13.399 ± 2.342  ops/ms
ClientPb.getUser                         thrpt       3  12.771 ± 3.713  ops/ms
ClientPb.listUser                        thrpt       3  10.681 ± 0.864  ops/ms
ClientPb.createUser                       avgt       3   2.560 ± 0.386   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.032   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 0.324   ms/op
ClientPb.listUser                         avgt       3   3.005 ± 0.292   ms/op
ClientPb.createUser                     sample  385241   2.489 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.990           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.219           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.255           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.482           ms/op
ClientPb.existUser                      sample  395053   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.897           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.865           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.001           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.107           ms/op
ClientPb.getUser                        sample  383286   2.503 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.915           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.850           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.599           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.352           ms/op
ClientPb.listUser                       sample  316205   3.033 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.876           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.383           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.845           ms/op
