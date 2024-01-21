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
# Warmup Iteration   1: 4.775 ops/ms
# Warmup Iteration   2: 11.953 ops/ms
# Warmup Iteration   3: 12.302 ops/ms
Iteration   1: 12.513 ops/ms
Iteration   2: 12.747 ops/ms
Iteration   3: 12.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.618 ±(99.9%) 2.167 ops/ms [Average]
  (min, avg, max) = (12.513, 12.618, 12.747), stdev = 0.119
  CI (99.9%): [10.451, 14.786] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.552 ops/ms
# Warmup Iteration   2: 13.280 ops/ms
# Warmup Iteration   3: 13.295 ops/ms
Iteration   1: 13.153 ops/ms
Iteration   2: 13.230 ops/ms
Iteration   3: 13.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.245 ±(99.9%) 1.847 ops/ms [Average]
  (min, avg, max) = (13.153, 13.245, 13.353), stdev = 0.101
  CI (99.9%): [11.398, 15.092] (assumes normal distribution)


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
# Warmup Iteration   1: 8.148 ops/ms
# Warmup Iteration   2: 12.604 ops/ms
# Warmup Iteration   3: 12.851 ops/ms
Iteration   1: 12.913 ops/ms
Iteration   2: 12.746 ops/ms
Iteration   3: 12.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.783 ±(99.9%) 2.114 ops/ms [Average]
  (min, avg, max) = (12.691, 12.783, 12.913), stdev = 0.116
  CI (99.9%): [10.669, 14.897] (assumes normal distribution)


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
# Warmup Iteration   1: 6.649 ops/ms
# Warmup Iteration   2: 10.576 ops/ms
# Warmup Iteration   3: 10.542 ops/ms
Iteration   1: 10.687 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.625 ±(99.9%) 0.995 ops/ms [Average]
  (min, avg, max) = (10.583, 10.625, 10.687), stdev = 0.055
  CI (99.9%): [9.630, 11.620] (assumes normal distribution)


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.536 ±(99.9%) 0.325 ms/op [Average]
  (min, avg, max) = (2.519, 2.536, 2.555), stdev = 0.018
  CI (99.9%): [2.211, 2.860] (assumes normal distribution)


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
# Warmup Iteration   1: 3.747 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.003 ms/op
Iteration   2: 2.462 ±(99.9%) 0.003 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.464 ±(99.9%) 0.046 ms/op [Average]
  (min, avg, max) = (2.462, 2.464, 2.467), stdev = 0.003
  CI (99.9%): [2.418, 2.510] (assumes normal distribution)


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.472 ±(99.9%) 0.004 ms/op
Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
Iteration   3: 2.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.456 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (2.436, 2.456, 2.472), stdev = 0.018
  CI (99.9%): [2.129, 2.783] (assumes normal distribution)


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
# Warmup Iteration   1: 4.789 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.005 ms/op
Iteration   1: 3.013 ±(99.9%) 0.005 ms/op
Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
Iteration   3: 3.040 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.021 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (3.011, 3.021, 3.040), stdev = 0.016
  CI (99.9%): [2.723, 3.320] (assumes normal distribution)


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
# Warmup Iteration   1: 4.271 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.580 ±(99.9%) 0.005 ms/op
Iteration   1: 2.606 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.174 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   3.958 ms/op
                 createUser·p0.999:  12.031 ms/op
                 createUser·p0.9999: 14.655 ms/op
                 createUser·p1.00:   15.270 ms/op

Iteration   2: 2.603 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.166 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   3.841 ms/op
                 createUser·p0.999:  9.377 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   3: 2.605 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 10.645 ms/op
                 createUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 368164
  mean =      2.605 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 174553 
    [ 2.500,  3.750) = 188480 
    [ 3.750,  5.000) = 4031 
    [ 5.000,  6.250) = 536 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.170 ms/op
     p(95.0000) =      3.297 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     14.767 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  11.092 ms/op
                 existUser·p0.9999: 13.631 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  5.664 ms/op
                 existUser·p0.9999: 15.106 ms/op
                 existUser·p1.00:   15.286 ms/op

Iteration   3: 2.587 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.012 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.322 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  9.347 ms/op
                 existUser·p0.9999: 12.610 ms/op
                 existUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 378775
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 184841 
    [ 2.500,  3.750) = 188976 
    [ 3.750,  5.000) = 3821 
    [ 5.000,  6.250) = 620 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      7.645 ms/op
     p(99.9900) =     13.781 ms/op
     p(99.9990) =     15.208 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.585 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.236 ms/op
                 getUser·p0.999:  11.649 ms/op
                 getUser·p0.9999: 14.658 ms/op
                 getUser·p1.00:   15.581 ms/op

Iteration   2: 2.630 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   2.650 ms/op
                 getUser·p0.90:   3.199 ms/op
                 getUser·p0.95:   3.416 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.278 ms/op
                 getUser·p0.9999: 13.987 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   3: 2.589 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.981 ms/op
                 getUser·p0.999:  8.536 ms/op
                 getUser·p0.9999: 12.113 ms/op
                 getUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 368782
  mean =      2.601 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 176640 
    [ 2.500,  3.750) = 184508 
    [ 3.750,  5.000) = 5509 
    [ 5.000,  6.250) = 1462 
    [ 6.250,  7.500) = 201 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.310 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     14.276 ms/op
     p(99.9990) =     15.516 ms/op
     p(99.9999) =     15.581 ms/op
    p(100.0000) =     15.581 ms/op


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
# Warmup Iteration   1: 5.129 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.009 ms/op
Iteration   1: 3.098 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.864 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  9.616 ms/op
                 listUser·p0.9999: 12.059 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   2: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.681 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.837 ms/op
                 listUser·p0.9999: 11.944 ms/op
                 listUser·p1.00:   13.107 ms/op

Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 11.017 ms/op
                 listUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314096
  mean =      3.052 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 86519 
    [ 2.500,  3.750) = 184487 
    [ 3.750,  5.000) = 34503 
    [ 5.000,  6.250) = 6846 
    [ 6.250,  7.500) = 940 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 245 
    [10.000, 11.250) = 161 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      9.468 ms/op
     p(99.9900) =     11.914 ms/op
     p(99.9990) =     13.089 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.618 ± 2.167  ops/ms
ClientPb.existUser                       thrpt       3  13.245 ± 1.847  ops/ms
ClientPb.getUser                         thrpt       3  12.783 ± 2.114  ops/ms
ClientPb.listUser                        thrpt       3  10.625 ± 0.995  ops/ms
ClientPb.createUser                       avgt       3   2.536 ± 0.325   ms/op
ClientPb.existUser                        avgt       3   2.464 ± 0.046   ms/op
ClientPb.getUser                          avgt       3   2.456 ± 0.327   ms/op
ClientPb.listUser                         avgt       3   3.021 ± 0.298   ms/op
ClientPb.createUser                     sample  368164   2.605 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.838           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.763           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.270           ms/op
ClientPb.existUser                      sample  378775   2.531 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.895           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.645           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.781           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.286           ms/op
ClientPb.getUser                        sample  368782   2.601 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.855           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.613           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.471           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.276           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.581           ms/op
ClientPb.listUser                       sample  314096   3.052 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.681           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.468           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.914           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.219           ms/op
