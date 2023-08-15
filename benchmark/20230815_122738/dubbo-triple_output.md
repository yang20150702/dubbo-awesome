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
# Warmup Iteration   1: 1.041 ops/ms
# Warmup Iteration   2: 2.332 ops/ms
# Warmup Iteration   3: 4.738 ops/ms
Iteration   1: 5.172 ops/ms
Iteration   2: 5.401 ops/ms
Iteration   3: 5.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.373 ±(99.9%) 3.444 ops/ms [Average]
  (min, avg, max) = (5.172, 5.373, 5.547), stdev = 0.189
  CI (99.9%): [1.930, 8.817] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.558 ops/ms
# Warmup Iteration   2: 4.699 ops/ms
# Warmup Iteration   3: 5.714 ops/ms
Iteration   1: 6.032 ops/ms
Iteration   2: 5.879 ops/ms
Iteration   3: 5.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.855 ±(99.9%) 3.472 ops/ms [Average]
  (min, avg, max) = (5.654, 5.855, 6.032), stdev = 0.190
  CI (99.9%): [2.383, 9.326] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.424 ops/ms
# Warmup Iteration   2: 4.369 ops/ms
# Warmup Iteration   3: 5.507 ops/ms
Iteration   1: 5.510 ops/ms
Iteration   2: 5.534 ops/ms
Iteration   3: 5.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.526 ±(99.9%) 0.259 ops/ms [Average]
  (min, avg, max) = (5.510, 5.526, 5.535), stdev = 0.014
  CI (99.9%): [5.268, 5.785] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.293 ops/ms
# Warmup Iteration   2: 3.666 ops/ms
# Warmup Iteration   3: 4.565 ops/ms
Iteration   1: 4.524 ops/ms
Iteration   2: 4.828 ops/ms
Iteration   3: 4.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.638 ±(99.9%) 3.017 ops/ms [Average]
  (min, avg, max) = (4.524, 4.638, 4.828), stdev = 0.165
  CI (99.9%): [1.621, 7.655] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 19.862 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.124 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.124 ±(99.9%) 0.009 ms/op
Iteration   1: 5.988 ±(99.9%) 0.010 ms/op
Iteration   2: 5.932 ±(99.9%) 0.018 ms/op
Iteration   3: 6.013 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.978 ±(99.9%) 0.751 ms/op [Average]
  (min, avg, max) = (5.932, 5.978, 6.013), stdev = 0.041
  CI (99.9%): [5.227, 6.729] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 16.995 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.495 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.720 ±(99.9%) 0.010 ms/op
Iteration   1: 5.462 ±(99.9%) 0.008 ms/op
Iteration   2: 5.499 ±(99.9%) 0.009 ms/op
Iteration   3: 5.354 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.438 ±(99.9%) 1.375 ms/op [Average]
  (min, avg, max) = (5.354, 5.438, 5.499), stdev = 0.075
  CI (99.9%): [4.064, 6.813] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 19.302 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 7.827 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.322 ±(99.9%) 0.005 ms/op
Iteration   1: 5.937 ±(99.9%) 0.008 ms/op
Iteration   2: 5.788 ±(99.9%) 0.011 ms/op
Iteration   3: 5.642 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.789 ±(99.9%) 2.691 ms/op [Average]
  (min, avg, max) = (5.642, 5.789, 5.937), stdev = 0.148
  CI (99.9%): [3.098, 8.480] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 22.028 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 8.458 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 7.448 ±(99.9%) 0.009 ms/op
Iteration   1: 7.112 ±(99.9%) 0.013 ms/op
Iteration   2: 6.671 ±(99.9%) 0.015 ms/op
Iteration   3: 6.537 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.773 ±(99.9%) 5.488 ms/op [Average]
  (min, avg, max) = (6.537, 6.773, 7.112), stdev = 0.301
  CI (99.9%): [1.285, 12.261] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 20.907 ±(99.9%) 0.365 ms/op
