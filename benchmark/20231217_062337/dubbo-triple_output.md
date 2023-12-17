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
# Warmup Iteration   1: 4.496 ops/ms
# Warmup Iteration   2: 11.870 ops/ms
# Warmup Iteration   3: 12.304 ops/ms
Iteration   1: 12.491 ops/ms
Iteration   2: 12.565 ops/ms
Iteration   3: 12.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.494 ±(99.9%) 1.269 ops/ms [Average]
  (min, avg, max) = (12.426, 12.494, 12.565), stdev = 0.070
  CI (99.9%): [11.225, 13.762] (assumes normal distribution)


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
# Warmup Iteration   1: 8.055 ops/ms
# Warmup Iteration   2: 12.942 ops/ms
# Warmup Iteration   3: 12.926 ops/ms
Iteration   1: 12.889 ops/ms
Iteration   2: 13.007 ops/ms
Iteration   3: 13.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.971 ±(99.9%) 1.289 ops/ms [Average]
  (min, avg, max) = (12.889, 12.971, 13.016), stdev = 0.071
  CI (99.9%): [11.682, 14.260] (assumes normal distribution)


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
# Warmup Iteration   1: 7.019 ops/ms
# Warmup Iteration   2: 12.114 ops/ms
# Warmup Iteration   3: 12.119 ops/ms
Iteration   1: 12.322 ops/ms
Iteration   2: 12.412 ops/ms
Iteration   3: 12.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.383 ±(99.9%) 0.978 ops/ms [Average]
  (min, avg, max) = (12.322, 12.383, 12.417), stdev = 0.054
  CI (99.9%): [11.405, 13.362] (assumes normal distribution)


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
# Warmup Iteration   1: 6.789 ops/ms
# Warmup Iteration   2: 10.350 ops/ms
# Warmup Iteration   3: 10.429 ops/ms
Iteration   1: 10.407 ops/ms
Iteration   2: 10.465 ops/ms
Iteration   3: 10.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.460 ±(99.9%) 0.925 ops/ms [Average]
  (min, avg, max) = (10.407, 10.460, 10.508), stdev = 0.051
  CI (99.9%): [9.535, 11.385] (assumes normal distribution)


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.585 ±(99.9%) 0.004 ms/op
Iteration   1: 2.592 ±(99.9%) 0.005 ms/op
Iteration   2: 2.583 ±(99.9%) 0.004 ms/op
Iteration   3: 2.589 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.588 ±(99.9%) 0.078 ms/op [Average]
  (min, avg, max) = (2.583, 2.588, 2.592), stdev = 0.004
  CI (99.9%): [2.510, 2.666] (assumes normal distribution)


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.513 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.497, 2.513, 2.527), stdev = 0.015
  CI (99.9%): [2.241, 2.785] (assumes normal distribution)


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.700 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.603 ±(99.9%) 0.005 ms/op
Iteration   1: 2.570 ±(99.9%) 0.004 ms/op
Iteration   2: 2.578 ±(99.9%) 0.004 ms/op
Iteration   3: 2.570 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.573 ±(99.9%) 0.084 ms/op [Average]
  (min, avg, max) = (2.570, 2.573, 2.578), stdev = 0.005
  CI (99.9%): [2.488, 2.657] (assumes normal distribution)


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
# Warmup Iteration   1: 4.705 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.093 ±(99.9%) 0.004 ms/op
Iteration   2: 3.075 ±(99.9%) 0.005 ms/op
Iteration   3: 3.079 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.082 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (3.075, 3.082, 3.093), stdev = 0.009
  CI (99.9%): [2.915, 3.250] (assumes normal distribution)


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.737 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.626 ±(99.9%) 0.006 ms/op
Iteration   1: 2.677 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.441 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  12.070 ms/op
                 createUser·p0.9999: 14.259 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 2.623 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.195 ms/op
                 createUser·p0.95:   3.322 ms/op
                 createUser·p0.99:   4.080 ms/op
                 createUser·p0.999:  9.897 ms/op
                 createUser·p0.9999: 13.992 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   3: 2.612 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  8.835 ms/op
                 createUser·p0.9999: 11.665 ms/op
                 createUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 363706
  mean =      2.637 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 168876 
    [ 2.500,  3.750) = 188845 
    [ 3.750,  5.000) = 4934 
    [ 5.000,  6.250) = 536 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.679 ms/op
     p(90.0000) =      3.215 ms/op
     p(95.0000) =      3.355 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      9.196 ms/op
     p(99.9900) =     13.855 ms/op
     p(99.9990) =     14.516 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  12.227 ms/op
                 existUser·p0.9999: 14.438 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  6.054 ms/op
                 existUser·p0.9999: 12.865 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  9.652 ms/op
                 existUser·p0.9999: 11.944 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383570
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 189169 
    [ 2.500,  3.750) = 190990 
    [ 3.750,  5.000) = 2556 
    [ 5.000,  6.250) = 431 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      6.332 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.671 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.575 ±(99.9%) 0.006 ms/op
Iteration   1: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  11.240 ms/op
                 getUser·p0.9999: 17.053 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.647 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   3.973 ms/op
                 getUser·p0.999:  9.539 ms/op
                 getUser·p0.9999: 12.911 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   3: 2.566 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.210 ms/op
                 getUser·p0.999:  6.098 ms/op
                 getUser·p0.9999: 10.748 ms/op
                 getUser·p1.00:   11.010 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375351
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 180376 
    [ 2.500,  3.750) = 189508 
    [ 3.750,  5.000) = 4445 
    [ 5.000,  6.250) = 558 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      6.502 ms/op
     p(99.9900) =     14.770 ms/op
     p(99.9990) =     17.891 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.739 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
Iteration   1: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.625 ms/op
                 listUser·p0.999:  8.744 ms/op
                 listUser·p0.9999: 10.510 ms/op
                 listUser·p1.00:   11.452 ms/op

Iteration   2: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.064 ms/op
                 listUser·p0.9999: 10.550 ms/op
                 listUser·p1.00:   11.338 ms/op

Iteration   3: 3.064 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 10.783 ms/op
                 listUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314913
  mean =      3.046 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 85863 
    [ 2.500,  3.750) = 187710 
    [ 3.750,  5.000) = 33701 
    [ 5.000,  6.250) = 6098 
    [ 6.250,  7.500) = 766 
    [ 7.500,  8.750) = 240 
    [ 8.750, 10.000) = 309 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.668 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     10.625 ms/op
     p(99.9990) =     12.084 ms/op
     p(99.9999) =     12.206 ms/op
    p(100.0000) =     12.206 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.494 ± 1.269  ops/ms
ClientPb.existUser                       thrpt       3  12.971 ± 1.289  ops/ms
ClientPb.getUser                         thrpt       3  12.383 ± 0.978  ops/ms
ClientPb.listUser                        thrpt       3  10.460 ± 0.925  ops/ms
ClientPb.createUser                       avgt       3   2.588 ± 0.078   ms/op
ClientPb.existUser                        avgt       3   2.513 ± 0.272   ms/op
ClientPb.getUser                          avgt       3   2.573 ± 0.084   ms/op
ClientPb.listUser                         avgt       3   3.082 ± 0.168   ms/op
ClientPb.createUser                     sample  363706   2.637 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.744           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.679           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.196           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.855           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.713           ms/op
ClientPb.existUser                      sample  383570   2.501 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.907           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.332           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.812           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.991           ms/op
ClientPb.getUser                        sample  375351   2.555 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.647           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.502           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.770           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.957           ms/op
ClientPb.listUser                       sample  314913   3.046 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.762           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.668           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.625           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.206           ms/op
