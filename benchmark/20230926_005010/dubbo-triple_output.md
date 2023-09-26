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
# Warmup Iteration   1: 1.644 ops/ms
# Warmup Iteration   2: 3.755 ops/ms
# Warmup Iteration   3: 7.035 ops/ms
Iteration   1: 7.277 ops/ms
Iteration   2: 7.960 ops/ms
Iteration   3: 8.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.800 ±(99.9%) 8.473 ops/ms [Average]
  (min, avg, max) = (7.277, 7.800, 8.163), stdev = 0.464
  CI (99.9%): [≈ 0, 16.273] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.300 ops/ms
# Warmup Iteration   2: 7.233 ops/ms
# Warmup Iteration   3: 8.001 ops/ms
Iteration   1: 8.564 ops/ms
Iteration   2: 8.394 ops/ms
Iteration   3: 8.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.511 ±(99.9%) 1.852 ops/ms [Average]
  (min, avg, max) = (8.394, 8.511, 8.576), stdev = 0.102
  CI (99.9%): [6.659, 10.363] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.514 ops/ms
# Warmup Iteration   2: 7.123 ops/ms
# Warmup Iteration   3: 7.764 ops/ms
Iteration   1: 8.294 ops/ms
Iteration   2: 8.022 ops/ms
Iteration   3: 8.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.176 ±(99.9%) 2.546 ops/ms [Average]
  (min, avg, max) = (8.022, 8.176, 8.294), stdev = 0.140
  CI (99.9%): [5.630, 10.723] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.278 ops/ms
# Warmup Iteration   2: 5.832 ops/ms
# Warmup Iteration   3: 6.618 ops/ms
Iteration   1: 6.684 ops/ms
Iteration   2: 6.802 ops/ms
Iteration   3: 6.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.723 ±(99.9%) 1.243 ops/ms [Average]
  (min, avg, max) = (6.684, 6.723, 6.802), stdev = 0.068
  CI (99.9%): [5.480, 7.967] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.238 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.005 ms/op
Iteration   1: 4.150 ±(99.9%) 0.006 ms/op
Iteration   2: 4.051 ±(99.9%) 0.005 ms/op
Iteration   3: 3.903 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.035 ±(99.9%) 2.266 ms/op [Average]
  (min, avg, max) = (3.903, 4.035, 4.150), stdev = 0.124
  CI (99.9%): [1.769, 6.300] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.938 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.003 ms/op
Iteration   1: 3.867 ±(99.9%) 0.003 ms/op
Iteration   2: 3.885 ±(99.9%) 0.004 ms/op
Iteration   3: 3.900 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.884 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (3.867, 3.884, 3.900), stdev = 0.017
  CI (99.9%): [3.578, 4.190] (assumes normal distribution)


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
# Warmup Iteration   1: 13.145 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.003 ms/op
Iteration   1: 4.155 ±(99.9%) 0.005 ms/op
Iteration   2: 3.964 ±(99.9%) 0.004 ms/op
Iteration   3: 3.972 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.030 ±(99.9%) 1.977 ms/op [Average]
  (min, avg, max) = (3.964, 4.030, 4.155), stdev = 0.108
  CI (99.9%): [2.053, 6.008] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.440 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.755 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.018 ±(99.9%) 0.006 ms/op
Iteration   1: 4.676 ±(99.9%) 0.008 ms/op
Iteration   2: 4.756 ±(99.9%) 0.010 ms/op
Iteration   3: 4.756 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.729 ±(99.9%) 0.837 ms/op [Average]
  (min, avg, max) = (4.676, 4.729, 4.756), stdev = 0.046
  CI (99.9%): [3.892, 5.567] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.088 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.709 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.017 ms/op
Iteration   1: 3.969 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.864 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   7.222 ms/op
                 createUser·p0.999:  23.373 ms/op
                 createUser·p0.9999: 29.031 ms/op
                 createUser·p1.00:   29.655 ms/op

