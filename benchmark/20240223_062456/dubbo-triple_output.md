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
# Warmup Iteration   1: 4.440 ops/ms
# Warmup Iteration   2: 11.712 ops/ms
# Warmup Iteration   3: 12.164 ops/ms
Iteration   1: 12.392 ops/ms
Iteration   2: 12.339 ops/ms
Iteration   3: 12.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.392 ±(99.9%) 0.972 ops/ms [Average]
  (min, avg, max) = (12.339, 12.392, 12.445), stdev = 0.053
  CI (99.9%): [11.420, 13.364] (assumes normal distribution)


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
# Warmup Iteration   1: 8.230 ops/ms
# Warmup Iteration   2: 12.826 ops/ms
# Warmup Iteration   3: 13.162 ops/ms
Iteration   1: 13.055 ops/ms
Iteration   2: 13.172 ops/ms
Iteration   3: 12.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.056 ±(99.9%) 2.095 ops/ms [Average]
  (min, avg, max) = (12.942, 13.056, 13.172), stdev = 0.115
  CI (99.9%): [10.961, 15.151] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.229 ops/ms
# Warmup Iteration   2: 12.213 ops/ms
# Warmup Iteration   3: 12.607 ops/ms
Iteration   1: 12.848 ops/ms
Iteration   2: 12.604 ops/ms
Iteration   3: 12.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.674 ±(99.9%) 2.779 ops/ms [Average]
  (min, avg, max) = (12.568, 12.674, 12.848), stdev = 0.152
  CI (99.9%): [9.895, 15.453] (assumes normal distribution)


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
# Warmup Iteration   1: 6.733 ops/ms
# Warmup Iteration   2: 10.378 ops/ms
# Warmup Iteration   3: 10.574 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.616 ops/ms
Iteration   3: 10.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.602 ±(99.9%) 0.432 ops/ms [Average]
  (min, avg, max) = (10.575, 10.602, 10.616), stdev = 0.024
  CI (99.9%): [10.170, 11.034] (assumes normal distribution)


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.547 ±(99.9%) 0.004 ms/op
Iteration   2: 2.574 ±(99.9%) 0.004 ms/op
Iteration   3: 2.553 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.547, 2.558, 2.574), stdev = 0.014
  CI (99.9%): [2.307, 2.809] (assumes normal distribution)


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.004 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.453 ±(99.9%) 0.003 ms/op
Iteration   3: 2.458 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.447 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (2.430, 2.447, 2.458), stdev = 0.015
  CI (99.9%): [2.172, 2.721] (assumes normal distribution)


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
# Warmup Iteration   1: 4.057 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.494 ±(99.9%) 0.004 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.496 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (2.471, 2.496, 2.524), stdev = 0.027
  CI (99.9%): [2.008, 2.985] (assumes normal distribution)


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
# Warmup Iteration   1: 4.729 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
Iteration   1: 2.990 ±(99.9%) 0.005 ms/op
Iteration   2: 2.978 ±(99.9%) 0.005 ms/op
Iteration   3: 3.041 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.003 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (2.978, 3.003, 3.041), stdev = 0.034
  CI (99.9%): [2.385, 3.621] (assumes normal distribution)


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
Iteration   1: 2.539 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  11.710 ms/op
                 createUser·p0.9999: 14.609 ms/op
                 createUser·p1.00:   15.745 ms/op

Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  9.530 ms/op
                 createUser·p0.9999: 11.870 ms/op
                 createUser·p1.00:   12.468 ms/op

Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  9.192 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377260
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180655 
    [ 2.500,  5.000) = 195840 
    [ 5.000,  7.500) = 356 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     15.143 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  6.125 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  8.092 ms/op
                 existUser·p0.9999: 13.796 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.834 ms/op
                 existUser·p0.999:  6.319 ms/op
                 existUser·p0.9999: 13.894 ms/op
                 existUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390323
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 195735 
    [ 2.500,  3.750) = 190719 
    [ 3.750,  5.000) = 2888 
    [ 5.000,  6.250) = 507 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      6.786 ms/op
     p(99.9900) =     13.909 ms/op
     p(99.9990) =     14.555 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.517 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  11.633 ms/op
                 getUser·p0.9999: 14.803 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.030 ms/op
                 getUser·p0.999:  9.472 ms/op
                 getUser·p0.9999: 14.468 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  8.303 ms/op
                 getUser·p0.9999: 10.924 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380550
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 186947 
    [ 2.500,  3.750) = 189260 
    [ 3.750,  5.000) = 3525 
    [ 5.000,  6.250) = 360 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.420 ms/op
     p(99.9900) =     14.254 ms/op
     p(99.9990) =     15.289 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 4.782 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.722 ms/op
                 listUser·p0.9999: 11.094 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   2: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.349 ms/op
                 listUser·p0.999:  10.100 ms/op
                 listUser·p0.9999: 11.665 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.812 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.340 ms/op
                 listUser·p0.9999: 10.689 ms/op
                 listUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318714
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 90129 
    [ 2.500,  3.750) = 190297 
    [ 3.750,  5.000) = 31423 
    [ 5.000,  6.250) = 5550 
    [ 6.250,  7.500) = 552 
    [ 7.500,  8.750) = 178 
    [ 8.750, 10.000) = 204 
    [10.000, 11.250) = 235 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     11.405 ms/op
     p(99.9990) =     11.811 ms/op
     p(99.9999) =     11.928 ms/op
    p(100.0000) =     11.928 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.392 ± 0.972  ops/ms
ClientPb.existUser                       thrpt       3  13.056 ± 2.095  ops/ms
ClientPb.getUser                         thrpt       3  12.674 ± 2.779  ops/ms
ClientPb.listUser                        thrpt       3  10.602 ± 0.432  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.251   ms/op
ClientPb.existUser                        avgt       3   2.447 ± 0.275   ms/op
ClientPb.getUser                          avgt       3   2.496 ± 0.489   ms/op
ClientPb.listUser                         avgt       3   3.003 ± 0.618   ms/op
ClientPb.createUser                     sample  377260   2.542 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.881           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.224           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.143           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.725           ms/op
ClientPb.existUser                      sample  390323   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.556           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.786           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.909           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.630           ms/op
ClientPb.getUser                        sample  380550   2.520 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.937           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.420           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.254           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.466           ms/op
ClientPb.listUser                       sample  318714   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.812           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.650           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.405           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.928           ms/op
