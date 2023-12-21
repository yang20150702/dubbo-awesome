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
# Warmup Iteration   1: 5.110 ops/ms
# Warmup Iteration   2: 12.059 ops/ms
# Warmup Iteration   3: 12.221 ops/ms
Iteration   1: 12.494 ops/ms
Iteration   2: 12.624 ops/ms
Iteration   3: 12.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.589 ±(99.9%) 1.510 ops/ms [Average]
  (min, avg, max) = (12.494, 12.589, 12.648), stdev = 0.083
  CI (99.9%): [11.079, 14.099] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.530 ops/ms
# Warmup Iteration   2: 13.643 ops/ms
# Warmup Iteration   3: 13.602 ops/ms
Iteration   1: 13.654 ops/ms
Iteration   2: 13.438 ops/ms
Iteration   3: 13.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.451 ±(99.9%) 3.592 ops/ms [Average]
  (min, avg, max) = (13.261, 13.451, 13.654), stdev = 0.197
  CI (99.9%): [9.859, 17.044] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.197 ops/ms
# Warmup Iteration   2: 12.730 ops/ms
# Warmup Iteration   3: 12.957 ops/ms
Iteration   1: 13.115 ops/ms
Iteration   2: 13.191 ops/ms
Iteration   3: 13.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.149 ±(99.9%) 0.699 ops/ms [Average]
  (min, avg, max) = (13.115, 13.149, 13.191), stdev = 0.038
  CI (99.9%): [12.450, 13.849] (assumes normal distribution)


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
# Warmup Iteration   1: 6.983 ops/ms
# Warmup Iteration   2: 10.718 ops/ms
# Warmup Iteration   3: 10.796 ops/ms
Iteration   1: 10.825 ops/ms
Iteration   2: 10.964 ops/ms
Iteration   3: 10.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.889 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (10.825, 10.889, 10.964), stdev = 0.070
  CI (99.9%): [9.609, 12.170] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.552 ±(99.9%) 0.004 ms/op
Iteration   2: 2.647 ±(99.9%) 0.004 ms/op
Iteration   3: 2.568 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.589 ±(99.9%) 0.926 ms/op [Average]
  (min, avg, max) = (2.552, 2.589, 2.647), stdev = 0.051
  CI (99.9%): [1.663, 3.515] (assumes normal distribution)


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
# Warmup Iteration   1: 3.754 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.437 ±(99.9%) 0.004 ms/op
Iteration   3: 2.410 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.448 ±(99.9%) 0.810 ms/op [Average]
  (min, avg, max) = (2.410, 2.448, 2.497), stdev = 0.044
  CI (99.9%): [1.638, 3.259] (assumes normal distribution)


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.007 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.547 ±(99.9%) 0.004 ms/op
Iteration   3: 2.564 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.537 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (2.501, 2.537, 2.564), stdev = 0.033
  CI (99.9%): [1.944, 3.130] (assumes normal distribution)


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
# Warmup Iteration   1: 4.775 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.007 ms/op
Iteration   1: 2.957 ±(99.9%) 0.008 ms/op
Iteration   2: 2.965 ±(99.9%) 0.007 ms/op
Iteration   3: 2.967 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.963 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.957, 2.963, 2.967), stdev = 0.005
  CI (99.9%): [2.868, 3.059] (assumes normal distribution)


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.471 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   2.433 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.937 ms/op
                 createUser·p0.999:  9.464 ms/op
                 createUser·p0.9999: 15.370 ms/op
                 createUser·p1.00:   15.860 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   2.445 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.002 ms/op
                 createUser·p0.999:  9.404 ms/op
                 createUser·p0.9999: 12.797 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   2.441 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.973 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 11.945 ms/op
                 createUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387749
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 205611 
    [ 2.500,  3.750) = 176471 
    [ 3.750,  5.000) = 4275 
    [ 5.000,  6.250) = 637 
    [ 6.250,  7.500) = 138 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.441 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     13.488 ms/op
     p(99.9990) =     15.751 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  5.825 ms/op
                 existUser·p0.9999: 14.146 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.714 ms/op
                 existUser·p0.999:  9.686 ms/op
                 existUser·p0.9999: 15.074 ms/op
                 existUser·p1.00:   16.744 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.392 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 12.124 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387158
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 201373 
    [ 2.500,  3.750) = 181892 
    [ 3.750,  5.000) = 2868 
    [ 5.000,  6.250) = 460 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      7.549 ms/op
     p(99.9900) =     14.357 ms/op
     p(99.9990) =     15.530 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.169 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  5.753 ms/op
                 getUser·p0.9999: 14.387 ms/op
                 getUser·p1.00:   16.286 ms/op

Iteration   2: 2.502 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  9.716 ms/op
                 getUser·p0.9999: 13.777 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.860 ms/op
                 getUser·p0.999:  8.738 ms/op
                 getUser·p0.9999: 13.566 ms/op
                 getUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383150
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 195189 
    [ 2.500,  3.750) = 182488 
    [ 3.750,  5.000) = 4384 
    [ 5.000,  6.250) = 558 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      6.969 ms/op
     p(99.9900) =     13.839 ms/op
     p(99.9990) =     14.656 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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
# Warmup Iteration   1: 4.945 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.009 ms/op
Iteration   1: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 11.090 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.333 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 12.425 ms/op
                 listUser·p1.00:   12.698 ms/op

Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 16.652 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318298
  mean =      3.012 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 90953 
    [ 2.500,  3.750) = 188289 
    [ 3.750,  5.000) = 31903 
    [ 5.000,  6.250) = 5712 
    [ 6.250,  7.500) = 650 
    [ 7.500,  8.750) = 222 
    [ 8.750, 10.000) = 264 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     12.340 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.589 ± 1.510  ops/ms
ClientPb.existUser                       thrpt       3  13.451 ± 3.592  ops/ms
ClientPb.getUser                         thrpt       3  13.149 ± 0.699  ops/ms
ClientPb.listUser                        thrpt       3  10.889 ± 1.281  ops/ms
ClientPb.createUser                       avgt       3   2.589 ± 0.926   ms/op
ClientPb.existUser                        avgt       3   2.448 ± 0.810   ms/op
ClientPb.getUser                          avgt       3   2.537 ± 0.593   ms/op
ClientPb.listUser                         avgt       3   2.963 ± 0.096   ms/op
ClientPb.createUser                     sample  387749   2.474 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.675           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.441           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.995           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.488           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.860           ms/op
ClientPb.existUser                      sample  387158   2.477 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.787           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.433           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.549           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.357           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.744           ms/op
ClientPb.getUser                        sample  383150   2.503 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.916           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.969           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.839           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.286           ms/op
ClientPb.listUser                       sample  318298   3.012 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.954           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.340           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.874           ms/op
