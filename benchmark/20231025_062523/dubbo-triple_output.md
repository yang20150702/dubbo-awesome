# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.211 ops/ms
# Warmup Iteration   2: 3.103 ops/ms
# Warmup Iteration   3: 6.017 ops/ms
Iteration   1: 6.026 ops/ms
Iteration   2: 6.193 ops/ms
Iteration   3: 6.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.102 ±(99.9%) 1.540 ops/ms [Average]
  (min, avg, max) = (6.026, 6.102, 6.193), stdev = 0.084
  CI (99.9%): [4.562, 7.641] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.965 ops/ms
# Warmup Iteration   2: 6.106 ops/ms
# Warmup Iteration   3: 6.354 ops/ms
Iteration   1: 6.375 ops/ms
Iteration   2: 6.283 ops/ms
Iteration   3: 6.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.375 ±(99.9%) 1.688 ops/ms [Average]
  (min, avg, max) = (6.283, 6.375, 6.468), stdev = 0.093
  CI (99.9%): [4.687, 8.063] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.806 ops/ms
# Warmup Iteration   2: 4.850 ops/ms
# Warmup Iteration   3: 6.031 ops/ms
Iteration   1: 5.805 ops/ms
Iteration   2: 5.825 ops/ms
Iteration   3: 6.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.997 ±(99.9%) 5.740 ops/ms [Average]
  (min, avg, max) = (5.805, 5.997, 6.360), stdev = 0.315
  CI (99.9%): [0.257, 11.737] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.719 ops/ms
# Warmup Iteration   2: 4.559 ops/ms
# Warmup Iteration   3: 5.328 ops/ms
Iteration   1: 5.209 ops/ms
Iteration   2: 5.049 ops/ms
Iteration   3: 5.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.142 ±(99.9%) 1.524 ops/ms [Average]
  (min, avg, max) = (5.049, 5.142, 5.209), stdev = 0.084
  CI (99.9%): [3.619, 6.666] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 18.235 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 6.703 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.701 ±(99.9%) 0.009 ms/op
Iteration   1: 5.515 ±(99.9%) 0.012 ms/op
Iteration   2: 5.417 ±(99.9%) 0.013 ms/op
Iteration   3: 5.464 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.465 ±(99.9%) 0.894 ms/op [Average]
  (min, avg, max) = (5.417, 5.465, 5.515), stdev = 0.049
  CI (99.9%): [4.571, 6.359] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 18.305 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 6.273 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.259 ±(99.9%) 0.006 ms/op
