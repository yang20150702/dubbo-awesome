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
# Warmup Iteration   1: 4.676 ops/ms
# Warmup Iteration   2: 11.830 ops/ms
# Warmup Iteration   3: 12.254 ops/ms
Iteration   1: 12.519 ops/ms
Iteration   2: 12.619 ops/ms
Iteration   3: 12.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.579 ±(99.9%) 0.965 ops/ms [Average]
  (min, avg, max) = (12.519, 12.579, 12.619), stdev = 0.053
  CI (99.9%): [11.615, 13.544] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.818 ops/ms
# Warmup Iteration   2: 12.821 ops/ms
# Warmup Iteration   3: 12.951 ops/ms
Iteration   1: 12.744 ops/ms
Iteration   2: 12.930 ops/ms
Iteration   3: 12.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.837 ±(99.9%) 1.703 ops/ms [Average]
  (min, avg, max) = (12.744, 12.837, 12.930), stdev = 0.093
  CI (99.9%): [11.134, 14.540] (assumes normal distribution)


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
# Warmup Iteration   1: 7.759 ops/ms
# Warmup Iteration   2: 12.427 ops/ms
# Warmup Iteration   3: 12.478 ops/ms
Iteration   1: 12.649 ops/ms
Iteration   2: 12.789 ops/ms
Iteration   3: 12.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.784 ±(99.9%) 2.417 ops/ms [Average]
  (min, avg, max) = (12.649, 12.784, 12.914), stdev = 0.132
  CI (99.9%): [10.368, 15.201] (assumes normal distribution)


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
# Warmup Iteration   1: 6.622 ops/ms
# Warmup Iteration   2: 10.385 ops/ms
# Warmup Iteration   3: 10.462 ops/ms
Iteration   1: 10.500 ops/ms
Iteration   2: 10.418 ops/ms
Iteration   3: 10.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.464 ±(99.9%) 0.770 ops/ms [Average]
  (min, avg, max) = (10.418, 10.464, 10.500), stdev = 0.042
  CI (99.9%): [9.694, 11.234] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.277 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.005 ms/op
Iteration   1: 2.569 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
Iteration   3: 2.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (2.526, 2.542, 2.569), stdev = 0.024
  CI (99.9%): [2.104, 2.979] (assumes normal distribution)


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.003 ms/op
Iteration   1: 2.492 ±(99.9%) 0.003 ms/op
Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.494 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.482, 2.494, 2.509), stdev = 0.014
  CI (99.9%): [2.240, 2.749] (assumes normal distribution)


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.004 ms/op
Iteration   1: 2.554 ±(99.9%) 0.004 ms/op
Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.548 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.538, 2.548, 2.554), stdev = 0.008
  CI (99.9%): [2.395, 2.700] (assumes normal distribution)


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
# Warmup Iteration   1: 4.657 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.005 ms/op
Iteration   1: 3.041 ±(99.9%) 0.005 ms/op
Iteration   2: 3.012 ±(99.9%) 0.005 ms/op
Iteration   3: 3.027 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.027 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (3.012, 3.027, 3.041), stdev = 0.014
  CI (99.9%): [2.764, 3.289] (assumes normal distribution)


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.691 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.006 ms/op
Iteration   1: 2.576 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   4.047 ms/op
                 createUser·p0.999:  12.563 ms/op
                 createUser·p0.9999: 13.959 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 2.573 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  10.314 ms/op
                 createUser·p0.9999: 13.306 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   3: 2.579 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.046 ms/op
                 createUser·p0.999:  9.650 ms/op
                 createUser·p0.9999: 11.728 ms/op
                 createUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372244
  mean =      2.576 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 176749 
    [ 2.500,  3.750) = 190043 
    [ 3.750,  5.000) = 4186 
    [ 5.000,  6.250) = 682 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.621 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  5.654 ms/op
                 existUser·p0.9999: 14.287 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  9.760 ms/op
                 existUser·p0.9999: 14.891 ms/op
                 existUser·p1.00:   15.466 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  8.117 ms/op
                 existUser·p0.9999: 11.560 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385781
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 188331 
    [ 2.500,  3.750) = 192819 
    [ 3.750,  5.000) = 3417 
    [ 5.000,  6.250) = 763 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      6.452 ms/op
     p(99.9900) =     14.287 ms/op
     p(99.9990) =     15.434 ms/op
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
# Warmup Iteration   1: 4.222 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.007 ms/op
Iteration   1: 2.551 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   3.967 ms/op
                 getUser·p0.999:  12.293 ms/op
                 getUser·p0.9999: 14.950 ms/op
                 getUser·p1.00:   16.663 ms/op

Iteration   2: 2.572 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.038 ms/op
                 getUser·p0.999:  9.716 ms/op
                 getUser·p0.9999: 13.313 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.581 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.166 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.882 ms/op
                 getUser·p0.9999: 11.168 ms/op
                 getUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 373512
  mean =      2.568 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 180737 
    [ 2.500,  3.750) = 186684 
    [ 3.750,  5.000) = 4582 
    [ 5.000,  6.250) = 998 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.281 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =      7.106 ms/op
     p(99.9900) =     14.270 ms/op
     p(99.9990) =     16.393 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 4.948 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.009 ms/op
Iteration   1: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  8.961 ms/op
                 listUser·p0.9999: 10.715 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   2: 3.068 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.089 ms/op
                 listUser·p0.9999: 11.535 ms/op
                 listUser·p1.00:   14.238 ms/op

Iteration   3: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 11.796 ms/op
                 listUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314371
  mean =      3.051 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 85164 
    [ 2.500,  3.750) = 186818 
    [ 3.750,  5.000) = 34705 
    [ 5.000,  6.250) = 6239 
    [ 6.250,  7.500) = 647 
    [ 7.500,  8.750) = 283 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     11.347 ms/op
     p(99.9990) =     13.011 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.579 ± 0.965  ops/ms
ClientPb.existUser                       thrpt       3  12.837 ± 1.703  ops/ms
ClientPb.getUser                         thrpt       3  12.784 ± 2.417  ops/ms
ClientPb.listUser                        thrpt       3  10.464 ± 0.770  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.438   ms/op
ClientPb.existUser                        avgt       3   2.494 ± 0.254   ms/op
ClientPb.getUser                          avgt       3   2.548 ± 0.152   ms/op
ClientPb.listUser                         avgt       3   3.027 ± 0.263   ms/op
ClientPb.createUser                     sample  372244   2.576 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.739           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.732           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.779           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.795           ms/op
ClientPb.existUser                      sample  385781   2.486 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.695           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.560           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.452           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.287           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.466           ms/op
ClientPb.getUser                        sample  373512   2.568 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.800           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.106           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.270           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.663           ms/op
ClientPb.listUser                       sample  314371   3.051 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.827           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.347           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.238           ms/op
