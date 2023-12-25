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
# Warmup Iteration   1: 4.790 ops/ms
# Warmup Iteration   2: 11.885 ops/ms
# Warmup Iteration   3: 12.177 ops/ms
Iteration   1: 12.481 ops/ms
Iteration   2: 12.288 ops/ms
Iteration   3: 12.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.406 ±(99.9%) 1.888 ops/ms [Average]
  (min, avg, max) = (12.288, 12.406, 12.481), stdev = 0.103
  CI (99.9%): [10.518, 14.294] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.616 ops/ms
# Warmup Iteration   2: 13.025 ops/ms
# Warmup Iteration   3: 13.148 ops/ms
Iteration   1: 12.833 ops/ms
Iteration   2: 12.967 ops/ms
Iteration   3: 13.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.934 ±(99.9%) 1.623 ops/ms [Average]
  (min, avg, max) = (12.833, 12.934, 13.001), stdev = 0.089
  CI (99.9%): [11.310, 14.557] (assumes normal distribution)


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
# Warmup Iteration   1: 7.861 ops/ms
# Warmup Iteration   2: 12.593 ops/ms
# Warmup Iteration   3: 12.720 ops/ms
Iteration   1: 12.630 ops/ms
Iteration   2: 12.828 ops/ms
Iteration   3: 12.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.736 ±(99.9%) 1.822 ops/ms [Average]
  (min, avg, max) = (12.630, 12.736, 12.828), stdev = 0.100
  CI (99.9%): [10.914, 14.558] (assumes normal distribution)


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
# Warmup Iteration   1: 6.660 ops/ms
# Warmup Iteration   2: 10.527 ops/ms
# Warmup Iteration   3: 10.569 ops/ms
Iteration   1: 10.629 ops/ms
Iteration   2: 10.588 ops/ms
Iteration   3: 10.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.617 ±(99.9%) 0.462 ops/ms [Average]
  (min, avg, max) = (10.588, 10.617, 10.635), stdev = 0.025
  CI (99.9%): [10.155, 11.079] (assumes normal distribution)


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.004 ms/op
Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
Iteration   3: 2.551 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.552 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (2.536, 2.552, 2.569), stdev = 0.016
  CI (99.9%): [2.254, 2.851] (assumes normal distribution)


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
Iteration   3: 2.403 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.515 ms/op [Average]
  (min, avg, max) = (2.403, 2.426, 2.458), stdev = 0.028
  CI (99.9%): [1.912, 2.941] (assumes normal distribution)


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
# Warmup Iteration   1: 3.920 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.003 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.481, 2.502, 2.514), stdev = 0.018
  CI (99.9%): [2.180, 2.824] (assumes normal distribution)


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.005 ms/op
Iteration   1: 3.046 ±(99.9%) 0.005 ms/op
Iteration   2: 3.045 ±(99.9%) 0.005 ms/op
Iteration   3: 3.040 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.061 ms/op [Average]
  (min, avg, max) = (3.040, 3.044, 3.046), stdev = 0.003
  CI (99.9%): [2.983, 3.105] (assumes normal distribution)


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
# Warmup Iteration   1: 4.296 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.668 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  11.196 ms/op
                 createUser·p0.9999: 14.012 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  8.929 ms/op
                 createUser·p0.9999: 12.240 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.808 ms/op
                 createUser·p0.999:  8.566 ms/op
                 createUser·p0.9999: 12.852 ms/op
                 createUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379914
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 183964 
    [ 2.500,  3.750) = 192148 
    [ 3.750,  5.000) = 3062 
    [ 5.000,  6.250) = 300 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.591 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     14.736 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.735 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  8.472 ms/op
                 existUser·p0.9999: 14.420 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  5.702 ms/op
                 existUser·p0.9999: 14.811 ms/op
                 existUser·p1.00:   15.466 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.944 ms/op
                 existUser·p0.999:  8.188 ms/op
                 existUser·p0.9999: 12.141 ms/op
                 existUser·p1.00:   13.582 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388153
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 192974 
    [ 2.500,  3.750) = 191205 
    [ 3.750,  5.000) = 2989 
    [ 5.000,  6.250) = 496 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      7.198 ms/op
     p(99.9900) =     14.372 ms/op
     p(99.9990) =     14.975 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.674 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
Iteration   1: 2.523 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  11.227 ms/op
                 getUser·p0.9999: 13.997 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  9.880 ms/op
                 getUser·p0.9999: 13.664 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.977 ms/op
                 getUser·p0.999:  7.773 ms/op
                 getUser·p0.9999: 11.527 ms/op
                 getUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379706
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 187033 
    [ 2.500,  3.750) = 187921 
    [ 3.750,  5.000) = 3907 
    [ 5.000,  6.250) = 368 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 123 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.721 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     14.608 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 4.682 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.009 ms/op
Iteration   1: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 11.197 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  11.494 ms/op
                 listUser·p0.9999: 12.793 ms/op
                 listUser·p1.00:   13.828 ms/op

Iteration   3: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 13.793 ms/op
                 listUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316430
  mean =      3.031 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 87879 
    [ 2.500,  3.750) = 189466 
    [ 3.750,  5.000) = 31750 
    [ 5.000,  6.250) = 5749 
    [ 6.250,  7.500) = 819 
    [ 7.500,  8.750) = 232 
    [ 8.750, 10.000) = 139 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.954 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.022 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.406 ± 1.888  ops/ms
ClientPb.existUser                       thrpt       3  12.934 ± 1.623  ops/ms
ClientPb.getUser                         thrpt       3  12.736 ± 1.822  ops/ms
ClientPb.listUser                        thrpt       3  10.617 ± 0.462  ops/ms
ClientPb.createUser                       avgt       3   2.552 ± 0.298   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.515   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.322   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.061   ms/op
ClientPb.createUser                     sample  379914   2.525 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.668           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.591           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.255           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.909           ms/op
ClientPb.existUser                      sample  388153   2.470 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.689           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.198           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.372           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.466           ms/op
ClientPb.getUser                        sample  379706   2.526 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.664           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.721           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.746           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.746           ms/op
ClientPb.listUser                       sample  316430   3.031 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.955           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.954           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.435           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.057           ms/op
