# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.601 ops/ms
# Warmup Iteration   2: 3.734 ops/ms
# Warmup Iteration   3: 7.404 ops/ms
Iteration   1: 7.436 ops/ms
Iteration   2: 8.187 ops/ms
Iteration   3: 8.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.905 ±(99.9%) 7.464 ops/ms [Average]
  (min, avg, max) = (7.436, 7.905, 8.187), stdev = 0.409
  CI (99.9%): [0.441, 15.369] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.204 ops/ms
# Warmup Iteration   2: 7.027 ops/ms
# Warmup Iteration   3: 8.184 ops/ms
Iteration   1: 8.509 ops/ms
Iteration   2: 8.424 ops/ms
Iteration   3: 8.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.506 ±(99.9%) 1.465 ops/ms [Average]
  (min, avg, max) = (8.424, 8.506, 8.584), stdev = 0.080
  CI (99.9%): [7.040, 9.971] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.237 ops/ms
# Warmup Iteration   2: 6.984 ops/ms
# Warmup Iteration   3: 7.905 ops/ms
Iteration   1: 7.858 ops/ms
Iteration   2: 7.805 ops/ms
Iteration   3: 7.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.831 ±(99.9%) 0.477 ops/ms [Average]
  (min, avg, max) = (7.805, 7.831, 7.858), stdev = 0.026
  CI (99.9%): [7.354, 8.308] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.165 ops/ms
# Warmup Iteration   2: 6.115 ops/ms
# Warmup Iteration   3: 6.976 ops/ms
Iteration   1: 6.835 ops/ms
Iteration   2: 6.747 ops/ms
Iteration   3: 6.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.824 ±(99.9%) 1.313 ops/ms [Average]
  (min, avg, max) = (6.747, 6.824, 6.890), stdev = 0.072
  CI (99.9%): [5.511, 8.137] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.221 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.005 ms/op
Iteration   1: 4.122 ±(99.9%) 0.005 ms/op
Iteration   2: 4.051 ±(99.9%) 0.006 ms/op
Iteration   3: 4.136 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.103 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (4.051, 4.103, 4.136), stdev = 0.045
  CI (99.9%): [3.277, 4.929] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.404 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.006 ms/op
Iteration   1: 3.836 ±(99.9%) 0.007 ms/op
Iteration   2: 3.939 ±(99.9%) 0.007 ms/op
Iteration   3: 3.736 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.837 ±(99.9%) 1.843 ms/op [Average]
  (min, avg, max) = (3.736, 3.837, 3.939), stdev = 0.101
  CI (99.9%): [1.994, 5.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.541 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.007 ms/op
Iteration   1: 4.025 ±(99.9%) 0.005 ms/op
Iteration   2: 4.040 ±(99.9%) 0.005 ms/op
Iteration   3: 3.969 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.011 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (3.969, 4.011, 4.040), stdev = 0.037
  CI (99.9%): [3.331, 4.692] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.819 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.418 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.815 ±(99.9%) 0.010 ms/op
Iteration   1: 4.615 ±(99.9%) 0.009 ms/op
Iteration   2: 4.607 ±(99.9%) 0.008 ms/op
Iteration   3: 4.630 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.617 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (4.607, 4.617, 4.630), stdev = 0.012
  CI (99.9%): [4.403, 4.832] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.764 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 4.956 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.301 ±(99.9%) 0.017 ms/op
Iteration   1: 4.075 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.210 ms/op
                 createUser·p0.99:   7.922 ms/op
                 createUser·p0.999:  23.005 ms/op
                 createUser·p0.9999: 25.171 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   2: 4.022 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.724 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  14.040 ms/op
                 createUser·p0.9999: 27.756 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.992 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.921 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  26.706 ms/op
                 createUser·p0.9999: 29.915 ms/op
                 createUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238095
  mean =      4.029 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 376 
    [ 2.500,  5.000) = 224410 
    [ 5.000,  7.500) = 11350 
    [ 7.500, 10.000) = 1165 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     23.030 ms/op
     p(99.9900) =     28.777 ms/op
     p(99.9990) =     30.384 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.311 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.015 ms/op
Iteration   1: 3.947 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.028 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  14.510 ms/op
                 existUser·p0.9999: 23.036 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.870 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.345 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.864 ms/op
                 existUser·p0.999:  22.151 ms/op
                 existUser·p0.9999: 25.115 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   3: 3.897 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   7.487 ms/op
                 existUser·p0.999:  17.103 ms/op
                 existUser·p0.9999: 28.593 ms/op
                 existUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245867
  mean =      3.905 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 314 
    [ 2.500,  5.000) = 234499 
    [ 5.000,  7.500) = 8987 
    [ 7.500, 10.000) = 1227 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.121 ms/op
     p(99.9000) =     17.277 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     28.970 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.385 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.011 ms/op
Iteration   1: 4.018 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.208 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.968 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  23.542 ms/op
                 getUser·p0.9999: 30.121 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   2: 3.994 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.882 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  25.913 ms/op
                 getUser·p0.9999: 29.194 ms/op
                 getUser·p1.00:   29.688 ms/op

Iteration   3: 3.976 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.720 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  27.630 ms/op
                 getUser·p0.9999: 34.600 ms/op
                 getUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240056
  mean =      3.996 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 107 
    [ 2.500,  5.000) = 228303 
    [ 5.000,  7.500) = 8467 
    [ 7.500, 10.000) = 2275 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     25.297 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     35.258 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.076 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.611 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.854 ±(99.9%) 0.016 ms/op
Iteration   1: 4.755 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  22.574 ms/op
                 listUser·p0.9999: 28.508 ms/op
                 listUser·p1.00:   29.491 ms/op

Iteration   2: 4.921 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  18.420 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   3: 4.818 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.761 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.326 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   8.331 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 20.876 ms/op
                 listUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198546
  mean =      4.830 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 150234 
    [ 5.000,  7.500) = 44099 
    [ 7.500, 10.000) = 3092 
    [10.000, 12.500) = 541 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 230 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.968 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     19.086 ms/op
     p(99.9900) =     27.254 ms/op
     p(99.9990) =     29.427 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.905 ± 7.464  ops/ms
ClientPb.existUser                       thrpt       3   8.506 ± 1.465  ops/ms
ClientPb.getUser                         thrpt       3   7.831 ± 0.477  ops/ms
ClientPb.listUser                        thrpt       3   6.824 ± 1.313  ops/ms
ClientPb.createUser                       avgt       3   4.103 ± 0.826   ms/op
ClientPb.existUser                        avgt       3   3.837 ± 1.843   ms/op
ClientPb.getUser                          avgt       3   4.011 ± 0.681   ms/op
ClientPb.listUser                         avgt       3   4.617 ± 0.215   ms/op
ClientPb.createUser                     sample  238095   4.029 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.393           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.719           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.078           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.030           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.777           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.409           ms/op
ClientPb.existUser                      sample  245867   3.905 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.444           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.907           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.121           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.277           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.001           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.065           ms/op
ClientPb.getUser                        sample  240056   3.996 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.720           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.964           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.028           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.297           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.686           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.521           ms/op
ClientPb.listUser                       sample  198546   4.830 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.968           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.086           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.254           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.491           ms/op
