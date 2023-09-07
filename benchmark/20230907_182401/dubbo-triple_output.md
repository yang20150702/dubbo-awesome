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
# Warmup Iteration   1: 1.460 ops/ms
# Warmup Iteration   2: 3.236 ops/ms
# Warmup Iteration   3: 6.414 ops/ms
Iteration   1: 7.109 ops/ms
Iteration   2: 7.236 ops/ms
Iteration   3: 6.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.034 ±(99.9%) 4.535 ops/ms [Average]
  (min, avg, max) = (6.756, 7.034, 7.236), stdev = 0.249
  CI (99.9%): [2.499, 11.568] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.835 ops/ms
# Warmup Iteration   2: 5.660 ops/ms
# Warmup Iteration   3: 6.978 ops/ms
Iteration   1: 7.276 ops/ms
Iteration   2: 7.545 ops/ms
Iteration   3: 7.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.546 ±(99.9%) 4.933 ops/ms [Average]
  (min, avg, max) = (7.276, 7.546, 7.817), stdev = 0.270
  CI (99.9%): [2.613, 12.479] (assumes normal distribution)


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
# Warmup Iteration   1: 1.754 ops/ms
# Warmup Iteration   2: 5.178 ops/ms
# Warmup Iteration   3: 6.760 ops/ms
Iteration   1: 7.072 ops/ms
Iteration   2: 6.873 ops/ms
Iteration   3: 7.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.283 ±(99.9%) 9.984 ops/ms [Average]
  (min, avg, max) = (6.873, 7.283, 7.905), stdev = 0.547
  CI (99.9%): [≈ 0, 17.268] (assumes normal distribution)


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
# Warmup Iteration   1: 2.027 ops/ms
# Warmup Iteration   2: 4.231 ops/ms
# Warmup Iteration   3: 5.899 ops/ms
Iteration   1: 5.952 ops/ms
Iteration   2: 5.658 ops/ms
Iteration   3: 6.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.976 ±(99.9%) 6.032 ops/ms [Average]
  (min, avg, max) = (5.658, 5.976, 6.318), stdev = 0.331
  CI (99.9%): [≈ 0, 12.008] (assumes normal distribution)


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
# Warmup Iteration   1: 14.482 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.551 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.639 ±(99.9%) 0.007 ms/op
Iteration   1: 4.266 ±(99.9%) 0.010 ms/op
Iteration   2: 4.897 ±(99.9%) 0.008 ms/op
Iteration   3: 4.593 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.585 ±(99.9%) 5.761 ms/op [Average]
  (min, avg, max) = (4.266, 4.585, 4.897), stdev = 0.316
  CI (99.9%): [≈ 0, 10.346] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.811 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.709 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.287 ±(99.9%) 0.008 ms/op
Iteration   1: 4.188 ±(99.9%) 0.004 ms/op
Iteration   2: 4.383 ±(99.9%) 0.006 ms/op
Iteration   3: 3.964 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.178 ±(99.9%) 3.825 ms/op [Average]
  (min, avg, max) = (3.964, 4.178, 4.383), stdev = 0.210
  CI (99.9%): [0.353, 8.003] (assumes normal distribution)


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
# Warmup Iteration   1: 13.534 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.080 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.004 ms/op
Iteration   1: 4.470 ±(99.9%) 0.006 ms/op
Iteration   2: 4.308 ±(99.9%) 0.007 ms/op
Iteration   3: 4.088 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.289 ±(99.9%) 3.498 ms/op [Average]
  (min, avg, max) = (4.088, 4.289, 4.470), stdev = 0.192
  CI (99.9%): [0.791, 7.786] (assumes normal distribution)


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
# Warmup Iteration   1: 16.667 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 6.363 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.139 ±(99.9%) 0.006 ms/op
Iteration   1: 4.811 ±(99.9%) 0.011 ms/op
Iteration   2: 4.671 ±(99.9%) 0.015 ms/op
Iteration   3: 4.934 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.805 ±(99.9%) 2.395 ms/op [Average]
  (min, avg, max) = (4.671, 4.805, 4.934), stdev = 0.131
  CI (99.9%): [2.410, 7.200] (assumes normal distribution)


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
# Warmup Iteration   1: 14.143 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.610 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.633 ±(99.9%) 0.021 ms/op
Iteration   1: 4.371 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.913 ms/op
                 createUser·p0.50:   4.035 ms/op
                 createUser·p0.90:   5.349 ms/op
                 createUser·p0.95:   6.111 ms/op
                 createUser·p0.99:   9.028 ms/op
                 createUser·p0.999:  25.224 ms/op
                 createUser·p0.9999: 28.639 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   2: 4.051 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.593 ms/op
                 createUser·p0.99:   7.504 ms/op
                 createUser·p0.999:  13.664 ms/op
                 createUser·p0.9999: 33.001 ms/op
                 createUser·p1.00:   33.620 ms/op

