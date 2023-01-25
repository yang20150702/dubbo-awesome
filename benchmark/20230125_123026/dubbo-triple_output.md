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
# Warmup Iteration   1: 1.553 ops/ms
# Warmup Iteration   2: 3.556 ops/ms
# Warmup Iteration   3: 7.387 ops/ms
Iteration   1: 7.391 ops/ms
Iteration   2: 7.860 ops/ms
Iteration   3: 8.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.797 ±(99.9%) 6.908 ops/ms [Average]
  (min, avg, max) = (7.391, 7.797, 8.140), stdev = 0.379
  CI (99.9%): [0.890, 14.705] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.073 ops/ms
# Warmup Iteration   2: 6.540 ops/ms
# Warmup Iteration   3: 7.589 ops/ms
Iteration   1: 7.976 ops/ms
Iteration   2: 8.319 ops/ms
Iteration   3: 8.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.183 ±(99.9%) 3.321 ops/ms [Average]
  (min, avg, max) = (7.976, 8.183, 8.319), stdev = 0.182
  CI (99.9%): [4.862, 11.504] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.289 ops/ms
# Warmup Iteration   2: 5.701 ops/ms
# Warmup Iteration   3: 7.821 ops/ms
Iteration   1: 8.076 ops/ms
Iteration   2: 8.141 ops/ms
Iteration   3: 7.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.051 ±(99.9%) 1.923 ops/ms [Average]
  (min, avg, max) = (7.935, 8.051, 8.141), stdev = 0.105
  CI (99.9%): [6.127, 9.974] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.044 ops/ms
# Warmup Iteration   2: 5.838 ops/ms
# Warmup Iteration   3: 6.401 ops/ms
Iteration   1: 6.768 ops/ms
Iteration   2: 6.899 ops/ms
Iteration   3: 7.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.893 ±(99.9%) 2.219 ops/ms [Average]
  (min, avg, max) = (6.768, 6.893, 7.011), stdev = 0.122
  CI (99.9%): [4.673, 9.112] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 14.804 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.113 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.389 ±(99.9%) 0.003 ms/op
Iteration   1: 4.101 ±(99.9%) 0.010 ms/op
Iteration   2: 3.980 ±(99.9%) 0.008 ms/op
Iteration   3: 3.958 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.013 ±(99.9%) 1.407 ms/op [Average]
  (min, avg, max) = (3.958, 4.013, 4.101), stdev = 0.077
  CI (99.9%): [2.606, 5.420] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 14.108 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.966 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.005 ms/op
Iteration   1: 3.833 ±(99.9%) 0.007 ms/op
Iteration   2: 3.798 ±(99.9%) 0.005 ms/op
Iteration   3: 3.778 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.803 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.778, 3.803, 3.833), stdev = 0.028
  CI (99.9%): [3.294, 4.313] (assumes normal distribution)


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
# Warmup Iteration   1: 13.559 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.569 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.010 ms/op
Iteration   1: 4.184 ±(99.9%) 0.005 ms/op
Iteration   2: 3.993 ±(99.9%) 0.007 ms/op
Iteration   3: 3.904 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.027 ±(99.9%) 2.610 ms/op [Average]
  (min, avg, max) = (3.904, 4.027, 4.184), stdev = 0.143
  CI (99.9%): [1.417, 6.637] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.270 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.409 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.944 ±(99.9%) 0.006 ms/op
Iteration   1: 4.848 ±(99.9%) 0.009 ms/op
Iteration   2: 4.732 ±(99.9%) 0.007 ms/op
Iteration   3: 4.694 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.758 ±(99.9%) 1.465 ms/op [Average]
  (min, avg, max) = (4.694, 4.758, 4.848), stdev = 0.080
  CI (99.9%): [3.293, 6.223] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.822 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 5.490 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.602 ±(99.9%) 0.021 ms/op
