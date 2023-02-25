# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.636 ops/ms
# Warmup Iteration   2: 9.206 ops/ms
# Warmup Iteration   3: 10.204 ops/ms
Iteration   1: 10.248 ops/ms
Iteration   2: 10.125 ops/ms
Iteration   3: 10.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.127 ±(99.9%) 2.187 ops/ms [Average]
  (min, avg, max) = (10.008, 10.127, 10.248), stdev = 0.120
  CI (99.9%): [7.941, 12.314] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.741 ops/ms
# Warmup Iteration   2: 10.164 ops/ms
# Warmup Iteration   3: 10.714 ops/ms
Iteration   1: 10.894 ops/ms
Iteration   2: 10.666 ops/ms
Iteration   3: 10.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.784 ±(99.9%) 2.084 ops/ms [Average]
  (min, avg, max) = (10.666, 10.784, 10.894), stdev = 0.114
  CI (99.9%): [8.701, 12.868] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.448 ops/ms
# Warmup Iteration   2: 9.971 ops/ms
# Warmup Iteration   3: 10.435 ops/ms
Iteration   1: 10.286 ops/ms
Iteration   2: 10.246 ops/ms
Iteration   3: 10.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.309 ±(99.9%) 1.421 ops/ms [Average]
  (min, avg, max) = (10.246, 10.309, 10.396), stdev = 0.078
  CI (99.9%): [8.888, 11.731] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.247 ops/ms
# Warmup Iteration   2: 7.568 ops/ms
# Warmup Iteration   3: 8.017 ops/ms
Iteration   1: 8.098 ops/ms
Iteration   2: 7.833 ops/ms
Iteration   3: 7.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.931 ±(99.9%) 2.647 ops/ms [Average]
  (min, avg, max) = (7.833, 7.931, 8.098), stdev = 0.145
  CI (99.9%): [5.284, 10.579] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.976 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.003 ms/op
Iteration   1: 3.030 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
Iteration   3: 3.079 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.045 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (3.025, 3.045, 3.079), stdev = 0.030
  CI (99.9%): [2.496, 3.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.795 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.972 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.002 ms/op
Iteration   1: 2.989 ±(99.9%) 0.002 ms/op
Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
Iteration   3: 3.036 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.996 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (2.963, 2.996, 3.036), stdev = 0.037
  CI (99.9%): [2.321, 3.671] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.003 ms/op
Iteration   1: 3.040 ±(99.9%) 0.002 ms/op
Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
Iteration   3: 3.069 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.082 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (3.040, 3.082, 3.138), stdev = 0.050
  CI (99.9%): [2.161, 4.003] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.161 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.014 ms/op
Iteration   1: 4.005 ±(99.9%) 0.014 ms/op
Iteration   2: 4.006 ±(99.9%) 0.015 ms/op
Iteration   3: 3.902 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.971 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (3.902, 3.971, 4.006), stdev = 0.060
  CI (99.9%): [2.884, 5.059] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.155 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.008 ms/op
Iteration   1: 3.126 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  10.273 ms/op
                 createUser·p0.9999: 12.575 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  7.381 ms/op
                 createUser·p0.9999: 14.205 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   3: 3.083 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.368 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  10.321 ms/op
                 createUser·p0.9999: 24.222 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309301
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28655 
    [ 2.500,  5.000) = 278977 
    [ 5.000,  7.500) = 1168 
    [ 7.500, 10.000) = 183 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =     10.120 ms/op
     p(99.9900) =     22.778 ms/op
     p(99.9990) =     24.570 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.801 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.470 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  8.419 ms/op
                 existUser·p0.9999: 12.622 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   2: 2.993 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.987 ms/op
                 existUser·p0.9999: 22.696 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  7.629 ms/op
                 existUser·p0.9999: 17.683 ms/op
                 existUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322253
  mean =      2.977 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43245 
    [ 2.500,  5.000) = 277858 
    [ 5.000,  7.500) = 733 
    [ 7.500, 10.000) = 187 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.987 ms/op
     p(99.9900) =     21.291 ms/op
     p(99.9990) =     23.054 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
Iteration   1: 3.041 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.736 ms/op
                 getUser·p0.999:  7.813 ms/op
                 getUser·p0.9999: 17.153 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.634 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  8.395 ms/op
                 getUser·p0.9999: 16.446 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.377 ms/op
                 getUser·p0.9999: 19.081 ms/op
                 getUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311122
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2073 
    [ 1.250,  2.500) = 24054 
    [ 2.500,  3.750) = 258141 
    [ 3.750,  5.000) = 25411 
    [ 5.000,  6.250) = 871 
    [ 6.250,  7.500) = 243 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 75 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.690 ms/op
     p(99.9900) =     18.375 ms/op
     p(99.9990) =     19.461 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.330 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.011 ms/op
Iteration   1: 4.060 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.264 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  11.702 ms/op
                 listUser·p0.9999: 15.122 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   2: 4.151 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  14.319 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 4.028 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.640 ms/op
                 listUser·p0.9999: 18.006 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235169
  mean =      4.079 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 3180 
    [ 2.500,  3.750) = 99216 
    [ 3.750,  5.000) = 93041 
    [ 5.000,  6.250) = 33262 
    [ 6.250,  7.500) = 4955 
    [ 7.500,  8.750) = 918 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 103 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 76 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.264 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     14.251 ms/op
     p(99.9900) =     17.300 ms/op
     p(99.9990) =     19.572 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.127 ± 2.187  ops/ms
ClientGrpc.existUser                       thrpt       3  10.784 ± 2.084  ops/ms
ClientGrpc.getUser                         thrpt       3  10.309 ± 1.421  ops/ms
ClientGrpc.listUser                        thrpt       3   7.931 ± 2.647  ops/ms
ClientGrpc.createUser                       avgt       3   3.045 ± 0.549   ms/op
ClientGrpc.existUser                        avgt       3   2.996 ± 0.675   ms/op
ClientGrpc.getUser                          avgt       3   3.082 ± 0.921   ms/op
ClientGrpc.listUser                         avgt       3   3.971 ± 1.088   ms/op
ClientGrpc.createUser                     sample  309301   3.106 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.368           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.981           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.120           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.778           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.707           ms/op
ClientGrpc.existUser                      sample  322253   2.977 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.470           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.987           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.291           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.167           ms/op
ClientGrpc.getUser                        sample  311122   3.085 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.634           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.690           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.375           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.530           ms/op
ClientGrpc.listUser                       sample  235169   4.079 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.264           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.251           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.300           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.825           ms/op
