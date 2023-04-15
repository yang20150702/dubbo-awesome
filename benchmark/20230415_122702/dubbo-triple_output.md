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
# Warmup Iteration   1: 1.761 ops/ms
# Warmup Iteration   2: 4.797 ops/ms
# Warmup Iteration   3: 7.093 ops/ms
Iteration   1: 8.325 ops/ms
Iteration   2: 8.586 ops/ms
Iteration   3: 8.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.566 ±(99.9%) 4.222 ops/ms [Average]
  (min, avg, max) = (8.325, 8.566, 8.786), stdev = 0.231
  CI (99.9%): [4.343, 12.788] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.326 ops/ms
# Warmup Iteration   2: 7.802 ops/ms
# Warmup Iteration   3: 8.498 ops/ms
Iteration   1: 8.950 ops/ms
Iteration   2: 8.816 ops/ms
Iteration   3: 9.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.040 ±(99.9%) 5.112 ops/ms [Average]
  (min, avg, max) = (8.816, 9.040, 9.354), stdev = 0.280
  CI (99.9%): [3.928, 14.152] (assumes normal distribution)


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
# Warmup Iteration   1: 2.527 ops/ms
# Warmup Iteration   2: 8.124 ops/ms
# Warmup Iteration   3: 8.849 ops/ms
Iteration   1: 8.653 ops/ms
Iteration   2: 8.653 ops/ms
Iteration   3: 8.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.614 ±(99.9%) 1.251 ops/ms [Average]
  (min, avg, max) = (8.534, 8.614, 8.653), stdev = 0.069
  CI (99.9%): [7.362, 9.865] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.331 ops/ms
# Warmup Iteration   2: 6.784 ops/ms
# Warmup Iteration   3: 7.368 ops/ms
Iteration   1: 7.730 ops/ms
Iteration   2: 7.976 ops/ms
Iteration   3: 7.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.749 ±(99.9%) 3.979 ops/ms [Average]
  (min, avg, max) = (7.542, 7.749, 7.976), stdev = 0.218
  CI (99.9%): [3.770, 11.729] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.966 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.013 ms/op
Iteration   1: 3.624 ±(99.9%) 0.006 ms/op
Iteration   2: 3.707 ±(99.9%) 0.008 ms/op
Iteration   3: 3.633 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.655 ±(99.9%) 0.827 ms/op [Average]
  (min, avg, max) = (3.624, 3.655, 3.707), stdev = 0.045
  CI (99.9%): [2.828, 4.482] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.045 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.005 ms/op
Iteration   1: 3.369 ±(99.9%) 0.004 ms/op
Iteration   2: 3.424 ±(99.9%) 0.012 ms/op
Iteration   3: 3.460 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.418 ±(99.9%) 0.832 ms/op [Average]
  (min, avg, max) = (3.369, 3.418, 3.460), stdev = 0.046
  CI (99.9%): [2.585, 4.250] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.140 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.007 ms/op
Iteration   1: 3.501 ±(99.9%) 0.008 ms/op
Iteration   2: 3.522 ±(99.9%) 0.006 ms/op
Iteration   3: 3.482 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.502 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (3.482, 3.502, 3.522), stdev = 0.020
  CI (99.9%): [3.135, 3.868] (assumes normal distribution)


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
# Warmup Iteration   1: 11.998 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.386 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.305 ±(99.9%) 0.007 ms/op
Iteration   1: 4.097 ±(99.9%) 0.009 ms/op
Iteration   2: 4.109 ±(99.9%) 0.011 ms/op
Iteration   3: 4.308 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.171 ±(99.9%) 2.161 ms/op [Average]
  (min, avg, max) = (4.097, 4.171, 4.308), stdev = 0.118
  CI (99.9%): [2.010, 6.332] (assumes normal distribution)


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
# Warmup Iteration   1: 12.470 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.016 ms/op
Iteration   1: 3.667 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.758 ms/op
                 createUser·p0.999:  13.976 ms/op
                 createUser·p0.9999: 25.151 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   2: 3.535 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.348 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.366 ms/op
                 createUser·p0.999:  11.158 ms/op
                 createUser·p0.9999: 23.362 ms/op
                 createUser·p1.00:   23.822 ms/op

