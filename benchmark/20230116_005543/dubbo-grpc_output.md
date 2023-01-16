# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.020 ops/ms
# Warmup Iteration   2: 9.815 ops/ms
# Warmup Iteration   3: 10.424 ops/ms
Iteration   1: 10.154 ops/ms
Iteration   2: 10.453 ops/ms
Iteration   3: 10.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.222 ±(99.9%) 3.757 ops/ms [Average]
  (min, avg, max) = (10.058, 10.222, 10.453), stdev = 0.206
  CI (99.9%): [6.465, 13.979] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.830 ops/ms
# Warmup Iteration   2: 10.708 ops/ms
# Warmup Iteration   3: 10.925 ops/ms
Iteration   1: 10.832 ops/ms
Iteration   2: 10.850 ops/ms
Iteration   3: 10.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.869 ±(99.9%) 0.896 ops/ms [Average]
  (min, avg, max) = (10.832, 10.869, 10.925), stdev = 0.049
  CI (99.9%): [9.972, 11.765] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.172 ops/ms
# Warmup Iteration   2: 10.262 ops/ms
# Warmup Iteration   3: 10.331 ops/ms
Iteration   1: 10.404 ops/ms
Iteration   2: 10.697 ops/ms
Iteration   3: 10.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.505 ±(99.9%) 3.041 ops/ms [Average]
  (min, avg, max) = (10.404, 10.505, 10.697), stdev = 0.167
  CI (99.9%): [7.464, 13.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.489 ops/ms
# Warmup Iteration   2: 7.492 ops/ms
# Warmup Iteration   3: 7.821 ops/ms
Iteration   1: 7.858 ops/ms
Iteration   2: 7.913 ops/ms
Iteration   3: 8.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.977 ±(99.9%) 2.934 ops/ms [Average]
  (min, avg, max) = (7.858, 7.977, 8.160), stdev = 0.161
  CI (99.9%): [5.043, 10.911] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.162 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.003 ms/op
Iteration   1: 3.046 ±(99.9%) 0.001 ms/op
Iteration   2: 3.092 ±(99.9%) 0.002 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.079 ±(99.9%) 0.529 ms/op [Average]
  (min, avg, max) = (3.046, 3.079, 3.100), stdev = 0.029
  CI (99.9%): [2.550, 3.608] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.772 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.003 ms/op
Iteration   1: 2.936 ±(99.9%) 0.004 ms/op
Iteration   2: 2.951 ±(99.9%) 0.002 ms/op
Iteration   3: 2.888 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.925 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (2.888, 2.925, 2.951), stdev = 0.033
  CI (99.9%): [2.324, 3.526] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.002 ms/op
Iteration   1: 3.064 ±(99.9%) 0.002 ms/op
Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
Iteration   3: 2.989 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.063 ±(99.9%) 1.325 ms/op [Average]
  (min, avg, max) = (2.989, 3.063, 3.135), stdev = 0.073
  CI (99.9%): [1.738, 4.388] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.951 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.317 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.025 ms/op
Iteration   1: 4.090 ±(99.9%) 0.018 ms/op
Iteration   2: 3.963 ±(99.9%) 0.018 ms/op
Iteration   3: 3.975 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.009 ±(99.9%) 1.275 ms/op [Average]
  (min, avg, max) = (3.963, 4.009, 4.090), stdev = 0.070
  CI (99.9%): [2.734, 5.285] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.979 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.712 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.423 ms/op
                 createUser·p0.9999: 15.066 ms/op
                 createUser·p1.00:   15.598 ms/op

Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  7.956 ms/op
                 createUser·p0.9999: 16.100 ms/op
                 createUser·p1.00:   16.761 ms/op

Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.370 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  7.610 ms/op
                 createUser·p0.9999: 17.322 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310889
  mean =      3.087 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 945 
    [ 1.250,  2.500) = 22949 
    [ 2.500,  3.750) = 262838 
    [ 3.750,  5.000) = 23079 
    [ 5.000,  6.250) = 578 
    [ 6.250,  7.500) = 163 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 83 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.692 ms/op
     p(99.9900) =     16.301 ms/op
     p(99.9990) =     17.527 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.770 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
Iteration   1: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  6.898 ms/op
                 existUser·p0.9999: 17.405 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   2: 2.957 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.646 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.059 ms/op
                 existUser·p0.999:  7.215 ms/op
                 existUser·p0.9999: 14.148 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.405 ms/op
                 existUser·p0.9999: 17.007 ms/op
                 existUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325535
  mean =      2.948 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2288 
    [ 1.250,  2.500) = 40604 
    [ 2.500,  3.750) = 266987 
    [ 3.750,  5.000) = 14761 
    [ 5.000,  6.250) = 439 
    [ 6.250,  7.500) = 209 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 55 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     17.021 ms/op
     p(99.9990) =     18.038 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.726 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.008 ms/op
Iteration   1: 3.077 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.454 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.554 ms/op
                 getUser·p0.9999: 11.177 ms/op
                 getUser·p1.00:   11.338 ms/op

Iteration   2: 3.143 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.601 ms/op
                 getUser·p0.9999: 13.609 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   3: 3.040 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  6.418 ms/op
                 getUser·p0.9999: 13.565 ms/op
                 getUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311001
  mean =      3.086 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1385 
    [ 1.250,  2.500) = 23703 
    [ 2.500,  3.750) = 257567 
    [ 3.750,  5.000) = 27552 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 169 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.521 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     15.456 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.206 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.010 ms/op
Iteration   1: 4.062 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  11.850 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   2: 3.980 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.021 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.445 ms/op
                 listUser·p0.9999: 17.298 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.971 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  14.442 ms/op
                 listUser·p0.9999: 25.556 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239653
  mean =      4.004 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5261 
    [ 2.500,  5.000) = 206837 
    [ 5.000,  7.500) = 26504 
    [ 7.500, 10.000) = 694 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     13.031 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     25.717 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.222 ± 3.757  ops/ms
ClientGrpc.existUser                       thrpt       3  10.869 ± 0.896  ops/ms
ClientGrpc.getUser                         thrpt       3  10.505 ± 3.041  ops/ms
ClientGrpc.listUser                        thrpt       3   7.977 ± 2.934  ops/ms
ClientGrpc.createUser                       avgt       3   3.079 ± 0.529   ms/op
ClientGrpc.existUser                        avgt       3   2.925 ± 0.601   ms/op
ClientGrpc.getUser                          avgt       3   3.063 ± 1.325   ms/op
ClientGrpc.listUser                         avgt       3   4.009 ± 1.275   ms/op
ClientGrpc.createUser                     sample  310889   3.087 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.370           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.692           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.301           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.760           ms/op
ClientGrpc.existUser                      sample  325535   2.948 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.637           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.102           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.021           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.088           ms/op
ClientGrpc.getUser                        sample  311001   3.086 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.454           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.521           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.435           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.548           ms/op
ClientGrpc.listUser                       sample  239653   4.004 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.779           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.031           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.938           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.756           ms/op
