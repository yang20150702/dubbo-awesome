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
# Warmup Iteration   1: 4.647 ops/ms
# Warmup Iteration   2: 11.967 ops/ms
# Warmup Iteration   3: 12.432 ops/ms
Iteration   1: 12.662 ops/ms
Iteration   2: 12.737 ops/ms
Iteration   3: 12.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.745 ±(99.9%) 1.576 ops/ms [Average]
  (min, avg, max) = (12.662, 12.745, 12.835), stdev = 0.086
  CI (99.9%): [11.169, 14.321] (assumes normal distribution)


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
# Warmup Iteration   1: 8.655 ops/ms
# Warmup Iteration   2: 12.851 ops/ms
# Warmup Iteration   3: 12.956 ops/ms
Iteration   1: 12.681 ops/ms
Iteration   2: 12.621 ops/ms
Iteration   3: 12.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.666 ±(99.9%) 0.715 ops/ms [Average]
  (min, avg, max) = (12.621, 12.666, 12.695), stdev = 0.039
  CI (99.9%): [11.951, 13.381] (assumes normal distribution)


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
# Warmup Iteration   1: 7.821 ops/ms
# Warmup Iteration   2: 12.498 ops/ms
# Warmup Iteration   3: 12.735 ops/ms
Iteration   1: 12.842 ops/ms
Iteration   2: 12.955 ops/ms
Iteration   3: 12.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.906 ±(99.9%) 1.064 ops/ms [Average]
  (min, avg, max) = (12.842, 12.906, 12.955), stdev = 0.058
  CI (99.9%): [11.843, 13.970] (assumes normal distribution)


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
# Warmup Iteration   1: 6.619 ops/ms
# Warmup Iteration   2: 10.502 ops/ms
# Warmup Iteration   3: 10.571 ops/ms
Iteration   1: 10.474 ops/ms
Iteration   2: 10.622 ops/ms
Iteration   3: 10.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.606 ±(99.9%) 2.267 ops/ms [Average]
  (min, avg, max) = (10.474, 10.606, 10.721), stdev = 0.124
  CI (99.9%): [8.339, 12.872] (assumes normal distribution)


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.586 ±(99.9%) 0.006 ms/op
Iteration   1: 2.605 ±(99.9%) 0.004 ms/op
Iteration   2: 2.648 ±(99.9%) 0.004 ms/op
Iteration   3: 2.587 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.613 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (2.587, 2.613, 2.648), stdev = 0.031
  CI (99.9%): [2.041, 3.185] (assumes normal distribution)


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.003 ms/op
Iteration   1: 2.463 ±(99.9%) 0.004 ms/op
Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.459 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.458, 2.459, 2.463), stdev = 0.003
  CI (99.9%): [2.404, 2.515] (assumes normal distribution)


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.580 ±(99.9%) 0.003 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.003 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.516 ±(99.9%) 0.543 ms/op [Average]
  (min, avg, max) = (2.496, 2.516, 2.551), stdev = 0.030
  CI (99.9%): [1.973, 3.059] (assumes normal distribution)


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
# Warmup Iteration   1: 4.809 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.005 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
Iteration   3: 3.023 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.025 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (3.015, 3.025, 3.035), stdev = 0.010
  CI (99.9%): [2.841, 3.209] (assumes normal distribution)


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.730 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.713 ms/op
                 createUser·p0.999:  11.960 ms/op
                 createUser·p0.9999: 14.410 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  9.994 ms/op
                 createUser·p0.9999: 12.927 ms/op
                 createUser·p1.00:   13.304 ms/op

Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   4.047 ms/op
                 createUser·p0.999:  9.170 ms/op
                 createUser·p0.9999: 14.979 ms/op
                 createUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381772
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 186130 
    [ 2.500,  3.750) = 191243 
    [ 3.750,  5.000) = 3424 
    [ 5.000,  6.250) = 383 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 147 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      9.261 ms/op
     p(99.9900) =     13.956 ms/op
     p(99.9990) =     15.128 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 19.173 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.803 ms/op
                 existUser·p0.999:  10.732 ms/op
                 existUser·p0.9999: 14.258 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.092 ms/op
                 existUser·p0.95:   3.244 ms/op
                 existUser·p0.99:   4.038 ms/op
                 existUser·p0.999:  6.850 ms/op
                 existUser·p0.9999: 13.458 ms/op
                 existUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382588
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 186631 
    [ 2.500,  3.750) = 191175 
    [ 3.750,  5.000) = 3648 
    [ 5.000,  6.250) = 592 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 129 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      7.348 ms/op
     p(99.9900) =     14.752 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  13.304 ms/op
                 getUser·p0.9999: 18.097 ms/op
                 getUser·p1.00:   18.711 ms/op

Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  12.149 ms/op
                 getUser·p0.9999: 14.755 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.051 ms/op
                 getUser·p0.999:  11.010 ms/op
                 getUser·p0.9999: 13.697 ms/op
                 getUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380923
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 188893 
    [ 2.500,  3.750) = 186529 
    [ 3.750,  5.000) = 4183 
    [ 5.000,  6.250) = 754 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 128 
    [13.750, 15.000) = 145 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =     11.029 ms/op
     p(99.9900) =     15.498 ms/op
     p(99.9990) =     18.559 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.976 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.009 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  10.677 ms/op
                 listUser·p0.9999: 12.157 ms/op
                 listUser·p1.00:   13.091 ms/op

Iteration   2: 2.961 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.728 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.516 ms/op
                 listUser·p0.999:  10.306 ms/op
                 listUser·p0.9999: 12.065 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   3: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.399 ms/op
                 listUser·p0.9999: 10.732 ms/op
                 listUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322567
  mean =      2.973 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 101044 
    [ 2.500,  3.750) = 183952 
    [ 3.750,  5.000) = 30418 
    [ 5.000,  6.250) = 5617 
    [ 6.250,  7.500) = 741 
    [ 7.500,  8.750) = 151 
    [ 8.750, 10.000) = 166 
    [10.000, 11.250) = 247 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     10.076 ms/op
     p(99.9900) =     12.038 ms/op
     p(99.9990) =     13.008 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.745 ± 1.576  ops/ms
ClientPb.existUser                       thrpt       3  12.666 ± 0.715  ops/ms
ClientPb.getUser                         thrpt       3  12.906 ± 1.064  ops/ms
ClientPb.listUser                        thrpt       3  10.606 ± 2.267  ops/ms
ClientPb.createUser                       avgt       3   2.613 ± 0.572   ms/op
ClientPb.existUser                        avgt       3   2.459 ± 0.056   ms/op
ClientPb.getUser                          avgt       3   2.516 ± 0.543   ms/op
ClientPb.listUser                         avgt       3   3.025 ± 0.184   ms/op
ClientPb.createUser                     sample  381772   2.511 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.856           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.261           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.956           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.401           ms/op
ClientPb.existUser                      sample  382588   2.507 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.867           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.348           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.752           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.497           ms/op
ClientPb.getUser                        sample  380923   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.820           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.029           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.498           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.711           ms/op
ClientPb.listUser                       sample  322567   2.973 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.728           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.076           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.038           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.091           ms/op
