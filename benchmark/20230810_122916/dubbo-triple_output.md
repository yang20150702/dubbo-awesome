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
# Warmup Iteration   1: 2.512 ops/ms
# Warmup Iteration   2: 5.626 ops/ms
# Warmup Iteration   3: 9.016 ops/ms
Iteration   1: 9.500 ops/ms
Iteration   2: 9.682 ops/ms
Iteration   3: 9.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.606 ±(99.9%) 1.725 ops/ms [Average]
  (min, avg, max) = (9.500, 9.606, 9.682), stdev = 0.095
  CI (99.9%): [7.880, 11.331] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.870 ops/ms
# Warmup Iteration   2: 9.243 ops/ms
# Warmup Iteration   3: 9.783 ops/ms
Iteration   1: 10.077 ops/ms
Iteration   2: 10.245 ops/ms
Iteration   3: 10.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.192 ±(99.9%) 1.808 ops/ms [Average]
  (min, avg, max) = (10.077, 10.192, 10.253), stdev = 0.099
  CI (99.9%): [8.383, 12.000] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.285 ops/ms
# Warmup Iteration   2: 9.149 ops/ms
# Warmup Iteration   3: 9.331 ops/ms
Iteration   1: 9.906 ops/ms
Iteration   2: 10.067 ops/ms
Iteration   3: 10.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.011 ±(99.9%) 1.660 ops/ms [Average]
  (min, avg, max) = (9.906, 10.011, 10.067), stdev = 0.091
  CI (99.9%): [8.351, 11.671] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.071 ops/ms
# Warmup Iteration   2: 7.326 ops/ms
# Warmup Iteration   3: 8.011 ops/ms
Iteration   1: 8.512 ops/ms
Iteration   2: 8.373 ops/ms
Iteration   3: 8.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.414 ±(99.9%) 1.560 ops/ms [Average]
  (min, avg, max) = (8.357, 8.414, 8.512), stdev = 0.086
  CI (99.9%): [6.854, 9.974] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.185 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.001 ms/op
Iteration   1: 3.202 ±(99.9%) 0.006 ms/op
Iteration   2: 3.177 ±(99.9%) 0.003 ms/op
Iteration   3: 3.169 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.183 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.169, 3.183, 3.202), stdev = 0.018
  CI (99.9%): [2.861, 3.505] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.336 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.003 ms/op
Iteration   1: 3.140 ±(99.9%) 0.004 ms/op
Iteration   2: 3.060 ±(99.9%) 0.002 ms/op
Iteration   3: 3.137 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.112 ±(99.9%) 0.823 ms/op [Average]
  (min, avg, max) = (3.060, 3.112, 3.140), stdev = 0.045
  CI (99.9%): [2.290, 3.935] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.029 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.004 ms/op
Iteration   1: 3.122 ±(99.9%) 0.004 ms/op
Iteration   2: 3.147 ±(99.9%) 0.005 ms/op
Iteration   3: 3.124 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.131 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (3.122, 3.131, 3.147), stdev = 0.014
  CI (99.9%): [2.874, 3.388] (assumes normal distribution)


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
# Warmup Iteration   1: 8.610 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.008 ms/op
Iteration   1: 3.885 ±(99.9%) 0.006 ms/op
Iteration   2: 3.823 ±(99.9%) 0.005 ms/op
Iteration   3: 3.786 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.831 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (3.786, 3.831, 3.885), stdev = 0.050
  CI (99.9%): [2.912, 4.751] (assumes normal distribution)


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
# Warmup Iteration   1: 7.092 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.010 ms/op
Iteration   1: 3.223 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  11.616 ms/op
                 createUser·p0.9999: 20.746 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 3.330 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.370 ms/op
                 createUser·p0.99:   6.189 ms/op
                 createUser·p0.999:  19.068 ms/op
                 createUser·p0.9999: 23.639 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 3.301 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  15.172 ms/op
                 createUser·p0.9999: 23.690 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292272
  mean =      3.284 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21260 
    [ 2.500,  5.000) = 262190 
    [ 5.000,  7.500) = 7610 
    [ 7.500, 10.000) = 753 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     23.356 ms/op
     p(99.9990) =     26.588 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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
# Warmup Iteration   1: 7.498 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
Iteration   1: 3.234 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  15.581 ms/op
                 existUser·p0.9999: 23.516 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 3.244 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  11.420 ms/op
                 existUser·p0.9999: 24.389 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.042 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  10.431 ms/op
                 existUser·p0.9999: 21.815 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298817
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28058 
    [ 2.500,  5.000) = 264205 
    [ 5.000,  7.500) = 5387 
    [ 7.500, 10.000) = 686 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     23.859 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 8.293 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.010 ms/op
Iteration   1: 3.286 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  13.453 ms/op
                 getUser·p0.9999: 17.931 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  11.747 ms/op
                 getUser·p0.9999: 18.380 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   3: 3.243 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  14.783 ms/op
                 getUser·p0.9999: 25.497 ms/op
                 getUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296946
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17238 
    [ 2.500,  5.000) = 271550 
    [ 5.000,  7.500) = 6420 
    [ 7.500, 10.000) = 1274 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     21.090 ms/op
     p(99.9990) =     26.845 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 9.331 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.012 ms/op
Iteration   1: 3.831 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  15.137 ms/op
                 listUser·p0.9999: 27.305 ms/op
                 listUser·p1.00:   27.754 ms/op

Iteration   2: 3.727 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  12.763 ms/op
                 listUser·p0.9999: 14.327 ms/op
                 listUser·p1.00:   16.105 ms/op

Iteration   3: 3.846 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  13.138 ms/op
                 listUser·p0.9999: 19.847 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252416
  mean =      3.801 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 243381 
    [ 5.000,  7.500) = 6587 
    [ 7.500, 10.000) = 1686 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     13.697 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     27.705 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.606 ± 1.725  ops/ms
ClientPb.existUser                       thrpt       3  10.192 ± 1.808  ops/ms
ClientPb.getUser                         thrpt       3  10.011 ± 1.660  ops/ms
ClientPb.listUser                        thrpt       3   8.414 ± 1.560  ops/ms
ClientPb.createUser                       avgt       3   3.183 ± 0.322   ms/op
ClientPb.existUser                        avgt       3   3.112 ± 0.823   ms/op
ClientPb.getUser                          avgt       3   3.131 ± 0.257   ms/op
ClientPb.listUser                         avgt       3   3.831 ± 0.919   ms/op
ClientPb.createUser                     sample  292272   3.284 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.296           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.972           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.172           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.356           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.771           ms/op
ClientPb.existUser                      sample  298817   3.212 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.042           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.998           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.895           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.859           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.395           ms/op
ClientPb.getUser                        sample  296946   3.235 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.571           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.455           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.762           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.090           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.279           ms/op
ClientPb.listUser                       sample  252416   3.801 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.180           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.125           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.315           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.697           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.969           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.754           ms/op
