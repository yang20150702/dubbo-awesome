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
# Warmup Iteration   1: 4.657 ops/ms
# Warmup Iteration   2: 12.027 ops/ms
# Warmup Iteration   3: 12.151 ops/ms
Iteration   1: 12.465 ops/ms
Iteration   2: 12.553 ops/ms
Iteration   3: 12.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.513 ±(99.9%) 0.819 ops/ms [Average]
  (min, avg, max) = (12.465, 12.513, 12.553), stdev = 0.045
  CI (99.9%): [11.694, 13.332] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.730 ops/ms
# Warmup Iteration   2: 13.027 ops/ms
# Warmup Iteration   3: 12.843 ops/ms
Iteration   1: 12.938 ops/ms
Iteration   2: 13.017 ops/ms
Iteration   3: 12.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.928 ±(99.9%) 1.714 ops/ms [Average]
  (min, avg, max) = (12.830, 12.928, 13.017), stdev = 0.094
  CI (99.9%): [11.214, 14.642] (assumes normal distribution)


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
# Warmup Iteration   1: 7.708 ops/ms
# Warmup Iteration   2: 12.413 ops/ms
# Warmup Iteration   3: 12.512 ops/ms
Iteration   1: 12.811 ops/ms
Iteration   2: 12.794 ops/ms
Iteration   3: 12.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.737 ±(99.9%) 2.088 ops/ms [Average]
  (min, avg, max) = (12.605, 12.737, 12.811), stdev = 0.114
  CI (99.9%): [10.649, 14.824] (assumes normal distribution)


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
# Warmup Iteration   1: 6.398 ops/ms
# Warmup Iteration   2: 10.444 ops/ms
# Warmup Iteration   3: 10.693 ops/ms
Iteration   1: 10.721 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.647 ±(99.9%) 1.170 ops/ms [Average]
  (min, avg, max) = (10.605, 10.647, 10.721), stdev = 0.064
  CI (99.9%): [9.477, 11.817] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.199 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.003 ms/op
Iteration   1: 2.582 ±(99.9%) 0.004 ms/op
Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
Iteration   3: 2.524 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.552 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (2.524, 2.552, 2.582), stdev = 0.029
  CI (99.9%): [2.029, 3.075] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.894 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.003 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
Iteration   3: 2.445 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.461 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.445, 2.461, 2.473), stdev = 0.014
  CI (99.9%): [2.198, 2.724] (assumes normal distribution)


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
Iteration   2: 2.493 ±(99.9%) 0.003 ms/op
Iteration   3: 2.536 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.517 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (2.493, 2.517, 2.536), stdev = 0.022
  CI (99.9%): [2.118, 2.916] (assumes normal distribution)


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
# Warmup Iteration   1: 4.706 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.005 ms/op
Iteration   1: 3.023 ±(99.9%) 0.004 ms/op
Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
Iteration   3: 2.998 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.005 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (2.993, 3.005, 3.023), stdev = 0.016
  CI (99.9%): [2.714, 3.295] (assumes normal distribution)


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  10.106 ms/op
                 createUser·p0.9999: 13.618 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  10.190 ms/op
                 createUser·p0.9999: 12.397 ms/op
                 createUser·p1.00:   13.140 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  8.430 ms/op
                 createUser·p0.9999: 13.899 ms/op
                 createUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383705
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 185929 
    [ 2.500,  3.750) = 192969 
    [ 3.750,  5.000) = 3898 
    [ 5.000,  6.250) = 354 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.452 ms/op
     p(99.9900) =     13.183 ms/op
     p(99.9990) =     14.797 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


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
# Warmup Iteration   1: 3.689 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  7.088 ms/op
                 existUser·p0.9999: 13.285 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   2: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  6.135 ms/op
                 existUser·p0.9999: 13.004 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  8.977 ms/op
                 existUser·p0.9999: 11.944 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394172
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 197773 
    [ 2.500,  3.750) = 193579 
    [ 3.750,  5.000) = 2042 
    [ 5.000,  6.250) = 251 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      8.451 ms/op
     p(99.9900) =     13.051 ms/op
     p(99.9990) =     13.681 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  5.924 ms/op
                 getUser·p0.9999: 14.090 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  9.608 ms/op
                 getUser·p0.9999: 13.737 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  7.333 ms/op
                 getUser·p0.9999: 11.590 ms/op
                 getUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383687
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 189048 
    [ 2.500,  3.750) = 190009 
    [ 3.750,  5.000) = 3558 
    [ 5.000,  6.250) = 607 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      7.340 ms/op
     p(99.9900) =     13.740 ms/op
     p(99.9990) =     14.704 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 4.791 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
Iteration   1: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.945 ms/op
                 listUser·p0.9999: 11.232 ms/op
                 listUser·p1.00:   12.812 ms/op

Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.348 ms/op
                 listUser·p0.9999: 12.815 ms/op
                 listUser·p1.00:   13.287 ms/op

Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.786 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 12.408 ms/op
                 listUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316453
  mean =      3.031 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 89241 
    [ 2.500,  3.750) = 187231 
    [ 3.750,  5.000) = 32426 
    [ 5.000,  6.250) = 6086 
    [ 6.250,  7.500) = 623 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 269 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     12.485 ms/op
     p(99.9990) =     13.282 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.513 ± 0.819  ops/ms
ClientPb.existUser                       thrpt       3  12.928 ± 1.714  ops/ms
ClientPb.getUser                         thrpt       3  12.737 ± 2.088  ops/ms
ClientPb.listUser                        thrpt       3  10.647 ± 1.170  ops/ms
ClientPb.createUser                       avgt       3   2.552 ± 0.523   ms/op
ClientPb.existUser                        avgt       3   2.461 ± 0.263   ms/op
ClientPb.getUser                          avgt       3   2.517 ± 0.399   ms/op
ClientPb.listUser                         avgt       3   3.005 ± 0.290   ms/op
ClientPb.createUser                     sample  383705   2.500 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.857           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.452           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.183           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.417           ms/op
ClientPb.existUser                      sample  394172   2.433 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.834           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.451           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.051           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.877           ms/op
ClientPb.getUser                        sample  383687   2.500 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.870           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.340           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.740           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.401           ms/op
ClientPb.listUser                       sample  316453   3.031 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.786           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.748           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.485           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.435           ms/op
