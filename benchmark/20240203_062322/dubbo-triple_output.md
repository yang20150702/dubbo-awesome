# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.026 ops/ms
# Warmup Iteration   2: 12.212 ops/ms
# Warmup Iteration   3: 12.356 ops/ms
Iteration   1: 12.575 ops/ms
Iteration   2: 12.602 ops/ms
Iteration   3: 12.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.613 ±(99.9%) 0.807 ops/ms [Average]
  (min, avg, max) = (12.575, 12.613, 12.662), stdev = 0.044
  CI (99.9%): [11.806, 13.420] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.561 ops/ms
# Warmup Iteration   2: 13.037 ops/ms
# Warmup Iteration   3: 13.026 ops/ms
Iteration   1: 13.000 ops/ms
Iteration   2: 13.037 ops/ms
Iteration   3: 12.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.996 ±(99.9%) 0.789 ops/ms [Average]
  (min, avg, max) = (12.951, 12.996, 13.037), stdev = 0.043
  CI (99.9%): [12.207, 13.785] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.513 ops/ms
# Warmup Iteration   2: 12.751 ops/ms
# Warmup Iteration   3: 12.913 ops/ms
Iteration   1: 12.788 ops/ms
Iteration   2: 13.070 ops/ms
Iteration   3: 13.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.959 ±(99.9%) 2.747 ops/ms [Average]
  (min, avg, max) = (12.788, 12.959, 13.070), stdev = 0.151
  CI (99.9%): [10.213, 15.706] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.514 ops/ms
# Warmup Iteration   2: 10.615 ops/ms
# Warmup Iteration   3: 10.627 ops/ms
Iteration   1: 10.676 ops/ms
Iteration   2: 10.602 ops/ms
Iteration   3: 10.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.654 ±(99.9%) 0.821 ops/ms [Average]
  (min, avg, max) = (10.602, 10.654, 10.684), stdev = 0.045
  CI (99.9%): [9.833, 11.475] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.940 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.566 ±(99.9%) 0.004 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.538 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (2.519, 2.538, 2.566), stdev = 0.025
  CI (99.9%): [2.087, 2.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.751 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.463 ±(99.9%) 0.112 ms/op [Average]
  (min, avg, max) = (2.456, 2.463, 2.468), stdev = 0.006
  CI (99.9%): [2.351, 2.575] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.003 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.059 ms/op [Average]
  (min, avg, max) = (2.499, 2.502, 2.505), stdev = 0.003
  CI (99.9%): [2.443, 2.561] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.647 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 2.973 ±(99.9%) 0.006 ms/op
Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
Iteration   3: 2.979 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.969 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.956, 2.969, 2.979), stdev = 0.012
  CI (99.9%): [2.750, 3.188] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.218 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
Iteration   1: 2.551 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  10.915 ms/op
                 createUser·p0.9999: 13.999 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  9.368 ms/op
                 createUser·p0.9999: 12.082 ms/op
                 createUser·p1.00:   12.435 ms/op

Iteration   3: 2.559 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.858 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 10.707 ms/op
                 createUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375314
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 178394 
    [ 2.500,  3.750) = 192706 
    [ 3.750,  5.000) = 3327 
    [ 5.000,  6.250) = 330 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      9.312 ms/op
     p(99.9900) =     13.246 ms/op
     p(99.9990) =     14.872 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.651 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.023 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  6.313 ms/op
                 existUser·p0.9999: 13.944 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  8.034 ms/op
                 existUser·p0.9999: 12.829 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  7.992 ms/op
                 existUser·p0.9999: 10.469 ms/op
                 existUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387445
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 192878 
    [ 2.500,  3.750) = 188895 
    [ 3.750,  5.000) = 4380 
    [ 5.000,  6.250) = 616 
    [ 6.250,  7.500) = 148 
    [ 7.500,  8.750) = 90 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =      7.995 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.158 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.847 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  11.230 ms/op
                 getUser·p0.9999: 13.704 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  6.249 ms/op
                 getUser·p0.9999: 12.567 ms/op
                 getUser·p1.00:   13.025 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 12.556 ms/op
                 getUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378730
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 185160 
    [ 2.500,  3.750) = 189499 
    [ 3.750,  5.000) = 3249 
    [ 5.000,  6.250) = 343 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      7.644 ms/op
     p(99.9900) =     12.845 ms/op
     p(99.9990) =     14.205 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.493 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
Iteration   1: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.033 ms/op
                 listUser·p0.9999: 11.378 ms/op
                 listUser·p1.00:   12.550 ms/op

Iteration   2: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 12.962 ms/op
                 listUser·p1.00:   13.877 ms/op

Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  8.933 ms/op
                 listUser·p0.9999: 11.064 ms/op
                 listUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318883
  mean =      3.008 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 91407 
    [ 2.500,  3.750) = 189630 
    [ 3.750,  5.000) = 31145 
    [ 5.000,  6.250) = 5337 
    [ 6.250,  7.500) = 537 
    [ 7.500,  8.750) = 269 
    [ 8.750, 10.000) = 270 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     12.290 ms/op
     p(99.9990) =     13.825 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.613 ± 0.807  ops/ms
ClientPb.existUser                       thrpt       3  12.996 ± 0.789  ops/ms
ClientPb.getUser                         thrpt       3  12.959 ± 2.747  ops/ms
ClientPb.listUser                        thrpt       3  10.654 ± 0.821  ops/ms
ClientPb.createUser                       avgt       3   2.538 ± 0.451   ms/op
ClientPb.existUser                        avgt       3   2.463 ± 0.112   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.059   ms/op
ClientPb.listUser                         avgt       3   2.969 ± 0.219   ms/op
ClientPb.createUser                     sample  375314   2.555 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.796           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.312           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.246           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.303           ms/op
ClientPb.existUser                      sample  387445   2.475 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.718           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.995           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.713           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.909           ms/op
ClientPb.getUser                        sample  378730   2.533 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.932           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.644           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.845           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.434           ms/op
ClientPb.listUser                       sample  318883   3.008 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.842           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.290           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.877           ms/op
