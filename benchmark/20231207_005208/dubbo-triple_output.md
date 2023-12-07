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
# Warmup Iteration   1: 4.877 ops/ms
# Warmup Iteration   2: 11.969 ops/ms
# Warmup Iteration   3: 12.150 ops/ms
Iteration   1: 12.395 ops/ms
Iteration   2: 12.204 ops/ms
Iteration   3: 12.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.301 ±(99.9%) 1.744 ops/ms [Average]
  (min, avg, max) = (12.204, 12.301, 12.395), stdev = 0.096
  CI (99.9%): [10.557, 14.045] (assumes normal distribution)


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
# Warmup Iteration   1: 8.349 ops/ms
# Warmup Iteration   2: 12.926 ops/ms
# Warmup Iteration   3: 12.789 ops/ms
Iteration   1: 12.726 ops/ms
Iteration   2: 12.829 ops/ms
Iteration   3: 12.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.767 ±(99.9%) 0.997 ops/ms [Average]
  (min, avg, max) = (12.726, 12.767, 12.829), stdev = 0.055
  CI (99.9%): [11.770, 13.764] (assumes normal distribution)


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
# Warmup Iteration   1: 7.988 ops/ms
# Warmup Iteration   2: 12.191 ops/ms
# Warmup Iteration   3: 12.506 ops/ms
Iteration   1: 12.621 ops/ms
Iteration   2: 12.633 ops/ms
Iteration   3: 12.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.546 ±(99.9%) 2.563 ops/ms [Average]
  (min, avg, max) = (12.384, 12.546, 12.633), stdev = 0.140
  CI (99.9%): [9.983, 15.109] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.783 ops/ms
# Warmup Iteration   2: 10.445 ops/ms
# Warmup Iteration   3: 10.446 ops/ms
Iteration   1: 10.506 ops/ms
Iteration   2: 10.564 ops/ms
Iteration   3: 10.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.513 ±(99.9%) 0.862 ops/ms [Average]
  (min, avg, max) = (10.470, 10.513, 10.564), stdev = 0.047
  CI (99.9%): [9.651, 11.375] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.999 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.004 ms/op
Iteration   1: 2.586 ±(99.9%) 0.003 ms/op
Iteration   2: 2.577 ±(99.9%) 0.003 ms/op
Iteration   3: 2.584 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.583 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.577, 2.583, 2.586), stdev = 0.005
  CI (99.9%): [2.490, 2.675] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.738 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.004 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.517 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.519 ±(99.9%) 0.079 ms/op [Average]
  (min, avg, max) = (2.516, 2.519, 2.524), stdev = 0.004
  CI (99.9%): [2.440, 2.598] (assumes normal distribution)


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.003 ms/op
Iteration   1: 2.535 ±(99.9%) 0.004 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.572 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.544 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (2.525, 2.544, 2.572), stdev = 0.025
  CI (99.9%): [2.093, 2.994] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.974 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
Iteration   3: 3.067 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.073 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (3.065, 3.073, 3.087), stdev = 0.012
  CI (99.9%): [2.847, 3.299] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.316 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.704 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.589 ±(99.9%) 0.006 ms/op
Iteration   1: 2.584 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  11.776 ms/op
                 createUser·p0.9999: 14.051 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 2.596 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  10.240 ms/op
                 createUser·p0.9999: 12.678 ms/op
                 createUser·p1.00:   13.681 ms/op

Iteration   3: 2.594 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  6.515 ms/op
                 createUser·p0.9999: 10.503 ms/op
                 createUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370158
  mean =      2.591 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 173530 
    [ 2.500,  3.750) = 191345 
    [ 3.750,  5.000) = 4321 
    [ 5.000,  6.250) = 494 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.146 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      6.928 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     14.493 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.748 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  5.929 ms/op
                 existUser·p0.9999: 13.910 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  9.443 ms/op
                 existUser·p0.9999: 22.839 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.895 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 13.816 ms/op
                 existUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381995
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 184523 
    [ 2.500,  5.000) = 196607 
    [ 5.000,  7.500) = 499 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      6.513 ms/op
     p(99.9900) =     14.628 ms/op
     p(99.9990) =     23.722 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  5.685 ms/op
                 getUser·p0.9999: 13.628 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  8.886 ms/op
                 getUser·p0.9999: 14.210 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  8.618 ms/op
                 getUser·p0.9999: 21.037 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379907
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185831 
    [ 2.500,  5.000) = 192764 
    [ 5.000,  7.500) = 942 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.026 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =     14.828 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 4.607 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.338 ms/op
                 listUser·p1.00:   10.912 ms/op

Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.154 ms/op
                 listUser·p0.9999: 10.803 ms/op
                 listUser·p1.00:   12.485 ms/op

Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 10.969 ms/op
                 listUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315952
  mean =      3.036 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 88805 
    [ 2.500,  3.750) = 185604 
    [ 3.750,  5.000) = 33474 
    [ 5.000,  6.250) = 6285 
    [ 6.250,  7.500) = 918 
    [ 7.500,  8.750) = 315 
    [ 8.750, 10.000) = 305 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     10.735 ms/op
     p(99.9990) =     11.636 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.301 ± 1.744  ops/ms
ClientPb.existUser                       thrpt       3  12.767 ± 0.997  ops/ms
ClientPb.getUser                         thrpt       3  12.546 ± 2.563  ops/ms
ClientPb.listUser                        thrpt       3  10.513 ± 0.862  ops/ms
ClientPb.createUser                       avgt       3   2.583 ± 0.092   ms/op
ClientPb.existUser                        avgt       3   2.519 ± 0.079   ms/op
ClientPb.getUser                          avgt       3   2.544 ± 0.450   ms/op
ClientPb.listUser                         avgt       3   3.073 ± 0.226   ms/op
ClientPb.createUser                     sample  370158   2.591 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.918           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.671           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.928           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.353           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.696           ms/op
ClientPb.existUser                      sample  381995   2.510 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.918           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.593           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.513           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.628           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.362           ms/op
ClientPb.getUser                        sample  379907   2.525 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.579           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.078           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.828           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.692           ms/op
ClientPb.listUser                       sample  315952   3.036 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.949           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.735           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.485           ms/op
