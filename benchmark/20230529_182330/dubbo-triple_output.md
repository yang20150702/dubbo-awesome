# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.982 ops/ms
# Warmup Iteration   2: 5.205 ops/ms
# Warmup Iteration   3: 8.637 ops/ms
Iteration   1: 9.142 ops/ms
Iteration   2: 9.109 ops/ms
Iteration   3: 9.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.217 ±(99.9%) 2.906 ops/ms [Average]
  (min, avg, max) = (9.109, 9.217, 9.400), stdev = 0.159
  CI (99.9%): [6.311, 12.123] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.921 ops/ms
# Warmup Iteration   2: 9.109 ops/ms
# Warmup Iteration   3: 9.634 ops/ms
Iteration   1: 9.747 ops/ms
Iteration   2: 9.995 ops/ms
Iteration   3: 9.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.851 ±(99.9%) 2.348 ops/ms [Average]
  (min, avg, max) = (9.747, 9.851, 9.995), stdev = 0.129
  CI (99.9%): [7.504, 12.199] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.066 ops/ms
# Warmup Iteration   2: 8.194 ops/ms
# Warmup Iteration   3: 9.093 ops/ms
Iteration   1: 8.732 ops/ms
Iteration   2: 9.553 ops/ms
Iteration   3: 9.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.245 ±(99.9%) 8.156 ops/ms [Average]
  (min, avg, max) = (8.732, 9.245, 9.553), stdev = 0.447
  CI (99.9%): [1.089, 17.401] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.559 ops/ms
# Warmup Iteration   2: 7.035 ops/ms
# Warmup Iteration   3: 7.923 ops/ms
Iteration   1: 7.896 ops/ms
Iteration   2: 8.066 ops/ms
Iteration   3: 7.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.933 ±(99.9%) 2.175 ops/ms [Average]
  (min, avg, max) = (7.836, 7.933, 8.066), stdev = 0.119
  CI (99.9%): [5.758, 10.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.630 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.005 ms/op
Iteration   1: 3.500 ±(99.9%) 0.006 ms/op
Iteration   2: 3.605 ±(99.9%) 0.005 ms/op
Iteration   3: 3.474 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.526 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (3.474, 3.526, 3.605), stdev = 0.069
  CI (99.9%): [2.261, 4.791] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.115 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.011 ms/op
Iteration   1: 3.377 ±(99.9%) 0.009 ms/op
Iteration   2: 3.296 ±(99.9%) 0.010 ms/op
Iteration   3: 3.266 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.313 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.266, 3.313, 3.377), stdev = 0.058
  CI (99.9%): [2.259, 4.367] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.109 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.786 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.005 ms/op
Iteration   1: 3.339 ±(99.9%) 0.011 ms/op
Iteration   2: 3.497 ±(99.9%) 0.004 ms/op
Iteration   3: 3.303 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.380 ±(99.9%) 1.883 ms/op [Average]
  (min, avg, max) = (3.303, 3.380, 3.497), stdev = 0.103
  CI (99.9%): [1.496, 5.263] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.989 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
Iteration   1: 3.875 ±(99.9%) 0.011 ms/op
Iteration   2: 3.960 ±(99.9%) 0.004 ms/op
Iteration   3: 3.810 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.882 ±(99.9%) 1.368 ms/op [Average]
  (min, avg, max) = (3.810, 3.882, 3.960), stdev = 0.075
  CI (99.9%): [2.514, 5.249] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.721 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.010 ms/op
Iteration   1: 3.385 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  18.695 ms/op
                 createUser·p0.9999: 23.447 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   2: 3.409 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  19.767 ms/op
                 createUser·p0.9999: 23.319 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.530 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.334 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.681 ms/op
                 createUser·p0.999:  18.776 ms/op
                 createUser·p0.9999: 37.598 ms/op
                 createUser·p1.00:   40.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279045
  mean =      3.440 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 271922 
    [ 5.000, 10.000) = 6606 
    [10.000, 15.000) = 228 
    [15.000, 20.000) = 58 
    [20.000, 25.000) = 186 
    [25.000, 30.000) = 13 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.334 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     18.807 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     39.873 ms/op
     p(99.9999) =     40.239 ms/op
    p(100.0000) =     40.239 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.496 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.610 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.010 ms/op
Iteration   1: 3.284 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.585 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  11.227 ms/op
                 existUser·p0.9999: 22.858 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   2: 3.291 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  14.123 ms/op
                 existUser·p0.9999: 28.666 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   3: 3.291 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  8.331 ms/op
                 existUser·p0.9999: 23.045 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291942
  mean =      3.289 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16362 
    [ 2.500,  5.000) = 269468 
    [ 5.000,  7.500) = 5284 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     10.453 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     29.330 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.558 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.009 ms/op
Iteration   1: 3.548 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  20.939 ms/op
                 getUser·p0.9999: 27.165 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   2: 3.407 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  22.512 ms/op
                 getUser·p0.9999: 25.521 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 3.369 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  17.983 ms/op
                 getUser·p0.9999: 30.196 ms/op
                 getUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279031
  mean =      3.440 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3252 
    [ 2.500,  5.000) = 265737 
    [ 5.000,  7.500) = 8512 
    [ 7.500, 10.000) = 894 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     20.151 ms/op
     p(99.9900) =     28.511 ms/op
     p(99.9990) =     30.605 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.608 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 5.358 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.276 ±(99.9%) 0.015 ms/op
Iteration   1: 4.003 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  23.626 ms/op
                 listUser·p0.9999: 31.064 ms/op
                 listUser·p1.00:   31.621 ms/op

Iteration   2: 3.931 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 18.711 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 3.985 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.735 ms/op
                 listUser·p0.999:  14.303 ms/op
                 listUser·p0.9999: 17.383 ms/op
                 listUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241635
  mean =      3.973 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 233937 
    [ 5.000,  7.500) = 5748 
    [ 7.500, 10.000) = 1123 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.520 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     16.089 ms/op
     p(99.9900) =     28.760 ms/op
     p(99.9990) =     31.438 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.217 ± 2.906  ops/ms
ClientPb.existUser                       thrpt       3   9.851 ± 2.348  ops/ms
ClientPb.getUser                         thrpt       3   9.245 ± 8.156  ops/ms
ClientPb.listUser                        thrpt       3   7.933 ± 2.175  ops/ms
ClientPb.createUser                       avgt       3   3.526 ± 1.265   ms/op
ClientPb.existUser                        avgt       3   3.313 ± 1.054   ms/op
ClientPb.getUser                          avgt       3   3.380 ± 1.883   ms/op
ClientPb.listUser                         avgt       3   3.882 ± 1.368   ms/op
ClientPb.createUser                     sample  279045   3.440 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.334           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.775           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.807           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.045           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.239           ms/op
ClientPb.existUser                      sample  291942   3.289 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.233           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.994           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.453           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.460           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.393           ms/op
ClientPb.getUser                        sample  279031   3.440 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.169           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.783           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.151           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.511           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.867           ms/op
ClientPb.listUser                       sample  241635   3.973 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.520           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.089           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.760           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.621           ms/op
