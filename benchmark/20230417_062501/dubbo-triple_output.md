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
# Warmup Iteration   1: 2.856 ops/ms
# Warmup Iteration   2: 6.290 ops/ms
# Warmup Iteration   3: 9.672 ops/ms
Iteration   1: 9.985 ops/ms
Iteration   2: 9.846 ops/ms
Iteration   3: 10.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.971 ±(99.9%) 2.159 ops/ms [Average]
  (min, avg, max) = (9.846, 9.971, 10.082), stdev = 0.118
  CI (99.9%): [7.813, 12.130] (assumes normal distribution)


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
# Warmup Iteration   1: 3.826 ops/ms
# Warmup Iteration   2: 9.421 ops/ms
# Warmup Iteration   3: 10.135 ops/ms
Iteration   1: 10.328 ops/ms
Iteration   2: 9.952 ops/ms
Iteration   3: 10.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.099 ±(99.9%) 3.670 ops/ms [Average]
  (min, avg, max) = (9.952, 10.099, 10.328), stdev = 0.201
  CI (99.9%): [6.430, 13.769] (assumes normal distribution)


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
# Warmup Iteration   1: 3.676 ops/ms
# Warmup Iteration   2: 9.197 ops/ms
# Warmup Iteration   3: 9.278 ops/ms
Iteration   1: 9.907 ops/ms
Iteration   2: 10.051 ops/ms
Iteration   3: 9.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.949 ±(99.9%) 1.613 ops/ms [Average]
  (min, avg, max) = (9.891, 9.949, 10.051), stdev = 0.088
  CI (99.9%): [8.337, 11.562] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.593 ops/ms
# Warmup Iteration   2: 7.910 ops/ms
# Warmup Iteration   3: 8.485 ops/ms
Iteration   1: 8.389 ops/ms
Iteration   2: 8.620 ops/ms
Iteration   3: 8.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.563 ±(99.9%) 2.794 ops/ms [Average]
  (min, avg, max) = (8.389, 8.563, 8.679), stdev = 0.153
  CI (99.9%): [5.769, 11.356] (assumes normal distribution)


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
# Warmup Iteration   1: 7.327 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.007 ms/op
Iteration   1: 3.279 ±(99.9%) 0.006 ms/op
Iteration   2: 3.092 ±(99.9%) 0.003 ms/op
Iteration   3: 3.157 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.176 ±(99.9%) 1.735 ms/op [Average]
  (min, avg, max) = (3.092, 3.176, 3.279), stdev = 0.095
  CI (99.9%): [1.441, 4.911] (assumes normal distribution)


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
# Warmup Iteration   1: 7.084 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.005 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
Iteration   2: 2.999 ±(99.9%) 0.003 ms/op
Iteration   3: 3.042 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.016 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (2.999, 3.016, 3.042), stdev = 0.023
  CI (99.9%): [2.592, 3.439] (assumes normal distribution)


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
# Warmup Iteration   1: 8.074 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.437 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.004 ms/op
Iteration   1: 3.224 ±(99.9%) 0.008 ms/op
Iteration   2: 3.247 ±(99.9%) 0.008 ms/op
Iteration   3: 3.318 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.263 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (3.224, 3.263, 3.318), stdev = 0.049
  CI (99.9%): [2.367, 4.160] (assumes normal distribution)


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
# Warmup Iteration   1: 8.950 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.004 ms/op
Iteration   1: 3.761 ±(99.9%) 0.007 ms/op
Iteration   2: 3.639 ±(99.9%) 0.011 ms/op
Iteration   3: 3.651 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.684 ±(99.9%) 1.227 ms/op [Average]
  (min, avg, max) = (3.639, 3.684, 3.761), stdev = 0.067
  CI (99.9%): [2.457, 4.911] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.053 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
Iteration   1: 3.239 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  15.469 ms/op
                 createUser·p0.9999: 24.496 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 25.526 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   3: 3.342 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.472 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  15.868 ms/op
                 createUser·p0.9999: 25.469 ms/op
                 createUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295127
  mean =      3.253 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18392 
    [ 2.500,  5.000) = 269025 
    [ 5.000,  7.500) = 6713 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     25.346 ms/op
     p(99.9990) =     27.037 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 6.878 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.008 ms/op
Iteration   1: 3.126 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  9.513 ms/op
                 existUser·p0.9999: 19.169 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   2: 3.052 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  13.877 ms/op
                 existUser·p0.9999: 22.285 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 3.116 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  12.933 ms/op
                 existUser·p0.9999: 21.261 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309816
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14446 
    [ 2.500,  5.000) = 289913 
    [ 5.000,  7.500) = 4543 
    [ 7.500, 10.000) = 424 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.602 ms/op
     p(99.9000) =     12.955 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     22.823 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 7.216 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.009 ms/op
Iteration   1: 3.220 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  9.869 ms/op
                 getUser·p0.9999: 19.366 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 25.916 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   3: 3.288 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.436 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  11.686 ms/op
                 getUser·p0.9999: 19.866 ms/op
                 getUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297028
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9000 
    [ 2.500,  5.000) = 279962 
    [ 5.000,  7.500) = 7174 
    [ 7.500, 10.000) = 541 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     11.976 ms/op
     p(99.9900) =     23.763 ms/op
     p(99.9990) =     27.037 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 9.179 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.010 ms/op
Iteration   1: 3.747 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  16.229 ms/op
                 listUser·p0.9999: 18.988 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   2: 3.738 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.081 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  14.442 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   3: 3.755 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.048 ms/op
                 listUser·p0.999:  13.610 ms/op
                 listUser·p0.9999: 16.898 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256158
  mean =      3.747 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 248310 
    [ 5.000,  7.500) = 5781 
    [ 7.500, 10.000) = 1260 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     18.363 ms/op
     p(99.9990) =     20.036 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.971 ± 2.159  ops/ms
ClientPb.existUser                       thrpt       3  10.099 ± 3.670  ops/ms
ClientPb.getUser                         thrpt       3   9.949 ± 1.613  ops/ms
ClientPb.listUser                        thrpt       3   8.563 ± 2.794  ops/ms
ClientPb.createUser                       avgt       3   3.176 ± 1.735   ms/op
ClientPb.existUser                        avgt       3   3.016 ± 0.423   ms/op
ClientPb.getUser                          avgt       3   3.263 ± 0.897   ms/op
ClientPb.listUser                         avgt       3   3.684 ± 1.227   ms/op
ClientPb.createUser                     sample  295127   3.253 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.472           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.466           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.346           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.230           ms/op
ClientPb.existUser                      sample  309816   3.098 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.603           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.602           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.955           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.627           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.069           ms/op
ClientPb.getUser                        sample  297028   3.230 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.139           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.650           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.976           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.763           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.165           ms/op
ClientPb.listUser                       sample  256158   3.747 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.526           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.613           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.363           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.414           ms/op
