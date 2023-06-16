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
# Warmup Iteration   1: 2.441 ops/ms
# Warmup Iteration   2: 5.559 ops/ms
# Warmup Iteration   3: 7.291 ops/ms
Iteration   1: 7.808 ops/ms
Iteration   2: 8.141 ops/ms
Iteration   3: 7.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.943 ±(99.9%) 3.197 ops/ms [Average]
  (min, avg, max) = (7.808, 7.943, 8.141), stdev = 0.175
  CI (99.9%): [4.746, 11.140] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.484 ops/ms
# Warmup Iteration   2: 7.766 ops/ms
# Warmup Iteration   3: 7.864 ops/ms
Iteration   1: 7.504 ops/ms
Iteration   2: 7.955 ops/ms
Iteration   3: 8.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.863 ±(99.9%) 5.887 ops/ms [Average]
  (min, avg, max) = (7.504, 7.863, 8.129), stdev = 0.323
  CI (99.9%): [1.976, 13.750] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.532 ops/ms
# Warmup Iteration   2: 7.237 ops/ms
# Warmup Iteration   3: 7.527 ops/ms
Iteration   1: 7.524 ops/ms
Iteration   2: 7.310 ops/ms
Iteration   3: 7.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.397 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (7.310, 7.397, 7.524), stdev = 0.112
  CI (99.9%): [5.348, 9.446] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.676 ops/ms
# Warmup Iteration   2: 5.026 ops/ms
# Warmup Iteration   3: 5.633 ops/ms
Iteration   1: 5.495 ops/ms
Iteration   2: 5.412 ops/ms
Iteration   3: 5.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.617 ±(99.9%) 5.233 ops/ms [Average]
  (min, avg, max) = (5.412, 5.617, 5.945), stdev = 0.287
  CI (99.9%): [0.385, 10.850] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.867 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.257 ±(99.9%) 0.005 ms/op
Iteration   1: 4.305 ±(99.9%) 0.003 ms/op
Iteration   2: 4.250 ±(99.9%) 0.003 ms/op
Iteration   3: 4.290 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.282 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (4.250, 4.282, 4.305), stdev = 0.029
  CI (99.9%): [3.761, 4.802] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.575 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.011 ms/op
Iteration   1: 4.016 ±(99.9%) 0.003 ms/op
Iteration   2: 3.978 ±(99.9%) 0.003 ms/op
Iteration   3: 3.923 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.972 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (3.923, 3.972, 4.016), stdev = 0.047
  CI (99.9%): [3.116, 4.829] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.447 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.534 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.243 ±(99.9%) 0.003 ms/op
Iteration   1: 4.184 ±(99.9%) 0.003 ms/op
Iteration   2: 4.132 ±(99.9%) 0.004 ms/op
Iteration   3: 4.100 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.139 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (4.100, 4.139, 4.184), stdev = 0.043
  CI (99.9%): [3.358, 4.920] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.177 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.988 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.484 ±(99.9%) 0.033 ms/op
Iteration   1: 5.497 ±(99.9%) 0.029 ms/op
Iteration   2: 5.500 ±(99.9%) 0.010 ms/op
Iteration   3: 5.481 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.492 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (5.481, 5.492, 5.500), stdev = 0.010
  CI (99.9%): [5.312, 5.673] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.547 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.661 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.289 ±(99.9%) 0.013 ms/op
Iteration   1: 4.160 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   4.059 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   7.119 ms/op
                 createUser·p0.999:  12.139 ms/op
                 createUser·p0.9999: 16.579 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   2: 4.002 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   6.626 ms/op
                 createUser·p0.999:  11.409 ms/op
                 createUser·p0.9999: 25.494 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   3: 4.002 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.308 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  11.472 ms/op
                 createUser·p0.9999: 20.546 ms/op
                 createUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 236840
  mean =      4.054 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5670 
    [ 2.500,  5.000) = 208596 
    [ 5.000,  7.500) = 20988 
    [ 7.500, 10.000) = 1158 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     11.665 ms/op
     p(99.9900) =     22.313 ms/op
     p(99.9990) =     25.764 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.062 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.013 ms/op