Iteration   2: 4.043 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.554 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   7.873 ms/op
                 createUser·p0.999:  25.348 ms/op
                 createUser·p0.9999: 27.729 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 4.016 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.062 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   7.127 ms/op
                 createUser·p0.999:  12.239 ms/op
                 createUser·p0.9999: 34.146 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239460
  mean =      4.009 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 281 
    [ 2.500,  5.000) = 226194 
    [ 5.000,  7.500) = 10778 
    [ 7.500, 10.000) = 1481 
    [10.000, 12.500) = 355 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.554 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     23.429 ms/op
     p(99.9900) =     31.694 ms/op
     p(99.9990) =     34.551 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.557 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.012 ms/op
Iteration   1: 4.016 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   7.509 ms/op
                 existUser·p0.999:  16.302 ms/op
                 existUser·p0.9999: 25.821 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   2: 3.894 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.612 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   7.903 ms/op
                 existUser·p0.999:  15.317 ms/op
                 existUser·p0.9999: 25.545 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   3: 3.948 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   7.971 ms/op
                 existUser·p0.999:  14.254 ms/op
                 existUser·p0.9999: 31.621 ms/op
                 existUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242758
  mean =      3.952 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 502 
    [ 2.500,  5.000) = 228154 
    [ 5.000,  7.500) = 11358 
    [ 7.500, 10.000) = 1811 
    [10.000, 12.500) = 519 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     15.274 ms/op
     p(99.9900) =     30.573 ms/op
     p(99.9990) =     32.150 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 13.530 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.442 ±(99.9%) 0.017 ms/op
Iteration   1: 4.051 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.599 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  21.137 ms/op
                 getUser·p0.9999: 24.419 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   2: 4.103 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  11.147 ms/op
                 getUser·p0.9999: 24.779 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   3: 4.156 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   6.046 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  24.425 ms/op
                 getUser·p0.9999: 27.034 ms/op
                 getUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233833
  mean =      4.103 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 219415 
    [ 5.000,  7.500) = 11672 
    [ 7.500, 10.000) = 1884 
    [10.000, 12.500) = 371 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     21.376 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     27.645 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 12.946 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.870 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.993 ±(99.9%) 0.016 ms/op
Iteration   1: 4.705 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  20.808 ms/op
                 listUser·p0.9999: 22.348 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 4.728 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  18.067 ms/op
                 listUser·p0.9999: 21.349 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   3: 4.840 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  18.085 ms/op
                 listUser·p0.9999: 21.071 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201750
  mean =      4.757 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 161932 
    [ 5.000,  7.500) = 35535 
    [ 7.500, 10.000) = 2985 
    [10.000, 12.500) = 668 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 183 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     22.211 ms/op
     p(99.9990) =     23.722 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.800 ± 8.473  ops/ms
ClientPb.existUser                       thrpt       3   8.511 ± 1.852  ops/ms
ClientPb.getUser                         thrpt       3   8.176 ± 2.546  ops/ms
ClientPb.listUser                        thrpt       3   6.723 ± 1.243  ops/ms
ClientPb.createUser                       avgt       3   4.035 ± 2.266   ms/op
ClientPb.existUser                        avgt       3   3.884 ± 0.306   ms/op
ClientPb.getUser                          avgt       3   4.030 ± 1.977   ms/op
ClientPb.listUser                         avgt       3   4.729 ± 0.837   ms/op
ClientPb.createUser                     sample  239460   4.009 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.554           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.381           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.429           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.694           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734           ms/op
ClientPb.existUser                      sample  242758   3.952 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.243           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.750           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.274           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.573           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.062           ms/op
ClientPb.getUser                        sample  233833   4.103 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.231           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.686           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.684           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.376           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.444           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.967           ms/op
ClientPb.listUser                       sample  201750   4.757 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.415           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.913           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.333           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.211           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.052           ms/op
