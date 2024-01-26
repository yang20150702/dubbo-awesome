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
# Warmup Iteration   1: 4.894 ops/ms
# Warmup Iteration   2: 12.054 ops/ms
# Warmup Iteration   3: 12.448 ops/ms
Iteration   1: 12.646 ops/ms
Iteration   2: 12.554 ops/ms
Iteration   3: 12.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.619 ±(99.9%) 1.040 ops/ms [Average]
  (min, avg, max) = (12.554, 12.619, 12.659), stdev = 0.057
  CI (99.9%): [11.579, 13.660] (assumes normal distribution)


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
# Warmup Iteration   1: 8.265 ops/ms
# Warmup Iteration   2: 13.129 ops/ms
# Warmup Iteration   3: 13.210 ops/ms
Iteration   1: 13.292 ops/ms
Iteration   2: 13.130 ops/ms
Iteration   3: 13.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.238 ±(99.9%) 1.693 ops/ms [Average]
  (min, avg, max) = (13.130, 13.238, 13.292), stdev = 0.093
  CI (99.9%): [11.544, 14.931] (assumes normal distribution)


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
# Warmup Iteration   1: 7.530 ops/ms
# Warmup Iteration   2: 12.754 ops/ms
# Warmup Iteration   3: 12.824 ops/ms
Iteration   1: 12.920 ops/ms
Iteration   2: 12.708 ops/ms
Iteration   3: 13.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.889 ±(99.9%) 3.058 ops/ms [Average]
  (min, avg, max) = (12.708, 12.889, 13.039), stdev = 0.168
  CI (99.9%): [9.830, 15.947] (assumes normal distribution)


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
# Warmup Iteration   1: 6.700 ops/ms
# Warmup Iteration   2: 10.581 ops/ms
# Warmup Iteration   3: 10.747 ops/ms
Iteration   1: 10.699 ops/ms
Iteration   2: 10.643 ops/ms
Iteration   3: 10.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.708 ±(99.9%) 1.262 ops/ms [Average]
  (min, avg, max) = (10.643, 10.708, 10.781), stdev = 0.069
  CI (99.9%): [9.445, 11.970] (assumes normal distribution)


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.003 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.513 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.495, 2.513, 2.528), stdev = 0.017
  CI (99.9%): [2.202, 2.825] (assumes normal distribution)


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.450 ±(99.9%) 0.005 ms/op
Iteration   2: 2.450 ±(99.9%) 0.004 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.001 ms/op [Average]
  (min, avg, max) = (2.450, 2.450, 2.450), stdev = 0.001
  CI (99.9%): [2.450, 2.451] (assumes normal distribution)


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.550 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.510 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (2.489, 2.510, 2.550), stdev = 0.035
  CI (99.9%): [1.876, 3.144] (assumes normal distribution)


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
# Warmup Iteration   1: 4.750 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.962 ±(99.9%) 0.004 ms/op
Iteration   2: 2.965 ±(99.9%) 0.005 ms/op
Iteration   3: 2.966 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.964 ±(99.9%) 0.041 ms/op [Average]
  (min, avg, max) = (2.962, 2.964, 2.966), stdev = 0.002
  CI (99.9%): [2.923, 3.005] (assumes normal distribution)


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.727 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  12.053 ms/op
                 createUser·p0.9999: 13.445 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 11.944 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  8.831 ms/op
                 createUser·p0.9999: 11.901 ms/op
                 createUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379495
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 182687 
    [ 2.500,  3.750) = 192287 
    [ 3.750,  5.000) = 3661 
    [ 5.000,  6.250) = 282 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      9.331 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     13.940 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


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
# Warmup Iteration   1: 3.692 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  5.661 ms/op
                 existUser·p0.9999: 13.960 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  7.472 ms/op
                 existUser·p0.9999: 13.058 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.891 ms/op
                 existUser·p0.999:  6.209 ms/op
                 existUser·p0.9999: 11.549 ms/op
                 existUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393493
  mean =      2.437 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 196434 
    [ 2.500,  3.750) = 193341 
    [ 3.750,  5.000) = 2808 
    [ 5.000,  6.250) = 450 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      6.869 ms/op
     p(99.9900) =     13.364 ms/op
     p(99.9990) =     14.257 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.920 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.006 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  5.927 ms/op
                 getUser·p0.9999: 13.665 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  6.641 ms/op
                 getUser·p0.9999: 12.060 ms/op
                 getUser·p1.00:   13.140 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.847 ms/op
                 getUser·p0.999:  7.743 ms/op
                 getUser·p0.9999: 10.872 ms/op
                 getUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386373
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 192116 
    [ 2.500,  3.750) = 190334 
    [ 3.750,  5.000) = 3186 
    [ 5.000,  6.250) = 287 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.749 ms/op
     p(99.9000) =      6.400 ms/op
     p(99.9900) =     13.113 ms/op
     p(99.9990) =     13.926 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 4.783 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
Iteration   1: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.249 ms/op
                 listUser·p0.9999: 10.246 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   2: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.386 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.495 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.558 ms/op
                 listUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320227
  mean =      2.995 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 93792 
    [ 2.500,  3.750) = 189188 
    [ 3.750,  5.000) = 30485 
    [ 5.000,  6.250) = 5306 
    [ 6.250,  7.500) = 648 
    [ 7.500,  8.750) = 222 
    [ 8.750, 10.000) = 291 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.417 ms/op
     p(99.9900) =     11.256 ms/op
     p(99.9990) =     12.700 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.619 ± 1.040  ops/ms
ClientPb.existUser                       thrpt       3  13.238 ± 1.693  ops/ms
ClientPb.getUser                         thrpt       3  12.889 ± 3.058  ops/ms
ClientPb.listUser                        thrpt       3  10.708 ± 1.262  ops/ms
ClientPb.createUser                       avgt       3   2.513 ± 0.311   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.001   ms/op
ClientPb.getUser                          avgt       3   2.510 ± 0.634   ms/op
ClientPb.listUser                         avgt       3   2.964 ± 0.041   ms/op
ClientPb.createUser                     sample  379495   2.528 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.674           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.331           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.976           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.172           ms/op
ClientPb.existUser                      sample  393493   2.437 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.808           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.869           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.364           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.336           ms/op
ClientPb.getUser                        sample  386373   2.483 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.825           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.749           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.400           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.113           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.107           ms/op
ClientPb.listUser                       sample  320227   2.995 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.854           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.417           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.256           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.927           ms/op
