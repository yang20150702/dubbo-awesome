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
# Warmup Iteration   1: 5.023 ops/ms
# Warmup Iteration   2: 12.226 ops/ms
# Warmup Iteration   3: 12.416 ops/ms
Iteration   1: 12.407 ops/ms
Iteration   2: 12.653 ops/ms
Iteration   3: 12.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.602 ±(99.9%) 3.195 ops/ms [Average]
  (min, avg, max) = (12.407, 12.602, 12.746), stdev = 0.175
  CI (99.9%): [9.407, 15.797] (assumes normal distribution)


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
# Warmup Iteration   1: 8.213 ops/ms
# Warmup Iteration   2: 13.018 ops/ms
# Warmup Iteration   3: 12.880 ops/ms
Iteration   1: 12.761 ops/ms
Iteration   2: 12.623 ops/ms
Iteration   3: 12.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.683 ±(99.9%) 1.284 ops/ms [Average]
  (min, avg, max) = (12.623, 12.683, 12.761), stdev = 0.070
  CI (99.9%): [11.399, 13.968] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.732 ops/ms
# Warmup Iteration   2: 12.535 ops/ms
# Warmup Iteration   3: 12.719 ops/ms
Iteration   1: 12.759 ops/ms
Iteration   2: 12.742 ops/ms
Iteration   3: 12.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.736 ±(99.9%) 0.476 ops/ms [Average]
  (min, avg, max) = (12.708, 12.736, 12.759), stdev = 0.026
  CI (99.9%): [12.260, 13.212] (assumes normal distribution)


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
# Warmup Iteration   1: 6.558 ops/ms
# Warmup Iteration   2: 10.367 ops/ms
# Warmup Iteration   3: 10.478 ops/ms
Iteration   1: 10.454 ops/ms
Iteration   2: 10.496 ops/ms
Iteration   3: 10.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.491 ±(99.9%) 0.621 ops/ms [Average]
  (min, avg, max) = (10.454, 10.491, 10.522), stdev = 0.034
  CI (99.9%): [9.870, 11.111] (assumes normal distribution)


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
# Warmup Iteration   1: 4.006 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.521 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (2.491, 2.521, 2.567), stdev = 0.041
  CI (99.9%): [1.781, 3.261] (assumes normal distribution)


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.371 ±(99.9%) 0.008 ms/op
Iteration   1: 2.427 ±(99.9%) 0.005 ms/op
Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
Iteration   3: 2.446 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.427, 2.439, 2.446), stdev = 0.010
  CI (99.9%): [2.252, 2.625] (assumes normal distribution)


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.498 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.484, 2.498, 2.509), stdev = 0.013
  CI (99.9%): [2.268, 2.729] (assumes normal distribution)


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
# Warmup Iteration   1: 4.745 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
Iteration   2: 3.028 ±(99.9%) 0.005 ms/op
Iteration   3: 3.034 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.031 ±(99.9%) 0.052 ms/op [Average]
  (min, avg, max) = (3.028, 3.031, 3.034), stdev = 0.003
  CI (99.9%): [2.978, 3.083] (assumes normal distribution)


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
# Warmup Iteration   1: 4.219 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   2.421 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.420 ms/op
                 createUser·p0.99:   4.133 ms/op
                 createUser·p0.999:  10.280 ms/op
                 createUser·p0.9999: 14.547 ms/op
                 createUser·p1.00:   15.532 ms/op

Iteration   2: 2.517 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   2.470 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.400 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  10.732 ms/op
                 createUser·p0.9999: 13.815 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.478 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   4.080 ms/op
                 createUser·p0.999:  9.145 ms/op
                 createUser·p0.9999: 10.948 ms/op
                 createUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383151
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 190 
    [ 1.250,  2.500) = 198810 
    [ 2.500,  3.750) = 175783 
    [ 3.750,  5.000) = 7200 
    [ 5.000,  6.250) = 672 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.355 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      9.170 ms/op
     p(99.9900) =     14.151 ms/op
     p(99.9990) =     15.404 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


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
# Warmup Iteration   1: 3.685 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  5.661 ms/op
                 existUser·p0.9999: 21.299 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  6.970 ms/op
                 existUser·p0.9999: 13.631 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  8.240 ms/op
                 existUser·p0.9999: 11.665 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387833
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191804 
    [ 2.500,  5.000) = 195435 
    [ 5.000,  7.500) = 209 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      7.109 ms/op
     p(99.9900) =     14.048 ms/op
     p(99.9990) =     21.733 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.586 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.195 ms/op
                 getUser·p0.95:   3.445 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.805 ms/op
                 getUser·p0.9999: 14.565 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.354 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  8.252 ms/op
                 getUser·p0.9999: 14.163 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   3: 2.494 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.425 ms/op
                 getUser·p0.90:   3.146 ms/op
                 getUser·p0.95:   3.387 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  8.439 ms/op
                 getUser·p0.9999: 12.553 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377494
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 194263 
    [ 2.500,  3.750) = 174209 
    [ 3.750,  5.000) = 7715 
    [ 5.000,  6.250) = 735 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.379 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.988 ms/op
     p(99.9900) =     14.176 ms/op
     p(99.9990) =     17.473 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 5.016 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.009 ms/op
Iteration   1: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 11.364 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   2: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.414 ms/op
                 listUser·p0.9999: 11.070 ms/op
                 listUser·p1.00:   12.206 ms/op

Iteration   3: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.563 ms/op
                 listUser·p0.999:  10.224 ms/op
                 listUser·p0.9999: 13.025 ms/op
                 listUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312288
  mean =      3.070 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 80061 
    [ 2.500,  3.750) = 188786 
    [ 3.750,  5.000) = 36220 
    [ 5.000,  6.250) = 5770 
    [ 6.250,  7.500) = 694 
    [ 7.500,  8.750) = 260 
    [ 8.750, 10.000) = 189 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.383 ms/op
     p(99.9900) =     12.304 ms/op
     p(99.9990) =     13.159 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.602 ± 3.195  ops/ms
ClientPb.existUser                       thrpt       3  12.683 ± 1.284  ops/ms
ClientPb.getUser                         thrpt       3  12.736 ± 0.476  ops/ms
ClientPb.listUser                        thrpt       3  10.491 ± 0.621  ops/ms
ClientPb.createUser                       avgt       3   2.521 ± 0.740   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.186   ms/op
ClientPb.getUser                          avgt       3   2.498 ± 0.230   ms/op
ClientPb.listUser                         avgt       3   3.031 ± 0.052   ms/op
ClientPb.createUser                     sample  383151   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.782           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.454           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.170           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.151           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.532           ms/op
ClientPb.existUser                      sample  387833   2.473 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.834           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.109           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.048           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.889           ms/op
ClientPb.getUser                        sample  377494   2.541 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.354           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.466           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.988           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.176           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.416           ms/op
ClientPb.listUser                       sample  312288   3.070 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.972           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.383           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.304           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.532           ms/op
