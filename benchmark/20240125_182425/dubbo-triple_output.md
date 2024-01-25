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
# Warmup Iteration   1: 5.412 ops/ms
# Warmup Iteration   2: 11.927 ops/ms
# Warmup Iteration   3: 12.404 ops/ms
Iteration   1: 12.605 ops/ms
Iteration   2: 12.722 ops/ms
Iteration   3: 12.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.707 ±(99.9%) 1.730 ops/ms [Average]
  (min, avg, max) = (12.605, 12.707, 12.793), stdev = 0.095
  CI (99.9%): [10.977, 14.437] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 8.459 ops/ms
# Warmup Iteration   2: 13.130 ops/ms
# Warmup Iteration   3: 13.175 ops/ms
Iteration   1: 13.066 ops/ms
Iteration   2: 13.223 ops/ms
Iteration   3: 13.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.184 ±(99.9%) 1.905 ops/ms [Average]
  (min, avg, max) = (13.066, 13.184, 13.263), stdev = 0.104
  CI (99.9%): [11.279, 15.089] (assumes normal distribution)


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
# Warmup Iteration   1: 7.905 ops/ms
# Warmup Iteration   2: 12.638 ops/ms
# Warmup Iteration   3: 12.895 ops/ms
Iteration   1: 12.988 ops/ms
Iteration   2: 12.954 ops/ms
Iteration   3: 12.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.975 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (12.954, 12.975, 12.988), stdev = 0.019
  CI (99.9%): [12.636, 13.315] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.950 ops/ms
# Warmup Iteration   2: 10.589 ops/ms
# Warmup Iteration   3: 10.779 ops/ms
Iteration   1: 10.839 ops/ms
Iteration   2: 10.850 ops/ms
Iteration   3: 10.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.804 ±(99.9%) 1.290 ops/ms [Average]
  (min, avg, max) = (10.723, 10.804, 10.850), stdev = 0.071
  CI (99.9%): [9.514, 12.094] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.005 ms/op
Iteration   1: 2.556 ±(99.9%) 0.004 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.526 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.532 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (2.514, 2.532, 2.556), stdev = 0.021
  CI (99.9%): [2.145, 2.919] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.659 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.444 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.431, 2.444, 2.454), stdev = 0.011
  CI (99.9%): [2.236, 2.651] (assumes normal distribution)


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.493 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (2.470, 2.492, 2.513), stdev = 0.022
  CI (99.9%): [2.094, 2.890] (assumes normal distribution)


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 2.958 ±(99.9%) 0.005 ms/op
Iteration   2: 2.945 ±(99.9%) 0.004 ms/op
Iteration   3: 2.977 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.960 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (2.945, 2.960, 2.977), stdev = 0.016
  CI (99.9%): [2.671, 3.249] (assumes normal distribution)


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.682 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
Iteration   1: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  11.436 ms/op
                 createUser·p0.9999: 14.041 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  9.225 ms/op
                 createUser·p0.9999: 11.892 ms/op
                 createUser·p1.00:   12.403 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  8.890 ms/op
                 createUser·p0.9999: 10.760 ms/op
                 createUser·p1.00:   10.961 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379860
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 182333 
    [ 2.500,  3.750) = 193726 
    [ 3.750,  5.000) = 2912 
    [ 5.000,  6.250) = 354 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 127 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      9.210 ms/op
     p(99.9900) =     13.534 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  6.212 ms/op
                 existUser·p0.9999: 13.500 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.516 ms/op
                 existUser·p0.999:  6.664 ms/op
                 existUser·p0.9999: 12.813 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  5.480 ms/op
                 existUser·p0.9999: 12.812 ms/op
                 existUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388785
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 190607 
    [ 2.500,  3.750) = 195371 
    [ 3.750,  5.000) = 2126 
    [ 5.000,  6.250) = 266 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.531 ms/op
     p(99.9000) =      6.064 ms/op
     p(99.9900) =     13.158 ms/op
     p(99.9990) =     13.901 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.006 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  7.233 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.527 ms/op
                 getUser·p0.999:  7.323 ms/op
                 getUser·p0.9999: 12.173 ms/op
                 getUser·p1.00:   12.550 ms/op

Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  8.410 ms/op
                 getUser·p0.9999: 11.135 ms/op
                 getUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386041
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 192538 
    [ 2.500,  3.750) = 188388 
    [ 3.750,  5.000) = 3346 
    [ 5.000,  6.250) = 1168 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      8.380 ms/op
     p(99.9900) =     12.599 ms/op
     p(99.9990) =     14.158 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 4.818 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.009 ms/op
Iteration   1: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.686 ms/op
                 listUser·p0.9999: 11.245 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.635 ms/op
                 listUser·p0.999:  8.830 ms/op
                 listUser·p0.9999: 10.921 ms/op
                 listUser·p1.00:   12.091 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.753 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320589
  mean =      2.992 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 96053 
    [ 2.500,  3.750) = 187082 
    [ 3.750,  5.000) = 30538 
    [ 5.000,  6.250) = 5471 
    [ 6.250,  7.500) = 671 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 263 
    [10.000, 11.250) = 167 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.108 ms/op
     p(99.9990) =     12.015 ms/op
     p(99.9999) =     12.091 ms/op
    p(100.0000) =     12.091 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.707 ± 1.730  ops/ms
ClientPb.existUser                       thrpt       3  13.184 ± 1.905  ops/ms
ClientPb.getUser                         thrpt       3  12.975 ± 0.340  ops/ms
ClientPb.listUser                        thrpt       3  10.804 ± 1.290  ops/ms
ClientPb.createUser                       avgt       3   2.532 ± 0.387   ms/op
ClientPb.existUser                        avgt       3   2.444 ± 0.207   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.398   ms/op
ClientPb.listUser                         avgt       3   2.960 ± 0.289   ms/op
ClientPb.createUser                     sample  379860   2.525 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.975           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.210           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.534           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.549           ms/op
ClientPb.existUser                      sample  388785   2.467 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.907           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.064           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.158           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.270           ms/op
ClientPb.getUser                        sample  386041   2.485 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.860           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.380           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.599           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.238           ms/op
ClientPb.listUser                       sample  320589   2.992 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.108           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.091           ms/op
