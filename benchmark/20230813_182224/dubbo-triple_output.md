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
# Warmup Iteration   1: 2.546 ops/ms
# Warmup Iteration   2: 6.249 ops/ms
# Warmup Iteration   3: 9.007 ops/ms
Iteration   1: 9.928 ops/ms
Iteration   2: 9.685 ops/ms
Iteration   3: 9.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.809 ±(99.9%) 2.216 ops/ms [Average]
  (min, avg, max) = (9.685, 9.809, 9.928), stdev = 0.121
  CI (99.9%): [7.594, 12.025] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.335 ops/ms
# Warmup Iteration   2: 9.066 ops/ms
# Warmup Iteration   3: 10.391 ops/ms
Iteration   1: 9.855 ops/ms
Iteration   2: 10.240 ops/ms
Iteration   3: 10.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.130 ±(99.9%) 4.368 ops/ms [Average]
  (min, avg, max) = (9.855, 10.130, 10.294), stdev = 0.239
  CI (99.9%): [5.761, 14.498] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.723 ops/ms
# Warmup Iteration   2: 8.408 ops/ms
# Warmup Iteration   3: 9.505 ops/ms
Iteration   1: 9.970 ops/ms
Iteration   2: 9.983 ops/ms
Iteration   3: 10.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.088 ±(99.9%) 3.539 ops/ms [Average]
  (min, avg, max) = (9.970, 10.088, 10.312), stdev = 0.194
  CI (99.9%): [6.549, 13.628] (assumes normal distribution)


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
# Warmup Iteration   1: 3.372 ops/ms
# Warmup Iteration   2: 7.904 ops/ms
# Warmup Iteration   3: 8.110 ops/ms
Iteration   1: 8.596 ops/ms
Iteration   2: 8.446 ops/ms
Iteration   3: 8.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.489 ±(99.9%) 1.695 ops/ms [Average]
  (min, avg, max) = (8.426, 8.489, 8.596), stdev = 0.093
  CI (99.9%): [6.794, 10.185] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.493 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.002 ms/op
Iteration   1: 3.310 ±(99.9%) 0.005 ms/op
Iteration   2: 3.255 ±(99.9%) 0.005 ms/op
Iteration   3: 3.169 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.245 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (3.169, 3.245, 3.310), stdev = 0.071
  CI (99.9%): [1.949, 4.541] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.433 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.005 ms/op
Iteration   1: 3.134 ±(99.9%) 0.005 ms/op
Iteration   2: 3.217 ±(99.9%) 0.007 ms/op
Iteration   3: 3.199 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.183 ±(99.9%) 0.795 ms/op [Average]
  (min, avg, max) = (3.134, 3.183, 3.217), stdev = 0.044
  CI (99.9%): [2.388, 3.978] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.403 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.004 ms/op
Iteration   1: 3.199 ±(99.9%) 0.003 ms/op
Iteration   2: 3.214 ±(99.9%) 0.002 ms/op
Iteration   3: 3.186 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.200 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (3.186, 3.200, 3.214), stdev = 0.014
  CI (99.9%): [2.951, 3.449] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.351 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.006 ms/op
Iteration   1: 3.907 ±(99.9%) 0.007 ms/op
Iteration   2: 3.759 ±(99.9%) 0.005 ms/op
Iteration   3: 3.804 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.823 ±(99.9%) 1.389 ms/op [Average]
  (min, avg, max) = (3.759, 3.823, 3.907), stdev = 0.076
  CI (99.9%): [2.434, 5.213] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.154 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.010 ms/op
Iteration   1: 3.273 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  15.176 ms/op
                 createUser·p0.9999: 20.120 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 3.217 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 28.412 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   3: 3.298 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.612 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  16.466 ms/op
                 createUser·p0.9999: 31.752 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294136
  mean =      3.262 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19652 
    [ 2.500,  5.000) = 267231 
    [ 5.000,  7.500) = 5669 
    [ 7.500, 10.000) = 1070 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     16.431 ms/op
     p(99.9900) =     28.238 ms/op
     p(99.9990) =     31.931 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.800 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.437 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.008 ms/op
Iteration   1: 3.142 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  14.700 ms/op
                 existUser·p0.9999: 20.873 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   2: 3.179 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  10.213 ms/op
                 existUser·p0.9999: 27.523 ms/op
                 existUser·p1.00:   28.508 ms/op

Iteration   3: 3.139 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   5.404 ms/op
                 existUser·p0.999:  17.730 ms/op
                 existUser·p0.9999: 21.686 ms/op
                 existUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304453
  mean =      3.153 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22383 
    [ 2.500,  5.000) = 274979 
    [ 5.000,  7.500) = 5593 
    [ 7.500, 10.000) = 1046 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     13.643 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.590 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.014 ms/op
Iteration   1: 3.305 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  14.438 ms/op
                 getUser·p0.9999: 26.028 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   2: 3.286 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.079 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  9.703 ms/op
                 getUser·p0.9999: 21.234 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   3: 3.259 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  13.449 ms/op
                 getUser·p0.9999: 21.856 ms/op
                 getUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292208
  mean =      3.284 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14790 
    [ 2.500,  5.000) = 268681 
    [ 5.000,  7.500) = 7435 
    [ 7.500, 10.000) = 947 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     24.004 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.829 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.014 ms/op
Iteration   1: 3.851 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  14.922 ms/op
                 listUser·p0.9999: 20.382 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   2: 3.796 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.759 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  13.833 ms/op
                 listUser·p0.9999: 20.859 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 3.811 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  11.698 ms/op
                 listUser·p0.9999: 14.746 ms/op
                 listUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251323
  mean =      3.819 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 242636 
    [ 5.000,  7.500) = 6163 
    [ 7.500, 10.000) = 1709 
    [10.000, 12.500) = 415 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     20.664 ms/op
     p(99.9990) =     21.216 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.809 ± 2.216  ops/ms
ClientPb.existUser                       thrpt       3  10.130 ± 4.368  ops/ms
ClientPb.getUser                         thrpt       3  10.088 ± 3.539  ops/ms
ClientPb.listUser                        thrpt       3   8.489 ± 1.695  ops/ms
ClientPb.createUser                       avgt       3   3.245 ± 1.296   ms/op
ClientPb.existUser                        avgt       3   3.183 ± 0.795   ms/op
ClientPb.getUser                          avgt       3   3.200 ± 0.249   ms/op
ClientPb.listUser                         avgt       3   3.823 ± 1.389   ms/op
ClientPb.createUser                     sample  294136   3.262 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.836           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.193           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.431           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.238           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  304453   3.153 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.922           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.111           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.643           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.313           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.508           ms/op
ClientPb.getUser                        sample  292208   3.284 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.846           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.943           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.004           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.132           ms/op
ClientPb.listUser                       sample  251323   3.819 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.315           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.730           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.664           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.282           ms/op
