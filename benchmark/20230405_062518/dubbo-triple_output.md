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
# Warmup Iteration   1: 0.921 ops/ms
# Warmup Iteration   2: 2.007 ops/ms
# Warmup Iteration   3: 4.563 ops/ms
Iteration   1: 5.246 ops/ms
Iteration   2: 5.319 ops/ms
Iteration   3: 5.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.308 ±(99.9%) 1.043 ops/ms [Average]
  (min, avg, max) = (5.246, 5.308, 5.358), stdev = 0.057
  CI (99.9%): [4.265, 6.350] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.573 ops/ms
# Warmup Iteration   2: 4.293 ops/ms
# Warmup Iteration   3: 5.391 ops/ms
Iteration   1: 5.182 ops/ms
Iteration   2: 5.375 ops/ms
Iteration   3: 5.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.246 ±(99.9%) 2.048 ops/ms [Average]
  (min, avg, max) = (5.179, 5.246, 5.375), stdev = 0.112
  CI (99.9%): [3.197, 7.294] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.436 ops/ms
# Warmup Iteration   2: 3.420 ops/ms
# Warmup Iteration   3: 5.261 ops/ms
Iteration   1: 5.495 ops/ms
Iteration   2: 5.600 ops/ms
Iteration   3: 4.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.344 ±(99.9%) 6.499 ops/ms [Average]
  (min, avg, max) = (4.937, 5.344, 5.600), stdev = 0.356
  CI (99.9%): [≈ 0, 11.843] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.233 ops/ms
# Warmup Iteration   2: 3.380 ops/ms
# Warmup Iteration   3: 4.286 ops/ms
Iteration   1: 4.469 ops/ms
Iteration   2: 4.803 ops/ms
Iteration   3: 4.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.723 ±(99.9%) 4.095 ops/ms [Average]
  (min, avg, max) = (4.469, 4.723, 4.897), stdev = 0.224
  CI (99.9%): [0.628, 8.818] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 20.187 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 7.104 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.032 ±(99.9%) 0.017 ms/op
Iteration   1: 6.526 ±(99.9%) 0.021 ms/op
Iteration   2: 5.822 ±(99.9%) 0.016 ms/op
Iteration   3: 6.130 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.159 ±(99.9%) 6.439 ms/op [Average]
  (min, avg, max) = (5.822, 6.159, 6.526), stdev = 0.353
  CI (99.9%): [≈ 0, 12.598] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 19.915 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 7.286 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.461 ±(99.9%) 0.011 ms/op
Iteration   1: 5.948 ±(99.9%) 0.006 ms/op
Iteration   2: 5.866 ±(99.9%) 0.017 ms/op
Iteration   3: 6.092 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.969 ±(99.9%) 2.085 ms/op [Average]
  (min, avg, max) = (5.866, 5.969, 6.092), stdev = 0.114
  CI (99.9%): [3.884, 8.054] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 19.709 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 7.127 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.060 ±(99.9%) 0.011 ms/op
Iteration   1: 5.910 ±(99.9%) 0.014 ms/op
Iteration   2: 6.191 ±(99.9%) 0.007 ms/op
Iteration   3: 6.051 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.050 ±(99.9%) 2.561 ms/op [Average]
  (min, avg, max) = (5.910, 6.050, 6.191), stdev = 0.140
  CI (99.9%): [3.490, 8.611] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.793 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 8.484 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.796 ±(99.9%) 0.015 ms/op
Iteration   1: 7.370 ±(99.9%) 0.017 ms/op
Iteration   2: 6.642 ±(99.9%) 0.022 ms/op
Iteration   3: 7.000 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.004 ±(99.9%) 6.642 ms/op [Average]
  (min, avg, max) = (6.642, 7.004, 7.370), stdev = 0.364
  CI (99.9%): [0.362, 13.646] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.926 ±(99.9%) 0.357 ms/op
