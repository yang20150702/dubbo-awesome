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
# Warmup Iteration   1: 2.155 ops/ms
# Warmup Iteration   2: 5.747 ops/ms
# Warmup Iteration   3: 8.594 ops/ms
Iteration   1: 9.372 ops/ms
Iteration   2: 9.564 ops/ms
Iteration   3: 9.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.420 ±(99.9%) 2.300 ops/ms [Average]
  (min, avg, max) = (9.326, 9.420, 9.564), stdev = 0.126
  CI (99.9%): [7.120, 11.720] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.854 ops/ms
# Warmup Iteration   2: 8.860 ops/ms
# Warmup Iteration   3: 9.488 ops/ms
Iteration   1: 9.641 ops/ms
Iteration   2: 9.861 ops/ms
Iteration   3: 9.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.785 ±(99.9%) 2.265 ops/ms [Average]
  (min, avg, max) = (9.641, 9.785, 9.861), stdev = 0.124
  CI (99.9%): [7.519, 12.050] (assumes normal distribution)


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
# Warmup Iteration   1: 2.851 ops/ms
# Warmup Iteration   2: 8.401 ops/ms
# Warmup Iteration   3: 9.422 ops/ms
Iteration   1: 9.461 ops/ms
Iteration   2: 9.603 ops/ms
Iteration   3: 9.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.557 ±(99.9%) 1.526 ops/ms [Average]
  (min, avg, max) = (9.461, 9.557, 9.609), stdev = 0.084
  CI (99.9%): [8.031, 11.084] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 6.688 ops/ms
# Warmup Iteration   3: 7.894 ops/ms
Iteration   1: 7.618 ops/ms
Iteration   2: 8.095 ops/ms
Iteration   3: 8.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.975 ±(99.9%) 5.728 ops/ms [Average]
  (min, avg, max) = (7.618, 7.975, 8.211), stdev = 0.314
  CI (99.9%): [2.246, 13.703] (assumes normal distribution)


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
# Warmup Iteration   1: 10.123 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.006 ms/op
Iteration   1: 3.375 ±(99.9%) 0.007 ms/op
Iteration   2: 3.315 ±(99.9%) 0.010 ms/op
Iteration   3: 3.384 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.358 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (3.315, 3.358, 3.384), stdev = 0.037
  CI (99.9%): [2.677, 4.039] (assumes normal distribution)


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
# Warmup Iteration   1: 8.152 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.005 ms/op
Iteration   1: 3.215 ±(99.9%) 0.011 ms/op
Iteration   2: 3.342 ±(99.9%) 0.009 ms/op
Iteration   3: 3.249 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.269 ±(99.9%) 1.200 ms/op [Average]
  (min, avg, max) = (3.215, 3.269, 3.342), stdev = 0.066
  CI (99.9%): [2.069, 4.469] (assumes normal distribution)


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
# Warmup Iteration   1: 8.701 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.006 ms/op
Iteration   1: 3.477 ±(99.9%) 0.006 ms/op
Iteration   2: 3.439 ±(99.9%) 0.005 ms/op
Iteration   3: 3.606 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.507 ±(99.9%) 1.595 ms/op [Average]
  (min, avg, max) = (3.439, 3.507, 3.606), stdev = 0.087
  CI (99.9%): [1.912, 5.102] (assumes normal distribution)


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
# Warmup Iteration   1: 11.103 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.615 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.008 ms/op
Iteration   1: 4.038 ±(99.9%) 0.009 ms/op
Iteration   2: 3.971 ±(99.9%) 0.007 ms/op
Iteration   3: 4.029 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.012 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.971, 4.012, 4.038), stdev = 0.037
  CI (99.9%): [3.345, 4.680] (assumes normal distribution)


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
# Warmup Iteration   1: 10.115 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.012 ms/op
Iteration   1: 3.767 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.538 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   6.259 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  21.526 ms/op
                 createUser·p0.9999: 23.871 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   2: 3.470 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  22.079 ms/op
                 createUser·p0.9999: 32.499 ms/op
                 createUser·p1.00:   33.456 ms/op

Iteration   3: 3.512 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.807 ms/op
                 createUser·p0.999:  24.391 ms/op
                 createUser·p0.9999: 29.057 ms/op
                 createUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268421
  mean =      3.578 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4599 
    [ 2.500,  5.000) = 251387 
    [ 5.000,  7.500) = 10691 
    [ 7.500, 10.000) = 1068 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     22.105 ms/op
     p(99.9900) =     31.102 ms/op
     p(99.9990) =     32.746 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 9.087 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.008 ms/op
Iteration   1: 3.371 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.597 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  10.142 ms/op
                 existUser·p0.9999: 27.361 ms/op
                 existUser·p1.00:   27.918 ms/op

Iteration   2: 3.350 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  20.808 ms/op
                 existUser·p0.9999: 26.411 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   3: 3.209 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  9.610 ms/op
                 existUser·p0.9999: 27.625 ms/op
                 existUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290201
  mean =      3.308 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16235 
    [ 2.500,  5.000) = 267837 
    [ 5.000,  7.500) = 5429 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 81 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     12.431 ms/op
     p(99.9900) =     27.262 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 10.050 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.012 ms/op
Iteration   1: 3.480 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  21.368 ms/op
                 getUser·p0.9999: 23.470 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 3.414 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.584 ms/op
                 getUser·p0.999:  23.822 ms/op
                 getUser·p0.9999: 28.431 ms/op
                 getUser·p1.00:   28.836 ms/op

Iteration   3: 3.431 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.501 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  22.133 ms/op
                 getUser·p0.9999: 27.646 ms/op
                 getUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278702
  mean =      3.442 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7000 
    [ 2.500,  5.000) = 265173 
    [ 5.000,  7.500) = 5338 
    [ 7.500, 10.000) = 662 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     21.604 ms/op
     p(99.9900) =     27.988 ms/op
     p(99.9990) =     28.667 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 11.160 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.683 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.015 ms/op
Iteration   1: 4.066 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  23.339 ms/op
                 listUser·p0.9999: 42.074 ms/op
                 listUser·p1.00:   42.533 ms/op

Iteration   2: 3.967 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.322 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 25.127 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   3: 4.099 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.990 ms/op
                 listUser·p0.99:   7.530 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237379
  mean =      4.043 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 228480 
    [ 5.000, 10.000) = 8072 
    [10.000, 15.000) = 404 
    [15.000, 20.000) = 295 
    [20.000, 25.000) = 78 
    [25.000, 30.000) = 18 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     39.387 ms/op
     p(99.9990) =     42.394 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.420 ± 2.300  ops/ms
ClientPb.existUser                       thrpt       3   9.785 ± 2.265  ops/ms
ClientPb.getUser                         thrpt       3   9.557 ± 1.526  ops/ms
ClientPb.listUser                        thrpt       3   7.975 ± 5.728  ops/ms
ClientPb.createUser                       avgt       3   3.358 ± 0.681   ms/op
ClientPb.existUser                        avgt       3   3.269 ± 1.200   ms/op
ClientPb.getUser                          avgt       3   3.507 ± 1.595   ms/op
ClientPb.listUser                         avgt       3   4.012 ± 0.667   ms/op
ClientPb.createUser                     sample  268421   3.578 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.538           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.882           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.217           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.105           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.102           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.456           ms/op
ClientPb.existUser                      sample  290201   3.308 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.122           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.743           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.431           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.262           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.967           ms/op
ClientPb.getUser                        sample  278702   3.442 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.161           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.604           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.988           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.836           ms/op
ClientPb.listUser                       sample  237379   4.043 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.968           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.447           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.072           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.533           ms/op
