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
# Warmup Iteration   1: 2.495 ops/ms
# Warmup Iteration   2: 5.216 ops/ms
# Warmup Iteration   3: 6.844 ops/ms
Iteration   1: 6.967 ops/ms
Iteration   2: 7.130 ops/ms
Iteration   3: 7.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.061 ±(99.9%) 1.530 ops/ms [Average]
  (min, avg, max) = (6.967, 7.061, 7.130), stdev = 0.084
  CI (99.9%): [5.531, 8.591] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.026 ops/ms
# Warmup Iteration   2: 7.256 ops/ms
# Warmup Iteration   3: 7.514 ops/ms
Iteration   1: 7.372 ops/ms
Iteration   2: 7.600 ops/ms
Iteration   3: 7.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.470 ±(99.9%) 2.133 ops/ms [Average]
  (min, avg, max) = (7.372, 7.470, 7.600), stdev = 0.117
  CI (99.9%): [5.337, 9.603] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.809 ops/ms
# Warmup Iteration   2: 6.793 ops/ms
# Warmup Iteration   3: 7.191 ops/ms
Iteration   1: 6.833 ops/ms
Iteration   2: 7.194 ops/ms
Iteration   3: 7.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.154 ±(99.9%) 5.529 ops/ms [Average]
  (min, avg, max) = (6.833, 7.154, 7.435), stdev = 0.303
  CI (99.9%): [1.625, 12.683] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.919 ops/ms
# Warmup Iteration   2: 5.128 ops/ms
# Warmup Iteration   3: 5.475 ops/ms
Iteration   1: 5.662 ops/ms
Iteration   2: 5.590 ops/ms
Iteration   3: 5.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.648 ±(99.9%) 0.950 ops/ms [Average]
  (min, avg, max) = (5.590, 5.648, 5.692), stdev = 0.052
  CI (99.9%): [4.698, 6.598] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.026 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.847 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.591 ±(99.9%) 0.009 ms/op
Iteration   1: 4.410 ±(99.9%) 0.003 ms/op
Iteration   2: 4.301 ±(99.9%) 0.002 ms/op
Iteration   3: 4.560 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.424 ±(99.9%) 2.374 ms/op [Average]
  (min, avg, max) = (4.301, 4.424, 4.560), stdev = 0.130
  CI (99.9%): [2.050, 6.798] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.990 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.004 ms/op
Iteration   1: 4.133 ±(99.9%) 0.003 ms/op
Iteration   2: 4.248 ±(99.9%) 0.004 ms/op
Iteration   3: 3.884 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.089 ±(99.9%) 3.392 ms/op [Average]
  (min, avg, max) = (3.884, 4.089, 4.248), stdev = 0.186
  CI (99.9%): [0.696, 7.481] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.330 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.637 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.395 ±(99.9%) 0.013 ms/op
Iteration   1: 4.293 ±(99.9%) 0.003 ms/op
Iteration   2: 4.197 ±(99.9%) 0.003 ms/op
Iteration   3: 4.207 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.233 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (4.197, 4.233, 4.293), stdev = 0.053
  CI (99.9%): [3.267, 5.198] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.437 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 6.013 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.832 ±(99.9%) 0.027 ms/op
Iteration   1: 5.705 ±(99.9%) 0.040 ms/op
Iteration   2: 5.690 ±(99.9%) 0.049 ms/op
Iteration   3: 5.830 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.741 ±(99.9%) 1.401 ms/op [Average]
  (min, avg, max) = (5.690, 5.741, 5.830), stdev = 0.077
  CI (99.9%): [4.341, 7.142] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.361 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.311 ±(99.9%) 0.014 ms/op
Iteration   1: 4.056 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   4.997 ms/op
                 createUser·p0.95:   5.489 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  14.701 ms/op
                 createUser·p0.9999: 17.243 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   2: 4.160 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   4.059 ms/op
                 createUser·p0.90:   5.497 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   7.463 ms/op
                 createUser·p0.999:  11.637 ms/op
                 createUser·p0.9999: 15.254 ms/op
                 createUser·p1.00:   16.007 ms/op

Iteration   3: 4.318 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   4.190 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   7.954 ms/op
                 createUser·p0.999:  12.747 ms/op
                 createUser·p0.9999: 32.335 ms/op
                 createUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 229720
  mean =      4.175 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5975 
    [ 2.500,  5.000) = 187301 
    [ 5.000,  7.500) = 34264 
    [ 7.500, 10.000) = 1747 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      4.055 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     12.826 ms/op
     p(99.9900) =     26.805 ms/op
     p(99.9990) =     32.781 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.936 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.014 ms/op
