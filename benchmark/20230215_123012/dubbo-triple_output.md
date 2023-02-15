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
# Warmup Iteration   1: 1.119 ops/ms
# Warmup Iteration   2: 2.611 ops/ms
# Warmup Iteration   3: 5.948 ops/ms
Iteration   1: 5.847 ops/ms
Iteration   2: 6.217 ops/ms
Iteration   3: 6.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.153 ±(99.9%) 5.090 ops/ms [Average]
  (min, avg, max) = (5.847, 6.153, 6.394), stdev = 0.279
  CI (99.9%): [1.063, 11.243] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.669 ops/ms
# Warmup Iteration   2: 4.758 ops/ms
# Warmup Iteration   3: 6.311 ops/ms
Iteration   1: 6.178 ops/ms
Iteration   2: 6.601 ops/ms
Iteration   3: 6.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.448 ±(99.9%) 4.265 ops/ms [Average]
  (min, avg, max) = (6.178, 6.448, 6.601), stdev = 0.234
  CI (99.9%): [2.182, 10.713] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.890 ops/ms
# Warmup Iteration   2: 5.019 ops/ms
# Warmup Iteration   3: 5.908 ops/ms
Iteration   1: 6.086 ops/ms
Iteration   2: 6.024 ops/ms
Iteration   3: 6.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.142 ±(99.9%) 2.833 ops/ms [Average]
  (min, avg, max) = (6.024, 6.142, 6.318), stdev = 0.155
  CI (99.9%): [3.310, 8.975] (assumes normal distribution)


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
# Warmup Iteration   1: 1.711 ops/ms
# Warmup Iteration   2: 4.318 ops/ms
# Warmup Iteration   3: 5.327 ops/ms
Iteration   1: 5.177 ops/ms
Iteration   2: 5.360 ops/ms
Iteration   3: 5.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.327 ±(99.9%) 2.478 ops/ms [Average]
  (min, avg, max) = (5.177, 5.327, 5.442), stdev = 0.136
  CI (99.9%): [2.848, 7.805] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 15.867 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.367 ±(99.9%) 0.014 ms/op
Iteration   1: 5.178 ±(99.9%) 0.012 ms/op
Iteration   2: 5.010 ±(99.9%) 0.008 ms/op
Iteration   3: 5.030 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.073 ±(99.9%) 1.682 ms/op [Average]
  (min, avg, max) = (5.010, 5.073, 5.178), stdev = 0.092
  CI (99.9%): [3.390, 6.755] (assumes normal distribution)


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
# Warmup Iteration   1: 14.530 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.753 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.645 ±(99.9%) 0.010 ms/op
Iteration   1: 4.403 ±(99.9%) 0.006 ms/op
Iteration   2: 4.268 ±(99.9%) 0.017 ms/op
Iteration   3: 4.387 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.353 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (4.268, 4.353, 4.403), stdev = 0.074
  CI (99.9%): [3.011, 5.695] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.224 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.363 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.857 ±(99.9%) 0.006 ms/op
Iteration   1: 4.738 ±(99.9%) 0.010 ms/op
Iteration   2: 5.001 ±(99.9%) 0.005 ms/op
Iteration   3: 4.989 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.909 ±(99.9%) 2.714 ms/op [Average]
  (min, avg, max) = (4.738, 4.909, 5.001), stdev = 0.149
  CI (99.9%): [2.195, 7.623] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.093 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.430 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.673 ±(99.9%) 0.015 ms/op
Iteration   1: 5.478 ±(99.9%) 0.019 ms/op
Iteration   2: 5.984 ±(99.9%) 0.017 ms/op
Iteration   3: 5.906 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.789 ±(99.9%) 4.967 ms/op [Average]
  (min, avg, max) = (5.478, 5.789, 5.984), stdev = 0.272
  CI (99.9%): [0.822, 10.757] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.147 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 5.814 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.180 ±(99.9%) 0.022 ms/op
Iteration   1: 4.472 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.091 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.767 ms/op
                 createUser·p0.99:   8.356 ms/op
                 createUser·p0.999:  23.691 ms/op
                 createUser·p0.9999: 33.549 ms/op
                 createUser·p1.00:   33.948 ms/op

Iteration   2: 4.655 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.126 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   6.349 ms/op
                 createUser·p0.99:   9.028 ms/op
                 createUser·p0.999:  16.008 ms/op
                 createUser·p0.9999: 27.616 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   3: 4.664 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.179 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   6.398 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  16.237 ms/op
                 createUser·p0.9999: 30.067 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 208873
  mean =      4.595 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 170633 
    [ 5.000,  7.500) = 33958 
    [ 7.500, 10.000) = 3251 
    [10.000, 12.500) = 579 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.091 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     22.618 ms/op
     p(99.9900) =     32.066 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 12.469 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.788 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.497 ±(99.9%) 0.013 ms/op
