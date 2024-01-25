# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.310 ops/ms
# Warmup Iteration   2: 11.806 ops/ms
# Warmup Iteration   3: 12.163 ops/ms
Iteration   1: 12.440 ops/ms
Iteration   2: 12.681 ops/ms
Iteration   3: 12.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.574 ±(99.9%) 2.235 ops/ms [Average]
  (min, avg, max) = (12.440, 12.574, 12.681), stdev = 0.123
  CI (99.9%): [10.339, 14.809] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.171 ops/ms
# Warmup Iteration   2: 13.005 ops/ms
# Warmup Iteration   3: 13.054 ops/ms
Iteration   1: 13.183 ops/ms
Iteration   2: 13.212 ops/ms
Iteration   3: 13.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.174 ±(99.9%) 0.793 ops/ms [Average]
  (min, avg, max) = (13.127, 13.174, 13.212), stdev = 0.043
  CI (99.9%): [12.381, 13.967] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.918 ops/ms
# Warmup Iteration   2: 12.632 ops/ms
# Warmup Iteration   3: 12.755 ops/ms
Iteration   1: 12.809 ops/ms
Iteration   2: 12.799 ops/ms
Iteration   3: 12.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.766 ±(99.9%) 1.213 ops/ms [Average]
  (min, avg, max) = (12.689, 12.766, 12.809), stdev = 0.067
  CI (99.9%): [11.552, 13.979] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.690 ops/ms
# Warmup Iteration   2: 10.332 ops/ms
# Warmup Iteration   3: 10.504 ops/ms
Iteration   1: 10.413 ops/ms
Iteration   2: 10.498 ops/ms
Iteration   3: 10.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.459 ±(99.9%) 0.786 ops/ms [Average]
  (min, avg, max) = (10.413, 10.459, 10.498), stdev = 0.043
  CI (99.9%): [9.673, 11.246] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.003 ms/op
Iteration   1: 2.579 ±(99.9%) 0.004 ms/op
Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
Iteration   3: 2.577 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.573 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (2.562, 2.573, 2.579), stdev = 0.009
  CI (99.9%): [2.401, 2.744] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.476 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (2.466, 2.476, 2.485), stdev = 0.010
  CI (99.9%): [2.298, 2.654] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.003 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.505 ±(99.9%) 0.003 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.504 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.485, 2.504, 2.523), stdev = 0.019
  CI (99.9%): [2.159, 2.850] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.675 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.055 ±(99.9%) 0.006 ms/op
Iteration   2: 3.029 ±(99.9%) 0.004 ms/op
Iteration   3: 3.049 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (3.029, 3.044, 3.055), stdev = 0.014
  CI (99.9%): [2.797, 3.292] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.330 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  11.104 ms/op
                 createUser·p0.9999: 13.732 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  8.529 ms/op
                 createUser·p0.9999: 12.031 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.029 ms/op
                 createUser·p0.999:  8.435 ms/op
                 createUser·p0.9999: 10.345 ms/op
                 createUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380691
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 181746 
    [ 2.500,  3.750) = 194666 
    [ 3.750,  5.000) = 3462 
    [ 5.000,  6.250) = 323 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.464 ms/op
     p(99.9900) =     13.090 ms/op
     p(99.9990) =     14.329 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.722 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  11.320 ms/op
                 existUser·p0.9999: 14.653 ms/op
                 existUser·p1.00:   15.286 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.777 ms/op
                 existUser·p0.999:  9.162 ms/op
                 existUser·p0.9999: 12.401 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  6.244 ms/op
                 existUser·p0.9999: 11.917 ms/op
                 existUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382601
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 186150 
    [ 2.500,  3.750) = 193050 
    [ 3.750,  5.000) = 2508 
    [ 5.000,  6.250) = 446 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      6.758 ms/op
     p(99.9900) =     13.242 ms/op
     p(99.9990) =     15.060 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.044 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.537 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  5.881 ms/op
                 getUser·p0.9999: 13.386 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  11.328 ms/op
                 getUser·p0.9999: 14.495 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  9.006 ms/op
                 getUser·p0.9999: 11.239 ms/op
                 getUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377920
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 184477 
    [ 2.500,  3.750) = 187788 
    [ 3.750,  5.000) = 4320 
    [ 5.000,  6.250) = 795 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.046 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     13.750 ms/op
     p(99.9990) =     15.106 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.816 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.759 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.083 ms/op
                 listUser·p0.9999: 10.737 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   2: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.932 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 11.773 ms/op
                 listUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317514
  mean =      3.021 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 88712 
    [ 2.500,  3.750) = 189605 
    [ 3.750,  5.000) = 31913 
    [ 5.000,  6.250) = 5735 
    [ 6.250,  7.500) = 699 
    [ 7.500,  8.750) = 266 
    [ 8.750, 10.000) = 267 
    [10.000, 11.250) = 183 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     11.145 ms/op
     p(99.9990) =     12.607 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.574 ± 2.235  ops/ms
ClientPb.existUser                       thrpt       3  13.174 ± 0.793  ops/ms
ClientPb.getUser                         thrpt       3  12.766 ± 1.213  ops/ms
ClientPb.listUser                        thrpt       3  10.459 ± 0.786  ops/ms
ClientPb.createUser                       avgt       3   2.573 ± 0.171   ms/op
ClientPb.existUser                        avgt       3   2.476 ± 0.178   ms/op
ClientPb.getUser                          avgt       3   2.504 ± 0.346   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.247   ms/op
ClientPb.createUser                     sample  380691   2.519 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.706           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.464           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.090           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.402           ms/op
ClientPb.existUser                      sample  382601   2.506 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.006           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.758           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.242           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.286           ms/op
ClientPb.getUser                        sample  377920   2.538 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.928           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.046           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.077           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.750           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.303           ms/op
ClientPb.listUser                       sample  317514   3.021 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.759           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.145           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.665           ms/op
