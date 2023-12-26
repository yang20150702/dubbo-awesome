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
# Warmup Iteration   1: 4.680 ops/ms
# Warmup Iteration   2: 11.830 ops/ms
# Warmup Iteration   3: 12.250 ops/ms
Iteration   1: 12.529 ops/ms
Iteration   2: 12.604 ops/ms
Iteration   3: 12.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.544 ±(99.9%) 0.995 ops/ms [Average]
  (min, avg, max) = (12.498, 12.544, 12.604), stdev = 0.055
  CI (99.9%): [11.549, 13.539] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.354 ops/ms
# Warmup Iteration   2: 12.977 ops/ms
# Warmup Iteration   3: 12.963 ops/ms
Iteration   1: 12.952 ops/ms
Iteration   2: 12.889 ops/ms
Iteration   3: 12.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.811 ±(99.9%) 3.517 ops/ms [Average]
  (min, avg, max) = (12.591, 12.811, 12.952), stdev = 0.193
  CI (99.9%): [9.294, 16.328] (assumes normal distribution)


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
# Warmup Iteration   1: 7.548 ops/ms
# Warmup Iteration   2: 12.122 ops/ms
# Warmup Iteration   3: 12.376 ops/ms
Iteration   1: 12.507 ops/ms
Iteration   2: 12.447 ops/ms
Iteration   3: 12.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.480 ±(99.9%) 0.551 ops/ms [Average]
  (min, avg, max) = (12.447, 12.480, 12.507), stdev = 0.030
  CI (99.9%): [11.929, 13.031] (assumes normal distribution)


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
# Warmup Iteration   1: 6.762 ops/ms
# Warmup Iteration   2: 10.443 ops/ms
# Warmup Iteration   3: 10.503 ops/ms
Iteration   1: 10.564 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.516 ±(99.9%) 1.185 ops/ms [Average]
  (min, avg, max) = (10.443, 10.516, 10.564), stdev = 0.065
  CI (99.9%): [9.331, 11.702] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.004 ms/op
Iteration   1: 2.585 ±(99.9%) 0.004 ms/op
Iteration   2: 2.569 ±(99.9%) 0.003 ms/op
Iteration   3: 2.540 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.565 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (2.540, 2.565, 2.585), stdev = 0.023
  CI (99.9%): [2.140, 2.989] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.709 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.462 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (2.435, 2.462, 2.492), stdev = 0.028
  CI (99.9%): [1.944, 2.981] (assumes normal distribution)


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.003 ms/op
Iteration   1: 2.545 ±(99.9%) 0.003 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.540 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.536 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (2.524, 2.536, 2.545), stdev = 0.011
  CI (99.9%): [2.333, 2.740] (assumes normal distribution)


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
# Warmup Iteration   1: 4.633 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.005 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
Iteration   3: 3.063 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.070 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (3.058, 3.070, 3.090), stdev = 0.017
  CI (99.9%): [2.759, 3.381] (assumes normal distribution)


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.713 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.624 ±(99.9%) 0.006 ms/op
Iteration   1: 2.587 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  11.942 ms/op
                 createUser·p0.9999: 18.842 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   2: 2.576 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  9.188 ms/op
                 createUser·p0.9999: 11.551 ms/op
                 createUser·p1.00:   12.534 ms/op

Iteration   3: 2.608 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 11.432 ms/op
                 createUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370299
  mean =      2.590 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 175699 
    [ 2.500,  3.750) = 190138 
    [ 3.750,  5.000) = 3476 
    [ 5.000,  6.250) = 448 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 150 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      9.129 ms/op
     p(99.9900) =     15.006 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  6.028 ms/op
                 existUser·p0.9999: 13.524 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  6.179 ms/op
                 existUser·p0.9999: 12.650 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  9.470 ms/op
                 existUser·p0.9999: 13.025 ms/op
                 existUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389209
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 193413 
    [ 2.500,  3.750) = 192714 
    [ 3.750,  5.000) = 2287 
    [ 5.000,  6.250) = 254 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      7.666 ms/op
     p(99.9900) =     13.010 ms/op
     p(99.9990) =     13.886 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.005 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  10.416 ms/op
                 getUser·p0.9999: 13.680 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  8.988 ms/op
                 getUser·p0.9999: 12.059 ms/op
                 getUser·p1.00:   12.485 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  8.601 ms/op
                 getUser·p0.9999: 11.988 ms/op
                 getUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380565
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 186875 
    [ 2.500,  3.750) = 189209 
    [ 3.750,  5.000) = 3671 
    [ 5.000,  6.250) = 322 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     12.908 ms/op
     p(99.9990) =     14.126 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 4.666 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.542 ms/op
                 listUser·p1.00:   11.141 ms/op

Iteration   2: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.232 ms/op
                 listUser·p0.9999: 10.542 ms/op
                 listUser·p1.00:   11.125 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.665 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.263 ms/op
                 listUser·p0.9999: 11.066 ms/op
                 listUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316756
  mean =      3.028 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 91615 
    [ 2.500,  3.750) = 184710 
    [ 3.750,  5.000) = 32879 
    [ 5.000,  6.250) = 6047 
    [ 6.250,  7.500) = 725 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 311 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     10.715 ms/op
     p(99.9990) =     11.188 ms/op
     p(99.9999) =     11.207 ms/op
    p(100.0000) =     11.207 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.544 ± 0.995  ops/ms
ClientPb.existUser                       thrpt       3  12.811 ± 3.517  ops/ms
ClientPb.getUser                         thrpt       3  12.480 ± 0.551  ops/ms
ClientPb.listUser                        thrpt       3  10.516 ± 1.185  ops/ms
ClientPb.createUser                       avgt       3   2.565 ± 0.425   ms/op
ClientPb.existUser                        avgt       3   2.462 ± 0.518   ms/op
ClientPb.getUser                          avgt       3   2.536 ± 0.203   ms/op
ClientPb.listUser                         avgt       3   3.070 ± 0.311   ms/op
ClientPb.createUser                     sample  370299   2.590 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.843           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.129           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.006           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.333           ms/op
ClientPb.existUser                      sample  389209   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.868           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.666           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.010           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.778           ms/op
ClientPb.getUser                        sample  380565   2.520 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.823           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.684           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.908           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.238           ms/op
ClientPb.listUser                       sample  316756   3.028 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.665           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.208           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.715           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.207           ms/op