Iteration   1: 4.270 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   4.166 ms/op
                 existUser·p0.90:   5.472 ms/op
                 existUser·p0.95:   5.972 ms/op
                 existUser·p0.99:   7.520 ms/op
                 existUser·p0.999:  11.903 ms/op
                 existUser·p0.9999: 16.188 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   2: 4.287 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   4.178 ms/op
                 existUser·p0.90:   5.538 ms/op
                 existUser·p0.95:   6.054 ms/op
                 existUser·p0.99:   7.698 ms/op
                 existUser·p0.999:  13.535 ms/op
                 existUser·p0.9999: 22.053 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   3: 4.106 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   5.857 ms/op
                 existUser·p0.99:   7.537 ms/op
                 existUser·p0.999:  12.946 ms/op
                 existUser·p0.9999: 23.003 ms/op
                 existUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 227487
  mean =      4.219 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7476 
    [ 2.500,  5.000) = 177781 
    [ 5.000,  7.500) = 39802 
    [ 7.500, 10.000) = 1850 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     23.670 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.131 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.708 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.365 ±(99.9%) 0.014 ms/op
Iteration   1: 4.463 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   4.350 ms/op
                 getUser·p0.90:   5.874 ms/op
                 getUser·p0.95:   6.365 ms/op
                 getUser·p0.99:   7.750 ms/op
                 getUser·p0.999:  11.262 ms/op
                 getUser·p0.9999: 17.951 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   2: 4.352 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.177 ms/op
                 getUser·p0.99:   7.971 ms/op
                 getUser·p0.999:  12.999 ms/op
                 getUser·p0.9999: 18.273 ms/op
                 getUser·p1.00:   18.579 ms/op

Iteration   3: 4.373 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.702 ms/op
                 getUser·p0.95:   6.218 ms/op
                 getUser·p0.99:   7.807 ms/op
                 getUser·p0.999:  12.333 ms/op
                 getUser·p0.9999: 19.390 ms/op
                 getUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218486
  mean =      4.395 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5422 
    [ 2.500,  5.000) = 157920 
    [ 5.000,  7.500) = 52265 
    [ 7.500, 10.000) = 2380 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =      7.856 ms/op
     p(99.9000) =     12.509 ms/op
     p(99.9900) =     18.552 ms/op
     p(99.9990) =     20.780 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 8.076 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.126 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.957 ±(99.9%) 0.024 ms/op
Iteration   1: 5.672 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.520 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.666 ms/op
                 listUser·p0.999:  17.550 ms/op
                 listUser·p0.9999: 22.654 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   2: 5.521 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.808 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.348 ms/op
                 listUser·p0.95:   8.217 ms/op
                 listUser·p0.99:   10.484 ms/op
                 listUser·p0.999:  17.894 ms/op
                 listUser·p0.9999: 27.126 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   3: 5.446 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   7.389 ms/op
                 listUser·p0.95:   8.315 ms/op
                 listUser·p0.99:   10.926 ms/op
                 listUser·p0.999:  20.930 ms/op
                 listUser·p0.9999: 31.278 ms/op
                 listUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173034
  mean =      5.545 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 246 
    [ 2.500,  5.000) = 70472 
    [ 5.000,  7.500) = 86075 
    [ 7.500, 10.000) = 13634 
    [10.000, 12.500) = 1919 
    [12.500, 15.000) = 327 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      5.251 ms/op
     p(90.0000) =      7.422 ms/op
     p(95.0000) =      8.331 ms/op
     p(99.0000) =     10.666 ms/op
     p(99.9000) =     18.185 ms/op
     p(99.9900) =     28.907 ms/op
     p(99.9990) =     31.689 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.061 ± 1.530  ops/ms
ClientGrpc.existUser                       thrpt       3   7.470 ± 2.133  ops/ms
ClientGrpc.getUser                         thrpt       3   7.154 ± 5.529  ops/ms
ClientGrpc.listUser                        thrpt       3   5.648 ± 0.950  ops/ms
ClientGrpc.createUser                       avgt       3   4.424 ± 2.374   ms/op
ClientGrpc.existUser                        avgt       3   4.089 ± 3.392   ms/op
ClientGrpc.getUser                          avgt       3   4.233 ± 0.966   ms/op
ClientGrpc.listUser                         avgt       3   5.741 ± 1.401   ms/op
ClientGrpc.createUser                     sample  229720   4.175 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.801           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.055           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.349           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.865           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.422           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.826           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.805           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.932           ms/op
ClientGrpc.existUser                      sample  227487   4.219 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.892           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.116           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.448           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.964           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.586           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.091           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.987           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.347           ms/op
ClientGrpc.getUser                        sample  218486   4.395 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.765           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.743           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.259           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.856           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.509           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.552           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.873           ms/op
ClientGrpc.listUser                       sample  173034   5.545 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.020           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.422           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.331           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.666           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.185           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.907           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.785           ms/op
