# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.997 ops/ms
# Warmup Iteration   2: 4.843 ops/ms
# Warmup Iteration   3: 8.599 ops/ms
Iteration   1: 9.063 ops/ms
Iteration   2: 9.178 ops/ms
Iteration   3: 9.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.190 ±(99.9%) 2.437 ops/ms [Average]
  (min, avg, max) = (9.063, 9.190, 9.330), stdev = 0.134
  CI (99.9%): [6.753, 11.628] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.870 ops/ms
# Warmup Iteration   2: 8.780 ops/ms
# Warmup Iteration   3: 9.351 ops/ms
Iteration   1: 9.536 ops/ms
Iteration   2: 9.562 ops/ms
Iteration   3: 9.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.585 ±(99.9%) 1.170 ops/ms [Average]
  (min, avg, max) = (9.536, 9.585, 9.658), stdev = 0.064
  CI (99.9%): [8.415, 10.756] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.688 ops/ms
# Warmup Iteration   2: 8.221 ops/ms
# Warmup Iteration   3: 8.578 ops/ms
Iteration   1: 9.332 ops/ms
Iteration   2: 9.276 ops/ms
Iteration   3: 9.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.233 ±(99.9%) 2.303 ops/ms [Average]
  (min, avg, max) = (9.091, 9.233, 9.332), stdev = 0.126
  CI (99.9%): [6.930, 11.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.675 ops/ms
# Warmup Iteration   2: 7.117 ops/ms
# Warmup Iteration   3: 7.592 ops/ms
Iteration   1: 7.599 ops/ms
Iteration   2: 7.687 ops/ms
Iteration   3: 7.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.697 ±(99.9%) 1.891 ops/ms [Average]
  (min, avg, max) = (7.599, 7.697, 7.806), stdev = 0.104
  CI (99.9%): [5.807, 9.588] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.607 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.003 ms/op
Iteration   1: 3.584 ±(99.9%) 0.005 ms/op
Iteration   2: 3.372 ±(99.9%) 0.006 ms/op
Iteration   3: 3.551 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.503 ±(99.9%) 2.079 ms/op [Average]
  (min, avg, max) = (3.372, 3.503, 3.584), stdev = 0.114
  CI (99.9%): [1.424, 5.582] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.352 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.004 ms/op
Iteration   1: 3.283 ±(99.9%) 0.004 ms/op
Iteration   2: 3.331 ±(99.9%) 0.006 ms/op
Iteration   3: 3.345 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.320 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (3.283, 3.320, 3.345), stdev = 0.032
  CI (99.9%): [2.732, 3.907] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.310 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.003 ms/op
Iteration   1: 3.517 ±(99.9%) 0.004 ms/op
Iteration   2: 3.464 ±(99.9%) 0.004 ms/op
Iteration   3: 3.513 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.498 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.464, 3.498, 3.517), stdev = 0.029
  CI (99.9%): [2.961, 4.035] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.955 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.285 ±(99.9%) 0.008 ms/op
Iteration   1: 4.188 ±(99.9%) 0.010 ms/op
Iteration   2: 4.215 ±(99.9%) 0.010 ms/op
Iteration   3: 4.150 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.184 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (4.150, 4.184, 4.215), stdev = 0.033
  CI (99.9%): [3.586, 4.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.369 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.958 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.012 ms/op
Iteration   1: 3.538 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.512 ms/op
                 createUser·p0.999:  22.446 ms/op
                 createUser·p0.9999: 25.297 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   2: 3.613 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   7.187 ms/op
                 createUser·p0.999:  21.699 ms/op
                 createUser·p0.9999: 25.494 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   3: 3.496 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.467 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   7.471 ms/op
                 createUser·p0.999:  21.809 ms/op
                 createUser·p0.9999: 28.335 ms/op
                 createUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270302
  mean =      3.548 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2561 
    [ 2.500,  5.000) = 259974 
    [ 5.000,  7.500) = 5745 
    [ 7.500, 10.000) = 1235 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 145 
    [25.000, 27.500) = 94 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     21.889 ms/op
     p(99.9900) =     26.803 ms/op
     p(99.9990) =     28.551 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.397 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
Iteration   1: 3.407 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  21.135 ms/op
                 existUser·p0.9999: 23.973 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   2: 3.465 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  14.082 ms/op
                 existUser·p0.9999: 24.667 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   3: 3.549 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   7.389 ms/op
                 existUser·p0.999:  22.932 ms/op
                 existUser·p0.9999: 28.934 ms/op
                 existUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276426
  mean =      3.473 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9026 
    [ 2.500,  5.000) = 257853 
    [ 5.000,  7.500) = 7468 
    [ 7.500, 10.000) = 1218 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 139 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     16.218 ms/op
     p(99.9900) =     28.422 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.748 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.013 ms/op
Iteration   1: 3.541 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  20.709 ms/op
                 getUser·p0.9999: 23.428 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   2: 3.494 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  23.497 ms/op
                 getUser·p0.9999: 25.418 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   3: 3.491 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  22.299 ms/op
                 getUser·p0.9999: 39.506 ms/op
                 getUser·p1.00:   45.482 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273589
  mean =      3.509 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 263625 
    [ 5.000, 10.000) = 9138 
    [10.000, 15.000) = 433 
    [15.000, 20.000) = 104 
    [20.000, 25.000) = 203 
    [25.000, 30.000) = 54 
    [30.000, 35.000) = 21 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     34.359 ms/op
     p(99.9990) =     45.272 ms/op
     p(99.9999) =     45.482 ms/op
    p(100.0000) =     45.482 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.834 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.668 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.013 ms/op
Iteration   1: 4.154 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  20.566 ms/op
                 listUser·p0.9999: 28.920 ms/op
                 listUser·p1.00:   36.635 ms/op

Iteration   2: 4.124 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.876 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   8.176 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 19.718 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.146 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.907 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   8.216 ms/op
                 listUser·p0.999:  14.389 ms/op
                 listUser·p0.9999: 17.977 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231932
  mean =      4.141 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 220739 
    [ 5.000,  7.500) = 7560 
    [ 7.500, 10.000) = 2486 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      8.233 ms/op
     p(99.9000) =     16.374 ms/op
     p(99.9900) =     25.527 ms/op
     p(99.9990) =     33.889 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.190 ± 2.437  ops/ms
ClientPb.existUser                       thrpt       3   9.585 ± 1.170  ops/ms
ClientPb.getUser                         thrpt       3   9.233 ± 2.303  ops/ms
ClientPb.listUser                        thrpt       3   7.697 ± 1.891  ops/ms
ClientPb.createUser                       avgt       3   3.503 ± 2.079   ms/op
ClientPb.existUser                        avgt       3   3.320 ± 0.588   ms/op
ClientPb.getUser                          avgt       3   3.498 ± 0.537   ms/op
ClientPb.listUser                         avgt       3   4.184 ± 0.598   ms/op
ClientPb.createUser                     sample  270302   3.548 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.467           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.889           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.803           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.000           ms/op
ClientPb.existUser                      sample  276426   3.473 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.282           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.225           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.218           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.422           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.195           ms/op
ClientPb.getUser                        sample  273589   3.509 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.973           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.143           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.037           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.359           ms/op
ClientPb.getUser:getUser·p1.00          sample          45.482           ms/op
ClientPb.listUser                       sample  231932   4.141 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.247           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.948           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.233           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.374           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.527           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.635           ms/op