Iteration   1: 4.731 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.005 ms/op
                 existUser·p0.50:   4.456 ms/op
                 existUser·p0.90:   5.841 ms/op
                 existUser·p0.95:   6.521 ms/op
                 existUser·p0.99:   9.093 ms/op
                 existUser·p0.999:  19.898 ms/op
                 existUser·p0.9999: 28.876 ms/op
                 existUser·p1.00:   29.196 ms/op

Iteration   2: 4.255 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   4.149 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.267 ms/op
                 existUser·p0.99:   6.971 ms/op
                 existUser·p0.999:  11.795 ms/op
                 existUser·p0.9999: 27.213 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 4.493 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.048 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.439 ms/op
                 existUser·p0.95:   6.308 ms/op
                 existUser·p0.99:   8.509 ms/op
                 existUser·p0.999:  15.936 ms/op
                 existUser·p0.9999: 26.702 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 213971
  mean =      4.485 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 154 
    [ 2.500,  5.000) = 179028 
    [ 5.000,  7.500) = 31323 
    [ 7.500, 10.000) = 2532 
    [10.000, 12.500) = 545 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     15.779 ms/op
     p(99.9900) =     28.056 ms/op
     p(99.9990) =     29.056 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 15.355 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 6.121 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.961 ±(99.9%) 0.018 ms/op
Iteration   1: 4.928 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.224 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   5.997 ms/op
                 getUser·p0.95:   7.315 ms/op
                 getUser·p0.99:   10.324 ms/op
                 getUser·p0.999:  22.079 ms/op
                 getUser·p0.9999: 28.132 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   2: 4.998 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   4.760 ms/op
                 getUser·p0.90:   6.054 ms/op
                 getUser·p0.95:   6.816 ms/op
                 getUser·p0.99:   9.683 ms/op
                 getUser·p0.999:  22.873 ms/op
                 getUser·p0.9999: 33.246 ms/op
                 getUser·p1.00:   33.751 ms/op

Iteration   3: 5.048 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.462 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   5.964 ms/op
                 getUser·p0.95:   6.513 ms/op
                 getUser·p0.99:   8.716 ms/op
                 getUser·p0.999:  30.057 ms/op
                 getUser·p0.9999: 36.613 ms/op
                 getUser·p1.00:   38.404 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 192166
  mean =      4.991 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 124289 
    [ 5.000,  7.500) = 61429 
    [ 7.500, 10.000) = 4734 
    [10.000, 12.500) = 1093 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.005 ms/op
     p(95.0000) =      6.824 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     22.457 ms/op
     p(99.9900) =     35.703 ms/op
     p(99.9990) =     38.404 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


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
# Warmup Iteration   1: 16.695 ±(99.9%) 0.252 ms/op
# Warmup Iteration   2: 6.618 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.972 ±(99.9%) 0.023 ms/op
Iteration   1: 5.749 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.839 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   6.799 ms/op
                 listUser·p0.95:   8.217 ms/op
                 listUser·p0.99:   10.453 ms/op
                 listUser·p0.999:  24.642 ms/op
                 listUser·p0.9999: 28.504 ms/op
                 listUser·p1.00:   28.803 ms/op

Iteration   2: 5.593 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  23.834 ms/op
                 listUser·p0.9999: 28.798 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   3: 5.917 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   7.987 ms/op
                 listUser·p0.99:   10.699 ms/op
                 listUser·p0.999:  17.823 ms/op
                 listUser·p0.9999: 20.741 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 166820
  mean =      5.750 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 24714 
    [ 5.000,  7.500) = 132918 
    [ 7.500, 10.000) = 7161 
    [10.000, 12.500) = 1218 
    [12.500, 15.000) = 350 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.454 ms/op
     p(50.0000) =      5.489 ms/op
     p(90.0000) =      6.660 ms/op
     p(95.0000) =      7.692 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     22.523 ms/op
     p(99.9900) =     28.267 ms/op
     p(99.9990) =     30.507 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.153 ± 5.090  ops/ms
ClientPb.existUser                       thrpt       3   6.448 ± 4.265  ops/ms
ClientPb.getUser                         thrpt       3   6.142 ± 2.833  ops/ms
ClientPb.listUser                        thrpt       3   5.327 ± 2.478  ops/ms
ClientPb.createUser                       avgt       3   5.073 ± 1.682   ms/op
ClientPb.existUser                        avgt       3   4.353 ± 1.342   ms/op
ClientPb.getUser                          avgt       3   4.909 ± 2.714   ms/op
ClientPb.listUser                         avgt       3   5.789 ± 4.967   ms/op
ClientPb.createUser                     sample  208873   4.595 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.091           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.177           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.667           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.066           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.948           ms/op
ClientPb.existUser                      sample  213971   4.485 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.048           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.103           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.225           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.779           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.056           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.196           ms/op
ClientPb.getUser                        sample  192166   4.991 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.175           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.735           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.824           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.732           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.457           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.703           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.404           ms/op
ClientPb.listUser                       sample  166820   5.750 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.454           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.660           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.692           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.273           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.523           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.267           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.573           ms/op
