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
# Warmup Iteration   1: 2.277 ops/ms
# Warmup Iteration   2: 6.119 ops/ms
# Warmup Iteration   3: 8.461 ops/ms
Iteration   1: 8.999 ops/ms
Iteration   2: 8.792 ops/ms
Iteration   3: 8.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.928 ±(99.9%) 2.142 ops/ms [Average]
  (min, avg, max) = (8.792, 8.928, 8.999), stdev = 0.117
  CI (99.9%): [6.786, 11.070] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.981 ops/ms
# Warmup Iteration   2: 8.384 ops/ms
# Warmup Iteration   3: 9.317 ops/ms
Iteration   1: 10.233 ops/ms
Iteration   2: 10.493 ops/ms
Iteration   3: 10.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.267 ±(99.9%) 3.859 ops/ms [Average]
  (min, avg, max) = (10.074, 10.267, 10.493), stdev = 0.212
  CI (99.9%): [6.408, 14.125] (assumes normal distribution)


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
# Warmup Iteration   1: 2.954 ops/ms
# Warmup Iteration   2: 8.329 ops/ms
# Warmup Iteration   3: 9.303 ops/ms
Iteration   1: 9.120 ops/ms
Iteration   2: 9.174 ops/ms
Iteration   3: 9.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.269 ±(99.9%) 3.895 ops/ms [Average]
  (min, avg, max) = (9.120, 9.269, 9.514), stdev = 0.213
  CI (99.9%): [5.375, 13.164] (assumes normal distribution)


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
# Warmup Iteration   1: 3.006 ops/ms
# Warmup Iteration   2: 7.702 ops/ms
# Warmup Iteration   3: 8.681 ops/ms
Iteration   1: 8.333 ops/ms
Iteration   2: 8.009 ops/ms
Iteration   3: 7.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.112 ±(99.9%) 3.493 ops/ms [Average]
  (min, avg, max) = (7.994, 8.112, 8.333), stdev = 0.191
  CI (99.9%): [4.619, 11.605] (assumes normal distribution)


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
# Warmup Iteration   1: 10.156 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.005 ms/op
Iteration   1: 3.499 ±(99.9%) 0.010 ms/op
Iteration   2: 3.448 ±(99.9%) 0.007 ms/op
Iteration   3: 3.390 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.446 ±(99.9%) 0.989 ms/op [Average]
  (min, avg, max) = (3.390, 3.446, 3.499), stdev = 0.054
  CI (99.9%): [2.456, 4.435] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.652 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.004 ms/op
Iteration   1: 3.237 ±(99.9%) 0.006 ms/op
Iteration   2: 3.135 ±(99.9%) 0.009 ms/op
Iteration   3: 3.273 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.215 ±(99.9%) 1.310 ms/op [Average]
  (min, avg, max) = (3.135, 3.215, 3.273), stdev = 0.072
  CI (99.9%): [1.905, 4.525] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.959 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 7.980 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 7.151 ±(99.9%) 0.022 ms/op
Iteration   1: 3.697 ±(99.9%) 0.010 ms/op
Iteration   2: 3.338 ±(99.9%) 0.004 ms/op
Iteration   3: 6.655 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.563 ±(99.9%) 33.210 ms/op [Average]
  (min, avg, max) = (3.338, 4.563, 6.655), stdev = 1.820
  CI (99.9%): [≈ 0, 37.774] (assumes normal distribution)


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
# Warmup Iteration   1: 17.969 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 11.660 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 9.468 ±(99.9%) 0.030 ms/op
Iteration   1: 4.915 ±(99.9%) 0.012 ms/op
Iteration   2: 4.063 ±(99.9%) 0.010 ms/op
Iteration   3: 4.040 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.339 ±(99.9%) 9.097 ms/op [Average]
  (min, avg, max) = (4.040, 4.339, 4.915), stdev = 0.499
  CI (99.9%): [≈ 0, 13.437] (assumes normal distribution)


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
# Warmup Iteration   1: 11.615 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.016 ms/op
Iteration   1: 3.608 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   6.939 ms/op
                 createUser·p0.999:  20.949 ms/op
                 createUser·p0.9999: 33.100 ms/op
                 createUser·p1.00:   33.522 ms/op

