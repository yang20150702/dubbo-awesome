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
# Warmup Iteration   1: 2.374 ops/ms
# Warmup Iteration   2: 5.797 ops/ms
# Warmup Iteration   3: 8.861 ops/ms
Iteration   1: 9.584 ops/ms
Iteration   2: 9.793 ops/ms
Iteration   3: 9.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.741 ±(99.9%) 2.532 ops/ms [Average]
  (min, avg, max) = (9.584, 9.741, 9.846), stdev = 0.139
  CI (99.9%): [7.209, 12.273] (assumes normal distribution)


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
# Warmup Iteration   1: 3.435 ops/ms
# Warmup Iteration   2: 9.287 ops/ms
# Warmup Iteration   3: 9.988 ops/ms
Iteration   1: 10.173 ops/ms
Iteration   2: 10.213 ops/ms
Iteration   3: 10.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.137 ±(99.9%) 1.799 ops/ms [Average]
  (min, avg, max) = (10.025, 10.137, 10.213), stdev = 0.099
  CI (99.9%): [8.338, 11.936] (assumes normal distribution)


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
# Warmup Iteration   1: 3.315 ops/ms
# Warmup Iteration   2: 8.954 ops/ms
# Warmup Iteration   3: 9.830 ops/ms
Iteration   1: 9.980 ops/ms
Iteration   2: 9.982 ops/ms
Iteration   3: 9.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.965 ±(99.9%) 0.495 ops/ms [Average]
  (min, avg, max) = (9.934, 9.965, 9.982), stdev = 0.027
  CI (99.9%): [9.470, 10.460] (assumes normal distribution)


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
# Warmup Iteration   1: 3.023 ops/ms
# Warmup Iteration   2: 7.738 ops/ms
# Warmup Iteration   3: 8.059 ops/ms
Iteration   1: 8.356 ops/ms
Iteration   2: 8.463 ops/ms
Iteration   3: 8.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.385 ±(99.9%) 1.249 ops/ms [Average]
  (min, avg, max) = (8.335, 8.385, 8.463), stdev = 0.068
  CI (99.9%): [7.136, 9.634] (assumes normal distribution)


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
# Warmup Iteration   1: 8.015 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.005 ms/op
Iteration   1: 3.282 ±(99.9%) 0.003 ms/op
Iteration   2: 3.239 ±(99.9%) 0.004 ms/op
Iteration   3: 3.299 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.273 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (3.239, 3.273, 3.299), stdev = 0.031
  CI (99.9%): [2.711, 3.835] (assumes normal distribution)


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
# Warmup Iteration   1: 7.714 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.002 ms/op
Iteration   1: 3.123 ±(99.9%) 0.002 ms/op
Iteration   2: 3.204 ±(99.9%) 0.003 ms/op
Iteration   3: 3.130 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.152 ±(99.9%) 0.823 ms/op [Average]
  (min, avg, max) = (3.123, 3.152, 3.204), stdev = 0.045
  CI (99.9%): [2.330, 3.975] (assumes normal distribution)


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
# Warmup Iteration   1: 7.979 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.002 ms/op
Iteration   1: 3.158 ±(99.9%) 0.002 ms/op
Iteration   2: 3.248 ±(99.9%) 0.003 ms/op
Iteration   3: 3.251 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.219 ±(99.9%) 0.960 ms/op [Average]
  (min, avg, max) = (3.158, 3.219, 3.251), stdev = 0.053
  CI (99.9%): [2.259, 4.180] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.764 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.004 ms/op
Iteration   1: 3.805 ±(99.9%) 0.005 ms/op
Iteration   2: 3.735 ±(99.9%) 0.007 ms/op
Iteration   3: 3.803 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.781 ±(99.9%) 0.725 ms/op [Average]
  (min, avg, max) = (3.735, 3.781, 3.805), stdev = 0.040
  CI (99.9%): [3.056, 4.506] (assumes normal distribution)


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
# Warmup Iteration   1: 8.427 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
Iteration   1: 3.216 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.670 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 21.727 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   2: 3.293 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  18.305 ms/op
                 createUser·p0.9999: 22.947 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.318 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.952 ms/op
                 createUser·p0.99:   5.022 ms/op
                 createUser·p0.999:  15.576 ms/op
                 createUser·p0.9999: 19.312 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292779
  mean =      3.275 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11382 
    [ 2.500,  5.000) = 277320 
    [ 5.000,  7.500) = 2950 
    [ 7.500, 10.000) = 418 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     21.978 ms/op
     p(99.9990) =     23.729 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 7.805 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.344 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.008 ms/op
Iteration   1: 3.183 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  15.516 ms/op
                 existUser·p0.9999: 20.873 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   2: 3.217 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.068 ms/op
                 existUser·p0.999:  14.606 ms/op
                 existUser·p0.9999: 24.067 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   3: 3.163 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  13.386 ms/op
                 existUser·p0.9999: 21.616 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301126
  mean =      3.188 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16948 
    [ 2.500,  5.000) = 279496 
    [ 5.000,  7.500) = 3607 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     14.596 ms/op
     p(99.9900) =     22.803 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 7.371 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.010 ms/op
Iteration   1: 3.305 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.067 ms/op
                 getUser·p0.999:  18.252 ms/op
                 getUser·p0.9999: 22.981 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   2: 3.202 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  20.152 ms/op
                 getUser·p0.9999: 22.479 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   3: 3.243 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 22.090 ms/op
                 getUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295180
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7859 
    [ 2.500,  5.000) = 282240 
    [ 5.000,  7.500) = 4243 
    [ 7.500, 10.000) = 290 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 183 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     14.841 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     23.270 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 8.814 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.011 ms/op
Iteration   1: 3.846 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  15.602 ms/op
                 listUser·p0.9999: 23.277 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   2: 3.803 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.477 ms/op
                 listUser·p0.999:  12.370 ms/op
                 listUser·p0.9999: 14.369 ms/op
                 listUser·p1.00:   14.860 ms/op

Iteration   3: 3.798 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.522 ms/op
                 listUser·p0.9999: 16.040 ms/op
                 listUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251490
  mean =      3.816 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 245247 
    [ 5.000,  7.500) = 4917 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 311 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.608 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     21.556 ms/op
     p(99.9990) =     23.445 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.741 ± 2.532  ops/ms
ClientPb.existUser                       thrpt       3  10.137 ± 1.799  ops/ms
ClientPb.getUser                         thrpt       3   9.965 ± 0.495  ops/ms
ClientPb.listUser                        thrpt       3   8.385 ± 1.249  ops/ms
ClientPb.createUser                       avgt       3   3.273 ± 0.562   ms/op
ClientPb.existUser                        avgt       3   3.152 ± 0.823   ms/op
ClientPb.getUser                          avgt       3   3.219 ± 0.960   ms/op
ClientPb.listUser                         avgt       3   3.781 ± 0.725   ms/op
ClientPb.createUser                     sample  292779   3.275 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.104           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.203           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.978           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.986           ms/op
ClientPb.existUser                      sample  301126   3.188 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.673           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.579           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.596           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.803           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.035           ms/op
ClientPb.getUser                        sample  295180   3.249 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.860           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.644           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.841           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.381           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.462           ms/op
ClientPb.listUser                       sample  251490   3.816 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.608           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.619           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.139           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.556           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.495           ms/op
