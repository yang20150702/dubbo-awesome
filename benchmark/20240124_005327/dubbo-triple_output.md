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
# Warmup Iteration   1: 4.968 ops/ms
# Warmup Iteration   2: 12.048 ops/ms
# Warmup Iteration   3: 12.284 ops/ms
Iteration   1: 12.850 ops/ms
Iteration   2: 12.835 ops/ms
Iteration   3: 12.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.839 ±(99.9%) 0.177 ops/ms [Average]
  (min, avg, max) = (12.832, 12.839, 12.850), stdev = 0.010
  CI (99.9%): [12.662, 13.016] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.106 ops/ms
# Warmup Iteration   2: 13.421 ops/ms
# Warmup Iteration   3: 13.160 ops/ms
Iteration   1: 13.170 ops/ms
Iteration   2: 13.213 ops/ms
Iteration   3: 13.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.194 ±(99.9%) 0.400 ops/ms [Average]
  (min, avg, max) = (13.170, 13.194, 13.213), stdev = 0.022
  CI (99.9%): [12.794, 13.593] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.703 ops/ms
# Warmup Iteration   2: 12.657 ops/ms
# Warmup Iteration   3: 12.755 ops/ms
Iteration   1: 13.040 ops/ms
Iteration   2: 12.954 ops/ms
Iteration   3: 12.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.968 ±(99.9%) 1.220 ops/ms [Average]
  (min, avg, max) = (12.909, 12.968, 13.040), stdev = 0.067
  CI (99.9%): [11.747, 14.188] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.434 ops/ms
# Warmup Iteration   2: 10.591 ops/ms
# Warmup Iteration   3: 10.713 ops/ms
Iteration   1: 10.769 ops/ms
Iteration   2: 10.716 ops/ms
Iteration   3: 10.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.745 ±(99.9%) 0.489 ops/ms [Average]
  (min, avg, max) = (10.716, 10.745, 10.769), stdev = 0.027
  CI (99.9%): [10.256, 11.234] (assumes normal distribution)


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.497 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (2.492, 2.497, 2.503), stdev = 0.006
  CI (99.9%): [2.392, 2.602] (assumes normal distribution)


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.496 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (2.492, 2.496, 2.499), stdev = 0.004
  CI (99.9%): [2.427, 2.565] (assumes normal distribution)


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.517 ±(99.9%) 0.003 ms/op
Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
Iteration   3: 2.491 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.497 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (2.483, 2.497, 2.517), stdev = 0.018
  CI (99.9%): [2.169, 2.825] (assumes normal distribution)


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
# Warmup Iteration   1: 4.686 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.004 ms/op
Iteration   1: 3.009 ±(99.9%) 0.005 ms/op
Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
Iteration   3: 3.021 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.018 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (3.009, 3.018, 3.022), stdev = 0.007
  CI (99.9%): [2.884, 3.152] (assumes normal distribution)


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.518 ms/op
                 createUser·p0.999:  12.272 ms/op
                 createUser·p0.9999: 17.007 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  9.250 ms/op
                 createUser·p0.9999: 13.517 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  8.754 ms/op
                 createUser·p0.9999: 11.886 ms/op
                 createUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383342
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 185762 
    [ 2.500,  3.750) = 194433 
    [ 3.750,  5.000) = 2404 
    [ 5.000,  6.250) = 188 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      9.115 ms/op
     p(99.9900) =     14.942 ms/op
     p(99.9990) =     17.307 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.334 ms/op
                 existUser·p0.999:  5.903 ms/op
                 existUser·p0.9999: 13.942 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  7.957 ms/op
                 existUser·p0.9999: 12.747 ms/op
                 existUser·p1.00:   12.861 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.657 ms/op
                 existUser·p0.999:  5.554 ms/op
                 existUser·p0.9999: 12.018 ms/op
                 existUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388388
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 191489 
    [ 2.500,  3.750) = 194412 
    [ 3.750,  5.000) = 1721 
    [ 5.000,  6.250) = 339 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.473 ms/op
     p(99.9000) =      6.141 ms/op
     p(99.9900) =     12.845 ms/op
     p(99.9990) =     14.666 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.830 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.543 ms/op
                 getUser·p0.999:  7.369 ms/op
                 getUser·p0.9999: 13.485 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  9.093 ms/op
                 getUser·p0.9999: 12.861 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.990 ms/op
                 getUser·p0.999:  7.660 ms/op
                 getUser·p0.9999: 10.207 ms/op
                 getUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385101
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 191148 
    [ 2.500,  3.750) = 188926 
    [ 3.750,  5.000) = 3550 
    [ 5.000,  6.250) = 908 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      7.806 ms/op
     p(99.9900) =     13.197 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 4.681 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.009 ms/op
Iteration   1: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 10.862 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 12.809 ms/op
                 listUser·p1.00:   13.304 ms/op

Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.682 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  8.749 ms/op
                 listUser·p0.9999: 12.692 ms/op
                 listUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319855
  mean =      2.999 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 95188 
    [ 2.500,  3.750) = 187012 
    [ 3.750,  5.000) = 30673 
    [ 5.000,  6.250) = 5616 
    [ 6.250,  7.500) = 595 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 265 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     12.239 ms/op
     p(99.9990) =     13.382 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.839 ± 0.177  ops/ms
ClientPb.existUser                       thrpt       3  13.194 ± 0.400  ops/ms
ClientPb.getUser                         thrpt       3  12.968 ± 1.220  ops/ms
ClientPb.listUser                        thrpt       3  10.745 ± 0.489  ops/ms
ClientPb.createUser                       avgt       3   2.497 ± 0.105   ms/op
ClientPb.existUser                        avgt       3   2.496 ± 0.069   ms/op
ClientPb.getUser                          avgt       3   2.497 ± 0.328   ms/op
ClientPb.listUser                         avgt       3   3.018 ± 0.134   ms/op
ClientPb.createUser                     sample  383342   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.872           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.115           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.942           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.498           ms/op
ClientPb.existUser                      sample  388388   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.938           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.141           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.845           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.729           ms/op
ClientPb.getUser                        sample  385101   2.491 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.701           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.806           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.197           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.500           ms/op
ClientPb.listUser                       sample  319855   2.999 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.682           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.239           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.517           ms/op
