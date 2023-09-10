# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.967 ops/ms
# Warmup Iteration   2: 4.674 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 8.787 ops/ms
Iteration   2: 9.114 ops/ms
Iteration   3: 9.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.004 ±(99.9%) 3.435 ops/ms [Average]
  (min, avg, max) = (8.787, 9.004, 9.114), stdev = 0.188
  CI (99.9%): [5.569, 12.439] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.591 ops/ms
# Warmup Iteration   2: 8.248 ops/ms
# Warmup Iteration   3: 8.960 ops/ms
Iteration   1: 9.240 ops/ms
Iteration   2: 9.281 ops/ms
Iteration   3: 9.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.291 ±(99.9%) 1.021 ops/ms [Average]
  (min, avg, max) = (9.240, 9.291, 9.351), stdev = 0.056
  CI (99.9%): [8.270, 10.312] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.431 ops/ms
# Warmup Iteration   2: 7.885 ops/ms
# Warmup Iteration   3: 8.903 ops/ms
Iteration   1: 9.095 ops/ms
Iteration   2: 9.120 ops/ms
Iteration   3: 8.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.065 ±(99.9%) 1.374 ops/ms [Average]
  (min, avg, max) = (8.979, 9.065, 9.120), stdev = 0.075
  CI (99.9%): [7.691, 10.439] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.319 ops/ms
# Warmup Iteration   2: 6.637 ops/ms
# Warmup Iteration   3: 7.660 ops/ms
Iteration   1: 7.603 ops/ms
Iteration   2: 8.044 ops/ms
Iteration   3: 7.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.856 ±(99.9%) 4.151 ops/ms [Average]
  (min, avg, max) = (7.603, 7.856, 8.044), stdev = 0.228
  CI (99.9%): [3.705, 12.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.922 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.006 ms/op
Iteration   1: 3.508 ±(99.9%) 0.005 ms/op
Iteration   2: 3.494 ±(99.9%) 0.007 ms/op
Iteration   3: 3.431 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.478 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (3.431, 3.478, 3.508), stdev = 0.041
  CI (99.9%): [2.733, 4.223] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.064 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.671 ±(99.9%) 0.006 ms/op
Iteration   1: 3.400 ±(99.9%) 0.005 ms/op
Iteration   2: 3.480 ±(99.9%) 0.004 ms/op
Iteration   3: 3.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.454 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (3.400, 3.454, 3.483), stdev = 0.047
  CI (99.9%): [2.598, 4.310] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.910 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.010 ms/op
Iteration   1: 3.584 ±(99.9%) 0.005 ms/op
Iteration   2: 3.593 ±(99.9%) 0.008 ms/op
Iteration   3: 3.565 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.581 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (3.565, 3.581, 3.593), stdev = 0.014
  CI (99.9%): [3.321, 3.840] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.842 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.639 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.332 ±(99.9%) 0.006 ms/op
Iteration   1: 4.161 ±(99.9%) 0.007 ms/op
Iteration   2: 3.985 ±(99.9%) 0.011 ms/op
Iteration   3: 4.026 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.057 ±(99.9%) 1.683 ms/op [Average]
  (min, avg, max) = (3.985, 4.057, 4.161), stdev = 0.092
  CI (99.9%): [2.375, 5.740] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.741 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.012 ms/op
Iteration   1: 3.610 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.595 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  22.526 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   2: 3.511 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.849 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  24.341 ms/op
                 createUser·p0.9999: 27.616 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   3: 3.543 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  22.174 ms/op
                 createUser·p0.9999: 30.474 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269952
  mean =      3.554 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5660 
    [ 2.500,  5.000) = 255917 
    [ 5.000,  7.500) = 6839 
    [ 7.500, 10.000) = 999 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     22.479 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     30.648 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.164 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.011 ms/op
Iteration   1: 3.524 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.630 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  22.225 ms/op
                 existUser·p0.9999: 24.442 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   2: 3.420 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.788 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  13.295 ms/op
                 existUser·p0.9999: 26.191 ms/op
                 existUser·p1.00:   27.329 ms/op

Iteration   3: 3.428 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  26.365 ms/op
                 existUser·p0.9999: 36.700 ms/op
                 existUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277653
  mean =      3.457 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13683 
    [ 2.500,  5.000) = 256220 
    [ 5.000,  7.500) = 6215 
    [ 7.500, 10.000) = 928 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     13.512 ms/op
     p(99.9900) =     35.062 ms/op
     p(99.9990) =     36.810 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.077 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.012 ms/op
Iteration   1: 3.535 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   7.602 ms/op
                 getUser·p0.999:  12.919 ms/op
                 getUser·p0.9999: 25.018 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   2: 3.458 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.424 ms/op
                 getUser·p0.999:  24.183 ms/op
                 getUser·p0.9999: 38.716 ms/op
                 getUser·p1.00:   40.305 ms/op

Iteration   3: 3.538 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  19.930 ms/op
                 getUser·p0.9999: 31.359 ms/op
                 getUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273272
  mean =      3.510 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 262406 
    [ 5.000, 10.000) = 9945 
    [10.000, 15.000) = 662 
    [15.000, 20.000) = 11 
    [20.000, 25.000) = 87 
    [25.000, 30.000) = 106 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     36.941 ms/op
     p(99.9990) =     40.060 ms/op
     p(99.9999) =     40.305 ms/op
    p(100.0000) =     40.305 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.989 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.701 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.334 ±(99.9%) 0.015 ms/op
Iteration   1: 4.277 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.827 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  22.790 ms/op
                 listUser·p0.9999: 32.050 ms/op
                 listUser·p1.00:   32.932 ms/op

Iteration   2: 4.198 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   8.969 ms/op
                 listUser·p0.999:  17.362 ms/op
                 listUser·p0.9999: 23.689 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   3: 4.143 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 20.424 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228235
  mean =      4.205 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 215936 
    [ 5.000,  7.500) = 8836 
    [ 7.500, 10.000) = 2091 
    [10.000, 12.500) = 727 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.827 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     18.090 ms/op
     p(99.9900) =     30.694 ms/op
     p(99.9990) =     32.871 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.004 ± 3.435  ops/ms
ClientPb.existUser                       thrpt       3   9.291 ± 1.021  ops/ms
ClientPb.getUser                         thrpt       3   9.065 ± 1.374  ops/ms
ClientPb.listUser                        thrpt       3   7.856 ± 4.151  ops/ms
ClientPb.createUser                       avgt       3   3.478 ± 0.745   ms/op
ClientPb.existUser                        avgt       3   3.454 ± 0.856   ms/op
ClientPb.getUser                          avgt       3   3.581 ± 0.260   ms/op
ClientPb.listUser                         avgt       3   4.057 ± 1.683   ms/op
ClientPb.createUser                     sample  269952   3.554 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.102           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.432           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.398           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.479           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.705           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.835           ms/op
ClientPb.existUser                      sample  277653   3.457 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.579           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.275           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.512           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.062           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.339           ms/op
ClientPb.getUser                        sample  273272   3.510 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.352           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.258           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.993           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.941           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.305           ms/op
ClientPb.listUser                       sample  228235   4.205 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.827           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.079           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.090           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.694           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.932           ms/op
