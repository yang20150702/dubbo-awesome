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
# Warmup Iteration   1: 4.562 ops/ms
# Warmup Iteration   2: 11.710 ops/ms
# Warmup Iteration   3: 12.042 ops/ms
Iteration   1: 12.416 ops/ms
Iteration   2: 12.505 ops/ms
Iteration   3: 12.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.477 ±(99.9%) 0.967 ops/ms [Average]
  (min, avg, max) = (12.416, 12.477, 12.511), stdev = 0.053
  CI (99.9%): [11.511, 13.444] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.412 ops/ms
# Warmup Iteration   2: 12.927 ops/ms
# Warmup Iteration   3: 13.150 ops/ms
Iteration   1: 12.953 ops/ms
Iteration   2: 12.808 ops/ms
Iteration   3: 12.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.875 ±(99.9%) 1.339 ops/ms [Average]
  (min, avg, max) = (12.808, 12.875, 12.953), stdev = 0.073
  CI (99.9%): [11.537, 14.214] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.725 ops/ms
# Warmup Iteration   2: 12.307 ops/ms
# Warmup Iteration   3: 12.677 ops/ms
Iteration   1: 12.846 ops/ms
Iteration   2: 12.638 ops/ms
Iteration   3: 12.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.778 ±(99.9%) 2.221 ops/ms [Average]
  (min, avg, max) = (12.638, 12.778, 12.851), stdev = 0.122
  CI (99.9%): [10.557, 14.999] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.751 ops/ms
# Warmup Iteration   2: 10.608 ops/ms
# Warmup Iteration   3: 10.612 ops/ms
Iteration   1: 10.713 ops/ms
Iteration   2: 10.743 ops/ms
Iteration   3: 10.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.705 ±(99.9%) 0.779 ops/ms [Average]
  (min, avg, max) = (10.659, 10.705, 10.743), stdev = 0.043
  CI (99.9%): [9.926, 11.484] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.118 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.004 ms/op
Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.546 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (2.536, 2.546, 2.556), stdev = 0.010
  CI (99.9%): [2.369, 2.723] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.628 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.424 ±(99.9%) 0.004 ms/op
Iteration   1: 2.422 ±(99.9%) 0.004 ms/op
Iteration   2: 2.416 ±(99.9%) 0.004 ms/op
Iteration   3: 2.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.418 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (2.416, 2.418, 2.422), stdev = 0.004
  CI (99.9%): [2.350, 2.485] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.301 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.003 ms/op
Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
Iteration   3: 2.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.513 ±(99.9%) 0.585 ms/op [Average]
  (min, avg, max) = (2.476, 2.513, 2.535), stdev = 0.032
  CI (99.9%): [1.928, 3.097] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.987 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.006 ms/op
Iteration   1: 3.076 ±(99.9%) 0.006 ms/op
Iteration   2: 3.112 ±(99.9%) 0.006 ms/op
Iteration   3: 3.098 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.095 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (3.076, 3.095, 3.112), stdev = 0.018
  CI (99.9%): [2.760, 3.430] (assumes normal distribution)


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.678 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 13.671 ms/op
                 createUser·p1.00:   13.828 ms/op

Iteration   2: 2.554 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  10.005 ms/op
                 createUser·p0.9999: 12.354 ms/op
                 createUser·p1.00:   12.845 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  9.174 ms/op
                 createUser·p0.9999: 11.878 ms/op
                 createUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377101
  mean =      2.543 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 179390 
    [ 2.500,  3.750) = 192253 
    [ 3.750,  5.000) = 4085 
    [ 5.000,  6.250) = 773 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 134 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.981 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     13.746 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.846 ms/op
                 existUser·p0.999:  7.915 ms/op
                 existUser·p0.9999: 14.268 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  5.286 ms/op
                 existUser·p0.9999: 15.647 ms/op
                 existUser·p1.00:   16.400 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 11.930 ms/op
                 existUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390595
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 195687 
    [ 2.500,  3.750) = 191446 
    [ 3.750,  5.000) = 2615 
    [ 5.000,  6.250) = 333 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      7.278 ms/op
     p(99.9900) =     14.238 ms/op
     p(99.9990) =     16.074 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


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
# Warmup Iteration   1: 4.315 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.597 ±(99.9%) 0.006 ms/op
Iteration   1: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  12.288 ms/op
                 getUser·p0.9999: 14.893 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   2: 2.586 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.154 ms/op
                 getUser·p0.95:   3.322 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  10.416 ms/op
                 getUser·p0.9999: 14.734 ms/op
                 getUser·p1.00:   15.565 ms/op

Iteration   3: 2.569 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.146 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  8.562 ms/op
                 getUser·p0.9999: 13.100 ms/op
                 getUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 373033
  mean =      2.571 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 179864 
    [ 2.500,  3.750) = 186670 
    [ 3.750,  5.000) = 5051 
    [ 5.000,  6.250) = 948 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.142 ms/op
     p(95.0000) =      3.297 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     14.642 ms/op
     p(99.9990) =     15.320 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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
# Warmup Iteration   1: 5.211 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.009 ms/op
Iteration   1: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.781 ms/op
                 listUser·p0.9999: 12.403 ms/op
                 listUser·p1.00:   13.271 ms/op

Iteration   2: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  10.067 ms/op
                 listUser·p0.9999: 12.215 ms/op
                 listUser·p1.00:   13.189 ms/op

Iteration   3: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  10.035 ms/op
                 listUser·p0.9999: 12.330 ms/op
                 listUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313865
  mean =      3.056 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 80553 
    [ 2.500,  3.750) = 191079 
    [ 3.750,  5.000) = 34415 
    [ 5.000,  6.250) = 6121 
    [ 6.250,  7.500) = 868 
    [ 7.500,  8.750) = 213 
    [ 8.750, 10.000) = 216 
    [10.000, 11.250) = 155 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.912 ms/op
     p(99.9900) =     12.321 ms/op
     p(99.9990) =     13.203 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.477 ± 0.967  ops/ms
ClientPb.existUser                       thrpt       3  12.875 ± 1.339  ops/ms
ClientPb.getUser                         thrpt       3  12.778 ± 2.221  ops/ms
ClientPb.listUser                        thrpt       3  10.705 ± 0.779  ops/ms
ClientPb.createUser                       avgt       3   2.546 ± 0.177   ms/op
ClientPb.existUser                        avgt       3   2.418 ± 0.068   ms/op
ClientPb.getUser                          avgt       3   2.513 ± 0.585   ms/op
ClientPb.listUser                         avgt       3   3.095 ± 0.335   ms/op
ClientPb.createUser                     sample  377101   2.543 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.974           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.486           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.468           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.828           ms/op
ClientPb.existUser                      sample  390595   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.918           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.278           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.238           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.400           ms/op
ClientPb.getUser                        sample  373033   2.571 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.903           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.585           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.642           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.565           ms/op
ClientPb.listUser                       sample  313865   3.056 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.932           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.912           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.321           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.271           ms/op
