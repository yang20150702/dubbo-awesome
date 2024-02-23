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
# Warmup Iteration   1: 5.449 ops/ms
# Warmup Iteration   2: 12.066 ops/ms
# Warmup Iteration   3: 12.463 ops/ms
Iteration   1: 12.543 ops/ms
Iteration   2: 12.732 ops/ms
Iteration   3: 12.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.612 ±(99.9%) 1.905 ops/ms [Average]
  (min, avg, max) = (12.543, 12.612, 12.732), stdev = 0.104
  CI (99.9%): [10.707, 14.517] (assumes normal distribution)


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
# Warmup Iteration   1: 7.830 ops/ms
# Warmup Iteration   2: 12.666 ops/ms
# Warmup Iteration   3: 12.816 ops/ms
Iteration   1: 12.820 ops/ms
Iteration   2: 12.795 ops/ms
Iteration   3: 12.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.789 ±(99.9%) 0.645 ops/ms [Average]
  (min, avg, max) = (12.750, 12.789, 12.820), stdev = 0.035
  CI (99.9%): [12.144, 13.433] (assumes normal distribution)


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
# Warmup Iteration   1: 7.721 ops/ms
# Warmup Iteration   2: 12.539 ops/ms
# Warmup Iteration   3: 12.655 ops/ms
Iteration   1: 12.724 ops/ms
Iteration   2: 12.731 ops/ms
Iteration   3: 12.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.692 ±(99.9%) 1.123 ops/ms [Average]
  (min, avg, max) = (12.622, 12.692, 12.731), stdev = 0.062
  CI (99.9%): [11.570, 13.815] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.563 ops/ms
# Warmup Iteration   2: 10.410 ops/ms
# Warmup Iteration   3: 10.592 ops/ms
Iteration   1: 10.555 ops/ms
Iteration   2: 10.569 ops/ms
Iteration   3: 10.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.574 ±(99.9%) 0.399 ops/ms [Average]
  (min, avg, max) = (10.555, 10.574, 10.598), stdev = 0.022
  CI (99.9%): [10.175, 10.973] (assumes normal distribution)


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.003 ms/op
Iteration   1: 2.499 ±(99.9%) 0.004 ms/op
Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.496 ±(99.9%) 0.378 ms/op [Average]
  (min, avg, max) = (2.474, 2.496, 2.515), stdev = 0.021
  CI (99.9%): [2.118, 2.874] (assumes normal distribution)


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
# Warmup Iteration   1: 3.675 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.438 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.454 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (2.438, 2.454, 2.481), stdev = 0.023
  CI (99.9%): [2.033, 2.876] (assumes normal distribution)


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
# Warmup Iteration   1: 3.861 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.513 ±(99.9%) 0.005 ms/op
Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.513 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.506, 2.513, 2.520), stdev = 0.007
  CI (99.9%): [2.387, 2.639] (assumes normal distribution)


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
# Warmup Iteration   1: 4.543 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
Iteration   1: 2.958 ±(99.9%) 0.006 ms/op
Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
Iteration   3: 2.985 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.972 ±(99.9%) 0.248 ms/op [Average]
  (min, avg, max) = (2.958, 2.972, 2.985), stdev = 0.014
  CI (99.9%): [2.723, 3.220] (assumes normal distribution)


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.679 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.558 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  11.994 ms/op
                 createUser·p0.9999: 13.592 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  9.372 ms/op
                 createUser·p0.9999: 12.427 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 2.591 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 11.272 ms/op
                 createUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373350
  mean =      2.569 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 177393 
    [ 2.500,  3.750) = 191183 
    [ 3.750,  5.000) = 3615 
    [ 5.000,  6.250) = 605 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      9.005 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     14.072 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.647 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  8.786 ms/op
                 existUser·p0.9999: 15.848 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  6.545 ms/op
                 existUser·p0.9999: 12.173 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  6.619 ms/op
                 existUser·p0.9999: 12.157 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388348
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 190417 
    [ 2.500,  3.750) = 195402 
    [ 3.750,  5.000) = 1915 
    [ 5.000,  6.250) = 192 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.502 ms/op
     p(99.9000) =      6.534 ms/op
     p(99.9900) =     13.918 ms/op
     p(99.9990) =     17.174 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.540 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  11.014 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  9.004 ms/op
                 getUser·p0.9999: 12.817 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   3: 2.566 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   3.973 ms/op
                 getUser·p0.999:  8.719 ms/op
                 getUser·p0.9999: 11.437 ms/op
                 getUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376181
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 181814 
    [ 2.500,  3.750) = 188396 
    [ 3.750,  5.000) = 4658 
    [ 5.000,  6.250) = 806 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      9.041 ms/op
     p(99.9900) =     13.349 ms/op
     p(99.9990) =     14.093 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 4.719 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.009 ms/op
Iteration   1: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.731 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.841 ms/op
                 listUser·p0.999:  8.787 ms/op
                 listUser·p0.9999: 11.567 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   2: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.568 ms/op
                 listUser·p0.999:  9.815 ms/op
                 listUser·p0.9999: 11.105 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   3: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.039 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  10.125 ms/op
                 listUser·p0.9999: 14.549 ms/op
                 listUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315618
  mean =      3.039 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 87803 
    [ 2.500,  3.750) = 186483 
    [ 3.750,  5.000) = 33344 
    [ 5.000,  6.250) = 6257 
    [ 6.250,  7.500) = 884 
    [ 7.500,  8.750) = 274 
    [ 8.750, 10.000) = 218 
    [10.000, 11.250) = 184 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.525 ms/op
     p(99.9900) =     12.821 ms/op
     p(99.9990) =     15.033 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.612 ± 1.905  ops/ms
ClientPb.existUser                       thrpt       3  12.789 ± 0.645  ops/ms
ClientPb.getUser                         thrpt       3  12.692 ± 1.123  ops/ms
ClientPb.listUser                        thrpt       3  10.574 ± 0.399  ops/ms
ClientPb.createUser                       avgt       3   2.496 ± 0.378   ms/op
ClientPb.existUser                        avgt       3   2.454 ± 0.422   ms/op
ClientPb.getUser                          avgt       3   2.513 ± 0.126   ms/op
ClientPb.listUser                         avgt       3   2.972 ± 0.248   ms/op
ClientPb.createUser                     sample  373350   2.569 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.834           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.005           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.189           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.189           ms/op
ClientPb.existUser                      sample  388348   2.470 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.822           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.534           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.918           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.367           ms/op
ClientPb.getUser                        sample  376181   2.550 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.958           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.589           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.041           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.349           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.500           ms/op
ClientPb.listUser                       sample  315618   3.039 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.525           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.821           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.237           ms/op
