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
# Warmup Iteration   1: 1.783 ops/ms
# Warmup Iteration   2: 3.885 ops/ms
# Warmup Iteration   3: 7.290 ops/ms
Iteration   1: 7.841 ops/ms
Iteration   2: 7.983 ops/ms
Iteration   3: 8.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.973 ±(99.9%) 2.306 ops/ms [Average]
  (min, avg, max) = (7.841, 7.973, 8.093), stdev = 0.126
  CI (99.9%): [5.667, 10.279] (assumes normal distribution)


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
# Warmup Iteration   1: 2.307 ops/ms
# Warmup Iteration   2: 7.089 ops/ms
# Warmup Iteration   3: 7.750 ops/ms
Iteration   1: 8.428 ops/ms
Iteration   2: 8.349 ops/ms
Iteration   3: 8.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.414 ±(99.9%) 1.063 ops/ms [Average]
  (min, avg, max) = (8.349, 8.414, 8.463), stdev = 0.058
  CI (99.9%): [7.351, 9.476] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.251 ops/ms
# Warmup Iteration   2: 6.693 ops/ms
# Warmup Iteration   3: 7.680 ops/ms
Iteration   1: 8.104 ops/ms
Iteration   2: 8.023 ops/ms
Iteration   3: 7.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.026 ±(99.9%) 1.401 ops/ms [Average]
  (min, avg, max) = (7.950, 8.026, 8.104), stdev = 0.077
  CI (99.9%): [6.624, 9.427] (assumes normal distribution)


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
# Warmup Iteration   1: 2.401 ops/ms
# Warmup Iteration   2: 5.790 ops/ms
# Warmup Iteration   3: 6.688 ops/ms
Iteration   1: 6.721 ops/ms
Iteration   2: 7.070 ops/ms
Iteration   3: 7.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.955 ±(99.9%) 3.694 ops/ms [Average]
  (min, avg, max) = (6.721, 6.955, 7.073), stdev = 0.203
  CI (99.9%): [3.260, 10.649] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.568 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.576 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.009 ms/op
Iteration   1: 4.153 ±(99.9%) 0.008 ms/op
Iteration   2: 3.920 ±(99.9%) 0.008 ms/op
Iteration   3: 3.916 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.996 ±(99.9%) 2.477 ms/op [Average]
  (min, avg, max) = (3.916, 3.996, 4.153), stdev = 0.136
  CI (99.9%): [1.519, 6.474] (assumes normal distribution)


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
# Warmup Iteration   1: 10.132 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.005 ms/op
Iteration   1: 3.706 ±(99.9%) 0.006 ms/op
Iteration   2: 3.769 ±(99.9%) 0.006 ms/op
Iteration   3: 3.750 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.742 ±(99.9%) 0.589 ms/op [Average]
  (min, avg, max) = (3.706, 3.742, 3.769), stdev = 0.032
  CI (99.9%): [3.153, 4.331] (assumes normal distribution)


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
# Warmup Iteration   1: 10.502 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.003 ms/op
Iteration   1: 3.997 ±(99.9%) 0.004 ms/op
Iteration   2: 4.006 ±(99.9%) 0.005 ms/op
Iteration   3: 3.842 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.949 ±(99.9%) 1.686 ms/op [Average]
  (min, avg, max) = (3.842, 3.949, 4.006), stdev = 0.092
  CI (99.9%): [2.262, 5.635] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.232 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.372 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.778 ±(99.9%) 0.008 ms/op
Iteration   1: 4.504 ±(99.9%) 0.009 ms/op
Iteration   2: 4.473 ±(99.9%) 0.010 ms/op
Iteration   3: 4.482 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.486 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (4.473, 4.486, 4.504), stdev = 0.016
  CI (99.9%): [4.196, 4.777] (assumes normal distribution)


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
# Warmup Iteration   1: 12.621 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 5.031 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.018 ms/op
Iteration   1: 3.937 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  12.294 ms/op
                 createUser·p0.9999: 26.370 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   2: 3.802 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  25.260 ms/op
                 createUser·p0.9999: 36.083 ms/op
                 createUser·p1.00:   37.093 ms/op

