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
# Warmup Iteration   1: 0.954 ops/ms
# Warmup Iteration   2: 1.966 ops/ms
# Warmup Iteration   3: 4.369 ops/ms
Iteration   1: 5.100 ops/ms
Iteration   2: 5.177 ops/ms
Iteration   3: 5.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.288 ±(99.9%) 4.778 ops/ms [Average]
  (min, avg, max) = (5.100, 5.288, 5.587), stdev = 0.262
  CI (99.9%): [0.510, 10.066] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.328 ops/ms
# Warmup Iteration   2: 3.853 ops/ms
# Warmup Iteration   3: 5.391 ops/ms
Iteration   1: 5.695 ops/ms
Iteration   2: 5.790 ops/ms
Iteration   3: 5.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.777 ±(99.9%) 1.402 ops/ms [Average]
  (min, avg, max) = (5.695, 5.777, 5.847), stdev = 0.077
  CI (99.9%): [4.375, 7.180] (assumes normal distribution)


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
# Warmup Iteration   1: 1.424 ops/ms
# Warmup Iteration   2: 4.418 ops/ms
# Warmup Iteration   3: 5.395 ops/ms
Iteration   1: 5.404 ops/ms
Iteration   2: 5.484 ops/ms
Iteration   3: 5.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.456 ±(99.9%) 0.825 ops/ms [Average]
  (min, avg, max) = (5.404, 5.456, 5.484), stdev = 0.045
  CI (99.9%): [4.631, 6.281] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.432 ops/ms
# Warmup Iteration   2: 3.720 ops/ms
# Warmup Iteration   3: 4.456 ops/ms
Iteration   1: 4.507 ops/ms
Iteration   2: 4.767 ops/ms
Iteration   3: 4.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.661 ±(99.9%) 2.499 ops/ms [Average]
  (min, avg, max) = (4.507, 4.661, 4.767), stdev = 0.137
  CI (99.9%): [2.162, 7.161] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 19.430 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 7.794 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.853 ±(99.9%) 0.014 ms/op
Iteration   1: 6.107 ±(99.9%) 0.011 ms/op
Iteration   2: 5.723 ±(99.9%) 0.015 ms/op
Iteration   3: 5.845 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.891 ±(99.9%) 3.580 ms/op [Average]
  (min, avg, max) = (5.723, 5.891, 6.107), stdev = 0.196
  CI (99.9%): [2.311, 9.471] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 18.727 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 7.286 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.717 ±(99.9%) 0.008 ms/op
Iteration   1: 5.615 ±(99.9%) 0.009 ms/op
Iteration   2: 5.600 ±(99.9%) 0.007 ms/op
Iteration   3: 5.429 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.548 ±(99.9%) 1.883 ms/op [Average]
  (min, avg, max) = (5.429, 5.548, 5.615), stdev = 0.103
  CI (99.9%): [3.665, 7.431] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 19.854 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.853 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.647 ±(99.9%) 0.017 ms/op
Iteration   1: 5.858 ±(99.9%) 0.011 ms/op
Iteration   2: 5.821 ±(99.9%) 0.013 ms/op
Iteration   3: 6.024 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.901 ±(99.9%) 1.970 ms/op [Average]
  (min, avg, max) = (5.821, 5.901, 6.024), stdev = 0.108
  CI (99.9%): [3.931, 7.871] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 22.139 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 9.103 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 7.307 ±(99.9%) 0.015 ms/op
Iteration   1: 6.795 ±(99.9%) 0.013 ms/op
Iteration   2: 6.574 ±(99.9%) 0.015 ms/op
Iteration   3: 6.831 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.733 ±(99.9%) 2.539 ms/op [Average]
  (min, avg, max) = (6.574, 6.733, 6.831), stdev = 0.139
  CI (99.9%): [4.194, 9.272] (assumes normal distribution)


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
# Warmup Iteration   1: 18.839 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 7.574 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.137 ±(99.9%) 0.030 ms/op
Iteration   1: 5.748 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.597 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   7.127 ms/op
                 createUser·p0.95:   8.061 ms/op
                 createUser·p0.99:   11.420 ms/op
                 createUser·p0.999:  20.480 ms/op
                 createUser·p0.9999: 34.669 ms/op
                 createUser·p1.00:   34.996 ms/op

