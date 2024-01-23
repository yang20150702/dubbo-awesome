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
# Warmup Iteration   1: 5.012 ops/ms
# Warmup Iteration   2: 12.140 ops/ms
# Warmup Iteration   3: 12.772 ops/ms
Iteration   1: 12.824 ops/ms
Iteration   2: 12.935 ops/ms
Iteration   3: 13.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.924 ±(99.9%) 1.730 ops/ms [Average]
  (min, avg, max) = (12.824, 12.924, 13.012), stdev = 0.095
  CI (99.9%): [11.194, 14.654] (assumes normal distribution)


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
# Warmup Iteration   1: 8.529 ops/ms
# Warmup Iteration   2: 13.260 ops/ms
# Warmup Iteration   3: 13.254 ops/ms
Iteration   1: 13.277 ops/ms
Iteration   2: 13.205 ops/ms
Iteration   3: 13.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.281 ±(99.9%) 1.413 ops/ms [Average]
  (min, avg, max) = (13.205, 13.281, 13.360), stdev = 0.077
  CI (99.9%): [11.867, 14.694] (assumes normal distribution)


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
# Warmup Iteration   1: 8.083 ops/ms
# Warmup Iteration   2: 12.548 ops/ms
# Warmup Iteration   3: 12.735 ops/ms
Iteration   1: 12.842 ops/ms
Iteration   2: 12.769 ops/ms
Iteration   3: 12.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.795 ±(99.9%) 0.750 ops/ms [Average]
  (min, avg, max) = (12.769, 12.795, 12.842), stdev = 0.041
  CI (99.9%): [12.045, 13.545] (assumes normal distribution)


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
# Warmup Iteration   1: 6.541 ops/ms
# Warmup Iteration   2: 10.538 ops/ms
# Warmup Iteration   3: 10.712 ops/ms
Iteration   1: 10.897 ops/ms
Iteration   2: 10.764 ops/ms
Iteration   3: 10.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.807 ±(99.9%) 1.420 ops/ms [Average]
  (min, avg, max) = (10.761, 10.807, 10.897), stdev = 0.078
  CI (99.9%): [9.387, 12.227] (assumes normal distribution)


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
# Warmup Iteration   1: 4.115 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.652 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.630 ±(99.9%) 0.005 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
Iteration   3: 2.520 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.509 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (2.490, 2.509, 2.520), stdev = 0.016
  CI (99.9%): [2.212, 2.806] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.708 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.394 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.004 ms/op
Iteration   1: 2.404 ±(99.9%) 0.004 ms/op
Iteration   2: 2.428 ±(99.9%) 0.003 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.434 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (2.404, 2.434, 2.471), stdev = 0.034
  CI (99.9%): [1.814, 3.054] (assumes normal distribution)


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.006 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
Iteration   3: 2.583 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 1.464 ms/op [Average]
  (min, avg, max) = (2.423, 2.501, 2.583), stdev = 0.080
  CI (99.9%): [1.036, 3.965] (assumes normal distribution)


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
# Warmup Iteration   1: 5.031 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.005 ms/op
Iteration   1: 3.096 ±(99.9%) 0.007 ms/op
Iteration   2: 3.049 ±(99.9%) 0.005 ms/op
Iteration   3: 3.071 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.072 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (3.049, 3.072, 3.096), stdev = 0.023
  CI (99.9%): [2.646, 3.498] (assumes normal distribution)


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
# Warmup Iteration   1: 4.657 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.007 ms/op
Iteration   1: 2.556 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.457 ms/op
                 createUser·p0.50:   2.482 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  12.387 ms/op
                 createUser·p0.9999: 15.310 ms/op
                 createUser·p1.00:   15.876 ms/op

