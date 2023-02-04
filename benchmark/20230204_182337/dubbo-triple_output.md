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
# Warmup Iteration   1: 2.006 ops/ms
# Warmup Iteration   2: 5.258 ops/ms
# Warmup Iteration   3: 8.386 ops/ms
Iteration   1: 8.892 ops/ms
Iteration   2: 8.814 ops/ms
Iteration   3: 9.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.982 ±(99.9%) 4.125 ops/ms [Average]
  (min, avg, max) = (8.814, 8.982, 9.239), stdev = 0.226
  CI (99.9%): [4.857, 13.106] (assumes normal distribution)


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
# Warmup Iteration   1: 2.790 ops/ms
# Warmup Iteration   2: 8.270 ops/ms
# Warmup Iteration   3: 9.486 ops/ms
Iteration   1: 9.289 ops/ms
Iteration   2: 9.796 ops/ms
Iteration   3: 10.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.705 ±(99.9%) 6.899 ops/ms [Average]
  (min, avg, max) = (9.289, 9.705, 10.029), stdev = 0.378
  CI (99.9%): [2.806, 16.603] (assumes normal distribution)


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
# Warmup Iteration   1: 3.020 ops/ms
# Warmup Iteration   2: 8.593 ops/ms
# Warmup Iteration   3: 9.070 ops/ms
Iteration   1: 9.302 ops/ms
Iteration   2: 9.472 ops/ms
Iteration   3: 9.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.383 ±(99.9%) 1.554 ops/ms [Average]
  (min, avg, max) = (9.302, 9.383, 9.472), stdev = 0.085
  CI (99.9%): [7.829, 10.938] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.518 ops/ms
# Warmup Iteration   2: 7.262 ops/ms
# Warmup Iteration   3: 8.071 ops/ms
Iteration   1: 8.022 ops/ms
Iteration   2: 7.980 ops/ms
Iteration   3: 7.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.986 ±(99.9%) 0.594 ops/ms [Average]
  (min, avg, max) = (7.957, 7.986, 8.022), stdev = 0.033
  CI (99.9%): [7.393, 8.580] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.820 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.007 ms/op
Iteration   1: 3.452 ±(99.9%) 0.009 ms/op
Iteration   2: 3.416 ±(99.9%) 0.005 ms/op
Iteration   3: 3.417 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.428 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (3.416, 3.428, 3.452), stdev = 0.020
  CI (99.9%): [3.055, 3.802] (assumes normal distribution)


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
# Warmup Iteration   1: 9.638 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.002 ms/op
Iteration   1: 3.267 ±(99.9%) 0.002 ms/op
Iteration   2: 3.390 ±(99.9%) 0.008 ms/op
Iteration   3: 3.279 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.312 ±(99.9%) 1.245 ms/op [Average]
  (min, avg, max) = (3.267, 3.312, 3.390), stdev = 0.068
  CI (99.9%): [2.067, 4.557] (assumes normal distribution)


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
# Warmup Iteration   1: 10.593 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.007 ms/op
Iteration   1: 3.537 ±(99.9%) 0.003 ms/op
Iteration   2: 3.380 ±(99.9%) 0.007 ms/op
Iteration   3: 3.383 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.434 ±(99.9%) 1.634 ms/op [Average]
  (min, avg, max) = (3.380, 3.434, 3.537), stdev = 0.090
  CI (99.9%): [1.800, 5.068] (assumes normal distribution)


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
# Warmup Iteration   1: 10.263 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.007 ms/op
Iteration   1: 4.045 ±(99.9%) 0.010 ms/op
Iteration   2: 3.995 ±(99.9%) 0.011 ms/op
Iteration   3: 3.976 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.005 ±(99.9%) 0.652 ms/op [Average]
  (min, avg, max) = (3.976, 4.005, 4.045), stdev = 0.036
  CI (99.9%): [3.353, 4.657] (assumes normal distribution)


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
# Warmup Iteration   1: 10.095 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.011 ms/op
Iteration   1: 3.644 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.513 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   6.348 ms/op
                 createUser·p0.99:   7.586 ms/op
                 createUser·p0.999:  21.332 ms/op
                 createUser·p0.9999: 23.338 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 3.521 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  24.543 ms/op
                 createUser·p0.9999: 29.357 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   3: 3.407 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  18.747 ms/op
                 createUser·p0.9999: 26.922 ms/op
                 createUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272525
  mean =      3.521 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5279 
    [ 2.500,  5.000) = 255838 
    [ 5.000,  7.500) = 9835 
    [ 7.500, 10.000) = 1003 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 94 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.544 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     19.873 ms/op
     p(99.9900) =     28.434 ms/op
     p(99.9990) =     29.673 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 9.707 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.010 ms/op
