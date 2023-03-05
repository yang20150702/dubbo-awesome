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
# Warmup Iteration   1: 2.729 ops/ms
# Warmup Iteration   2: 6.838 ops/ms
# Warmup Iteration   3: 9.392 ops/ms
Iteration   1: 9.677 ops/ms
Iteration   2: 9.721 ops/ms
Iteration   3: 9.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.747 ±(99.9%) 1.566 ops/ms [Average]
  (min, avg, max) = (9.677, 9.747, 9.843), stdev = 0.086
  CI (99.9%): [8.181, 11.313] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.738 ops/ms
# Warmup Iteration   2: 9.175 ops/ms
# Warmup Iteration   3: 10.183 ops/ms
Iteration   1: 10.904 ops/ms
Iteration   2: 10.459 ops/ms
Iteration   3: 10.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.573 ±(99.9%) 5.327 ops/ms [Average]
  (min, avg, max) = (10.354, 10.573, 10.904), stdev = 0.292
  CI (99.9%): [5.246, 15.899] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ops/ms
# Warmup Iteration   2: 9.418 ops/ms
# Warmup Iteration   3: 9.405 ops/ms
Iteration   1: 9.834 ops/ms
Iteration   2: 10.158 ops/ms
Iteration   3: 10.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.021 ±(99.9%) 3.054 ops/ms [Average]
  (min, avg, max) = (9.834, 10.021, 10.158), stdev = 0.167
  CI (99.9%): [6.966, 13.075] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.577 ops/ms
# Warmup Iteration   2: 7.800 ops/ms
# Warmup Iteration   3: 8.668 ops/ms
Iteration   1: 8.685 ops/ms
Iteration   2: 8.383 ops/ms
Iteration   3: 8.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.539 ±(99.9%) 2.763 ops/ms [Average]
  (min, avg, max) = (8.383, 8.539, 8.685), stdev = 0.151
  CI (99.9%): [5.776, 11.302] (assumes normal distribution)


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
# Warmup Iteration   1: 8.166 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.003 ms/op
Iteration   1: 3.160 ±(99.9%) 0.007 ms/op
Iteration   2: 3.252 ±(99.9%) 0.005 ms/op
Iteration   3: 3.173 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.195 ±(99.9%) 0.908 ms/op [Average]
  (min, avg, max) = (3.160, 3.195, 3.252), stdev = 0.050
  CI (99.9%): [2.287, 4.103] (assumes normal distribution)


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
# Warmup Iteration   1: 7.913 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.005 ms/op
Iteration   1: 3.102 ±(99.9%) 0.010 ms/op
Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
Iteration   3: 3.083 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.079 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (3.052, 3.079, 3.102), stdev = 0.025
  CI (99.9%): [2.617, 3.540] (assumes normal distribution)


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
# Warmup Iteration   1: 8.995 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.003 ms/op
Iteration   1: 3.269 ±(99.9%) 0.003 ms/op
Iteration   2: 3.202 ±(99.9%) 0.007 ms/op
Iteration   3: 3.338 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.270 ±(99.9%) 1.237 ms/op [Average]
  (min, avg, max) = (3.202, 3.270, 3.338), stdev = 0.068
  CI (99.9%): [2.032, 4.507] (assumes normal distribution)


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
# Warmup Iteration   1: 11.423 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.007 ms/op
Iteration   1: 3.693 ±(99.9%) 0.010 ms/op
Iteration   2: 3.689 ±(99.9%) 0.009 ms/op
Iteration   3: 3.759 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.714 ±(99.9%) 0.720 ms/op [Average]
  (min, avg, max) = (3.689, 3.714, 3.759), stdev = 0.039
  CI (99.9%): [2.994, 4.434] (assumes normal distribution)


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
# Warmup Iteration   1: 7.445 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.529 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
Iteration   1: 3.087 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  12.555 ms/op
                 createUser·p0.9999: 20.391 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.195 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  11.256 ms/op
                 createUser·p0.9999: 24.477 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   3: 3.211 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  17.695 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303145
  mean =      3.163 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23875 
    [ 2.500,  5.000) = 273949 
    [ 5.000,  7.500) = 4465 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     16.576 ms/op
     p(99.9900) =     23.648 ms/op
     p(99.9990) =     26.080 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 6.880 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
Iteration   1: 3.048 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  11.289 ms/op
                 existUser·p0.9999: 25.757 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  9.548 ms/op
                 existUser·p0.9999: 22.274 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  13.974 ms/op
                 existUser·p0.9999: 23.052 ms/op
                 existUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311246
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24926 
    [ 2.500,  5.000) = 282109 
    [ 5.000,  7.500) = 3487 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     24.502 ms/op
     p(99.9990) =     26.600 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 7.823 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
Iteration   1: 3.145 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  17.083 ms/op
                 getUser·p0.9999: 20.016 ms/op
                 getUser·p1.00:   20.283 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  8.974 ms/op
                 getUser·p0.9999: 25.002 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   3: 3.268 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.739 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  12.974 ms/op
                 getUser·p0.9999: 19.537 ms/op
                 getUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300756
  mean =      3.189 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20187 
    [ 2.500,  5.000) = 273759 
    [ 5.000,  7.500) = 5858 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 195 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     14.950 ms/op
     p(99.9900) =     23.674 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 8.946 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.012 ms/op
Iteration   1: 3.741 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.092 ms/op
                 listUser·p0.999:  15.343 ms/op
                 listUser·p0.9999: 22.133 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   2: 3.769 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.409 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 3.736 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  13.278 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256057
  mean =      3.749 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 248278 
    [ 5.000,  7.500) = 5744 
    [ 7.500, 10.000) = 1259 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 399 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     13.680 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     22.428 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.747 ± 1.566  ops/ms
ClientPb.existUser                       thrpt       3  10.573 ± 5.327  ops/ms
ClientPb.getUser                         thrpt       3  10.021 ± 3.054  ops/ms
ClientPb.listUser                        thrpt       3   8.539 ± 2.763  ops/ms
ClientPb.createUser                       avgt       3   3.195 ± 0.908   ms/op
ClientPb.existUser                        avgt       3   3.079 ± 0.461   ms/op
ClientPb.getUser                          avgt       3   3.270 ± 1.237   ms/op
ClientPb.listUser                         avgt       3   3.714 ± 0.720   ms/op
ClientPb.createUser                     sample  303145   3.163 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.126           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.432           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.576           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.648           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.706           ms/op
ClientPb.existUser                      sample  311246   3.083 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.098           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.517           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.502           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.673           ms/op
ClientPb.getUser                        sample  300756   3.189 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.903           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.666           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.950           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.674           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.116           ms/op
ClientPb.listUser                       sample  256057   3.749 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.669           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.127           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.135           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.708           ms/op
