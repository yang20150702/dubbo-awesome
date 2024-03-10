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
# Warmup Iteration   1: 4.930 ops/ms
# Warmup Iteration   2: 12.582 ops/ms
# Warmup Iteration   3: 12.605 ops/ms
Iteration   1: 12.654 ops/ms
Iteration   2: 12.676 ops/ms
Iteration   3: 12.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.713 ±(99.9%) 1.533 ops/ms [Average]
  (min, avg, max) = (12.654, 12.713, 12.809), stdev = 0.084
  CI (99.9%): [11.180, 14.246] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.124 ops/ms
# Warmup Iteration   2: 13.268 ops/ms
# Warmup Iteration   3: 13.138 ops/ms
Iteration   1: 13.197 ops/ms
Iteration   2: 13.444 ops/ms
Iteration   3: 13.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.320 ±(99.9%) 2.254 ops/ms [Average]
  (min, avg, max) = (13.197, 13.320, 13.444), stdev = 0.124
  CI (99.9%): [11.066, 15.574] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.986 ops/ms
# Warmup Iteration   2: 12.747 ops/ms
# Warmup Iteration   3: 12.864 ops/ms
Iteration   1: 12.980 ops/ms
Iteration   2: 12.971 ops/ms
Iteration   3: 12.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.969 ±(99.9%) 0.210 ops/ms [Average]
  (min, avg, max) = (12.957, 12.969, 12.980), stdev = 0.012
  CI (99.9%): [12.760, 13.179] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.871 ops/ms
# Warmup Iteration   2: 10.497 ops/ms
# Warmup Iteration   3: 10.468 ops/ms
Iteration   1: 10.463 ops/ms
Iteration   2: 10.452 ops/ms
Iteration   3: 10.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.482 ±(99.9%) 0.795 ops/ms [Average]
  (min, avg, max) = (10.452, 10.482, 10.532), stdev = 0.044
  CI (99.9%): [9.687, 11.278] (assumes normal distribution)


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.004 ms/op
Iteration   1: 2.562 ±(99.9%) 0.004 ms/op
Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
Iteration   3: 2.549 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.550 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.539, 2.550, 2.562), stdev = 0.012
  CI (99.9%): [2.335, 2.765] (assumes normal distribution)


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.415 ±(99.9%) 0.004 ms/op
Iteration   3: 2.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.425 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (2.415, 2.425, 2.444), stdev = 0.016
  CI (99.9%): [2.131, 2.719] (assumes normal distribution)


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.480 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.003 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.463 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (2.441, 2.463, 2.480), stdev = 0.020
  CI (99.9%): [2.096, 2.831] (assumes normal distribution)


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
# Warmup Iteration   1: 4.721 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
Iteration   1: 2.961 ±(99.9%) 0.005 ms/op
Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
Iteration   3: 2.974 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.968 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.961, 2.968, 2.974), stdev = 0.007
  CI (99.9%): [2.847, 3.090] (assumes normal distribution)


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.584 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  8.343 ms/op
                 createUser·p0.9999: 13.779 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 13.089 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  7.679 ms/op
                 createUser·p0.9999: 11.223 ms/op
                 createUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389320
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 193589 
    [ 2.500,  3.750) = 190789 
    [ 3.750,  5.000) = 3452 
    [ 5.000,  6.250) = 866 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      8.952 ms/op
     p(99.9900) =     13.190 ms/op
     p(99.9990) =     13.877 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.753 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  5.924 ms/op
                 existUser·p0.9999: 13.337 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  7.534 ms/op
                 existUser·p0.9999: 15.399 ms/op
                 existUser·p1.00:   15.860 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  7.549 ms/op
                 existUser·p0.9999: 11.619 ms/op
                 existUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391538
  mean =      2.450 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 197261 
    [ 2.500,  3.750) = 190267 
    [ 3.750,  5.000) = 3196 
    [ 5.000,  6.250) = 352 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      7.016 ms/op
     p(99.9900) =     13.476 ms/op
     p(99.9990) =     15.658 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.006 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.513 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  6.317 ms/op
                 getUser·p0.9999: 13.580 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   2: 2.493 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  9.723 ms/op
                 getUser·p0.9999: 13.143 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  5.443 ms/op
                 getUser·p0.9999: 10.778 ms/op
                 getUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390135
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 197371 
    [ 2.500,  3.750) = 188472 
    [ 3.750,  5.000) = 3279 
    [ 5.000,  6.250) = 549 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 144 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      6.028 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     13.830 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 4.816 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.009 ms/op
Iteration   1: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.592 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 10.955 ms/op
                 listUser·p1.00:   12.894 ms/op

Iteration   2: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.732 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 12.272 ms/op
                 listUser·p1.00:   13.271 ms/op

Iteration   3: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 11.617 ms/op
                 listUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319928
  mean =      2.998 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 94817 
    [ 2.500,  3.750) = 184984 
    [ 3.750,  5.000) = 32631 
    [ 5.000,  6.250) = 6117 
    [ 6.250,  7.500) = 588 
    [ 7.500,  8.750) = 148 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 170 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     11.944 ms/op
     p(99.9990) =     12.786 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.713 ± 1.533  ops/ms
ClientPb.existUser                       thrpt       3  13.320 ± 2.254  ops/ms
ClientPb.getUser                         thrpt       3  12.969 ± 0.210  ops/ms
ClientPb.listUser                        thrpt       3  10.482 ± 0.795  ops/ms
ClientPb.createUser                       avgt       3   2.550 ± 0.215   ms/op
ClientPb.existUser                        avgt       3   2.425 ± 0.294   ms/op
ClientPb.getUser                          avgt       3   2.463 ± 0.367   ms/op
ClientPb.listUser                         avgt       3   2.968 ± 0.121   ms/op
ClientPb.createUser                     sample  389320   2.463 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.584           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.507           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.952           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.190           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.778           ms/op
ClientPb.existUser                      sample  391538   2.450 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.844           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.016           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.476           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.860           ms/op
ClientPb.getUser                        sample  390135   2.459 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.513           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.028           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.238           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.189           ms/op
ClientPb.listUser                       sample  319928   2.998 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.732           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.650           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.944           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.271           ms/op
