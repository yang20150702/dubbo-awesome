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
# Warmup Iteration   1: 5.080 ops/ms
# Warmup Iteration   2: 12.490 ops/ms
# Warmup Iteration   3: 12.531 ops/ms
Iteration   1: 12.837 ops/ms
Iteration   2: 12.906 ops/ms
Iteration   3: 12.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.893 ±(99.9%) 0.932 ops/ms [Average]
  (min, avg, max) = (12.837, 12.893, 12.937), stdev = 0.051
  CI (99.9%): [11.961, 13.825] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 9.156 ops/ms
# Warmup Iteration   2: 13.523 ops/ms
# Warmup Iteration   3: 13.519 ops/ms
Iteration   1: 13.633 ops/ms
Iteration   2: 13.613 ops/ms
Iteration   3: 13.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.591 ±(99.9%) 1.045 ops/ms [Average]
  (min, avg, max) = (13.526, 13.591, 13.633), stdev = 0.057
  CI (99.9%): [12.546, 14.635] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.374 ops/ms
# Warmup Iteration   2: 12.773 ops/ms
# Warmup Iteration   3: 13.325 ops/ms
Iteration   1: 13.198 ops/ms
Iteration   2: 13.170 ops/ms
Iteration   3: 13.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.266 ±(99.9%) 2.601 ops/ms [Average]
  (min, avg, max) = (13.170, 13.266, 13.430), stdev = 0.143
  CI (99.9%): [10.665, 15.867] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.399 ops/ms
# Warmup Iteration   2: 10.785 ops/ms
# Warmup Iteration   3: 11.054 ops/ms
Iteration   1: 10.951 ops/ms
Iteration   2: 10.989 ops/ms
Iteration   3: 11.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  11.006 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (10.951, 11.006, 11.077), stdev = 0.064
  CI (99.9%): [9.831, 12.180] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.678 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.003 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.428 ±(99.9%) 0.004 ms/op
Iteration   3: 2.401 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.439 ±(99.9%) 0.802 ms/op [Average]
  (min, avg, max) = (2.401, 2.439, 2.487), stdev = 0.044
  CI (99.9%): [1.636, 3.241] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.483 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.375 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.373 ±(99.9%) 0.004 ms/op
Iteration   1: 2.327 ±(99.9%) 0.004 ms/op
Iteration   2: 2.381 ±(99.9%) 0.003 ms/op
Iteration   3: 2.406 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.372 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (2.327, 2.372, 2.406), stdev = 0.041
  CI (99.9%): [1.631, 3.112] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.611 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.387 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.004 ms/op
Iteration   1: 2.415 ±(99.9%) 0.004 ms/op
Iteration   2: 2.412 ±(99.9%) 0.005 ms/op
Iteration   3: 2.422 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.416 ±(99.9%) 0.091 ms/op [Average]
  (min, avg, max) = (2.412, 2.416, 2.422), stdev = 0.005
  CI (99.9%): [2.325, 2.508] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.476 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.924 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.920 ±(99.9%) 0.005 ms/op
Iteration   1: 2.888 ±(99.9%) 0.005 ms/op
Iteration   2: 2.908 ±(99.9%) 0.005 ms/op
Iteration   3: 2.887 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.894 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (2.887, 2.894, 2.908), stdev = 0.012
  CI (99.9%): [2.682, 3.107] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.838 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
Iteration   1: 2.431 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   2.425 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.506 ms/op
                 createUser·p0.999:  6.235 ms/op
                 createUser·p0.9999: 13.599 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.424 ms/op
                 createUser·p0.999:  6.043 ms/op
                 createUser·p0.9999: 11.796 ms/op
                 createUser·p1.00:   12.403 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   2.470 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  7.622 ms/op
                 createUser·p0.9999: 11.435 ms/op
                 createUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391718
  mean =      2.448 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 199644 
    [ 2.500,  3.750) = 189305 
    [ 3.750,  5.000) = 2139 
    [ 5.000,  6.250) = 168 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =      6.358 ms/op
     p(99.9900) =     12.777 ms/op
     p(99.9990) =     14.092 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 3.519 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.400 ±(99.9%) 0.005 ms/op
