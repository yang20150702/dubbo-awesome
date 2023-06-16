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
# Warmup Iteration   1: 2.628 ops/ms
# Warmup Iteration   2: 5.842 ops/ms
# Warmup Iteration   3: 9.315 ops/ms
Iteration   1: 10.058 ops/ms
Iteration   2: 9.715 ops/ms
Iteration   3: 10.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.007 ±(99.9%) 4.926 ops/ms [Average]
  (min, avg, max) = (9.715, 10.007, 10.248), stdev = 0.270
  CI (99.9%): [5.081, 14.933] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.683 ops/ms
# Warmup Iteration   2: 9.545 ops/ms
# Warmup Iteration   3: 9.653 ops/ms
Iteration   1: 10.561 ops/ms
Iteration   2: 10.637 ops/ms
Iteration   3: 9.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.373 ±(99.9%) 7.166 ops/ms [Average]
  (min, avg, max) = (9.922, 10.373, 10.637), stdev = 0.393
  CI (99.9%): [3.208, 17.539] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.366 ops/ms
# Warmup Iteration   2: 9.475 ops/ms
# Warmup Iteration   3: 9.560 ops/ms
Iteration   1: 10.016 ops/ms
Iteration   2: 9.822 ops/ms
Iteration   3: 9.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.942 ±(99.9%) 1.904 ops/ms [Average]
  (min, avg, max) = (9.822, 9.942, 10.016), stdev = 0.104
  CI (99.9%): [8.037, 11.846] (assumes normal distribution)


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
# Warmup Iteration   1: 3.336 ops/ms
# Warmup Iteration   2: 8.047 ops/ms
# Warmup Iteration   3: 8.544 ops/ms
Iteration   1: 8.444 ops/ms
Iteration   2: 8.650 ops/ms
Iteration   3: 8.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.645 ±(99.9%) 3.625 ops/ms [Average]
  (min, avg, max) = (8.444, 8.645, 8.841), stdev = 0.199
  CI (99.9%): [5.020, 12.269] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.864 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.007 ms/op
Iteration   1: 3.278 ±(99.9%) 0.005 ms/op
Iteration   2: 3.184 ±(99.9%) 0.004 ms/op
Iteration   3: 3.223 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.228 ±(99.9%) 0.865 ms/op [Average]
  (min, avg, max) = (3.184, 3.228, 3.278), stdev = 0.047
  CI (99.9%): [2.364, 4.093] (assumes normal distribution)


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
# Warmup Iteration   1: 7.209 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.002 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
Iteration   2: 3.119 ±(99.9%) 0.009 ms/op
Iteration   3: 3.056 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.069 ±(99.9%) 0.812 ms/op [Average]
  (min, avg, max) = (3.033, 3.069, 3.119), stdev = 0.044
  CI (99.9%): [2.257, 3.881] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.479 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.449 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.005 ms/op
Iteration   1: 3.245 ±(99.9%) 0.008 ms/op
Iteration   2: 3.305 ±(99.9%) 0.004 ms/op
Iteration   3: 3.270 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.273 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (3.245, 3.273, 3.305), stdev = 0.030
  CI (99.9%): [2.729, 3.818] (assumes normal distribution)


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
# Warmup Iteration   1: 8.609 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.005 ms/op
Iteration   1: 3.622 ±(99.9%) 0.011 ms/op
Iteration   2: 3.657 ±(99.9%) 0.012 ms/op
Iteration   3: 3.665 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.648 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.622, 3.648, 3.665), stdev = 0.023
  CI (99.9%): [3.225, 4.071] (assumes normal distribution)


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
# Warmup Iteration   1: 8.215 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
Iteration   1: 3.208 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  17.554 ms/op
                 createUser·p0.9999: 20.450 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 3.201 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  17.797 ms/op
                 createUser·p0.9999: 20.677 ms/op
                 createUser·p1.00:   21.234 ms/op

Iteration   3: 3.111 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.322 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   5.386 ms/op
                 createUser·p0.999:  14.909 ms/op
                 createUser·p0.9999: 35.062 ms/op
                 createUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302325
  mean =      3.173 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23238 
    [ 2.500,  5.000) = 272802 
    [ 5.000,  7.500) = 5327 
    [ 7.500, 10.000) = 373 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 180 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     16.002 ms/op
     p(99.9900) =     33.817 ms/op
     p(99.9990) =     35.191 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 7.167 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.414 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.009 ms/op
Iteration   1: 2.984 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.146 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  9.503 ms/op
                 existUser·p0.9999: 19.956 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   2: 3.059 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  12.861 ms/op
                 existUser·p0.9999: 26.938 ms/op
                 existUser·p1.00:   27.787 ms/op

Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.367 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  16.531 ms/op
                 existUser·p0.9999: 20.972 ms/op
                 existUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 317236
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17295 
    [ 2.500,  5.000) = 295684 
    [ 5.000,  7.500) = 3618 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.199 ms/op
     p(95.0000) =      3.408 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     14.738 ms/op
     p(99.9900) =     25.366 ms/op
     p(99.9990) =     27.732 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 7.685 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.010 ms/op
Iteration   1: 3.141 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  16.785 ms/op
                 getUser·p0.9999: 20.310 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  13.276 ms/op
                 getUser·p0.9999: 19.434 ms/op
                 getUser·p1.00:   20.578 ms/op

Iteration   3: 3.366 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  17.594 ms/op
                 getUser·p0.9999: 24.967 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296518
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16285 
    [ 2.500,  5.000) = 271486 
    [ 5.000,  7.500) = 7680 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 203 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     16.440 ms/op
     p(99.9900) =     23.388 ms/op
     p(99.9990) =     25.565 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 9.385 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.012 ms/op
Iteration   1: 3.738 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 24.478 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  12.796 ms/op
                 listUser·p0.9999: 18.594 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 3.682 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.841 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  12.583 ms/op
                 listUser·p0.9999: 14.914 ms/op
                 listUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258079
  mean =      3.721 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 250114 
    [ 5.000,  7.500) = 6139 
    [ 7.500, 10.000) = 967 
    [10.000, 12.500) = 359 
    [12.500, 15.000) = 305 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.785 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     25.573 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.007 ± 4.926  ops/ms
ClientPb.existUser                       thrpt       3  10.373 ± 7.166  ops/ms
ClientPb.getUser                         thrpt       3   9.942 ± 1.904  ops/ms
ClientPb.listUser                        thrpt       3   8.645 ± 3.625  ops/ms
ClientPb.createUser                       avgt       3   3.228 ± 0.865   ms/op
ClientPb.existUser                        avgt       3   3.069 ± 0.812   ms/op
ClientPb.getUser                          avgt       3   3.273 ± 0.545   ms/op
ClientPb.listUser                         avgt       3   3.648 ± 0.423   ms/op
ClientPb.createUser                     sample  302325   3.173 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.957           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.002           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.817           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.848           ms/op
ClientPb.existUser                      sample  317236   3.024 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.904           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.738           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.366           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.787           ms/op
ClientPb.getUser                        sample  296518   3.235 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.130           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.682           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.440           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.388           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.788           ms/op
ClientPb.listUser                       sample  258079   3.721 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.997           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.785           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.025           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.938           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.756           ms/op
