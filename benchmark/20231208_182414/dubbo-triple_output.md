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
# Warmup Iteration   1: 4.963 ops/ms
# Warmup Iteration   2: 12.258 ops/ms
# Warmup Iteration   3: 12.523 ops/ms
Iteration   1: 12.709 ops/ms
Iteration   2: 12.979 ops/ms
Iteration   3: 12.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.824 ±(99.9%) 2.538 ops/ms [Average]
  (min, avg, max) = (12.709, 12.824, 12.979), stdev = 0.139
  CI (99.9%): [10.285, 15.362] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.359 ops/ms
# Warmup Iteration   2: 13.143 ops/ms
# Warmup Iteration   3: 13.125 ops/ms
Iteration   1: 13.086 ops/ms
Iteration   2: 13.166 ops/ms
Iteration   3: 13.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.137 ±(99.9%) 0.803 ops/ms [Average]
  (min, avg, max) = (13.086, 13.137, 13.166), stdev = 0.044
  CI (99.9%): [12.334, 13.940] (assumes normal distribution)


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
# Warmup Iteration   1: 7.922 ops/ms
# Warmup Iteration   2: 12.603 ops/ms
# Warmup Iteration   3: 12.830 ops/ms
Iteration   1: 12.769 ops/ms
Iteration   2: 13.040 ops/ms
Iteration   3: 13.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.954 ±(99.9%) 2.923 ops/ms [Average]
  (min, avg, max) = (12.769, 12.954, 13.053), stdev = 0.160
  CI (99.9%): [10.031, 15.877] (assumes normal distribution)


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
# Warmup Iteration   1: 6.515 ops/ms
# Warmup Iteration   2: 10.489 ops/ms
# Warmup Iteration   3: 10.676 ops/ms
Iteration   1: 10.696 ops/ms
Iteration   2: 10.703 ops/ms
Iteration   3: 10.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.711 ±(99.9%) 0.378 ops/ms [Average]
  (min, avg, max) = (10.696, 10.711, 10.735), stdev = 0.021
  CI (99.9%): [10.334, 11.089] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.515 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (2.497, 2.515, 2.526), stdev = 0.015
  CI (99.9%): [2.237, 2.792] (assumes normal distribution)


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.003 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.469 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.448, 2.469, 2.480), stdev = 0.018
  CI (99.9%): [2.147, 2.791] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.004 ms/op
Iteration   1: 2.493 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.498 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.493, 2.498, 2.502), stdev = 0.004
  CI (99.9%): [2.416, 2.579] (assumes normal distribution)


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
# Warmup Iteration   1: 4.594 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.005 ms/op
Iteration   1: 2.981 ±(99.9%) 0.004 ms/op
Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
Iteration   3: 3.012 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.989 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (2.974, 2.989, 3.012), stdev = 0.020
  CI (99.9%): [2.622, 3.356] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.536 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  11.742 ms/op
                 createUser·p0.9999: 14.090 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  9.540 ms/op
                 createUser·p0.9999: 12.606 ms/op
                 createUser·p1.00:   13.271 ms/op

Iteration   3: 2.586 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.351 ms/op
                 createUser·p0.99:   4.258 ms/op
                 createUser·p0.999:  9.230 ms/op
                 createUser·p0.9999: 11.943 ms/op
                 createUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375598
  mean =      2.554 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 179045 
    [ 2.500,  3.750) = 191305 
    [ 3.750,  5.000) = 4270 
    [ 5.000,  6.250) = 486 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     13.375 ms/op
     p(99.9990) =     14.197 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  9.543 ms/op
                 existUser·p0.9999: 15.291 ms/op
                 existUser·p1.00:   16.581 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  8.289 ms/op
                 existUser·p0.9999: 14.459 ms/op
                 existUser·p1.00:   16.286 ms/op

Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 13.320 ms/op
                 existUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385100
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 191970 
    [ 2.500,  3.750) = 188351 
    [ 3.750,  5.000) = 3626 
    [ 5.000,  6.250) = 667 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 125 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      7.943 ms/op
     p(99.9900) =     14.229 ms/op
     p(99.9990) =     16.237 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.006 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  5.988 ms/op
                 getUser·p0.9999: 13.877 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  6.997 ms/op
                 getUser·p0.9999: 12.845 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.108 ms/op
                 getUser·p0.999:  8.670 ms/op
                 getUser·p0.9999: 10.832 ms/op
                 getUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387770
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 194081 
    [ 2.500,  3.750) = 188548 
    [ 3.750,  5.000) = 4177 
    [ 5.000,  6.250) = 432 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      8.386 ms/op
     p(99.9900) =     13.455 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 4.879 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.009 ms/op
Iteration   1: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.806 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  10.125 ms/op
                 listUser·p0.9999: 11.082 ms/op
                 listUser·p1.00:   12.124 ms/op

Iteration   2: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.527 ms/op
                 listUser·p0.999:  9.978 ms/op
                 listUser·p0.9999: 13.244 ms/op
                 listUser·p1.00:   13.697 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.349 ms/op
                 listUser·p0.999:  10.502 ms/op
                 listUser·p0.9999: 12.272 ms/op
                 listUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320119
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 93145 
    [ 2.500,  3.750) = 189187 
    [ 3.750,  5.000) = 30833 
    [ 5.000,  6.250) = 5566 
    [ 6.250,  7.500) = 551 
    [ 7.500,  8.750) = 149 
    [ 8.750, 10.000) = 199 
    [10.000, 11.250) = 272 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     10.156 ms/op
     p(99.9900) =     12.320 ms/op
     p(99.9990) =     13.671 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.824 ± 2.538  ops/ms
ClientPb.existUser                       thrpt       3  13.137 ± 0.803  ops/ms
ClientPb.getUser                         thrpt       3  12.954 ± 2.923  ops/ms
ClientPb.listUser                        thrpt       3  10.711 ± 0.378  ops/ms
ClientPb.createUser                       avgt       3   2.515 ± 0.277   ms/op
ClientPb.existUser                        avgt       3   2.469 ± 0.322   ms/op
ClientPb.getUser                          avgt       3   2.498 ± 0.081   ms/op
ClientPb.listUser                         avgt       3   2.989 ± 0.367   ms/op
ClientPb.createUser                     sample  375598   2.554 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.791           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.290           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.375           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.434           ms/op
ClientPb.existUser                      sample  385100   2.490 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.888           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.943           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.229           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.581           ms/op
ClientPb.getUser                        sample  387770   2.473 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.831           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.386           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.455           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.336           ms/op
ClientPb.listUser                       sample  320119   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.806           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.156           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.320           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.697           ms/op
