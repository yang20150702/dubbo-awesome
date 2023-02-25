# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.410 ops/ms
# Warmup Iteration   2: 5.962 ops/ms
# Warmup Iteration   3: 8.799 ops/ms
Iteration   1: 9.131 ops/ms
Iteration   2: 9.318 ops/ms
Iteration   3: 9.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.260 ±(99.9%) 2.043 ops/ms [Average]
  (min, avg, max) = (9.131, 9.260, 9.332), stdev = 0.112
  CI (99.9%): [7.218, 11.303] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.449 ops/ms
# Warmup Iteration   2: 9.098 ops/ms
# Warmup Iteration   3: 9.730 ops/ms
Iteration   1: 9.890 ops/ms
Iteration   2: 10.276 ops/ms
Iteration   3: 10.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.062 ±(99.9%) 3.588 ops/ms [Average]
  (min, avg, max) = (9.890, 10.062, 10.276), stdev = 0.197
  CI (99.9%): [6.474, 13.650] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.024 ops/ms
# Warmup Iteration   2: 8.663 ops/ms
# Warmup Iteration   3: 9.284 ops/ms
Iteration   1: 9.588 ops/ms
Iteration   2: 9.512 ops/ms
Iteration   3: 9.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.556 ±(99.9%) 0.717 ops/ms [Average]
  (min, avg, max) = (9.512, 9.556, 9.588), stdev = 0.039
  CI (99.9%): [8.839, 10.273] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.820 ops/ms
# Warmup Iteration   2: 7.100 ops/ms
# Warmup Iteration   3: 7.704 ops/ms
Iteration   1: 8.172 ops/ms
Iteration   2: 8.437 ops/ms
Iteration   3: 8.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.225 ±(99.9%) 3.502 ops/ms [Average]
  (min, avg, max) = (8.065, 8.225, 8.437), stdev = 0.192
  CI (99.9%): [4.723, 11.727] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.094 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.003 ms/op
Iteration   1: 3.397 ±(99.9%) 0.008 ms/op
Iteration   2: 3.382 ±(99.9%) 0.008 ms/op
Iteration   3: 3.363 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.381 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (3.363, 3.381, 3.397), stdev = 0.017
  CI (99.9%): [3.063, 3.699] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.848 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.005 ms/op
Iteration   1: 3.201 ±(99.9%) 0.012 ms/op
Iteration   2: 3.168 ±(99.9%) 0.009 ms/op
Iteration   3: 3.174 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.181 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (3.168, 3.181, 3.201), stdev = 0.018
  CI (99.9%): [2.860, 3.502] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.496 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.005 ms/op
Iteration   1: 3.296 ±(99.9%) 0.005 ms/op
Iteration   2: 3.190 ±(99.9%) 0.009 ms/op
Iteration   3: 3.257 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.248 ±(99.9%) 0.978 ms/op [Average]
  (min, avg, max) = (3.190, 3.248, 3.296), stdev = 0.054
  CI (99.9%): [2.269, 4.226] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.020 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.008 ms/op
Iteration   1: 3.897 ±(99.9%) 0.011 ms/op
Iteration   2: 3.906 ±(99.9%) 0.010 ms/op
Iteration   3: 3.884 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.895 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (3.884, 3.895, 3.906), stdev = 0.011
  CI (99.9%): [3.702, 4.089] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.796 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.010 ms/op
Iteration   1: 3.338 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  19.833 ms/op
                 createUser·p0.9999: 23.050 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   2: 3.379 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  21.543 ms/op
                 createUser·p0.9999: 24.561 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.530 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  18.311 ms/op
                 createUser·p0.9999: 23.656 ms/op
                 createUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281031
  mean =      3.414 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11610 
    [ 2.500,  5.000) = 262569 
    [ 5.000,  7.500) = 5649 
    [ 7.500, 10.000) = 680 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     23.983 ms/op
     p(99.9990) =     25.297 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.493 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.008 ms/op
Iteration   1: 3.275 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  11.163 ms/op
                 existUser·p0.9999: 22.585 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   2: 3.259 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  18.674 ms/op
                 existUser·p0.9999: 24.201 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   3: 3.414 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  17.190 ms/op
                 existUser·p0.9999: 23.929 ms/op
                 existUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289459
  mean =      3.314 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15399 
    [ 2.500,  5.000) = 268590 
    [ 5.000,  7.500) = 4733 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     17.155 ms/op
     p(99.9900) =     24.021 ms/op
     p(99.9990) =     24.807 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.503 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.010 ms/op
Iteration   1: 3.461 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  19.926 ms/op
                 getUser·p0.9999: 32.375 ms/op
                 getUser·p1.00:   32.834 ms/op

Iteration   2: 3.383 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  22.624 ms/op
                 getUser·p0.9999: 27.230 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   3: 3.344 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.697 ms/op
                 getUser·p0.999:  16.734 ms/op
                 getUser·p0.9999: 25.354 ms/op
                 getUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282685
  mean =      3.395 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4079 
    [ 2.500,  5.000) = 270951 
    [ 5.000,  7.500) = 6659 
    [ 7.500, 10.000) = 550 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     16.951 ms/op
     p(99.9900) =     30.629 ms/op
     p(99.9990) =     32.524 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.507 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.012 ms/op
Iteration   1: 4.001 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.817 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  19.990 ms/op
                 listUser·p0.9999: 25.494 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 3.904 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  14.078 ms/op
                 listUser·p0.9999: 17.688 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 3.875 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  14.737 ms/op
                 listUser·p0.9999: 20.668 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244438
  mean =      3.926 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 233932 
    [ 5.000,  7.500) = 7815 
    [ 7.500, 10.000) = 1851 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     15.246 ms/op
     p(99.9900) =     23.061 ms/op
     p(99.9990) =     25.839 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.260 ± 2.043  ops/ms
ClientPb.existUser                       thrpt       3  10.062 ± 3.588  ops/ms
ClientPb.getUser                         thrpt       3   9.556 ± 0.717  ops/ms
ClientPb.listUser                        thrpt       3   8.225 ± 3.502  ops/ms
ClientPb.createUser                       avgt       3   3.381 ± 0.318   ms/op
ClientPb.existUser                        avgt       3   3.181 ± 0.321   ms/op
ClientPb.getUser                          avgt       3   3.248 ± 0.978   ms/op
ClientPb.listUser                         avgt       3   3.895 ± 0.193   ms/op
ClientPb.createUser                     sample  281031   3.414 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.157           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.383           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.983           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.428           ms/op
ClientPb.existUser                      sample  289459   3.314 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.987           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.155           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.021           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.133           ms/op
ClientPb.getUser                        sample  282685   3.395 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.780           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.382           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.951           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.629           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.834           ms/op
ClientPb.listUser                       sample  244438   3.926 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.399           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.736           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.676           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.246           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.061           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.854           ms/op
