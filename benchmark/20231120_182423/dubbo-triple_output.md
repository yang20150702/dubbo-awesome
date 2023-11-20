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
# Warmup Iteration   1: 4.616 ops/ms
# Warmup Iteration   2: 11.587 ops/ms
# Warmup Iteration   3: 12.169 ops/ms
Iteration   1: 12.493 ops/ms
Iteration   2: 12.586 ops/ms
Iteration   3: 12.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.558 ±(99.9%) 1.028 ops/ms [Average]
  (min, avg, max) = (12.493, 12.558, 12.595), stdev = 0.056
  CI (99.9%): [11.530, 13.585] (assumes normal distribution)


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
# Warmup Iteration   1: 7.921 ops/ms
# Warmup Iteration   2: 13.065 ops/ms
# Warmup Iteration   3: 13.003 ops/ms
Iteration   1: 13.015 ops/ms
Iteration   2: 13.081 ops/ms
Iteration   3: 13.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.074 ±(99.9%) 1.022 ops/ms [Average]
  (min, avg, max) = (13.015, 13.074, 13.126), stdev = 0.056
  CI (99.9%): [12.052, 14.096] (assumes normal distribution)


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
# Warmup Iteration   1: 7.694 ops/ms
# Warmup Iteration   2: 12.770 ops/ms
# Warmup Iteration   3: 12.769 ops/ms
Iteration   1: 12.827 ops/ms
Iteration   2: 12.750 ops/ms
Iteration   3: 12.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.767 ±(99.9%) 0.982 ops/ms [Average]
  (min, avg, max) = (12.723, 12.767, 12.827), stdev = 0.054
  CI (99.9%): [11.785, 13.748] (assumes normal distribution)


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
# Warmup Iteration   1: 6.168 ops/ms
# Warmup Iteration   2: 10.236 ops/ms
# Warmup Iteration   3: 10.396 ops/ms
Iteration   1: 10.455 ops/ms
Iteration   2: 10.513 ops/ms
Iteration   3: 10.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.512 ±(99.9%) 1.036 ops/ms [Average]
  (min, avg, max) = (10.455, 10.512, 10.568), stdev = 0.057
  CI (99.9%): [9.476, 11.548] (assumes normal distribution)


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.004 ms/op
Iteration   1: 2.520 ±(99.9%) 0.003 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (2.500, 2.512, 2.520), stdev = 0.011
  CI (99.9%): [2.312, 2.712] (assumes normal distribution)


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.500 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.489, 2.500, 2.505), stdev = 0.009
  CI (99.9%): [2.335, 2.664] (assumes normal distribution)


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.495 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (2.488, 2.495, 2.506), stdev = 0.009
  CI (99.9%): [2.323, 2.668] (assumes normal distribution)


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
# Warmup Iteration   1: 4.516 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.004 ms/op
Iteration   1: 3.021 ±(99.9%) 0.005 ms/op
Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
Iteration   3: 2.994 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.012 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (2.994, 3.012, 3.022), stdev = 0.016
  CI (99.9%): [2.723, 3.302] (assumes normal distribution)


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.687 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  12.059 ms/op
                 createUser·p0.9999: 14.156 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.502 ms/op
                 createUser·p0.999:  8.203 ms/op
                 createUser·p0.9999: 11.144 ms/op
                 createUser·p1.00:   11.993 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  8.038 ms/op
                 createUser·p0.9999: 10.719 ms/op
                 createUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383471
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 183339 
    [ 2.500,  3.750) = 196321 
    [ 3.750,  5.000) = 2899 
    [ 5.000,  6.250) = 423 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      8.111 ms/op
     p(99.9900) =     13.462 ms/op
     p(99.9990) =     14.489 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.597 ms/op
                 existUser·p0.999:  6.563 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  5.734 ms/op
                 existUser·p0.9999: 19.009 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 12.669 ms/op
                 existUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387311
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188803 
    [ 2.500,  5.000) = 197626 
    [ 5.000,  7.500) = 504 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      6.927 ms/op
     p(99.9900) =     14.045 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.006 ms/op
Iteration   1: 2.563 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.034 ms/op
                 getUser·p0.999:  12.129 ms/op
                 getUser·p0.9999: 14.369 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.005 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  8.573 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   3: 2.580 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  9.011 ms/op
                 getUser·p0.9999: 10.434 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374222
  mean =      2.563 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 182131 
    [ 2.500,  5.000) = 190717 
    [ 5.000,  7.500) = 988 
    [ 7.500, 10.000) = 131 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      8.742 ms/op
     p(99.9900) =     14.598 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 4.847 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.009 ms/op
Iteration   1: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.011 ms/op
                 listUser·p0.9999: 12.201 ms/op
                 listUser·p1.00:   13.287 ms/op

Iteration   2: 3.076 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  10.699 ms/op
                 listUser·p0.9999: 14.382 ms/op
                 listUser·p1.00:   15.221 ms/op

Iteration   3: 3.095 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.272 ms/op
                 listUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311390
  mean =      3.080 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 80745 
    [ 2.500,  3.750) = 186214 
    [ 3.750,  5.000) = 35662 
    [ 5.000,  6.250) = 6963 
    [ 6.250,  7.500) = 937 
    [ 7.500,  8.750) = 300 
    [ 8.750, 10.000) = 199 
    [10.000, 11.250) = 157 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =      9.709 ms/op
     p(99.9900) =     13.613 ms/op
     p(99.9990) =     14.529 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.558 ± 1.028  ops/ms
ClientPb.existUser                       thrpt       3  13.074 ± 1.022  ops/ms
ClientPb.getUser                         thrpt       3  12.767 ± 0.982  ops/ms
ClientPb.listUser                        thrpt       3  10.512 ± 1.036  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.200   ms/op
ClientPb.existUser                        avgt       3   2.500 ± 0.165   ms/op
ClientPb.getUser                          avgt       3   2.495 ± 0.173   ms/op
ClientPb.listUser                         avgt       3   3.012 ± 0.290   ms/op
ClientPb.createUser                     sample  383471   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.001           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.111           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.462           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.680           ms/op
ClientPb.existUser                      sample  387311   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.939           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.927           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.045           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.251           ms/op
ClientPb.getUser                        sample  374222   2.563 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.614           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.742           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.598           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.643           ms/op
ClientPb.listUser                       sample  311390   3.080 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.833           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.775           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.709           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.613           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.221           ms/op
