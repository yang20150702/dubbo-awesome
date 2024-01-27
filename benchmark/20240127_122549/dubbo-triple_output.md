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
# Warmup Iteration   1: 5.109 ops/ms
# Warmup Iteration   2: 12.356 ops/ms
# Warmup Iteration   3: 12.436 ops/ms
Iteration   1: 12.441 ops/ms
Iteration   2: 12.562 ops/ms
Iteration   3: 12.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.563 ±(99.9%) 2.244 ops/ms [Average]
  (min, avg, max) = (12.441, 12.563, 12.687), stdev = 0.123
  CI (99.9%): [10.319, 14.807] (assumes normal distribution)


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
# Warmup Iteration   1: 7.833 ops/ms
# Warmup Iteration   2: 13.188 ops/ms
# Warmup Iteration   3: 13.264 ops/ms
Iteration   1: 13.241 ops/ms
Iteration   2: 13.631 ops/ms
Iteration   3: 13.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.396 ±(99.9%) 3.772 ops/ms [Average]
  (min, avg, max) = (13.241, 13.396, 13.631), stdev = 0.207
  CI (99.9%): [9.624, 17.169] (assumes normal distribution)


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
# Warmup Iteration   1: 7.977 ops/ms
# Warmup Iteration   2: 12.541 ops/ms
# Warmup Iteration   3: 13.130 ops/ms
Iteration   1: 13.071 ops/ms
Iteration   2: 13.149 ops/ms
Iteration   3: 13.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.150 ±(99.9%) 1.454 ops/ms [Average]
  (min, avg, max) = (13.071, 13.150, 13.231), stdev = 0.080
  CI (99.9%): [11.696, 14.605] (assumes normal distribution)


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
# Warmup Iteration   1: 6.949 ops/ms
# Warmup Iteration   2: 11.152 ops/ms
# Warmup Iteration   3: 11.258 ops/ms
Iteration   1: 11.171 ops/ms
Iteration   2: 11.257 ops/ms
Iteration   3: 11.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  11.300 ±(99.9%) 2.828 ops/ms [Average]
  (min, avg, max) = (11.171, 11.300, 11.472), stdev = 0.155
  CI (99.9%): [8.472, 14.128] (assumes normal distribution)


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.008 ms/op
Iteration   1: 2.520 ±(99.9%) 0.005 ms/op
Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
Iteration   3: 2.570 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.546 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (2.520, 2.546, 2.570), stdev = 0.025
  CI (99.9%): [2.087, 3.006] (assumes normal distribution)


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.402 ±(99.9%) 0.004 ms/op
Iteration   2: 2.410 ±(99.9%) 0.004 ms/op
Iteration   3: 2.392 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.402 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.392, 2.402, 2.410), stdev = 0.009
  CI (99.9%): [2.234, 2.569] (assumes normal distribution)


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.511 ±(99.9%) 0.003 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.505 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (2.482, 2.505, 2.522), stdev = 0.021
  CI (99.9%): [2.124, 2.886] (assumes normal distribution)


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
# Warmup Iteration   1: 4.723 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.005 ms/op
Iteration   1: 2.957 ±(99.9%) 0.004 ms/op
Iteration   2: 2.963 ±(99.9%) 0.005 ms/op
Iteration   3: 2.967 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.962 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.957, 2.962, 2.967), stdev = 0.005
  CI (99.9%): [2.870, 3.054] (assumes normal distribution)


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
# Warmup Iteration   1: 3.972 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  11.354 ms/op
                 createUser·p0.9999: 13.926 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.428 ms/op
                 createUser·p0.999:  10.464 ms/op
                 createUser·p0.9999: 12.042 ms/op
                 createUser·p1.00:   12.272 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  8.100 ms/op
                 createUser·p0.9999: 10.606 ms/op
                 createUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383146
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 185337 
    [ 2.500,  3.750) = 194783 
    [ 3.750,  5.000) = 2271 
    [ 5.000,  6.250) = 203 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     13.506 ms/op
     p(99.9990) =     14.178 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


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
# Warmup Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  6.295 ms/op
                 existUser·p0.9999: 13.841 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.398 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  5.948 ms/op
                 existUser·p0.9999: 11.285 ms/op
                 existUser·p1.00:   16.695 ms/op

Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.752 ms/op
                 existUser·p0.999:  8.549 ms/op
                 existUser·p0.9999: 12.040 ms/op
                 existUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395170
  mean =      2.427 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 195967 
    [ 2.500,  3.750) = 195990 
    [ 3.750,  5.000) = 2374 
    [ 5.000,  6.250) = 371 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      7.053 ms/op
     p(99.9900) =     13.246 ms/op
     p(99.9990) =     14.583 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.006 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.580 ms/op
                 getUser·p0.999:  8.157 ms/op
                 getUser·p0.9999: 13.435 ms/op
                 getUser·p1.00:   13.795 ms/op

Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   3.203 ms/op
                 getUser·p0.95:   3.486 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  9.077 ms/op
                 getUser·p0.9999: 13.367 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.219 ms/op
                 getUser·p0.95:   3.543 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  6.596 ms/op
                 getUser·p0.9999: 11.149 ms/op
                 getUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379407
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 171 
    [ 1.250,  2.500) = 191286 
    [ 2.500,  3.750) = 178734 
    [ 3.750,  5.000) = 8012 
    [ 5.000,  6.250) = 700 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.367 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.674 ms/op
     p(99.9900) =     13.273 ms/op
     p(99.9990) =     14.012 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 4.707 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.009 ms/op
Iteration   1: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.789 ms/op
                 listUser·p0.9999: 11.296 ms/op
                 listUser·p1.00:   11.387 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.390 ms/op
                 listUser·p0.999:  10.240 ms/op
                 listUser·p0.9999: 11.540 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   3: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.847 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.637 ms/op
                 listUser·p0.9999: 10.771 ms/op
                 listUser·p1.00:   11.158 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317591
  mean =      3.020 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 86707 
    [ 2.500,  3.750) = 191871 
    [ 3.750,  5.000) = 32951 
    [ 5.000,  6.250) = 4763 
    [ 6.250,  7.500) = 413 
    [ 7.500,  8.750) = 201 
    [ 8.750, 10.000) = 315 
    [10.000, 11.250) = 207 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =      9.863 ms/op
     p(99.9900) =     11.338 ms/op
     p(99.9990) =     11.873 ms/op
     p(99.9999) =     12.157 ms/op
    p(100.0000) =     12.157 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.563 ± 2.244  ops/ms
ClientPb.existUser                       thrpt       3  13.396 ± 3.772  ops/ms
ClientPb.getUser                         thrpt       3  13.150 ± 1.454  ops/ms
ClientPb.listUser                        thrpt       3  11.300 ± 2.828  ops/ms
ClientPb.createUser                       avgt       3   2.546 ± 0.459   ms/op
ClientPb.existUser                        avgt       3   2.402 ± 0.168   ms/op
ClientPb.getUser                          avgt       3   2.505 ± 0.381   ms/op
ClientPb.listUser                         avgt       3   2.962 ± 0.092   ms/op
ClientPb.createUser                     sample  383146   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.672           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.700           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.506           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.548           ms/op
ClientPb.existUser                      sample  395170   2.427 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.398           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.053           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.246           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.695           ms/op
ClientPb.getUser                        sample  379407   2.528 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.680           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.674           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.273           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.139           ms/op
ClientPb.listUser                       sample  317591   3.020 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.808           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.863           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.338           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.157           ms/op
