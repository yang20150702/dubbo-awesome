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
# Warmup Iteration   1: 2.640 ops/ms
# Warmup Iteration   2: 5.765 ops/ms
# Warmup Iteration   3: 8.973 ops/ms
Iteration   1: 9.395 ops/ms
Iteration   2: 9.834 ops/ms
Iteration   3: 10.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.778 ±(99.9%) 6.540 ops/ms [Average]
  (min, avg, max) = (9.395, 9.778, 10.105), stdev = 0.358
  CI (99.9%): [3.238, 16.317] (assumes normal distribution)


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
# Warmup Iteration   1: 4.098 ops/ms
# Warmup Iteration   2: 9.669 ops/ms
# Warmup Iteration   3: 9.932 ops/ms
Iteration   1: 10.314 ops/ms
Iteration   2: 10.777 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.511 ±(99.9%) 4.358 ops/ms [Average]
  (min, avg, max) = (10.314, 10.511, 10.777), stdev = 0.239
  CI (99.9%): [6.152, 14.869] (assumes normal distribution)


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
# Warmup Iteration   1: 3.157 ops/ms
# Warmup Iteration   2: 9.339 ops/ms
# Warmup Iteration   3: 10.268 ops/ms
Iteration   1: 10.248 ops/ms
Iteration   2: 10.129 ops/ms
Iteration   3: 9.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.053 ±(99.9%) 4.398 ops/ms [Average]
  (min, avg, max) = (9.783, 10.053, 10.248), stdev = 0.241
  CI (99.9%): [5.655, 14.452] (assumes normal distribution)


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
# Warmup Iteration   1: 3.275 ops/ms
# Warmup Iteration   2: 7.730 ops/ms
# Warmup Iteration   3: 8.334 ops/ms
Iteration   1: 8.480 ops/ms
Iteration   2: 8.643 ops/ms
Iteration   3: 8.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.504 ±(99.9%) 2.347 ops/ms [Average]
  (min, avg, max) = (8.390, 8.504, 8.643), stdev = 0.129
  CI (99.9%): [6.158, 10.851] (assumes normal distribution)


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
# Warmup Iteration   1: 8.027 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.007 ms/op
Iteration   1: 3.212 ±(99.9%) 0.004 ms/op
Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
Iteration   3: 3.081 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.148 ±(99.9%) 1.196 ms/op [Average]
  (min, avg, max) = (3.081, 3.148, 3.212), stdev = 0.066
  CI (99.9%): [1.952, 4.344] (assumes normal distribution)


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
# Warmup Iteration   1: 7.633 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.003 ms/op
Iteration   1: 3.007 ±(99.9%) 0.002 ms/op
Iteration   2: 2.979 ±(99.9%) 0.005 ms/op
Iteration   3: 2.986 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.991 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.979, 2.991, 3.007), stdev = 0.015
  CI (99.9%): [2.720, 3.261] (assumes normal distribution)


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
# Warmup Iteration   1: 7.937 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.001 ms/op
Iteration   1: 3.238 ±(99.9%) 0.006 ms/op
Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
Iteration   3: 3.140 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.159 ±(99.9%) 1.297 ms/op [Average]
  (min, avg, max) = (3.100, 3.159, 3.238), stdev = 0.071
  CI (99.9%): [1.863, 4.456] (assumes normal distribution)


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
# Warmup Iteration   1: 8.042 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.007 ms/op
Iteration   1: 3.745 ±(99.9%) 0.006 ms/op
Iteration   2: 3.709 ±(99.9%) 0.008 ms/op
Iteration   3: 3.681 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.712 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (3.681, 3.712, 3.745), stdev = 0.033
  CI (99.9%): [3.119, 4.305] (assumes normal distribution)


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
# Warmup Iteration   1: 8.573 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.008 ms/op
Iteration   1: 3.200 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  18.024 ms/op
                 createUser·p0.9999: 22.512 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   2: 3.163 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.706 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.297 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  19.719 ms/op
                 createUser·p0.9999: 22.279 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 3.131 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.531 ms/op
                 createUser·p0.99:   5.054 ms/op
                 createUser·p0.999:  8.946 ms/op
                 createUser·p0.9999: 16.406 ms/op
                 createUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303176
  mean =      3.164 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29913 
    [ 2.500,  5.000) = 268010 
    [ 5.000,  7.500) = 4493 
    [ 7.500, 10.000) = 385 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     15.081 ms/op
     p(99.9900) =     22.305 ms/op
     p(99.9990) =     23.445 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 6.756 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
Iteration   1: 3.048 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.254 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.368 ms/op
                 existUser·p0.999:  11.088 ms/op
                 existUser·p0.9999: 18.005 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   2: 3.076 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  8.358 ms/op
                 existUser·p0.9999: 22.853 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   4.917 ms/op
                 existUser·p0.999:  14.549 ms/op
                 existUser·p0.9999: 22.205 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315799
  mean =      3.039 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20390 
    [ 2.500,  5.000) = 291230 
    [ 5.000,  7.500) = 3514 
    [ 7.500, 10.000) = 271 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.465 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =     12.570 ms/op
     p(99.9900) =     22.099 ms/op
     p(99.9990) =     23.358 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 7.005 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.009 ms/op
Iteration   1: 3.212 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  14.598 ms/op
                 getUser·p0.9999: 23.167 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 3.331 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  19.070 ms/op
                 getUser·p0.9999: 22.839 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  14.794 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291217
  mean =      3.295 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24431 
    [ 2.500,  5.000) = 256837 
    [ 5.000,  7.500) = 8772 
    [ 7.500, 10.000) = 641 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     25.103 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 9.253 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.013 ms/op
Iteration   1: 3.729 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  14.305 ms/op
                 listUser·p0.9999: 18.816 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 3.710 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.121 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  12.796 ms/op
                 listUser·p0.9999: 14.968 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 3.881 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.759 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 19.686 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254389
  mean =      3.772 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 96 
    [ 2.500,  3.750) = 181982 
    [ 3.750,  5.000) = 65052 
    [ 5.000,  6.250) = 3020 
    [ 6.250,  7.500) = 2690 
    [ 7.500,  8.750) = 626 
    [ 8.750, 10.000) = 258 
    [10.000, 11.250) = 187 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 193 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     19.319 ms/op
     p(99.9990) =     19.807 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.778 ± 6.540  ops/ms
ClientPb.existUser                       thrpt       3  10.511 ± 4.358  ops/ms
ClientPb.getUser                         thrpt       3  10.053 ± 4.398  ops/ms
ClientPb.listUser                        thrpt       3   8.504 ± 2.347  ops/ms
ClientPb.createUser                       avgt       3   3.148 ± 1.196   ms/op
ClientPb.existUser                        avgt       3   2.991 ± 0.271   ms/op
ClientPb.getUser                          avgt       3   3.159 ± 1.297   ms/op
ClientPb.listUser                         avgt       3   3.712 ± 0.593   ms/op
ClientPb.createUser                     sample  303176   3.164 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.039           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.081           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.305           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.216           ms/op
ClientPb.existUser                      sample  315799   3.039 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.149           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.570           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.099           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.691           ms/op
ClientPb.getUser                        sample  291217   3.295 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.922           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.423           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.843           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.331           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.264           ms/op
ClientPb.listUser                       sample  254389   3.772 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.321           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.162           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.726           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.058           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.319           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.825           ms/op
