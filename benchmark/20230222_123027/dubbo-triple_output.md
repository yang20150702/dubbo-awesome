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
# Warmup Iteration   1: 2.320 ops/ms
# Warmup Iteration   2: 5.967 ops/ms
# Warmup Iteration   3: 9.093 ops/ms
Iteration   1: 9.781 ops/ms
Iteration   2: 9.998 ops/ms
Iteration   3: 9.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.777 ±(99.9%) 4.055 ops/ms [Average]
  (min, avg, max) = (9.553, 9.777, 9.998), stdev = 0.222
  CI (99.9%): [5.722, 13.833] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.941 ops/ms
# Warmup Iteration   2: 9.653 ops/ms
# Warmup Iteration   3: 10.264 ops/ms
Iteration   1: 9.909 ops/ms
Iteration   2: 10.104 ops/ms
Iteration   3: 10.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.089 ±(99.9%) 3.147 ops/ms [Average]
  (min, avg, max) = (9.909, 10.089, 10.253), stdev = 0.172
  CI (99.9%): [6.942, 13.236] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.509 ops/ms
# Warmup Iteration   2: 9.021 ops/ms
# Warmup Iteration   3: 10.211 ops/ms
Iteration   1: 9.810 ops/ms
Iteration   2: 10.013 ops/ms
Iteration   3: 9.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.930 ±(99.9%) 1.933 ops/ms [Average]
  (min, avg, max) = (9.810, 9.930, 10.013), stdev = 0.106
  CI (99.9%): [7.997, 11.862] (assumes normal distribution)


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
# Warmup Iteration   1: 3.515 ops/ms
# Warmup Iteration   2: 7.706 ops/ms
# Warmup Iteration   3: 8.544 ops/ms
Iteration   1: 8.638 ops/ms
Iteration   2: 8.708 ops/ms
Iteration   3: 8.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.696 ±(99.9%) 0.976 ops/ms [Average]
  (min, avg, max) = (8.638, 8.696, 8.742), stdev = 0.053
  CI (99.9%): [7.720, 9.672] (assumes normal distribution)


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
# Warmup Iteration   1: 9.169 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.007 ms/op
Iteration   1: 3.267 ±(99.9%) 0.009 ms/op
Iteration   2: 3.111 ±(99.9%) 0.005 ms/op
Iteration   3: 3.142 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.173 ±(99.9%) 1.507 ms/op [Average]
  (min, avg, max) = (3.111, 3.173, 3.267), stdev = 0.083
  CI (99.9%): [1.666, 4.681] (assumes normal distribution)


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
# Warmup Iteration   1: 7.462 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.005 ms/op
Iteration   1: 3.050 ±(99.9%) 0.011 ms/op
Iteration   2: 2.977 ±(99.9%) 0.003 ms/op
Iteration   3: 3.011 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.013 ±(99.9%) 0.664 ms/op [Average]
  (min, avg, max) = (2.977, 3.013, 3.050), stdev = 0.036
  CI (99.9%): [2.349, 3.676] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.202 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.003 ms/op
Iteration   1: 3.146 ±(99.9%) 0.005 ms/op
Iteration   2: 3.310 ±(99.9%) 0.007 ms/op
Iteration   3: 3.279 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.245 ±(99.9%) 1.582 ms/op [Average]
  (min, avg, max) = (3.146, 3.245, 3.310), stdev = 0.087
  CI (99.9%): [1.663, 4.827] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.233 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.005 ms/op
Iteration   1: 3.693 ±(99.9%) 0.006 ms/op
Iteration   2: 3.723 ±(99.9%) 0.007 ms/op
Iteration   3: 3.739 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.719 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.693, 3.719, 3.739), stdev = 0.023
  CI (99.9%): [3.295, 4.142] (assumes normal distribution)


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
# Warmup Iteration   1: 8.233 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.009 ms/op
Iteration   1: 3.312 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  13.691 ms/op
                 createUser·p0.9999: 21.442 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   2: 3.306 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  20.251 ms/op
                 createUser·p0.9999: 35.385 ms/op
                 createUser·p1.00:   36.635 ms/op

Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.481 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  15.142 ms/op
                 createUser·p0.9999: 20.030 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295825
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18058 
    [ 2.500,  5.000) = 272625 
    [ 5.000,  7.500) = 4254 
    [ 7.500, 10.000) = 445 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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
# Warmup Iteration   1: 7.030 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.008 ms/op
Iteration   1: 3.072 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  8.846 ms/op
                 existUser·p0.9999: 20.052 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   2: 3.091 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  12.183 ms/op
                 existUser·p0.9999: 23.940 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.363 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  14.954 ms/op
                 existUser·p0.9999: 23.284 ms/op
                 existUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311897
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19693 
    [ 2.500,  5.000) = 287447 
    [ 5.000,  7.500) = 4143 
    [ 7.500, 10.000) = 252 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     13.813 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     24.441 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 7.773 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
Iteration   1: 3.251 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.295 ms/op
                 getUser·p0.999:  18.678 ms/op
                 getUser·p0.9999: 25.035 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   2: 3.145 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  10.584 ms/op
                 getUser·p0.9999: 27.656 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 3.272 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.331 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  17.385 ms/op
                 getUser·p0.9999: 21.430 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297754
  mean =      3.222 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14958 
    [ 2.500,  5.000) = 272801 
    [ 5.000,  7.500) = 8764 
    [ 7.500, 10.000) = 613 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      0.331 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     17.768 ms/op
     p(99.9900) =     26.979 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 8.622 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.011 ms/op
Iteration   1: 3.884 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  14.545 ms/op
                 listUser·p0.9999: 23.031 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   2: 3.609 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   3.498 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.096 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  14.537 ms/op
                 listUser·p0.9999: 20.288 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 3.759 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  12.517 ms/op
                 listUser·p0.9999: 13.861 ms/op
                 listUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256030
  mean =      3.747 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 247967 
    [ 5.000,  7.500) = 5694 
    [ 7.500, 10.000) = 1559 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     20.591 ms/op
     p(99.9990) =     23.917 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.777 ± 4.055  ops/ms
ClientPb.existUser                       thrpt       3  10.089 ± 3.147  ops/ms
ClientPb.getUser                         thrpt       3   9.930 ± 1.933  ops/ms
ClientPb.listUser                        thrpt       3   8.696 ± 0.976  ops/ms
ClientPb.createUser                       avgt       3   3.173 ± 1.507   ms/op
ClientPb.existUser                        avgt       3   3.013 ± 0.664   ms/op
ClientPb.getUser                          avgt       3   3.245 ± 1.582   ms/op
ClientPb.listUser                         avgt       3   3.719 ± 0.423   ms/op
ClientPb.createUser                     sample  295825   3.245 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.944           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.531           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.341           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.635           ms/op
ClientPb.existUser                      sample  311897   3.076 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.813           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.298           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.510           ms/op
ClientPb.getUser                        sample  297754   3.222 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.331           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.666           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.119           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.768           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.979           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.098           ms/op
ClientPb.listUser                       sample  256030   3.747 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.229           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.609           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.315           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.943           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.591           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.248           ms/op
