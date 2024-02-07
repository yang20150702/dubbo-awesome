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
# Warmup Iteration   1: 5.047 ops/ms
# Warmup Iteration   2: 11.986 ops/ms
# Warmup Iteration   3: 12.258 ops/ms
Iteration   1: 12.425 ops/ms
Iteration   2: 12.523 ops/ms
Iteration   3: 12.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.530 ±(99.9%) 1.983 ops/ms [Average]
  (min, avg, max) = (12.425, 12.530, 12.642), stdev = 0.109
  CI (99.9%): [10.547, 14.513] (assumes normal distribution)


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
# Warmup Iteration   1: 8.324 ops/ms
# Warmup Iteration   2: 12.783 ops/ms
# Warmup Iteration   3: 12.979 ops/ms
Iteration   1: 12.837 ops/ms
Iteration   2: 12.899 ops/ms
Iteration   3: 12.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.905 ±(99.9%) 1.310 ops/ms [Average]
  (min, avg, max) = (12.837, 12.905, 12.980), stdev = 0.072
  CI (99.9%): [11.595, 14.215] (assumes normal distribution)


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
# Warmup Iteration   1: 7.472 ops/ms
# Warmup Iteration   2: 12.638 ops/ms
# Warmup Iteration   3: 12.719 ops/ms
Iteration   1: 12.753 ops/ms
Iteration   2: 13.039 ops/ms
Iteration   3: 12.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.914 ±(99.9%) 2.671 ops/ms [Average]
  (min, avg, max) = (12.753, 12.914, 13.039), stdev = 0.146
  CI (99.9%): [10.243, 15.586] (assumes normal distribution)


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
# Warmup Iteration   1: 6.790 ops/ms
# Warmup Iteration   2: 10.439 ops/ms
# Warmup Iteration   3: 10.690 ops/ms
Iteration   1: 10.681 ops/ms
Iteration   2: 10.601 ops/ms
Iteration   3: 10.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.608 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (10.541, 10.608, 10.681), stdev = 0.070
  CI (99.9%): [9.325, 11.891] (assumes normal distribution)


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.004 ms/op
Iteration   1: 2.523 ±(99.9%) 0.004 ms/op
Iteration   2: 2.581 ±(99.9%) 0.005 ms/op
Iteration   3: 2.568 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.557 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (2.523, 2.557, 2.581), stdev = 0.030
  CI (99.9%): [2.007, 3.107] (assumes normal distribution)


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.491 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.511 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (2.491, 2.511, 2.528), stdev = 0.018
  CI (99.9%): [2.178, 2.844] (assumes normal distribution)


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.004 ms/op
Iteration   1: 2.577 ±(99.9%) 0.004 ms/op
Iteration   2: 2.554 ±(99.9%) 0.003 ms/op
Iteration   3: 2.577 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.569 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.554, 2.569, 2.577), stdev = 0.013
  CI (99.9%): [2.329, 2.810] (assumes normal distribution)


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
# Warmup Iteration   1: 4.690 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
Iteration   1: 2.992 ±(99.9%) 0.005 ms/op
Iteration   2: 2.984 ±(99.9%) 0.005 ms/op
Iteration   3: 2.978 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.985 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (2.978, 2.985, 2.992), stdev = 0.007
  CI (99.9%): [2.858, 3.111] (assumes normal distribution)


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
# Warmup Iteration   1: 4.264 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.690 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.531 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  11.206 ms/op
                 createUser·p0.9999: 13.922 ms/op
                 createUser·p1.00:   15.008 ms/op

Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.543 ms/op
                 createUser·p0.999:  9.847 ms/op
                 createUser·p0.9999: 12.620 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  8.126 ms/op
                 createUser·p0.9999: 11.582 ms/op
                 createUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377279
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 181707 
    [ 2.500,  3.750) = 192082 
    [ 3.750,  5.000) = 2564 
    [ 5.000,  6.250) = 402 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      8.892 ms/op
     p(99.9900) =     13.275 ms/op
     p(99.9990) =     14.589 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  6.179 ms/op
                 existUser·p0.9999: 14.797 ms/op
                 existUser·p1.00:   15.745 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  8.156 ms/op
                 existUser·p0.9999: 13.555 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  8.312 ms/op
                 existUser·p0.9999: 12.277 ms/op
                 existUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387191
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 189676 
    [ 2.500,  3.750) = 194978 
    [ 3.750,  5.000) = 1868 
    [ 5.000,  6.250) = 234 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.490 ms/op
     p(99.9000) =      8.133 ms/op
     p(99.9900) =     13.915 ms/op
     p(99.9990) =     15.639 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  12.538 ms/op
                 getUser·p0.9999: 17.712 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.535 ms/op
                 getUser·p0.999:  9.317 ms/op
                 getUser·p0.9999: 13.865 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.014 ms/op
                 getUser·p0.999:  9.525 ms/op
                 getUser·p0.9999: 10.835 ms/op
                 getUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381292
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 187971 
    [ 2.500,  3.750) = 189451 
    [ 3.750,  5.000) = 3030 
    [ 5.000,  6.250) = 344 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     16.318 ms/op
     p(99.9990) =     18.303 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.752 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
Iteration   1: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 11.199 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   2: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  10.161 ms/op
                 listUser·p0.9999: 13.009 ms/op
                 listUser·p1.00:   13.550 ms/op

Iteration   3: 3.059 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 12.748 ms/op
                 listUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313749
  mean =      3.057 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 81358 
    [ 2.500,  3.750) = 191159 
    [ 3.750,  5.000) = 34367 
    [ 5.000,  6.250) = 5431 
    [ 6.250,  7.500) = 650 
    [ 7.500,  8.750) = 262 
    [ 8.750, 10.000) = 201 
    [10.000, 11.250) = 154 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     12.669 ms/op
     p(99.9990) =     13.337 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.530 ± 1.983  ops/ms
ClientPb.existUser                       thrpt       3  12.905 ± 1.310  ops/ms
ClientPb.getUser                         thrpt       3  12.914 ± 2.671  ops/ms
ClientPb.listUser                        thrpt       3  10.608 ± 1.283  ops/ms
ClientPb.createUser                       avgt       3   2.557 ± 0.550   ms/op
ClientPb.existUser                        avgt       3   2.511 ± 0.333   ms/op
ClientPb.getUser                          avgt       3   2.569 ± 0.241   ms/op
ClientPb.listUser                         avgt       3   2.985 ± 0.127   ms/op
ClientPb.createUser                     sample  377279   2.542 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.781           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.892           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.275           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.008           ms/op
ClientPb.existUser                      sample  387191   2.477 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.818           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.560           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.133           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.915           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.745           ms/op
ClientPb.getUser                        sample  381292   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.756           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.404           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.318           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.169           ms/op
ClientPb.listUser                       sample  313749   3.057 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.856           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.669           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.550           ms/op
