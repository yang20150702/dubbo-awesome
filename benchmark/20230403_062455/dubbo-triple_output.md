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
# Warmup Iteration   1: 1.867 ops/ms
# Warmup Iteration   2: 5.158 ops/ms
# Warmup Iteration   3: 8.302 ops/ms
Iteration   1: 9.061 ops/ms
Iteration   2: 9.317 ops/ms
Iteration   3: 9.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.196 ±(99.9%) 2.342 ops/ms [Average]
  (min, avg, max) = (9.061, 9.196, 9.317), stdev = 0.128
  CI (99.9%): [6.854, 11.538] (assumes normal distribution)


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
# Warmup Iteration   1: 2.835 ops/ms
# Warmup Iteration   2: 8.618 ops/ms
# Warmup Iteration   3: 9.658 ops/ms
Iteration   1: 9.244 ops/ms
Iteration   2: 9.887 ops/ms
Iteration   3: 9.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.589 ±(99.9%) 5.910 ops/ms [Average]
  (min, avg, max) = (9.244, 9.589, 9.887), stdev = 0.324
  CI (99.9%): [3.680, 15.499] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.635 ops/ms
# Warmup Iteration   2: 8.432 ops/ms
# Warmup Iteration   3: 9.109 ops/ms
Iteration   1: 9.276 ops/ms
Iteration   2: 9.593 ops/ms
Iteration   3: 9.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.434 ±(99.9%) 2.895 ops/ms [Average]
  (min, avg, max) = (9.276, 9.434, 9.593), stdev = 0.159
  CI (99.9%): [6.539, 12.329] (assumes normal distribution)


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
# Warmup Iteration   1: 2.882 ops/ms
# Warmup Iteration   2: 6.432 ops/ms
# Warmup Iteration   3: 7.448 ops/ms
Iteration   1: 8.109 ops/ms
Iteration   2: 7.860 ops/ms
Iteration   3: 8.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.045 ±(99.9%) 2.977 ops/ms [Average]
  (min, avg, max) = (7.860, 8.045, 8.166), stdev = 0.163
  CI (99.9%): [5.068, 11.022] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.030 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.004 ms/op
Iteration   1: 3.412 ±(99.9%) 0.008 ms/op
Iteration   2: 3.560 ±(99.9%) 0.005 ms/op
Iteration   3: 3.399 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.457 ±(99.9%) 1.634 ms/op [Average]
  (min, avg, max) = (3.399, 3.457, 3.560), stdev = 0.090
  CI (99.9%): [1.823, 5.091] (assumes normal distribution)


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
# Warmup Iteration   1: 8.317 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.004 ms/op
Iteration   1: 3.244 ±(99.9%) 0.009 ms/op
Iteration   2: 3.276 ±(99.9%) 0.010 ms/op
Iteration   3: 3.404 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.308 ±(99.9%) 1.548 ms/op [Average]
  (min, avg, max) = (3.244, 3.308, 3.404), stdev = 0.085
  CI (99.9%): [1.760, 4.856] (assumes normal distribution)


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
# Warmup Iteration   1: 10.260 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.006 ms/op
Iteration   1: 3.498 ±(99.9%) 0.004 ms/op
Iteration   2: 3.530 ±(99.9%) 0.004 ms/op
Iteration   3: 3.618 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.549 ±(99.9%) 1.129 ms/op [Average]
  (min, avg, max) = (3.498, 3.549, 3.618), stdev = 0.062
  CI (99.9%): [2.420, 4.678] (assumes normal distribution)


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
# Warmup Iteration   1: 12.158 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.626 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.008 ms/op
Iteration   1: 4.051 ±(99.9%) 0.012 ms/op
Iteration   2: 3.907 ±(99.9%) 0.014 ms/op
Iteration   3: 4.148 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.035 ±(99.9%) 2.219 ms/op [Average]
  (min, avg, max) = (3.907, 4.035, 4.148), stdev = 0.122
  CI (99.9%): [1.817, 6.254] (assumes normal distribution)


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
# Warmup Iteration   1: 9.616 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.325 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.011 ms/op
Iteration   1: 3.525 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.796 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  18.695 ms/op
                 createUser·p0.9999: 20.937 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   2: 3.461 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.706 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  21.574 ms/op
                 createUser·p0.9999: 24.758 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   3: 3.485 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  19.562 ms/op
                 createUser·p0.9999: 29.185 ms/op
                 createUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274700
  mean =      3.490 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5102 
    [ 2.500,  5.000) = 264419 
    [ 5.000,  7.500) = 4038 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     19.277 ms/op
     p(99.9900) =     27.772 ms/op
     p(99.9990) =     30.574 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 9.258 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.009 ms/op
