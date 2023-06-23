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
# Warmup Iteration   1: 2.538 ops/ms
# Warmup Iteration   2: 6.811 ops/ms
# Warmup Iteration   3: 9.074 ops/ms
Iteration   1: 9.688 ops/ms
Iteration   2: 9.889 ops/ms
Iteration   3: 9.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.780 ±(99.9%) 1.853 ops/ms [Average]
  (min, avg, max) = (9.688, 9.780, 9.889), stdev = 0.102
  CI (99.9%): [7.926, 11.633] (assumes normal distribution)


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
# Warmup Iteration   1: 3.505 ops/ms
# Warmup Iteration   2: 9.631 ops/ms
# Warmup Iteration   3: 9.872 ops/ms
Iteration   1: 10.201 ops/ms
Iteration   2: 10.251 ops/ms
Iteration   3: 10.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.356 ±(99.9%) 4.128 ops/ms [Average]
  (min, avg, max) = (10.201, 10.356, 10.616), stdev = 0.226
  CI (99.9%): [6.228, 14.484] (assumes normal distribution)


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
# Warmup Iteration   1: 3.946 ops/ms
# Warmup Iteration   2: 8.543 ops/ms
# Warmup Iteration   3: 9.445 ops/ms
Iteration   1: 9.937 ops/ms
Iteration   2: 9.871 ops/ms
Iteration   3: 10.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.022 ±(99.9%) 3.778 ops/ms [Average]
  (min, avg, max) = (9.871, 10.022, 10.258), stdev = 0.207
  CI (99.9%): [6.244, 13.800] (assumes normal distribution)


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
# Warmup Iteration   1: 3.415 ops/ms
# Warmup Iteration   2: 7.593 ops/ms
# Warmup Iteration   3: 8.315 ops/ms
Iteration   1: 8.376 ops/ms
Iteration   2: 8.480 ops/ms
Iteration   3: 8.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.574 ±(99.9%) 4.705 ops/ms [Average]
  (min, avg, max) = (8.376, 8.574, 8.865), stdev = 0.258
  CI (99.9%): [3.869, 13.279] (assumes normal distribution)


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
# Warmup Iteration   1: 7.584 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.003 ms/op
Iteration   1: 3.130 ±(99.9%) 0.005 ms/op
Iteration   2: 3.231 ±(99.9%) 0.007 ms/op
Iteration   3: 3.295 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.219 ±(99.9%) 1.522 ms/op [Average]
  (min, avg, max) = (3.130, 3.219, 3.295), stdev = 0.083
  CI (99.9%): [1.696, 4.741] (assumes normal distribution)


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
# Warmup Iteration   1: 7.319 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.005 ms/op
Iteration   1: 3.112 ±(99.9%) 0.009 ms/op
Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
Iteration   3: 3.006 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.044 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (3.006, 3.044, 3.112), stdev = 0.059
  CI (99.9%): [1.970, 4.118] (assumes normal distribution)


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
# Warmup Iteration   1: 7.938 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.005 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
Iteration   2: 3.280 ±(99.9%) 0.006 ms/op
Iteration   3: 3.176 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.193 ±(99.9%) 1.449 ms/op [Average]
  (min, avg, max) = (3.124, 3.193, 3.280), stdev = 0.079
  CI (99.9%): [1.745, 4.642] (assumes normal distribution)


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
# Warmup Iteration   1: 9.316 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.007 ms/op
Iteration   1: 3.696 ±(99.9%) 0.011 ms/op
Iteration   2: 3.753 ±(99.9%) 0.006 ms/op
Iteration   3: 3.800 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.749 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (3.696, 3.749, 3.800), stdev = 0.052
  CI (99.9%): [2.800, 4.698] (assumes normal distribution)


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
# Warmup Iteration   1: 8.435 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.009 ms/op
Iteration   1: 3.115 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.232 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  17.547 ms/op
                 createUser·p0.9999: 20.513 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   2: 3.255 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 21.338 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   3: 3.136 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.714 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  10.322 ms/op
                 createUser·p0.9999: 18.317 ms/op
                 createUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302523
  mean =      3.167 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29129 
    [ 2.500,  5.000) = 268664 
    [ 5.000,  7.500) = 3743 
    [ 7.500, 10.000) = 341 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 194 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     16.857 ms/op
     p(99.9900) =     20.504 ms/op
     p(99.9990) =     22.511 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 7.756 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.449 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.008 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  11.537 ms/op
                 existUser·p0.9999: 23.164 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.247 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   5.214 ms/op
                 existUser·p0.999:  14.402 ms/op
                 existUser·p0.9999: 21.398 ms/op
                 existUser·p1.00:   22.479 ms/op

Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  8.961 ms/op
                 existUser·p0.9999: 19.548 ms/op
                 existUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307143
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27353 
    [ 2.500,  5.000) = 274257 
    [ 5.000,  7.500) = 4986 
    [ 7.500, 10.000) = 137 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     13.013 ms/op
     p(99.9900) =     21.688 ms/op
     p(99.9990) =     23.359 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 7.155 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.010 ms/op
Iteration   1: 3.250 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  19.798 ms/op
                 getUser·p0.9999: 23.691 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 3.248 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.701 ms/op
                 getUser·p0.999:  10.633 ms/op
                 getUser·p0.9999: 28.148 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 3.272 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.751 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  10.508 ms/op
                 getUser·p0.9999: 18.914 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294689
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7824 
    [ 2.500,  5.000) = 276621 
    [ 5.000,  7.500) = 8921 
    [ 7.500, 10.000) = 813 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     27.018 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 8.760 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.011 ms/op
Iteration   1: 3.771 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  15.420 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 3.685 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   6.486 ms/op
                 listUser·p0.999:  13.074 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 3.681 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   3.994 ms/op
                 listUser·p0.99:   5.895 ms/op
                 listUser·p0.999:  12.583 ms/op
                 listUser·p0.9999: 13.506 ms/op
                 listUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258384
  mean =      3.712 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 251654 
    [ 5.000,  7.500) = 4989 
    [ 7.500, 10.000) = 1070 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.761 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.780 ± 1.853  ops/ms
ClientPb.existUser                       thrpt       3  10.356 ± 4.128  ops/ms
ClientPb.getUser                         thrpt       3  10.022 ± 3.778  ops/ms
ClientPb.listUser                        thrpt       3   8.574 ± 4.705  ops/ms
ClientPb.createUser                       avgt       3   3.219 ± 1.522   ms/op
ClientPb.existUser                        avgt       3   3.044 ± 1.074   ms/op
ClientPb.getUser                          avgt       3   3.193 ± 1.449   ms/op
ClientPb.listUser                         avgt       3   3.749 ± 0.949   ms/op
ClientPb.createUser                     sample  302523   3.167 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.124           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.857           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.504           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.970           ms/op
ClientPb.existUser                      sample  307143   3.121 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.247           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.251           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.013           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.688           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.626           ms/op
ClientPb.getUser                        sample  294689   3.257 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.083           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.625           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.447           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.533           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.018           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.312           ms/op
ClientPb.listUser                       sample  258384   3.712 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.761           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.714           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.628           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.266           ms/op
