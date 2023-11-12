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
# Warmup Iteration   1: 4.883 ops/ms
# Warmup Iteration   2: 12.017 ops/ms
# Warmup Iteration   3: 12.416 ops/ms
Iteration   1: 12.645 ops/ms
Iteration   2: 12.870 ops/ms
Iteration   3: 12.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.832 ±(99.9%) 3.129 ops/ms [Average]
  (min, avg, max) = (12.645, 12.832, 12.982), stdev = 0.172
  CI (99.9%): [9.703, 15.961] (assumes normal distribution)


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
# Warmup Iteration   1: 8.143 ops/ms
# Warmup Iteration   2: 13.110 ops/ms
# Warmup Iteration   3: 13.144 ops/ms
Iteration   1: 13.262 ops/ms
Iteration   2: 13.111 ops/ms
Iteration   3: 13.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.136 ±(99.9%) 2.111 ops/ms [Average]
  (min, avg, max) = (13.034, 13.136, 13.262), stdev = 0.116
  CI (99.9%): [11.025, 15.246] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.980 ops/ms
# Warmup Iteration   2: 12.693 ops/ms
# Warmup Iteration   3: 12.912 ops/ms
Iteration   1: 12.913 ops/ms
Iteration   2: 12.960 ops/ms
Iteration   3: 12.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.892 ±(99.9%) 1.459 ops/ms [Average]
  (min, avg, max) = (12.804, 12.892, 12.960), stdev = 0.080
  CI (99.9%): [11.434, 14.351] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.345 ops/ms
# Warmup Iteration   2: 10.263 ops/ms
# Warmup Iteration   3: 10.359 ops/ms
Iteration   1: 10.448 ops/ms
Iteration   2: 10.452 ops/ms
Iteration   3: 10.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.475 ±(99.9%) 0.798 ops/ms [Average]
  (min, avg, max) = (10.448, 10.475, 10.525), stdev = 0.044
  CI (99.9%): [9.677, 11.273] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 3.997 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.579 ±(99.9%) 0.003 ms/op
Iteration   3: 2.563 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.564 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (2.551, 2.564, 2.579), stdev = 0.014
  CI (99.9%): [2.306, 2.823] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.693 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.003 ms/op
Iteration   1: 2.454 ±(99.9%) 0.004 ms/op
Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
Iteration   3: 2.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.444 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (2.429, 2.444, 2.454), stdev = 0.013
  CI (99.9%): [2.210, 2.678] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.325 ms/op [Average]
  (min, avg, max) = (2.467, 2.487, 2.499), stdev = 0.018
  CI (99.9%): [2.162, 2.812] (assumes normal distribution)


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
# Warmup Iteration   1: 4.684 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
Iteration   2: 3.054 ±(99.9%) 0.005 ms/op
Iteration   3: 3.031 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.041 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (3.031, 3.041, 3.054), stdev = 0.012
  CI (99.9%): [2.830, 3.252] (assumes normal distribution)


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  11.378 ms/op
                 createUser·p0.9999: 13.779 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 13.189 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  8.337 ms/op
                 createUser·p0.9999: 10.288 ms/op
                 createUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381204
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 182983 
    [ 2.500,  3.750) = 193742 
    [ 3.750,  5.000) = 3548 
    [ 5.000,  6.250) = 397 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     13.318 ms/op
     p(99.9990) =     14.090 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.899 ms/op
                 existUser·p0.999:  11.711 ms/op
                 existUser·p0.9999: 18.096 ms/op
                 existUser·p1.00:   18.809 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  8.213 ms/op
                 existUser·p0.9999: 12.672 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.802 ms/op
                 existUser·p0.999:  5.609 ms/op
                 existUser·p0.9999: 11.583 ms/op
                 existUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383888
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 188074 
    [ 2.500,  3.750) = 191421 
    [ 3.750,  5.000) = 3435 
    [ 5.000,  6.250) = 494 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      7.038 ms/op
     p(99.9900) =     13.815 ms/op
     p(99.9990) =     18.683 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  11.887 ms/op
                 getUser·p0.9999: 13.548 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  9.382 ms/op
                 getUser·p0.9999: 14.479 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   3: 2.573 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.634 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  8.198 ms/op
                 getUser·p0.9999: 12.290 ms/op
                 getUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376214
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 184112 
    [ 2.500,  3.750) = 186425 
    [ 3.750,  5.000) = 4061 
    [ 5.000,  6.250) = 1097 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =      8.305 ms/op
     p(99.9900) =     13.681 ms/op
     p(99.9990) =     14.664 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.783 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.009 ms/op
Iteration   1: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  8.919 ms/op
                 listUser·p0.9999: 10.572 ms/op
                 listUser·p1.00:   11.387 ms/op

Iteration   2: 3.064 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  10.229 ms/op
                 listUser·p0.9999: 12.583 ms/op
                 listUser·p1.00:   13.337 ms/op

Iteration   3: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.330 ms/op
                 listUser·p0.9999: 12.011 ms/op
                 listUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312723
  mean =      3.067 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 83353 
    [ 2.500,  3.750) = 185543 
    [ 3.750,  5.000) = 35293 
    [ 5.000,  6.250) = 6902 
    [ 6.250,  7.500) = 880 
    [ 7.500,  8.750) = 193 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.360 ms/op
     p(99.9900) =     12.239 ms/op
     p(99.9990) =     13.082 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.832 ± 3.129  ops/ms
ClientPb.existUser                       thrpt       3  13.136 ± 2.111  ops/ms
ClientPb.getUser                         thrpt       3  12.892 ± 1.459  ops/ms
ClientPb.listUser                        thrpt       3  10.475 ± 0.798  ops/ms
ClientPb.createUser                       avgt       3   2.564 ± 0.258   ms/op
ClientPb.existUser                        avgt       3   2.444 ± 0.234   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.325   ms/op
ClientPb.listUser                         avgt       3   3.041 ± 0.211   ms/op
ClientPb.createUser                     sample  381204   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.736           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.389           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.318           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.270           ms/op
ClientPb.existUser                      sample  383888   2.499 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.936           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.038           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.815           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.809           ms/op
ClientPb.getUser                        sample  376214   2.549 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.927           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.305           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.681           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.680           ms/op
ClientPb.listUser                       sample  312723   3.067 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.826           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.360           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.239           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.337           ms/op
