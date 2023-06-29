# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.982 ops/ms
# Warmup Iteration   2: 4.531 ops/ms
# Warmup Iteration   3: 8.734 ops/ms
Iteration   1: 9.033 ops/ms
Iteration   2: 9.282 ops/ms
Iteration   3: 9.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.140 ±(99.9%) 2.340 ops/ms [Average]
  (min, avg, max) = (9.033, 9.140, 9.282), stdev = 0.128
  CI (99.9%): [6.799, 11.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.823 ops/ms
# Warmup Iteration   2: 8.587 ops/ms
# Warmup Iteration   3: 9.223 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 10.034 ops/ms
Iteration   3: 9.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.886 ±(99.9%) 2.746 ops/ms [Average]
  (min, avg, max) = (9.733, 9.886, 10.034), stdev = 0.151
  CI (99.9%): [7.141, 12.632] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.707 ops/ms
# Warmup Iteration   2: 8.468 ops/ms
# Warmup Iteration   3: 8.772 ops/ms
Iteration   1: 9.463 ops/ms
Iteration   2: 9.212 ops/ms
Iteration   3: 9.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.352 ±(99.9%) 2.341 ops/ms [Average]
  (min, avg, max) = (9.212, 9.352, 9.463), stdev = 0.128
  CI (99.9%): [7.011, 11.693] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.613 ops/ms
# Warmup Iteration   2: 6.578 ops/ms
# Warmup Iteration   3: 7.672 ops/ms
Iteration   1: 7.985 ops/ms
Iteration   2: 8.073 ops/ms
Iteration   3: 7.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.009 ±(99.9%) 1.018 ops/ms [Average]
  (min, avg, max) = (7.969, 8.009, 8.073), stdev = 0.056
  CI (99.9%): [6.990, 9.027] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.516 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.009 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.008 ms/op
Iteration   1: 3.380 ±(99.9%) 0.010 ms/op
Iteration   2: 3.484 ±(99.9%) 0.004 ms/op
Iteration   3: 3.439 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.434 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (3.380, 3.434, 3.484), stdev = 0.052
  CI (99.9%): [2.480, 4.388] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.239 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.009 ms/op
Iteration   1: 3.346 ±(99.9%) 0.007 ms/op
Iteration   2: 3.355 ±(99.9%) 0.005 ms/op
Iteration   3: 3.281 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.327 ±(99.9%) 0.737 ms/op [Average]
  (min, avg, max) = (3.281, 3.327, 3.355), stdev = 0.040
  CI (99.9%): [2.590, 4.065] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.692 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.549 ±(99.9%) 0.005 ms/op
Iteration   1: 3.455 ±(99.9%) 0.003 ms/op
Iteration   2: 3.382 ±(99.9%) 0.005 ms/op
Iteration   3: 3.393 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.410 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (3.382, 3.410, 3.455), stdev = 0.039
  CI (99.9%): [2.695, 4.125] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 12.466 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.013 ms/op
Iteration   1: 4.084 ±(99.9%) 0.010 ms/op
Iteration   2: 3.953 ±(99.9%) 0.013 ms/op
Iteration   3: 3.970 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.003 ±(99.9%) 1.300 ms/op [Average]
  (min, avg, max) = (3.953, 4.003, 4.084), stdev = 0.071
  CI (99.9%): [2.703, 5.302] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.499 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.184 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.014 ms/op
Iteration   1: 3.384 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  23.593 ms/op
                 createUser·p0.9999: 35.556 ms/op
                 createUser·p1.00:   36.897 ms/op

Iteration   2: 3.412 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  22.211 ms/op
                 createUser·p0.9999: 25.481 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.388 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.784 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  22.388 ms/op
                 createUser·p0.9999: 29.691 ms/op
                 createUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282880
  mean =      3.395 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5929 
    [ 2.500,  5.000) = 272080 
    [ 5.000,  7.500) = 4084 
    [ 7.500, 10.000) = 417 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 150 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     22.286 ms/op
     p(99.9900) =     33.582 ms/op
     p(99.9990) =     36.777 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.558 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.009 ms/op
Iteration   1: 3.272 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.701 ms/op
                 existUser·p0.999:  10.738 ms/op
                 existUser·p0.9999: 23.109 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   2: 3.301 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.819 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  13.466 ms/op
                 existUser·p0.9999: 25.603 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  9.224 ms/op
                 existUser·p0.9999: 28.311 ms/op
                 existUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288552
  mean =      3.329 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8643 
    [ 2.500,  5.000) = 274754 
    [ 5.000,  7.500) = 4333 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     11.837 ms/op
     p(99.9900) =     27.057 ms/op
     p(99.9990) =     28.982 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.399 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.011 ms/op
Iteration   1: 3.554 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.232 ms/op
                 getUser·p0.999:  21.972 ms/op
                 getUser·p0.9999: 32.931 ms/op
                 getUser·p1.00:   33.194 ms/op

Iteration   2: 3.425 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.721 ms/op
                 getUser·p0.999:  22.535 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   27.525 ms/op

Iteration   3: 3.448 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  19.760 ms/op
                 getUser·p0.9999: 27.460 ms/op
                 getUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276289
  mean =      3.475 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4661 
    [ 2.500,  5.000) = 263774 
    [ 5.000,  7.500) = 6758 
    [ 7.500, 10.000) = 711 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.207 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     20.372 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     33.136 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.524 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.517 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.013 ms/op
Iteration   1: 3.981 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.062 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.198 ms/op
                 listUser·p0.999:  21.813 ms/op
                 listUser·p0.9999: 31.060 ms/op
                 listUser·p1.00:   32.702 ms/op

Iteration   2: 4.012 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  17.957 ms/op
                 listUser·p0.9999: 21.137 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 4.064 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 17.011 ms/op
                 listUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238972
  mean =      4.019 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 228849 
    [ 5.000,  7.500) = 8073 
    [ 7.500, 10.000) = 1241 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.062 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     29.232 ms/op
     p(99.9990) =     32.320 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.140 ± 2.340  ops/ms
ClientPb.existUser                       thrpt       3   9.886 ± 2.746  ops/ms
ClientPb.getUser                         thrpt       3   9.352 ± 2.341  ops/ms
ClientPb.listUser                        thrpt       3   8.009 ± 1.018  ops/ms
ClientPb.createUser                       avgt       3   3.434 ± 0.954   ms/op
ClientPb.existUser                        avgt       3   3.327 ± 0.737   ms/op
ClientPb.getUser                          avgt       3   3.410 ± 0.715   ms/op
ClientPb.listUser                         avgt       3   4.003 ± 1.300   ms/op
ClientPb.createUser                     sample  282880   3.395 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.071           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.286           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.582           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.897           ms/op
ClientPb.existUser                      sample  288552   3.329 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.159           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.652           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.837           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.057           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.884           ms/op
ClientPb.getUser                        sample  276289   3.475 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.566           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.372           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.490           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.194           ms/op
ClientPb.listUser                       sample  238972   4.019 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.062           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.866           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.957           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.232           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.702           ms/op
