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
# Warmup Iteration   1: 4.747 ops/ms
# Warmup Iteration   2: 11.952 ops/ms
# Warmup Iteration   3: 12.173 ops/ms
Iteration   1: 12.475 ops/ms
Iteration   2: 12.458 ops/ms
Iteration   3: 12.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.453 ±(99.9%) 0.472 ops/ms [Average]
  (min, avg, max) = (12.424, 12.453, 12.475), stdev = 0.026
  CI (99.9%): [11.981, 12.924] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.792 ops/ms
# Warmup Iteration   2: 12.878 ops/ms
# Warmup Iteration   3: 13.013 ops/ms
Iteration   1: 13.083 ops/ms
Iteration   2: 13.078 ops/ms
Iteration   3: 13.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.055 ±(99.9%) 0.805 ops/ms [Average]
  (min, avg, max) = (13.004, 13.055, 13.083), stdev = 0.044
  CI (99.9%): [12.250, 13.859] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.344 ops/ms
# Warmup Iteration   2: 12.502 ops/ms
# Warmup Iteration   3: 12.580 ops/ms
Iteration   1: 12.920 ops/ms
Iteration   2: 12.755 ops/ms
Iteration   3: 12.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.787 ±(99.9%) 2.196 ops/ms [Average]
  (min, avg, max) = (12.686, 12.787, 12.920), stdev = 0.120
  CI (99.9%): [10.591, 14.983] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.510 ops/ms
# Warmup Iteration   2: 10.485 ops/ms
# Warmup Iteration   3: 10.331 ops/ms
Iteration   1: 10.525 ops/ms
Iteration   2: 10.490 ops/ms
Iteration   3: 10.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.478 ±(99.9%) 0.987 ops/ms [Average]
  (min, avg, max) = (10.419, 10.478, 10.525), stdev = 0.054
  CI (99.9%): [9.491, 11.465] (assumes normal distribution)


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.565 ±(99.9%) 0.005 ms/op
Iteration   2: 2.526 ±(99.9%) 0.003 ms/op
Iteration   3: 2.531 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (2.526, 2.541, 2.565), stdev = 0.021
  CI (99.9%): [2.159, 2.923] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.797 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.003 ms/op
Iteration   1: 2.494 ±(99.9%) 0.004 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.472 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.479 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.472, 2.479, 2.494), stdev = 0.013
  CI (99.9%): [2.240, 2.718] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.772 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.003 ms/op
Iteration   1: 2.499 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
Iteration   3: 2.482 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (2.482, 2.492, 2.499), stdev = 0.008
  CI (99.9%): [2.337, 2.646] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.817 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
Iteration   2: 3.028 ±(99.9%) 0.005 ms/op
Iteration   3: 3.042 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.046 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (3.028, 3.046, 3.068), stdev = 0.020
  CI (99.9%): [2.678, 3.414] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.188 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  11.567 ms/op
                 createUser·p0.9999: 14.687 ms/op
                 createUser·p1.00:   15.712 ms/op

Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  9.896 ms/op
                 createUser·p0.9999: 12.757 ms/op
                 createUser·p1.00:   13.500 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.936 ms/op
                 createUser·p0.999:  9.021 ms/op
                 createUser·p0.9999: 11.009 ms/op
                 createUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376604
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 179666 
    [ 2.500,  3.750) = 192976 
    [ 3.750,  5.000) = 3057 
    [ 5.000,  6.250) = 444 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 157 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      9.106 ms/op
     p(99.9900) =     13.714 ms/op
     p(99.9990) =     15.493 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.829 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  5.343 ms/op
                 existUser·p0.9999: 14.090 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  9.428 ms/op
                 existUser·p0.9999: 13.599 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  8.013 ms/op
                 existUser·p0.9999: 12.452 ms/op
                 existUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387375
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 187773 
    [ 2.500,  3.750) = 195939 
    [ 3.750,  5.000) = 2560 
    [ 5.000,  6.250) = 548 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      8.159 ms/op
     p(99.9900) =     13.738 ms/op
     p(99.9990) =     14.172 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.099 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  9.543 ms/op
                 getUser·p0.9999: 13.620 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  8.177 ms/op
                 getUser·p0.9999: 13.732 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  8.919 ms/op
                 getUser·p0.9999: 12.229 ms/op
                 getUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384656
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 190153 
    [ 2.500,  3.750) = 190153 
    [ 3.750,  5.000) = 3316 
    [ 5.000,  6.250) = 520 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      7.906 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     14.142 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.890 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.009 ms/op
Iteration   1: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.528 ms/op
                 listUser·p1.00:   11.289 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  10.093 ms/op
                 listUser·p0.9999: 13.349 ms/op
                 listUser·p1.00:   14.451 ms/op

Iteration   3: 3.083 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 13.343 ms/op
                 listUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312551
  mean =      3.069 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 79210 
    [ 2.500,  3.750) = 189811 
    [ 3.750,  5.000) = 35964 
    [ 5.000,  6.250) = 6124 
    [ 6.250,  7.500) = 684 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 252 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     13.021 ms/op
     p(99.9990) =     14.651 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.453 ± 0.472  ops/ms
ClientPb.existUser                       thrpt       3  13.055 ± 0.805  ops/ms
ClientPb.getUser                         thrpt       3  12.787 ± 2.196  ops/ms
ClientPb.listUser                        thrpt       3  10.478 ± 0.987  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.382   ms/op
ClientPb.existUser                        avgt       3   2.479 ± 0.239   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.155   ms/op
ClientPb.listUser                         avgt       3   3.046 ± 0.368   ms/op
ClientPb.createUser                     sample  376604   2.546 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.831           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.106           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.714           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.712           ms/op
ClientPb.existUser                      sample  387375   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.913           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.159           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.738           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.352           ms/op
ClientPb.getUser                        sample  384656   2.493 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.901           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.906           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.533           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.959           ms/op
ClientPb.listUser                       sample  312551   3.069 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.876           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.617           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.021           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.696           ms/op
