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
# Warmup Iteration   1: 5.305 ops/ms
# Warmup Iteration   2: 12.358 ops/ms
# Warmup Iteration   3: 12.450 ops/ms
Iteration   1: 12.683 ops/ms
Iteration   2: 12.594 ops/ms
Iteration   3: 12.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.728 ±(99.9%) 2.947 ops/ms [Average]
  (min, avg, max) = (12.594, 12.728, 12.907), stdev = 0.162
  CI (99.9%): [9.781, 15.675] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.209 ops/ms
# Warmup Iteration   2: 13.335 ops/ms
# Warmup Iteration   3: 13.442 ops/ms
Iteration   1: 13.240 ops/ms
Iteration   2: 13.444 ops/ms
Iteration   3: 13.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.301 ±(99.9%) 2.252 ops/ms [Average]
  (min, avg, max) = (13.221, 13.301, 13.444), stdev = 0.123
  CI (99.9%): [11.049, 15.554] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.825 ops/ms
# Warmup Iteration   2: 12.789 ops/ms
# Warmup Iteration   3: 13.099 ops/ms
Iteration   1: 13.046 ops/ms
Iteration   2: 12.713 ops/ms
Iteration   3: 13.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.950 ±(99.9%) 3.763 ops/ms [Average]
  (min, avg, max) = (12.713, 12.950, 13.090), stdev = 0.206
  CI (99.9%): [9.186, 16.713] (assumes normal distribution)


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
# Warmup Iteration   1: 6.987 ops/ms
# Warmup Iteration   2: 10.839 ops/ms
# Warmup Iteration   3: 10.809 ops/ms
Iteration   1: 10.903 ops/ms
Iteration   2: 11.001 ops/ms
Iteration   3: 10.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.946 ±(99.9%) 0.909 ops/ms [Average]
  (min, avg, max) = (10.903, 10.946, 11.001), stdev = 0.050
  CI (99.9%): [10.036, 11.855] (assumes normal distribution)


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.003 ms/op
Iteration   1: 2.470 ±(99.9%) 0.003 ms/op
Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.498 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (2.470, 2.498, 2.523), stdev = 0.026
  CI (99.9%): [2.015, 2.981] (assumes normal distribution)


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.424 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.004 ms/op
Iteration   1: 2.413 ±(99.9%) 0.004 ms/op
Iteration   2: 2.394 ±(99.9%) 0.004 ms/op
Iteration   3: 2.399 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.402 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (2.394, 2.402, 2.413), stdev = 0.010
  CI (99.9%): [2.224, 2.579] (assumes normal distribution)


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.416 ±(99.9%) 0.005 ms/op
Iteration   3: 2.433 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.424 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.416, 2.424, 2.433), stdev = 0.008
  CI (99.9%): [2.272, 2.576] (assumes normal distribution)


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
# Warmup Iteration   1: 4.658 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
Iteration   1: 2.924 ±(99.9%) 0.005 ms/op
Iteration   2: 2.923 ±(99.9%) 0.007 ms/op
Iteration   3: 2.940 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.929 ±(99.9%) 0.169 ms/op [Average]
  (min, avg, max) = (2.923, 2.929, 2.940), stdev = 0.009
  CI (99.9%): [2.760, 3.097] (assumes normal distribution)


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  6.777 ms/op
                 createUser·p0.9999: 13.437 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.490 ms/op
                 createUser·p0.999:  5.494 ms/op
                 createUser·p0.9999: 12.925 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.508 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  8.249 ms/op
                 createUser·p0.9999: 11.595 ms/op
                 createUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387985
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 191433 
    [ 2.500,  3.750) = 192768 
    [ 3.750,  5.000) = 2832 
    [ 5.000,  6.250) = 389 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.241 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     13.685 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.410 ±(99.9%) 0.005 ms/op
Iteration   1: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.293 ms/op
                 existUser·p0.999:  5.519 ms/op
                 existUser·p0.9999: 13.705 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.346 ms/op
                 existUser·p0.999:  6.957 ms/op
                 existUser·p0.9999: 12.694 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  8.864 ms/op
                 existUser·p0.9999: 11.265 ms/op
                 existUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395944
  mean =      2.422 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 197192 
    [ 2.500,  3.750) = 196382 
    [ 3.750,  5.000) = 1659 
    [ 5.000,  6.250) = 230 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.408 ms/op
     p(99.9000) =      8.635 ms/op
     p(99.9900) =     13.101 ms/op
     p(99.9990) =     14.402 ms/op
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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.039 ms/op
                 getUser·p0.99:   3.408 ms/op
                 getUser·p0.999:  5.478 ms/op
                 getUser·p0.9999: 13.074 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.628 ms/op
                 getUser·p0.999:  6.995 ms/op
                 getUser·p0.9999: 10.620 ms/op
                 getUser·p1.00:   11.289 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  9.443 ms/op
                 getUser·p0.9999: 11.552 ms/op
                 getUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391731
  mean =      2.448 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 198282 
    [ 2.500,  3.750) = 190015 
    [ 3.750,  5.000) = 2515 
    [ 5.000,  6.250) = 350 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     12.490 ms/op
     p(99.9990) =     13.420 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


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
# Warmup Iteration   1: 4.595 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.008 ms/op
Iteration   1: 2.961 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.684 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.585 ms/op
                 listUser·p0.9999: 10.263 ms/op
                 listUser·p1.00:   11.682 ms/op

Iteration   2: 2.944 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 10.846 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   3: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 10.724 ms/op
                 listUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324028
  mean =      2.961 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 103677 
    [ 2.500,  3.750) = 184463 
    [ 3.750,  5.000) = 29146 
    [ 5.000,  6.250) = 5177 
    [ 6.250,  7.500) = 718 
    [ 7.500,  8.750) = 330 
    [ 8.750, 10.000) = 256 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     10.725 ms/op
     p(99.9990) =     11.534 ms/op
     p(99.9999) =     11.682 ms/op
    p(100.0000) =     11.682 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.728 ± 2.947  ops/ms
ClientPb.existUser                       thrpt       3  13.301 ± 2.252  ops/ms
ClientPb.getUser                         thrpt       3  12.950 ± 3.763  ops/ms
ClientPb.listUser                        thrpt       3  10.946 ± 0.909  ops/ms
ClientPb.createUser                       avgt       3   2.498 ± 0.483   ms/op
ClientPb.existUser                        avgt       3   2.402 ± 0.178   ms/op
ClientPb.getUser                          avgt       3   2.424 ± 0.152   ms/op
ClientPb.listUser                         avgt       3   2.929 ± 0.169   ms/op
ClientPb.createUser                     sample  387985   2.472 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.508           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.531           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.241           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.943           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.022           ms/op
ClientPb.existUser                      sample  395944   2.422 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.833           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.635           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.101           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.500           ms/op
ClientPb.getUser                        sample  391731   2.448 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.695           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.458           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.978           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.666           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.651           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.490           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.582           ms/op
ClientPb.listUser                       sample  324028   2.961 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.684           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.897           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.725           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.682           ms/op