# Warmup Iteration   2: 7.827 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.208 ±(99.9%) 0.030 ms/op
Iteration   1: 5.683 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.351 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   7.062 ms/op
                 createUser·p0.95:   8.118 ms/op
                 createUser·p0.99:   10.945 ms/op
                 createUser·p0.999:  17.375 ms/op
                 createUser·p0.9999: 33.657 ms/op
                 createUser·p1.00:   34.079 ms/op

Iteration   2: 5.971 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.580 ms/op
                 createUser·p0.50:   5.587 ms/op
                 createUser·p0.90:   7.463 ms/op
                 createUser·p0.95:   8.684 ms/op
                 createUser·p0.99:   12.085 ms/op
                 createUser·p0.999:  27.409 ms/op
                 createUser·p0.9999: 34.922 ms/op
                 createUser·p1.00:   35.521 ms/op

Iteration   3: 5.788 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.400 ms/op
                 createUser·p0.50:   5.472 ms/op
                 createUser·p0.90:   7.127 ms/op
                 createUser·p0.95:   8.036 ms/op
                 createUser·p0.99:   11.158 ms/op
                 createUser·p0.999:  27.862 ms/op
                 createUser·p0.9999: 33.038 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 165031
  mean =      5.812 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 38985 
    [ 5.000,  7.500) = 112535 
    [ 7.500, 10.000) = 10409 
    [10.000, 12.500) = 2122 
    [12.500, 15.000) = 630 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.351 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      7.225 ms/op
     p(95.0000) =      8.266 ms/op
     p(99.0000) =     11.420 ms/op
     p(99.9000) =     19.972 ms/op
     p(99.9900) =     33.980 ms/op
     p(99.9990) =     35.435 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.609 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 7.158 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.453 ±(99.9%) 0.019 ms/op
Iteration   1: 5.587 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.273 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   7.291 ms/op
                 existUser·p0.95:   8.815 ms/op
                 existUser·p0.99:   12.239 ms/op
                 existUser·p0.999:  22.197 ms/op
                 existUser·p0.9999: 27.436 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 5.607 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.617 ms/op
                 existUser·p0.50:   5.145 ms/op
                 existUser·p0.90:   7.029 ms/op
                 existUser·p0.95:   8.274 ms/op
                 existUser·p0.99:   12.567 ms/op
                 existUser·p0.999:  26.287 ms/op
                 existUser·p0.9999: 32.633 ms/op
                 existUser·p1.00:   33.128 ms/op

Iteration   3: 5.459 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.593 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   6.849 ms/op
                 existUser·p0.95:   7.848 ms/op
                 existUser·p0.99:   10.569 ms/op
                 existUser·p0.999:  28.256 ms/op
                 existUser·p0.9999: 36.979 ms/op
                 existUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 173057
  mean =      5.550 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 70476 
    [ 5.000,  7.500) = 89615 
    [ 7.500, 10.000) = 9332 
    [10.000, 12.500) = 2298 
    [12.500, 15.000) = 738 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.273 ms/op
     p(50.0000) =      5.128 ms/op
     p(90.0000) =      7.021 ms/op
     p(95.0000) =      8.356 ms/op
     p(99.0000) =     11.895 ms/op
     p(99.9000) =     25.262 ms/op
     p(99.9900) =     32.725 ms/op
     p(99.9990) =     37.540 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 20.120 ±(99.9%) 0.390 ms/op
# Warmup Iteration   2: 6.750 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.933 ±(99.9%) 0.023 ms/op
Iteration   1: 5.944 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.676 ms/op
                 getUser·p0.95:   9.503 ms/op
                 getUser·p0.99:   13.347 ms/op
                 getUser·p0.999:  21.823 ms/op
                 getUser·p0.9999: 27.250 ms/op
                 getUser·p1.00:   27.525 ms/op

Iteration   2: 5.897 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   7.455 ms/op
                 getUser·p0.95:   8.782 ms/op
                 getUser·p0.99:   11.794 ms/op
                 getUser·p0.999:  26.390 ms/op
                 getUser·p0.9999: 31.842 ms/op
                 getUser·p1.00:   32.965 ms/op

