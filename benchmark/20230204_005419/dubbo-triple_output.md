# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.099 ops/ms
# Warmup Iteration   2: 4.909 ops/ms
# Warmup Iteration   3: 8.626 ops/ms
Iteration   1: 8.992 ops/ms
Iteration   2: 9.716 ops/ms
Iteration   3: 9.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.405 ±(99.9%) 6.807 ops/ms [Average]
  (min, avg, max) = (8.992, 9.405, 9.716), stdev = 0.373
  CI (99.9%): [2.598, 16.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.967 ops/ms
# Warmup Iteration   2: 8.399 ops/ms
# Warmup Iteration   3: 9.673 ops/ms
Iteration   1: 9.700 ops/ms
Iteration   2: 9.801 ops/ms
Iteration   3: 9.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.680 ±(99.9%) 2.433 ops/ms [Average]
  (min, avg, max) = (9.537, 9.680, 9.801), stdev = 0.133
  CI (99.9%): [7.247, 12.112] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.942 ops/ms
# Warmup Iteration   2: 8.650 ops/ms
# Warmup Iteration   3: 8.931 ops/ms
Iteration   1: 9.264 ops/ms
Iteration   2: 9.617 ops/ms
Iteration   3: 9.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.378 ±(99.9%) 3.769 ops/ms [Average]
  (min, avg, max) = (9.254, 9.378, 9.617), stdev = 0.207
  CI (99.9%): [5.609, 13.147] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.386 ops/ms
# Warmup Iteration   2: 7.181 ops/ms
# Warmup Iteration   3: 7.732 ops/ms
Iteration   1: 7.941 ops/ms
Iteration   2: 8.012 ops/ms
Iteration   3: 8.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.081 ±(99.9%) 3.357 ops/ms [Average]
  (min, avg, max) = (7.941, 8.081, 8.289), stdev = 0.184
  CI (99.9%): [4.724, 11.437] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.561 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.004 ms/op
Iteration   1: 3.363 ±(99.9%) 0.013 ms/op
Iteration   2: 3.389 ±(99.9%) 0.010 ms/op
Iteration   3: 3.375 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.376 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (3.363, 3.376, 3.389), stdev = 0.013
  CI (99.9%): [3.131, 3.620] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.166 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.004 ms/op
Iteration   1: 3.275 ±(99.9%) 0.004 ms/op
Iteration   2: 3.238 ±(99.9%) 0.006 ms/op
Iteration   3: 3.176 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.230 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (3.176, 3.230, 3.275), stdev = 0.050
  CI (99.9%): [2.320, 4.139] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.578 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.005 ms/op
Iteration   1: 3.408 ±(99.9%) 0.005 ms/op
Iteration   2: 3.266 ±(99.9%) 0.007 ms/op
Iteration   3: 3.417 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.363 ±(99.9%) 1.548 ms/op [Average]
  (min, avg, max) = (3.266, 3.363, 3.417), stdev = 0.085
  CI (99.9%): [1.815, 4.912] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.642 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.008 ms/op
Iteration   1: 3.969 ±(99.9%) 0.011 ms/op
Iteration   2: 3.896 ±(99.9%) 0.010 ms/op
Iteration   3: 3.873 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.913 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (3.873, 3.913, 3.969), stdev = 0.050
  CI (99.9%): [2.997, 4.829] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.660 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.011 ms/op
Iteration   1: 3.459 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.538 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  18.007 ms/op
                 createUser·p0.9999: 24.002 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   2: 3.532 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.657 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  20.234 ms/op
                 createUser·p0.9999: 23.495 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   3: 3.521 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.371 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  17.367 ms/op
                 createUser·p0.9999: 35.193 ms/op
                 createUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274033
  mean =      3.504 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6992 
    [ 2.500,  5.000) = 260646 
    [ 5.000,  7.500) = 5255 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.371 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     17.856 ms/op
     p(99.9900) =     33.489 ms/op
     p(99.9990) =     36.492 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.364 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.009 ms/op
Iteration   1: 3.207 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  15.166 ms/op
                 existUser·p0.9999: 28.017 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   2: 3.284 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  14.461 ms/op
                 existUser·p0.9999: 23.626 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   3: 3.260 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.342 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  12.714 ms/op
                 existUser·p0.9999: 27.210 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295333
  mean =      3.250 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9890 
    [ 2.500,  5.000) = 281194 
    [ 5.000,  7.500) = 3307 
    [ 7.500, 10.000) = 478 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.342 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     13.773 ms/op
     p(99.9900) =     27.034 ms/op
     p(99.9990) =     28.151 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.177 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.010 ms/op
Iteration   1: 3.406 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.602 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  20.120 ms/op
                 getUser·p0.9999: 22.001 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  20.972 ms/op
                 getUser·p0.9999: 24.718 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   3: 3.482 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  10.849 ms/op
                 getUser·p0.9999: 23.554 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279113
  mean =      3.439 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5651 
    [ 2.500,  5.000) = 263898 
    [ 5.000,  7.500) = 8025 
    [ 7.500, 10.000) = 1020 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     23.634 ms/op
     p(99.9990) =     25.036 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.679 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.475 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.014 ms/op
Iteration   1: 3.976 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.958 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  19.333 ms/op
                 listUser·p0.9999: 24.075 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   2: 3.932 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 16.346 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 4.010 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  15.507 ms/op
                 listUser·p0.9999: 19.105 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241464
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 233926 
    [ 5.000,  7.500) = 5366 
    [ 7.500, 10.000) = 1376 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.647 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     15.041 ms/op
     p(99.9900) =     22.427 ms/op
     p(99.9990) =     24.366 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.405 ± 6.807  ops/ms
ClientPb.existUser                       thrpt       3   9.680 ± 2.433  ops/ms
ClientPb.getUser                         thrpt       3   9.378 ± 3.769  ops/ms
ClientPb.listUser                        thrpt       3   8.081 ± 3.357  ops/ms
ClientPb.createUser                       avgt       3   3.376 ± 0.244   ms/op
ClientPb.existUser                        avgt       3   3.230 ± 0.909   ms/op
ClientPb.getUser                          avgt       3   3.363 ± 1.548   ms/op
ClientPb.listUser                         avgt       3   3.913 ± 0.916   ms/op
ClientPb.createUser                     sample  274033   3.504 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.371           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.070           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.856           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.489           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.962           ms/op
ClientPb.existUser                      sample  295333   3.250 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.342           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.773           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.034           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.410           ms/op
ClientPb.getUser                        sample  279113   3.439 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.198           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.570           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.025           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.634           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.461           ms/op
ClientPb.listUser                       sample  241464   3.972 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.647           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.041           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.427           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.805           ms/op
