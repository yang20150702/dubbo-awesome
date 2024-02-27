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
# Warmup Iteration   1: 4.263 ops/ms
# Warmup Iteration   2: 11.716 ops/ms
# Warmup Iteration   3: 12.036 ops/ms
Iteration   1: 12.321 ops/ms
Iteration   2: 12.326 ops/ms
Iteration   3: 12.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.360 ±(99.9%) 1.151 ops/ms [Average]
  (min, avg, max) = (12.321, 12.360, 12.433), stdev = 0.063
  CI (99.9%): [11.209, 13.510] (assumes normal distribution)


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
# Warmup Iteration   1: 7.485 ops/ms
# Warmup Iteration   2: 12.453 ops/ms
# Warmup Iteration   3: 12.842 ops/ms
Iteration   1: 12.773 ops/ms
Iteration   2: 12.806 ops/ms
Iteration   3: 12.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.747 ±(99.9%) 1.371 ops/ms [Average]
  (min, avg, max) = (12.662, 12.747, 12.806), stdev = 0.075
  CI (99.9%): [11.376, 14.118] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.312 ops/ms
# Warmup Iteration   2: 12.515 ops/ms
# Warmup Iteration   3: 12.553 ops/ms
Iteration   1: 12.634 ops/ms
Iteration   2: 12.746 ops/ms
Iteration   3: 12.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.615 ±(99.9%) 2.572 ops/ms [Average]
  (min, avg, max) = (12.466, 12.615, 12.746), stdev = 0.141
  CI (99.9%): [10.043, 15.188] (assumes normal distribution)


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
# Warmup Iteration   1: 6.347 ops/ms
# Warmup Iteration   2: 10.209 ops/ms
# Warmup Iteration   3: 10.212 ops/ms
Iteration   1: 10.359 ops/ms
Iteration   2: 10.415 ops/ms
Iteration   3: 10.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.329 ±(99.9%) 1.905 ops/ms [Average]
  (min, avg, max) = (10.213, 10.329, 10.415), stdev = 0.104
  CI (99.9%): [8.424, 12.234] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.602 ±(99.9%) 0.005 ms/op
Iteration   1: 2.591 ±(99.9%) 0.005 ms/op
Iteration   2: 2.614 ±(99.9%) 0.004 ms/op
Iteration   3: 2.627 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.611 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (2.591, 2.611, 2.627), stdev = 0.018
  CI (99.9%): [2.284, 2.938] (assumes normal distribution)


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
# Warmup Iteration   1: 3.842 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.004 ms/op
Iteration   1: 2.520 ±(99.9%) 0.004 ms/op
Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
Iteration   3: 2.534 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.526 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (2.520, 2.526, 2.534), stdev = 0.008
  CI (99.9%): [2.384, 2.667] (assumes normal distribution)


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.004 ms/op
Iteration   1: 2.552 ±(99.9%) 0.005 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.526 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.542 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (2.526, 2.542, 2.552), stdev = 0.015
  CI (99.9%): [2.278, 2.807] (assumes normal distribution)


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
# Warmup Iteration   1: 4.960 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.005 ms/op
Iteration   1: 3.114 ±(99.9%) 0.005 ms/op
Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
Iteration   3: 3.117 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.115 ±(99.9%) 0.037 ms/op [Average]
  (min, avg, max) = (3.114, 3.115, 3.117), stdev = 0.002
  CI (99.9%): [3.078, 3.153] (assumes normal distribution)


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.709 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.594 ±(99.9%) 0.006 ms/op
Iteration   1: 2.610 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   4.067 ms/op
                 createUser·p0.999:  6.455 ms/op
                 createUser·p0.9999: 14.410 ms/op
                 createUser·p1.00:   15.335 ms/op

Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  10.136 ms/op
                 createUser·p0.9999: 14.459 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   3: 2.588 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  8.864 ms/op
                 createUser·p0.9999: 12.583 ms/op
                 createUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371117
  mean =      2.584 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 176878 
    [ 2.500,  3.750) = 189634 
    [ 3.750,  5.000) = 3551 
    [ 5.000,  6.250) = 525 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.175 ms/op
     p(99.9900) =     14.303 ms/op
     p(99.9990) =     15.160 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  6.007 ms/op
                 existUser·p0.9999: 14.356 ms/op
                 existUser·p1.00:   15.565 ms/op

Iteration   2: 2.515 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  10.355 ms/op
                 existUser·p0.9999: 14.336 ms/op
                 existUser·p1.00:   15.663 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  8.045 ms/op
                 existUser·p0.9999: 13.173 ms/op
                 existUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381387
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 185724 
    [ 2.500,  3.750) = 192268 
    [ 3.750,  5.000) = 2424 
    [ 5.000,  6.250) = 494 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      8.164 ms/op
     p(99.9900) =     14.123 ms/op
     p(99.9990) =     14.935 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.682 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.613 ±(99.9%) 0.006 ms/op
Iteration   1: 2.607 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.621 ms/op
                 getUser·p0.90:   3.178 ms/op
                 getUser·p0.95:   3.322 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  12.376 ms/op
                 getUser·p0.9999: 14.959 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   2: 2.605 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.174 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  9.475 ms/op
                 getUser·p0.9999: 13.255 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   3: 2.590 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.154 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  8.538 ms/op
                 getUser·p0.9999: 12.266 ms/op
                 getUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 368744
  mean =      2.601 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 177259 
    [ 2.500,  3.750) = 186146 
    [ 3.750,  5.000) = 4155 
    [ 5.000,  6.250) = 687 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.170 ms/op
     p(95.0000) =      3.293 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     13.978 ms/op
     p(99.9990) =     15.106 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 4.941 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.009 ms/op
Iteration   1: 3.095 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.673 ms/op
                 listUser·p0.9999: 12.119 ms/op
                 listUser·p1.00:   12.780 ms/op

Iteration   2: 3.101 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.851 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.994 ms/op
                 listUser·p0.9999: 12.791 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   3: 3.076 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.667 ms/op
                 listUser·p0.999:  9.325 ms/op
                 listUser·p0.9999: 12.718 ms/op
                 listUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310277
  mean =      3.091 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 77273 
    [ 2.500,  3.750) = 188194 
    [ 3.750,  5.000) = 36575 
    [ 5.000,  6.250) = 6618 
    [ 6.250,  7.500) = 826 
    [ 7.500,  8.750) = 188 
    [ 8.750, 10.000) = 281 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     12.613 ms/op
     p(99.9990) =     13.302 ms/op
     p(99.9999) =     13.402 ms/op
    p(100.0000) =     13.402 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.360 ± 1.151  ops/ms
ClientPb.existUser                       thrpt       3  12.747 ± 1.371  ops/ms
ClientPb.getUser                         thrpt       3  12.615 ± 2.572  ops/ms
ClientPb.listUser                        thrpt       3  10.329 ± 1.905  ops/ms
ClientPb.createUser                       avgt       3   2.611 ± 0.327   ms/op
ClientPb.existUser                        avgt       3   2.526 ± 0.142   ms/op
ClientPb.getUser                          avgt       3   2.542 ± 0.265   ms/op
ClientPb.listUser                         avgt       3   3.115 ± 0.037   ms/op
ClientPb.createUser                     sample  371117   2.584 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.830           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.658           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.175           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.303           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.335           ms/op
ClientPb.existUser                      sample  381387   2.514 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.785           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.164           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.123           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.663           ms/op
ClientPb.getUser                        sample  368744   2.601 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.796           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.621           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.634           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.978           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.254           ms/op
ClientPb.listUser                       sample  310277   3.091 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.851           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.031           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.613           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.402           ms/op
