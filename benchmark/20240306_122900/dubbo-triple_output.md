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
# Warmup Iteration   1: 4.395 ops/ms
# Warmup Iteration   2: 11.803 ops/ms
# Warmup Iteration   3: 12.294 ops/ms
Iteration   1: 12.735 ops/ms
Iteration   2: 12.792 ops/ms
Iteration   3: 12.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.699 ±(99.9%) 2.105 ops/ms [Average]
  (min, avg, max) = (12.570, 12.699, 12.792), stdev = 0.115
  CI (99.9%): [10.594, 14.804] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.656 ops/ms
# Warmup Iteration   2: 13.565 ops/ms
# Warmup Iteration   3: 13.452 ops/ms
Iteration   1: 13.530 ops/ms
Iteration   2: 13.704 ops/ms
Iteration   3: 13.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.624 ±(99.9%) 1.602 ops/ms [Average]
  (min, avg, max) = (13.530, 13.624, 13.704), stdev = 0.088
  CI (99.9%): [12.022, 15.226] (assumes normal distribution)


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
# Warmup Iteration   1: 8.599 ops/ms
# Warmup Iteration   2: 13.171 ops/ms
# Warmup Iteration   3: 13.166 ops/ms
Iteration   1: 13.469 ops/ms
Iteration   2: 13.327 ops/ms
Iteration   3: 13.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.367 ±(99.9%) 1.630 ops/ms [Average]
  (min, avg, max) = (13.305, 13.367, 13.469), stdev = 0.089
  CI (99.9%): [11.737, 14.997] (assumes normal distribution)


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
# Warmup Iteration   1: 6.553 ops/ms
# Warmup Iteration   2: 10.856 ops/ms
# Warmup Iteration   3: 11.012 ops/ms
Iteration   1: 11.067 ops/ms
Iteration   2: 11.056 ops/ms
Iteration   3: 10.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  11.031 ±(99.9%) 0.967 ops/ms [Average]
  (min, avg, max) = (10.970, 11.031, 11.067), stdev = 0.053
  CI (99.9%): [10.064, 11.998] (assumes normal distribution)


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.415 ±(99.9%) 0.004 ms/op
Iteration   1: 2.432 ±(99.9%) 0.004 ms/op
Iteration   2: 2.439 ±(99.9%) 0.003 ms/op
Iteration   3: 2.436 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.436 ±(99.9%) 0.060 ms/op [Average]
  (min, avg, max) = (2.432, 2.436, 2.439), stdev = 0.003
  CI (99.9%): [2.376, 2.496] (assumes normal distribution)


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
# Warmup Iteration   1: 3.643 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.370 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.377 ±(99.9%) 0.004 ms/op
Iteration   1: 2.367 ±(99.9%) 0.003 ms/op
Iteration   2: 2.356 ±(99.9%) 0.004 ms/op
Iteration   3: 2.340 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.354 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.340, 2.354, 2.367), stdev = 0.014
  CI (99.9%): [2.103, 2.605] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.401 ±(99.9%) 0.004 ms/op
Iteration   1: 2.417 ±(99.9%) 0.003 ms/op
Iteration   2: 2.409 ±(99.9%) 0.003 ms/op
Iteration   3: 2.410 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.412 ±(99.9%) 0.075 ms/op [Average]
  (min, avg, max) = (2.409, 2.412, 2.417), stdev = 0.004
  CI (99.9%): [2.337, 2.487] (assumes normal distribution)


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
# Warmup Iteration   1: 4.682 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.952 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.906 ±(99.9%) 0.005 ms/op
Iteration   1: 2.910 ±(99.9%) 0.007 ms/op
Iteration   2: 2.902 ±(99.9%) 0.004 ms/op
Iteration   3: 2.907 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.906 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.902, 2.906, 2.910), stdev = 0.004
  CI (99.9%): [2.825, 2.987] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.006 ms/op
