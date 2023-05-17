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
# Warmup Iteration   1: 2.104 ops/ms
# Warmup Iteration   2: 5.906 ops/ms
# Warmup Iteration   3: 8.633 ops/ms
Iteration   1: 9.590 ops/ms
Iteration   2: 9.645 ops/ms
Iteration   3: 9.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.724 ±(99.9%) 3.390 ops/ms [Average]
  (min, avg, max) = (9.590, 9.724, 9.936), stdev = 0.186
  CI (99.9%): [6.333, 13.114] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.821 ops/ms
# Warmup Iteration   2: 8.960 ops/ms
# Warmup Iteration   3: 9.318 ops/ms
Iteration   1: 9.304 ops/ms
Iteration   2: 9.993 ops/ms
Iteration   3: 9.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.760 ±(99.9%) 7.206 ops/ms [Average]
  (min, avg, max) = (9.304, 9.760, 9.993), stdev = 0.395
  CI (99.9%): [2.555, 16.966] (assumes normal distribution)


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
# Warmup Iteration   1: 2.745 ops/ms
# Warmup Iteration   2: 8.540 ops/ms
# Warmup Iteration   3: 9.382 ops/ms
Iteration   1: 9.583 ops/ms
Iteration   2: 9.518 ops/ms
Iteration   3: 9.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.442 ±(99.9%) 3.464 ops/ms [Average]
  (min, avg, max) = (9.226, 9.442, 9.583), stdev = 0.190
  CI (99.9%): [5.979, 12.906] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.788 ops/ms
# Warmup Iteration   2: 7.283 ops/ms
# Warmup Iteration   3: 7.743 ops/ms
Iteration   1: 8.197 ops/ms
Iteration   2: 8.169 ops/ms
Iteration   3: 8.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.290 ±(99.9%) 3.374 ops/ms [Average]
  (min, avg, max) = (8.169, 8.290, 8.503), stdev = 0.185
  CI (99.9%): [4.915, 11.664] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.774 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.005 ms/op
Iteration   1: 3.312 ±(99.9%) 0.011 ms/op
Iteration   2: 3.383 ±(99.9%) 0.007 ms/op
Iteration   3: 3.356 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.350 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (3.312, 3.350, 3.383), stdev = 0.036
  CI (99.9%): [2.697, 4.003] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.942 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.007 ms/op
Iteration   1: 3.313 ±(99.9%) 0.007 ms/op
Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
Iteration   3: 3.290 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.242 ±(99.9%) 1.891 ms/op [Average]
  (min, avg, max) = (3.123, 3.242, 3.313), stdev = 0.104
  CI (99.9%): [1.350, 5.133] (assumes normal distribution)


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
# Warmup Iteration   1: 9.236 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.003 ms/op
Iteration   1: 3.342 ±(99.9%) 0.005 ms/op
Iteration   2: 3.289 ±(99.9%) 0.010 ms/op
Iteration   3: 3.315 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.315 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (3.289, 3.315, 3.342), stdev = 0.027
  CI (99.9%): [2.827, 3.804] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.316 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.009 ms/op
Iteration   1: 3.951 ±(99.9%) 0.010 ms/op
Iteration   2: 3.953 ±(99.9%) 0.012 ms/op
Iteration   3: 3.813 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.906 ±(99.9%) 1.467 ms/op [Average]
  (min, avg, max) = (3.813, 3.906, 3.953), stdev = 0.080
  CI (99.9%): [2.439, 5.372] (assumes normal distribution)


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
# Warmup Iteration   1: 9.318 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.009 ms/op
Iteration   1: 3.337 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.608 ms/op
                 createUser·p0.999:  21.141 ms/op
                 createUser·p0.9999: 23.279 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   2: 3.403 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  22.250 ms/op
                 createUser·p0.9999: 24.943 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   3: 3.558 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  17.138 ms/op
                 createUser·p0.9999: 29.262 ms/op
                 createUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279795
  mean =      3.430 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10348 
    [ 2.500,  5.000) = 263101 
    [ 5.000,  7.500) = 5381 
    [ 7.500, 10.000) = 456 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     20.061 ms/op
     p(99.9900) =     28.117 ms/op
     p(99.9990) =     29.872 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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
# Warmup Iteration   1: 8.609 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.513 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.008 ms/op
Iteration   1: 3.310 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.808 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  8.716 ms/op
                 existUser·p0.9999: 22.392 ms/op
                 existUser·p1.00:   22.839 ms/op

Iteration   2: 3.266 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  15.106 ms/op
                 existUser·p0.9999: 25.625 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   3: 3.366 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  17.582 ms/op
                 existUser·p0.9999: 31.358 ms/op
                 existUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289538
  mean =      3.313 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18182 
    [ 2.500,  5.000) = 265967 
    [ 5.000,  7.500) = 4542 
    [ 7.500, 10.000) = 373 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     30.246 ms/op
     p(99.9990) =     32.287 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 10.123 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.010 ms/op
Iteration   1: 3.555 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  20.341 ms/op
                 getUser·p0.9999: 27.525 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   2: 3.374 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.673 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  21.700 ms/op
                 getUser·p0.9999: 25.250 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 3.402 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  15.942 ms/op
                 getUser·p0.9999: 26.537 ms/op
                 getUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278833
  mean =      3.442 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4739 
    [ 2.500,  5.000) = 266714 
    [ 5.000,  7.500) = 6117 
    [ 7.500, 10.000) = 702 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      6.444 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     27.827 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 11.466 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.435 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.013 ms/op
Iteration   1: 3.933 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  20.804 ms/op
                 listUser·p0.9999: 26.107 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   2: 3.952 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.238 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   3: 4.031 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.099 ms/op
                 listUser·p0.999:  15.838 ms/op
                 listUser·p0.9999: 23.134 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241654
  mean =      3.971 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 233417 
    [ 5.000,  7.500) = 6477 
    [ 7.500, 10.000) = 991 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     15.843 ms/op
     p(99.9900) =     23.811 ms/op
     p(99.9990) =     26.599 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.724 ± 3.390  ops/ms
ClientPb.existUser                       thrpt       3   9.760 ± 7.206  ops/ms
ClientPb.getUser                         thrpt       3   9.442 ± 3.464  ops/ms
ClientPb.listUser                        thrpt       3   8.290 ± 3.374  ops/ms
ClientPb.createUser                       avgt       3   3.350 ± 0.653   ms/op
ClientPb.existUser                        avgt       3   3.242 ± 1.891   ms/op
ClientPb.getUser                          avgt       3   3.315 ± 0.488   ms/op
ClientPb.listUser                         avgt       3   3.906 ± 1.467   ms/op
ClientPb.createUser                     sample  279795   3.430 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.891           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.061           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.117           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.457           ms/op
ClientPb.existUser                      sample  289538   3.313 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.027           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.074           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.246           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.375           ms/op
ClientPb.getUser                        sample  278833   3.442 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.873           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.141           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.444           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.743           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.640           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.410           ms/op
ClientPb.listUser                       sample  241654   3.971 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.606           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.843           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.811           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.771           ms/op
