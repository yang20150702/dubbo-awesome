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
# Warmup Iteration   1: 1.454 ops/ms
# Warmup Iteration   2: 3.684 ops/ms
# Warmup Iteration   3: 7.434 ops/ms
Iteration   1: 7.120 ops/ms
Iteration   2: 8.264 ops/ms
Iteration   3: 8.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.843 ±(99.9%) 11.484 ops/ms [Average]
  (min, avg, max) = (7.120, 7.843, 8.264), stdev = 0.629
  CI (99.9%): [≈ 0, 19.328] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.305 ops/ms
# Warmup Iteration   2: 7.219 ops/ms
# Warmup Iteration   3: 8.260 ops/ms
Iteration   1: 8.199 ops/ms
Iteration   2: 8.535 ops/ms
Iteration   3: 8.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.475 ±(99.9%) 4.580 ops/ms [Average]
  (min, avg, max) = (8.199, 8.475, 8.691), stdev = 0.251
  CI (99.9%): [3.895, 13.055] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.966 ops/ms
# Warmup Iteration   2: 5.978 ops/ms
# Warmup Iteration   3: 8.041 ops/ms
Iteration   1: 7.948 ops/ms
Iteration   2: 7.937 ops/ms
Iteration   3: 8.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.060 ±(99.9%) 3.724 ops/ms [Average]
  (min, avg, max) = (7.937, 8.060, 8.296), stdev = 0.204
  CI (99.9%): [4.336, 11.784] (assumes normal distribution)


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
# Warmup Iteration   1: 2.178 ops/ms
# Warmup Iteration   2: 5.607 ops/ms
# Warmup Iteration   3: 6.829 ops/ms
Iteration   1: 6.820 ops/ms
Iteration   2: 6.924 ops/ms
Iteration   3: 6.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.889 ±(99.9%) 1.093 ops/ms [Average]
  (min, avg, max) = (6.820, 6.889, 6.924), stdev = 0.060
  CI (99.9%): [5.796, 7.982] (assumes normal distribution)


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
# Warmup Iteration   1: 12.918 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.678 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.004 ms/op
Iteration   1: 3.836 ±(99.9%) 0.011 ms/op
Iteration   2: 3.790 ±(99.9%) 0.013 ms/op
Iteration   3: 3.868 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.831 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (3.790, 3.831, 3.868), stdev = 0.039
  CI (99.9%): [3.120, 4.543] (assumes normal distribution)


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
# Warmup Iteration   1: 11.404 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.382 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.009 ms/op
Iteration   1: 3.790 ±(99.9%) 0.012 ms/op
Iteration   2: 3.697 ±(99.9%) 0.012 ms/op
Iteration   3: 3.716 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.734 ±(99.9%) 0.895 ms/op [Average]
  (min, avg, max) = (3.697, 3.734, 3.790), stdev = 0.049
  CI (99.9%): [2.840, 4.629] (assumes normal distribution)


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
# Warmup Iteration   1: 11.320 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.143 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.003 ms/op
Iteration   1: 3.988 ±(99.9%) 0.010 ms/op
Iteration   2: 4.112 ±(99.9%) 0.006 ms/op
Iteration   3: 3.867 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.989 ±(99.9%) 2.238 ms/op [Average]
  (min, avg, max) = (3.867, 3.989, 4.112), stdev = 0.123
  CI (99.9%): [1.751, 6.227] (assumes normal distribution)


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
# Warmup Iteration   1: 13.292 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.418 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.909 ±(99.9%) 0.007 ms/op
Iteration   1: 4.682 ±(99.9%) 0.010 ms/op
Iteration   2: 4.453 ±(99.9%) 0.015 ms/op
Iteration   3: 4.481 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.539 ±(99.9%) 2.285 ms/op [Average]
  (min, avg, max) = (4.453, 4.539, 4.682), stdev = 0.125
  CI (99.9%): [2.254, 6.823] (assumes normal distribution)


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
# Warmup Iteration   1: 12.245 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.646 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.261 ±(99.9%) 0.016 ms/op
Iteration   1: 3.969 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  23.964 ms/op
                 createUser·p0.9999: 31.588 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   2: 3.917 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   7.856 ms/op
                 createUser·p0.999:  24.412 ms/op
                 createUser·p0.9999: 28.039 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   3: 3.909 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.097 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.925 ms/op
                 createUser·p0.999:  11.977 ms/op
                 createUser·p0.9999: 31.085 ms/op
                 createUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244102
  mean =      3.932 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 345 
    [ 2.500,  5.000) = 233228 
    [ 5.000,  7.500) = 8481 
    [ 7.500, 10.000) = 1477 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     23.816 ms/op
     p(99.9900) =     31.280 ms/op
     p(99.9990) =     31.967 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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
