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
# Warmup Iteration   1: 0.966 ops/ms
# Warmup Iteration   2: 2.217 ops/ms
# Warmup Iteration   3: 4.453 ops/ms
Iteration   1: 5.131 ops/ms
Iteration   2: 5.259 ops/ms
Iteration   3: 5.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.346 ±(99.9%) 4.920 ops/ms [Average]
  (min, avg, max) = (5.131, 5.346, 5.649), stdev = 0.270
  CI (99.9%): [0.427, 10.266] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.321 ops/ms
# Warmup Iteration   2: 4.390 ops/ms
# Warmup Iteration   3: 5.694 ops/ms
Iteration   1: 5.628 ops/ms
Iteration   2: 5.757 ops/ms
Iteration   3: 5.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.688 ±(99.9%) 1.190 ops/ms [Average]
  (min, avg, max) = (5.628, 5.688, 5.757), stdev = 0.065
  CI (99.9%): [4.497, 6.878] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.455 ops/ms
# Warmup Iteration   2: 4.241 ops/ms
# Warmup Iteration   3: 5.291 ops/ms
Iteration   1: 5.557 ops/ms
Iteration   2: 5.344 ops/ms
Iteration   3: 5.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.400 ±(99.9%) 2.500 ops/ms [Average]
  (min, avg, max) = (5.301, 5.400, 5.557), stdev = 0.137
  CI (99.9%): [2.900, 7.900] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.356 ops/ms
# Warmup Iteration   2: 3.439 ops/ms
# Warmup Iteration   3: 4.498 ops/ms
Iteration   1: 4.541 ops/ms
Iteration   2: 4.642 ops/ms
Iteration   3: 4.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.560 ±(99.9%) 1.349 ops/ms [Average]
  (min, avg, max) = (4.498, 4.560, 4.642), stdev = 0.074
  CI (99.9%): [3.211, 5.910] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 21.790 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 9.176 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.358 ±(99.9%) 0.008 ms/op
Iteration   1: 6.130 ±(99.9%) 0.015 ms/op
Iteration   2: 6.137 ±(99.9%) 0.015 ms/op
Iteration   3: 6.015 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.094 ±(99.9%) 1.258 ms/op [Average]
  (min, avg, max) = (6.015, 6.094, 6.137), stdev = 0.069
  CI (99.9%): [4.836, 7.352] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 19.505 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 7.474 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.643 ±(99.9%) 0.014 ms/op
Iteration   1: 5.705 ±(99.9%) 0.007 ms/op
Iteration   2: 5.506 ±(99.9%) 0.010 ms/op
Iteration   3: 5.806 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.672 ±(99.9%) 2.787 ms/op [Average]
  (min, avg, max) = (5.506, 5.672, 5.806), stdev = 0.153
  CI (99.9%): [2.885, 8.460] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 20.402 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.283 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.112 ±(99.9%) 0.009 ms/op
Iteration   1: 5.954 ±(99.9%) 0.007 ms/op
Iteration   2: 6.000 ±(99.9%) 0.011 ms/op
Iteration   3: 5.801 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.919 ±(99.9%) 1.903 ms/op [Average]
  (min, avg, max) = (5.801, 5.919, 6.000), stdev = 0.104
  CI (99.9%): [4.015, 7.822] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.032 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 8.580 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 7.337 ±(99.9%) 0.009 ms/op
Iteration   1: 7.229 ±(99.9%) 0.018 ms/op
Iteration   2: 7.029 ±(99.9%) 0.010 ms/op
Iteration   3: 6.894 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.051 ±(99.9%) 3.074 ms/op [Average]
  (min, avg, max) = (6.894, 7.051, 7.229), stdev = 0.169
  CI (99.9%): [3.976, 10.125] (assumes normal distribution)


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
# Warmup Iteration   1: 20.294 ±(99.9%) 0.318 ms/op
# Warmup Iteration   2: 7.903 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.390 ±(99.9%) 0.034 ms/op
Iteration   1: 5.927 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.982 ms/op
                 createUser·p0.50:   5.595 ms/op
                 createUser·p0.90:   7.332 ms/op
                 createUser·p0.95:   8.421 ms/op
                 createUser·p0.99:   11.076 ms/op
                 createUser·p0.999:  25.952 ms/op
                 createUser·p0.9999: 29.643 ms/op
                 createUser·p1.00:   30.048 ms/op

