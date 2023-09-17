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
# Warmup Iteration   1: 4.781 ops/ms
# Warmup Iteration   2: 9.032 ops/ms
# Warmup Iteration   3: 9.620 ops/ms
Iteration   1: 10.256 ops/ms
Iteration   2: 10.385 ops/ms
Iteration   3: 10.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.289 ±(99.9%) 1.550 ops/ms [Average]
  (min, avg, max) = (10.225, 10.289, 10.385), stdev = 0.085
  CI (99.9%): [8.738, 11.839] (assumes normal distribution)


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
# Warmup Iteration   1: 8.611 ops/ms
# Warmup Iteration   2: 10.403 ops/ms
# Warmup Iteration   3: 10.840 ops/ms
Iteration   1: 10.808 ops/ms
Iteration   2: 10.816 ops/ms
Iteration   3: 10.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.814 ±(99.9%) 0.106 ops/ms [Average]
  (min, avg, max) = (10.808, 10.814, 10.819), stdev = 0.006
  CI (99.9%): [10.709, 10.920] (assumes normal distribution)


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
# Warmup Iteration   1: 7.300 ops/ms
# Warmup Iteration   2: 10.056 ops/ms
# Warmup Iteration   3: 10.261 ops/ms
Iteration   1: 10.536 ops/ms
Iteration   2: 10.129 ops/ms
Iteration   3: 10.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.298 ±(99.9%) 3.864 ops/ms [Average]
  (min, avg, max) = (10.129, 10.298, 10.536), stdev = 0.212
  CI (99.9%): [6.434, 14.162] (assumes normal distribution)


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
# Warmup Iteration   1: 5.954 ops/ms
# Warmup Iteration   2: 8.303 ops/ms
# Warmup Iteration   3: 8.244 ops/ms
Iteration   1: 8.267 ops/ms
Iteration   2: 8.373 ops/ms
Iteration   3: 8.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.331 ±(99.9%) 1.023 ops/ms [Average]
  (min, avg, max) = (8.267, 8.331, 8.373), stdev = 0.056
  CI (99.9%): [7.308, 9.354] (assumes normal distribution)


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.003 ms/op
Iteration   1: 3.036 ±(99.9%) 0.005 ms/op
Iteration   2: 3.049 ±(99.9%) 0.002 ms/op
Iteration   3: 3.090 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.058 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (3.036, 3.058, 3.090), stdev = 0.028
  CI (99.9%): [2.542, 3.574] (assumes normal distribution)


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.004 ms/op
Iteration   1: 3.007 ±(99.9%) 0.003 ms/op
Iteration   2: 2.959 ±(99.9%) 0.001 ms/op
Iteration   3: 2.969 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.979 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (2.959, 2.979, 3.007), stdev = 0.025
  CI (99.9%): [2.515, 3.442] (assumes normal distribution)


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.002 ms/op
Iteration   1: 3.056 ±(99.9%) 0.002 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.058 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.059 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (3.056, 3.059, 3.064), stdev = 0.004
  CI (99.9%): [2.987, 3.131] (assumes normal distribution)


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
# Warmup Iteration   1: 5.188 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.015 ms/op
Iteration   1: 4.173 ±(99.9%) 0.013 ms/op
Iteration   2: 4.072 ±(99.9%) 0.019 ms/op
Iteration   3: 4.015 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.087 ±(99.9%) 1.459 ms/op [Average]
  (min, avg, max) = (4.015, 4.087, 4.173), stdev = 0.080
  CI (99.9%): [2.628, 5.546] (assumes normal distribution)


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
# Warmup Iteration   1: 4.421 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.548 ms/op
                 createUser·p0.999:  7.183 ms/op
                 createUser·p0.9999: 11.531 ms/op
                 createUser·p1.00:   11.960 ms/op

Iteration   2: 3.071 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.392 ms/op
                 createUser·p0.999:  7.307 ms/op
                 createUser·p0.9999: 13.451 ms/op
                 createUser·p1.00:   15.581 ms/op