Iteration   3: 3.548 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  22.097 ms/op
                 createUser·p0.9999: 29.687 ms/op
                 createUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267808
  mean =      3.582 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5794 
    [ 2.500,  5.000) = 253659 
    [ 5.000,  7.500) = 6972 
    [ 7.500, 10.000) = 880 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.348 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     28.574 ms/op
     p(99.9990) =     32.499 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 10.162 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.009 ms/op
Iteration   1: 3.344 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.475 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  20.253 ms/op
                 existUser·p0.9999: 29.178 ms/op
                 existUser·p1.00:   30.507 ms/op

Iteration   2: 3.428 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.479 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  23.003 ms/op
                 existUser·p0.9999: 28.508 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   3: 3.652 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   7.307 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 26.550 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276535
  mean =      3.470 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8641 
    [ 2.500,  5.000) = 260398 
    [ 5.000,  7.500) = 6030 
    [ 7.500, 10.000) = 1067 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     13.410 ms/op
     p(99.9900) =     28.520 ms/op
     p(99.9990) =     30.175 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 11.508 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.013 ms/op
Iteration   1: 3.772 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.980 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  22.086 ms/op
                 getUser·p0.9999: 25.462 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   2: 3.769 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  9.635 ms/op
                 getUser·p0.9999: 26.544 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   3: 3.762 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  24.707 ms/op
                 getUser·p0.9999: 29.000 ms/op
                 getUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 254750
  mean =      3.768 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1850 
    [ 2.500,  5.000) = 241580 
    [ 5.000,  7.500) = 9674 
    [ 7.500, 10.000) = 1224 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     21.537 ms/op
     p(99.9900) =     28.362 ms/op
     p(99.9990) =     29.875 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 11.703 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.762 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.376 ±(99.9%) 0.015 ms/op
Iteration   1: 4.326 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  23.267 ms/op
                 listUser·p0.9999: 31.465 ms/op
                 listUser·p1.00:   32.539 ms/op

Iteration   2: 4.155 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  16.540 ms/op
                 listUser·p0.9999: 20.902 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   3: 4.293 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   4.162 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   8.233 ms/op
                 listUser·p0.999:  15.241 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225598
  mean =      4.257 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 213035 
    [ 5.000,  7.500) = 9112 
    [ 7.500, 10.000) = 2540 
    [10.000, 12.500) = 398 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     30.507 ms/op
     p(99.9990) =     32.489 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.566 ± 4.222  ops/ms
ClientPb.existUser                       thrpt       3   9.040 ± 5.112  ops/ms
ClientPb.getUser                         thrpt       3   8.614 ± 1.251  ops/ms
ClientPb.listUser                        thrpt       3   7.749 ± 3.979  ops/ms
ClientPb.createUser                       avgt       3   3.655 ± 0.827   ms/op
ClientPb.existUser                        avgt       3   3.418 ± 0.832   ms/op
ClientPb.getUser                          avgt       3   3.502 ± 0.366   ms/op
ClientPb.listUser                         avgt       3   4.171 ± 2.161   ms/op
ClientPb.createUser                     sample  267808   3.582 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.348           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.482           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.537           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.090           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.574           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.030           ms/op
ClientPb.existUser                      sample  276535   3.470 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.323           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.387           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.390           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.410           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.520           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.507           ms/op
ClientPb.getUser                        sample  254750   3.768 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.892           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.633           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.858           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.840           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.537           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.362           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.343           ms/op
ClientPb.listUser                       sample  225598   4.257 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.360           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.079           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.777           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.507           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.539           ms/op
