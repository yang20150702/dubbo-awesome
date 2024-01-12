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
# Warmup Iteration   1: 4.840 ops/ms
# Warmup Iteration   2: 12.152 ops/ms
# Warmup Iteration   3: 12.056 ops/ms
Iteration   1: 12.296 ops/ms
Iteration   2: 12.379 ops/ms
Iteration   3: 12.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.360 ±(99.9%) 1.033 ops/ms [Average]
  (min, avg, max) = (12.296, 12.360, 12.405), stdev = 0.057
  CI (99.9%): [11.327, 13.392] (assumes normal distribution)


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
# Warmup Iteration   1: 8.066 ops/ms
# Warmup Iteration   2: 13.001 ops/ms
# Warmup Iteration   3: 13.042 ops/ms
Iteration   1: 13.161 ops/ms
Iteration   2: 13.100 ops/ms
Iteration   3: 12.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.079 ±(99.9%) 1.721 ops/ms [Average]
  (min, avg, max) = (12.976, 13.079, 13.161), stdev = 0.094
  CI (99.9%): [11.358, 14.800] (assumes normal distribution)


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
# Warmup Iteration   1: 7.274 ops/ms
# Warmup Iteration   2: 12.186 ops/ms
# Warmup Iteration   3: 12.544 ops/ms
Iteration   1: 12.538 ops/ms
Iteration   2: 12.490 ops/ms
Iteration   3: 12.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.524 ±(99.9%) 0.540 ops/ms [Average]
  (min, avg, max) = (12.490, 12.524, 12.545), stdev = 0.030
  CI (99.9%): [11.984, 13.064] (assumes normal distribution)


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
# Warmup Iteration   1: 6.284 ops/ms
# Warmup Iteration   2: 10.526 ops/ms
# Warmup Iteration   3: 10.627 ops/ms
Iteration   1: 10.657 ops/ms
Iteration   2: 10.649 ops/ms
Iteration   3: 10.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.678 ±(99.9%) 0.800 ops/ms [Average]
  (min, avg, max) = (10.649, 10.678, 10.728), stdev = 0.044
  CI (99.9%): [9.878, 11.478] (assumes normal distribution)


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.563 ±(99.9%) 0.004 ms/op
Iteration   2: 2.554 ±(99.9%) 0.004 ms/op
Iteration   3: 2.550 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.555 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (2.550, 2.555, 2.563), stdev = 0.007
  CI (99.9%): [2.435, 2.676] (assumes normal distribution)


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.003 ms/op
Iteration   1: 2.421 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.435 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (2.421, 2.435, 2.444), stdev = 0.013
  CI (99.9%): [2.206, 2.665] (assumes normal distribution)


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.456 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.467 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (2.456, 2.467, 2.481), stdev = 0.013
  CI (99.9%): [2.230, 2.705] (assumes normal distribution)


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
# Warmup Iteration   1: 4.681 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.005 ms/op
Iteration   1: 3.024 ±(99.9%) 0.005 ms/op
Iteration   2: 3.066 ±(99.9%) 0.005 ms/op
Iteration   3: 3.036 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.042 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (3.024, 3.042, 3.066), stdev = 0.022
  CI (99.9%): [2.644, 3.440] (assumes normal distribution)


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
# Warmup Iteration   1: 4.259 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.706 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  11.416 ms/op
                 createUser·p0.9999: 14.549 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  10.342 ms/op
                 createUser·p0.9999: 14.137 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   3: 2.554 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  8.733 ms/op
                 createUser·p0.9999: 10.420 ms/op
                 createUser·p1.00:   10.699 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377095
  mean =      2.543 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 180248 
    [ 2.500,  3.750) = 192675 
    [ 3.750,  5.000) = 3375 
    [ 5.000,  6.250) = 324 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.813 ms/op
     p(99.9900) =     14.193 ms/op
     p(99.9990) =     14.986 ms/op
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
# Warmup Iteration   1: 3.751 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.199 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  11.268 ms/op
                 existUser·p0.9999: 14.160 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  5.751 ms/op
                 existUser·p0.9999: 15.257 ms/op
                 existUser·p1.00:   15.974 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  8.653 ms/op
                 existUser·p0.9999: 12.097 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384402
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 187420 
    [ 2.500,  3.750) = 192452 
    [ 3.750,  5.000) = 3541 
    [ 5.000,  6.250) = 512 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      6.665 ms/op
     p(99.9900) =     14.149 ms/op
     p(99.9990) =     15.811 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  11.063 ms/op
                 getUser·p0.9999: 14.569 ms/op
                 getUser·p1.00:   15.598 ms/op

Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  9.133 ms/op
                 getUser·p0.9999: 13.921 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  8.503 ms/op
                 getUser·p0.9999: 11.859 ms/op
                 getUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380296
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 186461 
    [ 2.500,  3.750) = 188574 
    [ 3.750,  5.000) = 4208 
    [ 5.000,  6.250) = 532 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      8.659 ms/op
     p(99.9900) =     14.041 ms/op
     p(99.9990) =     15.283 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


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
# Warmup Iteration   1: 4.673 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.009 ms/op
Iteration   1: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.533 ms/op
                 listUser·p0.9999: 11.493 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   2: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.439 ms/op
                 listUser·p0.9999: 11.213 ms/op
                 listUser·p1.00:   11.518 ms/op

Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.037 ms/op
                 listUser·p0.9999: 11.415 ms/op
                 listUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317510
  mean =      3.021 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 89489 
    [ 2.500,  3.750) = 188224 
    [ 3.750,  5.000) = 32593 
    [ 5.000,  6.250) = 5621 
    [ 6.250,  7.500) = 739 
    [ 7.500,  8.750) = 300 
    [ 8.750, 10.000) = 251 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.331 ms/op
     p(99.9900) =     11.403 ms/op
     p(99.9990) =     12.591 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.360 ± 1.033  ops/ms
ClientPb.existUser                       thrpt       3  13.079 ± 1.721  ops/ms
ClientPb.getUser                         thrpt       3  12.524 ± 0.540  ops/ms
ClientPb.listUser                        thrpt       3  10.678 ± 0.800  ops/ms
ClientPb.createUser                       avgt       3   2.555 ± 0.120   ms/op
ClientPb.existUser                        avgt       3   2.435 ± 0.229   ms/op
ClientPb.getUser                          avgt       3   2.467 ± 0.238   ms/op
ClientPb.listUser                         avgt       3   3.042 ± 0.398   ms/op
ClientPb.createUser                     sample  377095   2.543 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.885           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.813           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.193           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.106           ms/op
ClientPb.existUser                      sample  384402   2.495 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.900           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.665           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.149           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.974           ms/op
ClientPb.getUser                        sample  380296   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.792           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.659           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.041           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.598           ms/op
ClientPb.listUser                       sample  317510   3.021 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.766           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.331           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.403           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.763           ms/op
