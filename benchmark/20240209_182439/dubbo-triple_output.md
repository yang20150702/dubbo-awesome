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
# Warmup Iteration   1: 4.936 ops/ms
# Warmup Iteration   2: 12.465 ops/ms
# Warmup Iteration   3: 12.521 ops/ms
Iteration   1: 12.797 ops/ms
Iteration   2: 12.881 ops/ms
Iteration   3: 13.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.894 ±(99.9%) 1.885 ops/ms [Average]
  (min, avg, max) = (12.797, 12.894, 13.003), stdev = 0.103
  CI (99.9%): [11.009, 14.778] (assumes normal distribution)


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
# Warmup Iteration   1: 8.407 ops/ms
# Warmup Iteration   2: 13.200 ops/ms
# Warmup Iteration   3: 13.207 ops/ms
Iteration   1: 13.342 ops/ms
Iteration   2: 13.295 ops/ms
Iteration   3: 13.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.296 ±(99.9%) 0.822 ops/ms [Average]
  (min, avg, max) = (13.252, 13.296, 13.342), stdev = 0.045
  CI (99.9%): [12.475, 14.118] (assumes normal distribution)


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
# Warmup Iteration   1: 8.067 ops/ms
# Warmup Iteration   2: 12.776 ops/ms
# Warmup Iteration   3: 13.088 ops/ms
Iteration   1: 13.006 ops/ms
Iteration   2: 13.031 ops/ms
Iteration   3: 13.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.027 ±(99.9%) 0.352 ops/ms [Average]
  (min, avg, max) = (13.006, 13.027, 13.044), stdev = 0.019
  CI (99.9%): [12.675, 13.379] (assumes normal distribution)


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
# Warmup Iteration   1: 6.691 ops/ms
# Warmup Iteration   2: 10.788 ops/ms
# Warmup Iteration   3: 10.844 ops/ms
Iteration   1: 11.001 ops/ms
Iteration   2: 10.933 ops/ms
Iteration   3: 10.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.917 ±(99.9%) 1.694 ops/ms [Average]
  (min, avg, max) = (10.817, 10.917, 11.001), stdev = 0.093
  CI (99.9%): [9.223, 12.611] (assumes normal distribution)


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.003 ms/op
Iteration   1: 2.504 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.493 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.493 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (2.483, 2.493, 2.504), stdev = 0.011
  CI (99.9%): [2.301, 2.685] (assumes normal distribution)


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
# Warmup Iteration   1: 3.536 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.422 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.004 ms/op
Iteration   1: 2.429 ±(99.9%) 0.004 ms/op
Iteration   2: 2.404 ±(99.9%) 0.003 ms/op
Iteration   3: 2.447 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.427 ±(99.9%) 0.392 ms/op [Average]
  (min, avg, max) = (2.404, 2.427, 2.447), stdev = 0.022
  CI (99.9%): [2.034, 2.819] (assumes normal distribution)


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
# Warmup Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.473 ±(99.9%) 0.003 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.473 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.457, 2.473, 2.489), stdev = 0.016
  CI (99.9%): [2.187, 2.759] (assumes normal distribution)


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
# Warmup Iteration   1: 4.607 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
Iteration   1: 2.925 ±(99.9%) 0.005 ms/op
Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
Iteration   3: 2.942 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.947 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (2.925, 2.947, 2.974), stdev = 0.025
  CI (99.9%): [2.486, 3.408] (assumes normal distribution)


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
# Warmup Iteration   1: 4.311 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  11.639 ms/op
                 createUser·p0.9999: 15.089 ms/op
                 createUser·p1.00:   16.073 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.473 ms/op
                 createUser·p0.999:  8.988 ms/op
                 createUser·p0.9999: 15.024 ms/op
                 createUser·p1.00:   15.319 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  8.931 ms/op
                 createUser·p0.9999: 10.732 ms/op
                 createUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380945
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 182697 
    [ 2.500,  3.750) = 195025 
    [ 3.750,  5.000) = 2451 
    [ 5.000,  6.250) = 272 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =      9.000 ms/op
     p(99.9900) =     14.679 ms/op
     p(99.9990) =     15.322 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  5.661 ms/op
                 existUser·p0.9999: 14.267 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.020 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.355 ms/op
                 existUser·p0.999:  6.077 ms/op
                 existUser·p0.9999: 12.756 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  9.159 ms/op
                 existUser·p0.9999: 12.812 ms/op
                 existUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391897
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 193820 
    [ 2.500,  3.750) = 195542 
    [ 3.750,  5.000) = 1757 
    [ 5.000,  6.250) = 311 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.494 ms/op
     p(99.9000) =      8.077 ms/op
     p(99.9900) =     13.327 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 3.809 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  10.969 ms/op
                 getUser·p0.9999: 13.832 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  9.166 ms/op
                 getUser·p0.9999: 14.340 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.490 ms/op
                 getUser·p0.999:  7.875 ms/op
                 getUser·p0.9999: 11.096 ms/op
                 getUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383890
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 191087 
    [ 2.500,  3.750) = 189754 
    [ 3.750,  5.000) = 2285 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      8.336 ms/op
     p(99.9900) =     13.854 ms/op
     p(99.9990) =     15.062 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 4.668 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  8.798 ms/op
                 listUser·p0.9999: 10.147 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  10.060 ms/op
                 listUser·p0.9999: 16.984 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.569 ms/op
                 listUser·p0.9999: 10.377 ms/op
                 listUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320348
  mean =      2.994 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 92496 
    [ 2.500,  3.750) = 190508 
    [ 3.750,  5.000) = 30731 
    [ 5.000,  6.250) = 5285 
    [ 6.250,  7.500) = 529 
    [ 7.500,  8.750) = 283 
    [ 8.750, 10.000) = 201 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     13.917 ms/op
     p(99.9990) =     17.229 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.894 ± 1.885  ops/ms
ClientPb.existUser                       thrpt       3  13.296 ± 0.822  ops/ms
ClientPb.getUser                         thrpt       3  13.027 ± 0.352  ops/ms
ClientPb.listUser                        thrpt       3  10.917 ± 1.694  ops/ms
ClientPb.createUser                       avgt       3   2.493 ± 0.192   ms/op
ClientPb.existUser                        avgt       3   2.427 ± 0.392   ms/op
ClientPb.getUser                          avgt       3   2.473 ± 0.286   ms/op
ClientPb.listUser                         avgt       3   2.947 ± 0.461   ms/op
ClientPb.createUser                     sample  380945   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.664           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.641           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.000           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.679           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.073           ms/op
ClientPb.existUser                      sample  391897   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.922           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.077           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.327           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.434           ms/op
ClientPb.getUser                        sample  383890   2.498 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.716           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.604           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.336           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.854           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.139           ms/op
ClientPb.listUser                       sample  320348   2.994 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.929           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.917           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.334           ms/op
