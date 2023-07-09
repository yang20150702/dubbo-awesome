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
# Warmup Iteration   1: 1.712 ops/ms
# Warmup Iteration   2: 3.519 ops/ms
# Warmup Iteration   3: 7.188 ops/ms
Iteration   1: 7.484 ops/ms
Iteration   2: 7.869 ops/ms
Iteration   3: 7.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.688 ±(99.9%) 3.525 ops/ms [Average]
  (min, avg, max) = (7.484, 7.688, 7.869), stdev = 0.193
  CI (99.9%): [4.163, 11.213] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.440 ops/ms
# Warmup Iteration   2: 7.666 ops/ms
# Warmup Iteration   3: 8.201 ops/ms
Iteration   1: 8.200 ops/ms
Iteration   2: 8.444 ops/ms
Iteration   3: 8.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.390 ±(99.9%) 3.082 ops/ms [Average]
  (min, avg, max) = (8.200, 8.390, 8.525), stdev = 0.169
  CI (99.9%): [5.308, 11.472] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.307 ops/ms
# Warmup Iteration   2: 6.846 ops/ms
# Warmup Iteration   3: 7.691 ops/ms
Iteration   1: 7.879 ops/ms
Iteration   2: 8.091 ops/ms
Iteration   3: 8.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.074 ±(99.9%) 3.436 ops/ms [Average]
  (min, avg, max) = (7.879, 8.074, 8.254), stdev = 0.188
  CI (99.9%): [4.638, 11.511] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.216 ops/ms
# Warmup Iteration   2: 5.516 ops/ms
# Warmup Iteration   3: 6.782 ops/ms
Iteration   1: 6.614 ops/ms
Iteration   2: 6.890 ops/ms
Iteration   3: 7.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.843 ±(99.9%) 3.814 ops/ms [Average]
  (min, avg, max) = (6.614, 6.843, 7.024), stdev = 0.209
  CI (99.9%): [3.028, 10.657] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.670 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.813 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.009 ms/op
Iteration   1: 4.096 ±(99.9%) 0.008 ms/op
Iteration   2: 3.936 ±(99.9%) 0.004 ms/op
Iteration   3: 3.819 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.950 ±(99.9%) 2.534 ms/op [Average]
  (min, avg, max) = (3.819, 3.950, 4.096), stdev = 0.139
  CI (99.9%): [1.417, 6.484] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.755 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.004 ms/op
Iteration   1: 3.801 ±(99.9%) 0.010 ms/op
Iteration   2: 3.830 ±(99.9%) 0.005 ms/op
Iteration   3: 3.762 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.798 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (3.762, 3.798, 3.830), stdev = 0.034
  CI (99.9%): [3.181, 4.414] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.480 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.866 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.006 ms/op
Iteration   1: 3.854 ±(99.9%) 0.004 ms/op
Iteration   2: 3.822 ±(99.9%) 0.005 ms/op
Iteration   3: 3.872 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.849 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (3.822, 3.849, 3.872), stdev = 0.026
  CI (99.9%): [3.382, 4.317] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.974 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.827 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.770 ±(99.9%) 0.014 ms/op
Iteration   1: 4.899 ±(99.9%) 0.014 ms/op
Iteration   2: 4.477 ±(99.9%) 0.015 ms/op
Iteration   3: 4.587 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.654 ±(99.9%) 4.000 ms/op [Average]
  (min, avg, max) = (4.477, 4.654, 4.899), stdev = 0.219
  CI (99.9%): [0.654, 8.654] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.033 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.672 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.432 ±(99.9%) 0.019 ms/op
