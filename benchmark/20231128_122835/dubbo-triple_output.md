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
# Warmup Iteration   1: 4.439 ops/ms
# Warmup Iteration   2: 11.980 ops/ms
# Warmup Iteration   3: 12.554 ops/ms
Iteration   1: 12.645 ops/ms
Iteration   2: 12.666 ops/ms
Iteration   3: 12.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.684 ±(99.9%) 0.918 ops/ms [Average]
  (min, avg, max) = (12.645, 12.684, 12.741), stdev = 0.050
  CI (99.9%): [11.766, 13.602] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.373 ops/ms
# Warmup Iteration   2: 13.284 ops/ms
# Warmup Iteration   3: 13.168 ops/ms
Iteration   1: 13.202 ops/ms
Iteration   2: 13.155 ops/ms
Iteration   3: 13.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.157 ±(99.9%) 0.809 ops/ms [Average]
  (min, avg, max) = (13.113, 13.157, 13.202), stdev = 0.044
  CI (99.9%): [12.348, 13.966] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.003 ops/ms
# Warmup Iteration   2: 12.351 ops/ms
# Warmup Iteration   3: 12.753 ops/ms
Iteration   1: 12.846 ops/ms
Iteration   2: 12.806 ops/ms
Iteration   3: 12.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.767 ±(99.9%) 1.884 ops/ms [Average]
  (min, avg, max) = (12.651, 12.767, 12.846), stdev = 0.103
  CI (99.9%): [10.884, 14.651] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.476 ops/ms
# Warmup Iteration   2: 10.488 ops/ms
# Warmup Iteration   3: 10.604 ops/ms
Iteration   1: 10.664 ops/ms
Iteration   2: 10.680 ops/ms
Iteration   3: 10.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.622 ±(99.9%) 1.580 ops/ms [Average]
  (min, avg, max) = (10.523, 10.622, 10.680), stdev = 0.087
  CI (99.9%): [9.042, 12.202] (assumes normal distribution)


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.003 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.535 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (2.529, 2.535, 2.540), stdev = 0.006
  CI (99.9%): [2.430, 2.641] (assumes normal distribution)


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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.472 ±(99.9%) 0.004 ms/op
Iteration   2: 2.480 ±(99.9%) 0.003 ms/op
Iteration   3: 2.457 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.470 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.457, 2.470, 2.480), stdev = 0.012
  CI (99.9%): [2.259, 2.681] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.003 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.497 ±(99.9%) 0.076 ms/op [Average]
  (min, avg, max) = (2.492, 2.497, 2.501), stdev = 0.004
  CI (99.9%): [2.420, 2.573] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.580 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.005 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
Iteration   2: 2.996 ±(99.9%) 0.005 ms/op
Iteration   3: 2.975 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (2.975, 2.987, 2.996), stdev = 0.011
  CI (99.9%): [2.787, 3.187] (assumes normal distribution)


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
# Warmup Iteration   1: 4.162 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.722 ms/op
                 createUser·p0.999:  10.046 ms/op
                 createUser·p0.9999: 13.543 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  9.355 ms/op
                 createUser·p0.9999: 13.949 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  8.029 ms/op
                 createUser·p0.9999: 10.144 ms/op
                 createUser·p1.00:   10.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384710
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 187790 
    [ 2.500,  3.750) = 192629 
    [ 3.750,  5.000) = 3308 
    [ 5.000,  6.250) = 471 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      8.039 ms/op
     p(99.9900) =     13.591 ms/op
     p(99.9990) =     14.601 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.424 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  6.030 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  6.953 ms/op
                 existUser·p0.9999: 12.780 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.899 ms/op
                 existUser·p0.999:  7.572 ms/op
                 existUser·p0.9999: 11.745 ms/op
                 existUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395556
  mean =      2.425 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 195749 
    [ 2.500,  3.750) = 196444 
    [ 3.750,  5.000) = 2437 
    [ 5.000,  6.250) = 444 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      6.967 ms/op
     p(99.9900) =     13.164 ms/op
     p(99.9990) =     14.125 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  10.649 ms/op
                 getUser·p0.9999: 13.602 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  9.130 ms/op
                 getUser·p0.9999: 14.986 ms/op
                 getUser·p1.00:   16.024 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  8.770 ms/op
                 getUser·p0.9999: 12.069 ms/op
                 getUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381606
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 187356 
    [ 2.500,  3.750) = 187991 
    [ 3.750,  5.000) = 4419 
    [ 5.000,  6.250) = 1271 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.827 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     15.142 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.758 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.009 ms/op
Iteration   1: 3.044 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   5.898 ms/op
                 listUser·p0.999:  9.567 ms/op
                 listUser·p0.9999: 11.165 ms/op
                 listUser·p1.00:   11.993 ms/op

Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.592 ms/op
                 listUser·p0.9999: 13.148 ms/op
                 listUser·p1.00:   14.942 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.518 ms/op
                 listUser·p0.9999: 12.089 ms/op
                 listUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316010
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 90425 
    [ 2.500,  3.750) = 183577 
    [ 3.750,  5.000) = 33155 
    [ 5.000,  6.250) = 7220 
    [ 6.250,  7.500) = 752 
    [ 7.500,  8.750) = 228 
    [ 8.750, 10.000) = 310 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     12.311 ms/op
     p(99.9990) =     14.052 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.684 ± 0.918  ops/ms
ClientPb.existUser                       thrpt       3  13.157 ± 0.809  ops/ms
ClientPb.getUser                         thrpt       3  12.767 ± 1.884  ops/ms
ClientPb.listUser                        thrpt       3  10.622 ± 1.580  ops/ms
ClientPb.createUser                       avgt       3   2.535 ± 0.105   ms/op
ClientPb.existUser                        avgt       3   2.470 ± 0.211   ms/op
ClientPb.getUser                          avgt       3   2.497 ± 0.076   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.200   ms/op
ClientPb.createUser                     sample  384710   2.493 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.039           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.591           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.795           ms/op
ClientPb.existUser                      sample  395556   2.425 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.728           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.967           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.164           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.287           ms/op
ClientPb.getUser                        sample  381606   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.679           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.827           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.730           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.024           ms/op
ClientPb.listUser                       sample  316010   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.751           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.311           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.942           ms/op
