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
# Warmup Iteration   1: 1.147 ops/ms
# Warmup Iteration   2: 2.750 ops/ms
# Warmup Iteration   3: 5.876 ops/ms
Iteration   1: 5.950 ops/ms
Iteration   2: 6.424 ops/ms
Iteration   3: 6.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.269 ±(99.9%) 5.038 ops/ms [Average]
  (min, avg, max) = (5.950, 6.269, 6.433), stdev = 0.276
  CI (99.9%): [1.231, 11.307] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.901 ops/ms
# Warmup Iteration   2: 5.202 ops/ms
# Warmup Iteration   3: 6.498 ops/ms
Iteration   1: 6.821 ops/ms
Iteration   2: 6.620 ops/ms
Iteration   3: 7.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.839 ±(99.9%) 4.168 ops/ms [Average]
  (min, avg, max) = (6.620, 6.839, 7.076), stdev = 0.228
  CI (99.9%): [2.671, 11.007] (assumes normal distribution)


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
# Warmup Iteration   1: 1.818 ops/ms
# Warmup Iteration   2: 4.806 ops/ms
# Warmup Iteration   3: 6.307 ops/ms
Iteration   1: 6.509 ops/ms
Iteration   2: 6.688 ops/ms
Iteration   3: 6.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.605 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (6.509, 6.605, 6.688), stdev = 0.091
  CI (99.9%): [4.953, 8.258] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.769 ops/ms
# Warmup Iteration   2: 4.744 ops/ms
# Warmup Iteration   3: 5.538 ops/ms
Iteration   1: 5.467 ops/ms
Iteration   2: 5.800 ops/ms
Iteration   3: 5.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.653 ±(99.9%) 3.103 ops/ms [Average]
  (min, avg, max) = (5.467, 5.653, 5.800), stdev = 0.170
  CI (99.9%): [2.550, 8.756] (assumes normal distribution)


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
# Warmup Iteration   1: 16.436 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.820 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.145 ±(99.9%) 0.014 ms/op
Iteration   1: 5.153 ±(99.9%) 0.014 ms/op
Iteration   2: 4.911 ±(99.9%) 0.013 ms/op
Iteration   3: 4.858 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.974 ±(99.9%) 2.863 ms/op [Average]
  (min, avg, max) = (4.858, 4.974, 5.153), stdev = 0.157
  CI (99.9%): [2.111, 7.837] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 15.402 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.177 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.819 ±(99.9%) 0.010 ms/op
Iteration   1: 4.691 ±(99.9%) 0.007 ms/op
Iteration   2: 4.662 ±(99.9%) 0.010 ms/op
Iteration   3: 4.554 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.636 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (4.554, 4.636, 4.691), stdev = 0.072
  CI (99.9%): [3.323, 5.948] (assumes normal distribution)


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
# Warmup Iteration   1: 16.351 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.666 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.992 ±(99.9%) 0.009 ms/op
Iteration   1: 5.128 ±(99.9%) 0.009 ms/op
Iteration   2: 5.216 ±(99.9%) 0.010 ms/op
Iteration   3: 4.755 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.033 ±(99.9%) 4.464 ms/op [Average]
  (min, avg, max) = (4.755, 5.033, 5.216), stdev = 0.245
  CI (99.9%): [0.570, 9.497] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 18.576 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.628 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.737 ±(99.9%) 0.015 ms/op
Iteration   1: 5.653 ±(99.9%) 0.018 ms/op
Iteration   2: 5.662 ±(99.9%) 0.018 ms/op
Iteration   3: 5.616 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.644 ±(99.9%) 0.441 ms/op [Average]
  (min, avg, max) = (5.616, 5.644, 5.662), stdev = 0.024
  CI (99.9%): [5.202, 6.085] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.648 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 6.111 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.450 ±(99.9%) 0.023 ms/op
Iteration   1: 5.198 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   4.874 ms/op
                 createUser·p0.90:   6.496 ms/op
                 createUser·p0.95:   7.627 ms/op
                 createUser·p0.99:   10.579 ms/op
                 createUser·p0.999:  19.530 ms/op
                 createUser·p0.9999: 21.880 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   2: 4.913 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.679 ms/op
                 createUser·p0.50:   4.669 ms/op
                 createUser·p0.90:   5.898 ms/op
                 createUser·p0.95:   6.742 ms/op
                 createUser·p0.99:   9.519 ms/op
                 createUser·p0.999:  16.843 ms/op
                 createUser·p0.9999: 22.985 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   3: 5.038 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.298 ms/op
                 createUser·p0.50:   4.719 ms/op
                 createUser·p0.90:   6.373 ms/op
                 createUser·p0.95:   7.048 ms/op
                 createUser·p0.99:   9.191 ms/op
                 createUser·p0.999:  21.499 ms/op
                 createUser·p0.9999: 24.465 ms/op
                 createUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 190019
  mean =      5.047 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 119228 
    [ 5.000,  7.500) = 63195 
    [ 7.500, 10.000) = 5828 
    [10.000, 12.500) = 1101 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.119 ms/op
     p(99.0000) =      9.778 ms/op
     p(99.9000) =     19.528 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     25.238 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.530 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.473 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.917 ±(99.9%) 0.018 ms/op
Iteration   1: 4.736 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.765 ms/op
                 existUser·p0.50:   4.473 ms/op
                 existUser·p0.90:   5.710 ms/op
                 existUser·p0.95:   6.414 ms/op
                 existUser·p0.99:   9.077 ms/op
                 existUser·p0.999:  17.072 ms/op
                 existUser·p0.9999: 26.779 ms/op
                 existUser·p1.00:   31.293 ms/op

