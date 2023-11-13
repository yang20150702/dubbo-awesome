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
# Warmup Iteration   1: 4.596 ops/ms
# Warmup Iteration   2: 11.490 ops/ms
# Warmup Iteration   3: 11.811 ops/ms
Iteration   1: 12.336 ops/ms
Iteration   2: 12.391 ops/ms
Iteration   3: 12.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.400 ±(99.9%) 1.252 ops/ms [Average]
  (min, avg, max) = (12.336, 12.400, 12.472), stdev = 0.069
  CI (99.9%): [11.147, 13.652] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.589 ops/ms
# Warmup Iteration   2: 12.662 ops/ms
# Warmup Iteration   3: 12.686 ops/ms
Iteration   1: 12.802 ops/ms
Iteration   2: 12.762 ops/ms
Iteration   3: 12.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.801 ±(99.9%) 0.707 ops/ms [Average]
  (min, avg, max) = (12.762, 12.801, 12.839), stdev = 0.039
  CI (99.9%): [12.094, 13.508] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.123 ops/ms
# Warmup Iteration   2: 12.134 ops/ms
# Warmup Iteration   3: 12.469 ops/ms
Iteration   1: 12.525 ops/ms
Iteration   2: 12.569 ops/ms
Iteration   3: 12.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.542 ±(99.9%) 0.424 ops/ms [Average]
  (min, avg, max) = (12.525, 12.542, 12.569), stdev = 0.023
  CI (99.9%): [12.118, 12.966] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.296 ops/ms
# Warmup Iteration   2: 10.237 ops/ms
# Warmup Iteration   3: 10.311 ops/ms
Iteration   1: 10.212 ops/ms
Iteration   2: 10.263 ops/ms
Iteration   3: 10.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.295 ±(99.9%) 1.861 ops/ms [Average]
  (min, avg, max) = (10.212, 10.295, 10.409), stdev = 0.102
  CI (99.9%): [8.433, 12.156] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.059 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.669 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.582 ±(99.9%) 0.004 ms/op
Iteration   1: 2.565 ±(99.9%) 0.003 ms/op
Iteration   2: 2.607 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.578 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (2.560, 2.578, 2.607), stdev = 0.026
  CI (99.9%): [2.108, 3.047] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.991 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.003 ms/op
Iteration   1: 2.522 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
Iteration   3: 2.537 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.518 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (2.497, 2.518, 2.537), stdev = 0.020
  CI (99.9%): [2.145, 2.892] (assumes normal distribution)


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
Iteration   3: 2.512 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.529 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.512, 2.529, 2.556), stdev = 0.023
  CI (99.9%): [2.103, 2.956] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.006 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
Iteration   2: 3.116 ±(99.9%) 0.005 ms/op
Iteration   3: 3.128 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.115 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (3.103, 3.115, 3.128), stdev = 0.013
  CI (99.9%): [2.887, 3.344] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.402 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.720 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.606 ±(99.9%) 0.006 ms/op
Iteration   1: 2.637 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   2.691 ms/op
                 createUser·p0.90:   3.203 ms/op
                 createUser·p0.95:   3.351 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  12.337 ms/op
                 createUser·p0.9999: 14.039 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 2.596 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.703 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  9.617 ms/op
                 createUser·p0.9999: 12.976 ms/op
                 createUser·p1.00:   13.763 ms/op

Iteration   3: 2.591 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  9.308 ms/op
                 createUser·p0.9999: 12.080 ms/op
                 createUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 367875
  mean =      2.608 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 174352 
    [ 2.500,  3.750) = 188437 
    [ 3.750,  5.000) = 3965 
    [ 5.000,  6.250) = 582 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.691 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.289 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     14.188 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.642 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.887 ms/op
                 existUser·p0.999:  11.913 ms/op
                 existUser·p0.9999: 14.327 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  5.753 ms/op
                 existUser·p0.9999: 12.708 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.638 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.201 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  8.641 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 377722
  mean =      2.539 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 181906 
    [ 2.500,  3.750) = 191839 
    [ 3.750,  5.000) = 2907 
    [ 5.000,  6.250) = 640 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      6.611 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.462 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.595 ±(99.9%) 0.006 ms/op
Iteration   1: 2.563 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  12.234 ms/op
                 getUser·p0.9999: 14.906 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  10.203 ms/op
                 getUser·p0.9999: 14.837 ms/op
                 getUser·p1.00:   15.598 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  5.571 ms/op
                 getUser·p0.9999: 10.869 ms/op
                 getUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374371
  mean =      2.562 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 181281 
    [ 2.500,  3.750) = 188000 
    [ 3.750,  5.000) = 4000 
    [ 5.000,  6.250) = 654 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      6.485 ms/op
     p(99.9900) =     14.713 ms/op
     p(99.9990) =     15.573 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 4.877 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.009 ms/op
Iteration   1: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.773 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.515 ms/op
                 listUser·p0.9999: 11.966 ms/op
                 listUser·p1.00:   12.435 ms/op

Iteration   2: 3.070 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  10.024 ms/op
                 listUser·p0.9999: 11.806 ms/op
                 listUser·p1.00:   12.354 ms/op

Iteration   3: 3.081 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.773 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 10.949 ms/op
                 listUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312201
  mean =      3.073 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 79372 
    [ 2.500,  3.750) = 189395 
    [ 3.750,  5.000) = 35806 
    [ 5.000,  6.250) = 5968 
    [ 6.250,  7.500) = 831 
    [ 7.500,  8.750) = 179 
    [ 8.750, 10.000) = 277 
    [10.000, 11.250) = 190 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.614 ms/op
     p(99.9900) =     11.600 ms/op
     p(99.9990) =     12.354 ms/op
     p(99.9999) =     12.435 ms/op
    p(100.0000) =     12.435 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.400 ± 1.252  ops/ms
ClientPb.existUser                       thrpt       3  12.801 ± 0.707  ops/ms
ClientPb.getUser                         thrpt       3  12.542 ± 0.424  ops/ms
ClientPb.listUser                        thrpt       3  10.295 ± 1.861  ops/ms
ClientPb.createUser                       avgt       3   2.578 ± 0.470   ms/op
ClientPb.existUser                        avgt       3   2.518 ± 0.374   ms/op
ClientPb.getUser                          avgt       3   2.529 ± 0.426   ms/op
ClientPb.listUser                         avgt       3   3.115 ± 0.228   ms/op
ClientPb.createUser                     sample  367875   2.608 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.582           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.691           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.289           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.585           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.763           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.664           ms/op
ClientPb.existUser                      sample  377722   2.539 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.840           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.621           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.611           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.713           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.582           ms/op
ClientPb.getUser                        sample  374371   2.562 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.736           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.589           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.485           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.713           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.712           ms/op
ClientPb.listUser                       sample  312201   3.073 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.773           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.614           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.435           ms/op
