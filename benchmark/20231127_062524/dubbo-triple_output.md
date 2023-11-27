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
# Warmup Iteration   1: 4.793 ops/ms
# Warmup Iteration   2: 11.573 ops/ms
# Warmup Iteration   3: 12.148 ops/ms
Iteration   1: 12.396 ops/ms
Iteration   2: 12.378 ops/ms
Iteration   3: 12.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.435 ±(99.9%) 1.500 ops/ms [Average]
  (min, avg, max) = (12.378, 12.435, 12.529), stdev = 0.082
  CI (99.9%): [10.935, 13.934] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.516 ops/ms
# Warmup Iteration   2: 12.653 ops/ms
# Warmup Iteration   3: 12.669 ops/ms
Iteration   1: 12.726 ops/ms
Iteration   2: 12.752 ops/ms
Iteration   3: 12.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.710 ±(99.9%) 0.939 ops/ms [Average]
  (min, avg, max) = (12.653, 12.710, 12.752), stdev = 0.051
  CI (99.9%): [11.771, 13.650] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.730 ops/ms
# Warmup Iteration   2: 12.343 ops/ms
# Warmup Iteration   3: 12.401 ops/ms
Iteration   1: 12.335 ops/ms
Iteration   2: 12.476 ops/ms
Iteration   3: 12.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.414 ±(99.9%) 1.315 ops/ms [Average]
  (min, avg, max) = (12.335, 12.414, 12.476), stdev = 0.072
  CI (99.9%): [11.099, 13.730] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.587 ops/ms
# Warmup Iteration   2: 10.054 ops/ms
# Warmup Iteration   3: 10.247 ops/ms
Iteration   1: 10.286 ops/ms
Iteration   2: 10.270 ops/ms
Iteration   3: 10.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.279 ±(99.9%) 0.153 ops/ms [Average]
  (min, avg, max) = (10.270, 10.279, 10.286), stdev = 0.008
  CI (99.9%): [10.126, 10.432] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.137 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.654 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.595 ±(99.9%) 0.004 ms/op
Iteration   1: 2.679 ±(99.9%) 0.004 ms/op
Iteration   2: 2.591 ±(99.9%) 0.003 ms/op
Iteration   3: 2.642 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.638 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (2.591, 2.638, 2.679), stdev = 0.044
  CI (99.9%): [1.833, 3.442] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.880 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.498 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.492, 2.498, 2.509), stdev = 0.009
  CI (99.9%): [2.335, 2.662] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.914 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.669 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.004 ms/op
Iteration   1: 2.555 ±(99.9%) 0.005 ms/op
Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
Iteration   3: 2.570 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.568 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (2.555, 2.568, 2.580), stdev = 0.013
  CI (99.9%): [2.333, 2.803] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.730 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 3.085 ±(99.9%) 0.005 ms/op
Iteration   2: 3.059 ±(99.9%) 0.004 ms/op
Iteration   3: 3.064 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.069 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (3.059, 3.069, 3.085), stdev = 0.014
  CI (99.9%): [2.823, 3.316] (assumes normal distribution)


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.724 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.609 ±(99.9%) 0.006 ms/op
Iteration   1: 2.603 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   4.157 ms/op
                 createUser·p0.999:  12.288 ms/op
                 createUser·p0.9999: 14.334 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 2.576 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  9.616 ms/op
                 createUser·p0.9999: 13.936 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   3: 2.587 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  8.822 ms/op
                 createUser·p0.9999: 10.726 ms/op
                 createUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370424
  mean =      2.589 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 175941 
    [ 2.500,  3.750) = 188791 
    [ 3.750,  5.000) = 4436 
    [ 5.000,  6.250) = 721 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 140 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 79 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      4.018 ms/op
     p(99.9000) =      9.086 ms/op
     p(99.9900) =     14.105 ms/op
     p(99.9990) =     14.718 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.590 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  7.870 ms/op
                 existUser·p0.9999: 13.979 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  5.374 ms/op
                 existUser·p0.9999: 15.275 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.248 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  5.947 ms/op
                 existUser·p0.9999: 11.933 ms/op
                 existUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382357
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 187920 
    [ 2.500,  3.750) = 189448 
    [ 3.750,  5.000) = 3987 
    [ 5.000,  6.250) = 585 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      5.915 ms/op
     p(99.9900) =     14.172 ms/op
     p(99.9990) =     15.549 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.006 ms/op
Iteration   1: 2.577 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  12.812 ms/op
                 getUser·p0.9999: 14.837 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  10.135 ms/op
                 getUser·p0.9999: 13.264 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.593 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.162 ms/op
                 getUser·p0.95:   3.338 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  9.481 ms/op
                 getUser·p0.9999: 12.299 ms/op
                 getUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 371528
  mean =      2.581 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 179281 
    [ 2.500,  3.750) = 186021 
    [ 3.750,  5.000) = 4870 
    [ 5.000,  6.250) = 707 
    [ 6.250,  7.500) = 166 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 80 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.142 ms/op
     p(95.0000) =      3.281 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     14.546 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.958 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.009 ms/op
Iteration   1: 3.100 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  9.582 ms/op
                 listUser·p0.9999: 11.486 ms/op
                 listUser·p1.00:   12.714 ms/op

Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   5.948 ms/op
                 listUser·p0.999:  10.174 ms/op
                 listUser·p0.9999: 12.511 ms/op
                 listUser·p1.00:   13.058 ms/op

Iteration   3: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.973 ms/op
                 listUser·p0.9999: 11.576 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310856
  mean =      3.086 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 77501 
    [ 2.500,  3.750) = 188208 
    [ 3.750,  5.000) = 36763 
    [ 5.000,  6.250) = 6444 
    [ 6.250,  7.500) = 1031 
    [ 7.500,  8.750) = 272 
    [ 8.750, 10.000) = 219 
    [10.000, 11.250) = 239 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.787 ms/op
     p(99.9000) =      9.978 ms/op
     p(99.9900) =     11.600 ms/op
     p(99.9990) =     12.911 ms/op
     p(99.9999) =     13.058 ms/op
    p(100.0000) =     13.058 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.435 ± 1.500  ops/ms
ClientPb.existUser                       thrpt       3  12.710 ± 0.939  ops/ms
ClientPb.getUser                         thrpt       3  12.414 ± 1.315  ops/ms
ClientPb.listUser                        thrpt       3  10.279 ± 0.153  ops/ms
ClientPb.createUser                       avgt       3   2.638 ± 0.805   ms/op
ClientPb.existUser                        avgt       3   2.498 ± 0.164   ms/op
ClientPb.getUser                          avgt       3   2.568 ± 0.235   ms/op
ClientPb.listUser                         avgt       3   3.069 ± 0.247   ms/op
ClientPb.createUser                     sample  370424   2.589 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.861           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.086           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.105           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.746           ms/op
ClientPb.existUser                      sample  382357   2.508 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.839           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.915           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.172           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.778           ms/op
ClientPb.getUser                        sample  371528   2.581 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.783           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.601           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.683           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.546           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.303           ms/op
ClientPb.listUser                       sample  310856   3.086 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.826           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.787           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.978           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.058           ms/op
