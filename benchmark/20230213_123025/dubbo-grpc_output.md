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
# Warmup Iteration   1: 4.877 ops/ms
# Warmup Iteration   2: 9.274 ops/ms
# Warmup Iteration   3: 10.364 ops/ms
Iteration   1: 10.349 ops/ms
Iteration   2: 10.756 ops/ms
Iteration   3: 10.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.470 ±(99.9%) 4.548 ops/ms [Average]
  (min, avg, max) = (10.304, 10.470, 10.756), stdev = 0.249
  CI (99.9%): [5.922, 15.018] (assumes normal distribution)


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
# Warmup Iteration   1: 8.046 ops/ms
# Warmup Iteration   2: 10.699 ops/ms
# Warmup Iteration   3: 10.804 ops/ms
Iteration   1: 11.038 ops/ms
Iteration   2: 10.879 ops/ms
Iteration   3: 11.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.997 ±(99.9%) 1.906 ops/ms [Average]
  (min, avg, max) = (10.879, 10.997, 11.075), stdev = 0.104
  CI (99.9%): [9.092, 12.903] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.764 ops/ms
# Warmup Iteration   2: 10.498 ops/ms
# Warmup Iteration   3: 10.064 ops/ms
Iteration   1: 10.610 ops/ms
Iteration   2: 10.464 ops/ms
Iteration   3: 10.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.602 ±(99.9%) 2.457 ops/ms [Average]
  (min, avg, max) = (10.464, 10.602, 10.733), stdev = 0.135
  CI (99.9%): [8.145, 13.059] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.016 ops/ms
# Warmup Iteration   2: 7.952 ops/ms
# Warmup Iteration   3: 7.918 ops/ms
Iteration   1: 8.183 ops/ms
Iteration   2: 8.305 ops/ms
Iteration   3: 8.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.245 ±(99.9%) 1.119 ops/ms [Average]
  (min, avg, max) = (8.183, 8.245, 8.305), stdev = 0.061
  CI (99.9%): [7.126, 9.363] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.033 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.004 ms/op
Iteration   1: 2.977 ±(99.9%) 0.003 ms/op
Iteration   2: 3.119 ±(99.9%) 0.001 ms/op
Iteration   3: 3.119 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.072 ±(99.9%) 1.490 ms/op [Average]
  (min, avg, max) = (2.977, 3.072, 3.119), stdev = 0.082
  CI (99.9%): [1.582, 4.562] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.893 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.005 ms/op
Iteration   2: 2.942 ±(99.9%) 0.002 ms/op
Iteration   3: 2.961 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.986 ±(99.9%) 1.108 ms/op [Average]
  (min, avg, max) = (2.942, 2.986, 3.055), stdev = 0.061
  CI (99.9%): [1.879, 4.094] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.817 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.002 ms/op
Iteration   1: 3.081 ±(99.9%) 0.001 ms/op
Iteration   2: 3.041 ±(99.9%) 0.002 ms/op
Iteration   3: 2.957 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.026 ±(99.9%) 1.155 ms/op [Average]
  (min, avg, max) = (2.957, 3.026, 3.081), stdev = 0.063
  CI (99.9%): [1.871, 4.181] (assumes normal distribution)


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
# Warmup Iteration   1: 4.509 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.008 ms/op
Iteration   1: 3.879 ±(99.9%) 0.023 ms/op
Iteration   2: 3.953 ±(99.9%) 0.033 ms/op
Iteration   3: 3.850 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.894 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (3.850, 3.894, 3.953), stdev = 0.053
  CI (99.9%): [2.932, 4.856] (assumes normal distribution)


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 3.054 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.525 ms/op
                 createUser·p0.9999: 12.976 ms/op
                 createUser·p1.00:   13.271 ms/op

Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.974 ms/op
                 createUser·p0.9999: 19.246 ms/op
                 createUser·p1.00:   19.694 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.230 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.602 ms/op
                 createUser·p0.9999: 24.501 ms/op
                 createUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309577
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25773 
    [ 2.500,  5.000) = 282866 
    [ 5.000,  7.500) = 611 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.230 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.965 ms/op
     p(99.9900) =     22.579 ms/op
     p(99.9990) =     24.769 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.749 ms/op
                 existUser·p0.9999: 12.048 ms/op
                 existUser·p1.00:   12.239 ms/op

Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.715 ms/op
                 existUser·p0.9999: 20.097 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.452 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  11.262 ms/op
                 existUser·p0.9999: 15.848 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323387
  mean =      2.970 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44936 
    [ 2.500,  5.000) = 277524 
    [ 5.000,  7.500) = 611 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.452 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      7.271 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  9.339 ms/op
                 getUser·p0.9999: 12.188 ms/op
                 getUser·p1.00:   12.452 ms/op

Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.445 ms/op
                 getUser·p0.9999: 15.837 ms/op
                 getUser·p1.00:   16.286 ms/op

Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.700 ms/op
                 getUser·p0.9999: 25.057 ms/op
                 getUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311869
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26530 
    [ 2.500,  5.000) = 284544 
    [ 5.000,  7.500) = 507 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.235 ms/op
     p(99.9900) =     23.214 ms/op
     p(99.9990) =     25.326 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.010 ms/op
Iteration   1: 3.834 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  12.869 ms/op
                 listUser·p0.9999: 17.421 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   2: 4.045 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.369 ms/op
                 listUser·p0.9999: 24.340 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   3: 3.885 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.801 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.281 ms/op
                 listUser·p0.9999: 25.568 ms/op
                 listUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245010
  mean =      3.919 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7033 
    [ 2.500,  5.000) = 210250 
    [ 5.000,  7.500) = 26796 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.667 ms/op
     p(99.9000) =     14.532 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     25.956 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.470 ± 4.548  ops/ms
ClientGrpc.existUser                       thrpt       3  10.997 ± 1.906  ops/ms
ClientGrpc.getUser                         thrpt       3  10.602 ± 2.457  ops/ms
ClientGrpc.listUser                        thrpt       3   8.245 ± 1.119  ops/ms
ClientGrpc.createUser                       avgt       3   3.072 ± 1.490   ms/op
ClientGrpc.existUser                        avgt       3   2.986 ± 1.108   ms/op
ClientGrpc.getUser                          avgt       3   3.026 ± 1.155   ms/op
ClientGrpc.listUser                         avgt       3   3.894 ± 0.962   ms/op
ClientGrpc.createUser                     sample  309577   3.100 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.230           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.965           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.579           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.805           ms/op
ClientGrpc.existUser                      sample  323387   2.970 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.452           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.271           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.579           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.414           ms/op
ClientGrpc.getUser                        sample  311869   3.078 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.764           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.235           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.214           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.428           ms/op
ClientGrpc.listUser                       sample  245010   3.919 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.801           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.667           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.532           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.543           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.083           ms/op
