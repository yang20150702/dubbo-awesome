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
# Warmup Iteration   1: 5.296 ops/ms
# Warmup Iteration   2: 12.150 ops/ms
# Warmup Iteration   3: 12.691 ops/ms
Iteration   1: 12.741 ops/ms
Iteration   2: 12.886 ops/ms
Iteration   3: 12.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.846 ±(99.9%) 1.660 ops/ms [Average]
  (min, avg, max) = (12.741, 12.846, 12.910), stdev = 0.091
  CI (99.9%): [11.185, 14.506] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.238 ops/ms
# Warmup Iteration   2: 13.188 ops/ms
# Warmup Iteration   3: 13.195 ops/ms
Iteration   1: 12.983 ops/ms
Iteration   2: 13.242 ops/ms
Iteration   3: 13.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.151 ±(99.9%) 2.662 ops/ms [Average]
  (min, avg, max) = (12.983, 13.151, 13.242), stdev = 0.146
  CI (99.9%): [10.489, 15.813] (assumes normal distribution)


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
# Warmup Iteration   1: 8.049 ops/ms
# Warmup Iteration   2: 12.854 ops/ms
# Warmup Iteration   3: 12.913 ops/ms
Iteration   1: 13.089 ops/ms
Iteration   2: 12.836 ops/ms
Iteration   3: 12.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.944 ±(99.9%) 2.378 ops/ms [Average]
  (min, avg, max) = (12.836, 12.944, 13.089), stdev = 0.130
  CI (99.9%): [10.566, 15.321] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.414 ops/ms
# Warmup Iteration   2: 10.629 ops/ms
# Warmup Iteration   3: 10.751 ops/ms
Iteration   1: 10.717 ops/ms
Iteration   2: 10.840 ops/ms
Iteration   3: 10.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.793 ±(99.9%) 1.214 ops/ms [Average]
  (min, avg, max) = (10.717, 10.793, 10.840), stdev = 0.067
  CI (99.9%): [9.579, 12.007] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.027 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.004 ms/op
Iteration   1: 2.519 ±(99.9%) 0.003 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.496 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (2.474, 2.496, 2.519), stdev = 0.022
  CI (99.9%): [2.086, 2.906] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.689 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.004 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.464 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (2.458, 2.464, 2.472), stdev = 0.007
  CI (99.9%): [2.337, 2.592] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.919 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.488 ±(99.9%) 0.059 ms/op [Average]
  (min, avg, max) = (2.485, 2.488, 2.490), stdev = 0.003
  CI (99.9%): [2.429, 2.548] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.793 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.005 ms/op
Iteration   1: 3.004 ±(99.9%) 0.004 ms/op
Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
Iteration   3: 2.972 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.988 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (2.972, 2.988, 3.004), stdev = 0.016
  CI (99.9%): [2.700, 3.276] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  10.051 ms/op
                 createUser·p0.9999: 13.080 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   3.471 ms/op
                 createUser·p0.999:  7.433 ms/op
                 createUser·p0.9999: 11.796 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 11.553 ms/op
                 createUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386910
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 188212 
    [ 2.500,  3.750) = 195336 
    [ 3.750,  5.000) = 2460 
    [ 5.000,  6.250) = 344 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 129 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     12.812 ms/op
     p(99.9990) =     13.889 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 3.509 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.417 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  6.188 ms/op
                 existUser·p0.9999: 13.564 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  7.291 ms/op
                 existUser·p0.9999: 12.577 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  8.436 ms/op
                 existUser·p0.9999: 12.009 ms/op
                 existUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393960
  mean =      2.434 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 196621 
    [ 2.500,  3.750) = 194598 
    [ 3.750,  5.000) = 1994 
    [ 5.000,  6.250) = 205 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.518 ms/op
     p(99.9000) =      7.865 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     13.633 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  8.181 ms/op
                 getUser·p0.9999: 14.043 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  6.522 ms/op
                 getUser·p0.9999: 12.550 ms/op
                 getUser·p1.00:   12.747 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  5.456 ms/op
                 getUser·p0.9999: 11.551 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387530
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 194742 
    [ 2.500,  3.750) = 189176 
    [ 3.750,  5.000) = 2827 
    [ 5.000,  6.250) = 380 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 134 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      5.951 ms/op
     p(99.9900) =     13.132 ms/op
     p(99.9990) =     14.307 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.086 ms/op
                 listUser·p0.9999: 10.322 ms/op
                 listUser·p1.00:   11.289 ms/op

Iteration   2: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 11.305 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.745 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.089 ms/op
                 listUser·p0.9999: 10.830 ms/op
                 listUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321988
  mean =      2.978 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 98954 
    [ 2.500,  3.750) = 185335 
    [ 3.750,  5.000) = 30715 
    [ 5.000,  6.250) = 5659 
    [ 6.250,  7.500) = 553 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 320 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     11.138 ms/op
     p(99.9990) =     11.744 ms/op
     p(99.9999) =     12.812 ms/op
    p(100.0000) =     12.812 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.846 ± 1.660  ops/ms
ClientPb.existUser                       thrpt       3  13.151 ± 2.662  ops/ms
ClientPb.getUser                         thrpt       3  12.944 ± 2.378  ops/ms
ClientPb.listUser                        thrpt       3  10.793 ± 1.214  ops/ms
ClientPb.createUser                       avgt       3   2.496 ± 0.410   ms/op
ClientPb.existUser                        avgt       3   2.464 ± 0.127   ms/op
ClientPb.getUser                          avgt       3   2.488 ± 0.059   ms/op
ClientPb.listUser                         avgt       3   2.988 ± 0.288   ms/op
ClientPb.createUser                     sample  386910   2.479 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.826           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.241           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.812           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.238           ms/op
ClientPb.existUser                      sample  393960   2.434 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.936           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.865           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.713           ms/op
ClientPb.getUser                        sample  387530   2.475 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.931           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.951           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.132           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.582           ms/op
ClientPb.listUser                       sample  321988   2.978 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.208           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.138           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.812           ms/op
