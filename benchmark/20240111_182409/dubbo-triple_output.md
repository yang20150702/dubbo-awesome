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
# Warmup Iteration   1: 5.747 ops/ms
# Warmup Iteration   2: 12.737 ops/ms
# Warmup Iteration   3: 12.797 ops/ms
Iteration   1: 13.018 ops/ms
Iteration   2: 13.002 ops/ms
Iteration   3: 13.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.023 ±(99.9%) 0.434 ops/ms [Average]
  (min, avg, max) = (13.002, 13.023, 13.049), stdev = 0.024
  CI (99.9%): [12.589, 13.457] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.754 ops/ms
# Warmup Iteration   2: 13.623 ops/ms
# Warmup Iteration   3: 13.621 ops/ms
Iteration   1: 13.639 ops/ms
Iteration   2: 13.672 ops/ms
Iteration   3: 13.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.689 ±(99.9%) 1.081 ops/ms [Average]
  (min, avg, max) = (13.639, 13.689, 13.754), stdev = 0.059
  CI (99.9%): [12.607, 14.770] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.503 ops/ms
# Warmup Iteration   2: 13.025 ops/ms
# Warmup Iteration   3: 13.149 ops/ms
Iteration   1: 13.126 ops/ms
Iteration   2: 13.090 ops/ms
Iteration   3: 13.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.110 ±(99.9%) 0.344 ops/ms [Average]
  (min, avg, max) = (13.090, 13.110, 13.126), stdev = 0.019
  CI (99.9%): [12.766, 13.455] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.198 ops/ms
# Warmup Iteration   2: 10.014 ops/ms
# Warmup Iteration   3: 10.323 ops/ms
Iteration   1: 10.385 ops/ms
Iteration   2: 10.372 ops/ms
Iteration   3: 9.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.247 ±(99.9%) 4.152 ops/ms [Average]
  (min, avg, max) = (9.985, 10.247, 10.385), stdev = 0.228
  CI (99.9%): [6.096, 14.399] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
Iteration   1: 2.442 ±(99.9%) 0.004 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.450 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.455 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (2.442, 2.455, 2.472), stdev = 0.016
  CI (99.9%): [2.165, 2.744] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.571 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.359 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.364 ±(99.9%) 0.003 ms/op
Iteration   1: 2.361 ±(99.9%) 0.004 ms/op
Iteration   2: 2.366 ±(99.9%) 0.004 ms/op
Iteration   3: 2.375 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.367 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.361, 2.367, 2.375), stdev = 0.007
  CI (99.9%): [2.241, 2.494] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.011 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
Iteration   1: 2.601 ±(99.9%) 0.008 ms/op
Iteration   2: 2.472 ±(99.9%) 0.010 ms/op
Iteration   3: 2.528 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.534 ±(99.9%) 1.179 ms/op [Average]
  (min, avg, max) = (2.472, 2.534, 2.601), stdev = 0.065
  CI (99.9%): [1.354, 3.713] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.666 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.011 ms/op
Iteration   1: 3.071 ±(99.9%) 0.011 ms/op
Iteration   2: 3.085 ±(99.9%) 0.010 ms/op
Iteration   3: 3.047 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.068 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (3.047, 3.068, 3.085), stdev = 0.019
  CI (99.9%): [2.719, 3.417] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.193 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.790 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.007 ms/op
Iteration   1: 2.563 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.458 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  12.368 ms/op
                 createUser·p0.9999: 14.919 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   2: 2.528 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   3.240 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  11.159 ms/op
                 createUser·p0.9999: 12.911 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   3: 2.635 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.383 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  12.321 ms/op
                 createUser·p0.9999: 19.848 ms/op
                 createUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372627
  mean =      2.574 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181066 
    [ 2.500,  5.000) = 188412 
    [ 5.000,  7.500) = 2376 
    [ 7.500, 10.000) = 302 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =     11.780 ms/op
     p(99.9900) =     18.233 ms/op
     p(99.9990) =     20.048 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.087 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.007 ms/op
Iteration   1: 2.484 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.364 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  12.158 ms/op
                 existUser·p0.9999: 17.727 ms/op
                 existUser·p1.00:   18.514 ms/op

Iteration   2: 2.444 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.391 ms/op
                 existUser·p0.50:   2.396 ms/op
                 existUser·p0.90:   3.150 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  9.678 ms/op
                 existUser·p0.9999: 18.121 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   3: 2.478 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.946 ms/op
                 existUser·p0.9999: 17.501 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388487
  mean =      2.468 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 214984 
    [ 2.500,  5.000) = 171189 
    [ 5.000,  7.500) = 1836 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.364 ms/op
     p(50.0000) =      2.417 ms/op
     p(90.0000) =      3.191 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     17.695 ms/op
     p(99.9990) =     18.685 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.038 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.598 ±(99.9%) 0.008 ms/op
Iteration   1: 2.582 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.128 ms/op
                 getUser·p0.999:  12.164 ms/op
                 getUser·p0.9999: 15.548 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   2: 2.525 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.497 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   3.281 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 18.547 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   3: 2.567 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.501 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.218 ms/op
                 getUser·p0.999:  8.682 ms/op
                 getUser·p0.9999: 13.444 ms/op
                 getUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375010
  mean =      2.558 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 192362 
    [ 2.500,  5.000) = 178806 
    [ 5.000,  7.500) = 3115 
    [ 7.500, 10.000) = 280 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     16.073 ms/op
     p(99.9990) =     20.242 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.739 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.010 ms/op
Iteration   1: 3.005 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.679 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 11.794 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 3.015 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.599 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  10.828 ms/op
                 listUser·p0.9999: 13.126 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 2.961 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.456 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  11.518 ms/op
                 listUser·p0.9999: 14.019 ms/op
                 listUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320459
  mean =      2.994 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 111017 
    [ 2.500,  5.000) = 201013 
    [ 5.000,  7.500) = 7504 
    [ 7.500, 10.000) = 525 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     10.666 ms/op
     p(99.9900) =     13.497 ms/op
     p(99.9990) =     16.239 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.023 ± 0.434  ops/ms
ClientPb.existUser                       thrpt       3  13.689 ± 1.081  ops/ms
ClientPb.getUser                         thrpt       3  13.110 ± 0.344  ops/ms
ClientPb.listUser                        thrpt       3  10.247 ± 4.152  ops/ms
ClientPb.createUser                       avgt       3   2.455 ± 0.290   ms/op
ClientPb.existUser                        avgt       3   2.367 ± 0.126   ms/op
ClientPb.getUser                          avgt       3   2.534 ± 1.179   ms/op
ClientPb.listUser                         avgt       3   3.068 ± 0.349   ms/op
ClientPb.createUser                     sample  372627   2.574 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.383           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.531           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.817           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.780           ms/op
ClientPb.createUser:createUser·p0.9999  sample          18.233           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.152           ms/op
ClientPb.existUser                      sample  388487   2.468 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.364           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.417           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.749           ms/op
ClientPb.existUser:existUser·p0.9999    sample          17.695           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.430           ms/op
ClientPb.getUser                        sample  375010   2.558 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.497           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.030           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.567           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.073           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.249           ms/op
ClientPb.listUser                       sample  320459   2.994 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.456           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.666           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.497           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.282           ms/op
