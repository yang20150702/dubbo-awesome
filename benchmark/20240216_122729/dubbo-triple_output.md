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
# Warmup Iteration   1: 5.014 ops/ms
# Warmup Iteration   2: 12.177 ops/ms
# Warmup Iteration   3: 12.255 ops/ms
Iteration   1: 12.702 ops/ms
Iteration   2: 12.349 ops/ms
Iteration   3: 12.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.497 ±(99.9%) 3.344 ops/ms [Average]
  (min, avg, max) = (12.349, 12.497, 12.702), stdev = 0.183
  CI (99.9%): [9.153, 15.841] (assumes normal distribution)


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
# Warmup Iteration   1: 7.788 ops/ms
# Warmup Iteration   2: 13.079 ops/ms
# Warmup Iteration   3: 12.945 ops/ms
Iteration   1: 13.062 ops/ms
Iteration   2: 13.231 ops/ms
Iteration   3: 13.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.133 ±(99.9%) 1.600 ops/ms [Average]
  (min, avg, max) = (13.062, 13.133, 13.231), stdev = 0.088
  CI (99.9%): [11.533, 14.733] (assumes normal distribution)


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
# Warmup Iteration   1: 7.583 ops/ms
# Warmup Iteration   2: 12.650 ops/ms
# Warmup Iteration   3: 12.961 ops/ms
Iteration   1: 12.829 ops/ms
Iteration   2: 12.762 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.803 ±(99.9%) 0.660 ops/ms [Average]
  (min, avg, max) = (12.762, 12.803, 12.829), stdev = 0.036
  CI (99.9%): [12.143, 13.463] (assumes normal distribution)


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
# Warmup Iteration   1: 6.912 ops/ms
# Warmup Iteration   2: 10.782 ops/ms
# Warmup Iteration   3: 10.681 ops/ms
Iteration   1: 10.780 ops/ms
Iteration   2: 10.756 ops/ms
Iteration   3: 10.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.785 ±(99.9%) 0.598 ops/ms [Average]
  (min, avg, max) = (10.756, 10.785, 10.820), stdev = 0.033
  CI (99.9%): [10.187, 11.384] (assumes normal distribution)


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
Iteration   3: 2.541 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.539 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.520, 2.539, 2.556), stdev = 0.018
  CI (99.9%): [2.215, 2.863] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.787 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.465 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.459, 2.465, 2.468), stdev = 0.005
  CI (99.9%): [2.372, 2.557] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.843 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.483, 2.490, 2.499), stdev = 0.009
  CI (99.9%): [2.332, 2.647] (assumes normal distribution)


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
# Warmup Iteration   1: 4.906 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
Iteration   3: 3.031 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.032 ±(99.9%) 0.040 ms/op [Average]
  (min, avg, max) = (3.030, 3.032, 3.034), stdev = 0.002
  CI (99.9%): [2.992, 3.071] (assumes normal distribution)


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.508 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  11.348 ms/op
                 createUser·p0.9999: 13.927 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  9.372 ms/op
                 createUser·p0.9999: 13.206 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 11.433 ms/op
                 createUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379639
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 183294 
    [ 2.500,  3.750) = 191828 
    [ 3.750,  5.000) = 3527 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     14.156 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 3.619 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.367 ms/op
                 existUser·p0.999:  6.220 ms/op
                 existUser·p0.9999: 14.172 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  8.746 ms/op
                 existUser·p0.9999: 13.352 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.786 ms/op
                 existUser·p0.999:  6.144 ms/op
                 existUser·p0.9999: 11.846 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390493
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 189862 
    [ 2.500,  3.750) = 197498 
    [ 3.750,  5.000) = 2283 
    [ 5.000,  6.250) = 410 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      6.361 ms/op
     p(99.9900) =     13.401 ms/op
     p(99.9990) =     14.341 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.604 ms/op
                 getUser·p0.999:  5.198 ms/op
                 getUser·p0.9999: 13.688 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  10.195 ms/op
                 getUser·p0.9999: 15.853 ms/op
                 getUser·p1.00:   17.859 ms/op

Iteration   3: 2.543 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.055 ms/op
                 getUser·p0.999:  8.260 ms/op
                 getUser·p0.9999: 13.103 ms/op
                 getUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380239
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 186868 
    [ 2.500,  3.750) = 188538 
    [ 3.750,  5.000) = 3717 
    [ 5.000,  6.250) = 703 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      6.085 ms/op
     p(99.9900) =     13.795 ms/op
     p(99.9990) =     17.294 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.624 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.009 ms/op
Iteration   1: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.487 ms/op
                 listUser·p0.9999: 11.747 ms/op
                 listUser·p1.00:   12.812 ms/op

Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.742 ms/op
                 listUser·p0.9999: 11.099 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   3: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.595 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 11.453 ms/op
                 listUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315165
  mean =      3.043 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 86969 
    [ 2.500,  3.750) = 186243 
    [ 3.750,  5.000) = 34315 
    [ 5.000,  6.250) = 6158 
    [ 6.250,  7.500) = 715 
    [ 7.500,  8.750) = 162 
    [ 8.750, 10.000) = 312 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     11.428 ms/op
     p(99.9990) =     12.339 ms/op
     p(99.9999) =     12.812 ms/op
    p(100.0000) =     12.812 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.497 ± 3.344  ops/ms
ClientPb.existUser                       thrpt       3  13.133 ± 1.600  ops/ms
ClientPb.getUser                         thrpt       3  12.803 ± 0.660  ops/ms
ClientPb.listUser                        thrpt       3  10.785 ± 0.598  ops/ms
ClientPb.createUser                       avgt       3   2.539 ± 0.324   ms/op
ClientPb.existUser                        avgt       3   2.465 ± 0.092   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.158   ms/op
ClientPb.listUser                         avgt       3   3.032 ± 0.040   ms/op
ClientPb.createUser                     sample  379639   2.526 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.798           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.520           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.270           ms/op
ClientPb.existUser                      sample  390493   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.943           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.361           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.401           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.647           ms/op
ClientPb.getUser                        sample  380239   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.940           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.085           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.795           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.859           ms/op
ClientPb.listUser                       sample  315165   3.043 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.595           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.428           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.812           ms/op
