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
# Warmup Iteration   1: 2.343 ops/ms
# Warmup Iteration   2: 6.357 ops/ms
# Warmup Iteration   3: 9.019 ops/ms
Iteration   1: 9.657 ops/ms
Iteration   2: 9.863 ops/ms
Iteration   3: 9.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.720 ±(99.9%) 2.253 ops/ms [Average]
  (min, avg, max) = (9.641, 9.720, 9.863), stdev = 0.124
  CI (99.9%): [7.467, 11.973] (assumes normal distribution)


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
# Warmup Iteration   1: 3.485 ops/ms
# Warmup Iteration   2: 8.982 ops/ms
# Warmup Iteration   3: 10.227 ops/ms
Iteration   1: 9.821 ops/ms
Iteration   2: 10.124 ops/ms
Iteration   3: 10.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.189 ±(99.9%) 7.379 ops/ms [Average]
  (min, avg, max) = (9.821, 10.189, 10.622), stdev = 0.404
  CI (99.9%): [2.810, 17.567] (assumes normal distribution)


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
# Warmup Iteration   1: 3.017 ops/ms
# Warmup Iteration   2: 8.812 ops/ms
# Warmup Iteration   3: 9.256 ops/ms
Iteration   1: 9.683 ops/ms
Iteration   2: 9.951 ops/ms
Iteration   3: 10.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.888 ±(99.9%) 3.305 ops/ms [Average]
  (min, avg, max) = (9.683, 9.888, 10.029), stdev = 0.181
  CI (99.9%): [6.583, 13.192] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.998 ops/ms
# Warmup Iteration   2: 7.649 ops/ms
# Warmup Iteration   3: 8.386 ops/ms
Iteration   1: 8.513 ops/ms
Iteration   2: 8.522 ops/ms
Iteration   3: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.530 ±(99.9%) 0.393 ops/ms [Average]
  (min, avg, max) = (8.513, 8.530, 8.554), stdev = 0.022
  CI (99.9%): [8.137, 8.922] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.486 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.005 ms/op
Iteration   1: 3.232 ±(99.9%) 0.008 ms/op
Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
Iteration   3: 3.184 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.179 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (3.122, 3.179, 3.232), stdev = 0.055
  CI (99.9%): [2.179, 4.180] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.916 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.396 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.004 ms/op
Iteration   1: 3.052 ±(99.9%) 0.007 ms/op
Iteration   2: 3.100 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.051 ±(99.9%) 0.893 ms/op [Average]
  (min, avg, max) = (3.002, 3.051, 3.100), stdev = 0.049
  CI (99.9%): [2.158, 3.945] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.710 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.005 ms/op
Iteration   1: 3.314 ±(99.9%) 0.003 ms/op
Iteration   2: 3.197 ±(99.9%) 0.007 ms/op
Iteration   3: 3.309 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.274 ±(99.9%) 1.205 ms/op [Average]
  (min, avg, max) = (3.197, 3.274, 3.314), stdev = 0.066
  CI (99.9%): [2.069, 4.479] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.874 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.007 ms/op
Iteration   1: 3.785 ±(99.9%) 0.009 ms/op
Iteration   2: 3.764 ±(99.9%) 0.013 ms/op
Iteration   3: 3.834 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.795 ±(99.9%) 0.652 ms/op [Average]
  (min, avg, max) = (3.764, 3.795, 3.834), stdev = 0.036
  CI (99.9%): [3.142, 4.447] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.377 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.009 ms/op
Iteration   1: 3.264 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.422 ms/op
                 createUser·p0.999:  11.249 ms/op
                 createUser·p0.9999: 20.159 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.506 ms/op
                 createUser·p0.99:   5.095 ms/op
                 createUser·p0.999:  11.592 ms/op
                 createUser·p0.9999: 25.587 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   3: 3.220 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  16.413 ms/op
                 createUser·p0.9999: 27.525 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298653
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26801 
    [ 2.500,  5.000) = 267197 
    [ 5.000,  7.500) = 3817 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     26.134 ms/op
     p(99.9990) =     27.887 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 8.392 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.430 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.007 ms/op
Iteration   1: 3.064 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.364 ms/op
                 existUser·p0.9999: 21.987 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.364 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  8.725 ms/op
                 existUser·p0.9999: 22.395 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   3: 3.199 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  9.127 ms/op
                 existUser·p0.9999: 21.726 ms/op
                 existUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306956
  mean =      3.127 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27212 
    [ 2.500,  5.000) = 275238 
    [ 5.000,  7.500) = 4105 
    [ 7.500, 10.000) = 113 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 171 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      5.255 ms/op
     p(99.9000) =      8.948 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     24.473 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 9.407 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.600 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.008 ms/op
Iteration   1: 3.312 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  16.571 ms/op
                 getUser·p0.9999: 22.021 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   2: 3.286 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  11.677 ms/op
                 getUser·p0.9999: 22.889 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   3: 3.220 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  14.691 ms/op
                 getUser·p0.9999: 19.860 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293206
  mean =      3.272 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7041 
    [ 2.500,  5.000) = 277606 
    [ 5.000,  7.500) = 7400 
    [ 7.500, 10.000) = 702 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     23.501 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 9.514 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.760 ±(99.9%) 0.010 ms/op
Iteration   1: 3.863 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  17.902 ms/op
                 listUser·p0.9999: 21.478 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 3.813 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 3.773 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 17.220 ms/op
                 listUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251384
  mean =      3.816 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 242934 
    [ 5.000,  7.500) = 6242 
    [ 7.500, 10.000) = 1406 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     20.602 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.720 ± 2.253  ops/ms
ClientPb.existUser                       thrpt       3  10.189 ± 7.379  ops/ms
ClientPb.getUser                         thrpt       3   9.888 ± 3.305  ops/ms
ClientPb.listUser                        thrpt       3   8.530 ± 0.393  ops/ms
ClientPb.createUser                       avgt       3   3.179 ± 1.000   ms/op
ClientPb.existUser                        avgt       3   3.051 ± 0.893   ms/op
ClientPb.getUser                          avgt       3   3.274 ± 1.205   ms/op
ClientPb.listUser                         avgt       3   3.795 ± 0.652   ms/op
ClientPb.createUser                     sample  298653   3.211 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.682           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.926           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.134           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.017           ms/op
ClientPb.existUser                      sample  306956   3.127 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.288           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.255           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.948           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.020           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.740           ms/op
ClientPb.getUser                        sample  293206   3.272 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.892           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.745           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.086           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.986           ms/op
ClientPb.listUser                       sample  251384   3.816 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.867           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.174           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.516           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.602           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.217           ms/op