# Warmup Iteration   2: 7.737 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.399 ±(99.9%) 0.027 ms/op
Iteration   1: 6.548 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   2.548 ms/op
                 createUser·p0.50:   6.103 ms/op
                 createUser·p0.90:   8.618 ms/op
                 createUser·p0.95:   10.043 ms/op
                 createUser·p0.99:   14.172 ms/op
                 createUser·p0.999:  25.985 ms/op
                 createUser·p0.9999: 31.661 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   2: 6.408 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   2.544 ms/op
                 createUser·p0.50:   6.013 ms/op
                 createUser·p0.90:   8.262 ms/op
                 createUser·p0.95:   9.585 ms/op
                 createUser·p0.99:   14.336 ms/op
                 createUser·p0.999:  30.643 ms/op
                 createUser·p0.9999: 37.618 ms/op
                 createUser·p1.00:   39.977 ms/op

Iteration   3: 6.269 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.757 ms/op
                 createUser·p0.50:   5.964 ms/op
                 createUser·p0.90:   7.905 ms/op
                 createUser·p0.95:   9.060 ms/op
                 createUser·p0.99:   13.356 ms/op
                 createUser·p0.999:  22.083 ms/op
                 createUser·p0.9999: 30.340 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 149791
  mean =      6.407 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 27311 
    [ 5.000,  7.500) = 96959 
    [ 7.500, 10.000) = 19278 
    [10.000, 12.500) = 3592 
    [12.500, 15.000) = 1550 
    [15.000, 17.500) = 502 
    [17.500, 20.000) = 294 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      2.544 ms/op
     p(50.0000) =      6.021 ms/op
     p(90.0000) =      8.266 ms/op
     p(95.0000) =      9.585 ms/op
     p(99.0000) =     14.025 ms/op
     p(99.9000) =     25.926 ms/op
     p(99.9900) =     36.577 ms/op
     p(99.9990) =     39.063 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.050 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 6.958 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.279 ±(99.9%) 0.030 ms/op
Iteration   1: 6.322 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   1.810 ms/op
                 existUser·p0.50:   5.800 ms/op
                 existUser·p0.90:   8.471 ms/op
                 existUser·p0.95:   10.371 ms/op
                 existUser·p0.99:   15.113 ms/op
                 existUser·p0.999:  24.212 ms/op
                 existUser·p0.9999: 29.225 ms/op
                 existUser·p1.00:   30.704 ms/op

Iteration   2: 5.671 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   7.135 ms/op
                 existUser·p0.95:   8.225 ms/op
                 existUser·p0.99:   11.649 ms/op
                 existUser·p0.999:  19.219 ms/op
                 existUser·p0.9999: 31.719 ms/op
                 existUser·p1.00:   32.702 ms/op

Iteration   3: 5.990 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   5.644 ms/op
                 existUser·p0.90:   7.528 ms/op
                 existUser·p0.95:   8.569 ms/op
                 existUser·p0.99:   12.468 ms/op
                 existUser·p0.999:  28.352 ms/op
                 existUser·p0.9999: 31.741 ms/op
                 existUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 160419
  mean =      5.983 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 45334 
    [ 5.000,  7.500) = 97305 
    [ 7.500, 10.000) = 12243 
    [10.000, 12.500) = 3376 
    [12.500, 15.000) = 1245 
    [15.000, 17.500) = 498 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.660 ms/op
     p(95.0000) =      8.978 ms/op
     p(99.0000) =     13.451 ms/op
     p(99.9000) =     22.765 ms/op
     p(99.9900) =     31.620 ms/op
     p(99.9990) =     33.791 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.235 ±(99.9%) 0.356 ms/op
# Warmup Iteration   2: 7.774 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.833 ±(99.9%) 0.036 ms/op
Iteration   1: 6.095 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   3.142 ms/op
                 getUser·p0.50:   5.685 ms/op
                 getUser·p0.90:   7.479 ms/op
                 getUser·p0.95:   9.159 ms/op
                 getUser·p0.99:   14.451 ms/op
                 getUser·p0.999:  26.594 ms/op
                 getUser·p0.9999: 28.886 ms/op
                 getUser·p1.00:   29.557 ms/op

Iteration   2: 5.783 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.277 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   7.070 ms/op
                 getUser·p0.95:   8.372 ms/op
                 getUser·p0.99:   13.009 ms/op
                 getUser·p0.999:  26.795 ms/op
                 getUser·p0.9999: 32.583 ms/op
                 getUser·p1.00:   34.210 ms/op

