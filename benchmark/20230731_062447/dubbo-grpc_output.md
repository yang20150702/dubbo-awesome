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
# Warmup Iteration   1: 3.970 ops/ms
# Warmup Iteration   2: 8.911 ops/ms
# Warmup Iteration   3: 10.017 ops/ms
Iteration   1: 10.477 ops/ms
Iteration   2: 10.348 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.460 ±(99.9%) 1.905 ops/ms [Average]
  (min, avg, max) = (10.348, 10.460, 10.554), stdev = 0.104
  CI (99.9%): [8.554, 12.365] (assumes normal distribution)


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
# Warmup Iteration   1: 7.303 ops/ms
# Warmup Iteration   2: 10.570 ops/ms
# Warmup Iteration   3: 11.034 ops/ms
Iteration   1: 11.059 ops/ms
Iteration   2: 11.253 ops/ms
Iteration   3: 11.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.160 ±(99.9%) 1.774 ops/ms [Average]
  (min, avg, max) = (11.059, 11.160, 11.253), stdev = 0.097
  CI (99.9%): [9.386, 12.934] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.033 ops/ms
# Warmup Iteration   2: 9.892 ops/ms
# Warmup Iteration   3: 10.399 ops/ms
Iteration   1: 10.352 ops/ms
Iteration   2: 10.496 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.430 ±(99.9%) 1.325 ops/ms [Average]
  (min, avg, max) = (10.352, 10.430, 10.496), stdev = 0.073
  CI (99.9%): [9.105, 11.754] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.070 ops/ms
# Warmup Iteration   2: 7.591 ops/ms
# Warmup Iteration   3: 7.698 ops/ms
Iteration   1: 7.765 ops/ms
Iteration   2: 7.971 ops/ms
Iteration   3: 7.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.845 ±(99.9%) 2.016 ops/ms [Average]
  (min, avg, max) = (7.765, 7.845, 7.971), stdev = 0.110
  CI (99.9%): [5.829, 9.861] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.091 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.004 ms/op
Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
Iteration   3: 3.023 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.032 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (3.023, 3.032, 3.046), stdev = 0.012
  CI (99.9%): [2.810, 3.253] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.175 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.002 ms/op
Iteration   1: 2.954 ±(99.9%) 0.003 ms/op
Iteration   2: 2.895 ±(99.9%) 0.003 ms/op
Iteration   3: 2.873 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.908 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (2.873, 2.908, 2.954), stdev = 0.042
  CI (99.9%): [2.140, 3.675] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.301 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.003 ms/op
Iteration   1: 2.980 ±(99.9%) 0.003 ms/op
Iteration   2: 3.021 ±(99.9%) 0.003 ms/op
Iteration   3: 3.017 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.006 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.980, 3.006, 3.021), stdev = 0.023
  CI (99.9%): [2.594, 3.418] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.857 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.017 ms/op
Iteration   1: 4.002 ±(99.9%) 0.019 ms/op
Iteration   2: 4.066 ±(99.9%) 0.024 ms/op
Iteration   3: 4.097 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.055 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (4.002, 4.055, 4.097), stdev = 0.048
  CI (99.9%): [3.171, 4.939] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.604 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
Iteration   1: 3.093 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  8.232 ms/op
                 createUser·p0.9999: 16.187 ms/op
                 createUser·p1.00:   16.581 ms/op

Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  10.481 ms/op
                 createUser·p0.9999: 17.656 ms/op
                 createUser·p1.00:   18.940 ms/op

Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.631 ms/op
                 createUser·p0.999:  12.093 ms/op
                 createUser·p0.9999: 21.031 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310506
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21352 
    [ 2.500,  5.000) = 286751 
    [ 5.000,  7.500) = 1700 
    [ 7.500, 10.000) = 394 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      9.878 ms/op
     p(99.9900) =     19.757 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.006 ms/op
Iteration   1: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  7.956 ms/op
                 existUser·p0.9999: 14.957 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   2: 2.883 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  7.759 ms/op
                 existUser·p0.9999: 13.106 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.823 ms/op
                 existUser·p0.9999: 17.662 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330401
  mean =      2.904 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2075 
    [ 1.250,  2.500) = 33212 
    [ 2.500,  3.750) = 286062 
    [ 3.750,  5.000) = 6999 
    [ 5.000,  6.250) = 1074 
    [ 6.250,  7.500) = 567 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     16.497 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.382 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.405 ms/op
                 getUser·p0.9999: 13.333 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  9.127 ms/op
                 getUser·p0.9999: 14.513 ms/op
                 getUser·p1.00:   15.909 ms/op

Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  8.798 ms/op
                 getUser·p0.9999: 17.058 ms/op
                 getUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314251
  mean =      3.057 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 640 
    [ 1.250,  2.500) = 16824 
    [ 2.500,  3.750) = 278420 
    [ 3.750,  5.000) = 16060 
    [ 5.000,  6.250) = 1199 
    [ 6.250,  7.500) = 436 
    [ 7.500,  8.750) = 333 
    [ 8.750, 10.000) = 169 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     16.698 ms/op
     p(99.9990) =     17.227 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.859 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.013 ms/op
Iteration   1: 4.097 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.087 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  13.974 ms/op
                 listUser·p0.9999: 16.593 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   2: 4.086 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  17.100 ms/op
                 listUser·p0.9999: 25.630 ms/op
                 listUser·p1.00:   25.887 ms/op

Iteration   3: 3.919 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.742 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.390 ms/op
                 listUser·p0.9999: 20.251 ms/op
                 listUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237988
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3245 
    [ 2.500,  5.000) = 208961 
    [ 5.000,  7.500) = 23794 
    [ 7.500, 10.000) = 1528 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     14.779 ms/op
     p(99.9900) =     25.140 ms/op
     p(99.9990) =     25.809 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.460 ± 1.905  ops/ms
ClientGrpc.existUser                       thrpt       3  11.160 ± 1.774  ops/ms
ClientGrpc.getUser                         thrpt       3  10.430 ± 1.325  ops/ms
ClientGrpc.listUser                        thrpt       3   7.845 ± 2.016  ops/ms
ClientGrpc.createUser                       avgt       3   3.032 ± 0.221   ms/op
ClientGrpc.existUser                        avgt       3   2.908 ± 0.768   ms/op
ClientGrpc.getUser                          avgt       3   3.006 ± 0.412   ms/op
ClientGrpc.listUser                         avgt       3   4.055 ± 0.884   ms/op
ClientGrpc.createUser                     sample  310506   3.089 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.601           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.878           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.757           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.053           ms/op
ClientGrpc.existUser                      sample  330401   2.904 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.567           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.604           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.815           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.497           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  314251   3.057 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.775           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.831           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.698           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.367           ms/op
ClientGrpc.listUser                       sample  237988   4.032 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.742           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.779           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.140           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.887           ms/op
