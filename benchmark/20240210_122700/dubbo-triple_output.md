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
# Warmup Iteration   1: 4.921 ops/ms
# Warmup Iteration   2: 12.377 ops/ms
# Warmup Iteration   3: 12.691 ops/ms
Iteration   1: 12.874 ops/ms
Iteration   2: 12.912 ops/ms
Iteration   3: 12.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.909 ±(99.9%) 0.619 ops/ms [Average]
  (min, avg, max) = (12.874, 12.909, 12.942), stdev = 0.034
  CI (99.9%): [12.290, 13.528] (assumes normal distribution)


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
# Warmup Iteration   1: 8.790 ops/ms
# Warmup Iteration   2: 13.387 ops/ms
# Warmup Iteration   3: 13.386 ops/ms
Iteration   1: 13.422 ops/ms
Iteration   2: 13.436 ops/ms
Iteration   3: 13.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.343 ±(99.9%) 2.733 ops/ms [Average]
  (min, avg, max) = (13.170, 13.343, 13.436), stdev = 0.150
  CI (99.9%): [10.610, 16.076] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.969 ops/ms
# Warmup Iteration   2: 12.346 ops/ms
# Warmup Iteration   3: 12.528 ops/ms
Iteration   1: 12.794 ops/ms
Iteration   2: 12.617 ops/ms
Iteration   3: 12.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.683 ±(99.9%) 1.762 ops/ms [Average]
  (min, avg, max) = (12.617, 12.683, 12.794), stdev = 0.097
  CI (99.9%): [10.921, 14.445] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.737 ops/ms
# Warmup Iteration   2: 10.715 ops/ms
# Warmup Iteration   3: 10.756 ops/ms
Iteration   1: 10.766 ops/ms
Iteration   2: 10.829 ops/ms
Iteration   3: 10.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.781 ±(99.9%) 0.788 ops/ms [Average]
  (min, avg, max) = (10.747, 10.781, 10.829), stdev = 0.043
  CI (99.9%): [9.992, 11.569] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.003 ms/op
Iteration   1: 2.495 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.512 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.477, 2.495, 2.512), stdev = 0.018
  CI (99.9%): [2.171, 2.818] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.719 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.003 ms/op
Iteration   1: 2.406 ±(99.9%) 0.004 ms/op
Iteration   2: 2.421 ±(99.9%) 0.003 ms/op
Iteration   3: 2.446 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.424 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (2.406, 2.424, 2.446), stdev = 0.020
  CI (99.9%): [2.060, 2.788] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.782 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.004 ms/op
Iteration   1: 2.457 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
Iteration   3: 2.458 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.464 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (2.457, 2.464, 2.477), stdev = 0.011
  CI (99.9%): [2.259, 2.669] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.459 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.938 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.007 ms/op
Iteration   1: 2.964 ±(99.9%) 0.005 ms/op
Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
Iteration   3: 2.948 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.957 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (2.948, 2.957, 2.964), stdev = 0.009
  CI (99.9%): [2.801, 3.113] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.186 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  8.415 ms/op
                 createUser·p0.9999: 15.178 ms/op
                 createUser·p1.00:   16.220 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  9.859 ms/op
                 createUser·p0.9999: 12.260 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  7.779 ms/op
                 createUser·p0.9999: 9.997 ms/op
                 createUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384223
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 185866 
    [ 2.500,  3.750) = 195093 
    [ 3.750,  5.000) = 2465 
    [ 5.000,  6.250) = 297 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      8.350 ms/op
     p(99.9900) =     12.789 ms/op
     p(99.9990) =     15.813 ms/op
     p(99.9999) =     16.220 ms/op
    p(100.0000) =     16.220 ms/op


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
# Warmup Iteration   1: 3.637 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.467 ms/op
                 existUser·p0.999:  5.748 ms/op
                 existUser·p0.9999: 14.695 ms/op
                 existUser·p1.00:   16.318 ms/op

Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.293 ms/op
                 existUser·p0.999:  5.107 ms/op
                 existUser·p0.9999: 12.577 ms/op
                 existUser·p1.00:   12.763 ms/op

Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  7.125 ms/op
                 existUser·p0.9999: 13.320 ms/op
                 existUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393778
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 194109 
    [ 2.500,  3.750) = 196991 
    [ 3.750,  5.000) = 2063 
    [ 5.000,  6.250) = 225 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.445 ms/op
     p(99.9000) =      5.705 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     15.272 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 3.747 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.006 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.441 ms/op
                 getUser·p0.999:  5.470 ms/op
                 getUser·p0.9999: 14.105 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.929 ms/op
                 getUser·p0.95:   3.006 ms/op
                 getUser·p0.99:   3.297 ms/op
                 getUser·p0.999:  5.733 ms/op
                 getUser·p0.9999: 11.891 ms/op
                 getUser·p1.00:   12.501 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  5.977 ms/op
                 getUser·p0.9999: 10.453 ms/op
                 getUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 393980
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 199147 
    [ 2.500,  3.750) = 191758 
    [ 3.750,  5.000) = 2476 
    [ 5.000,  6.250) = 170 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      5.751 ms/op
     p(99.9900) =     13.215 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 4.502 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.008 ms/op
Iteration   1: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   2.939 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.172 ms/op
                 listUser·p0.9999: 11.458 ms/op
                 listUser·p1.00:   12.288 ms/op

Iteration   2: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.620 ms/op
                 listUser·p0.9999: 13.681 ms/op
                 listUser·p1.00:   14.287 ms/op

Iteration   3: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  8.440 ms/op
                 listUser·p0.9999: 11.895 ms/op
                 listUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321600
  mean =      2.982 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 102129 
    [ 2.500,  3.750) = 180981 
    [ 3.750,  5.000) = 31373 
    [ 5.000,  6.250) = 5715 
    [ 6.250,  7.500) = 632 
    [ 7.500,  8.750) = 258 
    [ 8.750, 10.000) = 145 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     12.515 ms/op
     p(99.9990) =     14.214 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.909 ± 0.619  ops/ms
ClientPb.existUser                       thrpt       3  13.343 ± 2.733  ops/ms
ClientPb.getUser                         thrpt       3  12.683 ± 1.762  ops/ms
ClientPb.listUser                        thrpt       3  10.781 ± 0.788  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.323   ms/op
ClientPb.existUser                        avgt       3   2.424 ± 0.364   ms/op
ClientPb.getUser                          avgt       3   2.464 ± 0.205   ms/op
ClientPb.listUser                         avgt       3   2.957 ± 0.156   ms/op
ClientPb.createUser                     sample  384223   2.496 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.801           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.350           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.789           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.220           ms/op
ClientPb.existUser                      sample  393778   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.067           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.705           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.402           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.318           ms/op
ClientPb.getUser                        sample  393980   2.435 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.858           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.466           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.751           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.215           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.106           ms/op
ClientPb.listUser                       sample  321600   2.982 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.842           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.929           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.515           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.287           ms/op