Iteration   2: 2.520 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   2.445 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  11.733 ms/op
                 createUser·p0.9999: 13.997 ms/op
                 createUser·p1.00:   16.630 ms/op

Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.433 ms/op
                 createUser·p0.50:   2.441 ms/op
                 createUser·p0.90:   3.191 ms/op
                 createUser·p0.95:   3.478 ms/op
                 createUser·p0.99:   4.214 ms/op
                 createUser·p0.999:  9.388 ms/op
                 createUser·p0.9999: 13.013 ms/op
                 createUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379744
  mean =      2.526 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 340 
    [ 1.250,  2.500) = 198433 
    [ 2.500,  3.750) = 169348 
    [ 3.750,  5.000) = 9906 
    [ 5.000,  6.250) = 725 
    [ 6.250,  7.500) = 233 
    [ 7.500,  8.750) = 171 
    [ 8.750, 10.000) = 167 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      3.240 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =     10.584 ms/op
     p(99.9900) =     14.861 ms/op
     p(99.9990) =     15.748 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.416 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.405 ±(99.9%) 0.006 ms/op
Iteration   1: 2.369 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   2.302 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  5.915 ms/op
                 existUser·p0.9999: 15.163 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 2.375 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   2.331 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.232 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  7.288 ms/op
                 existUser·p0.9999: 14.403 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   3: 2.323 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.455 ms/op
                 existUser·p0.50:   2.253 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.265 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  9.863 ms/op
                 existUser·p0.9999: 12.321 ms/op
                 existUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 407259
  mean =      2.355 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 485 
    [ 1.250,  2.500) = 248733 
    [ 2.500,  3.750) = 151615 
    [ 3.750,  5.000) = 5563 
    [ 5.000,  6.250) = 394 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      2.290 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.981 ms/op
     p(99.9000) =      7.926 ms/op
     p(99.9900) =     14.476 ms/op
     p(99.9990) =     16.609 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.006 ms/op
Iteration   1: 2.434 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   2.380 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  8.332 ms/op
                 getUser·p0.9999: 13.795 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 2.469 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   2.421 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  8.255 ms/op
                 getUser·p0.9999: 14.780 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   3: 2.474 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.851 ms/op
                 getUser·p0.9999: 11.494 ms/op
                 getUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389999
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 249 
    [ 1.250,  2.500) = 208802 
    [ 2.500,  3.750) = 173683 
    [ 3.750,  5.000) = 6072 
    [ 5.000,  6.250) = 708 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      2.408 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      8.061 ms/op
     p(99.9900) =     13.828 ms/op
     p(99.9990) =     15.388 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 4.925 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.008 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 11.199 ms/op
                 listUser·p1.00:   11.485 ms/op

Iteration   2: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 10.766 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   3: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 10.830 ms/op
                 listUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316019
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 89834 
    [ 2.500,  3.750) = 185325 
    [ 3.750,  5.000) = 32868 
    [ 5.000,  6.250) = 6401 
    [ 6.250,  7.500) = 766 
    [ 7.500,  8.750) = 234 
    [ 8.750, 10.000) = 281 
    [10.000, 11.250) = 175 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     10.853 ms/op
     p(99.9990) =     11.731 ms/op
     p(99.9999) =     12.141 ms/op
    p(100.0000) =     12.141 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.924 ± 1.730  ops/ms
ClientPb.existUser                       thrpt       3  13.281 ± 1.413  ops/ms
ClientPb.getUser                         thrpt       3  12.795 ± 0.750  ops/ms
ClientPb.listUser                        thrpt       3  10.807 ± 1.420  ops/ms
ClientPb.createUser                       avgt       3   2.509 ± 0.297   ms/op
ClientPb.existUser                        avgt       3   2.434 ± 0.620   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 1.464   ms/op
ClientPb.listUser                         avgt       3   3.072 ± 0.426   ms/op
ClientPb.createUser                     sample  379744   2.526 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.433           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.458           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.527           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.584           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.861           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.630           ms/op
ClientPb.existUser                      sample  407259   2.355 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.455           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.290           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.926           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.476           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.138           ms/op
ClientPb.getUser                        sample  389999   2.459 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.617           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.408           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.061           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.828           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.516           ms/op
ClientPb.listUser                       sample  316019   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.804           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.853           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.141           ms/op
