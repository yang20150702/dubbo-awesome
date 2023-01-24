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
# Warmup Iteration   1: 2.694 ops/ms
# Warmup Iteration   2: 6.676 ops/ms
# Warmup Iteration   3: 9.135 ops/ms
Iteration   1: 9.764 ops/ms
Iteration   2: 9.899 ops/ms
Iteration   3: 9.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.854 ±(99.9%) 1.429 ops/ms [Average]
  (min, avg, max) = (9.764, 9.854, 9.900), stdev = 0.078
  CI (99.9%): [8.425, 11.283] (assumes normal distribution)


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
# Warmup Iteration   1: 3.621 ops/ms
# Warmup Iteration   2: 9.372 ops/ms
# Warmup Iteration   3: 9.997 ops/ms
Iteration   1: 10.638 ops/ms
Iteration   2: 10.579 ops/ms
Iteration   3: 10.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.530 ±(99.9%) 2.550 ops/ms [Average]
  (min, avg, max) = (10.372, 10.530, 10.638), stdev = 0.140
  CI (99.9%): [7.980, 13.080] (assumes normal distribution)


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
# Warmup Iteration   1: 3.695 ops/ms
# Warmup Iteration   2: 9.496 ops/ms
# Warmup Iteration   3: 9.996 ops/ms
Iteration   1: 10.284 ops/ms
Iteration   2: 10.166 ops/ms
Iteration   3: 9.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.085 ±(99.9%) 4.561 ops/ms [Average]
  (min, avg, max) = (9.804, 10.085, 10.284), stdev = 0.250
  CI (99.9%): [5.524, 14.646] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.125 ops/ms
# Warmup Iteration   2: 7.701 ops/ms
# Warmup Iteration   3: 8.267 ops/ms
Iteration   1: 8.524 ops/ms
Iteration   2: 8.558 ops/ms
Iteration   3: 8.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.536 ±(99.9%) 0.349 ops/ms [Average]
  (min, avg, max) = (8.524, 8.536, 8.558), stdev = 0.019
  CI (99.9%): [8.187, 8.885] (assumes normal distribution)


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
# Warmup Iteration   1: 7.607 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.006 ms/op
Iteration   1: 3.228 ±(99.9%) 0.006 ms/op
Iteration   2: 3.222 ±(99.9%) 0.008 ms/op
Iteration   3: 3.287 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.245 ±(99.9%) 0.659 ms/op [Average]
  (min, avg, max) = (3.222, 3.245, 3.287), stdev = 0.036
  CI (99.9%): [2.587, 3.904] (assumes normal distribution)


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
# Warmup Iteration   1: 7.463 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.007 ms/op
Iteration   1: 2.993 ±(99.9%) 0.002 ms/op
Iteration   2: 3.073 ±(99.9%) 0.005 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.038 ±(99.9%) 0.751 ms/op [Average]
  (min, avg, max) = (2.993, 3.038, 3.073), stdev = 0.041
  CI (99.9%): [2.287, 3.789] (assumes normal distribution)


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
# Warmup Iteration   1: 8.303 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.004 ms/op
Iteration   1: 3.267 ±(99.9%) 0.005 ms/op
Iteration   2: 3.099 ±(99.9%) 0.004 ms/op
Iteration   3: 3.070 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.145 ±(99.9%) 1.937 ms/op [Average]
  (min, avg, max) = (3.070, 3.145, 3.267), stdev = 0.106
  CI (99.9%): [1.208, 5.083] (assumes normal distribution)


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
# Warmup Iteration   1: 8.748 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.006 ms/op
Iteration   1: 3.735 ±(99.9%) 0.009 ms/op
Iteration   2: 3.773 ±(99.9%) 0.004 ms/op
Iteration   3: 3.674 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.727 ±(99.9%) 0.911 ms/op [Average]
  (min, avg, max) = (3.674, 3.727, 3.773), stdev = 0.050
  CI (99.9%): [2.816, 4.639] (assumes normal distribution)


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
# Warmup Iteration   1: 8.214 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.009 ms/op
Iteration   1: 3.222 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  17.105 ms/op
                 createUser·p0.9999: 20.913 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   2: 3.258 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.409 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  10.235 ms/op
                 createUser·p0.9999: 22.845 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.218 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  13.232 ms/op
                 createUser·p0.9999: 25.266 ms/op
                 createUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296919
  mean =      3.233 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25572 
    [ 2.500,  5.000) = 265991 
    [ 5.000,  7.500) = 4432 
    [ 7.500, 10.000) = 504 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.409 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     25.563 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.140 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.009 ms/op
Iteration   1: 3.002 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.212 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.129 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   4.464 ms/op
                 existUser·p0.999:  8.602 ms/op
                 existUser·p0.9999: 21.346 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   2: 3.142 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  8.405 ms/op
                 existUser·p0.9999: 21.686 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  8.389 ms/op
                 existUser·p0.9999: 21.673 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311373
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23188 
    [ 2.500,  5.000) = 283869 
    [ 5.000,  7.500) = 3648 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 159 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.256 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     22.358 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.486 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.009 ms/op
Iteration   1: 3.129 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  10.940 ms/op
                 getUser·p0.9999: 24.478 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  9.224 ms/op
                 getUser·p0.9999: 25.006 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.265 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  10.977 ms/op
                 getUser·p0.9999: 22.381 ms/op
                 getUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299046
  mean =      3.210 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12591 
    [ 2.500,  5.000) = 280242 
    [ 5.000,  7.500) = 5324 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     10.928 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.779 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.011 ms/op
Iteration   1: 3.769 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  15.237 ms/op
                 listUser·p0.9999: 25.314 ms/op
                 listUser·p1.00:   28.705 ms/op

Iteration   2: 3.629 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.125 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  13.186 ms/op
                 listUser·p0.9999: 14.933 ms/op
                 listUser·p1.00:   16.400 ms/op

Iteration   3: 3.717 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  11.960 ms/op
                 listUser·p0.9999: 16.165 ms/op
                 listUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258875
  mean =      3.704 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 252458 
    [ 5.000,  7.500) = 4983 
    [ 7.500, 10.000) = 818 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     24.481 ms/op
     p(99.9990) =     28.685 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.854 ± 1.429  ops/ms
ClientPb.existUser                       thrpt       3  10.530 ± 2.550  ops/ms
ClientPb.getUser                         thrpt       3  10.085 ± 4.561  ops/ms
ClientPb.listUser                        thrpt       3   8.536 ± 0.349  ops/ms
ClientPb.createUser                       avgt       3   3.245 ± 0.659   ms/op
ClientPb.existUser                        avgt       3   3.038 ± 0.751   ms/op
ClientPb.getUser                          avgt       3   3.145 ± 1.937   ms/op
ClientPb.listUser                         avgt       3   3.727 ± 0.911   ms/op
ClientPb.createUser                     sample  296919   3.233 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.409           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.728           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.412           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.788           ms/op
ClientPb.existUser                      sample  311373   3.079 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.212           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.317           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.585           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.594           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.034           ms/op
ClientPb.getUser                        sample  299046   3.210 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.928           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.412           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.657           ms/op
ClientPb.listUser                       sample  258875   3.704 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.663           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.609           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.595           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.189           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.481           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.705           ms/op
