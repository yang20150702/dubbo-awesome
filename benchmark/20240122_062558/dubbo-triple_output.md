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
# Warmup Iteration   1: 4.486 ops/ms
# Warmup Iteration   2: 12.051 ops/ms
# Warmup Iteration   3: 12.472 ops/ms
Iteration   1: 12.549 ops/ms
Iteration   2: 12.647 ops/ms
Iteration   3: 12.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.625 ±(99.9%) 1.223 ops/ms [Average]
  (min, avg, max) = (12.549, 12.625, 12.678), stdev = 0.067
  CI (99.9%): [11.402, 13.848] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.112 ops/ms
# Warmup Iteration   2: 12.968 ops/ms
# Warmup Iteration   3: 12.888 ops/ms
Iteration   1: 12.957 ops/ms
Iteration   2: 12.967 ops/ms
Iteration   3: 13.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.976 ±(99.9%) 0.455 ops/ms [Average]
  (min, avg, max) = (12.957, 12.976, 13.004), stdev = 0.025
  CI (99.9%): [12.521, 13.431] (assumes normal distribution)


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
# Warmup Iteration   1: 7.229 ops/ms
# Warmup Iteration   2: 12.575 ops/ms
# Warmup Iteration   3: 12.723 ops/ms
Iteration   1: 12.966 ops/ms
Iteration   2: 12.938 ops/ms
Iteration   3: 12.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.921 ±(99.9%) 1.007 ops/ms [Average]
  (min, avg, max) = (12.859, 12.921, 12.966), stdev = 0.055
  CI (99.9%): [11.914, 13.928] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.581 ops/ms
# Warmup Iteration   2: 10.240 ops/ms
# Warmup Iteration   3: 10.468 ops/ms
Iteration   1: 10.433 ops/ms
Iteration   2: 10.515 ops/ms
Iteration   3: 10.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.448 ±(99.9%) 1.127 ops/ms [Average]
  (min, avg, max) = (10.395, 10.448, 10.515), stdev = 0.062
  CI (99.9%): [9.321, 11.574] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.985 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.003 ms/op
Iteration   2: 2.581 ±(99.9%) 0.005 ms/op
Iteration   3: 2.561 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (2.534, 2.558, 2.581), stdev = 0.024
  CI (99.9%): [2.128, 2.989] (assumes normal distribution)


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.453 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (2.441, 2.453, 2.471), stdev = 0.016
  CI (99.9%): [2.158, 2.748] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.117 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.508 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (2.485, 2.508, 2.523), stdev = 0.020
  CI (99.9%): [2.141, 2.876] (assumes normal distribution)


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
# Warmup Iteration   1: 4.611 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.005 ms/op
Iteration   1: 3.009 ±(99.9%) 0.004 ms/op
Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
Iteration   3: 2.982 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.982, 2.991, 3.009), stdev = 0.016
  CI (99.9%): [2.704, 3.278] (assumes normal distribution)


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  10.501 ms/op
                 createUser·p0.9999: 13.979 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  9.102 ms/op
                 createUser·p0.9999: 12.753 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  8.160 ms/op
                 createUser·p0.9999: 10.030 ms/op
                 createUser·p1.00:   10.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384048
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 185916 
    [ 2.500,  3.750) = 193963 
    [ 3.750,  5.000) = 3313 
    [ 5.000,  6.250) = 389 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.183 ms/op
     p(99.9900) =     13.248 ms/op
     p(99.9990) =     14.527 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 3.674 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  5.922 ms/op
                 existUser·p0.9999: 13.468 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  6.584 ms/op
                 existUser·p0.9999: 13.712 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  8.809 ms/op
                 existUser·p0.9999: 11.532 ms/op
                 existUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390886
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 192370 
    [ 2.500,  3.750) = 195173 
    [ 3.750,  5.000) = 2468 
    [ 5.000,  6.250) = 392 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     13.352 ms/op
     p(99.9990) =     14.525 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 4.118 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
Iteration   1: 2.540 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  11.443 ms/op
                 getUser·p0.9999: 13.955 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.600 ms/op
                 getUser·p0.999:  8.380 ms/op
                 getUser·p0.9999: 13.751 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  8.641 ms/op
                 getUser·p0.9999: 11.891 ms/op
                 getUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379081
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 187020 
    [ 2.500,  3.750) = 188338 
    [ 3.750,  5.000) = 2991 
    [ 5.000,  6.250) = 265 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     14.552 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 4.765 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.009 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.876 ms/op
                 listUser·p0.9999: 11.819 ms/op
                 listUser·p1.00:   13.795 ms/op

Iteration   2: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.077 ms/op
                 listUser·p0.9999: 12.039 ms/op
                 listUser·p1.00:   12.698 ms/op

Iteration   3: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.333 ms/op
                 listUser·p0.9999: 12.237 ms/op
                 listUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317371
  mean =      3.022 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 90157 
    [ 2.500,  3.750) = 186923 
    [ 3.750,  5.000) = 32938 
    [ 5.000,  6.250) = 5885 
    [ 6.250,  7.500) = 687 
    [ 7.500,  8.750) = 210 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     11.960 ms/op
     p(99.9990) =     13.209 ms/op
     p(99.9999) =     13.795 ms/op
    p(100.0000) =     13.795 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.625 ± 1.223  ops/ms
ClientPb.existUser                       thrpt       3  12.976 ± 0.455  ops/ms
ClientPb.getUser                         thrpt       3  12.921 ± 1.007  ops/ms
ClientPb.listUser                        thrpt       3  10.448 ± 1.127  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.431   ms/op
ClientPb.existUser                        avgt       3   2.453 ± 0.295   ms/op
ClientPb.getUser                          avgt       3   2.508 ± 0.368   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.287   ms/op
ClientPb.createUser                     sample  384048   2.498 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.805           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.183           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.248           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.615           ms/op
ClientPb.existUser                      sample  390886   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.911           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.684           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.352           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.385           ms/op
ClientPb.getUser                        sample  379081   2.530 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.844           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.438           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.615           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.729           ms/op
ClientPb.listUser                       sample  317371   3.022 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.810           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.960           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.795           ms/op
