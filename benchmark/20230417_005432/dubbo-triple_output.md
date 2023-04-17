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
# Warmup Iteration   1: 2.506 ops/ms
# Warmup Iteration   2: 6.830 ops/ms
# Warmup Iteration   3: 9.399 ops/ms
Iteration   1: 9.917 ops/ms
Iteration   2: 10.015 ops/ms
Iteration   3: 9.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.912 ±(99.9%) 1.916 ops/ms [Average]
  (min, avg, max) = (9.805, 9.912, 10.015), stdev = 0.105
  CI (99.9%): [7.996, 11.828] (assumes normal distribution)


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
# Warmup Iteration   1: 3.733 ops/ms
# Warmup Iteration   2: 9.241 ops/ms
# Warmup Iteration   3: 10.044 ops/ms
Iteration   1: 10.398 ops/ms
Iteration   2: 10.362 ops/ms
Iteration   3: 10.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.518 ±(99.9%) 4.375 ops/ms [Average]
  (min, avg, max) = (10.362, 10.518, 10.794), stdev = 0.240
  CI (99.9%): [6.143, 14.893] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.432 ops/ms
# Warmup Iteration   2: 9.596 ops/ms
# Warmup Iteration   3: 9.868 ops/ms
Iteration   1: 10.076 ops/ms
Iteration   2: 10.191 ops/ms
Iteration   3: 10.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.201 ±(99.9%) 2.372 ops/ms [Average]
  (min, avg, max) = (10.076, 10.201, 10.335), stdev = 0.130
  CI (99.9%): [7.829, 12.572] (assumes normal distribution)


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
# Warmup Iteration   1: 3.657 ops/ms
# Warmup Iteration   2: 7.881 ops/ms
# Warmup Iteration   3: 8.520 ops/ms
Iteration   1: 8.398 ops/ms
Iteration   2: 8.776 ops/ms
Iteration   3: 8.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.543 ±(99.9%) 3.716 ops/ms [Average]
  (min, avg, max) = (8.398, 8.543, 8.776), stdev = 0.204
  CI (99.9%): [4.826, 12.259] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.699 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.003 ms/op
Iteration   1: 3.103 ±(99.9%) 0.003 ms/op
Iteration   2: 3.204 ±(99.9%) 0.005 ms/op
Iteration   3: 3.076 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.128 ±(99.9%) 1.227 ms/op [Average]
  (min, avg, max) = (3.076, 3.128, 3.204), stdev = 0.067
  CI (99.9%): [1.900, 4.355] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.604 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.005 ms/op
Iteration   1: 2.973 ±(99.9%) 0.004 ms/op
Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
Iteration   3: 2.997 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.985 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (2.973, 2.985, 2.997), stdev = 0.012
  CI (99.9%): [2.773, 3.198] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.758 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.004 ms/op
Iteration   1: 3.221 ±(99.9%) 0.008 ms/op
Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
Iteration   3: 3.157 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.171 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (3.136, 3.171, 3.221), stdev = 0.044
  CI (99.9%): [2.362, 3.980] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.960 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.007 ms/op
Iteration   1: 3.658 ±(99.9%) 0.012 ms/op
Iteration   2: 3.681 ±(99.9%) 0.008 ms/op
Iteration   3: 3.678 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.672 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (3.658, 3.672, 3.681), stdev = 0.012
  CI (99.9%): [3.446, 3.898] (assumes normal distribution)


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
# Warmup Iteration   1: 7.489 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.009 ms/op
Iteration   1: 3.235 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  11.679 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   21.234 ms/op

Iteration   2: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.649 ms/op
                 createUser·p0.999:  15.635 ms/op
                 createUser·p0.9999: 21.559 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   3: 3.230 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  15.450 ms/op
                 createUser·p0.9999: 18.940 ms/op
                 createUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298650
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17707 
    [ 2.500,  5.000) = 274519 
    [ 5.000,  7.500) = 5493 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 170 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     21.988 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 7.795 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
Iteration   1: 3.252 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  14.565 ms/op
                 existUser·p0.9999: 17.307 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  12.572 ms/op
                 existUser·p0.9999: 20.414 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  8.691 ms/op
                 existUser·p0.9999: 21.189 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301613
  mean =      3.182 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21542 
    [ 2.500,  5.000) = 275610 
    [ 5.000,  7.500) = 3877 
    [ 7.500, 10.000) = 265 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.348 ms/op
     p(99.9000) =     14.105 ms/op
     p(99.9900) =     20.606 ms/op
     p(99.9990) =     21.655 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 8.585 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.009 ms/op
Iteration   1: 3.208 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   4.439 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  18.055 ms/op
                 getUser·p0.9999: 20.809 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.073 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.318 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  18.582 ms/op
                 getUser·p0.9999: 22.361 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.303 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  8.491 ms/op
                 getUser·p0.9999: 18.809 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300632
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16368 
    [ 2.500,  5.000) = 274920 
    [ 5.000,  7.500) = 8130 
    [ 7.500, 10.000) = 761 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 191 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     16.855 ms/op
     p(99.9900) =     21.756 ms/op
     p(99.9990) =     23.919 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 10.022 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.683 ±(99.9%) 0.010 ms/op
Iteration   1: 3.809 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.997 ms/op
                 listUser·p0.999:  14.318 ms/op
                 listUser·p0.9999: 26.837 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   2: 3.711 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.694 ms/op
                 listUser·p0.999:  12.790 ms/op
                 listUser·p0.9999: 14.696 ms/op
                 listUser·p1.00:   15.598 ms/op

Iteration   3: 3.803 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.058 ms/op
                 listUser·p0.9999: 18.468 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254366
  mean =      3.774 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 245337 
    [ 5.000,  7.500) = 7347 
    [ 7.500, 10.000) = 885 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.591 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.912 ± 1.916  ops/ms
ClientPb.existUser                       thrpt       3  10.518 ± 4.375  ops/ms
ClientPb.getUser                         thrpt       3  10.201 ± 2.372  ops/ms
ClientPb.listUser                        thrpt       3   8.543 ± 3.716  ops/ms
ClientPb.createUser                       avgt       3   3.128 ± 1.227   ms/op
ClientPb.existUser                        avgt       3   2.985 ± 0.213   ms/op
ClientPb.getUser                          avgt       3   3.171 ± 0.809   ms/op
ClientPb.listUser                         avgt       3   3.672 ± 0.226   ms/op
ClientPb.createUser                     sample  298650   3.212 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.145           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.483           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.299           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.217           ms/op
ClientPb.existUser                      sample  301613   3.182 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.913           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.348           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.105           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.606           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.889           ms/op
ClientPb.getUser                        sample  300632   3.192 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.321           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.625           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.226           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.855           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.756           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.019           ms/op
ClientPb.listUser                       sample  254366   3.774 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.591           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.816           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.713           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.904           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.903           ms/op