Iteration   2: 5.848 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.253 ms/op
                 createUser·p0.50:   5.554 ms/op
                 createUser·p0.90:   7.086 ms/op
                 createUser·p0.95:   7.889 ms/op
                 createUser·p0.99:   11.354 ms/op
                 createUser·p0.999:  29.479 ms/op
                 createUser·p0.9999: 38.081 ms/op
                 createUser·p1.00:   38.601 ms/op

Iteration   3: 5.933 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.755 ms/op
                 createUser·p0.50:   5.661 ms/op
                 createUser·p0.90:   7.225 ms/op
                 createUser·p0.95:   8.192 ms/op
                 createUser·p0.99:   11.256 ms/op
                 createUser·p0.999:  28.907 ms/op
                 createUser·p0.9999: 38.535 ms/op
                 createUser·p1.00:   40.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 162613
  mean =      5.903 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 31895 
    [ 5.000, 10.000) = 127689 
    [10.000, 15.000) = 2611 
    [15.000, 20.000) = 194 
    [20.000, 25.000) = 33 
    [25.000, 30.000) = 107 
    [30.000, 35.000) = 46 
    [35.000, 40.000) = 37 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.755 ms/op
     p(50.0000) =      5.603 ms/op
     p(90.0000) =      7.225 ms/op
     p(95.0000) =      8.176 ms/op
     p(99.0000) =     11.223 ms/op
     p(99.9000) =     27.013 ms/op
     p(99.9900) =     37.683 ms/op
     p(99.9990) =     39.689 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.250 ±(99.9%) 0.338 ms/op
# Warmup Iteration   2: 6.841 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.673 ±(99.9%) 0.021 ms/op
Iteration   1: 5.642 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.535 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   6.988 ms/op
                 existUser·p0.95:   8.290 ms/op
                 existUser·p0.99:   11.321 ms/op
                 existUser·p0.999:  25.592 ms/op
                 existUser·p0.9999: 32.582 ms/op
                 existUser·p1.00:   33.128 ms/op

Iteration   2: 5.802 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.605 ms/op
                 existUser·p0.50:   5.431 ms/op
                 existUser·p0.90:   7.348 ms/op
                 existUser·p0.95:   8.380 ms/op
                 existUser·p0.99:   11.190 ms/op
                 existUser·p0.999:  28.144 ms/op
                 existUser·p0.9999: 32.882 ms/op
                 existUser·p1.00:   34.079 ms/op

Iteration   3: 5.734 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.314 ms/op
                 existUser·p0.50:   5.382 ms/op
                 existUser·p0.90:   7.029 ms/op
                 existUser·p0.95:   8.094 ms/op
                 existUser·p0.99:   12.321 ms/op
                 existUser·p0.999:  18.809 ms/op
                 existUser·p0.9999: 34.893 ms/op
                 existUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 167547
  mean =      5.725 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 51296 
    [ 5.000,  7.500) = 103292 
    [ 7.500, 10.000) = 9511 
    [10.000, 12.500) = 2359 
    [12.500, 15.000) = 603 
    [15.000, 17.500) = 236 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 75 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.314 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.135 ms/op
     p(95.0000) =      8.274 ms/op
     p(99.0000) =     11.583 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     33.145 ms/op
     p(99.9990) =     36.348 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.351 ±(99.9%) 0.362 ms/op
# Warmup Iteration   2: 8.134 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 6.093 ±(99.9%) 0.024 ms/op
Iteration   1: 6.107 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   5.636 ms/op
                 getUser·p0.90:   7.905 ms/op
                 getUser·p0.95:   9.388 ms/op
                 getUser·p0.99:   12.861 ms/op
                 getUser·p0.999:  22.479 ms/op
                 getUser·p0.9999: 25.445 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   2: 5.981 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.355 ms/op
                 getUser·p0.50:   5.562 ms/op
                 getUser·p0.90:   7.504 ms/op
                 getUser·p0.95:   9.044 ms/op
                 getUser·p0.99:   12.557 ms/op
                 getUser·p0.999:  25.083 ms/op
                 getUser·p0.9999: 28.923 ms/op
                 getUser·p1.00:   32.309 ms/op

