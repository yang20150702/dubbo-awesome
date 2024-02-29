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
# Warmup Iteration   1: 4.810 ops/ms
# Warmup Iteration   2: 12.254 ops/ms
# Warmup Iteration   3: 12.370 ops/ms
Iteration   1: 12.730 ops/ms
Iteration   2: 12.796 ops/ms
Iteration   3: 12.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.766 ±(99.9%) 0.604 ops/ms [Average]
  (min, avg, max) = (12.730, 12.766, 12.796), stdev = 0.033
  CI (99.9%): [12.162, 13.370] (assumes normal distribution)


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
# Warmup Iteration   1: 8.199 ops/ms
# Warmup Iteration   2: 13.252 ops/ms
# Warmup Iteration   3: 13.212 ops/ms
Iteration   1: 13.363 ops/ms
Iteration   2: 13.348 ops/ms
Iteration   3: 13.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.288 ±(99.9%) 2.129 ops/ms [Average]
  (min, avg, max) = (13.154, 13.288, 13.363), stdev = 0.117
  CI (99.9%): [11.159, 15.417] (assumes normal distribution)


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
# Warmup Iteration   1: 7.711 ops/ms
# Warmup Iteration   2: 12.566 ops/ms
# Warmup Iteration   3: 12.870 ops/ms
Iteration   1: 12.975 ops/ms
Iteration   2: 13.034 ops/ms
Iteration   3: 13.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.020 ±(99.9%) 0.727 ops/ms [Average]
  (min, avg, max) = (12.975, 13.020, 13.050), stdev = 0.040
  CI (99.9%): [12.293, 13.747] (assumes normal distribution)


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
# Warmup Iteration   1: 6.964 ops/ms
# Warmup Iteration   2: 10.515 ops/ms
# Warmup Iteration   3: 10.596 ops/ms
Iteration   1: 10.723 ops/ms
Iteration   2: 10.629 ops/ms
Iteration   3: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.690 ±(99.9%) 0.969 ops/ms [Average]
  (min, avg, max) = (10.629, 10.690, 10.723), stdev = 0.053
  CI (99.9%): [9.721, 11.659] (assumes normal distribution)


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.533 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.515 ±(99.9%) 0.392 ms/op [Average]
  (min, avg, max) = (2.491, 2.515, 2.533), stdev = 0.022
  CI (99.9%): [2.122, 2.907] (assumes normal distribution)


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
# Warmup Iteration   1: 3.575 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.397 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.004 ms/op
Iteration   1: 2.404 ±(99.9%) 0.003 ms/op
Iteration   2: 2.377 ±(99.9%) 0.004 ms/op
Iteration   3: 2.403 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.395 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.377, 2.395, 2.404), stdev = 0.015
  CI (99.9%): [2.114, 2.675] (assumes normal distribution)


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
# Warmup Iteration   1: 3.727 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.003 ms/op
Iteration   1: 2.465 ±(99.9%) 0.003 ms/op
Iteration   2: 2.453 ±(99.9%) 0.003 ms/op
Iteration   3: 2.459 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.459 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (2.453, 2.459, 2.465), stdev = 0.006
  CI (99.9%): [2.352, 2.565] (assumes normal distribution)


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.007 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
Iteration   2: 2.970 ±(99.9%) 0.005 ms/op
Iteration   3: 2.967 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.973 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.967, 2.973, 2.983), stdev = 0.009
  CI (99.9%): [2.815, 3.132] (assumes normal distribution)


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.678 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.536 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  11.205 ms/op
                 createUser·p0.9999: 13.074 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.568 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 12.608 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  7.830 ms/op
                 createUser·p0.9999: 9.883 ms/op
                 createUser·p1.00:   14.959 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382749
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 185047 
    [ 2.500,  3.750) = 193021 
    [ 3.750,  5.000) = 3545 
    [ 5.000,  6.250) = 607 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      8.262 ms/op
     p(99.9900) =     12.906 ms/op
     p(99.9990) =     13.629 ms/op
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
# Warmup Iteration   1: 3.736 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  5.934 ms/op
                 existUser·p0.9999: 13.741 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  5.804 ms/op
                 existUser·p0.9999: 13.775 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  7.436 ms/op
                 existUser·p0.9999: 11.384 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396038
  mean =      2.421 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 202185 
    [ 2.500,  3.750) = 190736 
    [ 3.750,  5.000) = 2393 
    [ 5.000,  6.250) = 252 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 131 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.354 ms/op
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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  11.734 ms/op
                 getUser·p0.9999: 15.996 ms/op
                 getUser·p1.00:   16.482 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  6.350 ms/op
                 getUser·p0.9999: 15.002 ms/op
                 getUser·p1.00:   15.876 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.018 ms/op
                 getUser·p0.999:  8.972 ms/op
                 getUser·p0.9999: 13.253 ms/op
                 getUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382744
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 189814 
    [ 2.500,  3.750) = 187471 
    [ 3.750,  5.000) = 4072 
    [ 5.000,  6.250) = 920 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.971 ms/op
     p(99.9000) =      6.455 ms/op
     p(99.9900) =     15.478 ms/op
     p(99.9990) =     16.207 ms/op
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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.682 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
Iteration   1: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 11.915 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   2: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 11.391 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.611 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 11.665 ms/op
                 listUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321400
  mean =      2.984 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 96783 
    [ 2.500,  3.750) = 185593 
    [ 3.750,  5.000) = 31627 
    [ 5.000,  6.250) = 5892 
    [ 6.250,  7.500) = 739 
    [ 7.500,  8.750) = 263 
    [ 8.750, 10.000) = 166 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     11.583 ms/op
     p(99.9990) =     12.503 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.766 ± 0.604  ops/ms
ClientPb.existUser                       thrpt       3  13.288 ± 2.129  ops/ms
ClientPb.getUser                         thrpt       3  13.020 ± 0.727  ops/ms
ClientPb.listUser                        thrpt       3  10.690 ± 0.969  ops/ms
ClientPb.createUser                       avgt       3   2.515 ± 0.392   ms/op
ClientPb.existUser                        avgt       3   2.395 ± 0.281   ms/op
ClientPb.getUser                          avgt       3   2.459 ± 0.107   ms/op
ClientPb.listUser                         avgt       3   2.973 ± 0.158   ms/op
ClientPb.createUser                     sample  382749   2.505 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.951           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.262           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.906           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.959           ms/op
ClientPb.existUser                      sample  396038   2.421 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.835           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.458           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.726           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.582           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.500           ms/op
ClientPb.getUser                        sample  382744   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.720           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.971           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.455           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.478           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.482           ms/op
ClientPb.listUser                       sample  321400   2.984 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.827           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.583           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.665           ms/op
