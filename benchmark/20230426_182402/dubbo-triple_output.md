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
# Warmup Iteration   1: 1.112 ops/ms
# Warmup Iteration   2: 2.877 ops/ms
# Warmup Iteration   3: 5.513 ops/ms
Iteration   1: 5.774 ops/ms
Iteration   2: 5.981 ops/ms
Iteration   3: 5.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.887 ±(99.9%) 1.917 ops/ms [Average]
  (min, avg, max) = (5.774, 5.887, 5.981), stdev = 0.105
  CI (99.9%): [3.970, 7.805] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.631 ops/ms
# Warmup Iteration   2: 5.157 ops/ms
# Warmup Iteration   3: 5.887 ops/ms
Iteration   1: 6.040 ops/ms
Iteration   2: 6.022 ops/ms
Iteration   3: 6.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.023 ±(99.9%) 0.296 ops/ms [Average]
  (min, avg, max) = (6.008, 6.023, 6.040), stdev = 0.016
  CI (99.9%): [5.727, 6.319] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.585 ops/ms
# Warmup Iteration   2: 4.306 ops/ms
# Warmup Iteration   3: 5.647 ops/ms
Iteration   1: 5.801 ops/ms
Iteration   2: 5.682 ops/ms
Iteration   3: 5.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.775 ±(99.9%) 1.527 ops/ms [Average]
  (min, avg, max) = (5.682, 5.775, 5.844), stdev = 0.084
  CI (99.9%): [4.248, 7.302] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.580 ops/ms
# Warmup Iteration   2: 3.569 ops/ms
# Warmup Iteration   3: 4.819 ops/ms
Iteration   1: 4.952 ops/ms
Iteration   2: 5.011 ops/ms
Iteration   3: 4.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.959 ±(99.9%) 0.904 ops/ms [Average]
  (min, avg, max) = (4.912, 4.959, 5.011), stdev = 0.050
  CI (99.9%): [4.055, 5.863] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 19.967 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 6.756 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.712 ±(99.9%) 0.006 ms/op
Iteration   1: 5.581 ±(99.9%) 0.015 ms/op
Iteration   2: 5.486 ±(99.9%) 0.013 ms/op
Iteration   3: 5.445 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.504 ±(99.9%) 1.268 ms/op [Average]
  (min, avg, max) = (5.445, 5.504, 5.581), stdev = 0.070
  CI (99.9%): [4.236, 6.772] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.174 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.867 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.364 ±(99.9%) 0.009 ms/op
Iteration   1: 5.468 ±(99.9%) 0.010 ms/op
Iteration   2: 5.514 ±(99.9%) 0.013 ms/op
Iteration   3: 5.156 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.379 ±(99.9%) 3.554 ms/op [Average]
  (min, avg, max) = (5.156, 5.379, 5.514), stdev = 0.195
  CI (99.9%): [1.825, 8.934] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 17.260 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.702 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.668 ±(99.9%) 0.006 ms/op
Iteration   1: 5.484 ±(99.9%) 0.009 ms/op
Iteration   2: 5.247 ±(99.9%) 0.012 ms/op
Iteration   3: 5.211 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.314 ±(99.9%) 2.706 ms/op [Average]
  (min, avg, max) = (5.211, 5.314, 5.484), stdev = 0.148
  CI (99.9%): [2.609, 8.020] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 19.898 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 8.460 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.483 ±(99.9%) 0.015 ms/op
Iteration   1: 6.501 ±(99.9%) 0.009 ms/op
Iteration   2: 6.278 ±(99.9%) 0.020 ms/op
Iteration   3: 5.564 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.114 ±(99.9%) 8.926 ms/op [Average]
  (min, avg, max) = (5.564, 6.114, 6.501), stdev = 0.489
  CI (99.9%): [≈ 0, 15.040] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 15.334 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 6.810 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.207 ±(99.9%) 0.031 ms/op
Iteration   1: 5.511 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.695 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.881 ms/op
                 createUser·p0.95:   7.971 ms/op
                 createUser·p0.99:   10.715 ms/op
                 createUser·p0.999:  25.261 ms/op
                 createUser·p0.9999: 35.088 ms/op
                 createUser·p1.00:   37.290 ms/op

Iteration   2: 5.464 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.808 ms/op
                 createUser·p0.95:   7.654 ms/op
                 createUser·p0.99:   10.500 ms/op
                 createUser·p0.999:  24.132 ms/op
                 createUser·p0.9999: 30.611 ms/op
                 createUser·p1.00:   33.948 ms/op

Iteration   3: 5.468 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   6.865 ms/op
                 createUser·p0.95:   7.741 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  16.236 ms/op
                 createUser·p0.9999: 29.417 ms/op
                 createUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175063
  mean =      5.481 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 67308 
    [ 5.000,  7.500) = 97048 
    [ 7.500, 10.000) = 8360 
    [10.000, 12.500) = 1564 
    [12.500, 15.000) = 399 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     32.866 ms/op
     p(99.9990) =     36.060 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 16.027 ±(99.9%) 0.246 ms/op
# Warmup Iteration   2: 6.004 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.436 ±(99.9%) 0.020 ms/op
Iteration   1: 5.242 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.521 ms/op
                 existUser·p0.95:   7.750 ms/op
                 existUser·p0.99:   10.682 ms/op
                 existUser·p0.999:  25.325 ms/op
                 existUser·p0.9999: 28.585 ms/op
                 existUser·p1.00:   31.588 ms/op

