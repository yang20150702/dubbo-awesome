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
# Warmup Iteration   1: 2.186 ops/ms
# Warmup Iteration   2: 5.385 ops/ms
# Warmup Iteration   3: 8.259 ops/ms
Iteration   1: 9.233 ops/ms
Iteration   2: 9.165 ops/ms
Iteration   3: 9.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.157 ±(99.9%) 1.486 ops/ms [Average]
  (min, avg, max) = (9.071, 9.157, 9.233), stdev = 0.081
  CI (99.9%): [7.671, 10.642] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.169 ops/ms
# Warmup Iteration   2: 8.899 ops/ms
# Warmup Iteration   3: 9.399 ops/ms
Iteration   1: 9.386 ops/ms
Iteration   2: 9.640 ops/ms
Iteration   3: 9.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.578 ±(99.9%) 3.112 ops/ms [Average]
  (min, avg, max) = (9.386, 9.578, 9.710), stdev = 0.171
  CI (99.9%): [6.467, 12.690] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.922 ops/ms
# Warmup Iteration   2: 8.214 ops/ms
# Warmup Iteration   3: 9.078 ops/ms
Iteration   1: 8.836 ops/ms
Iteration   2: 9.152 ops/ms
Iteration   3: 9.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.034 ±(99.9%) 3.143 ops/ms [Average]
  (min, avg, max) = (8.836, 9.034, 9.152), stdev = 0.172
  CI (99.9%): [5.891, 12.177] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.907 ops/ms
# Warmup Iteration   2: 7.020 ops/ms
# Warmup Iteration   3: 7.498 ops/ms
Iteration   1: 7.671 ops/ms
Iteration   2: 7.807 ops/ms
Iteration   3: 7.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.789 ±(99.9%) 1.990 ops/ms [Average]
  (min, avg, max) = (7.671, 7.789, 7.887), stdev = 0.109
  CI (99.9%): [5.799, 9.778] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.293 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.006 ms/op
Iteration   1: 3.475 ±(99.9%) 0.003 ms/op
Iteration   2: 3.581 ±(99.9%) 0.004 ms/op
Iteration   3: 3.528 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.528 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.475, 3.528, 3.581), stdev = 0.053
  CI (99.9%): [2.557, 4.499] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.730 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.005 ms/op
Iteration   1: 3.330 ±(99.9%) 0.004 ms/op
Iteration   2: 3.352 ±(99.9%) 0.004 ms/op
Iteration   3: 3.298 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.327 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (3.298, 3.327, 3.352), stdev = 0.027
  CI (99.9%): [2.831, 3.822] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.010 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.002 ms/op
Iteration   1: 3.550 ±(99.9%) 0.009 ms/op
Iteration   2: 3.527 ±(99.9%) 0.007 ms/op
Iteration   3: 3.630 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.569 ±(99.9%) 0.979 ms/op [Average]
  (min, avg, max) = (3.527, 3.569, 3.630), stdev = 0.054
  CI (99.9%): [2.590, 4.548] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.393 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.008 ms/op
Iteration   1: 4.146 ±(99.9%) 0.008 ms/op
Iteration   2: 4.126 ±(99.9%) 0.010 ms/op
Iteration   3: 4.051 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.108 ±(99.9%) 0.910 ms/op [Average]
  (min, avg, max) = (4.051, 4.108, 4.146), stdev = 0.050
  CI (99.9%): [3.198, 5.018] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.027 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.011 ms/op
Iteration   1: 3.801 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   7.717 ms/op
                 createUser·p0.999:  11.509 ms/op
                 createUser·p0.9999: 23.416 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   2: 3.445 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  23.574 ms/op
                 createUser·p0.9999: 28.269 ms/op
                 createUser·p1.00:   29.098 ms/op

Iteration   3: 3.401 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.777 ms/op
                 createUser·p0.999:  20.081 ms/op
                 createUser·p0.9999: 30.329 ms/op
                 createUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271204
  mean =      3.540 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4739 
    [ 2.500,  5.000) = 253959 
    [ 5.000,  7.500) = 10191 
    [ 7.500, 10.000) = 1637 
    [10.000, 12.500) = 398 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     28.606 ms/op
     p(99.9990) =     30.460 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.389 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.008 ms/op
Iteration   1: 3.513 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  21.760 ms/op
                 existUser·p0.9999: 24.734 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   2: 3.330 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.726 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   6.313 ms/op
                 existUser·p0.999:  23.554 ms/op
                 existUser·p0.9999: 30.572 ms/op
                 existUser·p1.00:   32.899 ms/op

Iteration   3: 3.455 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  19.110 ms/op
                 existUser·p0.9999: 30.474 ms/op
                 existUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279677
  mean =      3.431 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17989 
    [ 2.500,  5.000) = 253312 
    [ 5.000,  7.500) = 6661 
    [ 7.500, 10.000) = 1068 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     19.737 ms/op
     p(99.9900) =     30.279 ms/op
     p(99.9990) =     31.420 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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
# Warmup Iteration   1: 9.319 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.013 ms/op
Iteration   1: 3.511 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.848 ms/op
                 getUser·p0.99:   7.268 ms/op
                 getUser·p0.999:  21.525 ms/op
                 getUser·p0.9999: 26.141 ms/op
                 getUser·p1.00:   27.656 ms/op

Iteration   2: 3.401 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  22.557 ms/op
                 getUser·p0.9999: 26.743 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   3: 3.464 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  20.231 ms/op
                 getUser·p0.9999: 34.603 ms/op
                 getUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277571
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3864 
    [ 2.500,  5.000) = 263174 
    [ 5.000,  7.500) = 8578 
    [ 7.500, 10.000) = 1244 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     20.517 ms/op
     p(99.9900) =     33.150 ms/op
     p(99.9990) =     35.761 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 10.645 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.541 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.014 ms/op
Iteration   1: 4.138 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.853 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  20.093 ms/op
                 listUser·p0.9999: 29.131 ms/op
                 listUser·p1.00:   29.786 ms/op

Iteration   2: 4.139 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  14.248 ms/op
                 listUser·p0.9999: 21.137 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   3: 4.154 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 20.170 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231641
  mean =      4.144 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 219677 
    [ 5.000,  7.500) = 8545 
    [ 7.500, 10.000) = 2353 
    [10.000, 12.500) = 532 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     16.505 ms/op
     p(99.9900) =     27.454 ms/op
     p(99.9990) =     29.460 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.157 ± 1.486  ops/ms
ClientPb.existUser                       thrpt       3   9.578 ± 3.112  ops/ms
ClientPb.getUser                         thrpt       3   9.034 ± 3.143  ops/ms
ClientPb.listUser                        thrpt       3   7.789 ± 1.990  ops/ms
ClientPb.createUser                       avgt       3   3.528 ± 0.971   ms/op
ClientPb.existUser                        avgt       3   3.327 ± 0.495   ms/op
ClientPb.getUser                          avgt       3   3.569 ± 0.979   ms/op
ClientPb.listUser                         avgt       3   4.108 ± 0.910   ms/op
ClientPb.createUser                     sample  271204   3.540 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.188           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.874           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.373           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.698           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.606           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.999           ms/op
ClientPb.existUser                      sample  279677   3.431 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.356           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.317           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.619           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.737           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.279           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.899           ms/op
ClientPb.getUser                        sample  277571   3.458 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.900           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.517           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.150           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.979           ms/op
ClientPb.listUser                       sample  231641   4.144 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.853           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.030           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.505           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.454           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.786           ms/op
