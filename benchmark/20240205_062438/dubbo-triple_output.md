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
# Warmup Iteration   1: 4.587 ops/ms
# Warmup Iteration   2: 11.962 ops/ms
# Warmup Iteration   3: 12.115 ops/ms
Iteration   1: 12.422 ops/ms
Iteration   2: 12.359 ops/ms
Iteration   3: 12.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.405 ±(99.9%) 0.749 ops/ms [Average]
  (min, avg, max) = (12.359, 12.405, 12.435), stdev = 0.041
  CI (99.9%): [11.656, 13.154] (assumes normal distribution)


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
# Warmup Iteration   1: 7.395 ops/ms
# Warmup Iteration   2: 12.463 ops/ms
# Warmup Iteration   3: 12.523 ops/ms
Iteration   1: 12.425 ops/ms
Iteration   2: 12.586 ops/ms
Iteration   3: 12.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.540 ±(99.9%) 1.822 ops/ms [Average]
  (min, avg, max) = (12.425, 12.540, 12.609), stdev = 0.100
  CI (99.9%): [10.718, 14.362] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.275 ops/ms
# Warmup Iteration   2: 12.257 ops/ms
# Warmup Iteration   3: 12.395 ops/ms
Iteration   1: 12.474 ops/ms
Iteration   2: 12.257 ops/ms
Iteration   3: 12.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.436 ±(99.9%) 2.965 ops/ms [Average]
  (min, avg, max) = (12.257, 12.436, 12.575), stdev = 0.163
  CI (99.9%): [9.471, 15.401] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.454 ops/ms
# Warmup Iteration   2: 10.312 ops/ms
# Warmup Iteration   3: 10.347 ops/ms
Iteration   1: 10.445 ops/ms
Iteration   2: 10.399 ops/ms
Iteration   3: 10.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.428 ±(99.9%) 0.465 ops/ms [Average]
  (min, avg, max) = (10.399, 10.428, 10.445), stdev = 0.026
  CI (99.9%): [9.963, 10.894] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.004 ms/op
Iteration   1: 2.566 ±(99.9%) 0.004 ms/op
Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
Iteration   3: 2.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.553 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (2.544, 2.553, 2.566), stdev = 0.011
  CI (99.9%): [2.345, 2.760] (assumes normal distribution)


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
# Warmup Iteration   1: 3.641 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
Iteration   3: 2.444 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.035 ms/op [Average]
  (min, avg, max) = (2.441, 2.443, 2.444), stdev = 0.002
  CI (99.9%): [2.408, 2.478] (assumes normal distribution)


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.478 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (2.473, 2.487, 2.511), stdev = 0.021
  CI (99.9%): [2.112, 2.863] (assumes normal distribution)


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
# Warmup Iteration   1: 5.034 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.005 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
Iteration   3: 2.994 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.004 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (2.993, 3.004, 3.025), stdev = 0.018
  CI (99.9%): [2.673, 3.336] (assumes normal distribution)


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
# Warmup Iteration   1: 4.495 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.719 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  12.226 ms/op
                 createUser·p0.9999: 16.482 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  10.081 ms/op
                 createUser·p0.9999: 12.766 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  8.720 ms/op
                 createUser·p0.9999: 13.027 ms/op
                 createUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380233
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 181705 
    [ 2.500,  3.750) = 195189 
    [ 3.750,  5.000) = 2585 
    [ 5.000,  6.250) = 204 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      9.581 ms/op
     p(99.9900) =     15.367 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  8.278 ms/op
                 existUser·p0.9999: 13.730 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  8.923 ms/op
                 existUser·p0.9999: 13.223 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  8.357 ms/op
                 existUser·p0.9999: 12.190 ms/op
                 existUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388902
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 191257 
    [ 2.500,  3.750) = 194711 
    [ 3.750,  5.000) = 2168 
    [ 5.000,  6.250) = 271 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      8.368 ms/op
     p(99.9900) =     13.437 ms/op
     p(99.9990) =     14.453 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.693 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  11.779 ms/op
                 getUser·p0.9999: 13.768 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  10.995 ms/op
                 getUser·p0.9999: 14.181 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.006 ms/op
                 getUser·p0.999:  9.253 ms/op
                 getUser·p0.9999: 11.770 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377629
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 184304 
    [ 2.500,  3.750) = 187923 
    [ 3.750,  5.000) = 4074 
    [ 5.000,  6.250) = 834 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =      9.279 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     14.638 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.746 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.009 ms/op
Iteration   1: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.025 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.813 ms/op
                 listUser·p0.9999: 12.296 ms/op
                 listUser·p1.00:   13.566 ms/op

Iteration   2: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  10.646 ms/op
                 listUser·p0.9999: 12.326 ms/op
                 listUser·p1.00:   13.681 ms/op

Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.832 ms/op
                 listUser·p0.9999: 11.959 ms/op
                 listUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315733
  mean =      3.038 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 88597 
    [ 2.500,  3.750) = 185745 
    [ 3.750,  5.000) = 33697 
    [ 5.000,  6.250) = 6191 
    [ 6.250,  7.500) = 699 
    [ 7.500,  8.750) = 153 
    [ 8.750, 10.000) = 213 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.982 ms/op
     p(99.9900) =     12.190 ms/op
     p(99.9990) =     13.463 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.405 ± 0.749  ops/ms
ClientPb.existUser                       thrpt       3  12.540 ± 1.822  ops/ms
ClientPb.getUser                         thrpt       3  12.436 ± 2.965  ops/ms
ClientPb.listUser                        thrpt       3  10.428 ± 0.465  ops/ms
ClientPb.createUser                       avgt       3   2.553 ± 0.208   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.035   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.375   ms/op
ClientPb.listUser                         avgt       3   3.004 ± 0.332   ms/op
ClientPb.createUser                     sample  380233   2.522 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.949           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.581           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.367           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.170           ms/op
ClientPb.existUser                      sample  388902   2.466 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.787           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.368           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.437           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.483           ms/op
ClientPb.getUser                        sample  377629   2.540 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.855           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.279           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.730           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.713           ms/op
ClientPb.listUser                       sample  315733   3.038 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.950           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.982           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.190           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.681           ms/op
