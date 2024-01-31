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
# Warmup Iteration   1: 5.311 ops/ms
# Warmup Iteration   2: 12.287 ops/ms
# Warmup Iteration   3: 12.426 ops/ms
Iteration   1: 12.695 ops/ms
Iteration   2: 12.605 ops/ms
Iteration   3: 12.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.705 ±(99.9%) 1.916 ops/ms [Average]
  (min, avg, max) = (12.605, 12.705, 12.814), stdev = 0.105
  CI (99.9%): [10.789, 14.620] (assumes normal distribution)


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
# Warmup Iteration   1: 8.329 ops/ms
# Warmup Iteration   2: 12.892 ops/ms
# Warmup Iteration   3: 13.022 ops/ms
Iteration   1: 13.080 ops/ms
Iteration   2: 13.074 ops/ms
Iteration   3: 12.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.976 ±(99.9%) 3.183 ops/ms [Average]
  (min, avg, max) = (12.775, 12.976, 13.080), stdev = 0.174
  CI (99.9%): [9.793, 16.159] (assumes normal distribution)


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
# Warmup Iteration   1: 8.024 ops/ms
# Warmup Iteration   2: 12.712 ops/ms
# Warmup Iteration   3: 12.942 ops/ms
Iteration   1: 12.845 ops/ms
Iteration   2: 12.911 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.859 ±(99.9%) 0.862 ops/ms [Average]
  (min, avg, max) = (12.819, 12.859, 12.911), stdev = 0.047
  CI (99.9%): [11.997, 13.721] (assumes normal distribution)


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
# Warmup Iteration   1: 6.586 ops/ms
# Warmup Iteration   2: 10.517 ops/ms
# Warmup Iteration   3: 10.714 ops/ms
Iteration   1: 10.695 ops/ms
Iteration   2: 10.773 ops/ms
Iteration   3: 10.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.743 ±(99.9%) 0.762 ops/ms [Average]
  (min, avg, max) = (10.695, 10.743, 10.773), stdev = 0.042
  CI (99.9%): [9.981, 11.505] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.946 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.004 ms/op
Iteration   1: 2.573 ±(99.9%) 0.005 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.528 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (2.502, 2.528, 2.573), stdev = 0.039
  CI (99.9%): [1.820, 3.236] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.413 ±(99.9%) 0.004 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.441 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (2.413, 2.441, 2.475), stdev = 0.031
  CI (99.9%): [1.872, 3.009] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.895 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.122 ms/op [Average]
  (min, avg, max) = (2.477, 2.485, 2.489), stdev = 0.007
  CI (99.9%): [2.363, 2.607] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.841 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.005 ms/op
Iteration   1: 3.011 ±(99.9%) 0.007 ms/op
Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
Iteration   3: 2.989 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.001 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (2.989, 3.001, 3.011), stdev = 0.011
  CI (99.9%): [2.798, 3.203] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.102 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.035 ms/op
                 createUser·p0.99:   3.494 ms/op
                 createUser·p0.999:  5.905 ms/op
                 createUser·p0.9999: 14.112 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  6.216 ms/op
                 createUser·p0.9999: 12.567 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  8.710 ms/op
                 createUser·p0.9999: 11.960 ms/op
                 createUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391111
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 193310 
    [ 2.500,  3.750) = 194772 
    [ 3.750,  5.000) = 2296 
    [ 5.000,  6.250) = 245 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     13.346 ms/op
     p(99.9990) =     14.747 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  6.191 ms/op
                 existUser·p0.9999: 13.140 ms/op
                 existUser·p1.00:   13.664 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  8.205 ms/op
                 existUser·p0.9999: 12.304 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  5.965 ms/op
                 existUser·p0.9999: 11.534 ms/op
                 existUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391631
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 196443 
    [ 2.500,  3.750) = 191272 
    [ 3.750,  5.000) = 2794 
    [ 5.000,  6.250) = 681 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 140 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      6.487 ms/op
     p(99.9900) =     12.859 ms/op
     p(99.9990) =     13.510 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  6.439 ms/op
                 getUser·p0.9999: 14.073 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  7.298 ms/op
                 getUser·p0.9999: 11.677 ms/op
                 getUser·p1.00:   12.206 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  8.736 ms/op
                 getUser·p0.9999: 11.325 ms/op
                 getUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387981
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 192977 
    [ 2.500,  3.750) = 190663 
    [ 3.750,  5.000) = 3555 
    [ 5.000,  6.250) = 271 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 140 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     12.868 ms/op
     p(99.9990) =     14.207 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 4.853 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
Iteration   1: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 10.934 ms/op
                 listUser·p1.00:   11.338 ms/op

Iteration   2: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  10.060 ms/op
                 listUser·p0.9999: 11.686 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  8.831 ms/op
                 listUser·p0.9999: 10.398 ms/op
                 listUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320820
  mean =      2.990 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 95086 
    [ 2.500,  3.750) = 187967 
    [ 3.750,  5.000) = 30561 
    [ 5.000,  6.250) = 5662 
    [ 6.250,  7.500) = 709 
    [ 7.500,  8.750) = 278 
    [ 8.750, 10.000) = 255 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.162 ms/op
     p(99.9900) =     11.335 ms/op
     p(99.9990) =     11.999 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.705 ± 1.916  ops/ms
ClientPb.existUser                       thrpt       3  12.976 ± 3.183  ops/ms
ClientPb.getUser                         thrpt       3  12.859 ± 0.862  ops/ms
ClientPb.listUser                        thrpt       3  10.743 ± 0.762  ops/ms
ClientPb.createUser                       avgt       3   2.528 ± 0.708   ms/op
ClientPb.existUser                        avgt       3   2.441 ± 0.568   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.122   ms/op
ClientPb.listUser                         avgt       3   3.001 ± 0.203   ms/op
ClientPb.createUser                     sample  391111   2.452 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.822           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.519           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.982           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.621           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.684           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.346           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.893           ms/op
ClientPb.existUser                      sample  391631   2.449 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.863           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.487           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.859           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.123           ms/op
ClientPb.getUser                        sample  387981   2.472 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.820           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.733           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.868           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.352           ms/op
ClientPb.listUser                       sample  320820   2.990 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.766           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.162           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.335           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.616           ms/op