Iteration   1: 2.452 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  6.606 ms/op
                 createUser·p0.9999: 15.303 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   2: 2.420 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   2.933 ms/op
                 createUser·p0.95:   3.035 ms/op
                 createUser·p0.99:   3.543 ms/op
                 createUser·p0.999:  10.107 ms/op
                 createUser·p0.9999: 12.314 ms/op
                 createUser·p1.00:   12.632 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  8.212 ms/op
                 createUser·p0.9999: 9.617 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 392298
  mean =      2.444 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 194042 
    [ 2.500,  3.750) = 194706 
    [ 3.750,  5.000) = 2661 
    [ 5.000,  6.250) = 381 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.695 ms/op
     p(99.9900) =     14.017 ms/op
     p(99.9990) =     15.806 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 3.704 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.415 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.373 ±(99.9%) 0.005 ms/op
Iteration   1: 2.360 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.859 ms/op
                 existUser·p0.95:   2.953 ms/op
                 existUser·p0.99:   3.371 ms/op
                 existUser·p0.999:  7.551 ms/op
                 existUser·p0.9999: 13.328 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   2: 2.364 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.408 ms/op
                 existUser·p0.90:   2.871 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.710 ms/op
                 existUser·p0.999:  7.491 ms/op
                 existUser·p0.9999: 11.821 ms/op
                 existUser·p1.00:   12.206 ms/op

Iteration   3: 2.376 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.408 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  7.671 ms/op
                 existUser·p0.9999: 10.553 ms/op
                 existUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 405229
  mean =      2.367 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 213836 
    [ 2.500,  3.750) = 188321 
    [ 3.750,  5.000) = 2134 
    [ 5.000,  6.250) = 372 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      2.413 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =      7.576 ms/op
     p(99.9900) =     12.984 ms/op
     p(99.9990) =     13.484 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.414 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.421 ms/op
                 getUser·p0.90:   2.937 ms/op
                 getUser·p0.95:   3.031 ms/op
                 getUser·p0.99:   3.424 ms/op
                 getUser·p0.999:  6.366 ms/op
                 getUser·p0.9999: 14.283 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  6.556 ms/op
                 getUser·p0.9999: 12.419 ms/op
                 getUser·p1.00:   13.189 ms/op

Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  7.793 ms/op
                 getUser·p0.9999: 10.435 ms/op
                 getUser·p1.00:   10.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 393012
  mean =      2.441 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 200263 
    [ 2.500,  3.750) = 188413 
    [ 3.750,  5.000) = 3445 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      6.537 ms/op
     p(99.9900) =     13.158 ms/op
     p(99.9990) =     14.685 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.540 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.952 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.008 ms/op
Iteration   1: 2.940 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 10.879 ms/op
                 listUser·p1.00:   11.846 ms/op

Iteration   2: 2.926 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.746 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.237 ms/op
                 listUser·p0.99:   5.333 ms/op
                 listUser·p0.999:  8.949 ms/op
                 listUser·p0.9999: 10.797 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   3: 2.928 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.398 ms/op
                 listUser·p0.9999: 10.815 ms/op
                 listUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 327189
  mean =      2.931 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 105853 
    [ 2.500,  3.750) = 186385 
    [ 3.750,  5.000) = 28487 
    [ 5.000,  6.250) = 5225 
    [ 6.250,  7.500) = 413 
    [ 7.500,  8.750) = 192 
    [ 8.750, 10.000) = 280 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     10.802 ms/op
     p(99.9990) =     11.780 ms/op
     p(99.9999) =     12.108 ms/op
    p(100.0000) =     12.108 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.699 ± 2.105  ops/ms
ClientPb.existUser                       thrpt       3  13.624 ± 1.602  ops/ms
ClientPb.getUser                         thrpt       3  13.367 ± 1.630  ops/ms
ClientPb.listUser                        thrpt       3  11.031 ± 0.967  ops/ms
ClientPb.createUser                       avgt       3   2.436 ± 0.060   ms/op
ClientPb.existUser                        avgt       3   2.354 ± 0.251   ms/op
ClientPb.getUser                          avgt       3   2.412 ± 0.075   ms/op
ClientPb.listUser                         avgt       3   2.906 ± 0.081   ms/op
ClientPb.createUser                     sample  392298   2.444 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.887           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.519           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.966           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.695           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.017           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.662           ms/op
ClientPb.existUser                      sample  405229   2.367 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.716           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.413           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.875           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.576           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.984           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.779           ms/op
ClientPb.getUser                        sample  393012   2.441 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.801           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.458           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.974           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.537           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.158           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.155           ms/op
ClientPb.listUser                       sample  327189   2.931 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.746           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.789           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.802           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.108           ms/op