Iteration   1: 4.045 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  13.478 ms/op
                 createUser·p0.9999: 25.532 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   2: 4.201 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.550 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   8.481 ms/op
                 createUser·p0.999:  27.095 ms/op
                 createUser·p0.9999: 29.973 ms/op
                 createUser·p1.00:   30.605 ms/op

Iteration   3: 4.043 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.737 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.619 ms/op
                 createUser·p0.999:  29.416 ms/op
                 createUser·p0.9999: 32.408 ms/op
                 createUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234469
  mean =      4.095 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 329 
    [ 2.500,  5.000) = 221807 
    [ 5.000,  7.500) = 9952 
    [ 7.500, 10.000) = 1419 
    [10.000, 12.500) = 460 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 72 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     24.790 ms/op
     p(99.9900) =     31.738 ms/op
     p(99.9990) =     32.580 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.697 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.506 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.012 ms/op
Iteration   1: 4.088 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   7.487 ms/op
                 existUser·p0.999:  13.042 ms/op
                 existUser·p0.9999: 25.598 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.906 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.921 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  24.218 ms/op
                 existUser·p0.9999: 26.863 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   3: 4.008 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.890 ms/op
                 existUser·p0.50:   3.920 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  11.647 ms/op
                 existUser·p0.9999: 33.817 ms/op
                 existUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239836
  mean =      3.999 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 225 
    [ 2.500,  5.000) = 226333 
    [ 5.000,  7.500) = 11449 
    [ 7.500, 10.000) = 1232 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      7.173 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     32.738 ms/op
     p(99.9990) =     34.276 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.990 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.682 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.013 ms/op
Iteration   1: 4.118 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.692 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   9.191 ms/op
                 getUser·p0.999:  23.462 ms/op
                 getUser·p0.9999: 27.369 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   2: 4.001 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.993 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  10.814 ms/op
                 getUser·p0.9999: 27.001 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   3: 4.150 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.030 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 30.451 ms/op
                 getUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234796
  mean =      4.088 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 219931 
    [ 5.000,  7.500) = 11545 
    [ 7.500, 10.000) = 2499 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 119 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.692 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     17.175 ms/op
     p(99.9900) =     29.297 ms/op
     p(99.9990) =     31.148 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 14.331 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.337 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.858 ±(99.9%) 0.018 ms/op
Iteration   1: 4.661 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.531 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  26.804 ms/op
                 listUser·p0.9999: 28.943 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   2: 4.582 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 23.629 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   3: 4.722 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.839 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  16.043 ms/op
                 listUser·p0.9999: 17.964 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206206
  mean =      4.654 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 183829 
    [ 5.000,  7.500) = 18602 
    [ 7.500, 10.000) = 2705 
    [10.000, 12.500) = 568 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     19.915 ms/op
     p(99.9900) =     28.230 ms/op
     p(99.9990) =     29.293 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.797 ± 6.908  ops/ms
ClientPb.existUser                       thrpt       3   8.183 ± 3.321  ops/ms
ClientPb.getUser                         thrpt       3   8.051 ± 1.923  ops/ms
ClientPb.listUser                        thrpt       3   6.893 ± 2.219  ops/ms
ClientPb.createUser                       avgt       3   4.013 ± 1.407   ms/op
ClientPb.existUser                        avgt       3   3.803 ± 0.509   ms/op
ClientPb.getUser                          avgt       3   4.027 ± 2.610   ms/op
ClientPb.listUser                         avgt       3   4.758 ± 1.465   ms/op
ClientPb.createUser                     sample  234469   4.095 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.444           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.038           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.537           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.790           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.738           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.128           ms/op
ClientPb.existUser                      sample  239836   3.999 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.532           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.095           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.173           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.074           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.738           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.406           ms/op
ClientPb.getUser                        sample  234796   4.088 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.692           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.971           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.175           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.297           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.261           ms/op
ClientPb.listUser                       sample  206206   4.654 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.401           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.915           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.230           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.524           ms/op
