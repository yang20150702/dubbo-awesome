# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.617 ops/ms
# Warmup Iteration   2: 6.619 ops/ms
# Warmup Iteration   3: 9.225 ops/ms
Iteration   1: 9.962 ops/ms
Iteration   2: 10.207 ops/ms
Iteration   3: 9.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.983 ±(99.9%) 3.924 ops/ms [Average]
  (min, avg, max) = (9.778, 9.983, 10.207), stdev = 0.215
  CI (99.9%): [6.059, 13.907] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ops/ms
# Warmup Iteration   2: 9.352 ops/ms
# Warmup Iteration   3: 10.524 ops/ms
Iteration   1: 10.557 ops/ms
Iteration   2: 10.274 ops/ms
Iteration   3: 10.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.410 ±(99.9%) 2.594 ops/ms [Average]
  (min, avg, max) = (10.274, 10.410, 10.557), stdev = 0.142
  CI (99.9%): [7.815, 13.004] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.576 ops/ms
# Warmup Iteration   2: 8.321 ops/ms
# Warmup Iteration   3: 9.882 ops/ms
Iteration   1: 10.038 ops/ms
Iteration   2: 10.170 ops/ms
Iteration   3: 10.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.093 ±(99.9%) 1.261 ops/ms [Average]
  (min, avg, max) = (10.038, 10.093, 10.170), stdev = 0.069
  CI (99.9%): [8.832, 11.354] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.129 ops/ms
# Warmup Iteration   2: 7.622 ops/ms
# Warmup Iteration   3: 8.436 ops/ms
Iteration   1: 8.503 ops/ms
Iteration   2: 8.326 ops/ms
Iteration   3: 8.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.470 ±(99.9%) 2.376 ops/ms [Average]
  (min, avg, max) = (8.326, 8.470, 8.581), stdev = 0.130
  CI (99.9%): [6.094, 10.846] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.216 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.002 ms/op
Iteration   1: 3.114 ±(99.9%) 0.004 ms/op
Iteration   2: 3.088 ±(99.9%) 0.005 ms/op
Iteration   3: 3.295 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.166 ±(99.9%) 2.063 ms/op [Average]
  (min, avg, max) = (3.088, 3.166, 3.295), stdev = 0.113
  CI (99.9%): [1.103, 5.228] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.298 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.003 ms/op
Iteration   1: 3.051 ±(99.9%) 0.005 ms/op
Iteration   2: 3.015 ±(99.9%) 0.002 ms/op
Iteration   3: 3.113 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.060 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (3.015, 3.060, 3.113), stdev = 0.049
  CI (99.9%): [2.162, 3.957] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.281 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.004 ms/op
Iteration   1: 3.219 ±(99.9%) 0.007 ms/op
Iteration   2: 3.132 ±(99.9%) 0.008 ms/op
Iteration   3: 3.195 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.182 ±(99.9%) 0.816 ms/op [Average]
  (min, avg, max) = (3.132, 3.182, 3.219), stdev = 0.045
  CI (99.9%): [2.366, 3.998] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.336 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.005 ms/op
Iteration   1: 3.672 ±(99.9%) 0.007 ms/op
Iteration   2: 3.705 ±(99.9%) 0.008 ms/op
Iteration   3: 3.683 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.687 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (3.672, 3.687, 3.705), stdev = 0.017
  CI (99.9%): [3.373, 4.000] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.193 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.520 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.012 ms/op
Iteration   1: 3.246 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.413 ms/op
                 createUser·p0.999:  15.972 ms/op
                 createUser·p0.9999: 20.247 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  8.091 ms/op
                 createUser·p0.9999: 27.686 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   3: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  15.353 ms/op
                 createUser·p0.9999: 24.835 ms/op
                 createUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299817
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22078 
    [ 2.500,  5.000) = 272244 
    [ 5.000,  7.500) = 4747 
    [ 7.500, 10.000) = 354 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     15.091 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     28.148 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.737 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.008 ms/op
Iteration   1: 3.197 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  8.003 ms/op
                 existUser·p0.9999: 17.465 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  10.371 ms/op
                 existUser·p0.9999: 20.432 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.505 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  9.650 ms/op
                 existUser·p0.9999: 22.789 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309955
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14360 
    [ 2.500,  5.000) = 290309 
    [ 5.000,  7.500) = 4683 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     23.233 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.598 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
Iteration   1: 3.269 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  19.366 ms/op
                 getUser·p0.9999: 26.948 ms/op
                 getUser·p1.00:   40.829 ms/op

Iteration   2: 3.297 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 23.439 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   3: 3.310 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  9.772 ms/op
                 getUser·p0.9999: 19.193 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291596
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 282474 
    [ 5.000, 10.000) = 8778 
    [10.000, 15.000) = 45 
    [15.000, 20.000) = 140 
    [20.000, 25.000) = 122 
    [25.000, 30.000) = 29 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     16.620 ms/op
     p(99.9900) =     25.292 ms/op
     p(99.9990) =     38.797 ms/op
     p(99.9999) =     40.829 ms/op
    p(100.0000) =     40.829 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.496 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.013 ms/op
Iteration   1: 3.757 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 19.118 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   2: 3.723 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   7.011 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 19.041 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   3: 3.716 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  12.616 ms/op
                 listUser·p0.9999: 13.453 ms/op
                 listUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257284
  mean =      3.732 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 249550 
    [ 5.000,  7.500) = 5882 
    [ 7.500, 10.000) = 1123 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     18.502 ms/op
     p(99.9990) =     19.529 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.983 ± 3.924  ops/ms
ClientPb.existUser                       thrpt       3  10.410 ± 2.594  ops/ms
ClientPb.getUser                         thrpt       3  10.093 ± 1.261  ops/ms
ClientPb.listUser                        thrpt       3   8.470 ± 2.376  ops/ms
ClientPb.createUser                       avgt       3   3.166 ± 2.063   ms/op
ClientPb.existUser                        avgt       3   3.060 ± 0.898   ms/op
ClientPb.getUser                          avgt       3   3.182 ± 0.816   ms/op
ClientPb.listUser                         avgt       3   3.687 ± 0.314   ms/op
ClientPb.createUser                     sample  299817   3.202 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.634           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.091           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.625           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.672           ms/op
ClientPb.existUser                      sample  309955   3.094 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.900           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.552           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.398           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.527           ms/op
ClientPb.getUser                        sample  291596   3.292 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.994           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.620           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.292           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.829           ms/op
ClientPb.listUser                       sample  257284   3.732 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.307           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.816           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.255           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.502           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.021           ms/op