Iteration   3: 6.076 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.671 ms/op
                 getUser·p0.50:   5.775 ms/op
                 getUser·p0.90:   7.479 ms/op
                 getUser·p0.95:   8.536 ms/op
                 getUser·p0.99:   12.698 ms/op
                 getUser·p0.999:  20.873 ms/op
                 getUser·p0.9999: 30.129 ms/op
                 getUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 160305
  mean =      5.981 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 39340 
    [ 5.000,  7.500) = 106487 
    [ 7.500, 10.000) = 9361 
    [10.000, 12.500) = 2900 
    [12.500, 15.000) = 1265 
    [15.000, 17.500) = 506 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.277 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.700 ms/op
     p(99.0000) =     13.418 ms/op
     p(99.9000) =     25.942 ms/op
     p(99.9900) =     30.995 ms/op
     p(99.9990) =     33.973 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.546 ±(99.9%) 0.386 ms/op
# Warmup Iteration   2: 8.157 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 7.170 ±(99.9%) 0.029 ms/op
Iteration   1: 7.185 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   6.791 ms/op
                 listUser·p0.90:   9.087 ms/op
                 listUser·p0.95:   10.338 ms/op
                 listUser·p0.99:   14.991 ms/op
                 listUser·p0.999:  26.507 ms/op
                 listUser·p0.9999: 29.098 ms/op
                 listUser·p1.00:   29.458 ms/op

Iteration   2: 7.118 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   2.978 ms/op
                 listUser·p0.50:   6.660 ms/op
                 listUser·p0.90:   9.060 ms/op
                 listUser·p0.95:   10.502 ms/op
                 listUser·p0.99:   15.283 ms/op
                 listUser·p0.999:  29.428 ms/op
                 listUser·p0.9999: 33.020 ms/op
                 listUser·p1.00:   35.258 ms/op

Iteration   3: 7.279 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.961 ms/op
                 listUser·p0.50:   6.898 ms/op
                 listUser·p0.90:   9.290 ms/op
                 listUser·p0.95:   10.437 ms/op
                 listUser·p0.99:   13.058 ms/op
                 listUser·p0.999:  29.965 ms/op
                 listUser·p0.9999: 33.266 ms/op
                 listUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 133396
  mean =      7.193 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 2322 
    [ 5.000,  7.500) = 91182 
    [ 7.500, 10.000) = 31580 
    [10.000, 12.500) = 5651 
    [12.500, 15.000) = 1543 
    [15.000, 17.500) = 599 
    [17.500, 20.000) = 178 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.298 ms/op
     p(50.0000) =      6.775 ms/op
     p(90.0000) =      9.142 ms/op
     p(95.0000) =     10.420 ms/op
     p(99.0000) =     14.385 ms/op
     p(99.9000) =     28.233 ms/op
     p(99.9900) =     32.865 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.308 ± 1.043  ops/ms
ClientPb.existUser                       thrpt       3   5.246 ± 2.048  ops/ms
ClientPb.getUser                         thrpt       3   5.344 ± 6.499  ops/ms
ClientPb.listUser                        thrpt       3   4.723 ± 4.095  ops/ms
ClientPb.createUser                       avgt       3   6.159 ± 6.439   ms/op
ClientPb.existUser                        avgt       3   5.969 ± 2.085   ms/op
ClientPb.getUser                          avgt       3   6.050 ± 2.561   ms/op
ClientPb.listUser                         avgt       3   7.004 ± 6.642   ms/op
ClientPb.createUser                     sample  149791   6.407 ± 0.017   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.50    sample           6.021           ms/op
ClientPb.createUser:createUser·p0.90    sample           8.266           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.585           ms/op
ClientPb.createUser:createUser·p0.99    sample          14.025           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.926           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.577           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.977           ms/op
ClientPb.existUser                      sample  160419   5.983 ± 0.015   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.507           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.660           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.978           ms/op
ClientPb.existUser:existUser·p0.99      sample          13.451           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.765           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.620           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.603           ms/op
ClientPb.getUser                        sample  160305   5.981 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.277           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.324           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.700           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.418           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.942           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.995           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.210           ms/op
ClientPb.listUser                       sample  133396   7.193 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.298           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.775           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.142           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.420           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.385           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.233           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.865           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.258           ms/op
