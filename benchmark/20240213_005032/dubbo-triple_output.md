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
# Warmup Iteration   1: 4.776 ops/ms
# Warmup Iteration   2: 12.192 ops/ms
# Warmup Iteration   3: 12.566 ops/ms
Iteration   1: 12.846 ops/ms
Iteration   2: 12.855 ops/ms
Iteration   3: 12.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.876 ±(99.9%) 0.804 ops/ms [Average]
  (min, avg, max) = (12.846, 12.876, 12.927), stdev = 0.044
  CI (99.9%): [12.072, 13.680] (assumes normal distribution)


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
# Warmup Iteration   1: 8.638 ops/ms
# Warmup Iteration   2: 13.337 ops/ms
# Warmup Iteration   3: 13.429 ops/ms
Iteration   1: 13.309 ops/ms
Iteration   2: 13.330 ops/ms
Iteration   3: 13.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.236 ±(99.9%) 2.655 ops/ms [Average]
  (min, avg, max) = (13.068, 13.236, 13.330), stdev = 0.146
  CI (99.9%): [10.580, 15.891] (assumes normal distribution)


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
# Warmup Iteration   1: 8.342 ops/ms
# Warmup Iteration   2: 12.763 ops/ms
# Warmup Iteration   3: 13.070 ops/ms
Iteration   1: 13.044 ops/ms
Iteration   2: 13.137 ops/ms
Iteration   3: 12.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.041 ±(99.9%) 1.767 ops/ms [Average]
  (min, avg, max) = (12.943, 13.041, 13.137), stdev = 0.097
  CI (99.9%): [11.274, 14.809] (assumes normal distribution)


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
# Warmup Iteration   1: 6.483 ops/ms
# Warmup Iteration   2: 10.610 ops/ms
# Warmup Iteration   3: 10.951 ops/ms
Iteration   1: 11.007 ops/ms
Iteration   2: 10.894 ops/ms
Iteration   3: 10.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.916 ±(99.9%) 1.493 ops/ms [Average]
  (min, avg, max) = (10.848, 10.916, 11.007), stdev = 0.082
  CI (99.9%): [9.424, 12.409] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.907 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.484 ±(99.9%) 0.003 ms/op
Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
Iteration   3: 2.524 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.515 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (2.484, 2.515, 2.537), stdev = 0.028
  CI (99.9%): [2.012, 3.018] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.703 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.399 ±(99.9%) 0.004 ms/op
Iteration   1: 2.427 ±(99.9%) 0.003 ms/op
Iteration   2: 2.424 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.427 ±(99.9%) 0.064 ms/op [Average]
  (min, avg, max) = (2.424, 2.427, 2.431), stdev = 0.004
  CI (99.9%): [2.363, 2.491] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.706 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.004 ms/op
Iteration   1: 2.466 ±(99.9%) 0.004 ms/op
Iteration   2: 2.442 ±(99.9%) 0.003 ms/op
Iteration   3: 2.447 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.452 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (2.442, 2.452, 2.466), stdev = 0.013
  CI (99.9%): [2.217, 2.686] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.724 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.005 ms/op
Iteration   1: 2.959 ±(99.9%) 0.005 ms/op
Iteration   2: 2.929 ±(99.9%) 0.004 ms/op
Iteration   3: 2.951 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.946 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.929, 2.946, 2.959), stdev = 0.015
  CI (99.9%): [2.665, 3.228] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   3.482 ms/op
                 createUser·p0.999:  6.243 ms/op
                 createUser·p0.9999: 13.386 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  6.988 ms/op
                 createUser·p0.9999: 16.581 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.468 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.706 ms/op
                 createUser·p0.999:  7.749 ms/op
                 createUser·p0.9999: 9.863 ms/op
                 createUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389107
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 192979 
    [ 2.500,  3.750) = 193037 
    [ 3.750,  5.000) = 2250 
    [ 5.000,  6.250) = 325 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      7.387 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     17.247 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 3.604 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.420 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.409 ±(99.9%) 0.005 ms/op
Iteration   1: 2.394 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.305 ms/op
                 existUser·p0.999:  5.468 ms/op
                 existUser·p0.9999: 13.369 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.398 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.408 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  7.187 ms/op
                 existUser·p0.9999: 12.632 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   3: 2.374 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.380 ms/op
                 existUser·p0.90:   2.888 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.579 ms/op
                 existUser·p0.999:  7.892 ms/op
                 existUser·p0.9999: 11.281 ms/op
                 existUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401462
  mean =      2.389 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 208605 
    [ 2.500,  3.750) = 190267 
    [ 3.750,  5.000) = 1894 
    [ 5.000,  6.250) = 198 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      2.421 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      3.441 ms/op
     p(99.9000) =      7.458 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     13.484 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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
# Warmup Iteration   1: 3.735 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.006 ms/op
Iteration   1: 2.450 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  6.321 ms/op
                 getUser·p0.9999: 14.939 ms/op
                 getUser·p1.00:   15.368 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  8.969 ms/op
                 getUser·p0.9999: 12.223 ms/op
                 getUser·p1.00:   13.058 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  7.267 ms/op
                 getUser·p0.9999: 11.043 ms/op
                 getUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390009
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 196609 
    [ 2.500,  3.750) = 189918 
    [ 3.750,  5.000) = 2674 
    [ 5.000,  6.250) = 304 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      7.446 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     15.178 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


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
# Warmup Iteration   1: 4.498 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.008 ms/op
Iteration   1: 2.934 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.323 ms/op
                 listUser·p0.9999: 11.715 ms/op
                 listUser·p1.00:   13.091 ms/op

Iteration   2: 2.935 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 12.845 ms/op
                 listUser·p1.00:   13.697 ms/op

Iteration   3: 2.936 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  10.061 ms/op
                 listUser·p0.9999: 12.079 ms/op
                 listUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 326752
  mean =      2.935 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 149 
    [ 1.250,  2.500) = 109440 
    [ 2.500,  3.750) = 181995 
    [ 3.750,  5.000) = 28444 
    [ 5.000,  6.250) = 5457 
    [ 6.250,  7.500) = 646 
    [ 7.500,  8.750) = 162 
    [ 8.750, 10.000) = 167 
    [10.000, 11.250) = 215 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      9.769 ms/op
     p(99.9900) =     12.195 ms/op
     p(99.9990) =     13.681 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.876 ± 0.804  ops/ms
ClientPb.existUser                       thrpt       3  13.236 ± 2.655  ops/ms
ClientPb.getUser                         thrpt       3  13.041 ± 1.767  ops/ms
ClientPb.listUser                        thrpt       3  10.916 ± 1.493  ops/ms
ClientPb.createUser                       avgt       3   2.515 ± 0.503   ms/op
ClientPb.existUser                        avgt       3   2.427 ± 0.064   ms/op
ClientPb.getUser                          avgt       3   2.452 ± 0.235   ms/op
ClientPb.listUser                         avgt       3   2.946 ± 0.281   ms/op
ClientPb.createUser                     sample  389107   2.465 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.468           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.519           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.387           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.564           ms/op
ClientPb.existUser                      sample  401462   2.389 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.937           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.421           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.904           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.458           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.878           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.041           ms/op
ClientPb.getUser                        sample  390009   2.459 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.912           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.446           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.746           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.368           ms/op
ClientPb.listUser                       sample  326752   2.935 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.823           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.769           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.195           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.697           ms/op
