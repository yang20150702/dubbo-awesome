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
# Warmup Iteration   1: 2.123 ops/ms
# Warmup Iteration   2: 5.605 ops/ms
# Warmup Iteration   3: 8.269 ops/ms
Iteration   1: 9.033 ops/ms
Iteration   2: 9.090 ops/ms
Iteration   3: 9.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.054 ±(99.9%) 0.582 ops/ms [Average]
  (min, avg, max) = (9.033, 9.054, 9.090), stdev = 0.032
  CI (99.9%): [8.472, 9.636] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.816 ops/ms
# Warmup Iteration   2: 8.476 ops/ms
# Warmup Iteration   3: 9.297 ops/ms
Iteration   1: 9.587 ops/ms
Iteration   2: 9.629 ops/ms
Iteration   3: 9.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.600 ±(99.9%) 0.451 ops/ms [Average]
  (min, avg, max) = (9.585, 9.600, 9.629), stdev = 0.025
  CI (99.9%): [9.149, 10.051] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.615 ops/ms
# Warmup Iteration   2: 8.333 ops/ms
# Warmup Iteration   3: 9.012 ops/ms
Iteration   1: 9.053 ops/ms
Iteration   2: 9.165 ops/ms
Iteration   3: 9.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.090 ±(99.9%) 1.182 ops/ms [Average]
  (min, avg, max) = (9.051, 9.090, 9.165), stdev = 0.065
  CI (99.9%): [7.908, 10.272] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.583 ops/ms
# Warmup Iteration   2: 6.884 ops/ms
# Warmup Iteration   3: 7.484 ops/ms
Iteration   1: 7.600 ops/ms
Iteration   2: 7.593 ops/ms
Iteration   3: 7.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.606 ±(99.9%) 0.308 ops/ms [Average]
  (min, avg, max) = (7.593, 7.606, 7.625), stdev = 0.017
  CI (99.9%): [7.298, 7.914] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.955 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.005 ms/op
Iteration   1: 3.541 ±(99.9%) 0.004 ms/op
Iteration   2: 3.599 ±(99.9%) 0.002 ms/op
Iteration   3: 3.494 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.545 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (3.494, 3.545, 3.599), stdev = 0.053
  CI (99.9%): [2.583, 4.507] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.103 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.003 ms/op
Iteration   1: 3.388 ±(99.9%) 0.005 ms/op
Iteration   2: 3.427 ±(99.9%) 0.003 ms/op
Iteration   3: 3.386 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.400 ±(99.9%) 0.418 ms/op [Average]
  (min, avg, max) = (3.386, 3.400, 3.427), stdev = 0.023
  CI (99.9%): [2.982, 3.819] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.123 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.004 ms/op
Iteration   1: 3.512 ±(99.9%) 0.006 ms/op
Iteration   2: 3.451 ±(99.9%) 0.004 ms/op
Iteration   3: 3.593 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.519 ±(99.9%) 1.299 ms/op [Average]
  (min, avg, max) = (3.451, 3.519, 3.593), stdev = 0.071
  CI (99.9%): [2.219, 4.818] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.139 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.375 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.244 ±(99.9%) 0.007 ms/op
Iteration   1: 4.288 ±(99.9%) 0.006 ms/op
Iteration   2: 4.201 ±(99.9%) 0.007 ms/op
Iteration   3: 4.283 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.257 ±(99.9%) 0.895 ms/op [Average]
  (min, avg, max) = (4.201, 4.257, 4.288), stdev = 0.049
  CI (99.9%): [3.362, 5.153] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.606 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.015 ms/op
Iteration   1: 3.546 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  22.341 ms/op
                 createUser·p0.9999: 24.870 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   2: 3.525 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  24.248 ms/op
                 createUser·p0.9999: 26.750 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   3: 3.516 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  20.087 ms/op
                 createUser·p0.9999: 28.671 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271961
  mean =      3.529 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3489 
    [ 2.500,  5.000) = 263501 
    [ 5.000,  7.500) = 3811 
    [ 7.500, 10.000) = 578 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 92 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     20.515 ms/op
     p(99.9900) =     27.781 ms/op
     p(99.9990) =     29.084 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.765 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.610 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.007 ms/op
Iteration   1: 3.381 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  20.322 ms/op
                 existUser·p0.9999: 23.283 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   2: 3.380 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  22.560 ms/op
                 existUser·p0.9999: 26.951 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   3: 3.468 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  18.186 ms/op
                 existUser·p0.9999: 27.420 ms/op
                 existUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281403
  mean =      3.409 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6289 
    [ 2.500,  5.000) = 269766 
    [ 5.000,  7.500) = 4260 
    [ 7.500, 10.000) = 475 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     18.566 ms/op
     p(99.9900) =     26.603 ms/op
     p(99.9990) =     28.248 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.032 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.009 ms/op
Iteration   1: 3.737 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   5.890 ms/op
                 getUser·p0.99:   8.151 ms/op
                 getUser·p0.999:  22.282 ms/op
                 getUser·p0.9999: 25.705 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   2: 3.638 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  24.454 ms/op
                 getUser·p0.9999: 29.098 ms/op
                 getUser·p1.00:   29.557 ms/op

Iteration   3: 3.598 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.068 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.527 ms/op
                 getUser·p0.999:  20.461 ms/op
                 getUser·p0.9999: 28.544 ms/op
                 getUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 262360
  mean =      3.656 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1645 
    [ 2.500,  5.000) = 250424 
    [ 5.000,  7.500) = 7632 
    [ 7.500, 10.000) = 1851 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 101 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     21.943 ms/op
     p(99.9900) =     28.263 ms/op
     p(99.9990) =     29.438 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 11.139 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.555 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.012 ms/op
Iteration   1: 4.224 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.567 ms/op
                 listUser·p0.999:  18.800 ms/op
                 listUser·p0.9999: 21.342 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   2: 4.263 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   4.137 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.439 ms/op
                 listUser·p0.999:  16.253 ms/op
                 listUser·p0.9999: 17.826 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 4.133 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228030
  mean =      4.206 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 218399 
    [ 5.000,  7.500) = 7605 
    [ 7.500, 10.000) = 1214 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     16.023 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     21.792 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.054 ± 0.582  ops/ms
ClientPb.existUser                       thrpt       3   9.600 ± 0.451  ops/ms
ClientPb.getUser                         thrpt       3   9.090 ± 1.182  ops/ms
ClientPb.listUser                        thrpt       3   7.606 ± 0.308  ops/ms
ClientPb.createUser                       avgt       3   3.545 ± 0.962   ms/op
ClientPb.existUser                        avgt       3   3.400 ± 0.418   ms/op
ClientPb.getUser                          avgt       3   3.519 ± 1.299   ms/op
ClientPb.listUser                         avgt       3   4.257 ± 0.895   ms/op
ClientPb.createUser                     sample  271961   3.529 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.126           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.432           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.515           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.781           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.426           ms/op
ClientPb.existUser                      sample  281403   3.409 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.959           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.833           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.566           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.603           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.770           ms/op
ClientPb.getUser                        sample  262360   3.656 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.959           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.943           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.263           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.557           ms/op
ClientPb.listUser                       sample  228030   4.206 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.894           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.023           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.546           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.020           ms/op
