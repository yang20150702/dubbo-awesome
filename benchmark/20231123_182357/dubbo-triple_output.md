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
# Warmup Iteration   1: 4.240 ops/ms
# Warmup Iteration   2: 11.491 ops/ms
# Warmup Iteration   3: 11.608 ops/ms
Iteration   1: 11.974 ops/ms
Iteration   2: 11.890 ops/ms
Iteration   3: 12.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  11.976 ±(99.9%) 1.571 ops/ms [Average]
  (min, avg, max) = (11.890, 11.976, 12.062), stdev = 0.086
  CI (99.9%): [10.404, 13.547] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 7.650 ops/ms
# Warmup Iteration   2: 12.890 ops/ms
# Warmup Iteration   3: 12.778 ops/ms
Iteration   1: 12.775 ops/ms
Iteration   2: 12.726 ops/ms
Iteration   3: 12.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.802 ±(99.9%) 1.695 ops/ms [Average]
  (min, avg, max) = (12.726, 12.802, 12.905), stdev = 0.093
  CI (99.9%): [11.107, 14.497] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.960 ops/ms
# Warmup Iteration   2: 12.187 ops/ms
# Warmup Iteration   3: 12.454 ops/ms
Iteration   1: 12.374 ops/ms
Iteration   2: 12.185 ops/ms
Iteration   3: 12.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.308 ±(99.9%) 1.949 ops/ms [Average]
  (min, avg, max) = (12.185, 12.308, 12.374), stdev = 0.107
  CI (99.9%): [10.359, 14.257] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.072 ops/ms
# Warmup Iteration   2: 9.933 ops/ms
# Warmup Iteration   3: 10.027 ops/ms
Iteration   1: 10.138 ops/ms
Iteration   2: 10.234 ops/ms
Iteration   3: 10.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.221 ±(99.9%) 1.407 ops/ms [Average]
  (min, avg, max) = (10.138, 10.221, 10.290), stdev = 0.077
  CI (99.9%): [8.813, 11.628] (assumes normal distribution)


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.612 ±(99.9%) 0.004 ms/op
Iteration   1: 2.610 ±(99.9%) 0.004 ms/op
Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
Iteration   3: 2.628 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.605 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (2.577, 2.605, 2.628), stdev = 0.026
  CI (99.9%): [2.129, 3.081] (assumes normal distribution)


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
# Warmup Iteration   1: 3.684 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.003 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.482 ±(99.9%) 0.088 ms/op [Average]
  (min, avg, max) = (2.477, 2.482, 2.486), stdev = 0.005
  CI (99.9%): [2.394, 2.570] (assumes normal distribution)


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.584 ±(99.9%) 0.004 ms/op
Iteration   1: 2.587 ±(99.9%) 0.005 ms/op
Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
Iteration   3: 2.547 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.566 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.547, 2.566, 2.587), stdev = 0.020
  CI (99.9%): [2.206, 2.925] (assumes normal distribution)


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
# Warmup Iteration   1: 4.903 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.006 ms/op
Iteration   1: 3.062 ±(99.9%) 0.004 ms/op
Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
Iteration   3: 3.057 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.065 ±(99.9%) 0.169 ms/op [Average]
  (min, avg, max) = (3.057, 3.065, 3.075), stdev = 0.009
  CI (99.9%): [2.896, 3.234] (assumes normal distribution)


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.742 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.006 ms/op
Iteration   1: 2.629 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   2.712 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.351 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  12.452 ms/op
                 createUser·p0.9999: 18.711 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   2: 2.617 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.174 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  12.091 ms/op
                 createUser·p0.9999: 14.365 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   3: 2.596 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  9.646 ms/op
                 createUser·p0.9999: 12.873 ms/op
                 createUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 366885
  mean =      2.614 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 170912 
    [ 2.500,  3.750) = 188767 
    [ 3.750,  5.000) = 5764 
    [ 5.000,  6.250) = 757 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 79 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.675 ms/op
     p(90.0000) =      3.170 ms/op
     p(95.0000) =      3.322 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =     10.469 ms/op
     p(99.9900) =     15.750 ms/op
     p(99.9990) =     19.726 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 3.754 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.006 ms/op
