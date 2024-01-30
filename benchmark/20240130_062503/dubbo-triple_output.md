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
# Warmup Iteration   1: 5.326 ops/ms
# Warmup Iteration   2: 12.160 ops/ms
# Warmup Iteration   3: 12.454 ops/ms
Iteration   1: 12.699 ops/ms
Iteration   2: 12.932 ops/ms
Iteration   3: 12.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.845 ±(99.9%) 2.314 ops/ms [Average]
  (min, avg, max) = (12.699, 12.845, 12.932), stdev = 0.127
  CI (99.9%): [10.531, 15.158] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 9.068 ops/ms
# Warmup Iteration   2: 13.263 ops/ms
# Warmup Iteration   3: 13.403 ops/ms
Iteration   1: 13.375 ops/ms
Iteration   2: 13.372 ops/ms
Iteration   3: 13.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.459 ±(99.9%) 2.709 ops/ms [Average]
  (min, avg, max) = (13.372, 13.459, 13.631), stdev = 0.148
  CI (99.9%): [10.750, 16.168] (assumes normal distribution)


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
# Warmup Iteration   1: 8.884 ops/ms
# Warmup Iteration   2: 12.999 ops/ms
# Warmup Iteration   3: 13.035 ops/ms
Iteration   1: 13.084 ops/ms
Iteration   2: 13.213 ops/ms
Iteration   3: 13.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.236 ±(99.9%) 3.012 ops/ms [Average]
  (min, avg, max) = (13.084, 13.236, 13.412), stdev = 0.165
  CI (99.9%): [10.224, 16.248] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.927 ops/ms
# Warmup Iteration   2: 10.530 ops/ms
# Warmup Iteration   3: 10.786 ops/ms
Iteration   1: 10.833 ops/ms
Iteration   2: 10.924 ops/ms
Iteration   3: 10.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.896 ±(99.9%) 0.995 ops/ms [Average]
  (min, avg, max) = (10.833, 10.896, 10.931), stdev = 0.055
  CI (99.9%): [9.901, 11.891] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.926 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.448 ±(99.9%) 0.004 ms/op
Iteration   2: 2.442 ±(99.9%) 0.003 ms/op
Iteration   3: 2.447 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.445 ±(99.9%) 0.060 ms/op [Average]
  (min, avg, max) = (2.442, 2.445, 2.448), stdev = 0.003
  CI (99.9%): [2.386, 2.505] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.590 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.389 ±(99.9%) 0.004 ms/op
Iteration   1: 2.383 ±(99.9%) 0.003 ms/op
Iteration   2: 2.346 ±(99.9%) 0.003 ms/op
Iteration   3: 2.391 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.373 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (2.346, 2.373, 2.391), stdev = 0.024
  CI (99.9%): [1.939, 2.808] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.870 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.438 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.467 ±(99.9%) 0.589 ms/op [Average]
  (min, avg, max) = (2.438, 2.467, 2.502), stdev = 0.032
  CI (99.9%): [1.878, 3.056] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.539 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.004 ms/op
Iteration   1: 2.943 ±(99.9%) 0.005 ms/op
Iteration   2: 2.959 ±(99.9%) 0.005 ms/op
Iteration   3: 3.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.969 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (2.943, 2.969, 3.006), stdev = 0.033
  CI (99.9%): [2.374, 3.565] (assumes normal distribution)


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.466 ms/op
                 createUser·p0.90:   2.961 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  5.646 ms/op
                 createUser·p0.9999: 14.871 ms/op
                 createUser·p1.00:   15.450 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.047 ms/op
                 createUser·p0.99:   3.461 ms/op
                 createUser·p0.999:  6.294 ms/op
                 createUser·p0.9999: 12.763 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 11.042 ms/op
                 createUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 392891
  mean =      2.441 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 196120 
    [ 2.500,  3.750) = 193740 
    [ 3.750,  5.000) = 2378 
    [ 5.000,  6.250) = 150 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      8.479 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     15.338 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 3.621 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.407 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.367 ±(99.9%) 0.005 ms/op
Iteration   1: 2.404 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.326 ms/op
                 existUser·p0.999:  5.054 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   2: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.452 ms/op
                 existUser·p0.999:  6.820 ms/op
                 existUser·p0.9999: 14.212 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   3: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  7.832 ms/op
                 existUser·p0.9999: 11.220 ms/op
                 existUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396848
  mean =      2.416 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 197990 
    [ 2.500,  3.750) = 196244 
    [ 3.750,  5.000) = 1899 
    [ 5.000,  6.250) = 211 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =      6.898 ms/op
     p(99.9900) =     12.834 ms/op
     p(99.9990) =     14.747 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.044 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.006 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.539 ms/op
                 getUser·p0.999:  6.555 ms/op
                 getUser·p0.9999: 13.253 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   4.082 ms/op
                 getUser·p0.999:  6.572 ms/op
                 getUser·p0.9999: 12.747 ms/op
                 getUser·p1.00:   12.927 ms/op

Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  7.504 ms/op
                 getUser·p0.9999: 11.219 ms/op
                 getUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392012
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 199806 
    [ 2.500,  3.750) = 188469 
    [ 3.750,  5.000) = 2750 
    [ 5.000,  6.250) = 481 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      7.012 ms/op
     p(99.9900) =     12.809 ms/op
     p(99.9990) =     13.818 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 4.440 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
Iteration   1: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.698 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.773 ms/op
                 listUser·p0.9999: 11.534 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   2: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 11.875 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   3: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.478 ms/op
                 listUser·p0.9999: 10.391 ms/op
                 listUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322108
  mean =      2.978 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 99728 
    [ 2.500,  3.750) = 185078 
    [ 3.750,  5.000) = 29695 
    [ 5.000,  6.250) = 6043 
    [ 6.250,  7.500) = 753 
    [ 7.500,  8.750) = 275 
    [ 8.750, 10.000) = 245 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.204 ms/op
     p(99.9900) =     11.429 ms/op
     p(99.9990) =     12.268 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.845 ± 2.314  ops/ms
ClientPb.existUser                       thrpt       3  13.459 ± 2.709  ops/ms
ClientPb.getUser                         thrpt       3  13.236 ± 3.012  ops/ms
ClientPb.listUser                        thrpt       3  10.896 ± 0.995  ops/ms
ClientPb.createUser                       avgt       3   2.445 ± 0.060   ms/op
ClientPb.existUser                        avgt       3   2.373 ± 0.434   ms/op
ClientPb.getUser                          avgt       3   2.467 ± 0.589   ms/op
ClientPb.listUser                         avgt       3   2.969 ± 0.596   ms/op
ClientPb.createUser                     sample  392891   2.441 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.844           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.503           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.966           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.479           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.911           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.450           ms/op
ClientPb.existUser                      sample  396848   2.416 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.885           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.898           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.834           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.139           ms/op
ClientPb.getUser                        sample  392012   2.447 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.831           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.454           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.978           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.012           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.809           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.336           ms/op
ClientPb.listUser                       sample  322108   2.978 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.698           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.204           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.429           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.501           ms/op