Iteration   3: 3.995 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.743 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  25.261 ms/op
                 createUser·p0.9999: 31.424 ms/op
                 createUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245380
  mean =      3.910 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 309 
    [ 2.500,  5.000) = 235668 
    [ 5.000,  7.500) = 7920 
    [ 7.500, 10.000) = 996 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 126 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     24.248 ms/op
     p(99.9900) =     32.287 ms/op
     p(99.9990) =     37.064 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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
# Warmup Iteration   1: 11.004 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.350 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.011 ms/op
Iteration   1: 3.782 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 25.416 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   2: 3.687 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.915 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.188 ms/op
                 existUser·p0.999:  10.129 ms/op
                 existUser·p0.9999: 29.895 ms/op
                 existUser·p1.00:   30.769 ms/op

Iteration   3: 3.779 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.806 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   6.401 ms/op
                 existUser·p0.999:  25.690 ms/op
                 existUser·p0.9999: 28.626 ms/op
                 existUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255991
  mean =      3.749 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 341 
    [ 2.500,  5.000) = 247554 
    [ 5.000,  7.500) = 6813 
    [ 7.500, 10.000) = 884 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.358 ms/op
     p(99.9000) =     14.271 ms/op
     p(99.9900) =     28.915 ms/op
     p(99.9990) =     30.677 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 12.261 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 5.008 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.390 ±(99.9%) 0.017 ms/op
Iteration   1: 3.951 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.815 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   7.528 ms/op
                 getUser·p0.999:  23.070 ms/op
                 getUser·p0.9999: 25.495 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   2: 3.974 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.269 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.854 ms/op
                 getUser·p0.999:  9.896 ms/op
                 getUser·p0.9999: 27.184 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 4.039 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  27.621 ms/op
                 getUser·p0.9999: 34.871 ms/op
                 getUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240553
  mean =      3.988 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 227723 
    [ 5.000,  7.500) = 11025 
    [ 7.500, 10.000) = 1241 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     23.083 ms/op
     p(99.9900) =     32.307 ms/op
     p(99.9990) =     36.516 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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
# Warmup Iteration   1: 15.672 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 5.641 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.780 ±(99.9%) 0.017 ms/op
Iteration   1: 4.767 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  24.835 ms/op
                 listUser·p0.9999: 26.837 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   2: 4.680 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  18.322 ms/op
                 listUser·p0.9999: 22.105 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   3: 4.630 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.728 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 19.426 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204349
  mean =      4.692 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 179158 
    [ 5.000,  7.500) = 20338 
    [ 7.500, 10.000) = 3742 
    [10.000, 12.500) = 506 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     20.097 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     27.487 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.973 ± 2.306  ops/ms
ClientPb.existUser                       thrpt       3   8.414 ± 1.063  ops/ms
ClientPb.getUser                         thrpt       3   8.026 ± 1.401  ops/ms
ClientPb.listUser                        thrpt       3   6.955 ± 3.694  ops/ms
ClientPb.createUser                       avgt       3   3.996 ± 2.477   ms/op
ClientPb.existUser                        avgt       3   3.742 ± 0.589   ms/op
ClientPb.getUser                          avgt       3   3.949 ± 1.686   ms/op
ClientPb.listUser                         avgt       3   4.486 ± 0.290   ms/op
ClientPb.createUser                     sample  245380   3.910 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.903           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.858           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.611           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.248           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.287           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.093           ms/op
ClientPb.existUser                      sample  255991   3.749 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.303           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.121           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.514           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.271           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.915           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.769           ms/op
ClientPb.getUser                        sample  240553   3.988 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.518           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.083           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.307           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.831           ms/op
ClientPb.listUser                       sample  204349   4.692 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.747           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.097           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.182           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.591           ms/op
