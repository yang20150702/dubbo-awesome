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
# Warmup Iteration   1: 2.064 ops/ms
# Warmup Iteration   2: 5.072 ops/ms
# Warmup Iteration   3: 8.324 ops/ms
Iteration   1: 8.961 ops/ms
Iteration   2: 8.906 ops/ms
Iteration   3: 9.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.980 ±(99.9%) 1.554 ops/ms [Average]
  (min, avg, max) = (8.906, 8.980, 9.073), stdev = 0.085
  CI (99.9%): [7.426, 10.534] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.740 ops/ms
# Warmup Iteration   2: 7.694 ops/ms
# Warmup Iteration   3: 9.448 ops/ms
Iteration   1: 9.601 ops/ms
Iteration   2: 9.399 ops/ms
Iteration   3: 9.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.515 ±(99.9%) 1.903 ops/ms [Average]
  (min, avg, max) = (9.399, 9.515, 9.601), stdev = 0.104
  CI (99.9%): [7.612, 11.419] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.432 ops/ms
# Warmup Iteration   2: 8.088 ops/ms
# Warmup Iteration   3: 9.103 ops/ms
Iteration   1: 9.172 ops/ms
Iteration   2: 8.977 ops/ms
Iteration   3: 8.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.026 ±(99.9%) 2.365 ops/ms [Average]
  (min, avg, max) = (8.927, 9.026, 9.172), stdev = 0.130
  CI (99.9%): [6.661, 11.391] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.510 ops/ms
# Warmup Iteration   2: 6.714 ops/ms
# Warmup Iteration   3: 7.238 ops/ms
Iteration   1: 7.533 ops/ms
Iteration   2: 7.553 ops/ms
Iteration   3: 7.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.543 ±(99.9%) 0.180 ops/ms [Average]
  (min, avg, max) = (7.533, 7.543, 7.553), stdev = 0.010
  CI (99.9%): [7.363, 7.723] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.851 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.003 ms/op
Iteration   1: 3.584 ±(99.9%) 0.006 ms/op
Iteration   2: 3.486 ±(99.9%) 0.009 ms/op
Iteration   3: 3.531 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.534 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (3.486, 3.534, 3.584), stdev = 0.049
  CI (99.9%): [2.645, 4.422] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.238 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.002 ms/op
Iteration   1: 3.377 ±(99.9%) 0.003 ms/op
Iteration   2: 3.409 ±(99.9%) 0.004 ms/op
Iteration   3: 3.463 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.416 ±(99.9%) 0.791 ms/op [Average]
  (min, avg, max) = (3.377, 3.416, 3.463), stdev = 0.043
  CI (99.9%): [2.625, 4.207] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.554 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.003 ms/op
Iteration   1: 3.503 ±(99.9%) 0.005 ms/op
Iteration   2: 3.469 ±(99.9%) 0.004 ms/op
Iteration   3: 3.517 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.496 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (3.469, 3.496, 3.517), stdev = 0.025
  CI (99.9%): [3.048, 3.944] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.530 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.350 ±(99.9%) 0.006 ms/op
Iteration   1: 4.214 ±(99.9%) 0.006 ms/op
Iteration   2: 4.134 ±(99.9%) 0.007 ms/op
Iteration   3: 4.205 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.185 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (4.134, 4.185, 4.214), stdev = 0.044
  CI (99.9%): [3.384, 4.985] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.283 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.012 ms/op
Iteration   1: 3.563 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.991 ms/op
                 createUser·p0.999:  22.031 ms/op
                 createUser·p0.9999: 25.267 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   2: 3.511 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  23.295 ms/op
                 createUser·p0.9999: 27.161 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   3: 3.547 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  18.514 ms/op
                 createUser·p0.9999: 29.358 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270913
  mean =      3.540 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3397 
    [ 2.500,  5.000) = 262241 
    [ 5.000,  7.500) = 4268 
    [ 7.500, 10.000) = 514 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 138 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     19.842 ms/op
     p(99.9900) =     27.877 ms/op
     p(99.9990) =     30.353 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.848 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.008 ms/op
Iteration   1: 3.441 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  23.165 ms/op
                 existUser·p0.9999: 26.270 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   2: 3.444 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  24.551 ms/op
                 existUser·p0.9999: 28.017 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   3: 3.477 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  22.093 ms/op
                 existUser·p0.9999: 29.667 ms/op
                 existUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277935
  mean =      3.454 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5402 
    [ 2.500,  5.000) = 266372 
    [ 5.000,  7.500) = 4804 
    [ 7.500, 10.000) = 740 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 135 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     22.551 ms/op
     p(99.9900) =     28.161 ms/op
     p(99.9990) =     30.179 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 10.312 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.634 ±(99.9%) 0.012 ms/op
Iteration   1: 3.570 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.974 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  13.615 ms/op
                 getUser·p0.9999: 27.692 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   2: 3.437 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  23.623 ms/op
                 getUser·p0.9999: 26.401 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   3: 3.509 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  18.279 ms/op
                 getUser·p0.9999: 32.556 ms/op
                 getUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273896
  mean =      3.504 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4155 
    [ 2.500,  5.000) = 263620 
    [ 5.000,  7.500) = 4933 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     14.483 ms/op
     p(99.9900) =     31.124 ms/op
     p(99.9990) =     33.408 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 12.025 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.785 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.373 ±(99.9%) 0.014 ms/op
Iteration   1: 4.209 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  22.943 ms/op
                 listUser·p0.9999: 26.654 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   2: 4.267 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 17.842 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.216 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.993 ms/op
                 listUser·p0.50:   4.149 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.946 ms/op
                 listUser·p0.9999: 18.587 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226856
  mean =      4.231 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 216173 
    [ 5.000,  7.500) = 8274 
    [ 7.500, 10.000) = 1493 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 230 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     27.245 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.980 ± 1.554  ops/ms
ClientPb.existUser                       thrpt       3   9.515 ± 1.903  ops/ms
ClientPb.getUser                         thrpt       3   9.026 ± 2.365  ops/ms
ClientPb.listUser                        thrpt       3   7.543 ± 0.180  ops/ms
ClientPb.createUser                       avgt       3   3.534 ± 0.889   ms/op
ClientPb.existUser                        avgt       3   3.416 ± 0.791   ms/op
ClientPb.getUser                          avgt       3   3.496 ± 0.448   ms/op
ClientPb.listUser                         avgt       3   4.185 ± 0.801   ms/op
ClientPb.createUser                     sample  270913   3.540 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.100           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.408           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.842           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.877           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.835           ms/op
ClientPb.existUser                      sample  277935   3.454 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.276           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.190           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.111           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.551           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.161           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.638           ms/op
ClientPb.getUser                        sample  273896   3.504 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.703           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.483           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.124           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.751           ms/op
ClientPb.listUser                       sample  226856   4.231 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.892           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.112           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.948           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.545           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.286           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.428           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.525           ms/op
