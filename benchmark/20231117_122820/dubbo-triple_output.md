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
# Warmup Iteration   1: 4.523 ops/ms
# Warmup Iteration   2: 11.690 ops/ms
# Warmup Iteration   3: 12.088 ops/ms
Iteration   1: 12.250 ops/ms
Iteration   2: 12.484 ops/ms
Iteration   3: 12.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.350 ±(99.9%) 2.198 ops/ms [Average]
  (min, avg, max) = (12.250, 12.350, 12.484), stdev = 0.120
  CI (99.9%): [10.153, 14.548] (assumes normal distribution)


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
# Warmup Iteration   1: 7.983 ops/ms
# Warmup Iteration   2: 12.990 ops/ms
# Warmup Iteration   3: 12.858 ops/ms
Iteration   1: 12.894 ops/ms
Iteration   2: 12.849 ops/ms
Iteration   3: 12.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.860 ±(99.9%) 0.545 ops/ms [Average]
  (min, avg, max) = (12.837, 12.860, 12.894), stdev = 0.030
  CI (99.9%): [12.315, 13.405] (assumes normal distribution)


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
# Warmup Iteration   1: 7.408 ops/ms
# Warmup Iteration   2: 12.333 ops/ms
# Warmup Iteration   3: 12.340 ops/ms
Iteration   1: 12.459 ops/ms
Iteration   2: 12.723 ops/ms
Iteration   3: 12.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.572 ±(99.9%) 2.482 ops/ms [Average]
  (min, avg, max) = (12.459, 12.572, 12.723), stdev = 0.136
  CI (99.9%): [10.090, 15.054] (assumes normal distribution)


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
# Warmup Iteration   1: 6.251 ops/ms
# Warmup Iteration   2: 10.124 ops/ms
# Warmup Iteration   3: 10.216 ops/ms
Iteration   1: 10.220 ops/ms
Iteration   2: 10.492 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.398 ±(99.9%) 2.805 ops/ms [Average]
  (min, avg, max) = (10.220, 10.398, 10.492), stdev = 0.154
  CI (99.9%): [7.592, 13.203] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.011 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.005 ms/op
Iteration   1: 2.557 ±(99.9%) 0.005 ms/op
Iteration   2: 2.576 ±(99.9%) 0.005 ms/op
Iteration   3: 2.566 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.566 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.557, 2.566, 2.576), stdev = 0.010
  CI (99.9%): [2.392, 2.740] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.005 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.558 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.532 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (2.508, 2.532, 2.558), stdev = 0.025
  CI (99.9%): [2.076, 2.989] (assumes normal distribution)


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.004 ms/op
Iteration   1: 2.561 ±(99.9%) 0.005 ms/op
Iteration   2: 2.610 ±(99.9%) 0.005 ms/op
Iteration   3: 2.559 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.577 ±(99.9%) 0.530 ms/op [Average]
  (min, avg, max) = (2.559, 2.577, 2.610), stdev = 0.029
  CI (99.9%): [2.047, 3.107] (assumes normal distribution)


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
# Warmup Iteration   1: 4.857 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.005 ms/op
Iteration   1: 3.124 ±(99.9%) 0.005 ms/op
Iteration   2: 3.125 ±(99.9%) 0.005 ms/op
Iteration   3: 3.109 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.119 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (3.109, 3.119, 3.125), stdev = 0.009
  CI (99.9%): [2.960, 3.279] (assumes normal distribution)


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.674 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.544 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  12.021 ms/op
                 createUser·p0.9999: 14.811 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  8.566 ms/op
                 createUser·p0.9999: 13.858 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.939 ms/op
                 createUser·p0.999:  9.343 ms/op
                 createUser·p0.9999: 17.952 ms/op
                 createUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377581
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181319 
    [ 2.500,  5.000) = 195047 
    [ 5.000,  7.500) = 751 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     14.942 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.491 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  11.341 ms/op
                 existUser·p0.9999: 14.068 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  8.815 ms/op
                 existUser·p0.9999: 13.616 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.792 ms/op
                 existUser·p0.999:  5.751 ms/op
                 existUser·p0.9999: 14.949 ms/op
                 existUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386426
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 193419 
    [ 2.500,  3.750) = 189039 
    [ 3.750,  5.000) = 2942 
    [ 5.000,  6.250) = 562 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 127 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      7.148 ms/op
     p(99.9900) =     14.325 ms/op
     p(99.9990) =     15.632 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  12.272 ms/op
                 getUser·p0.9999: 15.486 ms/op
                 getUser·p1.00:   16.482 ms/op

Iteration   2: 2.541 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.168 ms/op
                 getUser·p0.9999: 18.645 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.390 ms/op
                 getUser·p0.999:  8.770 ms/op
                 getUser·p0.9999: 11.640 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379409
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 185161 
    [ 2.500,  3.750) = 187699 
    [ 3.750,  5.000) = 4547 
    [ 5.000,  6.250) = 1372 
    [ 6.250,  7.500) = 198 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.181 ms/op
     p(99.9900) =     15.668 ms/op
     p(99.9990) =     18.685 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 4.763 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.009 ms/op
Iteration   1: 3.137 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   3.056 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   5.858 ms/op
                 listUser·p0.999:  9.752 ms/op
                 listUser·p0.9999: 11.515 ms/op
                 listUser·p1.00:   12.222 ms/op

Iteration   2: 3.120 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 10.940 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   3: 3.114 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  10.371 ms/op
                 listUser·p0.9999: 12.771 ms/op
                 listUser·p1.00:   15.204 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 306920
  mean =      3.124 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 71548 
    [ 2.500,  3.750) = 187290 
    [ 3.750,  5.000) = 38900 
    [ 5.000,  6.250) = 7425 
    [ 6.250,  7.500) = 889 
    [ 7.500,  8.750) = 198 
    [ 8.750, 10.000) = 265 
    [10.000, 11.250) = 257 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     12.375 ms/op
     p(99.9990) =     14.141 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.350 ± 2.198  ops/ms
ClientPb.existUser                       thrpt       3  12.860 ± 0.545  ops/ms
ClientPb.getUser                         thrpt       3  12.572 ± 2.482  ops/ms
ClientPb.listUser                        thrpt       3  10.398 ± 2.805  ops/ms
ClientPb.createUser                       avgt       3   2.566 ± 0.174   ms/op
ClientPb.existUser                        avgt       3   2.532 ± 0.456   ms/op
ClientPb.getUser                          avgt       3   2.577 ± 0.530   ms/op
ClientPb.listUser                         avgt       3   3.119 ± 0.160   ms/op
ClientPb.createUser                     sample  377581   2.540 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.951           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.241           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.942           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.592           ms/op
ClientPb.existUser                      sample  386426   2.483 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.764           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.148           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.325           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.515           ms/op
ClientPb.getUser                        sample  379409   2.528 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.601           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.181           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.668           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.743           ms/op
ClientPb.listUser                       sample  306920   3.124 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.839           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.052           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.060           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.375           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.204           ms/op
