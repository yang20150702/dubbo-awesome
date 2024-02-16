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
# Warmup Iteration   1: 4.745 ops/ms
# Warmup Iteration   2: 12.239 ops/ms
# Warmup Iteration   3: 12.439 ops/ms
Iteration   1: 12.631 ops/ms
Iteration   2: 12.552 ops/ms
Iteration   3: 12.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.614 ±(99.9%) 1.012 ops/ms [Average]
  (min, avg, max) = (12.552, 12.614, 12.659), stdev = 0.055
  CI (99.9%): [11.602, 13.626] (assumes normal distribution)


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
# Warmup Iteration   1: 8.371 ops/ms
# Warmup Iteration   2: 13.043 ops/ms
# Warmup Iteration   3: 13.125 ops/ms
Iteration   1: 13.159 ops/ms
Iteration   2: 13.208 ops/ms
Iteration   3: 13.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.176 ±(99.9%) 0.515 ops/ms [Average]
  (min, avg, max) = (13.159, 13.176, 13.208), stdev = 0.028
  CI (99.9%): [12.661, 13.690] (assumes normal distribution)


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
# Warmup Iteration   1: 7.281 ops/ms
# Warmup Iteration   2: 12.540 ops/ms
# Warmup Iteration   3: 12.750 ops/ms
Iteration   1: 12.482 ops/ms
Iteration   2: 12.767 ops/ms
Iteration   3: 12.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.670 ±(99.9%) 2.977 ops/ms [Average]
  (min, avg, max) = (12.482, 12.670, 12.767), stdev = 0.163
  CI (99.9%): [9.693, 15.647] (assumes normal distribution)


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
# Warmup Iteration   1: 6.834 ops/ms
# Warmup Iteration   2: 11.071 ops/ms
# Warmup Iteration   3: 11.119 ops/ms
Iteration   1: 11.074 ops/ms
Iteration   2: 11.021 ops/ms
Iteration   3: 11.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  11.036 ±(99.9%) 0.593 ops/ms [Average]
  (min, avg, max) = (11.014, 11.036, 11.074), stdev = 0.033
  CI (99.9%): [10.443, 11.629] (assumes normal distribution)


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (2.483, 2.502, 2.516), stdev = 0.017
  CI (99.9%): [2.187, 2.818] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.583 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.358 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.381 ±(99.9%) 0.004 ms/op
Iteration   1: 2.410 ±(99.9%) 0.004 ms/op
Iteration   2: 2.404 ±(99.9%) 0.003 ms/op
Iteration   3: 2.400 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.405 ±(99.9%) 0.090 ms/op [Average]
  (min, avg, max) = (2.400, 2.405, 2.410), stdev = 0.005
  CI (99.9%): [2.314, 2.495] (assumes normal distribution)


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
# Warmup Iteration   1: 4.075 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.002 ms/op
Iteration   2: 2.530 ±(99.9%) 0.003 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.504 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (2.486, 2.504, 2.530), stdev = 0.023
  CI (99.9%): [2.087, 2.921] (assumes normal distribution)


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
# Warmup Iteration   1: 4.794 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.005 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
Iteration   2: 3.028 ±(99.9%) 0.004 ms/op
Iteration   3: 3.013 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.019 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (3.013, 3.019, 3.028), stdev = 0.008
  CI (99.9%): [2.877, 3.161] (assumes normal distribution)


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.661 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.528 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  11.715 ms/op
                 createUser·p0.9999: 13.458 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  9.161 ms/op
                 createUser·p0.9999: 13.039 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   4.118 ms/op
                 createUser·p0.999:  8.720 ms/op
                 createUser·p0.9999: 10.819 ms/op
                 createUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380004
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 180895 
    [ 2.500,  3.750) = 194436 
    [ 3.750,  5.000) = 3529 
    [ 5.000,  6.250) = 653 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     13.979 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  5.910 ms/op
                 existUser·p0.9999: 16.368 ms/op
                 existUser·p1.00:   16.744 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  5.791 ms/op
                 existUser·p0.9999: 12.794 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  8.716 ms/op
                 existUser·p0.9999: 12.747 ms/op
                 existUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390811
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 193263 
    [ 2.500,  3.750) = 194506 
    [ 3.750,  5.000) = 2106 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 137 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     15.005 ms/op
     p(99.9990) =     16.552 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


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
# Warmup Iteration   1: 3.853 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.499 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.973 ms/op
                 getUser·p0.999:  11.293 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.951 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 13.061 ms/op
                 getUser·p1.00:   13.795 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  8.304 ms/op
                 getUser·p0.9999: 11.768 ms/op
                 getUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383744
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 189611 
    [ 2.500,  3.750) = 189249 
    [ 3.750,  5.000) = 3860 
    [ 5.000,  6.250) = 535 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      8.358 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     14.182 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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
# Warmup Iteration   1: 4.748 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.008 ms/op
Iteration   1: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.858 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 11.600 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   2: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.765 ms/op
                 listUser·p0.9999: 11.797 ms/op
                 listUser·p1.00:   12.747 ms/op

Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.048 ms/op
                 listUser·p0.9999: 10.789 ms/op
                 listUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314524
  mean =      3.050 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 84586 
    [ 2.500,  3.750) = 187413 
    [ 3.750,  5.000) = 35079 
    [ 5.000,  6.250) = 6011 
    [ 6.250,  7.500) = 600 
    [ 7.500,  8.750) = 220 
    [ 8.750, 10.000) = 259 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.330 ms/op
     p(99.9900) =     11.454 ms/op
     p(99.9990) =     12.424 ms/op
     p(99.9999) =     12.747 ms/op
    p(100.0000) =     12.747 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.614 ± 1.012  ops/ms
ClientPb.existUser                       thrpt       3  13.176 ± 0.515  ops/ms
ClientPb.getUser                         thrpt       3  12.670 ± 2.977  ops/ms
ClientPb.listUser                        thrpt       3  11.036 ± 0.593  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.316   ms/op
ClientPb.existUser                        avgt       3   2.405 ± 0.090   ms/op
ClientPb.getUser                          avgt       3   2.504 ± 0.417   ms/op
ClientPb.listUser                         avgt       3   3.019 ± 0.142   ms/op
ClientPb.createUser                     sample  380004   2.524 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.937           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.749           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.238           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.369           ms/op
ClientPb.existUser                      sample  390811   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.885           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.634           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.005           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.744           ms/op
ClientPb.getUser                        sample  383744   2.500 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.820           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.358           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.550           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.844           ms/op
ClientPb.listUser                       sample  314524   3.050 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.858           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.330           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.454           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.747           ms/op
