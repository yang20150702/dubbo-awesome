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
# Warmup Iteration   1: 4.762 ops/ms
# Warmup Iteration   2: 11.697 ops/ms
# Warmup Iteration   3: 12.094 ops/ms
Iteration   1: 12.345 ops/ms
Iteration   2: 12.320 ops/ms
Iteration   3: 12.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.402 ±(99.9%) 2.210 ops/ms [Average]
  (min, avg, max) = (12.320, 12.402, 12.541), stdev = 0.121
  CI (99.9%): [10.192, 14.612] (assumes normal distribution)


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
# Warmup Iteration   1: 8.483 ops/ms
# Warmup Iteration   2: 12.831 ops/ms
# Warmup Iteration   3: 12.745 ops/ms
Iteration   1: 12.673 ops/ms
Iteration   2: 12.869 ops/ms
Iteration   3: 12.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.778 ±(99.9%) 1.807 ops/ms [Average]
  (min, avg, max) = (12.673, 12.778, 12.869), stdev = 0.099
  CI (99.9%): [10.971, 14.585] (assumes normal distribution)


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
# Warmup Iteration   1: 7.503 ops/ms
# Warmup Iteration   2: 12.559 ops/ms
# Warmup Iteration   3: 12.760 ops/ms
Iteration   1: 12.750 ops/ms
Iteration   2: 12.744 ops/ms
Iteration   3: 12.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.770 ±(99.9%) 0.731 ops/ms [Average]
  (min, avg, max) = (12.744, 12.770, 12.816), stdev = 0.040
  CI (99.9%): [12.040, 13.501] (assumes normal distribution)


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
# Warmup Iteration   1: 6.407 ops/ms
# Warmup Iteration   2: 10.446 ops/ms
# Warmup Iteration   3: 10.497 ops/ms
Iteration   1: 10.601 ops/ms
Iteration   2: 10.544 ops/ms
Iteration   3: 10.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.581 ±(99.9%) 0.583 ops/ms [Average]
  (min, avg, max) = (10.544, 10.581, 10.601), stdev = 0.032
  CI (99.9%): [9.998, 11.164] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.969 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.509 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (2.500, 2.509, 2.514), stdev = 0.008
  CI (99.9%): [2.370, 2.647] (assumes normal distribution)


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.442 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.435, 2.442, 2.445), stdev = 0.006
  CI (99.9%): [2.341, 2.542] (assumes normal distribution)


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.536 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.507 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (2.483, 2.507, 2.536), stdev = 0.027
  CI (99.9%): [2.020, 2.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.715 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.007 ms/op
Iteration   2: 3.017 ±(99.9%) 0.004 ms/op
Iteration   3: 3.024 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.023 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (3.017, 3.023, 3.028), stdev = 0.006
  CI (99.9%): [2.916, 3.130] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.171 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  8.796 ms/op
                 createUser·p0.9999: 13.369 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.543 ms/op
                 createUser·p0.999:  9.306 ms/op
                 createUser·p0.9999: 12.738 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  8.143 ms/op
                 createUser·p0.9999: 10.771 ms/op
                 createUser·p1.00:   11.010 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382267
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 185174 
    [ 2.500,  3.750) = 193739 
    [ 3.750,  5.000) = 2456 
    [ 5.000,  6.250) = 369 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      8.143 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     13.856 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  8.619 ms/op
                 existUser·p0.9999: 13.501 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  6.248 ms/op
                 existUser·p0.9999: 13.452 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   3: 2.471 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  9.568 ms/op
                 existUser·p0.9999: 16.597 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388652
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 192641 
    [ 2.500,  3.750) = 193055 
    [ 3.750,  5.000) = 2124 
    [ 5.000,  6.250) = 311 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     14.081 ms/op
     p(99.9990) =     16.630 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  10.551 ms/op
                 getUser·p0.9999: 13.865 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  6.074 ms/op
                 getUser·p0.9999: 12.738 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.644 ms/op
                 getUser·p0.999:  8.702 ms/op
                 getUser·p0.9999: 11.211 ms/op
                 getUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380079
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 188087 
    [ 2.500,  3.750) = 187677 
    [ 3.750,  5.000) = 3523 
    [ 5.000,  6.250) = 373 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      6.078 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     14.100 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 5.063 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.025 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 11.138 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.377 ms/op
                 listUser·p0.9999: 12.604 ms/op
                 listUser·p1.00:   13.271 ms/op

Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.213 ms/op
                 listUser·p0.9999: 11.305 ms/op
                 listUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318007
  mean =      3.016 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 90679 
    [ 2.500,  3.750) = 186877 
    [ 3.750,  5.000) = 32594 
    [ 5.000,  6.250) = 6328 
    [ 6.250,  7.500) = 745 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 155 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     11.420 ms/op
     p(99.9990) =     12.957 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.402 ± 2.210  ops/ms
ClientPb.existUser                       thrpt       3  12.778 ± 1.807  ops/ms
ClientPb.getUser                         thrpt       3  12.770 ± 0.731  ops/ms
ClientPb.listUser                        thrpt       3  10.581 ± 0.583  ops/ms
ClientPb.createUser                       avgt       3   2.509 ± 0.138   ms/op
ClientPb.existUser                        avgt       3   2.442 ± 0.100   ms/op
ClientPb.getUser                          avgt       3   2.507 ± 0.487   ms/op
ClientPb.listUser                         avgt       3   3.023 ± 0.107   ms/op
ClientPb.createUser                     sample  382267   2.509 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.849           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.143           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.124           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.205           ms/op
ClientPb.existUser                      sample  388652   2.467 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.815           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.290           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.081           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.760           ms/op
ClientPb.getUser                        sample  380079   2.524 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.937           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.078           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.107           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.238           ms/op
ClientPb.listUser                       sample  318007   3.016 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.850           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.420           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.271           ms/op
