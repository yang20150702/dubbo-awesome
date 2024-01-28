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
# Warmup Iteration   1: 4.773 ops/ms
# Warmup Iteration   2: 11.877 ops/ms
# Warmup Iteration   3: 11.909 ops/ms
Iteration   1: 12.324 ops/ms
Iteration   2: 12.349 ops/ms
Iteration   3: 12.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.380 ±(99.9%) 1.403 ops/ms [Average]
  (min, avg, max) = (12.324, 12.380, 12.468), stdev = 0.077
  CI (99.9%): [10.977, 13.783] (assumes normal distribution)


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
# Warmup Iteration   1: 8.167 ops/ms
# Warmup Iteration   2: 12.933 ops/ms
# Warmup Iteration   3: 13.178 ops/ms
Iteration   1: 13.170 ops/ms
Iteration   2: 13.025 ops/ms
Iteration   3: 13.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.074 ±(99.9%) 1.529 ops/ms [Average]
  (min, avg, max) = (13.025, 13.074, 13.170), stdev = 0.084
  CI (99.9%): [11.544, 14.603] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.719 ops/ms
# Warmup Iteration   2: 12.390 ops/ms
# Warmup Iteration   3: 12.673 ops/ms
Iteration   1: 12.563 ops/ms
Iteration   2: 12.753 ops/ms
Iteration   3: 12.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.700 ±(99.9%) 2.175 ops/ms [Average]
  (min, avg, max) = (12.563, 12.700, 12.783), stdev = 0.119
  CI (99.9%): [10.524, 14.875] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.362 ops/ms
# Warmup Iteration   2: 10.516 ops/ms
# Warmup Iteration   3: 10.662 ops/ms
Iteration   1: 10.683 ops/ms
Iteration   2: 10.604 ops/ms
Iteration   3: 10.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.633 ±(99.9%) 0.786 ops/ms [Average]
  (min, avg, max) = (10.604, 10.633, 10.683), stdev = 0.043
  CI (99.9%): [9.847, 11.419] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.057 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.004 ms/op
Iteration   1: 2.567 ±(99.9%) 0.004 ms/op
Iteration   2: 2.591 ±(99.9%) 0.004 ms/op
Iteration   3: 2.558 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.572 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (2.558, 2.572, 2.591), stdev = 0.017
  CI (99.9%): [2.262, 2.882] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.626 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.004 ms/op
Iteration   1: 2.417 ±(99.9%) 0.004 ms/op
Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
Iteration   3: 2.428 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.430 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.417, 2.430, 2.444), stdev = 0.014
  CI (99.9%): [2.179, 2.680] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.749 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.483 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (2.478, 2.483, 2.492), stdev = 0.008
  CI (99.9%): [2.332, 2.633] (assumes normal distribution)


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
# Warmup Iteration   1: 4.567 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.004 ms/op
Iteration   1: 3.044 ±(99.9%) 0.005 ms/op
Iteration   2: 3.036 ±(99.9%) 0.005 ms/op
Iteration   3: 3.024 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.035 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.024, 3.035, 3.044), stdev = 0.010
  CI (99.9%): [2.858, 3.212] (assumes normal distribution)


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
# Warmup Iteration   1: 4.219 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  11.536 ms/op
                 createUser·p0.9999: 13.307 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  5.868 ms/op
                 createUser·p0.9999: 13.074 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  8.045 ms/op
                 createUser·p0.9999: 10.524 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385056
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 187874 
    [ 2.500,  3.750) = 193742 
    [ 3.750,  5.000) = 2637 
    [ 5.000,  6.250) = 275 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      8.044 ms/op
     p(99.9900) =     13.164 ms/op
     p(99.9990) =     13.770 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   4.077 ms/op
                 existUser·p0.999:  8.509 ms/op
                 existUser·p0.9999: 14.042 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  6.886 ms/op
                 existUser·p0.9999: 12.760 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  7.897 ms/op
                 existUser·p0.9999: 12.438 ms/op
                 existUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389677
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 195081 
    [ 2.500,  3.750) = 189929 
    [ 3.750,  5.000) = 3527 
    [ 5.000,  6.250) = 589 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      8.323 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.259 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  11.228 ms/op
                 getUser·p0.9999: 14.097 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  10.100 ms/op
                 getUser·p0.9999: 12.343 ms/op
                 getUser·p1.00:   12.730 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  8.676 ms/op
                 getUser·p0.9999: 14.558 ms/op
                 getUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381184
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 188315 
    [ 2.500,  3.750) = 188144 
    [ 3.750,  5.000) = 3341 
    [ 5.000,  6.250) = 828 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 139 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      8.861 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.914 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.009 ms/op
Iteration   1: 3.062 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.782 ms/op
                 listUser·p0.9999: 10.036 ms/op
                 listUser·p1.00:   12.222 ms/op

Iteration   2: 3.076 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.390 ms/op
                 listUser·p0.9999: 11.333 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   3: 3.086 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.903 ms/op
                 listUser·p0.9999: 11.588 ms/op
                 listUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311919
  mean =      3.075 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 79583 
    [ 2.500,  3.750) = 189572 
    [ 3.750,  5.000) = 35234 
    [ 5.000,  6.250) = 6227 
    [ 6.250,  7.500) = 597 
    [ 7.500,  8.750) = 235 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.335 ms/op
     p(99.9990) =     12.158 ms/op
     p(99.9999) =     12.222 ms/op
    p(100.0000) =     12.222 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.380 ± 1.403  ops/ms
ClientPb.existUser                       thrpt       3  13.074 ± 1.529  ops/ms
ClientPb.getUser                         thrpt       3  12.700 ± 2.175  ops/ms
ClientPb.listUser                        thrpt       3  10.633 ± 0.786  ops/ms
ClientPb.createUser                       avgt       3   2.572 ± 0.310   ms/op
ClientPb.existUser                        avgt       3   2.430 ± 0.251   ms/op
ClientPb.getUser                          avgt       3   2.483 ± 0.151   ms/op
ClientPb.listUser                         avgt       3   3.035 ± 0.177   ms/op
ClientPb.createUser                     sample  385056   2.490 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.882           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.044           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.164           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.645           ms/op
ClientPb.existUser                      sample  389677   2.462 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.752           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.323           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.435           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.762           ms/op
ClientPb.getUser                        sample  381184   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.648           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.861           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.779           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.926           ms/op
ClientPb.listUser                       sample  311919   3.075 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.950           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.335           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.222           ms/op
