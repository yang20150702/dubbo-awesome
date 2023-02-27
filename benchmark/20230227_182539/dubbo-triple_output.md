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
# Warmup Iteration   1: 2.150 ops/ms
# Warmup Iteration   2: 5.467 ops/ms
# Warmup Iteration   3: 8.213 ops/ms
Iteration   1: 9.186 ops/ms
Iteration   2: 8.954 ops/ms
Iteration   3: 9.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.206 ±(99.9%) 4.790 ops/ms [Average]
  (min, avg, max) = (8.954, 9.206, 9.478), stdev = 0.263
  CI (99.9%): [4.416, 13.996] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.839 ops/ms
# Warmup Iteration   2: 8.530 ops/ms
# Warmup Iteration   3: 9.421 ops/ms
Iteration   1: 9.581 ops/ms
Iteration   2: 9.403 ops/ms
Iteration   3: 9.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.559 ±(99.9%) 2.674 ops/ms [Average]
  (min, avg, max) = (9.403, 9.559, 9.693), stdev = 0.147
  CI (99.9%): [6.885, 12.233] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.659 ops/ms
# Warmup Iteration   2: 8.105 ops/ms
# Warmup Iteration   3: 9.449 ops/ms
Iteration   1: 9.003 ops/ms
Iteration   2: 9.590 ops/ms
Iteration   3: 9.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.298 ±(99.9%) 5.352 ops/ms [Average]
  (min, avg, max) = (9.003, 9.298, 9.590), stdev = 0.293
  CI (99.9%): [3.946, 14.650] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.538 ops/ms
# Warmup Iteration   2: 7.076 ops/ms
# Warmup Iteration   3: 7.683 ops/ms
Iteration   1: 7.882 ops/ms
Iteration   2: 8.188 ops/ms
Iteration   3: 7.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.981 ±(99.9%) 3.272 ops/ms [Average]
  (min, avg, max) = (7.872, 7.981, 8.188), stdev = 0.179
  CI (99.9%): [4.708, 11.253] (assumes normal distribution)


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
# Warmup Iteration   1: 8.918 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.005 ms/op
Iteration   1: 3.421 ±(99.9%) 0.013 ms/op
Iteration   2: 3.378 ±(99.9%) 0.014 ms/op
Iteration   3: 3.345 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.381 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (3.345, 3.381, 3.421), stdev = 0.038
  CI (99.9%): [2.687, 4.075] (assumes normal distribution)


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
# Warmup Iteration   1: 8.060 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.008 ms/op
Iteration   1: 3.294 ±(99.9%) 0.006 ms/op
Iteration   2: 3.241 ±(99.9%) 0.010 ms/op
Iteration   3: 3.324 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.286 ±(99.9%) 0.765 ms/op [Average]
  (min, avg, max) = (3.241, 3.286, 3.324), stdev = 0.042
  CI (99.9%): [2.521, 4.052] (assumes normal distribution)


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
# Warmup Iteration   1: 10.854 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.008 ms/op
Iteration   1: 3.432 ±(99.9%) 0.009 ms/op
Iteration   2: 3.390 ±(99.9%) 0.008 ms/op
Iteration   3: 3.437 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.419 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (3.390, 3.419, 3.437), stdev = 0.026
  CI (99.9%): [2.947, 3.892] (assumes normal distribution)


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
# Warmup Iteration   1: 12.271 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.765 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.013 ms/op
Iteration   1: 3.938 ±(99.9%) 0.013 ms/op
Iteration   2: 3.920 ±(99.9%) 0.018 ms/op
Iteration   3: 3.883 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.913 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (3.883, 3.913, 3.938), stdev = 0.028
  CI (99.9%): [3.401, 4.426] (assumes normal distribution)


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
# Warmup Iteration   1: 8.861 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.010 ms/op
Iteration   1: 3.442 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.673 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  22.580 ms/op
                 createUser·p0.9999: 25.484 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  23.494 ms/op
                 createUser·p0.9999: 27.971 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   3: 3.468 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  19.163 ms/op
                 createUser·p0.9999: 27.846 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277139
  mean =      3.461 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10435 
    [ 2.500,  5.000) = 259126 
    [ 5.000,  7.500) = 6531 
    [ 7.500, 10.000) = 565 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 99 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     19.661 ms/op
     p(99.9900) =     27.666 ms/op
     p(99.9990) =     28.596 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 8.707 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.009 ms/op
Iteration   1: 3.320 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  15.837 ms/op
                 existUser·p0.9999: 23.167 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.668 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  13.418 ms/op
                 existUser·p0.9999: 24.785 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 3.307 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.713 ms/op
                 existUser·p0.999:  19.674 ms/op
                 existUser·p0.9999: 25.166 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292110
  mean =      3.285 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10899 
    [ 2.500,  5.000) = 276289 
    [ 5.000,  7.500) = 3830 
    [ 7.500, 10.000) = 579 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     13.610 ms/op
     p(99.9900) =     24.831 ms/op
     p(99.9990) =     26.880 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 9.613 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.012 ms/op
Iteration   1: 3.567 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   7.094 ms/op
                 getUser·p0.999:  10.928 ms/op
                 getUser·p0.9999: 24.707 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   2: 3.564 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  23.829 ms/op
                 getUser·p0.9999: 26.509 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   3: 3.560 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  21.561 ms/op
                 getUser·p0.9999: 31.523 ms/op
                 getUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269193
  mean =      3.564 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6824 
    [ 2.500,  5.000) = 249665 
    [ 5.000,  7.500) = 10750 
    [ 7.500, 10.000) = 1387 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     14.665 ms/op
     p(99.9900) =     30.293 ms/op
     p(99.9990) =     32.090 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 12.123 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.724 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.015 ms/op
Iteration   1: 4.128 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  21.874 ms/op
                 listUser·p0.9999: 25.289 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   2: 4.135 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  16.344 ms/op
                 listUser·p0.9999: 20.030 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 3.982 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235021
  mean =      4.081 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 225380 
    [ 5.000,  7.500) = 6834 
    [ 7.500, 10.000) = 1797 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 296 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     16.597 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     25.864 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.206 ± 4.790  ops/ms
ClientPb.existUser                       thrpt       3   9.559 ± 2.674  ops/ms
ClientPb.getUser                         thrpt       3   9.298 ± 5.352  ops/ms
ClientPb.listUser                        thrpt       3   7.981 ± 3.272  ops/ms
ClientPb.createUser                       avgt       3   3.381 ± 0.694   ms/op
ClientPb.existUser                        avgt       3   3.286 ± 0.765   ms/op
ClientPb.getUser                          avgt       3   3.419 ± 0.473   ms/op
ClientPb.listUser                         avgt       3   3.913 ± 0.512   ms/op
ClientPb.createUser                     sample  277139   3.461 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.124           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.250           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.661           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.666           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.770           ms/op
ClientPb.existUser                      sample  292110   3.285 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.830           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.610           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.831           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  269193   3.564 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.225           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.817           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.102           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.665           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.293           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  235021   4.081 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.848           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.597           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.790           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.051           ms/op