Iteration   1: 2.383 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  6.160 ms/op
                 existUser·p0.9999: 13.841 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.372 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.888 ms/op
                 existUser·p0.95:   2.982 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  6.140 ms/op
                 existUser·p0.9999: 11.387 ms/op
                 existUser·p1.00:   11.682 ms/op

Iteration   3: 2.378 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  8.016 ms/op
                 existUser·p0.9999: 10.863 ms/op
                 existUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 403357
  mean =      2.378 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 209758 
    [ 2.500,  3.750) = 191124 
    [ 3.750,  5.000) = 1745 
    [ 5.000,  6.250) = 232 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 162 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      3.412 ms/op
     p(99.9000) =      7.736 ms/op
     p(99.9900) =     12.419 ms/op
     p(99.9990) =     14.104 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 3.786 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.417 ±(99.9%) 0.005 ms/op
Iteration   1: 2.404 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.413 ms/op
                 getUser·p0.90:   2.945 ms/op
                 getUser·p0.95:   3.043 ms/op
                 getUser·p0.99:   3.391 ms/op
                 getUser·p0.999:  5.366 ms/op
                 getUser·p0.9999: 12.934 ms/op
                 getUser·p1.00:   13.484 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  6.402 ms/op
                 getUser·p0.9999: 13.589 ms/op
                 getUser·p1.00:   15.483 ms/op

Iteration   3: 2.388 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.367 ms/op
                 getUser·p0.90:   2.945 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.572 ms/op
                 getUser·p0.999:  7.357 ms/op
                 getUser·p0.9999: 10.086 ms/op
                 getUser·p1.00:   10.240 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 398435
  mean =      2.408 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 209914 
    [ 2.500,  3.750) = 185333 
    [ 3.750,  5.000) = 2309 
    [ 5.000,  6.250) = 369 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.400 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     12.749 ms/op
     p(99.9990) =     15.418 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 4.681 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.969 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.906 ±(99.9%) 0.008 ms/op
Iteration   1: 2.933 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.732 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  8.552 ms/op
                 listUser·p0.9999: 9.988 ms/op
                 listUser·p1.00:   11.305 ms/op

Iteration   2: 2.915 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.858 ms/op
                 listUser·p0.50:   2.851 ms/op
                 listUser·p0.90:   3.752 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 11.439 ms/op
                 listUser·p1.00:   13.091 ms/op

Iteration   3: 2.945 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.787 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.396 ms/op
                 listUser·p0.9999: 11.282 ms/op
                 listUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 327223
  mean =      2.931 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 106877 
    [ 2.500,  3.750) = 185926 
    [ 3.750,  5.000) = 27700 
    [ 5.000,  6.250) = 5226 
    [ 6.250,  7.500) = 725 
    [ 7.500,  8.750) = 278 
    [ 8.750, 10.000) = 225 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     11.110 ms/op
     p(99.9990) =     12.100 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.893 ± 0.932  ops/ms
ClientPb.existUser                       thrpt       3  13.591 ± 1.045  ops/ms
ClientPb.getUser                         thrpt       3  13.266 ± 2.601  ops/ms
ClientPb.listUser                        thrpt       3  11.006 ± 1.175  ops/ms
ClientPb.createUser                       avgt       3   2.439 ± 0.802   ms/op
ClientPb.existUser                        avgt       3   2.372 ± 0.741   ms/op
ClientPb.getUser                          avgt       3   2.416 ± 0.091   ms/op
ClientPb.listUser                         avgt       3   2.894 ± 0.212   ms/op
ClientPb.createUser                     sample  391718   2.448 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.818           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.462           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.555           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.358           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.777           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.156           ms/op
ClientPb.existUser                      sample  403357   2.378 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.930           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.437           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.896           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.736           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.419           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.713           ms/op
ClientPb.getUser                        sample  398435   2.408 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.604           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.726           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.749           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.483           ms/op
ClientPb.listUser                       sample  327223   2.931 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.732           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.733           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.110           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.091           ms/op
