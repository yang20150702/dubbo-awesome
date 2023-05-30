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
# Warmup Iteration   1: 2.088 ops/ms
# Warmup Iteration   2: 6.003 ops/ms
# Warmup Iteration   3: 8.509 ops/ms
Iteration   1: 9.360 ops/ms
Iteration   2: 9.519 ops/ms
Iteration   3: 9.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.422 ±(99.9%) 1.547 ops/ms [Average]
  (min, avg, max) = (9.360, 9.422, 9.519), stdev = 0.085
  CI (99.9%): [7.876, 10.969] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.472 ops/ms
# Warmup Iteration   2: 8.865 ops/ms
# Warmup Iteration   3: 9.246 ops/ms
Iteration   1: 9.800 ops/ms
Iteration   2: 10.083 ops/ms
Iteration   3: 9.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.948 ±(99.9%) 2.589 ops/ms [Average]
  (min, avg, max) = (9.800, 9.948, 10.083), stdev = 0.142
  CI (99.9%): [7.359, 12.537] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.491 ops/ms
# Warmup Iteration   2: 8.690 ops/ms
# Warmup Iteration   3: 9.478 ops/ms
Iteration   1: 9.439 ops/ms
Iteration   2: 9.536 ops/ms
Iteration   3: 9.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.569 ±(99.9%) 2.740 ops/ms [Average]
  (min, avg, max) = (9.439, 9.569, 9.734), stdev = 0.150
  CI (99.9%): [6.829, 12.310] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.718 ops/ms
# Warmup Iteration   2: 7.642 ops/ms
# Warmup Iteration   3: 7.647 ops/ms
Iteration   1: 8.114 ops/ms
Iteration   2: 7.987 ops/ms
Iteration   3: 8.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.079 ±(99.9%) 1.465 ops/ms [Average]
  (min, avg, max) = (7.987, 8.079, 8.135), stdev = 0.080
  CI (99.9%): [6.614, 9.543] (assumes normal distribution)


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
# Warmup Iteration   1: 9.430 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.006 ms/op
Iteration   1: 3.457 ±(99.9%) 0.007 ms/op
Iteration   2: 3.389 ±(99.9%) 0.005 ms/op
Iteration   3: 3.329 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.391 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (3.329, 3.391, 3.457), stdev = 0.064
  CI (99.9%): [2.224, 4.558] (assumes normal distribution)


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
# Warmup Iteration   1: 8.093 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.009 ms/op
Iteration   1: 3.234 ±(99.9%) 0.008 ms/op
Iteration   2: 3.332 ±(99.9%) 0.004 ms/op
Iteration   3: 3.325 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.297 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (3.234, 3.297, 3.332), stdev = 0.055
  CI (99.9%): [2.296, 4.298] (assumes normal distribution)


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
# Warmup Iteration   1: 10.694 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.003 ms/op
Iteration   1: 3.407 ±(99.9%) 0.003 ms/op
Iteration   2: 3.404 ±(99.9%) 0.006 ms/op
Iteration   3: 3.383 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.398 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (3.383, 3.398, 3.407), stdev = 0.013
  CI (99.9%): [3.160, 3.636] (assumes normal distribution)


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
# Warmup Iteration   1: 9.635 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.011 ms/op
Iteration   1: 4.074 ±(99.9%) 0.008 ms/op
Iteration   2: 4.012 ±(99.9%) 0.010 ms/op
Iteration   3: 3.953 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.013 ±(99.9%) 1.109 ms/op [Average]
  (min, avg, max) = (3.953, 4.013, 4.074), stdev = 0.061
  CI (99.9%): [2.904, 5.122] (assumes normal distribution)


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
# Warmup Iteration   1: 9.782 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.011 ms/op
Iteration   1: 3.377 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  19.025 ms/op
                 createUser·p0.9999: 22.463 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.767 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  22.609 ms/op
                 createUser·p0.9999: 27.059 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  17.539 ms/op
                 createUser·p0.9999: 26.010 ms/op
                 createUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283141
  mean =      3.388 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6865 
    [ 2.500,  5.000) = 268674 
    [ 5.000,  7.500) = 6307 
    [ 7.500, 10.000) = 744 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     17.648 ms/op
     p(99.9900) =     26.073 ms/op
     p(99.9990) =     27.689 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 9.575 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.007 ms/op
Iteration   1: 3.370 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  20.099 ms/op
                 existUser·p0.9999: 23.053 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   2: 3.343 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  20.297 ms/op
                 existUser·p0.9999: 27.232 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   3: 3.327 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.773 ms/op
                 existUser·p0.999:  17.665 ms/op
                 existUser·p0.9999: 24.379 ms/op
                 existUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286686
  mean =      3.346 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5763 
    [ 2.500,  5.000) = 275125 
    [ 5.000,  7.500) = 4845 
    [ 7.500, 10.000) = 579 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.000 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     18.348 ms/op
     p(99.9900) =     26.356 ms/op
     p(99.9990) =     27.870 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.008 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.744 ±(99.9%) 0.011 ms/op
Iteration   1: 3.630 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.907 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   7.676 ms/op
                 getUser·p0.999:  21.103 ms/op
                 getUser·p0.9999: 24.255 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   2: 3.533 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  10.109 ms/op
                 getUser·p0.9999: 32.269 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   7.132 ms/op
                 getUser·p0.999:  20.977 ms/op
                 getUser·p0.9999: 25.854 ms/op
                 getUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269425
  mean =      3.558 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 331 
    [ 2.500,  5.000) = 259523 
    [ 5.000,  7.500) = 7403 
    [ 7.500, 10.000) = 1638 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     30.671 ms/op
     p(99.9990) =     32.566 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 11.614 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.556 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.015 ms/op
Iteration   1: 4.121 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  20.590 ms/op
                 listUser·p0.9999: 23.240 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   2: 4.042 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.784 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 27.463 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   3: 4.055 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  15.926 ms/op
                 listUser·p0.9999: 20.812 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235452
  mean =      4.072 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 226101 
    [ 5.000,  7.500) = 6384 
    [ 7.500, 10.000) = 1938 
    [10.000, 12.500) = 429 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     25.788 ms/op
     p(99.9990) =     28.343 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.422 ± 1.547  ops/ms
ClientPb.existUser                       thrpt       3   9.948 ± 2.589  ops/ms
ClientPb.getUser                         thrpt       3   9.569 ± 2.740  ops/ms
ClientPb.listUser                        thrpt       3   8.079 ± 1.465  ops/ms
ClientPb.createUser                       avgt       3   3.391 ± 1.167   ms/op
ClientPb.existUser                        avgt       3   3.297 ± 1.001   ms/op
ClientPb.getUser                          avgt       3   3.398 ± 0.238   ms/op
ClientPb.listUser                         avgt       3   4.013 ± 1.109   ms/op
ClientPb.createUser                     sample  283141   3.388 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.425           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.070           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.648           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.073           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.951           ms/op
ClientPb.existUser                      sample  286686   3.346 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.073           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.000           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.348           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.356           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.984           ms/op
ClientPb.getUser                        sample  269425   3.558 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.337           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.408           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.029           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.809           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.671           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  235452   4.072 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.444           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.946           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.334           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.788           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.574           ms/op
