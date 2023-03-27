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
# Warmup Iteration   1: 4.369 ops/ms
# Warmup Iteration   2: 8.480 ops/ms
# Warmup Iteration   3: 9.499 ops/ms
Iteration   1: 10.208 ops/ms
Iteration   2: 10.044 ops/ms
Iteration   3: 10.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.216 ±(99.9%) 3.204 ops/ms [Average]
  (min, avg, max) = (10.044, 10.216, 10.395), stdev = 0.176
  CI (99.9%): [7.012, 13.420] (assumes normal distribution)


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
# Warmup Iteration   1: 8.474 ops/ms
# Warmup Iteration   2: 10.310 ops/ms
# Warmup Iteration   3: 10.816 ops/ms
Iteration   1: 10.527 ops/ms
Iteration   2: 10.759 ops/ms
Iteration   3: 10.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.708 ±(99.9%) 2.953 ops/ms [Average]
  (min, avg, max) = (10.527, 10.708, 10.839), stdev = 0.162
  CI (99.9%): [7.755, 13.661] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.932 ops/ms
# Warmup Iteration   2: 9.952 ops/ms
# Warmup Iteration   3: 10.365 ops/ms
Iteration   1: 10.192 ops/ms
Iteration   2: 10.395 ops/ms
Iteration   3: 10.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.286 ±(99.9%) 1.862 ops/ms [Average]
  (min, avg, max) = (10.192, 10.286, 10.395), stdev = 0.102
  CI (99.9%): [8.424, 12.148] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.387 ops/ms
# Warmup Iteration   2: 7.724 ops/ms
# Warmup Iteration   3: 7.789 ops/ms
Iteration   1: 7.600 ops/ms
Iteration   2: 7.882 ops/ms
Iteration   3: 7.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.727 ±(99.9%) 2.602 ops/ms [Average]
  (min, avg, max) = (7.600, 7.727, 7.882), stdev = 0.143
  CI (99.9%): [5.126, 10.329] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.384 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.004 ms/op
Iteration   1: 3.184 ±(99.9%) 0.003 ms/op
Iteration   2: 3.185 ±(99.9%) 0.002 ms/op
Iteration   3: 3.267 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.212 ±(99.9%) 0.865 ms/op [Average]
  (min, avg, max) = (3.184, 3.212, 3.267), stdev = 0.047
  CI (99.9%): [2.347, 4.077] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.199 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.004 ms/op
Iteration   1: 2.924 ±(99.9%) 0.003 ms/op
Iteration   2: 2.913 ±(99.9%) 0.003 ms/op
Iteration   3: 3.086 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 1.763 ms/op [Average]
  (min, avg, max) = (2.913, 2.974, 3.086), stdev = 0.097
  CI (99.9%): [1.212, 4.737] (assumes normal distribution)


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
# Warmup Iteration   1: 4.346 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.005 ms/op
Iteration   1: 3.417 ±(99.9%) 0.003 ms/op
Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
Iteration   3: 3.238 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.243 ±(99.9%) 3.115 ms/op [Average]
  (min, avg, max) = (3.075, 3.243, 3.417), stdev = 0.171
  CI (99.9%): [0.129, 6.358] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.147 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.440 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.017 ms/op
Iteration   1: 4.230 ±(99.9%) 0.017 ms/op
Iteration   2: 4.090 ±(99.9%) 0.029 ms/op
Iteration   3: 4.127 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.149 ±(99.9%) 1.320 ms/op [Average]
  (min, avg, max) = (4.090, 4.149, 4.230), stdev = 0.072
  CI (99.9%): [2.829, 5.469] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.471 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.008 ms/op
Iteration   1: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.195 ms/op
                 createUser·p0.999:  7.985 ms/op
                 createUser·p0.9999: 13.124 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   2: 3.072 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  10.207 ms/op
                 createUser·p0.9999: 17.504 ms/op
                 createUser·p1.00:   18.022 ms/op

Iteration   3: 3.189 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.834 ms/op
                 createUser·p0.999:  8.314 ms/op
                 createUser·p0.9999: 20.446 ms/op
                 createUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305760
  mean =      3.138 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21218 
    [ 2.500,  5.000) = 279562 
    [ 5.000,  7.500) = 4415 
    [ 7.500, 10.000) = 323 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     19.380 ms/op
     p(99.9990) =     20.576 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.116 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.008 ms/op
Iteration   1: 3.072 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.513 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  9.272 ms/op
                 existUser·p0.9999: 17.747 ms/op
                 existUser·p1.00:   18.186 ms/op

Iteration   2: 3.029 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  11.253 ms/op
                 existUser·p0.9999: 15.441 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   3: 2.998 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  11.786 ms/op
                 existUser·p0.9999: 19.006 ms/op
                 existUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316443
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1121 
    [ 1.250,  2.500) = 29183 
    [ 2.500,  3.750) = 261815 
    [ 3.750,  5.000) = 19441 
    [ 5.000,  6.250) = 2949 
    [ 6.250,  7.500) = 1072 
    [ 7.500,  8.750) = 387 
    [ 8.750, 10.000) = 149 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     10.158 ms/op
     p(99.9900) =     18.493 ms/op
     p(99.9990) =     19.677 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.009 ms/op
Iteration   1: 3.229 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  11.303 ms/op
                 getUser·p0.9999: 18.225 ms/op
                 getUser·p1.00:   18.874 ms/op

Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.740 ms/op
                 getUser·p0.999:  10.373 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   3: 3.100 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  10.253 ms/op
                 getUser·p0.9999: 19.333 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302850
  mean =      3.169 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20811 
    [ 2.500,  5.000) = 276413 
    [ 5.000,  7.500) = 4586 
    [ 7.500, 10.000) = 688 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     10.666 ms/op
     p(99.9900) =     19.029 ms/op
     p(99.9990) =     24.158 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 5.615 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.168 ±(99.9%) 0.014 ms/op
Iteration   1: 4.168 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.300 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  15.558 ms/op
                 listUser·p0.9999: 18.426 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   2: 4.098 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.648 ms/op
                 listUser·p0.999:  16.829 ms/op
                 listUser·p0.9999: 23.121 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   3: 4.200 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.372 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.341 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  15.697 ms/op
                 listUser·p0.9999: 23.172 ms/op
                 listUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230923
  mean =      4.155 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2408 
    [ 2.500,  5.000) = 193836 
    [ 5.000,  7.500) = 31018 
    [ 7.500, 10.000) = 2773 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      6.210 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     22.869 ms/op
     p(99.9990) =     23.857 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.216 ± 3.204  ops/ms
ClientGrpc.existUser                       thrpt       3  10.708 ± 2.953  ops/ms
ClientGrpc.getUser                         thrpt       3  10.286 ± 1.862  ops/ms
ClientGrpc.listUser                        thrpt       3   7.727 ± 2.602  ops/ms
ClientGrpc.createUser                       avgt       3   3.212 ± 0.865   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 1.763   ms/op
ClientGrpc.getUser                          avgt       3   3.243 ± 3.115   ms/op
ClientGrpc.listUser                         avgt       3   4.149 ± 1.320   ms/op
ClientGrpc.createUser                     sample  305760   3.138 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.749           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.141           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.471           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.380           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.103           ms/op
ClientGrpc.existUser                      sample  316443   3.033 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.513           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.969           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.158           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.493           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.956           ms/op
ClientGrpc.getUser                        sample  302850   3.169 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.587           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.666           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.029           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.248           ms/op
ClientGrpc.listUser                       sample  230923   4.155 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.372           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.210           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.761           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.869           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.903           ms/op