# Warmup Iteration   1: 10.883 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.644 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.011 ms/op
Iteration   1: 3.689 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.786 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  22.290 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   2: 3.745 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.802 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   7.111 ms/op
                 existUser·p0.999:  14.361 ms/op
                 existUser·p0.9999: 26.113 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.690 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.800 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  27.587 ms/op
                 existUser·p0.9999: 31.119 ms/op
                 existUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 258853
  mean =      3.708 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 311 
    [ 2.500,  5.000) = 252711 
    [ 5.000,  7.500) = 4526 
    [ 7.500, 10.000) = 812 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.786 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     30.511 ms/op
     p(99.9990) =     31.419 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


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
# Warmup Iteration   1: 12.041 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.734 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.012 ms/op
Iteration   1: 4.179 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   6.291 ms/op
                 getUser·p0.99:   9.356 ms/op
                 getUser·p0.999:  17.013 ms/op
                 getUser·p0.9999: 29.801 ms/op
                 getUser·p1.00:   31.097 ms/op

Iteration   2: 3.969 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.911 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   7.173 ms/op
                 getUser·p0.999:  10.969 ms/op
                 getUser·p0.9999: 28.760 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   3: 3.937 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.626 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  27.160 ms/op
                 getUser·p0.9999: 30.798 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238082
  mean =      4.026 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 224453 
    [ 5.000,  7.500) = 10008 
    [ 7.500, 10.000) = 2544 
    [10.000, 12.500) = 629 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 104 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.995 ms/op
     p(99.9000) =     16.971 ms/op
     p(99.9900) =     29.799 ms/op
     p(99.9990) =     31.084 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 15.021 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 5.442 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.975 ±(99.9%) 0.018 ms/op
Iteration   1: 4.834 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  23.095 ms/op
                 listUser·p0.9999: 25.846 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   2: 4.564 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 26.312 ms/op
                 listUser·p1.00:   26.968 ms/op

Iteration   3: 4.526 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  16.069 ms/op
                 listUser·p0.9999: 18.282 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206836
  mean =      4.638 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 182076 
    [ 5.000,  7.500) = 20533 
    [ 7.500, 10.000) = 3071 
    [10.000, 12.500) = 577 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     18.454 ms/op
     p(99.9900) =     25.711 ms/op
     p(99.9990) =     26.542 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.843 ± 11.484  ops/ms
ClientPb.existUser                       thrpt       3   8.475 ±  4.580  ops/ms
ClientPb.getUser                         thrpt       3   8.060 ±  3.724  ops/ms
ClientPb.listUser                        thrpt       3   6.889 ±  1.093  ops/ms
ClientPb.createUser                       avgt       3   3.831 ±  0.712   ms/op
ClientPb.existUser                        avgt       3   3.734 ±  0.895   ms/op
ClientPb.getUser                          avgt       3   3.989 ±  2.238   ms/op
ClientPb.listUser                         avgt       3   4.539 ±  2.285   ms/op
ClientPb.createUser                     sample  244102   3.932 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.487            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.781            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.448            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.882            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.135            ms/op
ClientPb.createUser:createUser·p0.999   sample          23.816            ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.280            ms/op
ClientPb.createUser:createUser·p1.00    sample          32.113            ms/op
ClientPb.existUser                      sample  258853   3.708 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.786            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.613            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.010            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.283            ms/op
ClientPb.existUser:existUser·p0.999     sample          19.759            ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.511            ms/op
ClientPb.existUser:existUser·p1.00      sample          31.523            ms/op
ClientPb.getUser                        sample  238082   4.026 ±  0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.348            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.563            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.153            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.995            ms/op
ClientPb.getUser:getUser·p0.999         sample          16.971            ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.799            ms/op
ClientPb.getUser:getUser·p1.00          sample          31.392            ms/op
ClientPb.listUser                       sample  206836   4.638 ±  0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.249            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.465            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.079            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.521            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.749            ms/op
ClientPb.listUser:listUser·p0.999       sample          18.454            ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.711            ms/op
ClientPb.listUser:listUser·p1.00        sample          26.968            ms/op
