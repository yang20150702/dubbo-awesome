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
# Warmup Iteration   1: 4.513 ops/ms
# Warmup Iteration   2: 12.363 ops/ms
# Warmup Iteration   3: 12.490 ops/ms
Iteration   1: 12.600 ops/ms
Iteration   2: 12.615 ops/ms
Iteration   3: 12.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.648 ±(99.9%) 1.261 ops/ms [Average]
  (min, avg, max) = (12.600, 12.648, 12.727), stdev = 0.069
  CI (99.9%): [11.386, 13.909] (assumes normal distribution)


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
# Warmup Iteration   1: 7.985 ops/ms
# Warmup Iteration   2: 12.925 ops/ms
# Warmup Iteration   3: 13.147 ops/ms
Iteration   1: 13.067 ops/ms
Iteration   2: 12.951 ops/ms
Iteration   3: 12.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.983 ±(99.9%) 1.325 ops/ms [Average]
  (min, avg, max) = (12.932, 12.983, 13.067), stdev = 0.073
  CI (99.9%): [11.658, 14.309] (assumes normal distribution)


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
# Warmup Iteration   1: 7.603 ops/ms
# Warmup Iteration   2: 12.556 ops/ms
# Warmup Iteration   3: 12.638 ops/ms
Iteration   1: 12.656 ops/ms
Iteration   2: 12.754 ops/ms
Iteration   3: 12.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.714 ±(99.9%) 0.936 ops/ms [Average]
  (min, avg, max) = (12.656, 12.714, 12.754), stdev = 0.051
  CI (99.9%): [11.778, 13.650] (assumes normal distribution)


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
# Warmup Iteration   1: 6.428 ops/ms
# Warmup Iteration   2: 10.450 ops/ms
# Warmup Iteration   3: 10.519 ops/ms
Iteration   1: 10.536 ops/ms
Iteration   2: 10.456 ops/ms
Iteration   3: 10.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.515 ±(99.9%) 0.947 ops/ms [Average]
  (min, avg, max) = (10.456, 10.515, 10.553), stdev = 0.052
  CI (99.9%): [9.568, 11.462] (assumes normal distribution)


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
Iteration   1: 2.542 ±(99.9%) 0.004 ms/op
Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
Iteration   3: 2.525 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.539 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.525, 2.539, 2.548), stdev = 0.012
  CI (99.9%): [2.319, 2.758] (assumes normal distribution)


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.003 ms/op
Iteration   1: 2.413 ±(99.9%) 0.004 ms/op
Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.428 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (2.413, 2.428, 2.436), stdev = 0.013
  CI (99.9%): [2.190, 2.666] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.470 ±(99.9%) 0.111 ms/op [Average]
  (min, avg, max) = (2.463, 2.470, 2.475), stdev = 0.006
  CI (99.9%): [2.359, 2.582] (assumes normal distribution)


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
# Warmup Iteration   1: 5.002 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
Iteration   3: 3.007 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.024 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.007, 3.024, 3.037), stdev = 0.015
  CI (99.9%): [2.750, 3.297] (assumes normal distribution)


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.701 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.006 ms/op
Iteration   1: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  11.753 ms/op
                 createUser·p0.9999: 13.550 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  10.240 ms/op
                 createUser·p0.9999: 11.969 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  8.864 ms/op
                 createUser·p0.9999: 10.427 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376595
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 181161 
    [ 2.500,  3.750) = 191635 
    [ 3.750,  5.000) = 2949 
    [ 5.000,  6.250) = 367 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      8.952 ms/op
     p(99.9900) =     13.014 ms/op
     p(99.9990) =     13.828 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.421 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.800 ms/op
                 existUser·p0.999:  6.356 ms/op
                 existUser·p0.9999: 13.861 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  7.315 ms/op
                 existUser·p0.9999: 12.678 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  5.191 ms/op
                 existUser·p0.9999: 12.597 ms/op
                 existUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394501
  mean =      2.431 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 199880 
    [ 2.500,  3.750) = 191307 
    [ 3.750,  5.000) = 2536 
    [ 5.000,  6.250) = 315 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      6.328 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     14.158 ms/op
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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  9.349 ms/op
                 getUser·p0.9999: 14.164 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  6.717 ms/op
                 getUser·p0.9999: 12.438 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  6.037 ms/op
                 getUser·p0.9999: 12.930 ms/op
                 getUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385617
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 193070 
    [ 2.500,  3.750) = 188937 
    [ 3.750,  5.000) = 2856 
    [ 5.000,  6.250) = 332 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      6.054 ms/op
     p(99.9900) =     13.458 ms/op
     p(99.9990) =     14.453 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.127 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.009 ms/op
Iteration   1: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.423 ms/op
                 listUser·p0.9999: 10.519 ms/op
                 listUser·p1.00:   10.764 ms/op

Iteration   2: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.753 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  8.881 ms/op
                 listUser·p0.9999: 14.290 ms/op
                 listUser·p1.00:   15.417 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.965 ms/op
                 listUser·p0.9999: 11.207 ms/op
                 listUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317771
  mean =      3.018 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 91317 
    [ 2.500,  3.750) = 185699 
    [ 3.750,  5.000) = 33467 
    [ 5.000,  6.250) = 5746 
    [ 6.250,  7.500) = 721 
    [ 7.500,  8.750) = 278 
    [ 8.750, 10.000) = 212 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     13.340 ms/op
     p(99.9990) =     15.126 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.648 ± 1.261  ops/ms
ClientPb.existUser                       thrpt       3  12.983 ± 1.325  ops/ms
ClientPb.getUser                         thrpt       3  12.714 ± 0.936  ops/ms
ClientPb.listUser                        thrpt       3  10.515 ± 0.947  ops/ms
ClientPb.createUser                       avgt       3   2.539 ± 0.219   ms/op
ClientPb.existUser                        avgt       3   2.428 ± 0.238   ms/op
ClientPb.getUser                          avgt       3   2.470 ± 0.111   ms/op
ClientPb.listUser                         avgt       3   3.024 ± 0.274   ms/op
ClientPb.createUser                     sample  376595   2.546 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.868           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.952           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.014           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.760           ms/op
ClientPb.existUser                      sample  394501   2.431 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.797           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.328           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.451           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.516           ms/op
ClientPb.getUser                        sample  385617   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.954           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.054           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.458           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.778           ms/op
ClientPb.listUser                       sample  317771   3.018 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.208           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.340           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.417           ms/op
