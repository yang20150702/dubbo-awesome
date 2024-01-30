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
# Warmup Iteration   1: 4.581 ops/ms
# Warmup Iteration   2: 12.025 ops/ms
# Warmup Iteration   3: 12.245 ops/ms
Iteration   1: 12.370 ops/ms
Iteration   2: 12.425 ops/ms
Iteration   3: 12.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.438 ±(99.9%) 1.368 ops/ms [Average]
  (min, avg, max) = (12.370, 12.438, 12.519), stdev = 0.075
  CI (99.9%): [11.070, 13.806] (assumes normal distribution)


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
# Warmup Iteration   1: 8.570 ops/ms
# Warmup Iteration   2: 13.239 ops/ms
# Warmup Iteration   3: 13.109 ops/ms
Iteration   1: 13.034 ops/ms
Iteration   2: 13.132 ops/ms
Iteration   3: 13.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.089 ±(99.9%) 0.912 ops/ms [Average]
  (min, avg, max) = (13.034, 13.089, 13.132), stdev = 0.050
  CI (99.9%): [12.177, 14.002] (assumes normal distribution)


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
# Warmup Iteration   2: 12.746 ops/ms
# Warmup Iteration   3: 13.072 ops/ms
Iteration   1: 13.040 ops/ms
Iteration   2: 12.911 ops/ms
Iteration   3: 12.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.948 ±(99.9%) 1.466 ops/ms [Average]
  (min, avg, max) = (12.892, 12.948, 13.040), stdev = 0.080
  CI (99.9%): [11.482, 14.414] (assumes normal distribution)


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
# Warmup Iteration   1: 6.825 ops/ms
# Warmup Iteration   2: 10.547 ops/ms
# Warmup Iteration   3: 10.765 ops/ms
Iteration   1: 10.818 ops/ms
Iteration   2: 10.788 ops/ms
Iteration   3: 10.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.813 ±(99.9%) 0.402 ops/ms [Average]
  (min, avg, max) = (10.788, 10.813, 10.831), stdev = 0.022
  CI (99.9%): [10.411, 11.214] (assumes normal distribution)


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
# Warmup Iteration   1: 3.853 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
Iteration   3: 2.480 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.496 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (2.479, 2.496, 2.530), stdev = 0.029
  CI (99.9%): [1.961, 3.032] (assumes normal distribution)


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
# Warmup Iteration   1: 3.629 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.491 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.482 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.470, 2.482, 2.491), stdev = 0.011
  CI (99.9%): [2.283, 2.682] (assumes normal distribution)


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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.003 ms/op
Iteration   1: 2.536 ±(99.9%) 0.005 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.525 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (2.508, 2.525, 2.536), stdev = 0.015
  CI (99.9%): [2.256, 2.793] (assumes normal distribution)


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
Iteration   1: 3.052 ±(99.9%) 0.005 ms/op
Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
Iteration   3: 3.013 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.037 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (3.013, 3.037, 3.052), stdev = 0.021
  CI (99.9%): [2.651, 3.424] (assumes normal distribution)


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.712 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.592 ms/op
                 createUser·p0.999:  12.022 ms/op
                 createUser·p0.9999: 17.222 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  8.526 ms/op
                 createUser·p0.9999: 11.955 ms/op
                 createUser·p1.00:   12.288 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  8.090 ms/op
                 createUser·p0.9999: 11.682 ms/op
                 createUser·p1.00:   15.761 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380599
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 183381 
    [ 2.500,  3.750) = 193766 
    [ 3.750,  5.000) = 2730 
    [ 5.000,  6.250) = 254 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      8.321 ms/op
     p(99.9900) =     14.344 ms/op
     p(99.9990) =     18.035 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 3.679 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.416 ms/op
                 existUser·p0.999:  7.795 ms/op
                 existUser·p0.9999: 13.222 ms/op
                 existUser·p1.00:   13.664 ms/op

Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  7.767 ms/op
                 existUser·p0.9999: 12.618 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  7.651 ms/op
                 existUser·p0.9999: 12.190 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391380
  mean =      2.450 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 193514 
    [ 2.500,  3.750) = 195131 
    [ 3.750,  5.000) = 1862 
    [ 5.000,  6.250) = 367 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.478 ms/op
     p(99.9000) =      7.680 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     13.570 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  5.972 ms/op
                 getUser·p0.9999: 13.537 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  9.288 ms/op
                 getUser·p0.9999: 12.976 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 11.491 ms/op
                 getUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380190
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 186929 
    [ 2.500,  3.750) = 189060 
    [ 3.750,  5.000) = 3282 
    [ 5.000,  6.250) = 470 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      6.455 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     13.946 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 4.629 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
Iteration   1: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.715 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 13.964 ms/op
                 listUser·p1.00:   14.664 ms/op

Iteration   2: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 12.567 ms/op
                 listUser·p1.00:   13.156 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 11.361 ms/op
                 listUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315214
  mean =      3.042 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 86531 
    [ 2.500,  3.750) = 187241 
    [ 3.750,  5.000) = 34177 
    [ 5.000,  6.250) = 5736 
    [ 6.250,  7.500) = 666 
    [ 7.500,  8.750) = 240 
    [ 8.750, 10.000) = 283 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.602 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     12.688 ms/op
     p(99.9990) =     14.466 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.438 ± 1.368  ops/ms
ClientPb.existUser                       thrpt       3  13.089 ± 0.912  ops/ms
ClientPb.getUser                         thrpt       3  12.948 ± 1.466  ops/ms
ClientPb.listUser                        thrpt       3  10.813 ± 0.402  ops/ms
ClientPb.createUser                       avgt       3   2.496 ± 0.535   ms/op
ClientPb.existUser                        avgt       3   2.482 ± 0.199   ms/op
ClientPb.getUser                          avgt       3   2.525 ± 0.268   ms/op
ClientPb.listUser                         avgt       3   3.037 ± 0.386   ms/op
ClientPb.createUser                     sample  380599   2.519 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.824           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.321           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.344           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.186           ms/op
ClientPb.existUser                      sample  391380   2.450 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.043           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.680           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.878           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.664           ms/op
ClientPb.getUser                        sample  380190   2.523 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.900           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.455           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.206           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  315214   3.042 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.715           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.602           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.688           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.664           ms/op
