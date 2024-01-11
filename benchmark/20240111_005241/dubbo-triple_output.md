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
# Warmup Iteration   1: 4.511 ops/ms
# Warmup Iteration   2: 12.091 ops/ms
# Warmup Iteration   3: 12.330 ops/ms
Iteration   1: 12.474 ops/ms
Iteration   2: 12.372 ops/ms
Iteration   3: 12.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.456 ±(99.9%) 1.413 ops/ms [Average]
  (min, avg, max) = (12.372, 12.456, 12.523), stdev = 0.077
  CI (99.9%): [11.044, 13.869] (assumes normal distribution)


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
# Warmup Iteration   1: 8.135 ops/ms
# Warmup Iteration   2: 13.169 ops/ms
# Warmup Iteration   3: 12.957 ops/ms
Iteration   1: 13.147 ops/ms
Iteration   2: 12.993 ops/ms
Iteration   3: 13.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.064 ±(99.9%) 1.423 ops/ms [Average]
  (min, avg, max) = (12.993, 13.064, 13.147), stdev = 0.078
  CI (99.9%): [11.640, 14.487] (assumes normal distribution)


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
# Warmup Iteration   1: 7.510 ops/ms
# Warmup Iteration   2: 12.815 ops/ms
# Warmup Iteration   3: 12.932 ops/ms
Iteration   1: 12.941 ops/ms
Iteration   2: 13.287 ops/ms
Iteration   3: 13.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.128 ±(99.9%) 3.189 ops/ms [Average]
  (min, avg, max) = (12.941, 13.128, 13.287), stdev = 0.175
  CI (99.9%): [9.939, 16.317] (assumes normal distribution)


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
# Warmup Iteration   1: 6.815 ops/ms
# Warmup Iteration   2: 10.211 ops/ms
# Warmup Iteration   3: 10.506 ops/ms
Iteration   1: 10.448 ops/ms
Iteration   2: 10.479 ops/ms
Iteration   3: 10.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.468 ±(99.9%) 0.311 ops/ms [Average]
  (min, avg, max) = (10.448, 10.468, 10.479), stdev = 0.017
  CI (99.9%): [10.157, 10.779] (assumes normal distribution)


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.004 ms/op
Iteration   1: 2.566 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.532 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (2.503, 2.532, 2.566), stdev = 0.032
  CI (99.9%): [1.956, 3.108] (assumes normal distribution)


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.003 ms/op
Iteration   1: 2.446 ±(99.9%) 0.004 ms/op
Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.447 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.436, 2.447, 2.460), stdev = 0.012
  CI (99.9%): [2.227, 2.668] (assumes normal distribution)


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.002 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.500, 2.518, 2.528), stdev = 0.016
  CI (99.9%): [2.227, 2.809] (assumes normal distribution)


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
# Warmup Iteration   1: 4.692 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.007 ms/op
Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
Iteration   3: 3.010 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.017 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (3.010, 3.017, 3.029), stdev = 0.011
  CI (99.9%): [2.825, 3.208] (assumes normal distribution)


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
# Warmup Iteration   1: 4.198 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.683 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.560 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.560 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  12.171 ms/op
                 createUser·p0.9999: 13.935 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  10.142 ms/op
                 createUser·p0.9999: 13.211 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  8.386 ms/op
                 createUser·p0.9999: 12.239 ms/op
                 createUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378161
  mean =      2.536 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 181404 
    [ 2.500,  3.750) = 192806 
    [ 3.750,  5.000) = 3097 
    [ 5.000,  6.250) = 364 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 123 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     13.536 ms/op
     p(99.9990) =     14.157 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.048 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
Iteration   1: 2.520 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 14.169 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  6.210 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  7.381 ms/op
                 existUser·p0.9999: 11.682 ms/op
                 existUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384806
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 188503 
    [ 2.500,  3.750) = 192072 
    [ 3.750,  5.000) = 3254 
    [ 5.000,  6.250) = 408 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     13.394 ms/op
     p(99.9990) =     15.226 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.997 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  6.201 ms/op
                 getUser·p0.9999: 14.352 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  9.495 ms/op
                 getUser·p0.9999: 14.156 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.913 ms/op
                 getUser·p0.9999: 13.091 ms/op
                 getUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385058
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 191937 
    [ 2.500,  3.750) = 187576 
    [ 3.750,  5.000) = 4626 
    [ 5.000,  6.250) = 367 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      8.895 ms/op
     p(99.9900) =     14.123 ms/op
     p(99.9990) =     14.782 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.008 ms/op
Iteration   1: 3.059 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 11.838 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.581 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 12.490 ms/op
                 listUser·p1.00:   13.533 ms/op

Iteration   3: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  10.486 ms/op
                 listUser·p0.9999: 12.777 ms/op
                 listUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315249
  mean =      3.043 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 83813 
    [ 2.500,  3.750) = 190974 
    [ 3.750,  5.000) = 34010 
    [ 5.000,  6.250) = 5102 
    [ 6.250,  7.500) = 521 
    [ 7.500,  8.750) = 210 
    [ 8.750, 10.000) = 210 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.564 ms/op
     p(99.9900) =     12.403 ms/op
     p(99.9990) =     13.479 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.456 ± 1.413  ops/ms
ClientPb.existUser                       thrpt       3  13.064 ± 1.423  ops/ms
ClientPb.getUser                         thrpt       3  13.128 ± 3.189  ops/ms
ClientPb.listUser                        thrpt       3  10.468 ± 0.311  ops/ms
ClientPb.createUser                       avgt       3   2.532 ± 0.576   ms/op
ClientPb.existUser                        avgt       3   2.447 ± 0.220   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.291   ms/op
ClientPb.listUser                         avgt       3   3.017 ± 0.192   ms/op
ClientPb.createUser                     sample  378161   2.536 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.560           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.471           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.536           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.106           ms/op
ClientPb.existUser                      sample  384806   2.492 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.757           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.044           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.394           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.352           ms/op
ClientPb.getUser                        sample  385058   2.491 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.678           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.895           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.123           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.122           ms/op
ClientPb.listUser                       sample  315249   3.043 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.564           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.403           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.533           ms/op
