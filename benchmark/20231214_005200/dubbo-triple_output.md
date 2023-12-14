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
# Warmup Iteration   1: 4.431 ops/ms
# Warmup Iteration   2: 11.643 ops/ms
# Warmup Iteration   3: 12.065 ops/ms
Iteration   1: 12.372 ops/ms
Iteration   2: 12.389 ops/ms
Iteration   3: 12.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.348 ±(99.9%) 1.060 ops/ms [Average]
  (min, avg, max) = (12.281, 12.348, 12.389), stdev = 0.058
  CI (99.9%): [11.288, 13.408] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.917 ops/ms
# Warmup Iteration   2: 12.803 ops/ms
# Warmup Iteration   3: 12.848 ops/ms
Iteration   1: 12.769 ops/ms
Iteration   2: 12.676 ops/ms
Iteration   3: 12.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.744 ±(99.9%) 1.096 ops/ms [Average]
  (min, avg, max) = (12.676, 12.744, 12.788), stdev = 0.060
  CI (99.9%): [11.648, 13.840] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.831 ops/ms
# Warmup Iteration   2: 12.012 ops/ms
# Warmup Iteration   3: 12.409 ops/ms
Iteration   1: 12.418 ops/ms
Iteration   2: 12.367 ops/ms
Iteration   3: 12.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.446 ±(99.9%) 1.743 ops/ms [Average]
  (min, avg, max) = (12.367, 12.446, 12.552), stdev = 0.096
  CI (99.9%): [10.703, 14.188] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.977 ops/ms
# Warmup Iteration   2: 10.313 ops/ms
# Warmup Iteration   3: 10.500 ops/ms
Iteration   1: 10.619 ops/ms
Iteration   2: 10.688 ops/ms
Iteration   3: 10.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.684 ±(99.9%) 1.145 ops/ms [Average]
  (min, avg, max) = (10.619, 10.684, 10.744), stdev = 0.063
  CI (99.9%): [9.539, 11.828] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.118 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.004 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
Iteration   2: 2.475 ±(99.9%) 0.003 ms/op
Iteration   3: 2.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.455 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (2.437, 2.455, 2.475), stdev = 0.019
  CI (99.9%): [2.111, 2.799] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.572 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.449 ±(99.9%) 0.004 ms/op
Iteration   2: 2.427 ±(99.9%) 0.003 ms/op
Iteration   3: 2.428 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.435 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (2.427, 2.435, 2.449), stdev = 0.012
  CI (99.9%): [2.211, 2.658] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.840 ±(99.9%) 0.007 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.003 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.503 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.495, 2.503, 2.508), stdev = 0.007
  CI (99.9%): [2.376, 2.631] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.663 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.005 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
Iteration   3: 2.987 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.978 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (2.971, 2.978, 2.987), stdev = 0.008
  CI (99.9%): [2.831, 3.124] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.856 ms/op
                 createUser·p0.999:  9.073 ms/op
                 createUser·p0.9999: 13.145 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  5.778 ms/op
                 createUser·p0.9999: 12.864 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  7.668 ms/op
                 createUser·p0.9999: 11.505 ms/op
                 createUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385301
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 187890 
    [ 2.500,  3.750) = 192915 
    [ 3.750,  5.000) = 3540 
    [ 5.000,  6.250) = 427 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 150 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      7.428 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     13.731 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  5.431 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.733 ms/op
                 existUser·p0.999:  8.391 ms/op
                 existUser·p0.9999: 14.687 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  7.200 ms/op
                 existUser·p0.9999: 11.583 ms/op
                 existUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390094
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 191003 
    [ 2.500,  3.750) = 195778 
    [ 3.750,  5.000) = 2549 
    [ 5.000,  6.250) = 348 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      6.102 ms/op
     p(99.9900) =     14.074 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.997 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  11.101 ms/op
                 getUser·p0.9999: 14.734 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.499 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  10.054 ms/op
                 getUser·p0.9999: 15.370 ms/op
                 getUser·p1.00:   16.155 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  9.081 ms/op
                 getUser·p0.9999: 11.724 ms/op
                 getUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381311
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 188946 
    [ 2.500,  3.750) = 186274 
    [ 3.750,  5.000) = 4896 
    [ 5.000,  6.250) = 670 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      9.104 ms/op
     p(99.9900) =     14.725 ms/op
     p(99.9990) =     15.945 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.672 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.009 ms/op
Iteration   1: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.607 ms/op
                 listUser·p0.999:  10.012 ms/op
                 listUser·p0.9999: 13.271 ms/op
                 listUser·p1.00:   14.172 ms/op

Iteration   2: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.857 ms/op
                 listUser·p0.9999: 11.695 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.052 ms/op
                 listUser·p0.9999: 11.342 ms/op
                 listUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321580
  mean =      2.983 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 98739 
    [ 2.500,  3.750) = 186071 
    [ 3.750,  5.000) = 29868 
    [ 5.000,  6.250) = 5385 
    [ 6.250,  7.500) = 666 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 193 
    [10.000, 11.250) = 213 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     12.496 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.348 ± 1.060  ops/ms
ClientPb.existUser                       thrpt       3  12.744 ± 1.096  ops/ms
ClientPb.getUser                         thrpt       3  12.446 ± 1.743  ops/ms
ClientPb.listUser                        thrpt       3  10.684 ± 1.145  ops/ms
ClientPb.createUser                       avgt       3   2.455 ± 0.344   ms/op
ClientPb.existUser                        avgt       3   2.435 ± 0.224   ms/op
ClientPb.getUser                          avgt       3   2.503 ± 0.128   ms/op
ClientPb.listUser                         avgt       3   2.978 ± 0.147   ms/op
ClientPb.createUser                     sample  385301   2.489 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.758           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.428           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.993           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.615           ms/op
ClientPb.existUser                      sample  390094   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.890           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.102           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.074           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.172           ms/op
ClientPb.getUser                        sample  381311   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.499           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.104           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.725           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.155           ms/op
ClientPb.listUser                       sample  321580   2.983 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.852           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.880           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.496           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.172           ms/op
