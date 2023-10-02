# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.176 ops/ms
# Warmup Iteration   2: 5.726 ops/ms
# Warmup Iteration   3: 8.846 ops/ms
Iteration   1: 9.265 ops/ms
Iteration   2: 9.309 ops/ms
Iteration   3: 9.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.361 ±(99.9%) 2.385 ops/ms [Average]
  (min, avg, max) = (9.265, 9.361, 9.510), stdev = 0.131
  CI (99.9%): [6.976, 11.746] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.210 ops/ms
# Warmup Iteration   2: 8.934 ops/ms
# Warmup Iteration   3: 9.613 ops/ms
Iteration   1: 9.718 ops/ms
Iteration   2: 9.922 ops/ms
Iteration   3: 9.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.801 ±(99.9%) 1.946 ops/ms [Average]
  (min, avg, max) = (9.718, 9.801, 9.922), stdev = 0.107
  CI (99.9%): [7.855, 11.748] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.098 ops/ms
# Warmup Iteration   2: 8.687 ops/ms
# Warmup Iteration   3: 9.457 ops/ms
Iteration   1: 9.051 ops/ms
Iteration   2: 9.530 ops/ms
Iteration   3: 9.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.367 ±(99.9%) 4.996 ops/ms [Average]
  (min, avg, max) = (9.051, 9.367, 9.530), stdev = 0.274
  CI (99.9%): [4.371, 14.363] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.887 ops/ms
# Warmup Iteration   2: 7.164 ops/ms
# Warmup Iteration   3: 7.933 ops/ms
Iteration   1: 7.926 ops/ms
Iteration   2: 7.914 ops/ms
Iteration   3: 7.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.932 ±(99.9%) 0.402 ops/ms [Average]
  (min, avg, max) = (7.914, 7.932, 7.957), stdev = 0.022
  CI (99.9%): [7.530, 8.334] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.413 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.004 ms/op
Iteration   1: 3.450 ±(99.9%) 0.004 ms/op
Iteration   2: 3.357 ±(99.9%) 0.003 ms/op
Iteration   3: 3.397 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.401 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.357, 3.401, 3.450), stdev = 0.047
  CI (99.9%): [2.548, 4.254] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.172 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.378 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.002 ms/op
Iteration   1: 3.211 ±(99.9%) 0.004 ms/op
Iteration   2: 3.270 ±(99.9%) 0.002 ms/op
Iteration   3: 3.356 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.279 ±(99.9%) 1.330 ms/op [Average]
  (min, avg, max) = (3.211, 3.279, 3.356), stdev = 0.073
  CI (99.9%): [1.948, 4.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.594 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.004 ms/op
Iteration   1: 3.507 ±(99.9%) 0.004 ms/op
Iteration   2: 3.388 ±(99.9%) 0.003 ms/op
Iteration   3: 3.360 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.418 ±(99.9%) 1.430 ms/op [Average]
  (min, avg, max) = (3.360, 3.418, 3.507), stdev = 0.078
  CI (99.9%): [1.989, 4.848] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.429 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.268 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.005 ms/op
Iteration   1: 4.042 ±(99.9%) 0.006 ms/op
Iteration   2: 4.033 ±(99.9%) 0.007 ms/op
Iteration   3: 3.922 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.999 ±(99.9%) 1.217 ms/op [Average]
  (min, avg, max) = (3.922, 3.999, 4.042), stdev = 0.067
  CI (99.9%): [2.782, 5.216] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.410 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.008 ms/op
Iteration   1: 3.441 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.255 ms/op
                 createUser·p0.999:  19.073 ms/op
                 createUser·p0.9999: 21.182 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   2: 3.415 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.280 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  20.910 ms/op
                 createUser·p0.9999: 23.556 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 3.387 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  16.511 ms/op
                 createUser·p0.9999: 25.173 ms/op
                 createUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281080
  mean =      3.414 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6598 
    [ 2.500,  5.000) = 268209 
    [ 5.000,  7.500) = 5300 
    [ 7.500, 10.000) = 515 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 162 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     16.761 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     25.643 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.965 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.508 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.008 ms/op
Iteration   1: 3.348 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  11.271 ms/op
                 existUser·p0.9999: 20.277 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   2: 3.374 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   6.914 ms/op
                 existUser·p0.999:  15.008 ms/op
                 existUser·p0.9999: 21.889 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   3: 3.330 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.637 ms/op
                 existUser·p0.999:  17.489 ms/op
                 existUser·p0.9999: 22.197 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286388
  mean =      3.350 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13437 
    [ 2.500,  5.000) = 267598 
    [ 5.000,  7.500) = 4320 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      6.202 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     21.999 ms/op
     p(99.9990) =     22.942 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.857 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.011 ms/op
Iteration   1: 3.410 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  17.334 ms/op
                 getUser·p0.9999: 20.042 ms/op
                 getUser·p1.00:   21.070 ms/op

Iteration   2: 3.476 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  19.530 ms/op
                 getUser·p0.9999: 22.112 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 3.512 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  12.271 ms/op
                 getUser·p0.9999: 23.616 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276848
  mean =      3.465 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3300 
    [ 2.500,  5.000) = 266677 
    [ 5.000,  7.500) = 5814 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     15.663 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     23.863 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.268 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.012 ms/op
Iteration   1: 3.997 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.557 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  15.254 ms/op
                 listUser·p0.9999: 21.824 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 4.011 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.937 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   3: 4.049 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 15.450 ms/op
                 listUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238839
  mean =      4.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 231727 
    [ 5.000,  7.500) = 5481 
    [ 7.500, 10.000) = 848 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 301 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     20.881 ms/op
     p(99.9990) =     22.455 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.361 ± 2.385  ops/ms
ClientPb.existUser                       thrpt       3   9.801 ± 1.946  ops/ms
ClientPb.getUser                         thrpt       3   9.367 ± 4.996  ops/ms
ClientPb.listUser                        thrpt       3   7.932 ± 0.402  ops/ms
ClientPb.createUser                       avgt       3   3.401 ± 0.853   ms/op
ClientPb.existUser                        avgt       3   3.279 ± 1.330   ms/op
ClientPb.getUser                          avgt       3   3.418 ± 1.430   ms/op
ClientPb.listUser                         avgt       3   3.999 ± 1.217   ms/op
ClientPb.createUser                     sample  281080   3.414 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.255           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.874           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.761           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.822           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.821           ms/op
ClientPb.existUser                      sample  286388   3.350 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.008           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.202           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.008           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.999           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.364           ms/op
ClientPb.getUser                        sample  276848   3.465 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.945           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.128           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.663           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.544           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.921           ms/op
ClientPb.listUser                       sample  238839   4.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.405           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.024           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.881           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.741           ms/op
