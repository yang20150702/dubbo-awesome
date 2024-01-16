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
# Warmup Iteration   1: 4.735 ops/ms
# Warmup Iteration   2: 12.219 ops/ms
# Warmup Iteration   3: 12.119 ops/ms
Iteration   1: 12.594 ops/ms
Iteration   2: 12.545 ops/ms
Iteration   3: 12.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.598 ±(99.9%) 1.020 ops/ms [Average]
  (min, avg, max) = (12.545, 12.598, 12.656), stdev = 0.056
  CI (99.9%): [11.579, 13.618] (assumes normal distribution)


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
# Warmup Iteration   1: 8.283 ops/ms
# Warmup Iteration   2: 13.019 ops/ms
# Warmup Iteration   3: 12.999 ops/ms
Iteration   1: 13.069 ops/ms
Iteration   2: 13.131 ops/ms
Iteration   3: 12.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.037 ±(99.9%) 2.065 ops/ms [Average]
  (min, avg, max) = (12.912, 13.037, 13.131), stdev = 0.113
  CI (99.9%): [10.972, 15.102] (assumes normal distribution)


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
# Warmup Iteration   1: 7.498 ops/ms
# Warmup Iteration   2: 12.422 ops/ms
# Warmup Iteration   3: 12.846 ops/ms
Iteration   1: 12.772 ops/ms
Iteration   2: 12.842 ops/ms
Iteration   3: 12.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.832 ±(99.9%) 1.005 ops/ms [Average]
  (min, avg, max) = (12.772, 12.832, 12.881), stdev = 0.055
  CI (99.9%): [11.826, 13.837] (assumes normal distribution)


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
# Warmup Iteration   1: 6.897 ops/ms
# Warmup Iteration   2: 10.622 ops/ms
# Warmup Iteration   3: 10.699 ops/ms
Iteration   1: 10.755 ops/ms
Iteration   2: 10.778 ops/ms
Iteration   3: 10.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.740 ±(99.9%) 0.877 ops/ms [Average]
  (min, avg, max) = (10.686, 10.740, 10.778), stdev = 0.048
  CI (99.9%): [9.863, 11.617] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.003 ms/op
Iteration   1: 2.503 ±(99.9%) 0.004 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.534 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.529 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (2.503, 2.529, 2.549), stdev = 0.023
  CI (99.9%): [2.101, 2.956] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.736 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.004 ms/op
Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
Iteration   3: 2.424 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.422 ±(99.9%) 0.080 ms/op [Average]
  (min, avg, max) = (2.417, 2.422, 2.425), stdev = 0.004
  CI (99.9%): [2.342, 2.502] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.080 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.004 ms/op
Iteration   1: 2.522 ±(99.9%) 0.003 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.516 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.508, 2.516, 2.522), stdev = 0.007
  CI (99.9%): [2.385, 2.647] (assumes normal distribution)


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.005 ms/op
Iteration   1: 2.995 ±(99.9%) 0.005 ms/op
Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
Iteration   3: 3.017 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.004 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (2.995, 3.004, 3.017), stdev = 0.011
  CI (99.9%): [2.796, 3.212] (assumes normal distribution)


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.664 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
Iteration   1: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 13.609 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.931 ms/op
                 createUser·p0.999:  9.029 ms/op
                 createUser·p0.9999: 12.108 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.567 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.861 ms/op
                 createUser·p0.999:  8.116 ms/op
                 createUser·p0.9999: 11.363 ms/op
                 createUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376089
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 180570 
    [ 2.500,  3.750) = 191052 
    [ 3.750,  5.000) = 3632 
    [ 5.000,  6.250) = 356 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      8.254 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     13.865 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.293 ms/op
                 existUser·p0.999:  6.505 ms/op
                 existUser·p0.9999: 14.074 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.578 ms/op
                 existUser·p0.999:  7.344 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 11.484 ms/op
                 existUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393353
  mean =      2.438 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 195447 
    [ 2.500,  3.750) = 194879 
    [ 3.750,  5.000) = 2211 
    [ 5.000,  6.250) = 338 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      6.717 ms/op
     p(99.9900) =     13.331 ms/op
     p(99.9990) =     14.355 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  7.994 ms/op
                 getUser·p0.9999: 14.156 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  8.387 ms/op
                 getUser·p0.9999: 12.176 ms/op
                 getUser·p1.00:   13.255 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  9.224 ms/op
                 getUser·p0.9999: 10.420 ms/op
                 getUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385421
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 190558 
    [ 2.500,  3.750) = 189578 
    [ 3.750,  5.000) = 4417 
    [ 5.000,  6.250) = 366 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     14.863 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 4.958 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.008 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.699 ms/op
                 listUser·p1.00:   10.895 ms/op

Iteration   2: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 10.900 ms/op
                 listUser·p1.00:   11.141 ms/op

Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.817 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.372 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 10.838 ms/op
                 listUser·p1.00:   11.043 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321440
  mean =      2.984 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 189 
    [ 1.250,  2.500) = 98242 
    [ 2.500,  3.750) = 184654 
    [ 3.750,  5.000) = 31050 
    [ 5.000,  6.250) = 5937 
    [ 6.250,  7.500) = 729 
    [ 7.500,  8.750) = 258 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 157 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.119 ms/op
     p(99.9900) =     10.781 ms/op
     p(99.9990) =     11.043 ms/op
     p(99.9999) =     11.141 ms/op
    p(100.0000) =     11.141 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.598 ± 1.020  ops/ms
ClientPb.existUser                       thrpt       3  13.037 ± 2.065  ops/ms
ClientPb.getUser                         thrpt       3  12.832 ± 1.005  ops/ms
ClientPb.listUser                        thrpt       3  10.740 ± 0.877  ops/ms
ClientPb.createUser                       avgt       3   2.529 ± 0.427   ms/op
ClientPb.existUser                        avgt       3   2.422 ± 0.080   ms/op
ClientPb.getUser                          avgt       3   2.516 ± 0.131   ms/op
ClientPb.listUser                         avgt       3   3.004 ± 0.208   ms/op
ClientPb.createUser                     sample  376089   2.550 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.793           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.254           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.500           ms/op
ClientPb.existUser                      sample  393353   2.438 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.760           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.717           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.331           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.516           ms/op
ClientPb.getUser                        sample  385421   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.717           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.175           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.861           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.008           ms/op
ClientPb.listUser                       sample  321440   2.984 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.817           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.119           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.781           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.141           ms/op
