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
# Warmup Iteration   1: 4.808 ops/ms
# Warmup Iteration   2: 11.698 ops/ms
# Warmup Iteration   3: 12.185 ops/ms
Iteration   1: 12.374 ops/ms
Iteration   2: 12.514 ops/ms
Iteration   3: 12.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.475 ±(99.9%) 1.611 ops/ms [Average]
  (min, avg, max) = (12.374, 12.475, 12.537), stdev = 0.088
  CI (99.9%): [10.864, 14.086] (assumes normal distribution)


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
# Warmup Iteration   1: 8.646 ops/ms
# Warmup Iteration   2: 12.993 ops/ms
# Warmup Iteration   3: 12.889 ops/ms
Iteration   1: 13.135 ops/ms
Iteration   2: 13.176 ops/ms
Iteration   3: 13.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.114 ±(99.9%) 1.352 ops/ms [Average]
  (min, avg, max) = (13.032, 13.114, 13.176), stdev = 0.074
  CI (99.9%): [11.762, 14.466] (assumes normal distribution)


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
# Warmup Iteration   1: 7.651 ops/ms
# Warmup Iteration   2: 12.589 ops/ms
# Warmup Iteration   3: 12.690 ops/ms
Iteration   1: 12.700 ops/ms
Iteration   2: 12.804 ops/ms
Iteration   3: 12.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.690 ±(99.9%) 2.182 ops/ms [Average]
  (min, avg, max) = (12.566, 12.690, 12.804), stdev = 0.120
  CI (99.9%): [10.508, 14.872] (assumes normal distribution)


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
# Warmup Iteration   1: 6.601 ops/ms
# Warmup Iteration   2: 10.208 ops/ms
# Warmup Iteration   3: 10.424 ops/ms
Iteration   1: 10.383 ops/ms
Iteration   2: 10.503 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.473 ±(99.9%) 1.449 ops/ms [Average]
  (min, avg, max) = (10.383, 10.473, 10.533), stdev = 0.079
  CI (99.9%): [9.025, 11.922] (assumes normal distribution)


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.003 ms/op
Iteration   3: 2.538 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.539 ±(99.9%) 0.044 ms/op [Average]
  (min, avg, max) = (2.536, 2.539, 2.541), stdev = 0.002
  CI (99.9%): [2.495, 2.582] (assumes normal distribution)


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
# Warmup Iteration   1: 3.690 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.004 ms/op
Iteration   1: 2.452 ±(99.9%) 0.003 ms/op
Iteration   2: 2.448 ±(99.9%) 0.003 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.455 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.448, 2.455, 2.464), stdev = 0.009
  CI (99.9%): [2.295, 2.614] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.003 ms/op
Iteration   1: 2.477 ±(99.9%) 0.003 ms/op
Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.474 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.457, 2.474, 2.486), stdev = 0.015
  CI (99.9%): [2.204, 2.743] (assumes normal distribution)


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
# Warmup Iteration   1: 4.735 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
Iteration   1: 3.048 ±(99.9%) 0.006 ms/op
Iteration   2: 3.056 ±(99.9%) 0.005 ms/op
Iteration   3: 3.076 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.060 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (3.048, 3.060, 3.076), stdev = 0.015
  CI (99.9%): [2.793, 3.327] (assumes normal distribution)


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.708 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  11.432 ms/op
                 createUser·p0.9999: 13.383 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  9.649 ms/op
                 createUser·p0.9999: 13.477 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  8.609 ms/op
                 createUser·p0.9999: 10.704 ms/op
                 createUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378813
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 183635 
    [ 2.500,  3.750) = 191796 
    [ 3.750,  5.000) = 2659 
    [ 5.000,  6.250) = 249 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.724 ms/op
                 existUser·p0.9999: 14.466 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  6.626 ms/op
                 existUser·p0.9999: 13.500 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  6.070 ms/op
                 existUser·p0.9999: 11.387 ms/op
                 existUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390755
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 193546 
    [ 2.500,  3.750) = 193988 
    [ 3.750,  5.000) = 2515 
    [ 5.000,  6.250) = 265 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 135 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =      6.146 ms/op
     p(99.9900) =     13.614 ms/op
     p(99.9990) =     14.720 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.835 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  11.430 ms/op
                 getUser·p0.9999: 13.402 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  9.809 ms/op
                 getUser·p0.9999: 15.614 ms/op
                 getUser·p1.00:   16.368 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  8.448 ms/op
                 getUser·p0.9999: 11.665 ms/op
                 getUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381115
  mean =      2.517 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 187670 
    [ 2.500,  3.750) = 188806 
    [ 3.750,  5.000) = 3555 
    [ 5.000,  6.250) = 580 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.534 ms/op
     p(99.9900) =     14.385 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.009 ms/op
Iteration   1: 3.092 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 10.841 ms/op
                 listUser·p1.00:   12.812 ms/op

Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.509 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.469 ms/op
                 listUser·p0.9999: 13.542 ms/op
                 listUser·p1.00:   14.156 ms/op

Iteration   3: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.978 ms/op
                 listUser·p0.9999: 11.160 ms/op
                 listUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311763
  mean =      3.076 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 79437 
    [ 2.500,  3.750) = 188808 
    [ 3.750,  5.000) = 35755 
    [ 5.000,  6.250) = 6271 
    [ 6.250,  7.500) = 628 
    [ 7.500,  8.750) = 311 
    [ 8.750, 10.000) = 208 
    [10.000, 11.250) = 172 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     11.752 ms/op
     p(99.9990) =     14.081 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.475 ± 1.611  ops/ms
ClientPb.existUser                       thrpt       3  13.114 ± 1.352  ops/ms
ClientPb.getUser                         thrpt       3  12.690 ± 2.182  ops/ms
ClientPb.listUser                        thrpt       3  10.473 ± 1.449  ops/ms
ClientPb.createUser                       avgt       3   2.539 ± 0.044   ms/op
ClientPb.existUser                        avgt       3   2.455 ± 0.160   ms/op
ClientPb.getUser                          avgt       3   2.474 ± 0.270   ms/op
ClientPb.listUser                         avgt       3   3.060 ± 0.267   ms/op
ClientPb.createUser                     sample  378813   2.532 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.840           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.634           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.271           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.203           ms/op
ClientPb.existUser                      sample  390755   2.455 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.860           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.146           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.614           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.860           ms/op
ClientPb.getUser                        sample  381115   2.517 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.659           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.534           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.385           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.368           ms/op
ClientPb.listUser                       sample  311763   3.076 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.904           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.752           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.156           ms/op
