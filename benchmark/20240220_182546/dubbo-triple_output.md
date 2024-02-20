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
# Warmup Iteration   1: 4.749 ops/ms
# Warmup Iteration   2: 11.917 ops/ms
# Warmup Iteration   3: 12.190 ops/ms
Iteration   1: 12.461 ops/ms
Iteration   2: 12.371 ops/ms
Iteration   3: 12.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.494 ±(99.9%) 2.608 ops/ms [Average]
  (min, avg, max) = (12.371, 12.494, 12.651), stdev = 0.143
  CI (99.9%): [9.886, 15.102] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.248 ops/ms
# Warmup Iteration   2: 13.047 ops/ms
# Warmup Iteration   3: 12.927 ops/ms
Iteration   1: 13.018 ops/ms
Iteration   2: 13.218 ops/ms
Iteration   3: 12.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.071 ±(99.9%) 2.342 ops/ms [Average]
  (min, avg, max) = (12.978, 13.071, 13.218), stdev = 0.128
  CI (99.9%): [10.729, 15.413] (assumes normal distribution)


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
# Warmup Iteration   1: 7.439 ops/ms
# Warmup Iteration   2: 12.391 ops/ms
# Warmup Iteration   3: 12.616 ops/ms
Iteration   1: 12.748 ops/ms
Iteration   2: 12.885 ops/ms
Iteration   3: 12.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.797 ±(99.9%) 1.384 ops/ms [Average]
  (min, avg, max) = (12.748, 12.797, 12.885), stdev = 0.076
  CI (99.9%): [11.413, 14.181] (assumes normal distribution)


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
# Warmup Iteration   1: 6.830 ops/ms
# Warmup Iteration   2: 10.554 ops/ms
# Warmup Iteration   3: 10.786 ops/ms
Iteration   1: 10.752 ops/ms
Iteration   2: 10.733 ops/ms
Iteration   3: 10.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.785 ±(99.9%) 1.362 ops/ms [Average]
  (min, avg, max) = (10.733, 10.785, 10.871), stdev = 0.075
  CI (99.9%): [9.423, 12.147] (assumes normal distribution)


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.538 ±(99.9%) 0.003 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (2.521, 2.530, 2.538), stdev = 0.009
  CI (99.9%): [2.373, 2.686] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.775 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.004 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.393 ±(99.9%) 0.003 ms/op
Iteration   3: 2.412 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.421 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (2.393, 2.421, 2.458), stdev = 0.033
  CI (99.9%): [1.812, 3.030] (assumes normal distribution)


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
# Warmup Iteration   1: 3.747 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.003 ms/op
Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
Iteration   3: 2.493 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.480 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.468, 2.480, 2.493), stdev = 0.012
  CI (99.9%): [2.252, 2.707] (assumes normal distribution)


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
# Warmup Iteration   1: 4.897 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
Iteration   2: 3.004 ±(99.9%) 0.005 ms/op
Iteration   3: 3.046 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.014 ±(99.9%) 0.525 ms/op [Average]
  (min, avg, max) = (2.991, 3.014, 3.046), stdev = 0.029
  CI (99.9%): [2.489, 3.538] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.999 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.592 ms/op
                 createUser·p0.999:  7.402 ms/op
                 createUser·p0.9999: 13.337 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  10.309 ms/op
                 createUser·p0.9999: 12.714 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.847 ms/op
                 createUser·p0.999:  8.204 ms/op
                 createUser·p0.9999: 9.982 ms/op
                 createUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385280
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 189805 
    [ 2.500,  3.750) = 191307 
    [ 3.750,  5.000) = 3137 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 126 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     13.099 ms/op
     p(99.9990) =     13.634 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  6.335 ms/op
                 existUser·p0.9999: 14.633 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  6.377 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  8.602 ms/op
                 existUser·p0.9999: 14.483 ms/op
                 existUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386872
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 191088 
    [ 2.500,  3.750) = 192788 
    [ 3.750,  5.000) = 2334 
    [ 5.000,  6.250) = 177 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      6.668 ms/op
     p(99.9900) =     14.407 ms/op
     p(99.9990) =     15.237 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


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
# Warmup Iteration   1: 3.842 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.718 ms/op
                 getUser·p0.999:  5.970 ms/op
                 getUser·p0.9999: 14.224 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.875 ms/op
                 getUser·p0.9999: 13.497 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  6.126 ms/op
                 getUser·p0.9999: 12.140 ms/op
                 getUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386113
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 192237 
    [ 2.500,  3.750) = 189147 
    [ 3.750,  5.000) = 3683 
    [ 5.000,  6.250) = 618 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      6.160 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     14.638 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.640 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
Iteration   1: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.880 ms/op
                 listUser·p0.9999: 10.281 ms/op
                 listUser·p1.00:   11.125 ms/op

Iteration   2: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.625 ms/op
                 listUser·p0.9999: 10.945 ms/op
                 listUser·p1.00:   13.418 ms/op

Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 11.395 ms/op
                 listUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322525
  mean =      2.973 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 97388 
    [ 2.500,  3.750) = 188968 
    [ 3.750,  5.000) = 29370 
    [ 5.000,  6.250) = 5461 
    [ 6.250,  7.500) = 465 
    [ 7.500,  8.750) = 243 
    [ 8.750, 10.000) = 333 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.203 ms/op
     p(99.9990) =     12.293 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.494 ± 2.608  ops/ms
ClientPb.existUser                       thrpt       3  13.071 ± 2.342  ops/ms
ClientPb.getUser                         thrpt       3  12.797 ± 1.384  ops/ms
ClientPb.listUser                        thrpt       3  10.785 ± 1.362  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.157   ms/op
ClientPb.existUser                        avgt       3   2.421 ± 0.609   ms/op
ClientPb.getUser                          avgt       3   2.480 ± 0.228   ms/op
ClientPb.listUser                         avgt       3   3.014 ± 0.525   ms/op
ClientPb.createUser                     sample  385280   2.490 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.695           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.527           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.946           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.099           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.123           ms/op
ClientPb.existUser                      sample  386872   2.479 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.633           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.668           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.407           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.532           ms/op
ClientPb.getUser                        sample  386113   2.484 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.815           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.160           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.468           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.860           ms/op
ClientPb.listUser                       sample  322525   2.973 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.203           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.418           ms/op
