# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.639 ops/ms
# Warmup Iteration   2: 8.659 ops/ms
# Warmup Iteration   3: 9.843 ops/ms
Iteration   1: 9.978 ops/ms
Iteration   2: 10.081 ops/ms
Iteration   3: 10.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.042 ±(99.9%) 1.024 ops/ms [Average]
  (min, avg, max) = (9.978, 10.042, 10.081), stdev = 0.056
  CI (99.9%): [9.018, 11.066] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.500 ops/ms
# Warmup Iteration   2: 10.426 ops/ms
# Warmup Iteration   3: 10.885 ops/ms
Iteration   1: 10.803 ops/ms
Iteration   2: 10.844 ops/ms
Iteration   3: 11.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.913 ±(99.9%) 2.851 ops/ms [Average]
  (min, avg, max) = (10.803, 10.913, 11.092), stdev = 0.156
  CI (99.9%): [8.062, 13.764] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.722 ops/ms
# Warmup Iteration   2: 9.976 ops/ms
# Warmup Iteration   3: 10.089 ops/ms
Iteration   1: 10.415 ops/ms
Iteration   2: 10.533 ops/ms
Iteration   3: 10.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.399 ±(99.9%) 2.617 ops/ms [Average]
  (min, avg, max) = (10.248, 10.399, 10.533), stdev = 0.143
  CI (99.9%): [7.781, 13.016] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.626 ops/ms
# Warmup Iteration   2: 7.959 ops/ms
# Warmup Iteration   3: 8.203 ops/ms
Iteration   1: 8.511 ops/ms
Iteration   2: 8.352 ops/ms
Iteration   3: 8.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.400 ±(99.9%) 1.752 ops/ms [Average]
  (min, avg, max) = (8.338, 8.400, 8.511), stdev = 0.096
  CI (99.9%): [6.648, 10.152] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.077 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.001 ms/op
Iteration   1: 3.085 ±(99.9%) 0.002 ms/op
Iteration   2: 3.108 ±(99.9%) 0.001 ms/op
Iteration   3: 3.040 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.078 ±(99.9%) 0.636 ms/op [Average]
  (min, avg, max) = (3.040, 3.078, 3.108), stdev = 0.035
  CI (99.9%): [2.442, 3.714] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.897 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.002 ms/op
Iteration   1: 2.951 ±(99.9%) 0.002 ms/op
Iteration   2: 2.853 ±(99.9%) 0.002 ms/op
Iteration   3: 2.995 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.933 ±(99.9%) 1.331 ms/op [Average]
  (min, avg, max) = (2.853, 2.933, 2.995), stdev = 0.073
  CI (99.9%): [1.602, 4.264] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.119 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.002 ms/op
Iteration   1: 3.106 ±(99.9%) 0.002 ms/op
Iteration   2: 3.104 ±(99.9%) 0.002 ms/op
Iteration   3: 3.130 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.114 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (3.104, 3.114, 3.130), stdev = 0.014
  CI (99.9%): [2.853, 3.375] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.226 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.021 ms/op
Iteration   1: 3.899 ±(99.9%) 0.055 ms/op
Iteration   2: 3.843 ±(99.9%) 0.030 ms/op
Iteration   3: 3.904 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.882 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (3.843, 3.882, 3.904), stdev = 0.034
  CI (99.9%): [3.258, 4.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.152 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.007 ms/op
Iteration   1: 3.163 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.290 ms/op
                 createUser·p0.9999: 14.678 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   2: 3.182 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  10.617 ms/op
                 createUser·p0.9999: 16.432 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   3: 3.181 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  9.953 ms/op
                 createUser·p0.9999: 17.302 ms/op
                 createUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302177
  mean =      3.176 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 521 
    [ 1.250,  2.500) = 6305 
    [ 2.500,  3.750) = 265483 
    [ 3.750,  5.000) = 28315 
    [ 5.000,  6.250) = 793 
    [ 6.250,  7.500) = 290 
    [ 7.500,  8.750) = 97 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     16.668 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.005 ms/op
Iteration   1: 2.982 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   3.940 ms/op
                 existUser·p0.999:  6.830 ms/op
                 existUser·p0.9999: 10.970 ms/op
                 existUser·p1.00:   11.272 ms/op

Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  10.843 ms/op
                 existUser·p0.9999: 12.698 ms/op
                 existUser·p1.00:   12.845 ms/op

Iteration   3: 2.956 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.319 ms/op
                 existUser·p0.999:  9.117 ms/op
                 existUser·p0.9999: 15.548 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321693
  mean =      2.984 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1159 
    [ 1.250,  2.500) = 22295 
    [ 2.500,  3.750) = 287323 
    [ 3.750,  5.000) = 9759 
    [ 5.000,  6.250) = 524 
    [ 6.250,  7.500) = 242 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      9.567 ms/op
     p(99.9900) =     15.071 ms/op
     p(99.9990) =     15.630 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.708 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
Iteration   1: 3.086 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.418 ms/op
                 getUser·p0.9999: 11.417 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  8.047 ms/op
                 getUser·p0.9999: 21.192 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   3: 3.129 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  7.031 ms/op
                 getUser·p0.9999: 14.057 ms/op
                 getUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308933
  mean =      3.108 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8647 
    [ 2.500,  5.000) = 299147 
    [ 5.000,  7.500) = 862 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.988 ms/op
     p(99.9900) =     20.553 ms/op
     p(99.9990) =     21.395 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.367 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.008 ms/op
Iteration   1: 3.913 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  12.321 ms/op
                 listUser·p0.9999: 14.664 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 3.812 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.436 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 16.791 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   3: 3.867 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  12.126 ms/op
                 listUser·p0.9999: 16.964 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248500
  mean =      3.864 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2953 
    [ 2.500,  3.750) = 112089 
    [ 3.750,  5.000) = 120319 
    [ 5.000,  6.250) = 8721 
    [ 6.250,  7.500) = 3470 
    [ 7.500,  8.750) = 311 
    [ 8.750, 10.000) = 152 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 155 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     16.747 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.042 ± 1.024  ops/ms
ClientGrpc.existUser                       thrpt       3  10.913 ± 2.851  ops/ms
ClientGrpc.getUser                         thrpt       3  10.399 ± 2.617  ops/ms
ClientGrpc.listUser                        thrpt       3   8.400 ± 1.752  ops/ms
ClientGrpc.createUser                       avgt       3   3.078 ± 0.636   ms/op
ClientGrpc.existUser                        avgt       3   2.933 ± 1.331   ms/op
ClientGrpc.getUser                          avgt       3   3.114 ± 0.261   ms/op
ClientGrpc.listUser                         avgt       3   3.882 ± 0.624   ms/op
ClientGrpc.createUser                     sample  302177   3.176 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.700           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.568           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.668           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.416           ms/op
ClientGrpc.existUser                      sample  321693   2.984 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.651           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.567           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.071           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.679           ms/op
ClientGrpc.getUser                        sample  308933   3.108 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.604           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.988           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.553           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.463           ms/op
ClientGrpc.listUser                       sample  248500   3.864 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.176           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.334           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.545           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.632           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.747           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          17.760           ms/op