Iteration   1: 3.395 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.649 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  21.593 ms/op
                 existUser·p0.9999: 25.662 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   2: 3.309 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.082 ms/op
                 existUser·p0.999:  14.829 ms/op
                 existUser·p0.9999: 31.916 ms/op
                 existUser·p1.00:   34.275 ms/op

Iteration   3: 3.377 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.747 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  22.946 ms/op
                 existUser·p0.9999: 30.704 ms/op
                 existUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285479
  mean =      3.360 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9267 
    [ 2.500,  5.000) = 270691 
    [ 5.000,  7.500) = 4504 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.834 ms/op
     p(99.9000) =     21.809 ms/op
     p(99.9900) =     30.867 ms/op
     p(99.9990) =     33.770 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 9.157 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
Iteration   1: 3.402 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.579 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  10.681 ms/op
                 getUser·p0.9999: 28.539 ms/op
                 getUser·p1.00:   29.622 ms/op

Iteration   2: 3.420 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.880 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  22.400 ms/op
                 getUser·p0.9999: 25.777 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   3: 3.527 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.675 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  18.781 ms/op
                 getUser·p0.9999: 24.607 ms/op
                 getUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278199
  mean =      3.449 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5003 
    [ 2.500,  5.000) = 267560 
    [ 5.000,  7.500) = 4601 
    [ 7.500, 10.000) = 600 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     12.583 ms/op
     p(99.9900) =     26.914 ms/op
     p(99.9990) =     29.302 ms/op
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
# Warmup Iteration   1: 11.724 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.014 ms/op
Iteration   1: 4.063 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.240 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  18.547 ms/op
                 listUser·p0.9999: 24.351 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   2: 4.079 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.346 ms/op
                 listUser·p0.999:  14.270 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 3.863 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.226 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 20.242 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239813
  mean =      3.999 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 230674 
    [ 5.000,  7.500) = 6610 
    [ 7.500, 10.000) = 1463 
    [10.000, 12.500) = 457 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.617 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     24.833 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.196 ± 2.342  ops/ms
ClientPb.existUser                       thrpt       3   9.589 ± 5.910  ops/ms
ClientPb.getUser                         thrpt       3   9.434 ± 2.895  ops/ms
ClientPb.listUser                        thrpt       3   8.045 ± 2.977  ops/ms
ClientPb.createUser                       avgt       3   3.457 ± 1.634   ms/op
ClientPb.existUser                        avgt       3   3.308 ± 1.548   ms/op
ClientPb.getUser                          avgt       3   3.549 ± 1.129   ms/op
ClientPb.listUser                         avgt       3   4.035 ± 2.219   ms/op
ClientPb.createUser                     sample  274700   3.490 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.801           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.277           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.772           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.031           ms/op
ClientPb.existUser                      sample  285479   3.360 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.278           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.834           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.809           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.867           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.275           ms/op
ClientPb.getUser                        sample  278199   3.449 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.579           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.874           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.583           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.914           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.622           ms/op
ClientPb.listUser                       sample  239813   3.999 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.690           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.617           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.073           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.003           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.723           ms/op
