# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.008 ops/ms
# Warmup Iteration   2: 4.975 ops/ms
# Warmup Iteration   3: 8.083 ops/ms
Iteration   1: 8.821 ops/ms
Iteration   2: 8.902 ops/ms
Iteration   3: 9.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.908 ±(99.9%) 1.646 ops/ms [Average]
  (min, avg, max) = (8.821, 8.908, 9.002), stdev = 0.090
  CI (99.9%): [7.263, 10.554] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.236 ops/ms
# Warmup Iteration   2: 8.667 ops/ms
# Warmup Iteration   3: 9.170 ops/ms
Iteration   1: 9.101 ops/ms
Iteration   2: 9.282 ops/ms
Iteration   3: 9.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.255 ±(99.9%) 2.616 ops/ms [Average]
  (min, avg, max) = (9.101, 9.255, 9.384), stdev = 0.143
  CI (99.9%): [6.639, 11.871] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.639 ops/ms
# Warmup Iteration   2: 8.081 ops/ms
# Warmup Iteration   3: 9.010 ops/ms
Iteration   1: 8.998 ops/ms
Iteration   2: 9.182 ops/ms
Iteration   3: 9.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.126 ±(99.9%) 2.035 ops/ms [Average]
  (min, avg, max) = (8.998, 9.126, 9.199), stdev = 0.112
  CI (99.9%): [7.092, 11.161] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.871 ops/ms
# Warmup Iteration   2: 7.282 ops/ms
# Warmup Iteration   3: 7.560 ops/ms
Iteration   1: 7.479 ops/ms
Iteration   2: 7.605 ops/ms
Iteration   3: 7.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.688 ±(99.9%) 4.757 ops/ms [Average]
  (min, avg, max) = (7.479, 7.688, 7.980), stdev = 0.261
  CI (99.9%): [2.931, 12.445] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.700 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.004 ms/op
Iteration   1: 3.459 ±(99.9%) 0.006 ms/op
Iteration   2: 3.600 ±(99.9%) 0.005 ms/op
Iteration   3: 3.537 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.532 ±(99.9%) 1.285 ms/op [Average]
  (min, avg, max) = (3.459, 3.532, 3.600), stdev = 0.070
  CI (99.9%): [2.247, 4.817] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.365 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.003 ms/op
Iteration   1: 3.422 ±(99.9%) 0.004 ms/op
Iteration   2: 3.408 ±(99.9%) 0.006 ms/op
Iteration   3: 3.580 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.470 ±(99.9%) 1.747 ms/op [Average]
  (min, avg, max) = (3.408, 3.470, 3.580), stdev = 0.096
  CI (99.9%): [1.723, 5.217] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 10.123 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.670 ±(99.9%) 0.006 ms/op
Iteration   1: 3.502 ±(99.9%) 0.007 ms/op
Iteration   2: 3.648 ±(99.9%) 0.004 ms/op
Iteration   3: 3.486 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.545 ±(99.9%) 1.629 ms/op [Average]
  (min, avg, max) = (3.486, 3.545, 3.648), stdev = 0.089
  CI (99.9%): [1.917, 5.174] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 10.828 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.421 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.008 ms/op
Iteration   1: 4.273 ±(99.9%) 0.003 ms/op
Iteration   2: 4.264 ±(99.9%) 0.003 ms/op
Iteration   3: 4.174 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.237 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (4.174, 4.237, 4.273), stdev = 0.055
  CI (99.9%): [3.241, 5.232] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.651 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.011 ms/op
Iteration   1: 3.589 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  21.266 ms/op
                 createUser·p0.9999: 23.828 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   2: 3.556 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  22.134 ms/op
                 createUser·p0.9999: 26.641 ms/op
                 createUser·p1.00:   30.999 ms/op

Iteration   3: 3.510 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.249 ms/op
                 createUser·p0.999:  21.154 ms/op
                 createUser·p0.9999: 25.850 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270297
  mean =      3.551 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6482 
    [ 2.500,  5.000) = 257896 
    [ 5.000,  7.500) = 4581 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     21.201 ms/op
     p(99.9900) =     25.886 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.362 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.009 ms/op
Iteration   1: 3.504 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  18.350 ms/op
                 existUser·p0.9999: 21.291 ms/op
                 existUser·p1.00:   22.479 ms/op

Iteration   2: 3.428 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  20.110 ms/op
                 existUser·p0.9999: 22.249 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   3: 3.582 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 273924
  mean =      3.504 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7148 
    [ 2.500,  5.000) = 258728 
    [ 5.000,  7.500) = 6226 
    [ 7.500, 10.000) = 1236 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     24.092 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.902 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.012 ms/op
Iteration   1: 3.600 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.632 ms/op
                 getUser·p0.999:  18.776 ms/op
                 getUser·p0.9999: 21.004 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   2: 3.598 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.041 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  20.584 ms/op
                 getUser·p0.9999: 22.938 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.590 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  21.887 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266751
  mean =      3.596 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2739 
    [ 2.500,  5.000) = 254162 
    [ 5.000,  7.500) = 8257 
    [ 7.500, 10.000) = 826 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     19.210 ms/op
     p(99.9900) =     24.521 ms/op
     p(99.9990) =     26.192 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.358 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.615 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.265 ±(99.9%) 0.012 ms/op
Iteration   1: 4.263 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   4.166 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  21.393 ms/op
                 listUser·p0.9999: 24.543 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   2: 4.308 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   4.145 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 17.302 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 4.217 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 18.121 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225153
  mean =      4.263 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 211815 
    [ 5.000,  7.500) = 10792 
    [ 7.500, 10.000) = 1714 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      4.121 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     23.740 ms/op
     p(99.9990) =     26.263 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.908 ± 1.646  ops/ms
ClientPb.existUser                       thrpt       3   9.255 ± 2.616  ops/ms
ClientPb.getUser                         thrpt       3   9.126 ± 2.035  ops/ms
ClientPb.listUser                        thrpt       3   7.688 ± 4.757  ops/ms
ClientPb.createUser                       avgt       3   3.532 ± 1.285   ms/op
ClientPb.existUser                        avgt       3   3.470 ± 1.747   ms/op
ClientPb.getUser                          avgt       3   3.545 ± 1.629   ms/op
ClientPb.listUser                         avgt       3   4.237 ± 0.996   ms/op
ClientPb.createUser                     sample  270297   3.551 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.212           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.489           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.136           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.201           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.886           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.999           ms/op
ClientPb.existUser                      sample  273924   3.504 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.027           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.383           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.399           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.652           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.664           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.092           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.592           ms/op
ClientPb.getUser                        sample  266751   3.596 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.128           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.437           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.210           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.521           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.378           ms/op
ClientPb.listUser                       sample  225153   4.263 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.890           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.128           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.725           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.417           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.740           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.345           ms/op
