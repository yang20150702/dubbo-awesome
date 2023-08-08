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
# Warmup Iteration   1: 2.034 ops/ms
# Warmup Iteration   2: 5.451 ops/ms
# Warmup Iteration   3: 8.503 ops/ms
Iteration   1: 9.100 ops/ms
Iteration   2: 8.822 ops/ms
Iteration   3: 8.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.957 ±(99.9%) 2.537 ops/ms [Average]
  (min, avg, max) = (8.822, 8.957, 9.100), stdev = 0.139
  CI (99.9%): [6.420, 11.494] (assumes normal distribution)


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
# Warmup Iteration   1: 2.887 ops/ms
# Warmup Iteration   2: 8.685 ops/ms
# Warmup Iteration   3: 9.563 ops/ms
Iteration   1: 9.477 ops/ms
Iteration   2: 9.835 ops/ms
Iteration   3: 9.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.685 ±(99.9%) 3.395 ops/ms [Average]
  (min, avg, max) = (9.477, 9.685, 9.835), stdev = 0.186
  CI (99.9%): [6.290, 13.081] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.015 ops/ms
# Warmup Iteration   2: 8.070 ops/ms
# Warmup Iteration   3: 8.799 ops/ms
Iteration   1: 9.113 ops/ms
Iteration   2: 9.349 ops/ms
Iteration   3: 9.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.266 ±(99.9%) 2.412 ops/ms [Average]
  (min, avg, max) = (9.113, 9.266, 9.349), stdev = 0.132
  CI (99.9%): [6.853, 11.678] (assumes normal distribution)


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
# Warmup Iteration   1: 2.702 ops/ms
# Warmup Iteration   2: 7.268 ops/ms
# Warmup Iteration   3: 7.851 ops/ms
Iteration   1: 7.715 ops/ms
Iteration   2: 8.083 ops/ms
Iteration   3: 8.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.003 ±(99.9%) 4.692 ops/ms [Average]
  (min, avg, max) = (7.715, 8.003, 8.211), stdev = 0.257
  CI (99.9%): [3.311, 12.695] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.266 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.007 ms/op
Iteration   1: 3.545 ±(99.9%) 0.008 ms/op
Iteration   2: 3.479 ±(99.9%) 0.003 ms/op
Iteration   3: 3.424 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.483 ±(99.9%) 1.102 ms/op [Average]
  (min, avg, max) = (3.424, 3.483, 3.545), stdev = 0.060
  CI (99.9%): [2.381, 4.585] (assumes normal distribution)


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
# Warmup Iteration   1: 8.260 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.008 ms/op
Iteration   1: 3.371 ±(99.9%) 0.003 ms/op
Iteration   2: 3.374 ±(99.9%) 0.004 ms/op
Iteration   3: 3.363 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.369 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (3.363, 3.369, 3.374), stdev = 0.005
  CI (99.9%): [3.270, 3.468] (assumes normal distribution)


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
# Warmup Iteration   1: 10.162 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.672 ±(99.9%) 0.007 ms/op
Iteration   1: 3.355 ±(99.9%) 0.010 ms/op
Iteration   2: 3.478 ±(99.9%) 0.009 ms/op
Iteration   3: 3.457 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.430 ±(99.9%) 1.198 ms/op [Average]
  (min, avg, max) = (3.355, 3.430, 3.478), stdev = 0.066
  CI (99.9%): [2.232, 4.628] (assumes normal distribution)


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
# Warmup Iteration   1: 11.598 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.188 ±(99.9%) 0.011 ms/op
Iteration   1: 4.169 ±(99.9%) 0.007 ms/op
Iteration   2: 4.044 ±(99.9%) 0.008 ms/op
Iteration   3: 3.863 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.026 ±(99.9%) 2.802 ms/op [Average]
  (min, avg, max) = (3.863, 4.026, 4.169), stdev = 0.154
  CI (99.9%): [1.223, 6.828] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.820 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.983 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.011 ms/op
Iteration   1: 3.369 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.628 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  20.397 ms/op
                 createUser·p0.9999: 25.871 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   2: 3.453 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.184 ms/op
                 createUser·p0.999:  21.404 ms/op
                 createUser·p0.9999: 24.319 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   3: 3.493 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  12.217 ms/op
                 createUser·p0.9999: 27.984 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279315
  mean =      3.437 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5597 
    [ 2.500,  5.000) = 267361 
    [ 5.000,  7.500) = 5143 
    [ 7.500, 10.000) = 715 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     26.411 ms/op
     p(99.9990) =     28.989 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.861 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.009 ms/op
Iteration   1: 3.301 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  11.684 ms/op
                 existUser·p0.9999: 22.391 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 3.329 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.800 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  20.025 ms/op
                 existUser·p0.9999: 24.351 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   3: 3.287 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.778 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  10.240 ms/op
                 existUser·p0.9999: 24.379 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290381
  mean =      3.306 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19511 
    [ 2.500,  5.000) = 264913 
    [ 5.000,  7.500) = 4647 
    [ 7.500, 10.000) = 918 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     11.282 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.795 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.098 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.010 ms/op
Iteration   1: 3.655 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   8.127 ms/op
                 getUser·p0.999:  20.300 ms/op
                 getUser·p0.9999: 24.961 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 3.502 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  21.618 ms/op
                 getUser·p0.9999: 25.428 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.531 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.363 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  18.805 ms/op
                 getUser·p0.9999: 26.702 ms/op
                 getUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269337
  mean =      3.561 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6478 
    [ 2.500,  5.000) = 250336 
    [ 5.000,  7.500) = 9919 
    [ 7.500, 10.000) = 1950 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     20.076 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     27.502 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.802 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.433 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.012 ms/op
Iteration   1: 4.075 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 20.954 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 3.998 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   3: 4.026 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 20.757 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237962
  mean =      4.033 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 228608 
    [ 5.000,  7.500) = 5956 
    [ 7.500, 10.000) = 2266 
    [10.000, 12.500) = 573 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      8.282 ms/op
     p(99.9000) =     16.237 ms/op
     p(99.9900) =     20.716 ms/op
     p(99.9990) =     23.044 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.957 ± 2.537  ops/ms
ClientPb.existUser                       thrpt       3   9.685 ± 3.395  ops/ms
ClientPb.getUser                         thrpt       3   9.266 ± 2.412  ops/ms
ClientPb.listUser                        thrpt       3   8.003 ± 4.692  ops/ms
ClientPb.createUser                       avgt       3   3.483 ± 1.102   ms/op
ClientPb.existUser                        avgt       3   3.369 ± 0.099   ms/op
ClientPb.getUser                          avgt       3   3.430 ± 1.198   ms/op
ClientPb.listUser                         avgt       3   4.026 ± 2.802   ms/op
ClientPb.createUser                     sample  279315   3.437 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.933           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.972           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.779           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.411           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.491           ms/op
ClientPb.existUser                      sample  290381   3.306 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.548           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.282           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.150           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.919           ms/op
ClientPb.getUser                        sample  269337   3.561 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.303           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.076           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.592           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.591           ms/op
ClientPb.listUser                       sample  237962   4.033 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.409           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.282           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.237           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.716           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.495           ms/op
