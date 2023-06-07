# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.662 ops/ms
# Warmup Iteration   2: 3.601 ops/ms
# Warmup Iteration   3: 6.732 ops/ms
Iteration   1: 7.610 ops/ms
Iteration   2: 8.250 ops/ms
Iteration   3: 8.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.968 ±(99.9%) 5.967 ops/ms [Average]
  (min, avg, max) = (7.610, 7.968, 8.250), stdev = 0.327
  CI (99.9%): [2.001, 13.935] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.291 ops/ms
# Warmup Iteration   2: 7.394 ops/ms
# Warmup Iteration   3: 7.922 ops/ms
Iteration   1: 8.557 ops/ms
Iteration   2: 8.285 ops/ms
Iteration   3: 8.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.421 ±(99.9%) 2.478 ops/ms [Average]
  (min, avg, max) = (8.285, 8.421, 8.557), stdev = 0.136
  CI (99.9%): [5.942, 10.899] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.101 ops/ms
# Warmup Iteration   2: 6.527 ops/ms
# Warmup Iteration   3: 8.004 ops/ms
Iteration   1: 8.263 ops/ms
Iteration   2: 8.174 ops/ms
Iteration   3: 8.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.264 ±(99.9%) 1.633 ops/ms [Average]
  (min, avg, max) = (8.174, 8.264, 8.353), stdev = 0.090
  CI (99.9%): [6.630, 9.897] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.273 ops/ms
# Warmup Iteration   2: 5.689 ops/ms
# Warmup Iteration   3: 6.470 ops/ms
Iteration   1: 6.640 ops/ms
Iteration   2: 7.041 ops/ms
Iteration   3: 6.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.841 ±(99.9%) 3.656 ops/ms [Average]
  (min, avg, max) = (6.640, 6.841, 7.041), stdev = 0.200
  CI (99.9%): [3.185, 10.497] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.609 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.508 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.008 ms/op
Iteration   1: 3.914 ±(99.9%) 0.007 ms/op
Iteration   2: 3.902 ±(99.9%) 0.009 ms/op
Iteration   3: 4.037 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.951 ±(99.9%) 1.366 ms/op [Average]
  (min, avg, max) = (3.902, 3.951, 4.037), stdev = 0.075
  CI (99.9%): [2.585, 5.317] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.920 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.747 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.003 ms/op
Iteration   1: 3.665 ±(99.9%) 0.009 ms/op
Iteration   2: 3.919 ±(99.9%) 0.008 ms/op
Iteration   3: 3.687 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.757 ±(99.9%) 2.569 ms/op [Average]
  (min, avg, max) = (3.665, 3.757, 3.919), stdev = 0.141
  CI (99.9%): [1.188, 6.327] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.286 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.748 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.004 ms/op
Iteration   1: 4.105 ±(99.9%) 0.006 ms/op
Iteration   2: 3.910 ±(99.9%) 0.012 ms/op
Iteration   3: 3.879 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.965 ±(99.9%) 2.232 ms/op [Average]
  (min, avg, max) = (3.879, 3.965, 4.105), stdev = 0.122
  CI (99.9%): [1.733, 6.197] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.838 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.637 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.566 ±(99.9%) 0.015 ms/op
Iteration   1: 4.687 ±(99.9%) 0.011 ms/op
Iteration   2: 4.474 ±(99.9%) 0.016 ms/op
Iteration   3: 4.419 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.527 ±(99.9%) 2.586 ms/op [Average]
  (min, avg, max) = (4.419, 4.527, 4.687), stdev = 0.142
  CI (99.9%): [1.941, 7.113] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.005 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 5.081 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.496 ±(99.9%) 0.018 ms/op
Iteration   1: 3.794 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.991 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  22.610 ms/op
                 createUser·p0.9999: 27.296 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   2: 3.953 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   5.940 ms/op
                 createUser·p0.999:  25.464 ms/op
                 createUser·p0.9999: 28.011 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   3: 3.911 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.052 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.416 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  11.010 ms/op
                 createUser·p0.9999: 30.867 ms/op
                 createUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 246940
  mean =      3.885 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 161 
    [ 2.500,  5.000) = 239913 
    [ 5.000,  7.500) = 5808 
    [ 7.500, 10.000) = 551 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 123 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     22.816 ms/op
     p(99.9900) =     29.731 ms/op
     p(99.9990) =     31.278 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.394 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
Iteration   1: 3.716 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.690 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 24.163 ms/op
                 existUser·p1.00:   28.967 ms/op

Iteration   2: 3.864 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  22.365 ms/op
                 existUser·p0.9999: 25.190 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   3: 3.717 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.882 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  17.136 ms/op
                 existUser·p0.9999: 26.981 ms/op
                 existUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254825
  mean =      3.765 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 427 
    [ 2.500,  5.000) = 246044 
    [ 5.000,  7.500) = 7011 
    [ 7.500, 10.000) = 855 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     16.881 ms/op
     p(99.9900) =     26.526 ms/op
     p(99.9990) =     28.949 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.581 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.787 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.013 ms/op
Iteration   1: 4.050 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.993 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   8.053 ms/op
                 getUser·p0.999:  22.733 ms/op
                 getUser·p0.9999: 25.234 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   2: 3.945 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  11.141 ms/op
                 getUser·p0.9999: 30.143 ms/op
                 getUser·p1.00:   31.654 ms/op

Iteration   3: 4.058 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   7.496 ms/op
                 getUser·p0.999:  27.329 ms/op
                 getUser·p0.9999: 29.856 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238901
  mean =      4.017 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 225615 
    [ 5.000,  7.500) = 10839 
    [ 7.500, 10.000) = 1531 
    [10.000, 12.500) = 406 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 98 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     22.744 ms/op
     p(99.9900) =     29.633 ms/op
     p(99.9990) =     31.242 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.417 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.687 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.068 ±(99.9%) 0.022 ms/op
Iteration   1: 4.803 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   9.440 ms/op
                 listUser·p0.999:  26.487 ms/op
                 listUser·p0.9999: 30.583 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   2: 4.674 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  19.353 ms/op
                 listUser·p0.9999: 25.794 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   3: 4.843 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 17.391 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201154
  mean =      4.772 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 164411 
    [ 5.000,  7.500) = 31748 
    [ 7.500, 10.000) = 3648 
    [10.000, 12.500) = 778 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.482 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      9.208 ms/op
     p(99.9000) =     19.197 ms/op
     p(99.9900) =     29.206 ms/op
     p(99.9990) =     31.192 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.968 ± 5.967  ops/ms
ClientPb.existUser                       thrpt       3   8.421 ± 2.478  ops/ms
ClientPb.getUser                         thrpt       3   8.264 ± 1.633  ops/ms
ClientPb.listUser                        thrpt       3   6.841 ± 3.656  ops/ms
ClientPb.createUser                       avgt       3   3.951 ± 1.366   ms/op
ClientPb.existUser                        avgt       3   3.757 ± 2.569   ms/op
ClientPb.getUser                          avgt       3   3.965 ± 2.232   ms/op
ClientPb.listUser                         avgt       3   4.527 ± 2.586   ms/op
ClientPb.createUser                     sample  246940   3.885 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.069           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.816           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.731           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.523           ms/op
ClientPb.existUser                      sample  254825   3.765 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.446           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.645           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.578           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.881           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.526           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.457           ms/op
ClientPb.getUser                        sample  238901   4.017 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.571           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.487           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.744           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.633           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.654           ms/op
ClientPb.listUser                       sample  201154   4.772 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.482           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.906           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.208           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.197           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.206           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.228           ms/op
