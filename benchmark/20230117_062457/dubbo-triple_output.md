# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.770 ops/ms
# Warmup Iteration   2: 3.748 ops/ms
# Warmup Iteration   3: 7.520 ops/ms
Iteration   1: 7.749 ops/ms
Iteration   2: 8.509 ops/ms
Iteration   3: 8.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.253 ±(99.9%) 7.963 ops/ms [Average]
  (min, avg, max) = (7.749, 8.253, 8.509), stdev = 0.437
  CI (99.9%): [0.289, 16.216] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.465 ops/ms
# Warmup Iteration   2: 7.137 ops/ms
# Warmup Iteration   3: 8.066 ops/ms
Iteration   1: 8.491 ops/ms
Iteration   2: 8.568 ops/ms
Iteration   3: 7.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.341 ±(99.9%) 5.989 ops/ms [Average]
  (min, avg, max) = (7.964, 8.341, 8.568), stdev = 0.328
  CI (99.9%): [2.352, 14.330] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.771 ops/ms
# Warmup Iteration   2: 7.181 ops/ms
# Warmup Iteration   3: 7.381 ops/ms
Iteration   1: 8.018 ops/ms
Iteration   2: 8.127 ops/ms
Iteration   3: 8.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.146 ±(99.9%) 2.531 ops/ms [Average]
  (min, avg, max) = (8.018, 8.146, 8.293), stdev = 0.139
  CI (99.9%): [5.615, 10.677] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.396 ops/ms
# Warmup Iteration   2: 6.022 ops/ms
# Warmup Iteration   3: 6.975 ops/ms
Iteration   1: 7.143 ops/ms
Iteration   2: 7.300 ops/ms
Iteration   3: 7.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.241 ±(99.9%) 1.561 ops/ms [Average]
  (min, avg, max) = (7.143, 7.241, 7.300), stdev = 0.086
  CI (99.9%): [5.680, 8.803] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 13.086 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.293 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.006 ms/op
Iteration   1: 4.032 ±(99.9%) 0.010 ms/op
Iteration   2: 3.845 ±(99.9%) 0.011 ms/op
Iteration   3: 3.814 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.897 ±(99.9%) 2.144 ms/op [Average]
  (min, avg, max) = (3.814, 3.897, 4.032), stdev = 0.118
  CI (99.9%): [1.753, 6.041] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.938 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.008 ms/op
Iteration   1: 3.704 ±(99.9%) 0.007 ms/op
Iteration   2: 3.671 ±(99.9%) 0.004 ms/op
Iteration   3: 3.642 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.672 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (3.642, 3.672, 3.704), stdev = 0.031
  CI (99.9%): [3.112, 4.232] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.339 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.005 ms/op
Iteration   1: 3.822 ±(99.9%) 0.006 ms/op
Iteration   2: 4.001 ±(99.9%) 0.006 ms/op
Iteration   3: 3.807 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.877 ±(99.9%) 1.965 ms/op [Average]
  (min, avg, max) = (3.807, 3.877, 4.001), stdev = 0.108
  CI (99.9%): [1.911, 5.842] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.707 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.155 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.631 ±(99.9%) 0.010 ms/op
Iteration   1: 4.570 ±(99.9%) 0.011 ms/op
Iteration   2: 4.568 ±(99.9%) 0.008 ms/op
Iteration   3: 4.448 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.529 ±(99.9%) 1.269 ms/op [Average]
  (min, avg, max) = (4.448, 4.529, 4.570), stdev = 0.070
  CI (99.9%): [3.260, 5.798] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.730 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.875 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.302 ±(99.9%) 0.017 ms/op
Iteration   1: 3.931 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  21.748 ms/op
                 createUser·p0.9999: 26.374 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   2: 3.844 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.761 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.840 ms/op
                 createUser·p0.999:  22.632 ms/op
                 createUser·p0.9999: 24.991 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.787 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.839 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  19.907 ms/op
                 createUser·p0.9999: 29.495 ms/op
                 createUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 249185
  mean =      3.853 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 569 
    [ 2.500,  5.000) = 239515 
    [ 5.000,  7.500) = 7778 
    [ 7.500, 10.000) = 753 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.522 ms/op
     p(99.9000) =     21.117 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     29.737 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.205 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.012 ms/op
Iteration   1: 3.840 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  22.544 ms/op
                 existUser·p0.9999: 27.635 ms/op
                 existUser·p1.00:   28.508 ms/op

Iteration   2: 3.743 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.778 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  10.387 ms/op
                 existUser·p0.9999: 25.934 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   3: 3.941 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.212 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  26.361 ms/op
                 existUser·p0.9999: 30.933 ms/op
                 existUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250094
  mean =      3.839 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 556 
    [ 2.500,  5.000) = 239772 
    [ 5.000,  7.500) = 8490 
    [ 7.500, 10.000) = 873 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     21.972 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     31.343 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.993 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.174 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.016 ms/op
Iteration   1: 3.951 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.563 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.850 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   7.602 ms/op
                 getUser·p0.999:  17.891 ms/op
                 getUser·p0.9999: 25.985 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   2: 3.750 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  24.631 ms/op
                 getUser·p0.9999: 27.934 ms/op
                 getUser·p1.00:   28.377 ms/op

Iteration   3: 3.766 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  10.423 ms/op
                 getUser·p0.9999: 30.967 ms/op
                 getUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 251132
  mean =      3.820 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 479 
    [ 2.500,  5.000) = 238090 
    [ 5.000,  7.500) = 10800 
    [ 7.500, 10.000) = 1255 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     29.619 ms/op
     p(99.9990) =     31.096 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.968 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.984 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.661 ±(99.9%) 0.015 ms/op
Iteration   1: 4.676 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  25.480 ms/op
                 listUser·p0.9999: 28.617 ms/op
                 listUser·p1.00:   29.065 ms/op

Iteration   2: 4.541 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.855 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  16.111 ms/op
                 listUser·p0.9999: 25.915 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   3: 4.601 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   8.259 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208206
  mean =      4.605 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 186758 
    [ 5.000,  7.500) = 17674 
    [ 7.500, 10.000) = 2569 
    [10.000, 12.500) = 665 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 212 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     16.960 ms/op
     p(99.9900) =     27.203 ms/op
     p(99.9990) =     28.981 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.253 ± 7.963  ops/ms
ClientPb.existUser                       thrpt       3   8.341 ± 5.989  ops/ms
ClientPb.getUser                         thrpt       3   8.146 ± 2.531  ops/ms
ClientPb.listUser                        thrpt       3   7.241 ± 1.561  ops/ms
ClientPb.createUser                       avgt       3   3.897 ± 2.144   ms/op
ClientPb.existUser                        avgt       3   3.672 ± 0.560   ms/op
ClientPb.getUser                          avgt       3   3.877 ± 1.965   ms/op
ClientPb.listUser                         avgt       3   4.529 ± 1.269   ms/op
ClientPb.createUser                     sample  249185   3.853 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.333           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.841           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.522           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.117           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.312           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.392           ms/op
ClientPb.existUser                      sample  250094   3.839 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.212           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.972           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.229           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.588           ms/op
ClientPb.getUser                        sample  251132   3.820 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.296           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.005           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.971           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.695           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.619           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.178           ms/op
ClientPb.listUser                       sample  208206   4.605 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.430           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.382           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.634           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.960           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.203           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.065           ms/op