Iteration   2: 4.826 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.706 ms/op
                 existUser·p0.50:   4.555 ms/op
                 existUser·p0.90:   5.923 ms/op
                 existUser·p0.95:   6.734 ms/op
                 existUser·p0.99:   9.511 ms/op
                 existUser·p0.999:  15.511 ms/op
                 existUser·p0.9999: 33.075 ms/op
                 existUser·p1.00:   35.783 ms/op

Iteration   3: 4.770 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.892 ms/op
                 existUser·p0.50:   4.448 ms/op
                 existUser·p0.90:   5.874 ms/op
                 existUser·p0.95:   6.898 ms/op
                 existUser·p0.99:   10.256 ms/op
                 existUser·p0.999:  20.546 ms/op
                 existUser·p0.9999: 29.599 ms/op
                 existUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 200855
  mean =      4.777 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 150204 
    [ 5.000,  7.500) = 44413 
    [ 7.500, 10.000) = 4434 
    [10.000, 12.500) = 1086 
    [12.500, 15.000) = 346 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.652 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     18.598 ms/op
     p(99.9900) =     32.167 ms/op
     p(99.9990) =     33.684 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 16.717 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 6.651 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.234 ±(99.9%) 0.021 ms/op
Iteration   1: 4.962 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.884 ms/op
                 getUser·p0.50:   4.645 ms/op
                 getUser·p0.90:   6.078 ms/op
                 getUser·p0.95:   7.234 ms/op
                 getUser·p0.99:   10.338 ms/op
                 getUser·p0.999:  20.251 ms/op
                 getUser·p0.9999: 23.972 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   2: 4.905 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.306 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   5.980 ms/op
                 getUser·p0.95:   7.168 ms/op
                 getUser·p0.99:   10.256 ms/op
                 getUser·p0.999:  21.730 ms/op
                 getUser·p0.9999: 30.519 ms/op
                 getUser·p1.00:   31.228 ms/op

Iteration   3: 4.935 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   4.653 ms/op
                 getUser·p0.90:   6.021 ms/op
                 getUser·p0.95:   6.922 ms/op
                 getUser·p0.99:   9.585 ms/op
                 getUser·p0.999:  19.397 ms/op
                 getUser·p0.9999: 28.623 ms/op
                 getUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 194552
  mean =      4.934 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 133817 
    [ 5.000,  7.500) = 53222 
    [ 7.500, 10.000) = 5542 
    [10.000, 12.500) = 1188 
    [12.500, 15.000) = 391 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      6.029 ms/op
     p(95.0000) =      7.111 ms/op
     p(99.0000) =      9.994 ms/op
     p(99.9000) =     20.724 ms/op
     p(99.9900) =     29.149 ms/op
     p(99.9990) =     31.135 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.745 ±(99.9%) 0.292 ms/op
# Warmup Iteration   2: 6.958 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.858 ±(99.9%) 0.024 ms/op
Iteration   1: 5.879 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.062 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   6.963 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   12.124 ms/op
                 listUser·p0.999:  24.871 ms/op
                 listUser·p0.9999: 29.367 ms/op
                 listUser·p1.00:   29.786 ms/op

Iteration   2: 5.760 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.870 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   6.808 ms/op
                 listUser·p0.95:   7.635 ms/op
                 listUser·p0.99:   10.699 ms/op
                 listUser·p0.999:  27.492 ms/op
                 listUser·p0.9999: 32.466 ms/op
                 listUser·p1.00:   33.030 ms/op

Iteration   3: 5.814 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   6.906 ms/op
                 listUser·p0.95:   7.881 ms/op
                 listUser·p0.99:   11.141 ms/op
                 listUser·p0.999:  19.038 ms/op
                 listUser·p0.9999: 21.381 ms/op
                 listUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 164994
  mean =      5.817 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 28621 
    [ 5.000,  7.500) = 125797 
    [ 7.500, 10.000) = 7615 
    [10.000, 12.500) = 1910 
    [12.500, 15.000) = 458 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      5.521 ms/op
     p(90.0000) =      6.881 ms/op
     p(95.0000) =      7.954 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     24.740 ms/op
     p(99.9900) =     31.277 ms/op
     p(99.9990) =     33.009 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.269 ± 5.038  ops/ms
ClientPb.existUser                       thrpt       3   6.839 ± 4.168  ops/ms
ClientPb.getUser                         thrpt       3   6.605 ± 1.652  ops/ms
ClientPb.listUser                        thrpt       3   5.653 ± 3.103  ops/ms
ClientPb.createUser                       avgt       3   4.974 ± 2.863   ms/op
ClientPb.existUser                        avgt       3   4.636 ± 1.313   ms/op
ClientPb.getUser                          avgt       3   5.033 ± 4.464   ms/op
ClientPb.listUser                         avgt       3   5.644 ± 0.441   ms/op
ClientPb.createUser                     sample  190019   5.047 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.130           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.743           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.267           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.119           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.778           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.528           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.855           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.182           ms/op
ClientPb.existUser                      sample  200855   4.777 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.706           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.489           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.833           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.652           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.650           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.598           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.167           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.783           ms/op
ClientPb.getUser                        sample  194552   4.934 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.077           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.111           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.994           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.724           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.149           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.228           ms/op
ClientPb.listUser                       sample  164994   5.817 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.497           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.881           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.954           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.321           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.740           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.277           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.030           ms/op
