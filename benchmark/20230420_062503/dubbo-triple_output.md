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
# Warmup Iteration   1: 1.671 ops/ms
# Warmup Iteration   2: 4.980 ops/ms
# Warmup Iteration   3: 7.844 ops/ms
Iteration   1: 8.222 ops/ms
Iteration   2: 8.366 ops/ms
Iteration   3: 8.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.209 ±(99.9%) 3.009 ops/ms [Average]
  (min, avg, max) = (8.037, 8.209, 8.366), stdev = 0.165
  CI (99.9%): [5.200, 11.218] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.775 ops/ms
# Warmup Iteration   2: 7.971 ops/ms
# Warmup Iteration   3: 9.026 ops/ms
Iteration   1: 9.243 ops/ms
Iteration   2: 9.705 ops/ms
Iteration   3: 9.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.539 ±(99.9%) 4.683 ops/ms [Average]
  (min, avg, max) = (9.243, 9.539, 9.705), stdev = 0.257
  CI (99.9%): [4.856, 14.222] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.470 ops/ms
# Warmup Iteration   2: 8.490 ops/ms
# Warmup Iteration   3: 9.082 ops/ms
Iteration   1: 9.200 ops/ms
Iteration   2: 9.267 ops/ms
Iteration   3: 8.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.147 ±(99.9%) 2.812 ops/ms [Average]
  (min, avg, max) = (8.973, 9.147, 9.267), stdev = 0.154
  CI (99.9%): [6.335, 11.959] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.846 ops/ms
# Warmup Iteration   2: 6.569 ops/ms
# Warmup Iteration   3: 7.717 ops/ms
Iteration   1: 7.892 ops/ms
Iteration   2: 7.749 ops/ms
Iteration   3: 7.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.871 ±(99.9%) 2.061 ops/ms [Average]
  (min, avg, max) = (7.749, 7.871, 7.972), stdev = 0.113
  CI (99.9%): [5.809, 9.932] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.311 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.003 ms/op
Iteration   1: 3.568 ±(99.9%) 0.014 ms/op
Iteration   2: 3.967 ±(99.9%) 0.009 ms/op
Iteration   3: 3.978 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.838 ±(99.9%) 4.261 ms/op [Average]
  (min, avg, max) = (3.568, 3.838, 3.978), stdev = 0.234
  CI (99.9%): [≈ 0, 8.098] (assumes normal distribution)


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
# Warmup Iteration   1: 11.206 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.007 ms/op
Iteration   1: 3.936 ±(99.9%) 0.002 ms/op
Iteration   2: 3.869 ±(99.9%) 0.006 ms/op
Iteration   3: 3.825 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.877 ±(99.9%) 1.021 ms/op [Average]
  (min, avg, max) = (3.825, 3.877, 3.936), stdev = 0.056
  CI (99.9%): [2.856, 4.898] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 11.196 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.036 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.010 ms/op
Iteration   1: 3.479 ±(99.9%) 0.008 ms/op
Iteration   2: 3.522 ±(99.9%) 0.008 ms/op
Iteration   3: 3.393 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.465 ±(99.9%) 1.196 ms/op [Average]
  (min, avg, max) = (3.393, 3.465, 3.522), stdev = 0.066
  CI (99.9%): [2.268, 4.661] (assumes normal distribution)


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
# Warmup Iteration   1: 9.947 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.234 ±(99.9%) 0.014 ms/op
Iteration   1: 4.038 ±(99.9%) 0.008 ms/op
Iteration   2: 4.152 ±(99.9%) 0.008 ms/op
Iteration   3: 4.066 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.085 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (4.038, 4.085, 4.152), stdev = 0.059
  CI (99.9%): [3.002, 5.169] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.951 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.011 ms/op
Iteration   1: 3.523 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.628 ms/op
                 createUser·p0.999:  20.527 ms/op
                 createUser·p0.9999: 27.132 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   2: 3.494 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  22.757 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 3.471 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.683 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  15.349 ms/op
                 createUser·p0.9999: 25.657 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274498
  mean =      3.496 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7644 
    [ 2.500,  5.000) = 260144 
    [ 5.000,  7.500) = 5780 
    [ 7.500, 10.000) = 511 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 82 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     16.499 ms/op
     p(99.9900) =     26.411 ms/op
     p(99.9990) =     27.659 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.232 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.008 ms/op
Iteration   1: 3.362 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  10.485 ms/op
                 existUser·p0.9999: 20.349 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.351 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  20.414 ms/op
                 existUser·p0.9999: 23.196 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   3: 3.346 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  20.121 ms/op
                 existUser·p0.9999: 24.478 ms/op
                 existUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286305
  mean =      3.353 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11710 
    [ 2.500,  5.000) = 270085 
    [ 5.000,  7.500) = 3676 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 154 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     14.315 ms/op
     p(99.9900) =     23.191 ms/op
     p(99.9990) =     24.613 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 8.249 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.010 ms/op
Iteration   1: 3.628 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  19.330 ms/op
                 getUser·p0.9999: 24.194 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   2: 3.562 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.433 ms/op
                 getUser·p0.999:  22.126 ms/op
                 getUser·p0.9999: 25.396 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   3: 3.457 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  20.409 ms/op
                 getUser·p0.9999: 25.674 ms/op
                 getUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270288
  mean =      3.548 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4468 
    [ 2.500,  5.000) = 256564 
    [ 5.000,  7.500) = 8302 
    [ 7.500, 10.000) = 560 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     19.637 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     26.614 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 10.246 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.012 ms/op
Iteration   1: 4.247 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.436 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  20.008 ms/op
                 listUser·p0.9999: 33.716 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   2: 4.045 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 16.093 ms/op
                 listUser·p1.00:   16.744 ms/op

Iteration   3: 3.936 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.917 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235744
  mean =      4.072 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 225621 
    [ 5.000,  7.500) = 7266 
    [ 7.500, 10.000) = 2079 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 247 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     14.897 ms/op
     p(99.9900) =     31.733 ms/op
     p(99.9990) =     34.603 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.209 ± 3.009  ops/ms
ClientPb.existUser                       thrpt       3   9.539 ± 4.683  ops/ms
ClientPb.getUser                         thrpt       3   9.147 ± 2.812  ops/ms
ClientPb.listUser                        thrpt       3   7.871 ± 2.061  ops/ms
ClientPb.createUser                       avgt       3   3.838 ± 4.261   ms/op
ClientPb.existUser                        avgt       3   3.877 ± 1.021   ms/op
ClientPb.getUser                          avgt       3   3.465 ± 1.196   ms/op
ClientPb.listUser                         avgt       3   4.085 ± 1.083   ms/op
ClientPb.createUser                     sample  274498   3.496 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.063           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.499           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.411           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.475           ms/op
ClientPb.existUser                      sample  286305   3.353 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.856           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.936           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.315           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.191           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.231           ms/op
ClientPb.getUser                        sample  270288   3.548 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.210           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.637           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.297           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.935           ms/op
ClientPb.listUser                       sample  235744   4.072 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.436           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.897           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.733           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.127           ms/op
