# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.641 ops/ms
# Warmup Iteration   2: 6.603 ops/ms
# Warmup Iteration   3: 9.217 ops/ms
Iteration   1: 9.588 ops/ms
Iteration   2: 10.118 ops/ms
Iteration   3: 9.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.811 ±(99.9%) 5.022 ops/ms [Average]
  (min, avg, max) = (9.588, 9.811, 10.118), stdev = 0.275
  CI (99.9%): [4.789, 14.832] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.832 ops/ms
# Warmup Iteration   2: 9.042 ops/ms
# Warmup Iteration   3: 10.171 ops/ms
Iteration   1: 10.145 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.327 ±(99.9%) 3.513 ops/ms [Average]
  (min, avg, max) = (10.145, 10.327, 10.528), stdev = 0.193
  CI (99.9%): [6.814, 13.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.518 ops/ms
# Warmup Iteration   2: 8.990 ops/ms
# Warmup Iteration   3: 9.835 ops/ms
Iteration   1: 9.877 ops/ms
Iteration   2: 10.205 ops/ms
Iteration   3: 10.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.157 ±(99.9%) 4.739 ops/ms [Average]
  (min, avg, max) = (9.877, 10.157, 10.390), stdev = 0.260
  CI (99.9%): [5.418, 14.897] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ops/ms
# Warmup Iteration   2: 8.065 ops/ms
# Warmup Iteration   3: 8.261 ops/ms
Iteration   1: 8.631 ops/ms
Iteration   2: 8.325 ops/ms
Iteration   3: 8.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.459 ±(99.9%) 2.859 ops/ms [Average]
  (min, avg, max) = (8.325, 8.459, 8.631), stdev = 0.157
  CI (99.9%): [5.599, 11.318] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.831 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.006 ms/op
Iteration   1: 3.250 ±(99.9%) 0.002 ms/op
Iteration   2: 3.104 ±(99.9%) 0.005 ms/op
Iteration   3: 3.254 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.203 ±(99.9%) 1.566 ms/op [Average]
  (min, avg, max) = (3.104, 3.203, 3.254), stdev = 0.086
  CI (99.9%): [1.637, 4.769] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.505 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.378 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.002 ms/op
Iteration   1: 3.049 ±(99.9%) 0.004 ms/op
Iteration   2: 3.103 ±(99.9%) 0.004 ms/op
Iteration   3: 3.041 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.064 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (3.041, 3.064, 3.103), stdev = 0.034
  CI (99.9%): [2.448, 3.680] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.577 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.006 ms/op
Iteration   1: 3.273 ±(99.9%) 0.002 ms/op
Iteration   2: 3.147 ±(99.9%) 0.002 ms/op
Iteration   3: 3.309 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.243 ±(99.9%) 1.551 ms/op [Average]
  (min, avg, max) = (3.147, 3.243, 3.309), stdev = 0.085
  CI (99.9%): [1.692, 4.795] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.589 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.008 ms/op
Iteration   1: 3.814 ±(99.9%) 0.004 ms/op
Iteration   2: 3.704 ±(99.9%) 0.009 ms/op
Iteration   3: 3.824 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.781 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (3.704, 3.781, 3.824), stdev = 0.066
  CI (99.9%): [2.568, 4.994] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.910 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
Iteration   1: 3.438 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  18.346 ms/op
                 createUser·p0.9999: 20.546 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  9.830 ms/op
                 createUser·p0.9999: 21.761 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   3: 3.159 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  15.493 ms/op
                 createUser·p0.9999: 41.055 ms/op
                 createUser·p1.00:   42.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294074
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 288932 
    [ 5.000, 10.000) = 4783 
    [10.000, 15.000) = 45 
    [15.000, 20.000) = 190 
    [20.000, 25.000) = 92 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     15.482 ms/op
     p(99.9900) =     39.492 ms/op
     p(99.9990) =     42.009 ms/op
     p(99.9999) =     42.402 ms/op
    p(100.0000) =     42.402 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.140 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.326 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.008 ms/op
Iteration   1: 3.016 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  9.241 ms/op
                 existUser·p0.9999: 20.428 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   2: 3.119 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  13.523 ms/op
                 existUser·p0.9999: 21.692 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  13.730 ms/op
                 existUser·p0.9999: 20.380 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311549
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17482 
    [ 2.500,  5.000) = 289457 
    [ 5.000,  7.500) = 3985 
    [ 7.500, 10.000) = 214 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     13.435 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     22.377 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.179 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.009 ms/op
Iteration   1: 3.321 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  15.866 ms/op
                 getUser·p0.9999: 21.487 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   2: 3.185 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.933 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  14.574 ms/op
                 getUser·p0.9999: 22.671 ms/op
                 getUser·p1.00:   23.658 ms/op

Iteration   3: 3.144 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  8.962 ms/op
                 getUser·p0.9999: 21.991 ms/op
                 getUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298506
  mean =      3.215 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21549 
    [ 2.500,  5.000) = 268429 
    [ 5.000,  7.500) = 7622 
    [ 7.500, 10.000) = 452 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     13.099 ms/op
     p(99.9900) =     22.156 ms/op
     p(99.9990) =     23.399 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.965 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.011 ms/op
Iteration   1: 3.807 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.812 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  17.733 ms/op
                 listUser·p0.9999: 21.168 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   2: 3.751 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  14.123 ms/op
                 listUser·p0.9999: 16.572 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 3.735 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.876 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254784
  mean =      3.764 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 246747 
    [ 5.000,  7.500) = 5696 
    [ 7.500, 10.000) = 1577 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.812 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     16.224 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     21.838 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.811 ± 5.022  ops/ms
ClientPb.existUser                       thrpt       3  10.327 ± 3.513  ops/ms
ClientPb.getUser                         thrpt       3  10.157 ± 4.739  ops/ms
ClientPb.listUser                        thrpt       3   8.459 ± 2.859  ops/ms
ClientPb.createUser                       avgt       3   3.203 ± 1.566   ms/op
ClientPb.existUser                        avgt       3   3.064 ± 0.616   ms/op
ClientPb.getUser                          avgt       3   3.243 ± 1.551   ms/op
ClientPb.listUser                         avgt       3   3.781 ± 1.213   ms/op
ClientPb.createUser                     sample  294074   3.263 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.159           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.482           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.492           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.402           ms/op
ClientPb.existUser                      sample  311549   3.079 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.005           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.435           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.070           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.381           ms/op
ClientPb.getUser                        sample  298506   3.215 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.202           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.604           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.931           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.099           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.156           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.658           ms/op
ClientPb.listUser                       sample  254784   3.764 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.812           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.644           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.118           ms/op
