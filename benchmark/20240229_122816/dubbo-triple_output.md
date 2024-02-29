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
# Warmup Iteration   1: 4.632 ops/ms
# Warmup Iteration   2: 12.481 ops/ms
# Warmup Iteration   3: 12.678 ops/ms
Iteration   1: 12.910 ops/ms
Iteration   2: 12.932 ops/ms
Iteration   3: 12.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.895 ±(99.9%) 0.846 ops/ms [Average]
  (min, avg, max) = (12.843, 12.895, 12.932), stdev = 0.046
  CI (99.9%): [12.049, 13.741] (assumes normal distribution)


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
# Warmup Iteration   1: 8.421 ops/ms
# Warmup Iteration   2: 13.187 ops/ms
# Warmup Iteration   3: 13.380 ops/ms
Iteration   1: 13.345 ops/ms
Iteration   2: 13.352 ops/ms
Iteration   3: 13.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.367 ±(99.9%) 0.592 ops/ms [Average]
  (min, avg, max) = (13.345, 13.367, 13.404), stdev = 0.032
  CI (99.9%): [12.775, 13.959] (assumes normal distribution)


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
# Warmup Iteration   1: 8.111 ops/ms
# Warmup Iteration   2: 12.864 ops/ms
# Warmup Iteration   3: 13.192 ops/ms
Iteration   1: 13.391 ops/ms
Iteration   2: 13.197 ops/ms
Iteration   3: 13.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.317 ±(99.9%) 1.919 ops/ms [Average]
  (min, avg, max) = (13.197, 13.317, 13.391), stdev = 0.105
  CI (99.9%): [11.399, 15.236] (assumes normal distribution)


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
# Warmup Iteration   1: 6.940 ops/ms
# Warmup Iteration   2: 10.490 ops/ms
# Warmup Iteration   3: 10.813 ops/ms
Iteration   1: 10.921 ops/ms
Iteration   2: 10.847 ops/ms
Iteration   3: 10.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.877 ±(99.9%) 0.709 ops/ms [Average]
  (min, avg, max) = (10.847, 10.877, 10.921), stdev = 0.039
  CI (99.9%): [10.168, 11.585] (assumes normal distribution)


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.004 ms/op
Iteration   1: 2.447 ±(99.9%) 0.003 ms/op
Iteration   2: 2.434 ±(99.9%) 0.003 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.447 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.434, 2.447, 2.460), stdev = 0.013
  CI (99.9%): [2.208, 2.686] (assumes normal distribution)


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.405 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.391 ±(99.9%) 0.004 ms/op
Iteration   1: 2.392 ±(99.9%) 0.004 ms/op
Iteration   2: 2.369 ±(99.9%) 0.003 ms/op
Iteration   3: 2.382 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.381 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (2.369, 2.381, 2.392), stdev = 0.012
  CI (99.9%): [2.168, 2.595] (assumes normal distribution)


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.003 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.451 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.457 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.451, 2.457, 2.468), stdev = 0.009
  CI (99.9%): [2.294, 2.621] (assumes normal distribution)


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
# Warmup Iteration   1: 4.737 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
Iteration   3: 2.980 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.990 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.980, 2.990, 3.002), stdev = 0.011
  CI (99.9%): [2.783, 3.198] (assumes normal distribution)


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  9.900 ms/op
                 createUser·p0.9999: 14.197 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.428 ms/op
                 createUser·p0.999:  6.939 ms/op
                 createUser·p0.9999: 13.619 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.043 ms/op
                 createUser·p0.999:  8.784 ms/op
                 createUser·p0.9999: 11.403 ms/op
                 createUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383065
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 188090 
    [ 2.500,  3.750) = 191287 
    [ 3.750,  5.000) = 2958 
    [ 5.000,  6.250) = 267 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 123 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      8.764 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.666 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.418 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  5.964 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  7.147 ms/op
                 existUser·p0.9999: 13.906 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   3: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.830 ms/op
                 existUser·p0.999:  8.333 ms/op
                 existUser·p0.9999: 13.225 ms/op
                 existUser·p1.00:   14.959 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395189
  mean =      2.426 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 199811 
    [ 2.500,  3.750) = 191361 
    [ 3.750,  5.000) = 2929 
    [ 5.000,  6.250) = 557 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      7.199 ms/op
     p(99.9900) =     13.820 ms/op
     p(99.9990) =     14.764 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.841 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  7.217 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  6.100 ms/op
                 getUser·p0.9999: 12.714 ms/op
                 getUser·p1.00:   13.615 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.761 ms/op
                 getUser·p0.999:  6.933 ms/op
                 getUser·p0.9999: 12.977 ms/op
                 getUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388714
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 195760 
    [ 2.500,  3.750) = 188427 
    [ 3.750,  5.000) = 3658 
    [ 5.000,  6.250) = 384 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 126 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      6.482 ms/op
     p(99.9900) =     13.306 ms/op
     p(99.9990) =     13.799 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.008 ms/op
Iteration   1: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.528 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 10.276 ms/op
                 listUser·p1.00:   11.338 ms/op

Iteration   2: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  10.001 ms/op
                 listUser·p0.9999: 12.226 ms/op
                 listUser·p1.00:   12.780 ms/op

Iteration   3: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.420 ms/op
                 listUser·p0.999:  9.219 ms/op
                 listUser·p0.9999: 11.616 ms/op
                 listUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322908
  mean =      2.970 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 99393 
    [ 2.500,  3.750) = 186465 
    [ 3.750,  5.000) = 30303 
    [ 5.000,  6.250) = 5349 
    [ 6.250,  7.500) = 579 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 307 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     11.616 ms/op
     p(99.9990) =     12.552 ms/op
     p(99.9999) =     12.780 ms/op
    p(100.0000) =     12.780 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.895 ± 0.846  ops/ms
ClientPb.existUser                       thrpt       3  13.367 ± 0.592  ops/ms
ClientPb.getUser                         thrpt       3  13.317 ± 1.919  ops/ms
ClientPb.listUser                        thrpt       3  10.877 ± 0.709  ops/ms
ClientPb.createUser                       avgt       3   2.447 ± 0.239   ms/op
ClientPb.existUser                        avgt       3   2.381 ± 0.213   ms/op
ClientPb.getUser                          avgt       3   2.457 ± 0.163   ms/op
ClientPb.listUser                         avgt       3   2.990 ± 0.207   ms/op
ClientPb.createUser                     sample  383065   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.811           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.764           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.106           ms/op
ClientPb.existUser                      sample  395189   2.426 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.812           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.199           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.820           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.959           ms/op
ClientPb.getUser                        sample  388714   2.467 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.723           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.482           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.306           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.025           ms/op
ClientPb.listUser                       sample  322908   2.970 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.810           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.616           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.780           ms/op