Iteration   3: 6.005 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.294 ms/op
                 getUser·p0.50:   5.726 ms/op
                 getUser·p0.90:   7.381 ms/op
                 getUser·p0.95:   8.364 ms/op
                 getUser·p0.99:   10.895 ms/op
                 getUser·p0.999:  24.554 ms/op
                 getUser·p0.9999: 28.225 ms/op
                 getUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159166
  mean =      6.030 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 24526 
    [ 5.000,  7.500) = 117705 
    [ 7.500, 10.000) = 12638 
    [10.000, 12.500) = 2923 
    [12.500, 15.000) = 908 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      5.644 ms/op
     p(90.0000) =      7.602 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     12.206 ms/op
     p(99.9000) =     23.871 ms/op
     p(99.9900) =     28.606 ms/op
     p(99.9990) =     30.564 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 20.670 ±(99.9%) 0.367 ms/op
# Warmup Iteration   2: 9.190 ±(99.9%) 0.075 ms/op
# Warmup Iteration   3: 7.403 ±(99.9%) 0.036 ms/op
Iteration   1: 7.212 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   6.775 ms/op
                 listUser·p0.90:   8.880 ms/op
                 listUser·p0.95:   10.482 ms/op
                 listUser·p0.99:   13.910 ms/op
                 listUser·p0.999:  29.065 ms/op
                 listUser·p0.9999: 41.755 ms/op
                 listUser·p1.00:   42.140 ms/op

Iteration   2: 7.368 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   3.523 ms/op
                 listUser·p0.50:   6.922 ms/op
                 listUser·p0.90:   8.995 ms/op
                 listUser·p0.95:   10.666 ms/op
                 listUser·p0.99:   14.959 ms/op
                 listUser·p0.999:  31.657 ms/op
                 listUser·p0.9999: 34.843 ms/op
                 listUser·p1.00:   37.421 ms/op

Iteration   3: 7.503 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.744 ms/op
                 listUser·p0.50:   7.070 ms/op
                 listUser·p0.90:   9.404 ms/op
                 listUser·p0.95:   10.895 ms/op
                 listUser·p0.99:   14.598 ms/op
                 listUser·p0.999:  30.986 ms/op
                 listUser·p0.9999: 35.389 ms/op
                 listUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 130483
  mean =      7.359 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 921 
    [ 5.000, 10.000) = 120607 
    [10.000, 15.000) = 7918 
    [15.000, 20.000) = 717 
    [20.000, 25.000) = 59 
    [25.000, 30.000) = 108 
    [30.000, 35.000) = 112 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.109 ms/op
     p(50.0000) =      6.922 ms/op
     p(90.0000) =      9.093 ms/op
     p(95.0000) =     10.695 ms/op
     p(99.0000) =     14.582 ms/op
     p(99.9000) =     30.802 ms/op
     p(99.9900) =     40.364 ms/op
     p(99.9990) =     42.100 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.346 ± 4.920  ops/ms
ClientPb.existUser                       thrpt       3   5.688 ± 1.190  ops/ms
ClientPb.getUser                         thrpt       3   5.400 ± 2.500  ops/ms
ClientPb.listUser                        thrpt       3   4.560 ± 1.349  ops/ms
ClientPb.createUser                       avgt       3   6.094 ± 1.258   ms/op
ClientPb.existUser                        avgt       3   5.672 ± 2.787   ms/op
ClientPb.getUser                          avgt       3   5.919 ± 1.903   ms/op
ClientPb.listUser                         avgt       3   7.051 ± 3.074   ms/op
ClientPb.createUser                     sample  162613   5.903 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.755           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.176           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.223           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.013           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.683           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.632           ms/op
ClientPb.existUser                      sample  167547   5.725 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.314           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.135           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.274           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.583           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.808           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.145           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.569           ms/op
ClientPb.getUser                        sample  159166   6.030 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.028           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.644           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.602           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.946           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.206           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.871           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.606           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.309           ms/op
ClientPb.listUser                       sample  130483   7.359 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.109           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.922           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.093           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.695           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.582           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.802           ms/op
ClientPb.listUser:listUser·p0.9999      sample          40.364           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.140           ms/op
