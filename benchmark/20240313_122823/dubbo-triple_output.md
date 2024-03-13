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
# Warmup Iteration   1: 4.866 ops/ms
# Warmup Iteration   2: 12.366 ops/ms
# Warmup Iteration   3: 12.448 ops/ms
Iteration   1: 12.700 ops/ms
Iteration   2: 12.739 ops/ms
Iteration   3: 12.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.740 ±(99.9%) 0.747 ops/ms [Average]
  (min, avg, max) = (12.700, 12.740, 12.781), stdev = 0.041
  CI (99.9%): [11.993, 13.487] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.014 ops/ms
# Warmup Iteration   2: 12.951 ops/ms
# Warmup Iteration   3: 12.990 ops/ms
Iteration   1: 13.020 ops/ms
Iteration   2: 13.148 ops/ms
Iteration   3: 13.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.088 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (13.020, 13.088, 13.148), stdev = 0.064
  CI (99.9%): [11.914, 14.263] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.493 ops/ms
# Warmup Iteration   2: 12.724 ops/ms
# Warmup Iteration   3: 12.938 ops/ms
Iteration   1: 13.001 ops/ms
Iteration   2: 12.998 ops/ms
Iteration   3: 13.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.010 ±(99.9%) 0.338 ops/ms [Average]
  (min, avg, max) = (12.998, 13.010, 13.031), stdev = 0.019
  CI (99.9%): [12.672, 13.348] (assumes normal distribution)


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
# Warmup Iteration   1: 6.264 ops/ms
# Warmup Iteration   2: 10.237 ops/ms
# Warmup Iteration   3: 10.420 ops/ms
Iteration   1: 10.483 ops/ms
Iteration   2: 10.534 ops/ms
Iteration   3: 10.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.530 ±(99.9%) 0.822 ops/ms [Average]
  (min, avg, max) = (10.483, 10.530, 10.573), stdev = 0.045
  CI (99.9%): [9.708, 11.352] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.199 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.004 ms/op
Iteration   1: 2.558 ±(99.9%) 0.004 ms/op
Iteration   2: 2.532 ±(99.9%) 0.003 ms/op
Iteration   3: 2.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.544 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (2.532, 2.544, 2.558), stdev = 0.013
  CI (99.9%): [2.309, 2.780] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.463 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (2.463, 2.472, 2.478), stdev = 0.008
  CI (99.9%): [2.323, 2.622] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.066 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.003 ms/op
Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
Iteration   3: 2.453 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.455 ±(99.9%) 0.073 ms/op [Average]
  (min, avg, max) = (2.453, 2.455, 2.460), stdev = 0.004
  CI (99.9%): [2.382, 2.528] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.755 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.005 ms/op
Iteration   1: 3.061 ±(99.9%) 0.005 ms/op
Iteration   2: 3.065 ±(99.9%) 0.005 ms/op
Iteration   3: 3.066 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.064 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (3.061, 3.064, 3.066), stdev = 0.003
  CI (99.9%): [3.016, 3.112] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.444 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  11.748 ms/op
                 createUser·p0.9999: 14.426 ms/op
                 createUser·p1.00:   15.155 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  9.486 ms/op
                 createUser·p0.9999: 12.000 ms/op
                 createUser·p1.00:   12.943 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.936 ms/op
                 createUser·p0.999:  8.720 ms/op
                 createUser·p0.9999: 12.577 ms/op
                 createUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380866
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 183918 
    [ 2.500,  3.750) = 192215 
    [ 3.750,  5.000) = 3669 
    [ 5.000,  6.250) = 479 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     14.974 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.785 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  5.968 ms/op
                 existUser·p0.9999: 13.550 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.764 ms/op
                 existUser·p0.999:  7.102 ms/op
                 existUser·p0.9999: 13.588 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  8.558 ms/op
                 existUser·p0.9999: 12.231 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386629
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 193610 
    [ 2.500,  3.750) = 189423 
    [ 3.750,  5.000) = 2649 
    [ 5.000,  6.250) = 426 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 151 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      7.313 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     14.090 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.093 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  9.107 ms/op
                 getUser·p0.9999: 13.306 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  7.157 ms/op
                 getUser·p0.9999: 13.109 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   3: 2.490 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.116 ms/op
                 getUser·p0.9999: 11.750 ms/op
                 getUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385875
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 192636 
    [ 2.500,  3.750) = 187205 
    [ 3.750,  5.000) = 4454 
    [ 5.000,  6.250) = 955 
    [ 6.250,  7.500) = 157 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.081 ms/op
     p(99.9000) =      7.128 ms/op
     p(99.9900) =     13.048 ms/op
     p(99.9990) =     13.519 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.867 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.009 ms/op
Iteration   1: 3.068 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.811 ms/op
                 listUser·p0.9999: 11.043 ms/op
                 listUser·p1.00:   13.074 ms/op

Iteration   2: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  10.420 ms/op
                 listUser·p0.9999: 11.715 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   3: 3.070 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.148 ms/op
                 listUser·p0.9999: 11.085 ms/op
                 listUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312904
  mean =      3.065 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 81020 
    [ 2.500,  3.750) = 188383 
    [ 3.750,  5.000) = 35262 
    [ 5.000,  6.250) = 6756 
    [ 6.250,  7.500) = 657 
    [ 7.500,  8.750) = 138 
    [ 8.750, 10.000) = 300 
    [10.000, 11.250) = 210 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.847 ms/op
     p(99.9900) =     11.574 ms/op
     p(99.9990) =     12.943 ms/op
     p(99.9999) =     13.074 ms/op
    p(100.0000) =     13.074 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.740 ± 0.747  ops/ms
ClientPb.existUser                       thrpt       3  13.088 ± 1.175  ops/ms
ClientPb.getUser                         thrpt       3  13.010 ± 0.338  ops/ms
ClientPb.listUser                        thrpt       3  10.530 ± 0.822  ops/ms
ClientPb.createUser                       avgt       3   2.544 ± 0.235   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.149   ms/op
ClientPb.getUser                          avgt       3   2.455 ± 0.073   ms/op
ClientPb.listUser                         avgt       3   3.064 ± 0.048   ms/op
ClientPb.createUser                     sample  380866   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.777           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.372           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.599           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.155           ms/op
ClientPb.existUser                      sample  386629   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.738           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.313           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.451           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.746           ms/op
ClientPb.getUser                        sample  385875   2.486 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.680           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.081           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.128           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.048           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.959           ms/op
ClientPb.listUser                       sample  312904   3.065 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.930           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.847           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.574           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.074           ms/op
