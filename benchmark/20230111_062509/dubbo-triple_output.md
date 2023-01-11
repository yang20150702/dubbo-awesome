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
# Warmup Iteration   1: 2.565 ops/ms
# Warmup Iteration   2: 5.782 ops/ms
# Warmup Iteration   3: 9.143 ops/ms
Iteration   1: 9.598 ops/ms
Iteration   2: 9.637 ops/ms
Iteration   3: 9.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.629 ±(99.9%) 0.505 ops/ms [Average]
  (min, avg, max) = (9.598, 9.629, 9.652), stdev = 0.028
  CI (99.9%): [9.125, 10.134] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.563 ops/ms
# Warmup Iteration   2: 8.990 ops/ms
# Warmup Iteration   3: 9.784 ops/ms
Iteration   1: 10.201 ops/ms
Iteration   2: 10.482 ops/ms
Iteration   3: 10.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.323 ±(99.9%) 2.629 ops/ms [Average]
  (min, avg, max) = (10.201, 10.323, 10.482), stdev = 0.144
  CI (99.9%): [7.695, 12.952] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.553 ops/ms
# Warmup Iteration   2: 9.497 ops/ms
# Warmup Iteration   3: 9.683 ops/ms
Iteration   1: 9.864 ops/ms
Iteration   2: 9.876 ops/ms
Iteration   3: 10.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.918 ±(99.9%) 1.505 ops/ms [Average]
  (min, avg, max) = (9.864, 9.918, 10.013), stdev = 0.082
  CI (99.9%): [8.413, 11.423] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ops/ms
# Warmup Iteration   2: 7.902 ops/ms
# Warmup Iteration   3: 8.650 ops/ms
Iteration   1: 8.740 ops/ms
Iteration   2: 8.787 ops/ms
Iteration   3: 8.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.692 ±(99.9%) 2.296 ops/ms [Average]
  (min, avg, max) = (8.549, 8.692, 8.787), stdev = 0.126
  CI (99.9%): [6.396, 10.988] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.839 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.002 ms/op
Iteration   1: 3.287 ±(99.9%) 0.006 ms/op
Iteration   2: 3.314 ±(99.9%) 0.006 ms/op
Iteration   3: 3.192 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.264 ±(99.9%) 1.163 ms/op [Average]
  (min, avg, max) = (3.192, 3.264, 3.314), stdev = 0.064
  CI (99.9%): [2.101, 4.428] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.682 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.005 ms/op
Iteration   1: 3.089 ±(99.9%) 0.008 ms/op
Iteration   2: 3.046 ±(99.9%) 0.004 ms/op
Iteration   3: 3.053 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.063 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.046, 3.063, 3.089), stdev = 0.023
  CI (99.9%): [2.640, 3.486] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.743 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.003 ms/op
Iteration   1: 3.209 ±(99.9%) 0.001 ms/op
Iteration   2: 3.210 ±(99.9%) 0.006 ms/op
Iteration   3: 3.249 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.223 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.209, 3.223, 3.249), stdev = 0.022
  CI (99.9%): [2.813, 3.633] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.340 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.005 ms/op
Iteration   1: 3.720 ±(99.9%) 0.013 ms/op
Iteration   2: 3.711 ±(99.9%) 0.008 ms/op
Iteration   3: 3.587 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.673 ±(99.9%) 1.353 ms/op [Average]
  (min, avg, max) = (3.587, 3.673, 3.720), stdev = 0.074
  CI (99.9%): [2.320, 5.026] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.914 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.029 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.008 ms/op
Iteration   1: 3.182 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.862 ms/op
                 createUser·p0.999:  17.510 ms/op
                 createUser·p0.9999: 22.215 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   2: 3.195 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  14.105 ms/op
                 createUser·p0.9999: 20.643 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   3: 3.159 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   6.134 ms/op
                 createUser·p0.999:  15.958 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302170
  mean =      3.179 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17848 
    [ 2.500,  5.000) = 276883 
    [ 5.000,  7.500) = 6086 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 169 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      6.122 ms/op
     p(99.9000) =     17.055 ms/op
     p(99.9900) =     22.472 ms/op
     p(99.9990) =     23.525 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.211 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.008 ms/op
Iteration   1: 3.075 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  14.057 ms/op
                 existUser·p0.9999: 24.786 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   5.281 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 23.745 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   3: 3.146 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  11.917 ms/op
                 existUser·p0.9999: 24.216 ms/op
                 existUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309311
  mean =      3.103 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23023 
    [ 2.500,  5.000) = 280806 
    [ 5.000,  7.500) = 4753 
    [ 7.500, 10.000) = 354 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.606 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 7.837 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.011 ms/op
Iteration   1: 3.258 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  16.046 ms/op
                 getUser·p0.9999: 20.984 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.518 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  8.216 ms/op
                 getUser·p0.9999: 20.513 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   3: 3.204 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  9.866 ms/op
                 getUser·p0.9999: 22.611 ms/op
                 getUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302354
  mean =      3.174 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14106 
    [ 2.500,  5.000) = 281515 
    [ 5.000,  7.500) = 6044 
    [ 7.500, 10.000) = 366 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     15.701 ms/op
     p(99.9900) =     21.849 ms/op
     p(99.9990) =     23.624 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 8.328 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.010 ms/op
Iteration   1: 3.728 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 19.314 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 3.699 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.648 ms/op
                 listUser·p0.9999: 17.695 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 3.753 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.903 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 17.199 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257323
  mean =      3.726 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 68 
    [ 2.500,  3.750) = 191514 
    [ 3.750,  5.000) = 56988 
    [ 5.000,  6.250) = 3711 
    [ 6.250,  7.500) = 3169 
    [ 7.500,  8.750) = 863 
    [ 8.750, 10.000) = 364 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 145 
    [12.500, 13.750) = 187 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.937 ms/op
     p(99.9000) =     13.555 ms/op
     p(99.9900) =     18.269 ms/op
     p(99.9990) =     19.740 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.629 ± 0.505  ops/ms
ClientPb.existUser                       thrpt       3  10.323 ± 2.629  ops/ms
ClientPb.getUser                         thrpt       3   9.918 ± 1.505  ops/ms
ClientPb.listUser                        thrpt       3   8.692 ± 2.296  ops/ms
ClientPb.createUser                       avgt       3   3.264 ± 1.163   ms/op
ClientPb.existUser                        avgt       3   3.063 ± 0.423   ms/op
ClientPb.getUser                          avgt       3   3.223 ± 0.410   ms/op
ClientPb.listUser                         avgt       3   3.673 ± 1.353   ms/op
ClientPb.createUser                     sample  302170   3.179 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.940           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.473           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.122           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.055           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.472           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.691           ms/op
ClientPb.existUser                      sample  309311   3.103 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.718           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.812           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.150           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.083           ms/op
ClientPb.getUser                        sample  302354   3.174 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.126           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.539           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.701           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.849           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.443           ms/op
ClientPb.listUser                       sample  257323   3.726 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.626           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.937           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.555           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.269           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.923           ms/op
