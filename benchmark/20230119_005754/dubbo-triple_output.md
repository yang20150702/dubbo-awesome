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
# Warmup Iteration   1: 1.035 ops/ms
# Warmup Iteration   2: 2.313 ops/ms
# Warmup Iteration   3: 5.251 ops/ms
Iteration   1: 5.546 ops/ms
Iteration   2: 5.727 ops/ms
Iteration   3: 5.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.669 ±(99.9%) 1.948 ops/ms [Average]
  (min, avg, max) = (5.546, 5.669, 5.734), stdev = 0.107
  CI (99.9%): [3.721, 7.617] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.479 ops/ms
# Warmup Iteration   2: 4.367 ops/ms
# Warmup Iteration   3: 5.826 ops/ms
Iteration   1: 6.082 ops/ms
Iteration   2: 5.757 ops/ms
Iteration   3: 5.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.855 ±(99.9%) 3.589 ops/ms [Average]
  (min, avg, max) = (5.727, 5.855, 6.082), stdev = 0.197
  CI (99.9%): [2.267, 9.444] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.389 ops/ms
# Warmup Iteration   2: 4.064 ops/ms
# Warmup Iteration   3: 5.450 ops/ms
Iteration   1: 5.360 ops/ms
Iteration   2: 5.787 ops/ms
Iteration   3: 5.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.589 ±(99.9%) 3.921 ops/ms [Average]
  (min, avg, max) = (5.360, 5.589, 5.787), stdev = 0.215
  CI (99.9%): [1.668, 9.509] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.363 ops/ms
# Warmup Iteration   2: 3.215 ops/ms
# Warmup Iteration   3: 4.453 ops/ms
Iteration   1: 4.704 ops/ms
Iteration   2: 4.740 ops/ms
Iteration   3: 4.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.720 ±(99.9%) 0.332 ops/ms [Average]
  (min, avg, max) = (4.704, 4.720, 4.740), stdev = 0.018
  CI (99.9%): [4.388, 5.053] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.115 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 7.402 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.704 ±(99.9%) 0.012 ms/op
Iteration   1: 6.400 ±(99.9%) 0.012 ms/op
Iteration   2: 6.197 ±(99.9%) 0.018 ms/op
Iteration   3: 6.173 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.257 ±(99.9%) 2.274 ms/op [Average]
  (min, avg, max) = (6.173, 6.257, 6.400), stdev = 0.125
  CI (99.9%): [3.983, 8.531] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 21.158 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 7.964 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.941 ±(99.9%) 0.011 ms/op
Iteration   1: 5.732 ±(99.9%) 0.010 ms/op
Iteration   2: 5.750 ±(99.9%) 0.010 ms/op
Iteration   3: 5.625 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.703 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (5.625, 5.703, 5.750), stdev = 0.068
  CI (99.9%): [4.466, 6.939] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 20.101 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 8.070 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.322 ±(99.9%) 0.011 ms/op
Iteration   1: 6.023 ±(99.9%) 0.014 ms/op
Iteration   2: 6.284 ±(99.9%) 0.011 ms/op
Iteration   3: 6.024 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.110 ±(99.9%) 2.749 ms/op [Average]
  (min, avg, max) = (6.023, 6.110, 6.284), stdev = 0.151
  CI (99.9%): [3.361, 8.860] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.391 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 9.131 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.898 ±(99.9%) 0.017 ms/op
Iteration   1: 6.787 ±(99.9%) 0.010 ms/op
Iteration   2: 6.629 ±(99.9%) 0.018 ms/op
Iteration   3: 6.802 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.739 ±(99.9%) 1.748 ms/op [Average]
  (min, avg, max) = (6.629, 6.739, 6.802), stdev = 0.096
  CI (99.9%): [4.991, 8.487] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 21.684 ±(99.9%) 0.385 ms/op
# Warmup Iteration   2: 7.824 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.810 ±(99.9%) 0.043 ms/op
Iteration   1: 6.117 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.372 ms/op
                 createUser·p0.50:   5.571 ms/op
                 createUser·p0.90:   8.348 ms/op
                 createUser·p0.95:   9.568 ms/op
                 createUser·p0.99:   12.288 ms/op
                 createUser·p0.999:  28.106 ms/op
                 createUser·p0.9999: 36.110 ms/op
                 createUser·p1.00:   36.700 ms/op

Iteration   2: 6.022 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.466 ms/op
                 createUser·p0.50:   5.513 ms/op
                 createUser·p0.90:   8.167 ms/op
                 createUser·p0.95:   9.372 ms/op
                 createUser·p0.99:   12.091 ms/op
                 createUser·p0.999:  27.881 ms/op
                 createUser·p0.9999: 30.728 ms/op
                 createUser·p1.00:   31.523 ms/op

