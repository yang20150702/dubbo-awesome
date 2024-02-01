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
# Warmup Iteration   1: 4.182 ops/ms
# Warmup Iteration   2: 12.118 ops/ms
# Warmup Iteration   3: 12.412 ops/ms
Iteration   1: 12.625 ops/ms
Iteration   2: 12.488 ops/ms
Iteration   3: 12.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.652 ±(99.9%) 3.245 ops/ms [Average]
  (min, avg, max) = (12.488, 12.652, 12.841), stdev = 0.178
  CI (99.9%): [9.406, 15.897] (assumes normal distribution)


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
# Warmup Iteration   1: 8.086 ops/ms
# Warmup Iteration   2: 13.282 ops/ms
# Warmup Iteration   3: 13.364 ops/ms
Iteration   1: 13.040 ops/ms
Iteration   2: 13.280 ops/ms
Iteration   3: 13.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.224 ±(99.9%) 2.964 ops/ms [Average]
  (min, avg, max) = (13.040, 13.224, 13.350), stdev = 0.162
  CI (99.9%): [10.259, 16.188] (assumes normal distribution)


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
# Warmup Iteration   1: 7.747 ops/ms
# Warmup Iteration   2: 12.640 ops/ms
# Warmup Iteration   3: 12.756 ops/ms
Iteration   1: 12.921 ops/ms
Iteration   2: 13.083 ops/ms
Iteration   3: 13.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.013 ±(99.9%) 1.514 ops/ms [Average]
  (min, avg, max) = (12.921, 13.013, 13.083), stdev = 0.083
  CI (99.9%): [11.499, 14.527] (assumes normal distribution)


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
# Warmup Iteration   1: 6.535 ops/ms
# Warmup Iteration   2: 10.676 ops/ms
# Warmup Iteration   3: 10.679 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.649 ops/ms
Iteration   3: 10.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.636 ±(99.9%) 0.204 ops/ms [Average]
  (min, avg, max) = (10.626, 10.636, 10.649), stdev = 0.011
  CI (99.9%): [10.433, 10.840] (assumes normal distribution)


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.004 ms/op
Iteration   1: 2.554 ±(99.9%) 0.007 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.555 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (2.511, 2.540, 2.555), stdev = 0.025
  CI (99.9%): [2.082, 2.999] (assumes normal distribution)


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
Iteration   1: 2.369 ±(99.9%) 0.005 ms/op
Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
Iteration   3: 2.398 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.399 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (2.369, 2.399, 2.431), stdev = 0.031
  CI (99.9%): [1.838, 2.961] (assumes normal distribution)


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
# Warmup Iteration   1: 4.119 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.510 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.492, 2.510, 2.522), stdev = 0.016
  CI (99.9%): [2.220, 2.801] (assumes normal distribution)


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
# Warmup Iteration   1: 4.742 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.007 ms/op
Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
Iteration   3: 3.002 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.999 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (2.975, 2.999, 3.021), stdev = 0.023
  CI (99.9%): [2.576, 3.422] (assumes normal distribution)


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.735 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.006 ms/op
Iteration   1: 2.556 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   2.474 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.375 ms/op
                 createUser·p0.99:   4.121 ms/op
                 createUser·p0.999:  11.861 ms/op
                 createUser·p0.9999: 14.057 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.371 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  10.147 ms/op
                 createUser·p0.9999: 14.527 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   2.474 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   4.039 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 11.878 ms/op
                 createUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376020
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 189791 
    [ 2.500,  3.750) = 178774 
    [ 3.750,  5.000) = 6217 
    [ 5.000,  6.250) = 530 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.371 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.326 ms/op
     p(99.0000) =      4.096 ms/op
     p(99.9000) =      9.863 ms/op
     p(99.9900) =     13.982 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.006 ms/op
Iteration   1: 2.463 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   3.940 ms/op
                 existUser·p0.999:  6.144 ms/op
                 existUser·p0.9999: 15.124 ms/op
                 existUser·p1.00:   16.253 ms/op

Iteration   2: 2.422 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.355 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.277 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  6.054 ms/op
                 existUser·p0.9999: 13.972 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   3: 2.421 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.380 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  6.715 ms/op
                 existUser·p0.9999: 15.145 ms/op
                 existUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393829
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 215826 
    [ 2.500,  3.750) = 171378 
    [ 3.750,  5.000) = 5594 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 88 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.384 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.033 ms/op
     p(99.9000) =      6.414 ms/op
     p(99.9900) =     15.051 ms/op
     p(99.9990) =     16.207 ms/op
     p(99.9999) =     16.335 ms/op
    p(100.0000) =     16.335 ms/op


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.477 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  9.570 ms/op
                 getUser·p0.9999: 14.074 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  10.111 ms/op
                 getUser·p0.9999: 13.304 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  9.486 ms/op
                 getUser·p0.9999: 14.148 ms/op
                 getUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382739
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 190177 
    [ 2.500,  3.750) = 188005 
    [ 3.750,  5.000) = 3621 
    [ 5.000,  6.250) = 432 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.840 ms/op
     p(99.9000) =      9.495 ms/op
     p(99.9900) =     13.922 ms/op
     p(99.9990) =     14.784 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 4.766 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.009 ms/op
Iteration   1: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.043 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.994 ms/op
                 listUser·p0.9999: 11.379 ms/op
                 listUser·p1.00:   11.502 ms/op

Iteration   2: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.787 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 11.215 ms/op
                 listUser·p1.00:   11.616 ms/op

Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315449
  mean =      3.040 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 85020 
    [ 2.500,  3.750) = 190394 
    [ 3.750,  5.000) = 32748 
    [ 5.000,  6.250) = 5856 
    [ 6.250,  7.500) = 595 
    [ 7.500,  8.750) = 251 
    [ 8.750, 10.000) = 284 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     16.548 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.652 ± 3.245  ops/ms
ClientPb.existUser                       thrpt       3  13.224 ± 2.964  ops/ms
ClientPb.getUser                         thrpt       3  13.013 ± 1.514  ops/ms
ClientPb.listUser                        thrpt       3  10.636 ± 0.204  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.459   ms/op
ClientPb.existUser                        avgt       3   2.399 ± 0.562   ms/op
ClientPb.getUser                          avgt       3   2.510 ± 0.291   ms/op
ClientPb.listUser                         avgt       3   2.999 ± 0.423   ms/op
ClientPb.createUser                     sample  376020   2.551 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.371           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.486           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.863           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.982           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.352           ms/op
ClientPb.existUser                      sample  393829   2.435 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.783           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.384           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.033           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.414           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.051           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.335           ms/op
ClientPb.getUser                        sample  382739   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.477           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.840           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.495           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.922           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.877           ms/op
ClientPb.listUser                       sample  315449   3.040 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.787           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.548           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.874           ms/op
