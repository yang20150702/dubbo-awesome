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
# Warmup Iteration   1: 4.588 ops/ms
# Warmup Iteration   2: 11.887 ops/ms
# Warmup Iteration   3: 12.104 ops/ms
Iteration   1: 12.471 ops/ms
Iteration   2: 12.684 ops/ms
Iteration   3: 12.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.595 ±(99.9%) 2.014 ops/ms [Average]
  (min, avg, max) = (12.471, 12.595, 12.684), stdev = 0.110
  CI (99.9%): [10.581, 14.608] (assumes normal distribution)


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
# Warmup Iteration   1: 8.078 ops/ms
# Warmup Iteration   2: 12.893 ops/ms
# Warmup Iteration   3: 13.045 ops/ms
Iteration   1: 13.132 ops/ms
Iteration   2: 12.987 ops/ms
Iteration   3: 13.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.057 ±(99.9%) 1.319 ops/ms [Average]
  (min, avg, max) = (12.987, 13.057, 13.132), stdev = 0.072
  CI (99.9%): [11.738, 14.375] (assumes normal distribution)


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
# Warmup Iteration   1: 7.659 ops/ms
# Warmup Iteration   2: 12.424 ops/ms
# Warmup Iteration   3: 12.610 ops/ms
Iteration   1: 12.796 ops/ms
Iteration   2: 12.635 ops/ms
Iteration   3: 12.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.713 ±(99.9%) 1.478 ops/ms [Average]
  (min, avg, max) = (12.635, 12.713, 12.796), stdev = 0.081
  CI (99.9%): [11.235, 14.191] (assumes normal distribution)


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
# Warmup Iteration   1: 6.209 ops/ms
# Warmup Iteration   2: 10.522 ops/ms
# Warmup Iteration   3: 10.568 ops/ms
Iteration   1: 10.617 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.609 ±(99.9%) 0.394 ops/ms [Average]
  (min, avg, max) = (10.585, 10.609, 10.626), stdev = 0.022
  CI (99.9%): [10.215, 11.004] (assumes normal distribution)


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.581 ±(99.9%) 0.004 ms/op
Iteration   1: 2.565 ±(99.9%) 0.005 ms/op
Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
Iteration   3: 2.585 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.571 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (2.563, 2.571, 2.585), stdev = 0.012
  CI (99.9%): [2.346, 2.796] (assumes normal distribution)


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.003 ms/op
Iteration   1: 2.461 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.003 ms/op
Iteration   3: 2.441 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.447 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (2.440, 2.447, 2.461), stdev = 0.012
  CI (99.9%): [2.235, 2.660] (assumes normal distribution)


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
Iteration   1: 2.503 ±(99.9%) 0.003 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.513 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.503, 2.513, 2.521), stdev = 0.009
  CI (99.9%): [2.350, 2.676] (assumes normal distribution)


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
# Warmup Iteration   1: 4.686 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.005 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
Iteration   3: 3.008 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (3.000, 3.006, 3.011), stdev = 0.006
  CI (99.9%): [2.901, 3.112] (assumes normal distribution)


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
# Warmup Iteration   1: 4.346 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.692 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  11.528 ms/op
                 createUser·p0.9999: 13.786 ms/op
                 createUser·p1.00:   14.582 ms/op

Iteration   2: 2.552 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.860 ms/op
                 createUser·p0.999:  9.830 ms/op
                 createUser·p0.9999: 12.132 ms/op
                 createUser·p1.00:   12.894 ms/op

Iteration   3: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  8.867 ms/op
                 createUser·p0.9999: 12.312 ms/op
                 createUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376063
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 177834 
    [ 2.500,  3.750) = 194167 
    [ 3.750,  5.000) = 3319 
    [ 5.000,  6.250) = 263 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      9.076 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     13.885 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  6.871 ms/op
                 existUser·p0.9999: 13.596 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  5.535 ms/op
                 existUser·p0.9999: 13.292 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.899 ms/op
                 existUser·p0.999:  8.684 ms/op
                 existUser·p0.9999: 13.970 ms/op
                 existUser·p1.00:   14.254 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386975
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 190815 
    [ 2.500,  3.750) = 192658 
    [ 3.750,  5.000) = 2530 
    [ 5.000,  6.250) = 442 
    [ 6.250,  7.500) = 143 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 134 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      6.546 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     14.132 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  6.026 ms/op
                 getUser·p0.9999: 13.556 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   2: 2.560 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.338 ms/op
                 getUser·p0.99:   4.376 ms/op
                 getUser·p0.999:  8.929 ms/op
                 getUser·p0.9999: 14.295 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  8.707 ms/op
                 getUser·p0.9999: 11.710 ms/op
                 getUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377397
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 184696 
    [ 2.500,  3.750) = 186342 
    [ 3.750,  5.000) = 5281 
    [ 5.000,  6.250) = 598 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =      6.660 ms/op
     p(99.9900) =     13.464 ms/op
     p(99.9990) =     14.402 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 4.702 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.009 ms/op
Iteration   1: 3.075 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.987 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.436 ms/op
                 listUser·p1.00:   11.616 ms/op

Iteration   2: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.648 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.538 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   3: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 11.450 ms/op
                 listUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313086
  mean =      3.063 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 82238 
    [ 2.500,  3.750) = 187821 
    [ 3.750,  5.000) = 35205 
    [ 5.000,  6.250) = 6450 
    [ 6.250,  7.500) = 637 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 306 
    [10.000, 11.250) = 182 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.403 ms/op
     p(99.9990) =     13.012 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.595 ± 2.014  ops/ms
ClientPb.existUser                       thrpt       3  13.057 ± 1.319  ops/ms
ClientPb.getUser                         thrpt       3  12.713 ± 1.478  ops/ms
ClientPb.listUser                        thrpt       3  10.609 ± 0.394  ops/ms
ClientPb.createUser                       avgt       3   2.571 ± 0.225   ms/op
ClientPb.existUser                        avgt       3   2.447 ± 0.212   ms/op
ClientPb.getUser                          avgt       3   2.513 ± 0.163   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.106   ms/op
ClientPb.createUser                     sample  376063   2.550 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.903           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.076           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.500           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.582           ms/op
ClientPb.existUser                      sample  386975   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.913           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.546           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  377397   2.541 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.816           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.067           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.660           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.464           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.516           ms/op
ClientPb.listUser                       sample  313086   3.063 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.648           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.403           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.435           ms/op
