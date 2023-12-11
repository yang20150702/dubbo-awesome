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
# Warmup Iteration   1: 4.544 ops/ms
# Warmup Iteration   2: 11.760 ops/ms
# Warmup Iteration   3: 12.104 ops/ms
Iteration   1: 12.279 ops/ms
Iteration   2: 12.431 ops/ms
Iteration   3: 12.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.418 ±(99.9%) 2.420 ops/ms [Average]
  (min, avg, max) = (12.279, 12.418, 12.543), stdev = 0.133
  CI (99.9%): [9.997, 14.838] (assumes normal distribution)


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
# Warmup Iteration   1: 8.471 ops/ms
# Warmup Iteration   2: 13.287 ops/ms
# Warmup Iteration   3: 13.315 ops/ms
Iteration   1: 13.198 ops/ms
Iteration   2: 13.342 ops/ms
Iteration   3: 13.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.242 ±(99.9%) 1.594 ops/ms [Average]
  (min, avg, max) = (13.185, 13.242, 13.342), stdev = 0.087
  CI (99.9%): [11.648, 14.835] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.667 ops/ms
# Warmup Iteration   2: 12.696 ops/ms
# Warmup Iteration   3: 12.686 ops/ms
Iteration   1: 12.682 ops/ms
Iteration   2: 12.847 ops/ms
Iteration   3: 12.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.704 ±(99.9%) 2.425 ops/ms [Average]
  (min, avg, max) = (12.584, 12.704, 12.847), stdev = 0.133
  CI (99.9%): [10.279, 15.130] (assumes normal distribution)


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
# Warmup Iteration   1: 6.806 ops/ms
# Warmup Iteration   2: 10.643 ops/ms
# Warmup Iteration   3: 10.799 ops/ms
Iteration   1: 10.801 ops/ms
Iteration   2: 10.883 ops/ms
Iteration   3: 10.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.864 ±(99.9%) 1.013 ops/ms [Average]
  (min, avg, max) = (10.801, 10.864, 10.907), stdev = 0.056
  CI (99.9%): [9.851, 11.877] (assumes normal distribution)


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.569 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.544 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (2.512, 2.544, 2.569), stdev = 0.029
  CI (99.9%): [2.016, 3.071] (assumes normal distribution)


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
# Warmup Iteration   1: 3.545 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.431 ±(99.9%) 0.004 ms/op
Iteration   2: 2.435 ±(99.9%) 0.003 ms/op
Iteration   3: 2.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.438 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (2.431, 2.438, 2.449), stdev = 0.009
  CI (99.9%): [2.267, 2.610] (assumes normal distribution)


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
# Warmup Iteration   1: 3.736 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.003 ms/op
Iteration   1: 2.488 ±(99.9%) 0.003 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.463, 2.477, 2.488), stdev = 0.012
  CI (99.9%): [2.254, 2.699] (assumes normal distribution)


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
# Warmup Iteration   1: 4.941 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 2.960 ±(99.9%) 0.005 ms/op
Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
Iteration   3: 2.970 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.980 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (2.960, 2.980, 3.009), stdev = 0.026
  CI (99.9%): [2.507, 3.453] (assumes normal distribution)


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  11.362 ms/op
                 createUser·p0.9999: 13.910 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.649 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 12.294 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  9.107 ms/op
                 createUser·p0.9999: 11.829 ms/op
                 createUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378920
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 182065 
    [ 2.500,  3.750) = 192181 
    [ 3.750,  5.000) = 3721 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     13.586 ms/op
     p(99.9990) =     14.320 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.765 ms/op
                 existUser·p0.999:  7.751 ms/op
                 existUser·p0.9999: 13.666 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  6.727 ms/op
                 existUser·p0.9999: 14.058 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  7.567 ms/op
                 existUser·p0.9999: 12.408 ms/op
                 existUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388281
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 191012 
    [ 2.500,  3.750) = 193452 
    [ 3.750,  5.000) = 2873 
    [ 5.000,  6.250) = 470 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 148 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      7.471 ms/op
     p(99.9900) =     13.861 ms/op
     p(99.9990) =     14.717 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.006 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.118 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  7.158 ms/op
                 getUser·p0.9999: 13.765 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  7.496 ms/op
                 getUser·p0.9999: 12.714 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  5.616 ms/op
                 getUser·p0.9999: 20.808 ms/op
                 getUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387792
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 194167 
    [ 2.500,  5.000) = 192628 
    [ 5.000,  7.500) = 644 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      5.946 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 4.585 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.008 ms/op
Iteration   1: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 11.272 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   2: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  9.553 ms/op
                 listUser·p0.9999: 10.868 ms/op
                 listUser·p1.00:   11.305 ms/op

Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 11.959 ms/op
                 listUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321484
  mean =      2.983 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 95082 
    [ 2.500,  3.750) = 187841 
    [ 3.750,  5.000) = 31945 
    [ 5.000,  6.250) = 5120 
    [ 6.250,  7.500) = 659 
    [ 7.500,  8.750) = 219 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     11.469 ms/op
     p(99.9990) =     12.454 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.418 ± 2.420  ops/ms
ClientPb.existUser                       thrpt       3  13.242 ± 1.594  ops/ms
ClientPb.getUser                         thrpt       3  12.704 ± 2.425  ops/ms
ClientPb.listUser                        thrpt       3  10.864 ± 1.013  ops/ms
ClientPb.createUser                       avgt       3   2.544 ± 0.527   ms/op
ClientPb.existUser                        avgt       3   2.438 ± 0.172   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.223   ms/op
ClientPb.listUser                         avgt       3   2.980 ± 0.473   ms/op
ClientPb.createUser                     sample  378920   2.531 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.764           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.175           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.586           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.565           ms/op
ClientPb.existUser                      sample  388281   2.470 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.751           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.471           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.861           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.860           ms/op
ClientPb.getUser                        sample  387792   2.473 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.798           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.946           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.156           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.922           ms/op
ClientPb.listUser                       sample  321484   2.983 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.849           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.469           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.927           ms/op
