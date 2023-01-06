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
# Warmup Iteration   1: 2.548 ops/ms
# Warmup Iteration   2: 6.030 ops/ms
# Warmup Iteration   3: 9.020 ops/ms
Iteration   1: 9.562 ops/ms
Iteration   2: 10.138 ops/ms
Iteration   3: 9.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.900 ±(99.9%) 5.485 ops/ms [Average]
  (min, avg, max) = (9.562, 9.900, 10.138), stdev = 0.301
  CI (99.9%): [4.415, 15.384] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.612 ops/ms
# Warmup Iteration   2: 9.417 ops/ms
# Warmup Iteration   3: 10.603 ops/ms
Iteration   1: 10.388 ops/ms
Iteration   2: 10.295 ops/ms
Iteration   3: 10.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.430 ±(99.9%) 2.923 ops/ms [Average]
  (min, avg, max) = (10.295, 10.430, 10.607), stdev = 0.160
  CI (99.9%): [7.506, 13.353] (assumes normal distribution)


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
# Warmup Iteration   1: 3.377 ops/ms
# Warmup Iteration   2: 9.325 ops/ms
# Warmup Iteration   3: 9.592 ops/ms
Iteration   1: 10.334 ops/ms
Iteration   2: 9.745 ops/ms
Iteration   3: 9.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.915 ±(99.9%) 6.658 ops/ms [Average]
  (min, avg, max) = (9.667, 9.915, 10.334), stdev = 0.365
  CI (99.9%): [3.257, 16.573] (assumes normal distribution)


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
# Warmup Iteration   1: 3.542 ops/ms
# Warmup Iteration   2: 7.724 ops/ms
# Warmup Iteration   3: 8.296 ops/ms
Iteration   1: 8.125 ops/ms
Iteration   2: 8.396 ops/ms
Iteration   3: 8.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.284 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (8.125, 8.284, 8.396), stdev = 0.142
  CI (99.9%): [5.702, 10.866] (assumes normal distribution)


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
# Warmup Iteration   1: 8.225 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.006 ms/op
Iteration   1: 3.252 ±(99.9%) 0.005 ms/op
Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
Iteration   3: 3.274 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.206 ±(99.9%) 1.815 ms/op [Average]
  (min, avg, max) = (3.092, 3.206, 3.274), stdev = 0.099
  CI (99.9%): [1.391, 5.021] (assumes normal distribution)


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
# Warmup Iteration   1: 6.967 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.384 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.003 ms/op
Iteration   1: 3.020 ±(99.9%) 0.001 ms/op
Iteration   2: 3.016 ±(99.9%) 0.003 ms/op
Iteration   3: 3.017 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.018 ±(99.9%) 0.034 ms/op [Average]
  (min, avg, max) = (3.016, 3.018, 3.020), stdev = 0.002
  CI (99.9%): [2.983, 3.052] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.299 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.445 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.003 ms/op
Iteration   1: 3.113 ±(99.9%) 0.003 ms/op
Iteration   2: 3.191 ±(99.9%) 0.009 ms/op
Iteration   3: 3.250 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.185 ±(99.9%) 1.256 ms/op [Average]
  (min, avg, max) = (3.113, 3.185, 3.250), stdev = 0.069
  CI (99.9%): [1.929, 4.441] (assumes normal distribution)


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
# Warmup Iteration   1: 8.670 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.008 ms/op
Iteration   1: 3.676 ±(99.9%) 0.012 ms/op
Iteration   2: 3.736 ±(99.9%) 0.013 ms/op
Iteration   3: 3.754 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.722 ±(99.9%) 0.739 ms/op [Average]
  (min, avg, max) = (3.676, 3.722, 3.754), stdev = 0.041
  CI (99.9%): [2.983, 4.461] (assumes normal distribution)


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
# Warmup Iteration   1: 8.106 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.009 ms/op
Iteration   1: 3.390 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  17.848 ms/op
                 createUser·p0.9999: 24.534 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 26.311 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.694 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.514 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 24.591 ms/op
                 createUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297910
  mean =      3.220 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17338 
    [ 2.500,  5.000) = 274489 
    [ 5.000,  7.500) = 5215 
    [ 7.500, 10.000) = 548 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     26.609 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 7.170 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 3.282 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  16.351 ms/op
                 existUser·p0.9999: 20.382 ms/op
                 existUser·p1.00:   22.020 ms/op

Iteration   2: 3.079 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  13.010 ms/op
                 existUser·p0.9999: 25.901 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.178 ms/op
                 existUser·p0.95:   3.346 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  8.014 ms/op
                 existUser·p0.9999: 20.658 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307083
  mean =      3.124 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17573 
    [ 2.500,  5.000) = 283688 
    [ 5.000,  7.500) = 4774 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     24.549 ms/op
     p(99.9990) =     27.031 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 7.794 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.009 ms/op
Iteration   1: 3.130 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  19.726 ms/op
                 getUser·p0.9999: 28.639 ms/op
                 getUser·p1.00:   32.604 ms/op

Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  12.613 ms/op
                 getUser·p0.9999: 22.485 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   3: 3.248 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  17.201 ms/op
                 getUser·p0.9999: 26.088 ms/op
                 getUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299963
  mean =      3.197 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5011 
    [ 2.500,  5.000) = 289140 
    [ 5.000,  7.500) = 4293 
    [ 7.500, 10.000) = 899 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 168 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     19.367 ms/op
     p(99.9900) =     26.248 ms/op
     p(99.9990) =     28.706 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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
# Warmup Iteration   1: 9.843 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.012 ms/op
Iteration   1: 3.785 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  16.441 ms/op
                 listUser·p0.9999: 20.508 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 3.764 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 15.974 ms/op
                 listUser·p1.00:   16.728 ms/op

Iteration   3: 3.712 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.307 ms/op
                 listUser·p0.999:  12.941 ms/op
                 listUser·p0.9999: 15.401 ms/op
                 listUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255610
  mean =      3.753 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 247423 
    [ 5.000,  7.500) = 6077 
    [ 7.500, 10.000) = 1251 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 332 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     14.277 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.900 ± 5.485  ops/ms
ClientPb.existUser                       thrpt       3  10.430 ± 2.923  ops/ms
ClientPb.getUser                         thrpt       3   9.915 ± 6.658  ops/ms
ClientPb.listUser                        thrpt       3   8.284 ± 2.582  ops/ms
ClientPb.createUser                       avgt       3   3.206 ± 1.815   ms/op
ClientPb.existUser                        avgt       3   3.018 ± 0.034   ms/op
ClientPb.getUser                          avgt       3   3.185 ± 1.256   ms/op
ClientPb.listUser                         avgt       3   3.722 ± 0.739   ms/op
ClientPb.createUser                     sample  297910   3.220 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.296           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.452           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.002           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.673           ms/op
ClientPb.existUser                      sample  307083   3.124 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.319           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.549           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.394           ms/op
ClientPb.getUser                        sample  299963   3.197 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.857           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.478           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.915           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.367           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.248           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.604           ms/op
ClientPb.listUser                       sample  255610   3.753 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.035           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.277           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.169           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.332           ms/op
