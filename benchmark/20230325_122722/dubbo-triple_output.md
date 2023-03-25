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
# Warmup Iteration   1: 2.689 ops/ms
# Warmup Iteration   2: 6.285 ops/ms
# Warmup Iteration   3: 9.132 ops/ms
Iteration   1: 10.134 ops/ms
Iteration   2: 9.865 ops/ms
Iteration   3: 10.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.053 ±(99.9%) 2.978 ops/ms [Average]
  (min, avg, max) = (9.865, 10.053, 10.160), stdev = 0.163
  CI (99.9%): [7.075, 13.031] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.153 ops/ms
# Warmup Iteration   2: 9.617 ops/ms
# Warmup Iteration   3: 10.117 ops/ms
Iteration   1: 10.428 ops/ms
Iteration   2: 10.418 ops/ms
Iteration   3: 10.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.560 ±(99.9%) 4.324 ops/ms [Average]
  (min, avg, max) = (10.418, 10.560, 10.834), stdev = 0.237
  CI (99.9%): [6.236, 14.884] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.801 ops/ms
# Warmup Iteration   2: 9.677 ops/ms
# Warmup Iteration   3: 9.562 ops/ms
Iteration   1: 10.538 ops/ms
Iteration   2: 10.189 ops/ms
Iteration   3: 10.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.408 ±(99.9%) 3.485 ops/ms [Average]
  (min, avg, max) = (10.189, 10.408, 10.538), stdev = 0.191
  CI (99.9%): [6.924, 13.893] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.682 ops/ms
# Warmup Iteration   2: 8.134 ops/ms
# Warmup Iteration   3: 8.312 ops/ms
Iteration   1: 8.527 ops/ms
Iteration   2: 8.727 ops/ms
Iteration   3: 8.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.659 ±(99.9%) 2.074 ops/ms [Average]
  (min, avg, max) = (8.527, 8.659, 8.727), stdev = 0.114
  CI (99.9%): [6.584, 10.733] (assumes normal distribution)


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
# Warmup Iteration   1: 8.969 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.006 ms/op
Iteration   1: 3.223 ±(99.9%) 0.003 ms/op
Iteration   2: 3.111 ±(99.9%) 0.005 ms/op
Iteration   3: 3.080 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.138 ±(99.9%) 1.369 ms/op [Average]
  (min, avg, max) = (3.080, 3.138, 3.223), stdev = 0.075
  CI (99.9%): [1.769, 4.507] (assumes normal distribution)


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
# Warmup Iteration   1: 6.261 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.004 ms/op
Iteration   1: 3.147 ±(99.9%) 0.004 ms/op
Iteration   2: 3.024 ±(99.9%) 0.002 ms/op
Iteration   3: 3.020 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.064 ±(99.9%) 1.322 ms/op [Average]
  (min, avg, max) = (3.020, 3.064, 3.147), stdev = 0.072
  CI (99.9%): [1.741, 4.386] (assumes normal distribution)


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
# Warmup Iteration   1: 7.121 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.445 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.002 ms/op
Iteration   1: 3.069 ±(99.9%) 0.002 ms/op
Iteration   2: 3.115 ±(99.9%) 0.005 ms/op
Iteration   3: 3.158 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.114 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (3.069, 3.114, 3.158), stdev = 0.045
  CI (99.9%): [2.299, 3.928] (assumes normal distribution)


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
# Warmup Iteration   1: 8.697 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.006 ms/op
Iteration   1: 3.662 ±(99.9%) 0.005 ms/op
Iteration   2: 3.701 ±(99.9%) 0.008 ms/op
Iteration   3: 3.711 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.692 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (3.662, 3.692, 3.711), stdev = 0.026
  CI (99.9%): [3.220, 4.163] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.756 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
Iteration   1: 3.044 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.310 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  11.566 ms/op
                 createUser·p0.9999: 19.546 ms/op
                 createUser·p1.00:   20.054 ms/op

Iteration   2: 3.148 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 23.386 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.195 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   4.067 ms/op
                 createUser·p0.999:  12.610 ms/op
                 createUser·p0.9999: 17.743 ms/op
                 createUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 311965
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23174 
    [ 2.500,  5.000) = 284537 
    [ 5.000,  7.500) = 3460 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     12.550 ms/op
     p(99.9900) =     22.079 ms/op
     p(99.9990) =     24.277 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.580 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  10.295 ms/op
                 existUser·p0.9999: 21.975 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   2: 3.146 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  13.404 ms/op
                 existUser·p0.9999: 25.685 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   3: 3.430 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   4.997 ms/op
                 existUser·p0.95:   5.734 ms/op
                 existUser·p0.99:   7.373 ms/op
                 existUser·p0.999:  15.920 ms/op
                 existUser·p0.9999: 24.827 ms/op
                 existUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301830
  mean =      3.181 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21255 
    [ 2.500,  5.000) = 268343 
    [ 5.000,  7.500) = 11002 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     14.885 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 7.304 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.010 ms/op
Iteration   1: 3.063 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  17.419 ms/op
                 getUser·p0.9999: 23.972 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   2: 3.184 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  13.308 ms/op
                 getUser·p0.9999: 22.400 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   5.697 ms/op
                 getUser·p0.999:  11.076 ms/op
                 getUser·p0.9999: 30.940 ms/op
                 getUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304254
  mean =      3.155 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13016 
    [ 2.500,  5.000) = 285781 
    [ 5.000,  7.500) = 4596 
    [ 7.500, 10.000) = 387 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     15.069 ms/op
     p(99.9900) =     28.986 ms/op
     p(99.9990) =     31.587 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 9.296 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.012 ms/op
Iteration   1: 3.708 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 20.230 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   2: 3.723 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 15.293 ms/op
                 listUser·p1.00:   16.204 ms/op

Iteration   3: 3.781 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256809
  mean =      3.737 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 248525 
    [ 5.000,  7.500) = 6658 
    [ 7.500, 10.000) = 940 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 336 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.479 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     20.130 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.053 ± 2.978  ops/ms
ClientPb.existUser                       thrpt       3  10.560 ± 4.324  ops/ms
ClientPb.getUser                         thrpt       3  10.408 ± 3.485  ops/ms
ClientPb.listUser                        thrpt       3   8.659 ± 2.074  ops/ms
ClientPb.createUser                       avgt       3   3.138 ± 1.369   ms/op
ClientPb.existUser                        avgt       3   3.064 ± 1.322   ms/op
ClientPb.getUser                          avgt       3   3.114 ± 0.814   ms/op
ClientPb.listUser                         avgt       3   3.692 ± 0.471   ms/op
ClientPb.createUser                     sample  311965   3.073 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.784           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.645           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.550           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.079           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.314           ms/op
ClientPb.existUser                      sample  301830   3.181 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.993           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.373           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.885           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.068           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.051           ms/op
ClientPb.getUser                        sample  304254   3.155 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.640           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.535           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.456           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.069           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.986           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.178           ms/op
ClientPb.listUser                       sample  256809   3.737 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.479           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.353           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.130           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.266           ms/op