Iteration   2: 5.077 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   6.996 ms/op
                 existUser·p0.99:   9.454 ms/op
                 existUser·p0.999:  25.723 ms/op
                 existUser·p0.9999: 31.549 ms/op
                 existUser·p1.00:   32.047 ms/op

Iteration   3: 5.289 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.343 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.210 ms/op
                 existUser·p0.95:   7.037 ms/op
                 existUser·p0.99:   10.311 ms/op
                 existUser·p0.999:  15.180 ms/op
                 existUser·p0.9999: 31.225 ms/op
                 existUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184569
  mean =      5.201 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 100236 
    [ 5.000,  7.500) = 76213 
    [ 7.500, 10.000) = 6044 
    [10.000, 12.500) = 1372 
    [12.500, 15.000) = 431 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.250 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     15.785 ms/op
     p(99.9900) =     31.147 ms/op
     p(99.9990) =     32.274 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.530 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.257 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.376 ±(99.9%) 0.020 ms/op
Iteration   1: 5.354 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.032 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.357 ms/op
                 getUser·p0.95:   8.036 ms/op
                 getUser·p0.99:   11.862 ms/op
                 getUser·p0.999:  23.143 ms/op
                 getUser·p0.9999: 27.002 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   2: 5.422 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.693 ms/op
                 getUser·p0.95:   7.610 ms/op
                 getUser·p0.99:   11.092 ms/op
                 getUser·p0.999:  27.918 ms/op
                 getUser·p0.9999: 47.782 ms/op
                 getUser·p1.00:   48.890 ms/op

Iteration   3: 5.325 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.486 ms/op
                 getUser·p0.50:   5.063 ms/op
                 getUser·p0.90:   6.382 ms/op
                 getUser·p0.95:   7.397 ms/op
                 getUser·p0.99:   10.256 ms/op
                 getUser·p0.999:  29.284 ms/op
                 getUser·p0.9999: 33.522 ms/op
                 getUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 178798
  mean =      5.367 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 82845 
    [ 5.000, 10.000) = 93374 
    [10.000, 15.000) = 2198 
    [15.000, 20.000) = 185 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 74 
    [30.000, 35.000) = 63 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.790 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.513 ms/op
     p(95.0000) =      7.684 ms/op
     p(99.0000) =     10.863 ms/op
     p(99.9000) =     24.550 ms/op
     p(99.9900) =     45.613 ms/op
     p(99.9990) =     48.322 ms/op
     p(99.9999) =     48.890 ms/op
    p(100.0000) =     48.890 ms/op


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
# Warmup Iteration   1: 18.310 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 7.157 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.433 ±(99.9%) 0.026 ms/op
Iteration   1: 6.364 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.367 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   7.397 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   11.796 ms/op
                 listUser·p0.999:  28.346 ms/op
                 listUser·p0.9999: 31.750 ms/op
                 listUser·p1.00:   32.178 ms/op

Iteration   2: 6.105 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.920 ms/op
                 listUser·p0.50:   5.800 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.372 ms/op
                 listUser·p0.99:   11.829 ms/op
                 listUser·p0.999:  29.524 ms/op
                 listUser·p0.9999: 32.958 ms/op
                 listUser·p1.00:   34.013 ms/op

Iteration   3: 6.247 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.830 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  23.356 ms/op
                 listUser·p0.9999: 26.071 ms/op
                 listUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153882
  mean =      6.237 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 7329 
    [ 5.000,  7.500) = 133288 
    [ 7.500, 10.000) = 9892 
    [10.000, 12.500) = 2397 
    [12.500, 15.000) = 525 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.830 ms/op
     p(50.0000) =      5.939 ms/op
     p(90.0000) =      7.307 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     11.521 ms/op
     p(99.9000) =     27.267 ms/op
     p(99.9900) =     31.661 ms/op
     p(99.9990) =     33.978 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.887 ± 1.917  ops/ms
ClientPb.existUser                       thrpt       3   6.023 ± 0.296  ops/ms
ClientPb.getUser                         thrpt       3   5.775 ± 1.527  ops/ms
ClientPb.listUser                        thrpt       3   4.959 ± 0.904  ops/ms
ClientPb.createUser                       avgt       3   5.504 ± 1.268   ms/op
ClientPb.existUser                        avgt       3   5.379 ± 3.554   ms/op
ClientPb.getUser                          avgt       3   5.314 ± 2.706   ms/op
ClientPb.listUser                         avgt       3   6.114 ± 8.926   ms/op
ClientPb.createUser                     sample  175063   5.481 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.135           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.849           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.799           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.633           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.531           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.866           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.290           ms/op
ClientPb.existUser                      sample  184569   5.201 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.165           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.940           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.267           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.250           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.207           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.785           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.147           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.440           ms/op
ClientPb.getUser                        sample  178798   5.367 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.790           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.063           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.684           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.863           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.550           ms/op
ClientPb.getUser:getUser·p0.9999        sample          45.613           ms/op
ClientPb.getUser:getUser·p1.00          sample          48.890           ms/op
ClientPb.listUser                       sample  153882   6.237 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.830           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.939           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.307           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.421           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.521           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.267           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.661           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.013           ms/op
