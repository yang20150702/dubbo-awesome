# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.173 ops/ms
# Warmup Iteration   2: 12.255 ops/ms
# Warmup Iteration   3: 12.312 ops/ms
Iteration   1: 12.556 ops/ms
Iteration   2: 12.486 ops/ms
Iteration   3: 12.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.560 ±(99.9%) 1.385 ops/ms [Average]
  (min, avg, max) = (12.486, 12.560, 12.637), stdev = 0.076
  CI (99.9%): [11.175, 13.945] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.585 ops/ms
# Warmup Iteration   2: 12.901 ops/ms
# Warmup Iteration   3: 12.969 ops/ms
Iteration   1: 13.002 ops/ms
Iteration   2: 13.066 ops/ms
Iteration   3: 13.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.037 ±(99.9%) 0.589 ops/ms [Average]
  (min, avg, max) = (13.002, 13.037, 13.066), stdev = 0.032
  CI (99.9%): [12.448, 13.626] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.566 ops/ms
# Warmup Iteration   2: 12.334 ops/ms
# Warmup Iteration   3: 12.505 ops/ms
Iteration   1: 12.627 ops/ms
Iteration   2: 12.681 ops/ms
Iteration   3: 12.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.584 ±(99.9%) 2.258 ops/ms [Average]
  (min, avg, max) = (12.445, 12.584, 12.681), stdev = 0.124
  CI (99.9%): [10.326, 14.842] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.667 ops/ms
# Warmup Iteration   2: 10.213 ops/ms
# Warmup Iteration   3: 10.457 ops/ms
Iteration   1: 10.354 ops/ms
Iteration   2: 10.343 ops/ms
Iteration   3: 10.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.354 ±(99.9%) 0.184 ops/ms [Average]
  (min, avg, max) = (10.343, 10.354, 10.364), stdev = 0.010
  CI (99.9%): [10.170, 10.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.164 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.686 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.004 ms/op
Iteration   1: 2.555 ±(99.9%) 0.003 ms/op
Iteration   2: 2.566 ±(99.9%) 0.003 ms/op
Iteration   3: 2.559 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.560 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.555, 2.560, 2.566), stdev = 0.005
  CI (99.9%): [2.460, 2.660] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.717 ±(99.9%) 0.007 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.496 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
Iteration   3: 2.514 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.502 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (2.495, 2.502, 2.514), stdev = 0.011
  CI (99.9%): [2.300, 2.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.946 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.005 ms/op
Iteration   1: 2.545 ±(99.9%) 0.005 ms/op
Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
Iteration   3: 2.546 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.551 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (2.545, 2.551, 2.562), stdev = 0.009
  CI (99.9%): [2.381, 2.721] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.893 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.005 ms/op
Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
Iteration   3: 3.074 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.082 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (3.074, 3.082, 3.087), stdev = 0.007
  CI (99.9%): [2.950, 3.215] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.392 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.693 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
Iteration   1: 2.556 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.551 ms/op
                 createUser·p0.999:  12.353 ms/op
                 createUser·p0.9999: 22.233 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  8.322 ms/op
                 createUser·p0.9999: 11.134 ms/op
                 createUser·p1.00:   11.256 ms/op

Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.763 ms/op
                 createUser·p0.999:  8.126 ms/op
                 createUser·p0.9999: 10.568 ms/op
                 createUser·p1.00:   10.781 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374207
  mean =      2.563 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 179432 
    [ 2.500,  5.000) = 193803 
    [ 5.000,  7.500) = 549 
    [ 7.500, 10.000) = 187 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.909 ms/op
     p(99.9900) =     13.995 ms/op
     p(99.9990) =     22.323 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.923 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  8.813 ms/op
                 existUser·p0.9999: 13.733 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.826 ms/op
                 existUser·p0.999:  8.476 ms/op
                 existUser·p0.9999: 13.180 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  8.051 ms/op
                 existUser·p0.9999: 11.621 ms/op
                 existUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383362
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 185818 
    [ 2.500,  3.750) = 193309 
    [ 3.750,  5.000) = 2893 
    [ 5.000,  6.250) = 788 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.050 ms/op
     p(99.9900) =     13.457 ms/op
     p(99.9990) =     14.421 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.312 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.537 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.092 ms/op
                 getUser·p0.999:  11.993 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  8.705 ms/op
                 getUser·p0.9999: 17.022 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  8.146 ms/op
                 getUser·p0.9999: 12.386 ms/op
                 getUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380150
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 185837 
    [ 2.500,  3.750) = 189225 
    [ 3.750,  5.000) = 4144 
    [ 5.000,  6.250) = 458 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      8.564 ms/op
     p(99.9900) =     14.123 ms/op
     p(99.9990) =     17.878 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.853 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.009 ms/op
Iteration   1: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.055 ms/op
                 listUser·p0.9999: 13.107 ms/op
                 listUser·p1.00:   13.664 ms/op

Iteration   2: 3.062 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.740 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 10.893 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   3: 3.070 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 10.905 ms/op
                 listUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312906
  mean =      3.066 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 82134 
    [ 2.500,  3.750) = 187234 
    [ 3.750,  5.000) = 35566 
    [ 5.000,  6.250) = 6292 
    [ 6.250,  7.500) = 919 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 275 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.324 ms/op
     p(99.9900) =     11.272 ms/op
     p(99.9990) =     13.533 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.560 ± 1.385  ops/ms
ClientPb.existUser                       thrpt       3  13.037 ± 0.589  ops/ms
ClientPb.getUser                         thrpt       3  12.584 ± 2.258  ops/ms
ClientPb.listUser                        thrpt       3  10.354 ± 0.184  ops/ms
ClientPb.createUser                       avgt       3   2.560 ± 0.100   ms/op
ClientPb.existUser                        avgt       3   2.502 ± 0.201   ms/op
ClientPb.getUser                          avgt       3   2.551 ± 0.170   ms/op
ClientPb.listUser                         avgt       3   3.082 ± 0.133   ms/op
ClientPb.createUser                     sample  374207   2.563 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.000           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.909           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.995           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.446           ms/op
ClientPb.existUser                      sample  383362   2.501 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.926           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.050           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.457           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.598           ms/op
ClientPb.getUser                        sample  380150   2.523 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.643           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.564           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.123           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.514           ms/op
ClientPb.listUser                       sample  312906   3.066 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.740           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.324           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.272           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.664           ms/op
