# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.984 ops/ms
# Warmup Iteration   2: 12.036 ops/ms
# Warmup Iteration   3: 12.376 ops/ms
Iteration   1: 12.666 ops/ms
Iteration   2: 12.525 ops/ms
Iteration   3: 12.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.603 ±(99.9%) 1.306 ops/ms [Average]
  (min, avg, max) = (12.525, 12.603, 12.666), stdev = 0.072
  CI (99.9%): [11.296, 13.909] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.198 ops/ms
# Warmup Iteration   2: 13.313 ops/ms
# Warmup Iteration   3: 13.300 ops/ms
Iteration   1: 13.022 ops/ms
Iteration   2: 13.387 ops/ms
Iteration   3: 13.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.247 ±(99.9%) 3.594 ops/ms [Average]
  (min, avg, max) = (13.022, 13.247, 13.387), stdev = 0.197
  CI (99.9%): [9.653, 16.842] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.005 ops/ms
# Warmup Iteration   2: 12.488 ops/ms
# Warmup Iteration   3: 12.714 ops/ms
Iteration   1: 12.902 ops/ms
Iteration   2: 12.770 ops/ms
Iteration   3: 12.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.840 ±(99.9%) 1.213 ops/ms [Average]
  (min, avg, max) = (12.770, 12.840, 12.902), stdev = 0.067
  CI (99.9%): [11.627, 14.053] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.737 ops/ms
# Warmup Iteration   2: 10.374 ops/ms
# Warmup Iteration   3: 10.557 ops/ms
Iteration   1: 10.706 ops/ms
Iteration   2: 10.672 ops/ms
Iteration   3: 10.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.695 ±(99.9%) 0.353 ops/ms [Average]
  (min, avg, max) = (10.672, 10.695, 10.706), stdev = 0.019
  CI (99.9%): [10.341, 11.048] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.453 ±(99.9%) 0.004 ms/op
Iteration   3: 2.469 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.471 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (2.453, 2.471, 2.492), stdev = 0.020
  CI (99.9%): [2.113, 2.829] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.639 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.004 ms/op
Iteration   1: 2.441 ±(99.9%) 0.003 ms/op
Iteration   2: 2.450 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.449 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (2.441, 2.449, 2.455), stdev = 0.007
  CI (99.9%): [2.317, 2.581] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.448 ±(99.9%) 0.003 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.466 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.448, 2.466, 2.491), stdev = 0.023
  CI (99.9%): [2.054, 2.878] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.671 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 2.979 ±(99.9%) 0.005 ms/op
Iteration   2: 2.953 ±(99.9%) 0.005 ms/op
Iteration   3: 2.997 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.976 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (2.953, 2.976, 2.997), stdev = 0.023
  CI (99.9%): [2.566, 3.387] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  11.419 ms/op
                 createUser·p0.9999: 15.020 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  6.018 ms/op
                 createUser·p0.9999: 11.787 ms/op
                 createUser·p1.00:   12.681 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.401 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.469 ms/op
                 createUser·p0.9999: 10.753 ms/op
                 createUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384397
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 187451 
    [ 2.500,  3.750) = 192939 
    [ 3.750,  5.000) = 3048 
    [ 5.000,  6.250) = 453 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.401 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      8.998 ms/op
     p(99.9900) =     14.074 ms/op
     p(99.9990) =     15.207 ms/op
     p(99.9999) =     16.105 ms/op
    p(100.0000) =     16.105 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.565 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  5.259 ms/op
                 existUser·p0.9999: 13.500 ms/op
                 existUser·p1.00:   13.894 ms/op

Iteration   2: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  8.379 ms/op
                 existUser·p0.9999: 12.764 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.850 ms/op
                 existUser·p0.999:  7.333 ms/op
                 existUser·p0.9999: 13.107 ms/op
                 existUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394262
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 199141 
    [ 2.500,  3.750) = 191893 
    [ 3.750,  5.000) = 2411 
    [ 5.000,  6.250) = 329 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.606 ms/op
     p(99.9000) =      6.994 ms/op
     p(99.9900) =     13.288 ms/op
     p(99.9990) =     13.978 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  7.346 ms/op
                 getUser·p0.9999: 13.709 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 2.471 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  10.152 ms/op
                 getUser·p0.9999: 12.469 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.060 ms/op
                 getUser·p0.99:   3.531 ms/op
                 getUser·p0.999:  5.550 ms/op
                 getUser·p0.9999: 16.021 ms/op
                 getUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392089
  mean =      2.446 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 198499 
    [ 2.500,  3.750) = 188776 
    [ 3.750,  5.000) = 3785 
    [ 5.000,  6.250) = 477 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      7.798 ms/op
     p(99.9900) =     14.113 ms/op
     p(99.9990) =     16.780 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.442 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.100 ms/op
                 listUser·p1.00:   12.337 ms/op

Iteration   2: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  10.125 ms/op
                 listUser·p0.9999: 11.918 ms/op
                 listUser·p1.00:   12.485 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.986 ms/op
                 listUser·p0.9999: 11.483 ms/op
                 listUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319191
  mean =      3.005 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 167 
    [ 1.250,  2.500) = 94977 
    [ 2.500,  3.750) = 183803 
    [ 3.750,  5.000) = 32865 
    [ 5.000,  6.250) = 6077 
    [ 6.250,  7.500) = 611 
    [ 7.500,  8.750) = 228 
    [ 8.750, 10.000) = 263 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.682 ms/op
     p(99.9990) =     12.312 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.603 ± 1.306  ops/ms
ClientPb.existUser                       thrpt       3  13.247 ± 3.594  ops/ms
ClientPb.getUser                         thrpt       3  12.840 ± 1.213  ops/ms
ClientPb.listUser                        thrpt       3  10.695 ± 0.353  ops/ms
ClientPb.createUser                       avgt       3   2.471 ± 0.358   ms/op
ClientPb.existUser                        avgt       3   2.449 ± 0.132   ms/op
ClientPb.getUser                          avgt       3   2.466 ± 0.412   ms/op
ClientPb.listUser                         avgt       3   2.976 ± 0.411   ms/op
ClientPb.createUser                     sample  384397   2.494 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.401           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.998           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.074           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.105           ms/op
ClientPb.existUser                      sample  394262   2.433 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.742           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.606           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.994           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.288           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.090           ms/op
ClientPb.getUser                        sample  392089   2.446 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.731           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.978           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.798           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.113           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.843           ms/op
ClientPb.listUser                       sample  319191   3.005 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.682           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.485           ms/op
