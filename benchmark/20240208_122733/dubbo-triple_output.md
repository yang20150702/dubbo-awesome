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
# Warmup Iteration   1: 4.647 ops/ms
# Warmup Iteration   2: 12.004 ops/ms
# Warmup Iteration   3: 12.332 ops/ms
Iteration   1: 12.325 ops/ms
Iteration   2: 12.463 ops/ms
Iteration   3: 12.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.452 ±(99.9%) 2.233 ops/ms [Average]
  (min, avg, max) = (12.325, 12.452, 12.569), stdev = 0.122
  CI (99.9%): [10.219, 14.685] (assumes normal distribution)


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
# Warmup Iteration   1: 7.919 ops/ms
# Warmup Iteration   2: 12.644 ops/ms
# Warmup Iteration   3: 12.739 ops/ms
Iteration   1: 12.760 ops/ms
Iteration   2: 12.664 ops/ms
Iteration   3: 12.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.713 ±(99.9%) 0.870 ops/ms [Average]
  (min, avg, max) = (12.664, 12.713, 12.760), stdev = 0.048
  CI (99.9%): [11.843, 13.582] (assumes normal distribution)


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
# Warmup Iteration   1: 6.929 ops/ms
# Warmup Iteration   2: 12.159 ops/ms
# Warmup Iteration   3: 12.446 ops/ms
Iteration   1: 12.485 ops/ms
Iteration   2: 12.547 ops/ms
Iteration   3: 12.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.555 ±(99.9%) 1.347 ops/ms [Average]
  (min, avg, max) = (12.485, 12.555, 12.632), stdev = 0.074
  CI (99.9%): [11.208, 13.902] (assumes normal distribution)


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
# Warmup Iteration   1: 6.567 ops/ms
# Warmup Iteration   2: 10.342 ops/ms
# Warmup Iteration   3: 10.508 ops/ms
Iteration   1: 10.559 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.576 ±(99.9%) 0.303 ops/ms [Average]
  (min, avg, max) = (10.559, 10.576, 10.591), stdev = 0.017
  CI (99.9%): [10.273, 10.879] (assumes normal distribution)


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.562 ±(99.9%) 0.003 ms/op
Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
Iteration   3: 2.542 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.539 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (2.512, 2.539, 2.562), stdev = 0.025
  CI (99.9%): [2.075, 3.003] (assumes normal distribution)


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.004 ms/op
Iteration   1: 2.453 ±(99.9%) 0.004 ms/op
Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
Iteration   3: 2.441 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.446 ±(99.9%) 0.111 ms/op [Average]
  (min, avg, max) = (2.441, 2.446, 2.453), stdev = 0.006
  CI (99.9%): [2.335, 2.557] (assumes normal distribution)


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.004 ms/op
Iteration   1: 2.457 ±(99.9%) 0.003 ms/op
Iteration   2: 2.474 ±(99.9%) 0.003 ms/op
Iteration   3: 2.498 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.476 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (2.457, 2.476, 2.498), stdev = 0.021
  CI (99.9%): [2.102, 2.851] (assumes normal distribution)


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.005 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
Iteration   3: 3.022 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.011 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.995, 3.011, 3.022), stdev = 0.014
  CI (99.9%): [2.749, 3.274] (assumes normal distribution)


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  10.870 ms/op
                 createUser·p0.9999: 14.156 ms/op
                 createUser·p1.00:   14.959 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  9.404 ms/op
                 createUser·p0.9999: 11.944 ms/op
                 createUser·p1.00:   12.255 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.973 ms/op
                 createUser·p0.999:  8.205 ms/op
                 createUser·p0.9999: 10.469 ms/op
                 createUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381878
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 185504 
    [ 2.500,  3.750) = 192607 
    [ 3.750,  5.000) = 2832 
    [ 5.000,  6.250) = 438 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.286 ms/op
     p(99.9900) =     12.613 ms/op
     p(99.9990) =     14.585 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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
# Warmup Iteration   1: 3.752 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  7.169 ms/op
                 existUser·p0.9999: 13.321 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  8.146 ms/op
                 existUser·p0.9999: 12.634 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  8.382 ms/op
                 existUser·p0.9999: 10.927 ms/op
                 existUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390458
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 196972 
    [ 2.500,  3.750) = 190246 
    [ 3.750,  5.000) = 2408 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      8.312 ms/op
     p(99.9900) =     12.762 ms/op
     p(99.9990) =     13.720 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 3.854 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  10.161 ms/op
                 getUser·p0.9999: 12.894 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.108 ms/op
                 getUser·p0.999:  8.946 ms/op
                 getUser·p0.9999: 11.401 ms/op
                 getUser·p1.00:   12.386 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.221 ms/op
                 getUser·p0.9999: 10.240 ms/op
                 getUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379802
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 186592 
    [ 2.500,  3.750) = 187589 
    [ 3.750,  5.000) = 4261 
    [ 5.000,  6.250) = 906 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 155 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =      6.465 ms/op
     p(99.9900) =     12.534 ms/op
     p(99.9990) =     13.324 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


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
# Warmup Iteration   1: 4.698 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.009 ms/op
Iteration   1: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.713 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  8.651 ms/op
                 listUser·p0.9999: 10.340 ms/op
                 listUser·p1.00:   10.830 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.607 ms/op
                 listUser·p0.9999: 11.057 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.841 ms/op
                 listUser·p0.999:  9.415 ms/op
                 listUser·p0.9999: 11.370 ms/op
                 listUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315496
  mean =      3.041 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 87567 
    [ 2.500,  3.750) = 187864 
    [ 3.750,  5.000) = 32322 
    [ 5.000,  6.250) = 6072 
    [ 6.250,  7.500) = 904 
    [ 7.500,  8.750) = 249 
    [ 8.750, 10.000) = 250 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     11.076 ms/op
     p(99.9990) =     11.737 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.452 ± 2.233  ops/ms
ClientPb.existUser                       thrpt       3  12.713 ± 0.870  ops/ms
ClientPb.getUser                         thrpt       3  12.555 ± 1.347  ops/ms
ClientPb.listUser                        thrpt       3  10.576 ± 0.303  ops/ms
ClientPb.createUser                       avgt       3   2.539 ± 0.464   ms/op
ClientPb.existUser                        avgt       3   2.446 ± 0.111   ms/op
ClientPb.getUser                          avgt       3   2.476 ± 0.374   ms/op
ClientPb.listUser                         avgt       3   3.011 ± 0.263   ms/op
ClientPb.createUser                     sample  381878   2.512 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.286           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.613           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.959           ms/op
ClientPb.existUser                      sample  390458   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.737           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.312           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.762           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.910           ms/op
ClientPb.getUser                        sample  379802   2.525 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.869           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.465           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.534           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.418           ms/op
ClientPb.listUser                       sample  315496   3.041 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.713           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.076           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.878           ms/op
