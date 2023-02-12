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
# Warmup Iteration   1: 2.757 ops/ms
# Warmup Iteration   2: 6.120 ops/ms
# Warmup Iteration   3: 9.410 ops/ms
Iteration   1: 9.864 ops/ms
Iteration   2: 10.167 ops/ms
Iteration   3: 9.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.910 ±(99.9%) 4.328 ops/ms [Average]
  (min, avg, max) = (9.700, 9.910, 10.167), stdev = 0.237
  CI (99.9%): [5.582, 14.238] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.645 ops/ms
# Warmup Iteration   2: 9.621 ops/ms
# Warmup Iteration   3: 9.837 ops/ms
Iteration   1: 10.474 ops/ms
Iteration   2: 10.534 ops/ms
Iteration   3: 10.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.392 ±(99.9%) 3.579 ops/ms [Average]
  (min, avg, max) = (10.168, 10.392, 10.534), stdev = 0.196
  CI (99.9%): [6.813, 13.971] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.582 ops/ms
# Warmup Iteration   2: 9.155 ops/ms
# Warmup Iteration   3: 9.614 ops/ms
Iteration   1: 10.290 ops/ms
Iteration   2: 10.277 ops/ms
Iteration   3: 10.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.257 ±(99.9%) 0.852 ops/ms [Average]
  (min, avg, max) = (10.203, 10.257, 10.290), stdev = 0.047
  CI (99.9%): [9.405, 11.108] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.556 ops/ms
# Warmup Iteration   2: 7.770 ops/ms
# Warmup Iteration   3: 8.455 ops/ms
Iteration   1: 8.607 ops/ms
Iteration   2: 8.568 ops/ms
Iteration   3: 8.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.603 ±(99.9%) 0.594 ops/ms [Average]
  (min, avg, max) = (8.568, 8.603, 8.633), stdev = 0.033
  CI (99.9%): [8.009, 9.197] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.046 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.003 ms/op
Iteration   1: 3.173 ±(99.9%) 0.008 ms/op
Iteration   2: 3.207 ±(99.9%) 0.006 ms/op
Iteration   3: 3.137 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.173 ±(99.9%) 0.636 ms/op [Average]
  (min, avg, max) = (3.137, 3.173, 3.207), stdev = 0.035
  CI (99.9%): [2.537, 3.808] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.345 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.002 ms/op
Iteration   1: 3.184 ±(99.9%) 0.004 ms/op
Iteration   2: 3.083 ±(99.9%) 0.002 ms/op
Iteration   3: 3.117 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.128 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (3.083, 3.128, 3.184), stdev = 0.051
  CI (99.9%): [2.192, 4.064] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.450 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.006 ms/op
Iteration   1: 3.159 ±(99.9%) 0.002 ms/op
Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
Iteration   3: 3.053 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.134 ±(99.9%) 1.303 ms/op [Average]
  (min, avg, max) = (3.053, 3.134, 3.189), stdev = 0.071
  CI (99.9%): [1.831, 4.437] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.481 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.006 ms/op
Iteration   1: 3.721 ±(99.9%) 0.009 ms/op
Iteration   2: 3.670 ±(99.9%) 0.008 ms/op
Iteration   3: 3.675 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.689 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.670, 3.689, 3.721), stdev = 0.028
  CI (99.9%): [3.179, 4.198] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.116 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.010 ms/op
Iteration   1: 3.132 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  14.015 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 3.140 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.492 ms/op
                 createUser·p0.999:  19.464 ms/op
                 createUser·p0.9999: 28.260 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  15.942 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302841
  mean =      3.170 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23511 
    [ 2.500,  5.000) = 274423 
    [ 5.000,  7.500) = 3992 
    [ 7.500, 10.000) = 479 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     17.082 ms/op
     p(99.9900) =     25.587 ms/op
     p(99.9990) =     28.705 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.514 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.326 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
Iteration   1: 3.031 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  9.454 ms/op
                 existUser·p0.9999: 19.329 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   2: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  9.692 ms/op
                 existUser·p0.9999: 23.101 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.363 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  11.813 ms/op
                 existUser·p0.9999: 21.463 ms/op
                 existUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 317610
  mean =      3.021 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15707 
    [ 2.500,  5.000) = 297591 
    [ 5.000,  7.500) = 3531 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.269 ms/op
     p(95.0000) =      3.502 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     10.830 ms/op
     p(99.9900) =     21.872 ms/op
     p(99.9990) =     23.892 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.547 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.009 ms/op
Iteration   1: 3.428 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  18.007 ms/op
                 getUser·p0.9999: 20.808 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   2: 3.116 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  12.370 ms/op
                 getUser·p0.9999: 22.929 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.077 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  13.566 ms/op
                 getUser·p0.9999: 21.801 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292493
  mean =      3.279 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20285 
    [ 2.500,  5.000) = 264565 
    [ 5.000,  7.500) = 6605 
    [ 7.500, 10.000) = 606 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 153 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     14.724 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     23.303 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.909 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.011 ms/op
Iteration   1: 3.649 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.595 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  17.247 ms/op
                 listUser·p0.9999: 22.872 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   2: 3.734 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.036 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.695 ms/op
                 listUser·p0.9999: 15.630 ms/op
                 listUser·p1.00:   16.318 ms/op

Iteration   3: 3.820 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.326 ms/op
                 listUser·p0.9999: 15.172 ms/op
                 listUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257023
  mean =      3.733 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 250373 
    [ 5.000,  7.500) = 4789 
    [ 7.500, 10.000) = 1135 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.595 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     21.178 ms/op
     p(99.9990) =     23.907 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.910 ± 4.328  ops/ms
ClientPb.existUser                       thrpt       3  10.392 ± 3.579  ops/ms
ClientPb.getUser                         thrpt       3  10.257 ± 0.852  ops/ms
ClientPb.listUser                        thrpt       3   8.603 ± 0.594  ops/ms
ClientPb.createUser                       avgt       3   3.173 ± 0.636   ms/op
ClientPb.existUser                        avgt       3   3.128 ± 0.936   ms/op
ClientPb.getUser                          avgt       3   3.134 ± 1.303   ms/op
ClientPb.listUser                         avgt       3   3.689 ± 0.510   ms/op
ClientPb.createUser                     sample  302841   3.170 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.974           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.082           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.587           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.032           ms/op
ClientPb.existUser                      sample  317610   3.021 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.998           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.830           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.872           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.953           ms/op
ClientPb.getUser                        sample  292493   3.279 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.716           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.291           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.724           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.151           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.495           ms/op
ClientPb.listUser                       sample  257023   3.733 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.595           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.742           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.976           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.178           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.183           ms/op