Iteration   3: 3.128 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.222 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  15.393 ms/op
                 createUser·p0.9999: 18.998 ms/op
                 createUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310497
  mean =      3.090 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1717 
    [ 1.250,  2.500) = 13905 
    [ 2.500,  3.750) = 274249 
    [ 3.750,  5.000) = 18312 
    [ 5.000,  6.250) = 1486 
    [ 6.250,  7.500) = 390 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.222 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =     10.519 ms/op
     p(99.9900) =     17.333 ms/op
     p(99.9990) =     19.330 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.105 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 2.978 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  8.241 ms/op
                 existUser·p0.9999: 15.987 ms/op
                 existUser·p1.00:   16.433 ms/op

Iteration   2: 2.904 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  8.798 ms/op
                 existUser·p0.9999: 13.336 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  11.518 ms/op
                 existUser·p0.9999: 15.525 ms/op
                 existUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325485
  mean =      2.947 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3516 
    [ 1.250,  2.500) = 34357 
    [ 2.500,  3.750) = 271751 
    [ 3.750,  5.000) = 13382 
    [ 5.000,  6.250) = 1254 
    [ 6.250,  7.500) = 519 
    [ 7.500,  8.750) = 351 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 69 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      8.979 ms/op
     p(99.9900) =     15.556 ms/op
     p(99.9990) =     16.322 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 4.022 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
Iteration   1: 3.128 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  11.192 ms/op
                 getUser·p0.9999: 23.058 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.634 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 16.805 ms/op
                 getUser·p1.00:   17.760 ms/op

Iteration   3: 3.170 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.677 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.149 ms/op
                 getUser·p0.9999: 19.005 ms/op
                 getUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303934
  mean =      3.156 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11788 
    [ 2.500,  5.000) = 289787 
    [ 5.000,  7.500) = 1730 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     20.959 ms/op
     p(99.9990) =     24.179 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 5.055 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.009 ms/op
Iteration   1: 3.883 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  12.042 ms/op
                 listUser·p0.9999: 14.774 ms/op
                 listUser·p1.00:   15.761 ms/op

Iteration   2: 3.838 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.803 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  12.594 ms/op
                 listUser·p0.9999: 14.882 ms/op
                 listUser·p1.00:   16.105 ms/op

Iteration   3: 3.820 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  15.176 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249552
  mean =      3.847 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 5030 
    [ 2.500,  3.750) = 120032 
    [ 3.750,  5.000) = 108995 
    [ 5.000,  6.250) = 11423 
    [ 6.250,  7.500) = 3209 
    [ 7.500,  8.750) = 300 
    [ 8.750, 10.000) = 148 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 66 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     16.581 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.289 ± 1.550  ops/ms
ClientGrpc.existUser                       thrpt       3  10.814 ± 0.106  ops/ms
ClientGrpc.getUser                         thrpt       3  10.298 ± 3.864  ops/ms
ClientGrpc.listUser                        thrpt       3   8.331 ± 1.023  ops/ms
ClientGrpc.createUser                       avgt       3   3.058 ± 0.516   ms/op
ClientGrpc.existUser                        avgt       3   2.979 ± 0.464   ms/op
ClientGrpc.getUser                          avgt       3   3.059 ± 0.072   ms/op
ClientGrpc.listUser                         avgt       3   4.087 ± 1.459   ms/op
ClientGrpc.createUser                     sample  310497   3.090 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.222           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.519           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.333           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.464           ms/op
ClientGrpc.existUser                      sample  325485   2.947 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.510           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.727           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.979           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.556           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.433           ms/op
ClientGrpc.getUser                        sample  303934   3.156 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.634           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.748           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.959           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.379           ms/op
ClientGrpc.listUser                       sample  249552   3.847 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.803           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.424           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.472           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.485           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.581           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          17.891           ms/op
