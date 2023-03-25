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
# Warmup Iteration   1: 2.215 ops/ms
# Warmup Iteration   2: 5.668 ops/ms
# Warmup Iteration   3: 8.876 ops/ms
Iteration   1: 9.048 ops/ms
Iteration   2: 9.431 ops/ms
Iteration   3: 9.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.220 ±(99.9%) 3.548 ops/ms [Average]
  (min, avg, max) = (9.048, 9.220, 9.431), stdev = 0.194
  CI (99.9%): [5.672, 12.768] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.162 ops/ms
# Warmup Iteration   2: 8.820 ops/ms
# Warmup Iteration   3: 9.379 ops/ms
Iteration   1: 9.666 ops/ms
Iteration   2: 9.572 ops/ms
Iteration   3: 9.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.700 ±(99.9%) 2.693 ops/ms [Average]
  (min, avg, max) = (9.572, 9.700, 9.862), stdev = 0.148
  CI (99.9%): [7.007, 12.393] (assumes normal distribution)


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
# Warmup Iteration   1: 2.816 ops/ms
# Warmup Iteration   2: 7.750 ops/ms
# Warmup Iteration   3: 8.764 ops/ms
Iteration   1: 8.651 ops/ms
Iteration   2: 9.049 ops/ms
Iteration   3: 9.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.069 ±(99.9%) 7.804 ops/ms [Average]
  (min, avg, max) = (8.651, 9.069, 9.506), stdev = 0.428
  CI (99.9%): [1.265, 16.873] (assumes normal distribution)


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
# Warmup Iteration   1: 3.056 ops/ms
# Warmup Iteration   2: 7.292 ops/ms
# Warmup Iteration   3: 7.758 ops/ms
Iteration   1: 8.224 ops/ms
Iteration   2: 8.026 ops/ms
Iteration   3: 7.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.035 ±(99.9%) 3.369 ops/ms [Average]
  (min, avg, max) = (7.855, 8.035, 8.224), stdev = 0.185
  CI (99.9%): [4.666, 11.404] (assumes normal distribution)


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
# Warmup Iteration   1: 11.034 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.005 ms/op
Iteration   1: 3.404 ±(99.9%) 0.011 ms/op
Iteration   2: 3.320 ±(99.9%) 0.011 ms/op
Iteration   3: 3.366 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.363 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (3.320, 3.363, 3.404), stdev = 0.042
  CI (99.9%): [2.595, 4.132] (assumes normal distribution)


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
# Warmup Iteration   1: 8.480 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.006 ms/op
Iteration   1: 3.262 ±(99.9%) 0.004 ms/op
Iteration   2: 3.309 ±(99.9%) 0.008 ms/op
Iteration   3: 3.284 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.285 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (3.262, 3.285, 3.309), stdev = 0.024
  CI (99.9%): [2.850, 3.720] (assumes normal distribution)


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
# Warmup Iteration   1: 10.205 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.003 ms/op
Iteration   1: 3.492 ±(99.9%) 0.008 ms/op
Iteration   2: 3.516 ±(99.9%) 0.008 ms/op
Iteration   3: 3.652 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.553 ±(99.9%) 1.572 ms/op [Average]
  (min, avg, max) = (3.492, 3.553, 3.652), stdev = 0.086
  CI (99.9%): [1.981, 5.126] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.802 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.268 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.010 ms/op
Iteration   1: 4.042 ±(99.9%) 0.007 ms/op
Iteration   2: 3.992 ±(99.9%) 0.008 ms/op
Iteration   3: 3.925 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.986 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (3.925, 3.986, 4.042), stdev = 0.059
  CI (99.9%): [2.912, 5.060] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.294 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.009 ms/op
Iteration   1: 3.696 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   5.767 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  19.249 ms/op
                 createUser·p0.9999: 26.586 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 3.291 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.465 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  19.342 ms/op
                 createUser·p0.9999: 22.262 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   3: 3.471 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.673 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  19.128 ms/op
                 createUser·p0.9999: 36.110 ms/op
                 createUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275837
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15187 
    [ 2.500,  5.000) = 250888 
    [ 5.000,  7.500) = 8647 
    [ 7.500, 10.000) = 739 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 167 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     19.142 ms/op
     p(99.9900) =     33.437 ms/op
     p(99.9990) =     36.370 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.017 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.610 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.009 ms/op
Iteration   1: 3.343 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  17.898 ms/op
                 existUser·p0.9999: 21.299 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.739 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 22.249 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   3: 3.299 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.475 ms/op
                 existUser·p0.999:  12.097 ms/op
                 existUser·p0.9999: 24.979 ms/op
                 existUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293174
  mean =      3.274 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9273 
    [ 2.500,  5.000) = 278938 
    [ 5.000,  7.500) = 4166 
    [ 7.500, 10.000) = 405 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     11.826 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 8.866 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.009 ms/op
Iteration   1: 3.419 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  19.806 ms/op
                 getUser·p0.9999: 25.802 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   2: 3.487 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  21.716 ms/op
                 getUser·p0.9999: 34.013 ms/op
                 getUser·p1.00:   35.127 ms/op

Iteration   3: 3.353 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  18.090 ms/op
                 getUser·p0.9999: 26.313 ms/op
                 getUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280473
  mean =      3.419 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1278 
    [ 2.500,  5.000) = 269280 
    [ 5.000,  7.500) = 8527 
    [ 7.500, 10.000) = 869 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     19.811 ms/op
     p(99.9900) =     31.423 ms/op
     p(99.9990) =     34.747 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 11.731 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.494 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.013 ms/op
Iteration   1: 4.074 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.927 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.882 ms/op
                 listUser·p0.999:  21.349 ms/op
                 listUser·p0.9999: 29.675 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   2: 4.138 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  14.545 ms/op
                 listUser·p0.9999: 16.852 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   3: 3.981 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  15.069 ms/op
                 listUser·p0.9999: 16.777 ms/op
                 listUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236035
  mean =      4.063 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 226271 
    [ 5.000,  7.500) = 7266 
    [ 7.500, 10.000) = 1598 
    [10.000, 12.500) = 365 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.927 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     27.702 ms/op
     p(99.9990) =     30.409 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.220 ± 3.548  ops/ms
ClientPb.existUser                       thrpt       3   9.700 ± 2.693  ops/ms
ClientPb.getUser                         thrpt       3   9.069 ± 7.804  ops/ms
ClientPb.listUser                        thrpt       3   8.035 ± 3.369  ops/ms
ClientPb.createUser                       avgt       3   3.363 ± 0.769   ms/op
ClientPb.existUser                        avgt       3   3.285 ± 0.435   ms/op
ClientPb.getUser                          avgt       3   3.553 ± 1.572   ms/op
ClientPb.listUser                         avgt       3   3.986 ± 1.074   ms/op
ClientPb.createUser                     sample  275837   3.479 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.673           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.914           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.142           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.437           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.766           ms/op
ClientPb.existUser                      sample  293174   3.274 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.991           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.497           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.826           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.658           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.035           ms/op
ClientPb.getUser                        sample  280473   3.419 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.077           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.811           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.423           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.127           ms/op
ClientPb.listUser                       sample  236035   4.063 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.927           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.466           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.702           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.326           ms/op
