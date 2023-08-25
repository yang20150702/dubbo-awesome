# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.733 ops/ms
# Warmup Iteration   2: 4.912 ops/ms
# Warmup Iteration   3: 8.257 ops/ms
Iteration   1: 8.988 ops/ms
Iteration   2: 9.040 ops/ms
Iteration   3: 9.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.014 ±(99.9%) 0.472 ops/ms [Average]
  (min, avg, max) = (8.988, 9.014, 9.040), stdev = 0.026
  CI (99.9%): [8.542, 9.486] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.800 ops/ms
# Warmup Iteration   2: 8.571 ops/ms
# Warmup Iteration   3: 9.353 ops/ms
Iteration   1: 9.632 ops/ms
Iteration   2: 9.409 ops/ms
Iteration   3: 9.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.585 ±(99.9%) 2.888 ops/ms [Average]
  (min, avg, max) = (9.409, 9.585, 9.715), stdev = 0.158
  CI (99.9%): [6.698, 12.473] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.643 ops/ms
# Warmup Iteration   2: 8.294 ops/ms
# Warmup Iteration   3: 8.700 ops/ms
Iteration   1: 9.413 ops/ms
Iteration   2: 9.164 ops/ms
Iteration   3: 8.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.156 ±(99.9%) 4.742 ops/ms [Average]
  (min, avg, max) = (8.893, 9.156, 9.413), stdev = 0.260
  CI (99.9%): [4.414, 13.898] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.470 ops/ms
# Warmup Iteration   2: 7.164 ops/ms
# Warmup Iteration   3: 7.710 ops/ms
Iteration   1: 7.911 ops/ms
Iteration   2: 7.905 ops/ms
Iteration   3: 7.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.923 ±(99.9%) 0.467 ops/ms [Average]
  (min, avg, max) = (7.905, 7.923, 7.952), stdev = 0.026
  CI (99.9%): [7.456, 8.389] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.624 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.008 ms/op
Iteration   1: 3.512 ±(99.9%) 0.005 ms/op
Iteration   2: 3.460 ±(99.9%) 0.004 ms/op
Iteration   3: 3.418 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.463 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (3.418, 3.463, 3.512), stdev = 0.047
  CI (99.9%): [2.609, 4.318] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.074 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.004 ms/op
Iteration   1: 3.339 ±(99.9%) 0.003 ms/op
Iteration   2: 3.275 ±(99.9%) 0.004 ms/op
Iteration   3: 3.400 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.338 ±(99.9%) 1.138 ms/op [Average]
  (min, avg, max) = (3.275, 3.338, 3.400), stdev = 0.062
  CI (99.9%): [2.200, 4.475] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.502 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.005 ms/op
Iteration   1: 3.405 ±(99.9%) 0.007 ms/op
Iteration   2: 3.553 ±(99.9%) 0.004 ms/op
Iteration   3: 3.469 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.476 ±(99.9%) 1.351 ms/op [Average]
  (min, avg, max) = (3.405, 3.476, 3.553), stdev = 0.074
  CI (99.9%): [2.124, 4.827] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.433 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.621 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.004 ms/op
Iteration   1: 4.103 ±(99.9%) 0.010 ms/op
Iteration   2: 4.032 ±(99.9%) 0.010 ms/op
Iteration   3: 4.046 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.060 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (4.032, 4.060, 4.103), stdev = 0.038
  CI (99.9%): [3.373, 4.748] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.539 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.934 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.012 ms/op
Iteration   1: 3.453 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  21.299 ms/op
                 createUser·p0.9999: 23.633 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   2: 3.578 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   7.302 ms/op
                 createUser·p0.999:  12.419 ms/op
                 createUser·p0.9999: 24.775 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 3.485 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.751 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 28.622 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273732
  mean =      3.505 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6416 
    [ 2.500,  5.000) = 259351 
    [ 5.000,  7.500) = 6177 
    [ 7.500, 10.000) = 1290 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     14.513 ms/op
     p(99.9900) =     27.415 ms/op
     p(99.9990) =     29.327 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.208 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.009 ms/op
Iteration   1: 3.524 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   6.534 ms/op
                 existUser·p0.999:  19.129 ms/op
                 existUser·p0.9999: 23.291 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   2: 3.397 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  22.870 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   3: 3.370 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  12.519 ms/op
                 existUser·p0.9999: 25.346 ms/op
                 existUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279714
  mean =      3.429 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10593 
    [ 2.500,  5.000) = 261443 
    [ 5.000,  7.500) = 5918 
    [ 7.500, 10.000) = 1158 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     13.407 ms/op
     p(99.9900) =     25.200 ms/op
     p(99.9990) =     25.823 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.251 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.012 ms/op
Iteration   1: 3.581 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   7.815 ms/op
                 getUser·p0.999:  18.044 ms/op
                 getUser·p0.9999: 21.205 ms/op
                 getUser·p1.00:   21.758 ms/op

Iteration   2: 3.554 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.169 ms/op
                 getUser·p0.999:  13.140 ms/op
                 getUser·p0.9999: 30.737 ms/op
                 getUser·p1.00:   31.359 ms/op

Iteration   3: 3.489 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   7.093 ms/op
                 getUser·p0.999:  19.510 ms/op
                 getUser·p0.9999: 27.220 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270930
  mean =      3.541 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6391 
    [ 2.500,  5.000) = 253223 
    [ 5.000,  7.500) = 8961 
    [ 7.500, 10.000) = 1638 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     14.386 ms/op
     p(99.9900) =     29.990 ms/op
     p(99.9990) =     31.228 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.112 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.014 ms/op
Iteration   1: 4.111 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  21.135 ms/op
                 listUser·p0.9999: 28.318 ms/op
                 listUser·p1.00:   30.638 ms/op

Iteration   2: 4.119 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  19.996 ms/op
                 listUser·p0.9999: 23.044 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   3: 4.095 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 18.225 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233635
  mean =      4.108 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 223832 
    [ 5.000,  7.500) = 6534 
    [ 7.500, 10.000) = 2029 
    [10.000, 12.500) = 665 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      8.233 ms/op
     p(99.9000) =     17.739 ms/op
     p(99.9900) =     27.752 ms/op
     p(99.9990) =     30.022 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.014 ± 0.472  ops/ms
ClientPb.existUser                       thrpt       3   9.585 ± 2.888  ops/ms
ClientPb.getUser                         thrpt       3   9.156 ± 4.742  ops/ms
ClientPb.listUser                        thrpt       3   7.923 ± 0.467  ops/ms
ClientPb.createUser                       avgt       3   3.463 ± 0.854   ms/op
ClientPb.existUser                        avgt       3   3.338 ± 1.138   ms/op
ClientPb.getUser                          avgt       3   3.476 ± 1.351   ms/op
ClientPb.listUser                         avgt       3   4.060 ± 0.687   ms/op
ClientPb.createUser                     sample  273732   3.505 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.212           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.513           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.415           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.491           ms/op
ClientPb.existUser                      sample  279714   3.429 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.738           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.504           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.407           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.200           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.378           ms/op
ClientPb.getUser                        sample  270930   3.541 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.069           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.386           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.990           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.359           ms/op
ClientPb.listUser                       sample  233635   4.108 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.175           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.233           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.739           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.752           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.638           ms/op
