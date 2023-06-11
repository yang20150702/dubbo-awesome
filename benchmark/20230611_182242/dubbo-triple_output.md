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
# Warmup Iteration   1: 2.155 ops/ms
# Warmup Iteration   2: 5.533 ops/ms
# Warmup Iteration   3: 8.668 ops/ms
Iteration   1: 9.352 ops/ms
Iteration   2: 9.288 ops/ms
Iteration   3: 9.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.306 ±(99.9%) 0.731 ops/ms [Average]
  (min, avg, max) = (9.277, 9.306, 9.352), stdev = 0.040
  CI (99.9%): [8.575, 10.037] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.942 ops/ms
# Warmup Iteration   2: 8.667 ops/ms
# Warmup Iteration   3: 9.341 ops/ms
Iteration   1: 9.584 ops/ms
Iteration   2: 9.527 ops/ms
Iteration   3: 9.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.533 ±(99.9%) 0.874 ops/ms [Average]
  (min, avg, max) = (9.489, 9.533, 9.584), stdev = 0.048
  CI (99.9%): [8.660, 10.407] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.940 ops/ms
# Warmup Iteration   2: 8.740 ops/ms
# Warmup Iteration   3: 8.907 ops/ms
Iteration   1: 8.933 ops/ms
Iteration   2: 9.434 ops/ms
Iteration   3: 9.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.309 ±(99.9%) 6.054 ops/ms [Average]
  (min, avg, max) = (8.933, 9.309, 9.560), stdev = 0.332
  CI (99.9%): [3.255, 15.363] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.555 ops/ms
# Warmup Iteration   2: 6.985 ops/ms
# Warmup Iteration   3: 7.838 ops/ms
Iteration   1: 8.130 ops/ms
Iteration   2: 7.927 ops/ms
Iteration   3: 7.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.016 ±(99.9%) 1.885 ops/ms [Average]
  (min, avg, max) = (7.927, 8.016, 8.130), stdev = 0.103
  CI (99.9%): [6.132, 9.901] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.268 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.010 ms/op
Iteration   1: 3.454 ±(99.9%) 0.009 ms/op
Iteration   2: 3.327 ±(99.9%) 0.013 ms/op
Iteration   3: 3.318 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.366 ±(99.9%) 1.395 ms/op [Average]
  (min, avg, max) = (3.318, 3.366, 3.454), stdev = 0.076
  CI (99.9%): [1.971, 4.761] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.009 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.005 ms/op
Iteration   1: 3.284 ±(99.9%) 0.008 ms/op
Iteration   2: 3.462 ±(99.9%) 0.006 ms/op
Iteration   3: 3.383 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.376 ±(99.9%) 1.632 ms/op [Average]
  (min, avg, max) = (3.284, 3.376, 3.462), stdev = 0.089
  CI (99.9%): [1.744, 5.009] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.505 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.005 ms/op
Iteration   1: 3.460 ±(99.9%) 0.003 ms/op
Iteration   2: 3.339 ±(99.9%) 0.007 ms/op
Iteration   3: 3.355 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.385 ±(99.9%) 1.194 ms/op [Average]
  (min, avg, max) = (3.339, 3.385, 3.460), stdev = 0.065
  CI (99.9%): [2.190, 4.579] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.128 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.518 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.188 ±(99.9%) 0.009 ms/op
Iteration   1: 4.044 ±(99.9%) 0.009 ms/op
Iteration   2: 3.977 ±(99.9%) 0.013 ms/op
Iteration   3: 3.998 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.007 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (3.977, 4.007, 4.044), stdev = 0.034
  CI (99.9%): [3.382, 4.632] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.607 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.010 ms/op
Iteration   1: 3.412 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.706 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  20.482 ms/op
                 createUser·p0.9999: 24.510 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   2: 3.407 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  21.570 ms/op
                 createUser·p0.9999: 24.131 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   3: 3.421 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.692 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  18.416 ms/op
                 createUser·p0.9999: 24.663 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281234
  mean =      3.413 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12146 
    [ 2.500,  5.000) = 263890 
    [ 5.000,  7.500) = 4316 
    [ 7.500, 10.000) = 504 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 140 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     24.453 ms/op
     p(99.9990) =     25.074 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 8.694 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.008 ms/op
Iteration   1: 3.319 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  17.172 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   2: 3.321 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.754 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  20.667 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   3: 3.356 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 26.130 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287834
  mean =      3.332 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12493 
    [ 2.500,  5.000) = 269208 
    [ 5.000,  7.500) = 5245 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 160 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     26.481 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.227 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.009 ms/op
Iteration   1: 3.455 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  18.984 ms/op
                 getUser·p0.9999: 22.405 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.362 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  20.551 ms/op
                 getUser·p0.9999: 27.410 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   3: 3.486 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.821 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  19.471 ms/op
                 getUser·p0.9999: 32.993 ms/op
                 getUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279434
  mean =      3.434 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6170 
    [ 2.500,  5.000) = 265152 
    [ 5.000,  7.500) = 6904 
    [ 7.500, 10.000) = 834 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     19.581 ms/op
     p(99.9900) =     31.274 ms/op
     p(99.9990) =     34.223 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.852 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.528 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.013 ms/op
Iteration   1: 4.115 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.903 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  22.747 ms/op
                 listUser·p0.9999: 27.230 ms/op
                 listUser·p1.00:   28.115 ms/op

Iteration   2: 4.018 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.870 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  16.887 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 3.882 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.247 ms/op
                 listUser·p0.9999: 16.265 ms/op
                 listUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239922
  mean =      4.003 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 231113 
    [ 5.000,  7.500) = 6672 
    [ 7.500, 10.000) = 1346 
    [10.000, 12.500) = 309 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.870 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     27.499 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.306 ± 0.731  ops/ms
ClientPb.existUser                       thrpt       3   9.533 ± 0.874  ops/ms
ClientPb.getUser                         thrpt       3   9.309 ± 6.054  ops/ms
ClientPb.listUser                        thrpt       3   8.016 ± 1.885  ops/ms
ClientPb.createUser                       avgt       3   3.366 ± 1.395   ms/op
ClientPb.existUser                        avgt       3   3.376 ± 1.632   ms/op
ClientPb.getUser                          avgt       3   3.385 ± 1.194   ms/op
ClientPb.listUser                         avgt       3   4.007 ± 0.625   ms/op
ClientPb.createUser                     sample  281234   3.413 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.296           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.481           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.453           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.166           ms/op
ClientPb.existUser                      sample  287834   3.332 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.356           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.304           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.068           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.903           ms/op
ClientPb.getUser                        sample  279434   3.434 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.923           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.177           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.581           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.274           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.341           ms/op
ClientPb.listUser                       sample  239922   4.003 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.870           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.401           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.903           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.115           ms/op
