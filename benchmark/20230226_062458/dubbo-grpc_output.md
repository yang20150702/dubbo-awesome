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
# Warmup Iteration   1: 4.620 ops/ms
# Warmup Iteration   2: 9.000 ops/ms
# Warmup Iteration   3: 9.870 ops/ms
Iteration   1: 10.260 ops/ms
Iteration   2: 10.230 ops/ms
Iteration   3: 10.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.320 ±(99.9%) 2.379 ops/ms [Average]
  (min, avg, max) = (10.230, 10.320, 10.470), stdev = 0.130
  CI (99.9%): [7.941, 12.699] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.193 ops/ms
# Warmup Iteration   2: 10.047 ops/ms
# Warmup Iteration   3: 10.602 ops/ms
Iteration   1: 10.699 ops/ms
Iteration   2: 10.638 ops/ms
Iteration   3: 10.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.616 ±(99.9%) 1.742 ops/ms [Average]
  (min, avg, max) = (10.512, 10.616, 10.699), stdev = 0.095
  CI (99.9%): [8.874, 12.359] (assumes normal distribution)


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
# Warmup Iteration   1: 6.666 ops/ms
# Warmup Iteration   2: 10.148 ops/ms
# Warmup Iteration   3: 10.246 ops/ms
Iteration   1: 10.037 ops/ms
Iteration   2: 10.262 ops/ms
Iteration   3: 10.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.168 ±(99.9%) 2.131 ops/ms [Average]
  (min, avg, max) = (10.037, 10.168, 10.262), stdev = 0.117
  CI (99.9%): [8.036, 12.299] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.092 ops/ms
# Warmup Iteration   2: 7.595 ops/ms
# Warmup Iteration   3: 7.694 ops/ms
Iteration   1: 7.855 ops/ms
Iteration   2: 7.914 ops/ms
Iteration   3: 7.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.841 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (7.755, 7.841, 7.914), stdev = 0.080
  CI (99.9%): [6.381, 9.302] (assumes normal distribution)


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.008 ms/op
Iteration   1: 3.274 ±(99.9%) 0.001 ms/op
Iteration   2: 3.165 ±(99.9%) 0.002 ms/op
Iteration   3: 3.142 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.194 ±(99.9%) 1.287 ms/op [Average]
  (min, avg, max) = (3.142, 3.194, 3.274), stdev = 0.071
  CI (99.9%): [1.907, 4.481] (assumes normal distribution)


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
# Warmup Iteration   1: 4.202 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.004 ms/op
Iteration   1: 3.089 ±(99.9%) 0.001 ms/op
Iteration   2: 3.038 ±(99.9%) 0.002 ms/op
Iteration   3: 3.082 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.069 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (3.038, 3.069, 3.089), stdev = 0.028
  CI (99.9%): [2.564, 3.574] (assumes normal distribution)


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
# Warmup Iteration   1: 4.368 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.005 ms/op
Iteration   1: 3.130 ±(99.9%) 0.002 ms/op
Iteration   2: 3.211 ±(99.9%) 0.003 ms/op
Iteration   3: 3.132 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.158 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (3.130, 3.158, 3.211), stdev = 0.046
  CI (99.9%): [2.313, 4.002] (assumes normal distribution)


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
# Warmup Iteration   1: 4.623 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.019 ms/op
Iteration   1: 4.059 ±(99.9%) 0.019 ms/op
Iteration   2: 4.041 ±(99.9%) 0.008 ms/op
Iteration   3: 4.041 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.047 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (4.041, 4.047, 4.059), stdev = 0.010
  CI (99.9%): [3.864, 4.230] (assumes normal distribution)


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.007 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.032 ms/op
                 createUser·p0.9999: 12.952 ms/op
                 createUser·p1.00:   13.287 ms/op

Iteration   2: 3.147 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.288 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.438 ms/op
                 createUser·p0.9999: 16.037 ms/op
                 createUser·p1.00:   16.548 ms/op

Iteration   3: 3.172 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  10.155 ms/op
                 createUser·p0.9999: 19.757 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304910
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22049 
    [ 2.500,  5.000) = 281784 
    [ 5.000,  7.500) = 710 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.288 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.046 ms/op
     p(99.9900) =     17.372 ms/op
     p(99.9990) =     19.987 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.006 ms/op
Iteration   1: 3.012 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.225 ms/op
                 existUser·p0.9999: 11.258 ms/op
                 existUser·p1.00:   12.616 ms/op

Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  8.135 ms/op
                 existUser·p0.9999: 21.697 ms/op
                 existUser·p1.00:   22.512 ms/op

Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.429 ms/op
                 existUser·p0.9999: 16.347 ms/op
                 existUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313544
  mean =      3.061 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37091 
    [ 2.500,  5.000) = 275314 
    [ 5.000,  7.500) = 800 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.606 ms/op
     p(99.9900) =     20.806 ms/op
     p(99.9990) =     22.372 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.007 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  7.053 ms/op
                 getUser·p0.9999: 14.641 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.118 ms/op
                 getUser·p0.9999: 14.860 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   3: 3.171 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.594 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  10.210 ms/op
                 getUser·p0.9999: 18.082 ms/op
                 getUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305571
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 560 
    [ 1.250,  2.500) = 26289 
    [ 2.500,  3.750) = 240637 
    [ 3.750,  5.000) = 36484 
    [ 5.000,  6.250) = 926 
    [ 6.250,  7.500) = 276 
    [ 7.500,  8.750) = 116 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.208 ms/op
     p(99.9900) =     16.956 ms/op
     p(99.9990) =     18.412 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 5.143 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.011 ms/op
Iteration   1: 4.053 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 19.806 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   2: 4.088 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.314 ms/op
                 listUser·p0.9999: 25.625 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   3: 4.080 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.220 ms/op
                 listUser·p0.999:  16.001 ms/op
                 listUser·p0.9999: 19.092 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235643
  mean =      4.074 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2202 
    [ 2.500,  5.000) = 206292 
    [ 5.000,  7.500) = 25799 
    [ 7.500, 10.000) = 803 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     15.124 ms/op
     p(99.9900) =     23.443 ms/op
     p(99.9990) =     26.168 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.320 ± 2.379  ops/ms
ClientGrpc.existUser                       thrpt       3  10.616 ± 1.742  ops/ms
ClientGrpc.getUser                         thrpt       3  10.168 ± 2.131  ops/ms
ClientGrpc.listUser                        thrpt       3   7.841 ± 1.461  ops/ms
ClientGrpc.createUser                       avgt       3   3.194 ± 1.287   ms/op
ClientGrpc.existUser                        avgt       3   3.069 ± 0.505   ms/op
ClientGrpc.getUser                          avgt       3   3.158 ± 0.844   ms/op
ClientGrpc.listUser                         avgt       3   4.047 ± 0.183   ms/op
ClientGrpc.createUser                     sample  304910   3.148 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.288           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.998           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.046           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.372           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.087           ms/op
ClientGrpc.existUser                      sample  313544   3.061 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.720           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.957           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.606           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.806           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.512           ms/op
ClientGrpc.getUser                        sample  305571   3.140 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.590           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.035           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.208           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.956           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.678           ms/op
ClientGrpc.listUser                       sample  235643   4.074 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.921           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.124           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.443           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.214           ms/op
