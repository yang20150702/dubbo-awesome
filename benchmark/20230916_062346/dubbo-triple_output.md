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
# Warmup Iteration   1: 1.807 ops/ms
# Warmup Iteration   2: 4.219 ops/ms
# Warmup Iteration   3: 7.841 ops/ms
Iteration   1: 8.170 ops/ms
Iteration   2: 8.552 ops/ms
Iteration   3: 8.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.411 ±(99.9%) 3.836 ops/ms [Average]
  (min, avg, max) = (8.170, 8.411, 8.552), stdev = 0.210
  CI (99.9%): [4.575, 12.247] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.544 ops/ms
# Warmup Iteration   2: 7.797 ops/ms
# Warmup Iteration   3: 8.519 ops/ms
Iteration   1: 8.791 ops/ms
Iteration   2: 8.884 ops/ms
Iteration   3: 8.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.821 ±(99.9%) 0.993 ops/ms [Average]
  (min, avg, max) = (8.789, 8.821, 8.884), stdev = 0.054
  CI (99.9%): [7.828, 9.814] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.353 ops/ms
# Warmup Iteration   2: 6.749 ops/ms
# Warmup Iteration   3: 8.009 ops/ms
Iteration   1: 8.701 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 8.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.537 ±(99.9%) 4.258 ops/ms [Average]
  (min, avg, max) = (8.269, 8.537, 8.701), stdev = 0.233
  CI (99.9%): [4.278, 12.795] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.201 ops/ms
# Warmup Iteration   2: 6.008 ops/ms
# Warmup Iteration   3: 6.925 ops/ms
Iteration   1: 7.013 ops/ms
Iteration   2: 6.887 ops/ms
Iteration   3: 7.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.009 ±(99.9%) 2.195 ops/ms [Average]
  (min, avg, max) = (6.887, 7.009, 7.128), stdev = 0.120
  CI (99.9%): [4.815, 9.204] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.188 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.003 ms/op
Iteration   1: 3.741 ±(99.9%) 0.008 ms/op
Iteration   2: 3.696 ±(99.9%) 0.005 ms/op
Iteration   3: 3.801 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.746 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (3.696, 3.746, 3.801), stdev = 0.052
  CI (99.9%): [2.789, 4.703] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.072 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.184 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.741 ±(99.9%) 0.003 ms/op
Iteration   1: 3.698 ±(99.9%) 0.004 ms/op
Iteration   2: 3.657 ±(99.9%) 0.004 ms/op
Iteration   3: 3.608 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.654 ±(99.9%) 0.825 ms/op [Average]
  (min, avg, max) = (3.608, 3.654, 3.698), stdev = 0.045
  CI (99.9%): [2.829, 4.479] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.175 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.003 ms/op
Iteration   1: 3.737 ±(99.9%) 0.004 ms/op
Iteration   2: 3.706 ±(99.9%) 0.003 ms/op
Iteration   3: 3.746 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.730 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (3.706, 3.730, 3.746), stdev = 0.021
  CI (99.9%): [3.349, 4.111] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 13.215 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.099 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.632 ±(99.9%) 0.003 ms/op
Iteration   1: 4.364 ±(99.9%) 0.007 ms/op
Iteration   2: 4.478 ±(99.9%) 0.005 ms/op
Iteration   3: 4.384 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.408 ±(99.9%) 1.110 ms/op [Average]
  (min, avg, max) = (4.364, 4.408, 4.478), stdev = 0.061
  CI (99.9%): [3.299, 5.518] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 11.894 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.017 ms/op
Iteration   1: 3.904 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   7.176 ms/op
                 createUser·p0.999:  11.354 ms/op
                 createUser·p0.9999: 38.587 ms/op
                 createUser·p1.00:   40.698 ms/op

Iteration   2: 3.833 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  25.002 ms/op
                 createUser·p0.9999: 27.448 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   3: 3.785 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  26.625 ms/op
                 createUser·p0.9999: 30.999 ms/op
                 createUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 249957
  mean =      3.840 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 241178 
    [ 5.000, 10.000) = 8239 
    [10.000, 15.000) = 281 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 44 
    [25.000, 30.000) = 167 
    [30.000, 35.000) = 37 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     22.845 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     40.272 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


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
# Warmup Iteration   1: 11.755 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.012 ms/op
Iteration   1: 3.662 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  23.149 ms/op
                 existUser·p0.9999: 26.542 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   2: 3.778 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   7.807 ms/op
                 existUser·p0.999:  11.817 ms/op
                 existUser·p0.9999: 26.691 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 3.734 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  27.099 ms/op
                 existUser·p0.9999: 30.634 ms/op
                 existUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 257550
  mean =      3.724 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2063 
    [ 2.500,  5.000) = 248233 
    [ 5.000,  7.500) = 5259 
    [ 7.500, 10.000) = 1371 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     19.145 ms/op
     p(99.9900) =     30.195 ms/op
     p(99.9990) =     30.947 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 10.210 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.527 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.012 ms/op
Iteration   1: 3.860 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.093 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   8.323 ms/op
                 getUser·p0.999:  13.453 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   2: 3.779 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  25.415 ms/op
                 getUser·p0.9999: 30.230 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   3: 3.897 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.593 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  26.015 ms/op
                 getUser·p0.9999: 29.124 ms/op
                 getUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 249634
  mean =      3.844 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 545 
    [ 2.500,  5.000) = 239149 
    [ 5.000,  7.500) = 7232 
    [ 7.500, 10.000) = 1791 
    [10.000, 12.500) = 422 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     22.261 ms/op
     p(99.9900) =     29.099 ms/op
     p(99.9990) =     30.737 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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
# Warmup Iteration   1: 12.925 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 5.283 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.589 ±(99.9%) 0.015 ms/op
Iteration   1: 4.555 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.815 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   8.617 ms/op
                 listUser·p0.999:  24.930 ms/op
                 listUser·p0.9999: 26.737 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   2: 4.531 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   8.055 ms/op
                 listUser·p0.999:  17.717 ms/op
                 listUser·p0.9999: 23.899 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   3: 4.479 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   7.105 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 17.821 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212238
  mean =      4.522 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 190834 
    [ 5.000,  7.500) = 18554 
    [ 7.500, 10.000) = 1791 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 254 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.815 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     17.523 ms/op
     p(99.9900) =     26.240 ms/op
     p(99.9990) =     27.087 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.411 ± 3.836  ops/ms
ClientPb.existUser                       thrpt       3   8.821 ± 0.993  ops/ms
ClientPb.getUser                         thrpt       3   8.537 ± 4.258  ops/ms
ClientPb.listUser                        thrpt       3   7.009 ± 2.195  ops/ms
ClientPb.createUser                       avgt       3   3.746 ± 0.957   ms/op
ClientPb.existUser                        avgt       3   3.654 ± 0.825   ms/op
ClientPb.getUser                          avgt       3   3.730 ± 0.381   ms/op
ClientPb.listUser                         avgt       3   4.408 ± 1.110   ms/op
ClientPb.createUser                     sample  249957   3.840 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.991           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.760           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.709           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.845           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.490           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.698           ms/op
ClientPb.existUser                      sample  257550   3.724 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.053           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.604           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.145           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.195           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.999           ms/op
ClientPb.getUser                        sample  249634   3.844 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.593           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.709           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.261           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.099           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.162           ms/op
ClientPb.listUser                       sample  212238   4.522 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.815           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.523           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.240           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.132           ms/op
