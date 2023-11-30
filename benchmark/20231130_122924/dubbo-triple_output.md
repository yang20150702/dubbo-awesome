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
# Warmup Iteration   1: 4.995 ops/ms
# Warmup Iteration   2: 12.074 ops/ms
# Warmup Iteration   3: 12.526 ops/ms
Iteration   1: 12.577 ops/ms
Iteration   2: 12.515 ops/ms
Iteration   3: 12.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.577 ±(99.9%) 1.136 ops/ms [Average]
  (min, avg, max) = (12.515, 12.577, 12.640), stdev = 0.062
  CI (99.9%): [11.441, 13.714] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.215 ops/ms
# Warmup Iteration   2: 12.956 ops/ms
# Warmup Iteration   3: 13.013 ops/ms
Iteration   1: 12.830 ops/ms
Iteration   2: 12.979 ops/ms
Iteration   3: 13.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.943 ±(99.9%) 1.837 ops/ms [Average]
  (min, avg, max) = (12.830, 12.943, 13.022), stdev = 0.101
  CI (99.9%): [11.107, 14.780] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.614 ops/ms
# Warmup Iteration   2: 12.511 ops/ms
# Warmup Iteration   3: 12.597 ops/ms
Iteration   1: 12.452 ops/ms
Iteration   2: 12.812 ops/ms
Iteration   3: 12.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.727 ±(99.9%) 4.443 ops/ms [Average]
  (min, avg, max) = (12.452, 12.727, 12.916), stdev = 0.244
  CI (99.9%): [8.284, 17.169] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.539 ops/ms
# Warmup Iteration   2: 10.571 ops/ms
# Warmup Iteration   3: 10.596 ops/ms
Iteration   1: 10.706 ops/ms
Iteration   2: 10.611 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.677 ±(99.9%) 1.039 ops/ms [Average]
  (min, avg, max) = (10.611, 10.677, 10.713), stdev = 0.057
  CI (99.9%): [9.639, 11.716] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.004 ms/op
Iteration   1: 2.541 ±(99.9%) 0.003 ms/op
Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
Iteration   3: 2.540 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.534 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (2.520, 2.534, 2.541), stdev = 0.012
  CI (99.9%): [2.321, 2.747] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.819 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
Iteration   2: 2.445 ±(99.9%) 0.003 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.084 ms/op [Average]
  (min, avg, max) = (2.445, 2.450, 2.454), stdev = 0.005
  CI (99.9%): [2.366, 2.534] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.971 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.004 ms/op
Iteration   1: 2.538 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
Iteration   3: 2.535 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.534 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (2.527, 2.534, 2.538), stdev = 0.006
  CI (99.9%): [2.427, 2.640] (assumes normal distribution)


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
# Warmup Iteration   1: 4.755 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
Iteration   3: 2.997 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.000 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.994, 3.000, 3.010), stdev = 0.009
  CI (99.9%): [2.839, 3.162] (assumes normal distribution)


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
# Warmup Iteration   1: 4.185 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.657 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.987 ms/op
                 createUser·p0.999:  11.527 ms/op
                 createUser·p0.9999: 16.564 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  8.871 ms/op
                 createUser·p0.9999: 12.411 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 11.169 ms/op
                 createUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380352
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 183765 
    [ 2.500,  3.750) = 191761 
    [ 3.750,  5.000) = 3800 
    [ 5.000,  6.250) = 554 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 127 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      8.432 ms/op
     p(99.9900) =     12.894 ms/op
     p(99.9990) =     17.006 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 3.641 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  7.244 ms/op
                 existUser·p0.9999: 13.502 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  8.391 ms/op
                 existUser·p0.9999: 14.880 ms/op
                 existUser·p1.00:   16.269 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.850 ms/op
                 existUser·p0.999:  7.593 ms/op
                 existUser·p0.9999: 11.568 ms/op
                 existUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386922
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 192516 
    [ 2.500,  3.750) = 190773 
    [ 3.750,  5.000) = 2804 
    [ 5.000,  6.250) = 355 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      7.627 ms/op
     p(99.9900) =     13.817 ms/op
     p(99.9990) =     15.504 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  10.860 ms/op
                 getUser·p0.9999: 13.882 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.330 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  8.775 ms/op
                 getUser·p0.9999: 12.112 ms/op
                 getUser·p1.00:   12.861 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  8.823 ms/op
                 getUser·p0.9999: 11.354 ms/op
                 getUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377859
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 185438 
    [ 2.500,  3.750) = 186560 
    [ 3.750,  5.000) = 4537 
    [ 5.000,  6.250) = 767 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      4.030 ms/op
     p(99.9000) =      8.786 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     14.159 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


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
# Warmup Iteration   1: 4.610 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.008 ms/op
Iteration   1: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.184 ms/op
                 listUser·p0.9999: 13.767 ms/op
                 listUser·p1.00:   15.303 ms/op

Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.706 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 11.960 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   3: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.812 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 10.486 ms/op
                 listUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322669
  mean =      2.973 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 102227 
    [ 2.500,  3.750) = 183241 
    [ 3.750,  5.000) = 29838 
    [ 5.000,  6.250) = 5875 
    [ 6.250,  7.500) = 651 
    [ 7.500,  8.750) = 241 
    [ 8.750, 10.000) = 255 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     12.397 ms/op
     p(99.9990) =     15.070 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.577 ± 1.136  ops/ms
ClientPb.existUser                       thrpt       3  12.943 ± 1.837  ops/ms
ClientPb.getUser                         thrpt       3  12.727 ± 4.443  ops/ms
ClientPb.listUser                        thrpt       3  10.677 ± 1.039  ops/ms
ClientPb.createUser                       avgt       3   2.534 ± 0.213   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.084   ms/op
ClientPb.getUser                          avgt       3   2.534 ± 0.106   ms/op
ClientPb.listUser                         avgt       3   3.000 ± 0.162   ms/op
ClientPb.createUser                     sample  380352   2.521 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.912           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.432           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.894           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.269           ms/op
ClientPb.existUser                      sample  386922   2.479 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.770           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.627           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.817           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.269           ms/op
ClientPb.getUser                        sample  377859   2.538 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.922           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.786           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.255           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.172           ms/op
ClientPb.listUser                       sample  322669   2.973 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.785           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.397           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.303           ms/op
