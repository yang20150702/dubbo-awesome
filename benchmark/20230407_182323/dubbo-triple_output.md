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
# Warmup Iteration   1: 2.202 ops/ms
# Warmup Iteration   2: 5.980 ops/ms
# Warmup Iteration   3: 8.322 ops/ms
Iteration   1: 9.122 ops/ms
Iteration   2: 8.941 ops/ms
Iteration   3: 9.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.061 ±(99.9%) 1.891 ops/ms [Average]
  (min, avg, max) = (8.941, 9.061, 9.122), stdev = 0.104
  CI (99.9%): [7.170, 10.952] (assumes normal distribution)


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
# Warmup Iteration   1: 3.099 ops/ms
# Warmup Iteration   2: 8.986 ops/ms
# Warmup Iteration   3: 9.544 ops/ms
Iteration   1: 9.320 ops/ms
Iteration   2: 9.192 ops/ms
Iteration   3: 9.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.341 ±(99.9%) 2.916 ops/ms [Average]
  (min, avg, max) = (9.192, 9.341, 9.510), stdev = 0.160
  CI (99.9%): [6.424, 12.257] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.830 ops/ms
# Warmup Iteration   2: 8.106 ops/ms
# Warmup Iteration   3: 9.192 ops/ms
Iteration   1: 9.510 ops/ms
Iteration   2: 9.648 ops/ms
Iteration   3: 9.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.586 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (9.510, 9.586, 9.648), stdev = 0.070
  CI (99.9%): [8.313, 10.859] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.081 ops/ms
# Warmup Iteration   2: 7.247 ops/ms
# Warmup Iteration   3: 7.804 ops/ms
Iteration   1: 8.099 ops/ms
Iteration   2: 7.918 ops/ms
Iteration   3: 7.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.974 ±(99.9%) 1.974 ops/ms [Average]
  (min, avg, max) = (7.905, 7.974, 8.099), stdev = 0.108
  CI (99.9%): [6.000, 9.948] (assumes normal distribution)


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
# Warmup Iteration   1: 8.621 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.004 ms/op
Iteration   1: 3.330 ±(99.9%) 0.011 ms/op
Iteration   2: 3.459 ±(99.9%) 0.008 ms/op
Iteration   3: 3.276 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.355 ±(99.9%) 1.716 ms/op [Average]
  (min, avg, max) = (3.276, 3.355, 3.459), stdev = 0.094
  CI (99.9%): [1.638, 5.071] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.535 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.004 ms/op
Iteration   1: 3.190 ±(99.9%) 0.012 ms/op
Iteration   2: 3.130 ±(99.9%) 0.008 ms/op
Iteration   3: 3.241 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.187 ±(99.9%) 1.018 ms/op [Average]
  (min, avg, max) = (3.130, 3.187, 3.241), stdev = 0.056
  CI (99.9%): [2.169, 4.205] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.994 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.010 ms/op
Iteration   1: 3.367 ±(99.9%) 0.007 ms/op
Iteration   2: 3.410 ±(99.9%) 0.006 ms/op
Iteration   3: 3.391 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.389 ±(99.9%) 0.392 ms/op [Average]
  (min, avg, max) = (3.367, 3.389, 3.410), stdev = 0.022
  CI (99.9%): [2.997, 3.782] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 11.060 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.009 ms/op
Iteration   1: 3.899 ±(99.9%) 0.012 ms/op
Iteration   2: 3.973 ±(99.9%) 0.008 ms/op
Iteration   3: 3.936 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.936 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (3.899, 3.936, 3.973), stdev = 0.037
  CI (99.9%): [3.268, 4.604] (assumes normal distribution)


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
# Warmup Iteration   1: 9.114 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.009 ms/op
Iteration   1: 3.311 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  13.442 ms/op
                 createUser·p0.9999: 23.735 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 3.543 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.750 ms/op
                 createUser·p0.999:  20.906 ms/op
                 createUser·p0.9999: 24.510 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   3: 3.337 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  17.760 ms/op
                 createUser·p0.9999: 25.638 ms/op
                 createUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282754
  mean =      3.394 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6778 
    [ 2.500,  5.000) = 270089 
    [ 5.000,  7.500) = 4824 
    [ 7.500, 10.000) = 647 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     19.046 ms/op
     p(99.9900) =     24.731 ms/op
     p(99.9990) =     27.596 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 7.520 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.008 ms/op
Iteration   1: 3.256 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  10.758 ms/op
                 existUser·p0.9999: 23.342 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   2: 3.400 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.399 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  19.167 ms/op
                 existUser·p0.9999: 22.241 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   3: 3.291 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  15.729 ms/op
                 existUser·p0.9999: 24.683 ms/op
                 existUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289702
  mean =      3.314 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13479 
    [ 2.500,  5.000) = 270662 
    [ 5.000,  7.500) = 4627 
    [ 7.500, 10.000) = 532 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 161 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     23.463 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 9.189 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.012 ms/op
Iteration   1: 3.391 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  10.923 ms/op
                 getUser·p0.9999: 21.538 ms/op
                 getUser·p1.00:   22.905 ms/op

Iteration   2: 3.301 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  19.850 ms/op
                 getUser·p0.9999: 27.066 ms/op
                 getUser·p1.00:   30.933 ms/op

Iteration   3: 3.386 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  18.055 ms/op
                 getUser·p0.9999: 30.738 ms/op
                 getUser·p1.00:   42.205 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285632
  mean =      3.359 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 280377 
    [ 5.000, 10.000) = 4751 
    [10.000, 15.000) = 233 
    [15.000, 20.000) = 60 
    [20.000, 25.000) = 152 
    [25.000, 30.000) = 37 
    [30.000, 35.000) = 17 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     13.818 ms/op
     p(99.9900) =     27.838 ms/op
     p(99.9990) =     42.018 ms/op
     p(99.9999) =     42.205 ms/op
    p(100.0000) =     42.205 ms/op


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
# Warmup Iteration   1: 8.984 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.012 ms/op
Iteration   1: 4.132 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 25.199 ms/op
                 listUser·p1.00:   25.494 ms/op

Iteration   2: 4.052 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   8.110 ms/op
                 listUser·p0.999:  18.907 ms/op
                 listUser·p0.9999: 21.922 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   3: 3.852 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.561 ms/op
                 listUser·p0.9999: 19.323 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239493
  mean =      4.009 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 231407 
    [ 5.000,  7.500) = 5519 
    [ 7.500, 10.000) = 1627 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     23.758 ms/op
     p(99.9990) =     25.422 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.061 ± 1.891  ops/ms
ClientPb.existUser                       thrpt       3   9.341 ± 2.916  ops/ms
ClientPb.getUser                         thrpt       3   9.586 ± 1.273  ops/ms
ClientPb.listUser                        thrpt       3   7.974 ± 1.974  ops/ms
ClientPb.createUser                       avgt       3   3.355 ± 1.716   ms/op
ClientPb.existUser                        avgt       3   3.187 ± 1.018   ms/op
ClientPb.getUser                          avgt       3   3.389 ± 0.392   ms/op
ClientPb.listUser                         avgt       3   3.936 ± 0.668   ms/op
ClientPb.createUser                     sample  282754   3.394 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.939           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.046           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.731           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.754           ms/op
ClientPb.existUser                      sample  289702   3.314 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.286           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.170           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.729           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.463           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.456           ms/op
ClientPb.getUser                        sample  285632   3.359 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.046           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.818           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.838           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.205           ms/op
ClientPb.listUser                       sample  239493   4.009 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.671           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.186           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.758           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.494           ms/op
