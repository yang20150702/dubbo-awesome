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
# Warmup Iteration   1: 2.252 ops/ms
# Warmup Iteration   2: 5.654 ops/ms
# Warmup Iteration   3: 8.144 ops/ms
Iteration   1: 9.140 ops/ms
Iteration   2: 9.111 ops/ms
Iteration   3: 9.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.224 ±(99.9%) 3.130 ops/ms [Average]
  (min, avg, max) = (9.111, 9.224, 9.421), stdev = 0.172
  CI (99.9%): [6.094, 12.354] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.953 ops/ms
# Warmup Iteration   2: 8.449 ops/ms
# Warmup Iteration   3: 9.502 ops/ms
Iteration   1: 9.836 ops/ms
Iteration   2: 9.601 ops/ms
Iteration   3: 9.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.671 ±(99.9%) 2.619 ops/ms [Average]
  (min, avg, max) = (9.576, 9.671, 9.836), stdev = 0.144
  CI (99.9%): [7.052, 12.290] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.522 ops/ms
# Warmup Iteration   2: 7.942 ops/ms
# Warmup Iteration   3: 8.953 ops/ms
Iteration   1: 9.296 ops/ms
Iteration   2: 9.474 ops/ms
Iteration   3: 9.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.460 ±(99.9%) 2.863 ops/ms [Average]
  (min, avg, max) = (9.296, 9.460, 9.609), stdev = 0.157
  CI (99.9%): [6.597, 12.323] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.815 ops/ms
# Warmup Iteration   2: 7.026 ops/ms
# Warmup Iteration   3: 7.606 ops/ms
Iteration   1: 8.221 ops/ms
Iteration   2: 8.231 ops/ms
Iteration   3: 8.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.152 ±(99.9%) 2.361 ops/ms [Average]
  (min, avg, max) = (8.002, 8.152, 8.231), stdev = 0.129
  CI (99.9%): [5.790, 10.513] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.108 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.005 ms/op
Iteration   1: 3.359 ±(99.9%) 0.013 ms/op
Iteration   2: 3.411 ±(99.9%) 0.012 ms/op
Iteration   3: 3.624 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.465 ±(99.9%) 2.558 ms/op [Average]
  (min, avg, max) = (3.359, 3.465, 3.624), stdev = 0.140
  CI (99.9%): [0.907, 6.023] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.454 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.008 ms/op
Iteration   1: 3.150 ±(99.9%) 0.011 ms/op
Iteration   2: 3.519 ±(99.9%) 0.004 ms/op
Iteration   3: 3.419 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.363 ±(99.9%) 3.488 ms/op [Average]
  (min, avg, max) = (3.150, 3.363, 3.519), stdev = 0.191
  CI (99.9%): [≈ 0, 6.850] (assumes normal distribution)


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
# Warmup Iteration   1: 10.372 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.008 ms/op
Iteration   1: 3.392 ±(99.9%) 0.011 ms/op
Iteration   2: 3.479 ±(99.9%) 0.006 ms/op
Iteration   3: 3.505 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.459 ±(99.9%) 1.077 ms/op [Average]
  (min, avg, max) = (3.392, 3.459, 3.505), stdev = 0.059
  CI (99.9%): [2.382, 4.536] (assumes normal distribution)


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
# Warmup Iteration   1: 11.949 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.396 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.009 ms/op
Iteration   1: 4.048 ±(99.9%) 0.010 ms/op
Iteration   2: 4.009 ±(99.9%) 0.011 ms/op
Iteration   3: 3.956 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.004 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (3.956, 4.004, 4.048), stdev = 0.046
  CI (99.9%): [3.157, 4.852] (assumes normal distribution)


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
# Warmup Iteration   1: 9.808 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
Iteration   1: 3.434 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  20.677 ms/op
                 createUser·p0.9999: 24.347 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   2: 3.607 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  23.471 ms/op
                 createUser·p0.9999: 27.763 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   3: 3.392 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  20.506 ms/op
                 createUser·p0.9999: 28.797 ms/op
                 createUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276179
  mean =      3.475 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4702 
    [ 2.500,  5.000) = 265896 
    [ 5.000,  7.500) = 4462 
    [ 7.500, 10.000) = 511 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     20.966 ms/op
     p(99.9900) =     27.485 ms/op
     p(99.9990) =     29.646 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 9.879 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.011 ms/op
Iteration   1: 3.484 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  10.309 ms/op
                 existUser·p0.9999: 24.019 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   2: 3.532 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  23.285 ms/op
                 existUser·p0.9999: 30.802 ms/op
                 existUser·p1.00:   31.949 ms/op

Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  8.905 ms/op
                 existUser·p0.9999: 25.232 ms/op
                 existUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282017
  mean =      3.400 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8345 
    [ 2.500,  5.000) = 266768 
    [ 5.000,  7.500) = 6026 
    [ 7.500, 10.000) = 565 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     10.338 ms/op
     p(99.9900) =     29.190 ms/op
     p(99.9990) =     31.791 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 10.597 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.702 ±(99.9%) 0.011 ms/op
Iteration   1: 3.568 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  22.785 ms/op
                 getUser·p0.9999: 26.019 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 3.430 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.041 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  22.166 ms/op
                 getUser·p0.9999: 25.417 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   3: 3.576 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  21.482 ms/op
                 getUser·p0.9999: 25.069 ms/op
                 getUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272357
  mean =      3.523 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5071 
    [ 2.500,  5.000) = 258045 
    [ 5.000,  7.500) = 7769 
    [ 7.500, 10.000) = 928 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 191 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     26.953 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 11.122 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.761 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.015 ms/op
Iteration   1: 4.267 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  21.036 ms/op
                 listUser·p0.9999: 22.954 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 3.967 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  15.492 ms/op
                 listUser·p0.9999: 18.809 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   3: 3.921 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.237 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237147
  mean =      4.046 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 227294 
    [ 5.000,  7.500) = 6865 
    [ 7.500, 10.000) = 1907 
    [10.000, 12.500) = 485 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.702 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     15.614 ms/op
     p(99.9900) =     22.455 ms/op
     p(99.9990) =     23.315 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.224 ± 3.130  ops/ms
ClientPb.existUser                       thrpt       3   9.671 ± 2.619  ops/ms
ClientPb.getUser                         thrpt       3   9.460 ± 2.863  ops/ms
ClientPb.listUser                        thrpt       3   8.152 ± 2.361  ops/ms
ClientPb.createUser                       avgt       3   3.465 ± 2.558   ms/op
ClientPb.existUser                        avgt       3   3.363 ± 3.488   ms/op
ClientPb.getUser                          avgt       3   3.459 ± 1.077   ms/op
ClientPb.listUser                         avgt       3   4.004 ± 0.847   ms/op
ClientPb.createUser                     sample  276179   3.475 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.751           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.966           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.485           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.884           ms/op
ClientPb.existUser                      sample  282017   3.400 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.374           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.997           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.338           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.190           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.949           ms/op
ClientPb.getUser                        sample  272357   3.523 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.756           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.537           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.184           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.559           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.263           ms/op
ClientPb.listUser                       sample  237147   4.046 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.702           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.979           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.614           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.455           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.478           ms/op
