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
# Warmup Iteration   1: 4.061 ops/ms
# Warmup Iteration   2: 8.784 ops/ms
# Warmup Iteration   3: 9.731 ops/ms
Iteration   1: 9.896 ops/ms
Iteration   2: 9.718 ops/ms
Iteration   3: 10.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.875 ±(99.9%) 2.699 ops/ms [Average]
  (min, avg, max) = (9.718, 9.875, 10.011), stdev = 0.148
  CI (99.9%): [7.176, 12.574] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.784 ops/ms
# Warmup Iteration   2: 9.845 ops/ms
# Warmup Iteration   3: 10.169 ops/ms
Iteration   1: 10.498 ops/ms
Iteration   2: 10.283 ops/ms
Iteration   3: 10.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.393 ±(99.9%) 1.961 ops/ms [Average]
  (min, avg, max) = (10.283, 10.393, 10.498), stdev = 0.107
  CI (99.9%): [8.432, 12.353] (assumes normal distribution)


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
# Warmup Iteration   1: 6.410 ops/ms
# Warmup Iteration   2: 9.782 ops/ms
# Warmup Iteration   3: 9.820 ops/ms
Iteration   1: 9.956 ops/ms
Iteration   2: 10.019 ops/ms
Iteration   3: 9.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.964 ±(99.9%) 0.948 ops/ms [Average]
  (min, avg, max) = (9.916, 9.964, 10.019), stdev = 0.052
  CI (99.9%): [9.015, 10.912] (assumes normal distribution)


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
# Warmup Iteration   1: 5.271 ops/ms
# Warmup Iteration   2: 7.448 ops/ms
# Warmup Iteration   3: 7.636 ops/ms
Iteration   1: 7.707 ops/ms
Iteration   2: 7.531 ops/ms
Iteration   3: 7.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.648 ±(99.9%) 1.846 ops/ms [Average]
  (min, avg, max) = (7.531, 7.648, 7.707), stdev = 0.101
  CI (99.9%): [5.802, 9.494] (assumes normal distribution)


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
# Warmup Iteration   1: 4.597 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.002 ms/op
Iteration   1: 3.255 ±(99.9%) 0.002 ms/op
Iteration   2: 3.300 ±(99.9%) 0.001 ms/op
Iteration   3: 3.187 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.247 ±(99.9%) 1.033 ms/op [Average]
  (min, avg, max) = (3.187, 3.247, 3.300), stdev = 0.057
  CI (99.9%): [2.215, 4.280] (assumes normal distribution)


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.002 ms/op
Iteration   1: 3.110 ±(99.9%) 0.003 ms/op
Iteration   2: 3.159 ±(99.9%) 0.002 ms/op
Iteration   3: 3.131 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.133 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (3.110, 3.133, 3.159), stdev = 0.025
  CI (99.9%): [2.677, 3.590] (assumes normal distribution)


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.002 ms/op
Iteration   1: 3.310 ±(99.9%) 0.003 ms/op
Iteration   2: 3.362 ±(99.9%) 0.001 ms/op
Iteration   3: 3.328 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.333 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (3.310, 3.333, 3.362), stdev = 0.027
  CI (99.9%): [2.846, 3.821] (assumes normal distribution)


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
# Warmup Iteration   1: 5.756 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.009 ms/op
Iteration   1: 4.125 ±(99.9%) 0.013 ms/op
Iteration   2: 4.125 ±(99.9%) 0.011 ms/op
Iteration   3: 4.112 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.121 ±(99.9%) 0.135 ms/op [Average]
  (min, avg, max) = (4.112, 4.121, 4.125), stdev = 0.007
  CI (99.9%): [3.985, 4.256] (assumes normal distribution)


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.300 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
Iteration   1: 3.252 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  10.707 ms/op
                 createUser·p0.9999: 19.169 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   2: 3.233 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.055 ms/op
                 createUser·p0.9999: 18.288 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   3: 3.253 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  6.447 ms/op
                 createUser·p0.9999: 19.724 ms/op
                 createUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 295889
  mean =      3.246 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18033 
    [ 2.500,  5.000) = 276784 
    [ 5.000,  7.500) = 769 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.569 ms/op
     p(99.9900) =     19.248 ms/op
     p(99.9990) =     22.125 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
Iteration   1: 3.184 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.001 ms/op
                 existUser·p0.9999: 15.463 ms/op
                 existUser·p1.00:   16.089 ms/op

Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.246 ms/op
                 existUser·p0.999:  6.913 ms/op
                 existUser·p0.9999: 14.893 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   3: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  5.630 ms/op
                 existUser·p0.9999: 25.428 ms/op
                 existUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 307293
  mean =      3.126 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26860 
    [ 2.500,  5.000) = 279658 
    [ 5.000,  7.500) = 638 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.207 ms/op
     p(99.9900) =     24.808 ms/op
     p(99.9990) =     25.819 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.007 ms/op
Iteration   1: 3.199 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.596 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   2: 3.211 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  6.540 ms/op
                 getUser·p0.9999: 15.960 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   3: 3.245 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.881 ms/op
                 getUser·p0.9999: 18.940 ms/op
                 getUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298111
  mean =      3.218 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16384 
    [ 2.500,  5.000) = 280783 
    [ 5.000,  7.500) = 727 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      6.789 ms/op
     p(99.9900) =     19.509 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 5.729 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.295 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.013 ms/op
Iteration   1: 4.083 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  20.218 ms/op
                 listUser·p0.9999: 25.040 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 4.062 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 30.649 ms/op
                 listUser·p1.00:   31.097 ms/op

Iteration   3: 4.138 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.025 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.219 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.080 ms/op
                 listUser·p0.999:  15.548 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234473
  mean =      4.094 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1951 
    [ 2.500,  5.000) = 205493 
    [ 5.000,  7.500) = 25545 
    [ 7.500, 10.000) = 1036 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     18.498 ms/op
     p(99.9900) =     30.179 ms/op
     p(99.9990) =     31.008 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.875 ± 2.699  ops/ms
ClientGrpc.existUser                       thrpt       3  10.393 ± 1.961  ops/ms
ClientGrpc.getUser                         thrpt       3   9.964 ± 0.948  ops/ms
ClientGrpc.listUser                        thrpt       3   7.648 ± 1.846  ops/ms
ClientGrpc.createUser                       avgt       3   3.247 ± 1.033   ms/op
ClientGrpc.existUser                        avgt       3   3.133 ± 0.457   ms/op
ClientGrpc.getUser                          avgt       3   3.333 ± 0.488   ms/op
ClientGrpc.listUser                         avgt       3   4.121 ± 0.135   ms/op
ClientGrpc.createUser                     sample  295889   3.246 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.841           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.224           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.166           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.569           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.248           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.905           ms/op
ClientGrpc.existUser                      sample  307293   3.126 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.820           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.097           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.985           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.207           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.808           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.214           ms/op
ClientGrpc.getUser                        sample  298111   3.218 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.750           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.191           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.092           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.789           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.509           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  234473   4.094 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.025           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.498           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.179           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.097           ms/op
