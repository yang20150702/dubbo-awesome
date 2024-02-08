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
# Warmup Iteration   1: 5.042 ops/ms
# Warmup Iteration   2: 12.250 ops/ms
# Warmup Iteration   3: 12.170 ops/ms
Iteration   1: 12.437 ops/ms
Iteration   2: 12.544 ops/ms
Iteration   3: 12.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.493 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (12.437, 12.493, 12.544), stdev = 0.054
  CI (99.9%): [11.507, 13.479] (assumes normal distribution)


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
# Warmup Iteration   1: 8.081 ops/ms
# Warmup Iteration   2: 13.015 ops/ms
# Warmup Iteration   3: 12.924 ops/ms
Iteration   1: 12.942 ops/ms
Iteration   2: 12.872 ops/ms
Iteration   3: 12.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.848 ±(99.9%) 1.959 ops/ms [Average]
  (min, avg, max) = (12.731, 12.848, 12.942), stdev = 0.107
  CI (99.9%): [10.889, 14.807] (assumes normal distribution)


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
# Warmup Iteration   1: 7.697 ops/ms
# Warmup Iteration   2: 12.237 ops/ms
# Warmup Iteration   3: 12.342 ops/ms
Iteration   1: 12.766 ops/ms
Iteration   2: 12.662 ops/ms
Iteration   3: 12.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.658 ±(99.9%) 2.013 ops/ms [Average]
  (min, avg, max) = (12.545, 12.658, 12.766), stdev = 0.110
  CI (99.9%): [10.645, 14.670] (assumes normal distribution)


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
# Warmup Iteration   1: 6.220 ops/ms
# Warmup Iteration   2: 10.407 ops/ms
# Warmup Iteration   3: 10.559 ops/ms
Iteration   1: 10.839 ops/ms
Iteration   2: 10.834 ops/ms
Iteration   3: 10.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.884 ±(99.9%) 1.491 ops/ms [Average]
  (min, avg, max) = (10.834, 10.884, 10.978), stdev = 0.082
  CI (99.9%): [9.392, 12.375] (assumes normal distribution)


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.008 ms/op
Iteration   1: 2.468 ±(99.9%) 0.007 ms/op
Iteration   2: 2.487 ±(99.9%) 0.007 ms/op
Iteration   3: 2.502 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.486 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (2.468, 2.486, 2.502), stdev = 0.017
  CI (99.9%): [2.172, 2.799] (assumes normal distribution)


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
# Warmup Iteration   1: 3.563 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.393 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.358 ±(99.9%) 0.006 ms/op
Iteration   1: 2.354 ±(99.9%) 0.005 ms/op
Iteration   2: 2.330 ±(99.9%) 0.007 ms/op
Iteration   3: 2.377 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.354 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (2.330, 2.354, 2.377), stdev = 0.024
  CI (99.9%): [1.923, 2.785] (assumes normal distribution)


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
# Warmup Iteration   1: 4.051 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.572 ±(99.9%) 0.005 ms/op
Iteration   3: 2.501 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.529 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (2.501, 2.529, 2.572), stdev = 0.037
  CI (99.9%): [1.849, 3.210] (assumes normal distribution)


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
# Warmup Iteration   1: 4.781 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.005 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
Iteration   2: 3.022 ±(99.9%) 0.004 ms/op
Iteration   3: 3.022 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.022 ±(99.9%) 0.026 ms/op [Average]
  (min, avg, max) = (3.022, 3.022, 3.024), stdev = 0.001
  CI (99.9%): [2.997, 3.048] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.708 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.573 ±(99.9%) 0.006 ms/op
Iteration   1: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  11.217 ms/op
                 createUser·p0.9999: 14.178 ms/op
                 createUser·p1.00:   14.959 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 12.704 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.421 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  8.733 ms/op
                 createUser·p0.9999: 10.846 ms/op
                 createUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378603
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 183009 
    [ 2.500,  3.750) = 191938 
    [ 3.750,  5.000) = 2826 
    [ 5.000,  6.250) = 234 
    [ 6.250,  7.500) = 118 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 149 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     14.634 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.397 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  6.330 ms/op
                 existUser·p0.9999: 14.221 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  6.971 ms/op
                 existUser·p0.9999: 12.446 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  7.675 ms/op
                 existUser·p0.9999: 12.321 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384575
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 187343 
    [ 2.500,  3.750) = 193349 
    [ 3.750,  5.000) = 2981 
    [ 5.000,  6.250) = 437 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     13.198 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  11.690 ms/op
                 getUser·p0.9999: 14.308 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   2: 2.547 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.603 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.178 ms/op
                 getUser·p0.95:   3.449 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.502 ms/op
                 getUser·p0.9999: 14.138 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.244 ms/op
                 getUser·p0.95:   3.543 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  10.541 ms/op
                 getUser·p0.9999: 12.485 ms/op
                 getUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377069
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 201 
    [ 1.250,  2.500) = 189361 
    [ 2.500,  3.750) = 178003 
    [ 3.750,  5.000) = 7968 
    [ 5.000,  6.250) = 1019 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.387 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.767 ms/op
     p(99.9900) =     14.041 ms/op
     p(99.9990) =     14.593 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 4.923 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.009 ms/op
Iteration   1: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  8.477 ms/op
                 listUser·p0.9999: 11.134 ms/op
                 listUser·p1.00:   11.731 ms/op

Iteration   2: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  10.587 ms/op
                 listUser·p0.9999: 12.984 ms/op
                 listUser·p1.00:   13.484 ms/op

Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.653 ms/op
                 listUser·p0.9999: 13.966 ms/op
                 listUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321217
  mean =      2.985 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 186 
    [ 1.250,  2.500) = 102282 
    [ 2.500,  3.750) = 177970 
    [ 3.750,  5.000) = 33763 
    [ 5.000,  6.250) = 5565 
    [ 6.250,  7.500) = 726 
    [ 7.500,  8.750) = 249 
    [ 8.750, 10.000) = 206 
    [10.000, 11.250) = 171 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     12.632 ms/op
     p(99.9990) =     16.013 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.493 ± 0.986  ops/ms
ClientPb.existUser                       thrpt       3  12.848 ± 1.959  ops/ms
ClientPb.getUser                         thrpt       3  12.658 ± 2.013  ops/ms
ClientPb.listUser                        thrpt       3  10.884 ± 1.491  ops/ms
ClientPb.createUser                       avgt       3   2.486 ± 0.313   ms/op
ClientPb.existUser                        avgt       3   2.354 ± 0.431   ms/op
ClientPb.getUser                          avgt       3   2.529 ± 0.680   ms/op
ClientPb.listUser                         avgt       3   3.022 ± 0.026   ms/op
ClientPb.createUser                     sample  378603   2.532 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.421           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.175           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.877           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.959           ms/op
ClientPb.existUser                      sample  384575   2.493 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.397           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.881           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.198           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.385           ms/op
ClientPb.getUser                        sample  377069   2.544 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.603           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.767           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.041           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.778           ms/op
ClientPb.listUser                       sample  321217   2.985 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.893           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.632           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.646           ms/op
