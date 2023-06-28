# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.857 ops/ms
# Warmup Iteration   2: 8.224 ops/ms
# Warmup Iteration   3: 9.602 ops/ms
Iteration   1: 10.069 ops/ms
Iteration   2: 10.146 ops/ms
Iteration   3: 10.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.126 ±(99.9%) 0.910 ops/ms [Average]
  (min, avg, max) = (10.069, 10.126, 10.163), stdev = 0.050
  CI (99.9%): [9.216, 11.036] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.246 ops/ms
# Warmup Iteration   2: 10.494 ops/ms
# Warmup Iteration   3: 10.966 ops/ms
Iteration   1: 10.685 ops/ms
Iteration   2: 10.777 ops/ms
Iteration   3: 10.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.807 ±(99.9%) 2.538 ops/ms [Average]
  (min, avg, max) = (10.685, 10.807, 10.959), stdev = 0.139
  CI (99.9%): [8.269, 13.345] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.493 ops/ms
# Warmup Iteration   2: 9.775 ops/ms
# Warmup Iteration   3: 10.380 ops/ms
Iteration   1: 10.439 ops/ms
Iteration   2: 10.729 ops/ms
Iteration   3: 10.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.594 ±(99.9%) 2.663 ops/ms [Average]
  (min, avg, max) = (10.439, 10.594, 10.729), stdev = 0.146
  CI (99.9%): [7.931, 13.256] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.767 ops/ms
# Warmup Iteration   2: 7.905 ops/ms
# Warmup Iteration   3: 7.917 ops/ms
Iteration   1: 7.990 ops/ms
Iteration   2: 8.135 ops/ms
Iteration   3: 8.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.055 ±(99.9%) 1.342 ops/ms [Average]
  (min, avg, max) = (7.990, 8.055, 8.135), stdev = 0.074
  CI (99.9%): [6.713, 9.397] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.285 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.016 ±(99.9%) 0.002 ms/op
Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
Iteration   3: 3.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.022 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (3.012, 3.022, 3.038), stdev = 0.014
  CI (99.9%): [2.765, 3.278] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.044 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.002 ms/op
Iteration   1: 2.936 ±(99.9%) 0.003 ms/op
Iteration   2: 2.925 ±(99.9%) 0.002 ms/op
Iteration   3: 2.762 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.874 ±(99.9%) 1.780 ms/op [Average]
  (min, avg, max) = (2.762, 2.874, 2.936), stdev = 0.098
  CI (99.9%): [1.095, 4.654] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.990 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.002 ms/op
Iteration   1: 3.057 ±(99.9%) 0.004 ms/op
Iteration   2: 3.063 ±(99.9%) 0.004 ms/op
Iteration   3: 3.055 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.058 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (3.055, 3.058, 3.063), stdev = 0.004
  CI (99.9%): [2.982, 3.135] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.374 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.012 ms/op
Iteration   1: 3.926 ±(99.9%) 0.018 ms/op
Iteration   2: 4.012 ±(99.9%) 0.015 ms/op
Iteration   3: 3.876 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.938 ±(99.9%) 1.254 ms/op [Average]
  (min, avg, max) = (3.876, 3.938, 4.012), stdev = 0.069
  CI (99.9%): [2.684, 5.191] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.386 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.281 ms/op
                 createUser·p0.9999: 14.178 ms/op
                 createUser·p1.00:   14.631 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.762 ms/op
                 createUser·p0.9999: 14.631 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  12.242 ms/op
                 createUser·p0.9999: 18.858 ms/op
                 createUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315883
  mean =      3.037 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 583 
    [ 1.250,  2.500) = 28724 
    [ 2.500,  3.750) = 266805 
    [ 3.750,  5.000) = 18250 
    [ 5.000,  6.250) = 958 
    [ 6.250,  7.500) = 149 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.882 ms/op
     p(99.9900) =     18.508 ms/op
     p(99.9990) =     19.429 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.012 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.005 ms/op
Iteration   1: 2.873 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.391 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.050 ms/op
                 existUser·p0.9999: 18.907 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   2: 2.910 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  6.153 ms/op
                 existUser·p0.9999: 14.795 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   3: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  7.979 ms/op
                 existUser·p0.9999: 18.711 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330660
  mean =      2.905 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1875 
    [ 1.250,  2.500) = 35729 
    [ 2.500,  3.750) = 284166 
    [ 3.750,  5.000) = 8075 
    [ 5.000,  6.250) = 426 
    [ 6.250,  7.500) = 165 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      6.450 ms/op
     p(99.9900) =     18.741 ms/op
     p(99.9990) =     19.192 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.366 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.587 ms/op
                 getUser·p0.999:  9.365 ms/op
                 getUser·p0.9999: 14.118 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.855 ms/op
                 getUser·p0.9999: 15.616 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.776 ms/op
                 getUser·p0.999:  7.256 ms/op
                 getUser·p0.9999: 18.230 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316524
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 698 
    [ 1.250,  2.500) = 21647 
    [ 2.500,  3.750) = 277769 
    [ 3.750,  5.000) = 14612 
    [ 5.000,  6.250) = 1032 
    [ 6.250,  7.500) = 357 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.511 ms/op
     p(99.9900) =     16.800 ms/op
     p(99.9990) =     18.640 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.289 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.010 ms/op
Iteration   1: 3.969 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 18.348 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 4.000 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  12.928 ms/op
                 listUser·p0.9999: 15.925 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   3: 3.972 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  16.237 ms/op
                 listUser·p0.9999: 21.560 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241076
  mean =      3.980 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2659 
    [ 2.500,  5.000) = 216285 
    [ 5.000,  7.500) = 21008 
    [ 7.500, 10.000) = 684 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     21.718 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.126 ± 0.910  ops/ms
ClientGrpc.existUser                       thrpt       3  10.807 ± 2.538  ops/ms
ClientGrpc.getUser                         thrpt       3  10.594 ± 2.663  ops/ms
ClientGrpc.listUser                        thrpt       3   8.055 ± 1.342  ops/ms
ClientGrpc.createUser                       avgt       3   3.022 ± 0.256   ms/op
ClientGrpc.existUser                        avgt       3   2.874 ± 1.780   ms/op
ClientGrpc.getUser                          avgt       3   3.058 ± 0.077   ms/op
ClientGrpc.listUser                         avgt       3   3.938 ± 1.254   ms/op
ClientGrpc.createUser                     sample  315883   3.037 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.637           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.882           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.508           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.595           ms/op
ClientGrpc.existUser                      sample  330660   2.905 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.708           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.450           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.741           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.825           ms/op
ClientGrpc.getUser                        sample  316524   3.032 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.723           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.511           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.800           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.874           ms/op
ClientGrpc.listUser                       sample  241076   3.980 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.114           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.074           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.743           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.823           ms/op
