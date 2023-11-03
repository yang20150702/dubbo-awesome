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
# Warmup Iteration   1: 4.970 ops/ms
# Warmup Iteration   2: 12.027 ops/ms
# Warmup Iteration   3: 12.425 ops/ms
Iteration   1: 12.495 ops/ms
Iteration   2: 12.576 ops/ms
Iteration   3: 12.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.570 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (12.495, 12.570, 12.639), stdev = 0.072
  CI (99.9%): [11.249, 13.891] (assumes normal distribution)


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
# Warmup Iteration   1: 7.870 ops/ms
# Warmup Iteration   2: 12.876 ops/ms
# Warmup Iteration   3: 12.873 ops/ms
Iteration   1: 12.884 ops/ms
Iteration   2: 12.958 ops/ms
Iteration   3: 12.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.938 ±(99.9%) 0.871 ops/ms [Average]
  (min, avg, max) = (12.884, 12.938, 12.973), stdev = 0.048
  CI (99.9%): [12.067, 13.810] (assumes normal distribution)


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
# Warmup Iteration   1: 7.977 ops/ms
# Warmup Iteration   2: 12.457 ops/ms
# Warmup Iteration   3: 12.593 ops/ms
Iteration   1: 12.712 ops/ms
Iteration   2: 12.545 ops/ms
Iteration   3: 12.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.555 ±(99.9%) 2.783 ops/ms [Average]
  (min, avg, max) = (12.407, 12.555, 12.712), stdev = 0.153
  CI (99.9%): [9.772, 15.337] (assumes normal distribution)


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
# Warmup Iteration   1: 6.484 ops/ms
# Warmup Iteration   2: 10.304 ops/ms
# Warmup Iteration   3: 10.395 ops/ms
Iteration   1: 10.220 ops/ms
Iteration   2: 10.450 ops/ms
Iteration   3: 10.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.396 ±(99.9%) 2.846 ops/ms [Average]
  (min, avg, max) = (10.220, 10.396, 10.517), stdev = 0.156
  CI (99.9%): [7.550, 13.242] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.207 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.003 ms/op
Iteration   1: 2.541 ±(99.9%) 0.003 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.528 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.514, 2.528, 2.541), stdev = 0.014
  CI (99.9%): [2.277, 2.779] (assumes normal distribution)


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
# Warmup Iteration   1: 4.051 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.003 ms/op
Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.441 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.425, 2.441, 2.456), stdev = 0.016
  CI (99.9%): [2.155, 2.727] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.004 ms/op
Iteration   1: 2.522 ±(99.9%) 0.003 ms/op
Iteration   2: 2.514 ±(99.9%) 0.003 ms/op
Iteration   3: 2.558 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.531 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.514, 2.531, 2.558), stdev = 0.023
  CI (99.9%): [2.105, 2.957] (assumes normal distribution)


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
# Warmup Iteration   1: 4.867 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.007 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.020 ±(99.9%) 0.248 ms/op [Average]
  (min, avg, max) = (3.006, 3.020, 3.033), stdev = 0.014
  CI (99.9%): [2.772, 3.269] (assumes normal distribution)


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.705 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.167 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  11.454 ms/op
                 createUser·p0.9999: 14.353 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  9.703 ms/op
                 createUser·p0.9999: 12.590 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   3: 2.555 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  8.796 ms/op
                 createUser·p0.9999: 11.394 ms/op
                 createUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377446
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 178954 
    [ 2.500,  3.750) = 193820 
    [ 3.750,  5.000) = 3699 
    [ 5.000,  6.250) = 517 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =     13.525 ms/op
     p(99.9990) =     14.609 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.645 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  7.691 ms/op
                 existUser·p0.9999: 13.928 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.128 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  6.185 ms/op
                 existUser·p0.9999: 12.307 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  8.294 ms/op
                 existUser·p0.9999: 11.928 ms/op
                 existUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385148
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 186645 
    [ 2.500,  3.750) = 194747 
    [ 3.750,  5.000) = 2899 
    [ 5.000,  6.250) = 423 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      6.781 ms/op
     p(99.9900) =     13.394 ms/op
     p(99.9990) =     14.412 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.961 ms/op
                 getUser·p0.999:  7.741 ms/op
                 getUser·p0.9999: 14.206 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  9.876 ms/op
                 getUser·p0.9999: 13.032 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  6.337 ms/op
                 getUser·p0.9999: 11.239 ms/op
                 getUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386168
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 191739 
    [ 2.500,  3.750) = 189560 
    [ 3.750,  5.000) = 3594 
    [ 5.000,  6.250) = 746 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 4.907 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.009 ms/op
Iteration   1: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.965 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.196 ms/op
                 listUser·p0.9999: 10.631 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 10.972 ms/op
                 listUser·p1.00:   12.206 ms/op

Iteration   3: 3.082 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  9.966 ms/op
                 listUser·p0.9999: 11.856 ms/op
                 listUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311562
  mean =      3.079 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 81366 
    [ 2.500,  3.750) = 185333 
    [ 3.750,  5.000) = 36003 
    [ 5.000,  6.250) = 7279 
    [ 6.250,  7.500) = 834 
    [ 7.500,  8.750) = 170 
    [ 8.750, 10.000) = 256 
    [10.000, 11.250) = 167 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.527 ms/op
     p(99.9990) =     12.200 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.570 ± 1.321  ops/ms
ClientPb.existUser                       thrpt       3  12.938 ± 0.871  ops/ms
ClientPb.getUser                         thrpt       3  12.555 ± 2.783  ops/ms
ClientPb.listUser                        thrpt       3  10.396 ± 2.846  ops/ms
ClientPb.createUser                       avgt       3   2.528 ± 0.251   ms/op
ClientPb.existUser                        avgt       3   2.441 ± 0.286   ms/op
ClientPb.getUser                          avgt       3   2.531 ± 0.426   ms/op
ClientPb.listUser                         avgt       3   3.020 ± 0.248   ms/op
ClientPb.createUser                     sample  377446   2.541 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.916           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.847           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.525           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.909           ms/op
ClientPb.existUser                      sample  385148   2.490 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.801           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.585           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.781           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.394           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.615           ms/op
ClientPb.getUser                        sample  386168   2.484 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.672           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.799           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.992           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.221           ms/op
ClientPb.listUser                       sample  311562   3.079 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.879           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.527           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.239           ms/op
