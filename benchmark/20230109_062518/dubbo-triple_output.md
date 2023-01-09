# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.857 ops/ms
# Warmup Iteration   2: 6.832 ops/ms
# Warmup Iteration   3: 9.064 ops/ms
Iteration   1: 9.911 ops/ms
Iteration   2: 9.928 ops/ms
Iteration   3: 10.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.972 ±(99.9%) 1.676 ops/ms [Average]
  (min, avg, max) = (9.911, 9.972, 10.078), stdev = 0.092
  CI (99.9%): [8.297, 11.648] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ops/ms
# Warmup Iteration   2: 9.506 ops/ms
# Warmup Iteration   3: 10.109 ops/ms
Iteration   1: 10.034 ops/ms
Iteration   2: 10.582 ops/ms
Iteration   3: 10.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.257 ±(99.9%) 5.249 ops/ms [Average]
  (min, avg, max) = (10.034, 10.257, 10.582), stdev = 0.288
  CI (99.9%): [5.009, 15.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ops/ms
# Warmup Iteration   2: 9.185 ops/ms
# Warmup Iteration   3: 9.816 ops/ms
Iteration   1: 10.308 ops/ms
Iteration   2: 10.320 ops/ms
Iteration   3: 9.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.169 ±(99.9%) 4.599 ops/ms [Average]
  (min, avg, max) = (9.878, 10.169, 10.320), stdev = 0.252
  CI (99.9%): [5.569, 14.768] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.358 ops/ms
# Warmup Iteration   2: 7.785 ops/ms
# Warmup Iteration   3: 8.330 ops/ms
Iteration   1: 8.674 ops/ms
Iteration   2: 8.768 ops/ms
Iteration   3: 8.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.619 ±(99.9%) 3.324 ops/ms [Average]
  (min, avg, max) = (8.416, 8.619, 8.768), stdev = 0.182
  CI (99.9%): [5.296, 11.943] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.403 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.005 ms/op
Iteration   1: 3.222 ±(99.9%) 0.004 ms/op
Iteration   2: 3.048 ±(99.9%) 0.007 ms/op
Iteration   3: 3.101 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.123 ±(99.9%) 1.626 ms/op [Average]
  (min, avg, max) = (3.048, 3.123, 3.222), stdev = 0.089
  CI (99.9%): [1.497, 4.750] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.116 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.005 ms/op
Iteration   1: 2.987 ±(99.9%) 0.002 ms/op
Iteration   2: 3.100 ±(99.9%) 0.003 ms/op
Iteration   3: 3.038 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.042 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (2.987, 3.042, 3.100), stdev = 0.057
  CI (99.9%): [2.003, 4.081] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.192 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.005 ms/op
Iteration   1: 3.595 ±(99.9%) 0.007 ms/op
Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
Iteration   3: 3.232 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.320 ±(99.9%) 4.447 ms/op [Average]
  (min, avg, max) = (3.131, 3.320, 3.595), stdev = 0.244
  CI (99.9%): [≈ 0, 7.767] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.097 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.009 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.008 ms/op
Iteration   1: 3.628 ±(99.9%) 0.011 ms/op
Iteration   2: 3.888 ±(99.9%) 0.007 ms/op
Iteration   3: 3.693 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.736 ±(99.9%) 2.475 ms/op [Average]
  (min, avg, max) = (3.628, 3.736, 3.888), stdev = 0.136
  CI (99.9%): [1.261, 6.211] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.096 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.009 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  14.079 ms/op
                 createUser·p0.9999: 19.942 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   2: 3.086 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  18.470 ms/op
                 createUser·p0.9999: 21.353 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   3: 3.387 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.794 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  14.598 ms/op
                 createUser·p0.9999: 18.106 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298868
  mean =      3.210 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25328 
    [ 2.500,  5.000) = 267265 
    [ 5.000,  7.500) = 5402 
    [ 7.500, 10.000) = 282 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     22.906 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.693 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 3.163 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  9.110 ms/op
                 existUser·p0.9999: 26.960 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   2: 3.078 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  14.500 ms/op
                 existUser·p0.9999: 22.433 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  14.254 ms/op
                 existUser·p0.9999: 19.120 ms/op
                 existUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310069
  mean =      3.095 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26394 
    [ 2.500,  5.000) = 276618 
    [ 5.000,  7.500) = 6331 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     27.653 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.964 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.011 ms/op
Iteration   1: 3.307 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.902 ms/op
                 getUser·p0.999:  14.248 ms/op
                 getUser·p0.9999: 24.226 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   2: 3.258 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  14.339 ms/op
                 getUser·p0.9999: 22.872 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   3: 3.318 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  14.868 ms/op
                 getUser·p0.9999: 22.491 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291145
  mean =      3.294 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19300 
    [ 2.500,  5.000) = 261707 
    [ 5.000,  7.500) = 9095 
    [ 7.500, 10.000) = 585 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     14.249 ms/op
     p(99.9900) =     23.545 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.785 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.726 ±(99.9%) 0.012 ms/op
Iteration   1: 3.724 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.023 ms/op
                 listUser·p0.999:  15.435 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   2: 3.695 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  13.754 ms/op
                 listUser·p0.9999: 16.062 ms/op
                 listUser·p1.00:   16.105 ms/op

Iteration   3: 3.646 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.071 ms/op
                 listUser·p0.99:   6.349 ms/op
                 listUser·p0.999:  12.403 ms/op
                 listUser·p0.9999: 14.008 ms/op
                 listUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260129
  mean =      3.688 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 32 
    [ 2.500,  3.750) = 210735 
    [ 3.750,  5.000) = 42960 
    [ 5.000,  6.250) = 2617 
    [ 6.250,  7.500) = 2140 
    [ 7.500,  8.750) = 670 
    [ 8.750, 10.000) = 318 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 145 
    [12.500, 13.750) = 149 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 114 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     17.137 ms/op
     p(99.9990) =     17.950 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.972 ± 1.676  ops/ms
ClientPb.existUser                       thrpt       3  10.257 ± 5.249  ops/ms
ClientPb.getUser                         thrpt       3  10.169 ± 4.599  ops/ms
ClientPb.listUser                        thrpt       3   8.619 ± 3.324  ops/ms
ClientPb.createUser                       avgt       3   3.123 ± 1.626   ms/op
ClientPb.existUser                        avgt       3   3.042 ± 1.039   ms/op
ClientPb.getUser                          avgt       3   3.320 ± 4.447   ms/op
ClientPb.listUser                         avgt       3   3.736 ± 2.475   ms/op
ClientPb.createUser                     sample  298868   3.210 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.588           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.204           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.972           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.003           ms/op
ClientPb.existUser                      sample  310069   3.095 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.954           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.156           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.264           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.722           ms/op
ClientPb.getUser                        sample  291145   3.294 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.027           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.514           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.119           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.249           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.545           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.904           ms/op
ClientPb.listUser                       sample  260129   3.688 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.696           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.500           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.137           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.383           ms/op
