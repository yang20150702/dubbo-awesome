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
# Warmup Iteration   1: 4.649 ops/ms
# Warmup Iteration   2: 11.904 ops/ms
# Warmup Iteration   3: 12.169 ops/ms
Iteration   1: 12.365 ops/ms
Iteration   2: 12.585 ops/ms
Iteration   3: 12.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.547 ±(99.9%) 3.047 ops/ms [Average]
  (min, avg, max) = (12.365, 12.547, 12.692), stdev = 0.167
  CI (99.9%): [9.501, 15.594] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.160 ops/ms
# Warmup Iteration   2: 12.915 ops/ms
# Warmup Iteration   3: 12.799 ops/ms
Iteration   1: 12.723 ops/ms
Iteration   2: 12.790 ops/ms
Iteration   3: 12.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.715 ±(99.9%) 1.438 ops/ms [Average]
  (min, avg, max) = (12.633, 12.715, 12.790), stdev = 0.079
  CI (99.9%): [11.277, 14.154] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.441 ops/ms
# Warmup Iteration   2: 12.800 ops/ms
# Warmup Iteration   3: 12.524 ops/ms
Iteration   1: 12.752 ops/ms
Iteration   2: 13.113 ops/ms
Iteration   3: 12.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.937 ±(99.9%) 3.293 ops/ms [Average]
  (min, avg, max) = (12.752, 12.937, 13.113), stdev = 0.181
  CI (99.9%): [9.644, 16.230] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.549 ops/ms
# Warmup Iteration   2: 10.269 ops/ms
# Warmup Iteration   3: 10.413 ops/ms
Iteration   1: 10.418 ops/ms
Iteration   2: 10.342 ops/ms
Iteration   3: 10.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.395 ±(99.9%) 0.840 ops/ms [Average]
  (min, avg, max) = (10.342, 10.395, 10.424), stdev = 0.046
  CI (99.9%): [9.554, 11.235] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.027 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
Iteration   1: 2.574 ±(99.9%) 0.005 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.550 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.560 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.550, 2.560, 2.574), stdev = 0.013
  CI (99.9%): [2.332, 2.788] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
Iteration   1: 2.525 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
Iteration   3: 2.548 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.524 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (2.501, 2.524, 2.548), stdev = 0.024
  CI (99.9%): [2.095, 2.953] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.003 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.517 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.514, 2.521, 2.530), stdev = 0.009
  CI (99.9%): [2.363, 2.679] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.730 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.005 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
Iteration   3: 3.051 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.039 ±(99.9%) 0.443 ms/op [Average]
  (min, avg, max) = (3.011, 3.039, 3.055), stdev = 0.024
  CI (99.9%): [2.596, 3.482] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.370 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.594 ±(99.9%) 0.006 ms/op
Iteration   1: 2.535 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  12.286 ms/op
                 createUser·p0.9999: 13.988 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.539 ms/op
                 createUser·p0.999:  8.932 ms/op
                 createUser·p0.9999: 12.930 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.920 ms/op
                 createUser·p0.999:  8.117 ms/op
                 createUser·p0.9999: 11.708 ms/op
                 createUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378602
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 181880 
    [ 2.500,  3.750) = 192736 
    [ 3.750,  5.000) = 3158 
    [ 5.000,  6.250) = 355 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     13.802 ms/op
     p(99.9990) =     14.734 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.707 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.801 ms/op
                 existUser·p0.999:  5.894 ms/op
                 existUser·p0.9999: 13.308 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.020 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  8.484 ms/op
                 existUser·p0.9999: 14.189 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  8.036 ms/op
                 existUser·p0.9999: 12.045 ms/op
                 existUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384262
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 188208 
    [ 2.500,  3.750) = 191765 
    [ 3.750,  5.000) = 3197 
    [ 5.000,  6.250) = 603 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      7.049 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     14.388 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.788 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  11.401 ms/op
                 getUser·p0.9999: 14.336 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.537 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  9.680 ms/op
                 getUser·p0.9999: 12.642 ms/op
                 getUser·p1.00:   13.484 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.130 ms/op
                 getUser·p0.99:   4.039 ms/op
                 getUser·p0.999:  7.209 ms/op
                 getUser·p0.9999: 12.306 ms/op
                 getUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382584
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 188327 
    [ 2.500,  3.750) = 186667 
    [ 3.750,  5.000) = 5447 
    [ 5.000,  6.250) = 1403 
    [ 6.250,  7.500) = 258 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     13.476 ms/op
     p(99.9990) =     15.142 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.670 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.009 ms/op
Iteration   1: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.837 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 11.618 ms/op
                 listUser·p1.00:   12.829 ms/op

Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.956 ms/op
                 listUser·p0.9999: 10.799 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.766 ms/op
                 listUser·p0.9999: 10.754 ms/op
                 listUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316859
  mean =      3.027 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 92228 
    [ 2.500,  3.750) = 183463 
    [ 3.750,  5.000) = 32796 
    [ 5.000,  6.250) = 6746 
    [ 6.250,  7.500) = 808 
    [ 7.500,  8.750) = 208 
    [ 8.750, 10.000) = 262 
    [10.000, 11.250) = 184 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.489 ms/op
     p(99.9900) =     11.010 ms/op
     p(99.9990) =     12.438 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.547 ± 3.047  ops/ms
ClientPb.existUser                       thrpt       3  12.715 ± 1.438  ops/ms
ClientPb.getUser                         thrpt       3  12.937 ± 3.293  ops/ms
ClientPb.listUser                        thrpt       3  10.395 ± 0.840  ops/ms
ClientPb.createUser                       avgt       3   2.560 ± 0.228   ms/op
ClientPb.existUser                        avgt       3   2.524 ± 0.429   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.158   ms/op
ClientPb.listUser                         avgt       3   3.039 ± 0.443   ms/op
ClientPb.createUser                     sample  378602   2.533 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.904           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.503           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.802           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.826           ms/op
ClientPb.existUser                      sample  384262   2.496 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.777           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.049           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.451           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.451           ms/op
ClientPb.getUser                        sample  382584   2.507 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.895           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.470           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.476           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.155           ms/op
ClientPb.listUser                       sample  316859   3.027 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.874           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.489           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.010           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.829           ms/op