Iteration   1: 4.094 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   4.006 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   6.849 ms/op
                 existUser·p0.999:  12.169 ms/op
                 existUser·p0.9999: 25.250 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   2: 3.937 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  14.087 ms/op
                 existUser·p0.9999: 18.739 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   3: 4.023 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   3.928 ms/op
                 existUser·p0.90:   4.882 ms/op
                 existUser·p0.95:   5.292 ms/op
                 existUser·p0.99:   6.726 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 20.776 ms/op
                 existUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238910
  mean =      4.017 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4082 
    [ 2.500,  5.000) = 216077 
    [ 5.000,  7.500) = 17465 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     11.831 ms/op
     p(99.9900) =     24.288 ms/op
     p(99.9990) =     25.665 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.582 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.011 ms/op
Iteration   1: 4.122 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   4.022 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  9.765 ms/op
                 getUser·p0.9999: 21.201 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   2: 4.208 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   4.100 ms/op
                 getUser·p0.90:   5.300 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  13.173 ms/op
                 getUser·p0.9999: 23.265 ms/op
                 getUser·p1.00:   24.674 ms/op

Iteration   3: 4.228 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   4.125 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  10.655 ms/op
                 getUser·p0.9999: 24.881 ms/op
                 getUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 229279
  mean =      4.185 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4366 
    [ 2.500,  5.000) = 193002 
    [ 5.000,  7.500) = 30263 
    [ 7.500, 10.000) = 1272 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     10.830 ms/op
     p(99.9900) =     24.316 ms/op
     p(99.9990) =     31.353 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.712 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 6.326 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.498 ±(99.9%) 0.019 ms/op
Iteration   1: 5.345 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   6.873 ms/op
                 listUser·p0.95:   7.881 ms/op
                 listUser·p0.99:   10.060 ms/op
                 listUser·p0.999:  16.340 ms/op
                 listUser·p0.9999: 21.136 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 5.467 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.864 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   7.029 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 22.816 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 5.396 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   6.676 ms/op
                 listUser·p0.95:   7.791 ms/op
                 listUser·p0.99:   10.224 ms/op
                 listUser·p0.999:  18.800 ms/op
                 listUser·p0.9999: 21.503 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 177659
  mean =      5.402 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 73784 
    [ 5.000,  7.500) = 91909 
    [ 7.500, 10.000) = 9941 
    [10.000, 12.500) = 1432 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.865 ms/op
     p(95.0000) =      7.922 ms/op
     p(99.0000) =     10.142 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     21.602 ms/op
     p(99.9990) =     23.280 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.943 ± 3.197  ops/ms
ClientGrpc.existUser                       thrpt       3   7.863 ± 5.887  ops/ms
ClientGrpc.getUser                         thrpt       3   7.397 ± 2.049  ops/ms
ClientGrpc.listUser                        thrpt       3   5.617 ± 5.233  ops/ms
ClientGrpc.createUser                       avgt       3   4.282 ± 0.521   ms/op
ClientGrpc.existUser                        avgt       3   3.972 ± 0.856   ms/op
ClientGrpc.getUser                          avgt       3   4.139 ± 0.781   ms/op
ClientGrpc.listUser                         avgt       3   5.492 ± 0.180   ms/op
ClientGrpc.createUser                     sample  236840   4.054 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.611           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.973           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.382           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.881           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.665           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.313           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.788           ms/op
ClientGrpc.existUser                      sample  238910   4.017 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.844           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.928           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.866           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.259           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.595           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.831           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.288           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.756           ms/op
ClientGrpc.getUser                        sample  229279   4.185 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.002           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.620           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.947           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.830           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.316           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.850           ms/op
ClientGrpc.listUser                       sample  177659   5.402 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.389           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.922           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.142           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.727           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.602           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.331           ms/op
