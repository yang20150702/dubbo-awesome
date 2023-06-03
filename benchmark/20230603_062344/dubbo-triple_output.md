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
# Warmup Iteration   1: 2.105 ops/ms
# Warmup Iteration   2: 5.604 ops/ms
# Warmup Iteration   3: 8.156 ops/ms
Iteration   1: 9.488 ops/ms
Iteration   2: 9.765 ops/ms
Iteration   3: 9.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.592 ±(99.9%) 2.756 ops/ms [Average]
  (min, avg, max) = (9.488, 9.592, 9.765), stdev = 0.151
  CI (99.9%): [6.836, 12.347] (assumes normal distribution)


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
# Warmup Iteration   1: 3.049 ops/ms
# Warmup Iteration   2: 8.777 ops/ms
# Warmup Iteration   3: 9.353 ops/ms
Iteration   1: 9.625 ops/ms
Iteration   2: 9.607 ops/ms
Iteration   3: 9.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.577 ±(99.9%) 1.236 ops/ms [Average]
  (min, avg, max) = (9.500, 9.577, 9.625), stdev = 0.068
  CI (99.9%): [8.341, 10.813] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.056 ops/ms
# Warmup Iteration   2: 8.360 ops/ms
# Warmup Iteration   3: 9.316 ops/ms
Iteration   1: 9.204 ops/ms
Iteration   2: 9.414 ops/ms
Iteration   3: 9.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.427 ±(99.9%) 4.188 ops/ms [Average]
  (min, avg, max) = (9.204, 9.427, 9.662), stdev = 0.230
  CI (99.9%): [5.239, 13.614] (assumes normal distribution)


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
# Warmup Iteration   1: 2.794 ops/ms
# Warmup Iteration   2: 6.593 ops/ms
# Warmup Iteration   3: 7.971 ops/ms
Iteration   1: 7.965 ops/ms
Iteration   2: 7.963 ops/ms
Iteration   3: 7.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.958 ±(99.9%) 0.190 ops/ms [Average]
  (min, avg, max) = (7.946, 7.958, 7.965), stdev = 0.010
  CI (99.9%): [7.768, 8.148] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.193 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.009 ms/op
Iteration   1: 3.352 ±(99.9%) 0.009 ms/op
Iteration   2: 3.279 ±(99.9%) 0.010 ms/op
Iteration   3: 3.439 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.357 ±(99.9%) 1.467 ms/op [Average]
  (min, avg, max) = (3.279, 3.357, 3.439), stdev = 0.080
  CI (99.9%): [1.890, 4.823] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.977 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.559 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.008 ms/op
Iteration   1: 3.187 ±(99.9%) 0.010 ms/op
Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
Iteration   3: 3.234 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.201 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (3.181, 3.201, 3.234), stdev = 0.029
  CI (99.9%): [2.668, 3.733] (assumes normal distribution)


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
# Warmup Iteration   1: 9.332 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.006 ms/op
Iteration   1: 3.456 ±(99.9%) 0.010 ms/op
Iteration   2: 3.250 ±(99.9%) 0.012 ms/op
Iteration   3: 3.362 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.356 ±(99.9%) 1.878 ms/op [Average]
  (min, avg, max) = (3.250, 3.356, 3.456), stdev = 0.103
  CI (99.9%): [1.478, 5.234] (assumes normal distribution)


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
# Warmup Iteration   1: 10.545 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.201 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.010 ms/op
Iteration   1: 3.872 ±(99.9%) 0.012 ms/op
Iteration   2: 3.919 ±(99.9%) 0.014 ms/op
Iteration   3: 3.855 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.882 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.855, 3.882, 3.919), stdev = 0.033
  CI (99.9%): [3.281, 4.483] (assumes normal distribution)


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
# Warmup Iteration   1: 9.360 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.010 ms/op
Iteration   1: 3.316 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  14.246 ms/op
                 createUser·p0.9999: 21.999 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   2: 3.467 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  19.754 ms/op
                 createUser·p0.9999: 22.254 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   3: 3.556 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.134 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  17.107 ms/op
                 createUser·p0.9999: 30.212 ms/op
                 createUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278661
  mean =      3.443 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13307 
    [ 2.500,  5.000) = 258251 
    [ 5.000,  7.500) = 6198 
    [ 7.500, 10.000) = 468 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     17.542 ms/op
     p(99.9900) =     28.620 ms/op
     p(99.9990) =     30.645 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 8.778 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.009 ms/op
Iteration   1: 3.319 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  17.004 ms/op
                 existUser·p0.9999: 21.696 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  8.845 ms/op
                 existUser·p0.9999: 23.855 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 3.449 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   5.526 ms/op
                 existUser·p0.999:  21.650 ms/op
                 existUser·p0.9999: 25.264 ms/op
                 existUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289107
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9751 
    [ 2.500,  5.000) = 272982 
    [ 5.000,  7.500) = 5729 
    [ 7.500, 10.000) = 313 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 160 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     14.626 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     25.464 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 10.073 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.009 ms/op
Iteration   1: 3.396 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  19.508 ms/op
                 getUser·p0.9999: 23.767 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   2: 3.278 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   5.047 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 24.486 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   3: 3.389 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  15.361 ms/op
                 getUser·p0.9999: 24.201 ms/op
                 getUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286164
  mean =      3.353 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5211 
    [ 2.500,  5.000) = 275982 
    [ 5.000,  7.500) = 4152 
    [ 7.500, 10.000) = 348 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 149 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     15.418 ms/op
     p(99.9900) =     24.195 ms/op
     p(99.9990) =     25.169 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 10.093 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.012 ms/op
Iteration   1: 3.884 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.897 ms/op
                 listUser·p0.999:  19.825 ms/op
                 listUser·p0.9999: 25.674 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   2: 3.904 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  15.219 ms/op
                 listUser·p0.9999: 22.302 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 3.892 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246544
  mean =      3.893 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 238666 
    [ 5.000,  7.500) = 5615 
    [ 7.500, 10.000) = 1400 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.479 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.320 ms/op
     p(99.9000) =     15.392 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     26.429 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.592 ± 2.756  ops/ms
ClientPb.existUser                       thrpt       3   9.577 ± 1.236  ops/ms
ClientPb.getUser                         thrpt       3   9.427 ± 4.188  ops/ms
ClientPb.listUser                        thrpt       3   7.958 ± 0.190  ops/ms
ClientPb.createUser                       avgt       3   3.357 ± 1.467   ms/op
ClientPb.existUser                        avgt       3   3.201 ± 0.532   ms/op
ClientPb.getUser                          avgt       3   3.356 ± 1.878   ms/op
ClientPb.listUser                         avgt       3   3.882 ± 0.601   ms/op
ClientPb.createUser                     sample  278661   3.443 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.031           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.808           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.542           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.620           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.867           ms/op
ClientPb.existUser                      sample  289107   3.318 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.204           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.626           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.642           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.509           ms/op
ClientPb.getUser                        sample  286164   3.353 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.276           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.418           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.195           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.461           ms/op
ClientPb.listUser                       sample  246544   3.893 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.479           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.752           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.320           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.392           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.248           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.903           ms/op