Iteration   2: 5.902 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.335 ms/op
                 createUser·p0.50:   5.423 ms/op
                 createUser·p0.90:   7.635 ms/op
                 createUser·p0.95:   8.864 ms/op
                 createUser·p0.99:   11.895 ms/op
                 createUser·p0.999:  28.253 ms/op
                 createUser·p0.9999: 33.279 ms/op
                 createUser·p1.00:   33.325 ms/op

Iteration   3: 6.136 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   5.800 ms/op
                 createUser·p0.90:   7.750 ms/op
                 createUser·p0.95:   8.831 ms/op
                 createUser·p0.99:   12.239 ms/op
                 createUser·p0.999:  30.334 ms/op
                 createUser·p0.9999: 34.444 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161996
  mean =      5.924 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 43266 
    [ 5.000,  7.500) = 102260 
    [ 7.500, 10.000) = 12693 
    [10.000, 12.500) = 2505 
    [12.500, 15.000) = 747 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 77 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.722 ms/op
     p(50.0000) =      5.521 ms/op
     p(90.0000) =      7.520 ms/op
     p(95.0000) =      8.618 ms/op
     p(99.0000) =     11.895 ms/op
     p(99.9000) =     24.581 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     34.915 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 18.570 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 7.000 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.601 ±(99.9%) 0.020 ms/op
Iteration   1: 5.784 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   5.390 ms/op
                 existUser·p0.90:   7.496 ms/op
                 existUser·p0.95:   8.864 ms/op
                 existUser·p0.99:   11.889 ms/op
                 existUser·p0.999:  19.348 ms/op
                 existUser·p0.9999: 30.802 ms/op
                 existUser·p1.00:   31.392 ms/op

Iteration   2: 5.393 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.236 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.586 ms/op
                 existUser·p0.95:   7.640 ms/op
                 existUser·p0.99:   10.387 ms/op
                 existUser·p0.999:  29.318 ms/op
                 existUser·p0.9999: 32.410 ms/op
                 existUser·p1.00:   33.161 ms/op

Iteration   3: 5.440 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.454 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   6.644 ms/op
                 existUser·p0.95:   7.438 ms/op
                 existUser·p0.99:   10.371 ms/op
                 existUser·p0.999:  30.507 ms/op
                 existUser·p0.9999: 37.028 ms/op
                 existUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 173379
  mean =      5.534 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 69634 
    [ 5.000,  7.500) = 92275 
    [ 7.500, 10.000) = 8766 
    [10.000, 12.500) = 1719 
    [12.500, 15.000) = 566 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.881 ms/op
     p(95.0000) =      8.045 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     35.214 ms/op
     p(99.9990) =     37.259 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 18.072 ±(99.9%) 0.327 ms/op
# Warmup Iteration   2: 7.102 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.816 ±(99.9%) 0.020 ms/op
Iteration   1: 6.046 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.699 ms/op
                 getUser·p0.50:   5.603 ms/op
                 getUser·p0.90:   7.676 ms/op
                 getUser·p0.95:   9.401 ms/op
                 getUser·p0.99:   13.418 ms/op
                 getUser·p0.999:  26.255 ms/op
                 getUser·p0.9999: 31.592 ms/op
                 getUser·p1.00:   32.932 ms/op

