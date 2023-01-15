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
# Warmup Iteration   1: 2.268 ops/ms
# Warmup Iteration   2: 5.958 ops/ms
# Warmup Iteration   3: 9.322 ops/ms
Iteration   1: 9.864 ops/ms
Iteration   2: 9.677 ops/ms
Iteration   3: 9.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.820 ±(99.9%) 2.325 ops/ms [Average]
  (min, avg, max) = (9.677, 9.820, 9.920), stdev = 0.127
  CI (99.9%): [7.495, 12.145] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.513 ops/ms
# Warmup Iteration   2: 9.269 ops/ms
# Warmup Iteration   3: 9.775 ops/ms
Iteration   1: 9.936 ops/ms
Iteration   2: 10.524 ops/ms
Iteration   3: 10.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.252 ±(99.9%) 5.410 ops/ms [Average]
  (min, avg, max) = (9.936, 10.252, 10.524), stdev = 0.297
  CI (99.9%): [4.843, 15.662] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.305 ops/ms
# Warmup Iteration   2: 9.089 ops/ms
# Warmup Iteration   3: 9.881 ops/ms
Iteration   1: 9.937 ops/ms
Iteration   2: 10.098 ops/ms
Iteration   3: 10.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.089 ±(99.9%) 2.685 ops/ms [Average]
  (min, avg, max) = (9.937, 10.089, 10.231), stdev = 0.147
  CI (99.9%): [7.403, 12.774] (assumes normal distribution)


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
# Warmup Iteration   1: 3.073 ops/ms
# Warmup Iteration   2: 7.438 ops/ms
# Warmup Iteration   3: 8.563 ops/ms
Iteration   1: 8.425 ops/ms
Iteration   2: 8.720 ops/ms
Iteration   3: 8.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.595 ±(99.9%) 2.785 ops/ms [Average]
  (min, avg, max) = (8.425, 8.595, 8.720), stdev = 0.153
  CI (99.9%): [5.810, 11.380] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.905 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.004 ms/op
Iteration   1: 3.202 ±(99.9%) 0.004 ms/op
Iteration   2: 3.156 ±(99.9%) 0.002 ms/op
Iteration   3: 3.139 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.166 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (3.139, 3.166, 3.202), stdev = 0.032
  CI (99.9%): [2.577, 3.754] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.693 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.003 ms/op
Iteration   1: 3.174 ±(99.9%) 0.006 ms/op
Iteration   2: 3.150 ±(99.9%) 0.006 ms/op
Iteration   3: 3.137 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.154 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (3.137, 3.154, 3.174), stdev = 0.019
  CI (99.9%): [2.811, 3.496] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.885 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.003 ms/op
Iteration   1: 3.233 ±(99.9%) 0.005 ms/op
Iteration   2: 3.252 ±(99.9%) 0.006 ms/op
Iteration   3: 3.133 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.206 ±(99.9%) 1.172 ms/op [Average]
  (min, avg, max) = (3.133, 3.206, 3.252), stdev = 0.064
  CI (99.9%): [2.034, 4.378] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.493 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.004 ms/op
Iteration   1: 3.677 ±(99.9%) 0.012 ms/op
Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
Iteration   3: 3.714 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.720 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (3.677, 3.720, 3.768), stdev = 0.046
  CI (99.9%): [2.887, 4.553] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.211 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.009 ms/op
Iteration   1: 3.217 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  17.007 ms/op
                 createUser·p0.9999: 20.054 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 21.266 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   3: 3.274 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  10.885 ms/op
                 createUser·p0.9999: 19.537 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298041
  mean =      3.219 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21114 
    [ 2.500,  5.000) = 271329 
    [ 5.000,  7.500) = 4712 
    [ 7.500, 10.000) = 401 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     15.317 ms/op
     p(99.9900) =     20.610 ms/op
     p(99.9990) =     21.538 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


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
# Warmup Iteration   1: 8.518 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
Iteration   1: 3.117 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  10.607 ms/op
                 existUser·p0.9999: 22.700 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  14.123 ms/op
                 existUser·p0.9999: 20.341 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   3: 3.116 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  13.713 ms/op
                 existUser·p0.9999: 21.502 ms/op
                 existUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307758
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13210 
    [ 2.500,  5.000) = 289097 
    [ 5.000,  7.500) = 4620 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     13.697 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     24.268 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 8.335 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.009 ms/op
Iteration   1: 3.182 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.741 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  14.952 ms/op
                 getUser·p0.9999: 21.296 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.307 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.831 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.700 ms/op
                 getUser·p0.999:  20.966 ms/op
                 getUser·p0.9999: 25.133 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.170 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  10.732 ms/op
                 getUser·p0.9999: 21.882 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298180
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10767 
    [ 2.500,  5.000) = 282232 
    [ 5.000,  7.500) = 3878 
    [ 7.500, 10.000) = 681 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     16.935 ms/op
     p(99.9900) =     23.304 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 11.275 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.370 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.013 ms/op
Iteration   1: 3.794 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.988 ms/op
                 listUser·p0.9999: 22.432 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   2: 3.770 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   3.945 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  14.356 ms/op
                 listUser·p0.9999: 17.187 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.778 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  12.998 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253665
  mean =      3.781 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 246997 
    [ 5.000,  7.500) = 4793 
    [ 7.500, 10.000) = 1038 
    [10.000, 12.500) = 365 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     21.689 ms/op
     p(99.9990) =     23.671 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.820 ± 2.325  ops/ms
ClientPb.existUser                       thrpt       3  10.252 ± 5.410  ops/ms
ClientPb.getUser                         thrpt       3  10.089 ± 2.685  ops/ms
ClientPb.listUser                        thrpt       3   8.595 ± 2.785  ops/ms
ClientPb.createUser                       avgt       3   3.166 ± 0.588   ms/op
ClientPb.existUser                        avgt       3   3.154 ± 0.343   ms/op
ClientPb.getUser                          avgt       3   3.206 ± 1.172   ms/op
ClientPb.listUser                         avgt       3   3.720 ± 0.833   ms/op
ClientPb.createUser                     sample  298041   3.219 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.819           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.551           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.317           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.610           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.512           ms/op
ClientPb.existUser                      sample  307758   3.118 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.245           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.464           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.697           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.660           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.773           ms/op
ClientPb.getUser                        sample  298180   3.219 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.956           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.568           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.546           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.935           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.304           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.280           ms/op
ClientPb.listUser                       sample  253665   3.781 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.671           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.840           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.451           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.689           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.953           ms/op