Iteration   1: 2.560 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   2.646 ms/op
                 existUser·p0.90:   3.109 ms/op
                 existUser·p0.95:   3.219 ms/op
                 existUser·p0.99:   3.729 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 14.361 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   2.654 ms/op
                 existUser·p0.90:   3.125 ms/op
                 existUser·p0.95:   3.240 ms/op
                 existUser·p0.99:   3.858 ms/op
                 existUser·p0.999:  6.039 ms/op
                 existUser·p0.9999: 12.274 ms/op
                 existUser·p1.00:   12.829 ms/op

Iteration   3: 2.578 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.662 ms/op
                 existUser·p0.90:   3.142 ms/op
                 existUser·p0.95:   3.281 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  10.436 ms/op
                 existUser·p0.9999: 12.435 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 373276
  mean =      2.569 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 178449 
    [ 2.500,  3.750) = 190228 
    [ 3.750,  5.000) = 3760 
    [ 5.000,  6.250) = 428 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      7.576 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     14.652 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.006 ms/op
Iteration   1: 2.594 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.638 ms/op
                 getUser·p0.90:   3.146 ms/op
                 getUser·p0.95:   3.316 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  12.526 ms/op
                 getUser·p0.9999: 14.953 ms/op
                 getUser·p1.00:   15.925 ms/op

Iteration   2: 2.605 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.654 ms/op
                 getUser·p0.90:   3.174 ms/op
                 getUser·p0.95:   3.383 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.148 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   3: 2.597 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   2.621 ms/op
                 getUser·p0.90:   3.187 ms/op
                 getUser·p0.95:   3.375 ms/op
                 getUser·p0.99:   4.112 ms/op
                 getUser·p0.999:  5.882 ms/op
                 getUser·p0.9999: 12.173 ms/op
                 getUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 369078
  mean =      2.599 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 173024 
    [ 2.500,  3.750) = 186971 
    [ 3.750,  5.000) = 7382 
    [ 5.000,  6.250) = 1092 
    [ 6.250,  7.500) = 225 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.166 ms/op
     p(95.0000) =      3.359 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.110 ms/op
     p(99.9900) =     14.174 ms/op
     p(99.9990) =     15.121 ms/op
     p(99.9999) =     15.925 ms/op
    p(100.0000) =     15.925 ms/op


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
# Warmup Iteration   1: 4.949 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.009 ms/op
Iteration   1: 3.122 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   3.064 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.694 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   2: 3.109 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  10.011 ms/op
                 listUser·p0.9999: 11.197 ms/op
                 listUser·p1.00:   12.026 ms/op

Iteration   3: 3.110 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.022 ms/op
                 listUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 308022
  mean =      3.114 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 73227 
    [ 2.500,  3.750) = 188004 
    [ 3.750,  5.000) = 38626 
    [ 5.000,  6.250) = 6583 
    [ 6.250,  7.500) = 771 
    [ 7.500,  8.750) = 188 
    [ 8.750, 10.000) = 322 
    [10.000, 11.250) = 200 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     11.177 ms/op
     p(99.9990) =     12.025 ms/op
     p(99.9999) =     12.304 ms/op
    p(100.0000) =     12.304 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  11.976 ± 1.571  ops/ms
ClientPb.existUser                       thrpt       3  12.802 ± 1.695  ops/ms
ClientPb.getUser                         thrpt       3  12.308 ± 1.949  ops/ms
ClientPb.listUser                        thrpt       3  10.221 ± 1.407  ops/ms
ClientPb.createUser                       avgt       3   2.605 ± 0.476   ms/op
ClientPb.existUser                        avgt       3   2.482 ± 0.088   ms/op
ClientPb.getUser                          avgt       3   2.566 ± 0.360   ms/op
ClientPb.listUser                         avgt       3   3.065 ± 0.169   ms/op
ClientPb.createUser                     sample  366885   2.614 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.869           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.675           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.469           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.750           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.857           ms/op
ClientPb.existUser                      sample  373276   2.569 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.964           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.654           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.576           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.730           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.696           ms/op
ClientPb.getUser                        sample  369078   2.599 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.970           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.638           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.110           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.174           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.925           ms/op
ClientPb.listUser                       sample  308022   3.114 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.052           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.798           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.177           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.304           ms/op