Iteration   2: 6.097 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.879 ms/op
                 getUser·p0.50:   5.603 ms/op
                 getUser·p0.90:   8.159 ms/op
                 getUser·p0.95:   9.699 ms/op
                 getUser·p0.99:   12.517 ms/op
                 getUser·p0.999:  24.627 ms/op
                 getUser·p0.9999: 27.984 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 5.639 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.777 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   6.898 ms/op
                 getUser·p0.95:   7.750 ms/op
                 getUser·p0.99:   10.453 ms/op
                 getUser·p0.999:  34.165 ms/op
                 getUser·p0.9999: 36.984 ms/op
                 getUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 161997
  mean =      5.920 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 38067 
    [ 5.000,  7.500) = 108141 
    [ 7.500, 10.000) = 10720 
    [10.000, 12.500) = 3596 
    [12.500, 15.000) = 857 
    [15.000, 17.500) = 295 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      2.699 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      7.455 ms/op
     p(95.0000) =      9.060 ms/op
     p(99.0000) =     12.272 ms/op
     p(99.9000) =     25.625 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     37.577 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 23.001 ±(99.9%) 0.400 ms/op
# Warmup Iteration   2: 10.425 ±(99.9%) 0.093 ms/op
# Warmup Iteration   3: 7.247 ±(99.9%) 0.036 ms/op
Iteration   1: 6.833 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.502 ms/op
                 listUser·p0.50:   6.455 ms/op
                 listUser·p0.90:   8.307 ms/op
                 listUser·p0.95:   9.650 ms/op
                 listUser·p0.99:   12.537 ms/op
                 listUser·p0.999:  27.598 ms/op
                 listUser·p0.9999: 30.441 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   2: 6.909 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.170 ms/op
                 listUser·p0.50:   6.521 ms/op
                 listUser·p0.90:   8.339 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   13.074 ms/op
                 listUser·p0.999:  33.356 ms/op
                 listUser·p0.9999: 40.763 ms/op
                 listUser·p1.00:   41.484 ms/op

Iteration   3: 6.683 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   7.954 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   13.074 ms/op
                 listUser·p0.999:  31.626 ms/op
                 listUser·p0.9999: 37.697 ms/op
                 listUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140875
  mean =      6.807 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2131 
    [ 5.000, 10.000) = 133093 
    [10.000, 15.000) = 4943 
    [15.000, 20.000) = 363 
    [20.000, 25.000) = 86 
    [25.000, 30.000) = 99 
    [30.000, 35.000) = 116 
    [35.000, 40.000) = 39 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      6.398 ms/op
     p(90.0000) =      8.233 ms/op
     p(95.0000) =      9.503 ms/op
     p(99.0000) =     12.911 ms/op
     p(99.9000) =     30.441 ms/op
     p(99.9900) =     37.338 ms/op
     p(99.9990) =     41.457 ms/op
     p(99.9999) =     41.484 ms/op
    p(100.0000) =     41.484 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.288 ± 4.778  ops/ms
ClientPb.existUser                       thrpt       3   5.777 ± 1.402  ops/ms
ClientPb.getUser                         thrpt       3   5.456 ± 0.825  ops/ms
ClientPb.listUser                        thrpt       3   4.661 ± 2.499  ops/ms
ClientPb.createUser                       avgt       3   5.891 ± 3.580   ms/op
ClientPb.existUser                        avgt       3   5.548 ± 1.883   ms/op
ClientPb.getUser                          avgt       3   5.901 ± 1.970   ms/op
ClientPb.listUser                         avgt       3   6.733 ± 2.539   ms/op
ClientPb.createUser                     sample  161996   5.924 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.722           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.520           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.618           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.895           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.581           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.472           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.996           ms/op
ClientPb.existUser                      sample  173379   5.534 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.836           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.169           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.881           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.045           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.059           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.560           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.214           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.356           ms/op
ClientPb.getUser                        sample  161997   5.920 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.699           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.497           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.455           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.060           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.272           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.625           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.914           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.618           ms/op
ClientPb.listUser                       sample  140875   6.807 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.236           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.398           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.233           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.503           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.911           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.441           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.338           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.484           ms/op