Iteration   3: 5.900 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.793 ms/op
                 getUser·p0.50:   5.513 ms/op
                 getUser·p0.90:   7.365 ms/op
                 getUser·p0.95:   8.733 ms/op
                 getUser·p0.99:   12.009 ms/op
                 getUser·p0.999:  28.187 ms/op
                 getUser·p0.9999: 31.926 ms/op
                 getUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162250
  mean =      5.914 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 34850 
    [ 5.000,  7.500) = 111270 
    [ 7.500, 10.000) = 11436 
    [10.000, 12.500) = 3034 
    [12.500, 15.000) = 893 
    [15.000, 17.500) = 406 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      7.487 ms/op
     p(95.0000) =      9.011 ms/op
     p(99.0000) =     12.550 ms/op
     p(99.9000) =     24.994 ms/op
     p(99.9900) =     31.614 ms/op
     p(99.9990) =     32.903 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.544 ±(99.9%) 0.356 ms/op
# Warmup Iteration   2: 8.515 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 7.207 ±(99.9%) 0.033 ms/op
Iteration   1: 6.923 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.330 ms/op
                 listUser·p0.50:   6.488 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   10.240 ms/op
                 listUser·p0.99:   13.648 ms/op
                 listUser·p0.999:  29.393 ms/op
                 listUser·p0.9999: 37.577 ms/op
                 listUser·p1.00:   44.040 ms/op

Iteration   2: 6.903 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   6.504 ms/op
                 listUser·p0.90:   8.225 ms/op
                 listUser·p0.95:   9.880 ms/op
                 listUser·p0.99:   13.631 ms/op
                 listUser·p0.999:  30.491 ms/op
                 listUser·p0.9999: 34.716 ms/op
                 listUser·p1.00:   36.831 ms/op

Iteration   3: 6.899 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.765 ms/op
                 listUser·p0.50:   6.406 ms/op
                 listUser·p0.90:   8.782 ms/op
                 listUser·p0.95:   10.174 ms/op
                 listUser·p0.99:   13.599 ms/op
                 listUser·p0.999:  29.369 ms/op
                 listUser·p0.9999: 32.988 ms/op
                 listUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138971
  mean =      6.908 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2113 
    [ 5.000, 10.000) = 129600 
    [10.000, 15.000) = 6403 
    [15.000, 20.000) = 535 
    [20.000, 25.000) = 62 
    [25.000, 30.000) = 130 
    [30.000, 35.000) = 110 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.388 ms/op
     p(50.0000) =      6.472 ms/op
     p(90.0000) =      8.536 ms/op
     p(95.0000) =     10.099 ms/op
     p(99.0000) =     13.631 ms/op
     p(99.9000) =     29.753 ms/op
     p(99.9900) =     35.993 ms/op
     p(99.9990) =     42.916 ms/op
     p(99.9999) =     44.040 ms/op
    p(100.0000) =     44.040 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.373 ± 3.444  ops/ms
ClientPb.existUser                       thrpt       3   5.855 ± 3.472  ops/ms
ClientPb.getUser                         thrpt       3   5.526 ± 0.259  ops/ms
ClientPb.listUser                        thrpt       3   4.638 ± 3.017  ops/ms
ClientPb.createUser                       avgt       3   5.978 ± 0.751   ms/op
ClientPb.existUser                        avgt       3   5.438 ± 1.375   ms/op
ClientPb.getUser                          avgt       3   5.789 ± 2.691   ms/op
ClientPb.listUser                         avgt       3   6.773 ± 5.488   ms/op
ClientPb.createUser                     sample  165031   5.812 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.351           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.266           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.420           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.972           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.980           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.521           ms/op
ClientPb.existUser                      sample  173057   5.550 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.273           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.021           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.356           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.895           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.262           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.725           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.683           ms/op
ClientPb.getUser                        sample  162250   5.914 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.813           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.497           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.487           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.011           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.550           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.994           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.614           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.965           ms/op
ClientPb.listUser                       sample  138971   6.908 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.388           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.472           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.099           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.631           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.753           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.993           ms/op
ClientPb.listUser:listUser·p1.00        sample          44.040           ms/op
