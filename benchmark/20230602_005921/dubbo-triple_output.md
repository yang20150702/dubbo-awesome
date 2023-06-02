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
# Warmup Iteration   1: 2.041 ops/ms
# Warmup Iteration   2: 5.164 ops/ms
# Warmup Iteration   3: 8.737 ops/ms
Iteration   1: 8.935 ops/ms
Iteration   2: 9.107 ops/ms
Iteration   3: 9.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.124 ±(99.9%) 3.631 ops/ms [Average]
  (min, avg, max) = (8.935, 9.124, 9.331), stdev = 0.199
  CI (99.9%): [5.494, 12.755] (assumes normal distribution)


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
# Warmup Iteration   1: 2.836 ops/ms
# Warmup Iteration   2: 8.851 ops/ms
# Warmup Iteration   3: 9.086 ops/ms
Iteration   1: 9.740 ops/ms
Iteration   2: 9.452 ops/ms
Iteration   3: 9.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.633 ±(99.9%) 2.876 ops/ms [Average]
  (min, avg, max) = (9.452, 9.633, 9.740), stdev = 0.158
  CI (99.9%): [6.757, 12.509] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.824 ops/ms
# Warmup Iteration   2: 7.989 ops/ms
# Warmup Iteration   3: 8.806 ops/ms
Iteration   1: 9.291 ops/ms
Iteration   2: 9.438 ops/ms
Iteration   3: 9.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.263 ±(99.9%) 3.476 ops/ms [Average]
  (min, avg, max) = (9.060, 9.263, 9.438), stdev = 0.191
  CI (99.9%): [5.787, 12.740] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.907 ops/ms
# Warmup Iteration   2: 7.518 ops/ms
# Warmup Iteration   3: 7.913 ops/ms
Iteration   1: 8.011 ops/ms
Iteration   2: 7.909 ops/ms
Iteration   3: 8.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.007 ±(99.9%) 1.759 ops/ms [Average]
  (min, avg, max) = (7.909, 8.007, 8.102), stdev = 0.096
  CI (99.9%): [6.249, 9.766] (assumes normal distribution)


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
# Warmup Iteration   1: 9.405 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.005 ms/op
Iteration   1: 3.506 ±(99.9%) 0.004 ms/op
Iteration   2: 3.377 ±(99.9%) 0.004 ms/op
Iteration   3: 3.365 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.416 ±(99.9%) 1.423 ms/op [Average]
  (min, avg, max) = (3.365, 3.416, 3.506), stdev = 0.078
  CI (99.9%): [1.993, 4.839] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.231 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.008 ms/op
Iteration   1: 3.341 ±(99.9%) 0.008 ms/op
Iteration   2: 3.268 ±(99.9%) 0.008 ms/op
Iteration   3: 3.417 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.342 ±(99.9%) 1.357 ms/op [Average]
  (min, avg, max) = (3.268, 3.342, 3.417), stdev = 0.074
  CI (99.9%): [1.985, 4.699] (assumes normal distribution)


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
# Warmup Iteration   1: 10.385 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.004 ms/op
Iteration   1: 3.466 ±(99.9%) 0.005 ms/op
Iteration   2: 3.409 ±(99.9%) 0.009 ms/op
Iteration   3: 3.338 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.404 ±(99.9%) 1.166 ms/op [Average]
  (min, avg, max) = (3.338, 3.404, 3.466), stdev = 0.064
  CI (99.9%): [2.238, 4.571] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.455 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.011 ms/op
Iteration   1: 4.094 ±(99.9%) 0.010 ms/op
Iteration   2: 3.964 ±(99.9%) 0.009 ms/op
Iteration   3: 4.190 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.083 ±(99.9%) 2.073 ms/op [Average]
  (min, avg, max) = (3.964, 4.083, 4.190), stdev = 0.114
  CI (99.9%): [2.010, 6.155] (assumes normal distribution)


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
# Warmup Iteration   1: 9.594 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.665 ±(99.9%) 0.012 ms/op
Iteration   1: 3.427 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  22.643 ms/op
                 createUser·p0.9999: 26.608 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   2: 3.502 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  24.183 ms/op
                 createUser·p0.9999: 29.094 ms/op
                 createUser·p1.00:   30.310 ms/op

Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278949
  mean =      3.440 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10484 
    [ 2.500,  5.000) = 262971 
    [ 5.000,  7.500) = 4624 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     28.118 ms/op
     p(99.9990) =     29.521 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.744 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.009 ms/op
Iteration   1: 3.322 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  17.646 ms/op
                 existUser·p0.9999: 29.102 ms/op
                 existUser·p1.00:   29.721 ms/op

Iteration   2: 3.303 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  15.735 ms/op
                 existUser·p0.9999: 27.765 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.741 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  10.862 ms/op
                 existUser·p0.9999: 31.336 ms/op
                 existUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290144
  mean =      3.306 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10736 
    [ 2.500,  5.000) = 273531 
    [ 5.000,  7.500) = 5105 
    [ 7.500, 10.000) = 387 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.559 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     13.121 ms/op
     p(99.9900) =     30.244 ms/op
     p(99.9990) =     32.735 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 9.471 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.012 ms/op
Iteration   1: 3.499 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  23.386 ms/op
                 getUser·p0.9999: 31.813 ms/op
                 getUser·p1.00:   33.194 ms/op

Iteration   2: 3.540 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   7.307 ms/op
                 getUser·p0.999:  23.134 ms/op
                 getUser·p0.9999: 25.820 ms/op
                 getUser·p1.00:   26.247 ms/op

Iteration   3: 3.418 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  20.532 ms/op
                 getUser·p0.9999: 28.854 ms/op
                 getUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275088
  mean =      3.485 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3319 
    [ 2.500,  5.000) = 260167 
    [ 5.000,  7.500) = 9875 
    [ 7.500, 10.000) = 1169 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     22.506 ms/op
     p(99.9900) =     30.798 ms/op
     p(99.9990) =     32.481 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 11.417 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 5.752 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.134 ±(99.9%) 0.014 ms/op
Iteration   1: 4.060 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   8.015 ms/op
                 listUser·p0.999:  23.306 ms/op
                 listUser·p0.9999: 26.874 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   2: 4.007 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  17.636 ms/op
                 listUser·p0.9999: 23.102 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 4.023 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  16.016 ms/op
                 listUser·p0.9999: 21.299 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238015
  mean =      4.030 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 229001 
    [ 5.000,  7.500) = 6398 
    [ 7.500, 10.000) = 1675 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     25.500 ms/op
     p(99.9990) =     27.491 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.124 ± 3.631  ops/ms
ClientPb.existUser                       thrpt       3   9.633 ± 2.876  ops/ms
ClientPb.getUser                         thrpt       3   9.263 ± 3.476  ops/ms
ClientPb.listUser                        thrpt       3   8.007 ± 1.759  ops/ms
ClientPb.createUser                       avgt       3   3.416 ± 1.423   ms/op
ClientPb.existUser                        avgt       3   3.342 ± 1.357   ms/op
ClientPb.getUser                          avgt       3   3.404 ± 1.166   ms/op
ClientPb.listUser                         avgt       3   4.083 ± 2.073   ms/op
ClientPb.createUser                     sample  278949   3.440 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.110           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.005           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.118           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.310           ms/op
ClientPb.existUser                      sample  290144   3.306 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.559           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.121           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.244           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.260           ms/op
ClientPb.getUser                        sample  275088   3.485 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.002           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.832           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.506           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.798           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.194           ms/op
ClientPb.listUser                       sample  238015   4.030 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.809           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.500           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.722           ms/op
