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
# Warmup Iteration   1: 4.507 ops/ms
# Warmup Iteration   2: 9.209 ops/ms
# Warmup Iteration   3: 10.246 ops/ms
Iteration   1: 10.481 ops/ms
Iteration   2: 10.764 ops/ms
Iteration   3: 10.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.612 ±(99.9%) 2.604 ops/ms [Average]
  (min, avg, max) = (10.481, 10.612, 10.764), stdev = 0.143
  CI (99.9%): [8.008, 13.216] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.322 ops/ms
# Warmup Iteration   2: 10.551 ops/ms
# Warmup Iteration   3: 11.140 ops/ms
Iteration   1: 10.991 ops/ms
Iteration   2: 11.100 ops/ms
Iteration   3: 11.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.071 ±(99.9%) 1.271 ops/ms [Average]
  (min, avg, max) = (10.991, 11.071, 11.121), stdev = 0.070
  CI (99.9%): [9.799, 12.342] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.435 ops/ms
# Warmup Iteration   2: 10.242 ops/ms
# Warmup Iteration   3: 10.702 ops/ms
Iteration   1: 10.561 ops/ms
Iteration   2: 10.741 ops/ms
Iteration   3: 10.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.666 ±(99.9%) 1.700 ops/ms [Average]
  (min, avg, max) = (10.561, 10.666, 10.741), stdev = 0.093
  CI (99.9%): [8.966, 12.365] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.188 ops/ms
# Warmup Iteration   2: 8.024 ops/ms
# Warmup Iteration   3: 8.367 ops/ms
Iteration   1: 8.239 ops/ms
Iteration   2: 8.318 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.252 ±(99.9%) 1.094 ops/ms [Average]
  (min, avg, max) = (8.200, 8.252, 8.318), stdev = 0.060
  CI (99.9%): [7.158, 9.347] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.364 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.002 ms/op
Iteration   1: 3.039 ±(99.9%) 0.002 ms/op
Iteration   2: 2.992 ±(99.9%) 0.002 ms/op
Iteration   3: 2.969 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.000 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (2.969, 3.000, 3.039), stdev = 0.036
  CI (99.9%): [2.350, 3.650] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.841 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.939 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.770 ±(99.9%) 0.003 ms/op
Iteration   1: 2.872 ±(99.9%) 0.003 ms/op
Iteration   2: 2.818 ±(99.9%) 0.002 ms/op
Iteration   3: 2.836 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.842 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (2.818, 2.842, 2.872), stdev = 0.028
  CI (99.9%): [2.340, 3.345] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.139 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.003 ms/op
Iteration   2: 3.007 ±(99.9%) 0.003 ms/op
Iteration   3: 3.076 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.015 ±(99.9%) 1.053 ms/op [Average]
  (min, avg, max) = (2.961, 3.015, 3.076), stdev = 0.058
  CI (99.9%): [1.962, 4.067] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.252 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.017 ms/op
Iteration   1: 3.837 ±(99.9%) 0.033 ms/op
Iteration   2: 3.853 ±(99.9%) 0.023 ms/op
Iteration   3: 3.851 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.847 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (3.837, 3.847, 3.853), stdev = 0.008
  CI (99.9%): [3.694, 3.999] (assumes normal distribution)


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.007 ms/op
Iteration   1: 3.006 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.290 ms/op
                 createUser·p0.9999: 12.993 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.137 ms/op
                 createUser·p0.999:  7.790 ms/op
                 createUser·p0.9999: 17.053 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  10.486 ms/op
                 createUser·p0.9999: 16.187 ms/op
                 createUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316351
  mean =      3.034 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1308 
    [ 1.250,  2.500) = 24158 
    [ 2.500,  3.750) = 271899 
    [ 3.750,  5.000) = 17778 
    [ 5.000,  6.250) = 510 
    [ 6.250,  7.500) = 248 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 83 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      9.961 ms/op
     p(99.9900) =     16.734 ms/op
     p(99.9990) =     17.417 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 3.946 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.005 ms/op
Iteration   1: 2.939 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.320 ms/op
                 existUser·p0.9999: 19.566 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   2: 2.919 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.580 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.105 ms/op
                 existUser·p0.999:  6.967 ms/op
                 existUser·p0.9999: 14.993 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   3: 2.854 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.178 ms/op
                 existUser·p0.95:   3.260 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  6.431 ms/op
                 existUser·p0.9999: 16.967 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330542
  mean =      2.903 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 852 
    [ 1.250,  2.500) = 31321 
    [ 2.500,  3.750) = 290978 
    [ 3.750,  5.000) = 6443 
    [ 5.000,  6.250) = 412 
    [ 6.250,  7.500) = 292 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      6.893 ms/op
     p(99.9900) =     17.331 ms/op
     p(99.9990) =     19.815 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.005 ms/op
Iteration   1: 3.051 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.480 ms/op
                 getUser·p0.999:  10.243 ms/op
                 getUser·p0.9999: 13.075 ms/op
                 getUser·p1.00:   13.337 ms/op

Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.391 ms/op
                 getUser·p0.9999: 13.416 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   3: 3.035 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  6.895 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318027
  mean =      3.016 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23516 
    [ 2.500,  5.000) = 292883 
    [ 5.000,  7.500) = 1364 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      6.946 ms/op
     p(99.9900) =     23.993 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 4.993 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.208 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.011 ms/op
Iteration   1: 3.865 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 16.506 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   2: 3.801 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 18.402 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 3.991 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  19.231 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247180
  mean =      3.884 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2794 
    [ 2.500,  5.000) = 223110 
    [ 5.000,  7.500) = 20109 
    [ 7.500, 10.000) = 721 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     21.776 ms/op
     p(99.9990) =     22.353 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.612 ± 2.604  ops/ms
ClientGrpc.existUser                       thrpt       3  11.071 ± 1.271  ops/ms
ClientGrpc.getUser                         thrpt       3  10.666 ± 1.700  ops/ms
ClientGrpc.listUser                        thrpt       3   8.252 ± 1.094  ops/ms
ClientGrpc.createUser                       avgt       3   3.000 ± 0.650   ms/op
ClientGrpc.existUser                        avgt       3   2.842 ± 0.502   ms/op
ClientGrpc.getUser                          avgt       3   3.015 ± 1.053   ms/op
ClientGrpc.listUser                         avgt       3   3.847 ± 0.152   ms/op
ClientGrpc.createUser                     sample  316351   3.034 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.663           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.961           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.734           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.399           ms/op
ClientGrpc.existUser                      sample  330542   2.903 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.580           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.297           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.893           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.331           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.857           ms/op
ClientGrpc.getUser                        sample  318027   3.016 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.870           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.946           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.993           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.149           ms/op
ClientGrpc.listUser                       sample  247180   3.884 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.010           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.795           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.776           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.527           ms/op