Iteration   1: 4.054 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.403 ms/op
                 createUser·p0.99:   7.832 ms/op
                 createUser·p0.999:  13.861 ms/op
                 createUser·p0.9999: 26.280 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   2: 3.836 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  24.269 ms/op
                 createUser·p0.9999: 26.804 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 3.899 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.851 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  28.965 ms/op
                 createUser·p0.9999: 31.620 ms/op
                 createUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244369
  mean =      3.928 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 298 
    [ 2.500,  5.000) = 232030 
    [ 5.000,  7.500) = 10182 
    [ 7.500, 10.000) = 1308 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     23.777 ms/op
     p(99.9900) =     30.755 ms/op
     p(99.9990) =     34.211 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.741 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.012 ms/op
Iteration   1: 3.736 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.788 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.726 ms/op
                 existUser·p0.999:  14.359 ms/op
                 existUser·p0.9999: 23.771 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   2: 3.782 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  23.806 ms/op
                 existUser·p0.9999: 39.911 ms/op
                 existUser·p1.00:   39.977 ms/op

Iteration   3: 3.807 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  15.254 ms/op
                 existUser·p0.9999: 29.758 ms/op
                 existUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254303
  mean =      3.775 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 514 
    [ 2.500,  5.000) = 245427 
    [ 5.000,  7.500) = 6658 
    [ 7.500, 10.000) = 955 
    [10.000, 12.500) = 356 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     39.191 ms/op
     p(99.9990) =     39.941 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.979 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.658 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.015 ms/op
Iteration   1: 4.022 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   8.815 ms/op
                 getUser·p0.999:  24.101 ms/op
                 getUser·p0.9999: 26.842 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   2: 3.931 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.195 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   8.290 ms/op
                 getUser·p0.999:  11.813 ms/op
                 getUser·p0.9999: 26.341 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 3.888 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  27.460 ms/op
                 getUser·p0.9999: 33.933 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243092
  mean =      3.947 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 232806 
    [ 5.000,  7.500) = 6366 
    [ 7.500, 10.000) = 2846 
    [10.000, 12.500) = 620 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 114 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      8.323 ms/op
     p(99.9000) =     24.049 ms/op
     p(99.9900) =     32.092 ms/op
     p(99.9990) =     34.153 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.427 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.943 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.702 ±(99.9%) 0.016 ms/op
Iteration   1: 4.539 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.054 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  24.770 ms/op
                 listUser·p0.9999: 40.039 ms/op
                 listUser·p1.00:   41.091 ms/op

Iteration   2: 4.700 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  20.316 ms/op
                 listUser·p0.9999: 21.201 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   3: 4.752 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.798 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  16.724 ms/op
                 listUser·p0.9999: 20.382 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205819
  mean =      4.662 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 179970 
    [ 5.000, 10.000) = 24810 
    [10.000, 15.000) = 613 
    [15.000, 20.000) = 173 
    [20.000, 25.000) = 187 
    [25.000, 30.000) = 34 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.054 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     20.519 ms/op
     p(99.9900) =     39.376 ms/op
     p(99.9990) =     40.490 ms/op
     p(99.9999) =     41.091 ms/op
    p(100.0000) =     41.091 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.688 ± 3.525  ops/ms
ClientPb.existUser                       thrpt       3   8.390 ± 3.082  ops/ms
ClientPb.getUser                         thrpt       3   8.074 ± 3.436  ops/ms
ClientPb.listUser                        thrpt       3   6.843 ± 3.814  ops/ms
ClientPb.createUser                       avgt       3   3.950 ± 2.534   ms/op
ClientPb.existUser                        avgt       3   3.798 ± 0.616   ms/op
ClientPb.getUser                          avgt       3   3.849 ± 0.468   ms/op
ClientPb.listUser                         avgt       3   4.654 ± 4.000   ms/op
ClientPb.createUser                     sample  244369   3.928 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.214           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.989           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.777           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.755           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.127           ms/op
ClientPb.existUser                      sample  254303   3.775 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.487           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.563           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.742           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.204           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.191           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.977           ms/op
ClientPb.getUser                        sample  243092   3.947 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.264           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.323           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.049           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.092           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  205819   4.662 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.054           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.128           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.376           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.091           ms/op