Iteration   1: 5.133 ±(99.9%) 0.008 ms/op
Iteration   2: 4.979 ±(99.9%) 0.010 ms/op
Iteration   3: 4.906 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.006 ±(99.9%) 2.114 ms/op [Average]
  (min, avg, max) = (4.906, 5.006, 5.133), stdev = 0.116
  CI (99.9%): [2.892, 7.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.621 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.004 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.449 ±(99.9%) 0.008 ms/op
Iteration   1: 5.520 ±(99.9%) 0.011 ms/op
Iteration   2: 5.139 ±(99.9%) 0.009 ms/op
Iteration   3: 5.103 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.254 ±(99.9%) 4.220 ms/op [Average]
  (min, avg, max) = (5.103, 5.254, 5.520), stdev = 0.231
  CI (99.9%): [1.034, 9.474] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.377 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.172 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.243 ±(99.9%) 0.012 ms/op
Iteration   1: 6.001 ±(99.9%) 0.016 ms/op
Iteration   2: 6.186 ±(99.9%) 0.015 ms/op
Iteration   3: 6.394 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.194 ±(99.9%) 3.588 ms/op [Average]
  (min, avg, max) = (6.001, 6.194, 6.394), stdev = 0.197
  CI (99.9%): [2.606, 9.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.846 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 6.847 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.778 ±(99.9%) 0.027 ms/op
Iteration   1: 5.344 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.322 ms/op
                 createUser·p0.50:   5.030 ms/op
                 createUser·p0.90:   6.586 ms/op
                 createUser·p0.95:   7.553 ms/op
                 createUser·p0.99:   11.354 ms/op
                 createUser·p0.999:  25.466 ms/op
                 createUser·p0.9999: 28.971 ms/op
                 createUser·p1.00:   30.835 ms/op

Iteration   2: 5.348 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   5.071 ms/op
                 createUser·p0.90:   6.529 ms/op
                 createUser·p0.95:   7.463 ms/op
                 createUser·p0.99:   10.387 ms/op
                 createUser·p0.999:  24.070 ms/op
                 createUser·p0.9999: 30.704 ms/op
                 createUser·p1.00:   31.457 ms/op

Iteration   3: 5.357 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.036 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.586 ms/op
                 createUser·p0.95:   7.463 ms/op
                 createUser·p0.99:   11.239 ms/op
                 createUser·p0.999:  30.650 ms/op
                 createUser·p0.9999: 35.261 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179174
  mean =      5.350 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 84658 
    [ 5.000,  7.500) = 85580 
    [ 7.500, 10.000) = 6218 
    [10.000, 12.500) = 1638 
    [12.500, 15.000) = 502 
    [15.000, 17.500) = 222 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.516 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     26.706 ms/op
     p(99.9900) =     33.817 ms/op
     p(99.9990) =     35.419 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.899 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 5.939 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.039 ±(99.9%) 0.019 ms/op
Iteration   1: 4.946 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.351 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   6.169 ms/op
                 existUser·p0.95:   7.029 ms/op
                 existUser·p0.99:   9.486 ms/op
                 existUser·p0.999:  17.725 ms/op
                 existUser·p0.9999: 23.265 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   2: 5.044 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   4.792 ms/op
                 existUser·p0.90:   6.218 ms/op
                 existUser·p0.95:   7.241 ms/op
                 existUser·p0.99:   9.929 ms/op
                 existUser·p0.999:  20.860 ms/op
                 existUser·p0.9999: 27.951 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   3: 4.990 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.062 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   6.152 ms/op
                 existUser·p0.95:   7.094 ms/op
                 existUser·p0.99:   10.715 ms/op
                 existUser·p0.999:  26.277 ms/op
                 existUser·p0.9999: 29.740 ms/op
                 existUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 192113
  mean =      4.993 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 122163 
    [ 5.000,  7.500) = 62571 
    [ 7.500, 10.000) = 5383 
    [10.000, 12.500) = 1306 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.062 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.177 ms/op
     p(95.0000) =      7.111 ms/op
     p(99.0000) =     10.027 ms/op
     p(99.9000) =     21.001 ms/op
     p(99.9900) =     28.600 ms/op
     p(99.9990) =     30.187 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 14.881 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.010 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.301 ±(99.9%) 0.026 ms/op
Iteration   1: 5.202 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.294 ms/op
                 getUser·p0.50:   4.907 ms/op
                 getUser·p0.90:   6.431 ms/op
                 getUser·p0.95:   7.521 ms/op
                 getUser·p0.99:   11.059 ms/op
                 getUser·p0.999:  23.347 ms/op
                 getUser·p0.9999: 29.355 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   2: 5.008 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.030 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   6.070 ms/op
                 getUser·p0.95:   6.824 ms/op
                 getUser·p0.99:   9.535 ms/op
                 getUser·p0.999:  23.295 ms/op
                 getUser·p0.9999: 29.577 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   3: 5.040 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.030 ms/op
                 getUser·p0.50:   4.792 ms/op
                 getUser·p0.90:   6.103 ms/op
                 getUser·p0.95:   6.914 ms/op
                 getUser·p0.99:   9.863 ms/op
                 getUser·p0.999:  25.964 ms/op
                 getUser·p0.9999: 36.131 ms/op
                 getUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 188760
  mean =      5.082 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 111469 
    [ 5.000,  7.500) = 70028 
    [ 7.500, 10.000) = 5241 
    [10.000, 12.500) = 1241 
    [12.500, 15.000) = 355 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.030 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.210 ms/op
     p(95.0000) =      7.045 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     23.339 ms/op
     p(99.9900) =     34.415 ms/op
     p(99.9990) =     36.454 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.529 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 6.946 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.190 ±(99.9%) 0.025 ms/op
Iteration   1: 6.054 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.892 ms/op
                 listUser·p0.50:   5.734 ms/op
                 listUser·p0.90:   7.496 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  27.474 ms/op
                 listUser·p0.9999: 31.088 ms/op
                 listUser·p1.00:   32.637 ms/op

Iteration   2: 6.073 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.855 ms/op
                 listUser·p0.50:   5.734 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.864 ms/op
                 listUser·p0.99:   11.901 ms/op
                 listUser·p0.999:  29.306 ms/op
                 listUser·p0.9999: 31.206 ms/op
                 listUser·p1.00:   31.654 ms/op

Iteration   3: 5.848 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.993 ms/op
                 listUser·p0.50:   5.587 ms/op
                 listUser·p0.90:   7.045 ms/op
                 listUser·p0.95:   7.799 ms/op
                 listUser·p0.99:   10.322 ms/op
                 listUser·p0.999:  20.838 ms/op
                 listUser·p0.9999: 23.368 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 160201
  mean =      5.990 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 26714 
    [ 5.000,  7.500) = 119538 
    [ 7.500, 10.000) = 10618 
    [10.000, 12.500) = 2375 
    [12.500, 15.000) = 484 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.993 ms/op
     p(50.0000) =      5.685 ms/op
     p(90.0000) =      7.315 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     26.509 ms/op
     p(99.9900) =     30.703 ms/op
     p(99.9990) =     32.045 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.102 ± 1.540  ops/ms
ClientPb.existUser                       thrpt       3   6.375 ± 1.688  ops/ms
ClientPb.getUser                         thrpt       3   5.997 ± 5.740  ops/ms
ClientPb.listUser                        thrpt       3   5.142 ± 1.524  ops/ms
ClientPb.createUser                       avgt       3   5.465 ± 0.894   ms/op
ClientPb.existUser                        avgt       3   5.006 ± 2.114   ms/op
ClientPb.getUser                          avgt       3   5.254 ± 4.220   ms/op
ClientPb.listUser                         avgt       3   6.194 ± 3.588   ms/op
ClientPb.createUser                     sample  179174   5.350 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.516           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.046           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.570           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.496           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.059           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.706           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.817           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  192113   4.993 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.062           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.177           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.111           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.027           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.001           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.600           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.278           ms/op
ClientPb.getUser                        sample  188760   5.082 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.030           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.825           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.210           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.045           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.125           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.339           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.415           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.093           ms/op
ClientPb.listUser                       sample  160201   5.990 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.993           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.315           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.321           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.509           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.703           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.637           ms/op
