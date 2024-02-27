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
# Warmup Iteration   1: 4.349 ops/ms
# Warmup Iteration   2: 11.987 ops/ms
# Warmup Iteration   3: 12.536 ops/ms
Iteration   1: 12.717 ops/ms
Iteration   2: 12.678 ops/ms
Iteration   3: 12.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.715 ±(99.9%) 0.667 ops/ms [Average]
  (min, avg, max) = (12.678, 12.715, 12.751), stdev = 0.037
  CI (99.9%): [12.049, 13.382] (assumes normal distribution)


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
# Warmup Iteration   1: 7.859 ops/ms
# Warmup Iteration   2: 12.943 ops/ms
# Warmup Iteration   3: 12.960 ops/ms
Iteration   1: 12.995 ops/ms
Iteration   2: 13.037 ops/ms
Iteration   3: 13.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.020 ±(99.9%) 0.402 ops/ms [Average]
  (min, avg, max) = (12.995, 13.020, 13.037), stdev = 0.022
  CI (99.9%): [12.618, 13.423] (assumes normal distribution)


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
# Warmup Iteration   1: 7.672 ops/ms
# Warmup Iteration   2: 12.672 ops/ms
# Warmup Iteration   3: 12.643 ops/ms
Iteration   1: 12.885 ops/ms
Iteration   2: 12.805 ops/ms
Iteration   3: 12.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.831 ±(99.9%) 0.847 ops/ms [Average]
  (min, avg, max) = (12.804, 12.831, 12.885), stdev = 0.046
  CI (99.9%): [11.984, 13.678] (assumes normal distribution)


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
# Warmup Iteration   1: 6.710 ops/ms
# Warmup Iteration   2: 10.594 ops/ms
# Warmup Iteration   3: 10.570 ops/ms
Iteration   1: 10.738 ops/ms
Iteration   2: 10.753 ops/ms
Iteration   3: 10.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.732 ±(99.9%) 0.457 ops/ms [Average]
  (min, avg, max) = (10.704, 10.732, 10.753), stdev = 0.025
  CI (99.9%): [10.275, 11.189] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.003 ms/op
Iteration   1: 2.557 ±(99.9%) 0.004 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.545 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (2.519, 2.545, 2.560), stdev = 0.023
  CI (99.9%): [2.132, 2.959] (assumes normal distribution)


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
# Warmup Iteration   1: 3.675 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
Iteration   3: 2.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.462, 2.478, 2.491), stdev = 0.014
  CI (99.9%): [2.219, 2.736] (assumes normal distribution)


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
# Warmup Iteration   1: 3.893 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
Iteration   3: 2.467 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.465 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.449, 2.465, 2.479), stdev = 0.015
  CI (99.9%): [2.193, 2.738] (assumes normal distribution)


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
# Warmup Iteration   1: 4.602 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.005 ms/op
Iteration   1: 2.996 ±(99.9%) 0.005 ms/op
Iteration   2: 3.026 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.008 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.996, 3.008, 3.026), stdev = 0.016
  CI (99.9%): [2.717, 3.298] (assumes normal distribution)


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
# Warmup Iteration   1: 4.371 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
Iteration   1: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.666 ms/op
                 createUser·p0.999:  11.297 ms/op
                 createUser·p0.9999: 14.299 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.557 ms/op
                 createUser·p0.999:  9.267 ms/op
                 createUser·p0.9999: 12.681 ms/op
                 createUser·p1.00:   12.845 ms/op

Iteration   3: 2.575 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.112 ms/op
                 createUser·p0.999:  8.993 ms/op
                 createUser·p0.9999: 11.190 ms/op
                 createUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377044
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 179730 
    [ 2.500,  3.750) = 193586 
    [ 3.750,  5.000) = 2760 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     13.602 ms/op
     p(99.9990) =     14.647 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 3.601 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
Iteration   1: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.371 ms/op
                 existUser·p0.999:  6.127 ms/op
                 existUser·p0.9999: 13.743 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  7.243 ms/op
                 existUser·p0.9999: 13.193 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.891 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 11.502 ms/op
                 existUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393461
  mean =      2.438 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 197077 
    [ 2.500,  3.750) = 193102 
    [ 3.750,  5.000) = 2415 
    [ 5.000,  6.250) = 400 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      7.540 ms/op
     p(99.9900) =     13.216 ms/op
     p(99.9990) =     14.190 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.006 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  6.930 ms/op
                 getUser·p0.9999: 14.042 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 2.485 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  8.009 ms/op
                 getUser·p0.9999: 20.349 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  6.370 ms/op
                 getUser·p0.9999: 11.354 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387051
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 194463 
    [ 2.500,  5.000) = 191722 
    [ 5.000,  7.500) = 482 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      6.930 ms/op
     p(99.9900) =     14.576 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 4.676 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
Iteration   1: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.765 ms/op
                 listUser·p0.9999: 11.614 ms/op
                 listUser·p1.00:   12.288 ms/op

Iteration   2: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 12.960 ms/op
                 listUser·p1.00:   13.173 ms/op

Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.965 ms/op
                 listUser·p0.9999: 11.668 ms/op
                 listUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319789
  mean =      2.999 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 91470 
    [ 2.500,  3.750) = 190942 
    [ 3.750,  5.000) = 30742 
    [ 5.000,  6.250) = 5368 
    [ 6.250,  7.500) = 487 
    [ 7.500,  8.750) = 157 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 194 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     12.075 ms/op
     p(99.9990) =     13.025 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.715 ± 0.667  ops/ms
ClientPb.existUser                       thrpt       3  13.020 ± 0.402  ops/ms
ClientPb.getUser                         thrpt       3  12.831 ± 0.847  ops/ms
ClientPb.listUser                        thrpt       3  10.732 ± 0.457  ops/ms
ClientPb.createUser                       avgt       3   2.545 ± 0.414   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.259   ms/op
ClientPb.getUser                          avgt       3   2.465 ± 0.272   ms/op
ClientPb.listUser                         avgt       3   3.008 ± 0.291   ms/op
ClientPb.createUser                     sample  377044   2.544 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.766           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.011           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.602           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.057           ms/op
ClientPb.existUser                      sample  393461   2.438 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.932           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.540           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.216           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.238           ms/op
ClientPb.getUser                        sample  387051   2.478 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.941           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.930           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.576           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.660           ms/op
ClientPb.listUser                       sample  319789   2.999 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.897           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.748           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.075           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.173           ms/op
