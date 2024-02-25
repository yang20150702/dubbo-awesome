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
# Warmup Iteration   1: 4.538 ops/ms
# Warmup Iteration   2: 11.802 ops/ms
# Warmup Iteration   3: 12.113 ops/ms
Iteration   1: 12.231 ops/ms
Iteration   2: 12.256 ops/ms
Iteration   3: 12.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.279 ±(99.9%) 1.149 ops/ms [Average]
  (min, avg, max) = (12.231, 12.279, 12.351), stdev = 0.063
  CI (99.9%): [11.130, 13.428] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.137 ops/ms
# Warmup Iteration   2: 12.849 ops/ms
# Warmup Iteration   3: 12.954 ops/ms
Iteration   1: 13.034 ops/ms
Iteration   2: 13.004 ops/ms
Iteration   3: 12.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.983 ±(99.9%) 1.153 ops/ms [Average]
  (min, avg, max) = (12.913, 12.983, 13.034), stdev = 0.063
  CI (99.9%): [11.830, 14.137] (assumes normal distribution)


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
# Warmup Iteration   1: 7.300 ops/ms
# Warmup Iteration   2: 12.470 ops/ms
# Warmup Iteration   3: 12.854 ops/ms
Iteration   1: 12.950 ops/ms
Iteration   2: 12.793 ops/ms
Iteration   3: 12.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.854 ±(99.9%) 1.540 ops/ms [Average]
  (min, avg, max) = (12.793, 12.854, 12.950), stdev = 0.084
  CI (99.9%): [11.314, 14.394] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.404 ops/ms
# Warmup Iteration   2: 10.414 ops/ms
# Warmup Iteration   3: 10.489 ops/ms
Iteration   1: 10.496 ops/ms
Iteration   2: 10.428 ops/ms
Iteration   3: 10.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.488 ±(99.9%) 1.012 ops/ms [Average]
  (min, avg, max) = (10.428, 10.488, 10.539), stdev = 0.055
  CI (99.9%): [9.476, 11.499] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.942 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.003 ms/op
Iteration   1: 2.579 ±(99.9%) 0.004 ms/op
Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
Iteration   3: 2.554 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.562 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.553, 2.562, 2.579), stdev = 0.015
  CI (99.9%): [2.290, 2.834] (assumes normal distribution)


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.003 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.486 ±(99.9%) 0.443 ms/op [Average]
  (min, avg, max) = (2.471, 2.486, 2.514), stdev = 0.024
  CI (99.9%): [2.043, 2.929] (assumes normal distribution)


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.005 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.524 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (2.514, 2.524, 2.542), stdev = 0.016
  CI (99.9%): [2.235, 2.813] (assumes normal distribution)


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
# Warmup Iteration   1: 4.717 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.005 ms/op
Iteration   1: 3.043 ±(99.9%) 0.005 ms/op
Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
Iteration   3: 3.044 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.049 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (3.043, 3.049, 3.058), stdev = 0.009
  CI (99.9%): [2.892, 3.205] (assumes normal distribution)


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
# Warmup Iteration   1: 4.178 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.731 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.538 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  12.089 ms/op
                 createUser·p0.9999: 14.074 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  9.238 ms/op
                 createUser·p0.9999: 13.595 ms/op
                 createUser·p1.00:   14.631 ms/op

Iteration   3: 2.569 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  9.653 ms/op
                 createUser·p0.9999: 11.653 ms/op
                 createUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376577
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 178620 
    [ 2.500,  3.750) = 192169 
    [ 3.750,  5.000) = 4350 
    [ 5.000,  6.250) = 818 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      4.055 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     13.381 ms/op
     p(99.9990) =     14.569 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.404 ms/op
                 existUser·p0.999:  5.574 ms/op
                 existUser·p0.9999: 13.861 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  5.399 ms/op
                 existUser·p0.9999: 13.848 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  8.774 ms/op
                 existUser·p0.9999: 12.724 ms/op
                 existUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387294
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 191602 
    [ 2.500,  3.750) = 192918 
    [ 3.750,  5.000) = 2176 
    [ 5.000,  6.250) = 170 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      6.234 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.637 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  11.690 ms/op
                 getUser·p0.9999: 14.426 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  9.459 ms/op
                 getUser·p0.9999: 14.032 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.903 ms/op
                 getUser·p0.999:  8.748 ms/op
                 getUser·p0.9999: 11.669 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380893
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 186977 
    [ 2.500,  3.750) = 188764 
    [ 3.750,  5.000) = 4034 
    [ 5.000,  6.250) = 679 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      9.146 ms/op
     p(99.9900) =     14.135 ms/op
     p(99.9990) =     14.945 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.815 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.009 ms/op
Iteration   1: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.136 ms/op
                 listUser·p0.9999: 11.076 ms/op
                 listUser·p1.00:   12.730 ms/op

Iteration   2: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 16.376 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.336 ms/op
                 listUser·p0.9999: 12.705 ms/op
                 listUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314804
  mean =      3.047 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 85261 
    [ 2.500,  3.750) = 188650 
    [ 3.750,  5.000) = 33745 
    [ 5.000,  6.250) = 5702 
    [ 6.250,  7.500) = 726 
    [ 7.500,  8.750) = 194 
    [ 8.750, 10.000) = 194 
    [10.000, 11.250) = 160 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.424 ms/op
     p(99.9900) =     15.352 ms/op
     p(99.9990) =     16.578 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.279 ± 1.149  ops/ms
ClientPb.existUser                       thrpt       3  12.983 ± 1.153  ops/ms
ClientPb.getUser                         thrpt       3  12.854 ± 1.540  ops/ms
ClientPb.listUser                        thrpt       3  10.488 ± 1.012  ops/ms
ClientPb.createUser                       avgt       3   2.562 ± 0.272   ms/op
ClientPb.existUser                        avgt       3   2.486 ± 0.443   ms/op
ClientPb.getUser                          avgt       3   2.524 ± 0.289   ms/op
ClientPb.listUser                         avgt       3   3.049 ± 0.157   ms/op
ClientPb.createUser                     sample  376577   2.547 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.646           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.552           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.381           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.631           ms/op
ClientPb.existUser                      sample  387294   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.923           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.234           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.713           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.630           ms/op
ClientPb.getUser                        sample  380893   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.729           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.146           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.135           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.155           ms/op
ClientPb.listUser                       sample  314804   3.047 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.847           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.424           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.352           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.465           ms/op
