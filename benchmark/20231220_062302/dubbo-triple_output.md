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
# Warmup Iteration   1: 4.800 ops/ms
# Warmup Iteration   2: 12.026 ops/ms
# Warmup Iteration   3: 12.267 ops/ms
Iteration   1: 12.598 ops/ms
Iteration   2: 12.604 ops/ms
Iteration   3: 12.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.625 ±(99.9%) 0.752 ops/ms [Average]
  (min, avg, max) = (12.598, 12.625, 12.672), stdev = 0.041
  CI (99.9%): [11.873, 13.376] (assumes normal distribution)


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
# Warmup Iteration   1: 7.893 ops/ms
# Warmup Iteration   2: 13.025 ops/ms
# Warmup Iteration   3: 13.019 ops/ms
Iteration   1: 13.191 ops/ms
Iteration   2: 13.098 ops/ms
Iteration   3: 13.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.113 ±(99.9%) 1.304 ops/ms [Average]
  (min, avg, max) = (13.051, 13.113, 13.191), stdev = 0.072
  CI (99.9%): [11.809, 14.418] (assumes normal distribution)


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
# Warmup Iteration   1: 8.006 ops/ms
# Warmup Iteration   2: 12.491 ops/ms
# Warmup Iteration   3: 12.712 ops/ms
Iteration   1: 12.718 ops/ms
Iteration   2: 12.877 ops/ms
Iteration   3: 12.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.854 ±(99.9%) 2.304 ops/ms [Average]
  (min, avg, max) = (12.718, 12.854, 12.968), stdev = 0.126
  CI (99.9%): [10.550, 15.158] (assumes normal distribution)


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
# Warmup Iteration   1: 6.397 ops/ms
# Warmup Iteration   2: 10.342 ops/ms
# Warmup Iteration   3: 10.547 ops/ms
Iteration   1: 10.649 ops/ms
Iteration   2: 10.677 ops/ms
Iteration   3: 10.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.615 ±(99.9%) 1.550 ops/ms [Average]
  (min, avg, max) = (10.518, 10.615, 10.677), stdev = 0.085
  CI (99.9%): [9.065, 12.164] (assumes normal distribution)


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.003 ms/op
Iteration   1: 2.503 ±(99.9%) 0.004 ms/op
Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.516 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (2.503, 2.516, 2.531), stdev = 0.014
  CI (99.9%): [2.255, 2.777] (assumes normal distribution)


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.004 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.434 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (2.419, 2.434, 2.444), stdev = 0.013
  CI (99.9%): [2.191, 2.677] (assumes normal distribution)


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
# Warmup Iteration   1: 3.671 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.004 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.484 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (2.470, 2.484, 2.498), stdev = 0.014
  CI (99.9%): [2.228, 2.739] (assumes normal distribution)


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
# Warmup Iteration   1: 4.716 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.004 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
Iteration   2: 3.012 ±(99.9%) 0.005 ms/op
Iteration   3: 2.966 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.004 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (2.966, 3.004, 3.033), stdev = 0.034
  CI (99.9%): [2.379, 3.628] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.017 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.669 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.527 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   4.112 ms/op
                 createUser·p0.999:  11.019 ms/op
                 createUser·p0.9999: 12.988 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.531 ms/op
                 createUser·p0.999:  8.663 ms/op
                 createUser·p0.9999: 12.438 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 11.016 ms/op
                 createUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382920
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 185955 
    [ 2.500,  3.750) = 192702 
    [ 3.750,  5.000) = 3187 
    [ 5.000,  6.250) = 466 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     12.796 ms/op
     p(99.9990) =     13.424 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 3.618 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
Iteration   1: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  5.451 ms/op
                 existUser·p0.9999: 14.483 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  8.297 ms/op
                 existUser·p0.9999: 12.321 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  5.186 ms/op
                 existUser·p0.9999: 12.073 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393177
  mean =      2.439 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 195429 
    [ 2.500,  3.750) = 195096 
    [ 3.750,  5.000) = 2074 
    [ 5.000,  6.250) = 169 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 152 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =      5.844 ms/op
     p(99.9900) =     12.818 ms/op
     p(99.9990) =     14.748 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  6.119 ms/op
                 getUser·p0.9999: 14.452 ms/op
                 getUser·p1.00:   15.483 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  8.946 ms/op
                 getUser·p0.9999: 13.091 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  8.499 ms/op
                 getUser·p0.9999: 11.354 ms/op
                 getUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384409
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 191559 
    [ 2.500,  3.750) = 189410 
    [ 3.750,  5.000) = 2739 
    [ 5.000,  6.250) = 203 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.076 ms/op
     p(99.9900) =     13.444 ms/op
     p(99.9990) =     14.732 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 4.690 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.008 ms/op
Iteration   1: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.671 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.772 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.650 ms/op
                 listUser·p1.00:   11.256 ms/op

Iteration   2: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.353 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  10.064 ms/op
                 listUser·p0.9999: 12.146 ms/op
                 listUser·p1.00:   13.615 ms/op

Iteration   3: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.705 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 14.598 ms/op
                 listUser·p1.00:   15.466 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319186
  mean =      3.005 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 172 
    [ 1.250,  2.500) = 93133 
    [ 2.500,  3.750) = 186799 
    [ 3.750,  5.000) = 31983 
    [ 5.000,  6.250) = 5760 
    [ 6.250,  7.500) = 692 
    [ 7.500,  8.750) = 180 
    [ 8.750, 10.000) = 221 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     13.616 ms/op
     p(99.9990) =     15.293 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.625 ± 0.752  ops/ms
ClientPb.existUser                       thrpt       3  13.113 ± 1.304  ops/ms
ClientPb.getUser                         thrpt       3  12.854 ± 2.304  ops/ms
ClientPb.listUser                        thrpt       3  10.615 ± 1.550  ops/ms
ClientPb.createUser                       avgt       3   2.516 ± 0.261   ms/op
ClientPb.existUser                        avgt       3   2.434 ± 0.243   ms/op
ClientPb.getUser                          avgt       3   2.484 ± 0.255   ms/op
ClientPb.listUser                         avgt       3   3.004 ± 0.625   ms/op
ClientPb.createUser                     sample  382920   2.504 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.684           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.470           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.796           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.072           ms/op
ClientPb.existUser                      sample  393177   2.439 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.678           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.844           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.818           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.106           ms/op
ClientPb.getUser                        sample  384409   2.495 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.993           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.076           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.444           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.483           ms/op
ClientPb.listUser                       sample  319186   3.005 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.671           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.616           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.466           ms/op
