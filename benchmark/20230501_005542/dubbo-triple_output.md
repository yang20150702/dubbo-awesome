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
# Warmup Iteration   1: 2.188 ops/ms
# Warmup Iteration   2: 5.683 ops/ms
# Warmup Iteration   3: 8.755 ops/ms
Iteration   1: 9.098 ops/ms
Iteration   2: 9.019 ops/ms
Iteration   3: 9.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.065 ±(99.9%) 0.748 ops/ms [Average]
  (min, avg, max) = (9.019, 9.065, 9.098), stdev = 0.041
  CI (99.9%): [8.317, 9.813] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.695 ops/ms
# Warmup Iteration   2: 8.105 ops/ms
# Warmup Iteration   3: 9.040 ops/ms
Iteration   1: 9.671 ops/ms
Iteration   2: 10.100 ops/ms
Iteration   3: 9.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.848 ±(99.9%) 4.099 ops/ms [Average]
  (min, avg, max) = (9.671, 9.848, 10.100), stdev = 0.225
  CI (99.9%): [5.748, 13.947] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.849 ops/ms
# Warmup Iteration   2: 8.343 ops/ms
# Warmup Iteration   3: 8.903 ops/ms
Iteration   1: 9.123 ops/ms
Iteration   2: 9.344 ops/ms
Iteration   3: 9.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.240 ±(99.9%) 2.024 ops/ms [Average]
  (min, avg, max) = (9.123, 9.240, 9.344), stdev = 0.111
  CI (99.9%): [7.216, 11.264] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.923 ops/ms
# Warmup Iteration   2: 7.378 ops/ms
# Warmup Iteration   3: 7.851 ops/ms
Iteration   1: 7.820 ops/ms
Iteration   2: 8.300 ops/ms
Iteration   3: 8.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.082 ±(99.9%) 4.433 ops/ms [Average]
  (min, avg, max) = (7.820, 8.082, 8.300), stdev = 0.243
  CI (99.9%): [3.649, 12.515] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.052 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.922 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.007 ms/op
Iteration   1: 3.429 ±(99.9%) 0.006 ms/op
Iteration   2: 3.410 ±(99.9%) 0.005 ms/op
Iteration   3: 3.341 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.393 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.341, 3.393, 3.429), stdev = 0.047
  CI (99.9%): [2.541, 4.246] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.884 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.008 ms/op
Iteration   1: 3.281 ±(99.9%) 0.010 ms/op
Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
Iteration   3: 3.212 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.247 ±(99.9%) 0.632 ms/op [Average]
  (min, avg, max) = (3.212, 3.247, 3.281), stdev = 0.035
  CI (99.9%): [2.615, 3.879] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.228 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.005 ms/op
Iteration   1: 3.512 ±(99.9%) 0.010 ms/op
Iteration   2: 3.618 ±(99.9%) 0.005 ms/op
Iteration   3: 3.483 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.538 ±(99.9%) 1.292 ms/op [Average]
  (min, avg, max) = (3.483, 3.538, 3.618), stdev = 0.071
  CI (99.9%): [2.245, 4.830] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.135 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.468 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.009 ms/op
Iteration   1: 3.942 ±(99.9%) 0.011 ms/op
Iteration   2: 3.990 ±(99.9%) 0.015 ms/op
Iteration   3: 4.042 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.991 ±(99.9%) 0.913 ms/op [Average]
  (min, avg, max) = (3.942, 3.991, 4.042), stdev = 0.050
  CI (99.9%): [3.078, 4.905] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.136 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.014 ms/op
Iteration   1: 3.384 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.909 ms/op
                 createUser·p0.999:  22.348 ms/op
                 createUser·p0.9999: 24.466 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   2: 3.356 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  23.679 ms/op
                 createUser·p0.9999: 27.115 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 3.473 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  20.770 ms/op
                 createUser·p0.9999: 27.165 ms/op
                 createUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281824
  mean =      3.404 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8476 
    [ 2.500,  5.000) = 267607 
    [ 5.000,  7.500) = 4554 
    [ 7.500, 10.000) = 654 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 105 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     21.010 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     27.480 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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
# Warmup Iteration   1: 7.861 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.009 ms/op
Iteration   1: 3.447 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  21.851 ms/op
                 existUser·p0.9999: 28.213 ms/op
                 existUser·p1.00:   29.327 ms/op

Iteration   2: 3.401 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  22.872 ms/op
                 existUser·p0.9999: 26.727 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.399 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.749 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  10.928 ms/op
                 existUser·p0.9999: 28.364 ms/op
                 existUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280759
  mean =      3.415 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10476 
    [ 2.500,  5.000) = 263483 
    [ 5.000,  7.500) = 5571 
    [ 7.500, 10.000) = 766 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 131 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.942 ms/op
     p(99.9000) =     12.296 ms/op
     p(99.9900) =     28.014 ms/op
     p(99.9990) =     29.334 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 10.298 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.012 ms/op
Iteration   1: 3.459 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.931 ms/op
                 getUser·p0.999:  15.647 ms/op
                 getUser·p0.9999: 29.582 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   2: 3.409 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  23.423 ms/op
                 getUser·p0.9999: 26.280 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.425 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.720 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  22.207 ms/op
                 getUser·p0.9999: 28.530 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279434
  mean =      3.431 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 801 
    [ 2.500,  5.000) = 269933 
    [ 5.000,  7.500) = 7395 
    [ 7.500, 10.000) = 783 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     15.689 ms/op
     p(99.9900) =     28.576 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.849 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.659 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.202 ±(99.9%) 0.014 ms/op
Iteration   1: 4.136 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   8.495 ms/op
                 listUser·p0.999:  21.856 ms/op
                 listUser·p0.9999: 26.190 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   2: 4.041 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 22.777 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 4.092 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.104 ms/op
                 listUser·p0.999:  16.658 ms/op
                 listUser·p0.9999: 19.666 ms/op
                 listUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234780
  mean =      4.089 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 226282 
    [ 5.000,  7.500) = 5954 
    [ 7.500, 10.000) = 1570 
    [10.000, 12.500) = 424 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.976 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     24.775 ms/op
     p(99.9990) =     26.561 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.065 ± 0.748  ops/ms
ClientPb.existUser                       thrpt       3   9.848 ± 4.099  ops/ms
ClientPb.getUser                         thrpt       3   9.240 ± 2.024  ops/ms
ClientPb.listUser                        thrpt       3   8.082 ± 4.433  ops/ms
ClientPb.createUser                       avgt       3   3.393 ± 0.853   ms/op
ClientPb.existUser                        avgt       3   3.247 ± 0.632   ms/op
ClientPb.getUser                          avgt       3   3.538 ± 1.292   ms/op
ClientPb.listUser                         avgt       3   3.991 ± 0.913   ms/op
ClientPb.createUser                     sample  281824   3.404 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.217           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.010           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.001           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.984           ms/op
ClientPb.existUser                      sample  280759   3.415 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.751           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.407           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.942           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.296           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.014           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.393           ms/op
ClientPb.getUser                        sample  279434   3.431 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.221           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.689           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.576           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.179           ms/op
ClientPb.listUser                       sample  234780   4.089 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.976           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.700           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.383           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.775           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.706           ms/op
