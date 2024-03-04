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
# Warmup Iteration   1: 5.276 ops/ms
# Warmup Iteration   2: 12.453 ops/ms
# Warmup Iteration   3: 12.681 ops/ms
Iteration   1: 12.898 ops/ms
Iteration   2: 13.005 ops/ms
Iteration   3: 13.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.986 ±(99.9%) 1.463 ops/ms [Average]
  (min, avg, max) = (12.898, 12.986, 13.055), stdev = 0.080
  CI (99.9%): [11.523, 14.449] (assumes normal distribution)


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
# Warmup Iteration   1: 8.311 ops/ms
# Warmup Iteration   2: 12.945 ops/ms
# Warmup Iteration   3: 13.311 ops/ms
Iteration   1: 13.295 ops/ms
Iteration   2: 13.202 ops/ms
Iteration   3: 13.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.246 ±(99.9%) 0.846 ops/ms [Average]
  (min, avg, max) = (13.202, 13.246, 13.295), stdev = 0.046
  CI (99.9%): [12.399, 14.092] (assumes normal distribution)


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
# Warmup Iteration   1: 7.713 ops/ms
# Warmup Iteration   2: 12.836 ops/ms
# Warmup Iteration   3: 13.074 ops/ms
Iteration   1: 13.279 ops/ms
Iteration   2: 13.236 ops/ms
Iteration   3: 13.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.224 ±(99.9%) 1.149 ops/ms [Average]
  (min, avg, max) = (13.155, 13.224, 13.279), stdev = 0.063
  CI (99.9%): [12.075, 14.372] (assumes normal distribution)


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
# Warmup Iteration   1: 6.630 ops/ms
# Warmup Iteration   2: 10.571 ops/ms
# Warmup Iteration   3: 10.549 ops/ms
Iteration   1: 10.616 ops/ms
Iteration   2: 10.659 ops/ms
Iteration   3: 10.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.660 ±(99.9%) 0.809 ops/ms [Average]
  (min, avg, max) = (10.616, 10.660, 10.705), stdev = 0.044
  CI (99.9%): [9.851, 11.468] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.004 ms/op
Iteration   1: 2.458 ±(99.9%) 0.003 ms/op
Iteration   2: 2.453 ±(99.9%) 0.003 ms/op
Iteration   3: 2.458 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.456 ±(99.9%) 0.060 ms/op [Average]
  (min, avg, max) = (2.453, 2.456, 2.458), stdev = 0.003
  CI (99.9%): [2.397, 2.516] (assumes normal distribution)


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.391 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.391 ±(99.9%) 0.003 ms/op
Iteration   1: 2.383 ±(99.9%) 0.004 ms/op
Iteration   2: 2.385 ±(99.9%) 0.004 ms/op
Iteration   3: 2.375 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.381 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (2.375, 2.381, 2.385), stdev = 0.005
  CI (99.9%): [2.283, 2.478] (assumes normal distribution)


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.421 ±(99.9%) 0.003 ms/op
Iteration   1: 2.397 ±(99.9%) 0.005 ms/op
Iteration   2: 2.390 ±(99.9%) 0.003 ms/op
Iteration   3: 2.430 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.406 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (2.390, 2.406, 2.430), stdev = 0.021
  CI (99.9%): [2.022, 2.790] (assumes normal distribution)


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
# Warmup Iteration   1: 4.758 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.005 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
Iteration   2: 2.979 ±(99.9%) 0.005 ms/op
Iteration   3: 2.993 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.985 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (2.979, 2.985, 2.993), stdev = 0.007
  CI (99.9%): [2.852, 3.118] (assumes normal distribution)


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.007 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  6.558 ms/op
                 createUser·p0.9999: 14.025 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.490 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   3.461 ms/op
                 createUser·p0.999:  10.076 ms/op
                 createUser·p0.9999: 12.576 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   4.092 ms/op
                 createUser·p0.999:  8.584 ms/op
                 createUser·p0.9999: 10.240 ms/op
                 createUser·p1.00:   10.584 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389470
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 193651 
    [ 2.500,  3.750) = 191827 
    [ 3.750,  5.000) = 2979 
    [ 5.000,  6.250) = 389 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.807 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.425 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.378 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
Iteration   1: 2.368 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.867 ms/op
                 existUser·p0.95:   2.961 ms/op
                 existUser·p0.99:   3.297 ms/op
                 existUser·p0.999:  5.724 ms/op
                 existUser·p0.9999: 13.394 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.375 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  6.295 ms/op
                 existUser·p0.9999: 13.997 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   3: 2.380 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.404 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.694 ms/op
                 existUser·p0.999:  6.902 ms/op
                 existUser·p0.9999: 11.569 ms/op
                 existUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 403988
  mean =      2.374 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 209069 
    [ 2.500,  3.750) = 192112 
    [ 3.750,  5.000) = 2050 
    [ 5.000,  6.250) = 255 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 128 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.449 ms/op
     p(90.0000) =      2.884 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      3.523 ms/op
     p(99.9000) =      6.521 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.350 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.425 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.721 ms/op
                 getUser·p0.999:  5.582 ms/op
                 getUser·p0.9999: 13.546 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.062 ms/op
                 getUser·p0.9999: 12.206 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   3: 2.396 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   2.408 ms/op
                 getUser·p0.90:   2.925 ms/op
                 getUser·p0.95:   3.047 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  5.335 ms/op
                 getUser·p0.9999: 10.949 ms/op
                 getUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 396046
  mean =      2.422 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 207749 
    [ 2.500,  3.750) = 183505 
    [ 3.750,  5.000) = 3815 
    [ 5.000,  6.250) = 448 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 140 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.429 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.861 ms/op
     p(99.9000) =      6.511 ms/op
     p(99.9900) =     12.983 ms/op
     p(99.9990) =     14.140 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 2.982 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.008 ms/op
Iteration   1: 2.948 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.261 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   2: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.703 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.932 ms/op
                 listUser·p0.9999: 11.934 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   3: 2.932 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.790 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 11.161 ms/op
                 listUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325435
  mean =      2.948 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 103469 
    [ 2.500,  3.750) = 185379 
    [ 3.750,  5.000) = 29563 
    [ 5.000,  6.250) = 5599 
    [ 6.250,  7.500) = 549 
    [ 7.500,  8.750) = 281 
    [ 8.750, 10.000) = 280 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     11.697 ms/op
     p(99.9990) =     12.418 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.986 ± 1.463  ops/ms
ClientPb.existUser                       thrpt       3  13.246 ± 0.846  ops/ms
ClientPb.getUser                         thrpt       3  13.224 ± 1.149  ops/ms
ClientPb.listUser                        thrpt       3  10.660 ± 0.809  ops/ms
ClientPb.createUser                       avgt       3   2.456 ± 0.060   ms/op
ClientPb.existUser                        avgt       3   2.381 ± 0.097   ms/op
ClientPb.getUser                          avgt       3   2.406 ± 0.384   ms/op
ClientPb.listUser                         avgt       3   2.985 ± 0.133   ms/op
ClientPb.createUser                     sample  389470   2.463 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.759           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.511           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.807           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.320           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.549           ms/op
ClientPb.existUser                      sample  403988   2.374 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.685           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.449           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.884           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.521           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.386           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.516           ms/op
ClientPb.getUser                        sample  396046   2.422 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.768           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.429           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.861           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.511           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.983           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.369           ms/op
ClientPb.listUser                       sample  325435   2.948 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.703           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.884           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.697           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.534           ms/op
