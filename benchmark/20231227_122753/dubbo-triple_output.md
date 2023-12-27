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
# Warmup Iteration   1: 4.971 ops/ms
# Warmup Iteration   2: 12.074 ops/ms
# Warmup Iteration   3: 12.421 ops/ms
Iteration   1: 12.555 ops/ms
Iteration   2: 12.698 ops/ms
Iteration   3: 12.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.626 ±(99.9%) 1.307 ops/ms [Average]
  (min, avg, max) = (12.555, 12.626, 12.698), stdev = 0.072
  CI (99.9%): [11.319, 13.934] (assumes normal distribution)


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
# Warmup Iteration   1: 8.342 ops/ms
# Warmup Iteration   2: 13.070 ops/ms
# Warmup Iteration   3: 13.154 ops/ms
Iteration   1: 13.121 ops/ms
Iteration   2: 13.241 ops/ms
Iteration   3: 13.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.157 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (13.110, 13.157, 13.241), stdev = 0.072
  CI (99.9%): [11.836, 14.479] (assumes normal distribution)


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
# Warmup Iteration   1: 7.659 ops/ms
# Warmup Iteration   2: 12.649 ops/ms
# Warmup Iteration   3: 12.956 ops/ms
Iteration   1: 12.940 ops/ms
Iteration   2: 12.954 ops/ms
Iteration   3: 13.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.001 ±(99.9%) 1.717 ops/ms [Average]
  (min, avg, max) = (12.940, 13.001, 13.109), stdev = 0.094
  CI (99.9%): [11.284, 14.718] (assumes normal distribution)


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
# Warmup Iteration   1: 6.435 ops/ms
# Warmup Iteration   2: 10.672 ops/ms
# Warmup Iteration   3: 10.703 ops/ms
Iteration   1: 10.707 ops/ms
Iteration   2: 10.726 ops/ms
Iteration   3: 10.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.733 ±(99.9%) 0.548 ops/ms [Average]
  (min, avg, max) = (10.707, 10.733, 10.766), stdev = 0.030
  CI (99.9%): [10.185, 11.281] (assumes normal distribution)


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (2.489, 2.502, 2.521), stdev = 0.017
  CI (99.9%): [2.193, 2.811] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.835 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.004 ms/op
Iteration   1: 2.463 ±(99.9%) 0.003 ms/op
Iteration   2: 2.455 ±(99.9%) 0.003 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.463 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (2.455, 2.463, 2.471), stdev = 0.008
  CI (99.9%): [2.313, 2.614] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.783 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.004 ms/op
Iteration   2: 2.435 ±(99.9%) 0.004 ms/op
Iteration   3: 2.473 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.450 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (2.435, 2.450, 2.473), stdev = 0.020
  CI (99.9%): [2.082, 2.818] (assumes normal distribution)


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
# Warmup Iteration   1: 4.681 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.005 ms/op
Iteration   1: 2.986 ±(99.9%) 0.005 ms/op
Iteration   2: 2.971 ±(99.9%) 0.005 ms/op
Iteration   3: 2.969 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.975 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.969, 2.975, 2.986), stdev = 0.009
  CI (99.9%): [2.807, 3.143] (assumes normal distribution)


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.700 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  10.995 ms/op
                 createUser·p0.9999: 13.586 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.523 ms/op
                 createUser·p0.999:  9.224 ms/op
                 createUser·p0.9999: 11.982 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  9.404 ms/op
                 createUser·p0.9999: 15.728 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382191
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 185483 
    [ 2.500,  3.750) = 193177 
    [ 3.750,  5.000) = 2615 
    [ 5.000,  6.250) = 330 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     13.930 ms/op
     p(99.9990) =     17.173 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.005 ms/op
Iteration   1: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.355 ms/op
                 existUser·p0.999:  6.779 ms/op
                 existUser·p0.9999: 13.525 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.577 ms/op
                 existUser·p0.999:  7.025 ms/op
                 existUser·p0.9999: 12.748 ms/op
                 existUser·p1.00:   13.124 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.139 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  6.592 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391574
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 193109 
    [ 2.500,  3.750) = 195766 
    [ 3.750,  5.000) = 2097 
    [ 5.000,  6.250) = 175 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 138 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.535 ms/op
     p(99.9000) =      6.855 ms/op
     p(99.9900) =     13.263 ms/op
     p(99.9990) =     14.470 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  6.625 ms/op
                 getUser·p0.9999: 13.648 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  9.505 ms/op
                 getUser·p0.9999: 12.632 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  7.672 ms/op
                 getUser·p0.9999: 10.668 ms/op
                 getUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385003
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 191272 
    [ 2.500,  3.750) = 188195 
    [ 3.750,  5.000) = 4289 
    [ 5.000,  6.250) = 692 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.985 ms/op
     p(99.9000) =      7.241 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     14.308 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 4.828 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.009 ms/op
Iteration   1: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.717 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.194 ms/op
                 listUser·p0.9999: 11.528 ms/op
                 listUser·p1.00:   12.567 ms/op

Iteration   2: 2.958 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.390 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.665 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   3: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.803 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.246 ms/op
                 listUser·p0.9999: 12.042 ms/op
                 listUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321564
  mean =      2.983 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 96032 
    [ 2.500,  3.750) = 188187 
    [ 3.750,  5.000) = 30141 
    [ 5.000,  6.250) = 5838 
    [ 6.250,  7.500) = 584 
    [ 7.500,  8.750) = 230 
    [ 8.750, 10.000) = 289 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.578 ms/op
     p(99.9990) =     12.434 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.626 ± 1.307  ops/ms
ClientPb.existUser                       thrpt       3  13.157 ± 1.322  ops/ms
ClientPb.getUser                         thrpt       3  13.001 ± 1.717  ops/ms
ClientPb.listUser                        thrpt       3  10.733 ± 0.548  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.309   ms/op
ClientPb.existUser                        avgt       3   2.463 ± 0.150   ms/op
ClientPb.getUser                          avgt       3   2.450 ± 0.368   ms/op
ClientPb.listUser                         avgt       3   2.975 ± 0.168   ms/op
ClientPb.createUser                     sample  382191   2.509 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.926           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.339           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.930           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.727           ms/op
ClientPb.existUser                      sample  391574   2.449 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.962           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.855           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.263           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.647           ms/op
ClientPb.getUser                        sample  385003   2.491 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.864           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.241           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.960           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.434           ms/op
ClientPb.listUser                       sample  321564   2.983 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.717           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.578           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.567           ms/op