Iteration   2: 3.510 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  22.668 ms/op
                 createUser·p0.9999: 25.781 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   3: 3.600 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  22.255 ms/op
                 createUser·p0.9999: 40.829 ms/op
                 createUser·p1.00:   42.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268557
  mean =      3.572 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 257842 
    [ 5.000, 10.000) = 10151 
    [10.000, 15.000) = 239 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 167 
    [25.000, 30.000) = 87 
    [30.000, 35.000) = 34 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     21.929 ms/op
     p(99.9900) =     39.387 ms/op
     p(99.9990) =     42.153 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


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
# Warmup Iteration   1: 9.186 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.009 ms/op
Iteration   1: 3.343 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  23.049 ms/op
                 existUser·p0.9999: 26.327 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   2: 3.414 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  10.043 ms/op
                 existUser·p0.9999: 32.449 ms/op
                 existUser·p1.00:   33.260 ms/op

Iteration   3: 3.365 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.686 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  24.022 ms/op
                 existUser·p0.9999: 50.693 ms/op
                 existUser·p1.00:   52.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284222
  mean =      3.374 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 277764 
    [ 5.000, 10.000) = 6037 
    [10.000, 15.000) = 163 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 90 
    [25.000, 30.000) = 102 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     13.988 ms/op
     p(99.9900) =     49.780 ms/op
     p(99.9990) =     51.252 ms/op
     p(99.9999) =     52.036 ms/op
    p(100.0000) =     52.036 ms/op


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
# Warmup Iteration   1: 9.799 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.011 ms/op
Iteration   1: 3.409 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  24.445 ms/op
                 getUser·p0.9999: 31.969 ms/op
                 getUser·p1.00:   32.375 ms/op

Iteration   2: 3.526 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.322 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 27.424 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   3: 3.545 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.479 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  21.720 ms/op
                 getUser·p0.9999: 28.900 ms/op
                 getUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274796
  mean =      3.492 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4453 
    [ 2.500,  5.000) = 259316 
    [ 5.000,  7.500) = 9917 
    [ 7.500, 10.000) = 720 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 117 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     22.066 ms/op
     p(99.9900) =     29.004 ms/op
     p(99.9990) =     32.162 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 10.606 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.761 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.014 ms/op
Iteration   1: 3.859 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.985 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  20.873 ms/op
                 listUser·p0.9999: 23.092 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   2: 3.940 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  18.055 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 3.892 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 22.938 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246428
  mean =      3.896 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 239280 
    [ 5.000,  7.500) = 5315 
    [ 7.500, 10.000) = 991 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     24.954 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.928 ±  2.142  ops/ms
ClientPb.existUser                       thrpt       3  10.267 ±  3.859  ops/ms
ClientPb.getUser                         thrpt       3   9.269 ±  3.895  ops/ms
ClientPb.listUser                        thrpt       3   8.112 ±  3.493  ops/ms
ClientPb.createUser                       avgt       3   3.446 ±  0.989   ms/op
ClientPb.existUser                        avgt       3   3.215 ±  1.310   ms/op
ClientPb.getUser                          avgt       3   4.563 ± 33.210   ms/op
ClientPb.listUser                         avgt       3   4.339 ±  9.097   ms/op
ClientPb.createUser                     sample  268557   3.572 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.202            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.157            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.841            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.701            ms/op
ClientPb.createUser:createUser·p0.999   sample          21.929            ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.387            ms/op
ClientPb.createUser:createUser·p1.00    sample          42.533            ms/op
ClientPb.existUser                      sample  284222   3.374 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.294            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.813            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.194            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.849            ms/op
ClientPb.existUser:existUser·p0.999     sample          13.988            ms/op
ClientPb.existUser:existUser·p0.9999    sample          49.780            ms/op
ClientPb.existUser:existUser·p1.00      sample          52.036            ms/op
ClientPb.getUser                        sample  274796   3.492 ±  0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.255            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.006            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.250            ms/op
ClientPb.getUser:getUser·p0.999         sample          22.066            ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.004            ms/op
ClientPb.getUser:getUser·p1.00          sample          32.375            ms/op
ClientPb.listUser                       sample  246428   3.896 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.778            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.178            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547            ms/op
ClientPb.listUser:listUser·p0.99        sample           6.840            ms/op
ClientPb.listUser:listUser·p0.999       sample          18.055            ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.938            ms/op
ClientPb.listUser:listUser·p1.00        sample          26.444            ms/op
