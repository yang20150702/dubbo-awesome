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
# Warmup Iteration   1: 4.890 ops/ms
# Warmup Iteration   2: 12.220 ops/ms
# Warmup Iteration   3: 12.475 ops/ms
Iteration   1: 12.653 ops/ms
Iteration   2: 12.742 ops/ms
Iteration   3: 12.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.684 ±(99.9%) 0.919 ops/ms [Average]
  (min, avg, max) = (12.653, 12.684, 12.742), stdev = 0.050
  CI (99.9%): [11.764, 13.603] (assumes normal distribution)


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
# Warmup Iteration   1: 8.448 ops/ms
# Warmup Iteration   2: 13.110 ops/ms
# Warmup Iteration   3: 13.186 ops/ms
Iteration   1: 13.161 ops/ms
Iteration   2: 13.210 ops/ms
Iteration   3: 13.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.215 ±(99.9%) 1.027 ops/ms [Average]
  (min, avg, max) = (13.161, 13.215, 13.274), stdev = 0.056
  CI (99.9%): [12.188, 14.242] (assumes normal distribution)


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
# Warmup Iteration   1: 7.918 ops/ms
# Warmup Iteration   2: 12.463 ops/ms
# Warmup Iteration   3: 12.647 ops/ms
Iteration   1: 12.702 ops/ms
Iteration   2: 12.746 ops/ms
Iteration   3: 12.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.745 ±(99.9%) 0.773 ops/ms [Average]
  (min, avg, max) = (12.702, 12.745, 12.787), stdev = 0.042
  CI (99.9%): [11.972, 13.518] (assumes normal distribution)


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
# Warmup Iteration   1: 6.521 ops/ms
# Warmup Iteration   2: 10.594 ops/ms
# Warmup Iteration   3: 10.604 ops/ms
Iteration   1: 10.430 ops/ms
Iteration   2: 10.784 ops/ms
Iteration   3: 10.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.643 ±(99.9%) 3.430 ops/ms [Average]
  (min, avg, max) = (10.430, 10.643, 10.784), stdev = 0.188
  CI (99.9%): [7.213, 14.074] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.896 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.486 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (2.469, 2.486, 2.498), stdev = 0.015
  CI (99.9%): [2.219, 2.752] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.704 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.449 ±(99.9%) 0.003 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.468 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (2.449, 2.468, 2.483), stdev = 0.017
  CI (99.9%): [2.155, 2.781] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.003 ms/op
Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
Iteration   3: 2.486 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.489 ±(99.9%) 0.085 ms/op [Average]
  (min, avg, max) = (2.486, 2.489, 2.494), stdev = 0.005
  CI (99.9%): [2.404, 2.573] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.629 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.007 ms/op
Iteration   1: 3.009 ±(99.9%) 0.005 ms/op
Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
Iteration   3: 2.983 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.005 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (2.983, 3.005, 3.023), stdev = 0.020
  CI (99.9%): [2.635, 3.375] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.928 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.491 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.814 ms/op
                 createUser·p0.999:  8.990 ms/op
                 createUser·p0.9999: 17.405 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  10.018 ms/op
                 createUser·p0.9999: 12.953 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   4.082 ms/op
                 createUser·p0.999:  8.607 ms/op
                 createUser·p0.9999: 10.355 ms/op
                 createUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384075
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 188414 
    [ 2.500,  3.750) = 190908 
    [ 3.750,  5.000) = 3466 
    [ 5.000,  6.250) = 633 
    [ 6.250,  7.500) = 124 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     14.329 ms/op
     p(99.9990) =     17.683 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.765 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
Iteration   1: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.801 ms/op
                 existUser·p0.999:  6.983 ms/op
                 existUser·p0.9999: 13.816 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  7.119 ms/op
                 existUser·p0.9999: 12.351 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  5.898 ms/op
                 existUser·p0.9999: 12.150 ms/op
                 existUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396498
  mean =      2.419 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 202524 
    [ 2.500,  3.750) = 190158 
    [ 3.750,  5.000) = 2877 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      6.595 ms/op
     p(99.9900) =     13.266 ms/op
     p(99.9990) =     14.091 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  7.553 ms/op
                 getUser·p0.9999: 13.959 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.961 ms/op
                 getUser·p0.999:  7.236 ms/op
                 getUser·p0.9999: 13.502 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.507 ms/op
                 getUser·p0.9999: 10.718 ms/op
                 getUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386598
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 194078 
    [ 2.500,  3.750) = 186473 
    [ 3.750,  5.000) = 4359 
    [ 5.000,  6.250) = 1110 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      8.308 ms/op
     p(99.9900) =     13.604 ms/op
     p(99.9990) =     14.568 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.679 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.009 ms/op
Iteration   1: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.726 ms/op
                 listUser·p0.9999: 10.453 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   2: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.684 ms/op
                 listUser·p0.9999: 12.384 ms/op
                 listUser·p1.00:   14.828 ms/op

Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.518 ms/op
                 listUser·p0.9999: 10.982 ms/op
                 listUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321192
  mean =      2.987 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 97618 
    [ 2.500,  3.750) = 184463 
    [ 3.750,  5.000) = 31642 
    [ 5.000,  6.250) = 6065 
    [ 6.250,  7.500) = 575 
    [ 7.500,  8.750) = 242 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.418 ms/op
     p(99.9900) =     11.614 ms/op
     p(99.9990) =     13.726 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.684 ± 0.919  ops/ms
ClientPb.existUser                       thrpt       3  13.215 ± 1.027  ops/ms
ClientPb.getUser                         thrpt       3  12.745 ± 0.773  ops/ms
ClientPb.listUser                        thrpt       3  10.643 ± 3.430  ops/ms
ClientPb.createUser                       avgt       3   2.486 ± 0.266   ms/op
ClientPb.existUser                        avgt       3   2.468 ± 0.313   ms/op
ClientPb.getUser                          avgt       3   2.489 ± 0.085   ms/op
ClientPb.listUser                         avgt       3   3.005 ± 0.370   ms/op
ClientPb.createUser                     sample  384075   2.497 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.911           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.634           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.329           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.481           ms/op
ClientPb.existUser                      sample  396498   2.419 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.805           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.458           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.595           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.266           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.221           ms/op
ClientPb.getUser                        sample  386598   2.481 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.868           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.308           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.604           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.615           ms/op
ClientPb.listUser                       sample  321192   2.987 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.882           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.418           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.614           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.828           ms/op
