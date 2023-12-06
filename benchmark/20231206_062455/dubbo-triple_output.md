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
# Warmup Iteration   1: 4.750 ops/ms
# Warmup Iteration   2: 11.823 ops/ms
# Warmup Iteration   3: 12.472 ops/ms
Iteration   1: 12.596 ops/ms
Iteration   2: 12.615 ops/ms
Iteration   3: 12.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.640 ±(99.9%) 1.087 ops/ms [Average]
  (min, avg, max) = (12.596, 12.640, 12.707), stdev = 0.060
  CI (99.9%): [11.553, 13.726] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.142 ops/ms
# Warmup Iteration   2: 13.247 ops/ms
# Warmup Iteration   3: 13.002 ops/ms
Iteration   1: 12.886 ops/ms
Iteration   2: 13.084 ops/ms
Iteration   3: 13.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.067 ±(99.9%) 3.157 ops/ms [Average]
  (min, avg, max) = (12.886, 13.067, 13.231), stdev = 0.173
  CI (99.9%): [9.910, 16.224] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.728 ops/ms
# Warmup Iteration   2: 12.615 ops/ms
# Warmup Iteration   3: 12.519 ops/ms
Iteration   1: 12.472 ops/ms
Iteration   2: 12.797 ops/ms
Iteration   3: 12.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.650 ±(99.9%) 3.004 ops/ms [Average]
  (min, avg, max) = (12.472, 12.650, 12.797), stdev = 0.165
  CI (99.9%): [9.646, 15.655] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.533 ops/ms
# Warmup Iteration   2: 10.221 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.655 ops/ms
Iteration   2: 10.575 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.561 ±(99.9%) 1.847 ops/ms [Average]
  (min, avg, max) = (10.454, 10.561, 10.655), stdev = 0.101
  CI (99.9%): [8.714, 12.408] (assumes normal distribution)


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
# Warmup Iteration   1: 4.045 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.004 ms/op
Iteration   1: 2.535 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.003 ms/op
Iteration   3: 2.517 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.524 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (2.517, 2.524, 2.535), stdev = 0.009
  CI (99.9%): [2.353, 2.695] (assumes normal distribution)


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.003 ms/op
Iteration   3: 2.444 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.459 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (2.444, 2.459, 2.481), stdev = 0.019
  CI (99.9%): [2.103, 2.814] (assumes normal distribution)


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.491 ±(99.9%) 0.004 ms/op
Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (2.486, 2.500, 2.522), stdev = 0.019
  CI (99.9%): [2.147, 2.853] (assumes normal distribution)


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
# Warmup Iteration   1: 5.129 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.005 ms/op
Iteration   1: 3.011 ±(99.9%) 0.005 ms/op
Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
Iteration   3: 3.014 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (2.997, 3.007, 3.014), stdev = 0.009
  CI (99.9%): [2.847, 3.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.695 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.583 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   4.084 ms/op
                 createUser·p0.999:  12.109 ms/op
                 createUser·p0.9999: 17.775 ms/op
                 createUser·p1.00:   18.317 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.490 ms/op
                 createUser·p0.999:  9.421 ms/op
                 createUser·p0.9999: 14.319 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   4.082 ms/op
                 createUser·p0.999:  8.607 ms/op
                 createUser·p0.9999: 10.788 ms/op
                 createUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378868
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 182098 
    [ 2.500,  3.750) = 191792 
    [ 3.750,  5.000) = 4019 
    [ 5.000,  6.250) = 460 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      8.653 ms/op
     p(99.9900) =     15.026 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  6.026 ms/op
                 existUser·p0.9999: 16.679 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  6.930 ms/op
                 existUser·p0.9999: 13.658 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  6.656 ms/op
                 existUser·p0.9999: 13.056 ms/op
                 existUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392699
  mean =      2.442 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 194158 
    [ 2.500,  3.750) = 195276 
    [ 3.750,  5.000) = 2151 
    [ 5.000,  6.250) = 624 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      6.684 ms/op
     p(99.9900) =     14.287 ms/op
     p(99.9990) =     17.154 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  10.911 ms/op
                 getUser·p0.9999: 13.735 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  10.320 ms/op
                 getUser·p0.9999: 13.811 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.893 ms/op
                 getUser·p0.999:  7.129 ms/op
                 getUser·p0.9999: 13.111 ms/op
                 getUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385226
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 191333 
    [ 2.500,  3.750) = 189021 
    [ 3.750,  5.000) = 3416 
    [ 5.000,  6.250) = 800 
    [ 6.250,  7.500) = 151 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 140 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     14.324 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 4.747 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.009 ms/op
Iteration   1: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.721 ms/op
                 listUser·p0.9999: 11.843 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  10.813 ms/op
                 listUser·p0.9999: 14.094 ms/op
                 listUser·p1.00:   14.828 ms/op

Iteration   3: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 11.320 ms/op
                 listUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316342
  mean =      3.032 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 90166 
    [ 2.500,  3.750) = 184434 
    [ 3.750,  5.000) = 33687 
    [ 5.000,  6.250) = 6398 
    [ 6.250,  7.500) = 847 
    [ 7.500,  8.750) = 142 
    [ 8.750, 10.000) = 229 
    [10.000, 11.250) = 197 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     10.103 ms/op
     p(99.9900) =     13.031 ms/op
     p(99.9990) =     14.792 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.640 ± 1.087  ops/ms
ClientPb.existUser                       thrpt       3  13.067 ± 3.157  ops/ms
ClientPb.getUser                         thrpt       3  12.650 ± 3.004  ops/ms
ClientPb.listUser                        thrpt       3  10.561 ± 1.847  ops/ms
ClientPb.createUser                       avgt       3   2.524 ± 0.171   ms/op
ClientPb.existUser                        avgt       3   2.459 ± 0.355   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.353   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.161   ms/op
ClientPb.createUser                     sample  378868   2.531 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.583           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.653           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.026           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.317           ms/op
ClientPb.existUser                      sample  392699   2.442 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.824           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.684           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.287           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.826           ms/op
ClientPb.getUser                        sample  385226   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.899           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.929           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.599           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.533           ms/op
ClientPb.listUser                       sample  316342   3.032 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.830           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.103           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.031           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.828           ms/op
