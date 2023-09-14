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
# Warmup Iteration   1: 2.560 ops/ms
# Warmup Iteration   2: 6.346 ops/ms
# Warmup Iteration   3: 9.165 ops/ms
Iteration   1: 9.770 ops/ms
Iteration   2: 9.672 ops/ms
Iteration   3: 9.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.776 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (9.672, 9.776, 9.887), stdev = 0.108
  CI (99.9%): [7.811, 11.741] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.542 ops/ms
# Warmup Iteration   2: 9.382 ops/ms
# Warmup Iteration   3: 9.995 ops/ms
Iteration   1: 9.980 ops/ms
Iteration   2: 10.557 ops/ms
Iteration   3: 10.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.283 ±(99.9%) 5.282 ops/ms [Average]
  (min, avg, max) = (9.980, 10.283, 10.557), stdev = 0.290
  CI (99.9%): [5.001, 15.566] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.127 ops/ms
# Warmup Iteration   2: 9.480 ops/ms
# Warmup Iteration   3: 9.666 ops/ms
Iteration   1: 9.585 ops/ms
Iteration   2: 9.865 ops/ms
Iteration   3: 9.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.756 ±(99.9%) 2.744 ops/ms [Average]
  (min, avg, max) = (9.585, 9.756, 9.865), stdev = 0.150
  CI (99.9%): [7.013, 12.500] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.499 ops/ms
# Warmup Iteration   2: 7.961 ops/ms
# Warmup Iteration   3: 8.004 ops/ms
Iteration   1: 8.511 ops/ms
Iteration   2: 8.538 ops/ms
Iteration   3: 8.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.511 ±(99.9%) 0.497 ops/ms [Average]
  (min, avg, max) = (8.483, 8.511, 8.538), stdev = 0.027
  CI (99.9%): [8.013, 9.008] (assumes normal distribution)


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
# Warmup Iteration   1: 8.248 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.005 ms/op
Iteration   1: 3.242 ±(99.9%) 0.002 ms/op
Iteration   2: 3.186 ±(99.9%) 0.002 ms/op
Iteration   3: 3.196 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.208 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (3.186, 3.208, 3.242), stdev = 0.030
  CI (99.9%): [2.668, 3.747] (assumes normal distribution)


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
# Warmup Iteration   1: 7.419 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.002 ms/op
Iteration   1: 3.110 ±(99.9%) 0.003 ms/op
Iteration   2: 3.118 ±(99.9%) 0.002 ms/op
Iteration   3: 3.105 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.111 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (3.105, 3.111, 3.118), stdev = 0.006
  CI (99.9%): [2.995, 3.227] (assumes normal distribution)


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
# Warmup Iteration   1: 7.597 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.003 ms/op
Iteration   1: 3.193 ±(99.9%) 0.004 ms/op
Iteration   2: 3.191 ±(99.9%) 0.003 ms/op
Iteration   3: 3.159 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.181 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (3.159, 3.181, 3.193), stdev = 0.019
  CI (99.9%): [2.829, 3.533] (assumes normal distribution)


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
# Warmup Iteration   1: 9.224 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.004 ms/op
Iteration   1: 3.772 ±(99.9%) 0.006 ms/op
Iteration   2: 3.752 ±(99.9%) 0.003 ms/op
Iteration   3: 3.793 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.773 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.752, 3.773, 3.793), stdev = 0.021
  CI (99.9%): [3.397, 4.148] (assumes normal distribution)


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
# Warmup Iteration   1: 8.693 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
Iteration   1: 3.208 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  10.982 ms/op
                 createUser·p0.9999: 20.873 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.868 ms/op
                 createUser·p0.999:  19.366 ms/op
                 createUser·p0.9999: 21.453 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  15.957 ms/op
                 createUser·p0.9999: 20.326 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297671
  mean =      3.224 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16131 
    [ 2.500,  5.000) = 277629 
    [ 5.000,  7.500) = 3115 
    [ 7.500, 10.000) = 170 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     16.886 ms/op
     p(99.9900) =     21.077 ms/op
     p(99.9990) =     22.088 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 7.371 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.376 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
Iteration   1: 3.150 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 18.312 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  14.620 ms/op
                 existUser·p0.9999: 22.131 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   3: 3.142 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  8.191 ms/op
                 existUser·p0.9999: 21.615 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305352
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15028 
    [ 2.500,  5.000) = 286102 
    [ 5.000,  7.500) = 3410 
    [ 7.500, 10.000) = 248 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     12.817 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     22.639 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 9.054 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
Iteration   1: 3.385 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   5.296 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  18.055 ms/op
                 getUser·p0.9999: 20.090 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  15.513 ms/op
                 getUser·p0.9999: 22.806 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.243 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.884 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  13.844 ms/op
                 getUser·p0.9999: 20.288 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293193
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7723 
    [ 2.500,  5.000) = 276967 
    [ 5.000,  7.500) = 7484 
    [ 7.500, 10.000) = 395 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     16.063 ms/op
     p(99.9900) =     21.934 ms/op
     p(99.9990) =     23.333 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 8.580 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.011 ms/op
Iteration   1: 3.846 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.990 ms/op
                 listUser·p0.999:  15.860 ms/op
                 listUser·p0.9999: 23.079 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 3.869 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  12.711 ms/op
                 listUser·p0.9999: 16.989 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   3: 3.785 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.042 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  13.124 ms/op
                 listUser·p0.9999: 20.145 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250465
  mean =      3.833 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 244143 
    [ 5.000,  7.500) = 4860 
    [ 7.500, 10.000) = 586 
    [10.000, 12.500) = 382 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.320 ms/op
     p(99.9900) =     21.295 ms/op
     p(99.9990) =     23.756 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.776 ± 1.965  ops/ms
ClientPb.existUser                       thrpt       3  10.283 ± 5.282  ops/ms
ClientPb.getUser                         thrpt       3   9.756 ± 2.744  ops/ms
ClientPb.listUser                        thrpt       3   8.511 ± 0.497  ops/ms
ClientPb.createUser                       avgt       3   3.208 ± 0.539   ms/op
ClientPb.existUser                        avgt       3   3.111 ± 0.116   ms/op
ClientPb.getUser                          avgt       3   3.181 ± 0.352   ms/op
ClientPb.listUser                         avgt       3   3.773 ± 0.375   ms/op
ClientPb.createUser                     sample  297671   3.224 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.133           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.886           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.077           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.217           ms/op
ClientPb.existUser                      sample  305352   3.142 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.927           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.817           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.529           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.774           ms/op
ClientPb.getUser                        sample  293193   3.273 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.192           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.701           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.063           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.934           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.593           ms/op
ClientPb.listUser                       sample  250465   3.833 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.997           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.744           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.320           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.295           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.216           ms/op
