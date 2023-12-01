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
# Warmup Iteration   1: 4.663 ops/ms
# Warmup Iteration   2: 12.092 ops/ms
# Warmup Iteration   3: 12.269 ops/ms
Iteration   1: 12.447 ops/ms
Iteration   2: 12.679 ops/ms
Iteration   3: 12.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.590 ±(99.9%) 2.282 ops/ms [Average]
  (min, avg, max) = (12.447, 12.590, 12.679), stdev = 0.125
  CI (99.9%): [10.309, 14.872] (assumes normal distribution)


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
# Warmup Iteration   1: 8.048 ops/ms
# Warmup Iteration   2: 12.931 ops/ms
# Warmup Iteration   3: 12.944 ops/ms
Iteration   1: 12.851 ops/ms
Iteration   2: 12.839 ops/ms
Iteration   3: 13.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.905 ±(99.9%) 1.914 ops/ms [Average]
  (min, avg, max) = (12.839, 12.905, 13.026), stdev = 0.105
  CI (99.9%): [10.991, 14.820] (assumes normal distribution)


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
# Warmup Iteration   1: 7.838 ops/ms
# Warmup Iteration   2: 12.406 ops/ms
# Warmup Iteration   3: 12.529 ops/ms
Iteration   1: 12.650 ops/ms
Iteration   2: 12.682 ops/ms
Iteration   3: 12.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.643 ±(99.9%) 0.773 ops/ms [Average]
  (min, avg, max) = (12.598, 12.643, 12.682), stdev = 0.042
  CI (99.9%): [11.870, 13.416] (assumes normal distribution)


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
# Warmup Iteration   1: 6.815 ops/ms
# Warmup Iteration   2: 10.495 ops/ms
# Warmup Iteration   3: 10.583 ops/ms
Iteration   1: 10.322 ops/ms
Iteration   2: 10.552 ops/ms
Iteration   3: 10.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.476 ±(99.9%) 2.436 ops/ms [Average]
  (min, avg, max) = (10.322, 10.476, 10.555), stdev = 0.134
  CI (99.9%): [8.040, 12.913] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.539 ±(99.9%) 0.003 ms/op
Iteration   3: 2.486 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.513 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (2.486, 2.513, 2.539), stdev = 0.027
  CI (99.9%): [2.026, 3.001] (assumes normal distribution)


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
# Warmup Iteration   1: 3.557 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.004 ms/op
Iteration   2: 2.453 ±(99.9%) 0.003 ms/op
Iteration   3: 2.442 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.442, 2.451, 2.457), stdev = 0.008
  CI (99.9%): [2.308, 2.594] (assumes normal distribution)


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
# Warmup Iteration   1: 3.690 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.003 ms/op
Iteration   1: 2.464 ±(99.9%) 0.003 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.524 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (2.464, 2.490, 2.524), stdev = 0.031
  CI (99.9%): [1.922, 3.058] (assumes normal distribution)


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
# Warmup Iteration   1: 4.732 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.005 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
Iteration   3: 3.018 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.018 ±(99.9%) 0.047 ms/op [Average]
  (min, avg, max) = (3.015, 3.018, 3.020), stdev = 0.003
  CI (99.9%): [2.971, 3.064] (assumes normal distribution)


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.690 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.531 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  11.358 ms/op
                 createUser·p0.9999: 14.375 ms/op
                 createUser·p1.00:   14.533 ms/op

Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  9.601 ms/op
                 createUser·p0.9999: 12.475 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 11.870 ms/op
                 createUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377624
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 177954 
    [ 2.500,  3.750) = 194059 
    [ 3.750,  5.000) = 4483 
    [ 5.000,  6.250) = 523 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      8.870 ms/op
     p(99.9900) =     13.226 ms/op
     p(99.9990) =     14.454 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.497 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  11.603 ms/op
                 existUser·p0.9999: 14.093 ms/op
                 existUser·p1.00:   15.286 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  6.095 ms/op
                 existUser·p0.9999: 14.290 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  9.306 ms/op
                 existUser·p0.9999: 12.440 ms/op
                 existUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384628
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 189111 
    [ 2.500,  3.750) = 191392 
    [ 3.750,  5.000) = 3006 
    [ 5.000,  6.250) = 569 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      7.526 ms/op
     p(99.9900) =     13.706 ms/op
     p(99.9990) =     15.294 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  11.674 ms/op
                 getUser·p0.9999: 15.270 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  10.047 ms/op
                 getUser·p0.9999: 13.289 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   3: 2.565 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.573 ms/op
                 getUser·p0.9999: 10.996 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375034
  mean =      2.557 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 180962 
    [ 2.500,  3.750) = 186683 
    [ 3.750,  5.000) = 5813 
    [ 5.000,  6.250) = 1035 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     15.548 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.010 ms/op
Iteration   1: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.553 ms/op
                 listUser·p0.9999: 11.826 ms/op
                 listUser·p1.00:   14.221 ms/op

Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.494 ms/op
                 listUser·p0.9999: 10.912 ms/op
                 listUser·p1.00:   11.829 ms/op

Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.832 ms/op
                 listUser·p0.9999: 12.001 ms/op
                 listUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316315
  mean =      3.032 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 90547 
    [ 2.500,  3.750) = 185145 
    [ 3.750,  5.000) = 32829 
    [ 5.000,  6.250) = 6285 
    [ 6.250,  7.500) = 727 
    [ 7.500,  8.750) = 162 
    [ 8.750, 10.000) = 286 
    [10.000, 11.250) = 184 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     11.655 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.590 ± 2.282  ops/ms
ClientPb.existUser                       thrpt       3  12.905 ± 1.914  ops/ms
ClientPb.getUser                         thrpt       3  12.643 ± 0.773  ops/ms
ClientPb.listUser                        thrpt       3  10.476 ± 2.436  ops/ms
ClientPb.createUser                       avgt       3   2.513 ± 0.488   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.143   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.568   ms/op
ClientPb.listUser                         avgt       3   3.018 ± 0.047   ms/op
ClientPb.createUser                     sample  377624   2.540 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.957           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.870           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.226           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.533           ms/op
ClientPb.existUser                      sample  384628   2.493 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.870           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.526           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.706           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.385           ms/op
ClientPb.getUser                        sample  375034   2.557 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.916           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.152           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.910           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.614           ms/op
ClientPb.listUser                       sample  316315   3.032 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.805           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.655           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.221           ms/op
