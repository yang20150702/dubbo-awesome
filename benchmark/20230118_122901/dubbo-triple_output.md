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
# Warmup Iteration   1: 2.702 ops/ms
# Warmup Iteration   2: 5.974 ops/ms
# Warmup Iteration   3: 9.697 ops/ms
Iteration   1: 9.889 ops/ms
Iteration   2: 10.080 ops/ms
Iteration   3: 10.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.067 ±(99.9%) 3.128 ops/ms [Average]
  (min, avg, max) = (9.889, 10.067, 10.231), stdev = 0.171
  CI (99.9%): [6.938, 13.195] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ops/ms
# Warmup Iteration   2: 9.384 ops/ms
# Warmup Iteration   3: 9.756 ops/ms
Iteration   1: 10.522 ops/ms
Iteration   2: 10.125 ops/ms
Iteration   3: 10.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.378 ±(99.9%) 4.005 ops/ms [Average]
  (min, avg, max) = (10.125, 10.378, 10.522), stdev = 0.220
  CI (99.9%): [6.373, 14.383] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.716 ops/ms
# Warmup Iteration   2: 9.312 ops/ms
# Warmup Iteration   3: 9.569 ops/ms
Iteration   1: 9.987 ops/ms
Iteration   2: 10.210 ops/ms
Iteration   3: 10.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.126 ±(99.9%) 2.215 ops/ms [Average]
  (min, avg, max) = (9.987, 10.126, 10.210), stdev = 0.121
  CI (99.9%): [7.911, 12.341] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.155 ops/ms
# Warmup Iteration   2: 6.875 ops/ms
# Warmup Iteration   3: 8.419 ops/ms
Iteration   1: 8.258 ops/ms
Iteration   2: 8.379 ops/ms
Iteration   3: 8.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.463 ±(99.9%) 4.693 ops/ms [Average]
  (min, avg, max) = (8.258, 8.463, 8.751), stdev = 0.257
  CI (99.9%): [3.770, 13.156] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.084 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.398 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.003 ms/op
Iteration   1: 3.151 ±(99.9%) 0.003 ms/op
Iteration   2: 3.148 ±(99.9%) 0.005 ms/op
Iteration   3: 3.149 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.149 ±(99.9%) 0.034 ms/op [Average]
  (min, avg, max) = (3.148, 3.149, 3.151), stdev = 0.002
  CI (99.9%): [3.115, 3.183] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.155 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.004 ms/op
Iteration   1: 3.078 ±(99.9%) 0.006 ms/op
Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
Iteration   3: 3.191 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.081 ±(99.9%) 1.982 ms/op [Average]
  (min, avg, max) = (2.973, 3.081, 3.191), stdev = 0.109
  CI (99.9%): [1.099, 5.062] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.291 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.003 ms/op
Iteration   1: 3.218 ±(99.9%) 0.007 ms/op
Iteration   2: 3.306 ±(99.9%) 0.004 ms/op
Iteration   3: 3.101 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.208 ±(99.9%) 1.876 ms/op [Average]
  (min, avg, max) = (3.101, 3.208, 3.306), stdev = 0.103
  CI (99.9%): [1.332, 5.085] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.842 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.006 ms/op
Iteration   1: 3.762 ±(99.9%) 0.008 ms/op
Iteration   2: 3.748 ±(99.9%) 0.008 ms/op
Iteration   3: 3.609 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.707 ±(99.9%) 1.540 ms/op [Average]
  (min, avg, max) = (3.609, 3.707, 3.762), stdev = 0.084
  CI (99.9%): [2.166, 5.247] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.397 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.009 ms/op
Iteration   1: 3.265 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   6.030 ms/op
                 createUser·p0.999:  12.403 ms/op
                 createUser·p0.9999: 22.879 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   2: 3.299 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.184 ms/op
                 createUser·p0.999:  17.202 ms/op
                 createUser·p0.9999: 26.115 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   3: 3.094 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  15.460 ms/op
                 createUser·p0.9999: 29.556 ms/op
                 createUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298162
  mean =      3.217 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26528 
    [ 2.500,  5.000) = 265066 
    [ 5.000,  7.500) = 5553 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     15.510 ms/op
     p(99.9900) =     28.186 ms/op
     p(99.9990) =     31.131 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.792 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
Iteration   1: 3.106 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  10.158 ms/op
                 existUser·p0.9999: 25.323 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   2: 3.121 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  14.647 ms/op
                 existUser·p0.9999: 21.791 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  10.379 ms/op
                 existUser·p0.9999: 20.834 ms/op
                 existUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307397
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28358 
    [ 2.500,  5.000) = 273941 
    [ 5.000,  7.500) = 4286 
    [ 7.500, 10.000) = 282 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     23.962 ms/op
     p(99.9990) =     25.947 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.027 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.010 ms/op
Iteration   1: 3.247 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  16.259 ms/op
                 getUser·p0.9999: 18.438 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   2: 3.187 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  10.268 ms/op
                 getUser·p0.9999: 27.034 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   3: 3.141 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  16.538 ms/op
                 getUser·p0.9999: 22.626 ms/op
                 getUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300671
  mean =      3.191 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9838 
    [ 2.500,  5.000) = 283764 
    [ 5.000,  7.500) = 5987 
    [ 7.500, 10.000) = 647 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     27.949 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.212 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.012 ms/op
Iteration   1: 3.974 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.314 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 20.412 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   2: 3.805 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  15.102 ms/op
                 listUser·p0.9999: 23.317 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   3: 3.834 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.172 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  13.200 ms/op
                 listUser·p0.9999: 16.613 ms/op
                 listUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248130
  mean =      3.870 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 145 
    [ 2.500,  5.000) = 236274 
    [ 5.000,  7.500) = 9620 
    [ 7.500, 10.000) = 1470 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.314 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     15.186 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     24.092 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.067 ± 3.128  ops/ms
ClientPb.existUser                       thrpt       3  10.378 ± 4.005  ops/ms
ClientPb.getUser                         thrpt       3  10.126 ± 2.215  ops/ms
ClientPb.listUser                        thrpt       3   8.463 ± 4.693  ops/ms
ClientPb.createUser                       avgt       3   3.149 ± 0.034   ms/op
ClientPb.existUser                        avgt       3   3.081 ± 1.982   ms/op
ClientPb.getUser                          avgt       3   3.208 ± 1.876   ms/op
ClientPb.listUser                         avgt       3   3.707 ± 1.540   ms/op
ClientPb.createUser                     sample  298162   3.217 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.882           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.510           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.186           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.261           ms/op
ClientPb.existUser                      sample  307397   3.121 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.845           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.270           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.962           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.051           ms/op
ClientPb.getUser                        sample  300671   3.191 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.842           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.514           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.833           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.269           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.592           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.295           ms/op
ClientPb.listUser                       sample  248130   3.870 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.314           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.274           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.186           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.807           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.805           ms/op
