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
# Warmup Iteration   1: 4.941 ops/ms
# Warmup Iteration   2: 12.324 ops/ms
# Warmup Iteration   3: 12.665 ops/ms
Iteration   1: 12.783 ops/ms
Iteration   2: 12.818 ops/ms
Iteration   3: 12.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.816 ±(99.9%) 0.575 ops/ms [Average]
  (min, avg, max) = (12.783, 12.816, 12.846), stdev = 0.032
  CI (99.9%): [12.241, 13.391] (assumes normal distribution)


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
# Warmup Iteration   1: 8.161 ops/ms
# Warmup Iteration   2: 13.411 ops/ms
# Warmup Iteration   3: 13.330 ops/ms
Iteration   1: 13.340 ops/ms
Iteration   2: 13.448 ops/ms
Iteration   3: 13.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.376 ±(99.9%) 1.134 ops/ms [Average]
  (min, avg, max) = (13.340, 13.376, 13.448), stdev = 0.062
  CI (99.9%): [12.241, 14.510] (assumes normal distribution)


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
# Warmup Iteration   1: 7.896 ops/ms
# Warmup Iteration   2: 12.709 ops/ms
# Warmup Iteration   3: 13.033 ops/ms
Iteration   1: 13.067 ops/ms
Iteration   2: 13.031 ops/ms
Iteration   3: 12.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.027 ±(99.9%) 0.767 ops/ms [Average]
  (min, avg, max) = (12.983, 13.027, 13.067), stdev = 0.042
  CI (99.9%): [12.261, 13.794] (assumes normal distribution)


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
# Warmup Iteration   1: 6.864 ops/ms
# Warmup Iteration   2: 10.610 ops/ms
# Warmup Iteration   3: 10.684 ops/ms
Iteration   1: 10.838 ops/ms
Iteration   2: 10.893 ops/ms
Iteration   3: 10.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.857 ±(99.9%) 0.570 ops/ms [Average]
  (min, avg, max) = (10.838, 10.857, 10.893), stdev = 0.031
  CI (99.9%): [10.287, 11.427] (assumes normal distribution)


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.003 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.469 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.457, 2.469, 2.481), stdev = 0.012
  CI (99.9%): [2.254, 2.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.700 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.396 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.409 ±(99.9%) 0.003 ms/op
Iteration   1: 2.380 ±(99.9%) 0.003 ms/op
Iteration   2: 2.396 ±(99.9%) 0.004 ms/op
Iteration   3: 2.398 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.392 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (2.380, 2.392, 2.398), stdev = 0.010
  CI (99.9%): [2.211, 2.572] (assumes normal distribution)


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
# Warmup Iteration   1: 3.907 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.004 ms/op
Iteration   1: 2.455 ±(99.9%) 0.004 ms/op
Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
Iteration   3: 2.472 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.469 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (2.455, 2.469, 2.482), stdev = 0.014
  CI (99.9%): [2.216, 2.723] (assumes normal distribution)


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
# Warmup Iteration   1: 4.612 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
Iteration   2: 2.969 ±(99.9%) 0.004 ms/op
Iteration   3: 2.986 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.977 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (2.969, 2.977, 2.986), stdev = 0.008
  CI (99.9%): [2.827, 3.127] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.006 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.555 ms/op
                 createUser·p0.999:  6.374 ms/op
                 createUser·p0.9999: 13.483 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  9.437 ms/op
                 createUser·p0.9999: 12.090 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  8.773 ms/op
                 createUser·p0.9999: 10.373 ms/op
                 createUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391092
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 193910 
    [ 2.500,  3.750) = 193624 
    [ 3.750,  5.000) = 2613 
    [ 5.000,  6.250) = 390 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 135 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      9.157 ms/op
     p(99.9900) =     12.892 ms/op
     p(99.9990) =     13.698 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.646 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.402 ±(99.9%) 0.005 ms/op
Iteration   1: 2.399 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   3.424 ms/op
                 existUser·p0.999:  5.636 ms/op
                 existUser·p0.9999: 13.085 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  5.674 ms/op
                 existUser·p0.9999: 11.036 ms/op
                 existUser·p1.00:   11.469 ms/op

Iteration   3: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 11.980 ms/op
                 existUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398156
  mean =      2.409 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 201510 
    [ 2.500,  3.750) = 193268 
    [ 3.750,  5.000) = 2540 
    [ 5.000,  6.250) = 352 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      6.734 ms/op
     p(99.9900) =     12.567 ms/op
     p(99.9990) =     13.373 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.006 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  7.913 ms/op
                 getUser·p0.9999: 14.253 ms/op
                 getUser·p1.00:   15.663 ms/op

Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  9.503 ms/op
                 getUser·p0.9999: 12.767 ms/op
                 getUser·p1.00:   13.156 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.005 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  7.449 ms/op
                 getUser·p0.9999: 10.826 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386267
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 192760 
    [ 2.500,  3.750) = 188598 
    [ 3.750,  5.000) = 3764 
    [ 5.000,  6.250) = 582 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      7.914 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     14.769 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 4.709 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
Iteration   1: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 9.935 ms/op
                 listUser·p1.00:   10.453 ms/op

Iteration   2: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.864 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.556 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 11.371 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.581 ms/op
                 listUser·p0.999:  8.972 ms/op
                 listUser·p0.9999: 10.813 ms/op
                 listUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319140
  mean =      3.005 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 92092 
    [ 2.500,  3.750) = 187685 
    [ 3.750,  5.000) = 31740 
    [ 5.000,  6.250) = 6112 
    [ 6.250,  7.500) = 720 
    [ 7.500,  8.750) = 263 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     11.059 ms/op
     p(99.9990) =     11.928 ms/op
     p(99.9999) =     11.977 ms/op
    p(100.0000) =     11.977 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.816 ± 0.575  ops/ms
ClientPb.existUser                       thrpt       3  13.376 ± 1.134  ops/ms
ClientPb.getUser                         thrpt       3  13.027 ± 0.767  ops/ms
ClientPb.listUser                        thrpt       3  10.857 ± 0.570  ops/ms
ClientPb.createUser                       avgt       3   2.469 ± 0.215   ms/op
ClientPb.existUser                        avgt       3   2.392 ± 0.180   ms/op
ClientPb.getUser                          avgt       3   2.469 ± 0.253   ms/op
ClientPb.listUser                         avgt       3   2.977 ± 0.150   ms/op
ClientPb.createUser                     sample  391092   2.452 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.900           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.515           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.974           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.157           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.892           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.598           ms/op
ClientPb.existUser                      sample  398156   2.409 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.666           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.734           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.567           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.681           ms/op
ClientPb.getUser                        sample  386267   2.483 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.798           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.914           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.418           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.663           ms/op
ClientPb.listUser                       sample  319140   3.005 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.864           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.059           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.977           ms/op
