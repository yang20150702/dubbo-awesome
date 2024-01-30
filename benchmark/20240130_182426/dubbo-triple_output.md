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
# Warmup Iteration   1: 4.823 ops/ms
# Warmup Iteration   2: 12.257 ops/ms
# Warmup Iteration   3: 12.352 ops/ms
Iteration   1: 12.569 ops/ms
Iteration   2: 12.514 ops/ms
Iteration   3: 12.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.586 ±(99.9%) 1.483 ops/ms [Average]
  (min, avg, max) = (12.514, 12.586, 12.674), stdev = 0.081
  CI (99.9%): [11.103, 14.069] (assumes normal distribution)


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
# Warmup Iteration   1: 8.313 ops/ms
# Warmup Iteration   2: 12.716 ops/ms
# Warmup Iteration   3: 12.922 ops/ms
Iteration   1: 12.796 ops/ms
Iteration   2: 12.883 ops/ms
Iteration   3: 12.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.841 ±(99.9%) 0.793 ops/ms [Average]
  (min, avg, max) = (12.796, 12.841, 12.883), stdev = 0.043
  CI (99.9%): [12.048, 13.633] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.014 ops/ms
# Warmup Iteration   2: 12.477 ops/ms
# Warmup Iteration   3: 12.732 ops/ms
Iteration   1: 12.934 ops/ms
Iteration   2: 12.922 ops/ms
Iteration   3: 12.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.863 ±(99.9%) 2.067 ops/ms [Average]
  (min, avg, max) = (12.732, 12.863, 12.934), stdev = 0.113
  CI (99.9%): [10.796, 14.930] (assumes normal distribution)


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
# Warmup Iteration   1: 6.411 ops/ms
# Warmup Iteration   2: 10.334 ops/ms
# Warmup Iteration   3: 10.371 ops/ms
Iteration   1: 10.392 ops/ms
Iteration   2: 10.496 ops/ms
Iteration   3: 10.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.466 ±(99.9%) 1.169 ops/ms [Average]
  (min, avg, max) = (10.392, 10.466, 10.510), stdev = 0.064
  CI (99.9%): [9.297, 11.635] (assumes normal distribution)


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.004 ms/op
Iteration   1: 2.558 ±(99.9%) 0.004 ms/op
Iteration   2: 2.610 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.568 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (2.537, 2.568, 2.610), stdev = 0.038
  CI (99.9%): [1.883, 3.253] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.782 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.482 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (2.474, 2.482, 2.487), stdev = 0.007
  CI (99.9%): [2.352, 2.611] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.003 ms/op
Iteration   1: 2.513 ±(99.9%) 0.003 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.498 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (2.490, 2.498, 2.513), stdev = 0.014
  CI (99.9%): [2.251, 2.745] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.724 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.005 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
Iteration   2: 2.991 ±(99.9%) 0.006 ms/op
Iteration   3: 3.046 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.010 ±(99.9%) 0.564 ms/op [Average]
  (min, avg, max) = (2.991, 3.010, 3.046), stdev = 0.031
  CI (99.9%): [2.446, 3.575] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.327 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.683 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  12.067 ms/op
                 createUser·p0.9999: 14.507 ms/op
                 createUser·p1.00:   15.647 ms/op

Iteration   2: 2.560 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  10.109 ms/op
                 createUser·p0.9999: 12.387 ms/op
                 createUser·p1.00:   12.894 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  6.603 ms/op
                 createUser·p0.9999: 11.026 ms/op
                 createUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375736
  mean =      2.552 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 176955 
    [ 2.500,  3.750) = 194294 
    [ 3.750,  5.000) = 3595 
    [ 5.000,  6.250) = 433 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      6.828 ms/op
     p(99.9900) =     14.015 ms/op
     p(99.9990) =     15.278 ms/op
     p(99.9999) =     15.647 ms/op
    p(100.0000) =     15.647 ms/op


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.577 ms/op
                 existUser·p0.999:  8.158 ms/op
                 existUser·p0.9999: 13.437 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  8.300 ms/op
                 existUser·p0.9999: 18.121 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.634 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.908 ms/op
                 existUser·p0.999:  6.708 ms/op
                 existUser·p0.9999: 11.420 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384775
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 186543 
    [ 2.500,  3.750) = 194834 
    [ 3.750,  5.000) = 2483 
    [ 5.000,  6.250) = 449 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      7.186 ms/op
     p(99.9900) =     13.567 ms/op
     p(99.9990) =     18.814 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.924 ms/op
                 getUser·p0.999:  11.671 ms/op
                 getUser·p0.9999: 13.522 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  10.175 ms/op
                 getUser·p0.9999: 13.664 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  8.974 ms/op
                 getUser·p0.9999: 11.158 ms/op
                 getUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377940
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 182083 
    [ 2.500,  3.750) = 188420 
    [ 3.750,  5.000) = 5550 
    [ 5.000,  6.250) = 1312 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 151 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.996 ms/op
     p(99.9900) =     13.432 ms/op
     p(99.9990) =     13.815 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.992 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.009 ms/op
Iteration   1: 3.133 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   3.080 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  8.798 ms/op
                 listUser·p0.9999: 11.076 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   2: 3.107 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.874 ms/op
                 listUser·p0.999:  9.406 ms/op
                 listUser·p0.9999: 11.908 ms/op
                 listUser·p1.00:   12.567 ms/op

Iteration   3: 3.078 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.472 ms/op
                 listUser·p0.9999: 11.473 ms/op
                 listUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 308775
  mean =      3.106 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 77238 
    [ 2.500,  3.750) = 185884 
    [ 3.750,  5.000) = 36890 
    [ 5.000,  6.250) = 7211 
    [ 6.250,  7.500) = 779 
    [ 7.500,  8.750) = 233 
    [ 8.750, 10.000) = 298 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =      9.359 ms/op
     p(99.9900) =     11.389 ms/op
     p(99.9990) =     12.349 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.586 ± 1.483  ops/ms
ClientPb.existUser                       thrpt       3  12.841 ± 0.793  ops/ms
ClientPb.getUser                         thrpt       3  12.863 ± 2.067  ops/ms
ClientPb.listUser                        thrpt       3  10.466 ± 1.169  ops/ms
ClientPb.createUser                       avgt       3   2.568 ± 0.685   ms/op
ClientPb.existUser                        avgt       3   2.482 ± 0.129   ms/op
ClientPb.getUser                          avgt       3   2.498 ± 0.247   ms/op
ClientPb.listUser                         avgt       3   3.010 ± 0.564   ms/op
ClientPb.createUser                     sample  375736   2.552 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.924           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.828           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.015           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.647           ms/op
ClientPb.existUser                      sample  384775   2.493 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.888           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.597           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.186           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.567           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.169           ms/op
ClientPb.getUser                        sample  377940   2.538 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.706           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.996           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.432           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.549           ms/op
ClientPb.listUser                       sample  308775   3.106 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.781           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.052           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.784           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.359           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.389           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.567           ms/op
