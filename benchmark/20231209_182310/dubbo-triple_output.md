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
# Warmup Iteration   1: 4.827 ops/ms
# Warmup Iteration   2: 12.087 ops/ms
# Warmup Iteration   3: 12.274 ops/ms
Iteration   1: 12.572 ops/ms
Iteration   2: 12.795 ops/ms
Iteration   3: 12.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.698 ±(99.9%) 2.082 ops/ms [Average]
  (min, avg, max) = (12.572, 12.698, 12.795), stdev = 0.114
  CI (99.9%): [10.616, 14.780] (assumes normal distribution)


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
# Warmup Iteration   1: 8.134 ops/ms
# Warmup Iteration   2: 13.099 ops/ms
# Warmup Iteration   3: 13.085 ops/ms
Iteration   1: 13.094 ops/ms
Iteration   2: 13.151 ops/ms
Iteration   3: 13.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.102 ±(99.9%) 0.816 ops/ms [Average]
  (min, avg, max) = (13.062, 13.102, 13.151), stdev = 0.045
  CI (99.9%): [12.286, 13.918] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.075 ops/ms
# Warmup Iteration   2: 12.973 ops/ms
# Warmup Iteration   3: 13.027 ops/ms
Iteration   1: 13.042 ops/ms
Iteration   2: 12.967 ops/ms
Iteration   3: 13.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.031 ±(99.9%) 1.073 ops/ms [Average]
  (min, avg, max) = (12.967, 13.031, 13.083), stdev = 0.059
  CI (99.9%): [11.958, 14.104] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.738 ops/ms
# Warmup Iteration   2: 10.716 ops/ms
# Warmup Iteration   3: 10.721 ops/ms
Iteration   1: 10.758 ops/ms
Iteration   2: 10.832 ops/ms
Iteration   3: 10.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.753 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (10.671, 10.753, 10.832), stdev = 0.081
  CI (99.9%): [9.280, 12.227] (assumes normal distribution)


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.471 ±(99.9%) 0.003 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (2.471, 2.495, 2.540), stdev = 0.039
  CI (99.9%): [1.783, 3.208] (assumes normal distribution)


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
# Warmup Iteration   1: 3.685 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.004 ms/op
Iteration   1: 2.421 ±(99.9%) 0.003 ms/op
Iteration   2: 2.420 ±(99.9%) 0.003 ms/op
Iteration   3: 2.433 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.425 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (2.420, 2.425, 2.433), stdev = 0.007
  CI (99.9%): [2.289, 2.561] (assumes normal distribution)


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.471 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.447, 2.471, 2.487), stdev = 0.021
  CI (99.9%): [2.083, 2.860] (assumes normal distribution)


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
# Warmup Iteration   1: 4.679 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.005 ms/op
Iteration   2: 2.946 ±(99.9%) 0.004 ms/op
Iteration   3: 2.970 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.963 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.946, 2.963, 2.974), stdev = 0.015
  CI (99.9%): [2.691, 3.236] (assumes normal distribution)


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
# Warmup Iteration   1: 4.227 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.495 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  10.426 ms/op
                 createUser·p0.9999: 14.896 ms/op
                 createUser·p1.00:   15.729 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  6.453 ms/op
                 createUser·p0.9999: 12.157 ms/op
                 createUser·p1.00:   12.632 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  8.258 ms/op
                 createUser·p0.9999: 11.750 ms/op
                 createUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385961
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 187671 
    [ 2.500,  3.750) = 194374 
    [ 3.750,  5.000) = 2805 
    [ 5.000,  6.250) = 536 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.258 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     15.043 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


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
# Warmup Iteration   1: 3.842 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  5.723 ms/op
                 existUser·p0.9999: 14.009 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  6.283 ms/op
                 existUser·p0.9999: 13.556 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  9.188 ms/op
                 existUser·p0.9999: 17.510 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385748
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189847 
    [ 2.500,  5.000) = 195193 
    [ 5.000,  7.500) = 341 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      7.000 ms/op
     p(99.9900) =     14.130 ms/op
     p(99.9990) =     18.972 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.504 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.108 ms/op
                 getUser·p0.999:  11.085 ms/op
                 getUser·p0.9999: 16.060 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.825 ms/op
                 getUser·p0.999:  10.081 ms/op
                 getUser·p0.9999: 14.870 ms/op
                 getUser·p1.00:   15.368 ms/op

Iteration   3: 2.576 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.162 ms/op
                 getUser·p0.95:   3.342 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  8.549 ms/op
                 getUser·p0.9999: 12.042 ms/op
                 getUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377520
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 183589 
    [ 2.500,  3.750) = 187864 
    [ 3.750,  5.000) = 4811 
    [ 5.000,  6.250) = 738 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      4.035 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     14.864 ms/op
     p(99.9990) =     16.424 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 4.733 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  8.960 ms/op
                 listUser·p0.9999: 11.097 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   2: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  8.469 ms/op
                 listUser·p0.9999: 10.818 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.718 ms/op
                 listUser·p0.9999: 12.239 ms/op
                 listUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321068
  mean =      2.988 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 149 
    [ 1.250,  2.500) = 94494 
    [ 2.500,  3.750) = 189677 
    [ 3.750,  5.000) = 29979 
    [ 5.000,  6.250) = 5559 
    [ 6.250,  7.500) = 603 
    [ 7.500,  8.750) = 239 
    [ 8.750, 10.000) = 151 
    [10.000, 11.250) = 180 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     11.747 ms/op
     p(99.9990) =     12.569 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.698 ± 2.082  ops/ms
ClientPb.existUser                       thrpt       3  13.102 ± 0.816  ops/ms
ClientPb.getUser                         thrpt       3  13.031 ± 1.073  ops/ms
ClientPb.listUser                        thrpt       3  10.753 ± 1.473  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.713   ms/op
ClientPb.existUser                        avgt       3   2.425 ± 0.136   ms/op
ClientPb.getUser                          avgt       3   2.471 ± 0.389   ms/op
ClientPb.listUser                         avgt       3   2.963 ± 0.272   ms/op
ClientPb.createUser                     sample  385961   2.485 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.766           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.258           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.631           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.729           ms/op
ClientPb.existUser                      sample  385748   2.486 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.862           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.000           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.130           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.218           ms/op
ClientPb.getUser                        sample  377520   2.541 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.842           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.684           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.864           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.941           ms/op
ClientPb.listUser                       sample  321068   2.988 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.902           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.060           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.747           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.730           ms/op
