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
# Warmup Iteration   1: 4.297 ops/ms
# Warmup Iteration   2: 11.652 ops/ms
# Warmup Iteration   3: 11.962 ops/ms
Iteration   1: 12.241 ops/ms
Iteration   2: 12.118 ops/ms
Iteration   3: 12.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.242 ±(99.9%) 2.278 ops/ms [Average]
  (min, avg, max) = (12.118, 12.242, 12.367), stdev = 0.125
  CI (99.9%): [9.964, 14.520] (assumes normal distribution)


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
# Warmup Iteration   1: 8.113 ops/ms
# Warmup Iteration   2: 13.154 ops/ms
# Warmup Iteration   3: 13.025 ops/ms
Iteration   1: 12.797 ops/ms
Iteration   2: 13.032 ops/ms
Iteration   3: 13.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.958 ±(99.9%) 2.551 ops/ms [Average]
  (min, avg, max) = (12.797, 12.958, 13.045), stdev = 0.140
  CI (99.9%): [10.407, 15.509] (assumes normal distribution)


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
# Warmup Iteration   1: 7.810 ops/ms
# Warmup Iteration   2: 12.438 ops/ms
# Warmup Iteration   3: 12.648 ops/ms
Iteration   1: 12.827 ops/ms
Iteration   2: 12.884 ops/ms
Iteration   3: 12.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.814 ±(99.9%) 1.407 ops/ms [Average]
  (min, avg, max) = (12.731, 12.814, 12.884), stdev = 0.077
  CI (99.9%): [11.407, 14.221] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.625 ops/ms
# Warmup Iteration   2: 10.342 ops/ms
# Warmup Iteration   3: 10.313 ops/ms
Iteration   1: 10.379 ops/ms
Iteration   2: 10.363 ops/ms
Iteration   3: 10.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.362 ±(99.9%) 0.313 ops/ms [Average]
  (min, avg, max) = (10.344, 10.362, 10.379), stdev = 0.017
  CI (99.9%): [10.049, 10.675] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.085 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.003 ms/op
Iteration   1: 2.604 ±(99.9%) 0.005 ms/op
Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.575 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (2.559, 2.575, 2.604), stdev = 0.026
  CI (99.9%): [2.104, 3.045] (assumes normal distribution)


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
# Warmup Iteration   1: 3.715 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.003 ms/op
Iteration   3: 2.470 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.475 ±(99.9%) 0.154 ms/op [Average]
  (min, avg, max) = (2.470, 2.475, 2.485), stdev = 0.008
  CI (99.9%): [2.321, 2.629] (assumes normal distribution)


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.524 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.515, 2.524, 2.531), stdev = 0.008
  CI (99.9%): [2.372, 2.676] (assumes normal distribution)


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.005 ms/op
Iteration   2: 3.016 ±(99.9%) 0.004 ms/op
Iteration   3: 2.992 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.002 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (2.992, 3.002, 3.016), stdev = 0.013
  CI (99.9%): [2.771, 3.233] (assumes normal distribution)


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.696 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  12.370 ms/op
                 createUser·p0.9999: 19.937 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.222 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  9.621 ms/op
                 createUser·p0.9999: 12.313 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   3: 2.579 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 10.849 ms/op
                 createUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374215
  mean =      2.563 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 177776 
    [ 2.500,  5.000) = 195347 
    [ 5.000,  7.500) = 647 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     20.669 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.623 ms/op
                 existUser·p0.999:  6.574 ms/op
                 existUser·p0.9999: 14.352 ms/op
                 existUser·p1.00:   15.499 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  7.171 ms/op
                 existUser·p0.9999: 12.894 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  8.557 ms/op
                 existUser·p0.9999: 11.522 ms/op
                 existUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387528
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 189864 
    [ 2.500,  3.750) = 194781 
    [ 3.750,  5.000) = 2187 
    [ 5.000,  6.250) = 234 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      6.664 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     15.045 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  11.967 ms/op
                 getUser·p0.9999: 13.861 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   2: 2.571 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.338 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  9.229 ms/op
                 getUser·p0.9999: 13.414 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  8.098 ms/op
                 getUser·p0.9999: 11.383 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379147
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 184880 
    [ 2.500,  3.750) = 188232 
    [ 3.750,  5.000) = 4718 
    [ 5.000,  6.250) = 718 
    [ 6.250,  7.500) = 151 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      8.156 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     14.523 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.635 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
Iteration   1: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.735 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.507 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 10.797 ms/op
                 listUser·p1.00:   11.452 ms/op

Iteration   2: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.246 ms/op
                 listUser·p0.9999: 11.026 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  8.798 ms/op
                 listUser·p0.9999: 12.282 ms/op
                 listUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320200
  mean =      2.995 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 95064 
    [ 2.500,  3.750) = 187476 
    [ 3.750,  5.000) = 30831 
    [ 5.000,  6.250) = 5555 
    [ 6.250,  7.500) = 444 
    [ 7.500,  8.750) = 259 
    [ 8.750, 10.000) = 260 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     11.058 ms/op
     p(99.9990) =     12.380 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.242 ± 2.278  ops/ms
ClientPb.existUser                       thrpt       3  12.958 ± 2.551  ops/ms
ClientPb.getUser                         thrpt       3  12.814 ± 1.407  ops/ms
ClientPb.listUser                        thrpt       3  10.362 ± 0.313  ops/ms
ClientPb.createUser                       avgt       3   2.575 ± 0.471   ms/op
ClientPb.existUser                        avgt       3   2.475 ± 0.154   ms/op
ClientPb.getUser                          avgt       3   2.524 ± 0.152   ms/op
ClientPb.listUser                         avgt       3   3.002 ± 0.231   ms/op
ClientPb.createUser                     sample  374215   2.563 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.929           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.257           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.976           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.808           ms/op
ClientPb.existUser                      sample  387528   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.680           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.560           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.664           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.910           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.499           ms/op
ClientPb.getUser                        sample  379147   2.530 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.616           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.129           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.156           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.730           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.598           ms/op
ClientPb.listUser                       sample  320200   2.995 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.735           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.058           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.517           ms/op
