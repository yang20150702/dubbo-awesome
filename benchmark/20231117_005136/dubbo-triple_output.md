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
# Warmup Iteration   1: 4.574 ops/ms
# Warmup Iteration   2: 11.731 ops/ms
# Warmup Iteration   3: 12.092 ops/ms
Iteration   1: 12.291 ops/ms
Iteration   2: 12.239 ops/ms
Iteration   3: 12.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.361 ±(99.9%) 3.058 ops/ms [Average]
  (min, avg, max) = (12.239, 12.361, 12.552), stdev = 0.168
  CI (99.9%): [9.303, 15.418] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.852 ops/ms
# Warmup Iteration   2: 12.454 ops/ms
# Warmup Iteration   3: 12.858 ops/ms
Iteration   1: 12.754 ops/ms
Iteration   2: 12.873 ops/ms
Iteration   3: 12.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.873 ±(99.9%) 2.159 ops/ms [Average]
  (min, avg, max) = (12.754, 12.873, 12.991), stdev = 0.118
  CI (99.9%): [10.713, 15.032] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.209 ops/ms
# Warmup Iteration   2: 12.067 ops/ms
# Warmup Iteration   3: 12.217 ops/ms
Iteration   1: 12.407 ops/ms
Iteration   2: 12.480 ops/ms
Iteration   3: 12.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.386 ±(99.9%) 1.933 ops/ms [Average]
  (min, avg, max) = (12.271, 12.386, 12.480), stdev = 0.106
  CI (99.9%): [10.453, 14.319] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.457 ops/ms
# Warmup Iteration   2: 10.374 ops/ms
# Warmup Iteration   3: 10.190 ops/ms
Iteration   1: 10.378 ops/ms
Iteration   2: 10.533 ops/ms
Iteration   3: 10.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.418 ±(99.9%) 1.839 ops/ms [Average]
  (min, avg, max) = (10.343, 10.418, 10.533), stdev = 0.101
  CI (99.9%): [8.579, 12.258] (assumes normal distribution)


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
# Warmup Iteration   1: 4.182 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.708 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.004 ms/op
Iteration   1: 2.587 ±(99.9%) 0.005 ms/op
Iteration   2: 2.630 ±(99.9%) 0.004 ms/op
Iteration   3: 2.577 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.598 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (2.577, 2.598, 2.630), stdev = 0.028
  CI (99.9%): [2.082, 3.114] (assumes normal distribution)


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
# Warmup Iteration   1: 3.698 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.003 ms/op
Iteration   1: 2.421 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (2.421, 2.451, 2.470), stdev = 0.027
  CI (99.9%): [1.967, 2.935] (assumes normal distribution)


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.004 ms/op
Iteration   1: 2.558 ±(99.9%) 0.004 ms/op
Iteration   2: 2.564 ±(99.9%) 0.005 ms/op
Iteration   3: 2.557 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.559 ±(99.9%) 0.071 ms/op [Average]
  (min, avg, max) = (2.557, 2.559, 2.564), stdev = 0.004
  CI (99.9%): [2.489, 2.630] (assumes normal distribution)


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
# Warmup Iteration   1: 4.924 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.005 ms/op
Iteration   1: 3.059 ±(99.9%) 0.005 ms/op
Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
Iteration   3: 3.045 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (3.028, 3.044, 3.059), stdev = 0.015
  CI (99.9%): [2.763, 3.324] (assumes normal distribution)


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  11.390 ms/op
                 createUser·p0.9999: 14.046 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  8.749 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   3: 2.567 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.511 ms/op
                 createUser·p0.9999: 10.380 ms/op
                 createUser·p1.00:   10.617 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377868
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 182022 
    [ 2.500,  3.750) = 190211 
    [ 3.750,  5.000) = 4296 
    [ 5.000,  6.250) = 802 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     13.861 ms/op
     p(99.9990) =     14.147 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.750 ms/op
                 existUser·p0.999:  11.450 ms/op
                 existUser·p0.9999: 14.078 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  7.119 ms/op
                 existUser·p0.9999: 12.239 ms/op
                 existUser·p1.00:   12.419 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  8.862 ms/op
                 existUser·p0.9999: 11.923 ms/op
                 existUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382745
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 186192 
    [ 2.500,  3.750) = 192235 
    [ 3.750,  5.000) = 3204 
    [ 5.000,  6.250) = 631 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      7.776 ms/op
     p(99.9900) =     13.594 ms/op
     p(99.9990) =     14.241 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.531 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  11.759 ms/op
                 getUser·p0.9999: 13.916 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  10.188 ms/op
                 getUser·p0.9999: 15.660 ms/op
                 getUser·p1.00:   15.876 ms/op

Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.795 ms/op
                 getUser·p0.9999: 13.786 ms/op
                 getUser·p1.00:   14.303 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378592
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 184450 
    [ 2.500,  3.750) = 187077 
    [ 3.750,  5.000) = 5139 
    [ 5.000,  6.250) = 1308 
    [ 6.250,  7.500) = 125 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.877 ms/op
     p(99.9900) =     14.109 ms/op
     p(99.9990) =     15.743 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


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
# Warmup Iteration   1: 4.923 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.009 ms/op
Iteration   1: 3.119 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   5.890 ms/op
                 listUser·p0.999:  9.609 ms/op
                 listUser·p0.9999: 11.514 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   2: 3.134 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   3.056 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.929 ms/op
                 listUser·p0.999:  9.911 ms/op
                 listUser·p0.9999: 18.966 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   3: 3.094 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.731 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  10.174 ms/op
                 listUser·p0.9999: 11.545 ms/op
                 listUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 307850
  mean =      3.115 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 77417 
    [ 2.500,  3.750) = 182741 
    [ 3.750,  5.000) = 37889 
    [ 5.000,  6.250) = 7871 
    [ 6.250,  7.500) = 1043 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 305 
    [10.000, 11.250) = 196 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =      9.882 ms/op
     p(99.9900) =     17.323 ms/op
     p(99.9990) =     19.099 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.361 ± 3.058  ops/ms
ClientPb.existUser                       thrpt       3  12.873 ± 2.159  ops/ms
ClientPb.getUser                         thrpt       3  12.386 ± 1.933  ops/ms
ClientPb.listUser                        thrpt       3  10.418 ± 1.839  ops/ms
ClientPb.createUser                       avgt       3   2.598 ± 0.516   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.484   ms/op
ClientPb.getUser                          avgt       3   2.559 ± 0.071   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.281   ms/op
ClientPb.createUser                     sample  377868   2.538 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.693           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.962           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.861           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.287           ms/op
ClientPb.existUser                      sample  382745   2.506 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.787           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.776           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.594           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.418           ms/op
ClientPb.getUser                        sample  378592   2.533 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.818           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.877           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.109           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.876           ms/op
ClientPb.listUser                       sample  307850   3.115 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.043           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.865           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.882           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.323           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.169           ms/op