Iteration   1: 3.343 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.714 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  20.080 ms/op
                 existUser·p0.9999: 22.635 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   2: 3.354 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.751 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  7.890 ms/op
                 existUser·p0.9999: 23.772 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   3: 3.617 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   6.513 ms/op
                 existUser·p0.99:   8.438 ms/op
                 existUser·p0.999:  19.088 ms/op
                 existUser·p0.9999: 27.591 ms/op
                 existUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279587
  mean =      3.433 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17945 
    [ 2.500,  5.000) = 250483 
    [ 5.000,  7.500) = 8781 
    [ 7.500, 10.000) = 1869 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.683 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     16.254 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     28.023 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 9.088 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.011 ms/op
Iteration   1: 3.527 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  20.875 ms/op
                 getUser·p0.9999: 27.918 ms/op
                 getUser·p1.00:   28.770 ms/op

Iteration   2: 3.353 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.554 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.986 ms/op
                 getUser·p0.999:  23.095 ms/op
                 getUser·p0.9999: 26.965 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   3: 3.519 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.168 ms/op
                 getUser·p0.999:  21.240 ms/op
                 getUser·p0.9999: 28.833 ms/op
                 getUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277177
  mean =      3.464 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3898 
    [ 2.500,  5.000) = 266068 
    [ 5.000,  7.500) = 5949 
    [ 7.500, 10.000) = 866 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 90 

  Percentiles, ms/op:
      p(0.0000) =      1.554 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     21.031 ms/op
     p(99.9900) =     28.288 ms/op
     p(99.9990) =     29.622 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 12.115 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.861 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.015 ms/op
Iteration   1: 4.064 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  21.837 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   2: 4.168 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  20.354 ms/op
                 listUser·p0.9999: 23.233 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 4.076 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  16.450 ms/op
                 listUser·p0.9999: 18.201 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234139
  mean =      4.102 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 223927 
    [ 5.000,  7.500) = 7702 
    [ 7.500, 10.000) = 1737 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.632 ms/op
     p(99.9000) =     18.013 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     24.303 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.982 ± 4.125  ops/ms
ClientPb.existUser                       thrpt       3   9.705 ± 6.899  ops/ms
ClientPb.getUser                         thrpt       3   9.383 ± 1.554  ops/ms
ClientPb.listUser                        thrpt       3   7.986 ± 0.594  ops/ms
ClientPb.createUser                       avgt       3   3.428 ± 0.374   ms/op
ClientPb.existUser                        avgt       3   3.312 ± 1.245   ms/op
ClientPb.getUser                          avgt       3   3.434 ± 1.634   ms/op
ClientPb.listUser                         avgt       3   4.005 ± 0.652   ms/op
ClientPb.createUser                     sample  272525   3.521 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.745           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.544           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.078           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.873           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.434           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.884           ms/op
ClientPb.existUser                      sample  279587   3.433 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.683           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.334           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.340           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.254           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.068           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.082           ms/op
ClientPb.getUser                        sample  277177   3.464 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.554           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.031           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.288           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.622           ms/op
ClientPb.listUser                       sample  234139   4.102 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.085           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.866           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.632           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.013           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.331           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.510           ms/op
