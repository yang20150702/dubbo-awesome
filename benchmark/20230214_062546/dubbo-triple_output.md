# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.644 ops/ms
# Warmup Iteration   2: 6.480 ops/ms
# Warmup Iteration   3: 9.091 ops/ms
Iteration   1: 9.468 ops/ms
Iteration   2: 9.525 ops/ms
Iteration   3: 9.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.587 ±(99.9%) 2.916 ops/ms [Average]
  (min, avg, max) = (9.468, 9.587, 9.769), stdev = 0.160
  CI (99.9%): [6.671, 12.504] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.409 ops/ms
# Warmup Iteration   2: 9.209 ops/ms
# Warmup Iteration   3: 10.122 ops/ms
Iteration   1: 10.418 ops/ms
Iteration   2: 10.469 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.517 ±(99.9%) 2.367 ops/ms [Average]
  (min, avg, max) = (10.418, 10.517, 10.664), stdev = 0.130
  CI (99.9%): [8.150, 12.884] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.524 ops/ms
# Warmup Iteration   2: 8.929 ops/ms
# Warmup Iteration   3: 9.655 ops/ms
Iteration   1: 9.691 ops/ms
Iteration   2: 10.338 ops/ms
Iteration   3: 9.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.997 ±(99.9%) 5.927 ops/ms [Average]
  (min, avg, max) = (9.691, 9.997, 10.338), stdev = 0.325
  CI (99.9%): [4.070, 15.923] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.360 ops/ms
# Warmup Iteration   2: 7.865 ops/ms
# Warmup Iteration   3: 8.287 ops/ms
Iteration   1: 8.329 ops/ms
Iteration   2: 8.596 ops/ms
Iteration   3: 8.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.561 ±(99.9%) 3.949 ops/ms [Average]
  (min, avg, max) = (8.329, 8.561, 8.758), stdev = 0.216
  CI (99.9%): [4.612, 12.510] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.593 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.449 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.006 ms/op
Iteration   1: 3.119 ±(99.9%) 0.007 ms/op
Iteration   2: 3.276 ±(99.9%) 0.006 ms/op
Iteration   3: 3.339 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.245 ±(99.9%) 2.063 ms/op [Average]
  (min, avg, max) = (3.119, 3.245, 3.339), stdev = 0.113
  CI (99.9%): [1.182, 5.308] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.307 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.003 ms/op
Iteration   1: 3.181 ±(99.9%) 0.005 ms/op
Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
Iteration   3: 2.961 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.069 ±(99.9%) 2.009 ms/op [Average]
  (min, avg, max) = (2.961, 3.069, 3.181), stdev = 0.110
  CI (99.9%): [1.060, 5.078] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.270 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.002 ms/op
Iteration   1: 3.165 ±(99.9%) 0.004 ms/op
Iteration   2: 3.369 ±(99.9%) 0.003 ms/op
Iteration   3: 3.256 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.263 ±(99.9%) 1.864 ms/op [Average]
  (min, avg, max) = (3.165, 3.263, 3.369), stdev = 0.102
  CI (99.9%): [1.399, 5.128] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.738 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.005 ms/op
Iteration   1: 3.713 ±(99.9%) 0.009 ms/op
Iteration   2: 3.710 ±(99.9%) 0.009 ms/op
Iteration   3: 3.725 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.716 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (3.710, 3.716, 3.725), stdev = 0.008
  CI (99.9%): [3.573, 3.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.528 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.010 ms/op
Iteration   1: 3.207 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  15.019 ms/op
                 createUser·p0.9999: 20.055 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   2: 3.166 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  18.871 ms/op
                 createUser·p0.9999: 21.879 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   3: 3.267 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  15.991 ms/op
                 createUser·p0.9999: 22.243 ms/op
                 createUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298733
  mean =      3.213 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23720 
    [ 2.500,  5.000) = 268774 
    [ 5.000,  7.500) = 5282 
    [ 7.500, 10.000) = 470 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 177 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     17.384 ms/op
     p(99.9900) =     21.582 ms/op
     p(99.9990) =     22.841 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.843 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
Iteration   1: 3.103 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  12.026 ms/op
                 existUser·p0.9999: 23.761 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   2: 3.108 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  9.444 ms/op
                 existUser·p0.9999: 23.420 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   3: 3.111 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  13.827 ms/op
                 existUser·p0.9999: 24.548 ms/op
                 existUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308865
  mean =      3.107 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27261 
    [ 2.500,  5.000) = 277090 
    [ 5.000,  7.500) = 3598 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     13.030 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.161 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.008 ms/op
Iteration   1: 3.118 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  17.596 ms/op
                 getUser·p0.9999: 21.586 ms/op
                 getUser·p1.00:   21.758 ms/op

Iteration   2: 3.270 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  18.173 ms/op
                 getUser·p0.9999: 21.864 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 22.638 ms/op
                 getUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301589
  mean =      3.180 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13472 
    [ 2.500,  5.000) = 281874 
    [ 5.000,  7.500) = 5470 
    [ 7.500, 10.000) = 290 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     22.441 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.339 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.011 ms/op
Iteration   1: 3.723 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 18.031 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 3.803 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 21.482 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   3: 3.690 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  12.752 ms/op
                 listUser·p0.9999: 20.251 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256718
  mean =      3.738 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 110 
    [ 2.500,  5.000) = 247390 
    [ 5.000,  7.500) = 6546 
    [ 7.500, 10.000) = 1929 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 337 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     20.425 ms/op
     p(99.9990) =     22.438 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.587 ± 2.916  ops/ms
ClientPb.existUser                       thrpt       3  10.517 ± 2.367  ops/ms
ClientPb.getUser                         thrpt       3   9.997 ± 5.927  ops/ms
ClientPb.listUser                        thrpt       3   8.561 ± 3.949  ops/ms
ClientPb.createUser                       avgt       3   3.245 ± 2.063   ms/op
ClientPb.existUser                        avgt       3   3.069 ± 2.009   ms/op
ClientPb.getUser                          avgt       3   3.263 ± 1.864   ms/op
ClientPb.listUser                         avgt       3   3.716 ± 0.143   ms/op
ClientPb.createUser                     sample  298733   3.213 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.709           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.486           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.384           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.582           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.101           ms/op
ClientPb.existUser                      sample  308865   3.107 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.971           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.030           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.822           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.969           ms/op
ClientPb.getUser                        sample  301589   3.180 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.124           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.527           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.334           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.441           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.101           ms/op
ClientPb.listUser                       sample  256718   3.738 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.395           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.580           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.746           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.425           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.905           ms/op
