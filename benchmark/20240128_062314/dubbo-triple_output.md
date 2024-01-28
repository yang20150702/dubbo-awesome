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
# Warmup Iteration   1: 4.679 ops/ms
# Warmup Iteration   2: 11.858 ops/ms
# Warmup Iteration   3: 12.154 ops/ms
Iteration   1: 12.363 ops/ms
Iteration   2: 12.460 ops/ms
Iteration   3: 12.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.480 ±(99.9%) 2.329 ops/ms [Average]
  (min, avg, max) = (12.363, 12.480, 12.616), stdev = 0.128
  CI (99.9%): [10.151, 14.809] (assumes normal distribution)


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
# Warmup Iteration   1: 8.353 ops/ms
# Warmup Iteration   2: 13.203 ops/ms
# Warmup Iteration   3: 13.203 ops/ms
Iteration   1: 13.183 ops/ms
Iteration   2: 13.261 ops/ms
Iteration   3: 13.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.238 ±(99.9%) 0.873 ops/ms [Average]
  (min, avg, max) = (13.183, 13.238, 13.270), stdev = 0.048
  CI (99.9%): [12.365, 14.111] (assumes normal distribution)


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
# Warmup Iteration   1: 7.656 ops/ms
# Warmup Iteration   2: 12.381 ops/ms
# Warmup Iteration   3: 12.726 ops/ms
Iteration   1: 12.714 ops/ms
Iteration   2: 12.640 ops/ms
Iteration   3: 12.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.648 ±(99.9%) 1.129 ops/ms [Average]
  (min, avg, max) = (12.591, 12.648, 12.714), stdev = 0.062
  CI (99.9%): [11.520, 13.777] (assumes normal distribution)


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
# Warmup Iteration   1: 6.516 ops/ms
# Warmup Iteration   2: 10.591 ops/ms
# Warmup Iteration   3: 10.742 ops/ms
Iteration   1: 10.780 ops/ms
Iteration   2: 10.628 ops/ms
Iteration   3: 10.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.706 ±(99.9%) 1.387 ops/ms [Average]
  (min, avg, max) = (10.628, 10.706, 10.780), stdev = 0.076
  CI (99.9%): [9.319, 12.094] (assumes normal distribution)


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
# Warmup Iteration   1: 3.778 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.004 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
Iteration   3: 2.505 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.505, 2.512, 2.519), stdev = 0.007
  CI (99.9%): [2.384, 2.640] (assumes normal distribution)


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.403 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.387 ±(99.9%) 0.005 ms/op
Iteration   1: 2.397 ±(99.9%) 0.005 ms/op
Iteration   2: 2.424 ±(99.9%) 0.003 ms/op
Iteration   3: 2.417 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.413 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (2.397, 2.413, 2.424), stdev = 0.014
  CI (99.9%): [2.157, 2.668] (assumes normal distribution)


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.583 ±(99.9%) 0.004 ms/op
Iteration   1: 2.552 ±(99.9%) 0.004 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.564 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.553 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.545, 2.553, 2.564), stdev = 0.010
  CI (99.9%): [2.372, 2.735] (assumes normal distribution)


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
# Warmup Iteration   1: 5.085 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
Iteration   2: 3.019 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.009 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (3.002, 3.009, 3.019), stdev = 0.009
  CI (99.9%): [2.849, 3.169] (assumes normal distribution)


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
# Warmup Iteration   1: 4.222 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.755 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.581 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  12.060 ms/op
                 createUser·p0.9999: 13.881 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  9.588 ms/op
                 createUser·p0.9999: 12.791 ms/op
                 createUser·p1.00:   13.140 ms/op

Iteration   3: 2.563 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  8.885 ms/op
                 createUser·p0.9999: 12.354 ms/op
                 createUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377292
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 181470 
    [ 2.500,  3.750) = 192247 
    [ 3.750,  5.000) = 2786 
    [ 5.000,  6.250) = 254 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     14.323 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  11.501 ms/op
                 existUser·p0.9999: 17.588 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.593 ms/op
                 existUser·p0.999:  8.786 ms/op
                 existUser·p0.9999: 15.841 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  5.226 ms/op
                 existUser·p0.9999: 11.960 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385992
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 190115 
    [ 2.500,  3.750) = 192538 
    [ 3.750,  5.000) = 2653 
    [ 5.000,  6.250) = 259 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      5.915 ms/op
     p(99.9900) =     16.499 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.586 ±(99.9%) 0.006 ms/op
Iteration   1: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  11.933 ms/op
                 getUser·p0.9999: 14.545 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.642 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  6.417 ms/op
                 getUser·p0.9999: 13.623 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   3: 2.586 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.039 ms/op
                 getUser·p0.999:  9.535 ms/op
                 getUser·p0.9999: 12.272 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374083
  mean =      2.564 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 180323 
    [ 2.500,  3.750) = 188444 
    [ 3.750,  5.000) = 4357 
    [ 5.000,  6.250) = 460 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 130 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      7.012 ms/op
     p(99.9900) =     13.756 ms/op
     p(99.9990) =     14.762 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.958 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.009 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  8.953 ms/op
                 listUser·p0.9999: 11.393 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   2: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.904 ms/op
                 listUser·p1.00:   11.567 ms/op

Iteration   3: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.472 ms/op
                 listUser·p0.9999: 11.521 ms/op
                 listUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321850
  mean =      2.981 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 99540 
    [ 2.500,  3.750) = 184565 
    [ 3.750,  5.000) = 30751 
    [ 5.000,  6.250) = 5626 
    [ 6.250,  7.500) = 515 
    [ 7.500,  8.750) = 262 
    [ 8.750, 10.000) = 252 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.309 ms/op
     p(99.9900) =     11.370 ms/op
     p(99.9990) =     12.148 ms/op
     p(99.9999) =     12.681 ms/op
    p(100.0000) =     12.681 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.480 ± 2.329  ops/ms
ClientPb.existUser                       thrpt       3  13.238 ± 0.873  ops/ms
ClientPb.getUser                         thrpt       3  12.648 ± 1.129  ops/ms
ClientPb.listUser                        thrpt       3  10.706 ± 1.387  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.128   ms/op
ClientPb.existUser                        avgt       3   2.413 ± 0.256   ms/op
ClientPb.getUser                          avgt       3   2.553 ± 0.181   ms/op
ClientPb.listUser                         avgt       3   3.009 ± 0.160   ms/op
ClientPb.createUser                     sample  377292   2.542 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.852           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.946           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.418           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.369           ms/op
ClientPb.existUser                      sample  385992   2.484 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.990           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.915           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.499           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.317           ms/op
ClientPb.getUser                        sample  374083   2.564 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.904           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.605           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.012           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.756           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.959           ms/op
ClientPb.listUser                       sample  321850   2.981 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.785           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.309           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.370           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.681           ms/op
