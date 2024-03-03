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
# Warmup Iteration   1: 5.356 ops/ms
# Warmup Iteration   2: 12.241 ops/ms
# Warmup Iteration   3: 12.315 ops/ms
Iteration   1: 12.695 ops/ms
Iteration   2: 12.717 ops/ms
Iteration   3: 12.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.703 ±(99.9%) 0.220 ops/ms [Average]
  (min, avg, max) = (12.695, 12.703, 12.717), stdev = 0.012
  CI (99.9%): [12.483, 12.924] (assumes normal distribution)


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
# Warmup Iteration   1: 8.352 ops/ms
# Warmup Iteration   2: 13.428 ops/ms
# Warmup Iteration   3: 13.307 ops/ms
Iteration   1: 13.511 ops/ms
Iteration   2: 13.507 ops/ms
Iteration   3: 13.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.470 ±(99.9%) 1.233 ops/ms [Average]
  (min, avg, max) = (13.392, 13.470, 13.511), stdev = 0.068
  CI (99.9%): [12.236, 14.703] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.781 ops/ms
# Warmup Iteration   2: 12.902 ops/ms
# Warmup Iteration   3: 12.767 ops/ms
Iteration   1: 13.090 ops/ms
Iteration   2: 13.003 ops/ms
Iteration   3: 13.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.046 ±(99.9%) 0.797 ops/ms [Average]
  (min, avg, max) = (13.003, 13.046, 13.090), stdev = 0.044
  CI (99.9%): [12.249, 13.843] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.749 ops/ms
# Warmup Iteration   2: 10.497 ops/ms
# Warmup Iteration   3: 10.481 ops/ms
Iteration   1: 10.621 ops/ms
Iteration   2: 10.667 ops/ms
Iteration   3: 10.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.667 ±(99.9%) 0.850 ops/ms [Average]
  (min, avg, max) = (10.621, 10.667, 10.714), stdev = 0.047
  CI (99.9%): [9.818, 11.517] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.004 ms/op
Iteration   1: 2.498 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (2.487, 2.495, 2.499), stdev = 0.007
  CI (99.9%): [2.375, 2.614] (assumes normal distribution)


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
# Warmup Iteration   1: 3.689 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.415 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.404 ±(99.9%) 0.004 ms/op
Iteration   1: 2.407 ±(99.9%) 0.004 ms/op
Iteration   2: 2.401 ±(99.9%) 0.004 ms/op
Iteration   3: 2.403 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.404 ±(99.9%) 0.054 ms/op [Average]
  (min, avg, max) = (2.401, 2.404, 2.407), stdev = 0.003
  CI (99.9%): [2.350, 2.458] (assumes normal distribution)


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.003 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
Iteration   3: 2.447 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.447 ±(99.9%) 0.169 ms/op [Average]
  (min, avg, max) = (2.437, 2.447, 2.456), stdev = 0.009
  CI (99.9%): [2.277, 2.616] (assumes normal distribution)


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.005 ms/op
Iteration   1: 2.962 ±(99.9%) 0.007 ms/op
Iteration   2: 2.956 ±(99.9%) 0.004 ms/op
Iteration   3: 2.969 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.962 ±(99.9%) 0.117 ms/op [Average]
  (min, avg, max) = (2.956, 2.962, 2.969), stdev = 0.006
  CI (99.9%): [2.845, 3.079] (assumes normal distribution)


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  11.215 ms/op
                 createUser·p0.9999: 14.565 ms/op
                 createUser·p1.00:   14.860 ms/op

Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.490 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  9.552 ms/op
                 createUser·p0.9999: 12.054 ms/op
                 createUser·p1.00:   12.468 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  8.462 ms/op
                 createUser·p0.9999: 10.419 ms/op
                 createUser·p1.00:   10.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 392141
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 195696 
    [ 2.500,  3.750) = 192703 
    [ 3.750,  5.000) = 3043 
    [ 5.000,  6.250) = 191 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 141 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     13.661 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.436 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.402 ±(99.9%) 0.005 ms/op
Iteration   1: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  5.551 ms/op
                 existUser·p0.9999: 13.897 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  7.503 ms/op
                 existUser·p0.9999: 12.449 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.728 ms/op
                 existUser·p0.999:  7.569 ms/op
                 existUser·p0.9999: 12.210 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395181
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 198782 
    [ 2.500,  3.750) = 193236 
    [ 3.750,  5.000) = 2282 
    [ 5.000,  6.250) = 359 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      7.370 ms/op
     p(99.9900) =     13.057 ms/op
     p(99.9990) =     14.320 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.035 ms/op
                 getUser·p0.99:   3.338 ms/op
                 getUser·p0.999:  6.401 ms/op
                 getUser·p0.9999: 13.381 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  8.723 ms/op
                 getUser·p0.9999: 17.138 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  7.127 ms/op
                 getUser·p0.9999: 11.921 ms/op
                 getUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387663
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 193363 
    [ 2.500,  3.750) = 190188 
    [ 3.750,  5.000) = 2858 
    [ 5.000,  6.250) = 760 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 134 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      6.780 ms/op
     p(99.9900) =     13.705 ms/op
     p(99.9990) =     17.764 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 4.520 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.008 ms/op
Iteration   1: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.943 ms/op
                 listUser·p0.9999: 13.111 ms/op
                 listUser·p1.00:   14.025 ms/op

Iteration   2: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.186 ms/op
                 listUser·p0.9999: 12.335 ms/op
                 listUser·p1.00:   13.451 ms/op

Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.801 ms/op
                 listUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322487
  mean =      2.974 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 98876 
    [ 2.500,  3.750) = 186507 
    [ 3.750,  5.000) = 30099 
    [ 5.000,  6.250) = 5558 
    [ 6.250,  7.500) = 607 
    [ 7.500,  8.750) = 255 
    [ 8.750, 10.000) = 216 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     12.370 ms/op
     p(99.9990) =     13.429 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.703 ± 0.220  ops/ms
ClientPb.existUser                       thrpt       3  13.470 ± 1.233  ops/ms
ClientPb.getUser                         thrpt       3  13.046 ± 0.797  ops/ms
ClientPb.listUser                        thrpt       3  10.667 ± 0.850  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.120   ms/op
ClientPb.existUser                        avgt       3   2.404 ± 0.054   ms/op
ClientPb.getUser                          avgt       3   2.447 ± 0.169   ms/op
ClientPb.listUser                         avgt       3   2.962 ± 0.117   ms/op
ClientPb.createUser                     sample  392141   2.445 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.776           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.503           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.970           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.077           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.661           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.860           ms/op
ClientPb.existUser                      sample  395181   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.697           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.370           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.057           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.500           ms/op
ClientPb.getUser                        sample  387663   2.474 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.688           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.780           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.705           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.826           ms/op
ClientPb.listUser                       sample  322487   2.974 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.804           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.370           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.025           ms/op
