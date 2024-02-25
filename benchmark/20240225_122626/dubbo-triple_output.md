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
# Warmup Iteration   1: 4.570 ops/ms
# Warmup Iteration   2: 12.273 ops/ms
# Warmup Iteration   3: 12.464 ops/ms
Iteration   1: 12.801 ops/ms
Iteration   2: 12.732 ops/ms
Iteration   3: 12.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.735 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (12.672, 12.735, 12.801), stdev = 0.065
  CI (99.9%): [11.558, 13.912] (assumes normal distribution)


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
# Warmup Iteration   1: 8.425 ops/ms
# Warmup Iteration   2: 13.061 ops/ms
# Warmup Iteration   3: 13.135 ops/ms
Iteration   1: 13.140 ops/ms
Iteration   2: 13.193 ops/ms
Iteration   3: 13.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.132 ±(99.9%) 1.187 ops/ms [Average]
  (min, avg, max) = (13.063, 13.132, 13.193), stdev = 0.065
  CI (99.9%): [11.945, 14.319] (assumes normal distribution)


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
# Warmup Iteration   1: 7.879 ops/ms
# Warmup Iteration   2: 12.642 ops/ms
# Warmup Iteration   3: 12.726 ops/ms
Iteration   1: 12.910 ops/ms
Iteration   2: 12.667 ops/ms
Iteration   3: 12.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.695 ±(99.9%) 3.695 ops/ms [Average]
  (min, avg, max) = (12.508, 12.695, 12.910), stdev = 0.203
  CI (99.9%): [9.000, 16.390] (assumes normal distribution)


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
# Warmup Iteration   1: 6.738 ops/ms
# Warmup Iteration   2: 10.373 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.631 ops/ms
Iteration   2: 10.606 ops/ms
Iteration   3: 10.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.587 ±(99.9%) 1.032 ops/ms [Average]
  (min, avg, max) = (10.523, 10.587, 10.631), stdev = 0.057
  CI (99.9%): [9.555, 11.618] (assumes normal distribution)


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.004 ms/op
Iteration   1: 2.563 ±(99.9%) 0.004 ms/op
Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.546 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.537, 2.546, 2.563), stdev = 0.014
  CI (99.9%): [2.287, 2.805] (assumes normal distribution)


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.003 ms/op
Iteration   1: 2.471 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.442 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.440, 2.451, 2.471), stdev = 0.018
  CI (99.9%): [2.131, 2.770] (assumes normal distribution)


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.003 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.467 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (2.460, 2.467, 2.474), stdev = 0.007
  CI (99.9%): [2.338, 2.597] (assumes normal distribution)


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
# Warmup Iteration   1: 4.488 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.005 ms/op
Iteration   1: 3.024 ±(99.9%) 0.007 ms/op
Iteration   2: 2.992 ±(99.9%) 0.004 ms/op
Iteration   3: 2.996 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.004 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.992, 3.004, 3.024), stdev = 0.018
  CI (99.9%): [2.681, 3.327] (assumes normal distribution)


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  7.763 ms/op
                 createUser·p0.9999: 13.896 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  9.426 ms/op
                 createUser·p0.9999: 12.327 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  8.779 ms/op
                 createUser·p0.9999: 11.502 ms/op
                 createUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385553
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 188952 
    [ 2.500,  3.750) = 193092 
    [ 3.750,  5.000) = 2594 
    [ 5.000,  6.250) = 367 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     14.341 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.405 ±(99.9%) 0.005 ms/op
Iteration   1: 2.395 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  5.983 ms/op
                 existUser·p0.9999: 13.418 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.040 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  6.806 ms/op
                 existUser·p0.9999: 12.984 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  7.502 ms/op
                 existUser·p0.9999: 10.956 ms/op
                 existUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398803
  mean =      2.405 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 206298 
    [ 2.500,  3.750) = 189475 
    [ 3.750,  5.000) = 2320 
    [ 5.000,  6.250) = 205 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      6.966 ms/op
     p(99.9900) =     13.142 ms/op
     p(99.9990) =     13.864 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.604 ms/op
                 getUser·p0.999:  5.396 ms/op
                 getUser·p0.9999: 15.684 ms/op
                 getUser·p1.00:   16.482 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  9.992 ms/op
                 getUser·p0.9999: 13.271 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.180 ms/op
                 getUser·p0.999:  8.454 ms/op
                 getUser·p0.9999: 11.600 ms/op
                 getUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379729
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 187168 
    [ 2.500,  3.750) = 188374 
    [ 3.750,  5.000) = 3309 
    [ 5.000,  6.250) = 473 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      5.856 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     16.112 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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
# Warmup Iteration   1: 4.770 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.009 ms/op
Iteration   1: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.880 ms/op
                 listUser·p0.9999: 14.474 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   2: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  10.366 ms/op
                 listUser·p0.9999: 16.321 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.978 ms/op
                 listUser·p0.9999: 12.728 ms/op
                 listUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312416
  mean =      3.070 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 81359 
    [ 2.500,  3.750) = 188858 
    [ 3.750,  5.000) = 34447 
    [ 5.000,  6.250) = 6289 
    [ 6.250,  7.500) = 682 
    [ 7.500,  8.750) = 175 
    [ 8.750, 10.000) = 195 
    [10.000, 11.250) = 199 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.961 ms/op
     p(99.9900) =     15.688 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.735 ± 1.177  ops/ms
ClientPb.existUser                       thrpt       3  13.132 ± 1.187  ops/ms
ClientPb.getUser                         thrpt       3  12.695 ± 3.695  ops/ms
ClientPb.listUser                        thrpt       3  10.587 ± 1.032  ops/ms
ClientPb.createUser                       avgt       3   2.546 ± 0.259   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.319   ms/op
ClientPb.getUser                          avgt       3   2.467 ± 0.130   ms/op
ClientPb.listUser                         avgt       3   3.004 ± 0.323   ms/op
ClientPb.createUser                     sample  385553   2.488 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.685           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.765           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.942           ms/op
ClientPb.existUser                      sample  398803   2.405 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.737           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.445           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.929           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.966           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.142           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.270           ms/op
ClientPb.getUser                        sample  379729   2.526 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.923           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.856           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.763           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.482           ms/op
ClientPb.listUser                       sample  312416   3.070 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.911           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.961           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.688           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.203           ms/op
