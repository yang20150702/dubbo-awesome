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
# Warmup Iteration   1: 4.946 ops/ms
# Warmup Iteration   2: 12.300 ops/ms
# Warmup Iteration   3: 12.705 ops/ms
Iteration   1: 12.861 ops/ms
Iteration   2: 12.918 ops/ms
Iteration   3: 13.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.957 ±(99.9%) 2.199 ops/ms [Average]
  (min, avg, max) = (12.861, 12.957, 13.093), stdev = 0.121
  CI (99.9%): [10.758, 15.157] (assumes normal distribution)


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
# Warmup Iteration   1: 8.429 ops/ms
# Warmup Iteration   2: 13.321 ops/ms
# Warmup Iteration   3: 13.351 ops/ms
Iteration   1: 13.257 ops/ms
Iteration   2: 13.354 ops/ms
Iteration   3: 13.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.344 ±(99.9%) 1.506 ops/ms [Average]
  (min, avg, max) = (13.257, 13.344, 13.421), stdev = 0.083
  CI (99.9%): [11.838, 14.850] (assumes normal distribution)


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
# Warmup Iteration   1: 8.168 ops/ms
# Warmup Iteration   2: 12.954 ops/ms
# Warmup Iteration   3: 13.031 ops/ms
Iteration   1: 13.150 ops/ms
Iteration   2: 13.240 ops/ms
Iteration   3: 13.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.220 ±(99.9%) 1.140 ops/ms [Average]
  (min, avg, max) = (13.150, 13.220, 13.270), stdev = 0.062
  CI (99.9%): [12.080, 14.359] (assumes normal distribution)


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
# Warmup Iteration   1: 6.594 ops/ms
# Warmup Iteration   2: 10.734 ops/ms
# Warmup Iteration   3: 10.840 ops/ms
Iteration   1: 10.931 ops/ms
Iteration   2: 10.890 ops/ms
Iteration   3: 10.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.936 ±(99.9%) 0.903 ops/ms [Average]
  (min, avg, max) = (10.890, 10.936, 10.988), stdev = 0.049
  CI (99.9%): [10.034, 11.839] (assumes normal distribution)


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
# Warmup Iteration   1: 3.877 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.004 ms/op
Iteration   1: 2.449 ±(99.9%) 0.003 ms/op
Iteration   2: 2.422 ±(99.9%) 0.004 ms/op
Iteration   3: 2.423 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.431 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (2.422, 2.431, 2.449), stdev = 0.015
  CI (99.9%): [2.151, 2.712] (assumes normal distribution)


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
# Warmup Iteration   1: 3.505 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.406 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.381 ±(99.9%) 0.004 ms/op
Iteration   1: 2.382 ±(99.9%) 0.005 ms/op
Iteration   2: 2.381 ±(99.9%) 0.004 ms/op
Iteration   3: 2.364 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.376 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.364, 2.376, 2.382), stdev = 0.010
  CI (99.9%): [2.191, 2.560] (assumes normal distribution)


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
Iteration   1: 2.415 ±(99.9%) 0.003 ms/op
Iteration   2: 2.430 ±(99.9%) 0.003 ms/op
Iteration   3: 2.421 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.422 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (2.415, 2.422, 2.430), stdev = 0.007
  CI (99.9%): [2.292, 2.552] (assumes normal distribution)


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
# Warmup Iteration   1: 4.764 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.978 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.005 ms/op
Iteration   1: 2.900 ±(99.9%) 0.005 ms/op
Iteration   2: 2.905 ±(99.9%) 0.006 ms/op
Iteration   3: 2.909 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.905 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.900, 2.905, 2.909), stdev = 0.005
  CI (99.9%): [2.818, 2.991] (assumes normal distribution)


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.006 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  11.769 ms/op
                 createUser·p0.9999: 13.877 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  7.407 ms/op
                 createUser·p0.9999: 12.648 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  8.211 ms/op
                 createUser·p0.9999: 10.273 ms/op
                 createUser·p1.00:   10.519 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388758
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 192328 
    [ 2.500,  3.750) = 192611 
    [ 3.750,  5.000) = 2897 
    [ 5.000,  6.250) = 333 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     13.322 ms/op
     p(99.9990) =     14.158 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.542 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.420 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.370 ±(99.9%) 0.005 ms/op
Iteration   1: 2.385 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  7.496 ms/op
                 existUser·p0.9999: 14.013 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.383 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  6.959 ms/op
                 existUser·p0.9999: 12.599 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 2.385 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.632 ms/op
                 existUser·p0.999:  9.028 ms/op
                 existUser·p0.9999: 11.743 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 402415
  mean =      2.384 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 207080 
    [ 2.500,  3.750) = 191912 
    [ 3.750,  5.000) = 2364 
    [ 5.000,  6.250) = 469 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 138 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     14.286 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  6.792 ms/op
                 getUser·p0.9999: 13.580 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.135 ms/op
                 getUser·p0.9999: 12.193 ms/op
                 getUser·p1.00:   12.550 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  6.436 ms/op
                 getUser·p0.9999: 11.041 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390669
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 198919 
    [ 2.500,  3.750) = 186244 
    [ 3.750,  5.000) = 4622 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      4.018 ms/op
     p(99.9000) =      6.826 ms/op
     p(99.9900) =     13.120 ms/op
     p(99.9990) =     13.852 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.008 ms/op
Iteration   1: 2.906 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.851 ms/op
                 listUser·p0.90:   3.748 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   5.382 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 10.240 ms/op
                 listUser·p1.00:   10.764 ms/op

Iteration   2: 2.924 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.690 ms/op
                 listUser·p0.50:   2.855 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  8.874 ms/op
                 listUser·p0.9999: 11.356 ms/op
                 listUser·p1.00:   12.091 ms/op

Iteration   3: 2.916 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.777 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.756 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.486 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 11.404 ms/op
                 listUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 328966
  mean =      2.916 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 110434 
    [ 2.500,  3.750) = 184790 
    [ 3.750,  5.000) = 27331 
    [ 5.000,  6.250) = 5186 
    [ 6.250,  7.500) = 407 
    [ 7.500,  8.750) = 230 
    [ 8.750, 10.000) = 308 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     11.274 ms/op
     p(99.9990) =     11.782 ms/op
     p(99.9999) =     12.091 ms/op
    p(100.0000) =     12.091 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.957 ± 2.199  ops/ms
ClientPb.existUser                       thrpt       3  13.344 ± 1.506  ops/ms
ClientPb.getUser                         thrpt       3  13.220 ± 1.140  ops/ms
ClientPb.listUser                        thrpt       3  10.936 ± 0.903  ops/ms
ClientPb.createUser                       avgt       3   2.431 ± 0.280   ms/op
ClientPb.existUser                        avgt       3   2.376 ± 0.184   ms/op
ClientPb.getUser                          avgt       3   2.422 ± 0.130   ms/op
ClientPb.listUser                         avgt       3   2.905 ± 0.086   ms/op
ClientPb.createUser                     sample  388758   2.467 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.735           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.515           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.110           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.322           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.434           ms/op
ClientPb.existUser                      sample  402415   2.384 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.871           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.896           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.782           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.255           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.451           ms/op
ClientPb.getUser                        sample  390669   2.455 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.862           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.462           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.826           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.120           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.992           ms/op
ClientPb.listUser                       sample  328966   2.916 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.690           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.855           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.764           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.274           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.091           ms/op
