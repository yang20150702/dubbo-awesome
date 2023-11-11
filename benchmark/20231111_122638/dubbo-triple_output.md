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
# Warmup Iteration   1: 4.613 ops/ms
# Warmup Iteration   2: 11.815 ops/ms
# Warmup Iteration   3: 11.948 ops/ms
Iteration   1: 12.216 ops/ms
Iteration   2: 12.363 ops/ms
Iteration   3: 12.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.313 ±(99.9%) 1.545 ops/ms [Average]
  (min, avg, max) = (12.216, 12.313, 12.363), stdev = 0.085
  CI (99.9%): [10.768, 13.858] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.881 ops/ms
# Warmup Iteration   2: 12.625 ops/ms
# Warmup Iteration   3: 12.846 ops/ms
Iteration   1: 12.700 ops/ms
Iteration   2: 12.828 ops/ms
Iteration   3: 12.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.813 ±(99.9%) 1.945 ops/ms [Average]
  (min, avg, max) = (12.700, 12.813, 12.912), stdev = 0.107
  CI (99.9%): [10.868, 14.758] (assumes normal distribution)


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
# Warmup Iteration   1: 7.140 ops/ms
# Warmup Iteration   2: 12.303 ops/ms
# Warmup Iteration   3: 12.442 ops/ms
Iteration   1: 12.576 ops/ms
Iteration   2: 12.640 ops/ms
Iteration   3: 12.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.541 ±(99.9%) 2.206 ops/ms [Average]
  (min, avg, max) = (12.406, 12.541, 12.640), stdev = 0.121
  CI (99.9%): [10.334, 14.747] (assumes normal distribution)


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
# Warmup Iteration   1: 6.735 ops/ms
# Warmup Iteration   2: 10.290 ops/ms
# Warmup Iteration   3: 10.446 ops/ms
Iteration   1: 10.267 ops/ms
Iteration   2: 10.519 ops/ms
Iteration   3: 10.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.403 ±(99.9%) 2.315 ops/ms [Average]
  (min, avg, max) = (10.267, 10.403, 10.519), stdev = 0.127
  CI (99.9%): [8.088, 12.717] (assumes normal distribution)


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
# Warmup Iteration   1: 4.432 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.662 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.003 ms/op
Iteration   1: 2.596 ±(99.9%) 0.004 ms/op
Iteration   2: 2.573 ±(99.9%) 0.003 ms/op
Iteration   3: 2.552 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.574 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (2.552, 2.574, 2.596), stdev = 0.022
  CI (99.9%): [2.165, 2.982] (assumes normal distribution)


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.003 ms/op
Iteration   1: 2.443 ±(99.9%) 0.003 ms/op
Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
Iteration   3: 2.443 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.449 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (2.443, 2.449, 2.462), stdev = 0.011
  CI (99.9%): [2.245, 2.653] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.461 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.493 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.480 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (2.461, 2.480, 2.493), stdev = 0.016
  CI (99.9%): [2.181, 2.779] (assumes normal distribution)


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
# Warmup Iteration   1: 4.743 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
Iteration   1: 3.076 ±(99.9%) 0.004 ms/op
Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
Iteration   3: 3.030 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.089 ±(99.9%) 1.212 ms/op [Average]
  (min, avg, max) = (3.030, 3.089, 3.161), stdev = 0.066
  CI (99.9%): [1.877, 4.300] (assumes normal distribution)


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 2.708 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.585 ±(99.9%) 0.006 ms/op
Iteration   1: 2.540 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  12.225 ms/op
                 createUser·p0.9999: 14.081 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  10.175 ms/op
                 createUser·p0.9999: 14.803 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   3: 2.573 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   4.147 ms/op
                 createUser·p0.999:  9.126 ms/op
                 createUser·p0.9999: 12.110 ms/op
                 createUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375176
  mean =      2.557 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 177944 
    [ 2.500,  3.750) = 191597 
    [ 3.750,  5.000) = 4180 
    [ 5.000,  6.250) = 787 
    [ 6.250,  7.500) = 141 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 126 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     14.025 ms/op
     p(99.9990) =     15.102 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 3.846 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  6.193 ms/op
                 existUser·p0.9999: 16.941 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.371 ms/op
                 existUser·p0.999:  6.636 ms/op
                 existUser·p0.9999: 15.546 ms/op
                 existUser·p1.00:   16.597 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  8.389 ms/op
                 existUser·p0.9999: 11.322 ms/op
                 existUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390872
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 192047 
    [ 2.500,  3.750) = 195510 
    [ 3.750,  5.000) = 2320 
    [ 5.000,  6.250) = 532 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      6.514 ms/op
     p(99.9900) =     15.547 ms/op
     p(99.9990) =     17.209 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  12.075 ms/op
                 getUser·p0.9999: 15.791 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   2: 2.565 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.560 ms/op
                 getUser·p0.999:  7.971 ms/op
                 getUser·p0.9999: 12.215 ms/op
                 getUser·p1.00:   12.632 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  8.259 ms/op
                 getUser·p0.9999: 11.682 ms/op
                 getUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377329
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 184118 
    [ 2.500,  3.750) = 187838 
    [ 3.750,  5.000) = 4114 
    [ 5.000,  6.250) = 669 
    [ 6.250,  7.500) = 166 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =      7.979 ms/op
     p(99.9900) =     14.336 ms/op
     p(99.9990) =     16.428 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 4.698 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.009 ms/op
Iteration   1: 3.067 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 12.489 ms/op
                 listUser·p1.00:   13.369 ms/op

Iteration   2: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 11.449 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   3: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 10.813 ms/op
                 listUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312266
  mean =      3.071 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 81929 
    [ 2.500,  3.750) = 187418 
    [ 3.750,  5.000) = 34550 
    [ 5.000,  6.250) = 6719 
    [ 6.250,  7.500) = 860 
    [ 7.500,  8.750) = 228 
    [ 8.750, 10.000) = 258 
    [10.000, 11.250) = 155 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.515 ms/op
     p(99.9900) =     11.600 ms/op
     p(99.9990) =     13.059 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.313 ± 1.545  ops/ms
ClientPb.existUser                       thrpt       3  12.813 ± 1.945  ops/ms
ClientPb.getUser                         thrpt       3  12.541 ± 2.206  ops/ms
ClientPb.listUser                        thrpt       3  10.403 ± 2.315  ops/ms
ClientPb.createUser                       avgt       3   2.574 ± 0.409   ms/op
ClientPb.existUser                        avgt       3   2.449 ± 0.204   ms/op
ClientPb.getUser                          avgt       3   2.480 ± 0.299   ms/op
ClientPb.listUser                         avgt       3   3.089 ± 1.212   ms/op
ClientPb.createUser                     sample  375176   2.557 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.730           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.159           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.025           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.237           ms/op
ClientPb.existUser                      sample  390872   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.703           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.514           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.547           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.302           ms/op
ClientPb.getUser                        sample  377329   2.542 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.979           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.336           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.007           ms/op
ClientPb.listUser                       sample  312266   3.071 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.841           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.515           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.369           ms/op
