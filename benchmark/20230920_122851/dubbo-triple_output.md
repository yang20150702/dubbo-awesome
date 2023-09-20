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
# Warmup Iteration   1: 2.083 ops/ms
# Warmup Iteration   2: 4.977 ops/ms
# Warmup Iteration   3: 8.479 ops/ms
Iteration   1: 9.128 ops/ms
Iteration   2: 9.230 ops/ms
Iteration   3: 9.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.157 ±(99.9%) 1.167 ops/ms [Average]
  (min, avg, max) = (9.112, 9.157, 9.230), stdev = 0.064
  CI (99.9%): [7.990, 10.324] (assumes normal distribution)


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
# Warmup Iteration   1: 3.574 ops/ms
# Warmup Iteration   2: 9.043 ops/ms
# Warmup Iteration   3: 9.397 ops/ms
Iteration   1: 9.866 ops/ms
Iteration   2: 9.762 ops/ms
Iteration   3: 9.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.787 ±(99.9%) 1.277 ops/ms [Average]
  (min, avg, max) = (9.733, 9.787, 9.866), stdev = 0.070
  CI (99.9%): [8.510, 11.063] (assumes normal distribution)


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
# Warmup Iteration   1: 2.875 ops/ms
# Warmup Iteration   2: 8.272 ops/ms
# Warmup Iteration   3: 9.215 ops/ms
Iteration   1: 9.200 ops/ms
Iteration   2: 9.485 ops/ms
Iteration   3: 9.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.338 ±(99.9%) 2.609 ops/ms [Average]
  (min, avg, max) = (9.200, 9.338, 9.485), stdev = 0.143
  CI (99.9%): [6.729, 11.946] (assumes normal distribution)


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
# Warmup Iteration   1: 2.523 ops/ms
# Warmup Iteration   2: 6.633 ops/ms
# Warmup Iteration   3: 7.495 ops/ms
Iteration   1: 7.544 ops/ms
Iteration   2: 7.629 ops/ms
Iteration   3: 7.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.585 ±(99.9%) 0.778 ops/ms [Average]
  (min, avg, max) = (7.544, 7.585, 7.629), stdev = 0.043
  CI (99.9%): [6.807, 8.363] (assumes normal distribution)


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
# Warmup Iteration   1: 11.260 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.003 ms/op
Iteration   1: 3.551 ±(99.9%) 0.004 ms/op
Iteration   2: 3.471 ±(99.9%) 0.005 ms/op
Iteration   3: 3.403 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.475 ±(99.9%) 1.348 ms/op [Average]
  (min, avg, max) = (3.403, 3.475, 3.551), stdev = 0.074
  CI (99.9%): [2.127, 4.824] (assumes normal distribution)


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
# Warmup Iteration   1: 8.884 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.005 ms/op
Iteration   1: 3.330 ±(99.9%) 0.003 ms/op
Iteration   2: 3.330 ±(99.9%) 0.003 ms/op
Iteration   3: 3.323 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.328 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (3.323, 3.328, 3.330), stdev = 0.004
  CI (99.9%): [3.254, 3.402] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.330 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.003 ms/op
Iteration   1: 3.613 ±(99.9%) 0.004 ms/op
Iteration   2: 3.433 ±(99.9%) 0.004 ms/op
Iteration   3: 3.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.502 ±(99.9%) 1.774 ms/op [Average]
  (min, avg, max) = (3.433, 3.502, 3.613), stdev = 0.097
  CI (99.9%): [1.728, 5.276] (assumes normal distribution)


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
# Warmup Iteration   1: 11.683 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.568 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.008 ms/op
Iteration   1: 4.199 ±(99.9%) 0.011 ms/op
Iteration   2: 4.138 ±(99.9%) 0.011 ms/op
Iteration   3: 4.130 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.155 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (4.130, 4.155, 4.199), stdev = 0.038
  CI (99.9%): [3.468, 4.842] (assumes normal distribution)


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
# Warmup Iteration   1: 9.793 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.009 ms/op
Iteration   1: 3.562 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  21.084 ms/op
                 createUser·p0.9999: 32.866 ms/op
                 createUser·p1.00:   33.260 ms/op

Iteration   2: 3.582 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  23.164 ms/op
                 createUser·p0.9999: 26.477 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   3: 3.506 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.333 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.216 ms/op
                 createUser·p0.999:  19.391 ms/op
                 createUser·p0.9999: 28.103 ms/op
                 createUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270625
  mean =      3.550 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6510 
    [ 2.500,  5.000) = 256956 
    [ 5.000,  7.500) = 5970 
    [ 7.500, 10.000) = 629 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     20.062 ms/op
     p(99.9900) =     29.817 ms/op
     p(99.9990) =     33.213 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 8.393 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.011 ms/op
Iteration   1: 3.286 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  9.863 ms/op
                 existUser·p0.9999: 23.490 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   2: 3.345 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   6.422 ms/op
                 existUser·p0.999:  22.419 ms/op
                 existUser·p0.9999: 25.213 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   3: 3.350 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.753 ms/op
                 existUser·p0.999:  18.433 ms/op
                 existUser·p0.9999: 26.637 ms/op
                 existUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288445
  mean =      3.327 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7576 
    [ 2.500,  5.000) = 275060 
    [ 5.000,  7.500) = 4819 
    [ 7.500, 10.000) = 613 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     26.056 ms/op
     p(99.9990) =     27.463 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 9.490 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.009 ms/op
Iteration   1: 3.478 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  18.163 ms/op
                 getUser·p0.9999: 22.118 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   2: 3.414 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.534 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  21.475 ms/op
                 getUser·p0.9999: 24.793 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   3: 3.470 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  10.532 ms/op
                 getUser·p0.9999: 25.898 ms/op
                 getUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277784
  mean =      3.454 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5043 
    [ 2.500,  5.000) = 265793 
    [ 5.000,  7.500) = 5794 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     15.018 ms/op
     p(99.9900) =     25.057 ms/op
     p(99.9990) =     26.480 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 11.602 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.396 ±(99.9%) 0.015 ms/op
Iteration   1: 4.199 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  21.510 ms/op
                 listUser·p0.9999: 30.197 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   2: 4.182 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  15.509 ms/op
                 listUser·p0.9999: 17.182 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 4.188 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.002 ms/op
                 listUser·p0.9999: 16.986 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228980
  mean =      4.189 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 219929 
    [ 5.000,  7.500) = 7231 
    [ 7.500, 10.000) = 954 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 260 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     28.184 ms/op
     p(99.9990) =     30.956 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.157 ± 1.167  ops/ms
ClientPb.existUser                       thrpt       3   9.787 ± 1.277  ops/ms
ClientPb.getUser                         thrpt       3   9.338 ± 2.609  ops/ms
ClientPb.listUser                        thrpt       3   7.585 ± 0.778  ops/ms
ClientPb.createUser                       avgt       3   3.475 ± 1.348   ms/op
ClientPb.existUser                        avgt       3   3.328 ± 0.074   ms/op
ClientPb.getUser                          avgt       3   3.502 ± 1.774   ms/op
ClientPb.listUser                         avgt       3   4.155 ± 0.687   ms/op
ClientPb.createUser                     sample  270625   3.550 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.333           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.283           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.062           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.817           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.260           ms/op
ClientPb.existUser                      sample  288445   3.327 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.677           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.468           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.056           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.853           ms/op
ClientPb.getUser                        sample  277784   3.454 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.198           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.018           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.057           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.903           ms/op
ClientPb.listUser                       sample  228980   4.189 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.540           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.078           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.827           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.184           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.064           ms/op
