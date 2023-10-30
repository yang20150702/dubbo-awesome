# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.878 ops/ms
# Warmup Iteration   2: 5.350 ops/ms
# Warmup Iteration   3: 8.491 ops/ms
Iteration   1: 9.312 ops/ms
Iteration   2: 9.058 ops/ms
Iteration   3: 9.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.127 ±(99.9%) 2.957 ops/ms [Average]
  (min, avg, max) = (9.011, 9.127, 9.312), stdev = 0.162
  CI (99.9%): [6.170, 12.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.806 ops/ms
# Warmup Iteration   2: 8.784 ops/ms
# Warmup Iteration   3: 9.333 ops/ms
Iteration   1: 9.601 ops/ms
Iteration   2: 9.325 ops/ms
Iteration   3: 9.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.498 ±(99.9%) 2.750 ops/ms [Average]
  (min, avg, max) = (9.325, 9.498, 9.601), stdev = 0.151
  CI (99.9%): [6.747, 12.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.063 ops/ms
# Warmup Iteration   2: 8.638 ops/ms
# Warmup Iteration   3: 9.033 ops/ms
Iteration   1: 9.050 ops/ms
Iteration   2: 9.051 ops/ms
Iteration   3: 9.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.132 ±(99.9%) 2.571 ops/ms [Average]
  (min, avg, max) = (9.050, 9.132, 9.295), stdev = 0.141
  CI (99.9%): [6.562, 11.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 3.158 ops/ms
# Warmup Iteration   2: 7.360 ops/ms
# Warmup Iteration   3: 7.904 ops/ms
Iteration   1: 7.764 ops/ms
Iteration   2: 7.829 ops/ms
Iteration   3: 7.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.781 ±(99.9%) 0.762 ops/ms [Average]
  (min, avg, max) = (7.752, 7.781, 7.829), stdev = 0.042
  CI (99.9%): [7.019, 8.544] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.767 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.721 ±(99.9%) 0.004 ms/op
Iteration   1: 3.494 ±(99.9%) 0.005 ms/op
Iteration   2: 3.538 ±(99.9%) 0.004 ms/op
Iteration   3: 3.547 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.527 ±(99.9%) 0.517 ms/op [Average]
  (min, avg, max) = (3.494, 3.527, 3.547), stdev = 0.028
  CI (99.9%): [3.010, 4.043] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.191 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.004 ms/op
Iteration   1: 3.420 ±(99.9%) 0.004 ms/op
Iteration   2: 3.315 ±(99.9%) 0.003 ms/op
Iteration   3: 3.414 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.383 ±(99.9%) 1.073 ms/op [Average]
  (min, avg, max) = (3.315, 3.383, 3.420), stdev = 0.059
  CI (99.9%): [2.310, 4.455] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.432 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.004 ms/op
Iteration   1: 3.560 ±(99.9%) 0.005 ms/op
Iteration   2: 3.439 ±(99.9%) 0.004 ms/op
Iteration   3: 3.456 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.485 ±(99.9%) 1.201 ms/op [Average]
  (min, avg, max) = (3.439, 3.485, 3.560), stdev = 0.066
  CI (99.9%): [2.284, 4.686] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 12.449 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.492 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.004 ms/op
Iteration   1: 4.181 ±(99.9%) 0.005 ms/op
Iteration   2: 4.181 ±(99.9%) 0.004 ms/op
Iteration   3: 4.176 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.179 ±(99.9%) 0.051 ms/op [Average]
  (min, avg, max) = (4.176, 4.179, 4.181), stdev = 0.003
  CI (99.9%): [4.128, 4.230] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.429 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.736 ±(99.9%) 0.013 ms/op
Iteration   1: 3.589 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.381 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  19.625 ms/op
                 createUser·p0.9999: 26.348 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   2: 3.523 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  21.935 ms/op
                 createUser·p0.9999: 24.576 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 3.603 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 26.480 ms/op
                 createUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268724
  mean =      3.571 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2670 
    [ 2.500,  5.000) = 260337 
    [ 5.000,  7.500) = 4737 
    [ 7.500, 10.000) = 392 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      0.381 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     27.130 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.978 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.009 ms/op
Iteration   1: 3.330 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  19.721 ms/op
                 existUser·p0.9999: 23.246 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   2: 3.409 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   5.809 ms/op
                 existUser·p0.999:  21.458 ms/op
                 existUser·p0.9999: 23.986 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   3: 3.429 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  11.525 ms/op
                 existUser·p0.9999: 25.463 ms/op
                 existUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283011
  mean =      3.389 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4513 
    [ 2.500,  5.000) = 273239 
    [ 5.000,  7.500) = 4414 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     24.042 ms/op
     p(99.9990) =     26.264 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.323 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.011 ms/op
Iteration   1: 3.582 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  18.895 ms/op
                 getUser·p0.9999: 22.383 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   2: 3.399 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  19.825 ms/op
                 getUser·p0.9999: 23.907 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   3: 3.478 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.802 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  16.877 ms/op
                 getUser·p0.9999: 24.471 ms/op
                 getUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275465
  mean =      3.485 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1483 
    [ 2.500,  5.000) = 268305 
    [ 5.000,  7.500) = 4468 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     17.839 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     24.862 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.700 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.375 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.271 ±(99.9%) 0.012 ms/op
Iteration   1: 4.130 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  21.253 ms/op
                 listUser·p0.9999: 24.200 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   2: 4.200 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  15.367 ms/op
                 listUser·p0.9999: 20.530 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   3: 4.089 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.589 ms/op
                 listUser·p0.9999: 16.947 ms/op
                 listUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231695
  mean =      4.139 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 222077 
    [ 5.000,  7.500) = 7581 
    [ 7.500, 10.000) = 1028 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 382 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     16.099 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     24.865 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.127 ± 2.957  ops/ms
ClientPb.existUser                       thrpt       3   9.498 ± 2.750  ops/ms
ClientPb.getUser                         thrpt       3   9.132 ± 2.571  ops/ms
ClientPb.listUser                        thrpt       3   7.781 ± 0.762  ops/ms
ClientPb.createUser                       avgt       3   3.527 ± 0.517   ms/op
ClientPb.existUser                        avgt       3   3.383 ± 1.073   ms/op
ClientPb.getUser                          avgt       3   3.485 ± 1.201   ms/op
ClientPb.listUser                         avgt       3   4.179 ± 0.051   ms/op
ClientPb.createUser                     sample  268724   3.571 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.381           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.119           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.005           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.182           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.361           ms/op
ClientPb.existUser                      sample  283011   3.389 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.985           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.055           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.631           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.042           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.411           ms/op
ClientPb.getUser                        sample  275465   3.485 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.348           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.839           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.691           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.068           ms/op
ClientPb.listUser                       sample  231695   4.139 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.616           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.099           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.364           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.100           ms/op
