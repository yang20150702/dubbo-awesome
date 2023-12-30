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
# Warmup Iteration   1: 4.501 ops/ms
# Warmup Iteration   2: 11.944 ops/ms
# Warmup Iteration   3: 12.314 ops/ms
Iteration   1: 12.572 ops/ms
Iteration   2: 12.643 ops/ms
Iteration   3: 12.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.598 ±(99.9%) 0.711 ops/ms [Average]
  (min, avg, max) = (12.572, 12.598, 12.643), stdev = 0.039
  CI (99.9%): [11.887, 13.309] (assumes normal distribution)


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
# Warmup Iteration   1: 7.637 ops/ms
# Warmup Iteration   2: 13.140 ops/ms
# Warmup Iteration   3: 13.245 ops/ms
Iteration   1: 13.248 ops/ms
Iteration   2: 13.261 ops/ms
Iteration   3: 13.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.242 ±(99.9%) 0.410 ops/ms [Average]
  (min, avg, max) = (13.217, 13.242, 13.261), stdev = 0.022
  CI (99.9%): [12.832, 13.652] (assumes normal distribution)


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
# Warmup Iteration   1: 7.424 ops/ms
# Warmup Iteration   2: 12.436 ops/ms
# Warmup Iteration   3: 12.723 ops/ms
Iteration   1: 12.816 ops/ms
Iteration   2: 12.694 ops/ms
Iteration   3: 12.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.723 ±(99.9%) 1.510 ops/ms [Average]
  (min, avg, max) = (12.658, 12.723, 12.816), stdev = 0.083
  CI (99.9%): [11.213, 14.232] (assumes normal distribution)


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
# Warmup Iteration   1: 6.727 ops/ms
# Warmup Iteration   2: 10.312 ops/ms
# Warmup Iteration   3: 10.625 ops/ms
Iteration   1: 10.667 ops/ms
Iteration   2: 10.601 ops/ms
Iteration   3: 10.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.631 ±(99.9%) 0.613 ops/ms [Average]
  (min, avg, max) = (10.601, 10.631, 10.667), stdev = 0.034
  CI (99.9%): [10.018, 11.244] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.124 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.004 ms/op
Iteration   1: 2.586 ±(99.9%) 0.004 ms/op
Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
Iteration   3: 2.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.565 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (2.544, 2.565, 2.586), stdev = 0.021
  CI (99.9%): [2.178, 2.951] (assumes normal distribution)


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
# Warmup Iteration   1: 3.626 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.003 ms/op
Iteration   1: 2.428 ±(99.9%) 0.004 ms/op
Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
Iteration   3: 2.442 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.434 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.428, 2.434, 2.442), stdev = 0.007
  CI (99.9%): [2.303, 2.565] (assumes normal distribution)


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
# Warmup Iteration   1: 3.920 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.003 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (2.479, 2.502, 2.519), stdev = 0.021
  CI (99.9%): [2.128, 2.876] (assumes normal distribution)


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
# Warmup Iteration   1: 4.612 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.005 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
Iteration   3: 3.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (2.999, 3.007, 3.014), stdev = 0.007
  CI (99.9%): [2.871, 3.143] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.138 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  11.695 ms/op
                 createUser·p0.9999: 14.502 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  8.813 ms/op
                 createUser·p0.9999: 12.078 ms/op
                 createUser·p1.00:   12.403 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  8.896 ms/op
                 createUser·p0.9999: 11.631 ms/op
                 createUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382417
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 184793 
    [ 2.500,  3.750) = 193995 
    [ 3.750,  5.000) = 2907 
    [ 5.000,  6.250) = 231 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     14.779 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 3.641 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  5.643 ms/op
                 existUser·p0.9999: 13.402 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.413 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  6.546 ms/op
                 existUser·p0.9999: 12.260 ms/op
                 existUser·p1.00:   12.485 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  8.919 ms/op
                 existUser·p0.9999: 11.650 ms/op
                 existUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391479
  mean =      2.451 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 198272 
    [ 2.500,  3.750) = 190272 
    [ 3.750,  5.000) = 2171 
    [ 5.000,  6.250) = 272 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =      8.791 ms/op
     p(99.9900) =     13.088 ms/op
     p(99.9990) =     13.899 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.809 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  7.358 ms/op
                 getUser·p0.9999: 14.810 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   2: 2.496 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  9.746 ms/op
                 getUser·p0.9999: 12.648 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.420 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.641 ms/op
                 getUser·p0.999:  5.713 ms/op
                 getUser·p0.9999: 10.715 ms/op
                 getUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387851
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 196971 
    [ 2.500,  3.750) = 186527 
    [ 3.750,  5.000) = 3326 
    [ 5.000,  6.250) = 536 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.815 ms/op
     p(99.9000) =      7.337 ms/op
     p(99.9900) =     13.389 ms/op
     p(99.9990) =     15.271 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 4.723 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
Iteration   1: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.716 ms/op
                 listUser·p0.9999: 9.703 ms/op
                 listUser·p1.00:   10.502 ms/op

Iteration   2: 2.949 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.578 ms/op
                 listUser·p0.9999: 10.928 ms/op
                 listUser·p1.00:   11.846 ms/op

Iteration   3: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 11.387 ms/op
                 listUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324030
  mean =      2.960 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 101818 
    [ 2.500,  3.750) = 186660 
    [ 3.750,  5.000) = 28980 
    [ 5.000,  6.250) = 5315 
    [ 6.250,  7.500) = 472 
    [ 7.500,  8.750) = 244 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     10.895 ms/op
     p(99.9990) =     11.993 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.598 ± 0.711  ops/ms
ClientPb.existUser                       thrpt       3  13.242 ± 0.410  ops/ms
ClientPb.getUser                         thrpt       3  12.723 ± 1.510  ops/ms
ClientPb.listUser                        thrpt       3  10.631 ± 0.613  ops/ms
ClientPb.createUser                       avgt       3   2.565 ± 0.387   ms/op
ClientPb.existUser                        avgt       3   2.434 ± 0.131   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.374   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.136   ms/op
ClientPb.createUser                     sample  382417   2.508 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.723           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.897           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.615           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.057           ms/op
ClientPb.existUser                      sample  391479   2.451 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.766           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.791           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.088           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.992           ms/op
ClientPb.getUser                        sample  387851   2.473 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.420           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.815           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.337           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.389           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.696           ms/op
ClientPb.listUser                       sample  324030   2.960 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.962           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.895           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.075           ms/op
