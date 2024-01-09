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
# Warmup Iteration   1: 4.386 ops/ms
# Warmup Iteration   2: 11.483 ops/ms
# Warmup Iteration   3: 11.980 ops/ms
Iteration   1: 12.213 ops/ms
Iteration   2: 12.312 ops/ms
Iteration   3: 12.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.265 ±(99.9%) 0.907 ops/ms [Average]
  (min, avg, max) = (12.213, 12.265, 12.312), stdev = 0.050
  CI (99.9%): [11.357, 13.172] (assumes normal distribution)


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
# Warmup Iteration   1: 7.741 ops/ms
# Warmup Iteration   2: 12.682 ops/ms
# Warmup Iteration   3: 12.837 ops/ms
Iteration   1: 12.866 ops/ms
Iteration   2: 12.823 ops/ms
Iteration   3: 12.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.774 ±(99.9%) 2.250 ops/ms [Average]
  (min, avg, max) = (12.634, 12.774, 12.866), stdev = 0.123
  CI (99.9%): [10.525, 15.024] (assumes normal distribution)


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
# Warmup Iteration   1: 7.283 ops/ms
# Warmup Iteration   2: 12.329 ops/ms
# Warmup Iteration   3: 12.684 ops/ms
Iteration   1: 12.774 ops/ms
Iteration   2: 12.545 ops/ms
Iteration   3: 12.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.675 ±(99.9%) 2.142 ops/ms [Average]
  (min, avg, max) = (12.545, 12.675, 12.774), stdev = 0.117
  CI (99.9%): [10.533, 14.817] (assumes normal distribution)


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
# Warmup Iteration   1: 6.110 ops/ms
# Warmup Iteration   2: 10.198 ops/ms
# Warmup Iteration   3: 10.506 ops/ms
Iteration   1: 10.559 ops/ms
Iteration   2: 10.526 ops/ms
Iteration   3: 10.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.556 ±(99.9%) 0.517 ops/ms [Average]
  (min, avg, max) = (10.526, 10.556, 10.582), stdev = 0.028
  CI (99.9%): [10.039, 11.073] (assumes normal distribution)


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.658 ±(99.9%) 0.005 ms/op
Iteration   1: 2.609 ±(99.9%) 0.004 ms/op
Iteration   2: 2.587 ±(99.9%) 0.004 ms/op
Iteration   3: 2.543 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.580 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (2.543, 2.580, 2.609), stdev = 0.034
  CI (99.9%): [1.959, 3.200] (assumes normal distribution)


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
# Warmup Iteration   1: 3.740 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.474 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (2.459, 2.474, 2.489), stdev = 0.015
  CI (99.9%): [2.198, 2.749] (assumes normal distribution)


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.516 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (2.504, 2.516, 2.536), stdev = 0.017
  CI (99.9%): [2.203, 2.829] (assumes normal distribution)


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
# Warmup Iteration   1: 4.838 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.004 ms/op
Iteration   1: 3.036 ±(99.9%) 0.004 ms/op
Iteration   2: 3.061 ±(99.9%) 0.005 ms/op
Iteration   3: 3.049 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.049 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (3.036, 3.049, 3.061), stdev = 0.012
  CI (99.9%): [2.824, 3.273] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.536 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  11.647 ms/op
                 createUser·p0.9999: 21.808 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.762 ms/op
                 createUser·p0.999:  9.830 ms/op
                 createUser·p0.9999: 12.164 ms/op
                 createUser·p1.00:   12.780 ms/op

Iteration   3: 2.586 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  9.001 ms/op
                 createUser·p0.9999: 10.977 ms/op
                 createUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375544
  mean =      2.554 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180012 
    [ 2.500,  5.000) = 194727 
    [ 5.000,  7.500) = 403 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      9.092 ms/op
     p(99.9900) =     14.065 ms/op
     p(99.9990) =     22.462 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 13.763 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  5.144 ms/op
                 existUser·p0.9999: 14.303 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  8.902 ms/op
                 existUser·p0.9999: 12.158 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381703
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 185991 
    [ 2.500,  3.750) = 191547 
    [ 3.750,  5.000) = 3149 
    [ 5.000,  6.250) = 551 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      6.845 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     15.073 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.598 ±(99.9%) 0.006 ms/op
Iteration   1: 2.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.901 ms/op
                 getUser·p0.999:  11.649 ms/op
                 getUser·p0.9999: 21.050 ms/op
                 getUser·p1.00:   22.086 ms/op

Iteration   2: 2.556 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.305 ms/op
                 getUser·p0.99:   4.051 ms/op
                 getUser·p0.999:  11.208 ms/op
                 getUser·p0.9999: 15.971 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.944 ms/op
                 getUser·p0.999:  6.507 ms/op
                 getUser·p0.9999: 11.233 ms/op
                 getUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377977
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 184323 
    [ 2.500,  5.000) = 192820 
    [ 5.000,  7.500) = 468 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =     16.643 ms/op
     p(99.9990) =     21.798 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 4.899 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.009 ms/op
Iteration   1: 3.078 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 11.010 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   2: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.806 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 11.249 ms/op
                 listUser·p1.00:   12.091 ms/op

Iteration   3: 3.084 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.980 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.770 ms/op
                 listUser·p0.9999: 18.600 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311499
  mean =      3.079 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 79686 
    [ 2.500,  3.750) = 188725 
    [ 3.750,  5.000) = 35335 
    [ 5.000,  6.250) = 6161 
    [ 6.250,  7.500) = 845 
    [ 7.500,  8.750) = 124 
    [ 8.750, 10.000) = 271 
    [10.000, 11.250) = 176 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     19.067 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.265 ± 0.907  ops/ms
ClientPb.existUser                       thrpt       3  12.774 ± 2.250  ops/ms
ClientPb.getUser                         thrpt       3  12.675 ± 2.142  ops/ms
ClientPb.listUser                        thrpt       3  10.556 ± 0.517  ops/ms
ClientPb.createUser                       avgt       3   2.580 ± 0.620   ms/op
ClientPb.existUser                        avgt       3   2.474 ± 0.276   ms/op
ClientPb.getUser                          avgt       3   2.516 ± 0.313   ms/op
ClientPb.listUser                         avgt       3   3.049 ± 0.225   ms/op
ClientPb.createUser                     sample  375544   2.554 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.777           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.092           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.065           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.577           ms/op
ClientPb.existUser                      sample  381703   2.512 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.726           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.845           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.763           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.106           ms/op
ClientPb.getUser                        sample  377977   2.538 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.893           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.816           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.643           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.086           ms/op
ClientPb.listUser                       sample  311499   3.079 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.806           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.023           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.039           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.071           ms/op
