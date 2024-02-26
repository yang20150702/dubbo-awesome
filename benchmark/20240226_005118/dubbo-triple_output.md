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
# Warmup Iteration   2: 11.709 ops/ms
# Warmup Iteration   3: 12.096 ops/ms
Iteration   1: 12.563 ops/ms
Iteration   2: 12.289 ops/ms
Iteration   3: 12.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.477 ±(99.9%) 2.980 ops/ms [Average]
  (min, avg, max) = (12.289, 12.477, 12.580), stdev = 0.163
  CI (99.9%): [9.497, 15.457] (assumes normal distribution)


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
# Warmup Iteration   1: 8.487 ops/ms
# Warmup Iteration   2: 13.287 ops/ms
# Warmup Iteration   3: 13.127 ops/ms
Iteration   1: 13.124 ops/ms
Iteration   2: 13.080 ops/ms
Iteration   3: 12.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.043 ±(99.9%) 1.899 ops/ms [Average]
  (min, avg, max) = (12.926, 13.043, 13.124), stdev = 0.104
  CI (99.9%): [11.145, 14.942] (assumes normal distribution)


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
# Warmup Iteration   1: 7.295 ops/ms
# Warmup Iteration   2: 12.630 ops/ms
# Warmup Iteration   3: 12.772 ops/ms
Iteration   1: 12.719 ops/ms
Iteration   2: 12.913 ops/ms
Iteration   3: 12.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.820 ±(99.9%) 1.782 ops/ms [Average]
  (min, avg, max) = (12.719, 12.820, 12.913), stdev = 0.098
  CI (99.9%): [11.038, 14.602] (assumes normal distribution)


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
# Warmup Iteration   1: 6.496 ops/ms
# Warmup Iteration   2: 10.379 ops/ms
# Warmup Iteration   3: 10.398 ops/ms
Iteration   1: 10.552 ops/ms
Iteration   2: 10.554 ops/ms
Iteration   3: 10.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.557 ±(99.9%) 0.141 ops/ms [Average]
  (min, avg, max) = (10.552, 10.557, 10.566), stdev = 0.008
  CI (99.9%): [10.416, 10.698] (assumes normal distribution)


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
Iteration   1: 2.523 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
Iteration   3: 2.542 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.519 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (2.491, 2.519, 2.542), stdev = 0.026
  CI (99.9%): [2.051, 2.986] (assumes normal distribution)


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.004 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.446 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (2.435, 2.446, 2.460), stdev = 0.013
  CI (99.9%): [2.212, 2.680] (assumes normal distribution)


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.503 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (2.489, 2.503, 2.514), stdev = 0.013
  CI (99.9%): [2.267, 2.740] (assumes normal distribution)


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
# Warmup Iteration   1: 4.816 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.005 ms/op
Iteration   1: 3.019 ±(99.9%) 0.006 ms/op
Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
Iteration   3: 3.030 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.025 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (3.019, 3.025, 3.030), stdev = 0.005
  CI (99.9%): [2.926, 3.124] (assumes normal distribution)


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
# Warmup Iteration   1: 4.340 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  11.783 ms/op
                 createUser·p0.9999: 13.396 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.666 ms/op
                 createUser·p0.999:  9.765 ms/op
                 createUser·p0.9999: 12.792 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   3: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.985 ms/op
                 createUser·p0.999:  8.173 ms/op
                 createUser·p0.9999: 11.141 ms/op
                 createUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377871
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 179694 
    [ 2.500,  3.750) = 193918 
    [ 3.750,  5.000) = 3376 
    [ 5.000,  6.250) = 357 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      8.409 ms/op
     p(99.9900) =     13.131 ms/op
     p(99.9990) =     13.651 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 3.778 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
Iteration   1: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.445 ms/op
                 existUser·p0.999:  6.170 ms/op
                 existUser·p0.9999: 13.822 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  5.431 ms/op
                 existUser·p0.9999: 14.074 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  7.924 ms/op
                 existUser·p0.9999: 11.649 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392447
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 196091 
    [ 2.500,  3.750) = 193063 
    [ 3.750,  5.000) = 2409 
    [ 5.000,  6.250) = 436 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      6.239 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     14.998 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  8.189 ms/op
                 getUser·p0.9999: 13.500 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  9.007 ms/op
                 getUser·p0.9999: 12.747 ms/op
                 getUser·p1.00:   13.353 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  7.395 ms/op
                 getUser·p0.9999: 11.059 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384000
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 189175 
    [ 2.500,  3.750) = 188801 
    [ 3.750,  5.000) = 3982 
    [ 5.000,  6.250) = 1370 
    [ 6.250,  7.500) = 159 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     13.732 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.734 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.009 ms/op
Iteration   1: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.810 ms/op
                 listUser·p0.9999: 10.182 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   2: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 11.256 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.216 ms/op
                 listUser·p0.9999: 11.174 ms/op
                 listUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316889
  mean =      3.027 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 87615 
    [ 2.500,  3.750) = 189198 
    [ 3.750,  5.000) = 33138 
    [ 5.000,  6.250) = 5629 
    [ 6.250,  7.500) = 593 
    [ 7.500,  8.750) = 178 
    [ 8.750, 10.000) = 244 
    [10.000, 11.250) = 167 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.048 ms/op
     p(99.9990) =     11.728 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.477 ± 2.980  ops/ms
ClientPb.existUser                       thrpt       3  13.043 ± 1.899  ops/ms
ClientPb.getUser                         thrpt       3  12.820 ± 1.782  ops/ms
ClientPb.listUser                        thrpt       3  10.557 ± 0.141  ops/ms
ClientPb.createUser                       avgt       3   2.519 ± 0.468   ms/op
ClientPb.existUser                        avgt       3   2.446 ± 0.234   ms/op
ClientPb.getUser                          avgt       3   2.503 ± 0.236   ms/op
ClientPb.listUser                         avgt       3   3.025 ± 0.099   ms/op
ClientPb.createUser                     sample  377871   2.538 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.047           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.409           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.131           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.074           ms/op
ClientPb.existUser                      sample  392447   2.443 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.712           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.239           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.730           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.155           ms/op
ClientPb.getUser                        sample  384000   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.927           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.978           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.943           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.910           ms/op
ClientPb.listUser                       sample  316889   3.027 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.820           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.048           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.632           ms/op