Iteration   3: 5.804 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   7.553 ms/op
                 createUser·p0.95:   8.782 ms/op
                 createUser·p0.99:   11.796 ms/op
                 createUser·p0.999:  33.024 ms/op
                 createUser·p0.9999: 37.125 ms/op
                 createUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 160574
  mean =      5.978 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 42415 
    [ 5.000,  7.500) = 96988 
    [ 7.500, 10.000) = 15948 
    [10.000, 12.500) = 3897 
    [12.500, 15.000) = 870 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 52 
    [35.000, 37.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      8.036 ms/op
     p(95.0000) =      9.290 ms/op
     p(99.0000) =     12.157 ms/op
     p(99.9000) =     29.079 ms/op
     p(99.9900) =     36.107 ms/op
     p(99.9990) =     38.102 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.242 ±(99.9%) 0.309 ms/op
# Warmup Iteration   2: 6.222 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.405 ±(99.9%) 0.023 ms/op
Iteration   1: 5.744 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.044 ms/op
                 existUser·p0.50:   5.226 ms/op
                 existUser·p0.90:   7.897 ms/op
                 existUser·p0.95:   9.060 ms/op
                 existUser·p0.99:   11.616 ms/op
                 existUser·p0.999:  28.343 ms/op
                 existUser·p0.9999: 34.135 ms/op
                 existUser·p1.00:   36.176 ms/op

Iteration   2: 5.385 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.413 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.808 ms/op
                 existUser·p0.95:   7.823 ms/op
                 existUser·p0.99:   10.813 ms/op
                 existUser·p0.999:  28.727 ms/op
                 existUser·p0.9999: 32.737 ms/op
                 existUser·p1.00:   33.522 ms/op

Iteration   3: 5.603 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.944 ms/op
                 existUser·p0.50:   5.202 ms/op
                 existUser·p0.90:   7.299 ms/op
                 existUser·p0.95:   8.356 ms/op
                 existUser·p0.99:   10.895 ms/op
                 existUser·p0.999:  16.557 ms/op
                 existUser·p0.9999: 35.998 ms/op
                 existUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 172126
  mean =      5.573 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 73085 
    [ 5.000,  7.500) = 83375 
    [ 7.500, 10.000) = 12360 
    [10.000, 12.500) = 2515 
    [12.500, 15.000) = 465 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.944 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.520 ms/op
     p(99.0000) =     11.158 ms/op
     p(99.9000) =     23.134 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     36.409 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.553 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 6.545 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.518 ±(99.9%) 0.022 ms/op
Iteration   1: 5.784 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.789 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   7.651 ms/op
                 getUser·p0.95:   8.946 ms/op
                 getUser·p0.99:   13.648 ms/op
                 getUser·p0.999:  19.399 ms/op
                 getUser·p0.9999: 32.021 ms/op
                 getUser·p1.00:   33.522 ms/op

Iteration   2: 5.464 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.265 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.980 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   10.895 ms/op
                 getUser·p0.999:  27.651 ms/op
                 getUser·p0.9999: 32.985 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   3: 5.416 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.068 ms/op
                 getUser·p0.50:   5.054 ms/op
                 getUser·p0.90:   6.971 ms/op
                 getUser·p0.95:   7.930 ms/op
                 getUser·p0.99:   10.617 ms/op
                 getUser·p0.999:  34.733 ms/op
                 getUser·p0.9999: 37.460 ms/op
                 getUser·p1.00:   38.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172853
  mean =      5.550 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 73976 
    [ 5.000,  7.500) = 84488 
    [ 7.500, 10.000) = 10705 
    [10.000, 12.500) = 2521 
    [12.500, 15.000) = 667 
    [15.000, 17.500) = 222 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      2.068 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.502 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     36.466 ms/op
     p(99.9990) =     38.750 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


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
# Warmup Iteration   1: 19.176 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 9.191 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 7.088 ±(99.9%) 0.037 ms/op
Iteration   1: 6.494 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   9.585 ms/op
                 listUser·p0.99:   12.337 ms/op
                 listUser·p0.999:  25.835 ms/op
                 listUser·p0.9999: 30.278 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   2: 7.077 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   6.439 ms/op
                 listUser·p0.90:   9.616 ms/op
                 listUser·p0.95:   11.108 ms/op
                 listUser·p0.99:   13.615 ms/op
                 listUser·p0.999:  30.070 ms/op
                 listUser·p0.9999: 35.258 ms/op
                 listUser·p1.00:   36.110 ms/op

Iteration   3: 6.909 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   9.175 ms/op
                 listUser·p0.95:   10.551 ms/op
                 listUser·p0.99:   13.633 ms/op
                 listUser·p0.999:  30.736 ms/op
                 listUser·p0.9999: 38.166 ms/op
                 listUser·p1.00:   38.273 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140754
  mean =      6.818 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 6536 
    [ 5.000,  7.500) = 103289 
    [ 7.500, 10.000) = 22107 
    [10.000, 12.500) = 6540 
    [12.500, 15.000) = 1556 
    [15.000, 17.500) = 364 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.224 ms/op
     p(50.0000) =      6.267 ms/op
     p(90.0000) =      9.077 ms/op
     p(95.0000) =     10.437 ms/op
     p(99.0000) =     13.337 ms/op
     p(99.9000) =     28.360 ms/op
     p(99.9900) =     37.285 ms/op
     p(99.9990) =     38.246 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.669 ± 1.948  ops/ms
ClientPb.existUser                       thrpt       3   5.855 ± 3.589  ops/ms
ClientPb.getUser                         thrpt       3   5.589 ± 3.921  ops/ms
ClientPb.listUser                        thrpt       3   4.720 ± 0.332  ops/ms
ClientPb.createUser                       avgt       3   6.257 ± 2.274   ms/op
ClientPb.existUser                        avgt       3   5.703 ± 1.236   ms/op
ClientPb.getUser                          avgt       3   6.110 ± 2.749   ms/op
ClientPb.listUser                         avgt       3   6.739 ± 1.748   ms/op
ClientPb.createUser                     sample  160574   5.978 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.968           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.90    sample           8.036           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.290           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.157           ms/op
ClientPb.createUser:createUser·p0.999   sample          29.079           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.107           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.142           ms/op
ClientPb.existUser                      sample  172126   5.573 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.944           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.145           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.324           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.520           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.158           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.134           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.996           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.504           ms/op
ClientPb.getUser                        sample  172853   5.550 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.068           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.176           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.438           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.502           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.644           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.466           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.797           ms/op
ClientPb.listUser                       sample  140754   6.818 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.224           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.267           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.077           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.437           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.337           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.360           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.285           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.273           ms/op
