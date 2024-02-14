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
# Warmup Iteration   1: 4.995 ops/ms
# Warmup Iteration   2: 12.249 ops/ms
# Warmup Iteration   3: 12.321 ops/ms
Iteration   1: 12.635 ops/ms
Iteration   2: 12.432 ops/ms
Iteration   3: 12.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.596 ±(99.9%) 2.705 ops/ms [Average]
  (min, avg, max) = (12.432, 12.596, 12.721), stdev = 0.148
  CI (99.9%): [9.891, 15.300] (assumes normal distribution)


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
# Warmup Iteration   1: 8.275 ops/ms
# Warmup Iteration   2: 13.006 ops/ms
# Warmup Iteration   3: 12.937 ops/ms
Iteration   1: 13.491 ops/ms
Iteration   2: 13.289 ops/ms
Iteration   3: 13.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.440 ±(99.9%) 2.445 ops/ms [Average]
  (min, avg, max) = (13.289, 13.440, 13.542), stdev = 0.134
  CI (99.9%): [10.996, 15.885] (assumes normal distribution)


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
# Warmup Iteration   1: 7.892 ops/ms
# Warmup Iteration   2: 12.312 ops/ms
# Warmup Iteration   3: 12.727 ops/ms
Iteration   1: 12.901 ops/ms
Iteration   2: 12.667 ops/ms
Iteration   3: 12.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.783 ±(99.9%) 2.127 ops/ms [Average]
  (min, avg, max) = (12.667, 12.783, 12.901), stdev = 0.117
  CI (99.9%): [10.656, 14.910] (assumes normal distribution)


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
# Warmup Iteration   1: 6.677 ops/ms
# Warmup Iteration   2: 10.514 ops/ms
# Warmup Iteration   3: 10.635 ops/ms
Iteration   1: 10.669 ops/ms
Iteration   2: 10.683 ops/ms
Iteration   3: 10.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.691 ±(99.9%) 0.502 ops/ms [Average]
  (min, avg, max) = (10.669, 10.691, 10.722), stdev = 0.027
  CI (99.9%): [10.190, 11.193] (assumes normal distribution)


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
# Warmup Iteration   1: 3.888 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.003 ms/op
Iteration   1: 2.549 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
Iteration   3: 2.545 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.526, 2.540, 2.549), stdev = 0.012
  CI (99.9%): [2.314, 2.765] (assumes normal distribution)


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
# Warmup Iteration   1: 3.533 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
Iteration   3: 2.436 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.438 ±(99.9%) 0.112 ms/op [Average]
  (min, avg, max) = (2.433, 2.438, 2.445), stdev = 0.006
  CI (99.9%): [2.326, 2.550] (assumes normal distribution)


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
# Warmup Iteration   1: 3.920 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
Iteration   1: 2.524 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.514 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.500, 2.514, 2.524), stdev = 0.012
  CI (99.9%): [2.286, 2.741] (assumes normal distribution)


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.939 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.008 ms/op
Iteration   1: 2.947 ±(99.9%) 0.006 ms/op
Iteration   2: 2.960 ±(99.9%) 0.008 ms/op
Iteration   3: 3.006 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.971 ±(99.9%) 0.558 ms/op [Average]
  (min, avg, max) = (2.947, 2.971, 3.006), stdev = 0.031
  CI (99.9%): [2.414, 3.529] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.538 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  11.600 ms/op
                 createUser·p0.9999: 13.258 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.389 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  10.505 ms/op
                 createUser·p0.9999: 13.619 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  8.124 ms/op
                 createUser·p0.9999: 10.359 ms/op
                 createUser·p1.00:   10.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380598
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 182961 
    [ 2.500,  3.750) = 192832 
    [ 3.750,  5.000) = 3416 
    [ 5.000,  6.250) = 763 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.389 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      9.083 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     14.385 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.646 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.881 ms/op
                 existUser·p0.999:  9.539 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  5.826 ms/op
                 existUser·p0.9999: 13.586 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  7.102 ms/op
                 existUser·p0.9999: 11.960 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389075
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 190597 
    [ 2.500,  3.750) = 194365 
    [ 3.750,  5.000) = 3148 
    [ 5.000,  6.250) = 522 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      6.545 ms/op
     p(99.9900) =     13.240 ms/op
     p(99.9990) =     14.780 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.891 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.535 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.083 ms/op
                 getUser·p0.999:  11.221 ms/op
                 getUser·p0.9999: 13.619 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  9.963 ms/op
                 getUser·p0.9999: 14.090 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  8.503 ms/op
                 getUser·p0.9999: 11.600 ms/op
                 getUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380328
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 187334 
    [ 2.500,  3.750) = 187748 
    [ 3.750,  5.000) = 3879 
    [ 5.000,  6.250) = 861 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 135 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.981 ms/op
     p(99.9000) =      8.838 ms/op
     p(99.9900) =     13.549 ms/op
     p(99.9990) =     14.647 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 4.789 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.009 ms/op
Iteration   1: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.466 ms/op
                 listUser·p1.00:   10.977 ms/op

Iteration   2: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.590 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.880 ms/op
                 listUser·p0.9999: 11.654 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.515 ms/op
                 listUser·p0.9999: 10.869 ms/op
                 listUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319003
  mean =      3.007 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 92016 
    [ 2.500,  3.750) = 188098 
    [ 3.750,  5.000) = 31602 
    [ 5.000,  6.250) = 5745 
    [ 6.250,  7.500) = 701 
    [ 7.500,  8.750) = 252 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     11.141 ms/op
     p(99.9990) =     12.233 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.596 ± 2.705  ops/ms
ClientPb.existUser                       thrpt       3  13.440 ± 2.445  ops/ms
ClientPb.getUser                         thrpt       3  12.783 ± 2.127  ops/ms
ClientPb.listUser                        thrpt       3  10.691 ± 0.502  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.226   ms/op
ClientPb.existUser                        avgt       3   2.438 ± 0.112   ms/op
ClientPb.getUser                          avgt       3   2.514 ± 0.228   ms/op
ClientPb.listUser                         avgt       3   2.971 ± 0.558   ms/op
ClientPb.createUser                     sample  380598   2.520 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.389           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.083           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.238           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.451           ms/op
ClientPb.existUser                      sample  389075   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.695           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.545           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.240           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.942           ms/op
ClientPb.getUser                        sample  380328   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.922           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.838           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.549           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.991           ms/op
ClientPb.listUser                       sample  319003   3.007 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.590           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.141           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.419           ms/op
