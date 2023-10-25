# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.385 ops/ms
# Warmup Iteration   2: 4.902 ops/ms
# Warmup Iteration   3: 9.492 ops/ms
Iteration   1: 9.798 ops/ms
Iteration   2: 10.090 ops/ms
Iteration   3: 10.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.995 ±(99.9%) 3.111 ops/ms [Average]
  (min, avg, max) = (9.798, 9.995, 10.097), stdev = 0.171
  CI (99.9%): [6.884, 13.106] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.558 ops/ms
# Warmup Iteration   2: 9.095 ops/ms
# Warmup Iteration   3: 10.071 ops/ms
Iteration   1: 10.101 ops/ms
Iteration   2: 9.826 ops/ms
Iteration   3: 10.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.047 ±(99.9%) 3.648 ops/ms [Average]
  (min, avg, max) = (9.826, 10.047, 10.215), stdev = 0.200
  CI (99.9%): [6.400, 13.695] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.113 ops/ms
# Warmup Iteration   2: 9.213 ops/ms
# Warmup Iteration   3: 9.489 ops/ms
Iteration   1: 9.848 ops/ms
Iteration   2: 10.002 ops/ms
Iteration   3: 9.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.881 ±(99.9%) 1.968 ops/ms [Average]
  (min, avg, max) = (9.794, 9.881, 10.002), stdev = 0.108
  CI (99.9%): [7.913, 11.850] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.980 ops/ms
# Warmup Iteration   2: 7.638 ops/ms
# Warmup Iteration   3: 8.039 ops/ms
Iteration   1: 8.311 ops/ms
Iteration   2: 8.457 ops/ms
Iteration   3: 8.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.320 ±(99.9%) 2.412 ops/ms [Average]
  (min, avg, max) = (8.193, 8.320, 8.457), stdev = 0.132
  CI (99.9%): [5.909, 10.732] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.211 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.004 ms/op
Iteration   1: 3.351 ±(99.9%) 0.005 ms/op
Iteration   2: 3.285 ±(99.9%) 0.006 ms/op
Iteration   3: 3.254 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.297 ±(99.9%) 0.907 ms/op [Average]
  (min, avg, max) = (3.254, 3.297, 3.351), stdev = 0.050
  CI (99.9%): [2.390, 4.204] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.688 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.003 ms/op
Iteration   1: 3.158 ±(99.9%) 0.003 ms/op
Iteration   2: 3.159 ±(99.9%) 0.003 ms/op
Iteration   3: 3.189 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.168 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (3.158, 3.168, 3.189), stdev = 0.017
  CI (99.9%): [2.851, 3.486] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.965 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.002 ms/op
Iteration   1: 3.208 ±(99.9%) 0.002 ms/op
Iteration   2: 3.239 ±(99.9%) 0.003 ms/op
Iteration   3: 3.248 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.232 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.208, 3.232, 3.248), stdev = 0.021
  CI (99.9%): [2.849, 3.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.884 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.247 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.004 ms/op
Iteration   1: 3.827 ±(99.9%) 0.004 ms/op
Iteration   2: 3.764 ±(99.9%) 0.005 ms/op
Iteration   3: 3.880 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.824 ±(99.9%) 1.059 ms/op [Average]
  (min, avg, max) = (3.764, 3.824, 3.880), stdev = 0.058
  CI (99.9%): [2.765, 4.883] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.694 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.011 ms/op
Iteration   1: 3.375 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  17.038 ms/op
                 createUser·p0.9999: 19.630 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   2: 3.263 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  13.023 ms/op
                 createUser·p0.9999: 22.053 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   3: 3.302 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   6.758 ms/op
                 createUser·p0.999:  17.601 ms/op
                 createUser·p0.9999: 21.758 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289653
  mean =      3.313 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17602 
    [ 2.500,  5.000) = 266289 
    [ 5.000,  7.500) = 4569 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 181 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     22.449 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.943 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.008 ms/op
Iteration   1: 3.124 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  14.765 ms/op
                 existUser·p0.9999: 20.054 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  13.521 ms/op
                 existUser·p0.9999: 22.086 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  12.451 ms/op
                 existUser·p0.9999: 21.263 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304636
  mean =      3.148 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18732 
    [ 2.500,  5.000) = 279637 
    [ 5.000,  7.500) = 5420 
    [ 7.500, 10.000) = 289 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     12.491 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.235 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.009 ms/op
Iteration   1: 3.253 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  16.068 ms/op
                 getUser·p0.9999: 21.086 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   2: 3.249 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  16.004 ms/op
                 getUser·p0.9999: 22.418 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   3: 3.231 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  8.391 ms/op
                 getUser·p0.9999: 18.848 ms/op
                 getUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295767
  mean =      3.244 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7442 
    [ 2.500,  5.000) = 283255 
    [ 5.000,  7.500) = 4330 
    [ 7.500, 10.000) = 265 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     21.346 ms/op
     p(99.9990) =     23.071 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.434 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.012 ms/op
Iteration   1: 3.884 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  16.417 ms/op
                 listUser·p0.9999: 20.243 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   2: 3.793 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  13.697 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   3: 3.836 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  12.468 ms/op
                 listUser·p0.9999: 18.744 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249981
  mean =      3.837 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 243790 
    [ 5.000,  7.500) = 4911 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 267 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.917 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     21.348 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.995 ± 3.111  ops/ms
ClientPb.existUser                       thrpt       3  10.047 ± 3.648  ops/ms
ClientPb.getUser                         thrpt       3   9.881 ± 1.968  ops/ms
ClientPb.listUser                        thrpt       3   8.320 ± 2.412  ops/ms
ClientPb.createUser                       avgt       3   3.297 ± 0.907   ms/op
ClientPb.existUser                        avgt       3   3.168 ± 0.317   ms/op
ClientPb.getUser                          avgt       3   3.232 ± 0.383   ms/op
ClientPb.listUser                         avgt       3   3.824 ± 1.059   ms/op
ClientPb.createUser                     sample  289653   3.313 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.888           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.138           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.758           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.938           ms/op
ClientPb.existUser                      sample  304636   3.148 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.059           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.775           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.491           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.529           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.446           ms/op
ClientPb.getUser                        sample  295767   3.244 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.311           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.584           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.696           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.346           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.200           ms/op
ClientPb.listUser                       sample  249981   3.837 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.917           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.752           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.652           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.156           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.366           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.561           ms/op
