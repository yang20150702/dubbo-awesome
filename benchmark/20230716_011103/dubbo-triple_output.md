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
# Warmup Iteration   1: 2.010 ops/ms
# Warmup Iteration   2: 4.949 ops/ms
# Warmup Iteration   3: 8.518 ops/ms
Iteration   1: 8.785 ops/ms
Iteration   2: 9.418 ops/ms
Iteration   3: 9.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.144 ±(99.9%) 5.933 ops/ms [Average]
  (min, avg, max) = (8.785, 9.144, 9.418), stdev = 0.325
  CI (99.9%): [3.211, 15.077] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.097 ops/ms
# Warmup Iteration   2: 8.871 ops/ms
# Warmup Iteration   3: 9.325 ops/ms
Iteration   1: 9.664 ops/ms
Iteration   2: 9.509 ops/ms
Iteration   3: 9.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.584 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (9.509, 9.584, 9.664), stdev = 0.078
  CI (99.9%): [8.168, 11.000] (assumes normal distribution)


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
# Warmup Iteration   1: 2.466 ops/ms
# Warmup Iteration   2: 8.149 ops/ms
# Warmup Iteration   3: 8.837 ops/ms
Iteration   1: 9.118 ops/ms
Iteration   2: 9.415 ops/ms
Iteration   3: 9.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.325 ±(99.9%) 3.275 ops/ms [Average]
  (min, avg, max) = (9.118, 9.325, 9.441), stdev = 0.180
  CI (99.9%): [6.050, 12.600] (assumes normal distribution)


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
# Warmup Iteration   1: 2.599 ops/ms
# Warmup Iteration   2: 7.405 ops/ms
# Warmup Iteration   3: 7.594 ops/ms
Iteration   1: 7.854 ops/ms
Iteration   2: 7.944 ops/ms
Iteration   3: 7.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.830 ±(99.9%) 2.317 ops/ms [Average]
  (min, avg, max) = (7.693, 7.830, 7.944), stdev = 0.127
  CI (99.9%): [5.513, 10.147] (assumes normal distribution)


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
# Warmup Iteration   1: 10.481 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.006 ms/op
Iteration   1: 3.398 ±(99.9%) 0.013 ms/op
Iteration   2: 3.392 ±(99.9%) 0.011 ms/op
Iteration   3: 3.525 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.438 ±(99.9%) 1.374 ms/op [Average]
  (min, avg, max) = (3.392, 3.438, 3.525), stdev = 0.075
  CI (99.9%): [2.065, 4.812] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.735 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.003 ms/op
Iteration   1: 3.281 ±(99.9%) 0.009 ms/op
Iteration   2: 3.329 ±(99.9%) 0.006 ms/op
Iteration   3: 3.307 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.306 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (3.281, 3.306, 3.329), stdev = 0.024
  CI (99.9%): [2.870, 3.741] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.687 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.006 ms/op
Iteration   1: 3.466 ±(99.9%) 0.006 ms/op
Iteration   2: 3.455 ±(99.9%) 0.007 ms/op
Iteration   3: 3.448 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.456 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (3.448, 3.456, 3.466), stdev = 0.009
  CI (99.9%): [3.289, 3.623] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.536 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.007 ms/op
Iteration   1: 4.107 ±(99.9%) 0.013 ms/op
Iteration   2: 4.095 ±(99.9%) 0.016 ms/op
Iteration   3: 3.962 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.055 ±(99.9%) 1.463 ms/op [Average]
  (min, avg, max) = (3.962, 4.055, 4.107), stdev = 0.080
  CI (99.9%): [2.592, 5.518] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.291 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.011 ms/op
Iteration   1: 3.755 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  20.868 ms/op
                 createUser·p0.9999: 34.700 ms/op
                 createUser·p1.00:   35.521 ms/op

Iteration   2: 3.577 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  21.862 ms/op
                 createUser·p0.9999: 30.150 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   3: 3.490 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   5.826 ms/op
                 createUser·p0.999:  19.065 ms/op
                 createUser·p0.9999: 27.156 ms/op
                 createUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 266195
  mean =      3.604 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2761 
    [ 2.500,  5.000) = 252439 
    [ 5.000,  7.500) = 9647 
    [ 7.500, 10.000) = 826 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     20.343 ms/op
     p(99.9900) =     31.470 ms/op
     p(99.9990) =     35.259 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 8.712 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.009 ms/op
Iteration   1: 3.373 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.527 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  19.509 ms/op
                 existUser·p0.9999: 22.692 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.492 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  21.304 ms/op
                 existUser·p0.9999: 25.123 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 3.458 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.729 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  13.575 ms/op
                 existUser·p0.9999: 27.058 ms/op
                 existUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279142
  mean =      3.440 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16806 
    [ 2.500,  5.000) = 253805 
    [ 5.000,  7.500) = 7597 
    [ 7.500, 10.000) = 552 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     25.401 ms/op
     p(99.9990) =     27.656 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 8.913 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.010 ms/op
Iteration   1: 3.559 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  21.594 ms/op
                 getUser·p0.9999: 25.298 ms/op
                 getUser·p1.00:   29.000 ms/op

Iteration   2: 3.548 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.721 ms/op
                 getUser·p0.999:  21.425 ms/op
                 getUser·p0.9999: 33.948 ms/op
                 getUser·p1.00:   34.275 ms/op

Iteration   3: 3.498 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  21.758 ms/op
                 getUser·p0.9999: 27.096 ms/op
                 getUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271397
  mean =      3.535 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 850 
    [ 2.500,  5.000) = 260150 
    [ 5.000,  7.500) = 8817 
    [ 7.500, 10.000) = 856 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     21.594 ms/op
     p(99.9900) =     33.419 ms/op
     p(99.9990) =     34.163 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 10.313 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.012 ms/op
Iteration   1: 4.110 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  20.910 ms/op
                 listUser·p0.9999: 28.359 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   2: 3.987 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.642 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 19.791 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.882 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240460
  mean =      3.991 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 232826 
    [ 5.000,  7.500) = 5358 
    [ 7.500, 10.000) = 1373 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.987 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     26.736 ms/op
     p(99.9990) =     28.908 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.144 ± 5.933  ops/ms
ClientPb.existUser                       thrpt       3   9.584 ± 1.416  ops/ms
ClientPb.getUser                         thrpt       3   9.325 ± 3.275  ops/ms
ClientPb.listUser                        thrpt       3   7.830 ± 2.317  ops/ms
ClientPb.createUser                       avgt       3   3.438 ± 1.374   ms/op
ClientPb.existUser                        avgt       3   3.306 ± 0.435   ms/op
ClientPb.getUser                          avgt       3   3.456 ± 0.167   ms/op
ClientPb.listUser                         avgt       3   4.055 ± 1.463   ms/op
ClientPb.createUser                     sample  266195   3.604 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.290           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.424           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.840           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.343           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.470           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.521           ms/op
ClientPb.existUser                      sample  279142   3.440 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.527           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.030           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.029           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.599           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.401           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.689           ms/op
ClientPb.getUser                        sample  271397   3.535 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.278           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.758           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.594           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.419           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.275           ms/op
ClientPb.listUser                       sample  240460   3.991 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.987           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.465           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.736           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.967           ms/op
