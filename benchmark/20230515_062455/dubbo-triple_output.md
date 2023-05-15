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
# Warmup Iteration   1: 2.297 ops/ms
# Warmup Iteration   2: 6.100 ops/ms
# Warmup Iteration   3: 8.997 ops/ms
Iteration   1: 9.830 ops/ms
Iteration   2: 9.823 ops/ms
Iteration   3: 9.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.787 ±(99.9%) 1.247 ops/ms [Average]
  (min, avg, max) = (9.709, 9.787, 9.830), stdev = 0.068
  CI (99.9%): [8.540, 11.035] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.095 ops/ms
# Warmup Iteration   2: 8.888 ops/ms
# Warmup Iteration   3: 9.524 ops/ms
Iteration   1: 9.729 ops/ms
Iteration   2: 10.102 ops/ms
Iteration   3: 9.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.822 ±(99.9%) 4.512 ops/ms [Average]
  (min, avg, max) = (9.634, 9.822, 10.102), stdev = 0.247
  CI (99.9%): [5.310, 14.334] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.992 ops/ms
# Warmup Iteration   2: 8.865 ops/ms
# Warmup Iteration   3: 9.290 ops/ms
Iteration   1: 9.461 ops/ms
Iteration   2: 9.580 ops/ms
Iteration   3: 9.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.450 ±(99.9%) 2.475 ops/ms [Average]
  (min, avg, max) = (9.309, 9.450, 9.580), stdev = 0.136
  CI (99.9%): [6.975, 11.925] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.112 ops/ms
# Warmup Iteration   2: 7.386 ops/ms
# Warmup Iteration   3: 8.004 ops/ms
Iteration   1: 8.340 ops/ms
Iteration   2: 8.119 ops/ms
Iteration   3: 8.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.220 ±(99.9%) 2.043 ops/ms [Average]
  (min, avg, max) = (8.119, 8.220, 8.340), stdev = 0.112
  CI (99.9%): [6.177, 10.263] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.070 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.009 ms/op
Iteration   1: 3.469 ±(99.9%) 0.005 ms/op
Iteration   2: 3.337 ±(99.9%) 0.004 ms/op
Iteration   3: 3.375 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.394 ±(99.9%) 1.237 ms/op [Average]
  (min, avg, max) = (3.337, 3.394, 3.469), stdev = 0.068
  CI (99.9%): [2.157, 4.631] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.323 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.004 ms/op
Iteration   1: 3.168 ±(99.9%) 0.009 ms/op
Iteration   2: 3.250 ±(99.9%) 0.005 ms/op
Iteration   3: 3.264 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.227 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (3.168, 3.227, 3.264), stdev = 0.052
  CI (99.9%): [2.282, 4.173] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.130 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.006 ms/op
Iteration   1: 3.437 ±(99.9%) 0.006 ms/op
Iteration   2: 3.306 ±(99.9%) 0.009 ms/op
Iteration   3: 3.354 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.366 ±(99.9%) 1.215 ms/op [Average]
  (min, avg, max) = (3.306, 3.366, 3.437), stdev = 0.067
  CI (99.9%): [2.150, 4.581] (assumes normal distribution)


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
# Warmup Iteration   1: 8.824 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.249 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.008 ms/op
Iteration   1: 3.979 ±(99.9%) 0.006 ms/op
Iteration   2: 3.805 ±(99.9%) 0.011 ms/op
Iteration   3: 3.780 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.855 ±(99.9%) 1.979 ms/op [Average]
  (min, avg, max) = (3.780, 3.855, 3.979), stdev = 0.108
  CI (99.9%): [1.875, 5.834] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.034 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.010 ms/op
Iteration   1: 3.373 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.154 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  19.358 ms/op
                 createUser·p0.9999: 22.360 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.612 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.930 ms/op
                 createUser·p0.999:  12.718 ms/op
                 createUser·p0.9999: 26.137 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 3.470 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.794 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  15.726 ms/op
                 createUser·p0.9999: 21.940 ms/op
                 createUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284724
  mean =      3.367 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7404 
    [ 2.500,  5.000) = 272682 
    [ 5.000,  7.500) = 3607 
    [ 7.500, 10.000) = 603 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     15.750 ms/op
     p(99.9900) =     25.314 ms/op
     p(99.9990) =     27.727 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.471 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.007 ms/op
Iteration   1: 3.183 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.585 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  9.044 ms/op
                 existUser·p0.9999: 18.343 ms/op
                 existUser·p1.00:   19.792 ms/op

Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 20.578 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   3: 3.333 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.950 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  17.009 ms/op
                 existUser·p0.9999: 24.852 ms/op
                 existUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297325
  mean =      3.227 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14351 
    [ 2.500,  5.000) = 276630 
    [ 5.000,  7.500) = 5504 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =      9.978 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     25.921 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.707 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.012 ms/op
Iteration   1: 3.401 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  19.723 ms/op
                 getUser·p0.9999: 24.759 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 3.392 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  23.889 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   3: 3.391 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  12.829 ms/op
                 getUser·p0.9999: 24.529 ms/op
                 getUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282573
  mean =      3.395 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4541 
    [ 2.500,  5.000) = 272059 
    [ 5.000,  7.500) = 5041 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     14.743 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     26.052 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.708 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.013 ms/op
Iteration   1: 3.954 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 30.766 ms/op
                 listUser·p1.00:   31.261 ms/op

Iteration   2: 3.969 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.755 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  14.434 ms/op
                 listUser·p0.9999: 16.841 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   3: 3.831 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  15.885 ms/op
                 listUser·p0.9999: 20.644 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245039
  mean =      3.917 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 238314 
    [ 5.000,  7.500) = 4664 
    [ 7.500, 10.000) = 1252 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     15.597 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     31.082 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.787 ± 1.247  ops/ms
ClientPb.existUser                       thrpt       3   9.822 ± 4.512  ops/ms
ClientPb.getUser                         thrpt       3   9.450 ± 2.475  ops/ms
ClientPb.listUser                        thrpt       3   8.220 ± 2.043  ops/ms
ClientPb.createUser                       avgt       3   3.394 ± 1.237   ms/op
ClientPb.existUser                        avgt       3   3.227 ± 0.946   ms/op
ClientPb.getUser                          avgt       3   3.366 ± 1.215   ms/op
ClientPb.listUser                         avgt       3   3.855 ± 1.979   ms/op
ClientPb.createUser                     sample  284724   3.367 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.750           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.314           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.853           ms/op
ClientPb.existUser                      sample  297325   3.227 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.958           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.978           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.429           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.051           ms/op
ClientPb.getUser                        sample  282573   3.395 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.374           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.177           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.743           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.625           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.673           ms/op
ClientPb.listUser                       sample  245039   3.917 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.196           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.789           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.111           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.597           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.000           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.261           ms/op
