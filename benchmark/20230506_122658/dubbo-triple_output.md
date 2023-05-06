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
# Warmup Iteration   1: 2.499 ops/ms
# Warmup Iteration   2: 6.289 ops/ms
# Warmup Iteration   3: 9.418 ops/ms
Iteration   1: 9.749 ops/ms
Iteration   2: 10.137 ops/ms
Iteration   3: 10.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.989 ±(99.9%) 3.827 ops/ms [Average]
  (min, avg, max) = (9.749, 9.989, 10.137), stdev = 0.210
  CI (99.9%): [6.162, 13.816] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.859 ops/ms
# Warmup Iteration   2: 9.377 ops/ms
# Warmup Iteration   3: 10.373 ops/ms
Iteration   1: 10.214 ops/ms
Iteration   2: 10.225 ops/ms
Iteration   3: 10.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.306 ±(99.9%) 2.729 ops/ms [Average]
  (min, avg, max) = (10.214, 10.306, 10.479), stdev = 0.150
  CI (99.9%): [7.577, 13.035] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.283 ops/ms
# Warmup Iteration   2: 8.766 ops/ms
# Warmup Iteration   3: 9.911 ops/ms
Iteration   1: 10.036 ops/ms
Iteration   2: 10.017 ops/ms
Iteration   3: 9.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.887 ±(99.9%) 4.396 ops/ms [Average]
  (min, avg, max) = (9.609, 9.887, 10.036), stdev = 0.241
  CI (99.9%): [5.492, 14.283] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.021 ops/ms
# Warmup Iteration   2: 7.451 ops/ms
# Warmup Iteration   3: 8.366 ops/ms
Iteration   1: 8.434 ops/ms
Iteration   2: 8.462 ops/ms
Iteration   3: 8.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.481 ±(99.9%) 1.080 ops/ms [Average]
  (min, avg, max) = (8.434, 8.481, 8.548), stdev = 0.059
  CI (99.9%): [7.401, 9.561] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.168 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.005 ms/op
Iteration   1: 3.239 ±(99.9%) 0.006 ms/op
Iteration   2: 3.164 ±(99.9%) 0.006 ms/op
Iteration   3: 3.408 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.270 ±(99.9%) 2.286 ms/op [Average]
  (min, avg, max) = (3.164, 3.270, 3.408), stdev = 0.125
  CI (99.9%): [0.984, 5.556] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.761 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.008 ms/op
Iteration   1: 3.217 ±(99.9%) 0.002 ms/op
Iteration   2: 3.200 ±(99.9%) 0.004 ms/op
Iteration   3: 3.182 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.200 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.182, 3.200, 3.217), stdev = 0.017
  CI (99.9%): [2.885, 3.515] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.351 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.004 ms/op
Iteration   1: 3.332 ±(99.9%) 0.003 ms/op
Iteration   2: 3.196 ±(99.9%) 0.003 ms/op
Iteration   3: 3.287 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.272 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (3.196, 3.272, 3.332), stdev = 0.069
  CI (99.9%): [2.015, 4.528] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.550 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.949 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.006 ms/op
Iteration   1: 3.742 ±(99.9%) 0.008 ms/op
Iteration   2: 3.720 ±(99.9%) 0.004 ms/op
Iteration   3: 3.695 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.719 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (3.695, 3.719, 3.742), stdev = 0.024
  CI (99.9%): [3.288, 4.149] (assumes normal distribution)


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
# Warmup Iteration   1: 8.565 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.010 ms/op
Iteration   1: 3.182 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.948 ms/op
                 createUser·p0.999:  11.387 ms/op
                 createUser·p0.9999: 23.195 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   2: 3.269 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  9.462 ms/op
                 createUser·p0.9999: 24.092 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  15.041 ms/op
                 createUser·p0.9999: 22.217 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298879
  mean =      3.209 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20275 
    [ 2.500,  5.000) = 273934 
    [ 5.000,  7.500) = 3904 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     24.318 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 7.619 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.008 ms/op
Iteration   1: 3.159 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  13.364 ms/op
                 existUser·p0.9999: 20.251 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   2: 3.179 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  12.440 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  7.818 ms/op
                 existUser·p0.9999: 19.667 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304552
  mean =      3.151 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34752 
    [ 2.500,  5.000) = 264084 
    [ 5.000,  7.500) = 4904 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     21.514 ms/op
     p(99.9990) =     23.755 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.331 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.010 ms/op
Iteration   1: 3.210 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  16.078 ms/op
                 getUser·p0.9999: 20.842 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   2: 3.266 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.784 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  12.876 ms/op
                 getUser·p0.9999: 21.836 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   3: 3.300 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.304 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  9.939 ms/op
                 getUser·p0.9999: 18.424 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294645
  mean =      3.258 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18436 
    [ 2.500,  5.000) = 267869 
    [ 5.000,  7.500) = 7523 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.304 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     15.086 ms/op
     p(99.9900) =     21.203 ms/op
     p(99.9990) =     22.253 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 9.019 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.012 ms/op
Iteration   1: 3.851 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  14.238 ms/op
                 listUser·p0.9999: 21.061 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   2: 3.727 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   6.785 ms/op
                 listUser·p0.999:  14.307 ms/op
                 listUser·p0.9999: 17.039 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 3.712 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  11.859 ms/op
                 listUser·p0.9999: 15.598 ms/op
                 listUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255110
  mean =      3.762 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 247175 
    [ 5.000,  7.500) = 5842 
    [ 7.500, 10.000) = 1243 
    [10.000, 12.500) = 432 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.505 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     13.482 ms/op
     p(99.9900) =     19.332 ms/op
     p(99.9990) =     21.605 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.989 ± 3.827  ops/ms
ClientPb.existUser                       thrpt       3  10.306 ± 2.729  ops/ms
ClientPb.getUser                         thrpt       3   9.887 ± 4.396  ops/ms
ClientPb.listUser                        thrpt       3   8.481 ± 1.080  ops/ms
ClientPb.createUser                       avgt       3   3.270 ± 2.286   ms/op
ClientPb.existUser                        avgt       3   3.200 ± 0.315   ms/op
ClientPb.getUser                          avgt       3   3.272 ± 1.257   ms/op
ClientPb.listUser                         avgt       3   3.719 ± 0.431   ms/op
ClientPb.createUser                     sample  298879   3.209 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.219           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.008           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.462           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.871           ms/op
ClientPb.existUser                      sample  304552   3.151 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.611           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.436           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.514           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.052           ms/op
ClientPb.getUser                        sample  294645   3.258 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.304           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.145           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.086           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.203           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.381           ms/op
ClientPb.listUser                       sample  255110   3.762 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.505           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.482           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.332           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.823           ms/op
