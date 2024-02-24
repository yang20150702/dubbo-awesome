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
# Warmup Iteration   1: 5.231 ops/ms
# Warmup Iteration   2: 11.931 ops/ms
# Warmup Iteration   3: 12.388 ops/ms
Iteration   1: 12.684 ops/ms
Iteration   2: 12.556 ops/ms
Iteration   3: 12.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.645 ±(99.9%) 1.401 ops/ms [Average]
  (min, avg, max) = (12.556, 12.645, 12.694), stdev = 0.077
  CI (99.9%): [11.243, 14.046] (assumes normal distribution)


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
# Warmup Iteration   1: 8.131 ops/ms
# Warmup Iteration   2: 13.026 ops/ms
# Warmup Iteration   3: 13.216 ops/ms
Iteration   1: 13.274 ops/ms
Iteration   2: 13.258 ops/ms
Iteration   3: 13.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.230 ±(99.9%) 1.120 ops/ms [Average]
  (min, avg, max) = (13.160, 13.230, 13.274), stdev = 0.061
  CI (99.9%): [12.110, 14.351] (assumes normal distribution)


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
# Warmup Iteration   1: 8.175 ops/ms
# Warmup Iteration   2: 12.745 ops/ms
# Warmup Iteration   3: 12.975 ops/ms
Iteration   1: 13.135 ops/ms
Iteration   2: 13.009 ops/ms
Iteration   3: 13.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.090 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (13.009, 13.090, 13.135), stdev = 0.070
  CI (99.9%): [11.808, 14.371] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.747 ops/ms
# Warmup Iteration   2: 10.393 ops/ms
# Warmup Iteration   3: 10.564 ops/ms
Iteration   1: 10.549 ops/ms
Iteration   2: 10.564 ops/ms
Iteration   3: 10.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.550 ±(99.9%) 0.246 ops/ms [Average]
  (min, avg, max) = (10.537, 10.550, 10.564), stdev = 0.013
  CI (99.9%): [10.305, 10.796] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.488 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (2.472, 2.488, 2.509), stdev = 0.019
  CI (99.9%): [2.148, 2.829] (assumes normal distribution)


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
# Warmup Iteration   1: 3.584 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.424 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.003 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.409 ±(99.9%) 0.003 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (2.409, 2.439, 2.460), stdev = 0.027
  CI (99.9%): [1.949, 2.928] (assumes normal distribution)


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.004 ms/op
Iteration   1: 2.416 ±(99.9%) 0.004 ms/op
Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
Iteration   3: 2.433 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.431 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (2.416, 2.431, 2.444), stdev = 0.014
  CI (99.9%): [2.174, 2.688] (assumes normal distribution)


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
# Warmup Iteration   1: 4.678 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.005 ms/op
Iteration   1: 3.012 ±(99.9%) 0.006 ms/op
Iteration   2: 3.024 ±(99.9%) 0.007 ms/op
Iteration   3: 3.010 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (3.010, 3.015, 3.024), stdev = 0.008
  CI (99.9%): [2.875, 3.155] (assumes normal distribution)


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  8.444 ms/op
                 createUser·p0.9999: 13.491 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.527 ms/op
                 createUser·p0.999:  6.748 ms/op
                 createUser·p0.9999: 11.616 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 11.092 ms/op
                 createUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387170
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 188124 
    [ 2.500,  3.750) = 195337 
    [ 3.750,  5.000) = 2789 
    [ 5.000,  6.250) = 343 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     13.227 ms/op
     p(99.9990) =     13.814 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 3.579 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.424 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  5.132 ms/op
                 existUser·p0.9999: 15.737 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  8.445 ms/op
                 existUser·p0.9999: 12.889 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  8.310 ms/op
                 existUser·p0.9999: 13.074 ms/op
                 existUser·p1.00:   13.779 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394679
  mean =      2.430 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 198943 
    [ 2.500,  3.750) = 192910 
    [ 3.750,  5.000) = 2079 
    [ 5.000,  6.250) = 210 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      8.167 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     16.155 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.025 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.506 ms/op
                 getUser·p0.999:  5.951 ms/op
                 getUser·p0.9999: 13.484 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 2.504 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  8.225 ms/op
                 getUser·p0.9999: 12.074 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  5.989 ms/op
                 getUser·p0.9999: 10.308 ms/op
                 getUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386978
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 193449 
    [ 2.500,  3.750) = 188608 
    [ 3.750,  5.000) = 3537 
    [ 5.000,  6.250) = 898 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 146 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =     12.899 ms/op
     p(99.9990) =     13.671 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.009 ms/op
Iteration   1: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.753 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  8.782 ms/op
                 listUser·p0.9999: 11.246 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 11.387 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  10.093 ms/op
                 listUser·p0.9999: 13.369 ms/op
                 listUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317647
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 178 
    [ 1.250,  2.500) = 90041 
    [ 2.500,  3.750) = 186900 
    [ 3.750,  5.000) = 33196 
    [ 5.000,  6.250) = 6074 
    [ 6.250,  7.500) = 599 
    [ 7.500,  8.750) = 214 
    [ 8.750, 10.000) = 205 
    [10.000, 11.250) = 183 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.525 ms/op
     p(99.9900) =     11.518 ms/op
     p(99.9990) =     14.362 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.645 ± 1.401  ops/ms
ClientPb.existUser                       thrpt       3  13.230 ± 1.120  ops/ms
ClientPb.getUser                         thrpt       3  13.090 ± 1.281  ops/ms
ClientPb.listUser                        thrpt       3  10.550 ± 0.246  ops/ms
ClientPb.createUser                       avgt       3   2.488 ± 0.341   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.489   ms/op
ClientPb.getUser                          avgt       3   2.431 ± 0.257   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.140   ms/op
ClientPb.createUser                     sample  387170   2.477 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.758           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.585           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.227           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.107           ms/op
ClientPb.existUser                      sample  394679   2.430 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.788           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.167           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.812           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.302           ms/op
ClientPb.getUser                        sample  386978   2.479 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.805           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.176           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.899           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.779           ms/op
ClientPb.listUser                       sample  317647   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.525           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.518           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.451           ms/op
