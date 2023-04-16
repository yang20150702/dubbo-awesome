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
# Warmup Iteration   1: 2.533 ops/ms
# Warmup Iteration   2: 6.617 ops/ms
# Warmup Iteration   3: 9.337 ops/ms
Iteration   1: 9.598 ops/ms
Iteration   2: 10.139 ops/ms
Iteration   3: 10.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.929 ±(99.9%) 5.290 ops/ms [Average]
  (min, avg, max) = (9.598, 9.929, 10.139), stdev = 0.290
  CI (99.9%): [4.639, 15.220] (assumes normal distribution)


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
# Warmup Iteration   1: 3.642 ops/ms
# Warmup Iteration   2: 8.784 ops/ms
# Warmup Iteration   3: 10.264 ops/ms
Iteration   1: 10.641 ops/ms
Iteration   2: 10.330 ops/ms
Iteration   3: 10.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.387 ±(99.9%) 4.197 ops/ms [Average]
  (min, avg, max) = (10.191, 10.387, 10.641), stdev = 0.230
  CI (99.9%): [6.190, 14.585] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.684 ops/ms
# Warmup Iteration   2: 8.993 ops/ms
# Warmup Iteration   3: 9.603 ops/ms
Iteration   1: 10.092 ops/ms
Iteration   2: 10.013 ops/ms
Iteration   3: 10.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.190 ±(99.9%) 4.418 ops/ms [Average]
  (min, avg, max) = (10.013, 10.190, 10.466), stdev = 0.242
  CI (99.9%): [5.772, 14.608] (assumes normal distribution)


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
# Warmup Iteration   1: 3.283 ops/ms
# Warmup Iteration   2: 7.375 ops/ms
# Warmup Iteration   3: 8.074 ops/ms
Iteration   1: 8.747 ops/ms
Iteration   2: 8.819 ops/ms
Iteration   3: 8.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.701 ±(99.9%) 2.671 ops/ms [Average]
  (min, avg, max) = (8.538, 8.701, 8.819), stdev = 0.146
  CI (99.9%): [6.031, 11.372] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.045 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.007 ms/op
Iteration   1: 3.278 ±(99.9%) 0.004 ms/op
Iteration   2: 3.337 ±(99.9%) 0.005 ms/op
Iteration   3: 3.160 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.258 ±(99.9%) 1.648 ms/op [Average]
  (min, avg, max) = (3.160, 3.258, 3.337), stdev = 0.090
  CI (99.9%): [1.611, 4.906] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.105 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.005 ms/op
Iteration   1: 3.371 ±(99.9%) 0.011 ms/op
Iteration   2: 3.037 ±(99.9%) 0.002 ms/op
Iteration   3: 3.018 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.142 ±(99.9%) 3.617 ms/op [Average]
  (min, avg, max) = (3.018, 3.142, 3.371), stdev = 0.198
  CI (99.9%): [≈ 0, 6.758] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.518 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.005 ms/op
Iteration   1: 3.202 ±(99.9%) 0.005 ms/op
Iteration   2: 3.063 ±(99.9%) 0.003 ms/op
Iteration   3: 3.209 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.158 ±(99.9%) 1.501 ms/op [Average]
  (min, avg, max) = (3.063, 3.158, 3.209), stdev = 0.082
  CI (99.9%): [1.657, 4.659] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.326 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.006 ms/op
Iteration   1: 3.781 ±(99.9%) 0.006 ms/op
Iteration   2: 3.803 ±(99.9%) 0.003 ms/op
Iteration   3: 3.689 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.758 ±(99.9%) 1.100 ms/op [Average]
  (min, avg, max) = (3.689, 3.758, 3.803), stdev = 0.060
  CI (99.9%): [2.658, 4.858] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.936 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.009 ms/op
Iteration   1: 3.162 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 19.030 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   2: 3.093 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.211 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  10.922 ms/op
                 createUser·p0.9999: 30.916 ms/op
                 createUser·p1.00:   31.588 ms/op

Iteration   3: 3.123 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  13.422 ms/op
                 createUser·p0.9999: 17.581 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306993
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17113 
    [ 2.500,  5.000) = 286446 
    [ 5.000,  7.500) = 2689 
    [ 7.500, 10.000) = 348 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     28.800 ms/op
     p(99.9990) =     31.556 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 7.895 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.372 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.008 ms/op
Iteration   1: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.638 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 25.356 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   2: 3.108 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.466 ms/op
                 existUser·p0.999:  13.273 ms/op
                 existUser·p0.9999: 21.748 ms/op
                 existUser·p1.00:   22.512 ms/op

Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  9.398 ms/op
                 existUser·p0.9999: 19.909 ms/op
                 existUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309201
  mean =      3.104 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18442 
    [ 2.500,  5.000) = 285283 
    [ 5.000,  7.500) = 4591 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     23.759 ms/op
     p(99.9990) =     25.976 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 7.386 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
Iteration   1: 3.384 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  17.367 ms/op
                 getUser·p0.9999: 20.873 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   2: 3.136 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  10.249 ms/op
                 getUser·p0.9999: 21.981 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   3: 3.218 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  9.732 ms/op
                 getUser·p0.9999: 21.533 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295864
  mean =      3.243 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17088 
    [ 2.500,  5.000) = 269890 
    [ 5.000,  7.500) = 7814 
    [ 7.500, 10.000) = 654 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     22.678 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 8.553 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.011 ms/op
Iteration   1: 3.801 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 24.700 ms/op
                 listUser·p1.00:   32.539 ms/op

Iteration   2: 3.853 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   5.176 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 3.866 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  13.025 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249972
  mean =      3.840 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 238408 
    [ 5.000,  7.500) = 9693 
    [ 7.500, 10.000) = 1042 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 311 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     28.493 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.929 ± 5.290  ops/ms
ClientPb.existUser                       thrpt       3  10.387 ± 4.197  ops/ms
ClientPb.getUser                         thrpt       3  10.190 ± 4.418  ops/ms
ClientPb.listUser                        thrpt       3   8.701 ± 2.671  ops/ms
ClientPb.createUser                       avgt       3   3.258 ± 1.648   ms/op
ClientPb.existUser                        avgt       3   3.142 ± 3.617   ms/op
ClientPb.getUser                          avgt       3   3.158 ± 1.501   ms/op
ClientPb.listUser                         avgt       3   3.758 ± 1.100   ms/op
ClientPb.createUser                     sample  306993   3.125 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.442           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.412           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.128           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.189           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.800           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.588           ms/op
ClientPb.existUser                      sample  309201   3.104 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.736           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.140           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.759           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.149           ms/op
ClientPb.getUser                        sample  295864   3.243 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.991           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.908           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.692           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.938           ms/op
ClientPb.listUser                       sample  249972   3.840 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.874           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.992           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.790           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.539           ms/op