Iteration   3: 4.079 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.692 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   8.700 ms/op
                 createUser·p0.999:  30.573 ms/op
                 createUser·p0.9999: 33.323 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 230573
  mean =      4.162 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 208 
    [ 2.500,  5.000) = 205507 
    [ 5.000,  7.500) = 21479 
    [ 7.500, 10.000) = 2162 
    [10.000, 12.500) = 752 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 78 
    [32.500, 35.000) = 50 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     25.933 ms/op
     p(99.9900) =     32.963 ms/op
     p(99.9990) =     34.195 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 13.508 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.572 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.258 ±(99.9%) 0.015 ms/op
Iteration   1: 4.265 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.815 ms/op
                 existUser·p0.50:   3.953 ms/op
                 existUser·p0.90:   5.095 ms/op
                 existUser·p0.95:   6.496 ms/op
                 existUser·p0.99:   9.241 ms/op
                 existUser·p0.999:  19.268 ms/op
                 existUser·p0.9999: 27.476 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   2: 4.114 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.093 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   10.502 ms/op
                 existUser·p0.999:  19.642 ms/op
                 existUser·p0.9999: 28.934 ms/op
                 existUser·p1.00:   30.114 ms/op

Iteration   3: 4.099 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.966 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.669 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.832 ms/op
                 existUser·p0.999:  28.076 ms/op
                 existUser·p0.9999: 36.801 ms/op
                 existUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 231006
  mean =      4.158 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 220 
    [ 2.500,  5.000) = 211354 
    [ 5.000,  7.500) = 14705 
    [ 7.500, 10.000) = 3046 
    [10.000, 12.500) = 777 
    [12.500, 15.000) = 457 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.815 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     35.121 ms/op
     p(99.9990) =     37.618 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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
# Warmup Iteration   1: 12.948 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.858 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.301 ±(99.9%) 0.017 ms/op
Iteration   1: 4.225 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.778 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   6.595 ms/op
                 getUser·p0.99:   9.028 ms/op
                 getUser·p0.999:  24.188 ms/op
                 getUser·p0.9999: 26.968 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   2: 4.248 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.948 ms/op
                 getUser·p0.50:   4.002 ms/op
                 getUser·p0.90:   5.030 ms/op
                 getUser·p0.95:   6.119 ms/op
                 getUser·p0.99:   8.345 ms/op
                 getUser·p0.999:  20.001 ms/op
                 getUser·p0.9999: 30.573 ms/op
                 getUser·p1.00:   31.425 ms/op

Iteration   3: 4.119 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.860 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.603 ms/op
                 getUser·p0.99:   8.290 ms/op
                 getUser·p0.999:  29.208 ms/op
                 getUser·p0.9999: 41.531 ms/op
                 getUser·p1.00:   42.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 228697
  mean =      4.196 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 209492 
    [ 5.000, 10.000) = 17974 
    [10.000, 15.000) = 880 
    [15.000, 20.000) = 71 
    [20.000, 25.000) = 83 
    [25.000, 30.000) = 123 
    [30.000, 35.000) = 42 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     24.258 ms/op
     p(99.9900) =     40.051 ms/op
     p(99.9990) =     41.905 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


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
# Warmup Iteration   1: 16.714 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 6.197 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.256 ±(99.9%) 0.021 ms/op
Iteration   1: 5.098 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   7.766 ms/op
                 listUser·p0.99:   10.502 ms/op
                 listUser·p0.999:  25.411 ms/op
                 listUser·p0.9999: 28.467 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   2: 5.020 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.630 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   10.158 ms/op
                 listUser·p0.999:  24.846 ms/op
                 listUser·p0.9999: 31.355 ms/op
                 listUser·p1.00:   31.719 ms/op

Iteration   3: 4.848 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.414 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  19.890 ms/op
                 listUser·p0.9999: 23.783 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192403
  mean =      4.986 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 137555 
    [ 5.000,  7.500) = 46971 
    [ 7.500, 10.000) = 5822 
    [10.000, 12.500) = 1260 
    [12.500, 15.000) = 321 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.724 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      7.102 ms/op
     p(99.0000) =     10.141 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     30.491 ms/op
     p(99.9990) =     31.568 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.034 ± 4.535  ops/ms
ClientPb.existUser                       thrpt       3   7.546 ± 4.933  ops/ms
ClientPb.getUser                         thrpt       3   7.283 ± 9.984  ops/ms
ClientPb.listUser                        thrpt       3   5.976 ± 6.032  ops/ms
ClientPb.createUser                       avgt       3   4.585 ± 5.761   ms/op
ClientPb.existUser                        avgt       3   4.178 ± 3.825   ms/op
ClientPb.getUser                          avgt       3   4.289 ± 3.498   ms/op
ClientPb.listUser                         avgt       3   4.805 ± 2.395   ms/op
ClientPb.createUser                     sample  230573   4.162 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.118           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.438           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.933           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.963           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.275           ms/op
ClientPb.existUser                      sample  231006   4.158 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.815           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.817           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.906           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.978           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.251           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.121           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.880           ms/op
ClientPb.getUser                        sample  228697   4.196 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.778           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.038           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.618           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.258           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.051           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.009           ms/op
ClientPb.listUser                       sample  192403   4.986 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.724           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.141           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.626           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.491           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.719           ms/op
